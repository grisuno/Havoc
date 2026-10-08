# Subsystem: handlers

## teamserver/pkg/handlers/external.go
- Layer: presentation
- Language: go
- Symbols:
  - `NewExternal` (function, line 15) `func NewExternal(`
  - `Start` (function, line 24) `func (e *External) Start(`
  - `Request` (function, line 37) `func (e *External) Request(`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`

## teamserver/pkg/handlers/handlers.go
- Layer: presentation
- Language: go
- Symbols:
  - `parseAgentRequest` (function, line 23) `func parseAgentRequest(`
  - `handleDemonAgent` (function, line 56) `func handleDemonAgent(`
  - `handleServiceAgent` (function, line 311) `func handleServiceAgent(`
  - `notifyTaskSize` (function, line 349) `func notifyTaskSize(`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/listeners.go`

## teamserver/pkg/handlers/http.go
- Layer: presentation
- Language: go
- Symbols:
  - `NewConfigHttp` (function, line 24) `func NewConfigHttp(`
  - `generateCertFiles` (function, line 32) `func (h *HTTP) generateCertFiles(`
  - `fake404` (function, line 80) `func (h *HTTP) fake404(`
  - `request` (function, line 93) `func (h *HTTP) request(`
  - `Start` (function, line 203) `func (h *HTTP) Start(`
  - `Stop` (function, line 277) `func (h *HTTP) Stop(`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`

## teamserver/pkg/handlers/smb.go
- Layer: presentation
- Language: go
- Symbols:
  - `NewPivotSmb` (function, line 8) `func NewPivotSmb(`
  - `Start` (function, line 14) `func (s *SMB) Start(`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`

## teamserver/pkg/handlers/types.go
- Layer: presentation
- Language: go
- Depends on: `teamserver/pkg/handlers/http.go`
