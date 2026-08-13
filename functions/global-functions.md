# Global Functions

### identifyexecutor

```luau
identifyexecutor()
```

Returns two strings, being the executor's name and current version.

### base64encode

```luau
base64encode("string")
```

Encodes given string in base64.

### base64decode

```luau
base64decode("string")
```

Decodes given base64 string to normal string.

### loadstring

```luau
loadstring(source: string, chunkName: string?)
```

Compiles Luau source and returns a function. Returns `nil` and an error message if compilation fails.

### getscriptbytecode

```luau
getscriptbytecode(script: Instance): string
```

Returns the raw bytecode of a `Script`, `LocalScript`, or `ModuleScript`.

### decompile

```luau
decompile(scriptOrBytecode: Instance | string): string
```

Decompiles a script Instance or raw script bytecode and returns Luau source.
