# payloads/Shellcode/Include

*Community 5 | 3 files | cohesion 1.00*

## Definition

This community groups 3 file(s) rooted at `payloads/Shellcode/Include` with dominant language h (cohesion 1.00). Central symbols: `C_PTR`, `GET_SYMBOL`, `MemCopy`, `Modules`, `NTDLL_HASH`, `NtCurrentProcess`, `PAGE_SIZE`, `PPEB_PTR`. Core file: `payloads/Shellcode/Include/Core.h` (7 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `payloads/Shellcode/Include/Core.h` | h | utility | 7 | no |
| `payloads/Shellcode/Include/Macro.h` | h | utility | 7 | no |
| `payloads/Shellcode/Include/Win32.h` | h | utility | 0 | no |

## Key Symbols

- `PAGE_SIZE` (macro, `payloads/Shellcode/Include/Core.h:9`) `#define PAGE_SIZE`
- `MemCopy` (macro, `payloads/Shellcode/Include/Core.h:10`) `#define MemCopy`
- `NTDLL_HASH` (macro, `payloads/Shellcode/Include/Core.h:11`) `#define NTDLL_HASH`
- `SYS_LDRLOADDLL` (macro, `payloads/Shellcode/Include/Core.h:13`) `#define SYS_LDRLOADDLL`
- `SYS_NTALLOCATEVIRTUALMEMORY` (macro, `payloads/Shellcode/Include/Core.h:14`) `#define SYS_NTALLOCATEVIRTUALMEMORY`
- `SYS_NTPROTECTEDVIRTUALMEMORY` (macro, `payloads/Shellcode/Include/Core.h:15`) `#define SYS_NTPROTECTEDVIRTUALMEMORY`
- `Modules` (struct, `payloads/Shellcode/Include/Core.h:29`)
- `PPEB_PTR` (macro, `payloads/Shellcode/Include/Macro.h:5`) `#define PPEB_PTR`
- `PPEB_PTR` (macro, `payloads/Shellcode/Include/Macro.h:7`) `#define PPEB_PTR`
- `SEC` (macro, `payloads/Shellcode/Include/Macro.h:10`) `#define SEC( s, x )`
- `U_PTR` (macro, `payloads/Shellcode/Include/Macro.h:11`) `#define U_PTR( x )`
- `C_PTR` (macro, `payloads/Shellcode/Include/Macro.h:12`) `#define C_PTR( x )`
- `NtCurrentProcess` (macro, `payloads/Shellcode/Include/Macro.h:13`) `#define NtCurrentProcess()`
- `GET_SYMBOL` (macro, `payloads/Shellcode/Include/Macro.h:15`) `#define GET_SYMBOL( x )`

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 2
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- [INFERRED] duplicates community 5 <-> 7 (strength 0.6): Inferred duplicated scope: communities 5 and 7 share 11 symbols (Jaccard 0.50), e.g. `C_PTR`, `GET_SYMBOL`, `Modules`, `NTDLL_HASH`, `NtCurrentProcess`, `PPEB_PTR`. Candidate for consolidation.
- [INFERRED] shares_context community 0 <-> 5 (strength 0.5): Inferred shared context (language h and layer utility) with no import path between community 0 (payloads/Demon/include/core) and community 5 (payloads/Shellcode/Include).
- [INFERRED] shares_context community 2 <-> 5 (strength 0.5): Inferred shared context (layer utility) with no import path between community 2 (teamserver/cmd/server) and community 5 (payloads/Shellcode/Include).

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 3 file(s) lack file-level docs (e.g. `payloads/Shellcode/Include/Core.h`)? What purpose do they serve?
- What would break if the most connected file in payloads/Shellcode/Include changed?
- Should payloads/Shellcode/Include be split, given cohesion 1.00?

## Sources

- `payloads/Shellcode/Include/Core.h`
- `payloads/Shellcode/Include/Macro.h`
- `payloads/Shellcode/Include/Win32.h`
