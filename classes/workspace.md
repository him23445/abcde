# Workspace

```luau
local Workspace = game:GetService("Workspace")
local sameWorkspace = workspace
```

The global `workspace` value references the current Workspace service.

### Properties

```luau
Workspace.CurrentCamera: Camera?
```

The current camera. This property is read-only.

```luau
Workspace.DistributedGameTime: number
```

The amount of time the current game has been running. This property is read-only.

```luau
Workspace.ReadOnlyGravity: number
```

The current gravity value. This property is read-only.

```luau
Workspace.Gravity: number
```

The gravity applied to the world.

```luau
Workspace.FallenPartsDestroyHeight: number
```

Parts below this height are removed by Roblox.
