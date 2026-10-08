# Subsystem: agent

## teamserver/pkg/agent/agent.go
- Doc: IsKnownRequestID: check that the request the agent is valid
- Layer: utility
- Language: go
- Symbols:
  - `BuildPayloadMessage` (function, line 29) `func BuildPayloadMessage(`
  - `ParseHeader` (function, line 181) `func ParseHeader(`
  - `RegisterInfoToInstance` (function, line 215) `func RegisterInfoToInstance(`
  - `ParseDemonRegisterRequest` (function, line 328) `func ParseDemonRegisterRequest(`
  - `IsKnownRequestID` (function, line 609) `func (a *Agent) IsKnownRequestID(`
  - `AddRequest` (function, line 632) `func (a *Agent) AddRequest(`
  - `RequestCompleted` (function, line 638) `func (a *Agent) RequestCompleted(`
  - `AddJobToQueue` (function, line 647) `func (a *Agent) AddJobToQueue(`
  - `GetQueuedJobs` (function, line 661) `func (a *Agent) GetQueuedJobs(`
  - `UpdateLastCallback` (function, line 739) `func (a *Agent) UpdateLastCallback(`
  - `PivotAddJob` (function, line 746) `func (a *Agent) PivotAddJob(`
  - `DownloadAdd` (function, line 816) `func (a *Agent) DownloadAdd(`
  - `DownloadWrite` (function, line 865) `func (a *Agent) DownloadWrite(`
  - `DownloadClose` (function, line 888) `func (a *Agent) DownloadClose(`
  - `DownloadGet` (function, line 902) `func (a *Agent) DownloadGet(`
  - `PortFwdNew` (function, line 911) `func (a *Agent) PortFwdNew(`
  - `PortFwdGet` (function, line 929) `func (a *Agent) PortFwdGet(`
  - `PortFwdIsOpen` (function, line 948) `func (a *Agent) PortFwdIsOpen(`
  - `PortFwdOpen` (function, line 958) `func (a *Agent) PortFwdOpen(`
  - `PortFwdWrite` (function, line 979) `func (a *Agent) PortFwdWrite(`
  - `PortFwdRead` (function, line 997) `func (a *Agent) PortFwdRead(`
  - `PortFwdClose` (function, line 1023) `func (a *Agent) PortFwdClose(`
  - `SocksClientAdd` (function, line 1053) `func (a *Agent) SocksClientAdd(`
  - `SocksClientGet` (function, line 1073) `func (a *Agent) SocksClientGet(`
  - `SocksClientRead` (function, line 1096) `func (a *Agent) SocksClientRead(`
  - `SocksClientClose` (function, line 1130) `func (a *Agent) SocksClientClose(`
  - `SocksServerRemove` (function, line 1163) `func (a *Agent) SocksServerRemove(`
  - `ToMap` (function, line 1193) `func (a *Agent) ToMap(`
  - `ToJson` (function, line 1224) `func (a *Agent) ToJson(`
  - `AgentsAppend` (function, line 1238) `func (agents *Agents) AgentsAppend(`
  - `getWindowsVersionString` (function, line 1243) `func getWindowsVersionString(`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

## teamserver/pkg/agent/commands.go
- Layer: utility
- Language: go

## teamserver/pkg/agent/demons.go
- Doc: UploadMemFileInChunks: we upload heavy files to the implant in chunks, so SMB agents can handle...
- Layer: utility
- Language: go
- Symbols:
  - `UploadMemFileInChunks` (function, line 31) `func (a *Agent) UploadMemFileInChunks(`
  - `TeamserverTaskPrepare` (function, line 64) `func (a *Agent) TeamserverTaskPrepare(`
  - `TaskPrepare` (function, line 128) `func (a *Agent) TaskPrepare(`
  - `TaskDispatch` (function, line 2285) `func (a *Agent) TaskDispatch(`
  - `Console` (function, line 6430) `func (a *Agent) Console(`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/socks/socks.go`, `teamserver/pkg/utils/utils.go`

## teamserver/pkg/agent/types.go
- Doc: Agent: TODO: maybe change this to type map[string]any instead of struct
- Layer: utility
- Language: go
- Symbols:
  - `DemonInterface` (interface, line 19)
  - `EventInterface` (interface, line 23)
  - `Header` (struct, line 26)
  - `ServiceAgentInterface` (interface, line 33)
  - `TeamServer` (interface, line 40)
  - `Job` (struct, line 73)
  - `Pivots` (struct, line 89)
  - `Download` (struct, line 94)
  - `BofCallback` (struct, line 104)
  - `PortFwd` (struct, line 111)
  - `SocksClient` (struct, line 124)
  - `SocksServer` (struct, line 133)
  - `Agent` (struct, line 139)
  - `AgentInfo` (struct, line 174)
  - `Agents` (struct, line 212)
- Depends on: `teamserver/pkg/socks/socks.go`
