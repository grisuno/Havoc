# Subsystem: logr

## teamserver/pkg/logr/demon.go
- Layer: utility
- Language: go
- Symbols:
  - `AddAgentInput` (function, line 15) `func (l Logr) AddAgentInput(`
  - `AddAgentRaw` (function, line 50) `func (l Logr) AddAgentRaw(`
  - `DemonAddOutput` (function, line 82) `func (l Logr) DemonAddOutput(`
  - `DemonAddDownloadedFile` (function, line 134) `func (l Logr) DemonAddDownloadedFile(`
  - `DemonSaveScreenshot` (function, line 177) `func (l Logr) DemonSaveScreenshot(`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/logr/listener.go
- Layer: utility
- Language: go
- Symbols:
  - `ListenerAddKeyCert` (function, line 3) `func (l Logr) ListenerAddKeyCert(`

## teamserver/pkg/logr/logr.go
- Layer: utility
- Language: go
- Symbols:
  - `NewLogr` (function, line 21) `func NewLogr(`
  - `Logr` (struct, line 9)
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/events/demons.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/service/service.go`

## teamserver/pkg/logr/server.go
- Layer: utility
- Language: go
- Symbols:
  - `strip` (function, line 12) `func strip(`
  - `ServerStdOutInit` (function, line 21) `func (l Logr) ServerStdOutInit(`
- Depends on: `teamserver/pkg/logger/logger.go`
