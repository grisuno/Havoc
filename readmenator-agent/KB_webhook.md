# Subsystem: webhook

## teamserver/pkg/webhook/discord.go
- Layer: infrastructure
- Language: go
- Symbols:
  - `Message` (struct, line 3)
  - `Embed` (struct, line 10)
  - `Author` (struct, line 22)
  - `Field` (struct, line 28)
  - `Thumbnail` (struct, line 34)
  - `Image` (struct, line 38)
  - `Footer` (struct, line 42)

## teamserver/pkg/webhook/webhook.go
- Layer: utility
- Language: go
- Symbols:
  - `StringPtr` (function, line 20) `func StringPtr(`
  - `BoolPtr` (function, line 24) `func BoolPtr(`
  - `NewWebHook` (function, line 28) `func NewWebHook(`
  - `NewAgent` (function, line 32) `func (w *WebHook) NewAgent(`
  - `SetDiscord` (function, line 134) `func (w *WebHook) SetDiscord(`
  - `WebHook` (struct, line 12)
- Depends on: `teamserver/pkg/handlers/http.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`
