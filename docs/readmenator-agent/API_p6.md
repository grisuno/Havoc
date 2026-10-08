# API (page 6 of 8)
Previous: [API_p5.md](API_p5.md)

## teamserver/pkg/agent/agent.go
Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- `BuildPayloadMessage` (function) `teamserver/pkg/agent/agent.go:29` `func BuildPayloadMessage(`
- `ParseHeader` (function) `teamserver/pkg/agent/agent.go:181` `func ParseHeader(`
- `RegisterInfoToInstance` (function) `teamserver/pkg/agent/agent.go:215` `func RegisterInfoToInstance(`
- `ParseDemonRegisterRequest` (function) `teamserver/pkg/agent/agent.go:328` `func ParseDemonRegisterRequest(`
- `IsKnownRequestID` (function) `teamserver/pkg/agent/agent.go:609` `func (a *Agent) IsKnownRequestID(` -- check that the request the agent is valid
- `AddRequest` (function) `teamserver/pkg/agent/agent.go:632` `func (a *Agent) AddRequest(` -- the operator added a new request/command
- `RequestCompleted` (function) `teamserver/pkg/agent/agent.go:638` `func (a *Agent) RequestCompleted(` -- after a request has been completed, we can forget about the RequestID so that it is no longer valid
- `AddJobToQueue` (function) `teamserver/pkg/agent/agent.go:647` `func (a *Agent) AddJobToQueue(`
- `GetQueuedJobs` (function) `teamserver/pkg/agent/agent.go:661` `func (a *Agent) GetQueuedJobs(`
- `UpdateLastCallback` (function) `teamserver/pkg/agent/agent.go:739` `func (a *Agent) UpdateLastCallback(`
- `PivotAddJob` (function) `teamserver/pkg/agent/agent.go:746` `func (a *Agent) PivotAddJob(`
- `DownloadAdd` (function) `teamserver/pkg/agent/agent.go:816` `func (a *Agent) DownloadAdd(`
- `DownloadWrite` (function) `teamserver/pkg/agent/agent.go:865` `func (a *Agent) DownloadWrite(`
- `DownloadClose` (function) `teamserver/pkg/agent/agent.go:888` `func (a *Agent) DownloadClose(`
- `DownloadGet` (function) `teamserver/pkg/agent/agent.go:902` `func (a *Agent) DownloadGet(`
- `PortFwdNew` (function) `teamserver/pkg/agent/agent.go:911` `func (a *Agent) PortFwdNew(`
- `PortFwdGet` (function) `teamserver/pkg/agent/agent.go:929` `func (a *Agent) PortFwdGet(`
- `PortFwdIsOpen` (function) `teamserver/pkg/agent/agent.go:948` `func (a *Agent) PortFwdIsOpen(`
- `PortFwdOpen` (function) `teamserver/pkg/agent/agent.go:958` `func (a *Agent) PortFwdOpen(`
- `PortFwdWrite` (function) `teamserver/pkg/agent/agent.go:979` `func (a *Agent) PortFwdWrite(`
- `PortFwdRead` (function) `teamserver/pkg/agent/agent.go:997` `func (a *Agent) PortFwdRead(`
- `PortFwdClose` (function) `teamserver/pkg/agent/agent.go:1023` `func (a *Agent) PortFwdClose(`
- `SocksClientAdd` (function) `teamserver/pkg/agent/agent.go:1053` `func (a *Agent) SocksClientAdd(`
- `SocksClientGet` (function) `teamserver/pkg/agent/agent.go:1073` `func (a *Agent) SocksClientGet(`
- `SocksClientRead` (function) `teamserver/pkg/agent/agent.go:1096` `func (a *Agent) SocksClientRead(`
- `SocksClientClose` (function) `teamserver/pkg/agent/agent.go:1130` `func (a *Agent) SocksClientClose(`
- `SocksServerRemove` (function) `teamserver/pkg/agent/agent.go:1163` `func (a *Agent) SocksServerRemove(`
- `ToMap` (function) `teamserver/pkg/agent/agent.go:1193` `func (a *Agent) ToMap(` -- ToMap returns the agent info as a map
- `ToJson` (function) `teamserver/pkg/agent/agent.go:1224` `func (a *Agent) ToJson(`
- `AgentsAppend` (function) `teamserver/pkg/agent/agent.go:1238` `func (agents *Agents) AgentsAppend(`
- `getWindowsVersionString` (function) `teamserver/pkg/agent/agent.go:1243` `func getWindowsVersionString(`

