# API (page 2 of 8)
Previous: [API.md](API.md)

## client/include/Util/ColorText.h
Depends on: `client/include/global.hpp`
Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`
- `SetDraculaDark` (function) `client/include/Util/ColorText.h:33` `static void SetDraculaDark();`
- `SetDraculaLight` (function) `client/include/Util/ColorText.h:34` `static void SetDraculaLight();`
- `Color` (function) `client/include/Util/ColorText.h:36` `static QString Color(const QString& color, const QString& text);`
- `Background` (function) `client/include/Util/ColorText.h:37` `static QString Background(const QString&);`
- `Foreground` (function) `client/include/Util/ColorText.h:38` `static QString Foreground(const QString&);`
- `Comment` (function) `client/include/Util/ColorText.h:39` `static QString Comment(const QString&);`
- `Cyan` (function) `client/include/Util/ColorText.h:40` `static QString Cyan(const QString&);`
- `Green` (function) `client/include/Util/ColorText.h:41` `static QString Green(const QString&);`
- `Orange` (function) `client/include/Util/ColorText.h:42` `static QString Orange(const QString&);`
- `Pink` (function) `client/include/Util/ColorText.h:43` `static QString Pink(const QString&);`
- `Purple` (function) `client/include/Util/ColorText.h:44` `static QString Purple(const QString&);`
- `Red` (function) `client/include/Util/ColorText.h:45` `static QString Red(const QString&);`
- `Yellow` (function) `client/include/Util/ColorText.h:46` `static QString Yellow(const QString&);`
- `Underline` (function) `client/include/Util/ColorText.h:48` `static QString Underline(const QString& text);`
- `UnderlineBackground` (function) `client/include/Util/ColorText.h:49` `static QString UnderlineBackground(const QString& text);`
- `UnderlineForeground` (function) `client/include/Util/ColorText.h:50` `static QString UnderlineForeground(const QString& text);`
- `UnderlineComment` (function) `client/include/Util/ColorText.h:51` `static QString UnderlineComment(const QString& text);`
- `UnderlineCyan` (function) `client/include/Util/ColorText.h:52` `static QString UnderlineCyan(const QString& text);`
- `UnderlineGreen` (function) `client/include/Util/ColorText.h:53` `static QString UnderlineGreen(const QString& text);`
- `UnderlineOrange` (function) `client/include/Util/ColorText.h:54` `static QString UnderlineOrange(const QString& text);`
- `UnderlinePink` (function) `client/include/Util/ColorText.h:55` `static QString UnderlinePink(const QString& text);`
- `UnderlinePurple` (function) `client/include/Util/ColorText.h:56` `static QString UnderlinePurple(const QString& text);`
- `UnderlineRed` (function) `client/include/Util/ColorText.h:57` `static QString UnderlineRed(const QString& text);`
- `UnderlineYellow` (function) `client/include/Util/ColorText.h:58` `static QString UnderlineYellow(const QString& text);`
- `Bold` (function) `client/include/Util/ColorText.h:60` `static QString Bold(const QString& text);`

## client/include/global.hpp
Depends on: `client/include/External.h`, `client/include/Havoc/Service.hpp`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`
Imported by: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base64.h`, `client/include/Util/ColorText.h`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Main.cc`, `client/src/UserInterface/Dialogs/About.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Dialogs/Listener.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/Store.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/Base64.cpp`, `client/src/global.cc`
- `Export` (function) `client/include/global.hpp:245` `void Export();`

