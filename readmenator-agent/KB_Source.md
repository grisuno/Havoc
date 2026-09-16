# Subsystem: Source

## payloads/Shellcode/Source/Entry.c
- Layer: utility
- Doc: include <Core.h> include <Win32.h> include <ntdef.h>  ifdef _WIN64 define IMAGE_REL_TYPE IMAGE_REL_BASED_DIR64 else defi
- Language: c
- Symbols:
  - `SEC` (function, line 10) `SEC( text, B ) VOID Entry( VOID )`
  - `KaynLdrReloc` (function, line 103) `VOID KaynLdrReloc( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir, DWORD KHdrSize )`
  - `MemCopy` (function, line 50) `MemCopy( C_PTR( KVirtualMemory + SecHeader[ i ].VirtualAddress - KHdrSize ), // Section New Memory C_PTR( KaynLibraryLdr + SecHeader[ i ].PointerToRawData ), // Section Raw Data SecHeader[ i ].SizeOfR`
  - `BOOL` (function, line 99) `BOOL ( WINAPI *KaynDllMain ) ( PVOID, DWORD, PVOID ) = C_PTR( KVirtualMemory + NtHeaders->OptionalHeader.AddressOfEntryPoint - KHdrSize );`
  - `KaynDllMain` (function, line 100) `KaynDllMain( KVirtualMemory, DLL_PROCESS_ATTACH, &KaynArgs );`
  - `IMAGE_REL_TYPE` (macro, line 6) `#define IMAGE_REL_TYPE`
  - `IMAGE_REL_TYPE` (macro, line 8) `#define IMAGE_REL_TYPE`

## payloads/Shellcode/Source/Utils.c
- Layer: utility
- Doc: include <Utils.h> include <Macro.h>
- Language: c
- Symbols:
  - `SEC` (function, line 3) `SEC( text, B ) UINT_PTR HashString( LPVOID String, UINT_PTR Length )`
- Depends on: `payloads/Shellcode/Include/Utils.h`

## payloads/Shellcode/Source/Win32.c
- Layer: utility
- Doc: include <Win32.h> include <Utils.h> include <winternl.h>
- Language: c
- Symbols:
  - `SEC` (function, line 4) `SEC( text, B ) UINT_PTR LdrModulePeb( UINT_PTR hModuleHash )`
  - `SEC` (function, line 22) `SEC( text, B ) PVOID LdrFunctionAddr( UINT_PTR Module, UINT_PTR FunctionHash )`
- Depends on: `payloads/Shellcode/Include/Utils.h`
