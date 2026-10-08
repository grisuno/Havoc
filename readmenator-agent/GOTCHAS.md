# Gotchas

## God Nodes (high connectivity)

These files have the most connections. Changes here have high blast radius.

- `payloads/Demon/include/common/Native.h` (score: 238.60, imported by 7 files)
- `client/include/global.hpp` (score: 111.40, imported by 50 files)
- `payloads/Demon/include/Demon.h` (score: 102.40, imported by 32 files)
- `teamserver/pkg/logger/logger.go` (score: 61.20, imported by 29 files)
- `payloads/Demon/include/core/MiniStd.h` (score: 56.50, imported by 27 files)
- `payloads/Demon/include/common/Defines.h` (score: 48.70, imported by 7 files)
- `payloads/Demon/include/core/Win32.h` (score: 41.20, imported by 16 files)
- `client/include/Util/ColorText.h` (score: 36.80, imported by 16 files)
- `client/include/UserInterface/Widgets/DemonInteracted.h` (score: 33.60, imported by 14 files)
- `client/include/UserInterface/HavocUI.hpp` (score: 33.20, imported by 7 files)

## Blast Radius (change impact)

Editing these files can break the listed number of dependents. Run their tests after any change.

- `client/include/Havoc/Service.hpp` -- 2 direct, 52 total dependents
- `client/include/Util/Base.hpp` -- 4 direct, 52 total dependents
- `client/include/External.h` -- 1 direct, 51 total dependents
- `client/include/UserInterface/Widgets/FileBrowser.hpp` -- 4 direct, 51 total dependents
- `client/include/global.hpp` -- 50 direct, 50 total dependents
- `payloads/Demon/include/common/Native.h` -- 7 direct, 48 total dependents
- `payloads/Demon/include/common/Macros.h` -- 12 direct, 45 total dependents
- `payloads/Demon/include/core/Syscalls.h` -- 5 direct, 45 total dependents
- `payloads/Demon/include/core/Win32.h` -- 16 direct, 44 total dependents
- `payloads/Demon/include/core/Parser.h` -- 3 direct, 40 total dependents

## Hotspots (complexity + centrality)

- `client/include/global.hpp` -- complexity: 0.0, centrality: 1.0, combined: 0.6
- `payloads/Demon/include/Demon.h` -- complexity: 0.0, centrality: 0.9, combined: 0.5
- `payloads/Demon/include/common/Native.h` -- complexity: 1.0, centrality: 0.1, combined: 0.5
- `teamserver/pkg/logger/logger.go` -- complexity: 0.0, centrality: 0.4, combined: 0.3
- `teamserver/cmd/server/teamserver.go` -- complexity: 0.0, centrality: 0.4, combined: 0.3
- `client/include/UserInterface/HavocUI.hpp` -- complexity: 0.0, centrality: 0.4, combined: 0.2
- `client/src/UserInterface/Widgets/TeamserverTabSession.cc` -- complexity: 0.0, centrality: 0.4, combined: 0.2
- `client/src/UserInterface/HavocUi.cc` -- complexity: 0.0, centrality: 0.4, combined: 0.2
- `client/src/UserInterface/Widgets/SessionGraph.cc` -- complexity: 0.0, centrality: 0.3, combined: 0.2
- `client/include/UserInterface/Widgets/Store.hpp` -- complexity: 0.0, centrality: 0.3, combined: 0.2

## Dataflow Issues (INFERRED, review each lead)

- `client/include/Havoc/CmdLine.hpp:415` `parse` [DEAD_STORE] `argc`: `argc` assigned at line 415 but never read afterwards.
- `client/src/Havoc/PythonApi/HavocUi.cc:49` `CreateTab` [DEAD_STORE] `in_menu`: `in_menu` assigned at line 49 but never read afterwards.
- `payloads/Demon/include/common/Native.h:7469` `NtCurrentPeb` [UNINIT_USE] `ExceptionRecord`: `ExceptionRecord` may be read before initialization (declared line 7454).
- `payloads/Demon/include/common/Native.h:10097` `NtCurrentPeb` [UNINIT_USE] `NextPrefixTree`: `NextPrefixTree` may be read before initialization (declared line 10087).
- `payloads/Demon/include/common/Native.h:11186` `NtGetTickCount` [UNINIT_USE] `Next`: `Next` may be read before initialization (declared line 11103).
- `payloads/Demon/include/common/Native.h:17306` `NtGetTickCount` [UNINIT_USE] `Data`: `Data` may be read before initialization (declared line 11582).
