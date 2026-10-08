# Subsystem: main

## payloads/Demon/src/main/MainDll.c
- Doc: Export this for rundll32 or any other program that requires and exported functions...
- Layer: utility
- Language: c
- Symbols:
  - `Start` (function, line 8) `DLLEXPORT VOID Start(  )`
  - `DllMain` (function, line 24) `DLLEXPORT BOOL WINAPI DllMain(
    IN     HINSTANCE hDllBase,
    IN     DWORD     Reason,
    _I...`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`

## payloads/Demon/src/main/MainExe.c
- Layer: utility
- Language: c
- Symbols:
  - `WinMain` (function, line 3) `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )`
- Depends on: `payloads/Demon/include/Demon.h`

## payloads/Demon/src/main/MainSvc.c
- Doc: Service handle and status variable
- Layer: utility
- Language: c
- Symbols:
  - `WinMain` (function, line 16) `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )`
  - `SvcMain` (function, line 31) `VOID WINAPI SvcMain( DWORD dwArgc, LPTSTR* Argv )`
  - `SrvCtrlHandler` (function, line 41) `VOID WINAPI SrvCtrlHandler( DWORD CtrlCode )`
- Depends on: `payloads/Demon/include/Demon.h`
