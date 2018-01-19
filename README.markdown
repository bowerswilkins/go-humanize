# humantime

Self-conained `time.Duration`-to-human-readable-string conversion package.

Forked from https://godoc.org/github.com/dustin/go-humanize.

## usage

Example:

```go
fmt.Printf("posted %s", humantime.Time(time.Now().Add(-7 * time.Hour)))
```

Yields:

```
posted 7 hours ago
```

There's also a condensed option:

```go
fmt.Printf("posted %s", humantime.CondensedTime(time.Now().Add(-7 * time.Hour)))
```

Yields:

```
posted 7h ago
```
