# payloads/DllLdr/Include

*Community 7 | 2 files | cohesion 1.00*

## Definition

This community groups 2 file(s) rooted at `payloads/DllLdr/Include` with dominant language h (cohesion 1.00). Central symbols: `C_PTR`, `DLLEXPORT`, `DLL_QUERY_HMODULE`, `FORCE_INLINE`, `GET_SYMBOL`, `HASH_KEY`, `IMAGE_REL_TYPE`, `Modules`. Core file: `payloads/DllLdr/Include/Core.h` (16 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `payloads/DllLdr/Include/Core.h` | h | utility | 16 | no |
| `payloads/DllLdr/Include/Macro.h` | h | utility | 8 | no |

## Key Symbols

- `NTDLL_HASH` (macro, `payloads/DllLdr/Include/Core.h:5`) `#define NTDLL_HASH`
- `SYS_LDRLOADDLL` (macro, `payloads/DllLdr/Include/Core.h:7`) `#define SYS_LDRLOADDLL`
- `SYS_NTALLOCATEVIRTUALMEMORY` (macro, `payloads/DllLdr/Include/Core.h:8`) `#define SYS_NTALLOCATEVIRTUALMEMORY`
- `SYS_NTPROTECTEDVIRTUALMEMORY` (macro, `payloads/DllLdr/Include/Core.h:9`) `#define SYS_NTPROTECTEDVIRTUALMEMORY`
- `SYS_NTFLUSHINSTRUCTIONCACHE` (macro, `payloads/DllLdr/Include/Core.h:10`) `#define SYS_NTFLUSHINSTRUCTIONCACHE`
- `DLLEXPORT` (macro, `payloads/DllLdr/Include/Core.h:12`) `#define DLLEXPORT`
- `NAKED` (macro, `payloads/DllLdr/Include/Core.h:13`) `#define NAKED`
- `FORCE_INLINE` (macro, `payloads/DllLdr/Include/Core.h:14`) `#define FORCE_INLINE`
- `WIN32_FUNC` (macro, `payloads/DllLdr/Include/Core.h:15`) `#define WIN32_FUNC( x )`
- `U_PTR` (macro, `payloads/DllLdr/Include/Core.h:17`) `#define U_PTR( x )`
- `C_PTR` (macro, `payloads/DllLdr/Include/Core.h:18`) `#define C_PTR( x )`
- `RVA2VA` (macro, `payloads/DllLdr/Include/Core.h:19`) `#define RVA2VA(type, base, rva)`
- `DLL_QUERY_HMODULE` (macro, `payloads/DllLdr/Include/Core.h:21`) `#define DLL_QUERY_HMODULE`
- `IMAGE_REL_TYPE` (macro, `payloads/DllLdr/Include/Core.h:24`) `#define IMAGE_REL_TYPE`
- `IMAGE_REL_TYPE` (macro, `payloads/DllLdr/Include/Core.h:26`) `#define IMAGE_REL_TYPE`
- `Modules` (struct, `payloads/DllLdr/Include/Core.h:36`)
- `HASH_KEY` (macro, `payloads/DllLdr/Include/Macro.h:4`) `#define HASH_KEY`
- `PPEB_PTR` (macro, `payloads/DllLdr/Include/Macro.h:7`) `#define PPEB_PTR`
- `PPEB_PTR` (macro, `payloads/DllLdr/Include/Macro.h:9`) `#define PPEB_PTR`
- `SEC` (macro, `payloads/DllLdr/Include/Macro.h:12`) `#define SEC( s, x )`
- `U_PTR` (macro, `payloads/DllLdr/Include/Macro.h:13`) `#define U_PTR( x )`
- `C_PTR` (macro, `payloads/DllLdr/Include/Macro.h:14`) `#define C_PTR( x )`
- `NtCurrentProcess` (macro, `payloads/DllLdr/Include/Macro.h:15`) `#define NtCurrentProcess()`
- `GET_SYMBOL` (macro, `payloads/DllLdr/Include/Macro.h:17`) `#define GET_SYMBOL( x )`

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 1
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- [INFERRED] duplicates community 5 <-> 7 (strength 0.6): Inferred duplicated scope: communities 5 and 7 share 11 symbols (Jaccard 0.50), e.g. `C_PTR`, `GET_SYMBOL`, `Modules`, `NTDLL_HASH`, `NtCurrentProcess`, `PPEB_PTR`. Candidate for consolidation.
- [INFERRED] shares_context community 0 <-> 7 (strength 0.5): Inferred shared context (language h and layer utility) with no import path between community 0 (payloads/Demon/include/core) and community 7 (payloads/DllLdr/Include).
- [INFERRED] shares_context community 2 <-> 7 (strength 0.5): Inferred shared context (layer utility) with no import path between community 2 (teamserver/cmd/server) and community 7 (payloads/DllLdr/Include).

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 2 file(s) lack file-level docs (e.g. `payloads/DllLdr/Include/Core.h`)? What purpose do they serve?
- What would break if the most connected file in payloads/DllLdr/Include changed?
- Should payloads/DllLdr/Include be split, given cohesion 1.00?

## Sources

- `payloads/DllLdr/Include/Core.h`
- `payloads/DllLdr/Include/Macro.h`
