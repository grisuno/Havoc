# Subsystem: misc

## client/include/Havoc/DBManager/DBManager.hpp
- Layer: infrastructure
- Doc: ifndef HAVOC_DBMANAGER_HPP define HAVOC_DBMANAGER_HPP  include <global.hpp>  include <QSqlDatabase> include <QSqlQuery> 
- Language: hpp
- Symbols:
  - `createNewDatabase` (function, line 16) `bool createNewDatabase();`
  - `DBManager` (function, line 24) `DBManager(const QString& FilePath, int OpenFlag = OpenSqlFile);`
  - `addTeamserverInfo` (function, line 26) `bool addTeamserverInfo( const Util::ConnectionInfo& );`
  - `checkTeamserverExists` (function, line 28) `bool checkTeamserverExists( const QString& ProfileName );`
  - `removeTeamserverInfo` (function, line 29) `bool removeTeamserverInfo( const QString& ProfileName );`
  - `removeAllTeamservers` (function, line 30) `bool removeAllTeamservers();`
  - `listTeamservers` (function, line 31) `vector<Util::ConnectionInfo> listTeamservers();`
  - `AddScript` (function, line 32) `bool AddScript( QString Path );`
  - `RemoveScript` (function, line 34) `bool RemoveScript( QString Path );`
  - `CheckScript` (function, line 35) `bool CheckScript( QString Path );`
  - `GetScripts` (function, line 36) `vector<QString> GetScripts();`
  - `HAVOC_DBMANAGER_HPP` (macro, line 2) `#define HAVOC_DBMANAGER_HPP`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/DBManger/DBManager.cc`, `client/src/Havoc/DBManger/Scripts.cc`, `client/src/Havoc/DBManger/Teamserver.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

## client/include/UserInterface/HavocUI.hpp
- Layer: presentation
- Doc: ifndef HAVOC_HAVOCUI_HPP define HAVOC_HAVOCUI_HPP  include <global.hpp>  include <UserInterface/Dialogs/About.hpp> inclu
- Language: hpp
- Symbols:
  - `MarkSessionAs` (function, line 66) `public: void MarkSessionAs( HavocNamespace::Util::SessionItem session, QString Mark );`
  - `UpdateSessionsHealth` (function, line 69) `void UpdateSessionsHealth();`
  - `setupUi` (function, line 70) `void setupUi( QMainWindow *Havoc );`
  - `retranslateUi` (function, line 71) `void retranslateUi( QMainWindow *Havoc ) const;`
  - `setDBManager` (function, line 72) `void setDBManager( HavocSpace::DBManager* dbManager );`
  - `NewTeamserverTab` (function, line 73) `void NewTeamserverTab( HavocNamespace::Util::ConnectionInfo* );`
  - `NewBottomTab` (function, line 75) `void NewBottomTab( QWidget* TabWidget, const std::string& TitleName, const QString IconPath = "" ) const;`
  - `NewSmallTab` (function, line 76) `void NewSmallTab( QWidget* TabWidget, const std::string& TitleName ) const;`
  - `ConnectEvents` (function, line 77) `void ConnectEvents();`
  - `PythonPrepare` (function, line 78) `void PythonPrepare();`
  - `OneSecondTick` (function, line 79) `public slots: void OneSecondTick();`
  - `HAVOC_HAVOCUI_HPP` (macro, line 2) `#define HAVOC_HAVOCUI_HPP`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`

## client/include/UserInterface/SmallWidgets/EventViewer.hpp
- Layer: presentation
- Doc: ifndef HAVOC_EVENTVIEWER_HPP define HAVOC_EVENTVIEWER_HPP  include <global.hpp>
- Language: hpp
- Symbols:
  - `setupUi` (function, line 11) `void setupUi(QWidget* Widget);`
  - `AppendText` (function, line 13) `void AppendText(const QString& Time, const QString &text) const;`
  - `HAVOC_EVENTVIEWER_HPP` (macro, line 2) `#define HAVOC_EVENTVIEWER_HPP`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/src/UserInterface/HavocUi.cc
