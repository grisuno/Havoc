# Subsystem: inject

## payloads/Demon/include/inject/Inject.h
- Doc: defaults
- Layer: infrastructure
- Language: h
- Symbols:
  - `INJECTION_CTX` (struct, line 31)
  - `_DX_CREATE_THREAD` (enum, line 21)
  - `hProcess` (type_alias, line 30) `typedef struct INJECTION_CTX { HANDLE hProcess;`
  - `DEMON_BASEINJECT_H` (macro, line 3) `#define DEMON_BASEINJECT_H`
  - `INJECTION_TECHNIQUE_WIN32` (macro, line 10) `#define INJECTION_TECHNIQUE_WIN32`
  - `INJECTION_TECHNIQUE_SYSCALL` (macro, line 11) `#define INJECTION_TECHNIQUE_SYSCALL`
  - `INJECTION_TECHNIQUE_APC` (macro, line 12) `#define INJECTION_TECHNIQUE_APC`
  - `SPAWN_TECHNIQUE_SYSCALL` (macro, line 14) `#define SPAWN_TECHNIQUE_SYSCALL`
  - `SPAWN_TECHNIQUE_APC` (macro, line 15) `#define SPAWN_TECHNIQUE_APC`
  - `SPAWN_TECHNIQUE_DEFAULT` (macro, line 18) `#define SPAWN_TECHNIQUE_DEFAULT`
  - `INJECTION_TECHNIQUE_DEFAULT` (macro, line 19) `#define INJECTION_TECHNIQUE_DEFAULT`
  - `INJECT_ERROR_SUCCESS` (macro, line 48) `#define INJECT_ERROR_SUCCESS`
  - `INJECT_ERROR_FAILED` (macro, line 49) `#define INJECT_ERROR_FAILED`
  - `INJECT_ERROR_INVALID_PARAM` (macro, line 50) `#define INJECT_ERROR_INVALID_PARAM`
  - `INJECT_ERROR_PROCESS_ARCH_MISMATCH` (macro, line 51) `#define INJECT_ERROR_PROCESS_ARCH_MISMATCH`
  - `INJECT_WAY_SPAWN` (macro, line 53) `#define INJECT_WAY_SPAWN`
  - `INJECT_WAY_INJECT` (macro, line 54) `#define INJECT_WAY_INJECT`
  - `INJECT_WAY_EXECUTE` (macro, line 55) `#define INJECT_WAY_EXECUTE`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/Thread.h`
- Imported by: `payloads/Demon/include/inject/InjectUtil.h`, `payloads/Demon/src/Demon.c`, `payloads/Demon/src/core/Command.c`, `payloads/Demon/src/inject/Inject.c`

## payloads/Demon/include/inject/InjectUtil.h
- Layer: infrastructure
- Language: h
- Symbols:
  - `DEMON_INJECTUTIL_H` (macro, line 2) `#define DEMON_INJECTUTIL_H`
  - `DEREF_32` (macro, line 7) `#define DEREF_32( name )`
  - `DEREF_16` (macro, line 8) `#define DEREF_16( name )`
  - `PROC_THREAD_ATTRIBUTE_NUMBER` (macro, line 12) `#define PROC_THREAD_ATTRIBUTE_NUMBER`
  - `PROC_THREAD_ATTRIBUTE_THREAD` (macro, line 13) `#define PROC_THREAD_ATTRIBUTE_THREAD`
  - `PROC_THREAD_ATTRIBUTE_INPUT` (macro, line 14) `#define PROC_THREAD_ATTRIBUTE_INPUT`
  - `PROC_THREAD_ATTRIBUTE_ADDITIVE` (macro, line 15) `#define PROC_THREAD_ATTRIBUTE_ADDITIVE`
  - `ProcThreadAttributeValue` (macro, line 17) `#define ProcThreadAttributeValue(Number, Thread, Input, Additive)`
  - `ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X64_TO_X86` (macro, line 25) `#define ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X64_TO_X86`
  - `ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X86_TO_X64` (macro, line 26) `#define ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X86_TO_X64`
  - `ERROR_INJECT_FAILED_TO_SPAWN_TARGET_PROCESS` (macro, line 27) `#define ERROR_INJECT_FAILED_TO_SPAWN_TARGET_PROCESS`
- Depends on: `payloads/Demon/include/inject/Inject.h`
- Imported by: `payloads/Demon/src/core/CoffeeLdr.c`, `payloads/Demon/src/inject/Inject.c`, `payloads/Demon/src/inject/InjectUtil.c`