## teamserver/pkg/agent/demons.go
Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/socks/socks.go`, `teamserver/pkg/utils/utils.go`
- `UploadMemFileInChunks` (function) `teamserver/pkg/agent/demons.go:31` `func (a *Agent) UploadMemFileInChunks(` -- we upload heavy files to the implant in chunks, so SMB agents can handle the size
- `TeamserverTaskPrepare` (function) `teamserver/pkg/agent/demons.go:64` `func (a *Agent) TeamserverTaskPrepare(`
- `TaskPrepare` (function) `teamserver/pkg/agent/demons.go:128` `func (a *Agent) TaskPrepare(`
- `TaskDispatch` (function) `teamserver/pkg/agent/demons.go:2285` `func (a *Agent) TaskDispatch(`
- `Console` (function) `teamserver/pkg/agent/demons.go:6430` `func (a *Agent) Console(`

## teamserver/pkg/common/builder/builder.go
Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
Imported by: `teamserver/cmd/server/dispatch.go`
- `NewBuilder` (function) `teamserver/pkg/common/builder/builder.go:141` `func NewBuilder(`
- `SetSilent` (function) `teamserver/pkg/common/builder/builder.go:213` `func (b *Builder) SetSilent(`
- `Build` (function) `teamserver/pkg/common/builder/builder.go:217` `func (b *Builder) Build(`
- `SetListener` (function) `teamserver/pkg/common/builder/builder.go:459` `func (b *Builder) SetListener(`
- `SetPatchConfig` (function) `teamserver/pkg/common/builder/builder.go:464` `func (b *Builder) SetPatchConfig(`
- `SetFormat` (function) `teamserver/pkg/common/builder/builder.go:481` `func (b *Builder) SetFormat(`
- `SetArch` (function) `teamserver/pkg/common/builder/builder.go:485` `func (b *Builder) SetArch(`
- `SetConfig` (function) `teamserver/pkg/common/builder/builder.go:489` `func (b *Builder) SetConfig(`
- `SetOutputPath` (function) `teamserver/pkg/common/builder/builder.go:501` `func (b *Builder) SetOutputPath(`
- `SetExtension` (function) `teamserver/pkg/common/builder/builder.go:505` `func (b *Builder) SetExtension(`
- `GetOutputPath` (function) `teamserver/pkg/common/builder/builder.go:509` `func (b *Builder) GetOutputPath(`
- `Patch` (function) `teamserver/pkg/common/builder/builder.go:513` `func (b *Builder) Patch(`
- `PatchConfig` (function) `teamserver/pkg/common/builder/builder.go:561` `func (b *Builder) PatchConfig(`
- `GetPayloadBytes` (function) `teamserver/pkg/common/builder/builder.go:1024` `func (b *Builder) GetPayloadBytes(`
- `Cmd` (function) `teamserver/pkg/common/builder/builder.go:1064` `func (b *Builder) Cmd(`
- `CompileCmd` (function) `teamserver/pkg/common/builder/builder.go:1090` `func (b *Builder) CompileCmd(`
- `GetListenerDefines` (function) `teamserver/pkg/common/builder/builder.go:1102` `func (b *Builder) GetListenerDefines(`
- `DeletePayload` (function) `teamserver/pkg/common/builder/builder.go:1122` `func (b *Builder) DeletePayload(`

## teamserver/pkg/common/certs/https.go
Depends on: `teamserver/pkg/logger/logger.go`
- `randomState` (function) `teamserver/pkg/common/certs/https.go:115` `func randomState(`
- `randomLocality` (function) `teamserver/pkg/common/certs/https.go:123` `func randomLocality(`
- `randomStreetAddress` (function) `teamserver/pkg/common/certs/https.go:132` `func randomStreetAddress(`
- `randomProvinceLocalityStreetAddress` (function) `teamserver/pkg/common/certs/https.go:137` `func randomProvinceLocalityStreetAddress(`
- `randomPostalCode` (function) `teamserver/pkg/common/certs/https.go:144` `func randomPostalCode(`
- `randomSubject` (function) `teamserver/pkg/common/certs/https.go:153` `func randomSubject(`
- `randomOrganization` (function) `teamserver/pkg/common/certs/https.go:166` `func randomOrganization(`
- `publicKey` (function) `teamserver/pkg/common/certs/https.go:182` `func publicKey(`
- `randomInt` (function) `teamserver/pkg/common/certs/https.go:193` `func randomInt(`
- `pemBlockForKey` (function) `teamserver/pkg/common/certs/https.go:200` `func pemBlockForKey(`
- `generateCertificate` (function) `teamserver/pkg/common/certs/https.go:216` `func generateCertificate(`
- `HTTPSGenerateRSACertificate` (function) `teamserver/pkg/common/certs/https.go:300` `func HTTPSGenerateRSACertificate(` -- HTTPSGenerateRSACertificate - Generate a server certificate signed with a given CA

## teamserver/pkg/common/crypt/aes.go
Depends on: `teamserver/pkg/logger/logger.go`
- `XCryptBytesAES256` (function) `teamserver/pkg/common/crypt/aes.go:10` `func XCryptBytesAES256(`

## teamserver/pkg/common/packer/packer.go
Depends on: `teamserver/pkg/logger/logger.go`
Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`
- `NewPacker` (function) `teamserver/pkg/common/packer/packer.go:22` `func NewPacker(`
- `AddInt64` (function) `teamserver/pkg/common/packer/packer.go:29` `func (p *Packer) AddInt64(`
- `AddInt32` (function) `teamserver/pkg/common/packer/packer.go:37` `func (p *Packer) AddInt32(`
- `AddInt` (function) `teamserver/pkg/common/packer/packer.go:45` `func (p *Packer) AddInt(`
- `AddUInt32` (function) `teamserver/pkg/common/packer/packer.go:54` `func (p *Packer) AddUInt32(` -- AddUInt32 use a much as possible this function
- `AddString` (function) `teamserver/pkg/common/packer/packer.go:62` `func (p *Packer) AddString(`
- `AddWString` (function) `teamserver/pkg/common/packer/packer.go:66` `func (p *Packer) AddWString(`
- `AddBytes` (function) `teamserver/pkg/common/packer/packer.go:70` `func (p *Packer) AddBytes(`
- `Build` (function) `teamserver/pkg/common/packer/packer.go:80` `func (p *Packer) Build(`
- `Buffer` (function) `teamserver/pkg/common/packer/packer.go:95` `func (p *Packer) Buffer(`
- `Size` (function) `teamserver/pkg/common/packer/packer.go:99` `func (p *Packer) Size(`
- `AddOwnSizeFirst` (function) `teamserver/pkg/common/packer/packer.go:103` `func (p *Packer) AddOwnSizeFirst(`

## teamserver/pkg/common/parser/parser.go
- `NewParser` (function) `teamserver/pkg/common/parser/parser.go:24` `func NewParser(`
- `CanIRead` (function) `teamserver/pkg/common/parser/parser.go:31` `func (p *Parser) CanIRead(`
- `ParseInt32` (function) `teamserver/pkg/common/parser/parser.go:82` `func (p *Parser) ParseInt32(`
- `ParseInt64` (function) `teamserver/pkg/common/parser/parser.go:106` `func (p *Parser) ParseInt64(`
- `ParseBool` (function) `teamserver/pkg/common/parser/parser.go:130` `func (p *Parser) ParseBool(`
- `ParsePointer` (function) `teamserver/pkg/common/parser/parser.go:154` `func (p *Parser) ParsePointer(`
- `SetBigEndian` (function) `teamserver/pkg/common/parser/parser.go:158` `func (p *Parser) SetBigEndian(`
- `ParseBytes` (function) `teamserver/pkg/common/parser/parser.go:162` `func (p *Parser) ParseBytes(`
- `ParseAtLeastBytes` (function) `teamserver/pkg/common/parser/parser.go:177` `func (p *Parser) ParseAtLeastBytes(`
- `ParseUTF16String` (function) `teamserver/pkg/common/parser/parser.go:189` `func (p *Parser) ParseUTF16String(`
- `ParseString` (function) `teamserver/pkg/common/parser/parser.go:193` `func (p *Parser) ParseString(`
- `Length` (function) `teamserver/pkg/common/parser/parser.go:197` `func (p *Parser) Length(`
- `Buffer` (function) `teamserver/pkg/common/parser/parser.go:201` `func (p *Parser) Buffer(`
- `DecryptBuffer` (function) `teamserver/pkg/common/parser/parser.go:205` `func (p *Parser) DecryptBuffer(`

## teamserver/pkg/common/util.go
Depends on: `teamserver/pkg/logger/logger.go`
- `ParseWorkingHours` (function) `teamserver/pkg/common/util.go:26` `func ParseWorkingHours(`
- `Bmp2Png` (function) `teamserver/pkg/common/util.go:76` `func Bmp2Png(`
- `DecodeUTF16` (function) `teamserver/pkg/common/util.go:99` `func DecodeUTF16(`
- `EncodeUTF16` (function) `teamserver/pkg/common/util.go:118` `func EncodeUTF16(`
- `EncodeUTF8` (function) `teamserver/pkg/common/util.go:135` `func EncodeUTF8(`
- `ByteCountSI` (function) `teamserver/pkg/common/util.go:144` `func ByteCountSI(`
- `XorCipher` (function) `teamserver/pkg/common/util.go:158` `func XorCipher(`
- `RandomString` (function) `teamserver/pkg/common/util.go:166` `func RandomString(`
- `Int32ToLittle` (function) `teamserver/pkg/common/util.go:175` `func Int32ToLittle(`
- `StripNull` (function) `teamserver/pkg/common/util.go:181` `func StripNull(`
- `PercentageChange` (function) `teamserver/pkg/common/util.go:185` `func PercentageChange(`
- `IpStringToInt32` (function) `teamserver/pkg/common/util.go:189` `func IpStringToInt32(`
- `Int32ToIpString` (function) `teamserver/pkg/common/util.go:198` `func Int32ToIpString(`
- `EpochTimeToSystemTime` (function) `teamserver/pkg/common/util.go:209` `func EpochTimeToSystemTime(`
- `GetRandomChar` (function) `teamserver/pkg/common/util.go:222` `func GetRandomChar(`
- `GeneratePipeName` (function) `teamserver/pkg/common/util.go:227` `func GeneratePipeName(` -- generate a PipeName from a name template
- `GetInterfaceIpv4Addr` (function) `teamserver/pkg/common/util.go:279` `func GetInterfaceIpv4Addr(`

## teamserver/pkg/db/agents.go
- `AgentAdd` (function) `teamserver/pkg/db/agents.go:12` `func (db *DB) AgentAdd(`
- `AgentUpdate` (function) `teamserver/pkg/db/agents.go:81` `func (db *DB) AgentUpdate(`
- `AgentHasDied` (function) `teamserver/pkg/db/agents.go:145` `func (db *DB) AgentHasDied(`
- `AgentExist` (function) `teamserver/pkg/db/agents.go:163` `func (db *DB) AgentExist(`
- `AgentRemove` (function) `teamserver/pkg/db/agents.go:192` `func (db *DB) AgentRemove(`
- `AgentAll` (function) `teamserver/pkg/db/agents.go:211` `func (db *DB) AgentAll(`

## teamserver/pkg/db/db.go
Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`
- `DatabaseNew` (function) `teamserver/pkg/db/db.go:16` `func DatabaseNew(`
- `init` (function) `teamserver/pkg/db/db.go:48` `func (db *DB) init(`
- `Existed` (function) `teamserver/pkg/db/db.go:69` `func (db *DB) Existed(`
- `Path` (function) `teamserver/pkg/db/db.go:73` `func (db *DB) Path(`

## teamserver/pkg/db/links.go
- `LinkAdd` (function) `teamserver/pkg/db/links.go:8` `func (db *DB) LinkAdd(`
- `LinkExist` (function) `teamserver/pkg/db/links.go:46` `func (db *DB) LinkExist(`
- `ParentOf` (function) `teamserver/pkg/db/links.go:75` `func (db *DB) ParentOf(`
- `LinksOf` (function) `teamserver/pkg/db/links.go:104` `func (db *DB) LinksOf(`
- `LinkRemove` (function) `teamserver/pkg/db/links.go:136` `func (db *DB) LinkRemove(`

## teamserver/pkg/db/listeners.go
- `ListenerAdd` (function) `teamserver/pkg/db/listeners.go:8` `func (db *DB) ListenerAdd(`
- `ListenerExist` (function) `teamserver/pkg/db/listeners.go:46` `func (db *DB) ListenerExist(`
- `ListenerAll` (function) `teamserver/pkg/db/listeners.go:66` `func (db *DB) ListenerAll(`
- `ListenerCount` (function) `teamserver/pkg/db/listeners.go:107` `func (db *DB) ListenerCount(`
- `ListenerNames` (function) `teamserver/pkg/db/listeners.go:126` `func (db *DB) ListenerNames(`
- `ListenerRemove` (function) `teamserver/pkg/db/listeners.go:152` `func (db *DB) ListenerRemove(`

## teamserver/pkg/events/chatlog.go
- `NewUserConnected` (function) `teamserver/pkg/events/chatlog.go:11` `func (chatLog) NewUserConnected(`
- `UserDisconnected` (function) `teamserver/pkg/events/chatlog.go:27` `func (chatLog) UserDisconnected(`

## teamserver/pkg/events/demons.go
Depends on: `teamserver/pkg/logr/logr.go`
- `NewDemon` (function) `teamserver/pkg/events/demons.go:19` `func (demons) NewDemon(`
- `DemonOutput` (function) `teamserver/pkg/events/demons.go:83` `func (demons) DemonOutput(`
- `CallBack` (function) `teamserver/pkg/events/demons.go:105` `func (demons) CallBack(`
- `MarkAs` (function) `teamserver/pkg/events/demons.go:121` `func (demons) MarkAs(`

## teamserver/pkg/events/events.go
Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`
Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/service/service.go`
- `Authenticated` (function) `teamserver/pkg/events/events.go:22` `func Authenticated(`
- `UserAlreadyExits` (function) `teamserver/pkg/events/events.go:56` `func UserAlreadyExits(`
- `UserDoNotExists` (function) `teamserver/pkg/events/events.go:72` `func UserDoNotExists(`
- `SendProfile` (function) `teamserver/pkg/events/events.go:88` `func SendProfile(`

## teamserver/pkg/events/gate.go
- `SendStageless` (function) `teamserver/pkg/events/gate.go:12` `func (g gate) SendStageless(`
- `SendConsoleMessage` (function) `teamserver/pkg/events/gate.go:30` `func (g gate) SendConsoleMessage(`

## teamserver/pkg/events/listeners.go
Depends on: `teamserver/pkg/handlers/handlers.go`
- `ListenerAdd` (function) `teamserver/pkg/events/listeners.go:15` `func (listeners) ListenerAdd(`
- `ListenerEdit` (function) `teamserver/pkg/events/listeners.go:97` `func (listeners) ListenerEdit(`
- `ListenerError` (function) `teamserver/pkg/events/listeners.go:154` `func (listeners) ListenerError(`
- `ListenerRemove` (function) `teamserver/pkg/events/listeners.go:173` `func (listeners) ListenerRemove(`
- `ListenerMark` (function) `teamserver/pkg/events/listeners.go:187` `func (listeners) ListenerMark(`

## teamserver/pkg/events/service.go
- `AgentRegister` (function) `teamserver/pkg/events/service.go:11` `func (service) AgentRegister(`
- `ListenerRegister` (function) `teamserver/pkg/events/service.go:25` `func (service) ListenerRegister(`

## teamserver/pkg/events/teamserver.go
- `Logger` (function) `teamserver/pkg/events/teamserver.go:11` `func (teamserver) Logger(`
- `Profile` (function) `teamserver/pkg/events/teamserver.go:25` `func (teamserver) Profile(`

## teamserver/pkg/handlers/external.go
Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`
- `NewExternal` (function) `teamserver/pkg/handlers/external.go:15` `func NewExternal(`
- `Start` (function) `teamserver/pkg/handlers/external.go:24` `func (e *External) Start(`
- `Request` (function) `teamserver/pkg/handlers/external.go:37` `func (e *External) Request(` -- Request The way the external c2 handles or parses the request is like the HTTP listener.

## teamserver/pkg/handlers/handlers.go
Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`
Imported by: `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/listeners.go`
- `parseAgentRequest` (function) `teamserver/pkg/handlers/handlers.go:23` `func parseAgentRequest(` -- parseAgentRequest parses the agent request and handles the given data. return 2 types.
- `handleDemonAgent` (function) `teamserver/pkg/handlers/handlers.go:56` `func handleDemonAgent(` -- handleDemonAgent parse the demon agent request return 2 types:  Response bytes.Buffer Success  bool
- `handleServiceAgent` (function) `teamserver/pkg/handlers/handlers.go:311` `func handleServiceAgent(` -- handleServiceAgent handles and parses a service agent request return 2 types:  Response bytes.Buffer Success  bool
- `notifyTaskSize` (function) `teamserver/pkg/handlers/handlers.go:349` `func notifyTaskSize(` -- notifyTaskSize notifies every connected operator client how much we send to agent.

## teamserver/pkg/handlers/http.go
Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`
- `NewConfigHttp` (function) `teamserver/pkg/handlers/http.go:24` `func NewConfigHttp(`
- `generateCertFiles` (function) `teamserver/pkg/handlers/http.go:32` `func (h *HTTP) generateCertFiles(`
- `fake404` (function) `teamserver/pkg/handlers/http.go:80` `func (h *HTTP) fake404(` -- fake nginx 404 page
- `request` (function) `teamserver/pkg/handlers/http.go:93` `func (h *HTTP) request(`
- `Start` (function) `teamserver/pkg/handlers/http.go:203` `func (h *HTTP) Start(`
- `Stop` (function) `teamserver/pkg/handlers/http.go:277` `func (h *HTTP) Stop(`

## teamserver/pkg/handlers/smb.go
Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`
- `NewPivotSmb` (function) `teamserver/pkg/handlers/smb.go:8` `func NewPivotSmb(`
- `Start` (function) `teamserver/pkg/handlers/smb.go:14` `func (s *SMB) Start(`

## teamserver/pkg/logger/global.go
- `init` (function) `teamserver/pkg/logger/global.go:11` `func init(`
- `NewLogger` (function) `teamserver/pkg/logger/global.go:15` `func NewLogger(`
- `Info` (function) `teamserver/pkg/logger/global.go:27` `func Info(`
- `Good` (function) `teamserver/pkg/logger/global.go:31` `func Good(`
- `Debug` (function) `teamserver/pkg/logger/global.go:35` `func Debug(`
- `DebugError` (function) `teamserver/pkg/logger/global.go:39` `func DebugError(`
- `Warn` (function) `teamserver/pkg/logger/global.go:43` `func Warn(`
- `Error` (function) `teamserver/pkg/logger/global.go:47` `func Error(`
- `Fatal` (function) `teamserver/pkg/logger/global.go:51` `func Fatal(`
- `Panic` (function) `teamserver/pkg/logger/global.go:55` `func Panic(`
- `SetDebug` (function) `teamserver/pkg/logger/global.go:59` `func SetDebug(`
- `ShowTime` (function) `teamserver/pkg/logger/global.go:63` `func ShowTime(`
- `SetStdOut` (function) `teamserver/pkg/logger/global.go:67` `func SetStdOut(`

## teamserver/pkg/logger/logger.go
Depends on: `teamserver/pkg/colors/colors.go`
Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`
- `FunctionTrace` (function) `teamserver/pkg/logger/logger.go:15` `func FunctionTrace(`
- `Info` (function) `teamserver/pkg/logger/logger.go:43` `func (logger *Logger) Info(`
- `Good` (function) `teamserver/pkg/logger/logger.go:52` `func (logger *Logger) Good(`
- `Debug` (function) `teamserver/pkg/logger/logger.go:61` `func (logger *Logger) Debug(`
- `DebugError` (function) `teamserver/pkg/logger/logger.go:74` `func (logger *Logger) DebugError(`
- `Warn` (function) `teamserver/pkg/logger/logger.go:87` `func (logger *Logger) Warn(`
- `Error` (function) `teamserver/pkg/logger/logger.go:96` `func (logger *Logger) Error(`
- `Fatal` (function) `teamserver/pkg/logger/logger.go:105` `func (logger *Logger) Fatal(`
- `Panic` (function) `teamserver/pkg/logger/logger.go:115` `func (logger *Logger) Panic(`
- `SetDebug` (function) `teamserver/pkg/logger/logger.go:125` `func (logger *Logger) SetDebug(`
- `ShowTime` (function) `teamserver/pkg/logger/logger.go:129` `func (logger *Logger) ShowTime(`

## teamserver/pkg/logr/demon.go
Depends on: `teamserver/pkg/logger/logger.go`
- `AddAgentInput` (function) `teamserver/pkg/logr/demon.go:15` `func (l Logr) AddAgentInput(`
- `AddAgentRaw` (function) `teamserver/pkg/logr/demon.go:50` `func (l Logr) AddAgentRaw(`
- `DemonAddOutput` (function) `teamserver/pkg/logr/demon.go:82` `func (l Logr) DemonAddOutput(`
- `DemonAddDownloadedFile` (function) `teamserver/pkg/logr/demon.go:134` `func (l Logr) DemonAddDownloadedFile(`
- `DemonSaveScreenshot` (function) `teamserver/pkg/logr/demon.go:177` `func (l Logr) DemonSaveScreenshot(`

## teamserver/pkg/logr/listener.go
- `ListenerAddKeyCert` (function) `teamserver/pkg/logr/listener.go:3` `func (l Logr) ListenerAddKeyCert(`

## teamserver/pkg/logr/logr.go
Depends on: `teamserver/pkg/logger/logger.go`
Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/events/demons.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/service/service.go`
- `NewLogr` (function) `teamserver/pkg/logr/logr.go:21` `func NewLogr(`

## teamserver/pkg/logr/server.go
Depends on: `teamserver/pkg/logger/logger.go`
- `strip` (function) `teamserver/pkg/logr/server.go:12` `func strip(`
- `ServerStdOutInit` (function) `teamserver/pkg/logr/server.go:21` `func (l Logr) ServerStdOutInit(`

## teamserver/pkg/packager/packages.go
Depends on: `teamserver/pkg/logger/logger.go`
- `NewPackager` (function) `teamserver/pkg/packager/packages.go:9` `func NewPackager(`
- `CreatePackage` (function) `teamserver/pkg/packager/packages.go:13` `func (p Packager) CreatePackage(`

## teamserver/pkg/profile/profile.go
Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`
Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/service/types.go`
- `NewProfile` (function) `teamserver/pkg/profile/profile.go:13` `func NewProfile(`
- `SetProfile` (function) `teamserver/pkg/profile/profile.go:17` `func (p *Profile) SetProfile(`
- `ServerHost` (function) `teamserver/pkg/profile/profile.go:32` `func (p *Profile) ServerHost(`
- `ServerPort` (function) `teamserver/pkg/profile/profile.go:39` `func (p *Profile) ServerPort(`
- `ListOfUsernames` (function) `teamserver/pkg/profile/profile.go:46` `func (p *Profile) ListOfUsernames(`

## teamserver/pkg/profile/yaotl/diagnostic.go
- `Error` (function) `teamserver/pkg/profile/yaotl/diagnostic.go:76` `func (d *Diagnostic) Error(` -- error implementation, so that diagnostics can be returned via APIs that normally deal in vanilla Go errors.
- `Error` (function) `teamserver/pkg/profile/yaotl/diagnostic.go:82` `func (d Diagnostics) Error(` -- error implementation, so that sets of diagnostics can be returned via APIs that normally deal in vanilla Go errors.
- `Append` (function) `teamserver/pkg/profile/yaotl/diagnostic.go:104` `func (d Diagnostics) Append(` -- Append appends a new error to a Diagnostics and return the whole Diagnostics.
- `Extend` (function) `teamserver/pkg/profile/yaotl/diagnostic.go:113` `func (d Diagnostics) Extend(` -- Extend concatenates the given Diagnostics with the receiver and returns the whole new Diagnostics.
- `HasErrors` (function) `teamserver/pkg/profile/yaotl/diagnostic.go:119` `func (d Diagnostics) HasErrors(` -- HasErrors returns true if the receiver contains any diagnostics of severity DiagError.
- `Errs` (function) `teamserver/pkg/profile/yaotl/diagnostic.go:128` `func (d Diagnostics) Errs(`

## teamserver/pkg/profile/yaotl/diagnostic_text.go
- `NewDiagnosticTextWriter` (function) `teamserver/pkg/profile/yaotl/diagnostic_text.go:34` `func NewDiagnosticTextWriter(` -- NewDiagnosticTextWriter creates a DiagnosticWriter that writes diagnostics to the given writer as formatted text.
- `WriteDiagnostic` (function) `teamserver/pkg/profile/yaotl/diagnostic_text.go:43` `func (w *diagnosticTextWriter) WriteDiagnostic(`
- `WriteDiagnostics` (function) `teamserver/pkg/profile/yaotl/diagnostic_text.go:208` `func (w *diagnosticTextWriter) WriteDiagnostics(`
- `traversalStr` (function) `teamserver/pkg/profile/yaotl/diagnostic_text.go:218` `func (w *diagnosticTextWriter) traversalStr(`
- `valueStr` (function) `teamserver/pkg/profile/yaotl/diagnostic_text.go:246` `func (w *diagnosticTextWriter) valueStr(`
- `contextString` (function) `teamserver/pkg/profile/yaotl/diagnostic_text.go:302` `func contextString(`

## teamserver/pkg/profile/yaotl/didyoumean.go
- `nameSuggestion` (function) `teamserver/pkg/profile/yaotl/didyoumean.go:16` `func nameSuggestion(` -- nameSuggestion tries to find a name from the given slice of suggested names that is close to the given name and...

## teamserver/pkg/profile/yaotl/eval_context.go
- `NewChild` (function) `teamserver/pkg/profile/yaotl/eval_context.go:17` `func (ctx *EvalContext) NewChild(` -- NewChild returns a new EvalContext that is a child of the receiver.
- `Parent` (function) `teamserver/pkg/profile/yaotl/eval_context.go:23` `func (ctx *EvalContext) Parent(` -- Parent returns the parent of the receiver, or nil if the receiver has no parent.

## teamserver/pkg/profile/yaotl/expr_call.go
- `ExprCall` (function) `teamserver/pkg/profile/yaotl/expr_call.go:14` `func ExprCall(` -- ExprCall tests if the given expression is a function call and, if so, extracts the function name and the expressions...

## teamserver/pkg/profile/yaotl/expr_list.go
- `ExprList` (function) `teamserver/pkg/profile/yaotl/expr_list.go:14` `func ExprList(` -- ExprList tests if the given expression is a static list construct and, if so, extracts the expressions that...

## teamserver/pkg/profile/yaotl/expr_map.go
- `ExprMap` (function) `teamserver/pkg/profile/yaotl/expr_map.go:14` `func ExprMap(` -- ExprMap tests if the given expression is a static map construct and, if so, extracts the expressions that represent...

## teamserver/pkg/profile/yaotl/expr_unwrap.go
- `UnwrapExpression` (function) `teamserver/pkg/profile/yaotl/expr_unwrap.go:28` `func UnwrapExpression(` -- type-assert on the physical AST types used by the underlying syntax.
- `UnwrapExpressionUntil` (function) `teamserver/pkg/profile/yaotl/expr_unwrap.go:54` `func UnwrapExpressionUntil(` -- UnwrapExpressionUntil is similar to UnwrapExpression except it gives the caller an opportunity to test each level of...

## teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go
Imported by: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go`, `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go`, `teamserver/pkg/profile/yaotl/hcldec/spec.go`, `teamserver/pkg/profile/yaotl/hclsyntax/expression.go`
- `CustomExpressionDecoderForType` (function) `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go:48` `func CustomExpressionDecoderForType(` -- CustomExpressionDecoderForType takes any cty type and returns its custom expression decoder implementation if it has...

## teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go
- `ExpressionVal` (function) `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:27` `func ExpressionVal(` -- ExpressionVal returns a new cty value of type ExpressionType, wrapping the given expression.
- `ExpressionFromVal` (function) `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:33` `func ExpressionFromVal(` -- ExpressionFromVal returns the expression encapsulated in the given value, or panics if the value is not a known...
- `ExpressionClosureVal` (function) `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:58` `func ExpressionClosureVal(` -- ExpressionClosureVal returns a new cty value of type ExpressionClosureType, wrapping the given expression closure.
- `Value` (function) `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:64` `func (c *ExpressionClosure) Value(` -- Value evaluates the closure's expression using the closure's EvalContext, returning the result.
- `ExpressionClosureFromVal` (function) `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:75` `func ExpressionClosureFromVal(` -- ExpressionClosureFromVal returns the expression closure encapsulated in the given value, or panics if the value is...
- `init` (function) `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:82` `func init(`

## teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go
- `Content` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:29` `func (b *expandBody) Content(`
- `PartialContent` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:46` `func (b *expandBody) PartialContent(`
- `extendSchema` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:85` `func (b *expandBody) extendSchema(`
- `prepareAttributes` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:121` `func (b *expandBody) prepareAttributes(`
- `expandBlocks` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:151` `func (b *expandBody) expandBlocks(`
- `expandChild` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:232` `func (b *expandBody) expandChild(`
- `JustAttributes` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:239` `func (b *expandBody) JustAttributes(`
- `MissingItemRange` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:246` `func (b *expandBody) MissingItemRange(`

## teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go
- `Variables` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go:13` `func (e exprWrap) Variables(`
- `Value` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go:33` `func (e exprWrap) Value(`
- `UnwrapExpression` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go:40` `func (e exprWrap) UnwrapExpression(` -- UnwrapExpression returns the expression being wrapped by this instance.

## teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go
- `MakeIteration` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:15` `func (s *expandSpec) MakeIteration(`
- `Object` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:24` `func (i *iteration) Object(`
- `EvalContext` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:31` `func (i *iteration) EvalContext(`
- `MakeChild` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:45` `func (i *iteration) MakeChild(`

## teamserver/pkg/profile/yaotl/ext/dynblock/public.go
- `Expand` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/public.go:42` `func Expand(` -- dynamic "child" { for_each = child_objs content { dynamic "grandchild" { for_each = child.value.children labels   =...

## teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go
- `Unknown` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:24` `func (b unknownBody) Unknown(` -- hcldec.UnkownBody impl
- `Content` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:28` `func (b unknownBody) Content(`
- `PartialContent` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:38` `func (b unknownBody) PartialContent(`
- `JustAttributes` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:49` `func (b unknownBody) JustAttributes(`
- `MissingItemRange` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:59` `func (b unknownBody) MissingItemRange(`
- `fixupContent` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:63` `func (b unknownBody) fixupContent(`
- `fixupAttrs` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:78` `func (b unknownBody) fixupAttrs(`

## teamserver/pkg/profile/yaotl/ext/dynblock/variables.go
- `WalkVariables` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:19` `func WalkVariables(` -- WalkVariables begins the recursive process of walking all expressions and nested blocks in the given body and its...
- `WalkExpandVariables` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:32` `func WalkExpandVariables(` -- WalkExpandVariables is like Variables but it includes only the variables required for successful block expansion...
- `Body` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:58` `func (c WalkVariablesChild) Body(` -- Body returns the HCL Body associated with the child node, in case the caller wants to do some sort of inspection of...
- `Visit` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:70` `func (n WalkVariablesNode) Visit(` -- Visit returns the variable traversals required for any "dynamic" blocks directly in the body associated with this...
- `extendSchema` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:172` `func (n WalkVariablesNode) extendSchema(`

## teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go
- `VariablesHCLDec` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go:16` `func VariablesHCLDec(` -- VariablesHCLDec is a wrapper around WalkVariables that uses the given hcldec specification to automatically drive...
- `ExpandVariablesHCLDec` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go:25` `func ExpandVariablesHCLDec(` -- ExpandVariablesHCLDec is like VariablesHCLDec but it includes only the minimal set of variables required to call...
- `walkVariablesWithHCLDec` (function) `teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go:30` `func walkVariablesWithHCLDec(`

## teamserver/pkg/profile/yaotl/ext/transform/error.go
- `NewErrorBody` (function) `teamserver/pkg/profile/yaotl/ext/transform/error.go:17` `func NewErrorBody(` -- NewErrorBody returns a hcl.Body that returns the given diagnostics whenever any of its content-access methods are...
- `BodyWithDiagnostics` (function) `teamserver/pkg/profile/yaotl/ext/transform/error.go:39` `func BodyWithDiagnostics(` -- BodyWithDiagnostics returns a hcl.Body that wraps another hcl.Body and emits the given diagnostics for any...
- `Content` (function) `teamserver/pkg/profile/yaotl/ext/transform/error.go:56` `func (b diagBody) Content(`
- `PartialContent` (function) `teamserver/pkg/profile/yaotl/ext/transform/error.go:68` `func (b diagBody) PartialContent(`
- `JustAttributes` (function) `teamserver/pkg/profile/yaotl/ext/transform/error.go:80` `func (b diagBody) JustAttributes(`
- `MissingItemRange` (function) `teamserver/pkg/profile/yaotl/ext/transform/error.go:92` `func (b diagBody) MissingItemRange(`
- `emptyContent` (function) `teamserver/pkg/profile/yaotl/ext/transform/error.go:104` `func (b diagBody) emptyContent(`

## teamserver/pkg/profile/yaotl/ext/transform/transform.go
- `Shallow` (function) `teamserver/pkg/profile/yaotl/ext/transform/transform.go:9` `func Shallow(` -- Shallow is equivalent to calling transformer.TransformBody(body), and is provided only for completeness of the...
- `Deep` (function) `teamserver/pkg/profile/yaotl/ext/transform/transform.go:24` `func Deep(` -- Deep applies the given transform to the given body and then wraps the result such that any descendent blocks that...
- `Content` (function) `teamserver/pkg/profile/yaotl/ext/transform/transform.go:39` `func (w deepWrapper) Content(`
- `PartialContent` (function) `teamserver/pkg/profile/yaotl/ext/transform/transform.go:45` `func (w deepWrapper) PartialContent(`
- `transformContent` (function) `teamserver/pkg/profile/yaotl/ext/transform/transform.go:51` `func (w deepWrapper) transformContent(`
- `JustAttributes` (function) `teamserver/pkg/profile/yaotl/ext/transform/transform.go:76` `func (w deepWrapper) JustAttributes(`
- `MissingItemRange` (function) `teamserver/pkg/profile/yaotl/ext/transform/transform.go:81` `func (w deepWrapper) MissingItemRange(`

## teamserver/pkg/profile/yaotl/ext/transform/transformer.go
- `TransformBody` (function) `teamserver/pkg/profile/yaotl/ext/transform/transformer.go:23` `func (f TransformerFunc) TransformBody(` -- TransformBody is an implementation of Transformer.TransformBody.
- `Chain` (function) `teamserver/pkg/profile/yaotl/ext/transform/transformer.go:31` `func Chain(` -- Chain takes a slice of transformers and returns a single new Transformer that applies each of the given transformers...
- `TransformBody` (function) `teamserver/pkg/profile/yaotl/ext/transform/transformer.go:35` `func (c chain) TransformBody(`

## teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go
Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`
- `init` (function) `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:30` `func init(`
- `try` (function) `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:61` `func try(`
- `can` (function) `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:109` `func can(`
- `dependsOnUnknowns` (function) `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:130` `func dependsOnUnknowns(` -- dependsOnUnknowns returns true if any of the variables that the given expression might access are unknown values or...

## teamserver/pkg/profile/yaotl/ext/typeexpr/get_type.go
- `getType` (function) `teamserver/pkg/profile/yaotl/ext/typeexpr/get_type.go:15` `func getType(` -- getType is the internal implementation of both Type and TypeConstraint, using the passed flag to distinguish.

## teamserver/pkg/profile/yaotl/ext/typeexpr/public.go
- `Type` (function) `teamserver/pkg/profile/yaotl/ext/typeexpr/public.go:17` `func Type(` -- Type attempts to process the given expression as a type expression and, if successful, returns the resulting type.
- `TypeConstraint` (function) `teamserver/pkg/profile/yaotl/ext/typeexpr/public.go:28` `func TypeConstraint(` -- TypeConstraint attempts to parse the given expression as a type constraint and, if successful, returns the resulting...
- `TypeString` (function) `teamserver/pkg/profile/yaotl/ext/typeexpr/public.go:44` `func TypeString(` -- TypeString returns a string rendering of the given type as it would be expected to appear in the HCL native syntax.

## teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go
Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`
- `TypeConstraintVal` (function) `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:26` `func TypeConstraintVal(` -- TypeConstraintVal constructs a cty.Value whose type is TypeConstraintType.
- `TypeConstraintFromVal` (function) `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:35` `func TypeConstraintFromVal(` -- TypeConstraintFromVal extracts the type from a cty.Value of TypeConstraintType that was previously constructed using...
- `init` (function) `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:57` `func init(`

## teamserver/pkg/profile/yaotl/ext/userfunc/decode.go
- `decodeUserFunctions` (function) `teamserver/pkg/profile/yaotl/ext/userfunc/decode.go:26` `func decodeUserFunctions(`

## teamserver/pkg/profile/yaotl/ext/userfunc/public.go
- `DecodeUserFunctions` (function) `teamserver/pkg/profile/yaotl/ext/userfunc/public.go:40` `func DecodeUserFunctions(` -- along with a new body that represents the remaining content of the given body which can be used for further processing.

## teamserver/pkg/profile/yaotl/gohcl/decode.go
- `DecodeBody` (function) `teamserver/pkg/profile/yaotl/gohcl/decode.go:30` `func DecodeBody(` -- a map, where in the former case the configuration will be decoded using struct tags and in the latter case only...
- `decodeBodyToValue` (function) `teamserver/pkg/profile/yaotl/gohcl/decode.go:39` `func decodeBodyToValue(`
- `decodeBodyToStruct` (function) `teamserver/pkg/profile/yaotl/gohcl/decode.go:51` `func decodeBodyToStruct(`
- `decodeBodyToMap` (function) `teamserver/pkg/profile/yaotl/gohcl/decode.go:234` `func decodeBodyToMap(`
- `decodeBlockToValue` (function) `teamserver/pkg/profile/yaotl/gohcl/decode.go:260` `func decodeBlockToValue(`
- `DecodeExpression` (function) `teamserver/pkg/profile/yaotl/gohcl/decode.go:306` `func DecodeExpression(` -- DecodeExpression extracts the value of the given expression into the given value.

## teamserver/pkg/profile/yaotl/gohcl/encode.go
- `EncodeIntoBody` (function) `teamserver/pkg/profile/yaotl/gohcl/encode.go:36` `func EncodeIntoBody(` -- Any fields tagged as "label" are ignored by this function.
- `EncodeAsBlock` (function) `teamserver/pkg/profile/yaotl/gohcl/encode.go:60` `func EncodeAsBlock(` -- EncodeAsBlock creates a new hclwrite.Block populated with the data from the given value, which must be a struct or...
- `populateBody` (function) `teamserver/pkg/profile/yaotl/gohcl/encode.go:85` `func populateBody(`

## teamserver/pkg/profile/yaotl/gohcl/schema.go
- `ImpliedBodySchema` (function) `teamserver/pkg/profile/yaotl/gohcl/schema.go:22` `func ImpliedBodySchema(` -- ImpliedBodySchema produces a hcl.BodySchema derived from the type of the given value, which must be a struct value...
- `getFieldTags` (function) `teamserver/pkg/profile/yaotl/gohcl/schema.go:125` `func getFieldTags(`

## teamserver/pkg/profile/yaotl/hcldec/block_labels.go
- `labelsForBlock` (function) `teamserver/pkg/profile/yaotl/hcldec/block_labels.go:12` `func labelsForBlock(`

## teamserver/pkg/profile/yaotl/hcldec/decode.go
- `decode` (function) `teamserver/pkg/profile/yaotl/hcldec/decode.go:8` `func decode(`
- `impliedType` (function) `teamserver/pkg/profile/yaotl/hcldec/decode.go:27` `func impliedType(`
- `sourceRange` (function) `teamserver/pkg/profile/yaotl/hcldec/decode.go:31` `func sourceRange(`

## teamserver/pkg/profile/yaotl/hcldec/gob.go
- `init` (function) `teamserver/pkg/profile/yaotl/hcldec/gob.go:7` `func init(`

## teamserver/pkg/profile/yaotl/hcldec/public.go
- `Decode` (function) `teamserver/pkg/profile/yaotl/hcldec/public.go:14` `func Decode(` -- Decode interprets the given body using the given specification and returns the resulting value.
- `PartialDecode` (function) `teamserver/pkg/profile/yaotl/hcldec/public.go:25` `func PartialDecode(` -- PartialDecode is like Decode except that it permits "leftover" items in the top-level body, which are returned as a...
- `ImpliedType` (function) `teamserver/pkg/profile/yaotl/hcldec/public.go:31` `func ImpliedType(` -- ImpliedType returns the value type that should result from decoding the given spec.
- `SourceRange` (function) `teamserver/pkg/profile/yaotl/hcldec/public.go:51` `func SourceRange(` -- fulfill the spec.
- `ChildBlockTypes` (function) `teamserver/pkg/profile/yaotl/hcldec/public.go:58` `func ChildBlockTypes(` -- ChildBlockTypes returns a map of all of the child block types declared by the given spec, with block type names as...

## teamserver/pkg/profile/yaotl/hcldec/schema.go
- `ImpliedSchema` (function) `teamserver/pkg/profile/yaotl/hcldec/schema.go:10` `func ImpliedSchema(` -- ImpliedSchema returns the *hcl.BodySchema implied by the given specification.

## teamserver/pkg/profile/yaotl/hcldec/variables.go
- `Variables` (function) `teamserver/pkg/profile/yaotl/hcldec/variables.go:17` `func Variables(` -- Variables processes the given body with the given spec and returns a list of the variable traversals that would be...

## teamserver/pkg/profile/yaotl/hcled/navigation.go
- `ContextString` (function) `teamserver/pkg/profile/yaotl/hcled/navigation.go:15` `func ContextString(` -- ContextString returns a string describing the context of the given byte offset, if available.
- `ContextDefRange` (function) `teamserver/pkg/profile/yaotl/hcled/navigation.go:26` `func ContextDefRange(`


Next: [API_p7.md](API_p7.md)
