# Second Brain

*Last synthesized: 2026-10-07 | 379 files | 10 concept pages | offline, zero tokens*

> Raw sources -> readmenator wiki -> links (Karpathy LLM Wiki Pattern, deterministic).
> Start here, then open one community page. Prefer grep over full reads.

## Vault Overview

The codebase centres on `Native.h`, `global.hpp`, `Demon.h`. Architecturally it is 5 layers, dominant utility (225 files) across 10 import-based communities. Recorded risk surface: 0 security findings and 0 dependency cycles.

Surprising tissue lives between payloads/Demon/include/core, client/include/UserInterface/Widgets, teamserver/cmd/server: 1 extracted cross-community imports and 19 inferred bridges. Follow `connections.json` sorted by strength before refactoring.

Open work clusters around documentation (15% file coverage), 0 security findings, 20 taint paths, and 5 suggested exploration questions in `queries.md`.

## Stats

| Metric | Value |
|--------|-------|
| Files | 379 |
| Symbols | 6058 |
| Resolved imports | 522 |
| Languages | asm, c, cc, cpp, go, h, hpp, py, rb, s, sh |
| Communities | 10 |
| Doc coverage | 15% (58/379 files) |
| Security findings | 0 |
| Estimated read cost | ~62493 tokens (chars/4, offline so $0) |
| Large files (>256KB, maybe generated) | 1: `Native.h` |

## Reading Order

1. Skim Stats and God Nodes below for blast radius.
2. Open the largest community page first, then follow Connections.
3. Use `queries.md` for the next question; log the answer there.

```
grep -rn '<keyword>' index.md community_*.md
readmenator query "<question>" --target readmenator_Havoc_q3x8po8p
```

## Concept Wiki

- [payloads/Demon/include/core (67 files, cohesion 1.00)](./community_0_payloads_demon_include_core.md)
- [client/include/UserInterface/Widgets (64 files, cohesion 0.86)](./community_1_client_include_userinterface_widgets.md)
- [teamserver/cmd/server (43 files, cohesion 1.00)](./community_2_teamserver_cmd_server.md)
- [client/include/Havoc/PythonApi/UI (20 files, cohesion 0.50)](./community_3_client_include_havoc_pythonapi_ui.md)
- [teamserver/pkg/profile/yaotl/ext/customdecode (5 files, cohesion 1.00)](./community_4_teamserver_pkg_profile_yaotl_ext_customdecode.md)
- [payloads/Shellcode/Include (3 files, cohesion 1.00)](./community_5_payloads_shellcode_include.md)
- [payloads/Shellcode/Source (3 files, cohesion 1.00)](./community_6_payloads_shellcode_source.md)
- [payloads/DllLdr/Include (2 files, cohesion 1.00)](./community_7_payloads_dllldr_include.md)
- [teamserver/pkg/profile/yaotl/hclsyntax (2 files, cohesion 1.00)](./community_8_teamserver_pkg_profile_yaotl_hclsyntax.md)
- [orphans (170 files, cohesion 0.00)](./community_9_orphans.md)

## God Nodes

| File | Score |
|------|-------|
| `payloads/Demon/include/common/Native.h` | 238.6 (large, maybe generated) |
| `client/include/global.hpp` | 111.4 |
| `payloads/Demon/include/Demon.h` | 102.4 |
| `teamserver/pkg/logger/logger.go` | 61.2 |
| `payloads/Demon/include/core/MiniStd.h` | 56.5 |

## Strongest Connections

- 3 -> 1: depends_on (strength 0.9, EXTRACTED)
- 5 -> 7: duplicates (strength 0.6, INFERRED)
- 1 -> 3: bridges (strength 0.5, INFERRED)
- 1 -> 3: bridges (strength 0.5, INFERRED)
- 1 -> 3: bridges (strength 0.5, INFERRED)
- 1 -> 3: bridges (strength 0.5, INFERRED)
- 1 -> 3: bridges (strength 0.5, INFERRED)
- 0 -> 2: shares_context (strength 0.5, INFERRED)
- 0 -> 4: shares_context (strength 0.5, INFERRED)
- 0 -> 5: shares_context (strength 0.5, INFERRED)

## Navigation Tips

- Obsidian Graph View works: every community page links back here.
- `connections.json` is machine-readable for GraphRAG pipelines.
- `REPORT.md` states what was extracted vs inferred and current limits.
- Regenerate offline: `readmenator . --rebuild` (no network, no tokens).
