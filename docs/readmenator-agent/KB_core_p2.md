# Subsystem: core (page 2 of 2)
Previous: [KB_core.md](KB_core.md)

## payloads/Demon/include/core/Token.h
- Doc: Handle: ULONG HighWaterHandleTableUsage; ULONG InvalidAttributes; GENERIC_MAPPING...
- Layer: utility
- Language: h
- Symbols:
  - `_PROCESS_LIST` (struct, line 37)
  - `_USER_TOKEN_DATA` (struct, line 43)
  - `_OBJECT_TYPE_INFORMATION_V2` (struct, line 53)
  - `_TOKEN_LIST_DATA` (struct, line 80)
  - `Count` (type_alias, line 36) `typedef struct _PROCESS_LIST { ULONG Count;`
  - `username` (type_alias, line 42) `typedef struct _USER_TOKEN_DATA { WCHAR username[MAX_USERNAME];`
  - `TypeName` (type_alias, line 52) `typedef struct _OBJECT_TYPE_INFORMATION_V2 { UNICODE_STRING TypeName;`
  - `Handle` (type_alias, line 80) `typedef struct _TOKEN_LIST_DATA { HANDLE Handle;`
  - `SEC_IMP_LEVEL` (type_alias, line 94) `typedef SECURITY_IMPERSONATION_LEVEL SEC_IMP_LEVEL;`
  - `DEMON_TOKEN_H` (macro, line 2) `#define DEMON_TOKEN_H`
  - `TOKEN_TYPE_STOLEN` (macro, line 7) `#define TOKEN_TYPE_STOLEN`
  - `TOKEN_TYPE_MAKE_NETWORK` (macro, line 8) `#define TOKEN_TYPE_MAKE_NETWORK`
  - `TOKEN_OWNER_FLAG_DEFAULT` (macro, line 10) `#define TOKEN_OWNER_FLAG_DEFAULT`
  - `TOKEN_OWNER_FLAG_USER` (macro, line 11) `#define TOKEN_OWNER_FLAG_USER`
  - `TOKEN_OWNER_FLAG_DOMAIN` (macro, line 12) `#define TOKEN_OWNER_FLAG_DOMAIN`
  - `MAX_PROCESSES` (macro, line 14) `#define MAX_PROCESSES`
  - `BUF_SIZE` (macro, line 15) `#define BUF_SIZE`
  - `MAX_USERNAME` (macro, line 16) `#define MAX_USERNAME`
  - `RtlOffsetToPointer` (macro, line 18) `#define RtlOffsetToPointer(B,O)`
  - `ALIGN_UP_TYPE` (macro, line 21) `#define ALIGN_UP_TYPE(Address, Align)`
  - `ALIGN_UP` (macro, line 25) `#define ALIGN_UP(Address, Type)`
  - `ObjectTypesInformation` (macro, line 28) `#define ObjectTypesInformation`
  - `OBJECT_TYPES_FIRST_ENTRY` (macro, line 30) `#define OBJECT_TYPES_FIRST_ENTRY(ObjectTypes)`
  - `OBJECT_TYPES_NEXT_ENTRY` (macro, line 33) `#define OBJECT_TYPES_NEXT_ENTRY(ObjectType)`
- Depends on: `payloads/Demon/include/core/Win32.h`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/src/core/Command.c`, `payloads/Demon/src/core/Kerberos.c`, `payloads/Demon/src/core/Token.c`

## payloads/Demon/include/core/Transport.h
- Layer: utility
- Language: h
- Symbols:
  - `DEMON_INTERNET_H` (macro, line 2) `#define DEMON_INTERNET_H`
  - `PIPE_BUFFER_MAX` (macro, line 8) `#define PIPE_BUFFER_MAX`
