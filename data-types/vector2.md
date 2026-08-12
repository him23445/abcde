# Vector2

### Constructors

```luau
Vector2.new(x: number, y: number): Vector2
```

Creates a vector with `X` and `Y` properties.

### Operators

`Vector2` supports addition, subtraction, negation, multiplication, division, and equality. Multiplication and division accept another `Vector2` or a number.

```luau
local position = Vector2.new(100, 50)
local moved = position + Vector2.new(10, 20)
```
