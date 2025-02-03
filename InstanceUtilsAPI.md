## Functions
Throughout this documentation here, we're going to be using an example Roblox Studio object hierarchy:
```
game      # Class: DataModel
├─ Workspace
│  ├─ Camera      # Class: Camera
│  ├─ Camera2      # Class: Camera
│  │  ├─ SurfaceGui      # Class: Camera
│  │  ├─ SomethingElse      # Class: Camera
│  │  │  └─ Bar      # Class: TextLabel
│  │  ├─ ASimpleTruss      # Class: TrussPart
│  │  └─ Foo      # Class: Camera
│  ├─ GreenTheBlaze      # Class: Model
│  ├─ GreenTheBlaze      # Class: Part
│  ├─ FakeCamera      # Class: BasePart
│  ├─ Part      # Class: BasePart
│  ├─ Part      # Class: BasePart
│  ├─ Part1      # Class: BasePart
│  ├─ Part2      # Class: BasePart
│  ├─ Part2      # Class: BasePart
│  ├─ Part2      # Class: Union
│  ├─ Part2      # Class: MeshPart
│  └─ Terrain     # Class: Terrain
└─ Lighting
   ├─ ANormalLight      # Class: PointLight
   ├─ Sky      # Class: Sky
   └─ ANormalLightLol      # Class: MeshPart
```
*Don't mind the weird names LOL.*

#### getSiblings
Returns an array (a numerically indexed table) containing all direct siblings of the instance. In other words, it retrieves every `Instance` that shares the same `Parent` as the given `child`.

**Syntax:** `InstanceUtils:getSiblings(child: Instance) → {Instance}`

**Parameters:**
* `child`: The instance to whom the siblings are going to be searched from.

**Returns:**
* `Array`: An array containing the `child`'s siblings.

**Code Example:**
```lua
local siblingsOfSky = InstanceUtils:getSiblings(game.Lighting.Sky)  -- Returns: { Lighting.ANormalLight, Lighting.ANormalLightLol }
```

----
#### getAncestors
Returns an array containing all ancestors of the instance. Specifically, it retrieves every `Instance` in the hierarchy above the given `descendant`, starting from its immediate `Parent`, working up towards the `DataModel`.

**Syntax:** `InstanceUtils:getAncestors(descendant: Instance) → {Instance}`

**Parameters:**
* `descendant`: The instance to whom the ancestors are going to be searched from.

**Returns:**
* `Array`: An array containing the `descendant`'s ancestors.

**Code Example:**
```lua
local ancestorsOfBar = InstanceUtils:getSiblings(workspace.Camera2.SomethingElse.Bar)  -- Returns: { workspace.Camera2.SomethingElse, workspace.Camera2, workspace, game }
```

----
#### getChildrenOfName
[Needs doing]

**Syntax:** `InstanceUtils:getChildrenOfName(parent: Instance, name: string) → {Instance}`

**Parameters:**
* `parent`: The instance to whom the children are going to be searched from.

**Returns:**
* `Array`: An array containing the `parent`'s children.

**Code Example:**
```lua
local childrenOfCamera2 = InstanceUtils:getChildrenOfName(workspace.Camera2)  -- Returns: { workspace.Camera2.SurfaceGui, workspace.Camera2.SomethingElse, workspace.Camera2.ASimpleTruss, workspace.Camera2.Foo }

for _, child in childrenOfCamera2 do
   print(child.Name)
   -- Output:
   --> SurfaceGui
   --> SomethingElse
   --> ASimpleTruss
   --> Foo
```
----
#### getSiblingsOfName
[Needs doing]

**Syntax:** `InstanceUtils:getSiblingsOfName(sibling: Instance, name: string) → {Instance}`

**Parameters:**
* `sibling`: The instance to whom the siblings are going to be searched from.

**Returns:**
* `Array`: An array containing the `sibling`'s siblings.

**Code Example:**
```lua
local siblingsOfASimpleTruss = InstanceUtils:getSiblingsOfName(workspace.Camera2.ASimpleTruss)  -- Returns: { workspace.Camera2.SurfaceGui, workspace.Camera2.SomethingElse, workspace.Camera2.Foo }

for _, sibling in siblingsOfASimpleTruss do
   print(sibling.Name)
   -- Output:
   --> SurfaceGui
   --> SomethingElse
   --> Foo
```
