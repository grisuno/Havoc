# API (page 5 of 8)
Previous: [API_p4.md](API_p4.md)

## payloads/Demon/src/core/Token.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`
- `TokenDuplicate` (function) `payloads/Demon/src/core/Token.c:37` `BOOL TokenDuplicate(
    IN  HANDLE        TokenOriginal,
    IN  DWORD         Access,
    IN  S...` -- ! @brief Duplicate given token  @param TokenOriginal @param Access @param ImpersonateLevel @param TokenType @param...
- `TokenRevSelf` (function) `payloads/Demon/src/core/Token.c:74` `BOOL TokenRevSelf(
    VOID
)` -- ! @brief reverse to the original process user token  @return if successful reverse to original token
- `TokenQueryOwner` (function) `payloads/Demon/src/core/Token.c:103` `BOOL TokenQueryOwner(
    IN  HANDLE  Token,
    OUT PBUFFER UserDomain,
    IN  DWORD   Flags
)` -- ! @brief queries the username and or domain  @note the queried memory should be freed after used using...
- `PUTS` (function) `payloads/Demon/src/core/Token.c:177` `PUTS( "Unexpected successful call to NtQueryInformationToken.\n" )
    }

LEAVE:
    if ( UserInfo )`
- `DATA_FREE` (function) `payloads/Demon/src/core/Token.c:182` `DATA_FREE( UserInfo, UserSize )
    }

    if ( Flags == TOKEN_OWNER_FLAG_USER )`
- `TokenSetPrivilege` (function) `payloads/Demon/src/core/Token.c:203` `BOOL TokenSetPrivilege(
    IN LPSTR Privilege,
    IN BOOL  Enable
)` -- ! sets a privilege  TODO: change it to use wide strings.  @param Privilege @param Enable @return
- `TokenSetSeDebugPriv` (function) `payloads/Demon/src/core/Token.c:240` `BOOL TokenSetSeDebugPriv(
    IN BOOL  Enable
)`
- `TokenSetSeImpersonatePriv` (function) `payloads/Demon/src/core/Token.c:271` `BOOL TokenSetSeImpersonatePriv(
    IN BOOL  Enable
)`
- `TokenAdd` (function) `payloads/Demon/src/core/Token.c:323` `DWORD TokenAdd(
    IN HANDLE hToken,
    IN LPWSTR DomainUser,
    IN SHORT  Type,
    IN DWORD ...` -- Adds an token to the vault.
- `SysDuplicateTokenEx` (function) `payloads/Demon/src/core/Token.c:365` `BOOL SysDuplicateTokenEx(
    IN HANDLE ExistingTokenHandle,
    IN DWORD dwDesiredAccess,
    IN...`
- `TokenSteal` (function) `payloads/Demon/src/core/Token.c:414` `HANDLE TokenSteal(
    IN DWORD  ProcessID,
    IN HANDLE TargetHandle
)` -- !
- `PRINTF` (function) `payloads/Demon/src/core/Token.c:463` `PRINTF( "ProcessOpen: Failed:[%ld]\n", NtGetLastError() )
        PACKAGE_ERROR_WIN32
    }

    ...`
- `TokenRemove` (function) `payloads/Demon/src/core/Token.c:474` `BOOL TokenRemove( DWORD TokenID )`
- `TokenMake` (function) `payloads/Demon/src/core/Token.c:598` `HANDLE TokenMake( LPWSTR User, LPWSTR Password, LPWSTR Domain, DWORD LogonType )`
- `PRINTF` (function) `payloads/Demon/src/core/Token.c:602` `PRINTF( "TokenMake( %ls, %ls, %ls, %d )\n", User, Password, Domain, LogonType )

    if ( ! Token...`
- `PRINTF` (function) `payloads/Demon/src/core/Token.c:606` `PRINTF( "Failed to revert to self: Error:[%d]\n", NtGetLastError() )
        PACKAGE_ERROR_WIN32
...`
- `TokenCurrentHandle` (function) `payloads/Demon/src/core/Token.c:624` `HANDLE TokenCurrentHandle(
    VOID
)` -- ! get current process/thread token @return
- `TokenElevated` (function) `payloads/Demon/src/core/Token.c:650` `BOOL TokenElevated(
    IN HANDLE Token
)`
- `TokenGet` (function) `payloads/Demon/src/core/Token.c:664` `PTOKEN_LIST_DATA TokenGet(
    IN DWORD TokenID
)`
- `TokenClear` (function) `payloads/Demon/src/core/Token.c:681` `VOID TokenClear(
    VOID
)`
- `TokenImpersonate` (function) `payloads/Demon/src/core/Token.c:707` `BOOL TokenImpersonate(
    IN BOOL Impersonate
)`
- `AddUserToken` (function) `payloads/Demon/src/core/Token.c:733` `VOID AddUserToken(
    _Inout_ PUSER_TOKEN_DATA NewToken,
    _Inout_ PUSER_TOKEN_DATA Tokens,
  ...`
