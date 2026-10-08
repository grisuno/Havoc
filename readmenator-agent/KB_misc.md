# Subsystem: misc

## client/include/Havoc/DBManager/DBManager.hpp
- Layer: infrastructure
- Language: hpp
- Symbols:
  - `createNewDatabase` (function, line 17) `bool createNewDatabase();`
  - `addTeamserverInfo` (function, line 27) `bool addTeamserverInfo( const Util::ConnectionInfo& );`
  - `checkTeamserverExists` (function, line 28) `bool checkTeamserverExists( const QString& ProfileName );`
  - `removeTeamserverInfo` (function, line 29) `bool removeTeamserverInfo( const QString& ProfileName );`
  - `removeAllTeamservers` (function, line 30) `bool removeAllTeamservers();`
  - `AddScript` (function, line 33) `bool AddScript( QString Path );`
  - `RemoveScript` (function, line 34) `bool RemoveScript( QString Path );`
  - `CheckScript` (function, line 35) `bool CheckScript( QString Path );`
  - `HAVOC_DBMANAGER_HPP` (macro, line 2) `#define HAVOC_DBMANAGER_HPP`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/DBManger/DBManager.cc`, `client/src/Havoc/DBManger/Scripts.cc`, `client/src/Havoc/DBManger/Teamserver.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

## client/include/UserInterface/HavocUI.hpp
- Layer: presentation
- Doc: QT libraries
- Language: hpp
- Symbols:
  - `MarkSessionAs` (function, line 68) `public: void MarkSessionAs( HavocNamespace::Util::SessionItem session, QString Mark );`
  - `UpdateSessionsHealth` (function, line 69) `void UpdateSessionsHealth();`
  - `setupUi` (function, line 70) `void setupUi( QMainWindow *Havoc );`
  - `retranslateUi` (function, line 71) `void retranslateUi( QMainWindow *Havoc ) const;`
  - `setDBManager` (function, line 72) `void setDBManager( HavocSpace::DBManager* dbManager );`
  - `NewTeamserverTab` (function, line 73) `void NewTeamserverTab( HavocNamespace::Util::ConnectionInfo* );`
  - `NewBottomTab` (function, line 75) `void NewBottomTab( QWidget* TabWidget, const std::string& TitleName, const QString IconPath = "" ) const;`
  - `NewSmallTab` (function, line 76) `void NewSmallTab( QWidget* TabWidget, const std::string& TitleName ) const;`
  - `ConnectEvents` (function, line 77) `void ConnectEvents();`
  - `PythonPrepare` (function, line 78) `void PythonPrepare();`
  - `OneSecondTick` (function, line 81) `public slots: void OneSecondTick();`
  - `HAVOC_HAVOCUI_HPP` (macro, line 2) `#define HAVOC_HAVOCUI_HPP`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`

## client/include/UserInterface/SmallWidgets/EventViewer.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `setupUi` (function, line 12) `void setupUi(QWidget* Widget);`
  - `AppendText` (function, line 13) `void AppendText(const QString& Time, const QString &text) const;`
  - `HAVOC_EVENTVIEWER_HPP` (macro, line 2) `#define HAVOC_EVENTVIEWER_HPP`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/src/UserInterface/HavocUi.cc