- Layer: presentation
- Doc: include <global.hpp>  Headers for UserInterface include <Havoc/Havoc.hpp> include <Havoc/PythonApi/PythonApi.h>  include
- Language: cc
- Symbols:
  - `setupUi` (function, line 27) `void HavocNamespace::UserInterface::HavocUi::setupUi(QMainWindow *Havoc)`
  - `OneSecondTick` (function, line 199) `void HavocNamespace::UserInterface::HavocUi::OneSecondTick()`
  - `MarkSessionAs` (function, line 204) `void HavocNamespace::UserInterface::HavocUi::MarkSessionAs(HavocNamespace::Util::SessionItem Sess...`
  - `UpdateSessionsHealth` (function, line 261) `void HavocNamespace::UserInterface::HavocUi::UpdateSessionsHealth()`
  - `retranslateUi` (function, line 360) `void HavocNamespace::UserInterface::HavocUi::retranslateUi(QMainWindow* Havoc ) const`
  - `ConnectEvents` (function, line 394) `void HavocNamespace::UserInterface::HavocUi::ConnectEvents()`
  - `connect` (function, line 398) `QMainWindow::connect( OneSecondTimer, &QTimer::timeout, this, [&]()`
  - `connect` (function, line 403) `QMainWindow::connect( actionNew_Client, &QAction::triggered, this, []()`
  - `connect` (function, line 407) `QMainWindow::connect( actionChat, &QAction::triggered, this, [&]()`
  - `connect` (function, line 421) `QMainWindow::connect( actionDisconnect, &QAction::triggered, this, []()`
  - `connect` (function, line 430) `QMainWindow::connect( actionExit, &QAction::triggered, this, []()`
  - `connect` (function, line 434) `QMainWindow::connect( actionSessionsTable, &QAction::triggered, this, []()`
  - `connect` (function, line 438) `QMainWindow::connect( actionListeners, &QAction::triggered, this, [&]()`
  - `connect` (function, line 454) `QMainWindow::connect( actionTeamserver, &QAction::triggered, this, [&]()`
  - `connect` (function, line 466) `QMainWindow::connect( actionStore, &QAction::triggered, this, [&]()`
  - `connect` (function, line 478) `QMainWindow::connect( actionSessionsGraph, &QAction::triggered, this, [&]()`
  - `connect` (function, line 482) `QMainWindow::connect( actionLogs, &QAction::triggered, this, [&]()`
  - `connect` (function, line 497) `QMainWindow::connect( actionLoot, &QAction::triggered, this, [&]()`
  - `connect` (function, line 505) `QMainWindow::connect( actionGeneratePayload, &QAction::triggered, this, []()`
  - `connect` (function, line 515) `QMainWindow::connect( actionPythonConsole, &QAction::triggered, this, [&]()`
  - `connect` (function, line 529) `QMainWindow::connect( actionLoad_Script, &QAction::triggered, this, [&]()`
  - `connect` (function, line 548) `QMainWindow::connect( actionAbout, &QAction::triggered, this, [&]()`
  - `connect` (function, line 557) `QMainWindow::connect( actionGithub_Repository, &QAction::triggered, this, []()`
  - `connect` (function, line 561) `QMainWindow::connect( actionOpen_Help_Documentation, &QAction::triggered, this, []()`
  - `NewBottomTab` (function, line 566) `void HavocNamespace::UserInterface::HavocUi::NewBottomTab(QWidget* TabWidget, const std::string& ...`
  - `setDBManager` (function, line 571) `void HavocNamespace::UserInterface::HavocUi::setDBManager(HavocSpace::DBManager* dbManager)`
  - `NewTeamserverTab` (function, line 576) `void UserInterface::HavocUi::NewTeamserverTab(HavocNamespace::Util::ConnectionInfo* Connection )`
  - `NewTeamserverTab` (function, line 586) `void UserInterface::HavocUi::NewTeamserverTab(QString Name )`
  - `NewSmallTab` (function, line 595) `void UserInterface::HavocUi::NewSmallTab(QWidget *TabWidget, const string &TitleName ) const`
  - `PythonPrepare` (function, line 601) `void UserInterface::HavocUi::PythonPrepare()`
  - `connectSlotsByName` (function, line 196) `QMetaObject::connectSlotsByName( HavocWindow );`
  - `WinVersionIcon` (function, line 222) `WinVersionIcon( Session.OS, true ) : WinVersionIcon( Session.OS, false );`
  - `MessageBox` (function, line 425) `MessageBox( "Disconnected", "Disconnected from " + HavocX::Teamserver.Name, QMessageBox::Information );`
  - `Exit` (function, line 432) `Havoc::Exit();`
  - `openUrl` (function, line 559) `QDesktopServices::openUrl( QUrl( "https://github.com/HavocFramework/Havoc" ) );`
  - `PyImport_AppendInittab` (function, line 604) `PyImport_AppendInittab( "emb", emb::PyInit_emb );`
  - `Py_Initialize` (function, line 607) `Py_Initialize();`
  - `PyImport_ImportModule` (function, line 609) `PyImport_ImportModule( "emb" );`
  - `AddScript` (function, line 613) `Widgets::ScriptManager::AddScript( ScriptPath );`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/SmallWidgets/EventViewer.cc
