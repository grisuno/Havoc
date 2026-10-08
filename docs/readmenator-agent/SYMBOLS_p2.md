# Symbols (page 2 of 13)
Previous: [SYMBOLS.md](SYMBOLS.md)

| Symbol | Kind | File:Line | Signature |
|--------|------|-----------|-----------|
| `UnderlineBackground` | function | `client/include/Util/ColorText.h:49` | `static QString UnderlineBackground(const QString& text);` |
| `UnderlineComment` | function | `client/include/Util/ColorText.h:51` | `static QString UnderlineComment(const QString& text);` |
| `UnderlineCyan` | function | `client/include/Util/ColorText.h:52` | `static QString UnderlineCyan(const QString& text);` |
| `UnderlineForeground` | function | `client/include/Util/ColorText.h:50` | `static QString UnderlineForeground(const QString& text);` |
| `UnderlineGreen` | function | `client/include/Util/ColorText.h:53` | `static QString UnderlineGreen(const QString& text);` |
| `UnderlineOrange` | function | `client/include/Util/ColorText.h:54` | `static QString UnderlineOrange(const QString& text);` |
| `UnderlinePink` | function | `client/include/Util/ColorText.h:55` | `static QString UnderlinePink(const QString& text);` |
| `UnderlinePurple` | function | `client/include/Util/ColorText.h:56` | `static QString UnderlinePurple(const QString& text);` |
| `UnderlineRed` | function | `client/include/Util/ColorText.h:57` | `static QString UnderlineRed(const QString& text);` |
| `UnderlineYellow` | function | `client/include/Util/ColorText.h:58` | `static QString UnderlineYellow(const QString& text);` |
| `Yellow` | function | `client/include/Util/ColorText.h:46` | `static QString Yellow(const QString&);` |
| `Agent` | type_alias | `client/include/global.hpp:77` | `typedef struct RegisteredCommand { /* for what agent is it this command */ std::string Agent;` |
| `Agent` | type_alias | `client/include/global.hpp:92` | `typedef struct RegisteredModule { /* for what agent is it this command */ std::string Agent;` |
| `BYTE` | type_alias | `client/include/global.hpp:52` | `typedef char BYTE;` |
| `CodeName` | variable | `client/include/global.hpp:69` | `extern std::string CodeName;` |
| `ConnectionInfo` | struct | `client/include/global.hpp:248` | `` |
| `Connector` | variable | `client/include/global.hpp:283` | `extern HavocNamespace::Connector* Connector;` |
| `DebugMode` | variable | `client/include/global.hpp:277` | `extern bool DebugMode;` |
| `Export` | function | `client/include/global.hpp:245` | `void Export();` |
| `External` | struct | `client/include/global.hpp:177` | `` |
| `GateGUI` | variable | `client/include/global.hpp:278` | `extern bool GateGUI;` |
| `HAVOC_GLOBAL_HPP` | macro | `client/include/global.hpp:2` | `#define HAVOC_GLOBAL_HPP` |
| `HTTP` | struct | `client/include/global.hpp:152` | `` |
| `HavocApplication` | variable | `client/include/global.hpp:190` | `extern HavocNamespace::HavocSpace::Havoc* HavocApplication;` |
| `HavocUserInterface` | variable | `client/include/global.hpp:282` | `extern HavocNamespace::UserInterface::HavocUi* HavocUserInterface;` |
| `LPVOID` | type_alias | `client/include/global.hpp:54` | `typedef void* LPVOID;` |
| `Listener` | struct | `client/include/global.hpp:145` | `` |
| `ListenerItem` | struct | `client/include/global.hpp:106` | `` |
| `MapStrAny` | type_alias | `client/include/global.hpp:59` | `typedef std::map<std::string, std::any> MapStrAny;` |
| `MapStrStr` | type_alias | `client/include/global.hpp:58` | `typedef std::map<std::string, std::string> MapStrStr;` |
| `Name` | type_alias | `client/include/global.hpp:105` | `typedef struct ListenerItem { std::string Name;` |
| `PCHAR` | type_alias | `client/include/global.hpp:51` | `typedef char* PCHAR;` |
| `PVOID` | type_alias | `client/include/global.hpp:53` | `typedef void* PVOID;` |
| `RegisteredCommand` | struct | `client/include/global.hpp:78` | `` |
| `RegisteredModule` | struct | `client/include/global.hpp:93` | `` |
| `SMB` | struct | `client/include/global.hpp:172` | `` |
| `Service` | type_alias | `client/include/global.hpp:181` | `typedef MapStrStr Service;` |
| `SessionItem` | struct | `client/include/global.hpp:209` | `` |
| `Teamserver` | variable | `client/include/global.hpp:281` | `extern HavocNamespace::Util::ConnectionInfo Teamserver;` |
| `UINT_PTR` | type_alias | `client/include/global.hpp:55` | `typedef unsigned long int UINT_PTR;` |
| `Version` | variable | `client/include/global.hpp:68` | `extern std::string Version;` |
| `callbackGate` | variable | `client/include/global.hpp:279` | `extern PyObject* callbackGate;` |
| `callbackMessage` | variable | `client/include/global.hpp:280` | `extern PyObject* callbackMessage;` |
| `u32` | type_alias | `client/include/global.hpp:46` | `typedef uint32_t u32;` |
| `u64` | type_alias | `client/include/global.hpp:48` | `typedef uint64_t u64;` |
| `Connector` | function | `client/src/Havoc/Connector.cc:7` | `Connector::Connector( Util::ConnectionInfo* ConnectionInfo )` |
| `Disconnect` | function | `client/src/Havoc/Connector.cc:56` | `bool Connector::Disconnect()` |
| `SendLogin` | function | `client/src/Havoc/Connector.cc:72` | `void Connector::SendLogin()` |
| `SendPackage` | function | `client/src/Havoc/Connector.cc:93` | `void Connector::SendPackage( Util::Packager::PPackage Package )` |
| `connect` | function | `client/src/Havoc/Connector.cc:19` | `QObject::connect( Socket, &QWebSocket::binaryMessageReceived, this, [&]( const QByteArray& Message )` |
| `connect` | function | `client/src/Havoc/Connector.cc:36` | `QObject::connect( Socket, &QWebSocket::connected, this, [&]()` |
| `connect` | function | `client/src/Havoc/Connector.cc:44` | `QObject::connect( Socket, &QWebSocket::disconnected, this, [&]()` |
| `DBManager` | function | `client/src/Havoc/DBManger/DBManager.cc:9` | `DBManager::DBManager( const QString& FilePath, int OpenFlag )` |
| `createNewDatabase` | function | `client/src/Havoc/DBManger/DBManager.cc:32` | `bool DBManager::createNewDatabase()` |
| `AddScript` | function | `client/src/Havoc/DBManger/Scripts.cc:3` | `bool HavocNamespace::HavocSpace::DBManager::AddScript( QString Path )` |
| `CheckScript` | function | `client/src/Havoc/DBManger/Scripts.cc:41` | `bool HavocNamespace::HavocSpace::DBManager::CheckScript( QString Path )` |
| `GetScripts` | function | `client/src/Havoc/DBManger/Scripts.cc:63` | `vector<QString> HavocNamespace::HavocSpace::DBManager::GetScripts()` |
| `RemoveScript` | function | `client/src/Havoc/DBManger/Scripts.cc:20` | `bool HavocNamespace::HavocSpace::DBManager::RemoveScript( QString Path )` |
| `addTeamserverInfo` | function | `client/src/Havoc/DBManger/Teamserver.cc:6` | `bool HavocSpace::DBManager::addTeamserverInfo( const Util::ConnectionInfo& connection )` |
| `checkTeamserverExists` | function | `client/src/Havoc/DBManger/Teamserver.cc:31` | `bool HavocSpace::DBManager::checkTeamserverExists( const QString& ProfileName )` |
| `listTeamservers` | function | `client/src/Havoc/DBManger/Teamserver.cc:75` | `vector<Util::ConnectionInfo> HavocSpace::DBManager::listTeamservers()` |
| `removeAllTeamservers` | function | `client/src/Havoc/DBManger/Teamserver.cc:104` | `bool HavocSpace::DBManager::removeAllTeamservers()` |
| `removeTeamserverInfo` | function | `client/src/Havoc/DBManger/Teamserver.cc:55` | `bool HavocSpace::DBManager::removeTeamserverInfo( const QString& ProfileName )` |
| `MessageOutput` | function | `client/src/Havoc/Demon/CommandOutput.cc:15` | `void DispatchOutput::MessageOutput( QString JsonString, const QString& Date = "" ) const` |
| `BEHAVIOR_API_ONLY` | macro | `client/src/Havoc/Demon/Commands.cc:6` | `#define BEHAVIOR_API_ONLY` |
| `BEHAVIOR_FORK_AND_RUN` | macro | `client/src/Havoc/Demon/Commands.cc:5` | `#define BEHAVIOR_FORK_AND_RUN` |
| `BEHAVIOR_PROCESS_CREATION` | macro | `client/src/Havoc/Demon/Commands.cc:4` | `#define BEHAVIOR_PROCESS_CREATION` |
| `BEHAVIOR_PROCESS_INJECTION` | macro | `client/src/Havoc/Demon/Commands.cc:3` | `#define BEHAVIOR_PROCESS_INJECTION` |
| `BEHAVIOR_TEAMSERVER` | macro | `client/src/Havoc/Demon/Commands.cc:7` | `#define BEHAVIOR_TEAMSERVER` |
| `NO_SUBCOMMANDS` | macro | `client/src/Havoc/Demon/Commands.cc:9` | `#define NO_SUBCOMMANDS` |
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:667` | `CONSOLE_ERROR( "Not enough arguments" )                 }             }             else if ( Inp...` |
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:681` | `CONSOLE_ERROR( "Not enough arguments" )                 }             }             else if ( Inp...` |
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:700` | `CONSOLE_ERROR( "Sub command not found: " + InputCommands[ 1 ] )             }         }         e...` |
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1225` | `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )                     }         ...` |
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1260` | `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )                     }         ...` |
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1830` | `CONSOLE_ERROR( "Not enough arguments" )             }         }         else if ( InputCommands[ ...` |
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:2131` | `CONSOLE_ERROR( "No sub command specified" )             }         }         else if ( InputComman...` |
| `DemonCommands` | function | `client/src/Havoc/Demon/ConsoleInput.cc:188` | `DemonCommands::DemonCommands( )` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:611` | `SEND( Execute.Checkin( TaskID ) )         }         else if ( InputCommands[ 0 ].compare( "task" ...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:654` | `SEND( Execute.Job( TaskID, "list", "0" ) )             }             else if ( InputCommands[ 1 ]...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1138` | `SEND( Execute.DllInject( TaskID, Pid, Path, Args ) )             }             else if ( InputCom...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1166` | `SEND( Execute.DllSpawn( TaskID, Path, Args.toLocal8Bit() ) )              }         }         els...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1452` | `SEND( Execute.Token( TaskID, "clear", "" ) )             }             else if ( InputCommands[ 1...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1459` | `SEND( Execute.Token( TaskID, "getuid", "" ) )             }             else if ( InputCommands[ ...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1607` | `SEND( Execute.Socket( TaskID, "rportfwd list", "" ) )             }             else if ( InputCo...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1620` | `SEND( Execute.Socket( TaskID, "rportfwd remove", InputCommands[ 2 ] ) )             }            ...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1627` | `SEND( Execute.Socket( TaskID, "rportfwd clear", "" ) )             }          }         else if (...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1654` | `SEND( Execute.Socket( TaskID, "socks add", Port ) )             }             else if ( InputComm...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1661` | `SEND( Execute.Socket( TaskID, "socks list", "" ) )             }             else if ( InputComma...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1674` | `SEND( Execute.Socket( TaskID, "socks kill", InputCommands[ 2 ] ) )             }             else...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1681` | `SEND( Execute.Socket( TaskID, "socks clear", "" ) )             }          }         else if ( In...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1698` | `SEND( Execute.Transfer( TaskID, "list", "" ) )             }             else if ( InputCommands[...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1711` | `SEND( Execute.Transfer( TaskID, "stop", InputCommands[ 2 ] ) )             }             else if ...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1724` | `SEND( Execute.Transfer( TaskID, "resume", InputCommands[ 2 ] ) )             }             else i...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1737` | `SEND( Execute.Transfer( TaskID, "remove", InputCommands[ 2 ] ) )             }         }         ...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:2037` | `SEND( Execute.Screenshot( TaskID ) )         }         else if ( InputCommands[ 0 ].compare( "net...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:2184` | `SEND( Execute.Pivot( TaskID, Command, Param ) )             }         }         else if ( InputCo...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:2192` | `SEND( Execute.Luid( TaskID ) )         }         else if ( InputCommands[ 0 ].compare( "klist" ) ...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:2324` | `SEND( Execute.Exit( TaskID, "thread" ) )             }             else if ( InputCommands[ 1 ].c...` |
| `compareQString` | function | `client/src/Havoc/Demon/ConsoleInput.cc:183` | `bool compareQString(const QString &a, const QString &b)` |
| `is_number` | function | `client/src/Havoc/Demon/ConsoleInput.cc:28` | `static bool is_number( const std::string& s )` |
| `Exit` | function | `client/src/Havoc/Havoc.cc:93` | `void HavocSpace::Havoc::Exit()` |
| `Havoc` | function | `client/src/Havoc/Havoc.cc:7` | `HavocSpace::Havoc::Havoc( QMainWindow* w )` |
| `Init` | function | `client/src/Havoc/Havoc.cc:22` | `void HavocSpace::Havoc::Init( int argc, char** argv )` |
| `Start` | function | `client/src/Havoc/Havoc.cc:85` | `void HavocSpace::Havoc::Start()` |
| `singleShot` | function | `client/src/Havoc/Havoc.cc:70` | `QTimer::singleShot( 10, [&]()` |
| `DecodePackage` | function | `client/src/Havoc/Packager.cc:63` | `Util::Packager::PPackage Packager::DecodePackage( const QString& Package )` |
| `DispatchChat` | function | `client/src/Havoc/Packager.cc:483` | `bool Packager::DispatchChat( Util::Packager::PPackage Package)` |
| `DispatchGate` | function | `client/src/Havoc/Packager.cc:532` | `bool Packager::DispatchGate( Util::Packager::PPackage Package )` |
| `DispatchInitConnection` | function | `client/src/Havoc/Packager.cc:166` | `bool Packager::DispatchInitConnection( Util::Packager::PPackage Package )` |
| `DispatchListener` | function | `client/src/Havoc/Packager.cc:220` | `bool Packager::DispatchListener( Util::Packager::PPackage Package )` |
| `DispatchService` | function | `client/src/Havoc/Packager.cc:865` | `bool Packager::DispatchService( Util::Packager::PPackage Package )` |
| `DispatchSession` | function | `client/src/Havoc/Packager.cc:581` | `bool Packager::DispatchSession( Util::Packager::PPackage Package )` |
| `DispatchTeamserver` | function | `client/src/Havoc/Packager.cc:961` | `bool Packager::DispatchTeamserver( Util::Packager::PPackage Package )` |
| `EncodePackage` | function | `client/src/Havoc/Packager.cc:106` | `QJsonDocument Packager::EncodePackage( Util::Packager::Package Package )` |
| `foreach` | function | `client/src/Havoc/Packager.cc:90` | `foreach( const QString& key, BodyObject[ "Info" ].toObject().keys() )` |
| `setTeamserver` | function | `client/src/Havoc/Packager.cc:987` | `void Packager::setTeamserver( QString Name )` |
| `AllocMov` | macro | `client/src/Havoc/PythonApi/Event.cc:62` | `#define AllocMov( des, src, size )` |
| `EventClass_OnDemonOutput` | function | `client/src/Havoc/PythonApi/Event.cc:112` | `PyObject* EventClass_OnDemonOutput( PPyEvents self, PyObject *args )` |
| `EventClass_OnNewSession` | function | `client/src/Havoc/PythonApi/Event.cc:96` | `PyObject* EventClass_OnNewSession( PPyEvents self, PyObject *args )` |
| `EventClass_dealloc` | function | `client/src/Havoc/PythonApi/Event.cc:70` | `void EventClass_dealloc( PPyEvents self )` |
| `EventClass_init` | function | `client/src/Havoc/PythonApi/Event.cc:86` | `int EventClass_init( PPyEvents self, PyObject *args, PyObject *kwds )` |
| `EventClass_new` | function | `client/src/Havoc/PythonApi/Event.cc:77` | `PyObject* EventClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )` |
| `GeneratePayload` | function | `client/src/Havoc/PythonApi/Havoc.cc:139` | `PyObject* PythonAPI::Havoc::Core::GeneratePayload( PyObject *self, PyObject *args, PyObject* kwar...` |
| `GetAgents` | function | `client/src/Havoc/PythonApi/Havoc.cc:105` | `PyObject* PythonAPI::Havoc::Core::GetAgents( PyObject *self, PyObject *args )` |
| `GetDemons` | function | `client/src/Havoc/PythonApi/Havoc.cc:123` | `PyObject* PythonAPI::Havoc::Core::GetDemons( PyObject *self, PyObject *args )` |
| `GetListeners` | function | `client/src/Havoc/PythonApi/Havoc.cc:89` | `PyObject* PythonAPI::Havoc::Core::GetListeners( PyObject *self, PyObject *args )` |
| `Load` | function | `client/src/Havoc/PythonApi/Havoc.cc:67` | `PyObject* PythonAPI::Havoc::Core::Load( PyObject *self, PyObject *args )` |
| `PyInit_Havoc` | function | `client/src/Havoc/PythonApi/Havoc.cc:45` | `PyMODINIT_FUNC PythonAPI::Havoc::PyInit_Havoc( void )` |
| `RegisterCallback` | function | `client/src/Havoc/PythonApi/Havoc.cc:321` | `PyObject* PythonAPI::Havoc::Core::RegisterCallback( PyObject *self, PyObject *args )` |
| `RegisterCommand` | function | `client/src/Havoc/PythonApi/Havoc.cc:188` | `PyObject* PythonAPI::Havoc::Core::RegisterCommand( PyObject *self, PyObject *args, PyObject* kwar...` |
| `RegisterModule` | function | `client/src/Havoc/PythonApi/Havoc.cc:265` | `PyObject* PythonAPI::Havoc::Core::RegisterModule( PyObject *self, PyObject *args )` |
| `ColorDialog` | function | `client/src/Havoc/PythonApi/HavocUi.cc:180` | `PyObject* PythonAPI::HavocUI::Core::ColorDialog(PyObject *self, PyObject *args)` |
| `CreateTab` | function | `client/src/Havoc/PythonApi/HavocUi.cc:46` | `PyObject* PythonAPI::HavocUI::Core::CreateTab(PyObject *self, PyObject *args)` |
| `ErrorMessage` | function | `client/src/Havoc/PythonApi/HavocUi.cc:108` | `PyObject* PythonAPI::HavocUI::Core::ErrorMessage(PyObject *self, PyObject *args)` |
| `InputDialog` | function | `client/src/Havoc/PythonApi/HavocUi.cc:141` | `PyObject* PythonAPI::HavocUI::Core::InputDialog(PyObject *self, PyObject *args)` |
| `MessageBox` | function | `client/src/Havoc/PythonApi/HavocUi.cc:84` | `PyObject* PythonAPI::HavocUI::Core::MessageBox(PyObject *self, PyObject *args)` |
| `OpenFileDialog` | function | `client/src/Havoc/PythonApi/HavocUi.cc:154` | `PyObject* PythonAPI::HavocUI::Core::OpenFileDialog(PyObject *self, PyObject *args)` |
| `ProgressDialog` | function | `client/src/Havoc/PythonApi/HavocUi.cc:192` | `PyObject* PythonAPI::HavocUI::Core::ProgressDialog(PyObject *self, PyObject *args)` |
| `PyInit_HavocUI` | function | `client/src/Havoc/PythonApi/HavocUi.cc:241` | `PyMODINIT_FUNC PythonAPI::HavocUI::PyInit_HavocUI(void)` |
| `QuestionDialog` | function | `client/src/Havoc/PythonApi/HavocUi.cc:123` | `PyObject* PythonAPI::HavocUI::Core::QuestionDialog(PyObject *self, PyObject *args)` |
| `SaveFileDialog` | function | `client/src/Havoc/PythonApi/HavocUi.cc:167` | `PyObject* PythonAPI::HavocUI::Core::SaveFileDialog(PyObject *self, PyObject *args)` |
| `connect` | function | `client/src/Havoc/PythonApi/HavocUi.cc:76` | `QMainWindow::connect( tupleCallback, &QAction::triggered, HavocX::HavocUserInterface->HavocWindow...` |
| `connect` | function | `client/src/Havoc/PythonApi/HavocUi.cc:212` | `QMainWindow::connect( timer, &QTimer::timeout, HavocX::HavocUserInterface->HavocWindow, [callable...` |
| `connect` | function | `client/src/Havoc/PythonApi/HavocUi.cc:231` | `QMainWindow::connect( cancelButton, &QPushButton::clicked, HavocX::HavocUserInterface->HavocWindo...` |
| `AgentClass_Command` | function | `client/src/Havoc/PythonApi/PyAgentClass.cc:149` | `PyObject* AgentClass_Command( PPyAgentClass self, PyObject *args )` |
| `AgentClass_ConsoleWrite` | function | `client/src/Havoc/PythonApi/PyAgentClass.cc:112` | `PyObject* AgentClass_ConsoleWrite( PPyAgentClass self, PyObject *args )` |
| `AgentClass_dealloc` | function | `client/src/Havoc/PythonApi/PyAgentClass.cc:69` | `void AgentClass_dealloc( PPyAgentClass self )` |
| `AgentClass_init` | function | `client/src/Havoc/PythonApi/PyAgentClass.cc:85` | `int AgentClass_init( PPyAgentClass self, PyObject *args, PyObject *kwds )` |
| `AgentClass_new` | function | `client/src/Havoc/PythonApi/PyAgentClass.cc:76` | `PyObject* AgentClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )` |
| `PY_SSIZE_T_CLEAN` | macro | `client/src/Havoc/PythonApi/PyAgentClass.cc:2` | `#define PY_SSIZE_T_CLEAN` |
| `AllocMov` | macro | `client/src/Havoc/PythonApi/PyDemonClass.cc:92` | `#define AllocMov( des, src, size )` |
| `DemonClass_Command` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:333` | `PyObject* DemonClass_Command( PPyDemonClass self, PyObject *args )` |
| `DemonClass_CommandGetOutput` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:353` | `PyObject* DemonClass_CommandGetOutput( PPyDemonClass self, PyObject *args )` |
| `DemonClass_ConsoleWrite` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:539` | `PyObject* DemonClass_ConsoleWrite( PPyDemonClass self, PyObject *args )` |
| `DemonClass_DllInject` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:430` | `PyObject* DemonClass_DllInject( PPyDemonClass self, PyObject *args )` |
| `DemonClass_DllSpawn` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:453` | `PyObject* DemonClass_DllSpawn( PPyDemonClass self, PyObject *args )` |
| `DemonClass_DotnetInlineExecute` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:312` | `PyObject* DemonClass_DotnetInlineExecute( PPyDemonClass self, PyObject *args )` |
| `DemonClass_InlineExecute` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:200` | `PyObject* DemonClass_InlineExecute( PPyDemonClass self, PyObject *args )` |
| `DemonClass_InlineExecuteGetOutput` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:250` | `PyObject* DemonClass_InlineExecuteGetOutput( PPyDemonClass self, PyObject *args )` |
| `DemonClass_ProcessCreate` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:491` | `PyObject* DemonClass_ProcessCreate( PPyDemonClass self, PyObject *args )` |
| `DemonClass_Shell` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:179` | `PyObject* DemonClass_Shell( PPyDemonClass self, PyObject *args )` |
| `DemonClass_ShellcodeSpawn` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:389` | `PyObject* DemonClass_ShellcodeSpawn( PPyDemonClass self, PyObject *args )` |
| `DemonClass_dealloc` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:100` | `void DemonClass_dealloc( PPyDemonClass self )` |
| `DemonClass_init` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:128` | `int DemonClass_init( PPyDemonClass self, PyObject *args, PyObject *kwds )` |
| `DemonClass_new` | function | `client/src/Havoc/PythonApi/PyDemonClass.cc:119` | `PyObject* DemonClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )` |
| `PY_SSIZE_T_CLEAN` | macro | `client/src/Havoc/PythonApi/PyDemonClass.cc:2` | `#define PY_SSIZE_T_CLEAN` |
| `PyInit_emb` | function | `client/src/Havoc/PythonApi/PythonApi.cc:87` | `PyMODINIT_FUNC PyInit_emb(void)` |
| `Stdout_flush` | function | `client/src/Havoc/PythonApi/PythonApi.cc:22` | `PyObject* Stdout_flush(PyObject* self, PyObject* args)` |
| `Stdout_write` | function | `client/src/Havoc/PythonApi/PythonApi.cc:5` | `PyObject* Stdout_write(PyObject* self, PyObject* args)` |
| `reset_stdout` | function | `client/src/Havoc/PythonApi/PythonApi.cc:118` | `void reset_stdout()` |
| `set_stdout` | function | `client/src/Havoc/PythonApi/PythonApi.cc:105` | `void set_stdout(stdout_write_type write)` |
| `written` | function | `client/src/Havoc/PythonApi/PythonApi.cc:7` | `std::size_t written(0);` |
| `AllocMov` | macro | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:78` | `#define AllocMov( des, src, size )` |
| `DialogClass_addButton` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:193` | `PyObject* DialogClass_addButton( PPyDialogClass self, PyObject *args )` |
| `DialogClass_addCalendar` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:300` | `PyObject* DialogClass_addCalendar( PPyDialogClass self, PyObject *args )` |
| `DialogClass_addCheckbox` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:219` | `PyObject* DialogClass_addCheckbox( PPyDialogClass self, PyObject *args )` |
| `DialogClass_addCombobox` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:248` | `PyObject* DialogClass_addCombobox( PPyDialogClass self, PyObject *args )` |
| `DialogClass_addDial` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:329` | `PyObject* DialogClass_addDial( PPyDialogClass self, PyObject *args )` |
| `DialogClass_addImage` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:177` | `PyObject* DialogClass_addImage( PPyDialogClass self, PyObject *args )` |
| `DialogClass_addLabel` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:163` | `PyObject* DialogClass_addLabel( PPyDialogClass self, PyObject *args )` |
| `DialogClass_addLineedit` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:272` | `PyObject* DialogClass_addLineedit( PPyDialogClass self, PyObject *args )` |
| `DialogClass_addSlider` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:352` | `PyObject* DialogClass_addSlider( PPyDialogClass self, PyObject *args )` |
| `DialogClass_clear` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:412` | `PyObject* DialogClass_clear( PPyDialogClass self, PyObject *args )` |
| `DialogClass_close` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:405` | `PyObject* DialogClass_close( PPyDialogClass self, PyObject *args )` |
| `DialogClass_dealloc` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:86` | `void DialogClass_dealloc( PPyDialogClass self )` |
| `DialogClass_exec` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:155` | `PyObject* DialogClass_exec( PPyDialogClass self, PyObject *args )` |
| `DialogClass_init` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:121` | `int DialogClass_init( PPyDialogClass self, PyObject *args, PyObject *kwds )` |
| `DialogClass_new` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:99` | `PyObject* DialogClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )` |
| `DialogClass_replaceLabel` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:381` | `PyObject* DialogClass_replaceLabel( PPyDialogClass self, PyObject *args )` |
| `PY_SSIZE_T_CLEAN` | macro | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:2` | `#define PY_SSIZE_T_CLEAN` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:212` | `QObject::connect(button, &QPushButton::clicked, self->DialogWindow->window, [button_callback]()` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:241` | `QObject::connect(checkbox, &QCheckBox::clicked, self->DialogWindow->window, [checkbox_callback]()` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:265` | `QObject::connect(comboBox, QOverload<int>::of(&QComboBox::activated), [callable_obj](int index)` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:289` | `QObject::connect(line, &QLineEdit::editingFinished, self->DialogWindow->window, [line, line_callb...` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:317` | `QObject::connect(cal, &QCalendarWidget::selectionChanged, self->DialogWindow->window, [cal, cal_c...` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:345` | `QObject::connect(dial, &QDial::valueChanged, self->DialogWindow->window, [cal_callback](long value)` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:374` | `QObject::connect(slider, &QSlider::valueChanged, self->DialogWindow->window, [cal_callback](long ...` |
| `AllocMov` | macro | `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:69` | `#define AllocMov( des, src, size )` |
| `LoggerClass_addText` | function | `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:137` | `PyObject* LoggerClass_addText( PPyLoggerClass self, PyObject *args )` |
| `LoggerClass_clear` | function | `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:149` | `PyObject* LoggerClass_clear( PPyLoggerClass self, PyObject *args )` |
| `LoggerClass_dealloc` | function | `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:77` | `void LoggerClass_dealloc( PPyLoggerClass self )` |
| `LoggerClass_init` | function | `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:95` | `int LoggerClass_init( PPyLoggerClass self, PyObject *args, PyObject *kwds )` |
| `LoggerClass_new` | function | `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:86` | `PyObject* LoggerClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )` |
| `LoggerClass_setBottomTab` | function | `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:123` | `PyObject* LoggerClass_setBottomTab( PPyLoggerClass self, PyObject *args )` |
| `LoggerClass_setSmallTab` | function | `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:130` | `PyObject* LoggerClass_setSmallTab( PPyLoggerClass self, PyObject *args )` |
| `PY_SSIZE_T_CLEAN` | macro | `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:2` | `#define PY_SSIZE_T_CLEAN` |
| `AllocMov` | macro | `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:70` | `#define AllocMov( des, src, size )` |
| `PY_SSIZE_T_CLEAN` | macro | `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:2` | `#define PY_SSIZE_T_CLEAN` |
| `TreeClass_addRow` | function | `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:195` | `PyObject* TreeClass_addRow( PPyTreeClass self, PyObject *args )` |
| `TreeClass_dealloc` | function | `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:78` | `void TreeClass_dealloc( PPyTreeClass self )` |
| `TreeClass_init` | function | `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:112` | `int TreeClass_init( PPyTreeClass self, PyObject *args, PyObject *kwds )` |
| `TreeClass_new` | function | `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:91` | `PyObject* TreeClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )` |
| `TreeClass_setBottomTab` | function | `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:181` | `PyObject* TreeClass_setBottomTab( PPyTreeClass self, PyObject *args )` |
| `TreeClass_setItem` | function | `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:218` | `PyObject* TreeClass_setItem( PPyTreeClass self, PyObject *args )` |
| `TreeClass_setPanel` | function | `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:233` | `PyObject* TreeClass_setPanel( PPyTreeClass self, PyObject *args )` |
| `TreeClass_setSmallTab` | function | `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:188` | `PyObject* TreeClass_setSmallTab( PPyTreeClass self, PyObject *args )` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:165` | `QObject::connect(self->TreeWindow->tree_view->selectionModel(), &QItemSelectionModel::selectionCh...` |
| `AllocMov` | macro | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:78` | `#define AllocMov( des, src, size )` |
| `PY_SSIZE_T_CLEAN` | macro | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:2` | `#define PY_SSIZE_T_CLEAN` |
| `WidgetClass_addButton` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:193` | `PyObject* WidgetClass_addButton( PPyWidgetClass self, PyObject *args )` |
| `WidgetClass_addCalendar` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:300` | `PyObject* WidgetClass_addCalendar( PPyWidgetClass self, PyObject *args )` |
| `WidgetClass_addCheckbox` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:219` | `PyObject* WidgetClass_addCheckbox( PPyWidgetClass self, PyObject *args )` |
| `WidgetClass_addCombobox` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:248` | `PyObject* WidgetClass_addCombobox( PPyWidgetClass self, PyObject *args )` |
| `WidgetClass_addDial` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:329` | `PyObject* WidgetClass_addDial( PPyWidgetClass self, PyObject *args )` |
| `WidgetClass_addImage` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:163` | `PyObject* WidgetClass_addImage( PPyWidgetClass self, PyObject *args )` |
| `WidgetClass_addLabel` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:149` | `PyObject* WidgetClass_addLabel( PPyWidgetClass self, PyObject *args )` |
| `WidgetClass_addLineedit` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:272` | `PyObject* WidgetClass_addLineedit( PPyWidgetClass self, PyObject *args )` |
| `WidgetClass_addSlider` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:352` | `PyObject* WidgetClass_addSlider( PPyWidgetClass self, PyObject *args )` |
| `WidgetClass_clear` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:405` | `PyObject* WidgetClass_clear( PPyWidgetClass self, PyObject *args )` |
| `WidgetClass_dealloc` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:86` | `void WidgetClass_dealloc( PPyWidgetClass self )` |
| `WidgetClass_init` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:119` | `int WidgetClass_init( PPyWidgetClass self, PyObject *args, PyObject *kwds )` |
| `WidgetClass_new` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:99` | `PyObject* WidgetClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )` |
| `WidgetClass_replaceLabel` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:381` | `PyObject* WidgetClass_replaceLabel( PPyWidgetClass self, PyObject *args )` |
| `WidgetClass_setBottomTab` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:179` | `PyObject* WidgetClass_setBottomTab( PPyWidgetClass self, PyObject *args )` |
| `WidgetClass_setSmallTab` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:186` | `PyObject* WidgetClass_setSmallTab( PPyWidgetClass self, PyObject *args )` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:212` | `QObject::connect(button, &QPushButton::clicked, self->WidgetWindow->window, [button_callback]()` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:241` | `QObject::connect(checkbox, &QCheckBox::clicked, self->WidgetWindow->window, [checkbox_callback]()` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:265` | `QObject::connect(comboBox, QOverload<int>::of(&QComboBox::activated), [callable_obj](int index)` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:289` | `QObject::connect(line, &QLineEdit::editingFinished, self->WidgetWindow->window, [line, line_callb...` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:317` | `QObject::connect(cal, &QCalendarWidget::selectionChanged, self->WidgetWindow->window, [cal, cal_c...` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:345` | `QObject::connect(dial, &QDial::valueChanged, self->WidgetWindow->window, [cal_callback](long value)` |
| `connect` | function | `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:374` | `QObject::connect(slider, &QSlider::valueChanged, self->WidgetWindow->window, [cal_callback](long ...` |
| `About` | function | `client/src/UserInterface/Dialogs/About.cc:4` | `About::About( QDialog* dialog )` |
| `onButtonClose` | function | `client/src/UserInterface/Dialogs/About.cc:54` | `void About::onButtonClose()` |
| `setupUi` | function | `client/src/UserInterface/Dialogs/About.cc:49` | `void About::setupUi()` |
| `StartDialog` | function | `client/src/UserInterface/Dialogs/Connect.cc:165` | `Util::ConnectionInfo HavocNamespace::UserInterface::Dialogs::Connect::StartDialog( bool FromAction )` |
| `connect` | function | `client/src/UserInterface/Dialogs/Connect.cc:142` | `connect( lineEdit_Name, &QLineEdit::returnPressed, this, [&]()` |
| `connect` | function | `client/src/UserInterface/Dialogs/Connect.cc:146` | `connect( lineEdit_User, &QLineEdit::returnPressed, this, [&]()` |
| `connect` | function | `client/src/UserInterface/Dialogs/Connect.cc:150` | `connect( lineEdit_Host, &QLineEdit::returnPressed, this, [&]()` |
| `connect` | function | `client/src/UserInterface/Dialogs/Connect.cc:154` | `connect( lineEdit_Port, &QLineEdit::returnPressed, this, [&]()` |
| `connect` | function | `client/src/UserInterface/Dialogs/Connect.cc:158` | `connect( lineEdit_Password, &QLineEdit::returnPressed, this, [&]()` |
| `handleContextMenu` | function | `client/src/UserInterface/Dialogs/Connect.cc:356` | `void HavocNamespace::UserInterface::Dialogs::Connect::handleContextMenu( const QPoint &pos )` |
| `itemRemove` | function | `client/src/UserInterface/Dialogs/Connect.cc:362` | `void HavocNamespace::UserInterface::Dialogs::Connect::itemRemove()` |
| `itemSelected` | function | `client/src/UserInterface/Dialogs/Connect.cc:318` | `void HavocNamespace::UserInterface::Dialogs::Connect::itemSelected()` |
| `itemsClear` | function | `client/src/UserInterface/Dialogs/Connect.cc:376` | `void HavocNamespace::UserInterface::Dialogs::Connect::itemsClear()` |
| `onButton_Connect` | function | `client/src/UserInterface/Dialogs/Connect.cc:234` | `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_Connect()` |
| `onButton_NewProfile` | function | `client/src/UserInterface/Dialogs/Connect.cc:340` | `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_NewProfile()` |
| `passDB` | function | `client/src/UserInterface/Dialogs/Connect.cc:229` | `void HavocNamespace::UserInterface::Dialogs::Connect::passDB(HavocNamespace::HavocSpace::DBManage...` |
| `setupUi` | function | `client/src/UserInterface/Dialogs/Connect.cc:9` | `void HavocNamespace::UserInterface::Dialogs::Connect::setupUi( QDialog* Form )` |
| `NewListener` | function | `client/src/UserInterface/Dialogs/Listener.cc:24` | `NewListener::NewListener( QDialog* Dialog )` |
| `Start` | function | `client/src/UserInterface/Dialogs/Listener.cc:450` | `MapStrStr NewListener::Start( Util::ListenerItem Item, bool Edit )` |
| `connect` | function | `client/src/UserInterface/Dialogs/Listener.cc:331` | `QObject::connect( ButtonClose, &QPushButton::clicked, this, [&]()` |
| `connect` | function | `client/src/UserInterface/Dialogs/Listener.cc:339` | `QObject::connect( ButtonHostsGroupAdd, &QPushButton::clicked, this, [&]()` |
| `connect` | function | `client/src/UserInterface/Dialogs/Listener.cc:356` | `QObject::connect( ButtonHostsGroupClear, &QPushButton::clicked, this, [&]()` |
| `connect` | function | `client/src/UserInterface/Dialogs/Listener.cc:366` | `QObject::connect( ButtonUriGroupAdd, &QPushButton::clicked, this, [&]()` |
| `connect` | function | `client/src/UserInterface/Dialogs/Listener.cc:377` | `QObject::connect( ButtonUriGroupClear, &QPushButton::clicked, this, [&]()` |
| `connect` | function | `client/src/UserInterface/Dialogs/Listener.cc:387` | `QObject::connect( ButtonHeaderGroupAdd, &QPushButton::clicked, this, [&]()` |
| `connect` | function | `client/src/UserInterface/Dialogs/Listener.cc:398` | `QObject::connect( ButtonHeaderGroupClear, &QPushButton::clicked, this, [&]()` |
| `connect` | function | `client/src/UserInterface/Dialogs/Listener.cc:408` | `QObject::connect( ComboPayload, &QComboBox::currentTextChanged, this, [&]( const QString& text )` |
| `is_number` | function | `client/src/UserInterface/Dialogs/Listener.cc:17` | `bool is_number( const std::string& s )` |
| `onButton_Save` | function | `client/src/UserInterface/Dialogs/Listener.cc:817` | `void HavocNamespace::UserInterface::Dialogs::NewListener::onButton_Save()` |
| `onProxyEnabled` | function | `client/src/UserInterface/Dialogs/Listener.cc:947` | `void HavocNamespace::UserInterface::Dialogs::NewListener::onProxyEnabled()` |
| `buttonGenerate` | function | `client/src/UserInterface/Dialogs/Payload.cc:190` | `void Payload::buttonGenerate()` |
| `connect` | function | `client/src/UserInterface/Dialogs/Payload.cc:124` | `connect( ComboFormat, &QComboBox::currentTextChanged, this, [&]( const QString& text )` |
| `setupUi` | function | `client/src/UserInterface/Dialogs/Payload.cc:17` | `void Payload::setupUi( QDialog* Dialog )` |
| `ConnectEvents` | function | `client/src/UserInterface/HavocUi.cc:395` | `void HavocNamespace::UserInterface::HavocUi::ConnectEvents()` |
| `MarkSessionAs` | function | `client/src/UserInterface/HavocUi.cc:205` | `void HavocNamespace::UserInterface::HavocUi::MarkSessionAs(HavocNamespace::Util::SessionItem Sess...` |
| `NewBottomTab` | function | `client/src/UserInterface/HavocUi.cc:567` | `void HavocNamespace::UserInterface::HavocUi::NewBottomTab(QWidget* TabWidget, const std::string& ...` |
| `NewSmallTab` | function | `client/src/UserInterface/HavocUi.cc:596` | `void UserInterface::HavocUi::NewSmallTab(QWidget *TabWidget, const string &TitleName ) const` |
| `NewTeamserverTab` | function | `client/src/UserInterface/HavocUi.cc:577` | `void UserInterface::HavocUi::NewTeamserverTab(HavocNamespace::Util::ConnectionInfo* Connection )` |
| `NewTeamserverTab` | function | `client/src/UserInterface/HavocUi.cc:587` | `void UserInterface::HavocUi::NewTeamserverTab(QString Name )` |
| `OneSecondTick` | function | `client/src/UserInterface/HavocUi.cc:200` | `void HavocNamespace::UserInterface::HavocUi::OneSecondTick()` |
| `PythonPrepare` | function | `client/src/UserInterface/HavocUi.cc:602` | `void UserInterface::HavocUi::PythonPrepare()` |
| `UpdateSessionsHealth` | function | `client/src/UserInterface/HavocUi.cc:263` | `void HavocNamespace::UserInterface::HavocUi::UpdateSessionsHealth()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:399` | `QMainWindow::connect( OneSecondTimer, &QTimer::timeout, this, [&]()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:404` | `QMainWindow::connect( actionNew_Client, &QAction::triggered, this, []()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:408` | `QMainWindow::connect( actionChat, &QAction::triggered, this, [&]()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:422` | `QMainWindow::connect( actionDisconnect, &QAction::triggered, this, []()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:431` | `QMainWindow::connect( actionExit, &QAction::triggered, this, []()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:435` | `QMainWindow::connect( actionSessionsTable, &QAction::triggered, this, []()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:439` | `QMainWindow::connect( actionListeners, &QAction::triggered, this, [&]()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:455` | `QMainWindow::connect( actionTeamserver, &QAction::triggered, this, [&]()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:467` | `QMainWindow::connect( actionStore, &QAction::triggered, this, [&]()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:479` | `QMainWindow::connect( actionSessionsGraph, &QAction::triggered, this, [&]()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:483` | `QMainWindow::connect( actionLogs, &QAction::triggered, this, [&]()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:498` | `QMainWindow::connect( actionLoot, &QAction::triggered, this, [&]()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:506` | `QMainWindow::connect( actionGeneratePayload, &QAction::triggered, this, []()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:516` | `QMainWindow::connect( actionPythonConsole, &QAction::triggered, this, [&]()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:530` | `QMainWindow::connect( actionLoad_Script, &QAction::triggered, this, [&]()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:549` | `QMainWindow::connect( actionAbout, &QAction::triggered, this, [&]()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:558` | `QMainWindow::connect( actionGithub_Repository, &QAction::triggered, this, []()` |
| `connect` | function | `client/src/UserInterface/HavocUi.cc:562` | `QMainWindow::connect( actionOpen_Help_Documentation, &QAction::triggered, this, []()` |
| `retranslateUi` | function | `client/src/UserInterface/HavocUi.cc:361` | `void HavocNamespace::UserInterface::HavocUi::retranslateUi(QMainWindow* Havoc ) const` |
| `setDBManager` | function | `client/src/UserInterface/HavocUi.cc:572` | `void HavocNamespace::UserInterface::HavocUi::setDBManager(HavocSpace::DBManager* dbManager)` |
| `setupUi` | function | `client/src/UserInterface/HavocUi.cc:28` | `void HavocNamespace::UserInterface::HavocUi::setupUi(QMainWindow *Havoc)` |
| `AppendText` | function | `client/src/UserInterface/SmallWidgets/EventViewer.cc:23` | `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::AppendText(const QString& Time, co...` |
| `setupUi` | function | `client/src/UserInterface/SmallWidgets/EventViewer.cc:4` | `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::setupUi(QWidget *Widget)` |
| `AddUserMessage` | function | `client/src/UserInterface/Widgets/Chat.cc:70` | `void HavocNamespace::UserInterface::Widgets::Chat::AddUserMessage(const QString Time, QString Use...` |
| `AppendFromInput` | function | `client/src/UserInterface/Widgets/Chat.cc:78` | `void HavocNamespace::UserInterface::Widgets::Chat::AppendFromInput()` |
| `AppendText` | function | `client/src/UserInterface/Widgets/Chat.cc:63` | `void HavocNamespace::UserInterface::Widgets::Chat::AppendText(const QString& Time, const QString&...` |
| `setupUi` | function | `client/src/UserInterface/Widgets/Chat.cc:11` | `void HavocNamespace::UserInterface::Widgets::Chat::setupUi( QWidget *Form )` |
| `AddCommand` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:90` | `void DemonInteracted::DemonInput::AddCommand( const QString &Command )` |
| `AppendFromInput` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:209` | `void DemonInteracted::AppendFromInput()` |
| `AppendNoNL` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:308` | `void DemonInteracted::AppendNoNL( const QString &text )` |
| `AppendRaw` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:303` | `void UserInterface::Widgets::DemonInteracted::AppendRaw(const QString& text)` |
| `AppendText` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:214` | `void DemonInteracted::AppendText( const QString& text )` |
| `AutoCompleteAdd` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:317` | `void DemonInteracted::AutoCompleteAdd( QString text )` |
| `AutoCompleteAddList` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:336` | `void DemonInteracted::AutoCompleteAddList( QStringList list )` |
| `AutoCompleteClear` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:326` | `void DemonInteracted::AutoCompleteClear()` |
| `DemonInput` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:16` | `DemonInteracted::DemonInput::DemonInput( QWidget* parent ) : QLineEdit( parent )` |
| `TaskError` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:296` | `QString DemonInteracted::TaskError( const QString &text ) const` |
| `TaskInfo` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:281` | `QString DemonInteracted::TaskInfo( bool Show, QString TaskID, const QString &text ) const` |
| `event` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:78` | `bool DemonInteracted::DemonInput::event( QEvent* e )` |
| `handleDownKey` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:67` | `void DemonInteracted::DemonInput::handleDownKey()` |
| `handleKeyPress` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:21` | `bool DemonInteracted::DemonInput::handleKeyPress( QKeyEvent* eventKey )` |
| `handleTabKey` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:39` | `void DemonInteracted::DemonInput::handleTabKey()` |
| `handleUpKey` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:47` | `void DemonInteracted::DemonInput::handleUpKey()` |
| `setupUi` | function | `client/src/UserInterface/Widgets/DemonInteracted.cc:95` | `void DemonInteracted::setupUi( QWidget *Form )` |
| `AddData` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:159` | `void FileBrowser::AddData( QJsonDocument JsonData )` |
| `ChangePathAndSendRequest` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:297` | `void FileBrowser::ChangePathAndSendRequest( QString Path )` |
| `TableAddData` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:239` | `void FileBrowser::TableAddData( FileData Data )` |
| `TableClear` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:313` | `void FileBrowser::TableClear()` |
| `TreeAddChildToParent` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:537` | `void FileBrowser::TreeAddChildToParent( QString ParentPath, FileBrowserTreeItem* DataItem )` |
| `TreeAddData` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:234` | `void FileBrowser::TreeAddData( FileData Data )` |
| `TreeAddDisk` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:523` | `void FileBrowser::TreeAddDisk( QString Disk )` |
| `TreeClear` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:500` | `void FileBrowser::TreeClear( )` |
| `TreeUpdate` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:438` | `void FileBrowser::TreeUpdate()` |
| `onButtonUp` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:320` | `void FileBrowser::onButtonUp()` |
| `onInputPath` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:430` | `void FileBrowser::onInputPath()` |
| `onTableContextMenu` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:363` | `void FileBrowser::onTableContextMenu( const QPoint &pos )` |
| `onTableDoubleClick` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:276` | `void FileBrowser::onTableDoubleClick( int row, int column )` |
| `onTableMenuDownload` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:327` | `void FileBrowser::onTableMenuDownload()` |
| `onTableMenuMkdir` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:379` | `void FileBrowser::onTableMenuMkdir()` |
| `onTableMenuReload` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:384` | `void FileBrowser::onTableMenuReload()` |
| `onTableMenuRemove` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:405` | `void FileBrowser::onTableMenuRemove()` |
| `onTreeContextMenu` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:371` | `void FileBrowser::onTreeContextMenu( const QPoint &pos )` |
| `onTreeDoubleClick` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:292` | `void FileBrowser::onTreeDoubleClick()` |
| `onTreeMenuListDrives` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:410` | `void FileBrowser::onTreeMenuListDrives()` |
| `onTreeMenuMkdir` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:415` | `void FileBrowser::onTreeMenuMkdir()` |
| `onTreeMenuReload` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:420` | `void FileBrowser::onTreeMenuReload()` |
| `onTreeMenuRemove` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:425` | `void FileBrowser::onTreeMenuRemove()` |
| `retranslateUi` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:148` | `void FileBrowser::retranslateUi()` |
| `setupUi` | function | `client/src/UserInterface/Widgets/FileBrowser.cc:40` | `void FileBrowser::setupUi( QWidget* FileBrowser )` |
| `ButtonsInit` | function | `client/src/UserInterface/Widgets/ListenersTable.cc:85` | `void HavocNamespace::UserInterface::Widgets::ListenersTable::ButtonsInit()` |
| `CreateNewPackage` | function | `client/src/UserInterface/Widgets/ListenersTable.cc:289` | `Util::Packager::Package UserInterface::Widgets::ListenersTable::CreateNewPackage( int EventID, ma...` |
| `ListenerAdd` | function | `client/src/UserInterface/Widgets/ListenersTable.cc:178` | `void HavocNamespace::UserInterface::Widgets::ListenersTable::ListenerAdd( Util::ListenerItem item...` |
| `ListenerEdit` | function | `client/src/UserInterface/Widgets/ListenersTable.cc:312` | `void UserInterface::Widgets::ListenersTable::ListenerEdit( Util::ListenerItem item ) const` |
| `ListenerError` | function | `client/src/UserInterface/Widgets/ListenersTable.cc:357` | `void UserInterface::Widgets::ListenersTable::ListenerError( QString ListenerName, QString Error )...` |
| `ListenerRemove` | function | `client/src/UserInterface/Widgets/ListenersTable.cc:323` | `void UserInterface::Widgets::ListenersTable::ListenerRemove( QString ListenerName ) const` |
| `connect` | function | `client/src/UserInterface/Widgets/ListenersTable.cc:87` | `QObject::connect( buttonAdd, &QPushButton::clicked, this, [&]()` |
| `connect` | function | `client/src/UserInterface/Widgets/ListenersTable.cc:108` | `QObject::connect( buttonEdit, &QPushButton::clicked, this, [&]()` |
| `connect` | function | `client/src/UserInterface/Widgets/ListenersTable.cc:152` | `QObject::connect( buttonRemove,  &QPushButton::clicked, this, [&]()` |
| `setDBManager` | function | `client/src/UserInterface/Widgets/ListenersTable.cc:284` | `void HavocNamespace::UserInterface::Widgets::ListenersTable::setDBManager( HavocSpace::DBManager*...` |
| `setupUi` | function | `client/src/UserInterface/Widgets/ListenersTable.cc:15` | `void HavocNamespace::UserInterface::Widgets::ListenersTable::setupUi( QWidget* Form )` |
| `AddDownload` | function | `client/src/UserInterface/Widgets/LootWidget.cc:273` | `void LootWidget::AddDownload( const QString &DemonID, const QString &Name, const QString& Size, c...` |
| `AddScreenshot` | function | `client/src/UserInterface/Widgets/LootWidget.cc:253` | `void LootWidget::AddScreenshot( const QString& DemonID, const QString& Name, const QString& Date,...` |
| `AddSessionSection` | function | `client/src/UserInterface/Widgets/LootWidget.cc:364` | `void LootWidget::AddSessionSection( const QString& AgentID )` |
| `DownloadTableAdd` | function | `client/src/UserInterface/Widgets/LootWidget.cc:414` | `void LootWidget::DownloadTableAdd( const QString &Name, const QString &Size, const QString &Date )` |
| `ImageLabel` | function | `client/src/UserInterface/Widgets/LootWidget.cc:17` | `ImageLabel::ImageLabel( QWidget* parent ) : QWidget( parent )` |
| `LootWidget` | function | `client/src/UserInterface/Widgets/LootWidget.cc:92` | `LootWidget::LootWidget()` |
| `Reload` | function | `client/src/UserInterface/Widgets/LootWidget.cc:292` | `void LootWidget::Reload()` |
| `ScreenshotTableAdd` | function | `client/src/UserInterface/Widgets/LootWidget.cc:389` | `void LootWidget::ScreenshotTableAdd( const QString &Name, const QString &Date )` |
| `event` | function | `client/src/UserInterface/Widgets/LootWidget.cc:44` | `bool ImageLabel::event( QEvent* e )` |
| `keyReleaseEvent` | function | `client/src/UserInterface/Widgets/LootWidget.cc:60` | `void ImageLabel::keyReleaseEvent( QKeyEvent* event )` |
| `onAgentChange` | function | `client/src/UserInterface/Widgets/LootWidget.cc:334` | `void LootWidget::onAgentChange( const QString& text )` |
| `onDownloadTableClick` | function | `client/src/UserInterface/Widgets/LootWidget.cc:329` | `void LootWidget::onDownloadTableClick( const QModelIndex &index )` |
| `onScreenshotTableClick` | function | `client/src/UserInterface/Widgets/LootWidget.cc:305` | `void LootWidget::onScreenshotTableClick( const QModelIndex &index )` |
| `onScreenshotTableCtx` | function | `client/src/UserInterface/Widgets/LootWidget.cc:436` | `void LootWidget::onScreenshotTableCtx( const QPoint &pos )` |
| `onShowChange` | function | `client/src/UserInterface/Widgets/LootWidget.cc:377` | `void LootWidget::onShowChange( const QString& text )` |
| `pixmap` | function | `client/src/UserInterface/Widgets/LootWidget.cc:39` | `const QPixmap* ImageLabel::pixmap() const` |
| `resizeEvent` | function | `client/src/UserInterface/Widgets/LootWidget.cc:33` | `void ImageLabel::resizeEvent( QResizeEvent* event )` |
| `resizeImage` | function | `client/src/UserInterface/Widgets/LootWidget.cc:85` | `void ImageLabel::resizeImage()` |
| `setPixmap` | function | `client/src/UserInterface/Widgets/LootWidget.cc:78` | `void ImageLabel::setPixmap( const QPixmap &pixmap )` |
| `wheelEvent` | function | `client/src/UserInterface/Widgets/LootWidget.cc:71` | `void ImageLabel::wheelEvent( QWheelEvent* ev )` |
| `NewTableProcess` | function | `client/src/UserInterface/Widgets/ProcessList.cc:231` | `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTableProcess(std::map<QString, QStri...` |
| `NewTreeProcess` | function | `client/src/UserInterface/Widgets/ProcessList.cc:279` | `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTreeProcess( std::map<QString,QStrin...` |
| `UpdateProcessListJson` | function | `client/src/UserInterface/Widgets/ProcessList.cc:201` | `void HavocNamespace::UserInterface::Widgets::ProcessList::UpdateProcessListJson( QJsonDocument Pr...` |
| `handleTableListMenuContext` | function | `client/src/UserInterface/Widgets/ProcessList.cc:343` | `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTableListMenuContext( const QPoin...` |
| `handleTreeListMenuContext` | function | `client/src/UserInterface/Widgets/ProcessList.cc:351` | `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTreeListMenuContext( const QPoint...` |
| `onActionCopyPID` | function | `client/src/UserInterface/Widgets/ProcessList.cc:359` | `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionCopyPID()` |
| `onActionSetParentProcess` | function | `client/src/UserInterface/Widgets/ProcessList.cc:367` | `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionSetParentProcess()` |
| `onButton_Refresh` | function | `client/src/UserInterface/Widgets/ProcessList.cc:299` | `void HavocNamespace::UserInterface::Widgets::ProcessList::onButton_Refresh() const` |
| `onTableChange` | function | `client/src/UserInterface/Widgets/ProcessList.cc:314` | `void HavocNamespace::UserInterface::Widgets::ProcessList::onTableChange()` |
| `onTreeChange` | function | `client/src/UserInterface/Widgets/ProcessList.cc:330` | `void HavocNamespace::UserInterface::Widgets::ProcessList::onTreeChange()` |
| `setupUi` | function | `client/src/UserInterface/Widgets/ProcessList.cc:5` | `void HavocNamespace::UserInterface::Widgets::ProcessList::setupUi(QWidget *Widget)` |
| `AppendFromInput` | function | `client/src/UserInterface/Widgets/PythonScript.cc:64` | `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendFromInput()` |
| `AppendOutput` | function | `client/src/UserInterface/Widgets/PythonScript.cc:76` | `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendOutput( QString output )` |
| `RunCode` | function | `client/src/UserInterface/Widgets/PythonScript.cc:48` | `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::RunCode( QString code )` |
| `setupUi` | function | `client/src/UserInterface/Widgets/PythonScript.cc:9` | `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::setupUi(QWidget *WindowWidget)` |
| `AddScript` | function | `client/src/UserInterface/Widgets/ScriptManager.cc:111` | `bool ScriptManager::AddScript( QString Path )` |
| `AddScriptTable` | function | `client/src/UserInterface/Widgets/ScriptManager.cc:140` | `void ScriptManager::AddScriptTable( QString Path )` |
| `ReloadScript` | function | `client/src/UserInterface/Widgets/ScriptManager.cc:195` | `void ScriptManager::ReloadScript() const` |
| `RemoveScript` | function | `client/src/UserInterface/Widgets/ScriptManager.cc:204` | `void ScriptManager::RemoveScript() const` |
| `RetranslateUi` | function | `client/src/UserInterface/Widgets/ScriptManager.cc:104` | `void ScriptManager::RetranslateUi( )` |
| `SetupUi` | function | `client/src/UserInterface/Widgets/ScriptManager.cc:13` | `void ScriptManager::SetupUi( QWidget *Form )` |
| `b_LoadScript` | function | `client/src/UserInterface/Widgets/ScriptManager.cc:155` | `void ScriptManager::b_LoadScript()` |
| `menu_ScriptMenu` | function | `client/src/UserInterface/Widgets/ScriptManager.cc:186` | `void ScriptManager::menu_ScriptMenu( const QPoint &pos ) const` |
| `Color` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:863` | `void Edge::Color( QColor color )` |
| `Edge` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:508` | `Edge::Edge( Node* sourceNode, Node* destNode, QColor Color )     : source( sourceNode ), dest( de...` |
| `GraphNodeAdd` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:54` | `Node* GraphWidget::GraphNodeAdd( SessionItem Session )` |
| `GraphNodeGet` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:309` | `Node *GraphWidget::GraphNodeGet( QString AgentID )` |
| `GraphNodeRemove` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:84` | `void GraphWidget::GraphNodeRemove( SessionItem Session )` |
| `GraphPivotNodeAdd` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:105` | `void GraphWidget::GraphPivotNodeAdd( QString AgentID, SessionItem Session )` |
| `GraphPivotNodeDisconnect` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:147` | `void GraphWidget::GraphPivotNodeDisconnect( QString AgentID )` |
| `GraphPivotNodeReconnect` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:170` | `void GraphWidget::GraphPivotNodeReconnect( QString ParentAgentID, QString ChildAgentID )` |
| `GraphWidget` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:28` | `GraphWidget::GraphWidget( QWidget* parent ) : QGraphicsView( parent )` |
| `Node` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:871` | `Node::Node( NodeItemType NodeType, QString NodeLabel, GraphWidget* graphWidget ) : graph( graphWi...` |
| `addEdge` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:904` | `void Node::addEdge( Edge* edge )` |
| `adjust` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:798` | `void Edge::adjust()` |
| `advancePosition` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:941` | `bool Node::advancePosition()` |
| `ancestor` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:471` | `Node* GraphWidget::ancestor(Node* vim, Node* v, Node*& defaultAncestor)` |
| `appendChild` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:887` | `void Node::appendChild( Node* child )` |
| `apportion` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:383` | `void GraphWidget::apportion(Node* v, Node*& defaultAncestor)` |
| `boundingRect` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:822` | `QRectF Edge::boundingRect() const` |
| `boundingRect` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:899` | `QRectF Node::boundingRect() const` |
| `calculateForces` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:915` | `void Node::calculateForces()` |
| `contextMenuEvent` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:529` | `void Node::contextMenuEvent( QGraphicsSceneContextMenuEvent* event )` |
| `destNode` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:524` | `Node* Edge::destNode() const` |
| `drawBackground` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:263` | `void GraphWidget::drawBackground( QPainter* painter, const QRectF& rect )` |
| `edges` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:910` | `QVector<Edge*> Node::edges() const` |
| `executeShifts` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:481` | `void GraphWidget::executeShifts(Node* v)` |
| `firstWalk` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:350` | `void GraphWidget::firstWalk(Node* v)` |
| `initNode` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:329` | `void GraphWidget::initNode(Node* v)` |
| `itemChange` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:1007` | `QVariant Node::itemChange( GraphicsItemChange change, const QVariant& value )` |
| `itemMoved` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:198` | `void GraphWidget::itemMoved()` |
| `keyPressEvent` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:204` | `void GraphWidget::keyPressEvent( QKeyEvent* event )` |
| `layout` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:340` | `void GraphWidget::layout(Node* T)` |
| `mouseMoveEvent` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:936` | `void Node::mouseMoveEvent( QGraphicsSceneMouseEvent* event )` |
| `mousePressEvent` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:1026` | `void Node::mousePressEvent( QGraphicsSceneMouseEvent* event )` |
| `mouseReleaseEvent` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:1032` | `void Node::mouseReleaseEvent( QGraphicsSceneMouseEvent* event )` |
| `moveSubtree` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:434` | `void GraphWidget::moveSubtree(Node* wm, Node* wp, double shift)` |
| `nextLeft` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:453` | `Node* GraphWidget::nextLeft(Node* v)` |
| `nextRight` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:462` | `Node* GraphWidget::nextRight(Node* v)` |
| `paint` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:835` | `void Edge::paint( QPainter* painter, const QStyleOptionGraphicsItem*, QWidget* )` |
| `paint` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:959` | `void Node::paint( QPainter *painter, const QStyleOptionGraphicsItem* option, QWidget* )` |
| `removeChild` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:892` | `void Node::removeChild( Node* child )` |
| `resizeEvent` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:251` | `void GraphWidget::resizeEvent( QResizeEvent* event )` |
| `scaleView` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:279` | `void GraphWidget::scaleView( qreal scaleFactor )` |
| `secondWalk` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:496` | `void GraphWidget::secondWalk(Node* v, double m, double depth)` |
| `shape` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:950` | `QPainterPath Node::shape() const` |
| `shuffle` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:288` | `void GraphWidget::shuffle()` |
| `sourceNode` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:519` | `Node* Edge::sourceNode() const` |
| `timerEvent` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:221` | `void GraphWidget::timerEvent( QTimerEvent* event )` |
| `wheelEvent` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:258` | `void GraphWidget::wheelEvent( QWheelEvent* event )` |
| `zoomIn` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:299` | `void GraphWidget::zoomIn()` |
| `zoomOut` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:304` | `void GraphWidget::zoomOut()` |
| `ChangeSessionValue` | function | `client/src/UserInterface/Widgets/SessionTable.cc:211` | `void UserInterface::Widgets::SessionTable::ChangeSessionValue( QString DemonID, int key, QString ...` |
| `NewSessionItem` | function | `client/src/UserInterface/Widgets/SessionTable.cc:82` | `void HavocNamespace::UserInterface::Widgets::SessionTable::NewSessionItem( Util::SessionItem item...` |
| `setupUi` | function | `client/src/UserInterface/Widgets/SessionTable.cc:16` | `void HavocNamespace::UserInterface::Widgets::SessionTable::setupUi(QWidget *Form, QString Teamser...` |
| `updateRow` | function | `client/src/UserInterface/Widgets/SessionTable.cc:220` | `void HavocNamespace::UserInterface::Widgets::SessionTable::updateRow()` |
| `AddScript` | function | `client/src/UserInterface/Widgets/Store.cc:147` | `bool Store::AddScript( QString Path )` |
| `connect` | function | `client/src/UserInterface/Widgets/Store.cc:76` | `QObject::connect(reply, &QNetworkReply::finished, [reply, this]()` |
| `connect` | function | `client/src/UserInterface/Widgets/Store.cc:109` | `QObject::connect(StoreTable, &QTableWidget::itemSelectionChanged, [this]()` |
| `connect` | function | `client/src/UserInterface/Widgets/Store.cc:116` | `QObject::connect(installButton, &QPushButton::clicked, [this]()` |
| `displayData` | function | `client/src/UserInterface/Widgets/Store.cc:134` | `void Store::displayData(int position)` |
| `installScript` | function | `client/src/UserInterface/Widgets/Store.cc:176` | `void Store::installScript(int position)` |
| `retranslateUi` | function | `client/src/UserInterface/Widgets/Store.cc:224` | `void Store::retranslateUi()` |
| `setupUi` | function | `client/src/UserInterface/Widgets/Store.cc:10` | `void Store::setupUi( QWidget* Store)` |
| `AddLoggerText` | function | `client/src/UserInterface/Widgets/Teamserver.cc:31` | `void Teamserver::AddLoggerText( const QString& Text ) const` |
| `retranslateUi` | function | `client/src/UserInterface/Widgets/Teamserver.cc:26` | `void Teamserver::retranslateUi()` |
| `setupUi` | function | `client/src/UserInterface/Widgets/Teamserver.cc:5` | `void Teamserver::setupUi( QWidget* Teamserver )` |
| `NewBottomTab` | function | `client/src/UserInterface/Widgets/TeamserverTabSession.cc:469` | `void UserInterface::Widgets::TeamserverTabSession::NewBottomTab( QWidget* TabWidget, const string...` |
| `NewWidgetTab` | function | `client/src/UserInterface/Widgets/TeamserverTabSession.cc:488` | `void UserInterface::Widgets::TeamserverTabSession::NewWidgetTab( QWidget *TabWidget, const std::s...` |
| `connect` | function | `client/src/UserInterface/Widgets/TeamserverTabSession.cc:121` | `connect( tabWidget->tabBar(), &QTabBar::tabCloseRequested, this, [&]( int index )` |
| `connect` | function | `client/src/UserInterface/Widgets/TeamserverTabSession.cc:141` | `connect( SessionTableWidget->SessionTableWidget, &QTableWidget::doubleClicked, this, [&]( const Q...` |
| `handleDemonContextMenu` | function | `client/src/UserInterface/Widgets/TeamserverTabSession.cc:165` | `void UserInterface::Widgets::TeamserverTabSession::handleDemonContextMenu( const QPoint &pos )` |
| `removeTabSmall` | function | `client/src/UserInterface/Widgets/TeamserverTabSession.cc:509` | `void UserInterface::Widgets::TeamserverTabSession::removeTabSmall( int index ) const` |
| `setupUi` | function | `client/src/UserInterface/Widgets/TeamserverTabSession.cc:27` | `void HavocNamespace::UserInterface::Widgets::TeamserverTabSession::setupUi( QWidget* Page, QStrin...` |
| `base64_encode` | function | `client/src/Util/Base64.cpp:9` | `std::string HavocNamespace::Util::base64_encode(const char* buf, unsigned int bufLen)` |
| `Background` | function | `client/src/Util/ColorText.cpp:50` | `QString HavocNamespace::Util::ColorText::Background(const QString& text)` |
| `Bold` | function | `client/src/Util/ColorText.cpp:91` | `QString HavocNamespace::Util::ColorText::Bold(const QString& text)` |
| `Color` | function | `client/src/Util/ColorText.cpp:45` | `QString HavocNamespace::Util::ColorText::Color(const QString& color, const QString &text)` |
| `Comment` | function | `client/src/Util/ColorText.cpp:59` | `QString HavocNamespace::Util::ColorText::Comment(const QString& text)` |
| `Cyan` | function | `client/src/Util/ColorText.cpp:63` | `QString HavocNamespace::Util::ColorText::Cyan(const QString& text)` |
| `Foreground` | function | `client/src/Util/ColorText.cpp:55` | `QString HavocNamespace::Util::ColorText::Foreground(const QString& text)` |
| `Green` | function | `client/src/Util/ColorText.cpp:67` | `QString HavocNamespace::Util::ColorText::Green(const QString& text)` |
| `Orange` | function | `client/src/Util/ColorText.cpp:71` | `QString HavocNamespace::Util::ColorText::Orange(const QString& text)` |
| `Pink` | function | `client/src/Util/ColorText.cpp:75` | `QString HavocNamespace::Util::ColorText::Pink(const QString& text)` |
| `Purple` | function | `client/src/Util/ColorText.cpp:79` | `QString HavocNamespace::Util::ColorText::Purple(const QString& text)` |
| `Red` | function | `client/src/Util/ColorText.cpp:83` | `QString HavocNamespace::Util::ColorText::Red(const QString& text)` |
| `SetDraculaDark` | function | `client/src/Util/ColorText.cpp:24` | `void HavocNamespace::Util::ColorText::SetDraculaDark()` |
| `SetDraculaLight` | function | `client/src/Util/ColorText.cpp:40` | `void HavocNamespace::Util::ColorText::SetDraculaLight()` |

Next: [SYMBOLS_p3.md](SYMBOLS_p3.md)
