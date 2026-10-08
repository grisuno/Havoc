# API (page 4 of 8)
Previous: [API_p3.md](API_p3.md)

## payloads/Demon/src/core/HwBpExceptions.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpExceptions.h`
- `HwBpExAmsiScanBuffer` (function) `payloads/Demon/src/core/HwBpExceptions.c:6` `VOID HwBpExAmsiScanBuffer(
    _Inout_ PEXCEPTION_POINTERS Exception
)`
- `HwBpExNtTraceEvent` (function) `payloads/Demon/src/core/HwBpExceptions.c:23` `VOID HwBpExNtTraceEvent(
    _Inout_ PEXCEPTION_POINTERS Exception
)`

## payloads/Demon/src/core/Jobs.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`
- `JobAdd` (function) `payloads/Demon/src/core/Jobs.c:17` `VOID JobAdd( UINT32 RequestID, DWORD JobID, SHORT Type, SHORT State, HANDLE Handle, PVOID Data )` -- !
- `JobCheckList` (function) `payloads/Demon/src/core/Jobs.c:63` `VOID JobCheckList()` -- !
- `JobSuspend` (function) `payloads/Demon/src/core/Jobs.c:184` `BOOL JobSuspend( DWORD JobID )` -- !
- `PRINTF` (function) `payloads/Demon/src/core/Jobs.c:192` `PRINTF( "Found Job ID: %d", JobID )

            if ( JobList->Type == JOB_TYPE_THREAD )`
- `JobResume` (function) `payloads/Demon/src/core/Jobs.c:230` `BOOL JobResume( DWORD JobID )` -- !
- `PRINTF` (function) `payloads/Demon/src/core/Jobs.c:238` `PRINTF( "Found Job ID: %d", JobID )

            if ( JobList->Type == JOB_TYPE_THREAD )`
- `JobKill` (function) `payloads/Demon/src/core/Jobs.c:277` `BOOL JobKill( DWORD JobID )` -- !
- `PRINTF` (function) `payloads/Demon/src/core/Jobs.c:287` `PRINTF( "Found Job ID: %d\n", JobID )

            switch ( JobList->Type )`
- `PUTS` (function) `payloads/Demon/src/core/Jobs.c:300` `PUTS( "Kill using handle" )

                            if ( ! NT_SUCCESS( NtStatus = Instance->...`
- `JobRemove` (function) `payloads/Demon/src/core/Jobs.c:383` `VOID JobRemove( DWORD JobID )` -- !

## payloads/Demon/src/core/Kerberos.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`
- `IsHighIntegrity` (function) `payloads/Demon/src/core/Kerberos.c:8` `BOOL IsHighIntegrity(HANDLE TokenHandle)`
- `GetProcessIdByName` (function) `payloads/Demon/src/core/Kerberos.c:29` `DWORD GetProcessIdByName(WCHAR* processName)`
- `ElevateToSystem` (function) `payloads/Demon/src/core/Kerberos.c:61` `BOOL ElevateToSystem()`
- `IsSystem` (function) `payloads/Demon/src/core/Kerberos.c:131` `BOOL IsSystem( HANDLE TokenHandle )`
- `GetLsaHandle` (function) `payloads/Demon/src/core/Kerberos.c:155` `NTSTATUS GetLsaHandle( HANDLE hToken, BOOL highIntegrity, PHANDLE hLsa )`
- `GetLogonSessionData` (function) `payloads/Demon/src/core/Kerberos.c:218` `NTSTATUS GetLogonSessionData( LUID luid, PLOGON_SESSION_DATA* data )`
- `ExtractTicket` (function) `payloads/Demon/src/core/Kerberos.c:283` `VOID ExtractTicket( HANDLE hLsa, ULONG authPackage, LUID luid, UNICODE_STRING targetName, PUCHAR*...`
- `CopySessionInfo` (function) `payloads/Demon/src/core/Kerberos.c:337` `VOID CopySessionInfo( PSESSION_INFORMATION Session, PSECURITY_LOGON_SESSION_DATA Data )`
- `CopyTicketInfo` (function) `payloads/Demon/src/core/Kerberos.c:371` `VOID CopyTicketInfo( PTICKET_INFORMATION TicketInfo, PKERB_TICKET_CACHE_INFO_EX Data )`
- `Ptt` (function) `payloads/Demon/src/core/Kerberos.c:399` `BOOL Ptt( HANDLE hToken, PBYTE Ticket, DWORD TicketSize, LUID luid )`
- `Purge` (function) `payloads/Demon/src/core/Kerberos.c:494` `BOOL Purge( HANDLE hToken, LUID luid )`
- `Klist` (function) `payloads/Demon/src/core/Kerberos.c:585` `PSESSION_INFORMATION Klist( HANDLE hToken, LUID luid )`
- `GetLUID` (function) `payloads/Demon/src/core/Kerberos.c:752` `LUID* GetLUID( HANDLE hToken )`

