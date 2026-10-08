# payloads/Demon/include/core

*Community 0 | 67 files | cohesion 1.00*

## Definition

This community groups 67 file(s) rooted at `payloads/Demon/include/core` with dominant language h (cohesion 1.00). Central symbols: `1`, `5`, `ABSOLUTE_TIME`, `ACTIVATION_CONTEXT_STACK_FLAG_QUERIES_DISABLED`, `AES256`, `AES_BLOCKLEN`, `AES_KEYLEN`, `AES_keyExpSize`. Core file: `payloads/Demon/include/common/Native.h` (2246 symbols). Documented purpose: Heap allocation functions.

## Files

### `payloads/Demon/include/core` (26 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `payloads/Demon/include/core/CoffeeLdr.h` | h | utility | 27 | yes |
| `payloads/Demon/include/core/Command.h` | h | utility | 112 | yes |
| `payloads/Demon/include/core/Dotnet.h` | h | utility | 0 | no |

### `payloads/Demon/src/core` (26 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `payloads/Demon/src/core/CoffeeLdr.c` | c | utility | 24 | yes |
| `payloads/Demon/src/core/Command.c` | c | utility | 81 | no |
| `payloads/Demon/src/core/Dotnet.c` | c | utility | 19 | no |

### `payloads/Demon/include/common` (4 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `payloads/Demon/include/common/Clr.h` | h | utility | 45 | no |
| `payloads/Demon/include/common/Defines.h` | h | utility | 347 | no |
| `payloads/Demon/include/common/Macros.h` | h | utility | 41 | yes |

### `payloads/Demon/src/main` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `payloads/Demon/src/main/MainDll.c` | c | utility | 2 | yes |
| `payloads/Demon/src/main/MainExe.c` | c | utility | 1 | no |
| `payloads/Demon/src/main/MainSvc.c` | c | utility | 3 | yes |

### `payloads/Demon/include/inject` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `payloads/Demon/include/inject/Inject.h` | h | infrastructure | 18 | yes |
| `payloads/Demon/include/inject/InjectUtil.h` | h | infrastructure | 11 | no |

### `payloads/Demon/src/inject` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `payloads/Demon/src/inject/Inject.c` | c | infrastructure | 12 | yes |
| `payloads/Demon/src/inject/InjectUtil.c` | c | infrastructure | 4 | no |

### `payloads/Demon/include` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `payloads/Demon/include/Demon.h` | h | utility | 4 | no |

### `payloads/Demon/include/crypt` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `payloads/Demon/include/crypt/AesCrypt.h` | h | utility | 9 | no |

### `payloads/Demon/src` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `payloads/Demon/src/Demon.c` | c | utility | 9 | yes |

### `payloads/Demon/src/crypt` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `payloads/Demon/src/crypt/AesCrypt.c` | c | utility | 17 | no |

*... and 47 more files in this community.*


## Key Symbols

