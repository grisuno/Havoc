# Subsystem: Demon

## client/src/Havoc/Demon/CommandOutput.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `MessageOutput` (function, line 15) `void DispatchOutput::MessageOutput( QString JsonString, const QString& Date = "" ) const`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`

## client/src/Havoc/Demon/CommandSend.cc
- Doc: TODO: refactor this
- Layer: infrastructure
- Language: cc
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/Base64.h`

## client/src/Havoc/Demon/Commands.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `BEHAVIOR_PROCESS_INJECTION` (macro, line 3) `#define BEHAVIOR_PROCESS_INJECTION`
  - `BEHAVIOR_PROCESS_CREATION` (macro, line 4) `#define BEHAVIOR_PROCESS_CREATION`
  - `BEHAVIOR_FORK_AND_RUN` (macro, line 5) `#define BEHAVIOR_FORK_AND_RUN`
  - `BEHAVIOR_API_ONLY` (macro, line 6) `#define BEHAVIOR_API_ONLY`
  - `BEHAVIOR_TEAMSERVER` (macro, line 7) `#define BEHAVIOR_TEAMSERVER`
  - `NO_SUBCOMMANDS` (macro, line 9) `#define NO_SUBCOMMANDS`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`

## client/src/Havoc/Demon/ConsoleInput.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `is_number` (function, line 28) `static bool is_number( const std::string& s )`
  - `compareQString` (function, line 183) `bool compareQString(const QString &a, const QString &b)`
  - `DemonCommands` (function, line 188) `DemonCommands::DemonCommands( )`
  - `SEND` (function, line 611) `SEND( Execute.Checkin( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "task" ...`
  - `SEND` (function, line 654) `SEND( Execute.Job( TaskID, "list", "0" ) )
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
  - `SEND` (function, line 1138) `SEND( Execute.DllInject( TaskID, Pid, Path, Args ) )
            }
            else if ( InputCom...`
  - `SEND` (function, line 1166) `SEND( Execute.DllSpawn( TaskID, Path, Args.toLocal8Bit() ) )

            }
        }
        els...`
  - `CONSOLE_ERROR` (function, line 1225) `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...`
  - `CONSOLE_ERROR` (function, line 1260) `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...`
  - `SEND` (function, line 1452) `SEND( Execute.Token( TaskID, "clear", "" ) )
            }
            else if ( InputCommands[ 1...`
  - `SEND` (function, line 1459) `SEND( Execute.Token( TaskID, "getuid", "" ) )
            }
            else if ( InputCommands[ ...`
  - `SEND` (function, line 1607) `SEND( Execute.Socket( TaskID, "rportfwd list", "" ) )
            }
            else if ( InputCo...`
  - `SEND` (function, line 1620) `SEND( Execute.Socket( TaskID, "rportfwd remove", InputCommands[ 2 ] ) )
            }
           ...`
  - `SEND` (function, line 1627) `SEND( Execute.Socket( TaskID, "rportfwd clear", "" ) )
            }

        }
        else if (...`
  - `SEND` (function, line 1654) `SEND( Execute.Socket( TaskID, "socks add", Port ) )
            }
            else if ( InputComm...`
  - `SEND` (function, line 1661) `SEND( Execute.Socket( TaskID, "socks list", "" ) )
            }
            else if ( InputComma...`
  - `SEND` (function, line 1674) `SEND( Execute.Socket( TaskID, "socks kill", InputCommands[ 2 ] ) )
            }
            else...`
  - `SEND` (function, line 1681) `SEND( Execute.Socket( TaskID, "socks clear", "" ) )
            }

        }
        else if ( In...`
  - `SEND` (function, line 1698) `SEND( Execute.Transfer( TaskID, "list", "" ) )
            }
            else if ( InputCommands[...`
  - `SEND` (function, line 1711) `SEND( Execute.Transfer( TaskID, "stop", InputCommands[ 2 ] ) )
            }
            else if ...`
  - `SEND` (function, line 1724) `SEND( Execute.Transfer( TaskID, "resume", InputCommands[ 2 ] ) )
            }
            else i...`
  - `SEND` (function, line 1737) `SEND( Execute.Transfer( TaskID, "remove", InputCommands[ 2 ] ) )
            }
        }
        ...`
  - `CONSOLE_ERROR` (function, line 1830) `CONSOLE_ERROR( "Not enough arguments" )
            }
        }
        else if ( InputCommands[ ...`
  - `SEND` (function, line 2037) `SEND( Execute.Screenshot( TaskID ) )
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
  - `SEND` (function, line 2192) `SEND( Execute.Luid( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "klist" ) ...`
  - `SEND` (function, line 2324) `SEND( Execute.Exit( TaskID, "thread" ) )
            }
            else if ( InputCommands[ 1 ].c...`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
