# Vector3

### Constructors

```luau
Vector3.new(x: number, y: number, z: number): Vector3
```

Creates a vector with `X`, `Y`, and `Z` properties.

### Operators

`Vector3` supports addition, subtraction, negation, multiplication, division, and equality. Multiplication and division accept another `Vector3` or a number.

```luau
local offset = Vector3.new(0, 5, 0)
workspace.Baseplate.Position = workspace.Baseplate.Position + offset
```