## payloads/Demon/src/core/Memory.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`
- `MmHeapAlloc` (function) `payloads/Demon/src/core/Memory.c:15` `PVOID MmHeapAlloc(
    _In_ ULONG Length
)` -- ! @brief allocate memory on the heap  @param Length size of memory to allocate  @return allocated buffer pointer on...
- `MmHeapReAlloc` (function) `payloads/Demon/src/core/Memory.c:31` `PVOID MmHeapReAlloc(
    _In_ PVOID Memory,
    _In_ ULONG Length
)` -- ! @brief allocate memory on the heap  @param Length size of memory to reallocate  @return allocated buffer pointer...
- `MmHeapFree` (function) `payloads/Demon/src/core/Memory.c:48` `BOOL MmHeapFree(
    _In_ PVOID Memory
)` -- ! @brief free memory on the heap  @param Memory memory to free  @return if successfully freed memory on the heap
- `MmVirtualAlloc` (function) `payloads/Demon/src/core/Memory.c:62` `PVOID MmVirtualAlloc(
    IN DX_MEMORY Methode,
    IN HANDLE    Process,
    IN SIZE_T    Size,
...` -- !
- `PUTS` (function) `payloads/Demon/src/core/Memory.c:79` `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )`
- `MmVirtualProtect` (function) `payloads/Demon/src/core/Memory.c:133` `BOOL MmVirtualProtect(
    IN DX_MEMORY Method,
    IN HANDLE    Process,
    IN PVOID     Memory...` -- !
- `PUTS` (function) `payloads/Demon/src/core/Memory.c:147` `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )`
- `MmVirtualWrite` (function) `payloads/Demon/src/core/Memory.c:189` `BOOL MmVirtualWrite(
    IN  HANDLE Process,
    OUT PVOID  Memory,
    IN  PVOID  Buffer,
    IN...`
- `MmVirtualFree` (function) `payloads/Demon/src/core/Memory.c:209` `BOOL MmVirtualFree(
    IN HANDLE Process,
    IN PVOID  Memory
)` -- !
- `MmGadgetFind` (function) `payloads/Demon/src/core/Memory.c:240` `PVOID MmGadgetFind(
    _In_ PVOID  Memory,
    _In_ SIZE_T Length,
    _In_ PVOID  PatternBuffer...`
- `FreeReflectiveLoader` (function) `payloads/Demon/src/core/Memory.c:269` `BOOL FreeReflectiveLoader(
    IN PVOID BaseAddress
)` -- !

