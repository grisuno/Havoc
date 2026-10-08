# Subsystem: Include

## payloads/Shellcode/Include/Core.h
- Layer: utility
- Language: h
- Symbols:
  - `Modules` (struct, line 29)
  - `PAGE_SIZE` (macro, line 9) `#define PAGE_SIZE`
  - `MemCopy` (macro, line 10) `#define MemCopy`
  - `NTDLL_HASH` (macro, line 11) `#define NTDLL_HASH`
  - `SYS_LDRLOADDLL` (macro, line 13) `#define SYS_LDRLOADDLL`
  - `SYS_NTALLOCATEVIRTUALMEMORY` (macro, line 14) `#define SYS_NTALLOCATEVIRTUALMEMORY`
  - `SYS_NTPROTECTEDVIRTUALMEMORY` (macro, line 15) `#define SYS_NTPROTECTEDVIRTUALMEMORY`
- Depends on: `payloads/Shellcode/Include/Macro.h`

## payloads/Shellcode/Include/Macro.h
- Layer: utility
- Language: h
- Symbols:
  - `PPEB_PTR` (macro, line 5) `#define PPEB_PTR`
  - `PPEB_PTR` (macro, line 7) `#define PPEB_PTR`
  - `SEC` (macro, line 10) `#define SEC( s, x )`
  - `U_PTR` (macro, line 11) `#define U_PTR( x )`
  - `C_PTR` (macro, line 12) `#define C_PTR( x )`
  - `NtCurrentProcess` (macro, line 13) `#define NtCurrentProcess()`
  - `GET_SYMBOL` (macro, line 15) `#define GET_SYMBOL( x )`
- Imported by: `payloads/Shellcode/Include/Core.h`, `payloads/Shellcode/Include/Win32.h`

## payloads/Shellcode/Include/Utils.h
- Layer: utility
- Language: h
- Imported by: `payloads/Shellcode/Source/Utils.c`, `payloads/Shellcode/Source/Win32.c`

## payloads/Shellcode/Include/Win32.h
- Layer: utility
- Language: h
- Depends on: `payloads/Shellcode/Include/Macro.h`
