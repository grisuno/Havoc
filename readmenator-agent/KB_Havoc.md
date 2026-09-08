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
  - `critical` (function, line 32) `spdlog::critical( "Got Invalid json" );`
  - `MessageBox` (function, line 46) `MessageBox( "Teamserver error", Socket->errorString(), QMessageBox::Critical );`
  - `Exit` (function, line 49) `Havoc::Exit();`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

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
  - `set_pattern` (function, line 10) `spdlog::set_pattern( "[%T] [%^%l%$] %v" );`
  - `set_level` (function, line 35) `spdlog::set_level( spdlog::level::debug );`
  - `debug` (function, line 36) `spdlog::debug( "Debug mode enabled" );`
  - `error` (function, line 55) `spdlog::error( "couldn't find config file" );`
  - `setCodecForLocale` (function, line 67) `QTextCodec::setCodecForLocale( QTextCodec::codecForName( "UTF-8" ) );`
  - `setFont` (function, line 69) `QApplication::setFont( QFont( family.c_str(), size ) );`
  - `critical` (function, line 95) `spdlog::critical( "Exit Program" );`
  - `exit` (function, line 97) `exit( 0 );`
- Depends on: `client/include/Havoc/CmdLine.hpp`, `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

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
  - `DispatchService` (function, line 864) `bool Packager::DispatchService( Util::Packager::PPackage Package )`
  - `DispatchTeamserver` (function, line 960) `bool Packager::DispatchTeamserver( Util::Packager::PPackage Package )`
  - `setTeamserver` (function, line 985) `void Packager::setTeamserver( QString Name )`
  - `critical` (function, line 71) `spdlog::critical( "Invalid json" );`
  - `QJsonDocument` (function, line 130) `return QJsonDocument( JsonPackage );`
  - `info` (function, line 159) `default: spdlog::info( "[PACKAGE] Event Id not found" );`
  - `AddScript` (function, line 183) `ScriptManager::AddScript( file.c_str() );`
  - `MessageBox` (function, line 197) `MessageBox( "Teamserver Error", QString( "Couldn't connect to Teamserver:" + QString( Package->Body.Info[ "Message" ].c_str() ) ), QMessageBox::Critical );`
  - `PyObject_CallFunctionObjArgs` (function, line 559) `PyObject_CallFunctionObjArgs(HavocX::callbackGate, pyByteArray, nullptr);`
  - `error` (function, line 655) `spdlog::error( "Error calling callback" );`
  - `PyErr_PrintEx` (function, line 656) `PyErr_PrintEx(0);`
  - `PyErr_Clear` (function, line 657) `PyErr_Clear();`
  - `Comment` (function, line 684) `Util::ColorText::Comment( QString( Package->Head.Time.c_str() ) + " [" + QString( Package->Head.User.c_str() ) + "]" ) + " " + Util::ColorText::UnderlinePink( AgentType ) + Util::ColorText::Cyan(" » "`
  - `QString` (function, line 726) `QString( Package->Head.Time.c_str() ) );`
  - `PyObject_CallObject` (function, line 752) `PyObject_CallObject( Callback, arglist );`
  - `Py_XDECREF` (function, line 753) `Py_XDECREF( Callback );`
  - `WinVersionIcon` (function, line 829) `WinVersionIcon( session.OS, true ) : WinVersionIcon( session.OS, false );`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/Havoc/Service.cc
- Layer: business_logic
- Doc: include <Havoc/Service.hpp>
- Language: cc
- Depends on: `client/include/Havoc/Service.hpp`