- Layer: presentation
- Doc: Headers for UserInterface
- Language: cc
- Symbols:
  - `setupUi` (function, line 28) `void HavocNamespace::UserInterface::HavocUi::setupUi(QMainWindow *Havoc)`
  - `OneSecondTick` (function, line 200) `void HavocNamespace::UserInterface::HavocUi::OneSecondTick()`
  - `MarkSessionAs` (function, line 205) `void HavocNamespace::UserInterface::HavocUi::MarkSessionAs(HavocNamespace::Util::SessionItem Sess...`
  - `UpdateSessionsHealth` (function, line 263) `void HavocNamespace::UserInterface::HavocUi::UpdateSessionsHealth()`
  - `retranslateUi` (function, line 361) `void HavocNamespace::UserInterface::HavocUi::retranslateUi(QMainWindow* Havoc ) const`
  - `ConnectEvents` (function, line 395) `void HavocNamespace::UserInterface::HavocUi::ConnectEvents()`
  - `connect` (function, line 399) `QMainWindow::connect( OneSecondTimer, &QTimer::timeout, this, [&]()`
  - `connect` (function, line 404) `QMainWindow::connect( actionNew_Client, &QAction::triggered, this, []()`
  - `connect` (function, line 408) `QMainWindow::connect( actionChat, &QAction::triggered, this, [&]()`
  - `connect` (function, line 422) `QMainWindow::connect( actionDisconnect, &QAction::triggered, this, []()`
  - `connect` (function, line 431) `QMainWindow::connect( actionExit, &QAction::triggered, this, []()`
  - `connect` (function, line 435) `QMainWindow::connect( actionSessionsTable, &QAction::triggered, this, []()`
  - `connect` (function, line 439) `QMainWindow::connect( actionListeners, &QAction::triggered, this, [&]()`
  - `connect` (function, line 455) `QMainWindow::connect( actionTeamserver, &QAction::triggered, this, [&]()`
  - `connect` (function, line 467) `QMainWindow::connect( actionStore, &QAction::triggered, this, [&]()`
  - `connect` (function, line 479) `QMainWindow::connect( actionSessionsGraph, &QAction::triggered, this, [&]()`
  - `connect` (function, line 483) `QMainWindow::connect( actionLogs, &QAction::triggered, this, [&]()`
  - `connect` (function, line 498) `QMainWindow::connect( actionLoot, &QAction::triggered, this, [&]()`
  - `connect` (function, line 506) `QMainWindow::connect( actionGeneratePayload, &QAction::triggered, this, []()`
  - `connect` (function, line 516) `QMainWindow::connect( actionPythonConsole, &QAction::triggered, this, [&]()`
  - `connect` (function, line 530) `QMainWindow::connect( actionLoad_Script, &QAction::triggered, this, [&]()`
  - `connect` (function, line 549) `QMainWindow::connect( actionAbout, &QAction::triggered, this, [&]()`
  - `connect` (function, line 558) `QMainWindow::connect( actionGithub_Repository, &QAction::triggered, this, []()`
  - `connect` (function, line 562) `QMainWindow::connect( actionOpen_Help_Documentation, &QAction::triggered, this, []()`
  - `NewBottomTab` (function, line 567) `void HavocNamespace::UserInterface::HavocUi::NewBottomTab(QWidget* TabWidget, const std::string& ...`
  - `setDBManager` (function, line 572) `void HavocNamespace::UserInterface::HavocUi::setDBManager(HavocSpace::DBManager* dbManager)`
  - `NewTeamserverTab` (function, line 577) `void UserInterface::HavocUi::NewTeamserverTab(HavocNamespace::Util::ConnectionInfo* Connection )`
  - `NewTeamserverTab` (function, line 587) `void UserInterface::HavocUi::NewTeamserverTab(QString Name )`
  - `NewSmallTab` (function, line 596) `void UserInterface::HavocUi::NewSmallTab(QWidget *TabWidget, const string &TitleName ) const`
  - `PythonPrepare` (function, line 602) `void UserInterface::HavocUi::PythonPrepare()`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/SmallWidgets/EventViewer.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `setupUi` (function, line 4) `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::setupUi(QWidget *Widget)`
  - `AppendText` (function, line 23) `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::AppendText(const QString& Time, co...`
- Depends on: `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/Util/ColorText.h`

## payloads/Demon/include/Demon.h
- Layer: utility
- Language: h
- Symbols:
  - `_CONFIG` (struct, line 121)
  - `Session` (struct, line 48)
  - `Instance` (variable, line 559) `extern PINSTANCE Instance;`
  - `DEMON_DEMON_H` (macro, line 2) `#define DEMON_DEMON_H`
