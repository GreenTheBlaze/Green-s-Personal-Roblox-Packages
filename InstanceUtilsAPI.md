Throughout this documentation here, we're going to be using an example Roblox Studio object hierarchy:
```
game      # Class: DataModel
├─ Workspace
│  ├─ Camera      # Class: Camera
│  ├─ Camera2      # Class: Camera
│  │  ├─ FakeThing1      # Class: Camera
│  │  ├─ FakeThing1      # Class: Part
│  │  ├─ FakeThing1      # Class: Part
│  │  ├─ SomethingElse      # Class: Camera
│  │  │  └─ Bar      # Class: TextLabel
│  │  ├─ ASimpleTruss      # Class: TrussPart
│  │  └─ Foo      # Class: Camera
│  ├─ GreenTheBlaze      # Class: Model
│  ├─ GreenTheBlaze      # Class: Part
│  ├─ FakeCamera      # Class: BasePart
│  ├─ Part      # Class: Part
│  ├─ Part      # Class: Part
│  ├─ Part1      # Class: Part
│  ├─ Part2      # Class: Part
│  ├─ Part2      # Class: Part
│  ├─ Part2      # Class: Union
│  ├─ Part2      # Class: MeshPart
│  └─ Terrain     # Class: Terrain
└─ Lighting
   ├─ ANormalLight      # Class: PointLight
   ├─ Sky      # Class: Sky
   └─ ANormalLightLol      # Class: MeshPart
```
*Don't mind the weird names LOL.*
**Also, note that the way in which the objects are ordered here is not necessarily compliant with the order that Roblox puts instances in - any outputs in examples are to be in the order from which they are presented in the above. MAKE SURE TO READ THIS OR YOU MAY BE CONFUSED!**

## Miscellanious Functions

