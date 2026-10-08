# Symbols (page 10 of 13)
Previous: [SYMBOLS_p9.md](SYMBOLS_p9.md)

| Symbol | Kind | File:Line | Signature |
|--------|------|-----------|-----------|
| `RtWinHttp` | function | `payloads/Demon/src/core/Runtime.c:463` | `BOOL RtWinHttp(     VOID )` |
| `RtWs2_32` | function | `payloads/Demon/src/core/Runtime.c:349` | `BOOL RtWs2_32(     VOID )` |
| `DnsQueryIPv4` | function | `payloads/Demon/src/core/Socket.c:539` | `DWORD DnsQueryIPv4( LPSTR Domain )` |
| `DnsQueryIPv6` | function | `payloads/Demon/src/core/Socket.c:580` | `PBYTE DnsQueryIPv6( LPSTR Domain )` |
| `InitWSA` | function | `payloads/Demon/src/core/Socket.c:33` | `BOOL InitWSA( VOID )` |
| `PRINTF` | function | `payloads/Demon/src/core/Socket.c:112` | `PRINTF( "SockAddr6: %02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%d\n"...` |
| `PRINTF` | function | `payloads/Demon/src/core/Socket.c:429` | `PRINTF( "Closing socket %x\n", Socket->ID )      /* do we want to remove a reverse port forward c...` |
| `PUTS` | function | `payloads/Demon/src/core/Socket.c:41` | `PUTS( "Init Windows Socket..." )          if ( ( Result = Instance->Win32.WSAStartup( MAKEWORD( 2...` |
| `PUTS` | function | `payloads/Demon/src/core/Socket.c:74` | `PUTS( "Create Socket..." )          if ( UseIpv4 )` |
| `RecvAll` | function | `payloads/Demon/src/core/Socket.c:7` | `BOOL RecvAll( SOCKET Socket, PVOID Buffer, DWORD Length, PDWORD BytesRead )` |
| `SocketCleanDead` | function | `payloads/Demon/src/core/Socket.c:482` | `VOID SocketCleanDead()` |
| `SocketClients` | function | `payloads/Demon/src/core/Socket.c:213` | `VOID SocketClients()` |
| `SocketFree` | function | `payloads/Demon/src/core/Socket.c:425` | `VOID SocketFree( PSOCKET_DATA Socket )` |
| `SocketNew` | function | `payloads/Demon/src/core/Socket.c:59` | `PSOCKET_DATA SocketNew( SOCKET WinSock, DWORD Type, BOOL UseIpv4, DWORD IPv4, PBYTE IPv6, DWORD L...` |
| `SocketPush` | function | `payloads/Demon/src/core/Socket.c:522` | `VOID SocketPush()` |
| `SocketRead` | function | `payloads/Demon/src/core/Socket.c:281` | `VOID SocketRead()` |
| `SpoofRetAddr` | function | `payloads/Demon/src/core/Spoof.c:6` | `PVOID SpoofRetAddr(     _In_    PVOID  Module,     _In_    ULONG  Size,     _In_    HANDLE Functi...` |
| `SysNtAlertResumeThread` | function | `payloads/Demon/src/core/SysNative.c:358` | `NTSTATUS NTAPI SysNtAlertResumeThread(     IN      HANDLE ThreadHandle,     OUT OPT PULONG Previo...` |
| `SysNtAllocateVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:259` | `NTSTATUS NTAPI SysNtAllocateVirtualMemory(     IN     HANDLE    ProcessHandle,     _Inout_ PVOID*...` |
| `SysNtClose` | function | `payloads/Demon/src/core/SysNative.c:445` | `NTSTATUS NTAPI SysNtClose (     IN HANDLE Handle )` |
| `SysNtCreateEvent` | function | `payloads/Demon/src/core/SysNative.c:128` | `NTSTATUS NTAPI SysNtCreateEvent (     OUT    PHANDLE            EventHandle,     IN     ACCESS_MA...` |
| `SysNtCreateThreadEx` | function | `payloads/Demon/src/core/SysNative.c:143` | `NTSTATUS NTAPI SysNtCreateThreadEx(     OUT PHANDLE     hThread,     IN  ACCESS_MASK DesiredAcces...` |
| `SysNtDuplicateObject` | function | `payloads/Demon/src/core/SysNative.c:176` | `NTSTATUS NTAPI SysNtDuplicateObject(     IN     HANDLE      SourceProcessHandle,     IN     HANDL...` |
| `SysNtDuplicateToken` | function | `payloads/Demon/src/core/SysNative.c:73` | `NTSTATUS NTAPI SysNtDuplicateToken(     IN  HANDLE             ExistingTokenHandle,     IN  ACCES...` |
| `SysNtFreeVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:290` | `NTSTATUS NTAPI SysNtFreeVirtualMemory(     IN     HANDLE  ProcessHandle,     _Inout_ PVOID*  Base...` |
| `SysNtGetContextThread` | function | `payloads/Demon/src/core/SysNative.c:193` | `NTSTATUS NTAPI SysNtGetContextThread (     IN     HANDLE   ThreadHandle,     _Inout_ PCONTEXT Thr...` |
| `SysNtGetNextThread` | function | `payloads/Demon/src/core/SysNative.c:486` | `NTSTATUS NTAPI SysNtGetNextThread(     IN  HANDLE      ProcessHandle,     IN  HANDLE      ThreadH...` |
| `SysNtOpenProcess` | function | `payloads/Demon/src/core/SysNative.c:20` | `NTSTATUS NTAPI SysNtOpenProcess(     OUT    PHANDLE             ProcessHandle,     IN     ACCESS_...` |
| `SysNtOpenProcessToken` | function | `payloads/Demon/src/core/SysNative.c:60` | `NTSTATUS NTAPI SysNtOpenProcessToken(     IN  HANDLE      ProcessHandle,     IN  ACCESS_MASK Desi...` |
| `SysNtOpenThread` | function | `payloads/Demon/src/core/SysNative.c:6` | `NTSTATUS NTAPI SysNtOpenThread(     OUT    PHANDLE            ThreadHandle,     IN     ACCESS_MAS...` |
| `SysNtOpenThreadToken` | function | `payloads/Demon/src/core/SysNative.c:46` | `NTSTATUS NTAPI SysNtOpenThreadToken(     IN  HANDLE      ThreadHandle,     IN  ACCESS_MASK Desire...` |
| `SysNtProtectVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:316` | `NTSTATUS NTAPI SysNtProtectVirtualMemory(     IN     HANDLE  ProcessHandle,     _Inout_ PVOID*  B...` |
| `SysNtQueryInformationProcess` | function | `payloads/Demon/src/core/SysNative.c:217` | `NTSTATUS NTAPI SysNtQueryInformationProcess(     IN      HANDLE           ProcessHandle,     IN  ...` |
| `SysNtQueryInformationThread` | function | `payloads/Demon/src/core/SysNative.c:415` | `NTSTATUS NTAPI SysNtQueryInformationThread(     IN      HANDLE          ThreadHandle,     IN     ...` |
| `SysNtQueryInformationToken` | function | `payloads/Demon/src/core/SysNative.c:400` | `NTSTATUS NTAPI SysNtQueryInformationToken (     IN  HANDLE                  TokenHandle,     IN  ...` |
| `SysNtQueryObject` | function | `payloads/Demon/src/core/SysNative.c:430` | `NTSTATUS NTAPI SysNtQueryObject(     IN  HANDLE                   Handle,     IN  OBJECT_INFORMAT...` |
| `SysNtQuerySystemInformation` | function | `payloads/Demon/src/core/SysNative.c:232` | `NTSTATUS NTAPI SysNtQuerySystemInformation (     IN      SYSTEM_INFORMATION_CLASS SystemInformati...` |
| `SysNtQueryVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:384` | `NTSTATUS NTAPI SysNtQueryVirtualMemory(     IN      HANDLE                   ProcessHandle,     I...` |
| `SysNtQueueApcThread` | function | `payloads/Demon/src/core/SysNative.c:89` | `NTSTATUS NTAPI SysNtQueueApcThread(     IN     HANDLE          ThreadHandle,     IN     PPS_APC_R...` |
| `SysNtReadVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:331` | `NTSTATUS NTAPI SysNtReadVirtualMemory (     IN      HANDLE  ProcessHandle,     IN OPT  PVOID   Ba...` |
| `SysNtResumeThread` | function | `payloads/Demon/src/core/SysNative.c:116` | `NTSTATUS NTAPI SysNtResumeThread(     IN      HANDLE ThreadHandle,     OUT OPT PULONG PreviousSus...` |
| `SysNtSetContextThread` | function | `payloads/Demon/src/core/SysNative.c:205` | `NTSTATUS NTAPI SysNtSetContextThread(     IN HANDLE   ThreadHandle,     IN PCONTEXT ThreadContext )` |
| `SysNtSetInformationThread` | function | `payloads/Demon/src/core/SysNative.c:456` | `NTSTATUS NTAPI SysNtSetInformationThread (     IN HANDLE          ThreadHandle,     IN THREADINFO...` |
| `SysNtSetInformationVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:470` | `NTSTATUS NTAPI SysNtSetInformationVirtualMemory(     IN HANDLE                           ProcessH...` |
| `SysNtSignalAndWaitForSingleObject` | function | `payloads/Demon/src/core/SysNative.c:370` | `NTSTATUS NTAPI SysNtSignalAndWaitForSingleObject(     IN     HANDLE         SignalHandle,     IN ...` |
| `SysNtSuspendThread` | function | `payloads/Demon/src/core/SysNative.c:104` | `NTSTATUS NTAPI SysNtSuspendThread(     IN      HANDLE ThreadHandle,     OUT OPT PULONG PreviousSu...` |
| `SysNtTerminateProcess` | function | `payloads/Demon/src/core/SysNative.c:34` | `NTSTATUS NTAPI SysNtTerminateProcess(     IN OPTIONAL HANDLE   ProcessHandle,     IN          NTS...` |
| `SysNtTerminateThread` | function | `payloads/Demon/src/core/SysNative.c:346` | `NTSTATUS NTAPI SysNtTerminateThread (     IN OPT HANDLE   ThreadHandle,     IN     NTSTATUS ExitS...` |
| `SysNtUnmapViewOfSection` | function | `payloads/Demon/src/core/SysNative.c:304` | `NTSTATUS NTAPI SysNtUnmapViewOfSection(     IN HANDLE ProcessHandle,     IN PVOID  BaseAddress )` |
| `SysNtWaitForSingleObject` | function | `payloads/Demon/src/core/SysNative.c:246` | `NTSTATUS NTAPI SysNtWaitForSingleObject(     IN     HANDLE         Handle,     IN     BOOLEAN    ...` |
| `SysNtWriteVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:275` | `NTSTATUS NTAPI SysNtWriteVirtualMemory(     IN       HANDLE  ProcessHandle,     IN OPT   PVOID   ...` |
| `FindSsnOfHookedSyscall` | function | `payloads/Demon/src/core/Syscalls.c:201` | `BOOL FindSsnOfHookedSyscall(     IN  PVOID  Function,     OUT PWORD  Ssn )` |
| `PRINTF` | function | `payloads/Demon/src/core/Syscalls.c:184` | `PRINTF( "Could not resolve the Ssn of function at 0x%p\n", Function )         }          if ( Sys...` |
| `PRINTF` | function | `payloads/Demon/src/core/Syscalls.c:209` | `PRINTF( "The syscall at address 0x%p seems to be hooked, trying to resolve its Ssn via neighbouri...` |
| `SYS_EXTRACT` | function | `payloads/Demon/src/core/Syscalls.c:44` | `SYS_EXTRACT( NtOpenThread )     SYS_EXTRACT( NtOpenThreadToken )     SYS_EXTRACT( NtOpenProcess )...` |
| `SysInitialize` | function | `payloads/Demon/src/core/Syscalls.c:12` | `BOOL SysInitialize(     IN PVOID Ntdll )` |
| `PUTS` | function | `payloads/Demon/src/core/Thread.c:185` | `PUTS( "calling RtlCreateUserThread( ctx->h.hProcess, NULL, TRUE, 0, NULL, NULL, ctx->s.lpStartAdd...` |
| `ThreadCreate` | function | `payloads/Demon/src/core/Thread.c:217` | `HANDLE ThreadCreate(     IN  BYTE   Method,     IN  HANDLE Process,     IN  BOOL   x64,     IN  P...` |
| `ThreadCreateWoW64` | function | `payloads/Demon/src/core/Thread.c:118` | `HANDLE ThreadCreateWoW64(     IN  BYTE   Method,     IN  HANDLE Process,     IN  PVOID  Entry,   ...` |
| `ThreadQueryTib` | function | `payloads/Demon/src/core/Thread.c:20` | `BOOL ThreadQueryTib(     IN  PVOID   Adr,     OUT PNT_TIB Tib )` |
| `AddUserToken` | function | `payloads/Demon/src/core/Token.c:733` | `VOID AddUserToken(     _Inout_ PUSER_TOKEN_DATA NewToken,     _Inout_ PUSER_TOKEN_DATA Tokens,   ...` |
| `CanTokenBeImpersonated` | function | `payloads/Demon/src/core/Token.c:802` | `BOOL CanTokenBeImpersonated( IN HANDLE hToken )` |
| `DATA_FREE` | function | `payloads/Demon/src/core/Token.c:182` | `DATA_FREE( UserInfo, UserSize )     }      if ( Flags == TOKEN_OWNER_FLAG_USER )` |
| `GetAllHandles` | function | `payloads/Demon/src/core/Token.c:1076` | `BOOL GetAllHandles( OUT PSYSTEM_HANDLE_INFORMATION* phandle_table, OUT PULONG phandle_table_size )` |
| `GetProcessesFromHandleTable` | function | `payloads/Demon/src/core/Token.c:1040` | `BOOL GetProcessesFromHandleTable( IN PSYSTEM_HANDLE_INFORMATION handleTableInformation, OUT PPROC...` |
| `GetTokenInfo` | function | `payloads/Demon/src/core/Token.c:949` | `BOOL GetTokenInfo(     IN HANDLE hToken,     OUT PDWORD pTokenType,     OUT PDWORD pIntegrity,   ...` |
| `GetTypeIndexToken` | function | `payloads/Demon/src/core/Token.c:910` | `BOOL GetTypeIndexToken( OUT PULONG TokenTypeIndex )` |
| `ImpersonateTokenFromVault` | function | `payloads/Demon/src/core/Token.c:1257` | `BOOL ImpersonateTokenFromVault(     IN DWORD TokenID )` |
| `ImpersonateTokenInStore` | function | `payloads/Demon/src/core/Token.c:1361` | `BOOL ImpersonateTokenInStore(     IN PTOKEN_LIST_DATA TokenData )` |
| `IsImpersonationToken` | function | `payloads/Demon/src/core/Token.c:771` | `BOOL IsImpersonationToken( HANDLE token )` |
| `IsNotCurrentUser` | function | `payloads/Demon/src/core/Token.c:1122` | `BOOL IsNotCurrentUser( BOOL DoCheck, PBUFFER UserA, PBUFFER UserB )` |
| `ListTokens` | function | `payloads/Demon/src/core/Token.c:1130` | `BOOL ListTokens( PUSER_TOKEN_DATA* pTokens, PDWORD pNumTokens )` |
| `PRINTF` | function | `payloads/Demon/src/core/Token.c:463` | `PRINTF( "ProcessOpen: Failed:[%ld]\n", NtGetLastError() )         PACKAGE_ERROR_WIN32     }      ...` |
| `PRINTF` | function | `payloads/Demon/src/core/Token.c:602` | `PRINTF( "TokenMake( %ls, %ls, %ls, %d )\n", User, Password, Domain, LogonType )      if ( ! Token...` |
| `PRINTF` | function | `payloads/Demon/src/core/Token.c:606` | `PRINTF( "Failed to revert to self: Error:[%d]\n", NtGetLastError() )         PACKAGE_ERROR_WIN32 ...` |
| `PUTS` | function | `payloads/Demon/src/core/Token.c:177` | `PUTS( "Unexpected successful call to NtQueryInformationToken.\n" )     }  LEAVE:     if ( UserInfo )` |
| `PUTS` | function | `payloads/Demon/src/core/Token.c:991` | `PUTS( "GetTokenInformation failed" )             }         }         else if (TokenStatisticsInfo...` |
| `ProcessIsIncluded` | function | `payloads/Demon/src/core/Token.c:1029` | `BOOL ProcessIsIncluded( IN PPROCESS_LIST process_list, IN ULONG ProcessId )` |
| `ProcessUserToken` | function | `payloads/Demon/src/core/Token.c:830` | `VOID ProcessUserToken(     IN HANDLE hToken,     IN DWORD ProcessId,     IN HANDLE handle,     IN...` |
| `QueryObjectTypesInfo` | function | `payloads/Demon/src/core/Token.c:878` | `BOOL QueryObjectTypesInfo( POBJECT_TYPES_INFORMATION* pObjectTypes, PULONG pObjectTypesSize )` |
| `SysDuplicateTokenEx` | function | `payloads/Demon/src/core/Token.c:365` | `BOOL SysDuplicateTokenEx(     IN HANDLE ExistingTokenHandle,     IN DWORD dwDesiredAccess,     IN...` |
| `SysImpersonateLoggedOnUser` | function | `payloads/Demon/src/core/Token.c:1281` | `BOOL SysImpersonateLoggedOnUser( HANDLE hToken )` |
| `TokenAdd` | function | `payloads/Demon/src/core/Token.c:323` | `DWORD TokenAdd(     IN HANDLE hToken,     IN LPWSTR DomainUser,     IN SHORT  Type,     IN DWORD ...` |
| `TokenClear` | function | `payloads/Demon/src/core/Token.c:681` | `VOID TokenClear(     VOID )` |
| `TokenCurrentHandle` | function | `payloads/Demon/src/core/Token.c:624` | `HANDLE TokenCurrentHandle(     VOID )` |
| `TokenDuplicate` | function | `payloads/Demon/src/core/Token.c:37` | `BOOL TokenDuplicate(     IN  HANDLE        TokenOriginal,     IN  DWORD         Access,     IN  S...` |
| `TokenElevated` | function | `payloads/Demon/src/core/Token.c:650` | `BOOL TokenElevated(     IN HANDLE Token )` |
| `TokenGet` | function | `payloads/Demon/src/core/Token.c:664` | `PTOKEN_LIST_DATA TokenGet(     IN DWORD TokenID )` |
| `TokenImpersonate` | function | `payloads/Demon/src/core/Token.c:707` | `BOOL TokenImpersonate(     IN BOOL Impersonate )` |
| `TokenMake` | function | `payloads/Demon/src/core/Token.c:598` | `HANDLE TokenMake( LPWSTR User, LPWSTR Password, LPWSTR Domain, DWORD LogonType )` |
| `TokenQueryOwner` | function | `payloads/Demon/src/core/Token.c:103` | `BOOL TokenQueryOwner(     IN  HANDLE  Token,     OUT PBUFFER UserDomain,     IN  DWORD   Flags )` |
| `TokenRemove` | function | `payloads/Demon/src/core/Token.c:474` | `BOOL TokenRemove( DWORD TokenID )` |
| `TokenRevSelf` | function | `payloads/Demon/src/core/Token.c:74` | `BOOL TokenRevSelf(     VOID )` |
| `TokenSetPrivilege` | function | `payloads/Demon/src/core/Token.c:203` | `BOOL TokenSetPrivilege(     IN LPSTR Privilege,     IN BOOL  Enable )` |
| `TokenSetSeDebugPriv` | function | `payloads/Demon/src/core/Token.c:240` | `BOOL TokenSetSeDebugPriv(     IN BOOL  Enable )` |
| `TokenSetSeImpersonatePriv` | function | `payloads/Demon/src/core/Token.c:271` | `BOOL TokenSetSeImpersonatePriv(     IN BOOL  Enable )` |
| `TokenSteal` | function | `payloads/Demon/src/core/Token.c:414` | `HANDLE TokenSteal(     IN DWORD  ProcessID,     IN HANDLE TargetHandle )` |
| `SMBGetJob` | function | `payloads/Demon/src/core/Transport.c:89` | `BOOL SMBGetJob( PVOID* RecvData, PSIZE_T RecvSize )` |
| `TransportInit` | function | `payloads/Demon/src/core/Transport.c:13` | `BOOL TransportInit( )` |
| `TransportSend` | function | `payloads/Demon/src/core/Transport.c:52` | `BOOL TransportSend( LPVOID Data, SIZE_T Size, PVOID* RecvData, PSIZE_T RecvSize )` |
| `HostAdd` | function | `payloads/Demon/src/core/TransportHttp.c:356` | `PHOST_DATA HostAdd(     _In_ LPWSTR Host, SIZE_T Size, DWORD Port )` |
| `HostCheckup` | function | `payloads/Demon/src/core/TransportHttp.c:541` | `BOOL HostCheckup()` |
| `HostCount` | function | `payloads/Demon/src/core/TransportHttp.c:514` | `DWORD HostCount()` |
| `HostFailure` | function | `payloads/Demon/src/core/TransportHttp.c:378` | `PHOST_DATA HostFailure( PHOST_DATA Host )` |
| `HostRandom` | function | `payloads/Demon/src/core/TransportHttp.c:402` | `PHOST_DATA HostRandom()` |
| `HostRotation` | function | `payloads/Demon/src/core/TransportHttp.c:437` | `PHOST_DATA HostRotation( SHORT Strategy )` |
| `HttpQueryStatus` | function | `payloads/Demon/src/core/TransportHttp.c:336` | `DWORD HttpQueryStatus(     _In_ HANDLE Request )` |
| `HttpSend` | function | `payloads/Demon/src/core/TransportHttp.c:21` | `BOOL HttpSend(     _In_      PBUFFER Send,     _Out_opt_ PBUFFER Resp )` |
| `PRINTF_DONT_SEND` | function | `payloads/Demon/src/core/TransportHttp.c:291` | `PRINTF_DONT_SEND( "HTTP Error: %d\n", NtGetLastError() )     }  LEAVE:     if ( Connect )` |
| `PRINTF` | function | `payloads/Demon/src/core/TransportSmb.c:107` | `PRINTF( "PipeRead failed with to read 0x%x bytes from pipe\n", Resp->Length )                 if ...` |
| `SmbRecv` | function | `payloads/Demon/src/core/TransportSmb.c:65` | `BOOL SmbRecv( PBUFFER Resp )` |
| `SmbSecurityAttrFree` | function | `payloads/Demon/src/core/TransportSmb.c:213` | `VOID SmbSecurityAttrFree( PSMB_PIPE_SEC_ATTR SmbSecAttr )` |
| `SmbSecurityAttrOpen` | function | `payloads/Demon/src/core/TransportSmb.c:142` | `VOID SmbSecurityAttrOpen( PSMB_PIPE_SEC_ATTR SmbSecAttr, PSECURITY_ATTRIBUTES SecurityAttr )` |
| `SmbSend` | function | `payloads/Demon/src/core/TransportSmb.c:8` | `BOOL SmbSend( PBUFFER Send )` |
| `AnonPipesInit` | function | `payloads/Demon/src/core/Win32.c:981` | `BOOL AnonPipesInit(     IN PANONPIPE AnonPipes )` |
| `AnonPipesRead` | function | `payloads/Demon/src/core/Win32.c:1000` | `VOID AnonPipesRead(     IN PANONPIPE AnonPipes,     IN UINT32 RequestID )` |
| `BypassPatchAMSI` | function | `payloads/Demon/src/core/Win32.c:930` | `BOOL BypassPatchAMSI(     VOID )` |
| `CfgAddressAdd` | function | `payloads/Demon/src/core/Win32.c:1259` | `VOID CfgAddressAdd(     IN PVOID ImageBase,     IN PVOID Function )` |
| `CfgQueryEnforced` | function | `payloads/Demon/src/core/Win32.c:1227` | `BOOL CfgQueryEnforced(     VOID )` |
| `DemonPrintf` | function | `payloads/Demon/src/core/Win32.c:1402` | `VOID DemonPrintf( PCHAR fmt, ... )` |
| `EventSet` | function | `payloads/Demon/src/core/Win32.c:1293` | `BOOL EventSet(     IN HANDLE Event )` |
| `GetSyscallSize` | function | `payloads/Demon/src/core/Win32.c:440` | `UINT32 GetSyscallSize(     VOID )` |
| `HashEx` | function | `payloads/Demon/src/core/Win32.c:17` | `ULONG HashEx(     IN PVOID String,     IN ULONG Length,     IN BOOL  Upper )` |
| `LdrFunctionAddr` | function | `payloads/Demon/src/core/Win32.c:377` | `PVOID LdrFunctionAddr(     IN PVOID Module,     IN DWORD Hash )` |
| `LdrModuleLoad` | function | `payloads/Demon/src/core/Win32.c:215` | `PVOID LdrModuleLoad(     IN LPSTR ModuleName )` |
| `LdrModulePeb` | function | `payloads/Demon/src/core/Win32.c:65` | `PVOID LdrModulePeb(     IN DWORD Hash )` |
| `LdrModulePebByString` | function | `payloads/Demon/src/core/Win32.c:99` | `PVOID LdrModulePebByString(     IN LPWSTR Module )` |
| `LdrModuleSearch` | function | `payloads/Demon/src/core/Win32.c:165` | `PVOID LdrModuleSearch(     IN LPWSTR ModuleName)` |
| `LogToConsole` | function | `payloads/Demon/src/core/Win32.c:1434` | `VOID LogToConsole(     IN LPCSTR fmt,     ...)` |
| `PRINTF` | function | `payloads/Demon/src/core/Win32.c:354` | `PRINTF( "Module \"%s\": %p\n", ModuleName, Module )      /* close event end */     if ( Event )` |
| `PRINTF` | function | `payloads/Demon/src/core/Win32.c:654` | `PRINTF( "CmdLine           : %ls\n", CmdLine )         PRINTF( "lpCurrentDirectory: %ls\n", lpCur...` |
| `PRINTF` | function | `payloads/Demon/src/core/Win32.c:1023` | `PRINTF( "dwRead => %d\n", dwRead )          if ( dwRead == 0 )` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:252` | `PUTS( "Loading module using RtlRegisterWait" )              /* create an event for end of module ...` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:269` | `PUTS( "Loading module using RtlCreateTimer" )              /* create timer queue */             i...` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:286` | `PUTS( "Loading module using RtlQueueWorkItem" )              /* call LoadLibraryW and load specif...` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:626` | `PUTS( "Enable Wow64 process support" )         if ( ! Instance->Win32.Wow64DisableWow64FsRedirect...` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:671` | `PUTS( "CreateProcessWithTokenW" )             if ( ! Instance->Win32.CreateProcessWithTokenW(    ...` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:693` | `PUTS( "CreateProcessWithLogonW" )             PRINTF( "lpUser[%s] lpDomain[%s] lpPassword[%s]", I...` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:739` | `PUTS( "Send info back" )         if ( ! CmdLine )` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:831` | `PUTS( "Failed to terminate process" )     }  END:     if ( OpenedHandle )` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:1011` | `PUTS( "Start reading anon pipe" )     PRINTF( "AnonPipes->StdOutRead => %x\n", AnonPipes->StdOutR...` |
| `PipeRead` | function | `payloads/Demon/src/core/Win32.c:1175` | `BOOL PipeRead(     IN HANDLE  Handle,     IN PBUFFER Buffer )` |
| `PipeWrite` | function | `payloads/Demon/src/core/Win32.c:1202` | `BOOL PipeWrite(     IN  HANDLE   Handle,     OUT PBUFFER Buffer )` |
| `ProcessCreate` | function | `payloads/Demon/src/core/Win32.c:579` | `BOOL ProcessCreate(     IN  BOOL                 x86,     IN  LPWSTR               App,     IN  L...` |
| `ProcessIsWow` | function | `payloads/Demon/src/core/Win32.c:544` | `BOOL ProcessIsWow(     IN HANDLE Process )` |
| `ProcessOpen` | function | `payloads/Demon/src/core/Win32.c:515` | `HANDLE ProcessOpen(     IN DWORD Pid,     IN DWORD Access )` |
| `ProcessSnapShot` | function | `payloads/Demon/src/core/Win32.c:848` | `NTSTATUS ProcessSnapShot(     OUT PSYSTEM_PROCESS_INFORMATION* SnapShot,     OUT PSIZE_T         ...` |
| `ProcessTerminate` | function | `payloads/Demon/src/core/Win32.c:806` | `BOOL ProcessTerminate(     IN HANDLE hProcess,     IN DWORD  Pid)` |
| `RandomBool` | function | `payloads/Demon/src/core/Win32.c:1321` | `BOOL RandomBool(     VOID )` |
| `RandomNumber32` | function | `payloads/Demon/src/core/Win32.c:1304` | `ULONG RandomNumber32(     VOID )` |
| `ReadLocalFile` | function | `payloads/Demon/src/core/Win32.c:886` | `BOOL ReadLocalFile(     IN  LPCWSTR FileName,     OUT PVOID*  FileContent,     OUT PDWORD  FileSi...` |
| `SharedSleep` | function | `payloads/Demon/src/core/Win32.c:1357` | `VOID SharedSleep(     ULONG64 Delay )` |
| `SharedTimestamp` | function | `payloads/Demon/src/core/Win32.c:1337` | `ULONG64 SharedTimestamp(     VOID )` |
| `ShuffleArray` | function | `payloads/Demon/src/core/Win32.c:1379` | `VOID ShuffleArray(     _Inout_ PVOID* array,     IN     SIZE_T n )` |
| `WinScreenshot` | function | `payloads/Demon/src/core/Win32.c:1052` | `BOOL WinScreenshot(     OUT PVOID*  ImagePointer,     OUT PSIZE_T ImageSize )` |
| `___chkstk_ms` | function | `payloads/Demon/src/core/Win32.c:1396` | `VOID volatile ___chkstk_ms(         VOID )` |
| `listDir` | function | `payloads/Demon/src/core/Win32.c:1478` | `PROOT_DIR listDir(     IN LPWSTR StartPath,     IN BOOL   SubDirs,     IN BOOL   FilesOnly,     I...` |
| `AddRoundKey` | function | `payloads/Demon/src/crypt/AesCrypt.c:111` | `static void AddRoundKey(UINT8 round, state_t* state, const UINT8* RoundKey)` |
| `AesInit` | function | `payloads/Demon/src/crypt/AesCrypt.c:103` | `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv)` |
| `AesXCryptBuffer` | function | `payloads/Demon/src/crypt/AesCrypt.c:217` | `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length)` |
| `KeyExpansion` | function | `payloads/Demon/src/crypt/AesCrypt.c:47` | `void KeyExpansion(UINT8* RoundKey, const UINT8* Key)` |
| `MULTIPLY_AS_A_FUNCTION` | macro | `payloads/Demon/src/crypt/AesCrypt.c:18` | `#define MULTIPLY_AS_A_FUNCTION` |
| `MixColumns` | function | `payloads/Demon/src/crypt/AesCrypt.c:174` | `static void MixColumns(state_t* state)` |
| `Nb` | macro | `payloads/Demon/src/crypt/AesCrypt.c:4` | `#define Nb` |
| `Nk` | macro | `payloads/Demon/src/crypt/AesCrypt.c:7` | `#define Nk` |
| `Nk` | macro | `payloads/Demon/src/crypt/AesCrypt.c:10` | `#define Nk` |
| `Nk` | macro | `payloads/Demon/src/crypt/AesCrypt.c:13` | `#define Nk` |
| `Nr` | macro | `payloads/Demon/src/crypt/AesCrypt.c:8` | `#define Nr` |
| `Nr` | macro | `payloads/Demon/src/crypt/AesCrypt.c:11` | `#define Nr` |
| `Nr` | macro | `payloads/Demon/src/crypt/AesCrypt.c:14` | `#define Nr` |
| `ShiftRows` | function | `payloads/Demon/src/crypt/AesCrypt.c:140` | `static void ShiftRows(state_t* state)` |
| `SubBytes` | function | `payloads/Demon/src/crypt/AesCrypt.c:125` | `static void SubBytes(state_t* state)` |
| `getSBoxValue` | macro | `payloads/Demon/src/crypt/AesCrypt.c:45` | `#define getSBoxValue(num)` |
| `xtime` | function | `payloads/Demon/src/crypt/AesCrypt.c:168` | `static UINT8 xtime(UINT8 x)` |
| `DllInjectReflective` | function | `payloads/Demon/src/inject/Inject.c:172` | `DWORD DllInjectReflective( HANDLE hTargetProcess, LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuff...` |
| `DllSpawnReflective` | function | `payloads/Demon/src/inject/Inject.c:322` | `DWORD DllSpawnReflective( LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuffer, DWORD DllLength, PVO...` |
| `Inject` | function | `payloads/Demon/src/inject/Inject.c:27` | `DWORD Inject(     IN BYTE   Method,     IN HANDLE Handle,     IN DWORD  Pid,     IN BOOL   x64,  ...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:64` | `PRINTF( "[INJECT] Using specified process handle: %x\n", Process )     }      /* check the archit...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:91` | `PRINTF( "[INJECT] Allocated memory in the remote process: %p\n", Memory )     }      /* write pay...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:99` | `PRINTF( "[INJECT] Wrote payload into remote process: %d written\n", Size )     }      /* change a...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:118` | `PRINTF( "[INJECT] Allocated argument memory in the remote process: %p\n", Param )         }      ...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:126` | `PRINTF( "[INJECT] Wrote argument into remote process: %d written\n", Argc )         }     }      ...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:135` | `PRINTF( "[INJECT] Failed to create a new thread: %d\n", NtGetLastError() )     }  END:     PUTS( ...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:232` | `PRINTF( "Params: Size:[%d] Pointer:[%p]\n", ParamSize, Parameter )     if ( ParamSize > 0 )` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:278` | `PRINTF( "ctx->Parameter: %p\n", ctx->Parameter )                  if ( ! ThreadCreate( THREAD_MET...` |
| `PUTS` | function | `payloads/Demon/src/inject/Inject.c:107` | `PUTS( "[INJECT] Changed memory protection from RW to RX" )     }      /* check if any args has be...` |
| `GetPeArch` | function | `payloads/Demon/src/inject/InjectUtil.c:72` | `DWORD GetPeArch( PVOID PeBytes )` |
| `GetReflectiveLoaderOffset` | function | `payloads/Demon/src/inject/InjectUtil.c:36` | `DWORD GetReflectiveLoaderOffset( PVOID ReflectiveLdrAddr )` |
| `NTSTATUS` | type_alias | `payloads/Demon/src/inject/InjectUtil.c:9` | `typedef ULONG NTSTATUS;` |
| `Rva2Offset` | function | `payloads/Demon/src/inject/InjectUtil.c:12` | `DWORD Rva2Offset( DWORD dwRva, UINT_PTR uiBaseAddress )` |
| `DllMain` | function | `payloads/Demon/src/main/MainDll.c:24` | `DLLEXPORT BOOL WINAPI DllMain(     IN     HINSTANCE hDllBase,     IN     DWORD     Reason,     _I...` |
| `Start` | function | `payloads/Demon/src/main/MainDll.c:8` | `DLLEXPORT VOID Start(  )` |
| `WinMain` | function | `payloads/Demon/src/main/MainExe.c:3` | `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )` |
| `SrvCtrlHandler` | function | `payloads/Demon/src/main/MainSvc.c:41` | `VOID WINAPI SrvCtrlHandler( DWORD CtrlCode )` |
| `SvcMain` | function | `payloads/Demon/src/main/MainSvc.c:31` | `VOID WINAPI SvcMain( DWORD dwArgc, LPTSTR* Argv )` |
| `WinMain` | function | `payloads/Demon/src/main/MainSvc.c:16` | `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )` |
| `C_PTR` | macro | `payloads/DllLdr/Include/Core.h:18` | `#define C_PTR( x )` |
| `DLLEXPORT` | macro | `payloads/DllLdr/Include/Core.h:12` | `#define DLLEXPORT` |
| `DLL_QUERY_HMODULE` | macro | `payloads/DllLdr/Include/Core.h:21` | `#define DLL_QUERY_HMODULE` |
| `FORCE_INLINE` | macro | `payloads/DllLdr/Include/Core.h:14` | `#define FORCE_INLINE` |
| `IMAGE_REL_TYPE` | macro | `payloads/DllLdr/Include/Core.h:24` | `#define IMAGE_REL_TYPE` |
| `IMAGE_REL_TYPE` | macro | `payloads/DllLdr/Include/Core.h:26` | `#define IMAGE_REL_TYPE` |
| `Modules` | struct | `payloads/DllLdr/Include/Core.h:36` | `` |
| `NAKED` | macro | `payloads/DllLdr/Include/Core.h:13` | `#define NAKED` |
| `NTDLL_HASH` | macro | `payloads/DllLdr/Include/Core.h:5` | `#define NTDLL_HASH` |
| `RVA2VA` | macro | `payloads/DllLdr/Include/Core.h:19` | `#define RVA2VA(type, base, rva)` |
| `SYS_LDRLOADDLL` | macro | `payloads/DllLdr/Include/Core.h:7` | `#define SYS_LDRLOADDLL` |
| `SYS_NTALLOCATEVIRTUALMEMORY` | macro | `payloads/DllLdr/Include/Core.h:8` | `#define SYS_NTALLOCATEVIRTUALMEMORY` |
| `SYS_NTFLUSHINSTRUCTIONCACHE` | macro | `payloads/DllLdr/Include/Core.h:10` | `#define SYS_NTFLUSHINSTRUCTIONCACHE` |
| `SYS_NTPROTECTEDVIRTUALMEMORY` | macro | `payloads/DllLdr/Include/Core.h:9` | `#define SYS_NTPROTECTEDVIRTUALMEMORY` |
| `U_PTR` | macro | `payloads/DllLdr/Include/Core.h:17` | `#define U_PTR( x )` |
| `WIN32_FUNC` | macro | `payloads/DllLdr/Include/Core.h:15` | `#define WIN32_FUNC( x )` |
| `C_PTR` | macro | `payloads/DllLdr/Include/Macro.h:14` | `#define C_PTR( x )` |
| `GET_SYMBOL` | macro | `payloads/DllLdr/Include/Macro.h:17` | `#define GET_SYMBOL( x )` |
| `HASH_KEY` | macro | `payloads/DllLdr/Include/Macro.h:4` | `#define HASH_KEY` |
| `NtCurrentProcess` | macro | `payloads/DllLdr/Include/Macro.h:15` | `#define NtCurrentProcess()` |
| `PPEB_PTR` | macro | `payloads/DllLdr/Include/Macro.h:7` | `#define PPEB_PTR` |
| `PPEB_PTR` | macro | `payloads/DllLdr/Include/Macro.h:9` | `#define PPEB_PTR` |
| `SEC` | macro | `payloads/DllLdr/Include/Macro.h:12` | `#define SEC( s, x )` |
| `U_PTR` | macro | `payloads/DllLdr/Include/Macro.h:13` | `#define U_PTR( x )` |
| `DosPath` | type_alias | `payloads/DllLdr/Include/Native.h:8` | `typedef struct _CURDIR { myUNICODE_STRING DosPath;` |
| `GDI_HANDLE_BUFFER` | type_alias | `payloads/DllLdr/Include/Native.h:26` | `typedef ULONG GDI_HANDLE_BUFFER[GDI_HANDLE_BUFFER_SIZE];` |
| `GDI_HANDLE_BUFFER32` | type_alias | `payloads/DllLdr/Include/Native.h:23` | `typedef ULONG GDI_HANDLE_BUFFER32[GDI_HANDLE_BUFFER_SIZE32];` |
| `GDI_HANDLE_BUFFER64` | type_alias | `payloads/DllLdr/Include/Native.h:25` | `typedef ULONG GDI_HANDLE_BUFFER64[GDI_HANDLE_BUFFER_SIZE64];` |
| `GDI_HANDLE_BUFFER_SIZE` | macro | `payloads/DllLdr/Include/Native.h:19` | `#define GDI_HANDLE_BUFFER_SIZE` |
| `GDI_HANDLE_BUFFER_SIZE` | macro | `payloads/DllLdr/Include/Native.h:21` | `#define GDI_HANDLE_BUFFER_SIZE` |
| `GDI_HANDLE_BUFFER_SIZE32` | macro | `payloads/DllLdr/Include/Native.h:15` | `#define GDI_HANDLE_BUFFER_SIZE32` |
| `GDI_HANDLE_BUFFER_SIZE64` | macro | `payloads/DllLdr/Include/Native.h:16` | `#define GDI_HANDLE_BUFFER_SIZE64` |
| `InLoadOrderLinks` | type_alias | `payloads/DllLdr/Include/Native.h:172` | `typedef struct _LDR_DATA_TABLE_ENTRY { LIST_ENTRY InLoadOrderLinks;` |
| `InheritedAddressSpace` | type_alias | `payloads/DllLdr/Include/Native.h:40` | `typedef struct _PEB { BOOLEAN InheritedAddressSpace;` |
| `Length` | type_alias | `payloads/DllLdr/Include/Native.h:1` | `typedef struct _myUNICODE_STRING { USHORT Length;` |
| `Length` | type_alias | `payloads/DllLdr/Include/Native.h:27` | `typedef struct _PEB_LDR_DATA { ULONG Length;` |
| `_CURDIR` | struct | `payloads/DllLdr/Include/Native.h:9` | `` |
| `_LDR_DATA_TABLE_ENTRY` | struct | `payloads/DllLdr/Include/Native.h:173` | `` |
| `_PEB` | struct | `payloads/DllLdr/Include/Native.h:41` | `` |
| `_PEB_LDR_DATA` | struct | `payloads/DllLdr/Include/Native.h:28` | `` |
| `_myUNICODE_STRING` | struct | `payloads/DllLdr/Include/Native.h:2` | `` |
| `main` | function | `payloads/DllLdr/Scripts/extract.py:8` | `def main(options)` |
| `CopyDotStr` | function | `payloads/DllLdr/Source/Entry.c:206` | `FORCE_INLINE UINT32 CopyDotStr( PCHAR String )` |
| `KCharStringToWCharString` | function | `payloads/DllLdr/Source/Entry.c:409` | `SIZE_T KCharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )` |
| `KGetModuleByHash` | function | `payloads/DllLdr/Source/Entry.c:185` | `PVOID KGetModuleByHash( DWORD ModuleHash )` |
| `KGetProcAddressByHash` | function | `payloads/DllLdr/Source/Entry.c:215` | `PVOID KGetProcAddressByHash( PINSTANCE Instance, PVOID DllModuleBase, DWORD FunctionHash, DWORD O...` |
| `KHashString` | function | `payloads/DllLdr/Source/Entry.c:364` | `DWORD KHashString( PVOID String, SIZE_T Length )` |
| `KLoadLibrary` | function | `payloads/DllLdr/Source/Entry.c:331` | `PVOID KLoadLibrary( PINSTANCE Instance, LPSTR ModuleName )` |
| `KReAllocSections` | function | `payloads/DllLdr/Source/Entry.c:306` | `VOID KReAllocSections( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir )` |
| `KResolveIAT` | function | `payloads/DllLdr/Source/Entry.c:265` | `VOID KResolveIAT( PINSTANCE Instance, LPVOID KaynImage, LPVOID IatDir )` |
| `KStringLengthA` | function | `payloads/DllLdr/Source/Entry.c:393` | `SIZE_T KStringLengthA( LPCSTR String )` |
| `KStringLengthW` | function | `payloads/DllLdr/Source/Entry.c:400` | `SIZE_T KStringLengthW(LPCWSTR String)` |
| `KaynCaller` | function | `payloads/DllLdr/Source/Entry.c:144` | `NAKED LPVOID KaynCaller( PVOID StartAddress )` |
| `KaynLoader` | function | `payloads/DllLdr/Source/Entry.c:5` | `DLLEXPORT VOID KaynLoader( LPVOID lpParameter )` |
| `Memcpy` | function | `payloads/DllLdr/Source/Entry.c:166` | `NAKED VOID Memcpy( PVOID Destination, PVOID source, SIZE_T Size )` |
| `MemCopy` | macro | `payloads/Shellcode/Include/Core.h:10` | `#define MemCopy` |
| `Modules` | struct | `payloads/Shellcode/Include/Core.h:29` | `` |
| `NTDLL_HASH` | macro | `payloads/Shellcode/Include/Core.h:11` | `#define NTDLL_HASH` |
| `PAGE_SIZE` | macro | `payloads/Shellcode/Include/Core.h:9` | `#define PAGE_SIZE` |
| `SYS_LDRLOADDLL` | macro | `payloads/Shellcode/Include/Core.h:13` | `#define SYS_LDRLOADDLL` |
| `SYS_NTALLOCATEVIRTUALMEMORY` | macro | `payloads/Shellcode/Include/Core.h:14` | `#define SYS_NTALLOCATEVIRTUALMEMORY` |
| `SYS_NTPROTECTEDVIRTUALMEMORY` | macro | `payloads/Shellcode/Include/Core.h:15` | `#define SYS_NTPROTECTEDVIRTUALMEMORY` |
| `C_PTR` | macro | `payloads/Shellcode/Include/Macro.h:12` | `#define C_PTR( x )` |
| `GET_SYMBOL` | macro | `payloads/Shellcode/Include/Macro.h:15` | `#define GET_SYMBOL( x )` |
| `NtCurrentProcess` | macro | `payloads/Shellcode/Include/Macro.h:13` | `#define NtCurrentProcess()` |
| `PPEB_PTR` | macro | `payloads/Shellcode/Include/Macro.h:5` | `#define PPEB_PTR` |
| `PPEB_PTR` | macro | `payloads/Shellcode/Include/Macro.h:7` | `#define PPEB_PTR` |
| `SEC` | macro | `payloads/Shellcode/Include/Macro.h:10` | `#define SEC( s, x )` |
| `U_PTR` | macro | `payloads/Shellcode/Include/Macro.h:11` | `#define U_PTR( x )` |
| `Hash` | function | `payloads/Shellcode/Scripts/Hasher.c:4` | `long Hash( char* String )` |
| `ToUpperString` | function | `payloads/Shellcode/Scripts/Hasher.c:15` | `void ToUpperString(char * temp)` |
| `main` | function | `payloads/Shellcode/Scripts/Hasher.c:24` | `int main(int argc, char** argv)` |
| `IMAGE_REL_TYPE` | macro | `payloads/Shellcode/Source/Entry.c:6` | `#define IMAGE_REL_TYPE` |
| `IMAGE_REL_TYPE` | macro | `payloads/Shellcode/Source/Entry.c:8` | `#define IMAGE_REL_TYPE` |
| `KaynLdrReloc` | function | `payloads/Shellcode/Source/Entry.c:104` | `VOID KaynLdrReloc( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir, DWORD KHdrSize )` |
| `SEC` | function | `payloads/Shellcode/Source/Entry.c:11` | `SEC( text, B ) VOID Entry( VOID )` |
| `SEC` | function | `payloads/Shellcode/Source/Utils.c:4` | `SEC( text, B ) UINT_PTR HashString( LPVOID String, UINT_PTR Length )` |
| `SEC` | function | `payloads/Shellcode/Source/Win32.c:5` | `SEC( text, B ) UINT_PTR LdrModulePeb( UINT_PTR hModuleHash )` |
| `SEC` | function | `payloads/Shellcode/Source/Win32.c:23` | `SEC( text, B ) PVOID LdrFunctionAddr( UINT_PTR Module, UINT_PTR FunctionHash )` |
| `init` | function | `teamserver/cmd/cmd.go:29` | `func init(` |
| `startMenu` | function | `teamserver/cmd/cmd.go:61` | `func startMenu(` |
| `teamserverFunc` | function | `teamserver/cmd/cmd.go:47` | `func teamserverFunc(` |
| `AgentAdd` | function | `teamserver/cmd/server/agent.go:108` | `func (t *Teamserver) AgentAdd(` |
| `AgentCallback` | function | `teamserver/cmd/server/agent.go:220` | `func (t *Teamserver) AgentCallback(` |
| `AgentCallbackSize` | function | `teamserver/cmd/server/agent.go:138` | `func (t *Teamserver) AgentCallbackSize(` |
| `AgentConsole` | function | `teamserver/cmd/server/agent.go:198` | `func (t *Teamserver) AgentConsole(` |
| `AgentExist` | function | `teamserver/cmd/server/agent.go:183` | `func (t *Teamserver) AgentExist(` |
| `AgentHasDied` | function | `teamserver/cmd/server/agent.go:102` | `func (t *Teamserver) AgentHasDied(` |
| `AgentInstance` | function | `teamserver/cmd/server/agent.go:155` | `func (t *Teamserver) AgentInstance(` |
| `AgentLastTimeCalled` | function | `teamserver/cmd/server/agent.go:166` | `func (t *Teamserver) AgentLastTimeCalled(` |
| `AgentSendNotify` | function | `teamserver/cmd/server/agent.go:123` | `func (t *Teamserver) AgentSendNotify(` |
| `AgentUpdate` | function | `teamserver/cmd/server/agent.go:16` | `func (t *Teamserver) AgentUpdate(` |
| `Died` | function | `teamserver/cmd/server/agent.go:23` | `func (t *Teamserver) Died(` |
| `GetDotNetPipeTemplate` | function | `teamserver/cmd/server/agent.go:237` | `func (t *Teamserver) GetDotNetPipeTemplate(` |
| `LinkAdd` | function | `teamserver/cmd/server/agent.go:66` | `func (t *Teamserver) LinkAdd(` |
| `LinkRemove` | function | `teamserver/cmd/server/agent.go:78` | `func (t *Teamserver) LinkRemove(` |
| `LinksOf` | function | `teamserver/cmd/server/agent.go:60` | `func (t *Teamserver) LinksOf(` |
| `ParentOf` | function | `teamserver/cmd/server/agent.go:53` | `func (t *Teamserver) ParentOf(` |
| `PythonModuleCallback` | function | `teamserver/cmd/server/agent.go:208` | `func (t *Teamserver) PythonModuleCallback(` |
| `SendLogs` | function | `teamserver/cmd/server/agent.go:233` | `func (t *Teamserver) SendLogs(` |
| `UnlinkFromAll` | function | `teamserver/cmd/server/agent.go:30` | `func (t *Teamserver) UnlinkFromAll(` |
| `DispatchEvent` | function | `teamserver/cmd/server/dispatch.go:20` | `func (t *Teamserver) DispatchEvent(` |
| `ListenerAdd` | function | `teamserver/cmd/server/listener.go:220` | `func (t *Teamserver) ListenerAdd(` |
| `ListenerEdit` | function | `teamserver/cmd/server/listener.go:192` | `func (t *Teamserver) ListenerEdit(` |
| `ListenerExist` | function | `teamserver/cmd/server/listener.go:113` | `func (t *Teamserver) ListenerExist(` |
| `ListenerGetInfo` | function | `teamserver/cmd/server/listener.go:124` | `func (t *Teamserver) ListenerGetInfo(` |
| `ListenerRemove` | function | `teamserver/cmd/server/listener.go:144` | `func (t *Teamserver) ListenerRemove(` |
| `ListenerServiceExc2Add` | function | `teamserver/cmd/server/listener.go:337` | `func (t *Teamserver) ListenerServiceExc2Add(` |
| `ListenerStart` | function | `teamserver/cmd/server/listener.go:19` | `func (t *Teamserver) ListenerStart(` |
| `ListenerStartNotify` | function | `teamserver/cmd/server/listener.go:378` | `func (t *Teamserver) ListenerStartNotify(` |
| `ServiceAgent` | function | `teamserver/cmd/server/service.go:9` | `func (t *Teamserver) ServiceAgent(` |
| `ServiceAgentExist` | function | `teamserver/cmd/server/service.go:20` | `func (t *Teamserver) ServiceAgentExist(` |
| `ClientAuthenticate` | function | `teamserver/cmd/server/teamserver.go:637` | `func (t *Teamserver) ClientAuthenticate(` |
| `EndpointAdd` | function | `teamserver/cmd/server/teamserver.go:933` | `func (t *Teamserver) EndpointAdd(` |
| `EndpointRemove` | function | `teamserver/cmd/server/teamserver.go:945` | `func (t *Teamserver) EndpointRemove(` |
| `EventAgentMark` | function | `teamserver/cmd/server/teamserver.go:713` | `func (t *Teamserver) EventAgentMark(` |
| `EventAppend` | function | `teamserver/cmd/server/teamserver.go:797` | `func (t *Teamserver) EventAppend(` |
| `EventBroadcast` | function | `teamserver/cmd/server/teamserver.go:690` | `func (t *Teamserver) EventBroadcast(` |
| `EventListenerError` | function | `teamserver/cmd/server/teamserver.go:720` | `func (t *Teamserver) EventListenerError(` |
| `EventNewDemon` | function | `teamserver/cmd/server/teamserver.go:709` | `func (t *Teamserver) EventNewDemon(` |
| `EventRemove` | function | `teamserver/cmd/server/teamserver.go:812` | `func (t *Teamserver) EventRemove(` |
| `FindSystemPackages` | function | `teamserver/cmd/server/teamserver.go:842` | `func (t *Teamserver) FindSystemPackages(` |
| `NewTeamserver` | function | `teamserver/cmd/server/teamserver.go:37` | `func NewTeamserver(` |
| `RemoveClient` | function | `teamserver/cmd/server/teamserver.go:773` | `func (t *Teamserver) RemoveClient(` |
| `SendAllPackagesToNewClient` | function | `teamserver/cmd/server/teamserver.go:818` | `func (t *Teamserver) SendAllPackagesToNewClient(` |
| `SendEvent` | function | `teamserver/cmd/server/teamserver.go:741` | `func (t *Teamserver) SendEvent(` |
| `SetProfile` | function | `teamserver/cmd/server/teamserver.go:626` | `func (t *Teamserver) SetProfile(` |
| `SetServerFlags` | function | `teamserver/cmd/server/teamserver.go:48` | `func (t *Teamserver) SetServerFlags(` |
| `Start` | function | `teamserver/cmd/server/teamserver.go:52` | `func (t *Teamserver) Start(` |
| `handleRequest` | function | `teamserver/cmd/server/teamserver.go:497` | `func (t *Teamserver) handleRequest(` |
| `Client` | struct | `teamserver/cmd/server/types.go:22` | `` |
| `Endpoint` | struct | `teamserver/cmd/server/types.go:68` | `` |
| `Listener` | struct | `teamserver/cmd/server/types.go:16` | `` |
| `Teamserver` | struct | `teamserver/cmd/server/types.go:73` | `` |
| `TeamserverFlags` | struct | `teamserver/cmd/server/types.go:63` | `` |
| `Users` | struct | `teamserver/cmd/server/types.go:34` | `` |
| `serverFlags` | struct | `teamserver/cmd/server/types.go:41` | `` |
| `utilFlags` | struct | `teamserver/cmd/server/types.go:53` | `` |
| `main` | function | `teamserver/main.go:6` | `func main(` |
| `AddJobToQueue` | function | `teamserver/pkg/agent/agent.go:647` | `func (a *Agent) AddJobToQueue(` |
| `AddRequest` | function | `teamserver/pkg/agent/agent.go:632` | `func (a *Agent) AddRequest(` |
| `AgentsAppend` | function | `teamserver/pkg/agent/agent.go:1238` | `func (agents *Agents) AgentsAppend(` |
| `BuildPayloadMessage` | function | `teamserver/pkg/agent/agent.go:29` | `func BuildPayloadMessage(` |
| `DownloadAdd` | function | `teamserver/pkg/agent/agent.go:816` | `func (a *Agent) DownloadAdd(` |
| `DownloadClose` | function | `teamserver/pkg/agent/agent.go:888` | `func (a *Agent) DownloadClose(` |
| `DownloadGet` | function | `teamserver/pkg/agent/agent.go:902` | `func (a *Agent) DownloadGet(` |
| `DownloadWrite` | function | `teamserver/pkg/agent/agent.go:865` | `func (a *Agent) DownloadWrite(` |
| `GetQueuedJobs` | function | `teamserver/pkg/agent/agent.go:661` | `func (a *Agent) GetQueuedJobs(` |
| `IsKnownRequestID` | function | `teamserver/pkg/agent/agent.go:609` | `func (a *Agent) IsKnownRequestID(` |
| `ParseDemonRegisterRequest` | function | `teamserver/pkg/agent/agent.go:328` | `func ParseDemonRegisterRequest(` |
| `ParseHeader` | function | `teamserver/pkg/agent/agent.go:181` | `func ParseHeader(` |
| `PivotAddJob` | function | `teamserver/pkg/agent/agent.go:746` | `func (a *Agent) PivotAddJob(` |
| `PortFwdClose` | function | `teamserver/pkg/agent/agent.go:1023` | `func (a *Agent) PortFwdClose(` |
| `PortFwdGet` | function | `teamserver/pkg/agent/agent.go:929` | `func (a *Agent) PortFwdGet(` |
| `PortFwdIsOpen` | function | `teamserver/pkg/agent/agent.go:948` | `func (a *Agent) PortFwdIsOpen(` |
| `PortFwdNew` | function | `teamserver/pkg/agent/agent.go:911` | `func (a *Agent) PortFwdNew(` |
| `PortFwdOpen` | function | `teamserver/pkg/agent/agent.go:958` | `func (a *Agent) PortFwdOpen(` |
| `PortFwdRead` | function | `teamserver/pkg/agent/agent.go:997` | `func (a *Agent) PortFwdRead(` |
| `PortFwdWrite` | function | `teamserver/pkg/agent/agent.go:979` | `func (a *Agent) PortFwdWrite(` |
| `RegisterInfoToInstance` | function | `teamserver/pkg/agent/agent.go:215` | `func RegisterInfoToInstance(` |
| `RequestCompleted` | function | `teamserver/pkg/agent/agent.go:638` | `func (a *Agent) RequestCompleted(` |
| `SocksClientAdd` | function | `teamserver/pkg/agent/agent.go:1053` | `func (a *Agent) SocksClientAdd(` |
| `SocksClientClose` | function | `teamserver/pkg/agent/agent.go:1130` | `func (a *Agent) SocksClientClose(` |
| `SocksClientGet` | function | `teamserver/pkg/agent/agent.go:1073` | `func (a *Agent) SocksClientGet(` |
| `SocksClientRead` | function | `teamserver/pkg/agent/agent.go:1096` | `func (a *Agent) SocksClientRead(` |
| `SocksServerRemove` | function | `teamserver/pkg/agent/agent.go:1163` | `func (a *Agent) SocksServerRemove(` |
| `ToJson` | function | `teamserver/pkg/agent/agent.go:1224` | `func (a *Agent) ToJson(` |
| `ToMap` | function | `teamserver/pkg/agent/agent.go:1193` | `func (a *Agent) ToMap(` |
| `UpdateLastCallback` | function | `teamserver/pkg/agent/agent.go:739` | `func (a *Agent) UpdateLastCallback(` |
| `getWindowsVersionString` | function | `teamserver/pkg/agent/agent.go:1243` | `func getWindowsVersionString(` |
| `Console` | function | `teamserver/pkg/agent/demons.go:6430` | `func (a *Agent) Console(` |
| `TaskDispatch` | function | `teamserver/pkg/agent/demons.go:2285` | `func (a *Agent) TaskDispatch(` |
| `TaskPrepare` | function | `teamserver/pkg/agent/demons.go:128` | `func (a *Agent) TaskPrepare(` |
| `TeamserverTaskPrepare` | function | `teamserver/pkg/agent/demons.go:64` | `func (a *Agent) TeamserverTaskPrepare(` |
| `UploadMemFileInChunks` | function | `teamserver/pkg/agent/demons.go:31` | `func (a *Agent) UploadMemFileInChunks(` |
| `Agent` | struct | `teamserver/pkg/agent/types.go:139` | `` |
| `AgentInfo` | struct | `teamserver/pkg/agent/types.go:174` | `` |
| `Agents` | struct | `teamserver/pkg/agent/types.go:212` | `` |
| `BofCallback` | struct | `teamserver/pkg/agent/types.go:104` | `` |
| `DemonInterface` | interface | `teamserver/pkg/agent/types.go:19` | `` |
| `Download` | struct | `teamserver/pkg/agent/types.go:94` | `` |
| `EventInterface` | interface | `teamserver/pkg/agent/types.go:23` | `` |
| `Header` | struct | `teamserver/pkg/agent/types.go:26` | `` |
| `Job` | struct | `teamserver/pkg/agent/types.go:73` | `` |
| `Pivots` | struct | `teamserver/pkg/agent/types.go:89` | `` |
| `PortFwd` | struct | `teamserver/pkg/agent/types.go:111` | `` |
| `ServiceAgentInterface` | interface | `teamserver/pkg/agent/types.go:33` | `` |
| `SocksClient` | struct | `teamserver/pkg/agent/types.go:124` | `` |
| `SocksServer` | struct | `teamserver/pkg/agent/types.go:133` | `` |
| `TeamServer` | interface | `teamserver/pkg/agent/types.go:40` | `` |
| `Build` | function | `teamserver/pkg/common/builder/builder.go:217` | `func (b *Builder) Build(` |
| `Builder` | struct | `teamserver/pkg/common/builder/builder.go:78` | `` |
| `BuilderConfig` | struct | `teamserver/pkg/common/builder/builder.go:70` | `` |
| `Cmd` | function | `teamserver/pkg/common/builder/builder.go:1064` | `func (b *Builder) Cmd(` |
| `CompileCmd` | function | `teamserver/pkg/common/builder/builder.go:1090` | `func (b *Builder) CompileCmd(` |
| `DeletePayload` | function | `teamserver/pkg/common/builder/builder.go:1122` | `func (b *Builder) DeletePayload(` |
| `GetListenerDefines` | function | `teamserver/pkg/common/builder/builder.go:1102` | `func (b *Builder) GetListenerDefines(` |
| `GetOutputPath` | function | `teamserver/pkg/common/builder/builder.go:509` | `func (b *Builder) GetOutputPath(` |
| `GetPayloadBytes` | function | `teamserver/pkg/common/builder/builder.go:1024` | `func (b *Builder) GetPayloadBytes(` |
| `NewBuilder` | function | `teamserver/pkg/common/builder/builder.go:141` | `func NewBuilder(` |
| `Patch` | function | `teamserver/pkg/common/builder/builder.go:513` | `func (b *Builder) Patch(` |
| `PatchConfig` | function | `teamserver/pkg/common/builder/builder.go:561` | `func (b *Builder) PatchConfig(` |
| `SetArch` | function | `teamserver/pkg/common/builder/builder.go:485` | `func (b *Builder) SetArch(` |
| `SetConfig` | function | `teamserver/pkg/common/builder/builder.go:489` | `func (b *Builder) SetConfig(` |
| `SetExtension` | function | `teamserver/pkg/common/builder/builder.go:505` | `func (b *Builder) SetExtension(` |
| `SetFormat` | function | `teamserver/pkg/common/builder/builder.go:481` | `func (b *Builder) SetFormat(` |
| `SetListener` | function | `teamserver/pkg/common/builder/builder.go:459` | `func (b *Builder) SetListener(` |
| `SetOutputPath` | function | `teamserver/pkg/common/builder/builder.go:501` | `func (b *Builder) SetOutputPath(` |
| `SetPatchConfig` | function | `teamserver/pkg/common/builder/builder.go:464` | `func (b *Builder) SetPatchConfig(` |
| `SetSilent` | function | `teamserver/pkg/common/builder/builder.go:213` | `func (b *Builder) SetSilent(` |
| `HTTPSGenerateRSACertificate` | function | `teamserver/pkg/common/certs/https.go:300` | `func HTTPSGenerateRSACertificate(` |
| `generateCertificate` | function | `teamserver/pkg/common/certs/https.go:216` | `func generateCertificate(` |
| `pemBlockForKey` | function | `teamserver/pkg/common/certs/https.go:200` | `func pemBlockForKey(` |
| `publicKey` | function | `teamserver/pkg/common/certs/https.go:182` | `func publicKey(` |
| `randomInt` | function | `teamserver/pkg/common/certs/https.go:193` | `func randomInt(` |
| `randomLocality` | function | `teamserver/pkg/common/certs/https.go:123` | `func randomLocality(` |
| `randomOrganization` | function | `teamserver/pkg/common/certs/https.go:166` | `func randomOrganization(` |
| `randomPostalCode` | function | `teamserver/pkg/common/certs/https.go:144` | `func randomPostalCode(` |
| `randomProvinceLocalityStreetAddress` | function | `teamserver/pkg/common/certs/https.go:137` | `func randomProvinceLocalityStreetAddress(` |
| `randomState` | function | `teamserver/pkg/common/certs/https.go:115` | `func randomState(` |
| `randomStreetAddress` | function | `teamserver/pkg/common/certs/https.go:132` | `func randomStreetAddress(` |
| `randomSubject` | function | `teamserver/pkg/common/certs/https.go:153` | `func randomSubject(` |
| `XCryptBytesAES256` | function | `teamserver/pkg/common/crypt/aes.go:10` | `func XCryptBytesAES256(` |
| `AddBytes` | function | `teamserver/pkg/common/packer/packer.go:70` | `func (p *Packer) AddBytes(` |
| `AddInt` | function | `teamserver/pkg/common/packer/packer.go:45` | `func (p *Packer) AddInt(` |
| `AddInt32` | function | `teamserver/pkg/common/packer/packer.go:37` | `func (p *Packer) AddInt32(` |
| `AddInt64` | function | `teamserver/pkg/common/packer/packer.go:29` | `func (p *Packer) AddInt64(` |
| `AddOwnSizeFirst` | function | `teamserver/pkg/common/packer/packer.go:103` | `func (p *Packer) AddOwnSizeFirst(` |
| `AddString` | function | `teamserver/pkg/common/packer/packer.go:62` | `func (p *Packer) AddString(` |
| `AddUInt32` | function | `teamserver/pkg/common/packer/packer.go:54` | `func (p *Packer) AddUInt32(` |
| `AddWString` | function | `teamserver/pkg/common/packer/packer.go:66` | `func (p *Packer) AddWString(` |
| `Buffer` | function | `teamserver/pkg/common/packer/packer.go:95` | `func (p *Packer) Buffer(` |
| `Build` | function | `teamserver/pkg/common/packer/packer.go:80` | `func (p *Packer) Build(` |
| `NewPacker` | function | `teamserver/pkg/common/packer/packer.go:22` | `func NewPacker(` |
| `Packer` | struct | `teamserver/pkg/common/packer/packer.go:14` | `` |
| `Size` | function | `teamserver/pkg/common/packer/packer.go:99` | `func (p *Packer) Size(` |
| `Buffer` | function | `teamserver/pkg/common/parser/parser.go:201` | `func (p *Parser) Buffer(` |
| `CanIRead` | function | `teamserver/pkg/common/parser/parser.go:31` | `func (p *Parser) CanIRead(` |
| `DecryptBuffer` | function | `teamserver/pkg/common/parser/parser.go:205` | `func (p *Parser) DecryptBuffer(` |
| `Length` | function | `teamserver/pkg/common/parser/parser.go:197` | `func (p *Parser) Length(` |
| `NewParser` | function | `teamserver/pkg/common/parser/parser.go:24` | `func NewParser(` |
| `ParseAtLeastBytes` | function | `teamserver/pkg/common/parser/parser.go:177` | `func (p *Parser) ParseAtLeastBytes(` |
| `ParseBool` | function | `teamserver/pkg/common/parser/parser.go:130` | `func (p *Parser) ParseBool(` |
| `ParseBytes` | function | `teamserver/pkg/common/parser/parser.go:162` | `func (p *Parser) ParseBytes(` |
| `ParseInt32` | function | `teamserver/pkg/common/parser/parser.go:82` | `func (p *Parser) ParseInt32(` |
| `ParseInt64` | function | `teamserver/pkg/common/parser/parser.go:106` | `func (p *Parser) ParseInt64(` |
| `ParsePointer` | function | `teamserver/pkg/common/parser/parser.go:154` | `func (p *Parser) ParsePointer(` |
| `ParseString` | function | `teamserver/pkg/common/parser/parser.go:193` | `func (p *Parser) ParseString(` |
| `ParseUTF16String` | function | `teamserver/pkg/common/parser/parser.go:189` | `func (p *Parser) ParseUTF16String(` |
| `Parser` | struct | `teamserver/pkg/common/parser/parser.go:19` | `` |
| `SetBigEndian` | function | `teamserver/pkg/common/parser/parser.go:158` | `func (p *Parser) SetBigEndian(` |
| `Bmp2Png` | function | `teamserver/pkg/common/util.go:76` | `func Bmp2Png(` |
| `ByteCountSI` | function | `teamserver/pkg/common/util.go:144` | `func ByteCountSI(` |
| `DecodeUTF16` | function | `teamserver/pkg/common/util.go:99` | `func DecodeUTF16(` |
| `EncodeUTF16` | function | `teamserver/pkg/common/util.go:118` | `func EncodeUTF16(` |
| `EncodeUTF8` | function | `teamserver/pkg/common/util.go:135` | `func EncodeUTF8(` |
| `EpochTimeToSystemTime` | function | `teamserver/pkg/common/util.go:209` | `func EpochTimeToSystemTime(` |
| `GeneratePipeName` | function | `teamserver/pkg/common/util.go:227` | `func GeneratePipeName(` |
| `GetInterfaceIpv4Addr` | function | `teamserver/pkg/common/util.go:279` | `func GetInterfaceIpv4Addr(` |
| `GetRandomChar` | function | `teamserver/pkg/common/util.go:222` | `func GetRandomChar(` |
| `Int32ToIpString` | function | `teamserver/pkg/common/util.go:198` | `func Int32ToIpString(` |
| `Int32ToLittle` | function | `teamserver/pkg/common/util.go:175` | `func Int32ToLittle(` |
| `IpStringToInt32` | function | `teamserver/pkg/common/util.go:189` | `func IpStringToInt32(` |
| `ParseWorkingHours` | function | `teamserver/pkg/common/util.go:26` | `func ParseWorkingHours(` |
| `PercentageChange` | function | `teamserver/pkg/common/util.go:185` | `func PercentageChange(` |
| `RandomString` | function | `teamserver/pkg/common/util.go:166` | `func RandomString(` |
| `StripNull` | function | `teamserver/pkg/common/util.go:181` | `func StripNull(` |
| `XorCipher` | function | `teamserver/pkg/common/util.go:158` | `func XorCipher(` |
| `AgentAdd` | function | `teamserver/pkg/db/agents.go:12` | `func (db *DB) AgentAdd(` |
| `AgentAll` | function | `teamserver/pkg/db/agents.go:211` | `func (db *DB) AgentAll(` |
| `AgentExist` | function | `teamserver/pkg/db/agents.go:163` | `func (db *DB) AgentExist(` |
| `AgentHasDied` | function | `teamserver/pkg/db/agents.go:145` | `func (db *DB) AgentHasDied(` |
| `AgentRemove` | function | `teamserver/pkg/db/agents.go:192` | `func (db *DB) AgentRemove(` |
| `AgentUpdate` | function | `teamserver/pkg/db/agents.go:81` | `func (db *DB) AgentUpdate(` |
| `DB` | struct | `teamserver/pkg/db/db.go:10` | `` |
| `DatabaseNew` | function | `teamserver/pkg/db/db.go:16` | `func DatabaseNew(` |
| `Existed` | function | `teamserver/pkg/db/db.go:69` | `func (db *DB) Existed(` |
| `Path` | function | `teamserver/pkg/db/db.go:73` | `func (db *DB) Path(` |
| `init` | function | `teamserver/pkg/db/db.go:48` | `func (db *DB) init(` |
| `LinkAdd` | function | `teamserver/pkg/db/links.go:8` | `func (db *DB) LinkAdd(` |
| `LinkExist` | function | `teamserver/pkg/db/links.go:46` | `func (db *DB) LinkExist(` |
| `LinkRemove` | function | `teamserver/pkg/db/links.go:136` | `func (db *DB) LinkRemove(` |
| `LinksOf` | function | `teamserver/pkg/db/links.go:104` | `func (db *DB) LinksOf(` |
| `ParentOf` | function | `teamserver/pkg/db/links.go:75` | `func (db *DB) ParentOf(` |
| `ListenerAdd` | function | `teamserver/pkg/db/listeners.go:8` | `func (db *DB) ListenerAdd(` |
| `ListenerAll` | function | `teamserver/pkg/db/listeners.go:66` | `func (db *DB) ListenerAll(` |
| `ListenerCount` | function | `teamserver/pkg/db/listeners.go:107` | `func (db *DB) ListenerCount(` |
| `ListenerExist` | function | `teamserver/pkg/db/listeners.go:46` | `func (db *DB) ListenerExist(` |
| `ListenerNames` | function | `teamserver/pkg/db/listeners.go:126` | `func (db *DB) ListenerNames(` |
| `ListenerRemove` | function | `teamserver/pkg/db/listeners.go:152` | `func (db *DB) ListenerRemove(` |
| `NewUserConnected` | function | `teamserver/pkg/events/chatlog.go:11` | `func (chatLog) NewUserConnected(` |
| `UserDisconnected` | function | `teamserver/pkg/events/chatlog.go:27` | `func (chatLog) UserDisconnected(` |
| `CallBack` | function | `teamserver/pkg/events/demons.go:105` | `func (demons) CallBack(` |
| `DemonOutput` | function | `teamserver/pkg/events/demons.go:83` | `func (demons) DemonOutput(` |
| `MarkAs` | function | `teamserver/pkg/events/demons.go:121` | `func (demons) MarkAs(` |
| `NewDemon` | function | `teamserver/pkg/events/demons.go:19` | `func (demons) NewDemon(` |
| `Authenticated` | function | `teamserver/pkg/events/events.go:22` | `func Authenticated(` |

Next: [SYMBOLS_p11.md](SYMBOLS_p11.md)
