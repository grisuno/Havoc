# Subsystem: DBManger

## client/src/Havoc/DBManger/DBManager.cc
- Layer: infrastructure
- Doc: include <Havoc/DBManager/DBManager.hpp> include <QFileInfo>
- Language: cc
- Symbols:
  - `DBManager` (function, line 8) `DBManager::DBManager( const QString& FilePath, int OpenFlag )`
  - `createNewDatabase` (function, line 31) `bool DBManager::createNewDatabase()`
  - `info` (function, line 22) `spdlog::info( "Successful created database" );`
  - `error` (function, line 24) `spdlog::error( "Failed to create a new database" );`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

## client/src/Havoc/DBManger/Scripts.cc
- Layer: infrastructure
- Doc: include <Havoc/DBManager/DBManager.hpp>
- Language: cc
- Symbols:
  - `AddScript` (function, line 2) `bool HavocNamespace::HavocSpace::DBManager::AddScript( QString Path )`
  - `RemoveScript` (function, line 19) `bool HavocNamespace::HavocSpace::DBManager::RemoveScript( QString Path )`
  - `CheckScript` (function, line 40) `bool HavocNamespace::HavocSpace::DBManager::CheckScript( QString Path )`
  - `GetScripts` (function, line 62) `vector<QString> HavocNamespace::HavocSpace::DBManager::GetScripts()`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

## client/src/Havoc/DBManger/Teamserver.cc
- Layer: infrastructure
- Doc: include <Havoc/DBManager/DBManager.hpp> include <QSqlError>
- Language: cc
- Symbols:
  - `addTeamserverInfo` (function, line 5) `bool HavocSpace::DBManager::addTeamserverInfo( const Util::ConnectionInfo& connection )`
  - `checkTeamserverExists` (function, line 30) `bool HavocSpace::DBManager::checkTeamserverExists( const QString& ProfileName )`
  - `removeTeamserverInfo` (function, line 54) `bool HavocSpace::DBManager::removeTeamserverInfo( const QString& ProfileName )`
  - `listTeamservers` (function, line 74) `vector<Util::ConnectionInfo> HavocSpace::DBManager::listTeamservers()`
  - `removeAllTeamservers` (function, line 103) `bool HavocSpace::DBManager::removeAllTeamservers()`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`