- `DEMON_DEMON_H` (macro, `payloads/Demon/include/Demon.h:2`) `#define DEMON_DEMON_H`
- `Session` (struct, `payloads/Demon/include/Demon.h:48`) - TODO: remove all variables that are not switched/changed after some time
- `_CONFIG` (struct, `payloads/Demon/include/Demon.h:121`)
- `Instance` (variable, `payloads/Demon/include/Demon.h:559`) `extern PINSTANCE Instance;`
- `DEMON_CLR_H` (macro, `payloads/Demon/include/common/Clr.h:2`) `#define DEMON_CLR_H`
- `xCLSID_CLRMetaHost` (variable, `payloads/Demon/include/common/Clr.h:8`) `extern GUID xCLSID_CLRMetaHost;`
- `xIID_ICLRMetaHost` (variable, `payloads/Demon/include/common/Clr.h:9`) `extern GUID xIID_ICLRMetaHost;`
- `xIID_ICLRRuntimeInfo` (variable, `payloads/Demon/include/common/Clr.h:10`) `extern GUID xIID_ICLRRuntimeInfo;`
- `xCLSID_CorRuntimeHost` (variable, `payloads/Demon/include/common/Clr.h:11`) `extern GUID xCLSID_CorRuntimeHost;`
- `xIID_ICorRuntimeHost` (variable, `payloads/Demon/include/common/Clr.h:12`) `extern GUID xIID_ICorRuntimeHost;`
- `xIID_AppDomain` (variable, `payloads/Demon/include/common/Clr.h:13`) `extern GUID xIID_AppDomain;`
- `ICLRMetaHost` (type_alias, `payloads/Demon/include/common/Clr.h:14`) `typedef struct _ICLRMetaHost ICLRMetaHost;`
- `ICLRRuntimeInfo` (type_alias, `payloads/Demon/include/common/Clr.h:16`) `typedef struct _ICLRRuntimeInfo ICLRRuntimeInfo;`
- `IAppDomain` (type_alias, `payloads/Demon/include/common/Clr.h:17`) `typedef struct _AppDomain IAppDomain;`
- `IAssembly` (type_alias, `payloads/Demon/include/common/Clr.h:18`) `typedef struct _Assembly IAssembly;`
- `IType` (type_alias, `payloads/Demon/include/common/Clr.h:19`) `typedef struct _Type IType;`
- `IBinder` (type_alias, `payloads/Demon/include/common/Clr.h:20`) `typedef struct _Binder IBinder;`
- `IMethodInfo` (type_alias, `payloads/Demon/include/common/Clr.h:21`) `typedef struct _MethodInfo IMethodInfo;`
- `HDOMAINENUM` (type_alias, `payloads/Demon/include/common/Clr.h:29`) `typedef void* HDOMAINENUM;`
- `DUMMY_METHOD` (macro, `payloads/Demon/include/common/Clr.h:53`) `#define DUMMY_METHOD(x)`
- `_BinderVtbl` (struct, `payloads/Demon/include/common/Clr.h:55`)
- `lpVtbl` (type_alias, `payloads/Demon/include/common/Clr.h:82`) `typedef struct _Binder { BinderVtbl* lpVtbl;`
- `_Binder` (struct, `payloads/Demon/include/common/Clr.h:83`)
- `DUMMY_METHOD` (macro, `payloads/Demon/include/common/Clr.h:88`) `#define DUMMY_METHOD(x)`
- `_AppDomainVtbl` (struct, `payloads/Demon/include/common/Clr.h:90`)
- `lpVtbl` (type_alias, `payloads/Demon/include/common/Clr.h:180`) `typedef struct _AppDomain { AppDomainVtbl* lpVtbl;`
- `_AppDomain` (struct, `payloads/Demon/include/common/Clr.h:181`)
- `DUMMY_METHOD` (macro, `payloads/Demon/include/common/Clr.h:186`) `#define DUMMY_METHOD(x)`
- `_AssemblyVtbl` (struct, `payloads/Demon/include/common/Clr.h:188`)
- `_BindingFlags` (enum, `payloads/Demon/include/common/Clr.h:263`)

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 200
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- [INFERRED] shares_context community 0 <-> 2 (strength 0.5): Inferred shared context (layer utility) with no import path between community 0 (payloads/Demon/include/core) and community 2 (teamserver/cmd/server).
- [INFERRED] shares_context community 0 <-> 4 (strength 0.5): Inferred shared context (layer utility) with no import path between community 0 (payloads/Demon/include/core) and community 4 (teamserver/pkg/profile/yaotl/ext/customdecode).
- [INFERRED] shares_context community 0 <-> 5 (strength 0.5): Inferred shared context (language h and layer utility) with no import path between community 0 (payloads/Demon/include/core) and community 5 (payloads/Shellcode/Include).
- [INFERRED] shares_context community 0 <-> 6 (strength 0.5): Inferred shared context (layer utility) with no import path between community 0 (payloads/Demon/include/core) and community 6 (payloads/Shellcode/Source).
- [INFERRED] shares_context community 0 <-> 7 (strength 0.5): Inferred shared context (language h and layer utility) with no import path between community 0 (payloads/Demon/include/core) and community 7 (payloads/DllLdr/Include).
- [INFERRED] shares_context community 0 <-> 8 (strength 0.5): Inferred shared context (layer utility) with no import path between community 0 (payloads/Demon/include/core) and community 8 (teamserver/pkg/profile/yaotl/hclsyntax).
- [INFERRED] shares_context community 0 <-> 9 (strength 0.5): Inferred shared context (layer utility) with no import path between community 0 (payloads/Demon/include/core) and community 9 (orphans).

## Risks

- [dataflow UNINIT_USE] `payloads/Demon/include/common/Native.h:7469` `NtCurrentPeb` `ExceptionRecord`: `ExceptionRecord` may be read before initialization (declared line 7454).
- [dataflow UNINIT_USE] `payloads/Demon/include/common/Native.h:10097` `NtCurrentPeb` `NextPrefixTree`: `NextPrefixTree` may be read before initialization (declared line 10087).
- [dataflow UNINIT_USE] `payloads/Demon/include/common/Native.h:11186` `NtGetTickCount` `Next`: `Next` may be read before initialization (declared line 11103).
- [dataflow UNINIT_USE] `payloads/Demon/include/common/Native.h:17306` `NtGetTickCount` `Data`: `Data` may be read before initialization (declared line 11582).

## Open Questions

- Why do 37 file(s) lack file-level docs (e.g. `payloads/Demon/include/Demon.h`)? What purpose do they serve?
- What would break if the most connected file in payloads/Demon/include/core changed?
- Should payloads/Demon/include/core be split, given cohesion 1.00?

## Sources

- `payloads/Demon/include/Demon.h`
- `payloads/Demon/include/common/Clr.h`
- `payloads/Demon/include/common/Defines.h`
- `payloads/Demon/include/common/Macros.h`
- `payloads/Demon/include/common/Native.h`
- `payloads/Demon/include/core/CoffeeLdr.h`
- `payloads/Demon/include/core/Command.h`
- `payloads/Demon/include/core/Dotnet.h`
- `payloads/Demon/include/core/Download.h`
- `payloads/Demon/include/core/HwBpEngine.h`
- `payloads/Demon/include/core/HwBpExceptions.h`
- `payloads/Demon/include/core/Jobs.h`
- `payloads/Demon/include/core/Kerberos.h`
- `payloads/Demon/include/core/Memory.h`
- `payloads/Demon/include/core/MiniStd.h`
- `payloads/Demon/include/core/ObjectApi.h`
- `payloads/Demon/include/core/Package.h`
- `payloads/Demon/include/core/Parser.h`
- `payloads/Demon/include/core/Pivot.h`
- `payloads/Demon/include/core/Runtime.h`
- *... and 47 more*
