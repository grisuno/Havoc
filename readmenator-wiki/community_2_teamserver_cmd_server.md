# teamserver/cmd/server

*Community 2 | 43 files | cohesion 1.00*

## Definition

This community groups 43 file(s) rooted at `teamserver/cmd/server` with dominant language go (cohesion 1.00). Central symbols: `AddAgentInput`, `AddAgentRaw`, `AddBytes`, `AddInt`, `AddInt32`, `AddInt64`, `AddJobToQueue`, `AddOwnSizeFirst`. Core file: `teamserver/pkg/agent/agent.go` (31 symbols). Documented purpose: Package hcl contains the main modelling types and general utility functions for HCL.  For a simple entry point into HCL, see the package in the subdirectory "hc.

## Files

### `teamserver/cmd/server` (6 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/cmd/server/agent.go` | go | utility | 19 | no |

### `teamserver/pkg/handlers` (5 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/handlers/external.go` | go | presentation | 3 | no |

### `teamserver/pkg/service` (4 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/service/agent.go` | go | business_logic | 8 | no |

### `teamserver/pkg/agent` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/agent/agent.go` | go | utility | 31 | no |

### `teamserver/pkg/events` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/events/demons.go` | go | infrastructure | 4 | no |

### `teamserver/pkg/logr` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/logr/demon.go` | go | utility | 5 | no |

### `teamserver/cmd` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/cmd/cmd.go` | go | utility | 3 | no |

### `teamserver/pkg/socks` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/socks/socks.go` | go | utility | 5 | no |

### `teamserver` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/main.go` | go | utility | 1 | no |

### `teamserver/pkg/colors` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/colors/colors.go` | go | utility | 0 | no |

### `teamserver/pkg/common` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/common/util.go` | go | utility | 17 | no |

### `teamserver/pkg/common/builder` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/common/builder/builder.go` | go | infrastructure | 20 | no |

### `teamserver/pkg/common/certs` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/common/certs/https.go` | go | presentation | 12 | no |

### `teamserver/pkg/common/crypt` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/common/crypt/aes.go` | go | utility | 1 | no |

### `teamserver/pkg/common/packer` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/common/packer/packer.go` | go | utility | 13 | no |

### `teamserver/pkg/db` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/db/db.go` | go | utility | 5 | no |

### `teamserver/pkg/logger` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/logger/logger.go` | go | infrastructure | 12 | no |

### `teamserver/pkg/packager` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/packager/packages.go` | go | utility | 2 | no |

### `teamserver/pkg/profile` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/profile/profile.go` | go | utility | 6 | no |

### `teamserver/pkg/profile/yaotl` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/profile/yaotl/doc.go` | go | utility | 0 | yes |

*... and 23 more files in this community.*


## Key Symbols