- Depends on: `payloads/Demon/include/common/Clr.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Pivot.h`, `payloads/Demon/include/core/Socket.h`, `payloads/Demon/include/core/Spoof.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`
- Imported by: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/src/Demon.c`, `payloads/Demon/src/core/CoffeeLdr.c`, `payloads/Demon/src/core/Command.c`, `payloads/Demon/src/core/Dotnet.c`, `payloads/Demon/src/core/Download.c`, `payloads/Demon/src/core/HwBpEngine.c`, `payloads/Demon/src/core/HwBpExceptions.c`, `payloads/Demon/src/core/Jobs.c`, `payloads/Demon/src/core/Kerberos.c`, `payloads/Demon/src/core/Memory.c`, `payloads/Demon/src/core/MiniStd.c`, `payloads/Demon/src/core/Obf.c`, `payloads/Demon/src/core/ObjectApi.c`, `payloads/Demon/src/core/Parser.c`, `payloads/Demon/src/core/Pivot.c`, `payloads/Demon/src/core/Runtime.c`, `payloads/Demon/src/core/Socket.c`, `payloads/Demon/src/core/SysNative.c`, `payloads/Demon/src/core/Syscalls.c`, `payloads/Demon/src/core/Thread.c`, `payloads/Demon/src/core/Token.c`, `payloads/Demon/src/core/Transport.c`, `payloads/Demon/src/core/TransportHttp.c`, `payloads/Demon/src/core/TransportSmb.c`, `payloads/Demon/src/core/Win32.c`, `payloads/Demon/src/inject/Inject.c`, `payloads/Demon/src/inject/InjectUtil.c`, `payloads/Demon/src/main/MainDll.c`, `payloads/Demon/src/main/MainExe.c`, `payloads/Demon/src/main/MainSvc.c`

## payloads/Demon/include/crypt/AesCrypt.h
- Layer: utility
- Language: h
- Symbols:
  - `AesInit` (function, line 22) `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv);`
  - `AesXCryptBuffer` (function, line 23) `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length);`
  - `_AES_H_` (macro, line 2) `#define _AES_H_`
  - `CTR` (macro, line 6) `#define CTR`
  - `AES256` (macro, line 7) `#define AES256`
  - `CTR` (macro, line 10) `#define CTR`
  - `AES_BLOCKLEN` (macro, line 13) `#define AES_BLOCKLEN`
  - `AES_KEYLEN` (macro, line 14) `#define AES_KEYLEN`
  - `AES_keyExpSize` (macro, line 15) `#define AES_keyExpSize`
- Imported by: `payloads/Demon/src/core/Package.c`, `payloads/Demon/src/core/Parser.c`, `payloads/Demon/src/core/Transport.c`, `payloads/Demon/src/crypt/AesCrypt.c`

## payloads/Demon/scripts/hash_func.py
- Layer: utility
- Doc: credit: https://github.com/tigr0w/realoriginal_titanldr-ng/blob/5b8835143f36adfb8d077823e18f21d3043960fb/python3/hashstr
- Language: py
- Symbols:
  - `hash_string` (function, line 7) `def hash_string(string)`
  - `hash_coffapi` (function, line 18) `def hash_coffapi(string)`

## payloads/Demon/src/Demon.c
- Layer: utility
- Doc: Import Common Headers
- Language: c
- Symbols:
  - `DemonMain` (function, line 34) `VOID DemonMain( PVOID ModuleInst, PKAYN_ARGS KArgs )`
  - `DemonRoutine` (function, line 64) `_Noreturn
VOID DemonRoutine()`
  - `DemonMetaData` (function, line 95) `VOID DemonMetaData( PPACKAGE* MetaData, BOOL Header )`
  - `DemonInit` (function, line 267) `VOID DemonInit( PVOID ModuleInst, PKAYN_ARGS KArgs )`
  - `PUTS` (function, line 290) `PUTS( "TRANSPORT_HTTP" )
#endif

#ifdef TRANSPORT_SMB
    PUTS( "TRANSPORT_SMB" )
#endif


    /*...`
  - `PRINTF` (function, line 570) `PRINTF( "Instance DemonID => %x\n", Instance->Session.AgentID )
}

VOID DemonConfig()`
  - `PRINTF` (function, line 645) `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...`
  - `PRINTF` (function, line 673) `PRINTF( " - %ls:%ld\n", Buffer, Temp )

        /* if our host address is longer than 0 then lets...`
  - `PRINTF` (function, line 775) `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Runtime.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`

## payloads/Demon/src/crypt/AesCrypt.c
- Layer: utility
- Language: c
- Symbols:
  - `KeyExpansion` (function, line 47) `void KeyExpansion(UINT8* RoundKey, const UINT8* Key)`
  - `AesInit` (function, line 103) `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv)`
  - `AddRoundKey` (function, line 111) `static void AddRoundKey(UINT8 round, state_t* state, const UINT8* RoundKey)`
  - `SubBytes` (function, line 125) `static void SubBytes(state_t* state)`
  - `ShiftRows` (function, line 140) `static void ShiftRows(state_t* state)`
  - `xtime` (function, line 168) `static UINT8 xtime(UINT8 x)`
  - `MixColumns` (function, line 174) `static void MixColumns(state_t* state)`
  - `AesXCryptBuffer` (function, line 217) `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length)`
  - `Nb` (macro, line 4) `#define Nb`
  - `Nk` (macro, line 7) `#define Nk`
  - `Nr` (macro, line 8) `#define Nr`
  - `Nk` (macro, line 10) `#define Nk`
  - `Nr` (macro, line 11) `#define Nr`
  - `Nk` (macro, line 13) `#define Nk`
  - `Nr` (macro, line 14) `#define Nr`
  - `MULTIPLY_AS_A_FUNCTION` (macro, line 18) `#define MULTIPLY_AS_A_FUNCTION`
  - `getSBoxValue` (macro, line 45) `#define getSBoxValue(num)`
- Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/crypt/AesCrypt.h`

## payloads/DllLdr/Scripts/extract.py
- Layer: utility
- Language: py
- Symbols:
  - `main` (function, line 8) `def main(options)`

## payloads/DllLdr/Source/Entry.c
- Layer: utility
- Language: c
- Symbols:
  - `KaynLoader` (function, line 5) `DLLEXPORT VOID KaynLoader( LPVOID lpParameter )`
  - `KaynCaller` (function, line 144) `NAKED LPVOID KaynCaller( PVOID StartAddress )`
  - `Memcpy` (function, line 166) `NAKED VOID Memcpy( PVOID Destination, PVOID source, SIZE_T Size )`
  - `KGetModuleByHash` (function, line 185) `PVOID KGetModuleByHash( DWORD ModuleHash )`
  - `CopyDotStr` (function, line 206) `FORCE_INLINE UINT32 CopyDotStr( PCHAR String )`
  - `KGetProcAddressByHash` (function, line 215) `PVOID KGetProcAddressByHash( PINSTANCE Instance, PVOID DllModuleBase, DWORD FunctionHash, DWORD O...`
  - `KResolveIAT` (function, line 265) `VOID KResolveIAT( PINSTANCE Instance, LPVOID KaynImage, LPVOID IatDir )`
  - `KReAllocSections` (function, line 306) `VOID KReAllocSections( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir )`
  - `KLoadLibrary` (function, line 331) `PVOID KLoadLibrary( PINSTANCE Instance, LPSTR ModuleName )`
  - `KHashString` (function, line 364) `DWORD KHashString( PVOID String, SIZE_T Length )`
  - `KStringLengthA` (function, line 393) `SIZE_T KStringLengthA( LPCSTR String )`
  - `KStringLengthW` (function, line 400) `SIZE_T KStringLengthW(LPCWSTR String)`
  - `KCharStringToWCharString` (function, line 409) `SIZE_T KCharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )`

## payloads/Shellcode/Source/Asm/x64/Asm.s
- Layer: utility
- Language: s

## payloads/Shellcode/Source/Asm/x86/Asm.s
- Layer: utility
- Language: s

## teamserver/pkg/colors/colors.go
- Layer: utility
- Language: go
- Imported by: `teamserver/cmd/cmd.go`, `teamserver/cmd/server.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/service.go`

## teamserver/pkg/common/builder/builder.go
- Layer: presentation
- Language: go
- Symbols:
  - `NewBuilder` (function, line 141) `func NewBuilder(`
  - `SetSilent` (function, line 213) `func (b *Builder) SetSilent(`
  - `Build` (function, line 217) `func (b *Builder) Build(`
  - `SetListener` (function, line 459) `func (b *Builder) SetListener(`
  - `SetPatchConfig` (function, line 464) `func (b *Builder) SetPatchConfig(`
  - `SetFormat` (function, line 481) `func (b *Builder) SetFormat(`
  - `SetArch` (function, line 485) `func (b *Builder) SetArch(`
  - `SetConfig` (function, line 489) `func (b *Builder) SetConfig(`
  - `SetOutputPath` (function, line 501) `func (b *Builder) SetOutputPath(`
  - `SetExtension` (function, line 505) `func (b *Builder) SetExtension(`
  - `GetOutputPath` (function, line 509) `func (b *Builder) GetOutputPath(`
  - `Patch` (function, line 513) `func (b *Builder) Patch(`
  - `PatchConfig` (function, line 561) `func (b *Builder) PatchConfig(`
  - `GetPayloadBytes` (function, line 1024) `func (b *Builder) GetPayloadBytes(`
  - `Cmd` (function, line 1064) `func (b *Builder) Cmd(`
  - `CompileCmd` (function, line 1090) `func (b *Builder) CompileCmd(`
  - `GetListenerDefines` (function, line 1102) `func (b *Builder) GetListenerDefines(`
  - `DeletePayload` (function, line 1122) `func (b *Builder) DeletePayload(`
  - `BuilderConfig` (struct, line 70)
  - `Builder` (struct, line 78)
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

## teamserver/pkg/common/certs/https.go
- Layer: presentation
- Language: go
- Symbols:
  - `randomState` (function, line 115) `func randomState(`
  - `randomLocality` (function, line 123) `func randomLocality(`
  - `randomStreetAddress` (function, line 132) `func randomStreetAddress(`
  - `randomProvinceLocalityStreetAddress` (function, line 137) `func randomProvinceLocalityStreetAddress(`
  - `randomPostalCode` (function, line 144) `func randomPostalCode(`
  - `randomSubject` (function, line 153) `func randomSubject(`
  - `randomOrganization` (function, line 166) `func randomOrganization(`
  - `publicKey` (function, line 182) `func publicKey(`
  - `randomInt` (function, line 193) `func randomInt(`
  - `pemBlockForKey` (function, line 200) `func pemBlockForKey(`
  - `generateCertificate` (function, line 216) `func generateCertificate(`
  - `HTTPSGenerateRSACertificate` (function, line 300) `func HTTPSGenerateRSACertificate(`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/common/crypt/aes.go
- Layer: utility
- Language: go
- Symbols:
  - `XCryptBytesAES256` (function, line 10) `func XCryptBytesAES256(`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/common/packer/packer.go
- Layer: utility
- Language: go
- Symbols:
  - `NewPacker` (function, line 22) `func NewPacker(`
  - `AddInt64` (function, line 29) `func (p *Packer) AddInt64(`
  - `AddInt32` (function, line 37) `func (p *Packer) AddInt32(`
  - `AddInt` (function, line 45) `func (p *Packer) AddInt(`
  - `AddUInt32` (function, line 54) `func (p *Packer) AddUInt32(`
  - `AddString` (function, line 62) `func (p *Packer) AddString(`
  - `AddWString` (function, line 66) `func (p *Packer) AddWString(`
  - `AddBytes` (function, line 70) `func (p *Packer) AddBytes(`
  - `Build` (function, line 80) `func (p *Packer) Build(`
  - `Buffer` (function, line 95) `func (p *Packer) Buffer(`
  - `Size` (function, line 99) `func (p *Packer) Size(`
  - `AddOwnSizeFirst` (function, line 103) `func (p *Packer) AddOwnSizeFirst(`
  - `Packer` (struct, line 14)
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

## teamserver/pkg/common/parser/parser.go
- Layer: utility
- Language: go
- Symbols:
  - `NewParser` (function, line 24) `func NewParser(`
  - `CanIRead` (function, line 31) `func (p *Parser) CanIRead(`
  - `ParseInt32` (function, line 82) `func (p *Parser) ParseInt32(`
  - `ParseInt64` (function, line 106) `func (p *Parser) ParseInt64(`
  - `ParseBool` (function, line 130) `func (p *Parser) ParseBool(`
  - `ParsePointer` (function, line 154) `func (p *Parser) ParsePointer(`
  - `SetBigEndian` (function, line 158) `func (p *Parser) SetBigEndian(`
  - `ParseBytes` (function, line 162) `func (p *Parser) ParseBytes(`
  - `ParseAtLeastBytes` (function, line 177) `func (p *Parser) ParseAtLeastBytes(`
  - `ParseUTF16String` (function, line 189) `func (p *Parser) ParseUTF16String(`
  - `ParseString` (function, line 193) `func (p *Parser) ParseString(`
  - `Length` (function, line 197) `func (p *Parser) Length(`
  - `Buffer` (function, line 201) `func (p *Parser) Buffer(`
  - `DecryptBuffer` (function, line 205) `func (p *Parser) DecryptBuffer(`
  - `Parser` (struct, line 19)

## teamserver/pkg/common/util.go
- Layer: utility
- Language: go
- Symbols:
  - `ParseWorkingHours` (function, line 26) `func ParseWorkingHours(`
  - `Bmp2Png` (function, line 76) `func Bmp2Png(`
  - `DecodeUTF16` (function, line 99) `func DecodeUTF16(`
  - `EncodeUTF16` (function, line 118) `func EncodeUTF16(`
  - `EncodeUTF8` (function, line 135) `func EncodeUTF8(`
  - `ByteCountSI` (function, line 144) `func ByteCountSI(`
  - `XorCipher` (function, line 158) `func XorCipher(`
  - `RandomString` (function, line 166) `func RandomString(`
  - `Int32ToLittle` (function, line 175) `func Int32ToLittle(`
  - `StripNull` (function, line 181) `func StripNull(`
  - `PercentageChange` (function, line 185) `func PercentageChange(`
  - `IpStringToInt32` (function, line 189) `func IpStringToInt32(`
  - `Int32ToIpString` (function, line 198) `func Int32ToIpString(`
  - `EpochTimeToSystemTime` (function, line 209) `func EpochTimeToSystemTime(`
  - `GetRandomChar` (function, line 222) `func GetRandomChar(`
  - `GeneratePipeName` (function, line 227) `func GeneratePipeName(`
  - `GetInterfaceIpv4Addr` (function, line 279) `func GetInterfaceIpv4Addr(`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/profile/yaotl/guide/conf.py
- Layer: presentation
- Language: py

## teamserver/pkg/profile/yaotl/hclparse/parser.go
- Layer: utility
- Doc: Package hclparse has the main API entry point for parsing both HCL native syntax and HCL JSON.  The main HCL package als
- Language: go
- Symbols:
  - `NewParser` (function, line 43) `func NewParser(`
  - `ParseHCL` (function, line 52) `func (p *Parser) ParseHCL(`
  - `ParseHCLFile` (function, line 65) `func (p *Parser) ParseHCLFile(`
  - `ParseJSON` (function, line 86) `func (p *Parser) ParseJSON(`
  - `ParseJSONFile` (function, line 98) `func (p *Parser) ParseJSONFile(`
  - `AddFile` (function, line 110) `func (p *Parser) AddFile(`
  - `Sources` (function, line 119) `func (p *Parser) Sources(`
  - `Files` (function, line 133) `func (p *Parser) Files(`
  - `Parser` (struct, line 38)

## teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go
- Layer: utility
- Doc: Package hclsimple is a higher-level entry point for loading HCL configuration files directly into Go struct values in a 
- Language: go
- Symbols:
  - `Decode` (function, line 53) `func Decode(`
  - `DecodeFile` (function, line 72) `func DecodeFile(`
- Imported by: `teamserver/pkg/profile/profile.go`, `teamserver/pkg/profile/yaotl/doc.go`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/config/fuzz.go
- Layer: infrastructure
- Language: go
- Symbols:
  - `Fuzz` (function, line 8) `func Fuzz(`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/expr/fuzz.go
- Layer: utility
- Language: go
- Symbols:
  - `Fuzz` (function, line 8) `func Fuzz(`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/template/fuzz.go
- Layer: presentation
- Language: go
- Symbols:
  - `Fuzz` (function, line 8) `func Fuzz(`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/traversal/fuzz.go
- Layer: utility
- Language: go
- Symbols:
  - `Fuzz` (function, line 8) `func Fuzz(`

## teamserver/pkg/profile/yaotl/hclwrite/fuzz/config/fuzz.go
- Layer: infrastructure
- Language: go
- Symbols:
  - `Fuzz` (function, line 10) `func Fuzz(`

## teamserver/pkg/profile/yaotl/json/fuzz/config/fuzz.go
- Layer: infrastructure
- Language: go
- Symbols:
  - `Fuzz` (function, line 7) `func Fuzz(`

## teamserver/pkg/profile/yaotl/specsuite/spec_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestMain` (function, line 15) `func TestMain(`
  - `build` (function, line 30) `func build(`
  - `TestSpec` (function, line 44) `func TestSpec(`
  - `goBuild` (function, line 91) `func goBuild(`

## teamserver/pkg/utils/utils.go
- Layer: utility
- Language: go
- Symbols:
  - `UTF16BytesToString` (function, line 25) `func UTF16BytesToString(`
  - `GenerateID` (function, line 34) `func GenerateID(`
  - `GenerateString` (function, line 53) `func GenerateString(`
  - `EncodeCommand` (function, line 65) `func EncodeCommand(`
  - `IP2Inet` (function, line 70) `func IP2Inet(`
  - `Port2Htons` (function, line 84) `func Port2Htons(`
  - `ByteCountSI` (function, line 90) `func ByteCountSI(`
  - `GetTeamserverPath` (function, line 104) `func GetTeamserverPath(`
  - `IntToHexString` (function, line 131) `func IntToHexString(`
  - `HexIntToString` (function, line 135) `func HexIntToString(`
  - `HexIntToBigEndian` (function, line 141) `func HexIntToBigEndian(`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

## teamserver/pkg/win32/types.go
- Layer: utility
- Language: go
- Symbols:
  - `StatusToString` (function, line 78) `func StatusToString(`
