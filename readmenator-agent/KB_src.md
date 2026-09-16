# Subsystem: src

## client/src/Main.cc
- Layer: infrastructure
- Doc: include <global.hpp> include <Havoc/Havoc.hpp> include <QTimer>
- Language: cc
- Symbols:
  - `setWindowIcon` (function, line 11) `QGuiApplication::setWindowIcon( QIcon( ":/Havoc.ico" ) );`
- Depends on: `client/include/Havoc/Havoc.hpp`, `client/include/global.hpp`

## client/src/global.cc
- Layer: infrastructure
- Doc: include <global.hpp> include <random>  include <Havoc/Connector.hpp>  include <QFileDialog>
- Language: cc
- Symbols:
  - `gen_random` (function, line 30) `std::string Util::gen_random( const int len )`
  - `Export` (function, line 41) `void Util::SessionItem::Export()`
  - `shuffle` (function, line 36) `std::shuffle( str.begin(), str.end(), gen );`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/global.hpp`
