# Game

The global `game` value represents the current Roblox DataModel.

### Properties

```luau
game.PlaceId: number
```

The current place ID. This property is read-only.

```luau
game.GameId: number
```

The current universe ID. This property is read-only.

```luau
game.CreatorId: number
```

The ID of the experience creator. This property is read-only.

```luau
game.PlaceVersion: number
```

The published place version. This property is read-only.

```luau
game.JobId: string
```

The current server job ID. This property is read-only.

```luau
game.IsLoaded: boolean
```

Whether the current DataModel has loaded. This property is read-only.

```luau
game.PrimitiveCount: number
```

The current primitive count. This property is read-only.

```luau
game.ServerIP: string
```

The current server address when available. This property is read-only.

```luau
game.Workspace: Workspace
```

The current Workspace service. This property is read-only.

```luau
game.Players: Players
```

The Players service. This property is read-only.

### Methods

```luau
game:GetService(name: string): Instance
```

Returns a supported Roblox service by name.

```luau
game:HttpGet(url: string): string
```

Downloads and returns the response body from an HTTP or HTTPS URL.

