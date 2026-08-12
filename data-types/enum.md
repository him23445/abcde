# Enum

### KeyCode

```luau
Enum.KeyCode.F: EnumItem
```

`Enum.KeyCode` contains common keyboard keys, letters, number keys, navigation keys, modifiers, and `F1` through `F12`.

Enum items provide `Name`, `Value`, and `EnumType` properties and can be compared directly.

```luau
if input.KeyCode == Enum.KeyCode.F then
    print("F was released")
end
```