## payloads/Demon/src/core/MiniStd.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`
- `StringCompareA` (function) `payloads/Demon/src/core/MiniStd.c:9` `INT StringCompareA( LPCSTR String1, LPCSTR String2 )`
- `StringCompareW` (function) `payloads/Demon/src/core/MiniStd.c:21` `INT StringCompareW( LPWSTR String1, LPWSTR String2 )`
- `StringNCompareW` (function) `payloads/Demon/src/core/MiniStd.c:33` `INT StringNCompareW( LPWSTR String1, LPWSTR String2, INT Length )`
- `ToLowerCaseW` (function) `payloads/Demon/src/core/MiniStd.c:48` `WCHAR ToLowerCaseW( WCHAR C )`
- `StringCompareIW` (function) `payloads/Demon/src/core/MiniStd.c:53` `INT StringCompareIW( LPWSTR String1, LPWSTR String2 )`
- `StringNCompareIW` (function) `payloads/Demon/src/core/MiniStd.c:65` `INT StringNCompareIW( LPWSTR String1, LPWSTR String2, INT Length )`
- `EndsWithIW` (function) `payloads/Demon/src/core/MiniStd.c:80` `BOOL EndsWithIW( LPWSTR String, LPWSTR Ending )`
- `HashStringA` (function) `payloads/Demon/src/core/MiniStd.c:100` `DWORD HashStringA( PCHAR String )` -- return FALSE; Length1 = StringLengthW( String ); Length2 = StringLengthW( Ending ); if ( Length1 < Length2 ) return...
- `StringCopyA` (function) `payloads/Demon/src/core/MiniStd.c:112` `PCHAR StringCopyA(PCHAR String1, PCHAR String2)`
- `StringCopyW` (function) `payloads/Demon/src/core/MiniStd.c:121` `PWCHAR StringCopyW(PWCHAR String1, PWCHAR String2)`
- `StringLengthA` (function) `payloads/Demon/src/core/MiniStd.c:130` `SIZE_T StringLengthA(LPCSTR String)`
- `StringLengthW` (function) `payloads/Demon/src/core/MiniStd.c:142` `SIZE_T StringLengthW(LPCWSTR String)`
- `StringConcatA` (function) `payloads/Demon/src/core/MiniStd.c:151` `PCHAR StringConcatA(PCHAR String, PCHAR String2)`
- `StringConcatW` (function) `payloads/Demon/src/core/MiniStd.c:158` `PWCHAR StringConcatW(PWCHAR String, PWCHAR String2)`
- `WcsStr` (function) `payloads/Demon/src/core/MiniStd.c:165` `LPWSTR WcsStr( PWCHAR String, PWCHAR String2 )`
- `WcsIStr` (function) `payloads/Demon/src/core/MiniStd.c:185` `LPWSTR WcsIStr( PWCHAR String, PWCHAR String2 )`
- `MemCompare` (function) `payloads/Demon/src/core/MiniStd.c:205` `INT MemCompare( PVOID s1, PVOID s2, INT len)`
- `WCharStringToCharString` (function) `payloads/Demon/src/core/MiniStd.c:229` `SIZE_T WCharStringToCharString(PCHAR Destination, PWCHAR Source, SIZE_T MaximumAllowed)`
- `CharStringToWCharString` (function) `payloads/Demon/src/core/MiniStd.c:242` `SIZE_T CharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )`
- `StringTokenA` (function) `payloads/Demon/src/core/MiniStd.c:255` `PCHAR StringTokenA(PCHAR String, CONST PCHAR Delim)`
- `GetSystemFileTime` (function) `payloads/Demon/src/core/MiniStd.c:300` `UINT64 GetSystemFileTime( )`
- `HideChar` (function) `payloads/Demon/src/core/MiniStd.c:313` `BYTE NO_INLINE HideChar( BYTE C )` -- UINT64 GetSystemFileTime( ) { FILETIME ft; LARGE_INTEGER li; Instance->Win32.GetSystemTimeAsFileTime(&ft); //returns...

## payloads/Demon/src/core/Obf.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`
- `FoliageObf` (function) `payloads/Demon/src/core/Obf.c:22` `VOID FoliageObf(
    IN PSLEEP_PARAM Param
)` -- ! @brief foliage is a sleep obfuscation technique that is using APC calls to obfuscate itself in memory  @param...
- `PRINTF` (function) `payloads/Demon/src/core/Obf.c:603` `PRINTF( "RtlCreateTimerQueue/NtCreateEvent Failed: %lx\n", NtStatus )
    }

LEAVE: /* cleanup */...`
- `SleepTime` (function) `payloads/Demon/src/core/Obf.c:650` `UINT32 SleepTime(
    VOID
)`
- `SleepObf` (function) `payloads/Demon/src/core/Obf.c:714` `VOID SleepObf(
    VOID
)`

## payloads/Demon/src/core/ObjectApi.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`
- `LdrModulePebString` (function) `payloads/Demon/src/core/ObjectApi.c:20` `PVOID LdrModulePebString( PCHAR ModuleString )` -- Meh some wrapper functions for internal demon GetProcAddress and GetModuleHandleA functions.
- `LdrFunctionAddrString` (function) `payloads/Demon/src/core/ObjectApi.c:26` `PVOID LdrFunctionAddrString( PVOID Module, PCHAR Function )`
- `LdrFreeLibrary` (function) `payloads/Demon/src/core/ObjectApi.c:32` `BOOL LdrFreeLibrary( HMODULE hLibModule )`
- `LdrLocalFree` (function) `payloads/Demon/src/core/ObjectApi.c:37` `HLOCAL LdrLocalFree( PVOID hMem )`
- `swap_endianess` (function) `payloads/Demon/src/core/ObjectApi.c:131` `uint32_t swap_endianess(uint32_t indata)`
- `BeaconDataParse` (function) `payloads/Demon/src/core/ObjectApi.c:143` `VOID BeaconDataParse( PDATA parser, PCHAR buffer, INT size )`
- `BeaconDataInt` (function) `payloads/Demon/src/core/ObjectApi.c:155` `INT BeaconDataInt( PDATA parser )`
- `BeaconDataShort` (function) `payloads/Demon/src/core/ObjectApi.c:170` `SHORT BeaconDataShort( datap* parser )`
- `BeaconDataLength` (function) `payloads/Demon/src/core/ObjectApi.c:185` `INT BeaconDataLength( PDATA parser )`
- `BeaconDataExtract` (function) `payloads/Demon/src/core/ObjectApi.c:190` `PCHAR BeaconDataExtract( PDATA parser, PINT size )`
- `GetRequestIDForCallingObjectFile` (function) `payloads/Demon/src/core/ObjectApi.c:224` `BOOL GetRequestIDForCallingObjectFile( PVOID CoffeeFunctionReturn, PUINT32 RequestID )` -- This function is called by BeaconPrintf and BeaconOutput.
- `BeaconPrintf` (function) `payloads/Demon/src/core/ObjectApi.c:248` `VOID BeaconPrintf( INT Type, PCHAR fmt, ... )`
- `BeaconOutput` (function) `payloads/Demon/src/core/ObjectApi.c:305` `VOID BeaconOutput( INT Type, PCHAR data, INT len )`
- `BeaconIsAdmin` (function) `payloads/Demon/src/core/ObjectApi.c:324` `BOOL BeaconIsAdmin(
    VOID
)`
- `BeaconFormatAlloc` (function) `payloads/Demon/src/core/ObjectApi.c:343` `VOID BeaconFormatAlloc( PFORMAT format, int maxsz )`
- `BeaconFormatReset` (function) `payloads/Demon/src/core/ObjectApi.c:354` `VOID BeaconFormatReset( PFORMAT format )`
- `BeaconFormatFree` (function) `payloads/Demon/src/core/ObjectApi.c:361` `VOID BeaconFormatFree( PFORMAT format )`
- `BeaconFormatAppend` (function) `payloads/Demon/src/core/ObjectApi.c:377` `VOID BeaconFormatAppend( PFORMAT format, char* text, int len )`
- `BeaconFormatPrintf` (function) `payloads/Demon/src/core/ObjectApi.c:384` `VOID BeaconFormatPrintf( PFORMAT format, char* fmt, ... )`
- `BeaconFormatToString` (function) `payloads/Demon/src/core/ObjectApi.c:405` `char* BeaconFormatToString( PFORMAT format, int* size)`
- `BeaconFormatInt` (function) `payloads/Demon/src/core/ObjectApi.c:411` `VOID BeaconFormatInt( PFORMAT format, int value)`
- `BeaconUseToken` (function) `payloads/Demon/src/core/ObjectApi.c:425` `BOOL BeaconUseToken( HANDLE token )`
- `BeaconGetSpawnTo` (function) `payloads/Demon/src/core/ObjectApi.c:440` `VOID BeaconGetSpawnTo( BOOL x86, char* buffer, int length )`
- `BeaconSpawnTemporaryProcess` (function) `payloads/Demon/src/core/ObjectApi.c:463` `BOOL BeaconSpawnTemporaryProcess( BOOL x86, BOOL ignoreToken, STARTUPINFO* sInfo, PROCESS_INFORMA...`
- `BeaconInjectProcess` (function) `payloads/Demon/src/core/ObjectApi.c:487` `VOID BeaconInjectProcess( HANDLE hProc, int pid, char* payload, int p_len, int p_offset, char * a...`
- `BeaconInjectTemporaryProcess` (function) `payloads/Demon/src/core/ObjectApi.c:530` `VOID BeaconInjectTemporaryProcess( PROCESS_INFORMATION* pInfo, char* payload, int p_len, int p_of...`
- `BeaconCleanupProcess` (function) `payloads/Demon/src/core/ObjectApi.c:564` `VOID BeaconCleanupProcess( PROCESS_INFORMATION* pInfo )`
- `BeaconInformation` (function) `payloads/Demon/src/core/ObjectApi.c:578` `VOID BeaconInformation(BEACON_INFO * info)` -- not implemented
- `BeaconAddValue` (function) `payloads/Demon/src/core/ObjectApi.c:584` `BOOL BeaconAddValue(const char * key, void * ptr)`
- `BeaconGetValue` (function) `payloads/Demon/src/core/ObjectApi.c:633` `PVOID BeaconGetValue(const char * key)`
- `BeaconRemoveValue` (function) `payloads/Demon/src/core/ObjectApi.c:656` `BOOL BeaconRemoveValue(const char * key)`
- `BeaconDataStoreGetItem` (function) `payloads/Demon/src/core/ObjectApi.c:690` `PDATA_STORE_OBJECT BeaconDataStoreGetItem(SIZE_T index)` -- not implemented
- `BeaconDataStoreProtectItem` (function) `payloads/Demon/src/core/ObjectApi.c:697` `VOID BeaconDataStoreProtectItem(SIZE_T index)` -- not implemented
- `BeaconDataStoreUnprotectItem` (function) `payloads/Demon/src/core/ObjectApi.c:704` `VOID BeaconDataStoreUnprotectItem(SIZE_T index)` -- not implemented
- `BeaconDataStoreMaxEntries` (function) `payloads/Demon/src/core/ObjectApi.c:711` `SIZE_T BeaconDataStoreMaxEntries()` -- not implemented
- `BeaconGetCustomUserData` (function) `payloads/Demon/src/core/ObjectApi.c:718` `PCHAR BeaconGetCustomUserData()` -- not implemented
- `toWideChar` (function) `payloads/Demon/src/core/ObjectApi.c:724` `BOOL toWideChar( char* src, wchar_t* dst, int max )`

## payloads/Demon/src/core/Package.c
Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`
- `Int64ToBuffer` (function) `payloads/Demon/src/core/Package.c:13` `VOID Int64ToBuffer( PUCHAR Buffer, UINT64 Value )`
- `Int32ToBuffer` (function) `payloads/Demon/src/core/Package.c:39` `VOID Int32ToBuffer(
    OUT PUCHAR Buffer,
    IN  UINT32 Size
)`
- `PackageAddInt32` (function) `payloads/Demon/src/core/Package.c:49` `VOID PackageAddInt32(
    _Inout_ PPACKAGE Package,
    IN     UINT32   Data
)`
- `PackageAddInt64` (function) `payloads/Demon/src/core/Package.c:68` `VOID PackageAddInt64( PPACKAGE Package, UINT64 dataInt )`
- `PackageAddBool` (function) `payloads/Demon/src/core/Package.c:85` `VOID PackageAddBool(
    _Inout_ PPACKAGE Package,
    IN     BOOLEAN  Data
)`
- `PackageAddPtr` (function) `payloads/Demon/src/core/Package.c:104` `VOID PackageAddPtr( PPACKAGE Package, PVOID pointer )`
- `PackageAddPad` (function) `payloads/Demon/src/core/Package.c:109` `VOID PackageAddPad( PPACKAGE Package, PCHAR Data, SIZE_T Size )`
- `PackageAddBytes` (function) `payloads/Demon/src/core/Package.c:125` `VOID PackageAddBytes( PPACKAGE Package, PBYTE Data, SIZE_T Size )`
- `PackageAddString` (function) `payloads/Demon/src/core/Package.c:147` `VOID PackageAddString( PPACKAGE package, PCHAR data )`
- `PackageAddWString` (function) `payloads/Demon/src/core/Package.c:152` `VOID PackageAddWString( PPACKAGE package, PWCHAR data )`
- `PackageCreate` (function) `payloads/Demon/src/core/Package.c:157` `PPACKAGE PackageCreate( UINT32 CommandID )`
- `PackageCreateWithMetaData` (function) `payloads/Demon/src/core/Package.c:174` `PPACKAGE PackageCreateWithMetaData( UINT32 CommandID )`
- `PackageCreateWithRequestID` (function) `payloads/Demon/src/core/Package.c:187` `PPACKAGE PackageCreateWithRequestID( UINT32 CommandID, UINT32 RequestID )`
- `PackageDestroy` (function) `payloads/Demon/src/core/Package.c:196` `VOID PackageDestroy(
    IN PPACKAGE Package
)`
- `PackageTransmitNow` (function) `payloads/Demon/src/core/Package.c:229` `BOOL PackageTransmitNow(
    _Inout_ PPACKAGE Package,
    OUT    PVOID*   Response,
    OUT    P...` -- used to send the demon's metadata
- `PUTS_DONT_SEND` (function) `payloads/Demon/src/core/Package.c:264` `PUTS_DONT_SEND("TransportSend failed!")
        }

        if ( Package->Destroy )`
- `PackageTransmit` (function) `payloads/Demon/src/core/Package.c:281` `VOID PackageTransmit(
    IN PPACKAGE Package
)` -- don't transmit right away, simply store the package.
- `PackageTransmitAll` (function) `payloads/Demon/src/core/Package.c:333` `BOOL PackageTransmitAll(
    OUT    PVOID*   Response,
    OUT    PSIZE_T  Size
)` -- transmit all stored packages in a single request
- `PackageTransmitError` (function) `payloads/Demon/src/core/Package.c:471` `VOID PackageTransmitError(
    IN UINT32 ID,
    IN UINT32 ErrorCode
)`

## payloads/Demon/src/core/Parser.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`
- `ParserNew` (function) `payloads/Demon/src/core/Parser.c:7` `VOID ParserNew( PPARSER parser, PBYTE Buffer, UINT32 size )`
- `ParserDecrypt` (function) `payloads/Demon/src/core/Parser.c:21` `VOID ParserDecrypt( PPARSER parser, PBYTE Key, PBYTE IV )`
- `ParserGetInt16` (function) `payloads/Demon/src/core/Parser.c:33` `INT16 ParserGetInt16( PPARSER parser )`
- `ParserGetByte` (function) `payloads/Demon/src/core/Parser.c:48` `BYTE ParserGetByte( PPARSER parser )`
- `ParserGetInt32` (function) `payloads/Demon/src/core/Parser.c:64` `INT ParserGetInt32( PPARSER parser )`
- `ParserGetInt64` (function) `payloads/Demon/src/core/Parser.c:85` `INT64 ParserGetInt64( PPARSER parser )`
- `ParserGetBool` (function) `payloads/Demon/src/core/Parser.c:106` `BOOL ParserGetBool( PPARSER parser )`
- `ParserGetBytes` (function) `payloads/Demon/src/core/Parser.c:127` `PBYTE ParserGetBytes( PPARSER parser, PUINT32 size )`
- `ParserGetString` (function) `payloads/Demon/src/core/Parser.c:158` `PCHAR  ParserGetString( PPARSER parser, PUINT32 size )`
- `ParserGetWString` (function) `payloads/Demon/src/core/Parser.c:163` `PWCHAR  ParserGetWString( PPARSER parser, PUINT32 size )`
- `ParserDestroy` (function) `payloads/Demon/src/core/Parser.c:168` `VOID ParserDestroy( PPARSER Parser )`

## payloads/Demon/src/core/Pivot.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Parser.h`
- `PivotAdd` (function) `payloads/Demon/src/core/Pivot.c:24` `BOOL PivotAdd( BUFFER NamedPipe, PVOID* Output, PDWORD BytesSize )`
- `PivotGet` (function) `payloads/Demon/src/core/Pivot.c:121` `PPIVOT_DATA PivotGet( DWORD AgentID )`
- `PivotRemove` (function) `payloads/Demon/src/core/Pivot.c:139` `BOOL PivotRemove( DWORD AgentId )`
- `PivotCount` (function) `payloads/Demon/src/core/Pivot.c:218` `DWORD PivotCount()`
- `PivotPush` (function) `payloads/Demon/src/core/Pivot.c:235` `VOID PivotPush()`
- `PivotParseDemonID` (function) `payloads/Demon/src/core/Pivot.c:331` `UINT32 PivotParseDemonID( PVOID Response, SIZE_T Size )`

## payloads/Demon/src/core/Runtime.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`
- `RtAdvapi32` (function) `payloads/Demon/src/core/Runtime.c:6` `BOOL RtAdvapi32(
    VOID
)`
- `RtMscoree` (function) `payloads/Demon/src/core/Runtime.c:68` `BOOL RtMscoree(
    VOID
)` -- we delay loading mscoree.dll
- `RtOleaut32` (function) `payloads/Demon/src/core/Runtime.c:103` `BOOL RtOleaut32(
    VOID
)`
- `RtUser32` (function) `payloads/Demon/src/core/Runtime.c:142` `BOOL RtUser32(
    VOID
)`
- `RtShell32` (function) `payloads/Demon/src/core/Runtime.c:176` `BOOL RtShell32(
    VOID
)`
- `RtMsvcrt` (function) `payloads/Demon/src/core/Runtime.c:208` `BOOL RtMsvcrt(
    VOID
)`
- `RtIphlpapi` (function) `payloads/Demon/src/core/Runtime.c:240` `BOOL RtIphlpapi(
    VOID
)`
- `RtGdi32` (function) `payloads/Demon/src/core/Runtime.c:273` `BOOL RtGdi32(
    VOID
)`
- `RtNetApi32` (function) `payloads/Demon/src/core/Runtime.c:310` `BOOL RtNetApi32(
    VOID
)`
- `RtWs2_32` (function) `payloads/Demon/src/core/Runtime.c:349` `BOOL RtWs2_32(
    VOID
)`
- `RtSspicli` (function) `payloads/Demon/src/core/Runtime.c:394` `BOOL RtSspicli(
    VOID
)`
- `RtAmsi` (function) `payloads/Demon/src/core/Runtime.c:433` `BOOL RtAmsi(
    VOID
)`
- `RtWinHttp` (function) `payloads/Demon/src/core/Runtime.c:463` `BOOL RtWinHttp(
    VOID
)` -- ifdef TRANSPORT_HTTP

## payloads/Demon/src/core/Socket.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`
- `RecvAll` (function) `payloads/Demon/src/core/Socket.c:7` `BOOL RecvAll( SOCKET Socket, PVOID Buffer, DWORD Length, PDWORD BytesRead )` -- attempt to receive all the requested data from the socket * Took it from...
- `InitWSA` (function) `payloads/Demon/src/core/Socket.c:33` `BOOL InitWSA( VOID )`
- `PUTS` (function) `payloads/Demon/src/core/Socket.c:41` `PUTS( "Init Windows Socket..." )

        if ( ( Result = Instance->Win32.WSAStartup( MAKEWORD( 2...`
- `SocketNew` (function) `payloads/Demon/src/core/Socket.c:59` `PSOCKET_DATA SocketNew( SOCKET WinSock, DWORD Type, BOOL UseIpv4, DWORD IPv4, PBYTE IPv6, DWORD L...` -- PRINTF( "WSAStartup Failed: %d\n", Result ) /* cleanup and be gone.
- `PUTS` (function) `payloads/Demon/src/core/Socket.c:74` `PUTS( "Create Socket..." )

        if ( UseIpv4 )`
- `PRINTF` (function) `payloads/Demon/src/core/Socket.c:112` `PRINTF( "SockAddr6: %02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%d\n"...`
- `SocketClients` (function) `payloads/Demon/src/core/Socket.c:213` `VOID SocketClients()` -- CLEANUP: if ( WinSock && WinSock != INVALID_SOCKET ) { close the socket preserving the last error code ErrorCode =...
- `SocketRead` (function) `payloads/Demon/src/core/Socket.c:281` `VOID SocketRead()` -- { PRINTF( "ioctlsocket failed: %d\n", NtGetLastError() ) /* close socket.
- `SocketFree` (function) `payloads/Demon/src/core/Socket.c:425` `VOID SocketFree( PSOCKET_DATA Socket )`
- `PRINTF` (function) `payloads/Demon/src/core/Socket.c:429` `PRINTF( "Closing socket %x\n", Socket->ID )

    /* do we want to remove a reverse port forward c...`
- `SocketCleanDead` (function) `payloads/Demon/src/core/Socket.c:482` `VOID SocketCleanDead()`
- `SocketPush` (function) `payloads/Demon/src/core/Socket.c:522` `VOID SocketPush()`
- `DnsQueryIPv4` (function) `payloads/Demon/src/core/Socket.c:539` `DWORD DnsQueryIPv4( LPSTR Domain )` -- !
- `DnsQueryIPv6` (function) `payloads/Demon/src/core/Socket.c:580` `PBYTE DnsQueryIPv6( LPSTR Domain )` -- !

## payloads/Demon/src/core/Spoof.c
Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Spoof.h`
- `SpoofRetAddr` (function) `payloads/Demon/src/core/Spoof.c:6` `PVOID SpoofRetAddr(
    _In_    PVOID  Module,
    _In_    ULONG  Size,
    _In_    HANDLE Functi...`

## payloads/Demon/src/core/SysNative.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`
- `SysNtOpenThread` (function) `payloads/Demon/src/core/SysNative.c:6` `NTSTATUS NTAPI SysNtOpenThread(
    OUT    PHANDLE            ThreadHandle,
    IN     ACCESS_MAS...`
- `SysNtOpenProcess` (function) `payloads/Demon/src/core/SysNative.c:20` `NTSTATUS NTAPI SysNtOpenProcess(
    OUT    PHANDLE             ProcessHandle,
    IN     ACCESS_...`
- `SysNtTerminateProcess` (function) `payloads/Demon/src/core/SysNative.c:34` `NTSTATUS NTAPI SysNtTerminateProcess(
    IN OPTIONAL HANDLE   ProcessHandle,
    IN          NTS...`
- `SysNtOpenThreadToken` (function) `payloads/Demon/src/core/SysNative.c:46` `NTSTATUS NTAPI SysNtOpenThreadToken(
    IN  HANDLE      ThreadHandle,
    IN  ACCESS_MASK Desire...`
- `SysNtOpenProcessToken` (function) `payloads/Demon/src/core/SysNative.c:60` `NTSTATUS NTAPI SysNtOpenProcessToken(
    IN  HANDLE      ProcessHandle,
    IN  ACCESS_MASK Desi...`
- `SysNtDuplicateToken` (function) `payloads/Demon/src/core/SysNative.c:73` `NTSTATUS NTAPI SysNtDuplicateToken(
    IN  HANDLE             ExistingTokenHandle,
    IN  ACCES...`
- `SysNtQueueApcThread` (function) `payloads/Demon/src/core/SysNative.c:89` `NTSTATUS NTAPI SysNtQueueApcThread(
    IN     HANDLE          ThreadHandle,
    IN     PPS_APC_R...`
- `SysNtSuspendThread` (function) `payloads/Demon/src/core/SysNative.c:104` `NTSTATUS NTAPI SysNtSuspendThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSu...`
- `SysNtResumeThread` (function) `payloads/Demon/src/core/SysNative.c:116` `NTSTATUS NTAPI SysNtResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSus...`
- `SysNtCreateEvent` (function) `payloads/Demon/src/core/SysNative.c:128` `NTSTATUS NTAPI SysNtCreateEvent (
    OUT    PHANDLE            EventHandle,
    IN     ACCESS_MA...`
- `SysNtCreateThreadEx` (function) `payloads/Demon/src/core/SysNative.c:143` `NTSTATUS NTAPI SysNtCreateThreadEx(
    OUT PHANDLE     hThread,
    IN  ACCESS_MASK DesiredAcces...`
- `SysNtDuplicateObject` (function) `payloads/Demon/src/core/SysNative.c:176` `NTSTATUS NTAPI SysNtDuplicateObject(
    IN     HANDLE      SourceProcessHandle,
    IN     HANDL...`
- `SysNtGetContextThread` (function) `payloads/Demon/src/core/SysNative.c:193` `NTSTATUS NTAPI SysNtGetContextThread (
    IN     HANDLE   ThreadHandle,
    _Inout_ PCONTEXT Thr...`
- `SysNtSetContextThread` (function) `payloads/Demon/src/core/SysNative.c:205` `NTSTATUS NTAPI SysNtSetContextThread(
    IN HANDLE   ThreadHandle,
    IN PCONTEXT ThreadContext
)`
- `SysNtQueryInformationProcess` (function) `payloads/Demon/src/core/SysNative.c:217` `NTSTATUS NTAPI SysNtQueryInformationProcess(
    IN      HANDLE           ProcessHandle,
    IN  ...`
- `SysNtQuerySystemInformation` (function) `payloads/Demon/src/core/SysNative.c:232` `NTSTATUS NTAPI SysNtQuerySystemInformation (
    IN      SYSTEM_INFORMATION_CLASS SystemInformati...`
- `SysNtWaitForSingleObject` (function) `payloads/Demon/src/core/SysNative.c:246` `NTSTATUS NTAPI SysNtWaitForSingleObject(
    IN     HANDLE         Handle,
    IN     BOOLEAN    ...`
- `SysNtAllocateVirtualMemory` (function) `payloads/Demon/src/core/SysNative.c:259` `NTSTATUS NTAPI SysNtAllocateVirtualMemory(
    IN     HANDLE    ProcessHandle,
    _Inout_ PVOID*...`
- `SysNtWriteVirtualMemory` (function) `payloads/Demon/src/core/SysNative.c:275` `NTSTATUS NTAPI SysNtWriteVirtualMemory(
    IN       HANDLE  ProcessHandle,
    IN OPT   PVOID   ...`
- `SysNtFreeVirtualMemory` (function) `payloads/Demon/src/core/SysNative.c:290` `NTSTATUS NTAPI SysNtFreeVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  Base...`
- `SysNtUnmapViewOfSection` (function) `payloads/Demon/src/core/SysNative.c:304` `NTSTATUS NTAPI SysNtUnmapViewOfSection(
    IN HANDLE ProcessHandle,
    IN PVOID  BaseAddress
)`
- `SysNtProtectVirtualMemory` (function) `payloads/Demon/src/core/SysNative.c:316` `NTSTATUS NTAPI SysNtProtectVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  B...`
- `SysNtReadVirtualMemory` (function) `payloads/Demon/src/core/SysNative.c:331` `NTSTATUS NTAPI SysNtReadVirtualMemory (
    IN      HANDLE  ProcessHandle,
    IN OPT  PVOID   Ba...`
- `SysNtTerminateThread` (function) `payloads/Demon/src/core/SysNative.c:346` `NTSTATUS NTAPI SysNtTerminateThread (
    IN OPT HANDLE   ThreadHandle,
    IN     NTSTATUS ExitS...`
- `SysNtAlertResumeThread` (function) `payloads/Demon/src/core/SysNative.c:358` `NTSTATUS NTAPI SysNtAlertResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG Previo...`
- `SysNtSignalAndWaitForSingleObject` (function) `payloads/Demon/src/core/SysNative.c:370` `NTSTATUS NTAPI SysNtSignalAndWaitForSingleObject(
    IN     HANDLE         SignalHandle,
    IN ...`
- `SysNtQueryVirtualMemory` (function) `payloads/Demon/src/core/SysNative.c:384` `NTSTATUS NTAPI SysNtQueryVirtualMemory(
    IN      HANDLE                   ProcessHandle,
    I...`
- `SysNtQueryInformationToken` (function) `payloads/Demon/src/core/SysNative.c:400` `NTSTATUS NTAPI SysNtQueryInformationToken (
    IN  HANDLE                  TokenHandle,
    IN  ...`
- `SysNtQueryInformationThread` (function) `payloads/Demon/src/core/SysNative.c:415` `NTSTATUS NTAPI SysNtQueryInformationThread(
    IN      HANDLE          ThreadHandle,
    IN     ...`
- `SysNtQueryObject` (function) `payloads/Demon/src/core/SysNative.c:430` `NTSTATUS NTAPI SysNtQueryObject(
    IN  HANDLE                   Handle,
    IN  OBJECT_INFORMAT...`
- `SysNtClose` (function) `payloads/Demon/src/core/SysNative.c:445` `NTSTATUS NTAPI SysNtClose (
    IN HANDLE Handle
)`
- `SysNtSetInformationThread` (function) `payloads/Demon/src/core/SysNative.c:456` `NTSTATUS NTAPI SysNtSetInformationThread (
    IN HANDLE          ThreadHandle,
    IN THREADINFO...`
- `SysNtSetInformationVirtualMemory` (function) `payloads/Demon/src/core/SysNative.c:470` `NTSTATUS NTAPI SysNtSetInformationVirtualMemory(
    IN HANDLE                           ProcessH...`
- `SysNtGetNextThread` (function) `payloads/Demon/src/core/SysNative.c:486` `NTSTATUS NTAPI SysNtGetNextThread(
    IN  HANDLE      ProcessHandle,
    IN  HANDLE      ThreadH...`

## payloads/Demon/src/core/Syscalls.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`
- `SysInitialize` (function) `payloads/Demon/src/core/Syscalls.c:12` `BOOL SysInitialize(
    IN PVOID Ntdll
)` -- !
- `SYS_EXTRACT` (function) `payloads/Demon/src/core/Syscalls.c:44` `SYS_EXTRACT( NtOpenThread )
    SYS_EXTRACT( NtOpenThreadToken )
    SYS_EXTRACT( NtOpenProcess )...` -- Instance->Syscall.SysAddress = SysIndirectAddr; } else { PUTS_DONT_SEND( "Failed to resolve SysIndirectAddr" ); } }...
- `PRINTF` (function) `payloads/Demon/src/core/Syscalls.c:184` `PRINTF( "Could not resolve the Ssn of function at 0x%p\n", Function )
        }

        if ( Sys...`
- `FindSsnOfHookedSyscall` (function) `payloads/Demon/src/core/Syscalls.c:201` `BOOL FindSsnOfHookedSyscall(
    IN  PVOID  Function,
    OUT PWORD  Ssn
)` -- If a function is hooked, we can't obtain the Ssn directly.
- `PRINTF` (function) `payloads/Demon/src/core/Syscalls.c:209` `PRINTF( "The syscall at address 0x%p seems to be hooked, trying to resolve its Ssn via neighbouri...`

## payloads/Demon/src/core/Thread.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`
- `ThreadQueryTib` (function) `payloads/Demon/src/core/Thread.c:20` `BOOL ThreadQueryTib(
    IN  PVOID   Adr,
    OUT PNT_TIB Tib
)` -- ! queries the NT_TIB from the specified leaked thread RSP address  NOTE: this function is entirely taken from...
- `ThreadCreateWoW64` (function) `payloads/Demon/src/core/Thread.c:118` `HANDLE ThreadCreateWoW64(
    IN  BYTE   Method,
    IN  HANDLE Process,
    IN  PVOID  Entry,
  ...` -- https://github.com/rapid7/meterpreter/blob/5e309596e53ead0f64564fe77e0cad70908f6739/source/common/arch/win/i386/base_...
- `PUTS` (function) `payloads/Demon/src/core/Thread.c:185` `PUTS( "calling RtlCreateUserThread( ctx->h.hProcess, NULL, TRUE, 0, NULL, NULL, ctx->s.lpStartAdd...`
- `ThreadCreate` (function) `payloads/Demon/src/core/Thread.c:217` `HANDLE ThreadCreate(
    IN  BYTE   Method,
    IN  HANDLE Process,
    IN  BOOL   x64,
    IN  P...`


Next: [API_p5.md](API_p5.md)
