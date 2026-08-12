# HttpService

```luau
local HttpService = game:GetService("HttpService")
```

### Properties

```luau
HttpService.HttpEnabled: boolean
```

Returns whether HTTP functions are available.

### Methods

```luau
HttpService:JSONEncode(value: table): string
```

Converts a Luau value into a JSON string.

```luau
HttpService:JSONDecode(json: string): any
```

Converts a JSON string into a Luau value.

```luau
HttpService:GenerateGUID(wrapInCurlyBraces: boolean?): string
```

Creates a random GUID. Curly braces are included by default.

