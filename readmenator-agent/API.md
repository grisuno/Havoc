# API

## client/include/Havoc/CmdLine.hpp

### cast `public:
            static Target cast(const Source &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:46`

### cast `public:
            static Target cast(const Source &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:59`

### cast `public:
            static std::string cast(const Source &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:67`

### cast `public:
            static Target cast(const std::string &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:77`

### lexical_cast `Target lexical_cast(const Source &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:98`

### demangle `static inline std::string demangle(const std::string &name)`
- Defined: `client/include/Havoc/CmdLine.hpp:102`

### readable_typename `template <class T>
        std::string readable_typename()`
- Defined: `client/include/Havoc/CmdLine.hpp:111`

### default_value `template <class T>
        std::string default_value(T def)`
- Defined: `client/include/Havoc/CmdLine.hpp:117`

### cmdline_error `public:
        cmdline_error(const std::string &msg): msg(msg)`
- Defined: `client/include/Havoc/CmdLine.hpp:135`

### what `const char *what() const throw()`
- Defined: `client/include/Havoc/CmdLine.hpp:138`

### operator `T operator()(const std::string &str)`
- Defined: `client/include/Havoc/CmdLine.hpp:145`

### range_reader `range_reader(const T &low, const T &high): low(low), high(high)`
- Defined: `client/include/Havoc/CmdLine.hpp:152`

### operator `T operator()(const std::string &s) const`
- Defined: `client/include/Havoc/CmdLine.hpp:153`

### range `template <class T>
    range_reader<T> range(const T &low, const T &high)`
- Defined: `client/include/Havoc/CmdLine.hpp:161`

### operator `T operator()(const std::string &s)`
- Defined: `client/include/Havoc/CmdLine.hpp:170`

### add `void add(const T &v)`
- Defined: `client/include/Havoc/CmdLine.hpp:176`

### oneof `template <class T>
    oneof_reader<T> oneof(T a1)`
- Defined: `client/include/Havoc/CmdLine.hpp:180`

### oneof `template <class T>
    oneof_reader<T> oneof(T a1, T a2)`
- Defined: `client/include/Havoc/CmdLine.hpp:188`

### oneof `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3)`
- Defined: `client/include/Havoc/CmdLine.hpp:197`

### oneof `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4)`
- Defined: `client/include/Havoc/CmdLine.hpp:207`

### oneof `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5)`
- Defined: `client/include/Havoc/CmdLine.hpp:218`

### oneof `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6)`
- Defined: `client/include/Havoc/CmdLine.hpp:230`

### oneof `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7)`
- Defined: `client/include/Havoc/CmdLine.hpp:243`

### oneof `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8)`
- Defined: `client/include/Havoc/CmdLine.hpp:257`

### oneof `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9)`
- Defined: `client/include/Havoc/CmdLine.hpp:272`

### oneof `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9...`
- Defined: `client/include/Havoc/CmdLine.hpp:288`

### parser `public:
        parser()`
- Defined: `client/include/Havoc/CmdLine.hpp:309`

### add `void add(const std::string &name,
                 char short_name=0,
                 const std:...`
- Defined: `client/include/Havoc/CmdLine.hpp:317`

### add `template <class T>
        void add(const std::string &name,
                 char short_name=0,
...`
- Defined: `client/include/Havoc/CmdLine.hpp:325`

### add `void add(const std::string &name,
                 char short_name=0,
                 const std:...`
- Defined: `client/include/Havoc/CmdLine.hpp:336`

### footer `void footer(const std::string &f)`
- Defined: `client/include/Havoc/CmdLine.hpp:346`

### set_program_name `void set_program_name(const std::string &name)`
- Defined: `client/include/Havoc/CmdLine.hpp:350`

### exist `bool exist(const std::string &name) const`
- Defined: `client/include/Havoc/CmdLine.hpp:354`

### get `template <class T>
        const T &get(const std::string &name) const`
- Defined: `client/include/Havoc/CmdLine.hpp:359`

### rest `const std::vector<std::string> &rest() const`
- Defined: `client/include/Havoc/CmdLine.hpp:367`

### parse `bool parse(const std::string &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:371`

### parse `bool parse(const std::vector<std::string> &args)`
- Defined: `client/include/Havoc/CmdLine.hpp:413`

### parse `bool parse(int argc, const char * const argv[])`
- Defined: `client/include/Havoc/CmdLine.hpp:423`

### parse_check `void parse_check(const std::string &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:524`

### parse_check `void parse_check(const std::vector<std::string> &args)`
- Defined: `client/include/Havoc/CmdLine.hpp:530`

### parse_check `void parse_check(int argc, char *argv[])`
- Defined: `client/include/Havoc/CmdLine.hpp:536`

### error `std::string error() const`
- Defined: `client/include/Havoc/CmdLine.hpp:542`

### error_full `std::string error_full() const`
- Defined: `client/include/Havoc/CmdLine.hpp:546`

### usage `std::string usage() const`
- Defined: `client/include/Havoc/CmdLine.hpp:553`

### check `private:

        void check(int argc, bool ok)`
- Defined: `client/include/Havoc/CmdLine.hpp:584`

### set_option `void set_option(const std::string &name)`
- Defined: `client/include/Havoc/CmdLine.hpp:598`

### set_option `void set_option(const std::string &name, const std::string &value)`
- Defined: `client/include/Havoc/CmdLine.hpp:609`

### option_without_value `public:
            option_without_value(const std::string &name,
                               ...`
- Defined: `client/include/Havoc/CmdLine.hpp:639`

### has_value `bool has_value() const`
- Defined: `client/include/Havoc/CmdLine.hpp:646`

### set `bool set()`
- Defined: `client/include/Havoc/CmdLine.hpp:648`

### set `bool set(const std::string &)`
- Defined: `client/include/Havoc/CmdLine.hpp:653`

### has_set `bool has_set() const`
- Defined: `client/include/Havoc/CmdLine.hpp:657`

### valid `bool valid() const`
- Defined: `client/include/Havoc/CmdLine.hpp:661`

### must `bool must() const`
- Defined: `client/include/Havoc/CmdLine.hpp:665`

### name `const std::string &name() const`
- Defined: `client/include/Havoc/CmdLine.hpp:669`

### short_name `char short_name() const`
- Defined: `client/include/Havoc/CmdLine.hpp:673`

### description `const std::string &description() const`
- Defined: `client/include/Havoc/CmdLine.hpp:677`

### short_description `std::string short_description() const`
- Defined: `client/include/Havoc/CmdLine.hpp:681`

### option_with_value `public:
            option_with_value(const std::string &name,
                              char...`
- Defined: `client/include/Havoc/CmdLine.hpp:695`

### get `const T &get() const`
- Defined: `client/include/Havoc/CmdLine.hpp:706`

### has_value `bool has_value() const`
- Defined: `client/include/Havoc/CmdLine.hpp:710`

### set `bool set()`
- Defined: `client/include/Havoc/CmdLine.hpp:712`

### set `bool set(const std::string &value)`
- Defined: `client/include/Havoc/CmdLine.hpp:716`

### has_set `bool has_set() const`
- Defined: `client/include/Havoc/CmdLine.hpp:727`

### valid `bool valid() const`
- Defined: `client/include/Havoc/CmdLine.hpp:731`

### must `bool must() const`
- Defined: `client/include/Havoc/CmdLine.hpp:736`

### name `const std::string &name() const`
- Defined: `client/include/Havoc/CmdLine.hpp:740`

### short_name `char short_name() const`
- Defined: `client/include/Havoc/CmdLine.hpp:744`

### description `const std::string &description() const`
- Defined: `client/include/Havoc/CmdLine.hpp:748`

### short_description `std::string short_description() const`
- Defined: `client/include/Havoc/CmdLine.hpp:752`

### full_description `protected:
            std::string full_description(const std::string &desc)`
- Defined: `client/include/Havoc/CmdLine.hpp:756`

### option_with_value_with_reader `public:
            option_with_value_with_reader(const std::string &name,
                      ...`
- Defined: `client/include/Havoc/CmdLine.hpp:779`

### read `private:
            T read(const std::string &s)`
- Defined: `client/include/Havoc/CmdLine.hpp:788`

## client/include/UserInterface/Widgets/SessionGraph.hpp

### type `int type() const override`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:52`

### type `int type() const override`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:153`

## client/src/Havoc/Connector.cc

### Connector `Connector::Connector( Util::ConnectionInfo* ConnectionInfo )`
- Defined: `client/src/Havoc/Connector.cc:6`
- Doc: include <Havoc/Connector.hpp> include <Havoc/Havoc.hpp> include <QCryptographicHash> include <QMap> include <QBuffer>

### connect `QObject::connect( Socket, &QWebSocket::binaryMessageReceived, this, [&]( const QByteArray& Message )`
- Defined: `client/src/Havoc/Connector.cc:18`

### connect `QObject::connect( Socket, &QWebSocket::connected, this, [&]()`
- Defined: `client/src/Havoc/Connector.cc:35`

### connect `QObject::connect( Socket, &QWebSocket::disconnected, this, [&]()`
- Defined: `client/src/Havoc/Connector.cc:43`

### Disconnect `bool Connector::Disconnect()`
- Defined: `client/src/Havoc/Connector.cc:55`

### SendLogin `void Connector::SendLogin()`
- Defined: `client/src/Havoc/Connector.cc:71`

### SendPackage `void Connector::SendPackage( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Connector.cc:92`

## client/src/Havoc/DBManger/DBManager.cc

### DBManager `DBManager::DBManager( const QString& FilePath, int OpenFlag )`
- Defined: `client/src/Havoc/DBManger/DBManager.cc:8`

### createNewDatabase `bool DBManager::createNewDatabase()`
- Defined: `client/src/Havoc/DBManger/DBManager.cc:31`

## client/src/Havoc/DBManger/Scripts.cc

### AddScript `bool HavocNamespace::HavocSpace::DBManager::AddScript( QString Path )`
- Defined: `client/src/Havoc/DBManger/Scripts.cc:2`
- Doc: include <Havoc/DBManager/DBManager.hpp>

### RemoveScript `bool HavocNamespace::HavocSpace::DBManager::RemoveScript( QString Path )`
- Defined: `client/src/Havoc/DBManger/Scripts.cc:19`

### CheckScript `bool HavocNamespace::HavocSpace::DBManager::CheckScript( QString Path )`
- Defined: `client/src/Havoc/DBManger/Scripts.cc:40`

### GetScripts `vector<QString> HavocNamespace::HavocSpace::DBManager::GetScripts()`
- Defined: `client/src/Havoc/DBManger/Scripts.cc:62`

## client/src/Havoc/DBManger/Teamserver.cc

### addTeamserverInfo `bool HavocSpace::DBManager::addTeamserverInfo( const Util::ConnectionInfo& connection )`
- Defined: `client/src/Havoc/DBManger/Teamserver.cc:5`

### checkTeamserverExists `bool HavocSpace::DBManager::checkTeamserverExists( const QString& ProfileName )`
- Defined: `client/src/Havoc/DBManger/Teamserver.cc:30`

### removeTeamserverInfo `bool HavocSpace::DBManager::removeTeamserverInfo( const QString& ProfileName )`
- Defined: `client/src/Havoc/DBManger/Teamserver.cc:54`

### listTeamservers `vector<Util::ConnectionInfo> HavocSpace::DBManager::listTeamservers()`
- Defined: `client/src/Havoc/DBManger/Teamserver.cc:74`

### removeAllTeamservers `bool HavocSpace::DBManager::removeAllTeamservers()`
- Defined: `client/src/Havoc/DBManger/Teamserver.cc:103`

## client/src/Havoc/Demon/CommandOutput.cc

### MessageOutput `void DispatchOutput::MessageOutput( QString JsonString, const QString& Date = "" ) const`
- Defined: `client/src/Havoc/Demon/CommandOutput.cc:14`

## client/src/Havoc/Demon/ConsoleInput.cc

### is_number `static bool is_number( const std::string& s )`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:27`

### compareQString `bool compareQString(const QString &a, const QString &b)`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:182`

### DemonCommands `DemonCommands::DemonCommands( )`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:187`

### SEND `SEND( Execute.Checkin( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "task" ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:611`

### SEND `SEND( Execute.Job( TaskID, "list", "0" ) )
            }
            else if ( InputCommands[ 1 ]...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:653`

### CONSOLE_ERROR `CONSOLE_ERROR( "Not enough arguments" )
                }
            }
            else if ( Inp...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:667`

### CONSOLE_ERROR `CONSOLE_ERROR( "Not enough arguments" )
                }
            }
            else if ( Inp...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:681`

### CONSOLE_ERROR `CONSOLE_ERROR( "Sub command not found: " + InputCommands[ 1 ] )
            }
        }
        e...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:700`

### SEND `SEND( Execute.DllInject( TaskID, Pid, Path, Args ) )
            }
            else if ( InputCom...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1137`

### SEND `SEND( Execute.DllSpawn( TaskID, Path, Args.toLocal8Bit() ) )

            }
        }
        els...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1165`

### CONSOLE_ERROR `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1225`

### CONSOLE_ERROR `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1260`

### SEND `SEND( Execute.Token( TaskID, "clear", "" ) )
            }
            else if ( InputCommands[ 1...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1451`

### SEND `SEND( Execute.Token( TaskID, "getuid", "" ) )
            }
            else if ( InputCommands[ ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1458`

### SEND `SEND( Execute.Socket( TaskID, "rportfwd list", "" ) )
            }
            else if ( InputCo...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1606`

### SEND `SEND( Execute.Socket( TaskID, "rportfwd remove", InputCommands[ 2 ] ) )
            }
           ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1619`

### SEND `SEND( Execute.Socket( TaskID, "rportfwd clear", "" ) )
            }

        }
        else if (...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1626`

### SEND `SEND( Execute.Socket( TaskID, "socks add", Port ) )
            }
            else if ( InputComm...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1653`

### SEND `SEND( Execute.Socket( TaskID, "socks list", "" ) )
            }
            else if ( InputComma...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1660`

### SEND `SEND( Execute.Socket( TaskID, "socks kill", InputCommands[ 2 ] ) )
            }
            else...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1673`

### SEND `SEND( Execute.Socket( TaskID, "socks clear", "" ) )
            }

        }
        else if ( In...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1680`

### SEND `SEND( Execute.Transfer( TaskID, "list", "" ) )
            }
            else if ( InputCommands[...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1697`

### SEND `SEND( Execute.Transfer( TaskID, "stop", InputCommands[ 2 ] ) )
            }
            else if ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1710`

### SEND `SEND( Execute.Transfer( TaskID, "resume", InputCommands[ 2 ] ) )
            }
            else i...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1723`

### SEND `SEND( Execute.Transfer( TaskID, "remove", InputCommands[ 2 ] ) )
            }
        }
        ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1736`

### CONSOLE_ERROR `CONSOLE_ERROR( "Not enough arguments" )
            }
        }
        else if ( InputCommands[ ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1830`

### SEND `SEND( Execute.Screenshot( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "net...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:2036`

### CONSOLE_ERROR `CONSOLE_ERROR( "No sub command specified" )
            }
        }
        else if ( InputComman...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:2131`

### SEND `SEND( Execute.Pivot( TaskID, Command, Param ) )
            }
        }
        else if ( InputCo...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:2184`

### SEND `SEND( Execute.Luid( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "klist" ) ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:2191`

### SEND `SEND( Execute.Exit( TaskID, "thread" ) )
            }
            else if ( InputCommands[ 1 ].c...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:2323`

## client/src/Havoc/Havoc.cc

### Havoc `HavocSpace::Havoc::Havoc( QMainWindow* w )`
- Defined: `client/src/Havoc/Havoc.cc:6`
- Doc: include <QTimer>

### Init `void HavocSpace::Havoc::Init( int argc, char** argv )`
- Defined: `client/src/Havoc/Havoc.cc:21`

### singleShot `QTimer::singleShot( 10, [&]()`
- Defined: `client/src/Havoc/Havoc.cc:70`

### Start `void HavocSpace::Havoc::Start()`
- Defined: `client/src/Havoc/Havoc.cc:84`

### Exit `void HavocSpace::Havoc::Exit()`
- Defined: `client/src/Havoc/Havoc.cc:92`

## client/src/Havoc/Packager.cc

### DecodePackage `Util::Packager::PPackage Packager::DecodePackage( const QString& Package )`
- Defined: `client/src/Havoc/Packager.cc:62`

### foreach `foreach( const QString& key, BodyObject[ "Info" ].toObject().keys() )`
- Defined: `client/src/Havoc/Packager.cc:90`

### EncodePackage `QJsonDocument Packager::EncodePackage( Util::Packager::Package Package )`
- Defined: `client/src/Havoc/Packager.cc:105`

### DispatchInitConnection `bool Packager::DispatchInitConnection( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Packager.cc:165`

### DispatchListener `bool Packager::DispatchListener( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Packager.cc:219`

### DispatchChat `bool Packager::DispatchChat( Util::Packager::PPackage Package)`
- Defined: `client/src/Havoc/Packager.cc:482`

### DispatchGate `bool Packager::DispatchGate( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Packager.cc:531`

### DispatchSession `bool Packager::DispatchSession( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Packager.cc:580`

### case `case ( int ) Commands::CONSOLE_MESSAGE:

                            if ( QByteArray::fromBase64(...`
- Defined: `client/src/Havoc/Packager.cc:720`

### case `case ( int ) Commands::BOF_CALLBACK:

                            if ( QByteArray::fromBase64( Ou...`
- Defined: `client/src/Havoc/Packager.cc:734`

### DispatchService `bool Packager::DispatchService( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Packager.cc:864`

### DispatchTeamserver `bool Packager::DispatchTeamserver( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Packager.cc:960`

### setTeamserver `void Packager::setTeamserver( QString Name )`
- Defined: `client/src/Havoc/Packager.cc:985`

## client/src/Havoc/PythonApi/Event.cc

### EventClass_dealloc `void EventClass_dealloc( PPyEvents self )`
- Defined: `client/src/Havoc/PythonApi/Event.cc:69`

### EventClass_new `PyObject* EventClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/Event.cc:76`

### EventClass_init `int EventClass_init( PPyEvents self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/Event.cc:85`

### EventClass_OnNewSession `PyObject* EventClass_OnNewSession( PPyEvents self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Event.cc:95`
- Doc: Methods

### EventClass_OnDemonOutput `PyObject* EventClass_OnDemonOutput( PPyEvents self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Event.cc:111`

## client/src/Havoc/PythonApi/Havoc.cc

### PyInit_Havoc `PyMODINIT_FUNC PythonAPI::Havoc::PyInit_Havoc( void )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:44`

### Load `PyObject* PythonAPI::Havoc::Core::Load( PyObject *self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:66`

### GetListeners `PyObject* PythonAPI::Havoc::Core::GetListeners( PyObject *self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:88`

### GetAgents `PyObject* PythonAPI::Havoc::Core::GetAgents( PyObject *self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:104`

### GetDemons `PyObject* PythonAPI::Havoc::Core::GetDemons( PyObject *self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:122`

### GeneratePayload `PyObject* PythonAPI::Havoc::Core::GeneratePayload( PyObject *self, PyObject *args, PyObject* kwar...`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:138`

### RegisterCommand `PyObject* PythonAPI::Havoc::Core::RegisterCommand( PyObject *self, PyObject *args, PyObject* kwar...`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:188`
- Doc: RegisterCommand( PyFunction: func, Module: str, Command: str, Description: str, Behavior: int, Usage: str, Example: str 

### RegisterModule `PyObject* PythonAPI::Havoc::Core::RegisterModule( PyObject *self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:265`
- Doc: RegisterModule( Name: str, Description: str, Behavior: str, Usage: str, Example: str, Options: str )

### RegisterCallback `PyObject* PythonAPI::Havoc::Core::RegisterCallback( PyObject *self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:320`

## client/src/Havoc/PythonApi/HavocUi.cc

### CreateTab `PyObject* PythonAPI::HavocUI::Core::CreateTab(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:45`

### connect `QMainWindow::connect( tupleCallback, &QAction::triggered, HavocX::HavocUserInterface->HavocWindow...`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:76`

### MessageBox `PyObject* PythonAPI::HavocUI::Core::MessageBox(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:82`

### ErrorMessage `PyObject* PythonAPI::HavocUI::Core::ErrorMessage(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:107`

### QuestionDialog `PyObject* PythonAPI::HavocUI::Core::QuestionDialog(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:122`

### InputDialog `PyObject* PythonAPI::HavocUI::Core::InputDialog(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:140`

### OpenFileDialog `PyObject* PythonAPI::HavocUI::Core::OpenFileDialog(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:153`

### SaveFileDialog `PyObject* PythonAPI::HavocUI::Core::SaveFileDialog(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:166`

### ColorDialog `PyObject* PythonAPI::HavocUI::Core::ColorDialog(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:179`

### ProgressDialog `PyObject* PythonAPI::HavocUI::Core::ProgressDialog(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:191`

### connect `QMainWindow::connect( timer, &QTimer::timeout, HavocX::HavocUserInterface->HavocWindow, [callable...`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:211`

### connect `QMainWindow::connect( cancelButton, &QPushButton::clicked, HavocX::HavocUserInterface->HavocWindo...`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:231`

### PyInit_HavocUI `PyMODINIT_FUNC PythonAPI::HavocUI::PyInit_HavocUI(void)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:240`

## client/src/Havoc/PythonApi/PyAgentClass.cc

### AgentClass_dealloc `void AgentClass_dealloc( PPyAgentClass self )`
- Defined: `client/src/Havoc/PythonApi/PyAgentClass.cc:68`

### AgentClass_new `PyObject* AgentClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/PyAgentClass.cc:75`

### AgentClass_init `int AgentClass_init( PPyAgentClass self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/PyAgentClass.cc:84`

### AgentClass_ConsoleWrite `PyObject* AgentClass_ConsoleWrite( PPyAgentClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyAgentClass.cc:111`

### AgentClass_Command `PyObject* AgentClass_Command( PPyAgentClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyAgentClass.cc:148`

## client/src/Havoc/PythonApi/PyDemonClass.cc

### DemonClass_dealloc `void DemonClass_dealloc( PPyDemonClass self )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:99`

### DemonClass_new `PyObject* DemonClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:118`

### DemonClass_init `int DemonClass_init( PPyDemonClass self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:127`

### DemonClass_Shell `PyObject* DemonClass_Shell( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:179`
- Doc: Demon.shell( TaskID: str, ShellCommands: str )

### DemonClass_InlineExecute `PyObject* DemonClass_InlineExecute( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:200`
- Doc: Demon.InlineExecute( TaskID: str, EntryFunc: str, Path: str, Args: str, Threaded: bool )

### DemonClass_InlineExecuteGetOutput `PyObject* DemonClass_InlineExecuteGetOutput( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:249`

### DemonClass_DotnetInlineExecute `PyObject* DemonClass_DotnetInlineExecute( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:312`
- Doc: Demon.DotnetInlineExecute( TaskID: str, Path: str, Args: str )

### DemonClass_Command `PyObject* DemonClass_Command( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:332`

### DemonClass_CommandGetOutput `PyObject* DemonClass_CommandGetOutput( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:352`

### DemonClass_ShellcodeSpawn `PyObject* DemonClass_ShellcodeSpawn( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:389`
- Doc: ShellcodeSpawn( QString TaskID, QString InjectionTechnique, QString TargetArch, QString Path, QString Arguments )

### DemonClass_DllInject `PyObject* DemonClass_DllInject( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:430`
- Doc: Demon.DllInject( TaskID: str, Pid: str, DllPath: str, DllArgs: str )

### DemonClass_DllSpawn `PyObject* DemonClass_DllSpawn( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:453`
- Doc: Demon.DllInject( TaskID: str, DllPath: str, DllArgs: str )

### DemonClass_ProcessCreate `PyObject* DemonClass_ProcessCreate( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:491`
- Doc: Demon.ProcessCreate( TaskID: str App: str, Cmdline: str, Suspended: bool, Piped: bool, Verbose: bool )

### DemonClass_ConsoleWrite `PyObject* DemonClass_ConsoleWrite( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:539`
- Doc: Other Methods

## client/src/Havoc/PythonApi/PythonApi.cc

### Stdout_write `PyObject* Stdout_write(PyObject* self, PyObject* args)`
- Defined: `client/src/Havoc/PythonApi/PythonApi.cc:5`

### Stdout_flush `PyObject* Stdout_flush(PyObject* self, PyObject* args)`
- Defined: `client/src/Havoc/PythonApi/PythonApi.cc:21`

### PyInit_emb `PyMODINIT_FUNC PyInit_emb(void)`
- Defined: `client/src/Havoc/PythonApi/PythonApi.cc:86`

### set_stdout `void set_stdout(stdout_write_type write)`
- Defined: `client/src/Havoc/PythonApi/PythonApi.cc:104`

### reset_stdout `void reset_stdout()`
- Defined: `client/src/Havoc/PythonApi/PythonApi.cc:117`

## client/src/Havoc/PythonApi/UI/PyDialogClass.cc

### DialogClass_dealloc `void DialogClass_dealloc( PPyDialogClass self )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:85`

### DialogClass_new `PyObject* DialogClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:98`

### DialogClass_init `int DialogClass_init( PPyDialogClass self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:120`

### DialogClass_exec `PyObject* DialogClass_exec( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:155`
- Doc: Methods

### DialogClass_addLabel `PyObject* DialogClass_addLabel( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:162`

### DialogClass_addImage `PyObject* DialogClass_addImage( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:176`

### DialogClass_addButton `PyObject* DialogClass_addButton( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:192`

### connect `QObject::connect(button, &QPushButton::clicked, self->DialogWindow->window, [button_callback]()`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:212`

### DialogClass_addCheckbox `PyObject* DialogClass_addCheckbox( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:218`

### connect `QObject::connect(checkbox, &QCheckBox::clicked, self->DialogWindow->window, [checkbox_callback]()`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:241`

### DialogClass_addCombobox `PyObject* DialogClass_addCombobox( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:247`

### connect `QObject::connect(comboBox, QOverload<int>::of(&QComboBox::activated), [callable_obj](int index)`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:265`

### DialogClass_addLineedit `PyObject* DialogClass_addLineedit( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:271`

### connect `QObject::connect(line, &QLineEdit::editingFinished, self->DialogWindow->window, [line, line_callb...`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:289`

### DialogClass_addCalendar `PyObject* DialogClass_addCalendar( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:299`

### connect `QObject::connect(cal, &QCalendarWidget::selectionChanged, self->DialogWindow->window, [cal, cal_c...`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:316`

### DialogClass_addDial `PyObject* DialogClass_addDial( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:328`

### connect `QObject::connect(dial, &QDial::valueChanged, self->DialogWindow->window, [cal_callback](long value)`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:345`

### DialogClass_addSlider `PyObject* DialogClass_addSlider( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:351`

### connect `QObject::connect(slider, &QSlider::valueChanged, self->DialogWindow->window, [cal_callback](long ...`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:374`

### DialogClass_replaceLabel `PyObject* DialogClass_replaceLabel( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:380`

### DialogClass_close `PyObject* DialogClass_close( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:404`

### DialogClass_clear `PyObject* DialogClass_clear( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:411`

## client/src/Havoc/PythonApi/UI/PyLoggerClass.cc

### LoggerClass_dealloc `void LoggerClass_dealloc( PPyLoggerClass self )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:76`

### LoggerClass_new `PyObject* LoggerClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:85`

### LoggerClass_init `int LoggerClass_init( PPyLoggerClass self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:94`

### LoggerClass_setBottomTab `PyObject* LoggerClass_setBottomTab( PPyLoggerClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:122`
- Doc: Methods

### LoggerClass_setSmallTab `PyObject* LoggerClass_setSmallTab( PPyLoggerClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:129`

### LoggerClass_addText `PyObject* LoggerClass_addText( PPyLoggerClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:136`

### LoggerClass_clear `PyObject* LoggerClass_clear( PPyLoggerClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:148`

## client/src/Havoc/PythonApi/UI/PyTreeClass.cc

### TreeClass_dealloc `void TreeClass_dealloc( PPyTreeClass self )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:77`

### TreeClass_new `PyObject* TreeClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:90`

### TreeClass_init `int TreeClass_init( PPyTreeClass self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:111`

### connect `QObject::connect(self->TreeWindow->tree_view->selectionModel(), &QItemSelectionModel::selectionCh...`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:164`

### TreeClass_setBottomTab `PyObject* TreeClass_setBottomTab( PPyTreeClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:180`
- Doc: Methods

### TreeClass_setSmallTab `PyObject* TreeClass_setSmallTab( PPyTreeClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:187`

### TreeClass_addRow `PyObject* TreeClass_addRow( PPyTreeClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:194`

### TreeClass_setItem `PyObject* TreeClass_setItem( PPyTreeClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:217`

### TreeClass_setPanel `PyObject* TreeClass_setPanel( PPyTreeClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:232`

## client/src/Havoc/PythonApi/UI/PyWidgetClass.cc

### WidgetClass_dealloc `void WidgetClass_dealloc( PPyWidgetClass self )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:85`

### WidgetClass_new `PyObject* WidgetClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:98`

### WidgetClass_init `int WidgetClass_init( PPyWidgetClass self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:118`

### WidgetClass_addLabel `PyObject* WidgetClass_addLabel( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:149`
- Doc: Methods

### WidgetClass_addImage `PyObject* WidgetClass_addImage( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:162`

### WidgetClass_setBottomTab `PyObject* WidgetClass_setBottomTab( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:178`

### WidgetClass_setSmallTab `PyObject* WidgetClass_setSmallTab( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:185`

### WidgetClass_addButton `PyObject* WidgetClass_addButton( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:192`

### connect `QObject::connect(button, &QPushButton::clicked, self->WidgetWindow->window, [button_callback]()`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:212`

### WidgetClass_addCheckbox `PyObject* WidgetClass_addCheckbox( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:218`

### connect `QObject::connect(checkbox, &QCheckBox::clicked, self->WidgetWindow->window, [checkbox_callback]()`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:241`

### WidgetClass_addCombobox `PyObject* WidgetClass_addCombobox( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:247`

### connect `QObject::connect(comboBox, QOverload<int>::of(&QComboBox::activated), [callable_obj](int index)`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:265`

### WidgetClass_addLineedit `PyObject* WidgetClass_addLineedit( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:271`

### connect `QObject::connect(line, &QLineEdit::editingFinished, self->WidgetWindow->window, [line, line_callb...`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:289`

### WidgetClass_addCalendar `PyObject* WidgetClass_addCalendar( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:299`

### connect `QObject::connect(cal, &QCalendarWidget::selectionChanged, self->WidgetWindow->window, [cal, cal_c...`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:316`

### WidgetClass_addDial `PyObject* WidgetClass_addDial( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:328`

### connect `QObject::connect(dial, &QDial::valueChanged, self->WidgetWindow->window, [cal_callback](long value)`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:345`

### WidgetClass_addSlider `PyObject* WidgetClass_addSlider( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:351`

### connect `QObject::connect(slider, &QSlider::valueChanged, self->WidgetWindow->window, [cal_callback](long ...`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:374`

### WidgetClass_replaceLabel `PyObject* WidgetClass_replaceLabel( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:380`

### WidgetClass_clear `PyObject* WidgetClass_clear( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:404`

## client/src/UserInterface/Dialogs/About.cc

### About `About::About( QDialog* dialog )`
- Defined: `client/src/UserInterface/Dialogs/About.cc:3`
- Doc: include <global.hpp> include <UserInterface/Dialogs/About.hpp>

### setupUi `void About::setupUi()`
- Defined: `client/src/UserInterface/Dialogs/About.cc:48`

### onButtonClose `void About::onButtonClose()`
- Defined: `client/src/UserInterface/Dialogs/About.cc:53`

## client/src/UserInterface/Dialogs/Connect.cc

### setupUi `void HavocNamespace::UserInterface::Dialogs::Connect::setupUi( QDialog* Form )`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:8`
- Doc: include <UserInterface/Dialogs/Connect.hpp>

### connect `connect( lineEdit_Name, &QLineEdit::returnPressed, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:141`

### connect `connect( lineEdit_User, &QLineEdit::returnPressed, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:145`

### connect `connect( lineEdit_Host, &QLineEdit::returnPressed, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:149`

### connect `connect( lineEdit_Port, &QLineEdit::returnPressed, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:153`

### connect `connect( lineEdit_Password, &QLineEdit::returnPressed, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:157`

### StartDialog `Util::ConnectionInfo HavocNamespace::UserInterface::Dialogs::Connect::StartDialog( bool FromAction )`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:164`

### passDB `void HavocNamespace::UserInterface::Dialogs::Connect::passDB(HavocNamespace::HavocSpace::DBManage...`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:228`

### onButton_Connect `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_Connect()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:233`

### itemSelected `void HavocNamespace::UserInterface::Dialogs::Connect::itemSelected()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:317`

### onButton_NewProfile `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_NewProfile()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:339`

### handleContextMenu `void HavocNamespace::UserInterface::Dialogs::Connect::handleContextMenu( const QPoint &pos )`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:355`

### itemRemove `void HavocNamespace::UserInterface::Dialogs::Connect::itemRemove()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:361`

### itemsClear `void HavocNamespace::UserInterface::Dialogs::Connect::itemsClear()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:375`

## client/src/UserInterface/Dialogs/Listener.cc

### is_number `bool is_number( const std::string& s )`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:16`

### NewListener `NewListener::NewListener( QDialog* Dialog )`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:23`

### connect `QObject::connect( ButtonClose, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:331`

### connect `QObject::connect( ButtonHostsGroupAdd, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:338`

### connect `QObject::connect( ButtonHostsGroupClear, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:355`

### connect `QObject::connect( ButtonUriGroupAdd, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:365`

### connect `QObject::connect( ButtonUriGroupClear, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:376`

### connect `QObject::connect( ButtonHeaderGroupAdd, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:386`

### connect `QObject::connect( ButtonHeaderGroupClear, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:397`

### connect `QObject::connect( ComboPayload, &QComboBox::currentTextChanged, this, [&]( const QString& text )`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:407`

### Start `MapStrStr NewListener::Start( Util::ListenerItem Item, bool Edit )`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:449`

### onButton_Save `void HavocNamespace::UserInterface::Dialogs::NewListener::onButton_Save()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:816`

### onProxyEnabled `void HavocNamespace::UserInterface::Dialogs::NewListener::onProxyEnabled()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:946`

## client/src/UserInterface/Dialogs/Payload.cc

### setupUi `void Payload::setupUi( QDialog* Dialog )`
- Defined: `client/src/UserInterface/Dialogs/Payload.cc:16`

### connect `connect( ComboFormat, &QComboBox::currentTextChanged, this, [&]( const QString& text )`
- Defined: `client/src/UserInterface/Dialogs/Payload.cc:124`

### buttonGenerate `void Payload::buttonGenerate()`
- Defined: `client/src/UserInterface/Dialogs/Payload.cc:189`

## client/src/UserInterface/HavocUi.cc

### setupUi `void HavocNamespace::UserInterface::HavocUi::setupUi(QMainWindow *Havoc)`
- Defined: `client/src/UserInterface/HavocUi.cc:27`

### OneSecondTick `void HavocNamespace::UserInterface::HavocUi::OneSecondTick()`
- Defined: `client/src/UserInterface/HavocUi.cc:199`

### MarkSessionAs `void HavocNamespace::UserInterface::HavocUi::MarkSessionAs(HavocNamespace::Util::SessionItem Sess...`
- Defined: `client/src/UserInterface/HavocUi.cc:204`

### UpdateSessionsHealth `void HavocNamespace::UserInterface::HavocUi::UpdateSessionsHealth()`
- Defined: `client/src/UserInterface/HavocUi.cc:261`

### retranslateUi `void HavocNamespace::UserInterface::HavocUi::retranslateUi(QMainWindow* Havoc ) const`
- Defined: `client/src/UserInterface/HavocUi.cc:360`

### ConnectEvents `void HavocNamespace::UserInterface::HavocUi::ConnectEvents()`
- Defined: `client/src/UserInterface/HavocUi.cc:394`

### connect `QMainWindow::connect( OneSecondTimer, &QTimer::timeout, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:398`

### connect `QMainWindow::connect( actionNew_Client, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:403`

### connect `QMainWindow::connect( actionChat, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:407`

### connect `QMainWindow::connect( actionDisconnect, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:421`

### connect `QMainWindow::connect( actionExit, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:430`

### connect `QMainWindow::connect( actionSessionsTable, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:434`

### connect `QMainWindow::connect( actionListeners, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:438`

### connect `QMainWindow::connect( actionTeamserver, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:454`

### connect `QMainWindow::connect( actionStore, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:466`

### connect `QMainWindow::connect( actionSessionsGraph, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:478`

### connect `QMainWindow::connect( actionLogs, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:482`

### connect `QMainWindow::connect( actionLoot, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:497`

### connect `QMainWindow::connect( actionGeneratePayload, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:505`

### connect `QMainWindow::connect( actionPythonConsole, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:515`

### connect `QMainWindow::connect( actionLoad_Script, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:529`

### connect `QMainWindow::connect( actionAbout, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:548`

### connect `QMainWindow::connect( actionGithub_Repository, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:557`

### connect `QMainWindow::connect( actionOpen_Help_Documentation, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:561`

### NewBottomTab `void HavocNamespace::UserInterface::HavocUi::NewBottomTab(QWidget* TabWidget, const std::string& ...`
- Defined: `client/src/UserInterface/HavocUi.cc:566`

### setDBManager `void HavocNamespace::UserInterface::HavocUi::setDBManager(HavocSpace::DBManager* dbManager)`
- Defined: `client/src/UserInterface/HavocUi.cc:571`

### NewTeamserverTab `void UserInterface::HavocUi::NewTeamserverTab(HavocNamespace::Util::ConnectionInfo* Connection )`
- Defined: `client/src/UserInterface/HavocUi.cc:576`

### NewTeamserverTab `void UserInterface::HavocUi::NewTeamserverTab(QString Name )`
- Defined: `client/src/UserInterface/HavocUi.cc:586`

### NewSmallTab `void UserInterface::HavocUi::NewSmallTab(QWidget *TabWidget, const string &TitleName ) const`
- Defined: `client/src/UserInterface/HavocUi.cc:595`

### PythonPrepare `void UserInterface::HavocUi::PythonPrepare()`
- Defined: `client/src/UserInterface/HavocUi.cc:601`

## client/src/UserInterface/SmallWidgets/EventViewer.cc

### setupUi `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::setupUi(QWidget *Widget)`
- Defined: `client/src/UserInterface/SmallWidgets/EventViewer.cc:3`
- Doc: include <UserInterface/SmallWidgets/EventViewer.hpp> include <Util/ColorText.h>

### AppendText `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::AppendText(const QString& Time, co...`
- Defined: `client/src/UserInterface/SmallWidgets/EventViewer.cc:22`

## client/src/UserInterface/Widgets/Chat.cc

### setupUi `void HavocNamespace::UserInterface::Widgets::Chat::setupUi( QWidget *Form )`
- Defined: `client/src/UserInterface/Widgets/Chat.cc:10`
- Doc: include <Havoc/Packager.hpp> include <Havoc/Connector.hpp>

### AppendText `void HavocNamespace::UserInterface::Widgets::Chat::AppendText(const QString& Time, const QString&...`
- Defined: `client/src/UserInterface/Widgets/Chat.cc:62`

### AddUserMessage `void HavocNamespace::UserInterface::Widgets::Chat::AddUserMessage(const QString Time, QString Use...`
- Defined: `client/src/UserInterface/Widgets/Chat.cc:69`

### AppendFromInput `void HavocNamespace::UserInterface::Widgets::Chat::AppendFromInput()`
- Defined: `client/src/UserInterface/Widgets/Chat.cc:77`

## client/src/UserInterface/Widgets/DemonInteracted.cc

### DemonInput `DemonInteracted::DemonInput::DemonInput( QWidget* parent ) : QLineEdit( parent )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:15`

### handleKeyPress `bool DemonInteracted::DemonInput::handleKeyPress( QKeyEvent* eventKey )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:20`

### handleTabKey `void DemonInteracted::DemonInput::handleTabKey()`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:38`

### handleUpKey `void DemonInteracted::DemonInput::handleUpKey()`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:46`

### handleDownKey `void DemonInteracted::DemonInput::handleDownKey()`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:66`

### event `bool DemonInteracted::DemonInput::event( QEvent* e )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:77`

### AddCommand `void DemonInteracted::DemonInput::AddCommand( const QString &Command )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:89`

### setupUi `void DemonInteracted::setupUi( QWidget *Form )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:94`

### AppendFromInput `void DemonInteracted::AppendFromInput()`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:208`

### AppendText `void DemonInteracted::AppendText( const QString& text )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:213`

### TaskInfo `QString DemonInteracted::TaskInfo( bool Show, QString TaskID, const QString &text ) const`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:280`

### TaskError `QString DemonInteracted::TaskError( const QString &text ) const`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:295`

### AppendRaw `void UserInterface::Widgets::DemonInteracted::AppendRaw(const QString& text)`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:302`

### AppendNoNL `void DemonInteracted::AppendNoNL( const QString &text )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:307`

### AutoCompleteAdd `void DemonInteracted::AutoCompleteAdd( QString text )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:316`

### AutoCompleteClear `void DemonInteracted::AutoCompleteClear()`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:325`

### AutoCompleteAddList `void DemonInteracted::AutoCompleteAddList( QStringList list )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:335`

## client/src/UserInterface/Widgets/FileBrowser.cc

### setupUi `void FileBrowser::setupUi( QWidget* FileBrowser )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:39`

### retranslateUi `void FileBrowser::retranslateUi()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:147`

### AddData `void FileBrowser::AddData( QJsonDocument JsonData )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:158`

### TreeAddData `void FileBrowser::TreeAddData( FileData Data )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:233`

### TableAddData `void FileBrowser::TableAddData( FileData Data )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:238`

### onTableDoubleClick `void FileBrowser::onTableDoubleClick( int row, int column )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:275`

### onTreeDoubleClick `void FileBrowser::onTreeDoubleClick()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:290`

### ChangePathAndSendRequest `void FileBrowser::ChangePathAndSendRequest( QString Path )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:296`

### TableClear `void FileBrowser::TableClear()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:312`

### onButtonUp `void FileBrowser::onButtonUp()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:319`

### onTableMenuDownload `void FileBrowser::onTableMenuDownload()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:327`

### onTableContextMenu `void FileBrowser::onTableContextMenu( const QPoint &pos )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:361`

### onTreeContextMenu `void FileBrowser::onTreeContextMenu( const QPoint &pos )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:370`

### onTableMenuMkdir `void FileBrowser::onTableMenuMkdir()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:378`

### onTableMenuReload `void FileBrowser::onTableMenuReload()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:383`

### onTableMenuRemove `void FileBrowser::onTableMenuRemove()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:404`

### onTreeMenuListDrives `void FileBrowser::onTreeMenuListDrives()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:409`

### onTreeMenuMkdir `void FileBrowser::onTreeMenuMkdir()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:414`

### onTreeMenuReload `void FileBrowser::onTreeMenuReload()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:419`

### onTreeMenuRemove `void FileBrowser::onTreeMenuRemove()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:424`

### onInputPath `void FileBrowser::onInputPath()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:429`

### TreeUpdate `void FileBrowser::TreeUpdate()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:437`

### TreeClear `void FileBrowser::TreeClear( )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:499`

### TreeAddDisk `void FileBrowser::TreeAddDisk( QString Disk )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:522`

### TreeAddChildToParent `void FileBrowser::TreeAddChildToParent( QString ParentPath, FileBrowserTreeItem* DataItem )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:536`

## client/src/UserInterface/Widgets/ListenersTable.cc

### setupUi `void HavocNamespace::UserInterface::Widgets::ListenersTable::setupUi( QWidget* Form )`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:14`
- Doc: include <QMap>

### ButtonsInit `void HavocNamespace::UserInterface::Widgets::ListenersTable::ButtonsInit()`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:84`

### connect `QObject::connect( buttonAdd, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:87`

### connect `QObject::connect( buttonEdit, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:107`

### connect `QObject::connect( buttonRemove,  &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:151`

### ListenerAdd `void HavocNamespace::UserInterface::Widgets::ListenersTable::ListenerAdd( Util::ListenerItem item...`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:177`

### setDBManager `void HavocNamespace::UserInterface::Widgets::ListenersTable::setDBManager( HavocSpace::DBManager*...`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:283`

### CreateNewPackage `Util::Packager::Package UserInterface::Widgets::ListenersTable::CreateNewPackage( int EventID, ma...`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:288`

### ListenerEdit `void UserInterface::Widgets::ListenersTable::ListenerEdit( Util::ListenerItem item ) const`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:311`

### ListenerRemove `void UserInterface::Widgets::ListenersTable::ListenerRemove( QString ListenerName ) const`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:322`

### ListenerError `void UserInterface::Widgets::ListenersTable::ListenerError( QString ListenerName, QString Error )...`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:356`

## client/src/UserInterface/Widgets/LootWidget.cc

### ImageLabel `ImageLabel::ImageLabel( QWidget* parent ) : QWidget( parent )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:17`
- Doc: imagelabel.cpp

### resizeEvent `void ImageLabel::resizeEvent( QResizeEvent* event )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:32`

### pixmap `const QPixmap* ImageLabel::pixmap() const`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:38`

### event `bool ImageLabel::event( QEvent* e )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:43`

### keyReleaseEvent `void ImageLabel::keyReleaseEvent( QKeyEvent* event )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:59`

### wheelEvent `void ImageLabel::wheelEvent( QWheelEvent* ev )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:70`

### setPixmap `void ImageLabel::setPixmap( const QPixmap &pixmap )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:77`

### resizeImage `void ImageLabel::resizeImage()`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:84`

### LootWidget `LootWidget::LootWidget()`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:91`

### AddScreenshot `void LootWidget::AddScreenshot( const QString& DemonID, const QString& Name, const QString& Date,...`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:252`

### AddDownload `void LootWidget::AddDownload( const QString &DemonID, const QString &Name, const QString& Size, c...`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:272`

### Reload `void LootWidget::Reload()`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:291`

### onScreenshotTableClick `void LootWidget::onScreenshotTableClick( const QModelIndex &index )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:304`

### onDownloadTableClick `void LootWidget::onDownloadTableClick( const QModelIndex &index )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:328`

### onAgentChange `void LootWidget::onAgentChange( const QString& text )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:333`

### AddSessionSection `void LootWidget::AddSessionSection( const QString& AgentID )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:363`

### onShowChange `void LootWidget::onShowChange( const QString& text )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:376`

### ScreenshotTableAdd `void LootWidget::ScreenshotTableAdd( const QString &Name, const QString &Date )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:388`

### DownloadTableAdd `void LootWidget::DownloadTableAdd( const QString &Name, const QString &Size, const QString &Date )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:413`

### onScreenshotTableCtx `void LootWidget::onScreenshotTableCtx( const QPoint &pos )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:435`

## client/src/UserInterface/Widgets/ProcessList.cc

### setupUi `void HavocNamespace::UserInterface::Widgets::ProcessList::setupUi(QWidget *Widget)`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:4`
- Doc: include <UserInterface/Widgets/ProcessList.hpp> include <UserInterface/Widgets/DemonInteracted.h> include <QClipboard>

### UpdateProcessListJson `void HavocNamespace::UserInterface::Widgets::ProcessList::UpdateProcessListJson( QJsonDocument Pr...`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:200`

### NewTableProcess `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTableProcess(std::map<QString, QStri...`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:230`

### NewTreeProcess `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTreeProcess( std::map<QString,QStrin...`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:278`

### onButton_Refresh `void HavocNamespace::UserInterface::Widgets::ProcessList::onButton_Refresh() const`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:298`

### onTableChange `void HavocNamespace::UserInterface::Widgets::ProcessList::onTableChange()`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:313`

### onTreeChange `void HavocNamespace::UserInterface::Widgets::ProcessList::onTreeChange()`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:329`

### handleTableListMenuContext `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTableListMenuContext( const QPoin...`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:342`

### handleTreeListMenuContext `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTreeListMenuContext( const QPoint...`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:350`

### onActionCopyPID `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionCopyPID()`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:358`

### onActionSetParentProcess `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionSetParentProcess()`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:366`

## client/src/UserInterface/Widgets/PythonScript.cc

### setupUi `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::setupUi(QWidget *WindowWidget)`
- Defined: `client/src/UserInterface/Widgets/PythonScript.cc:7`
- Doc: include <UserInterface/Widgets/PythonScript.hpp> include <Util/ColorText.h> include <QThread> include <thread> include <

### RunCode `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::RunCode( QString code )`
- Defined: `client/src/UserInterface/Widgets/PythonScript.cc:47`

### AppendFromInput `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendFromInput()`
- Defined: `client/src/UserInterface/Widgets/PythonScript.cc:63`

### AppendOutput `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendOutput( QString output )`
- Defined: `client/src/UserInterface/Widgets/PythonScript.cc:75`

## client/src/UserInterface/Widgets/ScriptManager.cc

### SetupUi `void ScriptManager::SetupUi( QWidget *Form )`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:12`

### RetranslateUi `void ScriptManager::RetranslateUi( )`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:103`

### AddScript `bool ScriptManager::AddScript( QString Path )`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:110`

### AddScriptTable `void ScriptManager::AddScriptTable( QString Path )`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:139`

### b_LoadScript `void ScriptManager::b_LoadScript()`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:153`

### menu_ScriptMenu `void ScriptManager::menu_ScriptMenu( const QPoint &pos ) const`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:185`

### ReloadScript `void ScriptManager::ReloadScript() const`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:194`

### RemoveScript `void ScriptManager::RemoveScript() const`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:204`
- Doc: TODO: clear python interpreter and reload every script except the one that got removed

## client/src/UserInterface/Widgets/SessionGraph.cc

### GraphWidget `GraphWidget::GraphWidget( QWidget* parent ) : QGraphicsView( parent )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:27`

### GraphNodeAdd `Node* GraphWidget::GraphNodeAdd( SessionItem Session )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:53`

### GraphNodeRemove `void GraphWidget::GraphNodeRemove( SessionItem Session )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:83`

### GraphPivotNodeAdd `void GraphWidget::GraphPivotNodeAdd( QString AgentID, SessionItem Session )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:104`

### GraphPivotNodeDisconnect `void GraphWidget::GraphPivotNodeDisconnect( QString AgentID )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:146`

### GraphPivotNodeReconnect `void GraphWidget::GraphPivotNodeReconnect( QString ParentAgentID, QString ChildAgentID )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:169`

### itemMoved `void GraphWidget::itemMoved()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:197`

### keyPressEvent `void GraphWidget::keyPressEvent( QKeyEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:203`

### timerEvent `void GraphWidget::timerEvent( QTimerEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:220`

### resizeEvent `void GraphWidget::resizeEvent( QResizeEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:250`

### wheelEvent `void GraphWidget::wheelEvent( QWheelEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:257`

### drawBackground `void GraphWidget::drawBackground( QPainter* painter, const QRectF& rect )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:262`

### scaleView `void GraphWidget::scaleView( qreal scaleFactor )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:278`

### shuffle `void GraphWidget::shuffle()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:287`

### zoomIn `void GraphWidget::zoomIn()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:298`

### zoomOut `void GraphWidget::zoomOut()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:303`

### GraphNodeGet `Node *GraphWidget::GraphNodeGet( QString AgentID )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:308`

### initNode `void GraphWidget::initNode(Node* v)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:329`
- Doc: Initialize node properties for layout

### layout `void GraphWidget::layout(Node* T)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:340`
- Doc: Entry function for layout

### firstWalk `void GraphWidget::firstWalk(Node* v)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:350`
- Doc: Calculate preliminary x-coordinates for all nodes

### apportion `void GraphWidget::apportion(Node* v, Node*& defaultAncestor)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:383`
- Doc: Adjusts spacing between subtrees to ensure they don't overlap

### moveSubtree `void GraphWidget::moveSubtree(Node* wm, Node* wp, double shift)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:434`
- Doc: Move the subtree rooted at wp so it's shifted away from the subtree rooted at wm

### nextLeft `Node* GraphWidget::nextLeft(Node* v)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:453`
- Doc: Helper function to get the leftmost child or thread (left contour)

### nextRight `Node* GraphWidget::nextRight(Node* v)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:462`
- Doc: Helper function to get the rightmost child or thread (right contour)

### ancestor `Node* GraphWidget::ancestor(Node* vim, Node* v, Node*& defaultAncestor)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:471`
- Doc: Get the ancestor of vim that is in the same subtree as v, or return defaultAncestor

### executeShifts `void GraphWidget::executeShifts(Node* v)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:481`
- Doc: Propagate the shifts down to ensure subtrees are moved accordingly

### secondWalk `void GraphWidget::secondWalk(Node* v, double m, double depth)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:496`
- Doc: Walk the tree again to assign final x and y coordinates to each node

### Edge `Edge::Edge( Node* sourceNode, Node* destNode, QColor Color )
    : source( sourceNode ), dest( de...`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:508`
- Doc: ================================================== =================== Edge Class =================== ==================

### sourceNode `Node* Edge::sourceNode() const`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:518`

### destNode `Node* Edge::destNode() const`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:523`

### contextMenuEvent `void Node::contextMenuEvent( QGraphicsSceneContextMenuEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:528`

### adjust `void Edge::adjust()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:797`

### boundingRect `QRectF Edge::boundingRect() const`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:821`

### paint `void Edge::paint( QPainter* painter, const QStyleOptionGraphicsItem*, QWidget* )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:834`

### Color `void Edge::Color( QColor color )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:862`

### Node `Node::Node( NodeItemType NodeType, QString NodeLabel, GraphWidget* graphWidget ) : graph( graphWi...`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:871`
- Doc: ================================================== =================== Node Class =================== ==================

### appendChild `void Node::appendChild( Node* child )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:886`

### removeChild `void Node::removeChild( Node* child )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:891`

### boundingRect `QRectF Node::boundingRect() const`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:898`

### addEdge `void Node::addEdge( Edge* edge )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:903`

### edges `QVector<Edge*> Node::edges() const`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:909`

### calculateForces `void Node::calculateForces()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:914`

### mouseMoveEvent `void Node::mouseMoveEvent( QGraphicsSceneMouseEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:935`

### advancePosition `bool Node::advancePosition()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:940`

### shape `QPainterPath Node::shape() const`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:949`

### paint `void Node::paint( QPainter *painter, const QStyleOptionGraphicsItem* option, QWidget* )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:958`

### itemChange `QVariant Node::itemChange( GraphicsItemChange change, const QVariant& value )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:1006`

### mousePressEvent `void Node::mousePressEvent( QGraphicsSceneMouseEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:1025`

### mouseReleaseEvent `void Node::mouseReleaseEvent( QGraphicsSceneMouseEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:1031`

## client/src/UserInterface/Widgets/SessionTable.cc

### setupUi `void HavocNamespace::UserInterface::Widgets::SessionTable::setupUi(QWidget *Form, QString Teamser...`
- Defined: `client/src/UserInterface/Widgets/SessionTable.cc:15`

### NewSessionItem `void HavocNamespace::UserInterface::Widgets::SessionTable::NewSessionItem( Util::SessionItem item...`
- Defined: `client/src/UserInterface/Widgets/SessionTable.cc:81`

### ChangeSessionValue `void UserInterface::Widgets::SessionTable::ChangeSessionValue( QString DemonID, int key, QString ...`
- Defined: `client/src/UserInterface/Widgets/SessionTable.cc:210`

### updateRow `void HavocNamespace::UserInterface::Widgets::SessionTable::updateRow()`
- Defined: `client/src/UserInterface/Widgets/SessionTable.cc:219`

## client/src/UserInterface/Widgets/Store.cc

### setupUi `void Store::setupUi( QWidget* Store)`
- Defined: `client/src/UserInterface/Widgets/Store.cc:9`
- Doc: include <QScrollBar>

### connect `QObject::connect(reply, &QNetworkReply::finished, [reply, this]()`
- Defined: `client/src/UserInterface/Widgets/Store.cc:75`

### connect `QObject::connect(StoreTable, &QTableWidget::itemSelectionChanged, [this]()`
- Defined: `client/src/UserInterface/Widgets/Store.cc:108`

### connect `QObject::connect(installButton, &QPushButton::clicked, [this]()`
- Defined: `client/src/UserInterface/Widgets/Store.cc:115`

### displayData `void Store::displayData(int position)`
- Defined: `client/src/UserInterface/Widgets/Store.cc:133`

### AddScript `bool Store::AddScript( QString Path )`
- Defined: `client/src/UserInterface/Widgets/Store.cc:146`

### installScript `void Store::installScript(int position)`
- Defined: `client/src/UserInterface/Widgets/Store.cc:175`

### retranslateUi `void Store::retranslateUi()`
- Defined: `client/src/UserInterface/Widgets/Store.cc:223`

## client/src/UserInterface/Widgets/Teamserver.cc

### setupUi `void Teamserver::setupUi( QWidget* Teamserver )`
- Defined: `client/src/UserInterface/Widgets/Teamserver.cc:4`
- Doc: include <QScrollBar>

### retranslateUi `void Teamserver::retranslateUi()`
- Defined: `client/src/UserInterface/Widgets/Teamserver.cc:25`

### AddLoggerText `void Teamserver::AddLoggerText( const QString& Text ) const`
- Defined: `client/src/UserInterface/Widgets/Teamserver.cc:30`

## client/src/UserInterface/Widgets/TeamserverTabSession.cc

### setupUi `void HavocNamespace::UserInterface::Widgets::TeamserverTabSession::setupUi( QWidget* Page, QStrin...`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:26`

### connect `connect( tabWidget->tabBar(), &QTabBar::tabCloseRequested, this, [&]( int index )`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:121`

### connect `connect( SessionTableWidget->SessionTableWidget, &QTableWidget::doubleClicked, this, [&]( const Q...`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:140`

### handleDemonContextMenu `void UserInterface::Widgets::TeamserverTabSession::handleDemonContextMenu( const QPoint &pos )`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:164`

### NewBottomTab `void UserInterface::Widgets::TeamserverTabSession::NewBottomTab( QWidget* TabWidget, const string...`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:467`

### NewWidgetTab `void UserInterface::Widgets::TeamserverTabSession::NewWidgetTab( QWidget *TabWidget, const std::s...`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:487`

### removeTabSmall `void UserInterface::Widgets::TeamserverTabSession::removeTabSmall( int index ) const`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:508`

## client/src/Util/Base64.cpp

### base64_encode `std::string HavocNamespace::Util::base64_encode(const char* buf, unsigned int bufLen)`
- Defined: `client/src/Util/Base64.cpp:8`

## client/src/Util/ColorText.cpp

### SetDraculaDark `void HavocNamespace::Util::ColorText::SetDraculaDark()`
- Defined: `client/src/Util/ColorText.cpp:23`

### SetDraculaLight `void HavocNamespace::Util::ColorText::SetDraculaLight()`
- Defined: `client/src/Util/ColorText.cpp:39`

### Color `QString HavocNamespace::Util::ColorText::Color(const QString& color, const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:44`

### Background `QString HavocNamespace::Util::ColorText::Background(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:49`

### Foreground `QString HavocNamespace::Util::ColorText::Foreground(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:54`

### Comment `QString HavocNamespace::Util::ColorText::Comment(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:58`

### Cyan `QString HavocNamespace::Util::ColorText::Cyan(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:62`

### Green `QString HavocNamespace::Util::ColorText::Green(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:66`

### Orange `QString HavocNamespace::Util::ColorText::Orange(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:70`

### Pink `QString HavocNamespace::Util::ColorText::Pink(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:74`

### Purple `QString HavocNamespace::Util::ColorText::Purple(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:78`

### Red `QString HavocNamespace::Util::ColorText::Red(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:82`

### Yellow `QString HavocNamespace::Util::ColorText::Yellow(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:86`

### Bold `QString HavocNamespace::Util::ColorText::Bold(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:90`

### Underline `QString HavocNamespace::Util::ColorText::Underline(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:94`

### UnderlineBackground `QString HavocNamespace::Util::ColorText::UnderlineBackground(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:98`

### UnderlineForeground `QString HavocNamespace::Util::ColorText::UnderlineForeground(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:102`

### UnderlineComment `QString HavocNamespace::Util::ColorText::UnderlineComment(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:106`

### UnderlineCyan `QString HavocNamespace::Util::ColorText::UnderlineCyan(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:110`

### UnderlineGreen `QString HavocNamespace::Util::ColorText::UnderlineGreen(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:114`

### UnderlineOrange `QString HavocNamespace::Util::ColorText::UnderlineOrange(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:118`

### UnderlinePink `QString HavocNamespace::Util::ColorText::UnderlinePink(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:122`

### UnderlinePurple `QString HavocNamespace::Util::ColorText::UnderlinePurple(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:126`

### UnderlineRed `QString HavocNamespace::Util::ColorText::UnderlineRed(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:130`

### UnderlineYellow `QString HavocNamespace::Util::ColorText::UnderlineYellow(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:134`

## client/src/global.cc

### gen_random `std::string Util::gen_random( const int len )`
- Defined: `client/src/global.cc:30`

### Export `void Util::SessionItem::Export()`
- Defined: `client/src/global.cc:41`

## payloads/Demon/include/common/Native.h

### NtCurrentPeb `__inline struct _PEB * NtCurrentPeb()`
- Defined: `payloads/Demon/include/common/Native.h:7104`
- Doc: 17/3/2011 added

### GetKUserSharedData `__inline struct _KUSER_SHARED_DATA * GetKUserSharedData()`
- Defined: `payloads/Demon/include/common/Native.h:10904`
- Doc: define SHARED_USER_DATA_VA 0x7FFE0000 define USER_SHARED_DATA ((KUSER_SHARED_DATA * const)SHARED_USER_DATA_VA)

### NtGetTickCount `__forceinline ULONG NtGetTickCount()`
- Defined: `payloads/Demon/include/common/Native.h:10906`

## payloads/Demon/include/core/Win32.h

### __attribute__ `typedef struct __attribute__((packed))`
- Defined: `payloads/Demon/include/core/Win32.h:100`

## payloads/Demon/scripts/hash_func.py

### hash_string `def hash_string(string)`
- Defined: `payloads/Demon/scripts/hash_func.py:7`

### hash_coffapi `def hash_coffapi(string)`
- Defined: `payloads/Demon/scripts/hash_func.py:18`

## payloads/Demon/src/Demon.c

### DemonMain `VOID DemonMain( PVOID ModuleInst, PKAYN_ARGS KArgs )`
- Defined: `payloads/Demon/src/Demon.c:34`
- Doc: In DemonMain it should go as followed:  1. Initialize pointer, modules and win32 api 2. Initialize metadata 3. Parse con

### DemonRoutine `_Noreturn
VOID DemonRoutine()`
- Defined: `payloads/Demon/src/Demon.c:63`
- Doc: Main demon routine:  1. Connect to listener 2. Go into tasking routine: A. Sleep Obfuscation. B. Request for the task qu

### DemonMetaData `VOID DemonMetaData( PPACKAGE* MetaData, BOOL Header )`
- Defined: `payloads/Demon/src/Demon.c:95`
- Doc: } if ( Instance->Session.Connected ) { /* Enter tasking routine CommandDispatcher(); } /* Sleep for a while (with encryp

### DemonInit `VOID DemonInit( PVOID ModuleInst, PKAYN_ARGS KArgs )`
- Defined: `payloads/Demon/src/Demon.c:266`

### PUTS `PUTS( "TRANSPORT_HTTP" )
#endif

#ifdef TRANSPORT_SMB
    PUTS( "TRANSPORT_SMB" )
#endif


    /*...`
- Defined: `payloads/Demon/src/Demon.c:290`
- Doc: ifdef TRANSPORT_HTTP

### PRINTF `PRINTF( "Instance DemonID => %x\n", Instance->Session.AgentID )
}

VOID DemonConfig()`
- Defined: `payloads/Demon/src/Demon.c:569`

### PRINTF `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...`
- Defined: `payloads/Demon/src/Demon.c:645`

### PRINTF `PRINTF( " - %ls:%ld\n", Buffer, Temp )

        /* if our host address is longer than 0 then lets...`
- Defined: `payloads/Demon/src/Demon.c:672`

### PRINTF `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...`
- Defined: `payloads/Demon/src/Demon.c:775`

## payloads/Demon/src/asm/Spoof.x64.asm

### Spoof
- Defined: `payloads/Demon/src/asm/Spoof.x64.asm:8`

### fixup
- Defined: `payloads/Demon/src/asm/Spoof.x64.asm:22`

## payloads/Demon/src/asm/Spoof.x86.asm

### _Spoof
- Defined: `payloads/Demon/src/asm/Spoof.x86.asm:8`

## payloads/Demon/src/core/CoffeeLdr.c

### VehDebugger `LONG WINAPI VehDebugger( PEXCEPTION_POINTERS Exception )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:31`

### SymbolIncludesLibrary `BOOL SymbolIncludesLibrary( LPSTR Symbol )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:64`
- Doc: check if the symbol is on the form: __imp_LIBNAME$FUNCNAME

### SymbolIsImport `BOOL SymbolIsImport( LPSTR Symbol )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:80`

### CoffeeProcessSymbol `BOOL CoffeeProcessSymbol( PCOFFEE Coffee, LPSTR SymbolName, UINT16 SymbolType, PVOID* pFuncAddr )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:86`

### CoffeeFunction `VOID CoffeeFunction( PVOID Address, PVOID Argument, SIZE_T Size )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:242`
- Doc: This is our function where we can control/get the return address of it to use it in case of a Veh exception

### PUTS `PUTS( "Finished" )
}

BOOL CoffeeExecuteFunction( PCOFFEE Coffee, PCHAR Function, PVOID Argument,...`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:250`

### CoffeeCleanup `VOID CoffeeCleanup( PCOFFEE Coffee )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:393`

### CoffeeProcessSections `BOOL CoffeeProcessSections( PCOFFEE Coffee )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:423`
- Doc: Process sections relocation and symbols

### CoffeeGetFunMapSize `SIZE_T CoffeeGetFunMapSize( PCOFFEE Coffee )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:602`
- Doc: calculate how many __imp_* function there are

### RemoveCoffeeFromInstance `VOID RemoveCoffeeFromInstance( PCOFFEE Coffee )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:641`

### PUTS `PUTS( "Coffe entry was not found" )
}

VOID CoffeeLdr( PCHAR EntryName, PVOID CoffeeData, PVOID A...`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:668`

### PRINTF `PRINTF( "[EntryName: %s] [CoffeeData: %p] [ArgData: %p] [ArgSize: %ld]\n", EntryName, CoffeeData,...`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:677`

### CoffeeRunnerThread `VOID CoffeeRunnerThread( PCOFFEE_PARAMS Param )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:798`

### CoffeeRunner `VOID CoffeeRunner( PCHAR EntryName, DWORD EntryNameSize, PVOID CoffeeData, SIZE_T CoffeeDataSize,...`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:820`

## payloads/Demon/src/core/Command.c

### CommandDispatcher `VOID CommandDispatcher( VOID )`
- Defined: `payloads/Demon/src/core/Command.c:48`
- Doc: TODO: rewrite this part and move it into the Demon.c file

### PRINTF `PRINTF( "Task => RequestID:[%d : %x] CommandID:[%d : %x] TaskBuffer:[%x : %d]\n", RequestID, Requ...`
- Defined: `payloads/Demon/src/core/Command.c:107`

### PUTS `PUTS( "Out of while loop" )
}

VOID CommandCheckin( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:159`

### CommandSleep `VOID CommandSleep( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:173`

### CommandJob `VOID CommandJob( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:187`

### CommandProc `VOID CommandProc( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:262`

### PUTS `case DEMON_COMMAND_PROC_MODULES: PUTS( "Proc::Modules" )`
- Defined: `payloads/Demon/src/core/Command.c:272`

### PUTS `case DEMON_COMMAND_PROC_GREP: PUTS("Proc::Grep")`
- Defined: `payloads/Demon/src/core/Command.c:336`

### PUTS `case DEMON_COMMAND_PROC_CREATE: PUTS( "Proc::Create" )`
- Defined: `payloads/Demon/src/core/Command.c:422`

### PUTS `case DEMON_COMMAND_PROC_MEMORY: PUTS( "Proc::Memory" )`
- Defined: `payloads/Demon/src/core/Command.c:467`

### PUTS `case DEMON_COMMAND_PROC_KILL: PUTS( "Proc::Kill" )`
- Defined: `payloads/Demon/src/core/Command.c:527`

### CommandProcList `VOID CommandProcList(
    IN PPARSER Parser
)`
- Defined: `payloads/Demon/src/core/Command.c:562`
- Doc: ! get current list of running processes and sends it back to the server.  TODO: refactor this.  @param Parser

### PACKAGE_ERROR_NTSTATUS `PACKAGE_ERROR_NTSTATUS( NtStatus )
    }
}

VOID CommandFS( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:671`

### PUTS `case DEMON_COMMAND_FS_DIR: PUTS( "FS::Dir" )`
- Defined: `payloads/Demon/src/core/Command.c:684`

### PUTS `case DEMON_COMMAND_FS_DOWNLOAD: PUTS( "FS::Download" )`
- Defined: `payloads/Demon/src/core/Command.c:793`

### PRINTF `PRINTF( "FilePath.Buffer[%d]: %ls\n", PathSize, FilePath )

            if ( ! Instance->Win32.Ge...`
- Defined: `payloads/Demon/src/core/Command.c:824`

### PUTS `CleanupDownload:
            PUTS( "CleanupDownload" )

            if ( FileName.Buffer )`
- Defined: `payloads/Demon/src/core/Command.c:865`

### PUTS `case DEMON_COMMAND_FS_UPLOAD: PUTS( "FS::Upload" )`
- Defined: `payloads/Demon/src/core/Command.c:881`

### PUTS `case DEMON_COMMAND_FS_CD: PUTS( "FS::Cd" )`
- Defined: `payloads/Demon/src/core/Command.c:948`

### PUTS `case DEMON_COMMAND_FS_REMOVE: PUTS( "FS::Remove" )`
- Defined: `payloads/Demon/src/core/Command.c:963`

### PUTS `case DEMON_COMMAND_FS_MKDIR: PUTS( "FS::Mkdir" )`
- Defined: `payloads/Demon/src/core/Command.c:993`

### PUTS `case DEMON_COMMAND_FS_COPY: PUTS( "FS::Copy" )`
- Defined: `payloads/Demon/src/core/Command.c:1009`

### PUTS `case DEMON_COMMAND_FS_MOVE: PUTS( "FS::Move" )`
- Defined: `payloads/Demon/src/core/Command.c:1034`

### PUTS `case DEMON_COMMAND_FS_GET_PWD: PUTS( "FS::GetPwd" )`
- Defined: `payloads/Demon/src/core/Command.c:1059`

### PUTS `case DEMON_COMMAND_FS_CAT: PUTS( "FS::Cat" )`
- Defined: `payloads/Demon/src/core/Command.c:1074`

### CommandInlineExecute `VOID CommandInlineExecute( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:1113`

### PUTS `PUTS( "Use default (from config) CoffeeLdr" )

            if ( Instance->Config.Implant.CoffeeTh...`
- Defined: `payloads/Demon/src/core/Command.c:1181`

### CommandInjectDLL `VOID CommandInjectDLL( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:1202`

### CommandSpawnDLL `VOID CommandSpawnDLL( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:1246`

### CommandInjectShellcode `VOID CommandInjectShellcode(
    IN PPARSER Parser
)`
- Defined: `payloads/Demon/src/core/Command.c:1265`

### PRINTF `PRINTF(
        "Injection Args:      \n"
        " - Way     : %d      \n"
        " - Method  :...`
- Defined: `payloads/Demon/src/core/Command.c:1292`

### PUTS `case INJECT_WAY_SPAWN: PUTS( "INJECT_WAY_SPAWN" )`
- Defined: `payloads/Demon/src/core/Command.c:1312`

### PRINTF `PRINTF( "Target spawn process: %ls\n", Spawn )

            /* create process */
            if (...`
- Defined: `payloads/Demon/src/core/Command.c:1319`

### PUTS `case INJECT_WAY_INJECT: PUTS( "INJECT_WAY_INJECT" )`
- Defined: `payloads/Demon/src/core/Command.c:1352`

### PUTS `case INJECT_WAY_EXECUTE: PUTS( "INJECT_WAY_EXECUTE" )`
- Defined: `payloads/Demon/src/core/Command.c:1357`

### CommandToken `VOID CommandToken( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:1372`

### PUTS `case DEMON_COMMAND_TOKEN_IMPERSONATE: PUTS( "Token::Impersonate" )`
- Defined: `payloads/Demon/src/core/Command.c:1383`

### PUTS `case DEMON_COMMAND_TOKEN_STEAL: PUTS( "Token::Steal" )`
- Defined: `payloads/Demon/src/core/Command.c:1405`

### PUTS `case DEMON_COMMAND_TOKEN_LIST: PUTS( "Token::List" )`
- Defined: `payloads/Demon/src/core/Command.c:1449`

### PUTS `case DEMON_COMMAND_TOKEN_PRIVSGET_OR_LIST: PUTS( "Token::PrivsGetOrList" )`
- Defined: `payloads/Demon/src/core/Command.c:1476`

### PUTS `case DEMON_COMMAND_TOKEN_MAKE: PUTS( "Token::Make" )`
- Defined: `payloads/Demon/src/core/Command.c:1531`

### PUTS `case DEMON_COMMAND_TOKEN_GET_UID: PUTS( "Token::GetUID" )`
- Defined: `payloads/Demon/src/core/Command.c:1594`

### PUTS `case DEMON_COMMAND_TOKEN_REVERT: PUTS( "Token::Revert" )`
- Defined: `payloads/Demon/src/core/Command.c:1634`

### PUTS `case DEMON_COMMAND_TOKEN_REMOVE: PUTS( "Token::Remove" )`
- Defined: `payloads/Demon/src/core/Command.c:1649`

### PUTS `case DEMON_COMMAND_TOKEN_CLEAR: PUTS( "Token::Clear" )`
- Defined: `payloads/Demon/src/core/Command.c:1659`

### PUTS `case DEMON_COMMAND_TOKEN_FIND_TOKENS: PUTS( "Token::Find" )`
- Defined: `payloads/Demon/src/core/Command.c:1667`

### CommandAssemblyInlineExecute `VOID CommandAssemblyInlineExecute( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:1707`

### PRINTF `PRINTF(
            "Parsed Arguments:         \n"
            " - PipeName     [%d]: %ls \n"
   ...`
- Defined: `payloads/Demon/src/core/Command.c:1760`

### PUTS `PUTS( "Dotnet instance already running." )
    }
}

VOID CommandAssemblyListVersion( PPARSER Pars...`
- Defined: `payloads/Demon/src/core/Command.c:1788`

### PUTS `else
        PUTS("Failed to load mscoree.dll")


    if ( pClrMetaHost )`
- Defined: `payloads/Demon/src/core/Command.c:1840`

### CommandConfig `VOID CommandConfig( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:1864`

### CommandScreenshot `VOID CommandScreenshot( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:2083`

### CommandNet `VOID CommandNet( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:2109`
- Doc: TODO: The Net module is unstable so fix those issues to work on normal workstation and domain server

### PUTS `PUTS( "NetLocalGroupEnum => Success" )
                if ( GroupInfo )`
- Defined: `payloads/Demon/src/core/Command.c:2350`

### CommandPivot `VOID CommandPivot( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:2462`

### CommandTransfer `VOID CommandTransfer( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:2607`

### PUTS `case DEMON_COMMAND_TRANSFER_LIST: PUTS( "Transfer::list" )`
- Defined: `payloads/Demon/src/core/Command.c:2624`

### PUTS `case DEMON_COMMAND_TRANSFER_STOP: PUTS( "Transfer::stop" )`
- Defined: `payloads/Demon/src/core/Command.c:2640`

### PUTS `case DEMON_COMMAND_TRANSFER_RESUME: PUTS( "Transfer::resume" )`
- Defined: `payloads/Demon/src/core/Command.c:2667`

### PUTS `case DEMON_COMMAND_TRANSFER_REMOVE: PUTS( "Transfer::remove" )`
- Defined: `payloads/Demon/src/core/Command.c:2695`

### CommandSocket `VOID CommandSocket( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:2738`

### PUTS `case SOCKET_COMMAND_RPORTFWD_ADD: PUTS( "Socket::RPortFwdAdd" )`
- Defined: `payloads/Demon/src/core/Command.c:2751`

### PUTS `case SOCKET_COMMAND_RPORTFWD_LIST: PUTS( "Socket::RPortFwdList" )`
- Defined: `payloads/Demon/src/core/Command.c:2785`

### PUTS `case SOCKET_COMMAND_RPORTFWD_REMOVE: PUTS( "Socket::RPortFwdRemove" )`
- Defined: `payloads/Demon/src/core/Command.c:2818`

### PUTS `case SOCKET_COMMAND_RPORTFWD_CLEAR: PUTS( "Socket::RPortFwdClear" )`
- Defined: `payloads/Demon/src/core/Command.c:2849`

### PUTS `case SOCKET_COMMAND_SOCKSPROXY_ADD: PUTS( "Socket::SocksProxyAdd" )`
- Defined: `payloads/Demon/src/core/Command.c:2870`

### PUTS `case SOCKET_COMMAND_WRITE: PUTS( "Socket::Write" )`
- Defined: `payloads/Demon/src/core/Command.c:2877`

### PUTS `case SOCKET_COMMAND_CONNECT: PUTS( "Socket::Connect" )`
- Defined: `payloads/Demon/src/core/Command.c:2941`

### PRINTF `PRINTF( "Socket ID: %x\n", ScId )

            /* check if address is not 0 */
            if ( I...`
- Defined: `payloads/Demon/src/core/Command.c:2996`

### PUTS `case SOCKET_COMMAND_CLOSE: PUTS( "Socket::Close" )`
- Defined: `payloads/Demon/src/core/Command.c:3035`

### CommandKerberos `VOID CommandKerberos(
    IN PPARSER Parser
)`
- Defined: `payloads/Demon/src/core/Command.c:3076`

### PUTS `case KERBEROS_COMMAND_LUID: PUTS("Kerberos::LUID")`
- Defined: `payloads/Demon/src/core/Command.c:3090`

### PUTS `case KERBEROS_COMMAND_KLIST: PUTS("Kerberos::Klist")`
- Defined: `payloads/Demon/src/core/Command.c:3116`

### PUTS `case KERBEROS_COMMAND_PURGE: PUTS("Kerberos::Purge")`
- Defined: `payloads/Demon/src/core/Command.c:3204`

### PUTS `case KERBEROS_COMMAND_PTT: PUTS("Kerberos::Ptt")`
- Defined: `payloads/Demon/src/core/Command.c:3215`

### CommandMemFile `VOID CommandMemFile( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:3236`

### InWorkingHours `BOOL InWorkingHours( )`
- Defined: `payloads/Demon/src/core/Command.c:3262`

### ReachedKillDate `BOOL ReachedKillDate()`
- Defined: `payloads/Demon/src/core/Command.c:3294`

### KillDate `VOID KillDate( )`
- Defined: `payloads/Demon/src/core/Command.c:3299`

### CommandExit `VOID CommandExit( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:3315`
- Doc: TODO: rewrite this. disconnect all pivots. kill our threads. release memory and free itself.

## payloads/Demon/src/core/Dotnet.c

### DotnetExecute `BOOL DotnetExecute( BUFFER Assembly, BUFFER Arguments )`
- Defined: `payloads/Demon/src/core/Dotnet.c:18`

### PUTS `PUTS( "Init HwBp Engine" )
        /* use global engine */
        if ( ! NT_SUCCESS( HwBpEngineI...`
- Defined: `payloads/Demon/src/core/Dotnet.c:100`

### PUTS `PUTS( "HwBp Engine add AmsiScanBuffer bypass" )
            if ( ! NT_SUCCESS( Status = HwBpEngin...`
- Defined: `payloads/Demon/src/core/Dotnet.c:112`

### PUTS `PUTS( "HwBp Engine add NtTraceEvent bypass" )
        if ( ! NT_SUCCESS( HwBpEngineAdd( NULL, Thr...`
- Defined: `payloads/Demon/src/core/Dotnet.c:120`
- Doc: ThreadId = U_PTR( Instance->Teb->ClientId.UniqueThread ); /* add Amsi bypass if ( AmsiIsLoaded ) { PUTS( "HwBp Engine ad

### PUTS `PUTS( "CreateDomain..." )
    if ( ( Result = Instance->Dotnet->ICorRuntimeHost->lpVtbl->CreateDo...`
- Defined: `payloads/Demon/src/core/Dotnet.c:147`

### PUTS `PUTS( "QueryInterface..." )
    if ( ( Result = Instance->Dotnet->AppDomainThunk->lpVtbl->QueryIn...`
- Defined: `payloads/Demon/src/core/Dotnet.c:153`

### PRINTF `PRINTF("SafeArrayUnaccessData Failed: %x\n", Result )
        PACKAGE_ERROR_WIN32
    }

    PUTS...`
- Defined: `payloads/Demon/src/core/Dotnet.c:169`

### PUTS `PUTS( "Assembly EntryPoint..." )
    if ( ( Result = Instance->Dotnet->Assembly->lpVtbl->EntryPoi...`
- Defined: `payloads/Demon/src/core/Dotnet.c:178`

### PUTS `PUTS( "Creating events..." )
    if ( NT_SUCCESS( Instance->Win32.NtCreateEvent( &Instance->Dotne...`
- Defined: `payloads/Demon/src/core/Dotnet.c:236`

### PUTS `PUTS( "Resume Thread..." )
                if ( NT_SUCCESS( Instance->Win32.NtAlertResumeThread( ...`
- Defined: `payloads/Demon/src/core/Dotnet.c:285`

### DotnetPushPipe `VOID DotnetPushPipe()`
- Defined: `payloads/Demon/src/core/Dotnet.c:312`
- Doc: } else PUTS( "NtAlertResumeThread failed" ) } else PUTS( "NtGetThreadContext failed" ) } else PUTS( "NtCreateThreadEx fa

### DotnetPush `VOID DotnetPush()`
- Defined: `payloads/Demon/src/core/Dotnet.c:346`

### PRINTF `PRINTF( "Instance->Dotnet->Invoked: %s\n", Instance->Dotnet->Invoked ? "TRUE" : "FALSE" )
    if ...`
- Defined: `payloads/Demon/src/core/Dotnet.c:351`

### DotnetClose `VOID DotnetClose()`
- Defined: `payloads/Demon/src/core/Dotnet.c:378`

### PUTS `PUTS( "Free Output" )
    if ( Instance->Dotnet->Output.Buffer )`
- Defined: `payloads/Demon/src/core/Dotnet.c:427`

### PUTS `PUTS( "Unload and free CLR" )
    if ( Instance->Dotnet->MethodArgs )`
- Defined: `payloads/Demon/src/core/Dotnet.c:435`

### FindVersion `BOOL FindVersion( PVOID Assembly, DWORD length )`
- Defined: `payloads/Demon/src/core/Dotnet.c:500`

### ClrCreateInstance `DWORD ClrCreateInstance( LPCWSTR dotNetVersion, PICLRMetaHost *ppClrMetaHost, PICLRRuntimeInfo *p...`
- Defined: `payloads/Demon/src/core/Dotnet.c:523`

## payloads/Demon/src/core/Download.c

### DownloadAdd `PDOWNLOAD_DATA DownloadAdd( HANDLE hFile, LONGLONG MaxSize )`
- Defined: `payloads/Demon/src/core/Download.c:6`
- Doc: #include <Demon.h> #include <core/MiniStd.h> /* Add file to linked list with type (upload/download)

### DownloadGet `PDOWNLOAD_DATA DownloadGet( DWORD FileID )`
- Defined: `payloads/Demon/src/core/Download.c:27`
- Doc: Download->Size      = MaxSize; Download->State     = DOWNLOAD_STATE_RUNNING; Download->Next      = Instance->Downloads; 

### DownloadFree `VOID DownloadFree( PDOWNLOAD_DATA Download )`
- Defined: `payloads/Demon/src/core/Download.c:41`
- Doc: PDOWNLOAD_DATA DownloadGet( DWORD FileID ) { PDOWNLOAD_DATA Download = NULL; for ( Download = Instance->Downloads; Downl

### DownloadRemove `BOOL DownloadRemove( DWORD FileID )`
- Defined: `payloads/Demon/src/core/Download.c:55`

### DownloadPush `VOID DownloadPush()`
- Defined: `payloads/Demon/src/core/Download.c:94`
- Doc: /* return that we succeeded. Success = TRUE; break; } Last     = Download; Download = Download->Next; } return Success; 

### PRINTF `PRINTF( "Allocated memory for DownloadChunk. Buffer:[%p] Size:[%d]\n", Instance->DownloadChunk.Bu...`
- Defined: `payloads/Demon/src/core/Download.c:128`

### MemFileIsNew `BOOL MemFileIsNew( ULONG32 ID )`
- Defined: `payloads/Demon/src/core/Download.c:237`

### NewMemFile `PMEM_FILE NewMemFile( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
- Defined: `payloads/Demon/src/core/Download.c:254`
- Doc: PMEM_FILE MemFile = Instance->MemFiles; while ( MemFile ) { if ( MemFile->ID == ID ) return FALSE; MemFile = MemFile->Ne

### GetMemFile `PMEM_FILE GetMemFile( ULONG32 ID )`
- Defined: `payloads/Demon/src/core/Download.c:286`

### ProcessMemFileChunk `PMEM_FILE ProcessMemFileChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
- Defined: `payloads/Demon/src/core/Download.c:301`

### MemFileReadChunk `PMEM_FILE MemFileReadChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
- Defined: `payloads/Demon/src/core/Download.c:317`

### MemFileFree `VOID MemFileFree( PMEM_FILE MemFile )`
- Defined: `payloads/Demon/src/core/Download.c:338`

### RemoveMemFile `BOOL RemoveMemFile( ULONG32 ID )`
- Defined: `payloads/Demon/src/core/Download.c:354`

## payloads/Demon/src/core/HwBpEngine.c

### HwBpEngineInit `NTSTATUS HwBpEngineInit(
    OUT PHWBP_ENGINE Engine,
    IN  PVOID        Handler
)`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:18`
- Doc: ! Init Hardware breakpoint engine by registering a Vectored exception handler @param Engine   if empty global handler go

### HwBpEngineSetBp `NTSTATUS HwBpEngineSetBp(
    IN DWORD Tid,
    IN PVOID Address,
    IN BYTE  Position,
    IN B...`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:61`
- Doc: ! Set hardware breakpoint on specified address @param Tib @param Address @param Position @param Add @return

### PRINTF `PRINTF(
                "Dr Registers:  \n"
                "- Dr0[%d]: %p  \n"
                "...`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:115`

### HwBpEngineAdd `NTSTATUS HwBpEngineAdd(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID        ...`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:152`
- Doc: ! Set an hardware breakpoint to an address and adds it to the engine breakpoints list linked @param Engine @param Thread

### PRINTF `PRINTF( "Engine:[%p] Tid:[%d] Address:[%p] Function:[%p] Position:[%d]\n", Engine, Tid, Address, ...`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:161`

### HwBpEngineRemove `NTSTATUS HwBpEngineRemove(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID     ...`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:208`

### HwBpEngineDestroy `NTSTATUS HwBpEngineDestroy(
    IN PHWBP_ENGINE Engine
)`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:260`

### ExceptionHandler `LONG ExceptionHandler(
    _Inout_ PEXCEPTION_POINTERS Exception
)`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:320`
- Doc: ! Global exception handler @param Exception @return

### PRINTF `PRINTF( "Found exception handler: %s\n", Found ? "TRUE" : "FALSE" )
        if ( Found )`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:354`

## payloads/Demon/src/core/HwBpExceptions.c

### HwBpExAmsiScanBuffer `VOID HwBpExAmsiScanBuffer(
    _Inout_ PEXCEPTION_POINTERS Exception
)`
- Defined: `payloads/Demon/src/core/HwBpExceptions.c:5`
- Doc: if _WIN64

### HwBpExNtTraceEvent `VOID HwBpExNtTraceEvent(
    _Inout_ PEXCEPTION_POINTERS Exception
)`
- Defined: `payloads/Demon/src/core/HwBpExceptions.c:22`

## payloads/Demon/src/core/Jobs.c

### JobAdd `VOID JobAdd( UINT32 RequestID, DWORD JobID, SHORT Type, SHORT State, HANDLE Handle, PVOID Data )`
- Defined: `payloads/Demon/src/core/Jobs.c:17`
- Doc: ! JobAdd Adds a job to the job linked list @param JobID @param Type type of job: thread or process @param State current 

### JobCheckList `VOID JobCheckList()`
- Defined: `payloads/Demon/src/core/Jobs.c:63`
- Doc: ! Check if all jobs are still running and exists @return

### JobSuspend `BOOL JobSuspend( DWORD JobID )`
- Defined: `payloads/Demon/src/core/Jobs.c:184`
- Doc: ! JobSuspend Suspends the specified job @param JobID @return

### PRINTF `PRINTF( "Found Job ID: %d", JobID )

            if ( JobList->Type == JOB_TYPE_THREAD )`
- Defined: `payloads/Demon/src/core/Jobs.c:192`

### JobResume `BOOL JobResume( DWORD JobID )`
- Defined: `payloads/Demon/src/core/Jobs.c:230`
- Doc: ! JobSuspend Suspends the specified job @param JobID @return

### PRINTF `PRINTF( "Found Job ID: %d", JobID )

            if ( JobList->Type == JOB_TYPE_THREAD )`
- Defined: `payloads/Demon/src/core/Jobs.c:238`

### JobKill `BOOL JobKill( DWORD JobID )`
- Defined: `payloads/Demon/src/core/Jobs.c:277`
- Doc: ! JobKill Kills and remove the specified job @param JobID @return

### PRINTF `PRINTF( "Found Job ID: %d\n", JobID )

            switch ( JobList->Type )`
- Defined: `payloads/Demon/src/core/Jobs.c:287`

### PUTS `PUTS( "Kill using handle" )

                            if ( ! NT_SUCCESS( NtStatus = Instance->...`
- Defined: `payloads/Demon/src/core/Jobs.c:300`

### JobRemove `VOID JobRemove( DWORD JobID )`
- Defined: `payloads/Demon/src/core/Jobs.c:383`
- Doc: ! JobRemove Remove the specified job @param ThreadID @return

## payloads/Demon/src/core/Kerberos.c

### IsHighIntegrity `BOOL IsHighIntegrity(HANDLE TokenHandle)`
- Defined: `payloads/Demon/src/core/Kerberos.c:7`
- Doc: include <Demon.h> include <core/Kerberos.h> include <core/Win32.h> include <core/MiniStd.h> include <core/Token.h>

### GetProcessIdByName `DWORD GetProcessIdByName(WCHAR* processName)`
- Defined: `payloads/Demon/src/core/Kerberos.c:28`

### ElevateToSystem `BOOL ElevateToSystem()`
- Defined: `payloads/Demon/src/core/Kerberos.c:60`

### IsSystem `BOOL IsSystem( HANDLE TokenHandle )`
- Defined: `payloads/Demon/src/core/Kerberos.c:130`

### GetLsaHandle `NTSTATUS GetLsaHandle( HANDLE hToken, BOOL highIntegrity, PHANDLE hLsa )`
- Defined: `payloads/Demon/src/core/Kerberos.c:154`

### GetLogonSessionData `NTSTATUS GetLogonSessionData( LUID luid, PLOGON_SESSION_DATA* data )`
- Defined: `payloads/Demon/src/core/Kerberos.c:217`

### ExtractTicket `VOID ExtractTicket( HANDLE hLsa, ULONG authPackage, LUID luid, UNICODE_STRING targetName, PUCHAR*...`
- Defined: `payloads/Demon/src/core/Kerberos.c:282`

### CopySessionInfo `VOID CopySessionInfo( PSESSION_INFORMATION Session, PSECURITY_LOGON_SESSION_DATA Data )`
- Defined: `payloads/Demon/src/core/Kerberos.c:336`

### CopyTicketInfo `VOID CopyTicketInfo( PTICKET_INFORMATION TicketInfo, PKERB_TICKET_CACHE_INFO_EX Data )`
- Defined: `payloads/Demon/src/core/Kerberos.c:370`

### Ptt `BOOL Ptt( HANDLE hToken, PBYTE Ticket, DWORD TicketSize, LUID luid )`
- Defined: `payloads/Demon/src/core/Kerberos.c:398`

### Purge `BOOL Purge( HANDLE hToken, LUID luid )`
- Defined: `payloads/Demon/src/core/Kerberos.c:493`

### Klist `PSESSION_INFORMATION Klist( HANDLE hToken, LUID luid )`
- Defined: `payloads/Demon/src/core/Kerberos.c:584`

### GetLUID `LUID* GetLUID( HANDLE hToken )`
- Defined: `payloads/Demon/src/core/Kerberos.c:751`

## payloads/Demon/src/core/Memory.c

### MmHeapAlloc `PVOID MmHeapAlloc(
    _In_ ULONG Length
)`
- Defined: `payloads/Demon/src/core/Memory.c:15`
- Doc: ! @brief allocate memory on the heap  @param Length size of memory to allocate  @return allocated buffer pointer on the 

### MmHeapReAlloc `PVOID MmHeapReAlloc(
    _In_ PVOID Memory,
    _In_ ULONG Length
)`
- Defined: `payloads/Demon/src/core/Memory.c:31`
- Doc: ! @brief allocate memory on the heap  @param Length size of memory to reallocate  @return allocated buffer pointer on th

### MmHeapFree `BOOL MmHeapFree(
    _In_ PVOID Memory
)`
- Defined: `payloads/Demon/src/core/Memory.c:48`
- Doc: ! @brief free memory on the heap  @param Memory memory to free  @return if successfully freed memory on the heap

### MmVirtualAlloc `PVOID MmVirtualAlloc(
    IN DX_MEMORY Methode,
    IN HANDLE    Process,
    IN SIZE_T    Size,
...`
- Defined: `payloads/Demon/src/core/Memory.c:62`
- Doc: ! Allocates virtual memory @param Method @param Process @param Size @param Protect @return

### PUTS `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )`
- Defined: `payloads/Demon/src/core/Memory.c:79`

### MmVirtualProtect `BOOL MmVirtualProtect(
    IN DX_MEMORY Method,
    IN HANDLE    Process,
    IN PVOID     Memory...`
- Defined: `payloads/Demon/src/core/Memory.c:133`
- Doc: ! Changes the protection of a virtual memory. @param Method @param Process @param Memory @param Size @param Protect @ret

### PUTS `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )`
- Defined: `payloads/Demon/src/core/Memory.c:147`

### MmVirtualWrite `BOOL MmVirtualWrite(
    IN  HANDLE Process,
    OUT PVOID  Memory,
    IN  PVOID  Buffer,
    IN...`
- Defined: `payloads/Demon/src/core/Memory.c:188`

### MmVirtualFree `BOOL MmVirtualFree(
    IN HANDLE Process,
    IN PVOID  Memory
)`
- Defined: `payloads/Demon/src/core/Memory.c:209`
- Doc: ! Frees virtual memory @param Process @param Memory @return

### MmGadgetFind `PVOID MmGadgetFind(
    _In_ PVOID  Memory,
    _In_ SIZE_T Length,
    _In_ PVOID  PatternBuffer...`
- Defined: `payloads/Demon/src/core/Memory.c:239`

### FreeReflectiveLoader `BOOL FreeReflectiveLoader(
    IN PVOID BaseAddress
)`
- Defined: `payloads/Demon/src/core/Memory.c:269`
- Doc: ! Frees the reflective loader @param BaseAddress @return

## payloads/Demon/src/core/MiniStd.c

### StringCompareA `INT StringCompareA( LPCSTR String1, LPCSTR String2 )`
- Defined: `payloads/Demon/src/core/MiniStd.c:8`
- Doc: Most of the functions from here are from VX-Underground https://github.com/vxunderground/VX-API

### StringCompareW `INT StringCompareW( LPWSTR String1, LPWSTR String2 )`
- Defined: `payloads/Demon/src/core/MiniStd.c:20`

### StringNCompareW `INT StringNCompareW( LPWSTR String1, LPWSTR String2, INT Length )`
- Defined: `payloads/Demon/src/core/MiniStd.c:32`

### ToLowerCaseW `WCHAR ToLowerCaseW( WCHAR C )`
- Defined: `payloads/Demon/src/core/MiniStd.c:47`

### StringCompareIW `INT StringCompareIW( LPWSTR String1, LPWSTR String2 )`
- Defined: `payloads/Demon/src/core/MiniStd.c:52`

### StringNCompareIW `INT StringNCompareIW( LPWSTR String1, LPWSTR String2, INT Length )`
- Defined: `payloads/Demon/src/core/MiniStd.c:64`

### EndsWithIW `BOOL EndsWithIW( LPWSTR String, LPWSTR Ending )`
- Defined: `payloads/Demon/src/core/MiniStd.c:79`

### HashStringA `DWORD HashStringA( PCHAR String )`
- Defined: `payloads/Demon/src/core/MiniStd.c:100`
- Doc: return FALSE; Length1 = StringLengthW( String ); Length2 = StringLengthW( Ending ); if ( Length1 < Length2 ) return FALS

### StringCopyA `PCHAR StringCopyA(PCHAR String1, PCHAR String2)`
- Defined: `payloads/Demon/src/core/MiniStd.c:110`

### StringCopyW `PWCHAR StringCopyW(PWCHAR String1, PWCHAR String2)`
- Defined: `payloads/Demon/src/core/MiniStd.c:120`

### StringLengthA `SIZE_T StringLengthA(LPCSTR String)`
- Defined: `payloads/Demon/src/core/MiniStd.c:129`

### StringLengthW `SIZE_T StringLengthW(LPCWSTR String)`
- Defined: `payloads/Demon/src/core/MiniStd.c:141`

### StringConcatA `PCHAR StringConcatA(PCHAR String, PCHAR String2)`
- Defined: `payloads/Demon/src/core/MiniStd.c:150`

### StringConcatW `PWCHAR StringConcatW(PWCHAR String, PWCHAR String2)`
- Defined: `payloads/Demon/src/core/MiniStd.c:157`

### WcsStr `LPWSTR WcsStr( PWCHAR String, PWCHAR String2 )`
- Defined: `payloads/Demon/src/core/MiniStd.c:164`

### WcsIStr `LPWSTR WcsIStr( PWCHAR String, PWCHAR String2 )`
- Defined: `payloads/Demon/src/core/MiniStd.c:184`

### MemCompare `INT MemCompare( PVOID s1, PVOID s2, INT len)`
- Defined: `payloads/Demon/src/core/MiniStd.c:204`

### WCharStringToCharString `SIZE_T WCharStringToCharString(PCHAR Destination, PWCHAR Source, SIZE_T MaximumAllowed)`
- Defined: `payloads/Demon/src/core/MiniStd.c:228`

### CharStringToWCharString `SIZE_T CharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )`
- Defined: `payloads/Demon/src/core/MiniStd.c:241`

### StringTokenA `PCHAR StringTokenA(PCHAR String, CONST PCHAR Delim)`
- Defined: `payloads/Demon/src/core/MiniStd.c:254`

### GetSystemFileTime `UINT64 GetSystemFileTime( )`
- Defined: `payloads/Demon/src/core/MiniStd.c:299`

### HideChar `BYTE NO_INLINE HideChar( BYTE C )`
- Defined: `payloads/Demon/src/core/MiniStd.c:313`
- Doc: UINT64 GetSystemFileTime( ) { FILETIME ft; LARGE_INTEGER li; Instance->Win32.GetSystemTimeAsFileTime(&ft); //returns tic

## payloads/Demon/src/core/Obf.c

### FoliageObf `VOID FoliageObf(
    IN PSLEEP_PARAM Param
)`
- Defined: `payloads/Demon/src/core/Obf.c:22`
- Doc: ! @brief foliage is a sleep obfuscation technique that is using APC calls to obfuscate itself in memory  @param Param @r

### PRINTF `PRINTF( "RtlCreateTimerQueue/NtCreateEvent Failed: %lx\n", NtStatus )
    }

LEAVE: /* cleanup */...`
- Defined: `payloads/Demon/src/core/Obf.c:603`

### SleepTime `UINT32 SleepTime(
    VOID
)`
- Defined: `payloads/Demon/src/core/Obf.c:649`
- Doc: endif

### SleepObf `VOID SleepObf(
    VOID
)`
- Defined: `payloads/Demon/src/core/Obf.c:713`

## payloads/Demon/src/core/ObjectApi.c

### LdrModulePebString `PVOID LdrModulePebString( PCHAR ModuleString )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:20`
- Doc: Meh some wrapper functions for internal demon GetProcAddress and GetModuleHandleA functions.

### LdrFunctionAddrString `PVOID LdrFunctionAddrString( PVOID Module, PCHAR Function )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:25`

### LdrFreeLibrary `BOOL LdrFreeLibrary( HMODULE hLibModule )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:31`

### LdrLocalFree `HLOCAL LdrLocalFree( PVOID hMem )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:36`

### swap_endianess `uint32_t swap_endianess(uint32_t indata)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:130`

### BeaconDataParse `VOID BeaconDataParse( PDATA parser, PCHAR buffer, INT size )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:142`

### BeaconDataInt `INT BeaconDataInt( PDATA parser )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:154`

### BeaconDataShort `SHORT BeaconDataShort( datap* parser )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:169`

### BeaconDataLength `INT BeaconDataLength( PDATA parser )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:184`

### BeaconDataExtract `PCHAR BeaconDataExtract( PDATA parser, PINT size )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:189`

### GetRequestIDForCallingObjectFile `BOOL GetRequestIDForCallingObjectFile( PVOID CoffeeFunctionReturn, PUINT32 RequestID )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:224`
- Doc: This function is called by BeaconPrintf and BeaconOutput. It loops over all the COFFEE structs saved on the Instance obj

### BeaconPrintf `VOID BeaconPrintf( INT Type, PCHAR fmt, ... )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:247`

### BeaconOutput `VOID BeaconOutput( INT Type, PCHAR data, INT len )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:304`

### BeaconIsAdmin `BOOL BeaconIsAdmin(
    VOID
)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:323`

### BeaconFormatAlloc `VOID BeaconFormatAlloc( PFORMAT format, int maxsz )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:342`

### BeaconFormatReset `VOID BeaconFormatReset( PFORMAT format )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:353`

### BeaconFormatFree `VOID BeaconFormatFree( PFORMAT format )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:360`

### BeaconFormatAppend `VOID BeaconFormatAppend( PFORMAT format, char* text, int len )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:376`

### BeaconFormatPrintf `VOID BeaconFormatPrintf( PFORMAT format, char* fmt, ... )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:383`

### BeaconFormatToString `char* BeaconFormatToString( PFORMAT format, int* size)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:404`

### BeaconFormatInt `VOID BeaconFormatInt( PFORMAT format, int value)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:410`

### BeaconUseToken `BOOL BeaconUseToken( HANDLE token )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:424`

### BeaconGetSpawnTo `VOID BeaconGetSpawnTo( BOOL x86, char* buffer, int length )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:439`

### BeaconSpawnTemporaryProcess `BOOL BeaconSpawnTemporaryProcess( BOOL x86, BOOL ignoreToken, STARTUPINFO* sInfo, PROCESS_INFORMA...`
- Defined: `payloads/Demon/src/core/ObjectApi.c:462`

### BeaconInjectProcess `VOID BeaconInjectProcess( HANDLE hProc, int pid, char* payload, int p_len, int p_offset, char * a...`
- Defined: `payloads/Demon/src/core/ObjectApi.c:486`

### BeaconInjectTemporaryProcess `VOID BeaconInjectTemporaryProcess( PROCESS_INFORMATION* pInfo, char* payload, int p_len, int p_of...`
- Defined: `payloads/Demon/src/core/ObjectApi.c:529`

### BeaconCleanupProcess `VOID BeaconCleanupProcess( PROCESS_INFORMATION* pInfo )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:563`

### BeaconInformation `VOID BeaconInformation(BEACON_INFO * info)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:578`
- Doc: not implemented

### BeaconAddValue `BOOL BeaconAddValue(const char * key, void * ptr)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:583`

### BeaconGetValue `PVOID BeaconGetValue(const char * key)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:632`

### BeaconRemoveValue `BOOL BeaconRemoveValue(const char * key)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:655`

### BeaconDataStoreGetItem `PDATA_STORE_OBJECT BeaconDataStoreGetItem(SIZE_T index)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:690`
- Doc: not implemented

### BeaconDataStoreProtectItem `VOID BeaconDataStoreProtectItem(SIZE_T index)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:697`
- Doc: not implemented

### BeaconDataStoreUnprotectItem `VOID BeaconDataStoreUnprotectItem(SIZE_T index)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:704`
- Doc: not implemented

### BeaconDataStoreMaxEntries `SIZE_T BeaconDataStoreMaxEntries()`
- Defined: `payloads/Demon/src/core/ObjectApi.c:711`
- Doc: not implemented

### BeaconGetCustomUserData `PCHAR BeaconGetCustomUserData()`
- Defined: `payloads/Demon/src/core/ObjectApi.c:718`
- Doc: not implemented

### toWideChar `BOOL toWideChar( char* src, wchar_t* dst, int max )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:723`

## payloads/Demon/src/core/Package.c

### Int64ToBuffer `VOID Int64ToBuffer( PUCHAR Buffer, UINT64 Value )`
- Defined: `payloads/Demon/src/core/Package.c:12`
- Doc: /* Import Core Headers #include <core/Package.h> #include <core/MiniStd.h> #include <core/Command.h> #include <core/Tran

### Int32ToBuffer `VOID Int32ToBuffer(
    OUT PUCHAR Buffer,
    IN  UINT32 Size
)`
- Defined: `payloads/Demon/src/core/Package.c:38`

### PackageAddInt32 `VOID PackageAddInt32(
    _Inout_ PPACKAGE Package,
    IN     UINT32   Data
)`
- Defined: `payloads/Demon/src/core/Package.c:48`

### PackageAddInt64 `VOID PackageAddInt64( PPACKAGE Package, UINT64 dataInt )`
- Defined: `payloads/Demon/src/core/Package.c:67`

### PackageAddBool `VOID PackageAddBool(
    _Inout_ PPACKAGE Package,
    IN     BOOLEAN  Data
)`
- Defined: `payloads/Demon/src/core/Package.c:84`

### PackageAddPtr `VOID PackageAddPtr( PPACKAGE Package, PVOID pointer )`
- Defined: `payloads/Demon/src/core/Package.c:103`

### PackageAddPad `VOID PackageAddPad( PPACKAGE Package, PCHAR Data, SIZE_T Size )`
- Defined: `payloads/Demon/src/core/Package.c:108`

### PackageAddBytes `VOID PackageAddBytes( PPACKAGE Package, PBYTE Data, SIZE_T Size )`
- Defined: `payloads/Demon/src/core/Package.c:124`

### PackageAddString `VOID PackageAddString( PPACKAGE package, PCHAR data )`
- Defined: `payloads/Demon/src/core/Package.c:146`

### PackageAddWString `VOID PackageAddWString( PPACKAGE package, PWCHAR data )`
- Defined: `payloads/Demon/src/core/Package.c:151`

### PackageCreate `PPACKAGE PackageCreate( UINT32 CommandID )`
- Defined: `payloads/Demon/src/core/Package.c:156`

### PackageCreateWithMetaData `PPACKAGE PackageCreateWithMetaData( UINT32 CommandID )`
- Defined: `payloads/Demon/src/core/Package.c:173`

### PackageCreateWithRequestID `PPACKAGE PackageCreateWithRequestID( UINT32 CommandID, UINT32 RequestID )`
- Defined: `payloads/Demon/src/core/Package.c:186`

### PackageDestroy `VOID PackageDestroy(
    IN PPACKAGE Package
)`
- Defined: `payloads/Demon/src/core/Package.c:195`

### PackageTransmitNow `BOOL PackageTransmitNow(
    _Inout_ PPACKAGE Package,
    OUT    PVOID*   Response,
    OUT    P...`
- Defined: `payloads/Demon/src/core/Package.c:229`
- Doc: used to send the demon's metadata

### PUTS_DONT_SEND `PUTS_DONT_SEND("TransportSend failed!")
        }

        if ( Package->Destroy )`
- Defined: `payloads/Demon/src/core/Package.c:264`

### PackageTransmit `VOID PackageTransmit(
    IN PPACKAGE Package
)`
- Defined: `payloads/Demon/src/core/Package.c:281`
- Doc: don't transmit right away, simply store the package. Will be sent when PackageTransmitAll is called

### PackageTransmitAll `BOOL PackageTransmitAll(
    OUT    PVOID*   Response,
    OUT    PSIZE_T  Size
)`
- Defined: `payloads/Demon/src/core/Package.c:333`
- Doc: transmit all stored packages in a single request

### PackageTransmitError `VOID PackageTransmitError(
    IN UINT32 ID,
    IN UINT32 ErrorCode
)`
- Defined: `payloads/Demon/src/core/Package.c:470`

## payloads/Demon/src/core/Parser.c

### ParserNew `VOID ParserNew( PPARSER parser, PBYTE Buffer, UINT32 size )`
- Defined: `payloads/Demon/src/core/Parser.c:6`
- Doc: include <core/Parser.h> include <core/MiniStd.h> include <crypt/AesCrypt.h>

### ParserDecrypt `VOID ParserDecrypt( PPARSER parser, PBYTE Key, PBYTE IV )`
- Defined: `payloads/Demon/src/core/Parser.c:20`

### ParserGetInt16 `INT16 ParserGetInt16( PPARSER parser )`
- Defined: `payloads/Demon/src/core/Parser.c:31`

### ParserGetByte `BYTE ParserGetByte( PPARSER parser )`
- Defined: `payloads/Demon/src/core/Parser.c:47`

### ParserGetInt32 `INT ParserGetInt32( PPARSER parser )`
- Defined: `payloads/Demon/src/core/Parser.c:62`

### ParserGetInt64 `INT64 ParserGetInt64( PPARSER parser )`
- Defined: `payloads/Demon/src/core/Parser.c:84`

### ParserGetBool `BOOL ParserGetBool( PPARSER parser )`
- Defined: `payloads/Demon/src/core/Parser.c:105`

### ParserGetBytes `PBYTE ParserGetBytes( PPARSER parser, PUINT32 size )`
- Defined: `payloads/Demon/src/core/Parser.c:126`

### ParserGetString `PCHAR  ParserGetString( PPARSER parser, PUINT32 size )`
- Defined: `payloads/Demon/src/core/Parser.c:157`

### ParserGetWString `PWCHAR  ParserGetWString( PPARSER parser, PUINT32 size )`
- Defined: `payloads/Demon/src/core/Parser.c:162`

### ParserDestroy `VOID ParserDestroy( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Parser.c:167`

## payloads/Demon/src/core/Pivot.c

### PivotAdd `BOOL PivotAdd( BUFFER NamedPipe, PVOID* Output, PDWORD BytesSize )`
- Defined: `payloads/Demon/src/core/Pivot.c:23`
- Doc: TODO: Change the way new pivots gets added.  Instead of appending it to the newest token like: PivotNew->Next = Pivot  A

### PivotGet `PPIVOT_DATA PivotGet( DWORD AgentID )`
- Defined: `payloads/Demon/src/core/Pivot.c:120`

### PivotRemove `BOOL PivotRemove( DWORD AgentId )`
- Defined: `payloads/Demon/src/core/Pivot.c:138`

### PivotCount `DWORD PivotCount()`
- Defined: `payloads/Demon/src/core/Pivot.c:217`

### PivotPush `VOID PivotPush()`
- Defined: `payloads/Demon/src/core/Pivot.c:234`

### PivotParseDemonID `UINT32 PivotParseDemonID( PVOID Response, SIZE_T Size )`
- Defined: `payloads/Demon/src/core/Pivot.c:330`

## payloads/Demon/src/core/Runtime.c

### RtAdvapi32 `BOOL RtAdvapi32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:4`
- Doc: include <Demon.h> include <core/Runtime.h> include <core/MiniStd.h>

### RtMscoree `BOOL RtMscoree(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:68`
- Doc: we delay loading mscoree.dll

### RtOleaut32 `BOOL RtOleaut32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:102`

### RtUser32 `BOOL RtUser32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:141`

### RtShell32 `BOOL RtShell32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:175`

### RtMsvcrt `BOOL RtMsvcrt(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:207`

### RtIphlpapi `BOOL RtIphlpapi(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:239`

### RtGdi32 `BOOL RtGdi32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:272`

### RtNetApi32 `BOOL RtNetApi32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:309`

### RtWs2_32 `BOOL RtWs2_32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:348`

### RtSspicli `BOOL RtSspicli(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:392`

### RtAmsi `BOOL RtAmsi(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:432`

### RtWinHttp `BOOL RtWinHttp(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:463`
- Doc: ifdef TRANSPORT_HTTP

## payloads/Demon/src/core/Socket.c

### RecvAll `BOOL RecvAll( SOCKET Socket, PVOID Buffer, DWORD Length, PDWORD BytesRead )`
- Defined: `payloads/Demon/src/core/Socket.c:7`
- Doc: attempt to receive all the requested data from the socket * Took it from: https://github.com/rsmudge/metasploit-loader/b

### InitWSA `BOOL InitWSA( VOID )`
- Defined: `payloads/Demon/src/core/Socket.c:32`

### PUTS `PUTS( "Init Windows Socket..." )

        if ( ( Result = Instance->Win32.WSAStartup( MAKEWORD( 2...`
- Defined: `payloads/Demon/src/core/Socket.c:41`

### SocketNew `PSOCKET_DATA SocketNew( SOCKET WinSock, DWORD Type, BOOL UseIpv4, DWORD IPv4, PBYTE IPv6, DWORD L...`
- Defined: `payloads/Demon/src/core/Socket.c:59`
- Doc: PRINTF( "WSAStartup Failed: %d\n", Result ) /* cleanup and be gone. Instance->Win32.WSACleanup(); return FALSE; } Instan

### PUTS `PUTS( "Create Socket..." )

        if ( UseIpv4 )`
- Defined: `payloads/Demon/src/core/Socket.c:73`

### PRINTF `PRINTF( "SockAddr6: %02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%d\n"...`
- Defined: `payloads/Demon/src/core/Socket.c:111`

### SocketClients `VOID SocketClients()`
- Defined: `payloads/Demon/src/core/Socket.c:213`
- Doc: CLEANUP: if ( WinSock && WinSock != INVALID_SOCKET ) { close the socket preserving the last error code ErrorCode = NtGet

### SocketRead `VOID SocketRead()`
- Defined: `payloads/Demon/src/core/Socket.c:281`
- Doc: { PRINTF( "ioctlsocket failed: %d\n", NtGetLastError() ) /* close socket. Instance->Win32.closesocket( WinSock ); } } } 

### SocketFree `VOID SocketFree( PSOCKET_DATA Socket )`
- Defined: `payloads/Demon/src/core/Socket.c:424`

### PRINTF `PRINTF( "Closing socket %x\n", Socket->ID )

    /* do we want to remove a reverse port forward c...`
- Defined: `payloads/Demon/src/core/Socket.c:428`

### SocketCleanDead `VOID SocketCleanDead()`
- Defined: `payloads/Demon/src/core/Socket.c:481`

### SocketPush `VOID SocketPush()`
- Defined: `payloads/Demon/src/core/Socket.c:521`

### DnsQueryIPv4 `DWORD DnsQueryIPv4( LPSTR Domain )`
- Defined: `payloads/Demon/src/core/Socket.c:539`
- Doc: ! Query the IPv4 from the specified domain @param Domain @return IPv4 address

### DnsQueryIPv6 `PBYTE DnsQueryIPv6( LPSTR Domain )`
- Defined: `payloads/Demon/src/core/Socket.c:580`
- Doc: ! Query the IPv6 from the specified domain @param Domain @return IPv6 address

## payloads/Demon/src/core/Spoof.c

### SpoofRetAddr `PVOID SpoofRetAddr(
    _In_    PVOID  Module,
    _In_    ULONG  Size,
    _In_    HANDLE Functi...`
- Defined: `payloads/Demon/src/core/Spoof.c:5`
- Doc: if _WIN64

## payloads/Demon/src/core/SysNative.c

### SysNtOpenThread `NTSTATUS NTAPI SysNtOpenThread(
    OUT    PHANDLE            ThreadHandle,
    IN     ACCESS_MAS...`
- Defined: `payloads/Demon/src/core/SysNative.c:5`
- Doc: include <core/Syscalls.h> include <core/SysNative.h>

### SysNtOpenProcess `NTSTATUS NTAPI SysNtOpenProcess(
    OUT    PHANDLE             ProcessHandle,
    IN     ACCESS_...`
- Defined: `payloads/Demon/src/core/SysNative.c:19`

### SysNtTerminateProcess `NTSTATUS NTAPI SysNtTerminateProcess(
    IN OPTIONAL HANDLE   ProcessHandle,
    IN          NTS...`
- Defined: `payloads/Demon/src/core/SysNative.c:33`

### SysNtOpenThreadToken `NTSTATUS NTAPI SysNtOpenThreadToken(
    IN  HANDLE      ThreadHandle,
    IN  ACCESS_MASK Desire...`
- Defined: `payloads/Demon/src/core/SysNative.c:45`

### SysNtOpenProcessToken `NTSTATUS NTAPI SysNtOpenProcessToken(
    IN  HANDLE      ProcessHandle,
    IN  ACCESS_MASK Desi...`
- Defined: `payloads/Demon/src/core/SysNative.c:59`

### SysNtDuplicateToken `NTSTATUS NTAPI SysNtDuplicateToken(
    IN  HANDLE             ExistingTokenHandle,
    IN  ACCES...`
- Defined: `payloads/Demon/src/core/SysNative.c:72`

### SysNtQueueApcThread `NTSTATUS NTAPI SysNtQueueApcThread(
    IN     HANDLE          ThreadHandle,
    IN     PPS_APC_R...`
- Defined: `payloads/Demon/src/core/SysNative.c:88`

### SysNtSuspendThread `NTSTATUS NTAPI SysNtSuspendThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSu...`
- Defined: `payloads/Demon/src/core/SysNative.c:103`

### SysNtResumeThread `NTSTATUS NTAPI SysNtResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSus...`
- Defined: `payloads/Demon/src/core/SysNative.c:115`

### SysNtCreateEvent `NTSTATUS NTAPI SysNtCreateEvent (
    OUT    PHANDLE            EventHandle,
    IN     ACCESS_MA...`
- Defined: `payloads/Demon/src/core/SysNative.c:127`

### SysNtCreateThreadEx `NTSTATUS NTAPI SysNtCreateThreadEx(
    OUT PHANDLE     hThread,
    IN  ACCESS_MASK DesiredAcces...`
- Defined: `payloads/Demon/src/core/SysNative.c:142`

### SysNtDuplicateObject `NTSTATUS NTAPI SysNtDuplicateObject(
    IN     HANDLE      SourceProcessHandle,
    IN     HANDL...`
- Defined: `payloads/Demon/src/core/SysNative.c:175`

### SysNtGetContextThread `NTSTATUS NTAPI SysNtGetContextThread (
    IN     HANDLE   ThreadHandle,
    _Inout_ PCONTEXT Thr...`
- Defined: `payloads/Demon/src/core/SysNative.c:192`

### SysNtSetContextThread `NTSTATUS NTAPI SysNtSetContextThread(
    IN HANDLE   ThreadHandle,
    IN PCONTEXT ThreadContext
)`
- Defined: `payloads/Demon/src/core/SysNative.c:204`

### SysNtQueryInformationProcess `NTSTATUS NTAPI SysNtQueryInformationProcess(
    IN      HANDLE           ProcessHandle,
    IN  ...`
- Defined: `payloads/Demon/src/core/SysNative.c:216`

### SysNtQuerySystemInformation `NTSTATUS NTAPI SysNtQuerySystemInformation (
    IN      SYSTEM_INFORMATION_CLASS SystemInformati...`
- Defined: `payloads/Demon/src/core/SysNative.c:231`

### SysNtWaitForSingleObject `NTSTATUS NTAPI SysNtWaitForSingleObject(
    IN     HANDLE         Handle,
    IN     BOOLEAN    ...`
- Defined: `payloads/Demon/src/core/SysNative.c:245`

### SysNtAllocateVirtualMemory `NTSTATUS NTAPI SysNtAllocateVirtualMemory(
    IN     HANDLE    ProcessHandle,
    _Inout_ PVOID*...`
- Defined: `payloads/Demon/src/core/SysNative.c:258`

### SysNtWriteVirtualMemory `NTSTATUS NTAPI SysNtWriteVirtualMemory(
    IN       HANDLE  ProcessHandle,
    IN OPT   PVOID   ...`
- Defined: `payloads/Demon/src/core/SysNative.c:274`

### SysNtFreeVirtualMemory `NTSTATUS NTAPI SysNtFreeVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  Base...`
- Defined: `payloads/Demon/src/core/SysNative.c:289`

### SysNtUnmapViewOfSection `NTSTATUS NTAPI SysNtUnmapViewOfSection(
    IN HANDLE ProcessHandle,
    IN PVOID  BaseAddress
)`
- Defined: `payloads/Demon/src/core/SysNative.c:303`

### SysNtProtectVirtualMemory `NTSTATUS NTAPI SysNtProtectVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  B...`
- Defined: `payloads/Demon/src/core/SysNative.c:315`

### SysNtReadVirtualMemory `NTSTATUS NTAPI SysNtReadVirtualMemory (
    IN      HANDLE  ProcessHandle,
    IN OPT  PVOID   Ba...`
- Defined: `payloads/Demon/src/core/SysNative.c:330`

### SysNtTerminateThread `NTSTATUS NTAPI SysNtTerminateThread (
    IN OPT HANDLE   ThreadHandle,
    IN     NTSTATUS ExitS...`
- Defined: `payloads/Demon/src/core/SysNative.c:345`

### SysNtAlertResumeThread `NTSTATUS NTAPI SysNtAlertResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG Previo...`
- Defined: `payloads/Demon/src/core/SysNative.c:357`

### SysNtSignalAndWaitForSingleObject `NTSTATUS NTAPI SysNtSignalAndWaitForSingleObject(
    IN     HANDLE         SignalHandle,
    IN ...`
- Defined: `payloads/Demon/src/core/SysNative.c:369`

### SysNtQueryVirtualMemory `NTSTATUS NTAPI SysNtQueryVirtualMemory(
    IN      HANDLE                   ProcessHandle,
    I...`
- Defined: `payloads/Demon/src/core/SysNative.c:383`

### SysNtQueryInformationToken `NTSTATUS NTAPI SysNtQueryInformationToken (
    IN  HANDLE                  TokenHandle,
    IN  ...`
- Defined: `payloads/Demon/src/core/SysNative.c:399`

### SysNtQueryInformationThread `NTSTATUS NTAPI SysNtQueryInformationThread(
    IN      HANDLE          ThreadHandle,
    IN     ...`
- Defined: `payloads/Demon/src/core/SysNative.c:414`

### SysNtQueryObject `NTSTATUS NTAPI SysNtQueryObject(
    IN  HANDLE                   Handle,
    IN  OBJECT_INFORMAT...`
- Defined: `payloads/Demon/src/core/SysNative.c:429`

### SysNtClose `NTSTATUS NTAPI SysNtClose (
    IN HANDLE Handle
)`
- Defined: `payloads/Demon/src/core/SysNative.c:444`

### SysNtSetInformationThread `NTSTATUS NTAPI SysNtSetInformationThread (
    IN HANDLE          ThreadHandle,
    IN THREADINFO...`
- Defined: `payloads/Demon/src/core/SysNative.c:455`

### SysNtSetInformationVirtualMemory `NTSTATUS NTAPI SysNtSetInformationVirtualMemory(
    IN HANDLE                           ProcessH...`
- Defined: `payloads/Demon/src/core/SysNative.c:469`

### SysNtGetNextThread `NTSTATUS NTAPI SysNtGetNextThread(
    IN  HANDLE      ProcessHandle,
    IN  HANDLE      ThreadH...`
- Defined: `payloads/Demon/src/core/SysNative.c:485`

## payloads/Demon/src/core/Syscalls.c

### SysInitialize `BOOL SysInitialize(
    IN PVOID Ntdll
)`
- Defined: `payloads/Demon/src/core/Syscalls.c:12`
- Doc: ! Initialize syscall addr + ssn @param Ntdll @return

### SYS_EXTRACT `SYS_EXTRACT( NtOpenThread )
    SYS_EXTRACT( NtOpenThreadToken )
    SYS_EXTRACT( NtOpenProcess )...`
- Defined: `payloads/Demon/src/core/Syscalls.c:44`
- Doc: Instance->Syscall.SysAddress = SysIndirectAddr; } else { PUTS_DONT_SEND( "Failed to resolve SysIndirectAddr" ); } } #if 

### PRINTF `PRINTF( "Could not resolve the Ssn of function at 0x%p\n", Function )
        }

        if ( Sys...`
- Defined: `payloads/Demon/src/core/Syscalls.c:184`

### FindSsnOfHookedSyscall `BOOL FindSsnOfHookedSyscall(
    IN  PVOID  Function,
    OUT PWORD  Ssn
)`
- Defined: `payloads/Demon/src/core/Syscalls.c:201`
- Doc: If a function is hooked, we can't obtain the Ssn directly. Instead, we look for the Ssn of a neighbouring syscalls and a

### PRINTF `PRINTF( "The syscall at address 0x%p seems to be hooked, trying to resolve its Ssn via neighbouri...`
- Defined: `payloads/Demon/src/core/Syscalls.c:208`

## payloads/Demon/src/core/Thread.c

### ThreadQueryTib `BOOL ThreadQueryTib(
    IN  PVOID   Adr,
    OUT PNT_TIB Tib
)`
- Defined: `payloads/Demon/src/core/Thread.c:20`
- Doc: ! queries the NT_TIB from the specified leaked thread RSP address  NOTE: this function is entirely taken from Austins Hu

### ThreadCreateWoW64 `HANDLE ThreadCreateWoW64(
    IN  BYTE   Method,
    IN  HANDLE Process,
    IN  PVOID  Entry,
  ...`
- Defined: `payloads/Demon/src/core/Thread.c:118`
- Doc: https://github.com/rapid7/meterpreter/blob/5e309596e53ead0f64564fe77e0cad70908f6739/source/common/arch/win/i386/base_inj

### PUTS `PUTS( "calling RtlCreateUserThread( ctx->h.hProcess, NULL, TRUE, 0, NULL, NULL, ctx->s.lpStartAdd...`
- Defined: `payloads/Demon/src/core/Thread.c:184`

### ThreadCreate `HANDLE ThreadCreate(
    IN  BYTE   Method,
    IN  HANDLE Process,
    IN  BOOL   x64,
    IN  P...`
- Defined: `payloads/Demon/src/core/Thread.c:216`
- Doc: endif

## payloads/Demon/src/core/Token.c

### TokenDuplicate `BOOL TokenDuplicate(
    IN  HANDLE        TokenOriginal,
    IN  DWORD         Access,
    IN  S...`
- Defined: `payloads/Demon/src/core/Token.c:37`
- Doc: ! @brief Duplicate given token  @param TokenOriginal @param Access @param ImpersonateLevel @param TokenType @param Token

### TokenRevSelf `BOOL TokenRevSelf(
    VOID
)`
- Defined: `payloads/Demon/src/core/Token.c:74`
- Doc: ! @brief reverse to the original process user token  @return if successful reverse to original token

### TokenQueryOwner `BOOL TokenQueryOwner(
    IN  HANDLE  Token,
    OUT PBUFFER UserDomain,
    IN  DWORD   Flags
)`
- Defined: `payloads/Demon/src/core/Token.c:103`
- Doc: ! @brief queries the username and or domain  @note the queried memory should be freed after used using HeapFree/RtlFreeH

### PUTS `PUTS( "Unexpected successful call to NtQueryInformationToken.\n" )
    }

LEAVE:
    if ( UserInfo )`
- Defined: `payloads/Demon/src/core/Token.c:177`

### DATA_FREE `DATA_FREE( UserInfo, UserSize )
    }

    if ( Flags == TOKEN_OWNER_FLAG_USER )`
- Defined: `payloads/Demon/src/core/Token.c:182`

### TokenSetPrivilege `BOOL TokenSetPrivilege(
    IN LPSTR Privilege,
    IN BOOL  Enable
)`
- Defined: `payloads/Demon/src/core/Token.c:203`
- Doc: ! sets a privilege  TODO: change it to use wide strings.  @param Privilege @param Enable @return

### TokenSetSeDebugPriv `BOOL TokenSetSeDebugPriv(
    IN BOOL  Enable
)`
- Defined: `payloads/Demon/src/core/Token.c:239`

### TokenSetSeImpersonatePriv `BOOL TokenSetSeImpersonatePriv(
    IN BOOL  Enable
)`
- Defined: `payloads/Demon/src/core/Token.c:270`

### TokenAdd `DWORD TokenAdd(
    IN HANDLE hToken,
    IN LPWSTR DomainUser,
    IN SHORT  Type,
    IN DWORD ...`
- Defined: `payloads/Demon/src/core/Token.c:323`
- Doc: Adds an token to the vault.  TODO: rewrite the function param. accept token object + STOLEN PID or MAKE data as a struct

### SysDuplicateTokenEx `BOOL SysDuplicateTokenEx(
    IN HANDLE ExistingTokenHandle,
    IN DWORD dwDesiredAccess,
    IN...`
- Defined: `payloads/Demon/src/core/Token.c:364`

### TokenSteal `HANDLE TokenSteal(
    IN DWORD  ProcessID,
    IN HANDLE TargetHandle
)`
- Defined: `payloads/Demon/src/core/Token.c:414`
- Doc: ! Steals the process token from the specified pid @param ProcessID @param TargetHandle @return

### PRINTF `PRINTF( "ProcessOpen: Failed:[%ld]\n", NtGetLastError() )
        PACKAGE_ERROR_WIN32
    }

    ...`
- Defined: `payloads/Demon/src/core/Token.c:463`

### TokenRemove `BOOL TokenRemove( DWORD TokenID )`
- Defined: `payloads/Demon/src/core/Token.c:473`

### TokenMake `HANDLE TokenMake( LPWSTR User, LPWSTR Password, LPWSTR Domain, DWORD LogonType )`
- Defined: `payloads/Demon/src/core/Token.c:597`

### PRINTF `PRINTF( "TokenMake( %ls, %ls, %ls, %d )\n", User, Password, Domain, LogonType )

    if ( ! Token...`
- Defined: `payloads/Demon/src/core/Token.c:601`

### PRINTF `PRINTF( "Failed to revert to self: Error:[%d]\n", NtGetLastError() )
        PACKAGE_ERROR_WIN32
...`
- Defined: `payloads/Demon/src/core/Token.c:606`

### TokenCurrentHandle `HANDLE TokenCurrentHandle(
    VOID
)`
- Defined: `payloads/Demon/src/core/Token.c:624`
- Doc: ! get current process/thread token @return

### TokenElevated `BOOL TokenElevated(
    IN HANDLE Token
)`
- Defined: `payloads/Demon/src/core/Token.c:649`

### TokenGet `PTOKEN_LIST_DATA TokenGet(
    IN DWORD TokenID
)`
- Defined: `payloads/Demon/src/core/Token.c:663`

### TokenClear `VOID TokenClear(
    VOID
)`
- Defined: `payloads/Demon/src/core/Token.c:680`

### TokenImpersonate `BOOL TokenImpersonate(
    IN BOOL Impersonate
)`
- Defined: `payloads/Demon/src/core/Token.c:706`

### AddUserToken `VOID AddUserToken(
    _Inout_ PUSER_TOKEN_DATA NewToken,
    _Inout_ PUSER_TOKEN_DATA Tokens,
  ...`
- Defined: `payloads/Demon/src/core/Token.c:732`

### IsImpersonationToken `BOOL IsImpersonationToken( HANDLE token )`
- Defined: `payloads/Demon/src/core/Token.c:770`

### CanTokenBeImpersonated `BOOL CanTokenBeImpersonated( IN HANDLE hToken )`
- Defined: `payloads/Demon/src/core/Token.c:802`
- Doc: https://github.com/rapid7/metasploit-payloads/blob/master/c/meterpreter/source/extensions/incognito/list_tokens.c

### ProcessUserToken `VOID ProcessUserToken(
    IN HANDLE hToken,
    IN DWORD ProcessId,
    IN HANDLE handle,
    IN...`
- Defined: `payloads/Demon/src/core/Token.c:829`

### QueryObjectTypesInfo `BOOL QueryObjectTypesInfo( POBJECT_TYPES_INFORMATION* pObjectTypes, PULONG pObjectTypesSize )`
- Defined: `payloads/Demon/src/core/Token.c:878`
- Doc: call NtQueryObject with ObjectTypesInformation

### GetTypeIndexToken `BOOL GetTypeIndexToken( OUT PULONG TokenTypeIndex )`
- Defined: `payloads/Demon/src/core/Token.c:910`
- Doc: get index of object type 'Token'

### GetTokenInfo `BOOL GetTokenInfo(
    IN HANDLE hToken,
    OUT PDWORD pTokenType,
    OUT PDWORD pIntegrity,
  ...`
- Defined: `payloads/Demon/src/core/Token.c:948`

### PUTS `PUTS( "GetTokenInformation failed" )
            }
        }
        else if (TokenStatisticsInfo...`
- Defined: `payloads/Demon/src/core/Token.c:991`

### ProcessIsIncluded `BOOL ProcessIsIncluded( IN PPROCESS_LIST process_list, IN ULONG ProcessId )`
- Defined: `payloads/Demon/src/core/Token.c:1029`
- Doc: check if a PID is included in the process list

### GetProcessesFromHandleTable `BOOL GetProcessesFromHandleTable( IN PSYSTEM_HANDLE_INFORMATION handleTableInformation, OUT PPROC...`
- Defined: `payloads/Demon/src/core/Token.c:1040`
- Doc: obtain a list of PIDs from a handle table

### GetAllHandles `BOOL GetAllHandles( OUT PSYSTEM_HANDLE_INFORMATION* phandle_table, OUT PULONG phandle_table_size )`
- Defined: `payloads/Demon/src/core/Token.c:1076`
- Doc: get all handles in the system

### IsNotCurrentUser `BOOL IsNotCurrentUser( BOOL DoCheck, PBUFFER UserA, PBUFFER UserB )`
- Defined: `payloads/Demon/src/core/Token.c:1122`
- Doc: phandle_table = (PSYSTEM_HANDLE_INFORMATION)handleTableInformation; phandle_table_size = buffer_size; ret_val = TRUE; cl

### ListTokens `BOOL ListTokens( PUSER_TOKEN_DATA* pTokens, PDWORD pNumTokens )`
- Defined: `payloads/Demon/src/core/Token.c:1129`

### ImpersonateTokenFromVault `BOOL ImpersonateTokenFromVault(
    IN DWORD TokenID
)`
- Defined: `payloads/Demon/src/core/Token.c:1256`

### SysImpersonateLoggedOnUser `BOOL SysImpersonateLoggedOnUser( HANDLE hToken )`
- Defined: `payloads/Demon/src/core/Token.c:1281`
- Doc: https://doxygen.reactos.org/d1/d72/dll_2win32_2advapi32_2sec_2misc_8c_source.html#l00152

### ImpersonateTokenInStore `BOOL ImpersonateTokenInStore(
    IN PTOKEN_LIST_DATA TokenData
)`
- Defined: `payloads/Demon/src/core/Token.c:1360`

## payloads/Demon/src/core/Transport.c

### TransportInit `BOOL TransportInit( )`
- Defined: `payloads/Demon/src/core/Transport.c:12`
- Doc: include <crypt/AesCrypt.h>

### TransportSend `BOOL TransportSend( LPVOID Data, SIZE_T Size, PVOID* RecvData, PSIZE_T RecvSize )`
- Defined: `payloads/Demon/src/core/Transport.c:51`

### SMBGetJob `BOOL SMBGetJob( PVOID* RecvData, PSIZE_T RecvSize )`
- Defined: `payloads/Demon/src/core/Transport.c:88`
- Doc: ifdef TRANSPORT_SMB

## payloads/Demon/src/core/TransportHttp.c

### HttpSend `BOOL HttpSend(
    _In_      PBUFFER Send,
    _Out_opt_ PBUFFER Resp
)`
- Defined: `payloads/Demon/src/core/TransportHttp.c:21`
- Doc: ! @brief send a http request  @param Send buffer to send  @param Resp buffer response  @return if successful send reques

### PRINTF_DONT_SEND `PRINTF_DONT_SEND( "HTTP Error: %d\n", NtGetLastError() )
    }

LEAVE:
    if ( Connect )`
- Defined: `payloads/Demon/src/core/TransportHttp.c:290`

### HttpQueryStatus `DWORD HttpQueryStatus(
    _In_ HANDLE Request
)`
- Defined: `payloads/Demon/src/core/TransportHttp.c:336`
- Doc: ! @brief Query the Http Status code from the request response.  @param hRequest request handle  @return Http status code

### HostAdd `PHOST_DATA HostAdd(
    _In_ LPWSTR Host, SIZE_T Size, DWORD Port )`
- Defined: `payloads/Demon/src/core/TransportHttp.c:355`

### HostFailure `PHOST_DATA HostFailure( PHOST_DATA Host )`
- Defined: `payloads/Demon/src/core/TransportHttp.c:377`

### HostRandom `PHOST_DATA HostRandom()`
- Defined: `payloads/Demon/src/core/TransportHttp.c:402`
- Doc: /* Get our next host based on our rotation strategy. return HostRotation( Instance->Config.Transport.HostRotation ); } /

### HostRotation `PHOST_DATA HostRotation( SHORT Strategy )`
- Defined: `payloads/Demon/src/core/TransportHttp.c:436`

### HostCount `DWORD HostCount()`
- Defined: `payloads/Demon/src/core/TransportHttp.c:513`

### HostCheckup `BOOL HostCheckup()`
- Defined: `payloads/Demon/src/core/TransportHttp.c:540`

## payloads/Demon/src/core/TransportSmb.c

### SmbSend `BOOL SmbSend( PBUFFER Send )`
- Defined: `payloads/Demon/src/core/TransportSmb.c:7`
- Doc: ifdef TRANSPORT_SMB

### SmbRecv `BOOL SmbRecv( PBUFFER Resp )`
- Defined: `payloads/Demon/src/core/TransportSmb.c:64`

### PRINTF `PRINTF( "PipeRead failed with to read 0x%x bytes from pipe\n", Resp->Length )
                if ...`
- Defined: `payloads/Demon/src/core/TransportSmb.c:107`

### SmbSecurityAttrOpen `VOID SmbSecurityAttrOpen( PSMB_PIPE_SEC_ATTR SmbSecAttr, PSECURITY_ATTRIBUTES SecurityAttr )`
- Defined: `payloads/Demon/src/core/TransportSmb.c:142`
- Doc: Took it from https://github.com/rapid7/metasploit-payloads/blob/master/c/meterpreter/source/metsrv/server_pivot_named_pi

### SmbSecurityAttrFree `VOID SmbSecurityAttrFree( PSMB_PIPE_SEC_ATTR SmbSecAttr )`
- Defined: `payloads/Demon/src/core/TransportSmb.c:212`

## payloads/Demon/src/core/Win32.c

### HashEx `ULONG HashEx(
    IN PVOID String,
    IN ULONG Length,
    IN BOOL  Upper
)`
- Defined: `payloads/Demon/src/core/Win32.c:17`
- Doc: ! Extended String Hasher @param String @param Length @param Upper @return

### LdrModulePeb `PVOID LdrModulePeb(
    IN DWORD Hash
)`
- Defined: `payloads/Demon/src/core/Win32.c:65`
- Doc: ! load module from PEB InLoadOrderModuleList by Hash @param Hash @return

### LdrModulePebByString `PVOID LdrModulePebByString(
    IN LPWSTR Module
)`
- Defined: `payloads/Demon/src/core/Win32.c:99`
- Doc: ! load module from PEB InLoadOrderModuleList by String @param Module name of module (needs to be upper case: MODULE.DLL)

### LdrModuleSearch `PVOID LdrModuleSearch(
    IN LPWSTR ModuleName)`
- Defined: `payloads/Demon/src/core/Win32.c:165`
- Doc: ! Search for a DLL on the PEB module list  @param ModuleName module name @return

### LdrModuleLoad `PVOID LdrModuleLoad(
    IN LPSTR ModuleName
)`
- Defined: `payloads/Demon/src/core/Win32.c:215`
- Doc: ! Load Library by string name.  @note based on how it is configured to load the module it either proxy calls LoadLibrary

### PUTS `PUTS( "Loading module using RtlRegisterWait" )

            /* create an event for end of module ...`
- Defined: `payloads/Demon/src/core/Win32.c:252`

### PUTS `PUTS( "Loading module using RtlCreateTimer" )

            /* create timer queue */
            i...`
- Defined: `payloads/Demon/src/core/Win32.c:269`

### PUTS `PUTS( "Loading module using RtlQueueWorkItem" )

            /* call LoadLibraryW and load specif...`
- Defined: `payloads/Demon/src/core/Win32.c:286`

### PRINTF `PRINTF( "Module \"%s\": %p\n", ModuleName, Module )

    /* close event end */
    if ( Event )`
- Defined: `payloads/Demon/src/core/Win32.c:353`

### LdrFunctionAddr `PVOID LdrFunctionAddr(
    IN PVOID Module,
    IN DWORD Hash
)`
- Defined: `payloads/Demon/src/core/Win32.c:377`
- Doc: ! gets the function pointer @param Module @param FunctionHash @return

### GetSyscallSize `UINT32 GetSyscallSize(
    VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:440`
- Doc: Get the size of an NtApi by finding two consecutive syscalls and returning the difference of their addresses. This can't

### ProcessOpen `HANDLE ProcessOpen(
    IN DWORD Pid,
    IN DWORD Access
)`
- Defined: `payloads/Demon/src/core/Win32.c:515`
- Doc: ! opens a handle to the specified pid with specified access @param ProcessID @param Access @return

### ProcessIsWow `BOOL ProcessIsWow(
    IN HANDLE Process
)`
- Defined: `payloads/Demon/src/core/Win32.c:544`
- Doc: ! checks if a process runs under Wow64 @param Process @return

### ProcessCreate `BOOL ProcessCreate(
    IN  BOOL                 x86,
    IN  LPWSTR               App,
    IN  L...`
- Defined: `payloads/Demon/src/core/Win32.c:579`
- Doc: ! Starts a Process  @param x86 start 32-bit/wow64 process @param App App path @param CmdLine Process to run @param Flags

### PUTS `PUTS( "Enable Wow64 process support" )
        if ( ! Instance->Win32.Wow64DisableWow64FsRedirect...`
- Defined: `payloads/Demon/src/core/Win32.c:626`

### PRINTF `PRINTF( "CmdLine           : %ls\n", CmdLine )
        PRINTF( "lpCurrentDirectory: %ls\n", lpCur...`
- Defined: `payloads/Demon/src/core/Win32.c:653`

### PUTS `PUTS( "CreateProcessWithTokenW" )
            if ( ! Instance->Win32.CreateProcessWithTokenW(
   ...`
- Defined: `payloads/Demon/src/core/Win32.c:670`

### PUTS `PUTS( "CreateProcessWithLogonW" )
            PRINTF( "lpUser[%s] lpDomain[%s] lpPassword[%s]", I...`
- Defined: `payloads/Demon/src/core/Win32.c:693`

### PUTS `PUTS( "Send info back" )
        if ( ! CmdLine )`
- Defined: `payloads/Demon/src/core/Win32.c:739`

### ProcessTerminate `BOOL ProcessTerminate(
    IN HANDLE hProcess,
    IN DWORD  Pid)`
- Defined: `payloads/Demon/src/core/Win32.c:805`

### PUTS `PUTS( "Failed to terminate process" )
    }

END:
    if ( OpenedHandle )`
- Defined: `payloads/Demon/src/core/Win32.c:831`

### ProcessSnapShot `NTSTATUS ProcessSnapShot(
    OUT PSYSTEM_PROCESS_INFORMATION* SnapShot,
    OUT PSIZE_T         ...`
- Defined: `payloads/Demon/src/core/Win32.c:848`
- Doc: ! takes a snapshot of current running processes @param SnapShot @param Size @return

### ReadLocalFile `BOOL ReadLocalFile(
    IN  LPCWSTR FileName,
    OUT PVOID*  FileContent,
    OUT PDWORD  FileSi...`
- Defined: `payloads/Demon/src/core/Win32.c:885`

### BypassPatchAMSI `BOOL BypassPatchAMSI(
    VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:930`
- Doc: Patch AMSI * TODO: remove this and replace it with hardware breakpoints

### AnonPipesInit `BOOL AnonPipesInit(
    IN PANONPIPE AnonPipes
)`
- Defined: `payloads/Demon/src/core/Win32.c:980`

### AnonPipesRead `VOID AnonPipesRead(
    IN PANONPIPE AnonPipes,
    IN UINT32 RequestID
)`
- Defined: `payloads/Demon/src/core/Win32.c:1000`
- Doc: ! reads from the specified anonymous pipe and sends the result back to the teamserver @param AnonPipes @param RequestID

### PUTS `PUTS( "Start reading anon pipe" )
    PRINTF( "AnonPipes->StdOutRead => %x\n", AnonPipes->StdOutR...`
- Defined: `payloads/Demon/src/core/Win32.c:1010`

### PRINTF `PRINTF( "dwRead => %d\n", dwRead )

        if ( dwRead == 0 )`
- Defined: `payloads/Demon/src/core/Win32.c:1023`

### WinScreenshot `BOOL WinScreenshot(
    OUT PVOID*  ImagePointer,
    OUT PSIZE_T ImageSize
)`
- Defined: `payloads/Demon/src/core/Win32.c:1052`
- Doc: ! takes a BMP screenshot of the current desktop @param ImagePointer @param ImageSize @return

### PipeRead `BOOL PipeRead(
    IN HANDLE  Handle,
    IN PBUFFER Buffer
)`
- Defined: `payloads/Demon/src/core/Win32.c:1175`
- Doc: ! Read from the pipe and writes it to the specified buffer @param Handle handle to the pipe @param Buffer buffer to save

### PipeWrite `BOOL PipeWrite(
    IN  HANDLE   Handle,
    OUT PBUFFER Buffer
)`
- Defined: `payloads/Demon/src/core/Win32.c:1202`
- Doc: ! Write the specified buffer to the specified pipe @param Handle handle to the pipe @param Buffer buffer to write @retur

### CfgQueryEnforced `BOOL CfgQueryEnforced(
    VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:1227`
- Doc: ! @brief check if CFG is enforced in this current process.  @return

### CfgAddressAdd `VOID CfgAddressAdd(
    IN PVOID ImageBase,
    IN PVOID Function
)`
- Defined: `payloads/Demon/src/core/Win32.c:1259`
- Doc: ! @brief add module + function to CFG exception list.  @param ImageBase @param Function

### EventSet `BOOL EventSet(
    IN HANDLE Event
)`
- Defined: `payloads/Demon/src/core/Win32.c:1293`
- Doc: ! Sets an event @param Event

### RandomNumber32 `ULONG RandomNumber32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:1304`
- Doc: ! generates a random unsigned 32-bit integer @return

### RandomBool `BOOL RandomBool(
    VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:1321`
- Doc: ! generates a random bool @return

### SharedTimestamp `ULONG64 SharedTimestamp(
    VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:1337`
- Doc: ! get current timestamp since unix epoch from KUSER_SHARED_DATA @return

### SharedSleep `VOID SharedSleep(
    ULONG64 Delay
)`
- Defined: `payloads/Demon/src/core/Win32.c:1357`
- Doc: ! Sleep using KUSER_SHARED_DATA.SystemTime @param Delay

### ShuffleArray `VOID ShuffleArray(
    _Inout_ PVOID* array,
    IN     SIZE_T n
)`
- Defined: `payloads/Demon/src/core/Win32.c:1378`

### ___chkstk_ms `VOID volatile ___chkstk_ms(
        VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:1395`

### DemonPrintf `VOID DemonPrintf( PCHAR fmt, ... )`
- Defined: `payloads/Demon/src/core/Win32.c:1401`
- Doc: if defined(SEND_LOGS) && defined(DEBUG)

### LogToConsole `VOID LogToConsole(
    IN LPCSTR fmt,
    ...)`
- Defined: `payloads/Demon/src/core/Win32.c:1433`
- Doc: elif defined(SHELLCODE) && defined(DEBUG)

### listDir `PROOT_DIR listDir(
    IN LPWSTR StartPath,
    IN BOOL   SubDirs,
    IN BOOL   FilesOnly,
    I...`
- Defined: `payloads/Demon/src/core/Win32.c:1477`
- Doc: endif

## payloads/Demon/src/crypt/AesCrypt.c

### KeyExpansion `void KeyExpansion(UINT8* RoundKey, const UINT8* Key)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:46`
- Doc: define getSBoxValue(num) (sbox[(num)])

### AesInit `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:102`

### AddRoundKey `static void AddRoundKey(UINT8 round, state_t* state, const UINT8* RoundKey)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:111`
- Doc: This function adds the round key to state. The round key is added to the state by an XOR function.

### SubBytes `static void SubBytes(state_t* state)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:125`
- Doc: The SubBytes Function Substitutes the values in the state matrix with values in an S-box.

### ShiftRows `static void ShiftRows(state_t* state)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:140`
- Doc: The ShiftRows() function shifts the rows in the state to the left. Each row is shifted with different offset. Offset = R

### xtime `static UINT8 xtime(UINT8 x)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:167`

### MixColumns `static void MixColumns(state_t* state)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:174`
- Doc: MixColumns function mixes the columns of the state matrix

### AesXCryptBuffer `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:216`
- Doc: if defined(CTR) && (CTR == 1)

## payloads/Demon/src/inject/Inject.c

### Inject `DWORD Inject(
    IN BYTE   Method,
    IN HANDLE Handle,
    IN DWORD  Pid,
    IN BOOL   x64,
 ...`
- Defined: `payloads/Demon/src/inject/Inject.c:27`
- Doc: Inject code into a remote process  @param Method    thread execution method. @param Handle    opened handle to the remot

### PRINTF `PRINTF( "[INJECT] Using specified process handle: %x\n", Process )
    }

    /* check the archit...`
- Defined: `payloads/Demon/src/inject/Inject.c:64`

### PRINTF `PRINTF( "[INJECT] Allocated memory in the remote process: %p\n", Memory )
    }

    /* write pay...`
- Defined: `payloads/Demon/src/inject/Inject.c:91`

### PRINTF `PRINTF( "[INJECT] Wrote payload into remote process: %d written\n", Size )
    }

    /* change a...`
- Defined: `payloads/Demon/src/inject/Inject.c:99`

### PUTS `PUTS( "[INJECT] Changed memory protection from RW to RX" )
    }

    /* check if any args has be...`
- Defined: `payloads/Demon/src/inject/Inject.c:107`

### PRINTF `PRINTF( "[INJECT] Allocated argument memory in the remote process: %p\n", Param )
        }

    ...`
- Defined: `payloads/Demon/src/inject/Inject.c:118`

### PRINTF `PRINTF( "[INJECT] Wrote argument into remote process: %d written\n", Argc )
        }
    }

    ...`
- Defined: `payloads/Demon/src/inject/Inject.c:126`

### PRINTF `PRINTF( "[INJECT] Failed to create a new thread: %d\n", NtGetLastError() )
    }

END:
    PUTS( ...`
- Defined: `payloads/Demon/src/inject/Inject.c:135`

### DllInjectReflective `DWORD DllInjectReflective( HANDLE hTargetProcess, LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuff...`
- Defined: `payloads/Demon/src/inject/Inject.c:171`

### PRINTF `PRINTF( "Params: Size:[%d] Pointer:[%p]\n", ParamSize, Parameter )
    if ( ParamSize > 0 )`
- Defined: `payloads/Demon/src/inject/Inject.c:232`
- Doc: Alloc and write remote params

### PRINTF `PRINTF( "ctx->Parameter: %p\n", ctx->Parameter )

                if ( ! ThreadCreate( THREAD_MET...`
- Defined: `payloads/Demon/src/inject/Inject.c:278`

### DllSpawnReflective `DWORD DllSpawnReflective( LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuffer, DWORD DllLength, PVO...`
- Defined: `payloads/Demon/src/inject/Inject.c:321`

## payloads/Demon/src/inject/InjectUtil.c

### Rva2Offset `DWORD Rva2Offset( DWORD dwRva, UINT_PTR uiBaseAddress )`
- Defined: `payloads/Demon/src/inject/InjectUtil.c:11`
- Doc: endif

### GetReflectiveLoaderOffset `DWORD GetReflectiveLoaderOffset( PVOID ReflectiveLdrAddr )`
- Defined: `payloads/Demon/src/inject/InjectUtil.c:35`

### GetPeArch `DWORD GetPeArch( PVOID PeBytes )`
- Defined: `payloads/Demon/src/inject/InjectUtil.c:71`

## payloads/Demon/src/main/MainDll.c

### Start `DLLEXPORT VOID Start(  )`
- Defined: `payloads/Demon/src/main/MainDll.c:8`
- Doc: Export this for rundll32 or any other program that requires and exported functions... * TODO: make this function name op

### DllMain `DLLEXPORT BOOL WINAPI DllMain(
    IN     HINSTANCE hDllBase,
    IN     DWORD     Reason,
    _I...`
- Defined: `payloads/Demon/src/main/MainDll.c:24`
- Doc: /* prevent exiting if started using rundll32 or something PVOID Kernel32  = LdrModulePeb( H_MODULE_KERNEL32 ); VOID ( WI

## payloads/Demon/src/main/MainExe.c

### WinMain `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )`
- Defined: `payloads/Demon/src/main/MainExe.c:2`
- Doc: include <Demon.h>

## payloads/Demon/src/main/MainSvc.c

### WinMain `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )`
- Defined: `payloads/Demon/src/main/MainSvc.c:16`
- Doc: /* Service handle and status variable SERVICE_STATUS_HANDLE StatusHandle = { 0 }; SERVICE_STATUS        SvcStatus    = {

### SvcMain `VOID WINAPI SvcMain( DWORD dwArgc, LPTSTR* Argv )`
- Defined: `payloads/Demon/src/main/MainSvc.c:31`
- Doc: { PRINTF( "WinMain (Service Main): hInstance:[%p]\n", hInstance ) SERVICE_TABLE_ENTRY DispatchTable[ ] = { { SERVICE_NAM

### SrvCtrlHandler `VOID WINAPI SrvCtrlHandler( DWORD CtrlCode )`
- Defined: `payloads/Demon/src/main/MainSvc.c:40`

## payloads/DllLdr/Scripts/extract.py

### main `def main(options)`
- Defined: `payloads/DllLdr/Scripts/extract.py:8`

## payloads/DllLdr/Source/Entry.c

### KaynLoader `DLLEXPORT VOID KaynLoader( LPVOID lpParameter )`
- Defined: `payloads/DllLdr/Source/Entry.c:4`
- Doc: include <Core.h> include <Native.h> include <ntdef.h>

### KaynCaller `NAKED LPVOID KaynCaller( PVOID StartAddress )`
- Defined: `payloads/DllLdr/Source/Entry.c:143`

### Memcpy `NAKED VOID Memcpy( PVOID Destination, PVOID source, SIZE_T Size )`
- Defined: `payloads/DllLdr/Source/Entry.c:165`

### KGetModuleByHash `PVOID KGetModuleByHash( DWORD ModuleHash )`
- Defined: `payloads/DllLdr/Source/Entry.c:184`

### CopyDotStr `FORCE_INLINE UINT32 CopyDotStr( PCHAR String )`
- Defined: `payloads/DllLdr/Source/Entry.c:205`

### KGetProcAddressByHash `PVOID KGetProcAddressByHash( PINSTANCE Instance, PVOID DllModuleBase, DWORD FunctionHash, DWORD O...`
- Defined: `payloads/DllLdr/Source/Entry.c:214`

### KResolveIAT `VOID KResolveIAT( PINSTANCE Instance, LPVOID KaynImage, LPVOID IatDir )`
- Defined: `payloads/DllLdr/Source/Entry.c:264`

### KReAllocSections `VOID KReAllocSections( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir )`
- Defined: `payloads/DllLdr/Source/Entry.c:305`

### KLoadLibrary `PVOID KLoadLibrary( PINSTANCE Instance, LPSTR ModuleName )`
- Defined: `payloads/DllLdr/Source/Entry.c:330`

### KHashString `DWORD KHashString( PVOID String, SIZE_T Length )`
- Defined: `payloads/DllLdr/Source/Entry.c:363`
- Doc: -------------------------------- ---- String & Data functions ---- ---------------------------------

### KStringLengthA `SIZE_T KStringLengthA( LPCSTR String )`
- Defined: `payloads/DllLdr/Source/Entry.c:392`

### KStringLengthW `SIZE_T KStringLengthW(LPCWSTR String)`
- Defined: `payloads/DllLdr/Source/Entry.c:399`

### KCharStringToWCharString `SIZE_T KCharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )`
- Defined: `payloads/DllLdr/Source/Entry.c:408`

## payloads/Shellcode/Scripts/Hasher.c

### Hash `long Hash( char* String )`
- Defined: `payloads/Shellcode/Scripts/Hasher.c:3`
- Doc: include <stdio.h> include <ctype.h>

### ToUpperString `void ToUpperString(char * temp)`
- Defined: `payloads/Shellcode/Scripts/Hasher.c:14`

### main `int main(int argc, char** argv)`
- Defined: `payloads/Shellcode/Scripts/Hasher.c:23`

## payloads/Shellcode/Source/Entry.c

### SEC `SEC( text, B ) VOID Entry( VOID )`
- Defined: `payloads/Shellcode/Source/Entry.c:10`
- Doc: ifdef _WIN64 define IMAGE_REL_TYPE IMAGE_REL_BASED_DIR64 else define IMAGE_REL_TYPE IMAGE_REL_BASED_HIGHLOW endif

### KaynLdrReloc `VOID KaynLdrReloc( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir, DWORD KHdrSize )`
- Defined: `payloads/Shellcode/Source/Entry.c:103`

## payloads/Shellcode/Source/Utils.c

### SEC `SEC( text, B ) UINT_PTR HashString( LPVOID String, UINT_PTR Length )`
- Defined: `payloads/Shellcode/Source/Utils.c:3`
- Doc: include <Utils.h> include <Macro.h>

## payloads/Shellcode/Source/Win32.c

### SEC `SEC( text, B ) UINT_PTR LdrModulePeb( UINT_PTR hModuleHash )`
- Defined: `payloads/Shellcode/Source/Win32.c:4`
- Doc: include <Win32.h> include <Utils.h> include <winternl.h>

### SEC `SEC( text, B ) PVOID LdrFunctionAddr( UINT_PTR Module, UINT_PTR FunctionHash )`
- Defined: `payloads/Shellcode/Source/Win32.c:22`

## teamserver/cmd/cmd.go

### init `func init(`
- Defined: `teamserver/cmd/cmd.go:29`
- Doc: init all flags
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/main.go`

### teamserverFunc `func teamserverFunc(`
- Defined: `teamserver/cmd/cmd.go:47`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/main.go`

### startMenu `func startMenu(`
- Defined: `teamserver/cmd/cmd.go:61`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/main.go`

## teamserver/cmd/server/agent.go

### AgentUpdate `func (t *Teamserver) AgentUpdate(`
- Defined: `teamserver/cmd/server/agent.go:16`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### Died `func (t *Teamserver) Died(`
- Defined: `teamserver/cmd/server/agent.go:23`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### UnlinkFromAll `func (t *Teamserver) UnlinkFromAll(`
- Defined: `teamserver/cmd/server/agent.go:30`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### ParentOf `func (t *Teamserver) ParentOf(`
- Defined: `teamserver/cmd/server/agent.go:53`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### LinksOf `func (t *Teamserver) LinksOf(`
- Defined: `teamserver/cmd/server/agent.go:60`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### LinkAdd `func (t *Teamserver) LinkAdd(`
- Defined: `teamserver/cmd/server/agent.go:66`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### LinkRemove `func (t *Teamserver) LinkRemove(`
- Defined: `teamserver/cmd/server/agent.go:78`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentHasDied `func (t *Teamserver) AgentHasDied(`
- Defined: `teamserver/cmd/server/agent.go:102`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentAdd `func (t *Teamserver) AgentAdd(`
- Defined: `teamserver/cmd/server/agent.go:108`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentSendNotify `func (t *Teamserver) AgentSendNotify(`
- Defined: `teamserver/cmd/server/agent.go:123`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentCallbackSize `func (t *Teamserver) AgentCallbackSize(`
- Defined: `teamserver/cmd/server/agent.go:138`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentInstance `func (t *Teamserver) AgentInstance(`
- Defined: `teamserver/cmd/server/agent.go:155`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentLastTimeCalled `func (t *Teamserver) AgentLastTimeCalled(`
- Defined: `teamserver/cmd/server/agent.go:166`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentExist `func (t *Teamserver) AgentExist(`
- Defined: `teamserver/cmd/server/agent.go:183`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentConsole `func (t *Teamserver) AgentConsole(`
- Defined: `teamserver/cmd/server/agent.go:198`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### PythonModuleCallback `func (t *Teamserver) PythonModuleCallback(`
- Defined: `teamserver/cmd/server/agent.go:208`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentCallback `func (t *Teamserver) AgentCallback(`
- Defined: `teamserver/cmd/server/agent.go:220`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### SendLogs `func (t *Teamserver) SendLogs(`
- Defined: `teamserver/cmd/server/agent.go:233`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### GetDotNetPipeTemplate `func (t *Teamserver) GetDotNetPipeTemplate(`
- Defined: `teamserver/cmd/server/agent.go:237`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

## teamserver/cmd/server/dispatch.go

### DispatchEvent `func (t *Teamserver) DispatchEvent(`
- Defined: `teamserver/cmd/server/dispatch.go:20`
- Depends on: `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

## teamserver/cmd/server/listener.go

### ListenerStart `func (t *Teamserver) ListenerStart(`
- Defined: `teamserver/cmd/server/listener.go:19`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerExist `func (t *Teamserver) ListenerExist(`
- Defined: `teamserver/cmd/server/listener.go:113`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerGetInfo `func (t *Teamserver) ListenerGetInfo(`
- Defined: `teamserver/cmd/server/listener.go:124`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerRemove `func (t *Teamserver) ListenerRemove(`
- Defined: `teamserver/cmd/server/listener.go:144`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerEdit `func (t *Teamserver) ListenerEdit(`
- Defined: `teamserver/cmd/server/listener.go:192`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerAdd `func (t *Teamserver) ListenerAdd(`
- Defined: `teamserver/cmd/server/listener.go:220`
- Doc: ListenerAdd creates a package for the client that a new listener has been added.
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerServiceExc2Add `func (t *Teamserver) ListenerServiceExc2Add(`
- Defined: `teamserver/cmd/server/listener.go:337`
- Doc: ListenerServiceExc2Add adds an external c2 listener that has been started from a service script to the teamserver listen
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerStartNotify `func (t *Teamserver) ListenerStartNotify(`
- Defined: `teamserver/cmd/server/listener.go:378`
- Doc: ListenerStartNotify Notifies the clients of a new listener that is available to use.
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

## teamserver/cmd/server/service.go

### ServiceAgent `func (t *Teamserver) ServiceAgent(`
- Defined: `teamserver/cmd/server/service.go:9`
- Depends on: `teamserver/pkg/logger/logger.go`

### ServiceAgentExist `func (t *Teamserver) ServiceAgentExist(`
- Defined: `teamserver/cmd/server/service.go:20`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/cmd/server/teamserver.go

### NewTeamserver `func NewTeamserver(`
- Defined: `teamserver/cmd/server/teamserver.go:37`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### SetServerFlags `func (t *Teamserver) SetServerFlags(`
- Defined: `teamserver/cmd/server/teamserver.go:48`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### Start `func (t *Teamserver) Start(`
- Defined: `teamserver/cmd/server/teamserver.go:52`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### handleRequest `func (t *Teamserver) handleRequest(`
- Defined: `teamserver/cmd/server/teamserver.go:497`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### SetProfile `func (t *Teamserver) SetProfile(`
- Defined: `teamserver/cmd/server/teamserver.go:626`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### ClientAuthenticate `func (t *Teamserver) ClientAuthenticate(`
- Defined: `teamserver/cmd/server/teamserver.go:637`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EventBroadcast `func (t *Teamserver) EventBroadcast(`
- Defined: `teamserver/cmd/server/teamserver.go:690`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EventNewDemon `func (t *Teamserver) EventNewDemon(`
- Defined: `teamserver/cmd/server/teamserver.go:709`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EventAgentMark `func (t *Teamserver) EventAgentMark(`
- Defined: `teamserver/cmd/server/teamserver.go:713`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EventListenerError `func (t *Teamserver) EventListenerError(`
- Defined: `teamserver/cmd/server/teamserver.go:720`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### SendEvent `func (t *Teamserver) SendEvent(`
- Defined: `teamserver/cmd/server/teamserver.go:741`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### RemoveClient `func (t *Teamserver) RemoveClient(`
- Defined: `teamserver/cmd/server/teamserver.go:773`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EventAppend `func (t *Teamserver) EventAppend(`
- Defined: `teamserver/cmd/server/teamserver.go:797`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EventRemove `func (t *Teamserver) EventRemove(`
- Defined: `teamserver/cmd/server/teamserver.go:812`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### SendAllPackagesToNewClient `func (t *Teamserver) SendAllPackagesToNewClient(`
- Defined: `teamserver/cmd/server/teamserver.go:818`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### FindSystemPackages `func (t *Teamserver) FindSystemPackages(`
- Defined: `teamserver/cmd/server/teamserver.go:842`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EndpointAdd `func (t *Teamserver) EndpointAdd(`
- Defined: `teamserver/cmd/server/teamserver.go:933`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EndpointRemove `func (t *Teamserver) EndpointRemove(`
- Defined: `teamserver/cmd/server/teamserver.go:945`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

## teamserver/main.go

### main `func main(`
- Defined: `teamserver/main.go:6`
- Depends on: `teamserver/cmd/cmd.go`, `teamserver/pkg/logger/logger.go`

## teamserver/pkg/agent/agent.go

### BuildPayloadMessage `func BuildPayloadMessage(`
- Defined: `teamserver/pkg/agent/agent.go:29`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ParseHeader `func ParseHeader(`
- Defined: `teamserver/pkg/agent/agent.go:181`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### RegisterInfoToInstance `func RegisterInfoToInstance(`
- Defined: `teamserver/pkg/agent/agent.go:215`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ParseDemonRegisterRequest `func ParseDemonRegisterRequest(`
- Defined: `teamserver/pkg/agent/agent.go:328`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### IsKnownRequestID `func (a *Agent) IsKnownRequestID(`
- Defined: `teamserver/pkg/agent/agent.go:609`
- Doc: check that the request the agent is valid
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### AddRequest `func (a *Agent) AddRequest(`
- Defined: `teamserver/pkg/agent/agent.go:632`
- Doc: the operator added a new request/command
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### RequestCompleted `func (a *Agent) RequestCompleted(`
- Defined: `teamserver/pkg/agent/agent.go:638`
- Doc: after a request has been completed, we can forget about the RequestID so that it is no longer valid
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### AddJobToQueue `func (a *Agent) AddJobToQueue(`
- Defined: `teamserver/pkg/agent/agent.go:647`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### GetQueuedJobs `func (a *Agent) GetQueuedJobs(`
- Defined: `teamserver/pkg/agent/agent.go:661`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### UpdateLastCallback `func (a *Agent) UpdateLastCallback(`
- Defined: `teamserver/pkg/agent/agent.go:739`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PivotAddJob `func (a *Agent) PivotAddJob(`
- Defined: `teamserver/pkg/agent/agent.go:746`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### DownloadAdd `func (a *Agent) DownloadAdd(`
- Defined: `teamserver/pkg/agent/agent.go:816`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### DownloadWrite `func (a *Agent) DownloadWrite(`
- Defined: `teamserver/pkg/agent/agent.go:865`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### DownloadClose `func (a *Agent) DownloadClose(`
- Defined: `teamserver/pkg/agent/agent.go:888`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### DownloadGet `func (a *Agent) DownloadGet(`
- Defined: `teamserver/pkg/agent/agent.go:902`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdNew `func (a *Agent) PortFwdNew(`
- Defined: `teamserver/pkg/agent/agent.go:911`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdGet `func (a *Agent) PortFwdGet(`
- Defined: `teamserver/pkg/agent/agent.go:929`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdIsOpen `func (a *Agent) PortFwdIsOpen(`
- Defined: `teamserver/pkg/agent/agent.go:948`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdOpen `func (a *Agent) PortFwdOpen(`
- Defined: `teamserver/pkg/agent/agent.go:958`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdWrite `func (a *Agent) PortFwdWrite(`
- Defined: `teamserver/pkg/agent/agent.go:979`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdRead `func (a *Agent) PortFwdRead(`
- Defined: `teamserver/pkg/agent/agent.go:997`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdClose `func (a *Agent) PortFwdClose(`
- Defined: `teamserver/pkg/agent/agent.go:1023`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### SocksClientAdd `func (a *Agent) SocksClientAdd(`
- Defined: `teamserver/pkg/agent/agent.go:1053`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### SocksClientGet `func (a *Agent) SocksClientGet(`
- Defined: `teamserver/pkg/agent/agent.go:1073`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### SocksClientRead `func (a *Agent) SocksClientRead(`
- Defined: `teamserver/pkg/agent/agent.go:1096`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### SocksClientClose `func (a *Agent) SocksClientClose(`
- Defined: `teamserver/pkg/agent/agent.go:1130`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### SocksServerRemove `func (a *Agent) SocksServerRemove(`
- Defined: `teamserver/pkg/agent/agent.go:1163`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ToMap `func (a *Agent) ToMap(`
- Defined: `teamserver/pkg/agent/agent.go:1193`
- Doc: ToMap returns the agent info as a map
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ToJson `func (a *Agent) ToJson(`
- Defined: `teamserver/pkg/agent/agent.go:1224`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### AgentsAppend `func (agents *Agents) AgentsAppend(`
- Defined: `teamserver/pkg/agent/agent.go:1238`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### getWindowsVersionString `func getWindowsVersionString(`
- Defined: `teamserver/pkg/agent/agent.go:1243`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

## teamserver/pkg/agent/demons.go

### UploadMemFileInChunks `func (a *Agent) UploadMemFileInChunks(`
- Defined: `teamserver/pkg/agent/demons.go:31`
- Doc: we upload heavy files to the implant in chunks, so SMB agents can handle the size
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/socks/socks.go`, `teamserver/pkg/utils/utils.go`

### TeamserverTaskPrepare `func (a *Agent) TeamserverTaskPrepare(`
- Defined: `teamserver/pkg/agent/demons.go:64`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/socks/socks.go`, `teamserver/pkg/utils/utils.go`

### TaskPrepare `func (a *Agent) TaskPrepare(`
- Defined: `teamserver/pkg/agent/demons.go:128`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/socks/socks.go`, `teamserver/pkg/utils/utils.go`

### TaskDispatch `func (a *Agent) TaskDispatch(`
- Defined: `teamserver/pkg/agent/demons.go:2285`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/socks/socks.go`, `teamserver/pkg/utils/utils.go`

### Console `func (a *Agent) Console(`
- Defined: `teamserver/pkg/agent/demons.go:6430`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/socks/socks.go`, `teamserver/pkg/utils/utils.go`

## teamserver/pkg/common/builder/builder.go

### NewBuilder `func NewBuilder(`
- Defined: `teamserver/pkg/common/builder/builder.go:141`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetSilent `func (b *Builder) SetSilent(`
- Defined: `teamserver/pkg/common/builder/builder.go:213`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### Build `func (b *Builder) Build(`
- Defined: `teamserver/pkg/common/builder/builder.go:217`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetListener `func (b *Builder) SetListener(`
- Defined: `teamserver/pkg/common/builder/builder.go:459`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetPatchConfig `func (b *Builder) SetPatchConfig(`
- Defined: `teamserver/pkg/common/builder/builder.go:464`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetFormat `func (b *Builder) SetFormat(`
- Defined: `teamserver/pkg/common/builder/builder.go:481`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetArch `func (b *Builder) SetArch(`
- Defined: `teamserver/pkg/common/builder/builder.go:485`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetConfig `func (b *Builder) SetConfig(`
- Defined: `teamserver/pkg/common/builder/builder.go:489`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetOutputPath `func (b *Builder) SetOutputPath(`
- Defined: `teamserver/pkg/common/builder/builder.go:501`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetExtension `func (b *Builder) SetExtension(`
- Defined: `teamserver/pkg/common/builder/builder.go:505`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### GetOutputPath `func (b *Builder) GetOutputPath(`
- Defined: `teamserver/pkg/common/builder/builder.go:509`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### Patch `func (b *Builder) Patch(`
- Defined: `teamserver/pkg/common/builder/builder.go:513`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### PatchConfig `func (b *Builder) PatchConfig(`
- Defined: `teamserver/pkg/common/builder/builder.go:561`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### GetPayloadBytes `func (b *Builder) GetPayloadBytes(`
- Defined: `teamserver/pkg/common/builder/builder.go:1024`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### Cmd `func (b *Builder) Cmd(`
- Defined: `teamserver/pkg/common/builder/builder.go:1064`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### CompileCmd `func (b *Builder) CompileCmd(`
- Defined: `teamserver/pkg/common/builder/builder.go:1090`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### GetListenerDefines `func (b *Builder) GetListenerDefines(`
- Defined: `teamserver/pkg/common/builder/builder.go:1102`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### DeletePayload `func (b *Builder) DeletePayload(`
- Defined: `teamserver/pkg/common/builder/builder.go:1122`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

## teamserver/pkg/common/certs/https.go

### randomState `func randomState(`
- Defined: `teamserver/pkg/common/certs/https.go:115`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomLocality `func randomLocality(`
- Defined: `teamserver/pkg/common/certs/https.go:123`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomStreetAddress `func randomStreetAddress(`
- Defined: `teamserver/pkg/common/certs/https.go:132`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomProvinceLocalityStreetAddress `func randomProvinceLocalityStreetAddress(`
- Defined: `teamserver/pkg/common/certs/https.go:137`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomPostalCode `func randomPostalCode(`
- Defined: `teamserver/pkg/common/certs/https.go:144`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomSubject `func randomSubject(`
- Defined: `teamserver/pkg/common/certs/https.go:153`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomOrganization `func randomOrganization(`
- Defined: `teamserver/pkg/common/certs/https.go:166`
- Depends on: `teamserver/pkg/logger/logger.go`

### publicKey `func publicKey(`
- Defined: `teamserver/pkg/common/certs/https.go:182`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomInt `func randomInt(`
- Defined: `teamserver/pkg/common/certs/https.go:193`
- Depends on: `teamserver/pkg/logger/logger.go`

### pemBlockForKey `func pemBlockForKey(`
- Defined: `teamserver/pkg/common/certs/https.go:200`
- Depends on: `teamserver/pkg/logger/logger.go`

### generateCertificate `func generateCertificate(`
- Defined: `teamserver/pkg/common/certs/https.go:216`
- Depends on: `teamserver/pkg/logger/logger.go`

### HTTPSGenerateRSACertificate `func HTTPSGenerateRSACertificate(`
- Defined: `teamserver/pkg/common/certs/https.go:300`
- Doc: HTTPSGenerateRSACertificate - Generate a server certificate signed with a given CA
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/common/crypt/aes.go

### XCryptBytesAES256 `func XCryptBytesAES256(`
- Defined: `teamserver/pkg/common/crypt/aes.go:10`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/common/packer/packer.go

### NewPacker `func NewPacker(`
- Defined: `teamserver/pkg/common/packer/packer.go:22`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddInt64 `func (p *Packer) AddInt64(`
- Defined: `teamserver/pkg/common/packer/packer.go:29`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddInt32 `func (p *Packer) AddInt32(`
- Defined: `teamserver/pkg/common/packer/packer.go:37`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddInt `func (p *Packer) AddInt(`
- Defined: `teamserver/pkg/common/packer/packer.go:45`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddUInt32 `func (p *Packer) AddUInt32(`
- Defined: `teamserver/pkg/common/packer/packer.go:54`
- Doc: AddUInt32 use a much as possible this function
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddString `func (p *Packer) AddString(`
- Defined: `teamserver/pkg/common/packer/packer.go:62`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddWString `func (p *Packer) AddWString(`
- Defined: `teamserver/pkg/common/packer/packer.go:66`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddBytes `func (p *Packer) AddBytes(`
- Defined: `teamserver/pkg/common/packer/packer.go:70`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### Build `func (p *Packer) Build(`
- Defined: `teamserver/pkg/common/packer/packer.go:80`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### Buffer `func (p *Packer) Buffer(`
- Defined: `teamserver/pkg/common/packer/packer.go:95`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### Size `func (p *Packer) Size(`
- Defined: `teamserver/pkg/common/packer/packer.go:99`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddOwnSizeFirst `func (p *Packer) AddOwnSizeFirst(`
- Defined: `teamserver/pkg/common/packer/packer.go:103`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

## teamserver/pkg/common/parser/parser.go

### NewParser `func NewParser(`
- Defined: `teamserver/pkg/common/parser/parser.go:24`

### CanIRead `func (p *Parser) CanIRead(`
- Defined: `teamserver/pkg/common/parser/parser.go:31`

### ParseInt32 `func (p *Parser) ParseInt32(`
- Defined: `teamserver/pkg/common/parser/parser.go:82`

### ParseInt64 `func (p *Parser) ParseInt64(`
- Defined: `teamserver/pkg/common/parser/parser.go:106`

### ParseBool `func (p *Parser) ParseBool(`
- Defined: `teamserver/pkg/common/parser/parser.go:130`

### ParsePointer `func (p *Parser) ParsePointer(`
- Defined: `teamserver/pkg/common/parser/parser.go:154`

### SetBigEndian `func (p *Parser) SetBigEndian(`
- Defined: `teamserver/pkg/common/parser/parser.go:158`

### ParseBytes `func (p *Parser) ParseBytes(`
- Defined: `teamserver/pkg/common/parser/parser.go:162`

### ParseAtLeastBytes `func (p *Parser) ParseAtLeastBytes(`
- Defined: `teamserver/pkg/common/parser/parser.go:177`

### ParseUTF16String `func (p *Parser) ParseUTF16String(`
- Defined: `teamserver/pkg/common/parser/parser.go:189`

### ParseString `func (p *Parser) ParseString(`
- Defined: `teamserver/pkg/common/parser/parser.go:193`

### Length `func (p *Parser) Length(`
- Defined: `teamserver/pkg/common/parser/parser.go:197`

### Buffer `func (p *Parser) Buffer(`
- Defined: `teamserver/pkg/common/parser/parser.go:201`

### DecryptBuffer `func (p *Parser) DecryptBuffer(`
- Defined: `teamserver/pkg/common/parser/parser.go:205`

## teamserver/pkg/common/util.go

### ParseWorkingHours `func ParseWorkingHours(`
- Defined: `teamserver/pkg/common/util.go:26`
- Depends on: `teamserver/pkg/logger/logger.go`

### Bmp2Png `func Bmp2Png(`
- Defined: `teamserver/pkg/common/util.go:76`
- Depends on: `teamserver/pkg/logger/logger.go`

### DecodeUTF16 `func DecodeUTF16(`
- Defined: `teamserver/pkg/common/util.go:99`
- Depends on: `teamserver/pkg/logger/logger.go`

### EncodeUTF16 `func EncodeUTF16(`
- Defined: `teamserver/pkg/common/util.go:118`
- Depends on: `teamserver/pkg/logger/logger.go`

### EncodeUTF8 `func EncodeUTF8(`
- Defined: `teamserver/pkg/common/util.go:135`
- Depends on: `teamserver/pkg/logger/logger.go`

### ByteCountSI `func ByteCountSI(`
- Defined: `teamserver/pkg/common/util.go:144`
- Depends on: `teamserver/pkg/logger/logger.go`

### XorCipher `func XorCipher(`
- Defined: `teamserver/pkg/common/util.go:158`
- Depends on: `teamserver/pkg/logger/logger.go`

### RandomString `func RandomString(`
- Defined: `teamserver/pkg/common/util.go:166`
- Depends on: `teamserver/pkg/logger/logger.go`

### Int32ToLittle `func Int32ToLittle(`
- Defined: `teamserver/pkg/common/util.go:175`
- Depends on: `teamserver/pkg/logger/logger.go`

### StripNull `func StripNull(`
- Defined: `teamserver/pkg/common/util.go:181`
- Depends on: `teamserver/pkg/logger/logger.go`

### PercentageChange `func PercentageChange(`
- Defined: `teamserver/pkg/common/util.go:185`
- Depends on: `teamserver/pkg/logger/logger.go`

### IpStringToInt32 `func IpStringToInt32(`
- Defined: `teamserver/pkg/common/util.go:189`
- Depends on: `teamserver/pkg/logger/logger.go`

### Int32ToIpString `func Int32ToIpString(`
- Defined: `teamserver/pkg/common/util.go:198`
- Depends on: `teamserver/pkg/logger/logger.go`

### EpochTimeToSystemTime `func EpochTimeToSystemTime(`
- Defined: `teamserver/pkg/common/util.go:209`
- Depends on: `teamserver/pkg/logger/logger.go`

### GetRandomChar `func GetRandomChar(`
- Defined: `teamserver/pkg/common/util.go:222`
- Depends on: `teamserver/pkg/logger/logger.go`

### GeneratePipeName `func GeneratePipeName(`
- Defined: `teamserver/pkg/common/util.go:227`
- Doc: generate a PipeName from a name template
- Depends on: `teamserver/pkg/logger/logger.go`

### GetInterfaceIpv4Addr `func GetInterfaceIpv4Addr(`
- Defined: `teamserver/pkg/common/util.go:279`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/db/agents.go

### AgentAdd `func (db *DB) AgentAdd(`
- Defined: `teamserver/pkg/db/agents.go:12`

### AgentUpdate `func (db *DB) AgentUpdate(`
- Defined: `teamserver/pkg/db/agents.go:81`

### AgentHasDied `func (db *DB) AgentHasDied(`
- Defined: `teamserver/pkg/db/agents.go:145`

### AgentExist `func (db *DB) AgentExist(`
- Defined: `teamserver/pkg/db/agents.go:163`

### AgentRemove `func (db *DB) AgentRemove(`
- Defined: `teamserver/pkg/db/agents.go:192`

### AgentAll `func (db *DB) AgentAll(`
- Defined: `teamserver/pkg/db/agents.go:211`

## teamserver/pkg/db/db.go

### DatabaseNew `func DatabaseNew(`
- Defined: `teamserver/pkg/db/db.go:16`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### init `func (db *DB) init(`
- Defined: `teamserver/pkg/db/db.go:48`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### Existed `func (db *DB) Existed(`
- Defined: `teamserver/pkg/db/db.go:69`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### Path `func (db *DB) Path(`
- Defined: `teamserver/pkg/db/db.go:73`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

## teamserver/pkg/db/links.go

### LinkAdd `func (db *DB) LinkAdd(`
- Defined: `teamserver/pkg/db/links.go:8`

### LinkExist `func (db *DB) LinkExist(`
- Defined: `teamserver/pkg/db/links.go:46`

### ParentOf `func (db *DB) ParentOf(`
- Defined: `teamserver/pkg/db/links.go:75`

### LinksOf `func (db *DB) LinksOf(`
- Defined: `teamserver/pkg/db/links.go:104`

### LinkRemove `func (db *DB) LinkRemove(`
- Defined: `teamserver/pkg/db/links.go:136`

## teamserver/pkg/db/listeners.go

### ListenerAdd `func (db *DB) ListenerAdd(`
- Defined: `teamserver/pkg/db/listeners.go:8`

### ListenerExist `func (db *DB) ListenerExist(`
- Defined: `teamserver/pkg/db/listeners.go:46`

### ListenerAll `func (db *DB) ListenerAll(`
- Defined: `teamserver/pkg/db/listeners.go:66`

### ListenerCount `func (db *DB) ListenerCount(`
- Defined: `teamserver/pkg/db/listeners.go:107`

### ListenerNames `func (db *DB) ListenerNames(`
- Defined: `teamserver/pkg/db/listeners.go:126`

### ListenerRemove `func (db *DB) ListenerRemove(`
- Defined: `teamserver/pkg/db/listeners.go:152`

## teamserver/pkg/events/chatlog.go

### NewUserConnected `func (chatLog) NewUserConnected(`
- Defined: `teamserver/pkg/events/chatlog.go:11`

### UserDisconnected `func (chatLog) UserDisconnected(`
- Defined: `teamserver/pkg/events/chatlog.go:27`

## teamserver/pkg/events/demons.go

### NewDemon `func (demons) NewDemon(`
- Defined: `teamserver/pkg/events/demons.go:19`
- Depends on: `teamserver/pkg/logr/logr.go`

### DemonOutput `func (demons) DemonOutput(`
- Defined: `teamserver/pkg/events/demons.go:83`
- Depends on: `teamserver/pkg/logr/logr.go`

### CallBack `func (demons) CallBack(`
- Defined: `teamserver/pkg/events/demons.go:105`
- Depends on: `teamserver/pkg/logr/logr.go`

### MarkAs `func (demons) MarkAs(`
- Defined: `teamserver/pkg/events/demons.go:121`
- Depends on: `teamserver/pkg/logr/logr.go`

## teamserver/pkg/events/events.go

### Authenticated `func Authenticated(`
- Defined: `teamserver/pkg/events/events.go:22`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/service/service.go`

### UserAlreadyExits `func UserAlreadyExits(`
- Defined: `teamserver/pkg/events/events.go:56`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/service/service.go`

### UserDoNotExists `func UserDoNotExists(`
- Defined: `teamserver/pkg/events/events.go:72`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/service/service.go`

### SendProfile `func SendProfile(`
- Defined: `teamserver/pkg/events/events.go:88`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/service/service.go`

## teamserver/pkg/events/gate.go

### SendStageless `func (g gate) SendStageless(`
- Defined: `teamserver/pkg/events/gate.go:12`

### SendConsoleMessage `func (g gate) SendConsoleMessage(`
- Defined: `teamserver/pkg/events/gate.go:30`

## teamserver/pkg/events/listeners.go

### ListenerAdd `func (listeners) ListenerAdd(`
- Defined: `teamserver/pkg/events/listeners.go:15`
- Depends on: `teamserver/pkg/handlers/handlers.go`

### ListenerEdit `func (listeners) ListenerEdit(`
- Defined: `teamserver/pkg/events/listeners.go:97`
- Depends on: `teamserver/pkg/handlers/handlers.go`

### ListenerError `func (listeners) ListenerError(`
- Defined: `teamserver/pkg/events/listeners.go:154`
- Depends on: `teamserver/pkg/handlers/handlers.go`

### ListenerRemove `func (listeners) ListenerRemove(`
- Defined: `teamserver/pkg/events/listeners.go:173`
- Depends on: `teamserver/pkg/handlers/handlers.go`

### ListenerMark `func (listeners) ListenerMark(`
- Defined: `teamserver/pkg/events/listeners.go:187`
- Depends on: `teamserver/pkg/handlers/handlers.go`

## teamserver/pkg/events/service.go

### AgentRegister `func (service) AgentRegister(`
- Defined: `teamserver/pkg/events/service.go:11`

### ListenerRegister `func (service) ListenerRegister(`
- Defined: `teamserver/pkg/events/service.go:25`

## teamserver/pkg/events/teamserver.go

### Logger `func (teamserver) Logger(`
- Defined: `teamserver/pkg/events/teamserver.go:11`

### Profile `func (teamserver) Profile(`
- Defined: `teamserver/pkg/events/teamserver.go:25`

## teamserver/pkg/handlers/external.go

### NewExternal `func NewExternal(`
- Defined: `teamserver/pkg/handlers/external.go:15`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`

### Start `func (e *External) Start(`
- Defined: `teamserver/pkg/handlers/external.go:24`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`

### Request `func (e *External) Request(`
- Defined: `teamserver/pkg/handlers/external.go:37`
- Doc: Request The way the external c2 handles or parses the request is like the HTTP listener. Only one agent package can be p
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`

## teamserver/pkg/handlers/handlers.go

### parseAgentRequest `func parseAgentRequest(`
- Defined: `teamserver/pkg/handlers/handlers.go:23`
- Doc: parseAgentRequest parses the agent request and handles the given data. return 2 types. Response is the data/bytes once t
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/listeners.go`

### handleDemonAgent `func handleDemonAgent(`
- Defined: `teamserver/pkg/handlers/handlers.go:56`
- Doc: handleDemonAgent parse the demon agent request return 2 types:  Response bytes.Buffer Success  bool
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/listeners.go`

### handleServiceAgent `func handleServiceAgent(`
- Defined: `teamserver/pkg/handlers/handlers.go:311`
- Doc: handleServiceAgent handles and parses a service agent request return 2 types:  Response bytes.Buffer Success  bool
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/listeners.go`

### notifyTaskSize `func notifyTaskSize(`
- Defined: `teamserver/pkg/handlers/handlers.go:349`
- Doc: notifyTaskSize notifies every connected operator client how much we send to agent.
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/listeners.go`

## teamserver/pkg/handlers/http.go

### NewConfigHttp `func NewConfigHttp(`
- Defined: `teamserver/pkg/handlers/http.go:24`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`

### generateCertFiles `func (h *HTTP) generateCertFiles(`
- Defined: `teamserver/pkg/handlers/http.go:32`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`

### fake404 `func (h *HTTP) fake404(`
- Defined: `teamserver/pkg/handlers/http.go:80`
- Doc: fake nginx 404 page
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`

### request `func (h *HTTP) request(`
- Defined: `teamserver/pkg/handlers/http.go:93`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`

### Start `func (h *HTTP) Start(`
- Defined: `teamserver/pkg/handlers/http.go:203`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`

### Stop `func (h *HTTP) Stop(`
- Defined: `teamserver/pkg/handlers/http.go:277`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`

## teamserver/pkg/handlers/smb.go

### NewPivotSmb `func NewPivotSmb(`
- Defined: `teamserver/pkg/handlers/smb.go:8`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`

### Start `func (s *SMB) Start(`
- Defined: `teamserver/pkg/handlers/smb.go:14`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`

## teamserver/pkg/logger/global.go

### init `func init(`
- Defined: `teamserver/pkg/logger/global.go:11`

### NewLogger `func NewLogger(`
- Defined: `teamserver/pkg/logger/global.go:15`

### Info `func Info(`
- Defined: `teamserver/pkg/logger/global.go:27`

### Good `func Good(`
- Defined: `teamserver/pkg/logger/global.go:31`

### Debug `func Debug(`
- Defined: `teamserver/pkg/logger/global.go:35`

### DebugError `func DebugError(`
- Defined: `teamserver/pkg/logger/global.go:39`

### Warn `func Warn(`
- Defined: `teamserver/pkg/logger/global.go:43`

### Error `func Error(`
- Defined: `teamserver/pkg/logger/global.go:47`

### Fatal `func Fatal(`
- Defined: `teamserver/pkg/logger/global.go:51`

### Panic `func Panic(`
- Defined: `teamserver/pkg/logger/global.go:55`

### SetDebug `func SetDebug(`
- Defined: `teamserver/pkg/logger/global.go:59`

### ShowTime `func ShowTime(`
- Defined: `teamserver/pkg/logger/global.go:63`

### SetStdOut `func SetStdOut(`
- Defined: `teamserver/pkg/logger/global.go:67`

## teamserver/pkg/logger/logger.go

### FunctionTrace `func FunctionTrace(`
- Defined: `teamserver/pkg/logger/logger.go:15`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Info `func (logger *Logger) Info(`
- Defined: `teamserver/pkg/logger/logger.go:43`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Good `func (logger *Logger) Good(`
- Defined: `teamserver/pkg/logger/logger.go:52`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Debug `func (logger *Logger) Debug(`
- Defined: `teamserver/pkg/logger/logger.go:61`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### DebugError `func (logger *Logger) DebugError(`
- Defined: `teamserver/pkg/logger/logger.go:74`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Warn `func (logger *Logger) Warn(`
- Defined: `teamserver/pkg/logger/logger.go:87`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Error `func (logger *Logger) Error(`
- Defined: `teamserver/pkg/logger/logger.go:96`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Fatal `func (logger *Logger) Fatal(`
- Defined: `teamserver/pkg/logger/logger.go:105`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Panic `func (logger *Logger) Panic(`
- Defined: `teamserver/pkg/logger/logger.go:115`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### SetDebug `func (logger *Logger) SetDebug(`
- Defined: `teamserver/pkg/logger/logger.go:125`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### ShowTime `func (logger *Logger) ShowTime(`
- Defined: `teamserver/pkg/logger/logger.go:129`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

## teamserver/pkg/logr/demon.go

### AddAgentInput `func (l Logr) AddAgentInput(`
- Defined: `teamserver/pkg/logr/demon.go:15`
- Depends on: `teamserver/pkg/logger/logger.go`

### AddAgentRaw `func (l Logr) AddAgentRaw(`
- Defined: `teamserver/pkg/logr/demon.go:50`
- Depends on: `teamserver/pkg/logger/logger.go`

### DemonAddOutput `func (l Logr) DemonAddOutput(`
- Defined: `teamserver/pkg/logr/demon.go:82`
- Depends on: `teamserver/pkg/logger/logger.go`

### DemonAddDownloadedFile `func (l Logr) DemonAddDownloadedFile(`
- Defined: `teamserver/pkg/logr/demon.go:134`
- Depends on: `teamserver/pkg/logger/logger.go`

### DemonSaveScreenshot `func (l Logr) DemonSaveScreenshot(`
- Defined: `teamserver/pkg/logr/demon.go:177`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/logr/listener.go

### ListenerAddKeyCert `func (l Logr) ListenerAddKeyCert(`
- Defined: `teamserver/pkg/logr/listener.go:3`

## teamserver/pkg/logr/logr.go

### NewLogr `func NewLogr(`
- Defined: `teamserver/pkg/logr/logr.go:21`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/events/demons.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/service/service.go`

## teamserver/pkg/logr/server.go

### strip `func strip(`
- Defined: `teamserver/pkg/logr/server.go:12`
- Depends on: `teamserver/pkg/logger/logger.go`

### ServerStdOutInit `func (l Logr) ServerStdOutInit(`
- Defined: `teamserver/pkg/logr/server.go:21`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/packager/packages.go

### NewPackager `func NewPackager(`
- Defined: `teamserver/pkg/packager/packages.go:9`
- Depends on: `teamserver/pkg/logger/logger.go`

### CreatePackage `func (p Packager) CreatePackage(`
- Defined: `teamserver/pkg/packager/packages.go:13`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/profile/profile.go

### NewProfile `func NewProfile(`
- Defined: `teamserver/pkg/profile/profile.go:13`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/service/types.go`

### SetProfile `func (p *Profile) SetProfile(`
- Defined: `teamserver/pkg/profile/profile.go:17`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/service/types.go`

### ServerHost `func (p *Profile) ServerHost(`
- Defined: `teamserver/pkg/profile/profile.go:32`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/service/types.go`

### ServerPort `func (p *Profile) ServerPort(`
- Defined: `teamserver/pkg/profile/profile.go:39`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/service/types.go`

### ListOfUsernames `func (p *Profile) ListOfUsernames(`
- Defined: `teamserver/pkg/profile/profile.go:46`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/service/types.go`

## teamserver/pkg/profile/yaotl/diagnostic.go

### Error `func (d *Diagnostic) Error(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic.go:76`
- Doc: error implementation, so that diagnostics can be returned via APIs that normally deal in vanilla Go errors.  This presen

### Error `func (d Diagnostics) Error(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic.go:82`
- Doc: error implementation, so that sets of diagnostics can be returned via APIs that normally deal in vanilla Go errors.

### Append `func (d Diagnostics) Append(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic.go:104`
- Doc: Append appends a new error to a Diagnostics and return the whole Diagnostics.  This is provided as a convenience for ret

### Extend `func (d Diagnostics) Extend(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic.go:113`
- Doc: Extend concatenates the given Diagnostics with the receiver and returns the whole new Diagnostics.  This is similar to A

### HasErrors `func (d Diagnostics) HasErrors(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic.go:119`
- Doc: HasErrors returns true if the receiver contains any diagnostics of severity DiagError.

### Errs `func (d Diagnostics) Errs(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic.go:128`

## teamserver/pkg/profile/yaotl/diagnostic_text.go

### NewDiagnosticTextWriter `func NewDiagnosticTextWriter(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic_text.go:34`
- Doc: NewDiagnosticTextWriter creates a DiagnosticWriter that writes diagnostics to the given writer as formatted text.  It is

### WriteDiagnostic `func (w *diagnosticTextWriter) WriteDiagnostic(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic_text.go:43`

### WriteDiagnostics `func (w *diagnosticTextWriter) WriteDiagnostics(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic_text.go:208`

### traversalStr `func (w *diagnosticTextWriter) traversalStr(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic_text.go:218`

### valueStr `func (w *diagnosticTextWriter) valueStr(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic_text.go:246`

### contextString `func contextString(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic_text.go:302`

## teamserver/pkg/profile/yaotl/didyoumean.go

### nameSuggestion `func nameSuggestion(`
- Defined: `teamserver/pkg/profile/yaotl/didyoumean.go:16`
- Doc: nameSuggestion tries to find a name from the given slice of suggested names that is close to the given name and returns 

## teamserver/pkg/profile/yaotl/eval_context.go

### NewChild `func (ctx *EvalContext) NewChild(`
- Defined: `teamserver/pkg/profile/yaotl/eval_context.go:17`
- Doc: NewChild returns a new EvalContext that is a child of the receiver.

### Parent `func (ctx *EvalContext) Parent(`
- Defined: `teamserver/pkg/profile/yaotl/eval_context.go:23`
- Doc: Parent returns the parent of the receiver, or nil if the receiver has no parent.

## teamserver/pkg/profile/yaotl/expr_call.go

### ExprCall `func ExprCall(`
- Defined: `teamserver/pkg/profile/yaotl/expr_call.go:14`
- Doc: ExprCall tests if the given expression is a function call and, if so, extracts the function name and the expressions tha

## teamserver/pkg/profile/yaotl/expr_list.go

### ExprList `func ExprList(`
- Defined: `teamserver/pkg/profile/yaotl/expr_list.go:14`
- Doc: ExprList tests if the given expression is a static list construct and, if so, extracts the expressions that represent th

## teamserver/pkg/profile/yaotl/expr_map.go

### ExprMap `func ExprMap(`
- Defined: `teamserver/pkg/profile/yaotl/expr_map.go:14`
- Doc: ExprMap tests if the given expression is a static map construct and, if so, extracts the expressions that represent the 

## teamserver/pkg/profile/yaotl/expr_unwrap.go

### UnwrapExpression `func UnwrapExpression(`
- Defined: `teamserver/pkg/profile/yaotl/expr_unwrap.go:28`
- Doc: type-assert on the physical AST types used by the underlying syntax.  Unwrapping an expression may modify its behavior b

### UnwrapExpressionUntil `func UnwrapExpressionUntil(`
- Defined: `teamserver/pkg/profile/yaotl/expr_unwrap.go:54`
- Doc: UnwrapExpressionUntil is similar to UnwrapExpression except it gives the caller an opportunity to test each level of unw

## teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go

### CustomExpressionDecoderForType `func CustomExpressionDecoderForType(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go:48`
- Doc: CustomExpressionDecoderForType takes any cty type and returns its custom expression decoder implementation if it has one
- Imported by: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go`, `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go`, `teamserver/pkg/profile/yaotl/hcldec/spec.go`, `teamserver/pkg/profile/yaotl/hclsyntax/expression.go`

## teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go

### ExpressionVal `func ExpressionVal(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:27`
- Doc: ExpressionVal returns a new cty value of type ExpressionType, wrapping the given expression.

### ExpressionFromVal `func ExpressionFromVal(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:33`
- Doc: ExpressionFromVal returns the expression encapsulated in the given value, or panics if the value is not a known value of

### ExpressionClosureVal `func ExpressionClosureVal(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:58`
- Doc: ExpressionClosureVal returns a new cty value of type ExpressionClosureType, wrapping the given expression closure.

### Value `func (c *ExpressionClosure) Value(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:64`
- Doc: Value evaluates the closure's expression using the closure's EvalContext, returning the result.

### ExpressionClosureFromVal `func ExpressionClosureFromVal(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:75`
- Doc: ExpressionClosureFromVal returns the expression closure encapsulated in the given value, or panics if the value is not a

### init `func init(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:82`

## teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go

### Content `func (b *expandBody) Content(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:29`

### PartialContent `func (b *expandBody) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:46`

### extendSchema `func (b *expandBody) extendSchema(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:85`

### prepareAttributes `func (b *expandBody) prepareAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:121`

### expandBlocks `func (b *expandBody) expandBlocks(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:151`

### expandChild `func (b *expandBody) expandChild(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:232`

### JustAttributes `func (b *expandBody) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:239`

### MissingItemRange `func (b *expandBody) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:246`

## teamserver/pkg/profile/yaotl/ext/dynblock/expand_body_test.go

### TestExpand `func TestExpand(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body_test.go:13`

### TestExpandUnknownBodies `func TestExpandUnknownBodies(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body_test.go:336`

## teamserver/pkg/profile/yaotl/ext/dynblock/expand_spec.go

### decodeSpec `func (b *expandBody) decodeSpec(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_spec.go:22`

### newBlock `func (s *expandSpec) newBlock(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_spec.go:153`

## teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go

### Variables `func (e exprWrap) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go:13`

### Value `func (e exprWrap) Value(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go:33`

### UnwrapExpression `func (e exprWrap) UnwrapExpression(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go:40`
- Doc: UnwrapExpression returns the expression being wrapped by this instance. This allows the original expression to be recove

## teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go

### MakeIteration `func (s *expandSpec) MakeIteration(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:15`

### Object `func (i *iteration) Object(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:24`

### EvalContext `func (i *iteration) EvalContext(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:31`

### MakeChild `func (i *iteration) MakeChild(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:45`

## teamserver/pkg/profile/yaotl/ext/dynblock/public.go

### Expand `func Expand(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/public.go:42`
- Doc: dynamic "child" { for_each = child_objs content { dynamic "grandchild" { for_each = child.value.children labels   = [gra

## teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go

### Unknown `func (b unknownBody) Unknown(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:24`
- Doc: hcldec.UnkownBody impl

### Content `func (b unknownBody) Content(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:28`

### PartialContent `func (b unknownBody) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:38`

### JustAttributes `func (b unknownBody) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:49`

### MissingItemRange `func (b unknownBody) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:59`

### fixupContent `func (b unknownBody) fixupContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:63`

### fixupAttrs `func (b unknownBody) fixupAttrs(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:78`

## teamserver/pkg/profile/yaotl/ext/dynblock/variables.go

### WalkVariables `func WalkVariables(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:19`
- Doc: WalkVariables begins the recursive process of walking all expressions and nested blocks in the given body and its child 

### WalkExpandVariables `func WalkExpandVariables(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:32`
- Doc: WalkExpandVariables is like Variables but it includes only the variables required for successful block expansion, ignori

### Body `func (c WalkVariablesChild) Body(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:58`
- Doc: Body returns the HCL Body associated with the child node, in case the caller wants to do some sort of inspection of it i

### Visit `func (n WalkVariablesNode) Visit(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:70`
- Doc: Visit returns the variable traversals required for any "dynamic" blocks directly in the body associated with this node, 

### extendSchema `func (n WalkVariablesNode) extendSchema(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:172`

## teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go

### VariablesHCLDec `func VariablesHCLDec(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go:16`
- Doc: VariablesHCLDec is a wrapper around WalkVariables that uses the given hcldec specification to automatically drive the re

### ExpandVariablesHCLDec `func ExpandVariablesHCLDec(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go:25`
- Doc: ExpandVariablesHCLDec is like VariablesHCLDec but it includes only the minimal set of variables required to call Expand,

### walkVariablesWithHCLDec `func walkVariablesWithHCLDec(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go:30`

## teamserver/pkg/profile/yaotl/ext/dynblock/variables_test.go

### TestVariables `func TestVariables(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables_test.go:16`

## teamserver/pkg/profile/yaotl/ext/transform/error.go

### NewErrorBody `func NewErrorBody(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:17`
- Doc: NewErrorBody returns a hcl.Body that returns the given diagnostics whenever any of its content-access methods are called

### BodyWithDiagnostics `func BodyWithDiagnostics(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:39`
- Doc: BodyWithDiagnostics returns a hcl.Body that wraps another hcl.Body and emits the given diagnostics for any content-extra

### Content `func (b diagBody) Content(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:56`

### PartialContent `func (b diagBody) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:68`

### JustAttributes `func (b diagBody) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:80`

### MissingItemRange `func (b diagBody) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:92`

### emptyContent `func (b diagBody) emptyContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:104`

## teamserver/pkg/profile/yaotl/ext/transform/transform.go

### Shallow `func Shallow(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:9`
- Doc: Shallow is equivalent to calling transformer.TransformBody(body), and is provided only for completeness of the top-level

### Deep `func Deep(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:24`
- Doc: Deep applies the given transform to the given body and then wraps the result such that any descendent blocks that are de

### Content `func (w deepWrapper) Content(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:39`

### PartialContent `func (w deepWrapper) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:45`

### transformContent `func (w deepWrapper) transformContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:51`

### JustAttributes `func (w deepWrapper) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:76`

### MissingItemRange `func (w deepWrapper) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:81`

## teamserver/pkg/profile/yaotl/ext/transform/transform_test.go

### TestDeep `func TestDeep(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform_test.go:16`

## teamserver/pkg/profile/yaotl/ext/transform/transformer.go

### TransformBody `func (f TransformerFunc) TransformBody(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transformer.go:23`
- Doc: TransformBody is an implementation of Transformer.TransformBody.

### Chain `func Chain(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transformer.go:31`
- Doc: Chain takes a slice of transformers and returns a single new Transformer that applies each of the given transformers in 

### TransformBody `func (c chain) TransformBody(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transformer.go:35`

## teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go

### init `func init(`
- Defined: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:30`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### try `func try(`
- Defined: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:61`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### can `func can(`
- Defined: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:109`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### dependsOnUnknowns `func dependsOnUnknowns(`
- Defined: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:130`
- Doc: dependsOnUnknowns returns true if any of the variables that the given expression might access are unknown values or cont
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

## teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc_test.go

### TestTryFunc `func TestTryFunc(`
- Defined: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc_test.go:12`

### TestCanFunc `func TestCanFunc(`
- Defined: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc_test.go:169`

## teamserver/pkg/profile/yaotl/ext/typeexpr/get_type.go

### getType `func getType(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/get_type.go:15`
- Doc: getType is the internal implementation of both Type and TypeConstraint, using the passed flag to distinguish. When const

## teamserver/pkg/profile/yaotl/ext/typeexpr/get_type_test.go

### TestGetType `func TestGetType(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/get_type_test.go:14`

### TestGetTypeJSON `func TestGetTypeJSON(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/get_type_test.go:282`

## teamserver/pkg/profile/yaotl/ext/typeexpr/public.go

### Type `func Type(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/public.go:17`
- Doc: Type attempts to process the given expression as a type expression and, if successful, returns the resulting type. If un

### TypeConstraint `func TypeConstraint(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/public.go:28`
- Doc: TypeConstraint attempts to parse the given expression as a type constraint and, if successful, returns the resulting typ

### TypeString `func TypeString(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/public.go:44`
- Doc: TypeString returns a string rendering of the given type as it would be expected to appear in the HCL native syntax.  Thi

## teamserver/pkg/profile/yaotl/ext/typeexpr/type_string_test.go

### TestTypeString `func TestTypeString(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/type_string_test.go:9`

## teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go

### TypeConstraintVal `func TypeConstraintVal(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:26`
- Doc: TypeConstraintVal constructs a cty.Value whose type is TypeConstraintType.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### TypeConstraintFromVal `func TypeConstraintFromVal(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:35`
- Doc: TypeConstraintFromVal extracts the type from a cty.Value of TypeConstraintType that was previously constructed using Typ
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### init `func init(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:57`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

## teamserver/pkg/profile/yaotl/ext/typeexpr/type_type_test.go

### TestTypeConstraintType `func TestTypeConstraintType(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type_test.go:10`

### TestConvertFunc `func TestConvertFunc(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type_test.go:30`

## teamserver/pkg/profile/yaotl/ext/userfunc/decode.go

### decodeUserFunctions `func decodeUserFunctions(`
- Defined: `teamserver/pkg/profile/yaotl/ext/userfunc/decode.go:26`

## teamserver/pkg/profile/yaotl/ext/userfunc/decode_test.go

### TestDecodeUserFunctions `func TestDecodeUserFunctions(`
- Defined: `teamserver/pkg/profile/yaotl/ext/userfunc/decode_test.go:12`

## teamserver/pkg/profile/yaotl/ext/userfunc/public.go

### DecodeUserFunctions `func DecodeUserFunctions(`
- Defined: `teamserver/pkg/profile/yaotl/ext/userfunc/public.go:40`
- Doc: along with a new body that represents the remaining content of the given body which can be used for further processing. 

## teamserver/pkg/profile/yaotl/gohcl/decode.go

### DecodeBody `func DecodeBody(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/decode.go:30`
- Doc: a map, where in the former case the configuration will be decoded using struct tags and in the latter case only attribut

### decodeBodyToValue `func decodeBodyToValue(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/decode.go:39`

### decodeBodyToStruct `func decodeBodyToStruct(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/decode.go:51`

### decodeBodyToMap `func decodeBodyToMap(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/decode.go:234`

### decodeBlockToValue `func decodeBlockToValue(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/decode.go:260`

### DecodeExpression `func DecodeExpression(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/decode.go:306`
- Doc: DecodeExpression extracts the value of the given expression into the given value. This value must be something that goct

## teamserver/pkg/profile/yaotl/gohcl/encode.go

### EncodeIntoBody `func EncodeIntoBody(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/encode.go:36`
- Doc: Any fields tagged as "label" are ignored by this function. Use EncodeAsBlock to produce a whole hclwrite.Block including

### EncodeAsBlock `func EncodeAsBlock(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/encode.go:60`
- Doc: EncodeAsBlock creates a new hclwrite.Block populated with the data from the given value, which must be a struct or point

### populateBody `func populateBody(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/encode.go:85`

## teamserver/pkg/profile/yaotl/gohcl/schema.go

### ImpliedBodySchema `func ImpliedBodySchema(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/schema.go:22`
- Doc: ImpliedBodySchema produces a hcl.BodySchema derived from the type of the given value, which must be a struct value or a 

### getFieldTags `func getFieldTags(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/schema.go:125`

## teamserver/pkg/profile/yaotl/hcldec/block_labels.go

### labelsForBlock `func labelsForBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/block_labels.go:12`

## teamserver/pkg/profile/yaotl/hcldec/decode.go

### decode `func decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/decode.go:8`

### impliedType `func impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/decode.go:27`

### sourceRange `func sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/decode.go:31`

## teamserver/pkg/profile/yaotl/hcldec/gob.go

### init `func init(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/gob.go:7`

## teamserver/pkg/profile/yaotl/hcldec/public.go

### Decode `func Decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public.go:14`
- Doc: Decode interprets the given body using the given specification and returns the resulting value. If the given body is not

### PartialDecode `func PartialDecode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public.go:25`
- Doc: PartialDecode is like Decode except that it permits "leftover" items in the top-level body, which are returned as a new 

### ImpliedType `func ImpliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public.go:31`
- Doc: ImpliedType returns the value type that should result from decoding the given spec.

### SourceRange `func SourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public.go:51`
- Doc: fulfill the spec.  This can be used if application-level validation detects value errors, to obtain a reasonable SourceR

### ChildBlockTypes `func ChildBlockTypes(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public.go:58`
- Doc: ChildBlockTypes returns a map of all of the child block types declared by the given spec, with block type names as keys 

## teamserver/pkg/profile/yaotl/hcldec/public_test.go

### TestDecode `func TestDecode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public_test.go:13`

### TestSourceRange `func TestSourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public_test.go:1046`

## teamserver/pkg/profile/yaotl/hcldec/schema.go

### ImpliedSchema `func ImpliedSchema(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/schema.go:10`
- Doc: ImpliedSchema returns the *hcl.BodySchema implied by the given specification. This is the schema that the Decode functio

## teamserver/pkg/profile/yaotl/hcldec/spec.go

### visitSameBodyChildren `func (s ObjectSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:73`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s ObjectSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:79`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s ObjectSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:92`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s ObjectSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:104`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s TupleSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:115`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s TupleSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:121`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s TupleSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:134`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s TupleSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:146`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *AttrSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:162`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded `func (s *AttrSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:167`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### attrSchemata `func (s *AttrSpec) attrSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:177`
- Doc: attrSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *AttrSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:186`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *AttrSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:195`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *AttrSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:237`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *LiteralSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:247`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *LiteralSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:251`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *LiteralSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:255`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *LiteralSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:259`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *ExprSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:273`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded `func (s *ExprSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:278`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *ExprSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:282`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *ExprSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:286`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *ExprSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:291`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *BlockSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:307`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata `func (s *BlockSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:312`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec `func (s *BlockSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:322`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded `func (s *BlockSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:327`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *BlockSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:345`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *BlockSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:392`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *BlockSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:396`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *BlockListSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:423`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata `func (s *BlockListSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:428`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec `func (s *BlockListSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:438`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded `func (s *BlockListSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:443`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *BlockListSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:457`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *BlockListSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:547`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *BlockListSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:551`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *BlockTupleSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:585`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata `func (s *BlockTupleSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:590`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec `func (s *BlockTupleSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:600`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded `func (s *BlockTupleSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:605`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *BlockTupleSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:619`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *BlockTupleSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:671`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *BlockTupleSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:677`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *BlockSetSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:707`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata `func (s *BlockSetSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:712`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec `func (s *BlockSetSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:722`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded `func (s *BlockSetSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:727`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *BlockSetSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:741`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *BlockSetSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:832`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *BlockSetSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:836`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *BlockMapSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:868`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata `func (s *BlockMapSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:873`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec `func (s *BlockMapSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:883`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded `func (s *BlockMapSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:888`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *BlockMapSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:902`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *BlockMapSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:981`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *BlockMapSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:989`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *BlockObjectSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1025`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata `func (s *BlockObjectSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1030`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec `func (s *BlockObjectSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1040`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded `func (s *BlockObjectSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1045`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *BlockObjectSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1059`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *BlockObjectSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1135`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *BlockObjectSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1141`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *BlockAttrsSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1183`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata `func (s *BlockAttrsSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1188`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec `func (s *BlockAttrsSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1198`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded `func (s *BlockAttrsSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1208`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *BlockAttrsSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1235`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *BlockAttrsSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1306`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *BlockAttrsSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1310`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### findBlock `func (s *BlockAttrsSpec) findBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1318`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *BlockLabelSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1348`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *BlockLabelSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1352`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *BlockLabelSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1360`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *BlockLabelSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1364`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### findLabelSpecs `func findLabelSpecs(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1372`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *DefaultSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1430`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *DefaultSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1435`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *DefaultSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1445`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### attrSchemata `func (s *DefaultSpec) attrSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1450`
- Doc: attrSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata `func (s *DefaultSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1464`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec `func (s *DefaultSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1474`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *DefaultSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1481`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *TransformExprSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1503`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *TransformExprSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1507`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *TransformExprSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1525`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *TransformExprSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1535`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *TransformFuncSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1559`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *TransformFuncSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1563`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *TransformFuncSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1589`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *TransformFuncSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1600`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s *ValidateSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1619`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s *ValidateSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1623`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s *ValidateSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1644`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s *ValidateSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1648`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode `func (s noopSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1658`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType `func (s noopSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1662`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren `func (s noopSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1666`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange `func (s noopSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1670`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

## teamserver/pkg/profile/yaotl/hcldec/spec_test.go

### TestDefaultSpec `func TestDefaultSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec_test.go:49`

### TestValidateFuncSpec `func TestValidateFuncSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec_test.go:145`

## teamserver/pkg/profile/yaotl/hcldec/variables.go

### Variables `func Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/variables.go:17`
- Doc: Variables processes the given body with the given spec and returns a list of the variable traversals that would be requi

## teamserver/pkg/profile/yaotl/hcldec/variables_test.go

### TestVariables `func TestVariables(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/variables_test.go:13`

## teamserver/pkg/profile/yaotl/hcled/navigation.go

### ContextString `func ContextString(`
- Defined: `teamserver/pkg/profile/yaotl/hcled/navigation.go:15`
- Doc: ContextString returns a string describing the context of the given byte offset, if available. An empty string is returne

### ContextDefRange `func ContextDefRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcled/navigation.go:26`

## teamserver/pkg/profile/yaotl/hclparse/parser.go

### NewParser `func NewParser(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:43`
- Doc: NewParser creates a new parser, ready to parse configuration files.

### ParseHCL `func (p *Parser) ParseHCL(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:52`
- Doc: ParseHCL parses the given buffer (which is assumed to have been loaded from the given filename) as a native-syntax confi

### ParseHCLFile `func (p *Parser) ParseHCLFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:65`
- Doc: ParseHCLFile reads the given filename and parses it as a native-syntax HCL configuration file. An error diagnostic is re

### ParseJSON `func (p *Parser) ParseJSON(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:86`
- Doc: ParseJSON parses the given JSON buffer (which is assumed to have been loaded from the given filename) and returns the hc

### ParseJSONFile `func (p *Parser) ParseJSONFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:98`
- Doc: ParseJSONFile reads the given filename and parses it as JSON, similarly to ParseJSON. An error diagnostic is returned if

### AddFile `func (p *Parser) AddFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:110`
- Doc: AddFile allows a caller to record in a parser a file that was parsed some other way, thus allowing it to be included in 

### Sources `func (p *Parser) Sources(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:119`
- Doc: Sources returns a map from filenames to the raw source code that was read from them. This is intended to be used, for ex

### Files `func (p *Parser) Files(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:133`
- Doc: Files returns a map from filenames to the File objects produced from them. This is intended to be used, for example, to 

## teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go

### Decode `func Decode(`
- Defined: `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go:53`
- Doc: can just pass nil.  The "target" argument must be a pointer to a value of a struct type, with struct tags as defined by 
- Imported by: `teamserver/pkg/profile/profile.go`, `teamserver/pkg/profile/yaotl/doc.go`

### DecodeFile `func DecodeFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go:72`
- Doc: DecodeFile is a wrapper around Decode that first reads the given filename from disk. See the Decode documentation for mo
- Imported by: `teamserver/pkg/profile/profile.go`, `teamserver/pkg/profile/yaotl/doc.go`

## teamserver/pkg/profile/yaotl/hclsyntax/diagnostics.go

### setDiagEvalContext `func setDiagEvalContext(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/diagnostics.go:16`
- Doc: setDiagEvalContext is an internal helper that will impose a particular EvalContext on a set of diagnostics in-place, for

## teamserver/pkg/profile/yaotl/hclsyntax/didyoumean.go

### nameSuggestion `func nameSuggestion(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/didyoumean.go:16`
- Doc: nameSuggestion tries to find a name from the given slice of suggested names that is close to the given name and returns 

## teamserver/pkg/profile/yaotl/hclsyntax/expression.go

### Range `func (e *ParenthesesExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:45`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes `func (e *ParenthesesExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:49`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes `func (e *LiteralValueExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:62`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value `func (e *LiteralValueExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:66`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range `func (e *LiteralValueExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:70`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange `func (e *LiteralValueExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:74`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### AsTraversal `func (e *LiteralValueExpr) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:79`
- Doc: Implementation for hcl.AbsTraversalForExpr.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes `func (e *ScopeTraversalExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:130`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value `func (e *ScopeTraversalExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:134`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range `func (e *ScopeTraversalExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:140`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange `func (e *ScopeTraversalExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:144`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### AsTraversal `func (e *ScopeTraversalExpr) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:149`
- Doc: Implementation for hcl.AbsTraversalForExpr.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes `func (e *RelativeTraversalExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:161`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value `func (e *RelativeTraversalExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:165`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range `func (e *RelativeTraversalExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:173`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange `func (e *RelativeTraversalExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:177`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### AsTraversal `func (e *RelativeTraversalExpr) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:182`
- Doc: Implementation for hcl.AbsTraversalForExpr.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes `func (e *FunctionCallExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:210`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value `func (e *FunctionCallExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:216`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range `func (e *FunctionCallExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:541`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange `func (e *FunctionCallExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:545`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### ExprCall `func (e *FunctionCallExpr) ExprCall(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:550`
- Doc: Implementation for hcl.ExprCall.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes `func (e *ConditionalExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:572`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value `func (e *ConditionalExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:578`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range `func (e *ConditionalExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:715`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange `func (e *ConditionalExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:719`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes `func (e *IndexExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:732`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value `func (e *IndexExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:737`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range `func (e *IndexExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:750`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange `func (e *IndexExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:754`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes `func (e *TupleConsExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:765`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value `func (e *TupleConsExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:771`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range `func (e *TupleConsExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:785`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange `func (e *TupleConsExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:789`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### ExprList `func (e *TupleConsExpr) ExprList(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:794`
- Doc: Implementation for hcl.ExprList
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes `func (e *ObjectConsExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:814`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value `func (e *ObjectConsExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:821`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range `func (e *ObjectConsExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:897`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange `func (e *ObjectConsExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:901`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### ExprMap `func (e *ObjectConsExpr) ExprMap(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:906`
- Doc: Implementation for hcl.ExprMap
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### literalName `func (e *ObjectConsKeyExpr) literalName(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:925`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes `func (e *ObjectConsKeyExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:934`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value `func (e *ObjectConsKeyExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:942`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range `func (e *ObjectConsKeyExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:971`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange `func (e *ObjectConsKeyExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:975`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### AsTraversal `func (e *ObjectConsKeyExpr) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:980`
- Doc: Implementation for hcl.AbsTraversalForExpr.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### UnwrapExpression `func (e *ObjectConsKeyExpr) UnwrapExpression(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:996`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value `func (e *ForExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1022`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes `func (e *ForExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1346`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range `func (e *ForExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1375`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange `func (e *ForExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1379`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value `func (e *SplatExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1392`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes `func (e *SplatExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1522`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range `func (e *SplatExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1527`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange `func (e *SplatExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1531`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value `func (e *AnonSymbolExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1558`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### setValue `func (e *AnonSymbolExpr) setValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1575`
- Doc: setValue sets a temporary local value for the expression when evaluated in the given context, which must be non-nil.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### clearValue `func (e *AnonSymbolExpr) clearValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1588`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes `func (e *AnonSymbolExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1601`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range `func (e *AnonSymbolExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1605`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange `func (e *AnonSymbolExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1609`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go

### init `func init(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:86`

### walkChildNodes `func (e *BinaryOpExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:131`

### Value `func (e *BinaryOpExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:136`

### Range `func (e *BinaryOpExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:198`

### StartRange `func (e *BinaryOpExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:202`

### walkChildNodes `func (e *UnaryOpExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:214`

### Value `func (e *UnaryOpExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:218`

### Range `func (e *UnaryOpExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:262`

### StartRange `func (e *UnaryOpExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:266`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go

### walkChildNodes `func (e *TemplateExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:18`

### Value `func (e *TemplateExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:24`

### Range `func (e *TemplateExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:97`

### StartRange `func (e *TemplateExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:101`

### IsStringLiteral `func (e *TemplateExpr) IsStringLiteral(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:117`
- Doc: IsStringLiteral returns true if and only if the template consists only of single string literal, as would be created for

### walkChildNodes `func (e *TemplateJoinExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:133`

### Value `func (e *TemplateJoinExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:137`

### Range `func (e *TemplateJoinExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:207`

### StartRange `func (e *TemplateJoinExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:211`

### walkChildNodes `func (e *TemplateWrapExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:225`

### Value `func (e *TemplateWrapExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:229`

### Range `func (e *TemplateWrapExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:233`

### StartRange `func (e *TemplateWrapExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:237`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go

### Variables `func (e *AnonSymbolExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:10`

### Variables `func (e *BinaryOpExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:14`

### Variables `func (e *ConditionalExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:18`

### Variables `func (e *ForExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:22`

### Variables `func (e *FunctionCallExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:26`

### Variables `func (e *IndexExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:30`

### Variables `func (e *LiteralValueExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:34`

### Variables `func (e *ObjectConsExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:38`

### Variables `func (e *ObjectConsKeyExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:42`

### Variables `func (e *RelativeTraversalExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:46`

### Variables `func (e *ScopeTraversalExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:50`

### Variables `func (e *SplatExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:54`

### Variables `func (e *TemplateExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:58`

### Variables `func (e *TemplateJoinExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:62`

### Variables `func (e *TemplateWrapExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:66`

### Variables `func (e *TupleConsExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:70`

### Variables `func (e *UnaryOpExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:74`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go

### main `func main(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go:20`
- Depends on: `teamserver/pkg/profile/yaotl/hclsyntax/token.go`

### Variables `func (e %s) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go:97`
- Depends on: `teamserver/pkg/profile/yaotl/hclsyntax/token.go`

## teamserver/pkg/profile/yaotl/hclsyntax/file.go

### AsHCLFile `func (f *File) AsHCLFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/file.go:13`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/config/fuzz.go

### Fuzz `func Fuzz(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/config/fuzz.go:8`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/expr/fuzz.go

### Fuzz `func Fuzz(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/expr/fuzz.go:8`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/template/fuzz.go

### Fuzz `func Fuzz(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/template/fuzz.go:8`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/traversal/fuzz.go

### Fuzz `func Fuzz(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/traversal/fuzz.go:8`

## teamserver/pkg/profile/yaotl/hclsyntax/keywords.go

### TokenMatches `func (kw Keyword) TokenMatches(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/keywords.go:16`

## teamserver/pkg/profile/yaotl/hclsyntax/navigation.go

### ContextString `func (n navigation) ContextString(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/navigation.go:15`
- Doc: Implementation of hcled.ContextString

### ContextDefRange `func (n navigation) ContextDefRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/navigation.go:45`

## teamserver/pkg/profile/yaotl/hclsyntax/parser.go

### ParseBody `func (p *parser) ParseBody(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:25`

### ParseBodyItem `func (p *parser) ParseBodyItem(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:116`

### parseSingleAttrBody `func (p *parser) parseSingleAttrBody(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:156`
- Doc: parseSingleAttrBody is a weird variant of ParseBody that deals with the body of a nested block containing only one attri

### finishParsingBodyAttribute `func (p *parser) finishParsingBodyAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:217`

### finishParsingBodyBlock `func (p *parser) finishParsingBodyBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:274`

### ParseExpression `func (p *parser) ParseExpression(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:444`

### parseTernaryConditional `func (p *parser) parseTernaryConditional(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:448`

### parseBinaryOps `func (p *parser) parseBinaryOps(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:512`
- Doc: parseBinaryOps calls itself recursively to work through all of the operator precedence groups, and then eventually calls

### parseExpressionWithTraversals `func (p *parser) parseExpressionWithTraversals(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:584`

### parseExpressionTraversals `func (p *parser) parseExpressionTraversals(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:591`

### makeRelativeTraversal `func makeRelativeTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:891`
- Doc: makeRelativeTraversal takes an expression and a traverser and returns a traversal expression that combines the two. If t

### parseExpressionTerm `func (p *parser) parseExpressionTerm(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:910`

### numberLitValue `func (p *parser) numberLitValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1081`

### finishParsingFunctionCall `func (p *parser) finishParsingFunctionCall(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1105`
- Doc: finishParsingFunctionCall parses a function call assuming that the function name was already read, and so the peeker sho

### parseTupleCons `func (p *parser) parseTupleCons(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1200`

### parseObjectCons `func (p *parser) parseObjectCons(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1270`

### finishParsingForExpr `func (p *parser) finishParsingForExpr(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1427`

### parseQuotedStringLiteral `func (p *parser) parseQuotedStringLiteral(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1650`
- Doc: parseQuotedStringLiteral is a helper for parsing quoted strings that aren't allowed to contain any interpolations, such 

### ParseStringLiteralToken `func ParseStringLiteralToken(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1745`
- Doc: ParseStringLiteralToken processes the given token, which must be either a TokenQuotedLit or a TokenStringLit, returning 

### setRecovery `func (p *parser) setRecovery(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1912`
- Doc: setRecovery turns on recovery mode without actually doing any recovery. This can be used when a parser knowingly leaves 

### recover `func (p *parser) recover(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1924`
- Doc: recover seeks forward in the token stream until it finds TokenType "end", then returns with the peeker pointed at the fo

### recoverOver `func (p *parser) recoverOver(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1963`
- Doc: recoverOver seeks forward in the token stream until it finds a block starting with TokenType "start", then finds the cor

### recoverAfterBodyItem `func (p *parser) recoverAfterBodyItem(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1981`

### oppositeBracket `func (p *parser) oppositeBracket(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:2028`
- Doc: oppositeBracket finds the bracket that opposes the given bracketer, or NilToken if the given token isn't a bracketer.  "

### errPlaceholderExpr `func errPlaceholderExpr(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:2067`

## teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go

### ParseTemplate `func (p *parser) ParseTemplate(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:13`

### parseTemplate `func (p *parser) parseTemplate(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:17`

### parseTemplateInner `func (p *parser) parseTemplateInner(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:36`

### parseRoot `func (p *templateParser) parseRoot(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:65`

### parseExpr `func (p *templateParser) parseExpr(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:83`

### parseIf `func (p *templateParser) parseIf(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:135`

### parseFor `func (p *templateParser) parseFor(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:247`

### Peek `func (p *templateParser) Peek(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:344`

### Read `func (p *templateParser) Read(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:348`

### parseTemplateParts `func (p *parser) parseTemplateParts(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:361`
- Doc: parseTemplateParts produces a flat sequence of "template tokens", which are either literal values (with any "trimming" a

### flushHeredocTemplateParts `func flushHeredocTemplateParts(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:675`
- Doc: flushHeredocTemplateParts modifies in-place the line-leading literal strings to apply the flush heredoc processing rule:

### Name `func (t *templateEndCtrlToken) Name(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:787`

### templateToken `func (t isTemplateToken) templateToken(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:808`

## teamserver/pkg/profile/yaotl/hclsyntax/parser_traversal.go

### ParseTraversalAbs `func (p *parser) ParseTraversalAbs(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_traversal.go:12`
- Doc: ParseTraversalAbs parses an absolute traversal that is assumed to consume all of the remaining tokens in the peeker. The

## teamserver/pkg/profile/yaotl/hclsyntax/peeker.go

### newPeeker `func newPeeker(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:38`

### Peek `func (p *peeker) Peek(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:47`

### Read `func (p *peeker) Read(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:52`

### NextRange `func (p *peeker) NextRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:58`

### PrevRange `func (p *peeker) PrevRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:62`

### nextToken `func (p *peeker) nextToken(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:70`

### includingNewlines `func (p *peeker) includingNewlines(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:118`

### PushIncludeNewlines `func (p *peeker) PushIncludeNewlines(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:122`

### PopIncludeNewlines `func (p *peeker) PopIncludeNewlines(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:138`

### AssertEmptyIncludeNewlinesStack `func (p *peeker) AssertEmptyIncludeNewlinesStack(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:168`
- Doc: AssertEmptyNewlinesStack checks if the IncludeNewlinesStack is empty, doing panicking if it is not. This can be used to 

### formatPeekerNewlineStackChanges `func formatPeekerNewlineStackChanges(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:184`

## teamserver/pkg/profile/yaotl/hclsyntax/public.go

### ParseConfig `func ParseConfig(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:17`
- Doc: ParseConfig parses the given buffer as a whole HCL config file, returning a *hcl.File representing its contents. If HasE

### ParseExpression `func ParseExpression(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:41`
- Doc: ParseExpression parses the given buffer as a standalone HCL expression, returning it as an instance of Expression.

### ParseTemplate `func ParseTemplate(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:75`
- Doc: ParseTemplate parses the given buffer as a standalone HCL template, returning it as an instance of Expression.

### ParseTraversalAbs `func ParseTraversalAbs(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:96`
- Doc: ParseTraversalAbs parses the given buffer as a standalone absolute traversal.  Parsing as a traversal is more limited th

### LexConfig `func LexConfig(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:125`
- Doc: LexConfig performs lexical analysis on the given buffer, treating it as a whole HCL config file, and returns the resulti

### LexExpression `func LexExpression(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:138`
- Doc: LexExpression performs lexical analysis on the given buffer, treating it as a standalone HCL expression, and returns the

### LexTemplate `func LexTemplate(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:153`
- Doc: LexTemplate performs lexical analysis on the given buffer, treating it as a standalone HCL template, and returns the res

### ValidIdentifier `func ValidIdentifier(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:165`
- Doc: ValidIdentifier tests if the given string could be a valid identifier in a native syntax expression.  This is useful whe

## teamserver/pkg/profile/yaotl/hclsyntax/scan_string_lit.go

### scanStringLit `func scanStringLit(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/scan_string_lit.go:119`

## teamserver/pkg/profile/yaotl/hclsyntax/scan_tokens.go

### scanTokens `func scanTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/scan_tokens.go:4220`

## teamserver/pkg/profile/yaotl/hclsyntax/structure.go

### AsHCLBlock `func (b *Block) AsHCLBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:11`
- Doc: AsHCLBlock returns the block data expressed as a *hcl.Block.

### walkChildNodes `func (b *Body) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:49`

### Range `func (b *Body) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:54`

### Content `func (b *Body) Content(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:58`

### PartialContent `func (b *Body) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:128`

### JustAttributes `func (b *Body) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:250`

### MissingItemRange `func (b *Body) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:281`

### walkChildNodes `func (a Attributes) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:292`

### Range `func (a Attributes) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:303`
- Doc: Range returns the range of some arbitrary point within the set of attributes, or an invalid range if there are no attrib

### walkChildNodes `func (a *Attribute) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:327`

### Range `func (a *Attribute) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:331`

### AsHCLAttribute `func (a *Attribute) AsHCLAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:336`
- Doc: AsHCLAttribute returns the block data expressed as a *hcl.Attribute.

### walkChildNodes `func (bs Blocks) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:352`

### Range `func (bs Blocks) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:363`
- Doc: Range returns the range of some arbitrary point within the list of blocks, or an invalid range if there are no blocks.  

### walkChildNodes `func (b *Block) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:384`

### Range `func (b *Block) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:388`

### DefRange `func (b *Block) DefRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:392`

## teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go

### BlocksAtPos `func (b *Body) BlocksAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:15`
- Doc: BlocksAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.

### InnermostBlockAtPos `func (b *Body) InnermostBlockAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:22`
- Doc: InnermostBlockAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.

### OutermostBlockAtPos `func (b *Body) OutermostBlockAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:29`
- Doc: OutermostBlockAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.

### blocksAtPos `func (b *Body) blocksAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:40`
- Doc: blocksAtPos is the internal engine of both BlocksAtPos and InnermostBlockAtPos, which both need to do the same logic but

### outermostBlockAtPos `func (b *Body) outermostBlockAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:68`
- Doc: outermostBlockAtPos is the internal version of OutermostBlockAtPos that returns a hclsyntax.Block rather than an hcl.Blo

### AttributeAtPos `func (b *Body) AttributeAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:84`
- Doc: AttributeAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.

### attributeAtPos `func (b *Body) attributeAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:91`
- Doc: attributeAtPos is the internal version of AttributeAtPos that returns a hclsyntax.Block rather than an hcl.Block, allowi

### OutermostExprAtPos `func (b *Body) OutermostExprAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:109`
- Doc: OutermostExprAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.

## teamserver/pkg/profile/yaotl/hclsyntax/token.go

### GoString `func (t TokenType) GoString(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token.go:107`
- Imported by: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go`

### emitToken `func (f *tokenAccum) emitToken(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token.go:127`
- Imported by: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go`

### tokenOpensFlushHeredoc `func tokenOpensFlushHeredoc(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token.go:167`
- Imported by: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go`

### checkInvalidTokens `func checkInvalidTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token.go:182`
- Doc: checkInvalidTokens does a simple pass across the given tokens and generates diagnostics for tokens that should _never_ a
- Imported by: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go`

### stripUTF8BOM `func stripUTF8BOM(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token.go:326`
- Doc: stripUTF8BOM checks whether the given buffer begins with a UTF-8 byte order mark (0xEF 0xBB 0xBF) and, if so, returns a 
- Imported by: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go`

## teamserver/pkg/profile/yaotl/hclsyntax/token_type_string.go

### _ `func _(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token_type_string.go:7`

### String `func (i TokenType) String(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token_type_string.go:126`

## teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb

### each_alpha
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:80`
- Doc: # Downloads the document at url and yields every alpha line's hex range and description.

### to_hex
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:103`
- Doc: ## Formats to hex at minimum width

### to_ucs4
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:112`
- Doc: ## UCS4 is just a straight hex conversion of the unicode codepoint.

### to_utf8_enc
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:126`

### from_utf8_enc
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:150`

### utf8_ranges
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:181`
- Doc: ## Given a range, splits it up into ranges that can be continuously encoded into utf8.  Eg: 0x00 .. 0xff => [0x00..0x7f,

### build_range
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:197`

### to_utf8
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:246`

### count_codepoints
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:259`
- Doc: # Perform a 3-way comparison of the number of codepoints advertised by the unicode spec for the given range, the origina

### is_valid
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:273`

### generate_machine
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:285`
- Doc: # Generate the state matching to stdout

## teamserver/pkg/profile/yaotl/hclsyntax/variables.go

### Variables `func Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:11`
- Doc: Variables returns all of the variables referenced within a given expression.  This is the implementation of the "Variabl

### Enter `func (w *variablesWalker) Enter(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:32`

### Exit `func (w *variablesWalker) Exit(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:55`

### walkChildNodes `func (e ChildScope) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:78`

### Range `func (e ChildScope) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:84`
- Doc: Range returns the range of the expression that the ChildScope is encapsulating. It isn't really very useful to call Rang

## teamserver/pkg/profile/yaotl/hclsyntax/walk.go

### VisitAll `func VisitAll(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/walk.go:16`
- Doc: VisitAll is a basic way to traverse the AST beginning with a particular node. The given function will be called once for

### Walk `func Walk(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/walk.go:33`
- Doc: Walk is a more complex way to traverse the AST starting with a particular node, which provides information about the tre

## teamserver/pkg/profile/yaotl/hcltest/mock.go

### MockBody `func MockBody(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:15`
- Doc: MockBody returns a hcl.Body implementation that works in terms of a caller-constructed hcl.BodyContent, thus avoiding th

### Content `func (b mockBody) Content(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:23`

### PartialContent `func (b mockBody) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:45`

### JustAttributes `func (b mockBody) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:108`

### MissingItemRange `func (b mockBody) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:122`

### MockExprLiteral `func MockExprLiteral(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:128`
- Doc: MockExprLiteral returns a hcl.Expression that evaluates to the given literal value.

### Value `func (e mockExprLiteral) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:136`

### Variables `func (e mockExprLiteral) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:140`

### Range `func (e mockExprLiteral) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:144`

### StartRange `func (e mockExprLiteral) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:150`

### ExprList `func (e mockExprLiteral) ExprList(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:155`
- Doc: Implementation for hcl.ExprList

### ExprMap `func (e mockExprLiteral) ExprMap(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:170`
- Doc: Implementation for hcl.ExprMap

### MockExprVariable `func MockExprVariable(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:189`
- Doc: MockExprVariable returns a hcl.Expression that evaluates to the value of the variable with the given name.

### Value `func (e mockExprVariable) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:195`

### Variables `func (e mockExprVariable) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:214`

### Range `func (e mockExprVariable) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:225`

### StartRange `func (e mockExprVariable) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:231`

### AsTraversal `func (e mockExprVariable) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:236`
- Doc: Implementation for hcl.AbsTraversalForExpr and hcl.RelTraversalForExpr.

### MockExprTraversal `func MockExprTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:247`
- Doc: MockExprTraversal returns a hcl.Expression that evaluates the given absolute traversal.

### MockExprTraversalSrc `func MockExprTraversalSrc(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:258`
- Doc: MockExprTraversalSrc is like MockExprTraversal except it takes a traversal string as defined by the native syntax and pa

### Value `func (e mockExprTraversal) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:270`

### Variables `func (e mockExprTraversal) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:274`

### Range `func (e mockExprTraversal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:278`

### StartRange `func (e mockExprTraversal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:282`

### AsTraversal `func (e mockExprTraversal) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:287`
- Doc: Implementation for hcl.AbsTraversalForExpr and hcl.RelTraversalForExpr.

### MockExprList `func MockExprList(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:291`

### Value `func (e mockExprList) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:301`

### Variables `func (e mockExprList) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:317`

### Range `func (e mockExprList) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:325`

### StartRange `func (e mockExprList) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:331`

### ExprList `func (e mockExprList) ExprList(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:336`
- Doc: Implementation for hcl.ExprList

### MockAttrs `func MockAttrs(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:345`
- Doc: MockAttrs constructs and returns a hcl.Attributes map with attributes derived from the given expression map.  Each entry

## teamserver/pkg/profile/yaotl/hcltest/mock_test.go

### TestMockBodyPartialContent `func TestMockBodyPartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock_test.go:17`

### TestExprList `func TestExprList(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock_test.go:271`

### TestExprMap `func TestExprMap(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock_test.go:328`

## teamserver/pkg/profile/yaotl/hclwrite/ast.go

### NewEmptyFile `func NewEmptyFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:17`
- Doc: NewEmptyFile constructs a new file with no content, ready to be mutated by other calls that append to its body.

### Body `func (f *File) Body(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:28`
- Doc: Body returns the root body of the file, which contains the top-level attributes and blocks.

### WriteTo `func (f *File) WriteTo(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:36`
- Doc: WriteTo writes the tokens underlying the receiving file to the given writer.  The tokens first have a simple formatting 

### Bytes `func (f *File) Bytes(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:45`
- Doc: Bytes returns a buffer containing the source code resulting from the tokens underlying the receiving file. If any update

### newComments `func newComments(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:58`

### BuildTokens `func (c *comments) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:64`

### newIdentifier `func newIdentifier(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:75`

### BuildTokens `func (i *identifier) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:81`

### hasName `func (i *identifier) hasName(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:85`

### newNumber `func newNumber(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:96`

### BuildTokens `func (n *number) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:102`

### newQuoted `func newQuoted(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:113`

### BuildTokens `func (q *quoted) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:119`

## teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go

### newAttribute `func newAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go:16`

### init `func (a *Attribute) init(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go:22`

### Expr `func (a *Attribute) Expr(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go:46`

## teamserver/pkg/profile/yaotl/hclwrite/ast_block.go

### newBlock `func newBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:19`

### NewBlock `func NewBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:26`
- Doc: NewBlock constructs a new, empty block with the given type name and labels.

### init `func (b *Block) init(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:32`

### Body `func (b *Block) Body(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:67`
- Doc: Body returns the body that represents the content of the receiving block.  Appending to or otherwise modifying this body

### Type `func (b *Block) Type(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:72`
- Doc: Type returns the type name of the block.

### SetType `func (b *Block) SetType(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:78`
- Doc: SetType updates the type name of the block to a given name.

### Labels `func (b *Block) Labels(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:85`
- Doc: Labels returns the labels of the block.

### SetLabels `func (b *Block) SetLabels(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:92`
- Doc: SetLabels updates the labels of the block to given labels. Since we cannot assume that old and new labels are equal in l

### labelsObj `func (b *Block) labelsObj(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:101`
- Doc: labelsObj returns the internal node content representation of the block labels. This is not part of the public API becau

### newBlockLabels `func newBlockLabels(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:111`

### Replace `func (bl *blockLabels) Replace(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:121`

### Current `func (bl *blockLabels) Current(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:136`

## teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go

### TestBlockType `func TestBlockType(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go:15`

### TestBlockLabels `func TestBlockLabels(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go:49`

### TestBlockSetType `func TestBlockSetType(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go:138`

### TestBlockSetLabels `func TestBlockSetLabels(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go:198`

## teamserver/pkg/profile/yaotl/hclwrite/ast_body.go

### newBody `func newBody(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:17`

### appendItem `func (b *Body) appendItem(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:24`

### appendItemNode `func (b *Body) appendItemNode(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:30`

### Clear `func (b *Body) Clear(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:38`
- Doc: Clear removes all of the items from the body, making it empty.

### AppendUnstructuredTokens `func (b *Body) AppendUnstructuredTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:42`

### Attributes `func (b *Body) Attributes(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:48`
- Doc: Attributes returns a new map of all of the attributes in the body, with the attribute names as the keys.

### Blocks `func (b *Body) Blocks(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:61`
- Doc: Blocks returns a new slice of all the blocks in the body.

### GetAttribute `func (b *Body) GetAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:73`
- Doc: GetAttribute returns the attribute from the body that has the given name, or returns nil if there is currently no matchi

### getAttributeNode `func (b *Body) getAttributeNode(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:89`
- Doc: getAttributeNode is like GetAttribute but it returns the node containing the selected attribute (if one is found) rather

### FirstMatchingBlock `func (b *Body) FirstMatchingBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:106`
- Doc: FirstMatchingBlock returns a first matching block from the body that has the given name and labels or returns nil if the

### RemoveBlock `func (b *Body) RemoveBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:126`
- Doc: RemoveBlock removes the given block from the body, if it's in that body. If it isn't present, this is a no-op.  Returns 

### SetAttributeRaw `func (b *Body) SetAttributeRaw(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:144`
- Doc: SetAttributeRaw either replaces the expression of an existing attribute of the given name or adds a new attribute defini

### SetAttributeValue `func (b *Body) SetAttributeValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:165`
- Doc: SetAttributeValue either replaces the expression of an existing attribute of the given name or adds a new attribute defi

### SetAttributeTraversal `func (b *Body) SetAttributeTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:186`
- Doc: SetAttributeTraversal either replaces the expression of an existing attribute of the given name or adds a new attribute 

### RemoveAttribute `func (b *Body) RemoveAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:203`
- Doc: RemoveAttribute removes the attribute with the given name from the body.  The return value is the attribute that was rem

### AppendBlock `func (b *Body) AppendBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:215`
- Doc: AppendBlock appends an existing block (which must not be already attached to a body) to the end of the receiving body.

### AppendNewBlock `func (b *Body) AppendNewBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:222`
- Doc: AppendNewBlock appends a new nested block to the end of the receiving body with the given type name and labels.

### AppendNewline `func (b *Body) AppendNewline(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:232`
- Doc: AppendNewline appends a newline token to th end of the receiving body, which generally serves as a separator between dif

## teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go

### TestBodyGetAttribute `func TestBodyGetAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:16`

### TestBodyFirstMatchingBlock `func TestBodyFirstMatchingBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:220`

### TestBodySetAttributeValue `func TestBodySetAttributeValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:345`

### TestBodySetAttributeTraversal `func TestBodySetAttributeTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:543`

### TestBodySetAttributeRaw `func TestBodySetAttributeRaw(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:769`

### TestBodySetAttributeValueInBlock `func TestBodySetAttributeValueInBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:933`

### TestBodySetAttributeValueInNestedBlock `func TestBodySetAttributeValueInNestedBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:981`

### TestBodyRemoveAttribute `func TestBodyRemoveAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:1036`

### TestBodyAppendBlock `func TestBodyAppendBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:1149`

### TestBodyRemoveBlock `func TestBodyRemoveBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:1392`

## teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go

### newExpression `func newExpression(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:17`

### NewExpressionRaw `func NewExpressionRaw(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:36`
- Doc: NewExpressionRaw constructs an expression containing the given raw tokens.  There is no automatic validation that the gi

### NewExpressionLiteral `func NewExpressionLiteral(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:60`
- Doc: NewExpressionLiteral constructs an an expression that represents the given literal value.  Since an unknown value cannot

### NewExpressionAbsTraversal `func NewExpressionAbsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:69`
- Doc: NewExpressionAbsTraversal constructs an expression that represents the given traversal, which must be absolute or this f

### Variables `func (e *Expression) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:129`
- Doc: Variables returns the absolute traversals that exist within the receiving expression.

### RenameVariablePrefix `func (e *Expression) RenameVariablePrefix(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:150`
- Doc: RenameVariablePrefix examines each of the absolute traversals in the receiving expression to see if they have the given 

### newTraversal `func newTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:195`

### newTraverseName `func newTraverseName(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:208`

### newTraverseIndex `func newTraverseIndex(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:220`

## teamserver/pkg/profile/yaotl/hclwrite/ast_test.go

### makeTestTree `func makeTestTree(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_test.go:15`

## teamserver/pkg/profile/yaotl/hclwrite/examples_test.go

### Example_generateFromScratch `func Example_generateFromScratch(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/examples_test.go:11`

### ExampleExpression_RenameVariablePrefix `func ExampleExpression_RenameVariablePrefix(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/examples_test.go:74`

## teamserver/pkg/profile/yaotl/hclwrite/format.go

### format `func format(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:19`
- Doc: format rewrites tokens within the given sequence, in-place, to adjust the whitespace around their content to achieve can

### formatIndent `func formatIndent(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:40`

### formatSpaces `func formatSpaces(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:110`

### formatCells `func formatCells(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:158`

### spaceAfterToken `func spaceAfterToken(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:227`
- Doc: spaceAfterToken decides whether a particular subject token should have a space after it when surrounded by the given bef

### linesForFormat `func linesForFormat(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:342`

### tokenIsNewline `func tokenIsNewline(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:427`

### tokenBracketChange `func tokenBracketChange(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:440`

## teamserver/pkg/profile/yaotl/hclwrite/format_test.go

### TestFormat `func TestFormat(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format_test.go:13`

### TestLinesForFormat `func TestLinesForFormat(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format_test.go:632`

## teamserver/pkg/profile/yaotl/hclwrite/fuzz/config/fuzz.go

### Fuzz `func Fuzz(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/fuzz/config/fuzz.go:10`

## teamserver/pkg/profile/yaotl/hclwrite/generate.go

### TokensForValue `func TokensForValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:23`
- Doc: TokensForValue returns a sequence of tokens that represents the given constant value.  This function only supports types

### TokensForTraversal `func TokensForTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:36`
- Doc: TokensForTraversal returns a sequence of tokens that represents the given traversal.  If the traversal is absolute then 

### appendTokensForValue `func appendTokensForValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:42`

### appendTokensForTraversal `func appendTokensForTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:164`

### appendTokensForTraversalStep `func appendTokensForTraversalStep(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:171`

### escapeQuotedStringLit `func escapeQuotedStringLit(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:207`

### appendRune `func appendRune(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:248`

## teamserver/pkg/profile/yaotl/hclwrite/generate_test.go

### TestTokensForValue `func TestTokensForValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate_test.go:14`

### TestTokensForTraversal `func TestTokensForTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate_test.go:498`

## teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go

### Len `func (s nativeNodeSorter) Len(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go:11`

### Less `func (s nativeNodeSorter) Less(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go:15`

### Swap `func (s nativeNodeSorter) Swap(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go:21`

## teamserver/pkg/profile/yaotl/hclwrite/node.go

### newNode `func newNode(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:17`

### Equal `func (n *node) Equal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:23`

### BuildTokens `func (n *node) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:27`

### Detach `func (n *node) Detach(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:33`
- Doc: Detach removes the receiver from the list it currently belongs to. If the node is not currently in a list, this is a no-

### ReplaceWith `func (n *node) ReplaceWith(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:60`
- Doc: ReplaceWith removes the receiver from the list it currently belongs to and inserts a new node with the given content in 

### assertUnattached `func (n *node) assertUnattached(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:83`

### BuildTokens `func (ns *nodes) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:100`

### Clear `func (ns *nodes) Clear(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:107`

### Append `func (ns *nodes) Append(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:112`

### AppendNode `func (ns *nodes) AppendNode(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:121`

### Insert `func (ns *nodes) Insert(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:135`
- Doc: Insert inserts a nodeContent at a given position. This is just a wrapper for InsertNode. See InsertNode for details.

### InsertNode `func (ns *nodes) InsertNode(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:147`
- Doc: InsertNode inserts a node at a given position. The first argument is a node reference before which to insert. To insert 

### AppendUnstructuredTokens `func (ns *nodes) AppendUnstructuredTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:163`

### FindNodeWithContent `func (ns *nodes) FindNodeWithContent(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:176`
- Doc: FindNodeWithContent searches the nodes for a node whose content equals the given content. If it finds one then it return

### newNodeSet `func newNodeSet(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:190`

### Has `func (ns nodeSet) Has(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:194`

### Add `func (ns nodeSet) Add(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:202`

### Remove `func (ns nodeSet) Remove(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:206`

### Clear `func (ns nodeSet) Clear(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:210`

### List `func (ns nodeSet) List(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:216`

### FindNodeWithContent `func (ns nodeSet) FindNodeWithContent(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:246`
- Doc: FindNodeWithContent searches the nodes for a node whose content equals the given content. If it finds one then it return

### newInTree `func newInTree(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:265`

### assertUnattached `func (it *inTree) assertUnattached(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:271`

### walkChildNodes `func (it *inTree) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:277`

### BuildTokens `func (it *inTree) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:283`

### walkChildNodes `func (n *leafNode) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:295`

## teamserver/pkg/profile/yaotl/hclwrite/parser.go

### parse `func parse(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:29`
- Doc: up to AST nodes.  This strategy feels somewhat counter-intuitive, since most of the work the parser does is thrown away 

### Partition `func (it inputTokens) Partition(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:74`

### PartitionType `func (it inputTokens) PartitionType(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:82`

### PartitionTypeOk `func (it inputTokens) PartitionTypeOk(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:91`

### PartitionTypeSingle `func (it inputTokens) PartitionTypeSingle(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:101`

### PartitionIncludingComments `func (it inputTokens) PartitionIncludingComments(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:111`
- Doc: PartitionIncludeComments is like Partition except the returned "within" range includes any lead and line comments associ

### PartitionBlockItem `func (it inputTokens) PartitionBlockItem(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:128`
- Doc: PartitionBlockItem is similar to PartitionIncludeComments but it returns the comments as separate token sequences so tha

### PartitionLeadComments `func (it inputTokens) PartitionLeadComments(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:135`

### PartitionLineEndTokens `func (it inputTokens) PartitionLineEndTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:142`

### Slice `func (it inputTokens) Slice(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:150`

### Len `func (it inputTokens) Len(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:162`

### Tokens `func (it inputTokens) Tokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:166`

### Types `func (it inputTokens) Types(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:170`

### parseBody `func parseBody(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:181`
- Doc: parseBody locates the given body within the given input tokens and returns the resulting *Body object as well as the tok

### parseBodyItem `func parseBodyItem(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:220`

### parseAttribute `func parseAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:238`

### parseBlock `func parseBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:289`

### parseBlockLabels `func parseBlockLabels(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:347`

### parseExpression `func parseExpression(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:375`

### parseTraversal `func parseTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:396`

### parseTraversalStep `func parseTraversalStep(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:413`

### writerTokens `func writerTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:482`
- Doc: writerTokens takes a sequence of tokens as produced by the main hclsyntax package and transforms it into an equivalent s

### partitionTokens `func partitionTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:539`
- Doc: This works best when the range is aligned with token boundaries (e.g. because it was produced in terms of the scanner's 

### partitionLeadCommentTokens `func partitionLeadCommentTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:577`
- Doc: partitionLeadCommentTokens takes a sequence of tokens that is assumed to immediately precede a construct that can have l

### partitionLineEndTokens `func partitionLineEndTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:600`
- Doc: partitionLineEndTokens takes a sequence of tokens that is assumed to immediately follow a construct that can have a line

### lexConfig `func lexConfig(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:635`
- Doc: lexConfig uses the hclsyntax scanner to get a token stream and then rewrites it into this package's token model.  Any er

## teamserver/pkg/profile/yaotl/hclwrite/parser_test.go

### TestParse `func TestParse(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser_test.go:18`

### TestPartitionTokens `func TestPartitionTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser_test.go:1232`

### TestPartitionLeadCommentTokens `func TestPartitionLeadCommentTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser_test.go:1382`

### TestLexConfig `func TestLexConfig(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser_test.go:1458`

## teamserver/pkg/profile/yaotl/hclwrite/public.go

### NewFile `func NewFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/public.go:11`
- Doc: NewFile creates a new file object that is empty and ready to have constructs added t it.

### ParseConfig `func ParseConfig(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/public.go:26`
- Doc: ParseConfig interprets the given source bytes into a *hclwrite.File. The resulting AST can be used to perform surgical e

### Format `func Format(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/public.go:38`
- Doc: Format takes source code and performs simple whitespace changes to transform it to a canonical layout style.  Format ski

## teamserver/pkg/profile/yaotl/hclwrite/round_trip_test.go

### TestRoundTripVerbatim `func TestRoundTripVerbatim(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/round_trip_test.go:16`

### TestRoundTripFormat `func TestRoundTripFormat(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/round_trip_test.go:82`

## teamserver/pkg/profile/yaotl/hclwrite/tokens.go

### asHCLSyntax `func (t *Token) asHCLSyntax(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:33`
- Doc: asHCLSyntax returns the receiver expressed as an incomplete hclsyntax.Token. A complete token is not possible since we d

### Bytes `func (ts Tokens) Bytes(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:46`

### testValue `func (ts Tokens) testValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:52`

### Columns `func (ts Tokens) Columns(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:59`
- Doc: Columns returns the number of columns (grapheme clusters) the token sequence occupies. The result is not meaningful if t

### WriteTo `func (ts Tokens) WriteTo(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:72`
- Doc: WriteTo takes an io.Writer and writes the bytes for each token to it, along with the spacing that separates each token. 

### walkChildNodes `func (ts Tokens) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:109`

### BuildTokens `func (ts Tokens) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:113`

### newIdentToken `func newIdentToken(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:117`

## teamserver/pkg/profile/yaotl/json/ast.go

### Range `func (n *objectVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:21`

### StartRange `func (n *objectVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:25`

### Range `func (n *objectAttr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:35`

### StartRange `func (n *objectAttr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:39`

### Range `func (n *arrayVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:49`

### StartRange `func (n *arrayVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:53`

### Range `func (n *booleanVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:62`

### StartRange `func (n *booleanVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:66`

### Range `func (n *numberVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:75`

### StartRange `func (n *numberVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:79`

### Range `func (n *stringVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:88`

### StartRange `func (n *stringVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:92`

### Range `func (n *nullVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:100`

### StartRange `func (n *nullVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:104`

### Range `func (n invalidVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:115`

### StartRange `func (n invalidVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:119`

## teamserver/pkg/profile/yaotl/json/didyoumean.go

### keywordSuggestion `func keywordSuggestion(`
- Defined: `teamserver/pkg/profile/yaotl/json/didyoumean.go:12`
- Doc: keywordSuggestion tries to find a valid JSON keyword that is close to the given string and returns it if found. If no ke

### nameSuggestion `func nameSuggestion(`
- Defined: `teamserver/pkg/profile/yaotl/json/didyoumean.go:25`
- Doc: nameSuggestion tries to find a name from the given slice of suggested names that is close to the given name and returns 

## teamserver/pkg/profile/yaotl/json/didyoumean_test.go

### TestKeywordSuggestion `func TestKeywordSuggestion(`
- Defined: `teamserver/pkg/profile/yaotl/json/didyoumean_test.go:5`

## teamserver/pkg/profile/yaotl/json/fuzz/config/fuzz.go

### Fuzz `func Fuzz(`
- Defined: `teamserver/pkg/profile/yaotl/json/fuzz/config/fuzz.go:7`

## teamserver/pkg/profile/yaotl/json/navigation.go

### ContextString `func (n navigation) ContextString(`
- Defined: `teamserver/pkg/profile/yaotl/json/navigation.go:13`
- Doc: Implementation of hcled.ContextString

### navigationStepsRev `func navigationStepsRev(`
- Defined: `teamserver/pkg/profile/yaotl/json/navigation.go:32`

## teamserver/pkg/profile/yaotl/json/navigation_test.go

### TestNavigationContextString `func TestNavigationContextString(`
- Defined: `teamserver/pkg/profile/yaotl/json/navigation_test.go:9`

## teamserver/pkg/profile/yaotl/json/parser.go

### parseFileContent `func parseFileContent(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:11`

### parseExpression `func parseExpression(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:26`

### parseValue `func parseValue(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:41`

### tokenCanStartValue `func tokenCanStartValue(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:101`

### parseObject `func parseObject(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:110`

### parseArray `func parseArray(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:261`

### parseNumber `func parseNumber(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:363`

### parseString `func parseString(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:406`

### parseKeyword `func parseKeyword(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:461`

## teamserver/pkg/profile/yaotl/json/parser_test.go

### init `func init(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser_test.go:11`

### TestParse `func TestParse(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser_test.go:15`

### TestParseWithPos `func TestParseWithPos(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser_test.go:619`

### mustBigFloat `func mustBigFloat(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser_test.go:661`

## teamserver/pkg/profile/yaotl/json/peeker.go

### newPeeker `func newPeeker(`
- Defined: `teamserver/pkg/profile/yaotl/json/peeker.go:8`

### Peek `func (p *peeker) Peek(`
- Defined: `teamserver/pkg/profile/yaotl/json/peeker.go:15`

### Read `func (p *peeker) Read(`
- Defined: `teamserver/pkg/profile/yaotl/json/peeker.go:19`

## teamserver/pkg/profile/yaotl/json/public.go

### Parse `func Parse(`
- Defined: `teamserver/pkg/profile/yaotl/json/public.go:20`
- Doc: Parse attempts to parse the given buffer as JSON and, if successful, returns a hcl.File for the HCL configuration repres

### ParseWithStartPos `func ParseWithStartPos(`
- Defined: `teamserver/pkg/profile/yaotl/json/public.go:29`
- Doc: ParseWithStartPos attempts to parse like json.Parse, but unlike json.Parse you can pass a start position of the given JS

### ParseExpression `func ParseExpression(`
- Defined: `teamserver/pkg/profile/yaotl/json/public.go:76`
- Doc: ParseExpression parses the given buffer as a standalone JSON expression, returning it as an instance of Expression.

### ParseExpressionWithStartPos `func ParseExpressionWithStartPos(`
- Defined: `teamserver/pkg/profile/yaotl/json/public.go:83`
- Doc: ParseExpressionWithStartPos parses like json.ParseExpression, but unlike json.ParseExpression you can pass a start posit

### ParseFile `func ParseFile(`
- Defined: `teamserver/pkg/profile/yaotl/json/public.go:92`
- Doc: ParseFile is a convenience wrapper around Parse that first attempts to load data from the given filename, passing the re

## teamserver/pkg/profile/yaotl/json/public_test.go

### TestParse_nonObject `func TestParse_nonObject(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:12`

### TestParseTemplate `func TestParseTemplate(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:29`

### TestParseTemplateUnwrap `func TestParseTemplateUnwrap(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:65`

### TestParse_malformed `func TestParse_malformed(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:101`

### TestParseWithStartPos `func TestParseWithStartPos(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:117`

### TestParseExpression `func TestParseExpression(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:187`

### TestParseExpression_malformed `func TestParseExpression_malformed(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:260`

### TestParseExpressionWithStartPos `func TestParseExpressionWithStartPos(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:274`

## teamserver/pkg/profile/yaotl/json/scanner.go

### scan `func scan(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:41`
- Doc: scan returns the primary tokens for the given JSON buffer in sequence.  The responsibility of this pass is to just mark 

### byteCanStartNumber `func byteCanStartNumber(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:124`

### scanNumber `func scanNumber(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:138`

### byteCanStartKeyword `func byteCanStartKeyword(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:157`

### scanKeyword `func scanKeyword(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:172`

### scanString `func scanString(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:189`

### skipWhitespace `func skipWhitespace(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:241`

### Range `func (p *pos) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:280`

### posRange `func posRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:292`

### GoString `func (t token) GoString(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:300`

### isAlphabetical `func isAlphabetical(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:304`

## teamserver/pkg/profile/yaotl/json/scanner_test.go

### TestScan `func TestScan(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner_test.go:12`

## teamserver/pkg/profile/yaotl/json/structure.go

### Content `func (b *body) Content(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:29`

### PartialContent `func (b *body) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:77`

### JustAttributes `func (b *body) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:169`
- Doc: JustAttributes for JSON bodies interprets all properties of the wrapped JSON object as attributes and returns them.

### MissingItemRange `func (b *body) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:219`

### unpackBlock `func (b *body) unpackBlock(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:232`

### collectDeepAttrs `func (b *body) collectDeepAttrs(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:325`
- Doc: collectDeepAttrs takes either a single object or an array of objects and flattens it into a list of object attributes, c

### Value `func (e *expression) Value(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:381`

### Variables `func (e *expression) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:513`

### Range `func (e *expression) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:557`

### StartRange `func (e *expression) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:561`

### AsTraversal `func (e *expression) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:566`
- Doc: Implementation for hcl.AbsTraversalForExpr.

### ExprCall `func (e *expression) ExprCall(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:583`
- Doc: Implementation for hcl.ExprCall.

### ExprList `func (e *expression) ExprList(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:606`
- Doc: Implementation for hcl.ExprList.

### ExprMap `func (e *expression) ExprMap(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:620`
- Doc: Implementation for hcl.ExprMap.

## teamserver/pkg/profile/yaotl/json/structure_test.go

### TestBodyPartialContent `func TestBodyPartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:15`

### TestBodyContent `func TestBodyContent(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1080`

### TestJustAttributes `func TestJustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1139`

### TestExpressionVariables `func TestExpressionVariables(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1237`

### TestExpressionAsTraversal `func TestExpressionAsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1326`

### TestStaticExpressionList `func TestStaticExpressionList(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1338`

### TestExpression_Value `func TestExpression_Value(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1357`

### TestExpressionValue_Diags `func TestExpressionValue_Diags(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1418`
- Doc: TestExpressionValue_Diags asserts that Value() returns diagnostics from nested evaluations for complex objects (e.g. Obj

## teamserver/pkg/profile/yaotl/json/tokentype_string.go

### String `func (i tokenType) String(`
- Defined: `teamserver/pkg/profile/yaotl/json/tokentype_string.go:24`

## teamserver/pkg/profile/yaotl/merged.go

### MergeFiles `func MergeFiles(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:15`
- Doc: MergeFiles combines the given files to produce a single body that contains configuration from all of the given files.  T

### MergeBodies `func MergeBodies(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:25`
- Doc: MergeBodies is like MergeFiles except it deals directly with bodies, rather than with entire files.

### EmptyBody `func EmptyBody(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:71`
- Doc: EmptyBody returns a body with no content. This body can be used as a placeholder when a body is required but no body con

### Content `func (mb mergedBodies) Content(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:85`
- Doc: Content returns the content produced by applying the given schema to all of the merged bodies and merging the result.  A

### PartialContent `func (mb mergedBodies) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:92`

### JustAttributes `func (mb mergedBodies) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:96`

### MissingItemRange `func (mb mergedBodies) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:130`

### mergedContent `func (mb mergedBodies) mergedContent(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:142`

## teamserver/pkg/profile/yaotl/ops.go

### Index `func Index(`
- Defined: `teamserver/pkg/profile/yaotl/ops.go:23`
- Doc: Index is a helper function that performs the same operation as the index operator in the HCL expression language. That i

### GetAttr `func GetAttr(`
- Defined: `teamserver/pkg/profile/yaotl/ops.go:262`
- Doc: GetAttr is a helper function that performs the same operation as the attribute access in the HCL expression language. Th

### ApplyPath `func ApplyPath(`
- Defined: `teamserver/pkg/profile/yaotl/ops.go:404`
- Doc: ApplyPath is a helper function that applies a cty.Path to a value using the indexing and attribute access operations fro

## teamserver/pkg/profile/yaotl/pos.go

### RangeBetween `func RangeBetween(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:58`
- Doc: RangeBetween returns a new range that spans from the beginning of the start range to the end of the end range.  The resu

### RangeOver `func RangeOver(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:74`
- Doc: RangeOver returns a new range that covers both of the given ranges and possibly additional content between them if the t

### ContainsPos `func (r Range) ContainsPos(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:106`
- Doc: ContainsPos returns true if and only if the given position is contained within the receiving range.  In the unlikely cas

### ContainsOffset `func (r Range) ContainsOffset(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:112`
- Doc: ContainsOffset returns true if and only if the given byte offset is within the receiving Range.

### Ptr `func (r Range) Ptr(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:120`
- Doc: Ptr returns a pointer to a copy of the receiver. This is a convenience when ranges in places where pointers are required

### String `func (r Range) String(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:127`
- Doc: String returns a compact string representation of the receiver. Callers should generally prefer to present a range more 

### Empty `func (r Range) Empty(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:145`

### CanSliceBytes `func (r Range) CanSliceBytes(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:155`
- Doc: CanSliceBytes returns true if SliceBytes could return an accurate sub-slice of the given slice.  This effectively tests 

### SliceBytes `func (r Range) SliceBytes(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:176`
- Doc: SliceBytes returns a sub-slice of the given slice that is covered by the receiving range, assuming that the given slice 

### Overlaps `func (r Range) Overlaps(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:197`
- Doc: Overlaps returns true if the receiver and the other given range share any characters in common.

### Overlap `func (r Range) Overlap(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:219`
- Doc: Overlap finds a range that is either identical to or a sub-range of both the receiver and the other given range. It retu

### PartitionAround `func (r Range) PartitionAround(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:257`
- Doc: PartitionAround finds the portion of the given range that overlaps with the receiver and returns three ranges: the porti

## teamserver/pkg/profile/yaotl/pos_scanner.go

### NewRangeScanner `func NewRangeScanner(`
- Defined: `teamserver/pkg/profile/yaotl/pos_scanner.go:41`
- Doc: NewRangeScanner creates a new RangeScanner for the given buffer, producing ranges for the given filename.  Since ranges 

### NewRangeScannerFragment `func NewRangeScannerFragment(`
- Defined: `teamserver/pkg/profile/yaotl/pos_scanner.go:49`
- Doc: NewRangeScannerFragment is like NewRangeScanner but the ranges it produces will be offset by the given starting position

### Scan `func (sc *RangeScanner) Scan(`
- Defined: `teamserver/pkg/profile/yaotl/pos_scanner.go:58`

### Range `func (sc *RangeScanner) Range(`
- Defined: `teamserver/pkg/profile/yaotl/pos_scanner.go:138`
- Doc: Range returns a range that covers the latest token obtained after a call to Scan returns true.

### Bytes `func (sc *RangeScanner) Bytes(`
- Defined: `teamserver/pkg/profile/yaotl/pos_scanner.go:144`
- Doc: Bytes returns the slice of the input buffer that is covered by the range that would be returned by Range.

### Err `func (sc *RangeScanner) Err(`
- Defined: `teamserver/pkg/profile/yaotl/pos_scanner.go:150`
- Doc: Err can be called after Scan returns false to determine if the latest read resulted in an error, and obtain that error i

## teamserver/pkg/profile/yaotl/specsuite/spec_test.go

### TestMain `func TestMain(`
- Defined: `teamserver/pkg/profile/yaotl/specsuite/spec_test.go:15`

### build `func build(`
- Defined: `teamserver/pkg/profile/yaotl/specsuite/spec_test.go:30`

### TestSpec `func TestSpec(`
- Defined: `teamserver/pkg/profile/yaotl/specsuite/spec_test.go:44`

### goBuild `func goBuild(`
- Defined: `teamserver/pkg/profile/yaotl/specsuite/spec_test.go:91`

## teamserver/pkg/profile/yaotl/static_expr.go

### StaticExpr `func StaticExpr(`
- Defined: `teamserver/pkg/profile/yaotl/static_expr.go:22`
- Doc: StaticExpr returns an Expression that always evaluates to the given value.  This is useful to substitute default values 

### Value `func (e staticExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/static_expr.go:26`

### Variables `func (e staticExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/static_expr.go:30`

### Range `func (e staticExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/static_expr.go:34`

### StartRange `func (e staticExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/static_expr.go:38`

## teamserver/pkg/profile/yaotl/structure.go

### OfType `func (els Blocks) OfType(`
- Defined: `teamserver/pkg/profile/yaotl/structure.go:129`
- Doc: OfType filters the receiving block sequence by block type name, returning a new block sequence including only the blocks

### ByType `func (els Blocks) ByType(`
- Defined: `teamserver/pkg/profile/yaotl/structure.go:141`
- Doc: ByType transforms the receiving block sequence into a map from type name to block sequences of only that type.

## teamserver/pkg/profile/yaotl/structure_at_pos.go

### BlocksAtPos `func (f *File) BlocksAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/structure_at_pos.go:25`
- Doc: BlocksAtPos attempts to find all of the blocks that contain the given position, ordered so that the outermost block is f

### OutermostBlockAtPos `func (f *File) OutermostBlockAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/structure_at_pos.go:44`
- Doc: OutermostBlockAtPos attempts to find a top-level block in the receiving file that contains the given position. This is a

### InnermostBlockAtPos `func (f *File) InnermostBlockAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/structure_at_pos.go:64`
- Doc: InnermostBlockAtPos attempts to find the most deeply-nested block in the receiving file that contains the given position

### OutermostExprAtPos `func (f *File) OutermostExprAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/structure_at_pos.go:86`
- Doc: OutermostExprAtPos attempts to find an expression in the receiving file that contains the given position. This is a best

### AttributeAtPos `func (f *File) AttributeAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/structure_at_pos.go:105`
- Doc: AttributeAtPos attempts to find an attribute definition in the receiving file that contains the given position. This is 

## teamserver/pkg/profile/yaotl/traversal.go

### TraversalJoin `func TraversalJoin(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:24`
- Doc: TraversalJoin appends a relative traversal to an absolute traversal to produce a new absolute traversal.

### TraverseRel `func (t Traversal) TraverseRel(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:41`
- Doc: TraverseRel applies the receiving traversal to the given value, returning the resulting value. This is supported only fo

### TraverseAbs `func (t Traversal) TraverseAbs(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:62`
- Doc: TraverseAbs applies the receiving traversal to the given eval context, returning the resulting value. This is supported 

### IsRelative `func (t Traversal) IsRelative(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:122`
- Doc: IsRelative returns true if the receiver is a relative traversal, or false otherwise.

### SimpleSplit `func (t Traversal) SimpleSplit(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:139`
- Doc: SimpleSplit returns a TraversalSplit where the name lookup is the absolute part and the remainder is the relative part. 

### RootName `func (t Traversal) RootName(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:151`
- Doc: RootName returns the root name for a absolute traversal. Will panic if called on a relative traversal.

### SourceRange `func (t Traversal) SourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:160`
- Doc: SourceRange returns the source range for the traversal.

### TraverseAbs `func (t TraversalSplit) TraverseAbs(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:184`
- Doc: TraverseAbs traverses from a scope to the value resulting from the absolute traversal.

### TraverseRel `func (t TraversalSplit) TraverseRel(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:190`
- Doc: TraverseRel traverses from a given value, assumed to be the result of TraverseAbs on some scope, to a final result for t

### Traverse `func (t TraversalSplit) Traverse(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:196`
- Doc: Traverse is a convenience function to apply TraverseAbs followed by TraverseRel.

### Join `func (t TraversalSplit) Join(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:208`
- Doc: Join concatenates together the Abs and Rel parts to produce a single absolute traversal.

### RootName `func (t TraversalSplit) RootName(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:213`
- Doc: RootName returns the root name for the absolute part of the split.

### isTraverserSigil `func (tr isTraverser) isTraverserSigil(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:228`

### TraversalStep `func (tn TraverseRoot) TraversalStep(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:242`
- Doc: TraversalStep on a TraverseName immediately panics, because absolute traversals cannot be directly traversed.

### SourceRange `func (tn TraverseRoot) SourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:246`

### TraversalStep `func (tn TraverseAttr) TraversalStep(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:257`

### SourceRange `func (tn TraverseAttr) SourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:261`

### TraversalStep `func (tn TraverseIndex) TraversalStep(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:272`

### SourceRange `func (tn TraverseIndex) SourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:276`

### TraversalStep `func (tn TraverseSplat) TraversalStep(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:287`

### SourceRange `func (tn TraverseSplat) SourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:291`

## teamserver/pkg/profile/yaotl/traversal_for_expr.go

### AbsTraversalForExpr `func AbsTraversalForExpr(`
- Defined: `teamserver/pkg/profile/yaotl/traversal_for_expr.go:20`
- Doc: A particular Expression implementation can support this function by offering a method called AsTraversal that takes no a

### RelTraversalForExpr `func RelTraversalForExpr(`
- Defined: `teamserver/pkg/profile/yaotl/traversal_for_expr.go:52`
- Doc: RelTraversalForExpr is similar to AbsTraversalForExpr but it returns a relative traversal instead. Due to the nature of 

### ExprAsKeyword `func ExprAsKeyword(`
- Defined: `teamserver/pkg/profile/yaotl/traversal_for_expr.go:108`
- Doc: The above approach will generate the same message for both the use of an unrecognized keyword and for not using a keywor

## teamserver/pkg/service/agent.go

### NewAgentService `func NewAgentService(`
- Defined: `teamserver/pkg/service/agent.go:45`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/utils/utils.go`

### Json `func (a *AgentService) Json(`
- Defined: `teamserver/pkg/service/agent.go:58`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/utils/utils.go`

### SendTask `func (a *AgentService) SendTask(`
- Defined: `teamserver/pkg/service/agent.go:67`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/utils/utils.go`

### SendResponse `func (a *AgentService) SendResponse(`
- Defined: `teamserver/pkg/service/agent.go:87`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/utils/utils.go`

### SendAgentBuildRequest `func (a *AgentService) SendAgentBuildRequest(`
- Defined: `teamserver/pkg/service/agent.go:140`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/utils/utils.go`

## teamserver/pkg/service/listener.go

### Start `func (l *ListenerService) Start(`
- Defined: `teamserver/pkg/service/listener.go:17`
- Depends on: `teamserver/pkg/logger/logger.go`

### Json `func (l *ListenerService) Json(`
- Defined: `teamserver/pkg/service/listener.go:37`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/service/service.go

### NewService `func NewService(`
- Defined: `teamserver/pkg/service/service.go:27`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### Start `func (s *Service) Start(`
- Defined: `teamserver/pkg/service/service.go:35`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### handleConnection `func (s *Service) handleConnection(`
- Defined: `teamserver/pkg/service/service.go:50`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### authenticate `func (s *Service) authenticate(`
- Defined: `teamserver/pkg/service/service.go:75`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### routine `func (s *Service) routine(`
- Defined: `teamserver/pkg/service/service.go:144`
- Doc: the main service routine
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### dispatch `func (s *Service) dispatch(`
- Defined: `teamserver/pkg/service/service.go:166`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### AgentExist `func (s *Service) AgentExist(`
- Defined: `teamserver/pkg/service/service.go:703`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ClientClose `func (s *Service) ClientClose(`
- Defined: `teamserver/pkg/service/service.go:713`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ListenerExist `func (s *Service) ListenerExist(`
- Defined: `teamserver/pkg/service/service.go:763`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ListenerAdd `func (s *Service) ListenerAdd(`
- Defined: `teamserver/pkg/service/service.go:775`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

## teamserver/pkg/service/types.go

### WriteJson `func (c *ClientService) WriteJson(`
- Defined: `teamserver/pkg/service/types.go:69`
- Depends on: `teamserver/pkg/profile/profile.go`

## teamserver/pkg/socks/socks.go

### NewSocks `func NewSocks(`
- Defined: `teamserver/pkg/socks/socks.go:17`
- Imported by: `teamserver/pkg/agent/demons.go`, `teamserver/pkg/agent/types.go`

### SetHandler `func (s *Socks) SetHandler(`
- Defined: `teamserver/pkg/socks/socks.go:29`
- Imported by: `teamserver/pkg/agent/demons.go`, `teamserver/pkg/agent/types.go`

### Start `func (s *Socks) Start(`
- Defined: `teamserver/pkg/socks/socks.go:35`
- Imported by: `teamserver/pkg/agent/demons.go`, `teamserver/pkg/agent/types.go`

### Close `func (s *Socks) Close(`
- Defined: `teamserver/pkg/socks/socks.go:62`
- Imported by: `teamserver/pkg/agent/demons.go`, `teamserver/pkg/agent/types.go`

## teamserver/pkg/socks/util.go

### SubNegotiationClient `func SubNegotiationClient(`
- Defined: `teamserver/pkg/socks/util.go:70`
- Depends on: `teamserver/pkg/logger/logger.go`

### ReadSocksHeader `func ReadSocksHeader(`
- Defined: `teamserver/pkg/socks/util.go:114`
- Depends on: `teamserver/pkg/logger/logger.go`

### CreateResponsePackage `func CreateResponsePackage(`
- Defined: `teamserver/pkg/socks/util.go:239`
- Depends on: `teamserver/pkg/logger/logger.go`

### SendConnectSuccess `func SendConnectSuccess(`
- Defined: `teamserver/pkg/socks/util.go:255`
- Depends on: `teamserver/pkg/logger/logger.go`

### SendAddressTypeNotSupported `func SendAddressTypeNotSupported(`
- Defined: `teamserver/pkg/socks/util.go:260`
- Depends on: `teamserver/pkg/logger/logger.go`

### SendCommandNotSupported `func SendCommandNotSupported(`
- Defined: `teamserver/pkg/socks/util.go:265`
- Depends on: `teamserver/pkg/logger/logger.go`

### SendConnectFailure `func SendConnectFailure(`
- Defined: `teamserver/pkg/socks/util.go:270`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/utils/utils.go

### UTF16BytesToString `func UTF16BytesToString(`
- Defined: `teamserver/pkg/utils/utils.go:25`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### GenerateID `func GenerateID(`
- Defined: `teamserver/pkg/utils/utils.go:34`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### GenerateString `func GenerateString(`
- Defined: `teamserver/pkg/utils/utils.go:53`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### EncodeCommand `func EncodeCommand(`
- Defined: `teamserver/pkg/utils/utils.go:65`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### IP2Inet `func IP2Inet(`
- Defined: `teamserver/pkg/utils/utils.go:70`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### Port2Htons `func Port2Htons(`
- Defined: `teamserver/pkg/utils/utils.go:84`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### ByteCountSI `func ByteCountSI(`
- Defined: `teamserver/pkg/utils/utils.go:90`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### GetTeamserverPath `func GetTeamserverPath(`
- Defined: `teamserver/pkg/utils/utils.go:104`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### IntToHexString `func IntToHexString(`
- Defined: `teamserver/pkg/utils/utils.go:131`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### HexIntToString `func HexIntToString(`
- Defined: `teamserver/pkg/utils/utils.go:135`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### HexIntToBigEndian `func HexIntToBigEndian(`
- Defined: `teamserver/pkg/utils/utils.go:141`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

## teamserver/pkg/webhook/webhook.go

### StringPtr `func StringPtr(`
- Defined: `teamserver/pkg/webhook/webhook.go:20`
- Depends on: `teamserver/pkg/handlers/http.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### BoolPtr `func BoolPtr(`
- Defined: `teamserver/pkg/webhook/webhook.go:24`
- Depends on: `teamserver/pkg/handlers/http.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### NewWebHook `func NewWebHook(`
- Defined: `teamserver/pkg/webhook/webhook.go:28`
- Depends on: `teamserver/pkg/handlers/http.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### NewAgent `func (w *WebHook) NewAgent(`
- Defined: `teamserver/pkg/webhook/webhook.go:32`
- Depends on: `teamserver/pkg/handlers/http.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### SetDiscord `func (w *WebHook) SetDiscord(`
- Defined: `teamserver/pkg/webhook/webhook.go:134`
- Depends on: `teamserver/pkg/handlers/http.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

## teamserver/pkg/win32/types.go

### StatusToString `func StatusToString(`
- Defined: `teamserver/pkg/win32/types.go:78`