## client/src/Havoc/Connector.cc
Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`
- `Connector` (function) `client/src/Havoc/Connector.cc:7` `Connector::Connector( Util::ConnectionInfo* ConnectionInfo )`
- `connect` (function) `client/src/Havoc/Connector.cc:19` `QObject::connect( Socket, &QWebSocket::binaryMessageReceived, this, [&]( const QByteArray& Message )`
- `connect` (function) `client/src/Havoc/Connector.cc:36` `QObject::connect( Socket, &QWebSocket::connected, this, [&]()`
- `connect` (function) `client/src/Havoc/Connector.cc:44` `QObject::connect( Socket, &QWebSocket::disconnected, this, [&]()`
- `Disconnect` (function) `client/src/Havoc/Connector.cc:56` `bool Connector::Disconnect()`
- `SendLogin` (function) `client/src/Havoc/Connector.cc:72` `void Connector::SendLogin()`
- `SendPackage` (function) `client/src/Havoc/Connector.cc:93` `void Connector::SendPackage( Util::Packager::PPackage Package )`

## client/src/Havoc/DBManger/DBManager.cc
Depends on: `client/include/Havoc/DBManager/DBManager.hpp`
- `DBManager` (function) `client/src/Havoc/DBManger/DBManager.cc:9` `DBManager::DBManager( const QString& FilePath, int OpenFlag )`
- `createNewDatabase` (function) `client/src/Havoc/DBManger/DBManager.cc:32` `bool DBManager::createNewDatabase()`

## client/src/Havoc/DBManger/Scripts.cc
Depends on: `client/include/Havoc/DBManager/DBManager.hpp`
- `AddScript` (function) `client/src/Havoc/DBManger/Scripts.cc:3` `bool HavocNamespace::HavocSpace::DBManager::AddScript( QString Path )`
- `RemoveScript` (function) `client/src/Havoc/DBManger/Scripts.cc:20` `bool HavocNamespace::HavocSpace::DBManager::RemoveScript( QString Path )`
- `CheckScript` (function) `client/src/Havoc/DBManger/Scripts.cc:41` `bool HavocNamespace::HavocSpace::DBManager::CheckScript( QString Path )`
- `GetScripts` (function) `client/src/Havoc/DBManger/Scripts.cc:63` `vector<QString> HavocNamespace::HavocSpace::DBManager::GetScripts()`

## client/src/Havoc/DBManger/Teamserver.cc
Depends on: `client/include/Havoc/DBManager/DBManager.hpp`
- `addTeamserverInfo` (function) `client/src/Havoc/DBManger/Teamserver.cc:6` `bool HavocSpace::DBManager::addTeamserverInfo( const Util::ConnectionInfo& connection )`
- `checkTeamserverExists` (function) `client/src/Havoc/DBManger/Teamserver.cc:31` `bool HavocSpace::DBManager::checkTeamserverExists( const QString& ProfileName )`
- `removeTeamserverInfo` (function) `client/src/Havoc/DBManger/Teamserver.cc:55` `bool HavocSpace::DBManager::removeTeamserverInfo( const QString& ProfileName )`
- `listTeamservers` (function) `client/src/Havoc/DBManger/Teamserver.cc:75` `vector<Util::ConnectionInfo> HavocSpace::DBManager::listTeamservers()`
- `removeAllTeamservers` (function) `client/src/Havoc/DBManger/Teamserver.cc:104` `bool HavocSpace::DBManager::removeAllTeamservers()`

## client/src/Havoc/Demon/CommandOutput.cc
Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`
- `MessageOutput` (function) `client/src/Havoc/Demon/CommandOutput.cc:15` `void DispatchOutput::MessageOutput( QString JsonString, const QString& Date = "" ) const`

## client/src/Havoc/Demon/ConsoleInput.cc
Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
- `is_number` (function) `client/src/Havoc/Demon/ConsoleInput.cc:28` `static bool is_number( const std::string& s )`
- `compareQString` (function) `client/src/Havoc/Demon/ConsoleInput.cc:183` `bool compareQString(const QString &a, const QString &b)`
- `DemonCommands` (function) `client/src/Havoc/Demon/ConsoleInput.cc:188` `DemonCommands::DemonCommands( )`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:611` `SEND( Execute.Checkin( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "task" ...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:654` `SEND( Execute.Job( TaskID, "list", "0" ) )
            }
            else if ( InputCommands[ 1 ]...`
- `CONSOLE_ERROR` (function) `client/src/Havoc/Demon/ConsoleInput.cc:667` `CONSOLE_ERROR( "Not enough arguments" )
                }
            }
            else if ( Inp...`
- `CONSOLE_ERROR` (function) `client/src/Havoc/Demon/ConsoleInput.cc:681` `CONSOLE_ERROR( "Not enough arguments" )
                }
            }
            else if ( Inp...`
- `CONSOLE_ERROR` (function) `client/src/Havoc/Demon/ConsoleInput.cc:700` `CONSOLE_ERROR( "Sub command not found: " + InputCommands[ 1 ] )
            }
        }
        e...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1138` `SEND( Execute.DllInject( TaskID, Pid, Path, Args ) )
            }
            else if ( InputCom...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1166` `SEND( Execute.DllSpawn( TaskID, Path, Args.toLocal8Bit() ) )

            }
        }
        els...`
- `CONSOLE_ERROR` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1225` `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...`
- `CONSOLE_ERROR` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1260` `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1452` `SEND( Execute.Token( TaskID, "clear", "" ) )
            }
            else if ( InputCommands[ 1...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1459` `SEND( Execute.Token( TaskID, "getuid", "" ) )
            }
            else if ( InputCommands[ ...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1607` `SEND( Execute.Socket( TaskID, "rportfwd list", "" ) )
            }
            else if ( InputCo...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1620` `SEND( Execute.Socket( TaskID, "rportfwd remove", InputCommands[ 2 ] ) )
            }
           ...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1627` `SEND( Execute.Socket( TaskID, "rportfwd clear", "" ) )
            }

        }
        else if (...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1654` `SEND( Execute.Socket( TaskID, "socks add", Port ) )
            }
            else if ( InputComm...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1661` `SEND( Execute.Socket( TaskID, "socks list", "" ) )
            }
            else if ( InputComma...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1674` `SEND( Execute.Socket( TaskID, "socks kill", InputCommands[ 2 ] ) )
            }
            else...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1681` `SEND( Execute.Socket( TaskID, "socks clear", "" ) )
            }

        }
        else if ( In...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1698` `SEND( Execute.Transfer( TaskID, "list", "" ) )
            }
            else if ( InputCommands[...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1711` `SEND( Execute.Transfer( TaskID, "stop", InputCommands[ 2 ] ) )
            }
            else if ...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1724` `SEND( Execute.Transfer( TaskID, "resume", InputCommands[ 2 ] ) )
            }
            else i...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1737` `SEND( Execute.Transfer( TaskID, "remove", InputCommands[ 2 ] ) )
            }
        }
        ...`
- `CONSOLE_ERROR` (function) `client/src/Havoc/Demon/ConsoleInput.cc:1830` `CONSOLE_ERROR( "Not enough arguments" )
            }
        }
        else if ( InputCommands[ ...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:2037` `SEND( Execute.Screenshot( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "net...`
- `CONSOLE_ERROR` (function) `client/src/Havoc/Demon/ConsoleInput.cc:2131` `CONSOLE_ERROR( "No sub command specified" )
            }
        }
        else if ( InputComman...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:2184` `SEND( Execute.Pivot( TaskID, Command, Param ) )
            }
        }
        else if ( InputCo...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:2192` `SEND( Execute.Luid( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "klist" ) ...`
- `SEND` (function) `client/src/Havoc/Demon/ConsoleInput.cc:2324` `SEND( Execute.Exit( TaskID, "thread" ) )
            }
            else if ( InputCommands[ 1 ].c...`

## client/src/Havoc/Havoc.cc
Depends on: `client/include/Havoc/CmdLine.hpp`, `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`
- `Havoc` (function) `client/src/Havoc/Havoc.cc:7` `HavocSpace::Havoc::Havoc( QMainWindow* w )`
- `Init` (function) `client/src/Havoc/Havoc.cc:22` `void HavocSpace::Havoc::Init( int argc, char** argv )`
- `singleShot` (function) `client/src/Havoc/Havoc.cc:70` `QTimer::singleShot( 10, [&]()`
- `Start` (function) `client/src/Havoc/Havoc.cc:85` `void HavocSpace::Havoc::Start()`
- `Exit` (function) `client/src/Havoc/Havoc.cc:93` `void HavocSpace::Havoc::Exit()`

## client/src/Havoc/Packager.cc
Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
- `DecodePackage` (function) `client/src/Havoc/Packager.cc:63` `Util::Packager::PPackage Packager::DecodePackage( const QString& Package )`
- `foreach` (function) `client/src/Havoc/Packager.cc:90` `foreach( const QString& key, BodyObject[ "Info" ].toObject().keys() )`
- `EncodePackage` (function) `client/src/Havoc/Packager.cc:106` `QJsonDocument Packager::EncodePackage( Util::Packager::Package Package )`
- `DispatchInitConnection` (function) `client/src/Havoc/Packager.cc:166` `bool Packager::DispatchInitConnection( Util::Packager::PPackage Package )`
- `DispatchListener` (function) `client/src/Havoc/Packager.cc:220` `bool Packager::DispatchListener( Util::Packager::PPackage Package )`
- `DispatchChat` (function) `client/src/Havoc/Packager.cc:483` `bool Packager::DispatchChat( Util::Packager::PPackage Package)`
- `DispatchGate` (function) `client/src/Havoc/Packager.cc:532` `bool Packager::DispatchGate( Util::Packager::PPackage Package )`
- `DispatchSession` (function) `client/src/Havoc/Packager.cc:581` `bool Packager::DispatchSession( Util::Packager::PPackage Package )`
- `DispatchService` (function) `client/src/Havoc/Packager.cc:865` `bool Packager::DispatchService( Util::Packager::PPackage Package )`
- `DispatchTeamserver` (function) `client/src/Havoc/Packager.cc:961` `bool Packager::DispatchTeamserver( Util::Packager::PPackage Package )`
- `setTeamserver` (function) `client/src/Havoc/Packager.cc:987` `void Packager::setTeamserver( QString Name )`

## client/src/Havoc/PythonApi/Event.cc
Depends on: `client/include/Havoc/PythonApi/Event.h`
- `EventClass_dealloc` (function) `client/src/Havoc/PythonApi/Event.cc:70` `void EventClass_dealloc( PPyEvents self )`
- `EventClass_new` (function) `client/src/Havoc/PythonApi/Event.cc:77` `PyObject* EventClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `EventClass_init` (function) `client/src/Havoc/PythonApi/Event.cc:86` `int EventClass_init( PPyEvents self, PyObject *args, PyObject *kwds )`
- `EventClass_OnNewSession` (function) `client/src/Havoc/PythonApi/Event.cc:96` `PyObject* EventClass_OnNewSession( PPyEvents self, PyObject *args )`
- `EventClass_OnDemonOutput` (function) `client/src/Havoc/PythonApi/Event.cc:112` `PyObject* EventClass_OnDemonOutput( PPyEvents self, PyObject *args )`

## client/src/Havoc/PythonApi/Havoc.cc
Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/global.hpp`
- `PyInit_Havoc` (function) `client/src/Havoc/PythonApi/Havoc.cc:45` `PyMODINIT_FUNC PythonAPI::Havoc::PyInit_Havoc( void )`
- `Load` (function) `client/src/Havoc/PythonApi/Havoc.cc:67` `PyObject* PythonAPI::Havoc::Core::Load( PyObject *self, PyObject *args )`
- `GetListeners` (function) `client/src/Havoc/PythonApi/Havoc.cc:89` `PyObject* PythonAPI::Havoc::Core::GetListeners( PyObject *self, PyObject *args )`
- `GetAgents` (function) `client/src/Havoc/PythonApi/Havoc.cc:105` `PyObject* PythonAPI::Havoc::Core::GetAgents( PyObject *self, PyObject *args )`
- `GetDemons` (function) `client/src/Havoc/PythonApi/Havoc.cc:123` `PyObject* PythonAPI::Havoc::Core::GetDemons( PyObject *self, PyObject *args )`
- `GeneratePayload` (function) `client/src/Havoc/PythonApi/Havoc.cc:139` `PyObject* PythonAPI::Havoc::Core::GeneratePayload( PyObject *self, PyObject *args, PyObject* kwar...`
- `RegisterCommand` (function) `client/src/Havoc/PythonApi/Havoc.cc:188` `PyObject* PythonAPI::Havoc::Core::RegisterCommand( PyObject *self, PyObject *args, PyObject* kwar...` -- RegisterCommand( PyFunction: func, Module: str, Command: str, Description: str, Behavior: int, Usage: str, Example...
- `RegisterModule` (function) `client/src/Havoc/PythonApi/Havoc.cc:265` `PyObject* PythonAPI::Havoc::Core::RegisterModule( PyObject *self, PyObject *args )` -- RegisterModule( Name: str, Description: str, Behavior: str, Usage: str, Example: str, Options: str )
- `RegisterCallback` (function) `client/src/Havoc/PythonApi/Havoc.cc:321` `PyObject* PythonAPI::Havoc::Core::RegisterCallback( PyObject *self, PyObject *args )`

## client/src/Havoc/PythonApi/HavocUi.cc
Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`
- `CreateTab` (function) `client/src/Havoc/PythonApi/HavocUi.cc:46` `PyObject* PythonAPI::HavocUI::Core::CreateTab(PyObject *self, PyObject *args)`
- `connect` (function) `client/src/Havoc/PythonApi/HavocUi.cc:76` `QMainWindow::connect( tupleCallback, &QAction::triggered, HavocX::HavocUserInterface->HavocWindow...`
- `MessageBox` (function) `client/src/Havoc/PythonApi/HavocUi.cc:84` `PyObject* PythonAPI::HavocUI::Core::MessageBox(PyObject *self, PyObject *args)`
- `ErrorMessage` (function) `client/src/Havoc/PythonApi/HavocUi.cc:108` `PyObject* PythonAPI::HavocUI::Core::ErrorMessage(PyObject *self, PyObject *args)`
- `QuestionDialog` (function) `client/src/Havoc/PythonApi/HavocUi.cc:123` `PyObject* PythonAPI::HavocUI::Core::QuestionDialog(PyObject *self, PyObject *args)`
- `InputDialog` (function) `client/src/Havoc/PythonApi/HavocUi.cc:141` `PyObject* PythonAPI::HavocUI::Core::InputDialog(PyObject *self, PyObject *args)`
- `OpenFileDialog` (function) `client/src/Havoc/PythonApi/HavocUi.cc:154` `PyObject* PythonAPI::HavocUI::Core::OpenFileDialog(PyObject *self, PyObject *args)`
- `SaveFileDialog` (function) `client/src/Havoc/PythonApi/HavocUi.cc:167` `PyObject* PythonAPI::HavocUI::Core::SaveFileDialog(PyObject *self, PyObject *args)`
- `ColorDialog` (function) `client/src/Havoc/PythonApi/HavocUi.cc:180` `PyObject* PythonAPI::HavocUI::Core::ColorDialog(PyObject *self, PyObject *args)`
- `ProgressDialog` (function) `client/src/Havoc/PythonApi/HavocUi.cc:192` `PyObject* PythonAPI::HavocUI::Core::ProgressDialog(PyObject *self, PyObject *args)`
- `connect` (function) `client/src/Havoc/PythonApi/HavocUi.cc:212` `QMainWindow::connect( timer, &QTimer::timeout, HavocX::HavocUserInterface->HavocWindow, [callable...`
- `connect` (function) `client/src/Havoc/PythonApi/HavocUi.cc:231` `QMainWindow::connect( cancelButton, &QPushButton::clicked, HavocX::HavocUserInterface->HavocWindo...`
- `PyInit_HavocUI` (function) `client/src/Havoc/PythonApi/HavocUi.cc:241` `PyMODINIT_FUNC PythonAPI::HavocUI::PyInit_HavocUI(void)`

## client/src/Havoc/PythonApi/PyAgentClass.cc
Depends on: `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`
- `AgentClass_dealloc` (function) `client/src/Havoc/PythonApi/PyAgentClass.cc:69` `void AgentClass_dealloc( PPyAgentClass self )`
- `AgentClass_new` (function) `client/src/Havoc/PythonApi/PyAgentClass.cc:76` `PyObject* AgentClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `AgentClass_init` (function) `client/src/Havoc/PythonApi/PyAgentClass.cc:85` `int AgentClass_init( PPyAgentClass self, PyObject *args, PyObject *kwds )`
- `AgentClass_ConsoleWrite` (function) `client/src/Havoc/PythonApi/PyAgentClass.cc:112` `PyObject* AgentClass_ConsoleWrite( PPyAgentClass self, PyObject *args )`
- `AgentClass_Command` (function) `client/src/Havoc/PythonApi/PyAgentClass.cc:149` `PyObject* AgentClass_Command( PPyAgentClass self, PyObject *args )`

## client/src/Havoc/PythonApi/PyDemonClass.cc
Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`
- `DemonClass_dealloc` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:100` `void DemonClass_dealloc( PPyDemonClass self )`
- `DemonClass_new` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:119` `PyObject* DemonClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `DemonClass_init` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:128` `int DemonClass_init( PPyDemonClass self, PyObject *args, PyObject *kwds )`
- `DemonClass_Shell` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:179` `PyObject* DemonClass_Shell( PPyDemonClass self, PyObject *args )` -- Demon.shell( TaskID: str, ShellCommands: str )
- `DemonClass_InlineExecute` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:200` `PyObject* DemonClass_InlineExecute( PPyDemonClass self, PyObject *args )` -- Demon.InlineExecute( TaskID: str, EntryFunc: str, Path: str, Args: str, Threaded: bool )
- `DemonClass_InlineExecuteGetOutput` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:250` `PyObject* DemonClass_InlineExecuteGetOutput( PPyDemonClass self, PyObject *args )`
- `DemonClass_DotnetInlineExecute` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:312` `PyObject* DemonClass_DotnetInlineExecute( PPyDemonClass self, PyObject *args )` -- Demon.DotnetInlineExecute( TaskID: str, Path: str, Args: str )
- `DemonClass_Command` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:333` `PyObject* DemonClass_Command( PPyDemonClass self, PyObject *args )`
- `DemonClass_CommandGetOutput` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:353` `PyObject* DemonClass_CommandGetOutput( PPyDemonClass self, PyObject *args )`
- `DemonClass_ShellcodeSpawn` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:389` `PyObject* DemonClass_ShellcodeSpawn( PPyDemonClass self, PyObject *args )` -- ShellcodeSpawn( QString TaskID, QString InjectionTechnique, QString TargetArch, QString Path, QString Arguments )
- `DemonClass_DllInject` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:430` `PyObject* DemonClass_DllInject( PPyDemonClass self, PyObject *args )` -- Demon.DllInject( TaskID: str, Pid: str, DllPath: str, DllArgs: str )
- `DemonClass_DllSpawn` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:453` `PyObject* DemonClass_DllSpawn( PPyDemonClass self, PyObject *args )` -- Demon.DllInject( TaskID: str, DllPath: str, DllArgs: str )
- `DemonClass_ProcessCreate` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:491` `PyObject* DemonClass_ProcessCreate( PPyDemonClass self, PyObject *args )` -- Demon.ProcessCreate( TaskID: str App: str, Cmdline: str, Suspended: bool, Piped: bool, Verbose: bool )
- `DemonClass_ConsoleWrite` (function) `client/src/Havoc/PythonApi/PyDemonClass.cc:539` `PyObject* DemonClass_ConsoleWrite( PPyDemonClass self, PyObject *args )` -- Other Methods

## client/src/Havoc/PythonApi/PythonApi.cc
Depends on: `client/include/Havoc/PythonApi/PythonApi.h`
- `Stdout_write` (function) `client/src/Havoc/PythonApi/PythonApi.cc:5` `PyObject* Stdout_write(PyObject* self, PyObject* args)`
- `written` (function) `client/src/Havoc/PythonApi/PythonApi.cc:7` `std::size_t written(0);`
- `Stdout_flush` (function) `client/src/Havoc/PythonApi/PythonApi.cc:22` `PyObject* Stdout_flush(PyObject* self, PyObject* args)`
- `PyInit_emb` (function) `client/src/Havoc/PythonApi/PythonApi.cc:87` `PyMODINIT_FUNC PyInit_emb(void)`
- `set_stdout` (function) `client/src/Havoc/PythonApi/PythonApi.cc:105` `void set_stdout(stdout_write_type write)`
- `reset_stdout` (function) `client/src/Havoc/PythonApi/PythonApi.cc:118` `void reset_stdout()`

## client/src/Havoc/PythonApi/UI/PyDialogClass.cc
Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`
- `DialogClass_dealloc` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:86` `void DialogClass_dealloc( PPyDialogClass self )`
- `DialogClass_new` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:99` `PyObject* DialogClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `DialogClass_init` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:121` `int DialogClass_init( PPyDialogClass self, PyObject *args, PyObject *kwds )`
- `DialogClass_exec` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:155` `PyObject* DialogClass_exec( PPyDialogClass self, PyObject *args )` -- Methods
- `DialogClass_addLabel` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:163` `PyObject* DialogClass_addLabel( PPyDialogClass self, PyObject *args )`
- `DialogClass_addImage` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:177` `PyObject* DialogClass_addImage( PPyDialogClass self, PyObject *args )`
- `DialogClass_addButton` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:193` `PyObject* DialogClass_addButton( PPyDialogClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:212` `QObject::connect(button, &QPushButton::clicked, self->DialogWindow->window, [button_callback]()`
- `DialogClass_addCheckbox` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:219` `PyObject* DialogClass_addCheckbox( PPyDialogClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:241` `QObject::connect(checkbox, &QCheckBox::clicked, self->DialogWindow->window, [checkbox_callback]()`
- `DialogClass_addCombobox` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:248` `PyObject* DialogClass_addCombobox( PPyDialogClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:265` `QObject::connect(comboBox, QOverload<int>::of(&QComboBox::activated), [callable_obj](int index)`
- `DialogClass_addLineedit` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:272` `PyObject* DialogClass_addLineedit( PPyDialogClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:289` `QObject::connect(line, &QLineEdit::editingFinished, self->DialogWindow->window, [line, line_callb...`
- `DialogClass_addCalendar` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:300` `PyObject* DialogClass_addCalendar( PPyDialogClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:317` `QObject::connect(cal, &QCalendarWidget::selectionChanged, self->DialogWindow->window, [cal, cal_c...`
- `DialogClass_addDial` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:329` `PyObject* DialogClass_addDial( PPyDialogClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:345` `QObject::connect(dial, &QDial::valueChanged, self->DialogWindow->window, [cal_callback](long value)`
- `DialogClass_addSlider` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:352` `PyObject* DialogClass_addSlider( PPyDialogClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:374` `QObject::connect(slider, &QSlider::valueChanged, self->DialogWindow->window, [cal_callback](long ...`
- `DialogClass_replaceLabel` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:381` `PyObject* DialogClass_replaceLabel( PPyDialogClass self, PyObject *args )`
- `DialogClass_close` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:405` `PyObject* DialogClass_close( PPyDialogClass self, PyObject *args )`
- `DialogClass_clear` (function) `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:412` `PyObject* DialogClass_clear( PPyDialogClass self, PyObject *args )`

## client/src/Havoc/PythonApi/UI/PyLoggerClass.cc
Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`
- `LoggerClass_dealloc` (function) `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:77` `void LoggerClass_dealloc( PPyLoggerClass self )`
- `LoggerClass_new` (function) `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:86` `PyObject* LoggerClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `LoggerClass_init` (function) `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:95` `int LoggerClass_init( PPyLoggerClass self, PyObject *args, PyObject *kwds )`
- `LoggerClass_setBottomTab` (function) `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:123` `PyObject* LoggerClass_setBottomTab( PPyLoggerClass self, PyObject *args )`
- `LoggerClass_setSmallTab` (function) `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:130` `PyObject* LoggerClass_setSmallTab( PPyLoggerClass self, PyObject *args )`
- `LoggerClass_addText` (function) `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:137` `PyObject* LoggerClass_addText( PPyLoggerClass self, PyObject *args )`
- `LoggerClass_clear` (function) `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:149` `PyObject* LoggerClass_clear( PPyLoggerClass self, PyObject *args )`

## client/src/Havoc/PythonApi/UI/PyTreeClass.cc
Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`
- `TreeClass_dealloc` (function) `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:78` `void TreeClass_dealloc( PPyTreeClass self )`
- `TreeClass_new` (function) `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:91` `PyObject* TreeClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `TreeClass_init` (function) `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:112` `int TreeClass_init( PPyTreeClass self, PyObject *args, PyObject *kwds )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:165` `QObject::connect(self->TreeWindow->tree_view->selectionModel(), &QItemSelectionModel::selectionCh...`
- `TreeClass_setBottomTab` (function) `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:181` `PyObject* TreeClass_setBottomTab( PPyTreeClass self, PyObject *args )`
- `TreeClass_setSmallTab` (function) `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:188` `PyObject* TreeClass_setSmallTab( PPyTreeClass self, PyObject *args )`
- `TreeClass_addRow` (function) `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:195` `PyObject* TreeClass_addRow( PPyTreeClass self, PyObject *args )`
- `TreeClass_setItem` (function) `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:218` `PyObject* TreeClass_setItem( PPyTreeClass self, PyObject *args )`
- `TreeClass_setPanel` (function) `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:233` `PyObject* TreeClass_setPanel( PPyTreeClass self, PyObject *args )`

## client/src/Havoc/PythonApi/UI/PyWidgetClass.cc
Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`
- `WidgetClass_dealloc` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:86` `void WidgetClass_dealloc( PPyWidgetClass self )`
- `WidgetClass_new` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:99` `PyObject* WidgetClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- `WidgetClass_init` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:119` `int WidgetClass_init( PPyWidgetClass self, PyObject *args, PyObject *kwds )`
- `WidgetClass_addLabel` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:149` `PyObject* WidgetClass_addLabel( PPyWidgetClass self, PyObject *args )` -- Methods
- `WidgetClass_addImage` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:163` `PyObject* WidgetClass_addImage( PPyWidgetClass self, PyObject *args )`
- `WidgetClass_setBottomTab` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:179` `PyObject* WidgetClass_setBottomTab( PPyWidgetClass self, PyObject *args )`
- `WidgetClass_setSmallTab` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:186` `PyObject* WidgetClass_setSmallTab( PPyWidgetClass self, PyObject *args )`
- `WidgetClass_addButton` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:193` `PyObject* WidgetClass_addButton( PPyWidgetClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:212` `QObject::connect(button, &QPushButton::clicked, self->WidgetWindow->window, [button_callback]()`
- `WidgetClass_addCheckbox` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:219` `PyObject* WidgetClass_addCheckbox( PPyWidgetClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:241` `QObject::connect(checkbox, &QCheckBox::clicked, self->WidgetWindow->window, [checkbox_callback]()`
- `WidgetClass_addCombobox` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:248` `PyObject* WidgetClass_addCombobox( PPyWidgetClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:265` `QObject::connect(comboBox, QOverload<int>::of(&QComboBox::activated), [callable_obj](int index)`
- `WidgetClass_addLineedit` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:272` `PyObject* WidgetClass_addLineedit( PPyWidgetClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:289` `QObject::connect(line, &QLineEdit::editingFinished, self->WidgetWindow->window, [line, line_callb...`
- `WidgetClass_addCalendar` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:300` `PyObject* WidgetClass_addCalendar( PPyWidgetClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:317` `QObject::connect(cal, &QCalendarWidget::selectionChanged, self->WidgetWindow->window, [cal, cal_c...`
- `WidgetClass_addDial` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:329` `PyObject* WidgetClass_addDial( PPyWidgetClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:345` `QObject::connect(dial, &QDial::valueChanged, self->WidgetWindow->window, [cal_callback](long value)`
- `WidgetClass_addSlider` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:352` `PyObject* WidgetClass_addSlider( PPyWidgetClass self, PyObject *args )`
- `connect` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:374` `QObject::connect(slider, &QSlider::valueChanged, self->WidgetWindow->window, [cal_callback](long ...`
- `WidgetClass_replaceLabel` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:381` `PyObject* WidgetClass_replaceLabel( PPyWidgetClass self, PyObject *args )`
- `WidgetClass_clear` (function) `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:405` `PyObject* WidgetClass_clear( PPyWidgetClass self, PyObject *args )`

## client/src/UserInterface/Dialogs/About.cc
Depends on: `client/include/UserInterface/Dialogs/About.hpp`, `client/include/global.hpp`
- `About` (function) `client/src/UserInterface/Dialogs/About.cc:4` `About::About( QDialog* dialog )`
- `setupUi` (function) `client/src/UserInterface/Dialogs/About.cc:49` `void About::setupUi()`
- `onButtonClose` (function) `client/src/UserInterface/Dialogs/About.cc:54` `void About::onButtonClose()`

## client/src/UserInterface/Dialogs/Connect.cc
Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`
- `setupUi` (function) `client/src/UserInterface/Dialogs/Connect.cc:9` `void HavocNamespace::UserInterface::Dialogs::Connect::setupUi( QDialog* Form )`
- `connect` (function) `client/src/UserInterface/Dialogs/Connect.cc:142` `connect( lineEdit_Name, &QLineEdit::returnPressed, this, [&]()`
- `connect` (function) `client/src/UserInterface/Dialogs/Connect.cc:146` `connect( lineEdit_User, &QLineEdit::returnPressed, this, [&]()`
- `connect` (function) `client/src/UserInterface/Dialogs/Connect.cc:150` `connect( lineEdit_Host, &QLineEdit::returnPressed, this, [&]()`
- `connect` (function) `client/src/UserInterface/Dialogs/Connect.cc:154` `connect( lineEdit_Port, &QLineEdit::returnPressed, this, [&]()`
- `connect` (function) `client/src/UserInterface/Dialogs/Connect.cc:158` `connect( lineEdit_Password, &QLineEdit::returnPressed, this, [&]()`
- `StartDialog` (function) `client/src/UserInterface/Dialogs/Connect.cc:165` `Util::ConnectionInfo HavocNamespace::UserInterface::Dialogs::Connect::StartDialog( bool FromAction )`
- `passDB` (function) `client/src/UserInterface/Dialogs/Connect.cc:229` `void HavocNamespace::UserInterface::Dialogs::Connect::passDB(HavocNamespace::HavocSpace::DBManage...`
- `onButton_Connect` (function) `client/src/UserInterface/Dialogs/Connect.cc:234` `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_Connect()`
- `itemSelected` (function) `client/src/UserInterface/Dialogs/Connect.cc:318` `void HavocNamespace::UserInterface::Dialogs::Connect::itemSelected()`
- `onButton_NewProfile` (function) `client/src/UserInterface/Dialogs/Connect.cc:340` `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_NewProfile()`
- `handleContextMenu` (function) `client/src/UserInterface/Dialogs/Connect.cc:356` `void HavocNamespace::UserInterface::Dialogs::Connect::handleContextMenu( const QPoint &pos )`
- `itemRemove` (function) `client/src/UserInterface/Dialogs/Connect.cc:362` `void HavocNamespace::UserInterface::Dialogs::Connect::itemRemove()`
- `itemsClear` (function) `client/src/UserInterface/Dialogs/Connect.cc:376` `void HavocNamespace::UserInterface::Dialogs::Connect::itemsClear()`

## client/src/UserInterface/Dialogs/Listener.cc
Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`
- `is_number` (function) `client/src/UserInterface/Dialogs/Listener.cc:17` `bool is_number( const std::string& s )`
- `NewListener` (function) `client/src/UserInterface/Dialogs/Listener.cc:24` `NewListener::NewListener( QDialog* Dialog )`
- `connect` (function) `client/src/UserInterface/Dialogs/Listener.cc:331` `QObject::connect( ButtonClose, &QPushButton::clicked, this, [&]()`
- `connect` (function) `client/src/UserInterface/Dialogs/Listener.cc:339` `QObject::connect( ButtonHostsGroupAdd, &QPushButton::clicked, this, [&]()`
- `connect` (function) `client/src/UserInterface/Dialogs/Listener.cc:356` `QObject::connect( ButtonHostsGroupClear, &QPushButton::clicked, this, [&]()`
- `connect` (function) `client/src/UserInterface/Dialogs/Listener.cc:366` `QObject::connect( ButtonUriGroupAdd, &QPushButton::clicked, this, [&]()`
- `connect` (function) `client/src/UserInterface/Dialogs/Listener.cc:377` `QObject::connect( ButtonUriGroupClear, &QPushButton::clicked, this, [&]()`
- `connect` (function) `client/src/UserInterface/Dialogs/Listener.cc:387` `QObject::connect( ButtonHeaderGroupAdd, &QPushButton::clicked, this, [&]()`
- `connect` (function) `client/src/UserInterface/Dialogs/Listener.cc:398` `QObject::connect( ButtonHeaderGroupClear, &QPushButton::clicked, this, [&]()`
- `connect` (function) `client/src/UserInterface/Dialogs/Listener.cc:408` `QObject::connect( ComboPayload, &QComboBox::currentTextChanged, this, [&]( const QString& text )`
- `Start` (function) `client/src/UserInterface/Dialogs/Listener.cc:450` `MapStrStr NewListener::Start( Util::ListenerItem Item, bool Edit )`
- `onButton_Save` (function) `client/src/UserInterface/Dialogs/Listener.cc:817` `void HavocNamespace::UserInterface::Dialogs::NewListener::onButton_Save()`
- `onProxyEnabled` (function) `client/src/UserInterface/Dialogs/Listener.cc:947` `void HavocNamespace::UserInterface::Dialogs::NewListener::onProxyEnabled()`

## client/src/UserInterface/Dialogs/Payload.cc
Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
- `setupUi` (function) `client/src/UserInterface/Dialogs/Payload.cc:17` `void Payload::setupUi( QDialog* Dialog )`
- `connect` (function) `client/src/UserInterface/Dialogs/Payload.cc:124` `connect( ComboFormat, &QComboBox::currentTextChanged, this, [&]( const QString& text )`
- `buttonGenerate` (function) `client/src/UserInterface/Dialogs/Payload.cc:190` `void Payload::buttonGenerate()`

## client/src/UserInterface/HavocUi.cc
Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
- `setupUi` (function) `client/src/UserInterface/HavocUi.cc:28` `void HavocNamespace::UserInterface::HavocUi::setupUi(QMainWindow *Havoc)`
- `OneSecondTick` (function) `client/src/UserInterface/HavocUi.cc:200` `void HavocNamespace::UserInterface::HavocUi::OneSecondTick()`
- `MarkSessionAs` (function) `client/src/UserInterface/HavocUi.cc:205` `void HavocNamespace::UserInterface::HavocUi::MarkSessionAs(HavocNamespace::Util::SessionItem Sess...`
- `UpdateSessionsHealth` (function) `client/src/UserInterface/HavocUi.cc:263` `void HavocNamespace::UserInterface::HavocUi::UpdateSessionsHealth()`
- `retranslateUi` (function) `client/src/UserInterface/HavocUi.cc:361` `void HavocNamespace::UserInterface::HavocUi::retranslateUi(QMainWindow* Havoc ) const`
- `ConnectEvents` (function) `client/src/UserInterface/HavocUi.cc:395` `void HavocNamespace::UserInterface::HavocUi::ConnectEvents()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:399` `QMainWindow::connect( OneSecondTimer, &QTimer::timeout, this, [&]()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:404` `QMainWindow::connect( actionNew_Client, &QAction::triggered, this, []()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:408` `QMainWindow::connect( actionChat, &QAction::triggered, this, [&]()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:422` `QMainWindow::connect( actionDisconnect, &QAction::triggered, this, []()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:431` `QMainWindow::connect( actionExit, &QAction::triggered, this, []()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:435` `QMainWindow::connect( actionSessionsTable, &QAction::triggered, this, []()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:439` `QMainWindow::connect( actionListeners, &QAction::triggered, this, [&]()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:455` `QMainWindow::connect( actionTeamserver, &QAction::triggered, this, [&]()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:467` `QMainWindow::connect( actionStore, &QAction::triggered, this, [&]()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:479` `QMainWindow::connect( actionSessionsGraph, &QAction::triggered, this, [&]()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:483` `QMainWindow::connect( actionLogs, &QAction::triggered, this, [&]()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:498` `QMainWindow::connect( actionLoot, &QAction::triggered, this, [&]()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:506` `QMainWindow::connect( actionGeneratePayload, &QAction::triggered, this, []()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:516` `QMainWindow::connect( actionPythonConsole, &QAction::triggered, this, [&]()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:530` `QMainWindow::connect( actionLoad_Script, &QAction::triggered, this, [&]()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:549` `QMainWindow::connect( actionAbout, &QAction::triggered, this, [&]()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:558` `QMainWindow::connect( actionGithub_Repository, &QAction::triggered, this, []()`
- `connect` (function) `client/src/UserInterface/HavocUi.cc:562` `QMainWindow::connect( actionOpen_Help_Documentation, &QAction::triggered, this, []()`
- `NewBottomTab` (function) `client/src/UserInterface/HavocUi.cc:567` `void HavocNamespace::UserInterface::HavocUi::NewBottomTab(QWidget* TabWidget, const std::string& ...`
- `setDBManager` (function) `client/src/UserInterface/HavocUi.cc:572` `void HavocNamespace::UserInterface::HavocUi::setDBManager(HavocSpace::DBManager* dbManager)`
- `NewTeamserverTab` (function) `client/src/UserInterface/HavocUi.cc:577` `void UserInterface::HavocUi::NewTeamserverTab(HavocNamespace::Util::ConnectionInfo* Connection )`
- `NewTeamserverTab` (function) `client/src/UserInterface/HavocUi.cc:587` `void UserInterface::HavocUi::NewTeamserverTab(QString Name )`
- `NewSmallTab` (function) `client/src/UserInterface/HavocUi.cc:596` `void UserInterface::HavocUi::NewSmallTab(QWidget *TabWidget, const string &TitleName ) const`
- `PythonPrepare` (function) `client/src/UserInterface/HavocUi.cc:602` `void UserInterface::HavocUi::PythonPrepare()`

## client/src/UserInterface/SmallWidgets/EventViewer.cc
Depends on: `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/Util/ColorText.h`
- `setupUi` (function) `client/src/UserInterface/SmallWidgets/EventViewer.cc:4` `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::setupUi(QWidget *Widget)`
- `AppendText` (function) `client/src/UserInterface/SmallWidgets/EventViewer.cc:23` `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::AppendText(const QString& Time, co...`

## client/src/UserInterface/Widgets/Chat.cc
Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
- `setupUi` (function) `client/src/UserInterface/Widgets/Chat.cc:11` `void HavocNamespace::UserInterface::Widgets::Chat::setupUi( QWidget *Form )`
- `AppendText` (function) `client/src/UserInterface/Widgets/Chat.cc:63` `void HavocNamespace::UserInterface::Widgets::Chat::AppendText(const QString& Time, const QString&...`
- `AddUserMessage` (function) `client/src/UserInterface/Widgets/Chat.cc:70` `void HavocNamespace::UserInterface::Widgets::Chat::AddUserMessage(const QString Time, QString Use...`
- `AppendFromInput` (function) `client/src/UserInterface/Widgets/Chat.cc:78` `void HavocNamespace::UserInterface::Widgets::Chat::AppendFromInput()`

## client/src/UserInterface/Widgets/DemonInteracted.cc
Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
- `DemonInput` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:16` `DemonInteracted::DemonInput::DemonInput( QWidget* parent ) : QLineEdit( parent )`
- `handleKeyPress` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:21` `bool DemonInteracted::DemonInput::handleKeyPress( QKeyEvent* eventKey )`
- `handleTabKey` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:39` `void DemonInteracted::DemonInput::handleTabKey()`
- `handleUpKey` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:47` `void DemonInteracted::DemonInput::handleUpKey()`
- `handleDownKey` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:67` `void DemonInteracted::DemonInput::handleDownKey()`
- `event` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:78` `bool DemonInteracted::DemonInput::event( QEvent* e )`
- `AddCommand` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:90` `void DemonInteracted::DemonInput::AddCommand( const QString &Command )`
- `setupUi` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:95` `void DemonInteracted::setupUi( QWidget *Form )`
- `AppendFromInput` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:209` `void DemonInteracted::AppendFromInput()`
- `AppendText` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:214` `void DemonInteracted::AppendText( const QString& text )`
- `TaskInfo` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:281` `QString DemonInteracted::TaskInfo( bool Show, QString TaskID, const QString &text ) const`
- `TaskError` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:296` `QString DemonInteracted::TaskError( const QString &text ) const`
- `AppendRaw` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:303` `void UserInterface::Widgets::DemonInteracted::AppendRaw(const QString& text)`
- `AppendNoNL` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:308` `void DemonInteracted::AppendNoNL( const QString &text )`
- `AutoCompleteAdd` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:317` `void DemonInteracted::AutoCompleteAdd( QString text )`
- `AutoCompleteClear` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:326` `void DemonInteracted::AutoCompleteClear()`
- `AutoCompleteAddList` (function) `client/src/UserInterface/Widgets/DemonInteracted.cc:336` `void DemonInteracted::AutoCompleteAddList( QStringList list )`

## client/src/UserInterface/Widgets/FileBrowser.cc
Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`
- `setupUi` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:40` `void FileBrowser::setupUi( QWidget* FileBrowser )`
- `retranslateUi` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:148` `void FileBrowser::retranslateUi()`
- `AddData` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:159` `void FileBrowser::AddData( QJsonDocument JsonData )`
- `TreeAddData` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:234` `void FileBrowser::TreeAddData( FileData Data )`
- `TableAddData` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:239` `void FileBrowser::TableAddData( FileData Data )`
- `onTableDoubleClick` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:276` `void FileBrowser::onTableDoubleClick( int row, int column )`
- `onTreeDoubleClick` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:292` `void FileBrowser::onTreeDoubleClick()`
- `ChangePathAndSendRequest` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:297` `void FileBrowser::ChangePathAndSendRequest( QString Path )`
- `TableClear` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:313` `void FileBrowser::TableClear()`
- `onButtonUp` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:320` `void FileBrowser::onButtonUp()`
- `onTableMenuDownload` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:327` `void FileBrowser::onTableMenuDownload()`
- `onTableContextMenu` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:363` `void FileBrowser::onTableContextMenu( const QPoint &pos )`
- `onTreeContextMenu` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:371` `void FileBrowser::onTreeContextMenu( const QPoint &pos )`
- `onTableMenuMkdir` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:379` `void FileBrowser::onTableMenuMkdir()`
- `onTableMenuReload` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:384` `void FileBrowser::onTableMenuReload()`
- `onTableMenuRemove` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:405` `void FileBrowser::onTableMenuRemove()`
- `onTreeMenuListDrives` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:410` `void FileBrowser::onTreeMenuListDrives()`
- `onTreeMenuMkdir` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:415` `void FileBrowser::onTreeMenuMkdir()`
- `onTreeMenuReload` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:420` `void FileBrowser::onTreeMenuReload()`
- `onTreeMenuRemove` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:425` `void FileBrowser::onTreeMenuRemove()`
- `onInputPath` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:430` `void FileBrowser::onInputPath()`
- `TreeUpdate` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:438` `void FileBrowser::TreeUpdate()`
- `TreeClear` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:500` `void FileBrowser::TreeClear( )`
- `TreeAddDisk` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:523` `void FileBrowser::TreeAddDisk( QString Disk )`
- `TreeAddChildToParent` (function) `client/src/UserInterface/Widgets/FileBrowser.cc:537` `void FileBrowser::TreeAddChildToParent( QString ParentPath, FileBrowserTreeItem* DataItem )`

## client/src/UserInterface/Widgets/ListenersTable.cc
Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
- `setupUi` (function) `client/src/UserInterface/Widgets/ListenersTable.cc:15` `void HavocNamespace::UserInterface::Widgets::ListenersTable::setupUi( QWidget* Form )`
- `ButtonsInit` (function) `client/src/UserInterface/Widgets/ListenersTable.cc:85` `void HavocNamespace::UserInterface::Widgets::ListenersTable::ButtonsInit()`
- `connect` (function) `client/src/UserInterface/Widgets/ListenersTable.cc:87` `QObject::connect( buttonAdd, &QPushButton::clicked, this, [&]()`
- `connect` (function) `client/src/UserInterface/Widgets/ListenersTable.cc:108` `QObject::connect( buttonEdit, &QPushButton::clicked, this, [&]()`
- `connect` (function) `client/src/UserInterface/Widgets/ListenersTable.cc:152` `QObject::connect( buttonRemove,  &QPushButton::clicked, this, [&]()`
- `ListenerAdd` (function) `client/src/UserInterface/Widgets/ListenersTable.cc:178` `void HavocNamespace::UserInterface::Widgets::ListenersTable::ListenerAdd( Util::ListenerItem item...`
- `setDBManager` (function) `client/src/UserInterface/Widgets/ListenersTable.cc:284` `void HavocNamespace::UserInterface::Widgets::ListenersTable::setDBManager( HavocSpace::DBManager*...`
- `CreateNewPackage` (function) `client/src/UserInterface/Widgets/ListenersTable.cc:289` `Util::Packager::Package UserInterface::Widgets::ListenersTable::CreateNewPackage( int EventID, ma...`
- `ListenerEdit` (function) `client/src/UserInterface/Widgets/ListenersTable.cc:312` `void UserInterface::Widgets::ListenersTable::ListenerEdit( Util::ListenerItem item ) const`
- `ListenerRemove` (function) `client/src/UserInterface/Widgets/ListenersTable.cc:323` `void UserInterface::Widgets::ListenersTable::ListenerRemove( QString ListenerName ) const`
- `ListenerError` (function) `client/src/UserInterface/Widgets/ListenersTable.cc:357` `void UserInterface::Widgets::ListenersTable::ListenerError( QString ListenerName, QString Error )...`


Next: [API_p3.md](API_p3.md)
