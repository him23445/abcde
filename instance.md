# Instance

### Properties

```luau
Instance.Name: string
```

The instance name. This property is read-only.

```luau
Instance.ClassName: string
```

The Roblox class name. This property is read-only.

```luau
Instance.Parent: Instance?
```

The instance containing this instance. Returns `nil` when there is no parent. Assign another Instance to move it, or assign `nil` to remove its parent.


### Methods

```luau
Instance:FindFirstChild(name: string): Instance?
```

Returns the first direct child with the given name, or `nil` when it cannot be found.

```luau
Instance:FindFirstChildOfClass(className: string): Instance?
```

Returns the first direct child with the given class name.

```luau
Instance:GetChildren(): {Instance}
```

Returns an array containing the instance's direct children.

Children can also be accessed by name:

```luau
local baseplate = game.Workspace.Baseplate
```

