# Subsystem: Demon

## client/src/Havoc/Demon/CommandOutput.cc
- Layer: infrastructure
- Doc: include <QJsonDocument> include <QJsonArray>  include <Havoc/DemonCmdDispatch.h>  include <UserInterface/Widgets/DemonIn
- Language: cc
- Symbols:
  - `MessageOutput` (function, line 14) `void DispatchOutput::MessageOutput( QString JsonString, const QString& Date = "" ) const`
  - `PyObject_CallFunctionObjArgs` (function, line 44) `PyObject_CallFunctionObjArgs( HavocX::callbackMessage, arglist, NULL );`
  - `Py_XDECREF` (function, line 45) `Py_XDECREF( HavocX::callbackMessage );`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`

## client/src/Havoc/Demon/CommandSend.cc
- Layer: infrastructure
- Doc: include <Havoc/DemonCmdDispatch.h> include <Havoc/Packager.hpp> include <Havoc/Connector.hpp>  include <UserInterface/Wi
- Language: cc
- Symbols:
  - `NewPackageCommand` (function, line 41) `NewPackageCommand( this->DemonCommandInstance->Teamserver, Body );`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/Base64.h`

## client/src/Havoc/Demon/Commands.cc
- Layer: infrastructure
- Doc: include <Havoc/DemonCmdDispatch.h>  define BEHAVIOR_PROCESS_INJECTION  "Process Injection" define BEHAVIOR_PROCESS_CREAT
- Language: cc
- Symbols:
  - `BEHAVIOR_PROCESS_INJECTION` (macro, line 2) `#define BEHAVIOR_PROCESS_INJECTION`
  - `BEHAVIOR_PROCESS_CREATION` (macro, line 4) `#define BEHAVIOR_PROCESS_CREATION`
  - `BEHAVIOR_FORK_AND_RUN` (macro, line 5) `#define BEHAVIOR_FORK_AND_RUN`
  - `BEHAVIOR_API_ONLY` (macro, line 6) `#define BEHAVIOR_API_ONLY`
  - `BEHAVIOR_TEAMSERVER` (macro, line 7) `#define BEHAVIOR_TEAMSERVER`
  - `NO_SUBCOMMANDS` (macro, line 8) `#define NO_SUBCOMMANDS`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`

## client/src/Havoc/Demon/ConsoleInput.cc
- Layer: infrastructure
- Doc: include <global.hpp>  include <Havoc/DemonCmdDispatch.h> include <UserInterface/Widgets/DemonInteracted.h> include <Util
- Language: cc
- Symbols:
  - `is_number` (function, line 27) `static bool is_number( const std::string& s )`
  - `compareQString` (function, line 182) `bool compareQString(const QString &a, const QString &b)`
  - `DemonCommands` (function, line 187) `DemonCommands::DemonCommands( )`
  - `SEND` (function, line 611) `SEND( Execute.Checkin( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "task" ...`
  - `SEND` (function, line 653) `SEND( Execute.Job( TaskID, "list", "0" ) )
            }
            else if ( InputCommands[ 1 ]...`
  - `CONSOLE_ERROR` (function, line 667) `CONSOLE_ERROR( "Not enough arguments" )
                }
            }
            else if ( Inp...`
  - `CONSOLE_ERROR` (function, line 681) `CONSOLE_ERROR( "Not enough arguments" )
                }
            }
            else if ( Inp...`
  - `CONSOLE_ERROR` (function, line 700) `CONSOLE_ERROR( "Sub command not found: " + InputCommands[ 1 ] )
            }
        }
        e...`
  - `SEND` (function, line 1137) `SEND( Execute.DllInject( TaskID, Pid, Path, Args ) )
            }
            else if ( InputCom...`
  - `SEND` (function, line 1165) `SEND( Execute.DllSpawn( TaskID, Path, Args.toLocal8Bit() ) )

            }
        }
        els...`
  - `CONSOLE_ERROR` (function, line 1225) `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...`
  - `CONSOLE_ERROR` (function, line 1260) `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...`
  - `SEND` (function, line 1451) `SEND( Execute.Token( TaskID, "clear", "" ) )
            }
            else if ( InputCommands[ 1...`
  - `SEND` (function, line 1458) `SEND( Execute.Token( TaskID, "getuid", "" ) )
            }
            else if ( InputCommands[ ...`
  - `SEND` (function, line 1606) `SEND( Execute.Socket( TaskID, "rportfwd list", "" ) )
            }
            else if ( InputCo...`
  - `SEND` (function, line 1619) `SEND( Execute.Socket( TaskID, "rportfwd remove", InputCommands[ 2 ] ) )
            }
           ...`
  - `SEND` (function, line 1626) `SEND( Execute.Socket( TaskID, "rportfwd clear", "" ) )
            }

        }
        else if (...`
  - `SEND` (function, line 1653) `SEND( Execute.Socket( TaskID, "socks add", Port ) )
            }
            else if ( InputComm...`
  - `SEND` (function, line 1660) `SEND( Execute.Socket( TaskID, "socks list", "" ) )
            }
            else if ( InputComma...`
  - `SEND` (function, line 1673) `SEND( Execute.Socket( TaskID, "socks kill", InputCommands[ 2 ] ) )
            }
            else...`
  - `SEND` (function, line 1680) `SEND( Execute.Socket( TaskID, "socks clear", "" ) )
            }

        }
        else if ( In...`
  - `SEND` (function, line 1697) `SEND( Execute.Transfer( TaskID, "list", "" ) )
            }
            else if ( InputCommands[...`
  - `SEND` (function, line 1710) `SEND( Execute.Transfer( TaskID, "stop", InputCommands[ 2 ] ) )
            }
            else if ...`
  - `SEND` (function, line 1723) `SEND( Execute.Transfer( TaskID, "resume", InputCommands[ 2 ] ) )
            }
            else i...`
  - `SEND` (function, line 1736) `SEND( Execute.Transfer( TaskID, "remove", InputCommands[ 2 ] ) )
            }
        }
        ...`
  - `CONSOLE_ERROR` (function, line 1830) `CONSOLE_ERROR( "Not enough arguments" )
            }
        }
        else if ( InputCommands[ ...`
  - `SEND` (function, line 2036) `SEND( Execute.Screenshot( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "net...`
  - `CONSOLE_ERROR` (function, line 2131) `CONSOLE_ERROR( "No sub command specified" )
            }
        }
        else if ( InputComman...`
  - `SEND` (function, line 2184) `SEND( Execute.Pivot( TaskID, Command, Param ) )
            }
        }
        else if ( InputCo...`
  - `SEND` (function, line 2191) `SEND( Execute.Luid( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "klist" ) ...`
  - `SEND` (function, line 2323) `SEND( Execute.Exit( TaskID, "thread" ) )
            }
            else if ( InputCommands[ 1 ].c...`
  - `snprintf` (function, line 24) `std::snprintf( buf.get(), size, format.c_str(), args ... );`
  - `string` (function, line 25) `return std::string( buf.get(), buf.get() + size - 1 );`
  - `QString` (function, line 109) `InputCommands << QString(parsed.c_str());`
  - `debug` (function, line 377) `spdlog::debug( "check registered modules" );`
  - `sort` (function, line 528) `std::sort(commandOutput.begin(), commandOutput.end(), compareQString);`
  - `filecontent` (function, line 1291) `QFile filecontent("/tmp/TextEdit-dump.txt");`
  - `current_path` (function, line 2429) `std::filesystem::current_path( Command.Path );`
  - `PyTuple_SetItem` (function, line 2434) `PyTuple_SetItem( FuncArgs, 0, PyUnicode_FromString( this->DemonID.toStdString().c_str() ) );`
  - `PyErr_PrintEx` (function, line 2450) `PyErr_PrintEx(0);`
  - `PyErr_Clear` (function, line 2451) `PyErr_Clear();`
  - `Py_CLEAR` (function, line 2453) `Py_CLEAR( FuncArgs );`
  - `PrintModuleCachedMessages` (function, line 2461) `PrintModuleCachedMessages();`
  - `PyErr_SetString` (function, line 2517) `PyErr_SetString( PyExc_TypeError, "a callable is required" );`
  - `info` (function, line 2618) `spdlog::info("show help for command");`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