### createInstance
Creates a new [Instance](https://create.roblox.com/docs/reference/engine/classes/Instance) of type `className`, similar to the default constructor [Instance.new](https://create.roblox.com/docs/reference/engine/datatypes/Instance#new) which is already provided by Roblox.

**Syntax:** `InstanceUtils:createInstance(className: Instance, propertiesTable: {any}) → Instance`

**Parameters:**
* `className`: [string](https://create.roblox.com/docs/luau/strings) - Class name of the new object to create.
* `propertiesTable`: [Dictionary](https://create.roblox.com/docs/luau/tables#dictionaries) - The table in which the properties to configure for the new object should be listed.

**Returns:**
* [`Instance`](https://create.roblox.com/docs/reference/engine/classes/Instance) - The object created.

**Code Example:**
```lua
local newCoolBlock = InstanceUtils:createInstance("Part", {
   Name = "NewCoolBlock",
   BrickColor = BrickColor.new(1, 0, 0),
   Parent = workspace.Camera
})

print(typeof(newCoolBlock)) --> Instance
print(newCoolBlock.Parent.Name) --> Camera
```

----

### createInstances
Creates multiple instances based on the provided configuration array. Extended version of [createInstance](#createInstance).

**Syntax:** `InstanceUtils:createInstances(instancesConfig: {{any}}) → ...Instance`

**Parameters:**
* `instancesConfig: []`: The configuration array for each individual instance being created.

**Returns:**
* [`Tuple`](https://create.roblox.com/docs/luau/tuples): The created instances.

**Code Example:**
```lua
local fooBar, aRedMeshPart = InstanceUtils:createInstances({
   {
      Name = "FooBar",
      ClassName = "Part",
      BrickColor = BrickColor.new(1, 0, 0),
      Parent = workspace.Camera
   },
   {
      Name = "ARedMeshPart",
      ClassName = "MeshPart",
      Parent = workspace
   }
})

print(typeof(fooBar)) --> Instance
print(typeof(aRedMeshPart)) --> FooBar

print(fooBar.Name) --> Camera
```

----

### cloneAndReplaceProperties
Creates a full copy of the provided `cloneInstance` including all of its descendants, ignoring all instances that are not [Archivable](https://create.roblox.com/docs/reference/engine/classes/Instance#Archivable).

**Syntax:** `InstanceUtils:cloneAndReplaceProperties(cloneInstance: Instance, propertiesTable: {[string]: any}) → ...Instance`

**Parameters:**
* `cloneInstance`: [`Instance`](https://create.roblox.com/docs/reference/engine/classes/Instance) - The configuration array for each individual instance being created.
* `propertiesTable`: [`Array`](https://create.roblox.com/docs/luau/tables#arrays) - The configuration array for each individual instance being created.

**Returns:**
* [`Tuple`](https://create.roblox.com/docs/luau/tuples): The created instances.

**Code Example:**
```lua
local fooBar, aRedMeshPart = InstanceUtils:createInstances({
   {
      Name = "FooBar",
      ClassName = "Part",
      BrickColor = BrickColor.new(1, 0, 0),
      Parent = workspace.Camera
   },
   {
      Name = "ARedMeshPart",
      ClassName = "MeshPart",
      Parent = workspace
   }
})

print(typeof(fooBar)) --> Instance
print(typeof(aRedMeshPart)) --> FooBar

print(fooBar.Name) --> Camera
```

----

### clonesAndReplaceProperties
Creates a full copy of the provided `cloneInstance` including all of its descendants, ignoring all instances that are not [Archivable](https://create.roblox.com/docs/reference/engine/classes/Instance#Archivable).
Creates full copies Instance objects based on the provided configuration array. Extended version of [createInstance](#createInstance).

**Syntax:** `InstanceUtils:cloneAndReplaceProperties(cloneInstance: Instance) → ...Instance`

**Parameters:**
* `instancesConfig:` [`Array`](https://create.roblox.com/docs/luau/tables#arrays)`: The configuration array for each individual instance being created.

**Returns:**
* [`Tuple`](https://create.roblox.com/docs/luau/tuples): The created instances.

**Code Example:**
```lua
local fooBar, aRedMeshPart = InstanceUtils:createInstances({
   {
      Name = "FooBar",
      ClassName = "Part",
      BrickColor = BrickColor.new(1, 0, 0),
      Parent = workspace.Camera
   },
   {
      Name = "ARedMeshPart",
      ClassName = "MeshPart",
      Parent = workspace
   }
})

print(typeof(fooBar)) --> Instance
print(typeof(aRedMeshPart)) --> FooBar

print(fooBar.Name) --> Camera
```

----

## Get
This method extension focusses mainly on retrieving instances and outputting them in the form of an `Instance` array. Exceptions to this include the getting instances from path methods.

### getSiblings
Returns an array (a numerically indexed table) containing all direct siblings of the given `child`. In other words, it retrieves every `Instance` that shares the same `Parent` as the `child`.

**Syntax:** `InstanceUtils:getSiblings(child: Instance) → {Instance}`

**Parameters:**
* `child`: The instance to whom the siblings are going to be searched from.

**Returns:**
* [`Array`](https://create.roblox.com/docs/luau/tables#arrays): An array containing the `child`'s siblings.

**Code Example:**
```lua
local siblingsOfSky = InstanceUtils:getSiblings(game.Lighting.Sky) --> {game.Lighting.ANormalLight, game.Lighting.ANormalLightLol}
```

----

### getAncestors
Returns an array containing all ancestors of the given `descendant`. Specifically, it retrieves every `Instance` in the hierarchy above the `descendant`, starting from its immediate `Parent`, working up towards the `DataModel`.

**Syntax:** `InstanceUtils:getAncestors(descendant: Instance) → {Instance}`

**Parameters:**
* `descendant`: The instance to whom the ancestors are going to be searched from.

**Returns:**
* [`Array`](https://create.roblox.com/docs/luau/tables#arrays): An array containing the `descendant`'s ancestors.

**Code Example:**
```lua
local ancestorsOfBar = InstanceUtils:getSiblings(workspace.Camera2.SomethingElse.Bar) --> {workspace.Camera2.SomethingElse, workspace.Camera2, workspace, game}
```

----

### getChildrenOfName
Returns an array containing all children of the given `parent` of which their `Object.Name` properties are equal to the given `name`.

**Syntax:** `InstanceUtils:getChildrenOfName(parent: Instance, name: string) → {Instance}`

**Parameters:**
* `parent`: The instance to whom the children are going to be searched from.
* `name`: The `Object.Name` to be looked for.

**Returns:**
* [`Array`](https://create.roblox.com/docs/luau/tables#arrays): An array containing the `parent`'s children.

**Code Example:**
```lua
local childrenOfCamera2 = InstanceUtils:getChildrenOfName(workspace.Camera2, "FakeThing1") --> {workspace.Camera2.FakeThing1, workspace.Camera2.FakeThing1, workspace.Camera2.FakeThing1}

print("Name is '" .. childrenOfCamera2[1].Name .. "' and ClassName is '" .. childrenOfCamera2[1].ClassName .. "'") --> Name is 'FakeThing1' and ClassName is 'Camera'
print("Name is '" .. childrenOfCamera2[2].Name .. "' and ClassName is '" .. childrenOfCamera2[2].ClassName .. "'") --> Name is 'FakeThing1' and ClassName is 'Part'
print("Name is '" .. childrenOfCamera2[3].Name .. "' and ClassName is '" .. childrenOfCamera2[3].ClassName .. "'") --> Name is 'FakeThing1' and ClassName is 'Part'
```

----

### getSiblingsOfName
Returns an array containing all siblings of the given `parent` of which their `Object.Name` properties are equal to the given `name`.

**Syntax:** `InstanceUtils:getSiblingsOfName(child: Instance, name: string) → {Instance}`

**Parameters:**
* `sibling`: The instance to whom the siblings are going to be searched from.

**Returns:**
* [`Array`](https://create.roblox.com/docs/luau/tables#arrays): An array containing the `sibling`'s siblings.

**Code Example:**
```lua
local siblingsOfWorkspace = InstanceUtils:getSiblingsOfName(workspace.Part1, "Part2") --> {workspace.Part2, workspace.Part2, workspace.Part2, workspace.Part2}

for _, sibling in siblingsOfASimpleTruss do
   print(sibling.Name)
   -- Output:
   --> Part2
   --> Part2
   --> Part2
   --> Part2
```
