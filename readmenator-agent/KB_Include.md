# Subsystem: Include

## payloads/DllLdr/Include/Core.h
- Layer: utility
- Doc: include <windows.h> include <Macro.h>  define NTDLL_HASH                      0x70e61753  define SYS_LDRLOADDLL         
- Language: h
- Symbols:
  - `NTDLL_HASH` (macro, line 4)
  - `SYS_LDRLOADDLL` (macro, line 6)
  - `SYS_NTALLOCATEVIRTUALMEMORY` (macro, line 8)
  - `SYS_NTPROTECTEDVIRTUALMEMORY` (macro, line 9)
  - `SYS_NTFLUSHINSTRUCTIONCACHE` (macro, line 10)
  - `DLLEXPORT` (macro, line 11)
  - `NAKED` (macro, line 13)
  - `FORCE_INLINE` (macro, line 14)
  - `WIN32_FUNC` (macro, line 15)
  - `U_PTR` (macro, line 16)
  - `C_PTR` (macro, line 18)
  - `RVA2VA` (macro, line 19)
  - `DLL_QUERY_HMODULE` (macro, line 20)
  - `IMAGE_REL_TYPE` (macro, line 24)
  - `IMAGE_REL_TYPE` (macro, line 26)

## payloads/DllLdr/Include/Macro.h
- Layer: utility
- Doc: include <windows.h>  define HASH_KEY 5381  ifdef _WIN64 define PPEB_PTR __readgsqword( 0x60 ) else define PPEB_PTR __rea
- Language: h
- Symbols:
  - `HASH_KEY` (macro, line 3)
  - `PPEB_PTR` (macro, line 7)
  - `PPEB_PTR` (macro, line 9)
  - `SEC` (macro, line 11)
  - `U_PTR` (macro, line 13)
  - `C_PTR` (macro, line 14)
  - `NtCurrentProcess` (macro, line 15)
  - `GET_SYMBOL` (macro, line 16)

## payloads/DllLdr/Include/Native.h
- Layer: utility
- Language: h
- Symbols:
  - `_myUNICODE_STRING` (struct, line 2)
  - `_CURDIR` (struct, line 9)
  - `_PEB_LDR_DATA` (struct, line 28)
  - `_PEB` (struct, line 41)
  - `_LDR_DATA_TABLE_ENTRY` (struct, line 173)
  - `GDI_HANDLE_BUFFER_SIZE32` (macro, line 14)
  - `GDI_HANDLE_BUFFER_SIZE64` (macro, line 16)
  - `GDI_HANDLE_BUFFER_SIZE` (macro, line 19)
  - `GDI_HANDLE_BUFFER_SIZE` (macro, line 21)
