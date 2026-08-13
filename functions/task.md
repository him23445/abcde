# Task

### task.spawn

```luau
task.spawn(function(...), ...)
```

Schedules a function to run asynchronously.

### task.defer

```luau
task.defer(function(...), ...)
```

Schedules a function to run on the next VM update.

### task.wait

```luau
task.wait(seconds: number?): number
```

Yields the current thread and resumes it after the requested time. With no argument, it waits for the next 60 FPS update.
