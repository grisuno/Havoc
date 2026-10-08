# Symbols (page 1 of 13)
Pages: [SYMBOLS.md](SYMBOLS.md), [SYMBOLS_p2.md](SYMBOLS_p2.md), [SYMBOLS_p3.md](SYMBOLS_p3.md), [SYMBOLS_p4.md](SYMBOLS_p4.md), [SYMBOLS_p5.md](SYMBOLS_p5.md), [SYMBOLS_p6.md](SYMBOLS_p6.md), [SYMBOLS_p7.md](SYMBOLS_p7.md), [SYMBOLS_p8.md](SYMBOLS_p8.md), [SYMBOLS_p9.md](SYMBOLS_p9.md), [SYMBOLS_p10.md](SYMBOLS_p10.md), [SYMBOLS_p11.md](SYMBOLS_p11.md), [SYMBOLS_p12.md](SYMBOLS_p12.md), [SYMBOLS_p13.md](SYMBOLS_p13.md)

| Symbol | Kind | File:Line | Signature |
|--------|------|-----------|-----------|
| `HAVOC_EXTERNAL_H` | macro | `client/include/External.h:2` | `#define HAVOC_EXTERNAL_H` |
| `add` | function | `client/include/Havoc/CmdLine.hpp:176` | `void add(const T &v)` |
| `add` | function | `client/include/Havoc/CmdLine.hpp:318` | `void add(const std::string &name,                  char short_name=0,                  const std:...` |
| `add` | function | `client/include/Havoc/CmdLine.hpp:327` | `template <class T>         void add(const std::string &name,                  char short_name=0, ...` |
| `add` | function | `client/include/Havoc/CmdLine.hpp:336` | `void add(const std::string &name,                  char short_name=0,                  const std:...` |
| `argv` | function | `client/include/Havoc/CmdLine.hpp:416` | `std::vector<const char*> argv(argc);` |
| `cast` | function | `client/include/Havoc/CmdLine.hpp:47` | `public:             static Target cast(const Source &arg)` |
| `cast` | function | `client/include/Havoc/CmdLine.hpp:60` | `public:             static Target cast(const Source &arg)` |
| `cast` | function | `client/include/Havoc/CmdLine.hpp:68` | `public:             static std::string cast(const Source &arg)` |
| `cast` | function | `client/include/Havoc/CmdLine.hpp:78` | `public:             static Target cast(const std::string &arg)` |
| `check` | function | `client/include/Havoc/CmdLine.hpp:587` | `private:          void check(int argc, bool ok)` |
| `cmdline_error` | function | `client/include/Havoc/CmdLine.hpp:136` | `public:         cmdline_error(const std::string &msg): msg(msg)` |
| `default_reader` | struct | `client/include/Havoc/CmdLine.hpp:144` | `` |
| `default_value` | function | `client/include/Havoc/CmdLine.hpp:119` | `template <class T>         std::string default_value(T def)` |
| `demangle` | function | `client/include/Havoc/CmdLine.hpp:103` | `static inline std::string demangle(const std::string &name)` |
| `description` | function | `client/include/Havoc/CmdLine.hpp:678` | `const std::string &description() const` |
| `description` | function | `client/include/Havoc/CmdLine.hpp:749` | `const std::string &description() const` |
| `error` | function | `client/include/Havoc/CmdLine.hpp:543` | `std::string error() const` |
| `error_full` | function | `client/include/Havoc/CmdLine.hpp:547` | `std::string error_full() const` |
| `exist` | function | `client/include/Havoc/CmdLine.hpp:355` | `bool exist(const std::string &name) const` |
| `footer` | function | `client/include/Havoc/CmdLine.hpp:347` | `void footer(const std::string &f)` |
| `full_description` | function | `client/include/Havoc/CmdLine.hpp:758` | `protected:             std::string full_description(const std::string &desc)` |
| `get` | function | `client/include/Havoc/CmdLine.hpp:361` | `template <class T>         const T &get(const std::string &name) const` |
| `get` | function | `client/include/Havoc/CmdLine.hpp:707` | `const T &get() const` |
| `has_set` | function | `client/include/Havoc/CmdLine.hpp:658` | `bool has_set() const` |
| `has_set` | function | `client/include/Havoc/CmdLine.hpp:728` | `bool has_set() const` |
| `has_value` | function | `client/include/Havoc/CmdLine.hpp:647` | `bool has_value() const` |
| `has_value` | function | `client/include/Havoc/CmdLine.hpp:711` | `bool has_value() const` |
| `is_same` | struct | `client/include/Havoc/CmdLine.hpp:88` | `` |
| `lexical_cast` | function | `client/include/Havoc/CmdLine.hpp:98` | `Target lexical_cast(const Source &arg)` |
| `lexical_cast_t` | class | `client/include/Havoc/CmdLine.hpp:45` | `` |
| `must` | function | `client/include/Havoc/CmdLine.hpp:666` | `bool must() const` |
| `must` | function | `client/include/Havoc/CmdLine.hpp:737` | `bool must() const` |
| `name` | function | `client/include/Havoc/CmdLine.hpp:670` | `const std::string &name() const` |
| `name` | function | `client/include/Havoc/CmdLine.hpp:741` | `const std::string &name() const` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:182` | `template <class T>     oneof_reader<T> oneof(T a1)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:190` | `template <class T>     oneof_reader<T> oneof(T a1, T a2)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:199` | `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:209` | `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3, T a4)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:220` | `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:232` | `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:245` | `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:259` | `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:274` | `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:290` | `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9...` |
| `oneof_reader` | struct | `client/include/Havoc/CmdLine.hpp:169` | `` |
| `operator` | function | `client/include/Havoc/CmdLine.hpp:145` | `T operator()(const std::string &str)` |
| `operator` | function | `client/include/Havoc/CmdLine.hpp:153` | `T operator()(const std::string &s) const` |
| `operator` | function | `client/include/Havoc/CmdLine.hpp:170` | `T operator()(const std::string &s)` |
| `option_base` | class | `client/include/Havoc/CmdLine.hpp:621` | `` |
| `option_with_value` | class | `client/include/Havoc/CmdLine.hpp:694` | `` |
| `option_with_value` | function | `client/include/Havoc/CmdLine.hpp:696` | `public:             option_with_value(const std::string &name,                               char...` |
| `option_with_value_with_reader` | function | `client/include/Havoc/CmdLine.hpp:780` | `public:             option_with_value_with_reader(const std::string &name,                       ...` |
| `option_without_value` | class | `client/include/Havoc/CmdLine.hpp:638` | `` |
| `option_without_value` | function | `client/include/Havoc/CmdLine.hpp:640` | `public:             option_without_value(const std::string &name,                                ...` |
| `parse` | function | `client/include/Havoc/CmdLine.hpp:372` | `bool parse(const std::string &arg)` |
| `parse` | function | `client/include/Havoc/CmdLine.hpp:414` | `bool parse(const std::vector<std::string> &args)` |
| `parse` | function | `client/include/Havoc/CmdLine.hpp:424` | `bool parse(int argc, const char * const argv[])` |
| `parse_check` | function | `client/include/Havoc/CmdLine.hpp:525` | `void parse_check(const std::string &arg)` |
| `parse_check` | function | `client/include/Havoc/CmdLine.hpp:531` | `void parse_check(const std::vector<std::string> &args)` |
| `parse_check` | function | `client/include/Havoc/CmdLine.hpp:537` | `void parse_check(int argc, char *argv[])` |
| `parser` | class | `client/include/Havoc/CmdLine.hpp:308` | `` |
| `parser` | function | `client/include/Havoc/CmdLine.hpp:310` | `public:         parser()` |
| `range` | function | `client/include/Havoc/CmdLine.hpp:163` | `template <class T>     range_reader<T> range(const T &low, const T &high)` |
| `range_reader` | struct | `client/include/Havoc/CmdLine.hpp:151` | `` |
| `range_reader` | function | `client/include/Havoc/CmdLine.hpp:152` | `range_reader(const T &low, const T &high): low(low), high(high)` |
| `read` | function | `client/include/Havoc/CmdLine.hpp:790` | `private:             T read(const std::string &s)` |
| `readable_typename` | function | `client/include/Havoc/CmdLine.hpp:113` | `template <class T>         std::string readable_typename()` |
| `rest` | function | `client/include/Havoc/CmdLine.hpp:368` | `const std::vector<std::string> &rest() const` |
| `set` | function | `client/include/Havoc/CmdLine.hpp:649` | `bool set()` |
| `set` | function | `client/include/Havoc/CmdLine.hpp:654` | `bool set(const std::string &)` |
| `set` | function | `client/include/Havoc/CmdLine.hpp:713` | `bool set()` |
| `set` | function | `client/include/Havoc/CmdLine.hpp:717` | `bool set(const std::string &value)` |
| `set_option` | function | `client/include/Havoc/CmdLine.hpp:599` | `void set_option(const std::string &name)` |
| `set_option` | function | `client/include/Havoc/CmdLine.hpp:610` | `void set_option(const std::string &name, const std::string &value)` |
| `set_program_name` | function | `client/include/Havoc/CmdLine.hpp:351` | `void set_program_name(const std::string &name)` |
| `short_description` | function | `client/include/Havoc/CmdLine.hpp:682` | `std::string short_description() const` |
| `short_description` | function | `client/include/Havoc/CmdLine.hpp:753` | `std::string short_description() const` |
| `short_name` | function | `client/include/Havoc/CmdLine.hpp:674` | `char short_name() const` |
| `short_name` | function | `client/include/Havoc/CmdLine.hpp:745` | `char short_name() const` |
| `usage` | function | `client/include/Havoc/CmdLine.hpp:554` | `std::string usage() const` |
| `valid` | function | `client/include/Havoc/CmdLine.hpp:662` | `bool valid() const` |
| `valid` | function | `client/include/Havoc/CmdLine.hpp:732` | `bool valid() const` |
| `what` | function | `client/include/Havoc/CmdLine.hpp:138` | `const char *what() const throw()` |
| `Connector` | class | `client/include/Havoc/Connector.hpp:14` | `` |
| `Disconnect` | function | `client/include/Havoc/Connector.hpp:27` | `bool Disconnect();` |
| `HAVOC_CONNECTOR_HPP` | macro | `client/include/Havoc/Connector.hpp:2` | `#define HAVOC_CONNECTOR_HPP` |
| `SendLogin` | function | `client/include/Havoc/Connector.hpp:29` | `void SendLogin();` |
| `SendPackage` | function | `client/include/Havoc/Connector.hpp:30` | `void SendPackage( Util::Packager::PPackage package );` |
| `AddScript` | function | `client/include/Havoc/DBManager/DBManager.hpp:33` | `bool AddScript( QString Path );` |
| `CheckScript` | function | `client/include/Havoc/DBManager/DBManager.hpp:35` | `bool CheckScript( QString Path );` |
| `HAVOC_DBMANAGER_HPP` | macro | `client/include/Havoc/DBManager/DBManager.hpp:2` | `#define HAVOC_DBMANAGER_HPP` |
| `RemoveScript` | function | `client/include/Havoc/DBManager/DBManager.hpp:34` | `bool RemoveScript( QString Path );` |
| `addTeamserverInfo` | function | `client/include/Havoc/DBManager/DBManager.hpp:27` | `bool addTeamserverInfo( const Util::ConnectionInfo& );` |
| `checkTeamserverExists` | function | `client/include/Havoc/DBManager/DBManager.hpp:28` | `bool checkTeamserverExists( const QString& ProfileName );` |
| `createNewDatabase` | function | `client/include/Havoc/DBManager/DBManager.hpp:17` | `bool createNewDatabase();` |
| `removeAllTeamservers` | function | `client/include/Havoc/DBManager/DBManager.hpp:30` | `bool removeAllTeamservers();` |
| `removeTeamserverInfo` | function | `client/include/Havoc/DBManager/DBManager.hpp:29` | `bool removeTeamserverInfo( const QString& ProfileName );` |
| `CONSOLE_ERROR` | macro | `client/include/Havoc/DemonCmdDispatch.h:15` | `#define CONSOLE_ERROR( x )` |
| `CONSOLE_INFO` | macro | `client/include/Havoc/DemonCmdDispatch.h:20` | `#define CONSOLE_INFO( x )` |
| `Command` | struct | `client/include/Havoc/DemonCmdDispatch.h:130` | `` |
| `CommandExecute` | class | `client/include/Havoc/DemonCmdDispatch.h:61` | `` |
| `CommandString` | type_alias | `client/include/Havoc/DemonCmdDispatch.h:117` | `typedef struct SubCommand { QString CommandString;` |
| `CommandString` | type_alias | `client/include/Havoc/DemonCmdDispatch.h:129` | `typedef struct Command { QString CommandString;` |
| `Commands` | enum | `client/include/Havoc/DemonCmdDispatch.h:23` | `` |
| `Commands` | class | `client/include/Havoc/DemonCmdDispatch.h:23` | `` |
| `DispatchOutput` | class | `client/include/Havoc/DemonCmdDispatch.h:53` | `` |
| `HAVOC_DEMONCMDDISPATCH_H` | macro | `client/include/Havoc/DemonCmdDispatch.h:2` | `#define HAVOC_DEMONCMDDISPATCH_H` |
| `SEND` | macro | `client/include/Havoc/DemonCmdDispatch.h:12` | `#define SEND( f )` |
| `SubCommand` | struct | `client/include/Havoc/DemonCmdDispatch.h:118` | `` |
| `Exit` | function | `client/include/Havoc/Havoc.hpp:28` | `static void Exit();` |
| `HAVOC_HAVOC_HPP` | macro | `client/include/Havoc/Havoc.hpp:2` | `#define HAVOC_HAVOC_HPP` |
| `Init` | function | `client/include/Havoc/Havoc.hpp:25` | `void Init( int argc, char** argv );` |
| `Start` | function | `client/include/Havoc/Havoc.hpp:26` | `void Start();` |
| `Add` | variable | `client/include/Havoc/Packager.hpp:46` | `extern const int Add;` |
| `AgentRegister` | variable | `client/include/Havoc/Packager.hpp:87` | `extern const int AgentRegister;` |
| `Body_t` | struct | `client/include/Havoc/Packager.hpp:21` | `` |
| `DecodePackage` | function | `client/include/Havoc/Packager.hpp:106` | `public: static Util::Packager::PPackage DecodePackage(const QString& Package );` |
| `DispatchChat` | function | `client/include/Havoc/Packager.hpp:115` | `bool DispatchChat( Util::Packager::PPackage Package );` |
| `DispatchGate` | function | `client/include/Havoc/Packager.hpp:117` | `bool DispatchGate( Util::Packager::PPackage Package );` |
| `DispatchInitConnection` | function | `client/include/Havoc/Packager.hpp:113` | `public: bool DispatchInitConnection( Util::Packager::PPackage Package );` |
| `DispatchListener` | function | `client/include/Havoc/Packager.hpp:114` | `bool DispatchListener( Util::Packager::PPackage Package );` |
| `DispatchPackage` | function | `client/include/Havoc/Packager.hpp:109` | `bool DispatchPackage( Util::Packager::PPackage Package );` |
| `DispatchService` | function | `client/include/Havoc/Packager.hpp:118` | `bool DispatchService( Util::Packager::PPackage Package );` |
| `DispatchSession` | function | `client/include/Havoc/Packager.hpp:116` | `bool DispatchSession( Util::Packager::PPackage Package );` |
| `DispatchTeamserver` | function | `client/include/Havoc/Packager.hpp:119` | `bool DispatchTeamserver( Util::Packager::PPackage Package );` |
| `Edit` | variable | `client/include/Havoc/Packager.hpp:48` | `extern const int Edit;` |
| `Error` | variable | `client/include/Havoc/Packager.hpp:38` | `extern const int Error;` |
| `Error` | variable | `client/include/Havoc/Packager.hpp:50` | `extern const int Error;` |
| `HAVOC_PACKAGER_H` | macro | `client/include/Havoc/Packager.hpp:2` | `#define HAVOC_PACKAGER_H` |
| `Head` | type_alias | `client/include/Havoc/Packager.hpp:26` | `typedef struct Package { Head_t Head;` |
| `Head_t` | struct | `client/include/Havoc/Packager.hpp:12` | `` |
| `ListenerRegister` | variable | `client/include/Havoc/Packager.hpp:88` | `extern const int ListenerRegister;` |
| `Logger` | variable | `client/include/Havoc/Packager.hpp:94` | `extern const int Logger;` |
| `Login` | variable | `client/include/Havoc/Packager.hpp:39` | `extern const int Login;` |
| `MSOffice` | variable | `client/include/Havoc/Packager.hpp:70` | `extern const int MSOffice;` |
| `Mark` | variable | `client/include/Havoc/Packager.hpp:49` | `extern const int Mark;` |
| `MarkAs` | variable | `client/include/Havoc/Packager.hpp:80` | `extern const int MarkAs;` |
| `NewListener` | variable | `client/include/Havoc/Packager.hpp:58` | `extern const int NewListener;` |
| `NewMessage` | variable | `client/include/Havoc/Packager.hpp:57` | `extern const int NewMessage;` |
| `NewSession` | variable | `client/include/Havoc/Packager.hpp:61` | `extern const int NewSession;` |
| `NewSession` | variable | `client/include/Havoc/Packager.hpp:77` | `extern const int NewSession;` |
| `NewUser` | variable | `client/include/Havoc/Packager.hpp:59` | `extern const int NewUser;` |
| `Package` | struct | `client/include/Havoc/Packager.hpp:27` | `` |
| `Profile` | variable | `client/include/Havoc/Packager.hpp:95` | `extern const int Profile;` |
| `ReceiveCommand` | variable | `client/include/Havoc/Packager.hpp:79` | `extern const int ReceiveCommand;` |
| `Remove` | variable | `client/include/Havoc/Packager.hpp:47` | `extern const int Remove;` |
| `Remove` | variable | `client/include/Havoc/Packager.hpp:81` | `extern const int Remove;` |
| `SendCommand` | variable | `client/include/Havoc/Packager.hpp:78` | `extern const int SendCommand;` |
| `Staged` | variable | `client/include/Havoc/Packager.hpp:68` | `extern const int Staged;` |
| `Stageless` | variable | `client/include/Havoc/Packager.hpp:69` | `extern const int Stageless;` |
| `Success` | variable | `client/include/Havoc/Packager.hpp:37` | `extern const int Success;` |
| `Type` | variable | `client/include/Havoc/Packager.hpp:36` | `extern const int Type;` |
| `Type` | variable | `client/include/Havoc/Packager.hpp:44` | `extern const int Type;` |
| `Type` | variable | `client/include/Havoc/Packager.hpp:55` | `extern const int Type;` |
| `Type` | variable | `client/include/Havoc/Packager.hpp:66` | `extern const int Type;` |
| `Type` | variable | `client/include/Havoc/Packager.hpp:75` | `extern const int Type;` |
| `Type` | variable | `client/include/Havoc/Packager.hpp:86` | `extern const int Type;` |
| `Type` | variable | `client/include/Havoc/Packager.hpp:93` | `extern const int Type;` |
| `UserDisconnect` | variable | `client/include/Havoc/Packager.hpp:60` | `extern const int UserDisconnect;` |
| `setTeamserver` | function | `client/include/Havoc/Packager.hpp:110` | `void setTeamserver(QString Name);` |
| `EventClass_OnDemonOutput` | function | `client/include/Havoc/PythonApi/Event.h:23` | `PyObject* EventClass_OnDemonOutput( PPyEvents self, PyObject *args );` |
| `EventClass_OnNewSession` | function | `client/include/Havoc/PythonApi/Event.h:22` | `PyObject* EventClass_OnNewSession( PPyEvents self, PyObject *args );` |
| `EventClass_dealloc` | function | `client/include/Havoc/PythonApi/Event.h:16` | `void EventClass_dealloc( PPyEvents self );` |
| `EventClass_init` | function | `client/include/Havoc/PythonApi/Event.h:18` | `int EventClass_init( PPyEvents self, PyObject *args, PyObject *kwds );` |
| `EventClass_new` | function | `client/include/Havoc/PythonApi/Event.h:17` | `PyObject* EventClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );` |
| `HAVOC_EVENT_H` | macro | `client/include/Havoc/PythonApi/Event.h:2` | `#define HAVOC_EVENT_H` |
| `PyEventClass_Type` | variable | `client/include/Havoc/PythonApi/Event.h:14` | `extern PyTypeObject PyEventClass_Type;` |
| `HAVOC_HAVOCUI_H` | macro | `client/include/Havoc/PythonApi/HavocUi.h:2` | `#define HAVOC_HAVOCUI_H` |
| `AgentClass_Command` | function | `client/include/Havoc/PythonApi/PyAgentClass.hpp:31` | `PyObject* AgentClass_Command( PPyAgentClass self, PyObject *args );` |
| `AgentClass_ConsoleWrite` | function | `client/include/Havoc/PythonApi/PyAgentClass.hpp:30` | `PyObject* AgentClass_ConsoleWrite( PPyAgentClass self, PyObject *args );` |
| `AgentClass_dealloc` | function | `client/include/Havoc/PythonApi/PyAgentClass.hpp:27` | `void AgentClass_dealloc( PPyAgentClass self );` |
| `AgentClass_init` | function | `client/include/Havoc/PythonApi/PyAgentClass.hpp:29` | `int AgentClass_init( PPyAgentClass self, PyObject *args, PyObject *kwds );` |
| `AgentClass_new` | function | `client/include/Havoc/PythonApi/PyAgentClass.hpp:28` | `PyObject* AgentClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );` |
| `AllocMov` | macro | `client/include/Havoc/PythonApi/PyAgentClass.hpp:6` | `#define AllocMov( des, src, size )` |
| `HAVOC_PYAGENTCLASS_HPP` | macro | `client/include/Havoc/PythonApi/PyAgentClass.hpp:2` | `#define HAVOC_PYAGENTCLASS_HPP` |
| `PyAgentClass_Type` | variable | `client/include/Havoc/PythonApi/PyAgentClass.hpp:25` | `extern PyTypeObject PyAgentClass_Type;` |
| `DemonClass_Command` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:52` | `PyObject* DemonClass_Command( PPyDemonClass self, PyObject *args );` |
| `DemonClass_CommandGetOutput` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:53` | `PyObject* DemonClass_CommandGetOutput( PPyDemonClass self, PyObject *args );` |
| `DemonClass_ConsoleWrite` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:57` | `PyObject* DemonClass_ConsoleWrite( PPyDemonClass self, PyObject *args );` |
| `DemonClass_DllInject` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:46` | `PyObject* DemonClass_DllInject( PPyDemonClass self, PyObject *args );` |
| `DemonClass_DllSpawn` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:47` | `PyObject* DemonClass_DllSpawn( PPyDemonClass self, PyObject *args );` |
| `DemonClass_DotnetInlineExecute` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:50` | `PyObject* DemonClass_DotnetInlineExecute( PPyDemonClass self, PyObject *args );` |
| `DemonClass_InlineExecute` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:48` | `PyObject* DemonClass_InlineExecute( PPyDemonClass self, PyObject *args );` |
| `DemonClass_InlineExecuteGetOutput` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:49` | `PyObject* DemonClass_InlineExecuteGetOutput( PPyDemonClass self, PyObject *args );` |
| `DemonClass_ProcessCreate` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:45` | `PyObject* DemonClass_ProcessCreate( PPyDemonClass self, PyObject *args );` |
| `DemonClass_RegisterCallback` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:51` | `PyObject* DemonClass_RegisterCallback( PPyDemonClass self, PyObject *args );` |
| `DemonClass_ShellcodeSpawn` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:54` | `PyObject* DemonClass_ShellcodeSpawn( PPyDemonClass self, PyObject *args );` |
| `DemonClass_dealloc` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:36` | `void DemonClass_dealloc( PPyDemonClass self );` |
| `DemonClass_init` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:38` | `int DemonClass_init( PPyDemonClass self, PyObject *args, PyObject *kwds );` |
| `DemonClass_new` | function | `client/include/Havoc/PythonApi/PyDemonClass.h:37` | `PyObject* DemonClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );` |
| `HAVOC_PYDEMONCLASS_H` | macro | `client/include/Havoc/PythonApi/PyDemonClass.h:2` | `#define HAVOC_PYDEMONCLASS_H` |
| `PyDemonClass_Type` | variable | `client/include/Havoc/PythonApi/PyDemonClass.h:34` | `extern PyTypeObject PyDemonClass_Type;` |
| `HAVOC_PYTHONAPI_H` | macro | `client/include/Havoc/PythonApi/PythonApi.h:2` | `#define HAVOC_PYTHONAPI_H` |
| `PY_FUNCTION` | macro | `client/include/Havoc/PythonApi/PythonApi.h:10` | `#define PY_FUNCTION( x )` |
| `PY_FUNCTION_KW` | macro | `client/include/Havoc/PythonApi/PythonApi.h:11` | `#define PY_FUNCTION_KW( x )` |
| `PyMethode_Havoc` | variable | `client/include/Havoc/PythonApi/PythonApi.h:17` | `extern PyMethodDef PyMethode_Havoc[];` |
| `PyMethode_HavocUI` | variable | `client/include/Havoc/PythonApi/PythonApi.h:41` | `extern PyMethodDef PyMethode_HavocUI[];` |
| `Stdout` | struct | `client/include/Havoc/PythonApi/PythonApi.h:70` | `` |
| `Stdout_flush` | function | `client/include/Havoc/PythonApi/PythonApi.h:77` | `PyObject* Stdout_flush(PyObject* self, PyObject* args);` |
| `Stdout_write` | function | `client/include/Havoc/PythonApi/PythonApi.h:76` | `PyObject* Stdout_write(PyObject* self, PyObject* args);` |
| `havoc` | variable | `client/include/Havoc/PythonApi/PythonApi.h:33` | `extern struct PyModuleDef havoc;` |
| `havocui` | variable | `client/include/Havoc/PythonApi/PythonApi.h:58` | `extern struct PyModuleDef havocui;` |
| `reset_stdout` | function | `client/include/Havoc/PythonApi/PythonApi.h:80` | `void reset_stdout();` |
| `set_stdout` | function | `client/include/Havoc/PythonApi/PythonApi.h:79` | `void set_stdout(stdout_write_type write);` |
| `stdout_write_type` | type_alias | `client/include/Havoc/PythonApi/PythonApi.h:68` | `typedef std::function<void(std::string)> stdout_write_type;` |
| `DialogClass_addButton` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:51` | `PyObject* DialogClass_addButton( PPyDialogClass self, PyObject *args );` |
| `DialogClass_addCalendar` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:55` | `PyObject* DialogClass_addCalendar( PPyDialogClass self, PyObject *args );` |
| `DialogClass_addCheckbox` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:52` | `PyObject* DialogClass_addCheckbox( PPyDialogClass self, PyObject *args );` |
| `DialogClass_addCombobox` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:53` | `PyObject* DialogClass_addCombobox( PPyDialogClass self, PyObject *args );` |
| `DialogClass_addDial` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:58` | `PyObject* DialogClass_addDial( PPyDialogClass self, PyObject *args );` |
| `DialogClass_addImage` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:57` | `PyObject* DialogClass_addImage( PPyDialogClass self, PyObject *args );` |
| `DialogClass_addLabel` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:50` | `PyObject* DialogClass_addLabel( PPyDialogClass self, PyObject *args );` |
| `DialogClass_addLineedit` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:54` | `PyObject* DialogClass_addLineedit( PPyDialogClass self, PyObject *args );` |
| `DialogClass_addSlider` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:59` | `PyObject* DialogClass_addSlider( PPyDialogClass self, PyObject *args );` |
| `DialogClass_clear` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:49` | `PyObject* DialogClass_clear( PPyDialogClass self, PyObject *args );` |
| `DialogClass_close` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:48` | `PyObject* DialogClass_close( PPyDialogClass self, PyObject *args );` |
| `DialogClass_dealloc` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:41` | `void DialogClass_dealloc( PPyDialogClass self );` |
| `DialogClass_exec` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:47` | `PyObject* DialogClass_exec( PPyDialogClass self, PyObject *args );` |
| `DialogClass_init` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:43` | `int DialogClass_init( PPyDialogClass self, PyObject *args, PyObject *kwds );` |
| `DialogClass_new` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:42` | `PyObject* DialogClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );` |
| `DialogClass_replaceLabel` | function | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:56` | `PyObject* DialogClass_replaceLabel( PPyDialogClass self, PyObject *args );` |
| `HAVOC_PYDIALOGCLASS_H` | macro | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:2` | `#define HAVOC_PYDIALOGCLASS_H` |
| `PyDialogClass_Type` | variable | `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:39` | `extern PyTypeObject PyDialogClass_Type;` |
| `HAVOC_PYLOGGERCLASS_H` | macro | `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:2` | `#define HAVOC_PYLOGGERCLASS_H` |
| `LoggerClass_addText` | function | `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:40` | `PyObject* LoggerClass_addText( PPyLoggerClass self, PyObject *args );` |
| `LoggerClass_clear` | function | `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:41` | `PyObject* LoggerClass_clear( PPyLoggerClass self, PyObject *args );` |
| `LoggerClass_dealloc` | function | `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:32` | `void LoggerClass_dealloc( PPyLoggerClass self );` |
| `LoggerClass_init` | function | `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:34` | `int LoggerClass_init( PPyLoggerClass self, PyObject *args, PyObject *kwds );` |
| `LoggerClass_new` | function | `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:33` | `PyObject* LoggerClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );` |
| `LoggerClass_setBottomTab` | function | `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:38` | `PyObject* LoggerClass_setBottomTab( PPyLoggerClass self, PyObject *args );` |
| `LoggerClass_setSmallTab` | function | `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:39` | `PyObject* LoggerClass_setSmallTab( PPyLoggerClass self, PyObject *args );` |
| `PyLoggerClass_Type` | variable | `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:30` | `extern PyTypeObject PyLoggerClass_Type;` |
| `HAVOC_PYTREECLASS_H` | macro | `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:2` | `#define HAVOC_PYTREECLASS_H` |
| `PyTreeClass_Type` | variable | `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:46` | `extern PyTypeObject PyTreeClass_Type;` |
| `TreeClass_addRow` | function | `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:56` | `PyObject* TreeClass_addRow( PPyTreeClass self, PyObject *args );` |
| `TreeClass_dealloc` | function | `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:48` | `void TreeClass_dealloc( PPyTreeClass self );` |
| `TreeClass_init` | function | `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:50` | `int TreeClass_init( PPyTreeClass self, PyObject *args, PyObject *kwds );` |
| `TreeClass_new` | function | `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:49` | `PyObject* TreeClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );` |
| `TreeClass_setBottomTab` | function | `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:54` | `PyObject* TreeClass_setBottomTab( PPyTreeClass self, PyObject *args );` |
| `TreeClass_setItem` | function | `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:57` | `PyObject* TreeClass_setItem( PPyTreeClass self, PyObject *args );` |
| `TreeClass_setPanel` | function | `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:58` | `PyObject* TreeClass_setPanel( PPyTreeClass self, PyObject *args );` |
| `TreeClass_setSmallTab` | function | `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:55` | `PyObject* TreeClass_setSmallTab( PPyTreeClass self, PyObject *args );` |
| `HAVOC_PYWIDGETCLASS_H` | macro | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:2` | `#define HAVOC_PYWIDGETCLASS_H` |
| `PyWidgetClass_Type` | variable | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:39` | `extern PyTypeObject PyWidgetClass_Type;` |
| `WidgetClass_addButton` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:50` | `PyObject* WidgetClass_addButton( PPyWidgetClass self, PyObject *args );` |
| `WidgetClass_addCalendar` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:54` | `PyObject* WidgetClass_addCalendar( PPyWidgetClass self, PyObject *args );` |
| `WidgetClass_addCheckbox` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:51` | `PyObject* WidgetClass_addCheckbox( PPyWidgetClass self, PyObject *args );` |
| `WidgetClass_addCombobox` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:52` | `PyObject* WidgetClass_addCombobox( PPyWidgetClass self, PyObject *args );` |
| `WidgetClass_addDial` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:58` | `PyObject* WidgetClass_addDial( PPyWidgetClass self, PyObject *args );` |
| `WidgetClass_addImage` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:57` | `PyObject* WidgetClass_addImage( PPyWidgetClass self, PyObject *args );` |
| `WidgetClass_addLabel` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:47` | `PyObject* WidgetClass_addLabel( PPyWidgetClass self, PyObject *args );` |
| `WidgetClass_addLineedit` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:53` | `PyObject* WidgetClass_addLineedit( PPyWidgetClass self, PyObject *args );` |
| `WidgetClass_addSlider` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:59` | `PyObject* WidgetClass_addSlider( PPyWidgetClass self, PyObject *args );` |
| `WidgetClass_clear` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:56` | `PyObject* WidgetClass_clear( PPyWidgetClass self, PyObject *args );` |
| `WidgetClass_dealloc` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:41` | `void WidgetClass_dealloc( PPyWidgetClass self );` |
| `WidgetClass_init` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:43` | `int WidgetClass_init( PPyWidgetClass self, PyObject *args, PyObject *kwds );` |
| `WidgetClass_new` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:42` | `PyObject* WidgetClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );` |
| `WidgetClass_replaceLabel` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:55` | `PyObject* WidgetClass_replaceLabel( PPyWidgetClass self, PyObject *args );` |
| `WidgetClass_setBottomTab` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:48` | `PyObject* WidgetClass_setBottomTab( PPyWidgetClass self, PyObject *args );` |
| `WidgetClass_setSmallTab` | function | `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:49` | `PyObject* WidgetClass_setSmallTab( PPyWidgetClass self, PyObject *args );` |
| `AgentCommands` | struct | `client/include/Havoc/Service.hpp:23` | `` |
| `AgentFormat` | struct | `client/include/Havoc/Service.hpp:17` | `` |
| `CommandParam` | struct | `client/include/Havoc/Service.hpp:10` | `` |
| `DemonMagicValue` | variable | `client/include/Havoc/Service.hpp:48` | `extern uint64_t DemonMagicValue;` |
| `HAVOC_SERVICE_HPP` | macro | `client/include/Havoc/Service.hpp:2` | `#define HAVOC_SERVICE_HPP` |
| `ServiceAgent` | struct | `client/include/Havoc/Service.hpp:34` | `` |
| `About` | class | `client/include/UserInterface/Dialogs/About.hpp:7` | `` |
| `HAVOC_ABOUTDIALOG_H` | macro | `client/include/UserInterface/Dialogs/About.hpp:2` | `#define HAVOC_ABOUTDIALOG_H` |
| `onButtonClose` | function | `client/include/UserInterface/Dialogs/About.hpp:23` | `public slots: void onButtonClose();` |
| `setupUi` | function | `client/include/UserInterface/Dialogs/About.hpp:19` | `void setupUi();` |
| `HAVOC_CONNECTDIALOG_H` | macro | `client/include/UserInterface/Dialogs/Connect.hpp:2` | `#define HAVOC_CONNECTDIALOG_H` |
| `handleContextMenu` | function | `client/include/UserInterface/Dialogs/Connect.hpp:58` | `void handleContextMenu(const QPoint &pos);` |
| `itemRemove` | function | `client/include/UserInterface/Dialogs/Connect.hpp:60` | `void itemRemove();` |
| `itemSelected` | function | `client/include/UserInterface/Dialogs/Connect.hpp:57` | `void itemSelected();` |
| `itemsClear` | function | `client/include/UserInterface/Dialogs/Connect.hpp:61` | `void itemsClear();` |
| `onButton_Connect` | function | `client/include/UserInterface/Dialogs/Connect.hpp:54` | `private slots: void onButton_Connect();` |
| `onButton_NewProfile` | function | `client/include/UserInterface/Dialogs/Connect.hpp:55` | `void onButton_NewProfile();` |
| `passDB` | function | `client/include/UserInterface/Dialogs/Connect.hpp:51` | `void passDB( HavocNamespace::HavocSpace::DBManager* db );` |
| `setupUi` | function | `client/include/UserInterface/Dialogs/Connect.hpp:49` | `void setupUi( QDialog* Form );` |
| `Data` | struct | `client/include/UserInterface/Dialogs/Listener.hpp:30` | `` |
| `HAVOC_LISTENER_HPP` | macro | `client/include/UserInterface/Dialogs/Listener.hpp:3` | `#define HAVOC_LISTENER_HPP` |
| `ServiceListener` | struct | `client/include/UserInterface/Dialogs/Listener.hpp:35` | `` |
| `onButton_Save` | function | `client/include/UserInterface/Dialogs/Listener.hpp:156` | `protected slots: void onButton_Save();` |
| `onProxyEnabled` | function | `client/include/UserInterface/Dialogs/Listener.hpp:158` | `void onProxyEnabled();` |
| `HAVOC_STAGELESSDIALOG_H` | macro | `client/include/UserInterface/Dialogs/Payload.hpp:2` | `#define HAVOC_STAGELESSDIALOG_H` |
| `Payload` | class | `client/include/UserInterface/Dialogs/Payload.hpp:21` | `` |
| `ConnectEvents` | function | `client/include/UserInterface/HavocUI.hpp:77` | `void ConnectEvents();` |
| `HAVOC_HAVOCUI_HPP` | macro | `client/include/UserInterface/HavocUI.hpp:2` | `#define HAVOC_HAVOCUI_HPP` |
| `MarkSessionAs` | function | `client/include/UserInterface/HavocUI.hpp:68` | `public: void MarkSessionAs( HavocNamespace::Util::SessionItem session, QString Mark );` |
| `NewBottomTab` | function | `client/include/UserInterface/HavocUI.hpp:75` | `void NewBottomTab( QWidget* TabWidget, const std::string& TitleName, const QString IconPath = "" ) const;` |
| `NewSmallTab` | function | `client/include/UserInterface/HavocUI.hpp:76` | `void NewSmallTab( QWidget* TabWidget, const std::string& TitleName ) const;` |
| `NewTeamserverTab` | function | `client/include/UserInterface/HavocUI.hpp:73` | `void NewTeamserverTab( HavocNamespace::Util::ConnectionInfo* );` |
| `OneSecondTick` | function | `client/include/UserInterface/HavocUI.hpp:81` | `public slots: void OneSecondTick();` |
| `PythonPrepare` | function | `client/include/UserInterface/HavocUI.hpp:78` | `void PythonPrepare();` |
| `UpdateSessionsHealth` | function | `client/include/UserInterface/HavocUI.hpp:69` | `void UpdateSessionsHealth();` |
| `retranslateUi` | function | `client/include/UserInterface/HavocUI.hpp:71` | `void retranslateUi( QMainWindow *Havoc ) const;` |
| `setDBManager` | function | `client/include/UserInterface/HavocUI.hpp:72` | `void setDBManager( HavocSpace::DBManager* dbManager );` |
| `setupUi` | function | `client/include/UserInterface/HavocUI.hpp:70` | `void setupUi( QMainWindow *Havoc );` |
| `AppendText` | function | `client/include/UserInterface/SmallWidgets/EventViewer.hpp:13` | `void AppendText(const QString& Time, const QString &text) const;` |
| `HAVOC_EVENTVIEWER_HPP` | macro | `client/include/UserInterface/SmallWidgets/EventViewer.hpp:2` | `#define HAVOC_EVENTVIEWER_HPP` |
| `setupUi` | function | `client/include/UserInterface/SmallWidgets/EventViewer.hpp:12` | `void setupUi(QWidget* Widget);` |
| `AddUserMessage` | function | `client/include/UserInterface/Widgets/Chat.hpp:21` | `void AddUserMessage( const QString Time, QString User, QString text ) const;` |
| `AppendFromInput` | function | `client/include/UserInterface/Widgets/Chat.hpp:24` | `public slots: void AppendFromInput();` |
| `AppendText` | function | `client/include/UserInterface/Widgets/Chat.hpp:19` | `void AppendText( const QString& Time, const QString& text ) const;` |
| `HAVOC_CHATWIDGET_H` | macro | `client/include/UserInterface/Widgets/Chat.hpp:2` | `#define HAVOC_CHATWIDGET_H` |
| `setupUi` | function | `client/include/UserInterface/Widgets/Chat.hpp:18` | `void setupUi( QWidget* widget );` |
| `AddCommand` | function | `client/include/UserInterface/Widgets/DemonInteracted.h:33` | `void AddCommand( const QString& Command );` |
| `AppendFromInput` | function | `client/include/UserInterface/Widgets/DemonInteracted.h:59` | `private slots: void AppendFromInput();` |
| `AppendNoNL` | function | `client/include/UserInterface/Widgets/DemonInteracted.h:49` | `void AppendNoNL( const QString& test );` |
| `AppendRaw` | function | `client/include/UserInterface/Widgets/DemonInteracted.h:48` | `void AppendRaw( const QString& text = "" );` |
| `AppendText` | function | `client/include/UserInterface/Widgets/DemonInteracted.h:47` | `void AppendText( const QString& text );` |
| `AutoCompleteAdd` | function | `client/include/UserInterface/Widgets/DemonInteracted.h:54` | `void AutoCompleteAdd( QString text );` |
| `AutoCompleteAddList` | function | `client/include/UserInterface/Widgets/DemonInteracted.h:55` | `void AutoCompleteAddList( QStringList list );` |
| `AutoCompleteClear` | function | `client/include/UserInterface/Widgets/DemonInteracted.h:56` | `void AutoCompleteClear();` |
| `DemonInput` | class | `client/include/UserInterface/Widgets/DemonInteracted.h:26` | `` |
| `DemonInteracted` | class | `client/include/UserInterface/Widgets/DemonInteracted.h:9` | `` |
| `HAVOC_DEMONINTERACTED_H` | macro | `client/include/UserInterface/Widgets/DemonInteracted.h:2` | `#define HAVOC_DEMONINTERACTED_H` |
| `handleDownKey` | function | `client/include/UserInterface/Widgets/DemonInteracted.h:42` | `void handleDownKey();` |
| `handleKeyPress` | function | `client/include/UserInterface/Widgets/DemonInteracted.h:39` | `private: bool handleKeyPress(QKeyEvent* eventKey);` |
| `handleTabKey` | function | `client/include/UserInterface/Widgets/DemonInteracted.h:40` | `void handleTabKey();` |
| `handleUpKey` | function | `client/include/UserInterface/Widgets/DemonInteracted.h:41` | `void handleUpKey();` |
| `setupUi` | function | `client/include/UserInterface/Widgets/DemonInteracted.h:46` | `void setupUi( QWidget* Form );` |
| `AddData` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:85` | `void AddData( QJsonDocument JsonData );` |
| `ChangePathAndSendRequest` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:100` | `void ChangePathAndSendRequest( QString Path );` |
| `FileBrowser` | class | `client/include/UserInterface/Widgets/FileBrowser.hpp:53` | `` |
| `FileBrowserTableItem` | class | `client/include/UserInterface/Widgets/FileBrowser.hpp:40` | `` |
| `FileBrowserTreeItem` | class | `client/include/UserInterface/Widgets/FileBrowser.hpp:46` | `` |
| `FileData` | struct | `client/include/UserInterface/Widgets/FileBrowser.hpp:23` | `` |
| `HAVOC_FILEBROWSER_HPP` | macro | `client/include/UserInterface/Widgets/FileBrowser.hpp:2` | `#define HAVOC_FILEBROWSER_HPP` |
| `Path` | type_alias | `client/include/UserInterface/Widgets/FileBrowser.hpp:32` | `typedef struct _FileDirData { QString Path;` |
| `TableAddData` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:97` | `void TableAddData( FileData Data );` |
| `TableClear` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:98` | `void TableClear();` |
| `TreeAddChildToParent` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:94` | `void TreeAddChildToParent( QString ParentPath, FileBrowserTreeItem* DataItem );` |
| `TreeAddData` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:88` | `private: void TreeAddData( FileData Data );` |
| `TreeAddDisk` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:93` | `void TreeAddDisk( QString Disk );` |
| `TreeClear` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:90` | `void TreeClear( );` |
| `TreeUpdate` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:89` | `void TreeUpdate( );` |
| `_FileDirData` | struct | `client/include/UserInterface/Widgets/FileBrowser.hpp:33` | `` |
| `onButtonUp` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:119` | `void onButtonUp();` |
| `onInputPath` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:120` | `void onInputPath();` |
| `onTableContextMenu` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:108` | `void onTableContextMenu( const QPoint &pos );` |
| `onTableDoubleClick` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:107` | `void onTableDoubleClick( int row, int column );` |
| `onTableMenuDownload` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:118` | `void onTableMenuDownload();` |
| `onTableMenuMkdir` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:103` | `private slots: void onTableMenuMkdir();` |
| `onTableMenuReload` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:104` | `void onTableMenuReload();` |
| `onTableMenuRemove` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:105` | `void onTableMenuRemove();` |
| `onTreeContextMenu` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:116` | `void onTreeContextMenu( const QPoint &pos );` |
| `onTreeDoubleClick` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:115` | `void onTreeDoubleClick();` |
| `onTreeMenuListDrives` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:110` | `void onTreeMenuListDrives();` |
| `onTreeMenuMkdir` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:111` | `void onTreeMenuMkdir();` |
| `onTreeMenuReload` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:112` | `void onTreeMenuReload();` |
| `onTreeMenuRemove` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:113` | `void onTreeMenuRemove();` |
| `retranslateUi` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:83` | `void retranslateUi( );` |
| `setupUi` | function | `client/include/UserInterface/Widgets/FileBrowser.hpp:82` | `void setupUi( QWidget* FileBrowser );` |
| `ButtonsInit` | function | `client/include/UserInterface/Widgets/ListenerTable.hpp:26` | `void ButtonsInit();` |
| `ListenerAdd` | function | `client/include/UserInterface/Widgets/ListenerTable.hpp:31` | `void ListenerAdd( Util::ListenerItem item ) const;` |
| `ListenerEdit` | function | `client/include/UserInterface/Widgets/ListenerTable.hpp:32` | `void ListenerEdit( Util::ListenerItem item ) const;` |
| `ListenerError` | function | `client/include/UserInterface/Widgets/ListenerTable.hpp:34` | `void ListenerError( QString ListenerName, QString Error ) const;` |
| `ListenerRemove` | function | `client/include/UserInterface/Widgets/ListenerTable.hpp:33` | `void ListenerRemove( QString ListenerName ) const;` |
| `setDBManager` | function | `client/include/UserInterface/Widgets/ListenerTable.hpp:27` | `void setDBManager( HavocSpace::DBManager* dbManager );` |
| `setupUi` | function | `client/include/UserInterface/Widgets/ListenerTable.hpp:25` | `void setupUi( QWidget* widget );` |
| `AddDownload` | function | `client/include/UserInterface/Widgets/LootWidget.h:98` | `void AddDownload( const QString &DemonID, const QString &Name, const QString& Size, const QString &Date, const...` |
| `AddScreenshot` | function | `client/include/UserInterface/Widgets/LootWidget.h:97` | `void AddScreenshot( const QString& DemonID, const QString& Name, const QString& Date, const QByteArray& Data );` |
| `AddSessionSection` | function | `client/include/UserInterface/Widgets/LootWidget.h:96` | `void AddSessionSection( const QString& DemonID );` |
| `AddText` | function | `client/include/UserInterface/Widgets/LootWidget.h:99` | `void AddText( const QString& DemonID, const QString& Name, const QByteArray& Data );` |
| `DownloadTableAdd` | function | `client/include/UserInterface/Widgets/LootWidget.h:102` | `void DownloadTableAdd( const QString& Name, const QString& Size, const QString& Date );` |
| `File` | struct | `client/include/UserInterface/Widgets/LootWidget.h:47` | `` |
| `HAVOC_LOOTWIDGET_H` | macro | `client/include/UserInterface/Widgets/LootWidget.h:2` | `#define HAVOC_LOOTWIDGET_H` |
| `ImageLabel` | class | `client/include/UserInterface/Widgets/LootWidget.h:15` | `` |
| `LootWidget` | class | `client/include/UserInterface/Widgets/LootWidget.h:39` | `` |
| `Reload` | function | `client/include/UserInterface/Widgets/LootWidget.h:94` | `void Reload();` |
| `ScreenshotTableAdd` | function | `client/include/UserInterface/Widgets/LootWidget.h:101` | `void ScreenshotTableAdd( const QString& Name, const QString& Date );` |
| `keyReleaseEvent` | function | `client/include/UserInterface/Widgets/LootWidget.h:30` | `void keyReleaseEvent( QKeyEvent* event );` |
| `onAgentChange` | function | `client/include/UserInterface/Widgets/LootWidget.h:105` | `private Q_SLOTS: void onAgentChange( const QString& text );` |
| `onDownloadTableClick` | function | `client/include/UserInterface/Widgets/LootWidget.h:108` | `void onDownloadTableClick( const QModelIndex &index );` |
| `onScreenshotTableClick` | function | `client/include/UserInterface/Widgets/LootWidget.h:107` | `void onScreenshotTableClick( const QModelIndex &index );` |
| `onScreenshotTableCtx` | function | `client/include/UserInterface/Widgets/LootWidget.h:109` | `void onScreenshotTableCtx( const QPoint &pos );` |
| `onShowChange` | function | `client/include/UserInterface/Widgets/LootWidget.h:106` | `void onShowChange( const QString& text );` |
| `pixmap` | function | `client/include/UserInterface/Widgets/LootWidget.h:23` | `const QPixmap* pixmap() const;` |
| `resizeEvent` | function | `client/include/UserInterface/Widgets/LootWidget.h:29` | `protected: void resizeEvent(QResizeEvent *);` |
| `resizeImage` | function | `client/include/UserInterface/Widgets/LootWidget.h:35` | `public slots: void resizeImage();` |
| `setPixmap` | function | `client/include/UserInterface/Widgets/LootWidget.h:26` | `public slots: void setPixmap(const QPixmap&);` |
| `wheelEvent` | function | `client/include/UserInterface/Widgets/LootWidget.h:32` | `void wheelEvent(QWheelEvent *ev);` |
| `HAVOC_PROCESSLIST_HPP` | macro | `client/include/UserInterface/Widgets/ProcessList.hpp:2` | `#define HAVOC_PROCESSLIST_HPP` |
| `NewTableProcess` | function | `client/include/UserInterface/Widgets/ProcessList.hpp:45` | `void NewTableProcess(std::map<QString, QString> ProcessInfo);` |
| `NewTreeProcess` | function | `client/include/UserInterface/Widgets/ProcessList.hpp:46` | `void NewTreeProcess(std::map<QString, QString> ProcessInfo);` |
| `UpdateProcessListJson` | function | `client/include/UserInterface/Widgets/ProcessList.hpp:44` | `void UpdateProcessListJson(QJsonDocument ProcessListData);` |
| `handleTableListMenuContext` | function | `client/include/UserInterface/Widgets/ProcessList.hpp:54` | `void handleTableListMenuContext(const QPoint &pos);` |
| `handleTreeListMenuContext` | function | `client/include/UserInterface/Widgets/ProcessList.hpp:55` | `void handleTreeListMenuContext(const QPoint &pos);` |
| `onActionCopyPID` | function | `client/include/UserInterface/Widgets/ProcessList.hpp:57` | `void onActionCopyPID();` |
| `onActionSetParentProcess` | function | `client/include/UserInterface/Widgets/ProcessList.hpp:58` | `void onActionSetParentProcess();` |
| `onButton_Refresh` | function | `client/include/UserInterface/Widgets/ProcessList.hpp:49` | `private slots: void onButton_Refresh() const;` |
| `onTableChange` | function | `client/include/UserInterface/Widgets/ProcessList.hpp:51` | `void onTableChange();` |
| `onTreeChange` | function | `client/include/UserInterface/Widgets/ProcessList.hpp:52` | `void onTreeChange();` |
| `setupUi` | function | `client/include/UserInterface/Widgets/ProcessList.hpp:43` | `void setupUi(QWidget* Widget);` |
| `AppendFromInput` | function | `client/include/UserInterface/Widgets/PythonScript.hpp:29` | `private slots: void AppendFromInput();` |
| `AppendOutput` | function | `client/include/UserInterface/Widgets/PythonScript.hpp:26` | `void AppendOutput( QString output );` |
| `HAVOC_PYTHONSCRIPTWIDGET_HPP` | macro | `client/include/UserInterface/Widgets/PythonScript.hpp:3` | `#define HAVOC_PYTHONSCRIPTWIDGET_HPP` |
| `RunCode` | function | `client/include/UserInterface/Widgets/PythonScript.hpp:25` | `void RunCode(QString code);` |
| `setupUi` | function | `client/include/UserInterface/Widgets/PythonScript.hpp:24` | `void setupUi(QWidget *WindowWidget);` |
| `AddScript` | function | `client/include/UserInterface/Widgets/ScriptManager.h:23` | `static bool AddScript( QString Path );` |
| `AddScriptTable` | function | `client/include/UserInterface/Widgets/ScriptManager.h:24` | `void AddScriptTable( QString Path );` |
| `ReloadScript` | function | `client/include/UserInterface/Widgets/ScriptManager.h:30` | `void ReloadScript() const;` |
| `RemoveScript` | function | `client/include/UserInterface/Widgets/ScriptManager.h:31` | `void RemoveScript() const;` |
| `RetranslateUi` | function | `client/include/UserInterface/Widgets/ScriptManager.h:21` | `void RetranslateUi( void );` |
| `SCRIPTMANAGERVVJSUY_H` | macro | `client/include/UserInterface/Widgets/ScriptManager.h:2` | `#define SCRIPTMANAGERVVJSUY_H` |
| `SetupUi` | function | `client/include/UserInterface/Widgets/ScriptManager.h:20` | `void SetupUi( QWidget *Form );` |
| `b_LoadScript` | function | `client/include/UserInterface/Widgets/ScriptManager.h:27` | `private slots: void b_LoadScript();` |
| `menu_ScriptMenu` | function | `client/include/UserInterface/Widgets/ScriptManager.h:28` | `void menu_ScriptMenu( const QPoint &pos ) const;` |
| `Color` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:150` | `void Color( QColor color );` |
| `Edge` | class | `client/include/UserInterface/Widgets/SessionGraph.hpp:138` | `` |
| `GraphNodeAdd` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:95` | `Node* GraphNodeAdd( HavocNamespace::Util::SessionItem Session );` |
| `GraphNodeGet` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:97` | `Node* GraphNodeGet( QString AgentID );` |
| `GraphNodeRemove` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:96` | `void GraphNodeRemove( HavocNamespace::Util::SessionItem Session );` |
| `GraphPivotNodeAdd` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:99` | `void GraphPivotNodeAdd( QString AgentID, HavocNamespace::Util::SessionItem Session );` |
| `GraphPivotNodeDisconnect` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:100` | `void GraphPivotNodeDisconnect( QString AgentID );` |
| `GraphPivotNodeReconnect` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:101` | `void GraphPivotNodeReconnect( QString ParentAgentID, QString ChildAgentID );` |
| `GraphWidget` | class | `client/include/UserInterface/Widgets/SessionGraph.hpp:77` | `` |
| `HAVOC_SESSIONGRAPH_HPP` | macro | `client/include/UserInterface/Widgets/SessionGraph.hpp:2` | `#define HAVOC_SESSIONGRAPH_HPP` |
| `Member` | struct | `client/include/UserInterface/Widgets/SessionGraph.hpp:80` | `` |
| `Node` | class | `client/include/UserInterface/Widgets/SessionGraph.hpp:20` | `` |
| `NodeItemType` | enum | `client/include/UserInterface/Widgets/SessionGraph.hpp:14` | `` |
| `NodeItemType` | class | `client/include/UserInterface/Widgets/SessionGraph.hpp:14` | `` |
| `addEdge` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:48` | `void addEdge( Edge* edge );` |
| `adjust` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:149` | `void adjust();` |
| `advancePosition` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:55` | `bool advancePosition();` |
| `ancestor` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:133` | `Node* ancestor(Node* vim, Node* v, Node*& defaultAncestor);` |
| `appendChild` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:45` | `void appendChild( Node* child );` |
| `apportion` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:129` | `void apportion(Node* v, Node*& defaultAncestor);` |
| `calculateForces` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:54` | `void calculateForces();` |
| `destNode` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:147` | `Node* destNode() const;` |
| `edges` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:49` | `QVector<Edge*> edges() const;` |
| `executeShifts` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:134` | `void executeShifts(Node* v);` |
| `firstWalk` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:128` | `void firstWalk(Node* v);` |
| `initNode` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:126` | `void initNode(Node* v);` |
| `itemMoved` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:93` | `void itemMoved();` |
| `layout` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:127` | `void layout(Node* T);` |
| `moveSubtree` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:130` | `void moveSubtree(Node* wm, Node* wp, double shift);` |
| `nextLeft` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:131` | `Node* nextLeft(Node* v);` |
| `nextRight` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:132` | `Node* nextRight(Node* v);` |
| `removeChild` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:46` | `void removeChild( Node* child );` |
| `scaleView` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:118` | `void scaleView( qreal scaleFactor );` |
| `secondWalk` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:135` | `void secondWalk(Node* v, double m, double depth);` |
| `shuffle` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:104` | `public slots: void shuffle();` |
| `sourceNode` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:146` | `Node* sourceNode() const;` |
| `type` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:52` | `int type() const override` |
| `type` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:153` | `int type() const override` |
| `zoomIn` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:105` | `void zoomIn();` |
| `zoomOut` | function | `client/include/UserInterface/Widgets/SessionGraph.hpp:106` | `void zoomOut();` |
| `ChangeSessionValue` | function | `client/include/UserInterface/Widgets/SessionTable.hpp:30` | `void ChangeSessionValue( QString DemonID, int key, QString value );` |
| `HAVOC_SESSIONTABLE_HPP` | macro | `client/include/UserInterface/Widgets/SessionTable.hpp:2` | `#define HAVOC_SESSIONTABLE_HPP` |
| `NewSessionItem` | function | `client/include/UserInterface/Widgets/SessionTable.hpp:29` | `void NewSessionItem( Util::SessionItem item ) const;` |
| `setupUi` | function | `client/include/UserInterface/Widgets/SessionTable.hpp:28` | `void setupUi( QWidget* widget, QString TeamserverName );` |
| `updateRow` | function | `client/include/UserInterface/Widgets/SessionTable.hpp:31` | `void updateRow();` |
| `AddScript` | function | `client/include/UserInterface/Widgets/Store.hpp:65` | `bool AddScript( QString Path );` |
| `HAVOC_STORE_HPP` | macro | `client/include/UserInterface/Widgets/Store.hpp:2` | `#define HAVOC_STORE_HPP` |
| `Store` | class | `client/include/UserInterface/Widgets/Store.hpp:35` | `` |
| `displayData` | function | `client/include/UserInterface/Widgets/Store.hpp:63` | `void displayData( int position );` |
| `installScript` | function | `client/include/UserInterface/Widgets/Store.hpp:64` | `void installScript( int position );` |
| `retranslateUi` | function | `client/include/UserInterface/Widgets/Store.hpp:66` | `void retranslateUi( );` |
| `setupUi` | function | `client/include/UserInterface/Widgets/Store.hpp:62` | `void setupUi( QWidget* Store );` |
| `AddLoggerText` | function | `client/include/UserInterface/Widgets/Teamserver.hpp:26` | `void AddLoggerText( const QString& Text ) const;` |
| `HAVOC_TEAMSERVER_HPP` | macro | `client/include/UserInterface/Widgets/Teamserver.hpp:2` | `#define HAVOC_TEAMSERVER_HPP` |
| `Teamserver` | class | `client/include/UserInterface/Widgets/Teamserver.hpp:16` | `` |
| `retranslateUi` | function | `client/include/UserInterface/Widgets/Teamserver.hpp:24` | `void retranslateUi( );` |
| `setupUi` | function | `client/include/UserInterface/Widgets/Teamserver.hpp:23` | `void setupUi( QWidget* Teamserver );` |
| `HAVOC_TEAMSERVERTABSESSION_H` | macro | `client/include/UserInterface/Widgets/TeamserverTabSession.h:2` | `#define HAVOC_TEAMSERVERTABSESSION_H` |
| `NewBottomTab` | function | `client/include/UserInterface/Widgets/TeamserverTabSession.h:53` | `void NewBottomTab( QWidget* TabWidget, const std::string& TitleName, QString IconPath = "" ) const;` |
| `NewWidgetTab` | function | `client/include/UserInterface/Widgets/TeamserverTabSession.h:54` | `void NewWidgetTab( QWidget* TabWidget, const std::string& TitleName ) const;` |
| `SmallAppWidgets_t` | struct | `client/include/UserInterface/Widgets/TeamserverTabSession.h:19` | `` |
| `handleDemonContextMenu` | function | `client/include/UserInterface/Widgets/TeamserverTabSession.h:57` | `protected slots: void handleDemonContextMenu( const QPoint& pos );` |
| `removeTabSmall` | function | `client/include/UserInterface/Widgets/TeamserverTabSession.h:58` | `void removeTabSmall( int ) const;` |
| `setupUi` | function | `client/include/UserInterface/Widgets/TeamserverTabSession.h:52` | `void setupUi( QWidget* Page, QString TeamserverName );` |
| `HAVOC_BASE_HPP` | macro | `client/include/Util/Base.hpp:2` | `#define HAVOC_BASE_HPP` |
| `HAVOC_BASE64_H` | macro | `client/include/Util/Base64.h:2` | `#define HAVOC_BASE64_H` |
| `Background` | function | `client/include/Util/ColorText.h:37` | `static QString Background(const QString&);` |
| `Bold` | function | `client/include/Util/ColorText.h:60` | `static QString Bold(const QString& text);` |
| `Color` | function | `client/include/Util/ColorText.h:36` | `static QString Color(const QString& color, const QString& text);` |
| `Colors` | struct | `client/include/Util/ColorText.h:8` | `` |
| `Comment` | function | `client/include/Util/ColorText.h:39` | `static QString Comment(const QString&);` |
| `Cyan` | function | `client/include/Util/ColorText.h:40` | `static QString Cyan(const QString&);` |
| `Foreground` | function | `client/include/Util/ColorText.h:38` | `static QString Foreground(const QString&);` |
| `Green` | function | `client/include/Util/ColorText.h:41` | `static QString Green(const QString&);` |
| `HAVOC_COLORTEXT_H` | macro | `client/include/Util/ColorText.h:2` | `#define HAVOC_COLORTEXT_H` |
| `Hex` | struct | `client/include/Util/ColorText.h:9` | `` |
| `Orange` | function | `client/include/Util/ColorText.h:42` | `static QString Orange(const QString&);` |
| `Pink` | function | `client/include/Util/ColorText.h:43` | `static QString Pink(const QString&);` |
| `Purple` | function | `client/include/Util/ColorText.h:44` | `static QString Purple(const QString&);` |
| `Red` | function | `client/include/Util/ColorText.h:45` | `static QString Red(const QString&);` |
| `SetDraculaDark` | function | `client/include/Util/ColorText.h:33` | `static void SetDraculaDark();` |
| `SetDraculaLight` | function | `client/include/Util/ColorText.h:34` | `static void SetDraculaLight();` |
| `Underline` | function | `client/include/Util/ColorText.h:48` | `static QString Underline(const QString& text);` |

Next: [SYMBOLS_p2.md](SYMBOLS_p2.md)
