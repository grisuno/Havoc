# Subsystem: cmd

## teamserver/cmd/client.go
- Layer: infrastructure
- Language: go

## teamserver/cmd/cmd.go
- Layer: utility
- Language: go
- Symbols:
  - `init` (function, line 29) `func init(`
  - `teamserverFunc` (function, line 47) `func teamserverFunc(`
  - `startMenu` (function, line 61) `func startMenu(`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/main.go`

## teamserver/cmd/server.go
- Layer: utility
- Language: go
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
