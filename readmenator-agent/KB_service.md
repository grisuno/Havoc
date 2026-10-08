# Subsystem: service

## teamserver/pkg/service/agent.go
- Layer: business_logic
- Language: go
- Symbols:
  - `NewAgentService` (function, line 45) `func NewAgentService(`
  - `Json` (function, line 58) `func (a *AgentService) Json(`
  - `SendTask` (function, line 67) `func (a *AgentService) SendTask(`
  - `SendResponse` (function, line 87) `func (a *AgentService) SendResponse(`
  - `SendAgentBuildRequest` (function, line 140) `func (a *AgentService) SendAgentBuildRequest(`
  - `CommandParam` (struct, line 13)
  - `Command` (struct, line 19)
  - `AgentService` (struct, line 28)
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/utils/utils.go`

## teamserver/pkg/service/external.go
- Layer: business_logic
- Language: go

## teamserver/pkg/service/listener.go
- Layer: business_logic
- Language: go
- Symbols:
  - `Start` (function, line 17) `func (l *ListenerService) Start(`
  - `Json` (function, line 37) `func (l *ListenerService) Json(`
  - `ListenerService` (struct, line 8)
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/service/service.go
- Layer: business_logic
- Language: go
- Symbols:
  - `NewService` (function, line 27) `func NewService(`
  - `Start` (function, line 35) `func (s *Service) Start(`
  - `handleConnection` (function, line 50) `func (s *Service) handleConnection(`
  - `authenticate` (function, line 75) `func (s *Service) authenticate(`
  - `routine` (function, line 144) `func (s *Service) routine(`
  - `dispatch` (function, line 166) `func (s *Service) dispatch(`
  - `AgentExist` (function, line 703) `func (s *Service) AgentExist(`
  - `ClientClose` (function, line 713) `func (s *Service) ClientClose(`
  - `ListenerExist` (function, line 763) `func (s *Service) ListenerExist(`
  - `ListenerAdd` (function, line 775) `func (s *Service) ListenerAdd(`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

## teamserver/pkg/service/types.go
- Layer: business_logic
- Language: go
- Symbols:
  - `WriteJson` (function, line 69) `func (c *ClientService) WriteJson(`
  - `ClientService` (struct, line 13)
  - `Teamserver` (interface, line 19)
  - `ConfigService` (struct, line 30)
  - `Service` (struct, line 36)
- Depends on: `teamserver/pkg/profile/profile.go`
