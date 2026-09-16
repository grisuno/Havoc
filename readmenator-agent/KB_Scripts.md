# Subsystem: Scripts

## payloads/Shellcode/Scripts/Hasher.c
- Layer: utility
- Doc: include <stdio.h> include <ctype.h>
- Language: c
- Symbols:
  - `Hash` (function, line 3) `long Hash( char* String )`
  - `ToUpperString` (function, line 14) `void ToUpperString(char * temp)`
  - `main` (function, line 23) `int main(int argc, char** argv)`
  - `printf` (function, line 30) `printf("\n[+] Hashed %s ==> 0x%x\n\n", argv[1], Hash( argv[1] ));`

## payloads/Shellcode/Scripts/extract.py
- Layer: utility
- Doc: -*- coding:utf-8 -*-
- Language: py