- `IsImpersonationToken` (function) `payloads/Demon/src/core/Token.c:771` `BOOL IsImpersonationToken( HANDLE token )`
- `CanTokenBeImpersonated` (function) `payloads/Demon/src/core/Token.c:802` `BOOL CanTokenBeImpersonated( IN HANDLE hToken )` -- https://github.com/rapid7/metasploit-payloads/blob/master/c/meterpreter/source/extensions/incognito/list_tokens.c
- `ProcessUserToken` (function) `payloads/Demon/src/core/Token.c:830` `VOID ProcessUserToken(
    IN HANDLE hToken,
    IN DWORD ProcessId,
    IN HANDLE handle,
    IN...`
- `QueryObjectTypesInfo` (function) `payloads/Demon/src/core/Token.c:878` `BOOL QueryObjectTypesInfo( POBJECT_TYPES_INFORMATION* pObjectTypes, PULONG pObjectTypesSize )` -- call NtQueryObject with ObjectTypesInformation
- `GetTypeIndexToken` (function) `payloads/Demon/src/core/Token.c:910` `BOOL GetTypeIndexToken( OUT PULONG TokenTypeIndex )` -- get index of object type 'Token'
- `GetTokenInfo` (function) `payloads/Demon/src/core/Token.c:949` `BOOL GetTokenInfo(
    IN HANDLE hToken,
    OUT PDWORD pTokenType,
    OUT PDWORD pIntegrity,
  ...`
- `PUTS` (function) `payloads/Demon/src/core/Token.c:991` `PUTS( "GetTokenInformation failed" )
            }
        }
        else if (TokenStatisticsInfo...`
- `ProcessIsIncluded` (function) `payloads/Demon/src/core/Token.c:1029` `BOOL ProcessIsIncluded( IN PPROCESS_LIST process_list, IN ULONG ProcessId )` -- check if a PID is included in the process list
- `GetProcessesFromHandleTable` (function) `payloads/Demon/src/core/Token.c:1040` `BOOL GetProcessesFromHandleTable( IN PSYSTEM_HANDLE_INFORMATION handleTableInformation, OUT PPROC...` -- obtain a list of PIDs from a handle table
- `GetAllHandles` (function) `payloads/Demon/src/core/Token.c:1076` `BOOL GetAllHandles( OUT PSYSTEM_HANDLE_INFORMATION* phandle_table, OUT PULONG phandle_table_size )` -- get all handles in the system
- `IsNotCurrentUser` (function) `payloads/Demon/src/core/Token.c:1122` `BOOL IsNotCurrentUser( BOOL DoCheck, PBUFFER UserA, PBUFFER UserB )` -- phandle_table = (PSYSTEM_HANDLE_INFORMATION)handleTableInformation; phandle_table_size = buffer_size; ret_val =...
- `ListTokens` (function) `payloads/Demon/src/core/Token.c:1130` `BOOL ListTokens( PUSER_TOKEN_DATA* pTokens, PDWORD pNumTokens )`
- `ImpersonateTokenFromVault` (function) `payloads/Demon/src/core/Token.c:1257` `BOOL ImpersonateTokenFromVault(
    IN DWORD TokenID
)`
- `SysImpersonateLoggedOnUser` (function) `payloads/Demon/src/core/Token.c:1281` `BOOL SysImpersonateLoggedOnUser( HANDLE hToken )` -- https://doxygen.reactos.org/d1/d72/dll_2win32_2advapi32_2sec_2misc_8c_source.html#l00152
- `ImpersonateTokenInStore` (function) `payloads/Demon/src/core/Token.c:1361` `BOOL ImpersonateTokenInStore(
    IN PTOKEN_LIST_DATA TokenData
)`

## payloads/Demon/src/core/Transport.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportHttp.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`
- `TransportInit` (function) `payloads/Demon/src/core/Transport.c:13` `BOOL TransportInit( )`
- `TransportSend` (function) `payloads/Demon/src/core/Transport.c:52` `BOOL TransportSend( LPVOID Data, SIZE_T Size, PVOID* RecvData, PSIZE_T RecvSize )`
- `SMBGetJob` (function) `payloads/Demon/src/core/Transport.c:89` `BOOL SMBGetJob( PVOID* RecvData, PSIZE_T RecvSize )`

## payloads/Demon/src/core/TransportHttp.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportHttp.h`
- `HttpSend` (function) `payloads/Demon/src/core/TransportHttp.c:21` `BOOL HttpSend(
    _In_      PBUFFER Send,
    _Out_opt_ PBUFFER Resp
)` -- ! @brief send a http request  @param Send buffer to send  @param Resp buffer response  @return if successful send...
- `PRINTF_DONT_SEND` (function) `payloads/Demon/src/core/TransportHttp.c:291` `PRINTF_DONT_SEND( "HTTP Error: %d\n", NtGetLastError() )
    }

LEAVE:
    if ( Connect )`
