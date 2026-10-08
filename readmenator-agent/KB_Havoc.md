# Subsystem: Havoc

## client/src/Havoc/Connector.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `Connector` (function, line 7) `Connector::Connector( Util::ConnectionInfo* ConnectionInfo )`
  - `connect` (function, line 19) `QObject::connect( Socket, &QWebSocket::binaryMessageReceived, this, [&]( const QByteArray& Message )`
  - `connect` (function, line 36) `QObject::connect( Socket, &QWebSocket::connected, this, [&]()`
  - `connect` (function, line 44) `QObject::connect( Socket, &QWebSocket::disconnected, this, [&]()`
  - `Disconnect` (function, line 56) `bool Connector::Disconnect()`
  - `SendLogin` (function, line 72) `void Connector::SendLogin()`
  - `SendPackage` (function, line 93) `void Connector::SendPackage( Util::Packager::PPackage Package )`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

## client/src/Havoc/Havoc.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `Havoc` (function, line 7) `HavocSpace::Havoc::Havoc( QMainWindow* w )`
  - `Init` (function, line 22) `void HavocSpace::Havoc::Init( int argc, char** argv )`
  - `singleShot` (function, line 70) `QTimer::singleShot( 10, [&]()`
  - `Start` (function, line 85) `void HavocSpace::Havoc::Start()`
  - `Exit` (function, line 93) `void HavocSpace::Havoc::Exit()`
- Depends on: `client/include/Havoc/CmdLine.hpp`, `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

## client/src/Havoc/Packager.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `DecodePackage` (function, line 63) `Util::Packager::PPackage Packager::DecodePackage( const QString& Package )`
  - `foreach` (function, line 90) `foreach( const QString& key, BodyObject[ "Info" ].toObject().keys() )`
  - `EncodePackage` (function, line 106) `QJsonDocument Packager::EncodePackage( Util::Packager::Package Package )`
  - `DispatchInitConnection` (function, line 166) `bool Packager::DispatchInitConnection( Util::Packager::PPackage Package )`
  - `DispatchListener` (function, line 220) `bool Packager::DispatchListener( Util::Packager::PPackage Package )`
  - `DispatchChat` (function, line 483) `bool Packager::DispatchChat( Util::Packager::PPackage Package)`
  - `DispatchGate` (function, line 532) `bool Packager::DispatchGate( Util::Packager::PPackage Package )`
  - `DispatchSession` (function, line 581) `bool Packager::DispatchSession( Util::Packager::PPackage Package )`
  - `DispatchService` (function, line 865) `bool Packager::DispatchService( Util::Packager::PPackage Package )`
  - `DispatchTeamserver` (function, line 961) `bool Packager::DispatchTeamserver( Util::Packager::PPackage Package )`
  - `setTeamserver` (function, line 987) `void Packager::setTeamserver( QString Name )`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/Havoc/Service.cc
- Layer: business_logic
- Language: cc
- Depends on: `client/include/Havoc/Service.hpp`
