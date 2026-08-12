# Player

### Properties

```luau
Player.Character: Model?
```

The player's current character. This property is read-only.

```luau
Player.UserId: number
Player.DisplayName: string
Player.LocaleId: string
Player.AccountAge: number
Player.Team: Instance?
```

These properties are read-only.

```luau
Player.CameraMode: number
Player.MaxZoomDistance: number
Player.MinZoomDistance: number
Player.HealthDisplayDistance: number
Player.NameDisplayDistance: number
```

These properties can be read and changed.

### Methods

Player supports the methods listed on [Instance](../instance.md), including direct child lookup:

```luau
local backpack = player:FindFirstChild("Backpack")
```