- Layer: presentation
- Doc: include <UserInterface/SmallWidgets/EventViewer.hpp> include <Util/ColorText.h>
- Language: cc
- Symbols:
  - `setupUi` (function, line 3) `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::setupUi(QWidget *Widget)`
  - `AppendText` (function, line 22) `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::AppendText(const QString& Time, co...`
  - `connectSlotsByName` (function, line 19) `QMetaObject::connectSlotsByName(Widget);`
- Depends on: `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/Util/ColorText.h`

## payloads/Demon/include/Demon.h
- Layer: utility
- Doc: ifndef DEMON_DEMON_H define DEMON_DEMON_H  include <windows.h> include <winsock2.h> include <ntstatus.h> include <aclapi
- Language: h
- Symbols:
  - `_CONFIG` (struct, line 121)
  - `Session` (struct, line 48)
  - `WIN_FUNC` (function, line 165) `WIN_FUNC( LdrLoadDll ) WIN_FUNC( LdrGetProcedureAddress ) WIN_FUNC( RtlAllocateHeap ) WIN_FUNC( RtlReAllocateHeap ) WIN_FUNC( RtlFreeHeap ) WIN_FUNC( RtlRandomEx ) WIN_FUNC( RtlNtStatusToDosError ) WI`
  - `INT` (function, line 348) `INT ( *swprintf_s ) ( PWCHAR, SIZE_T, CONST PWCHAR, ... );`
  - `DemonMain` (function, line 560) `VOID DemonMain( PVOID ModuleInst, PKAYN_ARGS KArgs );`
  - `DemonRoutine` (function, line 562) `VOID DemonRoutine( );`
  - `DemonInit` (function, line 563) `VOID DemonInit( PVOID ModuleInst, PKAYN_ARGS KArgs );`
  - `DemonMetaData` (function, line 564) `VOID DemonMetaData( PPACKAGE* Package, BOOL Header );`
  - `DemonConfig` (function, line 565) `VOID DemonConfig();`
  - `Instance` (variable, line 558) `extern PINSTANCE Instance;`
  - `DEMON_DEMON_H` (macro, line 2) `#define DEMON_DEMON_H`
