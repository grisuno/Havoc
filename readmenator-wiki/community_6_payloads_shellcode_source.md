# payloads/Shellcode/Source

*Community 6 | 3 files | cohesion 1.00*

## Definition

This community groups 3 file(s) rooted at `payloads/Shellcode/Source` with dominant language c (cohesion 1.00). Central symbols: `SEC`. Core file: `payloads/Shellcode/Source/Win32.c` (2 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `payloads/Shellcode/Include/Utils.h` | h | utility | 0 | no |
| `payloads/Shellcode/Source/Utils.c` | c | utility | 1 | no |
| `payloads/Shellcode/Source/Win32.c` | c | utility | 2 | no |

## Key Symbols

- `SEC` (function, `payloads/Shellcode/Source/Utils.c:4`) `SEC( text, B ) UINT_PTR HashString( LPVOID String, UINT_PTR Length )`
- `SEC` (function, `payloads/Shellcode/Source/Win32.c:5`) `SEC( text, B ) UINT_PTR LdrModulePeb( UINT_PTR hModuleHash )`
- `SEC` (function, `payloads/Shellcode/Source/Win32.c:23`) `SEC( text, B ) PVOID LdrFunctionAddr( UINT_PTR Module, UINT_PTR FunctionHash )`

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 2
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- [INFERRED] shares_context community 0 <-> 6 (strength 0.5): Inferred shared context (layer utility) with no import path between community 0 (payloads/Demon/include/core) and community 6 (payloads/Shellcode/Source).
- [INFERRED] shares_context community 2 <-> 6 (strength 0.5): Inferred shared context (layer utility) with no import path between community 2 (teamserver/cmd/server) and community 6 (payloads/Shellcode/Source).

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 3 file(s) lack file-level docs (e.g. `payloads/Shellcode/Include/Utils.h`)? What purpose do they serve?
- What would break if the most connected file in payloads/Shellcode/Source changed?
- Should payloads/Shellcode/Source be split, given cohesion 1.00?

## Sources

- `payloads/Shellcode/Include/Utils.h`
- `payloads/Shellcode/Source/Utils.c`
- `payloads/Shellcode/Source/Win32.c`
