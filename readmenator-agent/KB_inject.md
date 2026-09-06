# Subsystem: inject

## payloads/Demon/src/inject/Inject.c
- Layer: infrastructure
- Doc: include <Demon.h> include <ntstatus.h>  include <core/Win32.h> include <core/Package.h> include <core/MiniStd.h> include
- Language: c
- Symbols:
  - `Inject` (function, line 27) `DWORD Inject(
    IN BYTE   Method,
    IN HANDLE Handle,
    IN DWORD  Pid,
    IN BOOL   x64,
 ...`
  - `PRINTF` (function, line 64) `PRINTF( "[INJECT] Using specified process handle: %x\n", Process )
    }

    /* check the archit...`
  - `PRINTF` (function, line 91) `PRINTF( "[INJECT] Allocated memory in the remote process: %p\n", Memory )
    }

    /* write pay...`
  - `PRINTF` (function, line 99) `PRINTF( "[INJECT] Wrote payload into remote process: %d written\n", Size )
    }

    /* change a...`
  - `PUTS` (function, line 107) `PUTS( "[INJECT] Changed memory protection from RW to RX" )
    }

    /* check if any args has be...`
  - `PRINTF` (function, line 118) `PRINTF( "[INJECT] Allocated argument memory in the remote process: %p\n", Param )
        }

    ...`
  - `PRINTF` (function, line 126) `PRINTF( "[INJECT] Wrote argument into remote process: %d written\n", Argc )
        }
    }

    ...`
  - `PRINTF` (function, line 135) `PRINTF( "[INJECT] Failed to create a new thread: %d\n", NtGetLastError() )
    }

END:
    PUTS( ...`
  - `DllInjectReflective` (function, line 171) `DWORD DllInjectReflective( HANDLE hTargetProcess, LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuff...`
  - `PRINTF` (function, line 232) `PRINTF( "Params: Size:[%d] Pointer:[%p]\n", ParamSize, Parameter )
    if ( ParamSize > 0 )`
  - `PRINTF` (function, line 278) `PRINTF( "ctx->Parameter: %p\n", ctx->Parameter )

                if ( ! ThreadCreate( THREAD_MET...`
  - `DllSpawnReflective` (function, line 321) `DWORD DllSpawnReflective( LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuffer, DWORD DllLength, PVO...`

## payloads/Demon/src/inject/InjectUtil.c
- Layer: infrastructure
- Doc: include <Demon.h>  include <core/MiniStd.h> include <core/Package.h> include <inject/InjectUtil.h> include <common/Defin
- Language: c
- Symbols:
  - `Rva2Offset` (function, line 11) `DWORD Rva2Offset( DWORD dwRva, UINT_PTR uiBaseAddress )`
  - `GetReflectiveLoaderOffset` (function, line 35) `DWORD GetReflectiveLoaderOffset( PVOID ReflectiveLdrAddr )`
  - `GetPeArch` (function, line 71) `DWORD GetPeArch( PVOID PeBytes )`
