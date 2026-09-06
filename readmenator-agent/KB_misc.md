# Subsystem: misc

## client/include/Havoc/DBManager/DBManager.hpp
- Layer: infrastructure
- Doc: ifndef HAVOC_DBMANAGER_HPP define HAVOC_DBMANAGER_HPP  include <global.hpp>  include <QSqlDatabase> include <QSqlQuery> 
- Language: hpp
- Symbols:
  - `HAVOC_DBMANAGER_HPP` (macro, line 2)

## client/include/UserInterface/HavocUI.hpp
- Layer: presentation
- Doc: ifndef HAVOC_HAVOCUI_HPP define HAVOC_HAVOCUI_HPP  include <global.hpp>  include <UserInterface/Dialogs/About.hpp> inclu
- Language: hpp
- Symbols:
  - `HAVOC_HAVOCUI_HPP` (macro, line 2)

## client/include/UserInterface/SmallWidgets/EventViewer.hpp
- Layer: presentation
- Doc: ifndef HAVOC_EVENTVIEWER_HPP define HAVOC_EVENTVIEWER_HPP  include <global.hpp>
- Language: hpp
- Symbols:
  - `HAVOC_EVENTVIEWER_HPP` (macro, line 2)

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

## client/src/UserInterface/SmallWidgets/EventViewer.cc
- Layer: presentation
- Doc: include <UserInterface/SmallWidgets/EventViewer.hpp> include <Util/ColorText.h>
- Language: cc
- Symbols:
  - `setupUi` (function, line 3) `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::setupUi(QWidget *Widget)`
  - `AppendText` (function, line 22) `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::AppendText(const QString& Time, co...`

## payloads/Demon/include/Demon.h
- Layer: utility
- Doc: ifndef DEMON_DEMON_H define DEMON_DEMON_H  include <windows.h> include <winsock2.h> include <ntstatus.h> include <aclapi
- Language: h
- Symbols:
  - `_CONFIG` (struct, line 121)
  - `DEMON_DEMON_H` (macro, line 2)

## payloads/Demon/include/crypt/AesCrypt.h
- Layer: utility
- Doc: ifndef _AES_H_ define _AES_H_  include <windows.h>  define CTR 1 define AES256 1  ifndef CTR define CTR 1 endif  define 
- Language: h
- Symbols:
  - `_AES_H_` (macro, line 2)
  - `CTR` (macro, line 5)
  - `AES256` (macro, line 7)
  - `CTR` (macro, line 10)
  - `AES_BLOCKLEN` (macro, line 12)
  - `AES_KEYLEN` (macro, line 14)
  - `AES_keyExpSize` (macro, line 15)

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
  - `Nb` (macro, line 3)
  - `Nk` (macro, line 7)
  - `Nr` (macro, line 8)
  - `Nk` (macro, line 10)
  - `Nr` (macro, line 11)
  - `Nk` (macro, line 13)
  - `Nr` (macro, line 14)
  - `MULTIPLY_AS_A_FUNCTION` (macro, line 18)
  - `getSBoxValue` (macro, line 44)

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
