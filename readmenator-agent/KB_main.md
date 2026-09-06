# Subsystem: main

## payloads/Demon/src/main/MainDll.c
- Layer: utility
- Doc: include <Demon.h>  include <common/Defines.h>  ifndef SHELLCODE Export this for rundll32 or any other program that requi
- Language: c
- Symbols:
  - `Start` (function, line 8) `DLLEXPORT VOID Start(  )`
  - `DllMain` (function, line 24) `DLLEXPORT BOOL WINAPI DllMain(
    IN     HINSTANCE hDllBase,
    IN     DWORD     Reason,
    _I...`

## payloads/Demon/src/main/MainExe.c
- Layer: utility
- Doc: include <Demon.h>
- Language: c
- Symbols:
  - `WinMain` (function, line 2) `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )`

## payloads/Demon/src/main/MainSvc.c
- Layer: utility
- Doc: include <Demon.h>  Service handle and status variable
- Language: c
- Symbols:
  - `WinMain` (function, line 16) `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )`
  - `SvcMain` (function, line 31) `VOID WINAPI SvcMain( DWORD dwArgc, LPTSTR* Argv )`
  - `SrvCtrlHandler` (function, line 40) `VOID WINAPI SrvCtrlHandler( DWORD CtrlCode )`
