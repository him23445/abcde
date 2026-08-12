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

```luau
Players.PlayerRemoving: RBXScriptSignal
```

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

