# Subsystem: socks

## teamserver/pkg/socks/socks.go
- Layer: utility
- Language: go
- Symbols:
  - `NewSocks` (function, line 17) `func NewSocks(`
  - `SetHandler` (function, line 29) `func (s *Socks) SetHandler(`
  - `Start` (function, line 35) `func (s *Socks) Start(`
  - `Close` (function, line 62) `func (s *Socks) Close(`
  - `Socks` (struct, line 9)
- Imported by: `teamserver/pkg/agent/demons.go`, `teamserver/pkg/agent/types.go`

## teamserver/pkg/socks/util.go
- Layer: utility
- Language: go
- Symbols:
  - `SubNegotiationClient` (function, line 70) `func SubNegotiationClient(`
  - `ReadSocksHeader` (function, line 114) `func ReadSocksHeader(`
  - `CreateResponsePackage` (function, line 239) `func CreateResponsePackage(`
  - `SendConnectSuccess` (function, line 255) `func SendConnectSuccess(`
  - `SendAddressTypeNotSupported` (function, line 260) `func SendAddressTypeNotSupported(`
  - `SendCommandNotSupported` (function, line 265) `func SendCommandNotSupported(`
  - `SendConnectFailure` (function, line 270) `func SendConnectFailure(`
  - `SocksHeader` (struct, line 55)
  - `NegotiationHeader` (struct, line 64)
- Depends on: `teamserver/pkg/logger/logger.go`
