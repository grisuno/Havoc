# Symbols (page 9 of 13)
Previous: [SYMBOLS_p8.md](SYMBOLS_p8.md)

| Symbol | Kind | File:Line | Signature |
|--------|------|-----------|-----------|
| `RequestID` | type_alias | `payloads/Demon/include/core/Package.h:7` | `typedef struct _PACKAGE { UINT32 RequestID;` |
| `_PACKAGE` | struct | `payloads/Demon/include/core/Package.h:8` | `` |
| `DEMON_PARSER_H` | macro | `payloads/Demon/include/core/Parser.h:2` | `#define DEMON_PARSER_H` |
| `DEMON_PIVOT_H` | macro | `payloads/Demon/include/core/Pivot.h:2` | `#define DEMON_PIVOT_H` |
| `DemonID` | type_alias | `payloads/Demon/include/core/Pivot.h:7` | `typedef struct _PIVOT_DATA { UINT32 DemonID;` |
| `MAX_SMB_PACKETS_PER_LOOP` | macro | `payloads/Demon/include/core/Pivot.h:6` | `#define MAX_SMB_PACKETS_PER_LOOP` |
| `_PIVOT_DATA` | struct | `payloads/Demon/include/core/Pivot.h:8` | `` |
| `DEMON_PROCESS_H` | macro | `payloads/Demon/include/core/Process.h:2` | `#define DEMON_PROCESS_H` |
| `DEMON_RUNTIME_H` | macro | `payloads/Demon/include/core/Runtime.h:2` | `#define DEMON_RUNTIME_H` |
| `DEMON_SLEEPOBF_H` | macro | `payloads/Demon/include/core/SleepObf.h:3` | `#define DEMON_SLEEPOBF_H` |
| `OBF_JMP` | macro | `payloads/Demon/include/core/SleepObf.h:16` | `#define OBF_JMP( i, p )` |
| `SLEEPOBF_BYPASS_JMPRAX` | macro | `payloads/Demon/include/core/SleepObf.h:13` | `#define SLEEPOBF_BYPASS_JMPRAX` |
| `SLEEPOBF_BYPASS_JMPRBX` | macro | `payloads/Demon/include/core/SleepObf.h:14` | `#define SLEEPOBF_BYPASS_JMPRBX` |
| `SLEEPOBF_BYPASS_NONE` | macro | `payloads/Demon/include/core/SleepObf.h:12` | `#define SLEEPOBF_BYPASS_NONE` |
| `SLEEPOBF_EKKO` | macro | `payloads/Demon/include/core/SleepObf.h:8` | `#define SLEEPOBF_EKKO` |
| `SLEEPOBF_FOLIAGE` | macro | `payloads/Demon/include/core/SleepObf.h:10` | `#define SLEEPOBF_FOLIAGE` |
| `SLEEPOBF_NO_OBF` | macro | `payloads/Demon/include/core/SleepObf.h:7` | `#define SLEEPOBF_NO_OBF` |
| `SLEEPOBF_ZILEAN` | macro | `payloads/Demon/include/core/SleepObf.h:9` | `#define SLEEPOBF_ZILEAN` |
| `TimeOut` | type_alias | `payloads/Demon/include/core/SleepObf.h:31` | `typedef struct _SLEEP_PARAM { UINT32 TimeOut;` |
| `USTRING` | struct | `payloads/Demon/include/core/SleepObf.h:25` | `` |
| `_SLEEP_PARAM` | struct | `payloads/Demon/include/core/SleepObf.h:32` | `` |
| `HTTP` | function | `payloads/Demon/include/core/Socket.h:66` | `* This is needed for Socks5 and HTTP(S) agents. * @return TRUE or FALSE */ BOOL InitWSA( VOID );` |
| `ID` | type_alias | `payloads/Demon/include/core/Socket.h:38` | `typedef struct _SOCKET_DATA { DWORD ID;` |
| `SOCKET_COMMAND_CLOSE` | macro | `payloads/Demon/include/core/Socket.h:22` | `#define SOCKET_COMMAND_CLOSE` |
| `SOCKET_COMMAND_CONNECT` | macro | `payloads/Demon/include/core/Socket.h:23` | `#define SOCKET_COMMAND_CONNECT` |
| `SOCKET_COMMAND_OPEN` | macro | `payloads/Demon/include/core/Socket.h:19` | `#define SOCKET_COMMAND_OPEN` |
| `SOCKET_COMMAND_READ` | macro | `payloads/Demon/include/core/Socket.h:20` | `#define SOCKET_COMMAND_READ` |
| `SOCKET_COMMAND_RPORTFWD_ADD` | macro | `payloads/Demon/include/core/Socket.h:8` | `#define SOCKET_COMMAND_RPORTFWD_ADD` |
| `SOCKET_COMMAND_RPORTFWD_ADDLCL` | macro | `payloads/Demon/include/core/Socket.h:9` | `#define SOCKET_COMMAND_RPORTFWD_ADDLCL` |
| `SOCKET_COMMAND_RPORTFWD_CLEAR` | macro | `payloads/Demon/include/core/Socket.h:11` | `#define SOCKET_COMMAND_RPORTFWD_CLEAR` |
| `SOCKET_COMMAND_RPORTFWD_LIST` | macro | `payloads/Demon/include/core/Socket.h:10` | `#define SOCKET_COMMAND_RPORTFWD_LIST` |
| `SOCKET_COMMAND_RPORTFWD_REMOVE` | macro | `payloads/Demon/include/core/Socket.h:12` | `#define SOCKET_COMMAND_RPORTFWD_REMOVE` |
| `SOCKET_COMMAND_SOCKSPROXY_ADD` | macro | `payloads/Demon/include/core/Socket.h:14` | `#define SOCKET_COMMAND_SOCKSPROXY_ADD` |
| `SOCKET_COMMAND_SOCKSPROXY_CLEAR` | macro | `payloads/Demon/include/core/Socket.h:17` | `#define SOCKET_COMMAND_SOCKSPROXY_CLEAR` |
| `SOCKET_COMMAND_SOCKSPROXY_LIST` | macro | `payloads/Demon/include/core/Socket.h:15` | `#define SOCKET_COMMAND_SOCKSPROXY_LIST` |
| `SOCKET_COMMAND_SOCKSPROXY_REMOVE` | macro | `payloads/Demon/include/core/Socket.h:16` | `#define SOCKET_COMMAND_SOCKSPROXY_REMOVE` |
| `SOCKET_COMMAND_WRITE` | macro | `payloads/Demon/include/core/Socket.h:21` | `#define SOCKET_COMMAND_WRITE` |
| `SOCKET_ERROR_ALREADY_BOUND` | macro | `payloads/Demon/include/core/Socket.h:26` | `#define SOCKET_ERROR_ALREADY_BOUND` |
| `SOCKET_TYPE_CLIENT` | macro | `payloads/Demon/include/core/Socket.h:6` | `#define SOCKET_TYPE_CLIENT` |
| `SOCKET_TYPE_NONE` | macro | `payloads/Demon/include/core/Socket.h:3` | `#define SOCKET_TYPE_NONE` |
| `SOCKET_TYPE_REVERSE_PORTFWD` | macro | `payloads/Demon/include/core/Socket.h:4` | `#define SOCKET_TYPE_REVERSE_PORTFWD` |
| `SOCKET_TYPE_REVERSE_PROXY` | macro | `payloads/Demon/include/core/Socket.h:5` | `#define SOCKET_TYPE_REVERSE_PROXY` |
| `_SOCKET_DATA` | struct | `payloads/Demon/include/core/Socket.h:39` | `` |
| `sin6_family` | type_alias | `payloads/Demon/include/core/Socket.h:27` | `typedef struct sockaddr_in6 { ADDRESS_FAMILY sin6_family;` |
| `sockaddr_in6` | struct | `payloads/Demon/include/core/Socket.h:28` | `` |
| `DEMON_SPOOF_H` | macro | `payloads/Demon/include/core/Spoof.h:2` | `#define DEMON_SPOOF_H` |
| `SETUP_ARGS` | macro | `payloads/Demon/include/core/Spoof.h:28` | `#define SETUP_ARGS(arg1, arg2, arg3, arg4, arg5, arg6, arg7, arg8, arg9, arg10, arg11, arg12, ...)` |
| `SPOOF_A` | macro | `payloads/Demon/include/core/Spoof.h:20` | `#define SPOOF_A( function, module, size, a )` |
| `SPOOF_B` | macro | `payloads/Demon/include/core/Spoof.h:21` | `#define SPOOF_B( function, module, size, a, b )` |
| `SPOOF_C` | macro | `payloads/Demon/include/core/Spoof.h:22` | `#define SPOOF_C( function, module, size, a, b, c )` |
| `SPOOF_D` | macro | `payloads/Demon/include/core/Spoof.h:23` | `#define SPOOF_D( function, module, size, a, b, c, d )` |
| `SPOOF_E` | macro | `payloads/Demon/include/core/Spoof.h:24` | `#define SPOOF_E( function, module, size, a, b, c, d, e )` |
| `SPOOF_F` | macro | `payloads/Demon/include/core/Spoof.h:25` | `#define SPOOF_F( function, module, size, a, b, c, d, e, f )` |
| `SPOOF_G` | macro | `payloads/Demon/include/core/Spoof.h:26` | `#define SPOOF_G( function, module, size, a, b, c, d, e, f, g )` |
| `SPOOF_H` | macro | `payloads/Demon/include/core/Spoof.h:27` | `#define SPOOF_H( function, module, size, a, b, c, d, e, f, g, h )` |
| `SPOOF_MACRO_CHOOSER` | macro | `payloads/Demon/include/core/Spoof.h:29` | `#define SPOOF_MACRO_CHOOSER(...)` |
| `SPOOF_X` | macro | `payloads/Demon/include/core/Spoof.h:19` | `#define SPOOF_X( function, module, size )` |
| `Spoof` | function | `payloads/Demon/include/core/Spoof.h:17` | `static ULONG_PTR Spoof();` |
| `SpoofFunc` | macro | `payloads/Demon/include/core/Spoof.h:30` | `#define SpoofFunc(...)` |
| `DEMON_SYSNATIVE_H` | macro | `payloads/Demon/include/core/SysNative.h:2` | `#define DEMON_SYSNATIVE_H` |
| `OPT` | macro | `payloads/Demon/include/core/SysNative.h:9` | `#define OPT` |
| `SYSCALL_INVOKE` | macro | `payloads/Demon/include/core/SysNative.h:12` | `#define SYSCALL_INVOKE( SYS_NAME, ... )` |
| `Adr` | type_alias | `payloads/Demon/include/core/Syscalls.h:31` | `typedef struct _SYS_CONFIG { PVOID Adr;` |
| `DEMON_SYSCALLS_H` | macro | `payloads/Demon/include/core/Syscalls.h:3` | `#define DEMON_SYSCALLS_H` |
| `SSN_OFFSET_1` | macro | `payloads/Demon/include/core/Syscalls.h:13` | `#define SSN_OFFSET_1` |
| `SSN_OFFSET_1` | macro | `payloads/Demon/include/core/Syscalls.h:17` | `#define SSN_OFFSET_1` |
| `SSN_OFFSET_2` | macro | `payloads/Demon/include/core/Syscalls.h:14` | `#define SSN_OFFSET_2` |
| `SSN_OFFSET_2` | macro | `payloads/Demon/include/core/Syscalls.h:18` | `#define SSN_OFFSET_2` |
| `SYSCALL_ASM` | macro | `payloads/Demon/include/core/Syscalls.h:12` | `#define SYSCALL_ASM` |
| `SYSCALL_ASM` | macro | `payloads/Demon/include/core/Syscalls.h:16` | `#define SYSCALL_ASM` |
| `SYS_ASM_RET` | macro | `payloads/Demon/include/core/Syscalls.h:9` | `#define SYS_ASM_RET` |
| `SYS_EXTRACT` | macro | `payloads/Demon/include/core/Syscalls.h:21` | `#define SYS_EXTRACT( NtName )` |
| `SYS_RANGE` | macro | `payloads/Demon/include/core/Syscalls.h:10` | `#define SYS_RANGE` |
| `_SYS_CONFIG` | struct | `payloads/Demon/include/core/Syscalls.h:32` | `` |
| `DEMON_THREAD_H` | macro | `payloads/Demon/include/core/Thread.h:2` | `#define DEMON_THREAD_H` |
| `THREAD_METHOD_CREATEREMOTETHREAD` | macro | `payloads/Demon/include/core/Thread.h:9` | `#define THREAD_METHOD_CREATEREMOTETHREAD` |
| `THREAD_METHOD_DEFAULT` | macro | `payloads/Demon/include/core/Thread.h:8` | `#define THREAD_METHOD_DEFAULT` |
| `THREAD_METHOD_NTCREATEHREADEX` | macro | `payloads/Demon/include/core/Thread.h:10` | `#define THREAD_METHOD_NTCREATEHREADEX` |
| `THREAD_METHOD_NTQUEUEAPCTHREAD` | macro | `payloads/Demon/include/core/Thread.h:11` | `#define THREAD_METHOD_NTQUEUEAPCTHREAD` |
| `_WOW64CONTEXT` | struct | `payloads/Demon/include/core/Thread.h:25` | `` |
| `hProcess` | type_alias | `payloads/Demon/include/core/Thread.h:25` | `typedef struct _WOW64CONTEXT { union { HANDLE hProcess;` |
| `ALIGN_UP` | macro | `payloads/Demon/include/core/Token.h:25` | `#define ALIGN_UP(Address, Type)` |
| `ALIGN_UP_TYPE` | macro | `payloads/Demon/include/core/Token.h:21` | `#define ALIGN_UP_TYPE(Address, Align)` |
| `BUF_SIZE` | macro | `payloads/Demon/include/core/Token.h:15` | `#define BUF_SIZE` |
| `Count` | type_alias | `payloads/Demon/include/core/Token.h:36` | `typedef struct _PROCESS_LIST { ULONG Count;` |
| `DEMON_TOKEN_H` | macro | `payloads/Demon/include/core/Token.h:2` | `#define DEMON_TOKEN_H` |
| `Handle` | type_alias | `payloads/Demon/include/core/Token.h:80` | `typedef struct _TOKEN_LIST_DATA { HANDLE Handle;` |
| `MAX_PROCESSES` | macro | `payloads/Demon/include/core/Token.h:14` | `#define MAX_PROCESSES` |
| `MAX_USERNAME` | macro | `payloads/Demon/include/core/Token.h:16` | `#define MAX_USERNAME` |
| `OBJECT_TYPES_FIRST_ENTRY` | macro | `payloads/Demon/include/core/Token.h:30` | `#define OBJECT_TYPES_FIRST_ENTRY(ObjectTypes)` |
| `OBJECT_TYPES_NEXT_ENTRY` | macro | `payloads/Demon/include/core/Token.h:33` | `#define OBJECT_TYPES_NEXT_ENTRY(ObjectType)` |
| `ObjectTypesInformation` | macro | `payloads/Demon/include/core/Token.h:28` | `#define ObjectTypesInformation` |
| `RtlOffsetToPointer` | macro | `payloads/Demon/include/core/Token.h:18` | `#define RtlOffsetToPointer(B,O)` |
| `SEC_IMP_LEVEL` | type_alias | `payloads/Demon/include/core/Token.h:94` | `typedef SECURITY_IMPERSONATION_LEVEL SEC_IMP_LEVEL;` |
| `TOKEN_OWNER_FLAG_DEFAULT` | macro | `payloads/Demon/include/core/Token.h:10` | `#define TOKEN_OWNER_FLAG_DEFAULT` |
| `TOKEN_OWNER_FLAG_DOMAIN` | macro | `payloads/Demon/include/core/Token.h:12` | `#define TOKEN_OWNER_FLAG_DOMAIN` |
| `TOKEN_OWNER_FLAG_USER` | macro | `payloads/Demon/include/core/Token.h:11` | `#define TOKEN_OWNER_FLAG_USER` |
| `TOKEN_TYPE_MAKE_NETWORK` | macro | `payloads/Demon/include/core/Token.h:8` | `#define TOKEN_TYPE_MAKE_NETWORK` |
| `TOKEN_TYPE_STOLEN` | macro | `payloads/Demon/include/core/Token.h:7` | `#define TOKEN_TYPE_STOLEN` |
| `TypeName` | type_alias | `payloads/Demon/include/core/Token.h:52` | `typedef struct _OBJECT_TYPE_INFORMATION_V2 { UNICODE_STRING TypeName;` |
| `_OBJECT_TYPE_INFORMATION_V2` | struct | `payloads/Demon/include/core/Token.h:53` | `` |
| `_PROCESS_LIST` | struct | `payloads/Demon/include/core/Token.h:37` | `` |
| `_TOKEN_LIST_DATA` | struct | `payloads/Demon/include/core/Token.h:80` | `` |
| `_USER_TOKEN_DATA` | struct | `payloads/Demon/include/core/Token.h:43` | `` |
| `username` | type_alias | `payloads/Demon/include/core/Token.h:42` | `typedef struct _USER_TOKEN_DATA { WCHAR username[MAX_USERNAME];` |
| `DEMON_INTERNET_H` | macro | `payloads/Demon/include/core/Transport.h:2` | `#define DEMON_INTERNET_H` |
| `PIPE_BUFFER_MAX` | macro | `payloads/Demon/include/core/Transport.h:8` | `#define PIPE_BUFFER_MAX` |
| `DEMON_TRANSPORTHTTP_H` | macro | `payloads/Demon/include/core/TransportHttp.h:2` | `#define DEMON_TRANSPORTHTTP_H` |
| `ERROR_INTERNET_CANNOT_CONNECT` | macro | `payloads/Demon/include/core/TransportHttp.h:13` | `#define ERROR_INTERNET_CANNOT_CONNECT` |
| `Host` | type_alias | `payloads/Demon/include/core/TransportHttp.h:14` | `typedef struct _HOST_DATA { /* Host Data */ LPWSTR Host;` |
| `TRANSPORT_HTTP_ROTATION_RANDOM` | macro | `payloads/Demon/include/core/TransportHttp.h:12` | `#define TRANSPORT_HTTP_ROTATION_RANDOM` |
| `TRANSPORT_HTTP_ROTATION_ROUND_ROBIN` | macro | `payloads/Demon/include/core/TransportHttp.h:11` | `#define TRANSPORT_HTTP_ROTATION_ROUND_ROBIN` |
| `_HOST_DATA` | struct | `payloads/Demon/include/core/TransportHttp.h:15` | `` |
| `DEMON_TRANSPORTSMB_H` | macro | `payloads/Demon/include/core/TransportSmb.h:2` | `#define DEMON_TRANSPORTSMB_H` |
| `Attribute` | type_alias | `payloads/Demon/include/core/Win32.h:92` | `typedef struct _PROC_THREAD_ATTRIBUTE_ENTRY { ULONG_PTR Attribute;` |
| `Buffer` | type_alias | `payloads/Demon/include/core/Win32.h:63` | `typedef struct _BUFFER { PVOID Buffer;` |
| `DEMON_WIN32_H` | macro | `payloads/Demon/include/core/Win32.h:2` | `#define DEMON_WIN32_H` |
| `DEREF` | macro | `payloads/Demon/include/core/Win32.h:21` | `#define DEREF( name )` |
| `DEREF_16` | macro | `payloads/Demon/include/core/Win32.h:23` | `#define DEREF_16( name )` |
| `DEREF_32` | macro | `payloads/Demon/include/core/Win32.h:22` | `#define DEREF_32( name )` |
| `ExtendedProcessInfo` | type_alias | `payloads/Demon/include/core/Win32.h:100` | `typedef struct __attribute__((packed)) { ULONG ExtendedProcessInfo;` |
| `FileName` | type_alias | `payloads/Demon/include/core/Win32.h:27` | `typedef struct _DIR_OR_FILE { WCHAR FileName[MAX_PATH+1];` |
| `HASH_KEY` | macro | `payloads/Demon/include/core/Win32.h:18` | `#define HASH_KEY` |
| `Length` | type_alias | `payloads/Demon/include/core/Win32.h:106` | `typedef struct _PROC_THREAD_ATTRIBUTE_LIST { ULONG_PTR Length;` |
| `MAX` | macro | `payloads/Demon/include/core/Win32.h:25` | `#define MAX( a, b )` |
| `MIN` | macro | `payloads/Demon/include/core/Win32.h:26` | `#define MIN( a, b )` |
| `OBJ_ATTR` | type_alias | `payloads/Demon/include/core/Win32.h:115` | `typedef OBJECT_ATTRIBUTES OBJ_ATTR;` |
| `OBJ_ATTR` | type_alias | `payloads/Demon/include/core/Win32.h:116` | `typedef OBJECT_ATTRIBUTES OBJ_ATTR;` |
| `PROC_INFO` | type_alias | `payloads/Demon/include/core/Win32.h:118` | `typedef PROCESS_INFORMATION PROC_INFO;` |
| `PSYS_PROC_INFO` | type_alias | `payloads/Demon/include/core/Win32.h:112` | `typedef PSYSTEM_PROCESS_INFORMATION PSYS_PROC_INFO;` |
| `Path` | type_alias | `payloads/Demon/include/core/Win32.h:38` | `typedef struct _SUB_DIR { WCHAR Path[MAX_PATH+1];` |
| `Path` | type_alias | `payloads/Demon/include/core/Win32.h:45` | `typedef struct _ROOT_DIR { WCHAR Path[MAX_PATH+1];` |
| `SEC_QUALITY_SERVICE` | type_alias | `payloads/Demon/include/core/Win32.h:114` | `typedef SECURITY_QUALITY_OF_SERVICE SEC_QUALITY_SERVICE;` |
| `StdOutRead` | type_alias | `payloads/Demon/include/core/Win32.h:69` | `typedef struct _ANONPIPE { HANDLE StdOutRead;` |
| `THD_ATTR_LIST` | type_alias | `payloads/Demon/include/core/Win32.h:117` | `typedef PROC_THREAD_ATTRIBUTE_LIST THD_ATTR_LIST;` |
| `THREAD_TEB_INFORMATION` | struct | `payloads/Demon/include/core/Win32.h:57` | `` |
| `WIN_FUNC` | macro | `payloads/Demon/include/core/Win32.h:19` | `#define WIN_FUNC(x)` |
| `_ANONPIPE` | struct | `payloads/Demon/include/core/Win32.h:70` | `` |
| `_BUFFER` | struct | `payloads/Demon/include/core/Win32.h:64` | `` |
| `_DIR_OR_FILE` | struct | `payloads/Demon/include/core/Win32.h:28` | `` |
| `_PROC_THREAD_ATTRIBUTE_ENTRY` | struct | `payloads/Demon/include/core/Win32.h:93` | `` |
| `_PROC_THREAD_ATTRIBUTE_LIST` | struct | `payloads/Demon/include/core/Win32.h:107` | `` |
| `_PS_ATTRIBUTE_NUM` | enum | `payloads/Demon/include/core/Win32.h:76` | `` |
| `_ROOT_DIR` | struct | `payloads/Demon/include/core/Win32.h:46` | `` |
| `_SUB_DIR` | struct | `payloads/Demon/include/core/Win32.h:39` | `` |
| `__attribute__` | function | `payloads/Demon/include/core/Win32.h:101` | `typedef struct __attribute__((packed))` |
| `AES256` | macro | `payloads/Demon/include/crypt/AesCrypt.h:7` | `#define AES256` |
| `AES_BLOCKLEN` | macro | `payloads/Demon/include/crypt/AesCrypt.h:13` | `#define AES_BLOCKLEN` |
| `AES_KEYLEN` | macro | `payloads/Demon/include/crypt/AesCrypt.h:14` | `#define AES_KEYLEN` |
| `AES_keyExpSize` | macro | `payloads/Demon/include/crypt/AesCrypt.h:15` | `#define AES_keyExpSize` |
| `AesInit` | function | `payloads/Demon/include/crypt/AesCrypt.h:22` | `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv);` |
| `AesXCryptBuffer` | function | `payloads/Demon/include/crypt/AesCrypt.h:23` | `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length);` |
| `CTR` | macro | `payloads/Demon/include/crypt/AesCrypt.h:6` | `#define CTR` |
| `CTR` | macro | `payloads/Demon/include/crypt/AesCrypt.h:10` | `#define CTR` |
| `_AES_H_` | macro | `payloads/Demon/include/crypt/AesCrypt.h:2` | `#define _AES_H_` |
| `DEMON_BASEINJECT_H` | macro | `payloads/Demon/include/inject/Inject.h:3` | `#define DEMON_BASEINJECT_H` |
| `INJECTION_CTX` | struct | `payloads/Demon/include/inject/Inject.h:31` | `` |
| `INJECTION_TECHNIQUE_APC` | macro | `payloads/Demon/include/inject/Inject.h:12` | `#define INJECTION_TECHNIQUE_APC` |
| `INJECTION_TECHNIQUE_DEFAULT` | macro | `payloads/Demon/include/inject/Inject.h:19` | `#define INJECTION_TECHNIQUE_DEFAULT` |
| `INJECTION_TECHNIQUE_SYSCALL` | macro | `payloads/Demon/include/inject/Inject.h:11` | `#define INJECTION_TECHNIQUE_SYSCALL` |
| `INJECTION_TECHNIQUE_WIN32` | macro | `payloads/Demon/include/inject/Inject.h:10` | `#define INJECTION_TECHNIQUE_WIN32` |
| `INJECT_ERROR_FAILED` | macro | `payloads/Demon/include/inject/Inject.h:49` | `#define INJECT_ERROR_FAILED` |
| `INJECT_ERROR_INVALID_PARAM` | macro | `payloads/Demon/include/inject/Inject.h:50` | `#define INJECT_ERROR_INVALID_PARAM` |
| `INJECT_ERROR_PROCESS_ARCH_MISMATCH` | macro | `payloads/Demon/include/inject/Inject.h:51` | `#define INJECT_ERROR_PROCESS_ARCH_MISMATCH` |
| `INJECT_ERROR_SUCCESS` | macro | `payloads/Demon/include/inject/Inject.h:48` | `#define INJECT_ERROR_SUCCESS` |
| `INJECT_WAY_EXECUTE` | macro | `payloads/Demon/include/inject/Inject.h:55` | `#define INJECT_WAY_EXECUTE` |
| `INJECT_WAY_INJECT` | macro | `payloads/Demon/include/inject/Inject.h:54` | `#define INJECT_WAY_INJECT` |
| `INJECT_WAY_SPAWN` | macro | `payloads/Demon/include/inject/Inject.h:53` | `#define INJECT_WAY_SPAWN` |
| `SPAWN_TECHNIQUE_APC` | macro | `payloads/Demon/include/inject/Inject.h:15` | `#define SPAWN_TECHNIQUE_APC` |
| `SPAWN_TECHNIQUE_DEFAULT` | macro | `payloads/Demon/include/inject/Inject.h:18` | `#define SPAWN_TECHNIQUE_DEFAULT` |
| `SPAWN_TECHNIQUE_SYSCALL` | macro | `payloads/Demon/include/inject/Inject.h:14` | `#define SPAWN_TECHNIQUE_SYSCALL` |
| `_DX_CREATE_THREAD` | enum | `payloads/Demon/include/inject/Inject.h:21` | `` |
| `hProcess` | type_alias | `payloads/Demon/include/inject/Inject.h:30` | `typedef struct INJECTION_CTX { HANDLE hProcess;` |
| `DEMON_INJECTUTIL_H` | macro | `payloads/Demon/include/inject/InjectUtil.h:2` | `#define DEMON_INJECTUTIL_H` |
| `DEREF_16` | macro | `payloads/Demon/include/inject/InjectUtil.h:8` | `#define DEREF_16( name )` |
| `DEREF_32` | macro | `payloads/Demon/include/inject/InjectUtil.h:7` | `#define DEREF_32( name )` |
| `ERROR_INJECT_FAILED_TO_SPAWN_TARGET_PROCESS` | macro | `payloads/Demon/include/inject/InjectUtil.h:27` | `#define ERROR_INJECT_FAILED_TO_SPAWN_TARGET_PROCESS` |
| `ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X64_TO_X86` | macro | `payloads/Demon/include/inject/InjectUtil.h:25` | `#define ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X64_TO_X86` |
| `ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X86_TO_X64` | macro | `payloads/Demon/include/inject/InjectUtil.h:26` | `#define ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X86_TO_X64` |
| `PROC_THREAD_ATTRIBUTE_ADDITIVE` | macro | `payloads/Demon/include/inject/InjectUtil.h:15` | `#define PROC_THREAD_ATTRIBUTE_ADDITIVE` |
| `PROC_THREAD_ATTRIBUTE_INPUT` | macro | `payloads/Demon/include/inject/InjectUtil.h:14` | `#define PROC_THREAD_ATTRIBUTE_INPUT` |
| `PROC_THREAD_ATTRIBUTE_NUMBER` | macro | `payloads/Demon/include/inject/InjectUtil.h:12` | `#define PROC_THREAD_ATTRIBUTE_NUMBER` |
| `PROC_THREAD_ATTRIBUTE_THREAD` | macro | `payloads/Demon/include/inject/InjectUtil.h:13` | `#define PROC_THREAD_ATTRIBUTE_THREAD` |
| `ProcThreadAttributeValue` | macro | `payloads/Demon/include/inject/InjectUtil.h:17` | `#define ProcThreadAttributeValue(Number, Thread, Input, Additive)` |
| `hash_coffapi` | function | `payloads/Demon/scripts/hash_func.py:18` | `def hash_coffapi(string)` |
| `hash_string` | function | `payloads/Demon/scripts/hash_func.py:7` | `def hash_string(string)` |
| `DemonInit` | function | `payloads/Demon/src/Demon.c:267` | `VOID DemonInit( PVOID ModuleInst, PKAYN_ARGS KArgs )` |
| `DemonMain` | function | `payloads/Demon/src/Demon.c:34` | `VOID DemonMain( PVOID ModuleInst, PKAYN_ARGS KArgs )` |
| `DemonMetaData` | function | `payloads/Demon/src/Demon.c:95` | `VOID DemonMetaData( PPACKAGE* MetaData, BOOL Header )` |
| `DemonRoutine` | function | `payloads/Demon/src/Demon.c:64` | `_Noreturn VOID DemonRoutine()` |
| `PRINTF` | function | `payloads/Demon/src/Demon.c:570` | `PRINTF( "Instance DemonID => %x\n", Instance->Session.AgentID ) }  VOID DemonConfig()` |
| `PRINTF` | function | `payloads/Demon/src/Demon.c:645` | `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )     // check if the kill date has...` |
| `PRINTF` | function | `payloads/Demon/src/Demon.c:673` | `PRINTF( " - %ls:%ld\n", Buffer, Temp )          /* if our host address is longer than 0 then lets...` |
| `PRINTF` | function | `payloads/Demon/src/Demon.c:775` | `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )     // check if the kill date has...` |
| `PUTS` | function | `payloads/Demon/src/Demon.c:290` | `PUTS( "TRANSPORT_HTTP" ) #endif  #ifdef TRANSPORT_SMB     PUTS( "TRANSPORT_SMB" ) #endif       /*...` |
| `Spoof` | function | `payloads/Demon/src/asm/Spoof.x64.asm:8` | `` |
| `fixup` | function | `payloads/Demon/src/asm/Spoof.x64.asm:22` | `` |
| `_Spoof` | function | `payloads/Demon/src/asm/Spoof.x86.asm:8` | `` |
| `COFF_INSTANCE` | macro | `payloads/Demon/src/core/CoffeeLdr.c:18` | `#define COFF_INSTANCE` |
| `COFF_INSTANCE` | macro | `payloads/Demon/src/core/CoffeeLdr.c:27` | `#define COFF_INSTANCE` |
| `COFF_PREP_BEACON` | macro | `payloads/Demon/src/core/CoffeeLdr.c:15` | `#define COFF_PREP_BEACON` |
| `COFF_PREP_BEACON` | macro | `payloads/Demon/src/core/CoffeeLdr.c:24` | `#define COFF_PREP_BEACON` |
| `COFF_PREP_BEACON_SIZE` | macro | `payloads/Demon/src/core/CoffeeLdr.c:16` | `#define COFF_PREP_BEACON_SIZE` |
| `COFF_PREP_BEACON_SIZE` | macro | `payloads/Demon/src/core/CoffeeLdr.c:25` | `#define COFF_PREP_BEACON_SIZE` |
| `COFF_PREP_SYMBOL` | macro | `payloads/Demon/src/core/CoffeeLdr.c:12` | `#define COFF_PREP_SYMBOL` |
| `COFF_PREP_SYMBOL` | macro | `payloads/Demon/src/core/CoffeeLdr.c:21` | `#define COFF_PREP_SYMBOL` |
| `COFF_PREP_SYMBOL_SIZE` | macro | `payloads/Demon/src/core/CoffeeLdr.c:13` | `#define COFF_PREP_SYMBOL_SIZE` |
| `COFF_PREP_SYMBOL_SIZE` | macro | `payloads/Demon/src/core/CoffeeLdr.c:22` | `#define COFF_PREP_SYMBOL_SIZE` |
| `CoffeeCleanup` | function | `payloads/Demon/src/core/CoffeeLdr.c:394` | `VOID CoffeeCleanup( PCOFFEE Coffee )` |
| `CoffeeFunction` | function | `payloads/Demon/src/core/CoffeeLdr.c:242` | `VOID CoffeeFunction( PVOID Address, PVOID Argument, SIZE_T Size )` |
| `CoffeeGetFunMapSize` | function | `payloads/Demon/src/core/CoffeeLdr.c:602` | `SIZE_T CoffeeGetFunMapSize( PCOFFEE Coffee )` |
| `CoffeeProcessSections` | function | `payloads/Demon/src/core/CoffeeLdr.c:423` | `BOOL CoffeeProcessSections( PCOFFEE Coffee )` |
| `CoffeeProcessSymbol` | function | `payloads/Demon/src/core/CoffeeLdr.c:87` | `BOOL CoffeeProcessSymbol( PCOFFEE Coffee, LPSTR SymbolName, UINT16 SymbolType, PVOID* pFuncAddr )` |
| `CoffeeRunner` | function | `payloads/Demon/src/core/CoffeeLdr.c:821` | `VOID CoffeeRunner( PCHAR EntryName, DWORD EntryNameSize, PVOID CoffeeData, SIZE_T CoffeeDataSize,...` |
| `CoffeeRunnerThread` | function | `payloads/Demon/src/core/CoffeeLdr.c:799` | `VOID CoffeeRunnerThread( PCOFFEE_PARAMS Param )` |
| `PRINTF` | function | `payloads/Demon/src/core/CoffeeLdr.c:678` | `PRINTF( "[EntryName: %s] [CoffeeData: %p] [ArgData: %p] [ArgSize: %ld]\n", EntryName, CoffeeData,...` |
| `PUTS` | function | `payloads/Demon/src/core/CoffeeLdr.c:251` | `PUTS( "Finished" ) }  BOOL CoffeeExecuteFunction( PCOFFEE Coffee, PCHAR Function, PVOID Argument,...` |
| `PUTS` | function | `payloads/Demon/src/core/CoffeeLdr.c:669` | `PUTS( "Coffe entry was not found" ) }  VOID CoffeeLdr( PCHAR EntryName, PVOID CoffeeData, PVOID A...` |
| `RemoveCoffeeFromInstance` | function | `payloads/Demon/src/core/CoffeeLdr.c:642` | `VOID RemoveCoffeeFromInstance( PCOFFEE Coffee )` |
| `SymbolIncludesLibrary` | function | `payloads/Demon/src/core/CoffeeLdr.c:64` | `BOOL SymbolIncludesLibrary( LPSTR Symbol )` |
| `SymbolIsImport` | function | `payloads/Demon/src/core/CoffeeLdr.c:81` | `BOOL SymbolIsImport( LPSTR Symbol )` |
| `VehDebugger` | function | `payloads/Demon/src/core/CoffeeLdr.c:32` | `LONG WINAPI VehDebugger( PEXCEPTION_POINTERS Exception )` |
| `CommandAssemblyInlineExecute` | function | `payloads/Demon/src/core/Command.c:1708` | `VOID CommandAssemblyInlineExecute( PPARSER Parser )` |
| `CommandConfig` | function | `payloads/Demon/src/core/Command.c:1865` | `VOID CommandConfig( PPARSER Parser )` |
| `CommandDispatcher` | function | `payloads/Demon/src/core/Command.c:48` | `VOID CommandDispatcher( VOID )` |
| `CommandExit` | function | `payloads/Demon/src/core/Command.c:3315` | `VOID CommandExit( PPARSER Parser )` |
| `CommandInjectDLL` | function | `payloads/Demon/src/core/Command.c:1203` | `VOID CommandInjectDLL( PPARSER Parser )` |
| `CommandInjectShellcode` | function | `payloads/Demon/src/core/Command.c:1266` | `VOID CommandInjectShellcode(     IN PPARSER Parser )` |
| `CommandInlineExecute` | function | `payloads/Demon/src/core/Command.c:1114` | `VOID CommandInlineExecute( PPARSER Parser )` |
| `CommandJob` | function | `payloads/Demon/src/core/Command.c:188` | `VOID CommandJob( PPARSER Parser )` |
| `CommandKerberos` | function | `payloads/Demon/src/core/Command.c:3077` | `VOID CommandKerberos(     IN PPARSER Parser )` |
| `CommandMemFile` | function | `payloads/Demon/src/core/Command.c:3237` | `VOID CommandMemFile( PPARSER Parser )` |
| `CommandNet` | function | `payloads/Demon/src/core/Command.c:2109` | `VOID CommandNet( PPARSER Parser )` |
| `CommandPivot` | function | `payloads/Demon/src/core/Command.c:2463` | `VOID CommandPivot( PPARSER Parser )` |
| `CommandProc` | function | `payloads/Demon/src/core/Command.c:263` | `VOID CommandProc( PPARSER Parser )` |
| `CommandProcList` | function | `payloads/Demon/src/core/Command.c:562` | `VOID CommandProcList(     IN PPARSER Parser )` |
| `CommandScreenshot` | function | `payloads/Demon/src/core/Command.c:2084` | `VOID CommandScreenshot( PPARSER Parser )` |
| `CommandSleep` | function | `payloads/Demon/src/core/Command.c:174` | `VOID CommandSleep( PPARSER Parser )` |
| `CommandSocket` | function | `payloads/Demon/src/core/Command.c:2739` | `VOID CommandSocket( PPARSER Parser )` |
| `CommandSpawnDLL` | function | `payloads/Demon/src/core/Command.c:1247` | `VOID CommandSpawnDLL( PPARSER Parser )` |
| `CommandToken` | function | `payloads/Demon/src/core/Command.c:1373` | `VOID CommandToken( PPARSER Parser )` |
| `CommandTransfer` | function | `payloads/Demon/src/core/Command.c:2608` | `VOID CommandTransfer( PPARSER Parser )` |
| `Data` | function | `payloads/Demon/src/core/Command.c:844` | `* * Data (Open): * [ File Size ] * [ File Name ] * * Data (Write) * [ Chunk Data ] Size + FileChunk * * Data...` |
| `InWorkingHours` | function | `payloads/Demon/src/core/Command.c:3263` | `BOOL InWorkingHours( )` |
| `KillDate` | function | `payloads/Demon/src/core/Command.c:3300` | `VOID KillDate( )` |
| `PACKAGE_ERROR_NTSTATUS` | function | `payloads/Demon/src/core/Command.c:671` | `PACKAGE_ERROR_NTSTATUS( NtStatus )     } }  VOID CommandFS( PPARSER Parser )` |
| `PRINTF` | function | `payloads/Demon/src/core/Command.c:107` | `PRINTF( "Task => RequestID:[%d : %x] CommandID:[%d : %x] TaskBuffer:[%x : %d]\n", RequestID, Requ...` |
| `PRINTF` | function | `payloads/Demon/src/core/Command.c:824` | `PRINTF( "FilePath.Buffer[%d]: %ls\n", PathSize, FilePath )              if ( ! Instance->Win32.Ge...` |
| `PRINTF` | function | `payloads/Demon/src/core/Command.c:1293` | `PRINTF(         "Injection Args:      \n"         " - Way     : %d      \n"         " - Method  :...` |
| `PRINTF` | function | `payloads/Demon/src/core/Command.c:1320` | `PRINTF( "Target spawn process: %ls\n", Spawn )              /* create process */             if (...` |
| `PRINTF` | function | `payloads/Demon/src/core/Command.c:1761` | `PRINTF(             "Parsed Arguments:         \n"             " - PipeName     [%d]: %ls \n"    ...` |
| `PRINTF` | function | `payloads/Demon/src/core/Command.c:2997` | `PRINTF( "Socket ID: %x\n", ScId )              /* check if address is not 0 */             if ( I...` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:160` | `PUTS( "Out of while loop" ) }  VOID CommandCheckin( PPARSER Parser )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:272` | `case DEMON_COMMAND_PROC_MODULES: PUTS( "Proc::Modules" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:337` | `case DEMON_COMMAND_PROC_GREP: PUTS("Proc::Grep")` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:423` | `case DEMON_COMMAND_PROC_CREATE: PUTS( "Proc::Create" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:468` | `case DEMON_COMMAND_PROC_MEMORY: PUTS( "Proc::Memory" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:528` | `case DEMON_COMMAND_PROC_KILL: PUTS( "Proc::Kill" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:684` | `case DEMON_COMMAND_FS_DIR: PUTS( "FS::Dir" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:794` | `case DEMON_COMMAND_FS_DOWNLOAD: PUTS( "FS::Download" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:867` | `CleanupDownload:             PUTS( "CleanupDownload" )              if ( FileName.Buffer )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:882` | `case DEMON_COMMAND_FS_UPLOAD: PUTS( "FS::Upload" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:949` | `case DEMON_COMMAND_FS_CD: PUTS( "FS::Cd" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:964` | `case DEMON_COMMAND_FS_REMOVE: PUTS( "FS::Remove" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:994` | `case DEMON_COMMAND_FS_MKDIR: PUTS( "FS::Mkdir" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1010` | `case DEMON_COMMAND_FS_COPY: PUTS( "FS::Copy" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1035` | `case DEMON_COMMAND_FS_MOVE: PUTS( "FS::Move" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1060` | `case DEMON_COMMAND_FS_GET_PWD: PUTS( "FS::GetPwd" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1075` | `case DEMON_COMMAND_FS_CAT: PUTS( "FS::Cat" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1181` | `PUTS( "Use default (from config) CoffeeLdr" )              if ( Instance->Config.Implant.CoffeeTh...` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1312` | `case INJECT_WAY_SPAWN: PUTS( "INJECT_WAY_SPAWN" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1353` | `case INJECT_WAY_INJECT: PUTS( "INJECT_WAY_INJECT" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1358` | `case INJECT_WAY_EXECUTE: PUTS( "INJECT_WAY_EXECUTE" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1383` | `case DEMON_COMMAND_TOKEN_IMPERSONATE: PUTS( "Token::Impersonate" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1406` | `case DEMON_COMMAND_TOKEN_STEAL: PUTS( "Token::Steal" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1450` | `case DEMON_COMMAND_TOKEN_LIST: PUTS( "Token::List" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1477` | `case DEMON_COMMAND_TOKEN_PRIVSGET_OR_LIST: PUTS( "Token::PrivsGetOrList" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1532` | `case DEMON_COMMAND_TOKEN_MAKE: PUTS( "Token::Make" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1595` | `case DEMON_COMMAND_TOKEN_GET_UID: PUTS( "Token::GetUID" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1635` | `case DEMON_COMMAND_TOKEN_REVERT: PUTS( "Token::Revert" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1650` | `case DEMON_COMMAND_TOKEN_REMOVE: PUTS( "Token::Remove" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1660` | `case DEMON_COMMAND_TOKEN_CLEAR: PUTS( "Token::Clear" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1668` | `case DEMON_COMMAND_TOKEN_FIND_TOKENS: PUTS( "Token::Find" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1788` | `PUTS( "Dotnet instance already running." )     } }  VOID CommandAssemblyListVersion( PPARSER Pars...` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1841` | `else         PUTS("Failed to load mscoree.dll")       if ( pClrMetaHost )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2350` | `PUTS( "NetLocalGroupEnum => Success" )                 if ( GroupInfo )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2624` | `case DEMON_COMMAND_TRANSFER_LIST: PUTS( "Transfer::list" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2641` | `case DEMON_COMMAND_TRANSFER_STOP: PUTS( "Transfer::stop" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2668` | `case DEMON_COMMAND_TRANSFER_RESUME: PUTS( "Transfer::resume" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2696` | `case DEMON_COMMAND_TRANSFER_REMOVE: PUTS( "Transfer::remove" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2751` | `case SOCKET_COMMAND_RPORTFWD_ADD: PUTS( "Socket::RPortFwdAdd" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2786` | `case SOCKET_COMMAND_RPORTFWD_LIST: PUTS( "Socket::RPortFwdList" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2819` | `case SOCKET_COMMAND_RPORTFWD_REMOVE: PUTS( "Socket::RPortFwdRemove" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2850` | `case SOCKET_COMMAND_RPORTFWD_CLEAR: PUTS( "Socket::RPortFwdClear" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2871` | `case SOCKET_COMMAND_SOCKSPROXY_ADD: PUTS( "Socket::SocksProxyAdd" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2878` | `case SOCKET_COMMAND_WRITE: PUTS( "Socket::Write" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2942` | `case SOCKET_COMMAND_CONNECT: PUTS( "Socket::Connect" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:3036` | `case SOCKET_COMMAND_CLOSE: PUTS( "Socket::Close" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:3090` | `case KERBEROS_COMMAND_LUID: PUTS("Kerberos::LUID")` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:3117` | `case KERBEROS_COMMAND_KLIST: PUTS("Kerberos::Klist")` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:3205` | `case KERBEROS_COMMAND_PURGE: PUTS("Kerberos::Purge")` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:3216` | `case KERBEROS_COMMAND_PTT: PUTS("Kerberos::Ptt")` |
| `ReachedKillDate` | function | `payloads/Demon/src/core/Command.c:3295` | `BOOL ReachedKillDate()` |
| `ClrCreateInstance` | function | `payloads/Demon/src/core/Dotnet.c:524` | `DWORD ClrCreateInstance( LPCWSTR dotNetVersion, PICLRMetaHost *ppClrMetaHost, PICLRRuntimeInfo *p...` |
| `DotnetClose` | function | `payloads/Demon/src/core/Dotnet.c:379` | `VOID DotnetClose()` |
| `DotnetExecute` | function | `payloads/Demon/src/core/Dotnet.c:19` | `BOOL DotnetExecute( BUFFER Assembly, BUFFER Arguments )` |
| `DotnetPush` | function | `payloads/Demon/src/core/Dotnet.c:347` | `VOID DotnetPush()` |
| `DotnetPushPipe` | function | `payloads/Demon/src/core/Dotnet.c:312` | `VOID DotnetPushPipe()` |
| `FindVersion` | function | `payloads/Demon/src/core/Dotnet.c:501` | `BOOL FindVersion( PVOID Assembly, DWORD length )` |
| `PIPE_BUFFER` | macro | `payloads/Demon/src/core/Dotnet.c:8` | `#define PIPE_BUFFER` |
| `PRINTF` | function | `payloads/Demon/src/core/Dotnet.c:169` | `PRINTF("SafeArrayUnaccessData Failed: %x\n", Result )         PACKAGE_ERROR_WIN32     }      PUTS...` |
| `PRINTF` | function | `payloads/Demon/src/core/Dotnet.c:352` | `PRINTF( "Instance->Dotnet->Invoked: %s\n", Instance->Dotnet->Invoked ? "TRUE" : "FALSE" )     if ...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:101` | `PUTS( "Init HwBp Engine" )         /* use global engine */         if ( ! NT_SUCCESS( HwBpEngineI...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:112` | `PUTS( "HwBp Engine add AmsiScanBuffer bypass" )             if ( ! NT_SUCCESS( Status = HwBpEngin...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:120` | `PUTS( "HwBp Engine add NtTraceEvent bypass" )         if ( ! NT_SUCCESS( HwBpEngineAdd( NULL, Thr...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:148` | `PUTS( "CreateDomain..." )     if ( ( Result = Instance->Dotnet->ICorRuntimeHost->lpVtbl->CreateDo...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:154` | `PUTS( "QueryInterface..." )     if ( ( Result = Instance->Dotnet->AppDomainThunk->lpVtbl->QueryIn...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:179` | `PUTS( "Assembly EntryPoint..." )     if ( ( Result = Instance->Dotnet->Assembly->lpVtbl->EntryPoi...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:237` | `PUTS( "Creating events..." )     if ( NT_SUCCESS( Instance->Win32.NtCreateEvent( &Instance->Dotne...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:286` | `PUTS( "Resume Thread..." )                 if ( NT_SUCCESS( Instance->Win32.NtAlertResumeThread( ...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:428` | `PUTS( "Free Output" )     if ( Instance->Dotnet->Output.Buffer )` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:436` | `PUTS( "Unload and free CLR" )     if ( Instance->Dotnet->MethodArgs )` |
| `DownloadAdd` | function | `payloads/Demon/src/core/Download.c:6` | `PDOWNLOAD_DATA DownloadAdd( HANDLE hFile, LONGLONG MaxSize )` |
| `DownloadFree` | function | `payloads/Demon/src/core/Download.c:41` | `VOID DownloadFree( PDOWNLOAD_DATA Download )` |
| `DownloadGet` | function | `payloads/Demon/src/core/Download.c:27` | `PDOWNLOAD_DATA DownloadGet( DWORD FileID )` |
| `DownloadPush` | function | `payloads/Demon/src/core/Download.c:94` | `VOID DownloadPush()` |
| `DownloadRemove` | function | `payloads/Demon/src/core/Download.c:56` | `BOOL DownloadRemove( DWORD FileID )` |
| `GetMemFile` | function | `payloads/Demon/src/core/Download.c:287` | `PMEM_FILE GetMemFile( ULONG32 ID )` |
| `MemFileFree` | function | `payloads/Demon/src/core/Download.c:339` | `VOID MemFileFree( PMEM_FILE MemFile )` |
| `MemFileIsNew` | function | `payloads/Demon/src/core/Download.c:238` | `BOOL MemFileIsNew( ULONG32 ID )` |
| `MemFileReadChunk` | function | `payloads/Demon/src/core/Download.c:318` | `PMEM_FILE MemFileReadChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )` |
| `NewMemFile` | function | `payloads/Demon/src/core/Download.c:254` | `PMEM_FILE NewMemFile( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )` |
| `PRINTF` | function | `payloads/Demon/src/core/Download.c:129` | `PRINTF( "Allocated memory for DownloadChunk. Buffer:[%p] Size:[%d]\n", Instance->DownloadChunk.Bu...` |
| `ProcessMemFileChunk` | function | `payloads/Demon/src/core/Download.c:302` | `PMEM_FILE ProcessMemFileChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )` |
| `RemoveMemFile` | function | `payloads/Demon/src/core/Download.c:355` | `BOOL RemoveMemFile( ULONG32 ID )` |
| `ExceptionHandler` | function | `payloads/Demon/src/core/HwBpEngine.c:320` | `LONG ExceptionHandler(     _Inout_ PEXCEPTION_POINTERS Exception )` |
| `HwBpEngineAdd` | function | `payloads/Demon/src/core/HwBpEngine.c:152` | `NTSTATUS HwBpEngineAdd(     IN PHWBP_ENGINE Engine,     IN DWORD        Tid,     IN PVOID        ...` |
| `HwBpEngineDestroy` | function | `payloads/Demon/src/core/HwBpEngine.c:261` | `NTSTATUS HwBpEngineDestroy(     IN PHWBP_ENGINE Engine )` |
| `HwBpEngineInit` | function | `payloads/Demon/src/core/HwBpEngine.c:18` | `NTSTATUS HwBpEngineInit(     OUT PHWBP_ENGINE Engine,     IN  PVOID        Handler )` |
| `HwBpEngineRemove` | function | `payloads/Demon/src/core/HwBpEngine.c:209` | `NTSTATUS HwBpEngineRemove(     IN PHWBP_ENGINE Engine,     IN DWORD        Tid,     IN PVOID     ...` |
| `HwBpEngineSetBp` | function | `payloads/Demon/src/core/HwBpEngine.c:61` | `NTSTATUS HwBpEngineSetBp(     IN DWORD Tid,     IN PVOID Address,     IN BYTE  Position,     IN B...` |
| `PRINTF` | function | `payloads/Demon/src/core/HwBpEngine.c:116` | `PRINTF(                 "Dr Registers:  \n"                 "- Dr0[%d]: %p  \n"                 "...` |
| `PRINTF` | function | `payloads/Demon/src/core/HwBpEngine.c:162` | `PRINTF( "Engine:[%p] Tid:[%d] Address:[%p] Function:[%p] Position:[%d]\n", Engine, Tid, Address, ...` |
| `PRINTF` | function | `payloads/Demon/src/core/HwBpEngine.c:355` | `PRINTF( "Found exception handler: %s\n", Found ? "TRUE" : "FALSE" )         if ( Found )` |
| `HwBpExAmsiScanBuffer` | function | `payloads/Demon/src/core/HwBpExceptions.c:6` | `VOID HwBpExAmsiScanBuffer(     _Inout_ PEXCEPTION_POINTERS Exception )` |
| `HwBpExNtTraceEvent` | function | `payloads/Demon/src/core/HwBpExceptions.c:23` | `VOID HwBpExNtTraceEvent(     _Inout_ PEXCEPTION_POINTERS Exception )` |
| `JobAdd` | function | `payloads/Demon/src/core/Jobs.c:17` | `VOID JobAdd( UINT32 RequestID, DWORD JobID, SHORT Type, SHORT State, HANDLE Handle, PVOID Data )` |
| `JobCheckList` | function | `payloads/Demon/src/core/Jobs.c:63` | `VOID JobCheckList()` |
| `JobKill` | function | `payloads/Demon/src/core/Jobs.c:277` | `BOOL JobKill( DWORD JobID )` |
| `JobRemove` | function | `payloads/Demon/src/core/Jobs.c:383` | `VOID JobRemove( DWORD JobID )` |
| `JobResume` | function | `payloads/Demon/src/core/Jobs.c:230` | `BOOL JobResume( DWORD JobID )` |
| `JobSuspend` | function | `payloads/Demon/src/core/Jobs.c:184` | `BOOL JobSuspend( DWORD JobID )` |
| `PRINTF` | function | `payloads/Demon/src/core/Jobs.c:192` | `PRINTF( "Found Job ID: %d", JobID )              if ( JobList->Type == JOB_TYPE_THREAD )` |
| `PRINTF` | function | `payloads/Demon/src/core/Jobs.c:238` | `PRINTF( "Found Job ID: %d", JobID )              if ( JobList->Type == JOB_TYPE_THREAD )` |
| `PRINTF` | function | `payloads/Demon/src/core/Jobs.c:287` | `PRINTF( "Found Job ID: %d\n", JobID )              switch ( JobList->Type )` |
| `PUTS` | function | `payloads/Demon/src/core/Jobs.c:300` | `PUTS( "Kill using handle" )                              if ( ! NT_SUCCESS( NtStatus = Instance->...` |
| `CopySessionInfo` | function | `payloads/Demon/src/core/Kerberos.c:337` | `VOID CopySessionInfo( PSESSION_INFORMATION Session, PSECURITY_LOGON_SESSION_DATA Data )` |
| `CopyTicketInfo` | function | `payloads/Demon/src/core/Kerberos.c:371` | `VOID CopyTicketInfo( PTICKET_INFORMATION TicketInfo, PKERB_TICKET_CACHE_INFO_EX Data )` |
| `ElevateToSystem` | function | `payloads/Demon/src/core/Kerberos.c:61` | `BOOL ElevateToSystem()` |
| `ExtractTicket` | function | `payloads/Demon/src/core/Kerberos.c:283` | `VOID ExtractTicket( HANDLE hLsa, ULONG authPackage, LUID luid, UNICODE_STRING targetName, PUCHAR*...` |
| `GetLUID` | function | `payloads/Demon/src/core/Kerberos.c:752` | `LUID* GetLUID( HANDLE hToken )` |
| `GetLogonSessionData` | function | `payloads/Demon/src/core/Kerberos.c:218` | `NTSTATUS GetLogonSessionData( LUID luid, PLOGON_SESSION_DATA* data )` |
| `GetLsaHandle` | function | `payloads/Demon/src/core/Kerberos.c:155` | `NTSTATUS GetLsaHandle( HANDLE hToken, BOOL highIntegrity, PHANDLE hLsa )` |
| `GetProcessIdByName` | function | `payloads/Demon/src/core/Kerberos.c:29` | `DWORD GetProcessIdByName(WCHAR* processName)` |
| `IsHighIntegrity` | function | `payloads/Demon/src/core/Kerberos.c:8` | `BOOL IsHighIntegrity(HANDLE TokenHandle)` |
| `IsSystem` | function | `payloads/Demon/src/core/Kerberos.c:131` | `BOOL IsSystem( HANDLE TokenHandle )` |
| `Klist` | function | `payloads/Demon/src/core/Kerberos.c:585` | `PSESSION_INFORMATION Klist( HANDLE hToken, LUID luid )` |
| `Ptt` | function | `payloads/Demon/src/core/Kerberos.c:399` | `BOOL Ptt( HANDLE hToken, PBYTE Ticket, DWORD TicketSize, LUID luid )` |
| `Purge` | function | `payloads/Demon/src/core/Kerberos.c:494` | `BOOL Purge( HANDLE hToken, LUID luid )` |
| `FreeReflectiveLoader` | function | `payloads/Demon/src/core/Memory.c:269` | `BOOL FreeReflectiveLoader(     IN PVOID BaseAddress )` |
| `MmGadgetFind` | function | `payloads/Demon/src/core/Memory.c:240` | `PVOID MmGadgetFind(     _In_ PVOID  Memory,     _In_ SIZE_T Length,     _In_ PVOID  PatternBuffer...` |
| `MmHeapAlloc` | function | `payloads/Demon/src/core/Memory.c:15` | `PVOID MmHeapAlloc(     _In_ ULONG Length )` |
| `MmHeapFree` | function | `payloads/Demon/src/core/Memory.c:48` | `BOOL MmHeapFree(     _In_ PVOID Memory )` |
| `MmHeapReAlloc` | function | `payloads/Demon/src/core/Memory.c:31` | `PVOID MmHeapReAlloc(     _In_ PVOID Memory,     _In_ ULONG Length )` |
| `MmVirtualAlloc` | function | `payloads/Demon/src/core/Memory.c:62` | `PVOID MmVirtualAlloc(     IN DX_MEMORY Methode,     IN HANDLE    Process,     IN SIZE_T    Size, ...` |
| `MmVirtualFree` | function | `payloads/Demon/src/core/Memory.c:209` | `BOOL MmVirtualFree(     IN HANDLE Process,     IN PVOID  Memory )` |
| `MmVirtualProtect` | function | `payloads/Demon/src/core/Memory.c:133` | `BOOL MmVirtualProtect(     IN DX_MEMORY Method,     IN HANDLE    Process,     IN PVOID     Memory...` |
| `MmVirtualWrite` | function | `payloads/Demon/src/core/Memory.c:189` | `BOOL MmVirtualWrite(     IN  HANDLE Process,     OUT PVOID  Memory,     IN  PVOID  Buffer,     IN...` |
| `PUTS` | function | `payloads/Demon/src/core/Memory.c:79` | `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )` |
| `PUTS` | function | `payloads/Demon/src/core/Memory.c:147` | `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )` |
| `CharStringToWCharString` | function | `payloads/Demon/src/core/MiniStd.c:242` | `SIZE_T CharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )` |
| `EndsWithIW` | function | `payloads/Demon/src/core/MiniStd.c:80` | `BOOL EndsWithIW( LPWSTR String, LPWSTR Ending )` |
| `GetSystemFileTime` | function | `payloads/Demon/src/core/MiniStd.c:300` | `UINT64 GetSystemFileTime( )` |
| `HashStringA` | function | `payloads/Demon/src/core/MiniStd.c:100` | `DWORD HashStringA( PCHAR String )` |
| `HideChar` | function | `payloads/Demon/src/core/MiniStd.c:313` | `BYTE NO_INLINE HideChar( BYTE C )` |
| `MemCompare` | function | `payloads/Demon/src/core/MiniStd.c:205` | `INT MemCompare( PVOID s1, PVOID s2, INT len)` |
| `StringCompareA` | function | `payloads/Demon/src/core/MiniStd.c:9` | `INT StringCompareA( LPCSTR String1, LPCSTR String2 )` |
| `StringCompareIW` | function | `payloads/Demon/src/core/MiniStd.c:53` | `INT StringCompareIW( LPWSTR String1, LPWSTR String2 )` |
| `StringCompareW` | function | `payloads/Demon/src/core/MiniStd.c:21` | `INT StringCompareW( LPWSTR String1, LPWSTR String2 )` |
| `StringConcatA` | function | `payloads/Demon/src/core/MiniStd.c:151` | `PCHAR StringConcatA(PCHAR String, PCHAR String2)` |
| `StringConcatW` | function | `payloads/Demon/src/core/MiniStd.c:158` | `PWCHAR StringConcatW(PWCHAR String, PWCHAR String2)` |
| `StringCopyA` | function | `payloads/Demon/src/core/MiniStd.c:112` | `PCHAR StringCopyA(PCHAR String1, PCHAR String2)` |
| `StringCopyW` | function | `payloads/Demon/src/core/MiniStd.c:121` | `PWCHAR StringCopyW(PWCHAR String1, PWCHAR String2)` |
| `StringLengthA` | function | `payloads/Demon/src/core/MiniStd.c:130` | `SIZE_T StringLengthA(LPCSTR String)` |
| `StringLengthW` | function | `payloads/Demon/src/core/MiniStd.c:142` | `SIZE_T StringLengthW(LPCWSTR String)` |
| `StringNCompareIW` | function | `payloads/Demon/src/core/MiniStd.c:65` | `INT StringNCompareIW( LPWSTR String1, LPWSTR String2, INT Length )` |
| `StringNCompareW` | function | `payloads/Demon/src/core/MiniStd.c:33` | `INT StringNCompareW( LPWSTR String1, LPWSTR String2, INT Length )` |
| `StringTokenA` | function | `payloads/Demon/src/core/MiniStd.c:255` | `PCHAR StringTokenA(PCHAR String, CONST PCHAR Delim)` |
| `ToLowerCaseW` | function | `payloads/Demon/src/core/MiniStd.c:48` | `WCHAR ToLowerCaseW( WCHAR C )` |
| `WCharStringToCharString` | function | `payloads/Demon/src/core/MiniStd.c:229` | `SIZE_T WCharStringToCharString(PCHAR Destination, PWCHAR Source, SIZE_T MaximumAllowed)` |
| `WcsIStr` | function | `payloads/Demon/src/core/MiniStd.c:185` | `LPWSTR WcsIStr( PWCHAR String, PWCHAR String2 )` |
| `WcsStr` | function | `payloads/Demon/src/core/MiniStd.c:165` | `LPWSTR WcsStr( PWCHAR String, PWCHAR String2 )` |
| `FoliageObf` | function | `payloads/Demon/src/core/Obf.c:22` | `VOID FoliageObf(     IN PSLEEP_PARAM Param )` |
| `PRINTF` | function | `payloads/Demon/src/core/Obf.c:603` | `PRINTF( "RtlCreateTimerQueue/NtCreateEvent Failed: %lx\n", NtStatus )     }  LEAVE: /* cleanup */...` |
| `SleepObf` | function | `payloads/Demon/src/core/Obf.c:714` | `VOID SleepObf(     VOID )` |
| `SleepTime` | function | `payloads/Demon/src/core/Obf.c:650` | `UINT32 SleepTime(     VOID )` |
| `BeaconAddValue` | function | `payloads/Demon/src/core/ObjectApi.c:584` | `BOOL BeaconAddValue(const char * key, void * ptr)` |
| `BeaconCleanupProcess` | function | `payloads/Demon/src/core/ObjectApi.c:564` | `VOID BeaconCleanupProcess( PROCESS_INFORMATION* pInfo )` |
| `BeaconDataExtract` | function | `payloads/Demon/src/core/ObjectApi.c:190` | `PCHAR BeaconDataExtract( PDATA parser, PINT size )` |
| `BeaconDataInt` | function | `payloads/Demon/src/core/ObjectApi.c:155` | `INT BeaconDataInt( PDATA parser )` |
| `BeaconDataLength` | function | `payloads/Demon/src/core/ObjectApi.c:185` | `INT BeaconDataLength( PDATA parser )` |
| `BeaconDataParse` | function | `payloads/Demon/src/core/ObjectApi.c:143` | `VOID BeaconDataParse( PDATA parser, PCHAR buffer, INT size )` |
| `BeaconDataShort` | function | `payloads/Demon/src/core/ObjectApi.c:170` | `SHORT BeaconDataShort( datap* parser )` |
| `BeaconDataStoreGetItem` | function | `payloads/Demon/src/core/ObjectApi.c:690` | `PDATA_STORE_OBJECT BeaconDataStoreGetItem(SIZE_T index)` |
| `BeaconDataStoreMaxEntries` | function | `payloads/Demon/src/core/ObjectApi.c:711` | `SIZE_T BeaconDataStoreMaxEntries()` |
| `BeaconDataStoreProtectItem` | function | `payloads/Demon/src/core/ObjectApi.c:697` | `VOID BeaconDataStoreProtectItem(SIZE_T index)` |
| `BeaconDataStoreUnprotectItem` | function | `payloads/Demon/src/core/ObjectApi.c:704` | `VOID BeaconDataStoreUnprotectItem(SIZE_T index)` |
| `BeaconFormatAlloc` | function | `payloads/Demon/src/core/ObjectApi.c:343` | `VOID BeaconFormatAlloc( PFORMAT format, int maxsz )` |
| `BeaconFormatAppend` | function | `payloads/Demon/src/core/ObjectApi.c:377` | `VOID BeaconFormatAppend( PFORMAT format, char* text, int len )` |
| `BeaconFormatFree` | function | `payloads/Demon/src/core/ObjectApi.c:361` | `VOID BeaconFormatFree( PFORMAT format )` |
| `BeaconFormatInt` | function | `payloads/Demon/src/core/ObjectApi.c:411` | `VOID BeaconFormatInt( PFORMAT format, int value)` |
| `BeaconFormatPrintf` | function | `payloads/Demon/src/core/ObjectApi.c:384` | `VOID BeaconFormatPrintf( PFORMAT format, char* fmt, ... )` |
| `BeaconFormatReset` | function | `payloads/Demon/src/core/ObjectApi.c:354` | `VOID BeaconFormatReset( PFORMAT format )` |
| `BeaconFormatToString` | function | `payloads/Demon/src/core/ObjectApi.c:405` | `char* BeaconFormatToString( PFORMAT format, int* size)` |
| `BeaconGetCustomUserData` | function | `payloads/Demon/src/core/ObjectApi.c:718` | `PCHAR BeaconGetCustomUserData()` |
| `BeaconGetSpawnTo` | function | `payloads/Demon/src/core/ObjectApi.c:440` | `VOID BeaconGetSpawnTo( BOOL x86, char* buffer, int length )` |
| `BeaconGetValue` | function | `payloads/Demon/src/core/ObjectApi.c:633` | `PVOID BeaconGetValue(const char * key)` |
| `BeaconInformation` | function | `payloads/Demon/src/core/ObjectApi.c:578` | `VOID BeaconInformation(BEACON_INFO * info)` |
| `BeaconInjectProcess` | function | `payloads/Demon/src/core/ObjectApi.c:487` | `VOID BeaconInjectProcess( HANDLE hProc, int pid, char* payload, int p_len, int p_offset, char * a...` |
| `BeaconInjectTemporaryProcess` | function | `payloads/Demon/src/core/ObjectApi.c:530` | `VOID BeaconInjectTemporaryProcess( PROCESS_INFORMATION* pInfo, char* payload, int p_len, int p_of...` |
| `BeaconIsAdmin` | function | `payloads/Demon/src/core/ObjectApi.c:324` | `BOOL BeaconIsAdmin(     VOID )` |
| `BeaconOutput` | function | `payloads/Demon/src/core/ObjectApi.c:305` | `VOID BeaconOutput( INT Type, PCHAR data, INT len )` |
| `BeaconPrintf` | function | `payloads/Demon/src/core/ObjectApi.c:248` | `VOID BeaconPrintf( INT Type, PCHAR fmt, ... )` |
| `BeaconRemoveValue` | function | `payloads/Demon/src/core/ObjectApi.c:656` | `BOOL BeaconRemoveValue(const char * key)` |
| `BeaconSpawnTemporaryProcess` | function | `payloads/Demon/src/core/ObjectApi.c:463` | `BOOL BeaconSpawnTemporaryProcess( BOOL x86, BOOL ignoreToken, STARTUPINFO* sInfo, PROCESS_INFORMA...` |
| `BeaconUseToken` | function | `payloads/Demon/src/core/ObjectApi.c:425` | `BOOL BeaconUseToken( HANDLE token )` |
| `GetRequestIDForCallingObjectFile` | function | `payloads/Demon/src/core/ObjectApi.c:224` | `BOOL GetRequestIDForCallingObjectFile( PVOID CoffeeFunctionReturn, PUINT32 RequestID )` |
| `LdrFreeLibrary` | function | `payloads/Demon/src/core/ObjectApi.c:32` | `BOOL LdrFreeLibrary( HMODULE hLibModule )` |
| `LdrFunctionAddrString` | function | `payloads/Demon/src/core/ObjectApi.c:26` | `PVOID LdrFunctionAddrString( PVOID Module, PCHAR Function )` |
| `LdrLocalFree` | function | `payloads/Demon/src/core/ObjectApi.c:37` | `HLOCAL LdrLocalFree( PVOID hMem )` |
| `LdrModulePebString` | function | `payloads/Demon/src/core/ObjectApi.c:20` | `PVOID LdrModulePebString( PCHAR ModuleString )` |
| `bufsize` | macro | `payloads/Demon/src/core/ObjectApi.c:16` | `#define bufsize` |
| `swap_endianess` | function | `payloads/Demon/src/core/ObjectApi.c:131` | `uint32_t swap_endianess(uint32_t indata)` |
| `toWideChar` | function | `payloads/Demon/src/core/ObjectApi.c:724` | `BOOL toWideChar( char* src, wchar_t* dst, int max )` |
| `AES256` | macro | `payloads/Demon/src/core/Package.c:10` | `#define AES256` |
| `CTR` | macro | `payloads/Demon/src/core/Package.c:9` | `#define CTR` |
| `Int32ToBuffer` | function | `payloads/Demon/src/core/Package.c:39` | `VOID Int32ToBuffer(     OUT PUCHAR Buffer,     IN  UINT32 Size )` |
| `Int64ToBuffer` | function | `payloads/Demon/src/core/Package.c:13` | `VOID Int64ToBuffer( PUCHAR Buffer, UINT64 Value )` |
| `PUTS_DONT_SEND` | function | `payloads/Demon/src/core/Package.c:264` | `PUTS_DONT_SEND("TransportSend failed!")         }          if ( Package->Destroy )` |
| `PackageAddBool` | function | `payloads/Demon/src/core/Package.c:85` | `VOID PackageAddBool(     _Inout_ PPACKAGE Package,     IN     BOOLEAN  Data )` |
| `PackageAddBytes` | function | `payloads/Demon/src/core/Package.c:125` | `VOID PackageAddBytes( PPACKAGE Package, PBYTE Data, SIZE_T Size )` |
| `PackageAddInt32` | function | `payloads/Demon/src/core/Package.c:49` | `VOID PackageAddInt32(     _Inout_ PPACKAGE Package,     IN     UINT32   Data )` |
| `PackageAddInt64` | function | `payloads/Demon/src/core/Package.c:68` | `VOID PackageAddInt64( PPACKAGE Package, UINT64 dataInt )` |
| `PackageAddPad` | function | `payloads/Demon/src/core/Package.c:109` | `VOID PackageAddPad( PPACKAGE Package, PCHAR Data, SIZE_T Size )` |
| `PackageAddPtr` | function | `payloads/Demon/src/core/Package.c:104` | `VOID PackageAddPtr( PPACKAGE Package, PVOID pointer )` |
| `PackageAddString` | function | `payloads/Demon/src/core/Package.c:147` | `VOID PackageAddString( PPACKAGE package, PCHAR data )` |
| `PackageAddWString` | function | `payloads/Demon/src/core/Package.c:152` | `VOID PackageAddWString( PPACKAGE package, PWCHAR data )` |
| `PackageCreate` | function | `payloads/Demon/src/core/Package.c:157` | `PPACKAGE PackageCreate( UINT32 CommandID )` |
| `PackageCreateWithMetaData` | function | `payloads/Demon/src/core/Package.c:174` | `PPACKAGE PackageCreateWithMetaData( UINT32 CommandID )` |
| `PackageCreateWithRequestID` | function | `payloads/Demon/src/core/Package.c:187` | `PPACKAGE PackageCreateWithRequestID( UINT32 CommandID, UINT32 RequestID )` |
| `PackageDestroy` | function | `payloads/Demon/src/core/Package.c:196` | `VOID PackageDestroy(     IN PPACKAGE Package )` |
| `PackageTransmit` | function | `payloads/Demon/src/core/Package.c:281` | `VOID PackageTransmit(     IN PPACKAGE Package )` |
| `PackageTransmitAll` | function | `payloads/Demon/src/core/Package.c:333` | `BOOL PackageTransmitAll(     OUT    PVOID*   Response,     OUT    PSIZE_T  Size )` |
| `PackageTransmitError` | function | `payloads/Demon/src/core/Package.c:471` | `VOID PackageTransmitError(     IN UINT32 ID,     IN UINT32 ErrorCode )` |
| `PackageTransmitNow` | function | `payloads/Demon/src/core/Package.c:229` | `BOOL PackageTransmitNow(     _Inout_ PPACKAGE Package,     OUT    PVOID*   Response,     OUT    P...` |
| `ParserDecrypt` | function | `payloads/Demon/src/core/Parser.c:21` | `VOID ParserDecrypt( PPARSER parser, PBYTE Key, PBYTE IV )` |
| `ParserDestroy` | function | `payloads/Demon/src/core/Parser.c:168` | `VOID ParserDestroy( PPARSER Parser )` |
| `ParserGetBool` | function | `payloads/Demon/src/core/Parser.c:106` | `BOOL ParserGetBool( PPARSER parser )` |
| `ParserGetByte` | function | `payloads/Demon/src/core/Parser.c:48` | `BYTE ParserGetByte( PPARSER parser )` |
| `ParserGetBytes` | function | `payloads/Demon/src/core/Parser.c:127` | `PBYTE ParserGetBytes( PPARSER parser, PUINT32 size )` |
| `ParserGetInt16` | function | `payloads/Demon/src/core/Parser.c:33` | `INT16 ParserGetInt16( PPARSER parser )` |
| `ParserGetInt32` | function | `payloads/Demon/src/core/Parser.c:64` | `INT ParserGetInt32( PPARSER parser )` |
| `ParserGetInt64` | function | `payloads/Demon/src/core/Parser.c:85` | `INT64 ParserGetInt64( PPARSER parser )` |
| `ParserGetString` | function | `payloads/Demon/src/core/Parser.c:158` | `PCHAR  ParserGetString( PPARSER parser, PUINT32 size )` |
| `ParserGetWString` | function | `payloads/Demon/src/core/Parser.c:163` | `PWCHAR  ParserGetWString( PPARSER parser, PUINT32 size )` |
| `ParserNew` | function | `payloads/Demon/src/core/Parser.c:7` | `VOID ParserNew( PPARSER parser, PBYTE Buffer, UINT32 size )` |
| `PivotAdd` | function | `payloads/Demon/src/core/Pivot.c:24` | `BOOL PivotAdd( BUFFER NamedPipe, PVOID* Output, PDWORD BytesSize )` |
| `PivotCount` | function | `payloads/Demon/src/core/Pivot.c:218` | `DWORD PivotCount()` |
| `PivotGet` | function | `payloads/Demon/src/core/Pivot.c:121` | `PPIVOT_DATA PivotGet( DWORD AgentID )` |
| `PivotParseDemonID` | function | `payloads/Demon/src/core/Pivot.c:331` | `UINT32 PivotParseDemonID( PVOID Response, SIZE_T Size )` |
| `PivotPush` | function | `payloads/Demon/src/core/Pivot.c:235` | `VOID PivotPush()` |
| `PivotRemove` | function | `payloads/Demon/src/core/Pivot.c:139` | `BOOL PivotRemove( DWORD AgentId )` |
| `RtAdvapi32` | function | `payloads/Demon/src/core/Runtime.c:6` | `BOOL RtAdvapi32(     VOID )` |
| `RtAmsi` | function | `payloads/Demon/src/core/Runtime.c:433` | `BOOL RtAmsi(     VOID )` |
| `RtGdi32` | function | `payloads/Demon/src/core/Runtime.c:273` | `BOOL RtGdi32(     VOID )` |
| `RtIphlpapi` | function | `payloads/Demon/src/core/Runtime.c:240` | `BOOL RtIphlpapi(     VOID )` |
| `RtMscoree` | function | `payloads/Demon/src/core/Runtime.c:68` | `BOOL RtMscoree(     VOID )` |
| `RtMsvcrt` | function | `payloads/Demon/src/core/Runtime.c:208` | `BOOL RtMsvcrt(     VOID )` |
| `RtNetApi32` | function | `payloads/Demon/src/core/Runtime.c:310` | `BOOL RtNetApi32(     VOID )` |
| `RtOleaut32` | function | `payloads/Demon/src/core/Runtime.c:103` | `BOOL RtOleaut32(     VOID )` |
| `RtShell32` | function | `payloads/Demon/src/core/Runtime.c:176` | `BOOL RtShell32(     VOID )` |
| `RtSspicli` | function | `payloads/Demon/src/core/Runtime.c:394` | `BOOL RtSspicli(     VOID )` |
| `RtUser32` | function | `payloads/Demon/src/core/Runtime.c:142` | `BOOL RtUser32(     VOID )` |

Next: [SYMBOLS_p10.md](SYMBOLS_p10.md)
