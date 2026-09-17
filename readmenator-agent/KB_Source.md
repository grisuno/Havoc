# Subsystem: Source

## payloads/Shellcode/Source/Entry.c
- Layer: utility
- Language: c
- Symbols:
  - `SEC` (function, line 11) `SEC( text, B ) VOID Entry( VOID )`
  - `KaynLdrReloc` (function, line 104) `VOID KaynLdrReloc( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir, DWORD KHdrSize )`
  - `IMAGE_REL_TYPE` (macro, line 6) `#define IMAGE_REL_TYPE`
  - `IMAGE_REL_TYPE` (macro, line 8) `#define IMAGE_REL_TYPE`

## payloads/Shellcode/Source/Utils.c
- Layer: utility
- Language: c
- Symbols:
  - `SEC` (function, line 4) `SEC( text, B ) UINT_PTR HashString( LPVOID String, UINT_PTR Length )`
- Depends on: `payloads/Shellcode/Include/Utils.h`

## payloads/Shellcode/Source/Win32.c
- Layer: utility
- Language: c
- Symbols:
  - `SEC` (function, line 5) `SEC( text, B ) UINT_PTR LdrModulePeb( UINT_PTR hModuleHash )`
  - `SEC` (function, line 23) `SEC( text, B ) PVOID LdrFunctionAddr( UINT_PTR Module, UINT_PTR FunctionHash )`
- Depends on: `payloads/Shellcode/Include/Utils.h`
