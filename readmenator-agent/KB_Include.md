# Subsystem: Include

## payloads/DllLdr/Include/Core.h
- Layer: utility
- Language: h
- Symbols:
  - `Modules` (struct, line 36)
  - `NTDLL_HASH` (macro, line 5) `#define NTDLL_HASH`
  - `SYS_LDRLOADDLL` (macro, line 7) `#define SYS_LDRLOADDLL`
  - `SYS_NTALLOCATEVIRTUALMEMORY` (macro, line 8) `#define SYS_NTALLOCATEVIRTUALMEMORY`
  - `SYS_NTPROTECTEDVIRTUALMEMORY` (macro, line 9) `#define SYS_NTPROTECTEDVIRTUALMEMORY`
  - `SYS_NTFLUSHINSTRUCTIONCACHE` (macro, line 10) `#define SYS_NTFLUSHINSTRUCTIONCACHE`
  - `DLLEXPORT` (macro, line 12) `#define DLLEXPORT`
  - `NAKED` (macro, line 13) `#define NAKED`
  - `FORCE_INLINE` (macro, line 14) `#define FORCE_INLINE`
  - `WIN32_FUNC` (macro, line 15) `#define WIN32_FUNC( x )`
  - `U_PTR` (macro, line 17) `#define U_PTR( x )`
  - `C_PTR` (macro, line 18) `#define C_PTR( x )`
  - `RVA2VA` (macro, line 19) `#define RVA2VA(type, base, rva)`
  - `DLL_QUERY_HMODULE` (macro, line 21) `#define DLL_QUERY_HMODULE`
  - `IMAGE_REL_TYPE` (macro, line 24) `#define IMAGE_REL_TYPE`
  - `IMAGE_REL_TYPE` (macro, line 26) `#define IMAGE_REL_TYPE`
- Depends on: `payloads/DllLdr/Include/Macro.h`

## payloads/DllLdr/Include/Macro.h
- Layer: utility
- Language: h
- Symbols:
  - `HASH_KEY` (macro, line 4) `#define HASH_KEY`
  - `PPEB_PTR` (macro, line 7) `#define PPEB_PTR`
  - `PPEB_PTR` (macro, line 9) `#define PPEB_PTR`
  - `SEC` (macro, line 12) `#define SEC( s, x )`
  - `U_PTR` (macro, line 13) `#define U_PTR( x )`
  - `C_PTR` (macro, line 14) `#define C_PTR( x )`
  - `NtCurrentProcess` (macro, line 15) `#define NtCurrentProcess()`
  - `GET_SYMBOL` (macro, line 17) `#define GET_SYMBOL( x )`
- Imported by: `payloads/DllLdr/Include/Core.h`

## payloads/DllLdr/Include/Native.h
- Layer: utility
- Language: h
- Symbols:
  - `_myUNICODE_STRING` (struct, line 2)
  - `_CURDIR` (struct, line 9)
  - `_PEB_LDR_DATA` (struct, line 28)
  - `_PEB` (struct, line 41)
  - `_LDR_DATA_TABLE_ENTRY` (struct, line 173)
  - `Length` (type_alias, line 1) `typedef struct _myUNICODE_STRING { USHORT Length;`
  - `DosPath` (type_alias, line 8) `typedef struct _CURDIR { myUNICODE_STRING DosPath;`
  - `GDI_HANDLE_BUFFER32` (type_alias, line 23) `typedef ULONG GDI_HANDLE_BUFFER32[GDI_HANDLE_BUFFER_SIZE32];`
  - `GDI_HANDLE_BUFFER64` (type_alias, line 25) `typedef ULONG GDI_HANDLE_BUFFER64[GDI_HANDLE_BUFFER_SIZE64];`
  - `GDI_HANDLE_BUFFER` (type_alias, line 26) `typedef ULONG GDI_HANDLE_BUFFER[GDI_HANDLE_BUFFER_SIZE];`
  - `Length` (type_alias, line 27) `typedef struct _PEB_LDR_DATA { ULONG Length;`
  - `InheritedAddressSpace` (type_alias, line 40) `typedef struct _PEB { BOOLEAN InheritedAddressSpace;`
  - `InLoadOrderLinks` (type_alias, line 172) `typedef struct _LDR_DATA_TABLE_ENTRY { LIST_ENTRY InLoadOrderLinks;`
  - `GDI_HANDLE_BUFFER_SIZE32` (macro, line 15) `#define GDI_HANDLE_BUFFER_SIZE32`
  - `GDI_HANDLE_BUFFER_SIZE64` (macro, line 16) `#define GDI_HANDLE_BUFFER_SIZE64`
  - `GDI_HANDLE_BUFFER_SIZE` (macro, line 19) `#define GDI_HANDLE_BUFFER_SIZE`
  - `GDI_HANDLE_BUFFER_SIZE` (macro, line 21) `#define GDI_HANDLE_BUFFER_SIZE`
