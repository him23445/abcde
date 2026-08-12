# RunService

```luau
local RunService = game:GetService("RunService")
```

### Properties

```luau
RunService.RenderStepped: RBXScriptSignal
```

Fires at a fixed rate of 60 times per second and passes the frame delta to the callback.

### Events

```luau
RunService.RenderStepped:Connect(function(deltaTime: number)
    print(deltaTime)
end)
```
