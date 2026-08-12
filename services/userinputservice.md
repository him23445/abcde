# UserInputService

```luau
local UserInputService = game:GetService("UserInputService")
```

### Events

```luau
UserInputService.InputEnded:Connect(function(input: InputObject)
end)
```

Fires when a supported keyboard key is released.

```luau
UserInputService.InputBegan:Connect(function(input: InputObject)
end)
```

Fires when a supported keyboard key is pressed.

### InputObject

```luau
InputObject.KeyCode: EnumItem
```

`KeyCode` identifies the keyboard input.

