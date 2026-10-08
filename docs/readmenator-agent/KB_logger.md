# Subsystem: logger

## teamserver/pkg/logger/global.go
- Layer: infrastructure
- Language: go
- Symbols:
  - `init` (function, line 11) `func init(`
  - `NewLogger` (function, line 15) `func NewLogger(`
  - `Info` (function, line 27) `func Info(`
  - `Good` (function, line 31) `func Good(`
  - `Debug` (function, line 35) `func Debug(`
  - `DebugError` (function, line 39) `func DebugError(`
  - `Warn` (function, line 43) `func Warn(`
  - `Error` (function, line 47) `func Error(`
  - `Fatal` (function, line 51) `func Fatal(`
  - `Panic` (function, line 55) `func Panic(`
  - `SetDebug` (function, line 59) `func SetDebug(`
  - `ShowTime` (function, line 63) `func ShowTime(`
  - `SetStdOut` (function, line 67) `func SetStdOut(`

## teamserver/pkg/logger/logger.go
- Layer: infrastructure
- Language: go
- Symbols:
  - `FunctionTrace` (function, line 15) `func FunctionTrace(`
  - `Info` (function, line 43) `func (logger *Logger) Info(`
  - `Good` (function, line 52) `func (logger *Logger) Good(`
  - `Debug` (function, line 61) `func (logger *Logger) Debug(`
  - `DebugError` (function, line 74) `func (logger *Logger) DebugError(`
  - `Warn` (function, line 87) `func (logger *Logger) Warn(`
  - `Error` (function, line 96) `func (logger *Logger) Error(`
  - `Fatal` (function, line 105) `func (logger *Logger) Fatal(`
  - `Panic` (function, line 115) `func (logger *Logger) Panic(`
  - `SetDebug` (function, line 125) `func (logger *Logger) SetDebug(`
  - `ShowTime` (function, line 129) `func (logger *Logger) ShowTime(`
  - `Logger` (struct, line 34)
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`