- Depends on: `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/TransportHttp.h`, `payloads/Demon/include/core/TransportSmb.h`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/src/Demon.c`, `payloads/Demon/src/core/Package.c`, `payloads/Demon/src/core/Transport.c`

## payloads/Demon/include/core/TransportHttp.h
- Doc: Host: define TRANSPORT_HTTP_ROTATION_ROUND_ROBIN  0 define TRANSPORT_HTTP_ROTATION_RANDOM...
- Layer: presentation
- Language: h
- Symbols:
  - `_HOST_DATA` (struct, line 15)
  - `Host` (type_alias, line 14) `typedef struct _HOST_DATA { /* Host Data */ LPWSTR Host;`
  - `DEMON_TRANSPORTHTTP_H` (macro, line 2) `#define DEMON_TRANSPORTHTTP_H`
  - `TRANSPORT_HTTP_ROTATION_ROUND_ROBIN` (macro, line 11) `#define TRANSPORT_HTTP_ROTATION_ROUND_ROBIN`
  - `TRANSPORT_HTTP_ROTATION_RANDOM` (macro, line 12) `#define TRANSPORT_HTTP_ROTATION_RANDOM`
  - `ERROR_INTERNET_CANNOT_CONNECT` (macro, line 13) `#define ERROR_INTERNET_CANNOT_CONNECT`
- Depends on: `payloads/Demon/include/core/Win32.h`
- Imported by: `payloads/Demon/include/core/Transport.h`, `payloads/Demon/src/core/Transport.c`, `payloads/Demon/src/core/TransportHttp.c`

## payloads/Demon/include/core/TransportSmb.h
- Doc: Objects we allocated and need to free
- Layer: utility
- Language: h
- Symbols:
  - `DEMON_TRANSPORTSMB_H` (macro, line 2) `#define DEMON_TRANSPORTSMB_H`
- Depends on: `payloads/Demon/include/core/Win32.h`
- Imported by: `payloads/Demon/include/core/Transport.h`, `payloads/Demon/src/core/Package.c`, `payloads/Demon/src/core/Transport.c`, `payloads/Demon/src/core/TransportSmb.c`

## payloads/Demon/include/core/Win32.h
- Doc: FileName: define MAX( a, b ) ( ( a ) > ( b ) ?
- Layer: utility
- Language: h
- Symbols:
  - `_DIR_OR_FILE` (struct, line 28)
  - `_SUB_DIR` (struct, line 39)
  - `_ROOT_DIR` (struct, line 46)
  - `_BUFFER` (struct, line 64)
  - `_ANONPIPE` (struct, line 70)
  - `_PROC_THREAD_ATTRIBUTE_ENTRY` (struct, line 93)
  - `_PROC_THREAD_ATTRIBUTE_LIST` (struct, line 107)
  - `THREAD_TEB_INFORMATION` (struct, line 57)
  - `_PS_ATTRIBUTE_NUM` (enum, line 76)
  - `FileName` (type_alias, line 27) `typedef struct _DIR_OR_FILE { WCHAR FileName[MAX_PATH+1];`
  - `Path` (type_alias, line 38) `typedef struct _SUB_DIR { WCHAR Path[MAX_PATH+1];`
  - `Path` (type_alias, line 45) `typedef struct _ROOT_DIR { WCHAR Path[MAX_PATH+1];`
  - `Buffer` (type_alias, line 63) `typedef struct _BUFFER { PVOID Buffer;`
  - `StdOutRead` (type_alias, line 69) `typedef struct _ANONPIPE { HANDLE StdOutRead;`
  - `Attribute` (type_alias, line 92) `typedef struct _PROC_THREAD_ATTRIBUTE_ENTRY { ULONG_PTR Attribute;`
  - `ExtendedProcessInfo` (type_alias, line 100) `typedef struct __attribute__((packed)) { ULONG ExtendedProcessInfo;`
  - `Length` (type_alias, line 106) `typedef struct _PROC_THREAD_ATTRIBUTE_LIST { ULONG_PTR Length;`
  - `PSYS_PROC_INFO` (type_alias, line 112) `typedef PSYSTEM_PROCESS_INFORMATION PSYS_PROC_INFO;`
  - `SEC_QUALITY_SERVICE` (type_alias, line 114) `typedef SECURITY_QUALITY_OF_SERVICE SEC_QUALITY_SERVICE;`
  - `OBJ_ATTR` (type_alias, line 115) `typedef OBJECT_ATTRIBUTES OBJ_ATTR;`
  - `OBJ_ATTR` (type_alias, line 116) `typedef OBJECT_ATTRIBUTES OBJ_ATTR;`
  - `THD_ATTR_LIST` (type_alias, line 117) `typedef PROC_THREAD_ATTRIBUTE_LIST THD_ATTR_LIST;`
  - `PROC_INFO` (type_alias, line 118) `typedef PROCESS_INFORMATION PROC_INFO;`
  - `__attribute__` (function, line 101) `typedef struct __attribute__((packed))`
  - `DEMON_WIN32_H` (macro, line 2) `#define DEMON_WIN32_H`
  - `HASH_KEY` (macro, line 18) `#define HASH_KEY`
  - `WIN_FUNC` (macro, line 19) `#define WIN_FUNC(x)`
  - `DEREF` (macro, line 21) `#define DEREF( name )`
  - `DEREF_32` (macro, line 22) `#define DEREF_32( name )`
  - `DEREF_16` (macro, line 23) `#define DEREF_16( name )`
  - `MAX` (macro, line 25) `#define MAX( a, b )`
  - `MIN` (macro, line 26) `#define MIN( a, b )`
- Depends on: `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/Syscalls.h`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Clr.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/TransportHttp.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/src/Demon.c`, `payloads/Demon/src/core/CoffeeLdr.c`, `payloads/Demon/src/core/Kerberos.c`, `payloads/Demon/src/core/Obf.c`, `payloads/Demon/src/core/ObjectApi.c`, `payloads/Demon/src/core/Syscalls.c`, `payloads/Demon/src/core/Thread.c`, `payloads/Demon/src/core/Token.c`, `payloads/Demon/src/core/Win32.c`, `payloads/Demon/src/inject/Inject.c`

