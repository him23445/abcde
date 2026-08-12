# Data Types

### Vector2

```luau
Vector2.new(x: number, y: number): Vector2
```

Creates a two-dimensional vector with `X` and `Y` properties.

### Vector3

```luau
Vector3.new(x: number, y: number, z: number): Vector3
```

Creates a three-dimensional vector with `X`, `Y`, and `Z` properties.

`Vector2` and `Vector3` support addition, subtraction, negation, multiplication, division, and equality. Multiplication and division accept either another vector or a number.

```luau
local offset = Vector3.new(0, 5, 0)
workspace.Baseplate.Position = workspace.Baseplate.Position + offset
workspace.Baseplate.Velocity = Vector3.new(0, 20, 0)
```

### Color3

```luau
Color3.new(r: number, g: number, b: number): Color3
Color3.fromRGB(r: number, g: number, b: number): Color3
Color3.fromHSV(h: number, s: number, v: number): Color3
```

Creates a color with `R`, `G`, and `B` properties.