- `HttpQueryStatus` (function) `payloads/Demon/src/core/TransportHttp.c:336` `DWORD HttpQueryStatus(
    _In_ HANDLE Request
)` -- ! @brief Query the Http Status code from the request response.  @param hRequest request handle  @return Http status code
- `HostAdd` (function) `payloads/Demon/src/core/TransportHttp.c:356` `PHOST_DATA HostAdd(
    _In_ LPWSTR Host, SIZE_T Size, DWORD Port )`
- `HostFailure` (function) `payloads/Demon/src/core/TransportHttp.c:378` `PHOST_DATA HostFailure( PHOST_DATA Host )`
- `HostRandom` (function) `payloads/Demon/src/core/TransportHttp.c:402` `PHOST_DATA HostRandom()` -- /* Get our next host based on our rotation strategy. return HostRotation( Instance->Config.Transport.HostRotation )...
- `HostRotation` (function) `payloads/Demon/src/core/TransportHttp.c:437` `PHOST_DATA HostRotation( SHORT Strategy )`
- `HostCount` (function) `payloads/Demon/src/core/TransportHttp.c:514` `DWORD HostCount()`
- `HostCheckup` (function) `payloads/Demon/src/core/TransportHttp.c:541` `BOOL HostCheckup()`

## payloads/Demon/src/core/TransportSmb.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportSmb.h`
- `SmbSend` (function) `payloads/Demon/src/core/TransportSmb.c:8` `BOOL SmbSend( PBUFFER Send )`
- `SmbRecv` (function) `payloads/Demon/src/core/TransportSmb.c:65` `BOOL SmbRecv( PBUFFER Resp )`
- `PRINTF` (function) `payloads/Demon/src/core/TransportSmb.c:107` `PRINTF( "PipeRead failed with to read 0x%x bytes from pipe\n", Resp->Length )
                if ...`
- `SmbSecurityAttrOpen` (function) `payloads/Demon/src/core/TransportSmb.c:142` `VOID SmbSecurityAttrOpen( PSMB_PIPE_SEC_ATTR SmbSecAttr, PSECURITY_ATTRIBUTES SecurityAttr )` -- Took it from https://github.com/rapid7/metasploit-payloads/blob/master/c/meterpreter/source/metsrv/server_pivot_named...
- `SmbSecurityAttrFree` (function) `payloads/Demon/src/core/TransportSmb.c:213` `VOID SmbSecurityAttrFree( PSMB_PIPE_SEC_ATTR SmbSecAttr )`

## payloads/Demon/src/core/Win32.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`
- `HashEx` (function) `payloads/Demon/src/core/Win32.c:17` `ULONG HashEx(
    IN PVOID String,
    IN ULONG Length,
    IN BOOL  Upper
)` -- !
- `LdrModulePeb` (function) `payloads/Demon/src/core/Win32.c:65` `PVOID LdrModulePeb(
    IN DWORD Hash
)` -- ! load module from PEB InLoadOrderModuleList by Hash @param Hash @return
- `LdrModulePebByString` (function) `payloads/Demon/src/core/Win32.c:99` `PVOID LdrModulePebByString(
    IN LPWSTR Module
)` -- ! load module from PEB InLoadOrderModuleList by String @param Module name of module (needs to be upper case...
- `LdrModuleSearch` (function) `payloads/Demon/src/core/Win32.c:165` `PVOID LdrModuleSearch(
    IN LPWSTR ModuleName)` -- !
- `LdrModuleLoad` (function) `payloads/Demon/src/core/Win32.c:215` `PVOID LdrModuleLoad(
    IN LPSTR ModuleName
)` -- !
- `PUTS` (function) `payloads/Demon/src/core/Win32.c:252` `PUTS( "Loading module using RtlRegisterWait" )

            /* create an event for end of module ...`
- `PUTS` (function) `payloads/Demon/src/core/Win32.c:269` `PUTS( "Loading module using RtlCreateTimer" )

            /* create timer queue */
            i...`
- `PUTS` (function) `payloads/Demon/src/core/Win32.c:286` `PUTS( "Loading module using RtlQueueWorkItem" )

            /* call LoadLibraryW and load specif...`
- `PRINTF` (function) `payloads/Demon/src/core/Win32.c:354` `PRINTF( "Module \"%s\": %p\n", ModuleName, Module )

    /* close event end */
    if ( Event )`
- `LdrFunctionAddr` (function) `payloads/Demon/src/core/Win32.c:377` `PVOID LdrFunctionAddr(
    IN PVOID Module,
    IN DWORD Hash
)` -- ! gets the function pointer @param Module @param FunctionHash @return
- `GetSyscallSize` (function) `payloads/Demon/src/core/Win32.c:440` `UINT32 GetSyscallSize(
    VOID
)` -- Get the size of an NtApi by finding two consecutive syscalls and returning the difference of their addresses.
- `ProcessOpen` (function) `payloads/Demon/src/core/Win32.c:515` `HANDLE ProcessOpen(
    IN DWORD Pid,
    IN DWORD Access
)` -- ! opens a handle to the specified pid with specified access @param ProcessID @param Access @return
- `ProcessIsWow` (function) `payloads/Demon/src/core/Win32.c:544` `BOOL ProcessIsWow(
    IN HANDLE Process
)` -- ! checks if a process runs under Wow64 @param Process @return
- `ProcessCreate` (function) `payloads/Demon/src/core/Win32.c:579` `BOOL ProcessCreate(
    IN  BOOL                 x86,
    IN  LPWSTR               App,
    IN  L...` -- !
- `PUTS` (function) `payloads/Demon/src/core/Win32.c:626` `PUTS( "Enable Wow64 process support" )
        if ( ! Instance->Win32.Wow64DisableWow64FsRedirect...`
- `PRINTF` (function) `payloads/Demon/src/core/Win32.c:654` `PRINTF( "CmdLine           : %ls\n", CmdLine )
        PRINTF( "lpCurrentDirectory: %ls\n", lpCur...`
- `PUTS` (function) `payloads/Demon/src/core/Win32.c:671` `PUTS( "CreateProcessWithTokenW" )
            if ( ! Instance->Win32.CreateProcessWithTokenW(
   ...`
- `PUTS` (function) `payloads/Demon/src/core/Win32.c:693` `PUTS( "CreateProcessWithLogonW" )
            PRINTF( "lpUser[%s] lpDomain[%s] lpPassword[%s]", I...`
- `PUTS` (function) `payloads/Demon/src/core/Win32.c:739` `PUTS( "Send info back" )
        if ( ! CmdLine )`
- `ProcessTerminate` (function) `payloads/Demon/src/core/Win32.c:806` `BOOL ProcessTerminate(
    IN HANDLE hProcess,
    IN DWORD  Pid)`
- `PUTS` (function) `payloads/Demon/src/core/Win32.c:831` `PUTS( "Failed to terminate process" )
    }

END:
    if ( OpenedHandle )`
- `ProcessSnapShot` (function) `payloads/Demon/src/core/Win32.c:848` `NTSTATUS ProcessSnapShot(
    OUT PSYSTEM_PROCESS_INFORMATION* SnapShot,
    OUT PSIZE_T         ...` -- ! takes a snapshot of current running processes @param SnapShot @param Size @return
- `ReadLocalFile` (function) `payloads/Demon/src/core/Win32.c:886` `BOOL ReadLocalFile(
    IN  LPCWSTR FileName,
    OUT PVOID*  FileContent,
    OUT PDWORD  FileSi...`
- `BypassPatchAMSI` (function) `payloads/Demon/src/core/Win32.c:930` `BOOL BypassPatchAMSI(
    VOID
)` -- Patch AMSI * TODO: remove this and replace it with hardware breakpoints
- `AnonPipesInit` (function) `payloads/Demon/src/core/Win32.c:981` `BOOL AnonPipesInit(
    IN PANONPIPE AnonPipes
)`
- `AnonPipesRead` (function) `payloads/Demon/src/core/Win32.c:1000` `VOID AnonPipesRead(
    IN PANONPIPE AnonPipes,
    IN UINT32 RequestID
)` -- ! reads from the specified anonymous pipe and sends the result back to the teamserver @param AnonPipes @param RequestID
- `PUTS` (function) `payloads/Demon/src/core/Win32.c:1011` `PUTS( "Start reading anon pipe" )
    PRINTF( "AnonPipes->StdOutRead => %x\n", AnonPipes->StdOutR...`
- `PRINTF` (function) `payloads/Demon/src/core/Win32.c:1023` `PRINTF( "dwRead => %d\n", dwRead )

        if ( dwRead == 0 )`
- `WinScreenshot` (function) `payloads/Demon/src/core/Win32.c:1052` `BOOL WinScreenshot(
    OUT PVOID*  ImagePointer,
    OUT PSIZE_T ImageSize
)` -- ! takes a BMP screenshot of the current desktop @param ImagePointer @param ImageSize @return
- `PipeRead` (function) `payloads/Demon/src/core/Win32.c:1175` `BOOL PipeRead(
    IN HANDLE  Handle,
    IN PBUFFER Buffer
)` -- !
- `PipeWrite` (function) `payloads/Demon/src/core/Win32.c:1202` `BOOL PipeWrite(
    IN  HANDLE   Handle,
    OUT PBUFFER Buffer
)` -- !
- `CfgQueryEnforced` (function) `payloads/Demon/src/core/Win32.c:1227` `BOOL CfgQueryEnforced(
    VOID
)` -- ! @brief check if CFG is enforced in this current process.  @return
- `CfgAddressAdd` (function) `payloads/Demon/src/core/Win32.c:1259` `VOID CfgAddressAdd(
    IN PVOID ImageBase,
    IN PVOID Function
)` -- ! @brief add module + function to CFG exception list.  @param ImageBase @param Function
- `EventSet` (function) `payloads/Demon/src/core/Win32.c:1293` `BOOL EventSet(
    IN HANDLE Event
)` -- !
- `RandomNumber32` (function) `payloads/Demon/src/core/Win32.c:1304` `ULONG RandomNumber32(
    VOID
)` -- ! generates a random unsigned 32-bit integer @return
- `RandomBool` (function) `payloads/Demon/src/core/Win32.c:1321` `BOOL RandomBool(
    VOID
)` -- ! generates a random bool @return
- `SharedTimestamp` (function) `payloads/Demon/src/core/Win32.c:1337` `ULONG64 SharedTimestamp(
    VOID
)` -- ! get current timestamp since unix epoch from KUSER_SHARED_DATA @return
- `SharedSleep` (function) `payloads/Demon/src/core/Win32.c:1357` `VOID SharedSleep(
    ULONG64 Delay
)` -- !
- `ShuffleArray` (function) `payloads/Demon/src/core/Win32.c:1379` `VOID ShuffleArray(
    _Inout_ PVOID* array,
    IN     SIZE_T n
)`
- `DemonPrintf` (function) `payloads/Demon/src/core/Win32.c:1402` `VOID DemonPrintf( PCHAR fmt, ... )`
- `LogToConsole` (function) `payloads/Demon/src/core/Win32.c:1434` `VOID LogToConsole(
    IN LPCSTR fmt,
    ...)`
- `listDir` (function) `payloads/Demon/src/core/Win32.c:1478` `PROOT_DIR listDir(
    IN LPWSTR StartPath,
    IN BOOL   SubDirs,
    IN BOOL   FilesOnly,
    I...`

## payloads/Demon/src/crypt/AesCrypt.c
Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/crypt/AesCrypt.h`
- `KeyExpansion` (function) `payloads/Demon/src/crypt/AesCrypt.c:47` `void KeyExpansion(UINT8* RoundKey, const UINT8* Key)`
- `AesInit` (function) `payloads/Demon/src/crypt/AesCrypt.c:103` `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv)`
- `AddRoundKey` (function) `payloads/Demon/src/crypt/AesCrypt.c:111` `static void AddRoundKey(UINT8 round, state_t* state, const UINT8* RoundKey)` -- This function adds the round key to state.
- `SubBytes` (function) `payloads/Demon/src/crypt/AesCrypt.c:125` `static void SubBytes(state_t* state)` -- The SubBytes Function Substitutes the values in the state matrix with values in an S-box.
- `ShiftRows` (function) `payloads/Demon/src/crypt/AesCrypt.c:140` `static void ShiftRows(state_t* state)` -- The ShiftRows() function shifts the rows in the state to the left.
- `xtime` (function) `payloads/Demon/src/crypt/AesCrypt.c:168` `static UINT8 xtime(UINT8 x)`
- `MixColumns` (function) `payloads/Demon/src/crypt/AesCrypt.c:174` `static void MixColumns(state_t* state)` -- MixColumns function mixes the columns of the state matrix
- `AesXCryptBuffer` (function) `payloads/Demon/src/crypt/AesCrypt.c:217` `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length)`

## payloads/Demon/src/inject/Inject.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/include/inject/InjectUtil.h`
- `Inject` (function) `payloads/Demon/src/inject/Inject.c:27` `DWORD Inject(
    IN BYTE   Method,
    IN HANDLE Handle,
    IN DWORD  Pid,
    IN BOOL   x64,
 ...` -- Inject code into a remote process  @param Method    thread execution method. @param Handle    opened handle to the...
- `PRINTF` (function) `payloads/Demon/src/inject/Inject.c:64` `PRINTF( "[INJECT] Using specified process handle: %x\n", Process )
    }

    /* check the archit...`
- `PRINTF` (function) `payloads/Demon/src/inject/Inject.c:91` `PRINTF( "[INJECT] Allocated memory in the remote process: %p\n", Memory )
    }

    /* write pay...`
- `PRINTF` (function) `payloads/Demon/src/inject/Inject.c:99` `PRINTF( "[INJECT] Wrote payload into remote process: %d written\n", Size )
    }

    /* change a...`
- `PUTS` (function) `payloads/Demon/src/inject/Inject.c:107` `PUTS( "[INJECT] Changed memory protection from RW to RX" )
    }

    /* check if any args has be...`
- `PRINTF` (function) `payloads/Demon/src/inject/Inject.c:118` `PRINTF( "[INJECT] Allocated argument memory in the remote process: %p\n", Param )
        }

    ...`
- `PRINTF` (function) `payloads/Demon/src/inject/Inject.c:126` `PRINTF( "[INJECT] Wrote argument into remote process: %d written\n", Argc )
        }
    }

    ...`
- `PRINTF` (function) `payloads/Demon/src/inject/Inject.c:135` `PRINTF( "[INJECT] Failed to create a new thread: %d\n", NtGetLastError() )
    }

END:
    PUTS( ...`
- `DllInjectReflective` (function) `payloads/Demon/src/inject/Inject.c:172` `DWORD DllInjectReflective( HANDLE hTargetProcess, LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuff...`
- `PRINTF` (function) `payloads/Demon/src/inject/Inject.c:232` `PRINTF( "Params: Size:[%d] Pointer:[%p]\n", ParamSize, Parameter )
    if ( ParamSize > 0 )` -- Alloc and write remote params
- `PRINTF` (function) `payloads/Demon/src/inject/Inject.c:278` `PRINTF( "ctx->Parameter: %p\n", ctx->Parameter )

                if ( ! ThreadCreate( THREAD_MET...`
- `DllSpawnReflective` (function) `payloads/Demon/src/inject/Inject.c:322` `DWORD DllSpawnReflective( LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuffer, DWORD DllLength, PVO...`

## payloads/Demon/src/inject/InjectUtil.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/inject/InjectUtil.h`
- `Rva2Offset` (function) `payloads/Demon/src/inject/InjectUtil.c:12` `DWORD Rva2Offset( DWORD dwRva, UINT_PTR uiBaseAddress )`
- `GetReflectiveLoaderOffset` (function) `payloads/Demon/src/inject/InjectUtil.c:36` `DWORD GetReflectiveLoaderOffset( PVOID ReflectiveLdrAddr )`
- `GetPeArch` (function) `payloads/Demon/src/inject/InjectUtil.c:72` `DWORD GetPeArch( PVOID PeBytes )`

## payloads/Demon/src/main/MainDll.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`
- `Start` (function) `payloads/Demon/src/main/MainDll.c:8` `DLLEXPORT VOID Start(  )` -- Export this for rundll32 or any other program that requires and exported functions... * TODO: make this function...
- `DllMain` (function) `payloads/Demon/src/main/MainDll.c:24` `DLLEXPORT BOOL WINAPI DllMain(
    IN     HINSTANCE hDllBase,
    IN     DWORD     Reason,
    _I...` -- /* prevent exiting if started using rundll32 or something PVOID Kernel32  = LdrModulePeb( H_MODULE_KERNEL32 ); VOID...

## payloads/Demon/src/main/MainExe.c
Depends on: `payloads/Demon/include/Demon.h`
- `WinMain` (function) `payloads/Demon/src/main/MainExe.c:3` `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )`

## payloads/Demon/src/main/MainSvc.c
Depends on: `payloads/Demon/include/Demon.h`
- `WinMain` (function) `payloads/Demon/src/main/MainSvc.c:16` `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )` -- /* Service handle and status variable SERVICE_STATUS_HANDLE StatusHandle = { 0 }; SERVICE_STATUS        SvcStatus...
- `SvcMain` (function) `payloads/Demon/src/main/MainSvc.c:31` `VOID WINAPI SvcMain( DWORD dwArgc, LPTSTR* Argv )` -- { PRINTF( "WinMain (Service Main): hInstance:[%p]\n", hInstance ) SERVICE_TABLE_ENTRY DispatchTable[ ] = { {...
- `SrvCtrlHandler` (function) `payloads/Demon/src/main/MainSvc.c:41` `VOID WINAPI SrvCtrlHandler( DWORD CtrlCode )`

## payloads/DllLdr/Scripts/extract.py
- `main` (function) `payloads/DllLdr/Scripts/extract.py:8` `def main(options)`

## payloads/DllLdr/Source/Entry.c
- `KaynLoader` (function) `payloads/DllLdr/Source/Entry.c:5` `DLLEXPORT VOID KaynLoader( LPVOID lpParameter )`
- `KaynCaller` (function) `payloads/DllLdr/Source/Entry.c:144` `NAKED LPVOID KaynCaller( PVOID StartAddress )`
- `Memcpy` (function) `payloads/DllLdr/Source/Entry.c:166` `NAKED VOID Memcpy( PVOID Destination, PVOID source, SIZE_T Size )`
- `KGetModuleByHash` (function) `payloads/DllLdr/Source/Entry.c:185` `PVOID KGetModuleByHash( DWORD ModuleHash )`
- `CopyDotStr` (function) `payloads/DllLdr/Source/Entry.c:206` `FORCE_INLINE UINT32 CopyDotStr( PCHAR String )`
- `KGetProcAddressByHash` (function) `payloads/DllLdr/Source/Entry.c:215` `PVOID KGetProcAddressByHash( PINSTANCE Instance, PVOID DllModuleBase, DWORD FunctionHash, DWORD O...`
- `KResolveIAT` (function) `payloads/DllLdr/Source/Entry.c:265` `VOID KResolveIAT( PINSTANCE Instance, LPVOID KaynImage, LPVOID IatDir )`
- `KReAllocSections` (function) `payloads/DllLdr/Source/Entry.c:306` `VOID KReAllocSections( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir )`
- `KLoadLibrary` (function) `payloads/DllLdr/Source/Entry.c:331` `PVOID KLoadLibrary( PINSTANCE Instance, LPSTR ModuleName )`
- `KHashString` (function) `payloads/DllLdr/Source/Entry.c:364` `DWORD KHashString( PVOID String, SIZE_T Length )`
- `KStringLengthA` (function) `payloads/DllLdr/Source/Entry.c:393` `SIZE_T KStringLengthA( LPCSTR String )`
- `KStringLengthW` (function) `payloads/DllLdr/Source/Entry.c:400` `SIZE_T KStringLengthW(LPCWSTR String)`
- `KCharStringToWCharString` (function) `payloads/DllLdr/Source/Entry.c:409` `SIZE_T KCharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )`

## payloads/Shellcode/Scripts/Hasher.c
- `Hash` (function) `payloads/Shellcode/Scripts/Hasher.c:4` `long Hash( char* String )`
- `ToUpperString` (function) `payloads/Shellcode/Scripts/Hasher.c:15` `void ToUpperString(char * temp)`
- `main` (function) `payloads/Shellcode/Scripts/Hasher.c:24` `int main(int argc, char** argv)`

## payloads/Shellcode/Source/Entry.c
- `SEC` (function) `payloads/Shellcode/Source/Entry.c:11` `SEC( text, B ) VOID Entry( VOID )`
- `KaynLdrReloc` (function) `payloads/Shellcode/Source/Entry.c:104` `VOID KaynLdrReloc( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir, DWORD KHdrSize )`

## payloads/Shellcode/Source/Utils.c
Depends on: `payloads/Shellcode/Include/Utils.h`
- `SEC` (function) `payloads/Shellcode/Source/Utils.c:4` `SEC( text, B ) UINT_PTR HashString( LPVOID String, UINT_PTR Length )`

## payloads/Shellcode/Source/Win32.c
Depends on: `payloads/Shellcode/Include/Utils.h`
- `SEC` (function) `payloads/Shellcode/Source/Win32.c:5` `SEC( text, B ) UINT_PTR LdrModulePeb( UINT_PTR hModuleHash )`
- `SEC` (function) `payloads/Shellcode/Source/Win32.c:23` `SEC( text, B ) PVOID LdrFunctionAddr( UINT_PTR Module, UINT_PTR FunctionHash )`

## teamserver/cmd/cmd.go
Depends on: `teamserver/pkg/colors/colors.go`
Imported by: `teamserver/main.go`
- `init` (function) `teamserver/cmd/cmd.go:29` `func init(` -- init all flags
- `teamserverFunc` (function) `teamserver/cmd/cmd.go:47` `func teamserverFunc(`
- `startMenu` (function) `teamserver/cmd/cmd.go:61` `func startMenu(`

## teamserver/cmd/server/agent.go
Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`
- `AgentUpdate` (function) `teamserver/cmd/server/agent.go:16` `func (t *Teamserver) AgentUpdate(`
- `Died` (function) `teamserver/cmd/server/agent.go:23` `func (t *Teamserver) Died(`
- `UnlinkFromAll` (function) `teamserver/cmd/server/agent.go:30` `func (t *Teamserver) UnlinkFromAll(`
- `ParentOf` (function) `teamserver/cmd/server/agent.go:53` `func (t *Teamserver) ParentOf(`
- `LinksOf` (function) `teamserver/cmd/server/agent.go:60` `func (t *Teamserver) LinksOf(`
- `LinkAdd` (function) `teamserver/cmd/server/agent.go:66` `func (t *Teamserver) LinkAdd(`
- `LinkRemove` (function) `teamserver/cmd/server/agent.go:78` `func (t *Teamserver) LinkRemove(`
- `AgentHasDied` (function) `teamserver/cmd/server/agent.go:102` `func (t *Teamserver) AgentHasDied(`
- `AgentAdd` (function) `teamserver/cmd/server/agent.go:108` `func (t *Teamserver) AgentAdd(`
- `AgentSendNotify` (function) `teamserver/cmd/server/agent.go:123` `func (t *Teamserver) AgentSendNotify(`
- `AgentCallbackSize` (function) `teamserver/cmd/server/agent.go:138` `func (t *Teamserver) AgentCallbackSize(`
- `AgentInstance` (function) `teamserver/cmd/server/agent.go:155` `func (t *Teamserver) AgentInstance(`
- `AgentLastTimeCalled` (function) `teamserver/cmd/server/agent.go:166` `func (t *Teamserver) AgentLastTimeCalled(`
- `AgentExist` (function) `teamserver/cmd/server/agent.go:183` `func (t *Teamserver) AgentExist(`
- `AgentConsole` (function) `teamserver/cmd/server/agent.go:198` `func (t *Teamserver) AgentConsole(`
- `PythonModuleCallback` (function) `teamserver/cmd/server/agent.go:208` `func (t *Teamserver) PythonModuleCallback(`
- `AgentCallback` (function) `teamserver/cmd/server/agent.go:220` `func (t *Teamserver) AgentCallback(`
- `SendLogs` (function) `teamserver/cmd/server/agent.go:233` `func (t *Teamserver) SendLogs(`
- `GetDotNetPipeTemplate` (function) `teamserver/cmd/server/agent.go:237` `func (t *Teamserver) GetDotNetPipeTemplate(`

## teamserver/cmd/server/dispatch.go
Depends on: `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- `DispatchEvent` (function) `teamserver/cmd/server/dispatch.go:20` `func (t *Teamserver) DispatchEvent(`

## teamserver/cmd/server/listener.go
Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`
- `ListenerStart` (function) `teamserver/cmd/server/listener.go:19` `func (t *Teamserver) ListenerStart(`
- `ListenerExist` (function) `teamserver/cmd/server/listener.go:113` `func (t *Teamserver) ListenerExist(`
- `ListenerGetInfo` (function) `teamserver/cmd/server/listener.go:124` `func (t *Teamserver) ListenerGetInfo(`
- `ListenerRemove` (function) `teamserver/cmd/server/listener.go:144` `func (t *Teamserver) ListenerRemove(`
- `ListenerEdit` (function) `teamserver/cmd/server/listener.go:192` `func (t *Teamserver) ListenerEdit(`
- `ListenerAdd` (function) `teamserver/cmd/server/listener.go:220` `func (t *Teamserver) ListenerAdd(` -- ListenerAdd creates a package for the client that a new listener has been added.
- `ListenerServiceExc2Add` (function) `teamserver/cmd/server/listener.go:337` `func (t *Teamserver) ListenerServiceExc2Add(` -- ListenerServiceExc2Add adds an external c2 listener that has been started from a service script to the teamserver...
- `ListenerStartNotify` (function) `teamserver/cmd/server/listener.go:378` `func (t *Teamserver) ListenerStartNotify(` -- ListenerStartNotify Notifies the clients of a new listener that is available to use.

## teamserver/cmd/server/service.go
Depends on: `teamserver/pkg/logger/logger.go`
- `ServiceAgent` (function) `teamserver/cmd/server/service.go:9` `func (t *Teamserver) ServiceAgent(`
- `ServiceAgentExist` (function) `teamserver/cmd/server/service.go:20` `func (t *Teamserver) ServiceAgentExist(`

## teamserver/cmd/server/teamserver.go
Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`
- `NewTeamserver` (function) `teamserver/cmd/server/teamserver.go:37` `func NewTeamserver(`
- `SetServerFlags` (function) `teamserver/cmd/server/teamserver.go:48` `func (t *Teamserver) SetServerFlags(`
- `Start` (function) `teamserver/cmd/server/teamserver.go:52` `func (t *Teamserver) Start(`
- `handleRequest` (function) `teamserver/cmd/server/teamserver.go:497` `func (t *Teamserver) handleRequest(`
- `SetProfile` (function) `teamserver/cmd/server/teamserver.go:626` `func (t *Teamserver) SetProfile(`
- `ClientAuthenticate` (function) `teamserver/cmd/server/teamserver.go:637` `func (t *Teamserver) ClientAuthenticate(`
- `EventBroadcast` (function) `teamserver/cmd/server/teamserver.go:690` `func (t *Teamserver) EventBroadcast(`
- `EventNewDemon` (function) `teamserver/cmd/server/teamserver.go:709` `func (t *Teamserver) EventNewDemon(`
- `EventAgentMark` (function) `teamserver/cmd/server/teamserver.go:713` `func (t *Teamserver) EventAgentMark(`
- `EventListenerError` (function) `teamserver/cmd/server/teamserver.go:720` `func (t *Teamserver) EventListenerError(`
- `SendEvent` (function) `teamserver/cmd/server/teamserver.go:741` `func (t *Teamserver) SendEvent(`
- `RemoveClient` (function) `teamserver/cmd/server/teamserver.go:773` `func (t *Teamserver) RemoveClient(`
- `EventAppend` (function) `teamserver/cmd/server/teamserver.go:797` `func (t *Teamserver) EventAppend(`
- `EventRemove` (function) `teamserver/cmd/server/teamserver.go:812` `func (t *Teamserver) EventRemove(`
- `SendAllPackagesToNewClient` (function) `teamserver/cmd/server/teamserver.go:818` `func (t *Teamserver) SendAllPackagesToNewClient(`
- `FindSystemPackages` (function) `teamserver/cmd/server/teamserver.go:842` `func (t *Teamserver) FindSystemPackages(`
- `EndpointAdd` (function) `teamserver/cmd/server/teamserver.go:933` `func (t *Teamserver) EndpointAdd(`
- `EndpointRemove` (function) `teamserver/cmd/server/teamserver.go:945` `func (t *Teamserver) EndpointRemove(`

## teamserver/main.go
Depends on: `teamserver/cmd/cmd.go`, `teamserver/pkg/logger/logger.go`
- `main` (function) `teamserver/main.go:6` `func main(`


Next: [API_p6.md](API_p6.md)
