# Subsystem: events

## teamserver/pkg/events/chatlog.go
- Layer: infrastructure
- Language: go
- Symbols:
  - `NewUserConnected` (function, line 11) `func (chatLog) NewUserConnected(`
  - `UserDisconnected` (function, line 27) `func (chatLog) UserDisconnected(`

## teamserver/pkg/events/demons.go
- Layer: infrastructure
- Language: go
- Symbols:
  - `NewDemon` (function, line 19) `func (demons) NewDemon(`
  - `DemonOutput` (function, line 83) `func (demons) DemonOutput(`
  - `CallBack` (function, line 105) `func (demons) CallBack(`
  - `MarkAs` (function, line 121) `func (demons) MarkAs(`
- Depends on: `teamserver/pkg/logr/logr.go`

## teamserver/pkg/events/events.go
- Layer: infrastructure
- Language: go
- Symbols:
  - `Authenticated` (function, line 22) `func Authenticated(`
  - `UserAlreadyExits` (function, line 56) `func UserAlreadyExits(`
  - `UserDoNotExists` (function, line 72) `func UserDoNotExists(`
  - `SendProfile` (function, line 88) `func SendProfile(`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/service/service.go`

## teamserver/pkg/events/gate.go
- Layer: infrastructure
- Language: go
- Symbols:
  - `SendStageless` (function, line 12) `func (g gate) SendStageless(`
  - `SendConsoleMessage` (function, line 30) `func (g gate) SendConsoleMessage(`

## teamserver/pkg/events/listeners.go
- Layer: infrastructure
- Language: go
- Symbols:
  - `ListenerAdd` (function, line 15) `func (listeners) ListenerAdd(`
  - `ListenerEdit` (function, line 97) `func (listeners) ListenerEdit(`
  - `ListenerError` (function, line 154) `func (listeners) ListenerError(`
  - `ListenerRemove` (function, line 173) `func (listeners) ListenerRemove(`
  - `ListenerMark` (function, line 187) `func (listeners) ListenerMark(`
- Depends on: `teamserver/pkg/handlers/handlers.go`

## teamserver/pkg/events/service.go
- Layer: business_logic
- Language: go
- Symbols:
  - `AgentRegister` (function, line 11) `func (service) AgentRegister(`
  - `ListenerRegister` (function, line 25) `func (service) ListenerRegister(`

## teamserver/pkg/events/teamserver.go
- Layer: infrastructure
- Language: go
- Symbols:
  - `Logger` (function, line 11) `func (teamserver) Logger(`
  - `Profile` (function, line 25) `func (teamserver) Profile(`
