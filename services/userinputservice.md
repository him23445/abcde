# UserInputService

```luau
local UserInputService = game:GetService("UserInputService")
```

### Events

```luau
UserInputService.InputEnded:Connect(function(input: InputObject)
end)
```

Fires when a supported keyboard key is released. The callback receives one argument.

```luau
UserInputService.InputChanged:Connect(function(input: InputObject)
end)
```

Fires when the cursor moves while Roblox is focused. The callback receives one argument.

### InputObject

```luau
InputObject.KeyCode: EnumItem
InputObject.Position: Vector3
InputObject.Delta: Vector3
```

`KeyCode` identifies released keyboard input. Cursor movement uses `Enum.KeyCode.Unknown` and provides its client position and movement delta.