- Depends on: `payloads/Demon/include/common/Clr.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Pivot.h`, `payloads/Demon/include/core/Socket.h`, `payloads/Demon/include/core/Spoof.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`
- Imported by: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/src/Demon.c`, `payloads/Demon/src/core/CoffeeLdr.c`, `payloads/Demon/src/core/Command.c`, `payloads/Demon/src/core/Dotnet.c`, `payloads/Demon/src/core/Download.c`, `payloads/Demon/src/core/HwBpEngine.c`, `payloads/Demon/src/core/HwBpExceptions.c`, `payloads/Demon/src/core/Jobs.c`, `payloads/Demon/src/core/Kerberos.c`, `payloads/Demon/src/core/Memory.c`, `payloads/Demon/src/core/MiniStd.c`, `payloads/Demon/src/core/Obf.c`, `payloads/Demon/src/core/ObjectApi.c`, `payloads/Demon/src/core/Parser.c`, `payloads/Demon/src/core/Pivot.c`, `payloads/Demon/src/core/Runtime.c`, `payloads/Demon/src/core/Socket.c`, `payloads/Demon/src/core/SysNative.c`, `payloads/Demon/src/core/Syscalls.c`, `payloads/Demon/src/core/Thread.c`, `payloads/Demon/src/core/Token.c`, `payloads/Demon/src/core/Transport.c`, `payloads/Demon/src/core/TransportHttp.c`, `payloads/Demon/src/core/TransportSmb.c`, `payloads/Demon/src/core/Win32.c`, `payloads/Demon/src/inject/Inject.c`, `payloads/Demon/src/inject/InjectUtil.c`, `payloads/Demon/src/main/MainDll.c`, `payloads/Demon/src/main/MainExe.c`, `payloads/Demon/src/main/MainSvc.c`

## payloads/Demon/include/crypt/AesCrypt.h
- Layer: utility
- Doc: ifndef _AES_H_ define _AES_H_  include <windows.h>  define CTR 1 define AES256 1  ifndef CTR define CTR 1 endif  define 
- Language: h
- Symbols:
  - `AesInit` (function, line 21) `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv);`
  - `AesXCryptBuffer` (function, line 23) `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length);`
  - `_AES_H_` (macro, line 2) `#define _AES_H_`
  - `CTR` (macro, line 5) `#define CTR`
  - `AES256` (macro, line 7) `#define AES256`
  - `CTR` (macro, line 10) `#define CTR`
  - `AES_BLOCKLEN` (macro, line 12) `#define AES_BLOCKLEN`
  - `AES_KEYLEN` (macro, line 14) `#define AES_KEYLEN`
  - `AES_keyExpSize` (macro, line 15) `#define AES_keyExpSize`
- Imported by: `payloads/Demon/src/core/Package.c`, `payloads/Demon/src/core/Parser.c`, `payloads/Demon/src/core/Transport.c`, `payloads/Demon/src/crypt/AesCrypt.c`

## payloads/Demon/scripts/hash_func.py
- Layer: utility
- Doc: -*- coding:utf-8 -*- credit: https://github.com/tigr0w/realoriginal_titanldr-ng/blob/5b8835143f36adfb8d077823e18f21d3043
- Language: py
- Symbols:
  - `hash_string` (function, line 7) `def hash_string(string)`
  - `hash_coffapi` (function, line 18) `def hash_coffapi(string)`

