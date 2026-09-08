# Subsystem: teamserver

## teamserver/Install.sh
- Layer: utility
- Language: sh

## teamserver/main.go
- Layer: utility
- Language: go
- Symbols:
  - `main` (function, line 6) `func main(`
- Depends on: `teamserver/cmd/cmd.go`, `teamserver/pkg/logger/logger.go`
