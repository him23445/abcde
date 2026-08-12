# Camera

### Properties

```luau
Camera.FieldOfView: number
```

The vertical field of view in degrees.

```luau
Camera.CameraSubject: Instance?
```

The instance currently followed by the camera. This property is read-only.

```luau
Camera.CameraType: number
```

The numeric camera type.

```luau
Camera.ImagePlaneDepth: number
```

The camera image-plane depth. This property is read-only.

```luau
Camera.Position: Vector3
```

The world position of the camera.

### Methods

```luau
Camera:WorldToViewportPoint(position: Vector3): Vector3, boolean
```

Converts a world position into screen coordinates. The second return value says whether the point is on screen.
