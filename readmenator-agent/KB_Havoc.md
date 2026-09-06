# Subsystem: Havoc

## client/src/Havoc/Connector.cc
- Layer: infrastructure
- Doc: include <Havoc/Connector.hpp> include <Havoc/Havoc.hpp> include <QCryptographicHash> include <QMap> include <QBuffer>
- Language: cc
- Symbols:
  - `Connector` (function, line 6) `Connector::Connector( Util::ConnectionInfo* ConnectionInfo )`
  - `connect` (function, line 18) `QObject::connect( Socket, &QWebSocket::binaryMessageReceived, this, [&]( const QByteArray& Message )`
  - `connect` (function, line 35) `QObject::connect( Socket, &QWebSocket::connected, this, [&]()`
  - `connect` (function, line 43) `QObject::connect( Socket, &QWebSocket::disconnected, this, [&]()`
  - `Disconnect` (function, line 55) `bool Connector::Disconnect()`
  - `SendLogin` (function, line 71) `void Connector::SendLogin()`
  - `SendPackage` (function, line 92) `void Connector::SendPackage( Util::Packager::PPackage Package )`

## client/src/Havoc/Havoc.cc
- Layer: infrastructure
- Doc: include <Havoc/Havoc.hpp> include <Havoc/Connector.hpp> include <Havoc/CmdLine.hpp>  include <QTimer>
- Language: cc
- Symbols:
  - `Havoc` (function, line 6) `HavocSpace::Havoc::Havoc( QMainWindow* w )`
  - `Init` (function, line 21) `void HavocSpace::Havoc::Init( int argc, char** argv )`
  - `singleShot` (function, line 70) `QTimer::singleShot( 10, [&]()`
  - `Start` (function, line 84) `void HavocSpace::Havoc::Start()`
  - `Exit` (function, line 92) `void HavocSpace::Havoc::Exit()`

## client/src/Havoc/Packager.cc
- Layer: infrastructure
- Doc: include <global.hpp>  include <Havoc/Havoc.hpp> include <Havoc/Packager.hpp> include <Havoc/DemonCmdDispatch.h> include 
- Language: cc
- Symbols:
  - `DecodePackage` (function, line 62) `Util::Packager::PPackage Packager::DecodePackage( const QString& Package )`
  - `foreach` (function, line 90) `foreach( const QString& key, BodyObject[ "Info" ].toObject().keys() )`
  - `EncodePackage` (function, line 105) `QJsonDocument Packager::EncodePackage( Util::Packager::Package Package )`
  - `DispatchInitConnection` (function, line 165) `bool Packager::DispatchInitConnection( Util::Packager::PPackage Package )`
  - `DispatchListener` (function, line 219) `bool Packager::DispatchListener( Util::Packager::PPackage Package )`
  - `DispatchChat` (function, line 482) `bool Packager::DispatchChat( Util::Packager::PPackage Package)`
  - `DispatchGate` (function, line 531) `bool Packager::DispatchGate( Util::Packager::PPackage Package )`
  - `DispatchSession` (function, line 580) `bool Packager::DispatchSession( Util::Packager::PPackage Package )`
  - `case` (function, line 720) `case ( int ) Commands::CONSOLE_MESSAGE:

                            if ( QByteArray::fromBase64(...`
  - `case` (function, line 734) `case ( int ) Commands::BOF_CALLBACK:

                            if ( QByteArray::fromBase64( Ou...`
  - `DispatchService` (function, line 864) `bool Packager::DispatchService( Util::Packager::PPackage Package )`
  - `DispatchTeamserver` (function, line 960) `bool Packager::DispatchTeamserver( Util::Packager::PPackage Package )`
  - `setTeamserver` (function, line 985) `void Packager::setTeamserver( QString Name )`

## client/src/Havoc/Service.cc
- Layer: business_logic
- Doc: include <Havoc/Service.hpp>
- Language: cc
