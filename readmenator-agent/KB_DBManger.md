# Subsystem: DBManger

## client/src/Havoc/DBManger/DBManager.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `DBManager` (function, line 9) `DBManager::DBManager( const QString& FilePath, int OpenFlag )`
  - `createNewDatabase` (function, line 32) `bool DBManager::createNewDatabase()`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

## client/src/Havoc/DBManger/Scripts.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `AddScript` (function, line 3) `bool HavocNamespace::HavocSpace::DBManager::AddScript( QString Path )`
  - `RemoveScript` (function, line 20) `bool HavocNamespace::HavocSpace::DBManager::RemoveScript( QString Path )`
  - `CheckScript` (function, line 41) `bool HavocNamespace::HavocSpace::DBManager::CheckScript( QString Path )`
  - `GetScripts` (function, line 63) `vector<QString> HavocNamespace::HavocSpace::DBManager::GetScripts()`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

## client/src/Havoc/DBManger/Teamserver.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `addTeamserverInfo` (function, line 6) `bool HavocSpace::DBManager::addTeamserverInfo( const Util::ConnectionInfo& connection )`
  - `checkTeamserverExists` (function, line 31) `bool HavocSpace::DBManager::checkTeamserverExists( const QString& ProfileName )`
  - `removeTeamserverInfo` (function, line 55) `bool HavocSpace::DBManager::removeTeamserverInfo( const QString& ProfileName )`
  - `listTeamservers` (function, line 75) `vector<Util::ConnectionInfo> HavocSpace::DBManager::listTeamservers()`
  - `removeAllTeamservers` (function, line 104) `bool HavocSpace::DBManager::removeAllTeamservers()`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`
