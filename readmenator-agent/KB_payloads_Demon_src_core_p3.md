# Subsystem: payloads_Demon_src_core (page 3 of 3)
Previous: [KB_payloads_Demon_src_core_p2.md](KB_payloads_Demon_src_core_p2.md)

## payloads/Demon/src/core/Win32.c
- Doc: HashEx: !
- Layer: utility
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

