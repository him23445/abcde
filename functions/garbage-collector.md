# Garbage Collector

### getgc

```luau
getgc(includeTables: boolean?): {any}
```

Returns objects tracked by the garbage collector. Pass `true` to include tables.

```luau
for _, object in getgc(true) do
    if object.FireRate ~= nil then
        print(object.FireRate)
    end
end
```

### setgc

```luau
setgc(name: string, value: any): number
```

Finds matching fields and changes their values. Returns the number of fields changed.

```luau
local changed = setgc("FireRate", 0)
print(changed)
```

Multiple fields can be changed at once:

```luau
setgc({
    FireRate = 0,
    SpreadAngle = 0,
    CameraRecoilMult = 0,
})
```
