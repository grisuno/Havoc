# Subsystem: Source

## payloads/Shellcode/Source/Entry.c
- Layer: utility
- Doc: include <Core.h> include <Win32.h> include <ntdef.h>  ifdef _WIN64 define IMAGE_REL_TYPE IMAGE_REL_BASED_DIR64 else defi
- Language: c
- Symbols:
  - `SEC` (function, line 10) `SEC( text, B ) VOID Entry( VOID )`
  - `KaynLdrReloc` (function, line 103) `VOID KaynLdrReloc( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir, DWORD KHdrSize )`
  - `IMAGE_REL_TYPE` (macro, line 6)
  - `IMAGE_REL_TYPE` (macro, line 8)

## payloads/Shellcode/Source/Utils.c
- Layer: utility
- Doc: include <Utils.h> include <Macro.h>
- Language: c
- Symbols:
  - `SEC` (function, line 3) `SEC( text, B ) UINT_PTR HashString( LPVOID String, UINT_PTR Length )`

## payloads/Shellcode/Source/Win32.c
- Layer: utility
- Doc: include <Win32.h> include <Utils.h> include <winternl.h>
- Language: c
- Symbols:
  - `SEC` (function, line 4) `SEC( text, B ) UINT_PTR LdrModulePeb( UINT_PTR hModuleHash )`
  - `SEC` (function, line 22) `SEC( text, B ) PVOID LdrFunctionAddr( UINT_PTR Module, UINT_PTR FunctionHash )`
