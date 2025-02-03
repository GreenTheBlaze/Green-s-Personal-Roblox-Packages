## Functions
Throughout this documentation here, we're going to be using an example Roblox Studio object hierarchy:
```
.
├─ Workspace
│  ├─ Camera      # Class: Camera
│  ├─ Camera2      # Class: Camera
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

#### getSiblings
[Needs adding]

**Syntax:** `InstanceUtils:getSiblings(child: Instance) → {Instance}`
**Parameters:**
* `child`: The instance to whom the siblings are going to be searched from.
**Returns:**
* `Array`: An array containing the child's siblings.
**Code Example:**
```lua
local siblingsOfCamera = InstanceUtils:getSiblings(game.Lighting.Sky)  -- Returns: { Lighting.ANormalLight, Lighting.ANormalLightLol }
```

----
#### getAncestors
[Needs adding]

**Syntax:** `InstanceUtils:getSiblings(child: Instance) → {Instance}`
**Parameters:**
* `child`: The instance to whom the siblings are going to be searched from.
**Returns:**
* `Array`: An array containing the child's siblings.
**Code Example:**
```lua
local siblingsOfCamera = InstanceUtils:getSiblings(game.Lighting.Sky)  -- Returns: { Lighting.ANormalLight, Lighting.ANormalLightLol }
```
Returns an icon of the given name or UID.