- `init` (function, `teamserver/cmd/cmd.go:29`) `func init(` - init all flags
- `teamserverFunc` (function, `teamserver/cmd/cmd.go:47`) `func teamserverFunc(`
- `startMenu` (function, `teamserver/cmd/cmd.go:61`) `func startMenu(`
- `AgentUpdate` (function, `teamserver/cmd/server/agent.go:16`) `func (t *Teamserver) AgentUpdate(`
- `Died` (function, `teamserver/cmd/server/agent.go:23`) `func (t *Teamserver) Died(`
- `UnlinkFromAll` (function, `teamserver/cmd/server/agent.go:30`) `func (t *Teamserver) UnlinkFromAll(`
- `ParentOf` (function, `teamserver/cmd/server/agent.go:53`) `func (t *Teamserver) ParentOf(`
- `LinksOf` (function, `teamserver/cmd/server/agent.go:60`) `func (t *Teamserver) LinksOf(`
- `LinkAdd` (function, `teamserver/cmd/server/agent.go:66`) `func (t *Teamserver) LinkAdd(`
- `LinkRemove` (function, `teamserver/cmd/server/agent.go:78`) `func (t *Teamserver) LinkRemove(`
- `AgentHasDied` (function, `teamserver/cmd/server/agent.go:102`) `func (t *Teamserver) AgentHasDied(`
- `AgentAdd` (function, `teamserver/cmd/server/agent.go:108`) `func (t *Teamserver) AgentAdd(`
- `AgentSendNotify` (function, `teamserver/cmd/server/agent.go:123`) `func (t *Teamserver) AgentSendNotify(`
- `AgentCallbackSize` (function, `teamserver/cmd/server/agent.go:138`) `func (t *Teamserver) AgentCallbackSize(`
- `AgentInstance` (function, `teamserver/cmd/server/agent.go:155`) `func (t *Teamserver) AgentInstance(`
- `AgentLastTimeCalled` (function, `teamserver/cmd/server/agent.go:166`) `func (t *Teamserver) AgentLastTimeCalled(`
- `AgentExist` (function, `teamserver/cmd/server/agent.go:183`) `func (t *Teamserver) AgentExist(`
- `AgentConsole` (function, `teamserver/cmd/server/agent.go:198`) `func (t *Teamserver) AgentConsole(`
- `PythonModuleCallback` (function, `teamserver/cmd/server/agent.go:208`) `func (t *Teamserver) PythonModuleCallback(`
- `AgentCallback` (function, `teamserver/cmd/server/agent.go:220`) `func (t *Teamserver) AgentCallback(`
- `SendLogs` (function, `teamserver/cmd/server/agent.go:233`) `func (t *Teamserver) SendLogs(`
- `GetDotNetPipeTemplate` (function, `teamserver/cmd/server/agent.go:237`) `func (t *Teamserver) GetDotNetPipeTemplate(`
- `DispatchEvent` (function, `teamserver/cmd/server/dispatch.go:20`) `func (t *Teamserver) DispatchEvent(`
- `ListenerStart` (function, `teamserver/cmd/server/listener.go:19`) `func (t *Teamserver) ListenerStart(`
- `ListenerExist` (function, `teamserver/cmd/server/listener.go:113`) `func (t *Teamserver) ListenerExist(`
- `ListenerGetInfo` (function, `teamserver/cmd/server/listener.go:124`) `func (t *Teamserver) ListenerGetInfo(`
- `ListenerRemove` (function, `teamserver/cmd/server/listener.go:144`) `func (t *Teamserver) ListenerRemove(`
- `ListenerEdit` (function, `teamserver/cmd/server/listener.go:192`) `func (t *Teamserver) ListenerEdit(`
- `ListenerAdd` (function, `teamserver/cmd/server/listener.go:220`) `func (t *Teamserver) ListenerAdd(` - ListenerAdd creates a package for the client that a new listener has been added.
- `ListenerServiceExc2Add` (function, `teamserver/cmd/server/listener.go:337`) `func (t *Teamserver) ListenerServiceExc2Add(` - ListenerServiceExc2Add adds an external c2 listener that has been started from a service script to t

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 83
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- [INFERRED] shares_context community 0 <-> 2 (strength 0.5): Inferred shared context (layer utility) with no import path between community 0 (payloads/Demon/include/core) and community 2 (teamserver/cmd/server).
- [INFERRED] shares_context community 2 <-> 4 (strength 0.5): Inferred shared context (language go and layer utility) with no import path between community 2 (teamserver/cmd/server) and community 4 (teamserver/pkg/profile/yaotl/ext/customdecode).
- [INFERRED] shares_context community 2 <-> 5 (strength 0.5): Inferred shared context (layer utility) with no import path between community 2 (teamserver/cmd/server) and community 5 (payloads/Shellcode/Include).
- [INFERRED] shares_context community 2 <-> 6 (strength 0.5): Inferred shared context (layer utility) with no import path between community 2 (teamserver/cmd/server) and community 6 (payloads/Shellcode/Source).
- [INFERRED] shares_context community 2 <-> 7 (strength 0.5): Inferred shared context (layer utility) with no import path between community 2 (teamserver/cmd/server) and community 7 (payloads/DllLdr/Include).
- [INFERRED] shares_context community 2 <-> 8 (strength 0.5): Inferred shared context (language go and layer utility) with no import path between community 2 (teamserver/cmd/server) and community 8 (teamserver/pkg/profile/yaotl/hclsyntax).
- [INFERRED] shares_context community 2 <-> 9 (strength 0.5): Inferred shared context (language go and layer utility) with no import path between community 2 (teamserver/cmd/server) and community 9 (orphans).

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 41 file(s) lack file-level docs (e.g. `teamserver/cmd/cmd.go`)? What purpose do they serve?
- What would break if the most connected file in teamserver/cmd/server changed?
- Should teamserver/cmd/server be split, given cohesion 1.00?

## Sources

- `teamserver/cmd/cmd.go`
- `teamserver/cmd/server.go`
- `teamserver/cmd/server/agent.go`
- `teamserver/cmd/server/dispatch.go`
- `teamserver/cmd/server/listener.go`
- `teamserver/cmd/server/service.go`
- `teamserver/cmd/server/teamserver.go`
- `teamserver/cmd/server/types.go`
- `teamserver/main.go`
- `teamserver/pkg/agent/agent.go`
- `teamserver/pkg/agent/demons.go`
- `teamserver/pkg/agent/types.go`
- `teamserver/pkg/colors/colors.go`
- `teamserver/pkg/common/builder/builder.go`
- `teamserver/pkg/common/certs/https.go`
- `teamserver/pkg/common/crypt/aes.go`
- `teamserver/pkg/common/packer/packer.go`
- `teamserver/pkg/common/util.go`
- `teamserver/pkg/db/db.go`
- `teamserver/pkg/events/demons.go`
- *... and 23 more*
