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
  - `VOID` (function, line 12) `VOID ( WINAPI *DoSleep ) ( DWORD ) = LdrFunctionAddr( Kernel32, H_FUNC_SLEEP );`
  - `DoSleep` (function, line 18) `DoSleep( 24 * 60 * 60 * 1000 );`
  - `AllocConsole` (function, line 36) `AllocConsole();`
  - `freopen` (function, line 37) `freopen( "CONOUT$", "w", stdout );`
  - `DemonMain` (function, line 42) `DemonMain( hDllBase, Reserved );`
  - `HANDLE` (function, line 48) `HANDLE ( WINAPI *NewThread ) ( LPSECURITY_ATTRIBUTES, SIZE_T, LPTHREAD_START_ROUTINE, LPVOID, DWORD, LPDWORD ) = LdrFunctionAddr( Kernel32, H_FUNC_CREATETHREAD );`
  - `NewThread` (function, line 57) `NewThread( NULL, 0, C_PTR( DemonMain ), hDllBase, 0, NULL );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`

## payloads/Demon/src/main/MainExe.c
- Layer: utility
- Doc: include <Demon.h>
- Language: c
- Symbols:
  - `WinMain` (function, line 2) `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )`
  - `PRINTF` (function, line 5) `PRINTF( "WinMain: hInstance:[%p] hPrevInstance:[%p] lpCmdLine:[%s] nShowCmd:[%d]\n", hInstance, hPrevInstance, lpCmdLine, nShowCmd ) DemonMain( NULL, NULL );`
- Depends on: `payloads/Demon/include/Demon.h`

## payloads/Demon/src/main/MainSvc.c
- Layer: utility
- Doc: include <Demon.h>  Service handle and status variable
- Language: c
- Symbols:
  - `WinMain` (function, line 16) `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )`
  - `SvcMain` (function, line 31) `VOID WINAPI SvcMain( DWORD dwArgc, LPTSTR* Argv )`
  - `SrvCtrlHandler` (function, line 40) `VOID WINAPI SrvCtrlHandler( DWORD CtrlCode )`
  - `StartServiceCtrlDispatcherA` (function, line 24) `StartServiceCtrlDispatcherA( DispatchTable );`
  - `DemonMain` (function, line 38) `DemonMain( NULL, NULL );`
  - `SetServiceStatus` (function, line 48) `SetServiceStatus( StatusHandle, &SvcStatus );`
- Depends on: `payloads/Demon/include/Demon.h`
