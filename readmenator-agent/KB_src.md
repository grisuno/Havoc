# Subsystem: src

## client/src/Main.cc
- Layer: infrastructure
- Language: cc
- Depends on: `client/include/Havoc/Havoc.hpp`, `client/include/global.hpp`

## client/src/global.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `gen_random` (function, line 31) `std::string Util::gen_random( const int len )`
  - `Export` (function, line 42) `void Util::SessionItem::Export()`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/global.hpp`
