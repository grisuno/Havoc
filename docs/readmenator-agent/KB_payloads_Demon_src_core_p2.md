# Subsystem: payloads_Demon_src_core (page 2 of 3)
Previous: [KB_payloads_Demon_src_core.md](KB_payloads_Demon_src_core.md)

## payloads/Demon/src/core/Package.c
- Doc: Import Core Headers
- Layer: utility
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
- Doc: TODO: Change the way new pivots gets added.
- Layer: utility
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
- Doc: RtMscoree: we delay loading mscoree.dll
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
- Doc: attempt to receive all the requested data from the socket Took it from...
- Layer: utility
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
- Doc: SysInitialize: !
- Layer: utility
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
- Doc: ThreadQueryTib: ! queries the NT_TIB from the specified leaked thread RSP address  NOTE: this...
- Layer: utility
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
- Doc: TODO: Change the way new tokens gets added.
- Layer: utility
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
- Doc: HttpSend: ! @brief send a http request  @param Send buffer to send  @param Resp buffer response...
- Layer: presentation
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
- Doc: SmbSecurityAttrOpen: Took it from https://github.com/rapid7/metasploit-payloads/blob/master/c/met...
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


Next: [KB_payloads_Demon_src_core_p3.md](KB_payloads_Demon_src_core_p3.md)
