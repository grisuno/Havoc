# Subsystem: Demon

## client/src/Havoc/Demon/CommandOutput.cc
- Layer: infrastructure
- Doc: include <QJsonDocument> include <QJsonArray>  include <Havoc/DemonCmdDispatch.h>  include <UserInterface/Widgets/DemonIn
- Language: cc
- Symbols:
  - `MessageOutput` (function, line 14) `void DispatchOutput::MessageOutput( QString JsonString, const QString& Date = "" ) const`

## client/src/Havoc/Demon/CommandSend.cc
- Layer: infrastructure
- Doc: include <Havoc/DemonCmdDispatch.h> include <Havoc/Packager.hpp> include <Havoc/Connector.hpp>  include <UserInterface/Wi
- Language: cc

## client/src/Havoc/Demon/Commands.cc
- Layer: infrastructure
- Doc: include <Havoc/DemonCmdDispatch.h>  define BEHAVIOR_PROCESS_INJECTION  "Process Injection" define BEHAVIOR_PROCESS_CREAT
- Language: cc
- Symbols:
  - `BEHAVIOR_PROCESS_INJECTION` (macro, line 2)
  - `BEHAVIOR_PROCESS_CREATION` (macro, line 4)
  - `BEHAVIOR_FORK_AND_RUN` (macro, line 5)
  - `BEHAVIOR_API_ONLY` (macro, line 6)
  - `BEHAVIOR_TEAMSERVER` (macro, line 7)
  - `NO_SUBCOMMANDS` (macro, line 8)

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
