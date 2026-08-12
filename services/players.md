# Players

```luau
local Players = game:GetService("Players")
```

### Properties

```luau
Players.LocalPlayer: Player?
```

The player controlled by the current Roblox client.

```luau
Players.PlayerAdded: RBXScriptSignal
```

Fires when another player joins the server.

```luau
Players.PlayerRemoving: RBXScriptSignal
```

Fires when a player leaves the server.

```luau
Players.Name: string
```

Returns `"Players"`.

```luau
Players.ClassName: string
```

Returns `"Players"`.

### Methods

```luau
Players:GetPlayers(): {Player}
```

Returns an array containing the players currently in the server.

### Events

```luau
Players.PlayerAdded:Connect(function(player: Player)
    print(player.Name, "joined")
end)
```

```luau
Players.PlayerRemoving:Connect(function(player: Player)
    print(player.Name, "left")
end)
```

