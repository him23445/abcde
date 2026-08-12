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
UserInputService.InputChanged:Connect(function(input: InputObject)
end)
```

Fires when a supported keyboard key changes between pressed and released.

### InputObject

```luau
InputObject.KeyCode: EnumItem
```

`KeyCode` identifies the keyboard input.

