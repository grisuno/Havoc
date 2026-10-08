# Subsystem: server

## teamserver/cmd/server/agent.go
- Layer: utility
- Language: go
- Symbols:
  - `AgentUpdate` (function, line 16) `func (t *Teamserver) AgentUpdate(`
  - `Died` (function, line 23) `func (t *Teamserver) Died(`
  - `UnlinkFromAll` (function, line 30) `func (t *Teamserver) UnlinkFromAll(`
  - `ParentOf` (function, line 53) `func (t *Teamserver) ParentOf(`
  - `LinksOf` (function, line 60) `func (t *Teamserver) LinksOf(`
  - `LinkAdd` (function, line 66) `func (t *Teamserver) LinkAdd(`
  - `LinkRemove` (function, line 78) `func (t *Teamserver) LinkRemove(`
  - `AgentHasDied` (function, line 102) `func (t *Teamserver) AgentHasDied(`
  - `AgentAdd` (function, line 108) `func (t *Teamserver) AgentAdd(`
  - `AgentSendNotify` (function, line 123) `func (t *Teamserver) AgentSendNotify(`
  - `AgentCallbackSize` (function, line 138) `func (t *Teamserver) AgentCallbackSize(`
  - `AgentInstance` (function, line 155) `func (t *Teamserver) AgentInstance(`
  - `AgentLastTimeCalled` (function, line 166) `func (t *Teamserver) AgentLastTimeCalled(`
  - `AgentExist` (function, line 183) `func (t *Teamserver) AgentExist(`
  - `AgentConsole` (function, line 198) `func (t *Teamserver) AgentConsole(`
  - `PythonModuleCallback` (function, line 208) `func (t *Teamserver) PythonModuleCallback(`
  - `AgentCallback` (function, line 220) `func (t *Teamserver) AgentCallback(`
  - `SendLogs` (function, line 233) `func (t *Teamserver) SendLogs(`
  - `GetDotNetPipeTemplate` (function, line 237) `func (t *Teamserver) GetDotNetPipeTemplate(`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

## teamserver/cmd/server/dispatch.go
- Layer: utility
- Language: go
- Symbols:
  - `DispatchEvent` (function, line 20) `func (t *Teamserver) DispatchEvent(`
- Depends on: `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

## teamserver/cmd/server/listener.go
- Doc: ListenerAdd: ListenerAdd creates a package for the client that a new listener has been added.
- Layer: utility
- Language: go
- Symbols:
  - `ListenerStart` (function, line 19) `func (t *Teamserver) ListenerStart(`
  - `ListenerExist` (function, line 113) `func (t *Teamserver) ListenerExist(`
  - `ListenerGetInfo` (function, line 124) `func (t *Teamserver) ListenerGetInfo(`
  - `ListenerRemove` (function, line 144) `func (t *Teamserver) ListenerRemove(`
  - `ListenerEdit` (function, line 192) `func (t *Teamserver) ListenerEdit(`
  - `ListenerAdd` (function, line 220) `func (t *Teamserver) ListenerAdd(`
  - `ListenerServiceExc2Add` (function, line 337) `func (t *Teamserver) ListenerServiceExc2Add(`
  - `ListenerStartNotify` (function, line 378) `func (t *Teamserver) ListenerStartNotify(`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

## teamserver/cmd/server/service.go
- Layer: business_logic
- Language: go
- Symbols:
  - `ServiceAgent` (function, line 9) `func (t *Teamserver) ServiceAgent(`
  - `ServiceAgentExist` (function, line 20) `func (t *Teamserver) ServiceAgentExist(`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/cmd/server/teamserver.go
- Layer: utility
- Language: go
- Symbols:
  - `NewTeamserver` (function, line 37) `func NewTeamserver(`
  - `SetServerFlags` (function, line 48) `func (t *Teamserver) SetServerFlags(`
  - `Start` (function, line 52) `func (t *Teamserver) Start(`
  - `handleRequest` (function, line 497) `func (t *Teamserver) handleRequest(`
  - `SetProfile` (function, line 626) `func (t *Teamserver) SetProfile(`
  - `ClientAuthenticate` (function, line 637) `func (t *Teamserver) ClientAuthenticate(`
  - `EventBroadcast` (function, line 690) `func (t *Teamserver) EventBroadcast(`
  - `EventNewDemon` (function, line 709) `func (t *Teamserver) EventNewDemon(`
  - `EventAgentMark` (function, line 713) `func (t *Teamserver) EventAgentMark(`
  - `EventListenerError` (function, line 720) `func (t *Teamserver) EventListenerError(`
  - `SendEvent` (function, line 741) `func (t *Teamserver) SendEvent(`
  - `RemoveClient` (function, line 773) `func (t *Teamserver) RemoveClient(`
  - `EventAppend` (function, line 797) `func (t *Teamserver) EventAppend(`
  - `EventRemove` (function, line 812) `func (t *Teamserver) EventRemove(`
  - `SendAllPackagesToNewClient` (function, line 818) `func (t *Teamserver) SendAllPackagesToNewClient(`
  - `FindSystemPackages` (function, line 842) `func (t *Teamserver) FindSystemPackages(`
  - `EndpointAdd` (function, line 933) `func (t *Teamserver) EndpointAdd(`
  - `EndpointRemove` (function, line 945) `func (t *Teamserver) EndpointRemove(`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

## teamserver/cmd/server/types.go
- Layer: utility
- Language: go
- Symbols:
  - `Listener` (struct, line 16)
  - `Client` (struct, line 22)
  - `Users` (struct, line 34)
  - `serverFlags` (struct, line 41)
  - `utilFlags` (struct, line 53)
  - `TeamserverFlags` (struct, line 63)
  - `Endpoint` (struct, line 68)
  - `Teamserver` (struct, line 73)
- Depends on: `teamserver/pkg/db/db.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/webhook/webhook.go`