## payloads/Demon/src/Demon.c
- Layer: utility
- Doc: include <Demon.h>  Import Common Headers
- Language: c
- Symbols:
  - `DemonMain` (function, line 34) `VOID DemonMain( PVOID ModuleInst, PKAYN_ARGS KArgs )`
  - `DemonRoutine` (function, line 63) `_Noreturn
VOID DemonRoutine()`
  - `DemonMetaData` (function, line 95) `VOID DemonMetaData( PPACKAGE* MetaData, BOOL Header )`
  - `DemonInit` (function, line 266) `VOID DemonInit( PVOID ModuleInst, PKAYN_ARGS KArgs )`
  - `PUTS` (function, line 290) `PUTS( "TRANSPORT_HTTP" )
#endif

#ifdef TRANSPORT_SMB
    PUTS( "TRANSPORT_SMB" )
#endif


    /*...`
  - `PRINTF` (function, line 569) `PRINTF( "Instance DemonID => %x\n", Instance->Session.AgentID )
}

VOID DemonConfig()`
  - `PRINTF` (function, line 645) `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...`
  - `PRINTF` (function, line 672) `PRINTF( " - %ls:%ld\n", Buffer, Temp )

        /* if our host address is longer than 0 then lets...`
  - `PRINTF` (function, line 775) `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...`
  - `CommandDispatcher` (function, line 86) `CommandDispatcher();`
  - `SleepObf` (function, line 90) `SleepObf();`
  - `Header` (function, line 126) `Header (if specified): [ SIZE ] 4 bytes [ Magic Value ] 4 bytes [ Agent ID ] 4 bytes [ COMMAND ID ] 4 bytes [ Request ID ] 4 bytes MetaData: [ AES KEY ] 32 bytes [ AES IV ] 16 bytes [ Magic Value ] 4 `
  - `PackageAddPad` (function, line 161) `PackageAddPad( *MetaData, ( PCHAR ) Instance->Config.AES.IV, 16 );`
  - `PackageAddInt32` (function, line 164) `PackageAddInt32( *MetaData, Instance->Session.AgentID );`
  - `MemSet` (function, line 172) `MemSet( Data, 0, dwLength );`
  - `DATA_FREE` (function, line 177) `DATA_FREE( Data, dwLength );`
  - `PackageAddWString` (function, line 242) `PackageAddWString( *MetaData, ( ( PRTL_USER_PROCESS_PARAMETERS ) Instance->Teb->ProcessEnvironmentBlock->ProcessParameters )->ImagePathName.Buffer );`
  - `PackageAddInt64` (function, line 249) `PackageAddInt64( *MetaData, U_PTR( Instance->Session.ModuleBase ) );`
  - `DemonConfig` (function, line 463) `DemonConfig();`
  - `ShuffleArray` (function, line 476) `ShuffleArray( RtModules, SIZEOF_ARRAY( RtModules ) );`
  - `FreeReflectiveLoader` (function, line 495) `FreeReflectiveLoader( KArgs->KaynLdr );`
  - `CfgAddressAdd` (function, line 553) `CfgAddressAdd( Instance->Modules.Ntdll, Instance->Win32.NtContinue );`
  - `RtlSecureZeroMemory` (function, line 584) `RtlSecureZeroMemory( AgentConfig, sizeof( AgentConfig ) );`
  - `MemCopy` (function, line 603) `MemCopy( Instance->Config.Process.Spawn64, Buffer, Length );`
  - `HostAdd` (function, line 678) `HostAdd( Buffer, Length, Temp );`
  - `ParserDestroy` (function, line 788) `ParserDestroy( &Parser );`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Runtime.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`

## payloads/Demon/src/crypt/AesCrypt.c
- Layer: utility
- Doc: include <crypt/AesCrypt.h> include <core/MiniStd.h>  define Nb 4  if defined(AES256) && (AES256 == 1) define Nk 8 define
- Language: c
- Symbols:
  - `KeyExpansion` (function, line 46) `void KeyExpansion(UINT8* RoundKey, const UINT8* Key)`
  - `AesInit` (function, line 102) `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv)`
  - `AddRoundKey` (function, line 111) `static void AddRoundKey(UINT8 round, state_t* state, const UINT8* RoundKey)`
  - `SubBytes` (function, line 125) `static void SubBytes(state_t* state)`
  - `ShiftRows` (function, line 140) `static void ShiftRows(state_t* state)`
  - `xtime` (function, line 167) `static UINT8 xtime(UINT8 x)`
  - `MixColumns` (function, line 174) `static void MixColumns(state_t* state)`
  - `AesXCryptBuffer` (function, line 216) `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length)`
  - `MemCopy` (function, line 106) `MemCopy( ctx->Iv, iv, AES_BLOCKLEN );`
  - `Cipher` (function, line 228) `Cipher((state_t*)buffer,ctx->RoundKey);`
  - `Nb` (macro, line 3) `#define Nb`
  - `Nk` (macro, line 7) `#define Nk`
  - `Nr` (macro, line 8) `#define Nr`
  - `Nk` (macro, line 10) `#define Nk`
  - `Nr` (macro, line 11) `#define Nr`
  - `Nk` (macro, line 13) `#define Nk`
  - `Nr` (macro, line 14) `#define Nr`
  - `MULTIPLY_AS_A_FUNCTION` (macro, line 18) `#define MULTIPLY_AS_A_FUNCTION`
  - `getSBoxValue` (macro, line 44) `#define getSBoxValue(num)`
- Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/crypt/AesCrypt.h`

## payloads/DllLdr/Scripts/extract.py
- Layer: utility
- Doc: -*- coding:utf-8 -*-
- Language: py
- Symbols:
  - `main` (function, line 8) `def main(options)`

## payloads/DllLdr/Source/Entry.c
- Layer: utility
- Doc: include <Core.h> include <Native.h> include <ntdef.h>
- Language: c
- Symbols:
  - `KaynLoader` (function, line 4) `DLLEXPORT VOID KaynLoader( LPVOID lpParameter )`
  - `KaynCaller` (function, line 143) `NAKED LPVOID KaynCaller( PVOID StartAddress )`
  - `Memcpy` (function, line 165) `NAKED VOID Memcpy( PVOID Destination, PVOID source, SIZE_T Size )`
  - `KGetModuleByHash` (function, line 184) `PVOID KGetModuleByHash( DWORD ModuleHash )`
  - `CopyDotStr` (function, line 205) `FORCE_INLINE UINT32 CopyDotStr( PCHAR String )`
  - `KGetProcAddressByHash` (function, line 214) `PVOID KGetProcAddressByHash( PINSTANCE Instance, PVOID DllModuleBase, DWORD FunctionHash, DWORD O...`
  - `KResolveIAT` (function, line 264) `VOID KResolveIAT( PINSTANCE Instance, LPVOID KaynImage, LPVOID IatDir )`
  - `KReAllocSections` (function, line 305) `VOID KReAllocSections( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir )`
  - `KLoadLibrary` (function, line 330) `PVOID KLoadLibrary( PINSTANCE Instance, LPSTR ModuleName )`
  - `KHashString` (function, line 363) `DWORD KHashString( PVOID String, SIZE_T Length )`
  - `KStringLengthA` (function, line 392) `SIZE_T KStringLengthA( LPCSTR String )`
  - `KStringLengthW` (function, line 399) `SIZE_T KStringLengthW(LPCWSTR String)`
  - `KCharStringToWCharString` (function, line 408) `SIZE_T KCharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )`
  - `BOOL` (function, line 139) `BOOL ( WINAPI *KaynDllMain ) ( PVOID, DWORD, PVOID ) = RVA2VA( PVOID, KVirtualMemory, NtHeaders->OptionalHeader.AddressOfEntryPoint );`
  - `KaynDllMain` (function, line 140) `KaynDllMain( KVirtualMemory, DLL_PROCESS_ATTACH, lpParameter );`
  - `asm` (function, line 146) `asm( "start: \n" "xor rbx, rbx \n" "mov ebx, 0x5A4D \n" "loop: \n" "inc rcx \n" "cmp bx, [ rcx ] \n" "jne loop \n" "xor rax, rax \n" "mov ax, [ rcx + 0x3C ] \n" "add rax, rcx \n" "xor rbx, rbx \n" "ad`

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
