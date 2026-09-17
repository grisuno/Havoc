# Subsystem: profile

## teamserver/pkg/profile/config.go
- Layer: infrastructure
- Language: go
- Symbols:
  - `HavocConfig` (struct, line 3)
  - `WebHookDiscordConfig` (struct, line 12)
  - `WebHookConfig` (struct, line 18)
  - `BuildConfig` (struct, line 22)
  - `ServiceConfig` (struct, line 28)
  - `ServerProfile` (struct, line 33)
  - `OperatorsBlock` (struct, line 42)
  - `UsersBlock` (struct, line 46)
  - `Listeners` (struct, line 51)
  - `ListenerHTTP` (struct, line 57)
  - `ListenerSMB` (struct, line 87)
  - `ListenerExternal` (struct, line 97)
  - `ListenerHttpResponse` (struct, line 102)
  - `ListenerHttpProxy` (struct, line 106)
  - `ListenerHttpCerts` (struct, line 113)
  - `HeaderBlock` (struct, line 118)
  - `Binary` (struct, line 127)
  - `ProcessInjectionBlock` (struct, line 134)
  - `Demon` (struct, line 139)

## teamserver/pkg/profile/profile.go
- Layer: utility
- Language: go
- Symbols:
  - `NewProfile` (function, line 13) `func NewProfile(`
  - `SetProfile` (function, line 17) `func (p *Profile) SetProfile(`
  - `ServerHost` (function, line 32) `func (p *Profile) ServerHost(`
  - `ServerPort` (function, line 39) `func (p *Profile) ServerPort(`
  - `ListOfUsernames` (function, line 46) `func (p *Profile) ListOfUsernames(`
  - `Profile` (struct, line 9)
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/service/types.go`
