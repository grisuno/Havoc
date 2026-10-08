# Symbols

| Symbol | Kind | File:Line | Signature |
|--------|------|-----------|-----------|
| `HAVOC_EXTERNAL_H` | macro | `client/include/External.h:2` | `#define HAVOC_EXTERNAL_H` |
| `add` | function | `client/include/Havoc/CmdLine.hpp:176` | `void add(const T &v)` |
| `add` | function | `client/include/Havoc/CmdLine.hpp:318` | `void add(const std::string &name,
                 char short_name=0,
                 const std:...` |
| `add` | function | `client/include/Havoc/CmdLine.hpp:327` | `template <class T>
        void add(const std::string &name,
                 char short_name=0,
...` |
| `add` | function | `client/include/Havoc/CmdLine.hpp:336` | `void add(const std::string &name,
                 char short_name=0,
                 const std:...` |
| `argv` | function | `client/include/Havoc/CmdLine.hpp:416` | `std::vector<const char*> argv(argc);` |
| `cast` | function | `client/include/Havoc/CmdLine.hpp:47` | `public:
            static Target cast(const Source &arg)` |
| `cast` | function | `client/include/Havoc/CmdLine.hpp:60` | `public:
            static Target cast(const Source &arg)` |
| `cast` | function | `client/include/Havoc/CmdLine.hpp:68` | `public:
            static std::string cast(const Source &arg)` |
| `cast` | function | `client/include/Havoc/CmdLine.hpp:78` | `public:
            static Target cast(const std::string &arg)` |
| `check` | function | `client/include/Havoc/CmdLine.hpp:587` | `private:

        void check(int argc, bool ok)` |
| `cmdline_error` | function | `client/include/Havoc/CmdLine.hpp:136` | `public:
        cmdline_error(const std::string &msg): msg(msg)` |
| `default_reader` | struct | `client/include/Havoc/CmdLine.hpp:144` | `` |
| `default_value` | function | `client/include/Havoc/CmdLine.hpp:119` | `template <class T>
        std::string default_value(T def)` |
| `demangle` | function | `client/include/Havoc/CmdLine.hpp:103` | `static inline std::string demangle(const std::string &name)` |
| `description` | function | `client/include/Havoc/CmdLine.hpp:678` | `const std::string &description() const` |
| `description` | function | `client/include/Havoc/CmdLine.hpp:749` | `const std::string &description() const` |
| `error` | function | `client/include/Havoc/CmdLine.hpp:543` | `std::string error() const` |
| `error_full` | function | `client/include/Havoc/CmdLine.hpp:547` | `std::string error_full() const` |
| `exist` | function | `client/include/Havoc/CmdLine.hpp:355` | `bool exist(const std::string &name) const` |
| `footer` | function | `client/include/Havoc/CmdLine.hpp:347` | `void footer(const std::string &f)` |
| `full_description` | function | `client/include/Havoc/CmdLine.hpp:758` | `protected:
            std::string full_description(const std::string &desc)` |
| `get` | function | `client/include/Havoc/CmdLine.hpp:361` | `template <class T>
        const T &get(const std::string &name) const` |
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
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:182` | `template <class T>
    oneof_reader<T> oneof(T a1)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:190` | `template <class T>
    oneof_reader<T> oneof(T a1, T a2)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:199` | `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:209` | `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:220` | `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:232` | `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:245` | `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:259` | `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:274` | `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9)` |
| `oneof` | function | `client/include/Havoc/CmdLine.hpp:290` | `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9...` |
| `oneof_reader` | struct | `client/include/Havoc/CmdLine.hpp:169` | `` |
| `operator` | function | `client/include/Havoc/CmdLine.hpp:145` | `T operator()(const std::string &str)` |
| `operator` | function | `client/include/Havoc/CmdLine.hpp:153` | `T operator()(const std::string &s) const` |
| `operator` | function | `client/include/Havoc/CmdLine.hpp:170` | `T operator()(const std::string &s)` |
| `option_base` | class | `client/include/Havoc/CmdLine.hpp:621` | `` |
| `option_with_value` | class | `client/include/Havoc/CmdLine.hpp:694` | `` |
| `option_with_value` | function | `client/include/Havoc/CmdLine.hpp:696` | `public:
            option_with_value(const std::string &name,
                              char...` |
| `option_with_value_with_reader` | function | `client/include/Havoc/CmdLine.hpp:780` | `public:
            option_with_value_with_reader(const std::string &name,
                      ...` |
| `option_without_value` | class | `client/include/Havoc/CmdLine.hpp:638` | `` |
| `option_without_value` | function | `client/include/Havoc/CmdLine.hpp:640` | `public:
            option_without_value(const std::string &name,
                               ...` |
| `parse` | function | `client/include/Havoc/CmdLine.hpp:372` | `bool parse(const std::string &arg)` |
| `parse` | function | `client/include/Havoc/CmdLine.hpp:414` | `bool parse(const std::vector<std::string> &args)` |
| `parse` | function | `client/include/Havoc/CmdLine.hpp:424` | `bool parse(int argc, const char * const argv[])` |
| `parse_check` | function | `client/include/Havoc/CmdLine.hpp:525` | `void parse_check(const std::string &arg)` |
| `parse_check` | function | `client/include/Havoc/CmdLine.hpp:531` | `void parse_check(const std::vector<std::string> &args)` |
| `parse_check` | function | `client/include/Havoc/CmdLine.hpp:537` | `void parse_check(int argc, char *argv[])` |
| `parser` | class | `client/include/Havoc/CmdLine.hpp:308` | `` |
| `parser` | function | `client/include/Havoc/CmdLine.hpp:310` | `public:
        parser()` |
| `range` | function | `client/include/Havoc/CmdLine.hpp:163` | `template <class T>
    range_reader<T> range(const T &low, const T &high)` |
| `range_reader` | struct | `client/include/Havoc/CmdLine.hpp:151` | `` |
| `range_reader` | function | `client/include/Havoc/CmdLine.hpp:152` | `range_reader(const T &low, const T &high): low(low), high(high)` |
| `read` | function | `client/include/Havoc/CmdLine.hpp:790` | `private:
            T read(const std::string &s)` |
| `readable_typename` | function | `client/include/Havoc/CmdLine.hpp:113` | `template <class T>
        std::string readable_typename()` |
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
| `AddDownload` | function | `client/include/UserInterface/Widgets/LootWidget.h:98` | `void AddDownload( const QString &DemonID, const QString &Name, const QString& Size, const QString &Date, const QByteArra` |
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
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:667` | `CONSOLE_ERROR( "Not enough arguments" )
                }
            }
            else if ( Inp...` |
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:681` | `CONSOLE_ERROR( "Not enough arguments" )
                }
            }
            else if ( Inp...` |
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:700` | `CONSOLE_ERROR( "Sub command not found: " + InputCommands[ 1 ] )
            }
        }
        e...` |
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1225` | `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...` |
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1260` | `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...` |
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1830` | `CONSOLE_ERROR( "Not enough arguments" )
            }
        }
        else if ( InputCommands[ ...` |
| `CONSOLE_ERROR` | function | `client/src/Havoc/Demon/ConsoleInput.cc:2131` | `CONSOLE_ERROR( "No sub command specified" )
            }
        }
        else if ( InputComman...` |
| `DemonCommands` | function | `client/src/Havoc/Demon/ConsoleInput.cc:188` | `DemonCommands::DemonCommands( )` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:611` | `SEND( Execute.Checkin( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "task" ...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:654` | `SEND( Execute.Job( TaskID, "list", "0" ) )
            }
            else if ( InputCommands[ 1 ]...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1138` | `SEND( Execute.DllInject( TaskID, Pid, Path, Args ) )
            }
            else if ( InputCom...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1166` | `SEND( Execute.DllSpawn( TaskID, Path, Args.toLocal8Bit() ) )

            }
        }
        els...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1452` | `SEND( Execute.Token( TaskID, "clear", "" ) )
            }
            else if ( InputCommands[ 1...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1459` | `SEND( Execute.Token( TaskID, "getuid", "" ) )
            }
            else if ( InputCommands[ ...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1607` | `SEND( Execute.Socket( TaskID, "rportfwd list", "" ) )
            }
            else if ( InputCo...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1620` | `SEND( Execute.Socket( TaskID, "rportfwd remove", InputCommands[ 2 ] ) )
            }
           ...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1627` | `SEND( Execute.Socket( TaskID, "rportfwd clear", "" ) )
            }

        }
        else if (...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1654` | `SEND( Execute.Socket( TaskID, "socks add", Port ) )
            }
            else if ( InputComm...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1661` | `SEND( Execute.Socket( TaskID, "socks list", "" ) )
            }
            else if ( InputComma...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1674` | `SEND( Execute.Socket( TaskID, "socks kill", InputCommands[ 2 ] ) )
            }
            else...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1681` | `SEND( Execute.Socket( TaskID, "socks clear", "" ) )
            }

        }
        else if ( In...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1698` | `SEND( Execute.Transfer( TaskID, "list", "" ) )
            }
            else if ( InputCommands[...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1711` | `SEND( Execute.Transfer( TaskID, "stop", InputCommands[ 2 ] ) )
            }
            else if ...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1724` | `SEND( Execute.Transfer( TaskID, "resume", InputCommands[ 2 ] ) )
            }
            else i...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:1737` | `SEND( Execute.Transfer( TaskID, "remove", InputCommands[ 2 ] ) )
            }
        }
        ...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:2037` | `SEND( Execute.Screenshot( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "net...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:2184` | `SEND( Execute.Pivot( TaskID, Command, Param ) )
            }
        }
        else if ( InputCo...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:2192` | `SEND( Execute.Luid( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "klist" ) ...` |
| `SEND` | function | `client/src/Havoc/Demon/ConsoleInput.cc:2324` | `SEND( Execute.Exit( TaskID, "thread" ) )
            }
            else if ( InputCommands[ 1 ].c...` |
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
| `Edge` | function | `client/src/UserInterface/Widgets/SessionGraph.cc:508` | `Edge::Edge( Node* sourceNode, Node* destNode, QColor Color )
    : source( sourceNode ), dest( de...` |
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
| `Underline` | function | `client/src/Util/ColorText.cpp:95` | `QString HavocNamespace::Util::ColorText::Underline(const QString &text)` |
| `UnderlineBackground` | function | `client/src/Util/ColorText.cpp:99` | `QString HavocNamespace::Util::ColorText::UnderlineBackground(const QString &text)` |
| `UnderlineComment` | function | `client/src/Util/ColorText.cpp:107` | `QString HavocNamespace::Util::ColorText::UnderlineComment(const QString &text)` |
| `UnderlineCyan` | function | `client/src/Util/ColorText.cpp:111` | `QString HavocNamespace::Util::ColorText::UnderlineCyan(const QString &text)` |
| `UnderlineForeground` | function | `client/src/Util/ColorText.cpp:103` | `QString HavocNamespace::Util::ColorText::UnderlineForeground(const QString &text)` |
| `UnderlineGreen` | function | `client/src/Util/ColorText.cpp:115` | `QString HavocNamespace::Util::ColorText::UnderlineGreen(const QString &text)` |
| `UnderlineOrange` | function | `client/src/Util/ColorText.cpp:119` | `QString HavocNamespace::Util::ColorText::UnderlineOrange(const QString &text)` |
| `UnderlinePink` | function | `client/src/Util/ColorText.cpp:123` | `QString HavocNamespace::Util::ColorText::UnderlinePink(const QString &text)` |
| `UnderlinePurple` | function | `client/src/Util/ColorText.cpp:127` | `QString HavocNamespace::Util::ColorText::UnderlinePurple(const QString &text)` |
| `UnderlineRed` | function | `client/src/Util/ColorText.cpp:131` | `QString HavocNamespace::Util::ColorText::UnderlineRed(const QString &text)` |
| `UnderlineYellow` | function | `client/src/Util/ColorText.cpp:135` | `QString HavocNamespace::Util::ColorText::UnderlineYellow(const QString &text)` |
| `Yellow` | function | `client/src/Util/ColorText.cpp:87` | `QString HavocNamespace::Util::ColorText::Yellow(const QString& text)` |
| `Export` | function | `client/src/global.cc:42` | `void Util::SessionItem::Export()` |
| `gen_random` | function | `client/src/global.cc:31` | `std::string Util::gen_random( const int len )` |
| `DEMON_DEMON_H` | macro | `payloads/Demon/include/Demon.h:2` | `#define DEMON_DEMON_H` |
| `Instance` | variable | `payloads/Demon/include/Demon.h:559` | `extern PINSTANCE Instance;` |
| `Session` | struct | `payloads/Demon/include/Demon.h:48` | `` |
| `_CONFIG` | struct | `payloads/Demon/include/Demon.h:121` | `` |
| `DEMON_CLR_H` | macro | `payloads/Demon/include/common/Clr.h:2` | `#define DEMON_CLR_H` |
| `DEMOn_CLR_ERROR_REFUSE_VERSION` | macro | `payloads/Demon/include/common/Clr.h:709` | `#define DEMOn_CLR_ERROR_REFUSE_VERSION` |
| `DUMMY_METHOD` | macro | `payloads/Demon/include/common/Clr.h:53` | `#define DUMMY_METHOD(x)` |
| `DUMMY_METHOD` | macro | `payloads/Demon/include/common/Clr.h:88` | `#define DUMMY_METHOD(x)` |
| `DUMMY_METHOD` | macro | `payloads/Demon/include/common/Clr.h:186` | `#define DUMMY_METHOD(x)` |
| `DUMMY_METHOD` | macro | `payloads/Demon/include/common/Clr.h:291` | `#define DUMMY_METHOD(x)` |
| `DUMMY_METHOD` | macro | `payloads/Demon/include/common/Clr.h:586` | `#define DUMMY_METHOD(x)` |
| `HDOMAINENUM` | type_alias | `payloads/Demon/include/common/Clr.h:29` | `typedef void* HDOMAINENUM;` |
| `IAppDomain` | type_alias | `payloads/Demon/include/common/Clr.h:17` | `typedef struct _AppDomain IAppDomain;` |
| `IAssembly` | type_alias | `payloads/Demon/include/common/Clr.h:18` | `typedef struct _Assembly IAssembly;` |
| `IBinder` | type_alias | `payloads/Demon/include/common/Clr.h:20` | `typedef struct _Binder IBinder;` |
| `ICLRMetaHost` | type_alias | `payloads/Demon/include/common/Clr.h:14` | `typedef struct _ICLRMetaHost ICLRMetaHost;` |
| `ICLRMetaHostVtbl` | struct | `payloads/Demon/include/common/Clr.h:525` | `` |
| `ICLRRuntimeInfo` | type_alias | `payloads/Demon/include/common/Clr.h:16` | `typedef struct _ICLRRuntimeInfo ICLRRuntimeInfo;` |
| `ICLRRuntimeInfoVtbl` | struct | `payloads/Demon/include/common/Clr.h:433` | `` |
| `IMethodInfo` | type_alias | `payloads/Demon/include/common/Clr.h:21` | `typedef struct _MethodInfo IMethodInfo;` |
| `IType` | type_alias | `payloads/Demon/include/common/Clr.h:19` | `typedef struct _Type IType;` |
| `RequestID` | type_alias | `payloads/Demon/include/common/Clr.h:659` | `typedef struct _DOTNET_ARGS { /* The random task id associated with the requested DOTNET exec */ UINT32 RequestID;` |
| `_AppDomain` | struct | `payloads/Demon/include/common/Clr.h:181` | `` |
| `_AppDomainVtbl` | struct | `payloads/Demon/include/common/Clr.h:90` | `` |
| `_Assembly` | struct | `payloads/Demon/include/common/Clr.h:286` | `` |
| `_AssemblyVtbl` | struct | `payloads/Demon/include/common/Clr.h:188` | `` |
| `_Binder` | struct | `payloads/Demon/include/common/Clr.h:83` | `` |
| `_BinderVtbl` | struct | `payloads/Demon/include/common/Clr.h:55` | `` |
| `_BindingFlags` | enum | `payloads/Demon/include/common/Clr.h:263` | `` |
| `_DOTNET_ARGS` | struct | `payloads/Demon/include/common/Clr.h:660` | `` |
| `_ICLRMetaHost` | struct | `payloads/Demon/include/common/Clr.h:579` | `` |
| `_ICLRRuntimeInfo` | struct | `payloads/Demon/include/common/Clr.h:517` | `` |
| `_MethodInfo` | struct | `payloads/Demon/include/common/Clr.h:656` | `` |
| `_MethodInfoVtbl` | struct | `payloads/Demon/include/common/Clr.h:588` | `` |
| `_Type` | struct | `payloads/Demon/include/common/Clr.h:521` | `` |
| `_TypeVtbl` | struct | `payloads/Demon/include/common/Clr.h:293` | `` |
| `lpVtbl` | type_alias | `payloads/Demon/include/common/Clr.h:82` | `typedef struct _Binder { BinderVtbl* lpVtbl;` |
| `lpVtbl` | type_alias | `payloads/Demon/include/common/Clr.h:180` | `typedef struct _AppDomain { AppDomainVtbl* lpVtbl;` |
| `lpVtbl` | type_alias | `payloads/Demon/include/common/Clr.h:285` | `typedef struct _Assembly { AssemblyVtbl* lpVtbl;` |
| `lpVtbl` | type_alias | `payloads/Demon/include/common/Clr.h:516` | `typedef struct _ICLRRuntimeInfo { ICLRRuntimeInfoVtbl* lpVtbl;` |
| `lpVtbl` | type_alias | `payloads/Demon/include/common/Clr.h:520` | `typedef struct _Type { TypeVtbl* lpVtbl;` |
| `lpVtbl` | type_alias | `payloads/Demon/include/common/Clr.h:578` | `typedef struct _ICLRMetaHost { ICLRMetaHostVtbl* lpVtbl;` |
| `lpVtbl` | type_alias | `payloads/Demon/include/common/Clr.h:655` | `typedef struct _MethodInfo { MethodInfoVtbl* lpVtbl;` |
| `xCLSID_CLRMetaHost` | variable | `payloads/Demon/include/common/Clr.h:8` | `extern GUID xCLSID_CLRMetaHost;` |
| `xCLSID_CorRuntimeHost` | variable | `payloads/Demon/include/common/Clr.h:11` | `extern GUID xCLSID_CorRuntimeHost;` |
| `xIID_AppDomain` | variable | `payloads/Demon/include/common/Clr.h:13` | `extern GUID xIID_AppDomain;` |
| `xIID_ICLRMetaHost` | variable | `payloads/Demon/include/common/Clr.h:9` | `extern GUID xIID_ICLRMetaHost;` |
| `xIID_ICLRRuntimeInfo` | variable | `payloads/Demon/include/common/Clr.h:10` | `extern GUID xIID_ICLRRuntimeInfo;` |
| `xIID_ICorRuntimeHost` | variable | `payloads/Demon/include/common/Clr.h:12` | `extern GUID xIID_ICorRuntimeHost;` |
| `AMSIETW_PATCH_HWBP` | macro | `payloads/Demon/include/common/Defines.h:40` | `#define AMSIETW_PATCH_HWBP` |
| `AMSIETW_PATCH_MEMORY` | macro | `payloads/Demon/include/common/Defines.h:41` | `#define AMSIETW_PATCH_MEMORY` |
| `AMSIETW_PATCH_NONE` | macro | `payloads/Demon/include/common/Defines.h:39` | `#define AMSIETW_PATCH_NONE` |
| `DEMON_MAGIC_VALUE` | macro | `payloads/Demon/include/common/Defines.h:15` | `#define DEMON_MAGIC_VALUE` |
| `DEMON_STRINGS_H` | macro | `payloads/Demon/include/common/Defines.h:2` | `#define DEMON_STRINGS_H` |
| `H_COFFAPI_BEACONADDVALUE` | macro | `payloads/Demon/include/common/Defines.h:317` | `#define H_COFFAPI_BEACONADDVALUE` |
| `H_COFFAPI_BEACONCLEANUPPROCESS` | macro | `payloads/Demon/include/common/Defines.h:315` | `#define H_COFFAPI_BEACONCLEANUPPROCESS` |
| `H_COFFAPI_BEACONDATAEXTRACT` | macro | `payloads/Demon/include/common/Defines.h:296` | `#define H_COFFAPI_BEACONDATAEXTRACT` |
| `H_COFFAPI_BEACONDATAINT` | macro | `payloads/Demon/include/common/Defines.h:293` | `#define H_COFFAPI_BEACONDATAINT` |
| `H_COFFAPI_BEACONDATALENGTH` | macro | `payloads/Demon/include/common/Defines.h:295` | `#define H_COFFAPI_BEACONDATALENGTH` |
| `H_COFFAPI_BEACONDATAPARSER` | macro | `payloads/Demon/include/common/Defines.h:292` | `#define H_COFFAPI_BEACONDATAPARSER` |
| `H_COFFAPI_BEACONDATASHORT` | macro | `payloads/Demon/include/common/Defines.h:294` | `#define H_COFFAPI_BEACONDATASHORT` |
| `H_COFFAPI_BEACONDATASTOREGETITEM` | macro | `payloads/Demon/include/common/Defines.h:320` | `#define H_COFFAPI_BEACONDATASTOREGETITEM` |
| `H_COFFAPI_BEACONDATASTOREMAXENTRIES` | macro | `payloads/Demon/include/common/Defines.h:323` | `#define H_COFFAPI_BEACONDATASTOREMAXENTRIES` |
| `H_COFFAPI_BEACONDATASTOREPROTECTITEM` | macro | `payloads/Demon/include/common/Defines.h:321` | `#define H_COFFAPI_BEACONDATASTOREPROTECTITEM` |
| `H_COFFAPI_BEACONDATASTOREUNPROTECTITEM` | macro | `payloads/Demon/include/common/Defines.h:322` | `#define H_COFFAPI_BEACONDATASTOREUNPROTECTITEM` |
| `H_COFFAPI_BEACONFORMATALLOC` | macro | `payloads/Demon/include/common/Defines.h:298` | `#define H_COFFAPI_BEACONFORMATALLOC` |
| `H_COFFAPI_BEACONFORMATAPPEND` | macro | `payloads/Demon/include/common/Defines.h:301` | `#define H_COFFAPI_BEACONFORMATAPPEND` |
| `H_COFFAPI_BEACONFORMATFREE` | macro | `payloads/Demon/include/common/Defines.h:300` | `#define H_COFFAPI_BEACONFORMATFREE` |
| `H_COFFAPI_BEACONFORMATINT` | macro | `payloads/Demon/include/common/Defines.h:304` | `#define H_COFFAPI_BEACONFORMATINT` |
| `H_COFFAPI_BEACONFORMATPRINTF` | macro | `payloads/Demon/include/common/Defines.h:302` | `#define H_COFFAPI_BEACONFORMATPRINTF` |
| `H_COFFAPI_BEACONFORMATRESET` | macro | `payloads/Demon/include/common/Defines.h:299` | `#define H_COFFAPI_BEACONFORMATRESET` |
| `H_COFFAPI_BEACONFORMATTOSTRING` | macro | `payloads/Demon/include/common/Defines.h:303` | `#define H_COFFAPI_BEACONFORMATTOSTRING` |
| `H_COFFAPI_BEACONGETCUSTOMUSERDATA` | macro | `payloads/Demon/include/common/Defines.h:324` | `#define H_COFFAPI_BEACONGETCUSTOMUSERDATA` |
| `H_COFFAPI_BEACONGETSPAWNTO` | macro | `payloads/Demon/include/common/Defines.h:311` | `#define H_COFFAPI_BEACONGETSPAWNTO` |
| `H_COFFAPI_BEACONGETVALUE` | macro | `payloads/Demon/include/common/Defines.h:318` | `#define H_COFFAPI_BEACONGETVALUE` |
| `H_COFFAPI_BEACONINFORMATION` | macro | `payloads/Demon/include/common/Defines.h:316` | `#define H_COFFAPI_BEACONINFORMATION` |
| `H_COFFAPI_BEACONINJECTPROCESS` | macro | `payloads/Demon/include/common/Defines.h:313` | `#define H_COFFAPI_BEACONINJECTPROCESS` |
| `H_COFFAPI_BEACONINJECTTEMPORARYPROCESS` | macro | `payloads/Demon/include/common/Defines.h:314` | `#define H_COFFAPI_BEACONINJECTTEMPORARYPROCESS` |
| `H_COFFAPI_BEACONISADMIN` | macro | `payloads/Demon/include/common/Defines.h:310` | `#define H_COFFAPI_BEACONISADMIN` |
| `H_COFFAPI_BEACONOUTPUT` | macro | `payloads/Demon/include/common/Defines.h:307` | `#define H_COFFAPI_BEACONOUTPUT` |
| `H_COFFAPI_BEACONPRINTF` | macro | `payloads/Demon/include/common/Defines.h:306` | `#define H_COFFAPI_BEACONPRINTF` |
| `H_COFFAPI_BEACONREMOVEVALUE` | macro | `payloads/Demon/include/common/Defines.h:319` | `#define H_COFFAPI_BEACONREMOVEVALUE` |
| `H_COFFAPI_BEACONREVERTTOKEN` | macro | `payloads/Demon/include/common/Defines.h:309` | `#define H_COFFAPI_BEACONREVERTTOKEN` |
| `H_COFFAPI_BEACONSPAWNTEMPORARYPROCESS` | macro | `payloads/Demon/include/common/Defines.h:312` | `#define H_COFFAPI_BEACONSPAWNTEMPORARYPROCESS` |
| `H_COFFAPI_BEACONUSETOKEN` | macro | `payloads/Demon/include/common/Defines.h:308` | `#define H_COFFAPI_BEACONUSETOKEN` |
| `H_COFFAPI_FREELIBRARY` | macro | `payloads/Demon/include/common/Defines.h:330` | `#define H_COFFAPI_FREELIBRARY` |
| `H_COFFAPI_GETMODULEHANDLE` | macro | `payloads/Demon/include/common/Defines.h:329` | `#define H_COFFAPI_GETMODULEHANDLE` |
| `H_COFFAPI_GETPROCADDRESS` | macro | `payloads/Demon/include/common/Defines.h:328` | `#define H_COFFAPI_GETPROCADDRESS` |
| `H_COFFAPI_LOADLIBRARYA` | macro | `payloads/Demon/include/common/Defines.h:327` | `#define H_COFFAPI_LOADLIBRARYA` |
| `H_COFFAPI_LOCALFREE` | macro | `payloads/Demon/include/common/Defines.h:331` | `#define H_COFFAPI_LOCALFREE` |
| `H_COFFAPI_NTALERTRESUMETHREAD` | macro | `payloads/Demon/include/common/Defines.h:357` | `#define H_COFFAPI_NTALERTRESUMETHREAD` |
| `H_COFFAPI_NTALLOCATEVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:350` | `#define H_COFFAPI_NTALLOCATEVIRTUALMEMORY` |
| `H_COFFAPI_NTCLOSE` | macro | `payloads/Demon/include/common/Defines.h:363` | `#define H_COFFAPI_NTCLOSE` |
| `H_COFFAPI_NTCREATEEVENT` | macro | `payloads/Demon/include/common/Defines.h:342` | `#define H_COFFAPI_NTCREATEEVENT` |
| `H_COFFAPI_NTCREATETHREADEX` | macro | `payloads/Demon/include/common/Defines.h:343` | `#define H_COFFAPI_NTCREATETHREADEX` |
| `H_COFFAPI_NTDUPLICATEOBJECT` | macro | `payloads/Demon/include/common/Defines.h:344` | `#define H_COFFAPI_NTDUPLICATEOBJECT` |
| `H_COFFAPI_NTDUPLICATETOKEN` | macro | `payloads/Demon/include/common/Defines.h:338` | `#define H_COFFAPI_NTDUPLICATETOKEN` |
| `H_COFFAPI_NTFREEVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:352` | `#define H_COFFAPI_NTFREEVIRTUALMEMORY` |
| `H_COFFAPI_NTGETCONTEXTTHREAD` | macro | `payloads/Demon/include/common/Defines.h:345` | `#define H_COFFAPI_NTGETCONTEXTTHREAD` |
| `H_COFFAPI_NTGETNEXTTHREAD` | macro | `payloads/Demon/include/common/Defines.h:366` | `#define H_COFFAPI_NTGETNEXTTHREAD` |
| `H_COFFAPI_NTOPENPROCESS` | macro | `payloads/Demon/include/common/Defines.h:334` | `#define H_COFFAPI_NTOPENPROCESS` |
| `H_COFFAPI_NTOPENPROCESSTOKEN` | macro | `payloads/Demon/include/common/Defines.h:337` | `#define H_COFFAPI_NTOPENPROCESSTOKEN` |
| `H_COFFAPI_NTOPENTHREAD` | macro | `payloads/Demon/include/common/Defines.h:333` | `#define H_COFFAPI_NTOPENTHREAD` |
| `H_COFFAPI_NTOPENTHREADTOKEN` | macro | `payloads/Demon/include/common/Defines.h:336` | `#define H_COFFAPI_NTOPENTHREADTOKEN` |
| `H_COFFAPI_NTPROTECTVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:354` | `#define H_COFFAPI_NTPROTECTVIRTUALMEMORY` |
| `H_COFFAPI_NTQUERYINFORMATIONPROCESS` | macro | `payloads/Demon/include/common/Defines.h:347` | `#define H_COFFAPI_NTQUERYINFORMATIONPROCESS` |
| `H_COFFAPI_NTQUERYINFORMATIONTHREAD` | macro | `payloads/Demon/include/common/Defines.h:361` | `#define H_COFFAPI_NTQUERYINFORMATIONTHREAD` |
| `H_COFFAPI_NTQUERYINFORMATIONTOKEN` | macro | `payloads/Demon/include/common/Defines.h:360` | `#define H_COFFAPI_NTQUERYINFORMATIONTOKEN` |
| `H_COFFAPI_NTQUERYOBJECT` | macro | `payloads/Demon/include/common/Defines.h:362` | `#define H_COFFAPI_NTQUERYOBJECT` |
| `H_COFFAPI_NTQUERYSYSTEMINFORMATION` | macro | `payloads/Demon/include/common/Defines.h:348` | `#define H_COFFAPI_NTQUERYSYSTEMINFORMATION` |
| `H_COFFAPI_NTQUERYVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:359` | `#define H_COFFAPI_NTQUERYVIRTUALMEMORY` |
| `H_COFFAPI_NTQUEUEAPCTHREAD` | macro | `payloads/Demon/include/common/Defines.h:339` | `#define H_COFFAPI_NTQUEUEAPCTHREAD` |
| `H_COFFAPI_NTREADVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:355` | `#define H_COFFAPI_NTREADVIRTUALMEMORY` |
| `H_COFFAPI_NTRESUMETHREAD` | macro | `payloads/Demon/include/common/Defines.h:341` | `#define H_COFFAPI_NTRESUMETHREAD` |
| `H_COFFAPI_NTSETCONTEXTTHREAD` | macro | `payloads/Demon/include/common/Defines.h:346` | `#define H_COFFAPI_NTSETCONTEXTTHREAD` |
| `H_COFFAPI_NTSETINFORMATIONTHREAD` | macro | `payloads/Demon/include/common/Defines.h:364` | `#define H_COFFAPI_NTSETINFORMATIONTHREAD` |
| `H_COFFAPI_NTSETINFORMATIONVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:365` | `#define H_COFFAPI_NTSETINFORMATIONVIRTUALMEMORY` |
| `H_COFFAPI_NTSIGNALANDWAITFORSINGLEOBJECT` | macro | `payloads/Demon/include/common/Defines.h:358` | `#define H_COFFAPI_NTSIGNALANDWAITFORSINGLEOBJECT` |
| `H_COFFAPI_NTSUSPENDTHREAD` | macro | `payloads/Demon/include/common/Defines.h:340` | `#define H_COFFAPI_NTSUSPENDTHREAD` |
| `H_COFFAPI_NTTERMINATEPROCESS` | macro | `payloads/Demon/include/common/Defines.h:335` | `#define H_COFFAPI_NTTERMINATEPROCESS` |
| `H_COFFAPI_NTTERMINATETHREAD` | macro | `payloads/Demon/include/common/Defines.h:356` | `#define H_COFFAPI_NTTERMINATETHREAD` |
| `H_COFFAPI_NTUNMAPVIEWOFSECTION` | macro | `payloads/Demon/include/common/Defines.h:353` | `#define H_COFFAPI_NTUNMAPVIEWOFSECTION` |
| `H_COFFAPI_NTWAITFORSINGLEOBJECT` | macro | `payloads/Demon/include/common/Defines.h:349` | `#define H_COFFAPI_NTWAITFORSINGLEOBJECT` |
| `H_COFFAPI_NTWRITEVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:351` | `#define H_COFFAPI_NTWRITEVIRTUALMEMORY` |
| `H_COFFAPI_TOWIDECHAR` | macro | `payloads/Demon/include/common/Defines.h:326` | `#define H_COFFAPI_TOWIDECHAR` |
| `H_FUNC_ACCEPT` | macro | `payloads/Demon/include/common/Defines.h:269` | `#define H_FUNC_ACCEPT` |
| `H_FUNC_ADDMANDATORYACE` | macro | `payloads/Demon/include/common/Defines.h:220` | `#define H_FUNC_ADDMANDATORYACE` |
| `H_FUNC_ADJUSTTOKENPRIVILEGES` | macro | `payloads/Demon/include/common/Defines.h:213` | `#define H_FUNC_ADJUSTTOKENPRIVILEGES` |
| `H_FUNC_ALLOCATEANDINITIALIZESID` | macro | `payloads/Demon/include/common/Defines.h:222` | `#define H_FUNC_ALLOCATEANDINITIALIZESID` |
| `H_FUNC_ALLOCCONSOLE` | macro | `payloads/Demon/include/common/Defines.h:169` | `#define H_FUNC_ALLOCCONSOLE` |
| `H_FUNC_AMSISCANBUFFER` | macro | `payloads/Demon/include/common/Defines.h:286` | `#define H_FUNC_AMSISCANBUFFER` |
| `H_FUNC_ATTACHCONSOLE` | macro | `payloads/Demon/include/common/Defines.h:199` | `#define H_FUNC_ATTACHCONSOLE` |
| `H_FUNC_BIND` | macro | `payloads/Demon/include/common/Defines.h:267` | `#define H_FUNC_BIND` |
| `H_FUNC_BITBLT` | macro | `payloads/Demon/include/common/Defines.h:249` | `#define H_FUNC_BITBLT` |
| `H_FUNC_CHECKTOKENMEMBERSHIP` | macro | `payloads/Demon/include/common/Defines.h:223` | `#define H_FUNC_CHECKTOKENMEMBERSHIP` |
| `H_FUNC_CLOSESOCKET` | macro | `payloads/Demon/include/common/Defines.h:270` | `#define H_FUNC_CLOSESOCKET` |
| `H_FUNC_CLRCREATEINSTANCE` | macro | `payloads/Demon/include/common/Defines.h:253` | `#define H_FUNC_CLRCREATEINSTANCE` |
| `H_FUNC_COMMANDLINETOARGVW` | macro | `payloads/Demon/include/common/Defines.h:239` | `#define H_FUNC_COMMANDLINETOARGVW` |
| `H_FUNC_CONNECT` | macro | `payloads/Demon/include/common/Defines.h:273` | `#define H_FUNC_CONNECT` |
| `H_FUNC_CONNECTNAMEDPIPE` | macro | `payloads/Demon/include/common/Defines.h:178` | `#define H_FUNC_CONNECTNAMEDPIPE` |
| `H_FUNC_CONVERTFIBERTOTHREAD` | macro | `payloads/Demon/include/common/Defines.h:157` | `#define H_FUNC_CONVERTFIBERTOTHREAD` |
| `H_FUNC_CONVERTSIDTOSTRINGSIDW` | macro | `payloads/Demon/include/common/Defines.h:228` | `#define H_FUNC_CONVERTSIDTOSTRINGSIDW` |
| `H_FUNC_CONVERTTHREADTOFIBEREX` | macro | `payloads/Demon/include/common/Defines.h:166` | `#define H_FUNC_CONVERTTHREADTOFIBEREX` |
| `H_FUNC_COPYFILEW` | macro | `payloads/Demon/include/common/Defines.h:190` | `#define H_FUNC_COPYFILEW` |
| `H_FUNC_CREATECOMPATIBLEDC` | macro | `payloads/Demon/include/common/Defines.h:246` | `#define H_FUNC_CREATECOMPATIBLEDC` |
| `H_FUNC_CREATEDIBSECTION` | macro | `payloads/Demon/include/common/Defines.h:247` | `#define H_FUNC_CREATEDIBSECTION` |
| `H_FUNC_CREATEDIRECTORYW` | macro | `payloads/Demon/include/common/Defines.h:189` | `#define H_FUNC_CREATEDIRECTORYW` |
| `H_FUNC_CREATEFIBEREX` | macro | `payloads/Demon/include/common/Defines.h:158` | `#define H_FUNC_CREATEFIBEREX` |
| `H_FUNC_CREATEFILEW` | macro | `payloads/Demon/include/common/Defines.h:152` | `#define H_FUNC_CREATEFILEW` |
| `H_FUNC_CREATENAMEDPIPEW` | macro | `payloads/Demon/include/common/Defines.h:156` | `#define H_FUNC_CREATENAMEDPIPEW` |
| `H_FUNC_CREATEPIPE` | macro | `payloads/Demon/include/common/Defines.h:150` | `#define H_FUNC_CREATEPIPE` |
| `H_FUNC_CREATEPROCESSW` | macro | `payloads/Demon/include/common/Defines.h:151` | `#define H_FUNC_CREATEPROCESSW` |
| `H_FUNC_CREATEPROCESSWITHLOGONW` | macro | `payloads/Demon/include/common/Defines.h:205` | `#define H_FUNC_CREATEPROCESSWITHLOGONW` |
| `H_FUNC_CREATEPROCESSWITHTOKENW` | macro | `payloads/Demon/include/common/Defines.h:204` | `#define H_FUNC_CREATEPROCESSWITHTOKENW` |
| `H_FUNC_CREATEREMOTETHREAD` | macro | `payloads/Demon/include/common/Defines.h:146` | `#define H_FUNC_CREATEREMOTETHREAD` |
| `H_FUNC_CREATETHREAD` | macro | `payloads/Demon/include/common/Defines.h:285` | `#define H_FUNC_CREATETHREAD` |
| `H_FUNC_CREATETOOLHELP32SNAPSHOT` | macro | `payloads/Demon/include/common/Defines.h:147` | `#define H_FUNC_CREATETOOLHELP32SNAPSHOT` |
| `H_FUNC_DEBUGBREAK` | macro | `payloads/Demon/include/common/Defines.h:124` | `#define H_FUNC_DEBUGBREAK` |
| `H_FUNC_DELETEDC` | macro | `payloads/Demon/include/common/Defines.h:251` | `#define H_FUNC_DELETEDC` |
| `H_FUNC_DELETEFIBER` | macro | `payloads/Demon/include/common/Defines.h:168` | `#define H_FUNC_DELETEFIBER` |
| `H_FUNC_DELETEFILEW` | macro | `payloads/Demon/include/common/Defines.h:188` | `#define H_FUNC_DELETEFILEW` |
| `H_FUNC_DELETEOBJECT` | macro | `payloads/Demon/include/common/Defines.h:250` | `#define H_FUNC_DELETEOBJECT` |
| `H_FUNC_DISCONNECTNAMEDPIPE` | macro | `payloads/Demon/include/common/Defines.h:176` | `#define H_FUNC_DISCONNECTNAMEDPIPE` |
| `H_FUNC_DUPLICATEHANDLE` | macro | `payloads/Demon/include/common/Defines.h:198` | `#define H_FUNC_DUPLICATEHANDLE` |
| `H_FUNC_EQUALSID` | macro | `payloads/Demon/include/common/Defines.h:227` | `#define H_FUNC_EQUALSID` |
| `H_FUNC_EXITPROCESS` | macro | `payloads/Demon/include/common/Defines.h:163` | `#define H_FUNC_EXITPROCESS` |
| `H_FUNC_FILETIMETOSYSTEMTIME` | macro | `payloads/Demon/include/common/Defines.h:121` | `#define H_FUNC_FILETIMETOSYSTEMTIME` |
| `H_FUNC_FILETIMETOSYSTEMTIME` | macro | `payloads/Demon/include/common/Defines.h:185` | `#define H_FUNC_FILETIMETOSYSTEMTIME` |
| `H_FUNC_FINDCLOSE` | macro | `payloads/Demon/include/common/Defines.h:120` | `#define H_FUNC_FINDCLOSE` |
| `H_FUNC_FINDCLOSE` | macro | `payloads/Demon/include/common/Defines.h:184` | `#define H_FUNC_FINDCLOSE` |
| `H_FUNC_FINDFIRSTFILEW` | macro | `payloads/Demon/include/common/Defines.h:118` | `#define H_FUNC_FINDFIRSTFILEW` |
| `H_FUNC_FINDFIRSTFILEW` | macro | `payloads/Demon/include/common/Defines.h:182` | `#define H_FUNC_FINDFIRSTFILEW` |
| `H_FUNC_FINDNEXTFILEW` | macro | `payloads/Demon/include/common/Defines.h:119` | `#define H_FUNC_FINDNEXTFILEW` |
| `H_FUNC_FINDNEXTFILEW` | macro | `payloads/Demon/include/common/Defines.h:183` | `#define H_FUNC_FINDNEXTFILEW` |
| `H_FUNC_FREEADDRINFO` | macro | `payloads/Demon/include/common/Defines.h:275` | `#define H_FUNC_FREEADDRINFO` |
| `H_FUNC_FREECONSOLE` | macro | `payloads/Demon/include/common/Defines.h:170` | `#define H_FUNC_FREECONSOLE` |
| `H_FUNC_FREELIBRARY` | macro | `payloads/Demon/include/common/Defines.h:179` | `#define H_FUNC_FREELIBRARY` |
| `H_FUNC_FREESID` | macro | `payloads/Demon/include/common/Defines.h:216` | `#define H_FUNC_FREESID` |
| `H_FUNC_GETADAPTERSINFO` | macro | `payloads/Demon/include/common/Defines.h:129` | `#define H_FUNC_GETADAPTERSINFO` |
| `H_FUNC_GETADAPTERSINFO` | macro | `payloads/Demon/include/common/Defines.h:254` | `#define H_FUNC_GETADAPTERSINFO` |
| `H_FUNC_GETADDRINFO` | macro | `payloads/Demon/include/common/Defines.h:274` | `#define H_FUNC_GETADDRINFO` |
| `H_FUNC_GETCOMPUTERNAMEEXA` | macro | `payloads/Demon/include/common/Defines.h:112` | `#define H_FUNC_GETCOMPUTERNAMEEXA` |
| `H_FUNC_GETCOMPUTERNAMEEXA` | macro | `payloads/Demon/include/common/Defines.h:162` | `#define H_FUNC_GETCOMPUTERNAMEEXA` |
| `H_FUNC_GETCONSOLEWINDOW` | macro | `payloads/Demon/include/common/Defines.h:171` | `#define H_FUNC_GETCONSOLEWINDOW` |
| `H_FUNC_GETCURRENTDIRECTORYW` | macro | `payloads/Demon/include/common/Defines.h:117` | `#define H_FUNC_GETCURRENTDIRECTORYW` |
| `H_FUNC_GETCURRENTDIRECTORYW` | macro | `payloads/Demon/include/common/Defines.h:180` | `#define H_FUNC_GETCURRENTDIRECTORYW` |
| `H_FUNC_GETCURRENTOBJECT` | macro | `payloads/Demon/include/common/Defines.h:244` | `#define H_FUNC_GETCURRENTOBJECT` |
| `H_FUNC_GETDC` | macro | `payloads/Demon/include/common/Defines.h:242` | `#define H_FUNC_GETDC` |
| `H_FUNC_GETEXITCODEPROCESS` | macro | `payloads/Demon/include/common/Defines.h:164` | `#define H_FUNC_GETEXITCODEPROCESS` |
| `H_FUNC_GETEXITCODETHREAD` | macro | `payloads/Demon/include/common/Defines.h:165` | `#define H_FUNC_GETEXITCODETHREAD` |
| `H_FUNC_GETFILEATTRIBUTESW` | macro | `payloads/Demon/include/common/Defines.h:181` | `#define H_FUNC_GETFILEATTRIBUTESW` |
| `H_FUNC_GETFILESIZE` | macro | `payloads/Demon/include/common/Defines.h:154` | `#define H_FUNC_GETFILESIZE` |
| `H_FUNC_GETFILESIZEEX` | macro | `payloads/Demon/include/common/Defines.h:155` | `#define H_FUNC_GETFILESIZEEX` |
| `H_FUNC_GETFULLPATHNAMEW` | macro | `payloads/Demon/include/common/Defines.h:153` | `#define H_FUNC_GETFULLPATHNAMEW` |
| `H_FUNC_GETLOCALTIME` | macro | `payloads/Demon/include/common/Defines.h:197` | `#define H_FUNC_GETLOCALTIME` |
| `H_FUNC_GETMODULEHANDLEA` | macro | `payloads/Demon/include/common/Defines.h:115` | `#define H_FUNC_GETMODULEHANDLEA` |
| `H_FUNC_GETMODULEHANDLEA` | macro | `payloads/Demon/include/common/Defines.h:195` | `#define H_FUNC_GETMODULEHANDLEA` |
| `H_FUNC_GETOBJECTW` | macro | `payloads/Demon/include/common/Defines.h:245` | `#define H_FUNC_GETOBJECTW` |
| `H_FUNC_GETPROCADDRESS` | macro | `payloads/Demon/include/common/Defines.h:116` | `#define H_FUNC_GETPROCADDRESS` |
| `H_FUNC_GETSIDSUBAUTHORITY` | macro | `payloads/Demon/include/common/Defines.h:230` | `#define H_FUNC_GETSIDSUBAUTHORITY` |
| `H_FUNC_GETSIDSUBAUTHORITYCOUNT` | macro | `payloads/Demon/include/common/Defines.h:229` | `#define H_FUNC_GETSIDSUBAUTHORITYCOUNT` |
| `H_FUNC_GETSTDHANDLE` | macro | `payloads/Demon/include/common/Defines.h:172` | `#define H_FUNC_GETSTDHANDLE` |
| `H_FUNC_GETSYSTEMMETRICS` | macro | `payloads/Demon/include/common/Defines.h:241` | `#define H_FUNC_GETSYSTEMMETRICS` |
| `H_FUNC_GETSYSTEMTIMEASFILETIME` | macro | `payloads/Demon/include/common/Defines.h:196` | `#define H_FUNC_GETSYSTEMTIMEASFILETIME` |
| `H_FUNC_GETTOKENINFORMATION` | macro | `payloads/Demon/include/common/Defines.h:203` | `#define H_FUNC_GETTOKENINFORMATION` |
| `H_FUNC_GETUSERNAMEA` | macro | `payloads/Demon/include/common/Defines.h:207` | `#define H_FUNC_GETUSERNAMEA` |
| `H_FUNC_GLOBALFREE` | macro | `payloads/Demon/include/common/Defines.h:287` | `#define H_FUNC_GLOBALFREE` |
| `H_FUNC_INITIALIZEACL` | macro | `payloads/Demon/include/common/Defines.h:221` | `#define H_FUNC_INITIALIZEACL` |
| `H_FUNC_INITIALIZESECURITYDESCRIPTOR` | macro | `payloads/Demon/include/common/Defines.h:219` | `#define H_FUNC_INITIALIZESECURITYDESCRIPTOR` |
| `H_FUNC_IOCTLSOCKET` | macro | `payloads/Demon/include/common/Defines.h:266` | `#define H_FUNC_IOCTLSOCKET` |
| `H_FUNC_LDRGETPROCEDUREADDRESS` | macro | `payloads/Demon/include/common/Defines.h:45` | `#define H_FUNC_LDRGETPROCEDUREADDRESS` |
| `H_FUNC_LDRLOADDLL` | macro | `payloads/Demon/include/common/Defines.h:44` | `#define H_FUNC_LDRLOADDLL` |
| `H_FUNC_LISTEN` | macro | `payloads/Demon/include/common/Defines.h:268` | `#define H_FUNC_LISTEN` |
| `H_FUNC_LOADLIBRARYW` | macro | `payloads/Demon/include/common/Defines.h:111` | `#define H_FUNC_LOADLIBRARYW` |
| `H_FUNC_LOCALALLOC` | macro | `payloads/Demon/include/common/Defines.h:143` | `#define H_FUNC_LOCALALLOC` |
| `H_FUNC_LOCALFREE` | macro | `payloads/Demon/include/common/Defines.h:145` | `#define H_FUNC_LOCALFREE` |
| `H_FUNC_LOCALREALLOC` | macro | `payloads/Demon/include/common/Defines.h:144` | `#define H_FUNC_LOCALREALLOC` |
| `H_FUNC_LOGONUSEREXW` | macro | `payloads/Demon/include/common/Defines.h:127` | `#define H_FUNC_LOGONUSEREXW` |
| `H_FUNC_LOGONUSERW` | macro | `payloads/Demon/include/common/Defines.h:208` | `#define H_FUNC_LOGONUSERW` |
| `H_FUNC_LOOKUPACCOUNTSIDA` | macro | `payloads/Demon/include/common/Defines.h:209` | `#define H_FUNC_LOOKUPACCOUNTSIDA` |
| `H_FUNC_LOOKUPACCOUNTSIDW` | macro | `payloads/Demon/include/common/Defines.h:126` | `#define H_FUNC_LOOKUPACCOUNTSIDW` |
| `H_FUNC_LOOKUPACCOUNTSIDW` | macro | `payloads/Demon/include/common/Defines.h:210` | `#define H_FUNC_LOOKUPACCOUNTSIDW` |
| `H_FUNC_LOOKUPPRIVILEGENAMEA` | macro | `payloads/Demon/include/common/Defines.h:214` | `#define H_FUNC_LOOKUPPRIVILEGENAMEA` |
| `H_FUNC_LOOKUPPRIVILEGEVALUEA` | macro | `payloads/Demon/include/common/Defines.h:231` | `#define H_FUNC_LOOKUPPRIVILEGEVALUEA` |
| `H_FUNC_LSACALLAUTHENTICATIONPACKAGE` | macro | `payloads/Demon/include/common/Defines.h:281` | `#define H_FUNC_LSACALLAUTHENTICATIONPACKAGE` |
| `H_FUNC_LSACONNECTUNTRUSTED` | macro | `payloads/Demon/include/common/Defines.h:279` | `#define H_FUNC_LSACONNECTUNTRUSTED` |
| `H_FUNC_LSADEREGISTERLOGONPROCESS` | macro | `payloads/Demon/include/common/Defines.h:278` | `#define H_FUNC_LSADEREGISTERLOGONPROCESS` |
| `H_FUNC_LSAENUMERATELOGONSESSIONS` | macro | `payloads/Demon/include/common/Defines.h:283` | `#define H_FUNC_LSAENUMERATELOGONSESSIONS` |
| `H_FUNC_LSAFREERETURNBUFFER` | macro | `payloads/Demon/include/common/Defines.h:280` | `#define H_FUNC_LSAFREERETURNBUFFER` |
| `H_FUNC_LSAGETLOGONSESSIONDATA` | macro | `payloads/Demon/include/common/Defines.h:282` | `#define H_FUNC_LSAGETLOGONSESSIONDATA` |
| `H_FUNC_LSALOOKUPAUTHENTICATIONPACKAGE` | macro | `payloads/Demon/include/common/Defines.h:277` | `#define H_FUNC_LSALOOKUPAUTHENTICATIONPACKAGE` |
| `H_FUNC_LSANTSTATUSTOWINERROR` | macro | `payloads/Demon/include/common/Defines.h:226` | `#define H_FUNC_LSANTSTATUSTOWINERROR` |
| `H_FUNC_LSAREGISTERLOGONPROCESS` | macro | `payloads/Demon/include/common/Defines.h:276` | `#define H_FUNC_LSAREGISTERLOGONPROCESS` |
| `H_FUNC_MOVEFILEEXW` | macro | `payloads/Demon/include/common/Defines.h:191` | `#define H_FUNC_MOVEFILEEXW` |
| `H_FUNC_NETAPIBUFFERFREE` | macro | `payloads/Demon/include/common/Defines.h:261` | `#define H_FUNC_NETAPIBUFFERFREE` |
| `H_FUNC_NETGROUPENUM` | macro | `payloads/Demon/include/common/Defines.h:256` | `#define H_FUNC_NETGROUPENUM` |
| `H_FUNC_NETLOCALGROUPENUM` | macro | `payloads/Demon/include/common/Defines.h:255` | `#define H_FUNC_NETLOCALGROUPENUM` |
| `H_FUNC_NETSESSIONENUM` | macro | `payloads/Demon/include/common/Defines.h:259` | `#define H_FUNC_NETSESSIONENUM` |
| `H_FUNC_NETSHAREENUM` | macro | `payloads/Demon/include/common/Defines.h:260` | `#define H_FUNC_NETSHAREENUM` |
| `H_FUNC_NETUSERENUM` | macro | `payloads/Demon/include/common/Defines.h:257` | `#define H_FUNC_NETUSERENUM` |
| `H_FUNC_NETWKSTAUSERENUM` | macro | `payloads/Demon/include/common/Defines.h:258` | `#define H_FUNC_NETWKSTAUSERENUM` |
| `H_FUNC_NTADDBOOTENTRY` | macro | `payloads/Demon/include/common/Defines.h:46` | `#define H_FUNC_NTADDBOOTENTRY` |
| `H_FUNC_NTALERTRESUMETHREAD` | macro | `payloads/Demon/include/common/Defines.h:87` | `#define H_FUNC_NTALERTRESUMETHREAD` |
| `H_FUNC_NTALLOCATEVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:47` | `#define H_FUNC_NTALLOCATEVIRTUALMEMORY` |
| `H_FUNC_NTCLOSE` | macro | `payloads/Demon/include/common/Defines.h:63` | `#define H_FUNC_NTCLOSE` |
| `H_FUNC_NTCONTINUE` | macro | `payloads/Demon/include/common/Defines.h:64` | `#define H_FUNC_NTCONTINUE` |
| `H_FUNC_NTCREATEEVENT` | macro | `payloads/Demon/include/common/Defines.h:66` | `#define H_FUNC_NTCREATEEVENT` |
| `H_FUNC_NTCREATETHREADEX` | macro | `payloads/Demon/include/common/Defines.h:74` | `#define H_FUNC_NTCREATETHREADEX` |
| `H_FUNC_NTDUPLICATEOBJECT` | macro | `payloads/Demon/include/common/Defines.h:72` | `#define H_FUNC_NTDUPLICATEOBJECT` |
| `H_FUNC_NTDUPLICATETOKEN` | macro | `payloads/Demon/include/common/Defines.h:86` | `#define H_FUNC_NTDUPLICATETOKEN` |
| `H_FUNC_NTFREEVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:48` | `#define H_FUNC_NTFREEVIRTUALMEMORY` |
| `H_FUNC_NTFREEVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:83` | `#define H_FUNC_NTFREEVIRTUALMEMORY` |
| `H_FUNC_NTGETCONTEXTTHREAD` | macro | `payloads/Demon/include/common/Defines.h:62` | `#define H_FUNC_NTGETCONTEXTTHREAD` |
| `H_FUNC_NTGETNEXTTHREAD` | macro | `payloads/Demon/include/common/Defines.h:69` | `#define H_FUNC_NTGETNEXTTHREAD` |
| `H_FUNC_NTOPENPROCESS` | macro | `payloads/Demon/include/common/Defines.h:57` | `#define H_FUNC_NTOPENPROCESS` |
| `H_FUNC_NTOPENPROCESSTOKEN` | macro | `payloads/Demon/include/common/Defines.h:53` | `#define H_FUNC_NTOPENPROCESSTOKEN` |
| `H_FUNC_NTOPENTHREAD` | macro | `payloads/Demon/include/common/Defines.h:59` | `#define H_FUNC_NTOPENTHREAD` |
| `H_FUNC_NTOPENTHREADTOKEN` | macro | `payloads/Demon/include/common/Defines.h:54` | `#define H_FUNC_NTOPENTHREADTOKEN` |
| `H_FUNC_NTOPENTHREADTOKEN` | macro | `payloads/Demon/include/common/Defines.h:60` | `#define H_FUNC_NTOPENTHREADTOKEN` |
| `H_FUNC_NTPROTECTVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:81` | `#define H_FUNC_NTPROTECTVIRTUALMEMORY` |
| `H_FUNC_NTQUERYINFORMATIONPROCESS` | macro | `payloads/Demon/include/common/Defines.h:78` | `#define H_FUNC_NTQUERYINFORMATIONPROCESS` |
| `H_FUNC_NTQUERYINFORMATIONTHREAD` | macro | `payloads/Demon/include/common/Defines.h:73` | `#define H_FUNC_NTQUERYINFORMATIONTHREAD` |
| `H_FUNC_NTQUERYINFORMATIONTOKEN` | macro | `payloads/Demon/include/common/Defines.h:77` | `#define H_FUNC_NTQUERYINFORMATIONTOKEN` |
| `H_FUNC_NTQUERYOBJECT` | macro | `payloads/Demon/include/common/Defines.h:55` | `#define H_FUNC_NTQUERYOBJECT` |
| `H_FUNC_NTQUERYSYSTEMINFORMATION` | macro | `payloads/Demon/include/common/Defines.h:76` | `#define H_FUNC_NTQUERYSYSTEMINFORMATION` |
| `H_FUNC_NTQUERYVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:52` | `#define H_FUNC_NTQUERYVIRTUALMEMORY` |
| `H_FUNC_NTQUEUEAPCTHREAD` | macro | `payloads/Demon/include/common/Defines.h:75` | `#define H_FUNC_NTQUEUEAPCTHREAD` |
| `H_FUNC_NTREADVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:82` | `#define H_FUNC_NTREADVIRTUALMEMORY` |
| `H_FUNC_NTRESUMETHREAD` | macro | `payloads/Demon/include/common/Defines.h:70` | `#define H_FUNC_NTRESUMETHREAD` |
| `H_FUNC_NTSETCONTEXTTHREAD` | macro | `payloads/Demon/include/common/Defines.h:61` | `#define H_FUNC_NTSETCONTEXTTHREAD` |
| `H_FUNC_NTSETEVENT` | macro | `payloads/Demon/include/common/Defines.h:65` | `#define H_FUNC_NTSETEVENT` |
| `H_FUNC_NTSETINFORMATIONTHREAD` | macro | `payloads/Demon/include/common/Defines.h:79` | `#define H_FUNC_NTSETINFORMATIONTHREAD` |
| `H_FUNC_NTSETINFORMATIONVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:51` | `#define H_FUNC_NTSETINFORMATIONVIRTUALMEMORY` |
| `H_FUNC_NTSETINFORMATIONVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:80` | `#define H_FUNC_NTSETINFORMATIONVIRTUALMEMORY` |
| `H_FUNC_NTSIGNALANDWAITFORSINGLEOBJECT` | macro | `payloads/Demon/include/common/Defines.h:68` | `#define H_FUNC_NTSIGNALANDWAITFORSINGLEOBJECT` |
| `H_FUNC_NTSUSPENDTHREAD` | macro | `payloads/Demon/include/common/Defines.h:71` | `#define H_FUNC_NTSUSPENDTHREAD` |
| `H_FUNC_NTTERMINATEPROCESS` | macro | `payloads/Demon/include/common/Defines.h:58` | `#define H_FUNC_NTTERMINATEPROCESS` |
| `H_FUNC_NTTERMINATETHREAD` | macro | `payloads/Demon/include/common/Defines.h:84` | `#define H_FUNC_NTTERMINATETHREAD` |
| `H_FUNC_NTTESTALERT` | macro | `payloads/Demon/include/common/Defines.h:88` | `#define H_FUNC_NTTESTALERT` |
| `H_FUNC_NTTRACEEVENT` | macro | `payloads/Demon/include/common/Defines.h:56` | `#define H_FUNC_NTTRACEEVENT` |
| `H_FUNC_NTUNMAPVIEWOFSECTION` | macro | `payloads/Demon/include/common/Defines.h:49` | `#define H_FUNC_NTUNMAPVIEWOFSECTION` |
| `H_FUNC_NTWAITFORSINGLEOBJECT` | macro | `payloads/Demon/include/common/Defines.h:67` | `#define H_FUNC_NTWAITFORSINGLEOBJECT` |
| `H_FUNC_NTWRITEVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:50` | `#define H_FUNC_NTWRITEVIRTUALMEMORY` |
| `H_FUNC_NTWRITEVIRTUALMEMORY` | macro | `payloads/Demon/include/common/Defines.h:85` | `#define H_FUNC_NTWRITEVIRTUALMEMORY` |
| `H_FUNC_OPENPROCESSTOKEN` | macro | `payloads/Demon/include/common/Defines.h:212` | `#define H_FUNC_OPENPROCESSTOKEN` |
| `H_FUNC_OPENTHREADTOKEN` | macro | `payloads/Demon/include/common/Defines.h:211` | `#define H_FUNC_OPENTHREADTOKEN` |
| `H_FUNC_OUTPUTDEBUGSTRINGA` | macro | `payloads/Demon/include/common/Defines.h:123` | `#define H_FUNC_OUTPUTDEBUGSTRINGA` |
| `H_FUNC_PEEKNAMEDPIPE` | macro | `payloads/Demon/include/common/Defines.h:175` | `#define H_FUNC_PEEKNAMEDPIPE` |
| `H_FUNC_PROCESS32FIRSTW` | macro | `payloads/Demon/include/common/Defines.h:148` | `#define H_FUNC_PROCESS32FIRSTW` |
| `H_FUNC_PROCESS32NEXTW` | macro | `payloads/Demon/include/common/Defines.h:149` | `#define H_FUNC_PROCESS32NEXTW` |
| `H_FUNC_READFILE` | macro | `payloads/Demon/include/common/Defines.h:159` | `#define H_FUNC_READFILE` |
| `H_FUNC_RECV` | macro | `payloads/Demon/include/common/Defines.h:271` | `#define H_FUNC_RECV` |
| `H_FUNC_RELEASEDC` | macro | `payloads/Demon/include/common/Defines.h:243` | `#define H_FUNC_RELEASEDC` |
| `H_FUNC_REMOVEDIRECTORYW` | macro | `payloads/Demon/include/common/Defines.h:187` | `#define H_FUNC_REMOVEDIRECTORYW` |
| `H_FUNC_REVERTTOSELF` | macro | `payloads/Demon/include/common/Defines.h:206` | `#define H_FUNC_REVERTTOSELF` |
| `H_FUNC_RTLADDVECTOREDEXCEPTIONHANDLER` | macro | `payloads/Demon/include/common/Defines.h:97` | `#define H_FUNC_RTLADDVECTOREDEXCEPTIONHANDLER` |
| `H_FUNC_RTLALLOCATEHEAP` | macro | `payloads/Demon/include/common/Defines.h:89` | `#define H_FUNC_RTLALLOCATEHEAP` |
| `H_FUNC_RTLCAPTURECONTEXT` | macro | `payloads/Demon/include/common/Defines.h:104` | `#define H_FUNC_RTLCAPTURECONTEXT` |
| `H_FUNC_RTLCOPYMAPPEDMEMORY` | macro | `payloads/Demon/include/common/Defines.h:105` | `#define H_FUNC_RTLCOPYMAPPEDMEMORY` |
| `H_FUNC_RTLCREATETIMER` | macro | `payloads/Demon/include/common/Defines.h:101` | `#define H_FUNC_RTLCREATETIMER` |
| `H_FUNC_RTLCREATETIMERQUEUE` | macro | `payloads/Demon/include/common/Defines.h:99` | `#define H_FUNC_RTLCREATETIMERQUEUE` |
| `H_FUNC_RTLDELETETIMERQUEUE` | macro | `payloads/Demon/include/common/Defines.h:100` | `#define H_FUNC_RTLDELETETIMERQUEUE` |
| `H_FUNC_RTLEXITUSERPROCESS` | macro | `payloads/Demon/include/common/Defines.h:92` | `#define H_FUNC_RTLEXITUSERPROCESS` |
| `H_FUNC_RTLEXITUSERTHREAD` | macro | `payloads/Demon/include/common/Defines.h:107` | `#define H_FUNC_RTLEXITUSERTHREAD` |
| `H_FUNC_RTLFILLMEMORY` | macro | `payloads/Demon/include/common/Defines.h:106` | `#define H_FUNC_RTLFILLMEMORY` |
| `H_FUNC_RTLFREEHEAP` | macro | `payloads/Demon/include/common/Defines.h:91` | `#define H_FUNC_RTLFREEHEAP` |
| `H_FUNC_RTLGETVERSION` | macro | `payloads/Demon/include/common/Defines.h:96` | `#define H_FUNC_RTLGETVERSION` |
| `H_FUNC_RTLNTSTATUSTODOSERROR` | macro | `payloads/Demon/include/common/Defines.h:95` | `#define H_FUNC_RTLNTSTATUSTODOSERROR` |
| `H_FUNC_RTLQUEUEWORKITEM` | macro | `payloads/Demon/include/common/Defines.h:102` | `#define H_FUNC_RTLQUEUEWORKITEM` |
| `H_FUNC_RTLRANDOMEX` | macro | `payloads/Demon/include/common/Defines.h:93` | `#define H_FUNC_RTLRANDOMEX` |
| `H_FUNC_RTLRANDOMEX` | macro | `payloads/Demon/include/common/Defines.h:94` | `#define H_FUNC_RTLRANDOMEX` |
| `H_FUNC_RTLREALLOCATEHEAP` | macro | `payloads/Demon/include/common/Defines.h:90` | `#define H_FUNC_RTLREALLOCATEHEAP` |
| `H_FUNC_RTLREGISTERWAIT` | macro | `payloads/Demon/include/common/Defines.h:103` | `#define H_FUNC_RTLREGISTERWAIT` |
| `H_FUNC_RTLREMOVEVECTOREDEXCEPTIONHANDLER` | macro | `payloads/Demon/include/common/Defines.h:98` | `#define H_FUNC_RTLREMOVEVECTOREDEXCEPTIONHANDLER` |
| `H_FUNC_RTLSUBAUTHORITYCOUNTSID` | macro | `payloads/Demon/include/common/Defines.h:109` | `#define H_FUNC_RTLSUBAUTHORITYCOUNTSID` |
| `H_FUNC_RTLSUBAUTHORITYSID` | macro | `payloads/Demon/include/common/Defines.h:108` | `#define H_FUNC_RTLSUBAUTHORITYSID` |
| `H_FUNC_SAFEARRAYACCESSDATA` | macro | `payloads/Demon/include/common/Defines.h:232` | `#define H_FUNC_SAFEARRAYACCESSDATA` |
| `H_FUNC_SAFEARRAYCREATE` | macro | `payloads/Demon/include/common/Defines.h:234` | `#define H_FUNC_SAFEARRAYCREATE` |
| `H_FUNC_SAFEARRAYCREATEVECTOR` | macro | `payloads/Demon/include/common/Defines.h:236` | `#define H_FUNC_SAFEARRAYCREATEVECTOR` |
| `H_FUNC_SAFEARRAYDESTROY` | macro | `payloads/Demon/include/common/Defines.h:237` | `#define H_FUNC_SAFEARRAYDESTROY` |
| `H_FUNC_SAFEARRAYPUTELEMENT` | macro | `payloads/Demon/include/common/Defines.h:235` | `#define H_FUNC_SAFEARRAYPUTELEMENT` |
| `H_FUNC_SAFEARRAYUNACCESSDATA` | macro | `payloads/Demon/include/common/Defines.h:233` | `#define H_FUNC_SAFEARRAYUNACCESSDATA` |
| `H_FUNC_SELECTOBJECT` | macro | `payloads/Demon/include/common/Defines.h:248` | `#define H_FUNC_SELECTOBJECT` |
| `H_FUNC_SEND` | macro | `payloads/Demon/include/common/Defines.h:272` | `#define H_FUNC_SEND` |
| `H_FUNC_SETCURRENTDIRECTORYW` | macro | `payloads/Demon/include/common/Defines.h:192` | `#define H_FUNC_SETCURRENTDIRECTORYW` |
| `H_FUNC_SETENTRIESINACLW` | macro | `payloads/Demon/include/common/Defines.h:224` | `#define H_FUNC_SETENTRIESINACLW` |
| `H_FUNC_SETPROCESSVALIDCALLTARGETS` | macro | `payloads/Demon/include/common/Defines.h:252` | `#define H_FUNC_SETPROCESSVALIDCALLTARGETS` |
| `H_FUNC_SETSECURITYDESCRIPTORDACL` | macro | `payloads/Demon/include/common/Defines.h:218` | `#define H_FUNC_SETSECURITYDESCRIPTORDACL` |
| `H_FUNC_SETSECURITYDESCRIPTORSACL` | macro | `payloads/Demon/include/common/Defines.h:217` | `#define H_FUNC_SETSECURITYDESCRIPTORSACL` |
| `H_FUNC_SETSTDHANDLE` | macro | `payloads/Demon/include/common/Defines.h:173` | `#define H_FUNC_SETSTDHANDLE` |
| `H_FUNC_SETTHREADTOKEN` | macro | `payloads/Demon/include/common/Defines.h:225` | `#define H_FUNC_SETTHREADTOKEN` |
| `H_FUNC_SHOWWINDOW` | macro | `payloads/Demon/include/common/Defines.h:240` | `#define H_FUNC_SHOWWINDOW` |
| `H_FUNC_SLEEP` | macro | `payloads/Demon/include/common/Defines.h:284` | `#define H_FUNC_SLEEP` |
| `H_FUNC_SWITCHTOFIBER` | macro | `payloads/Demon/include/common/Defines.h:167` | `#define H_FUNC_SWITCHTOFIBER` |
| `H_FUNC_SWPRINTF_S` | macro | `payloads/Demon/include/common/Defines.h:288` | `#define H_FUNC_SWPRINTF_S` |
| `H_FUNC_SYSALLOCSTRING` | macro | `payloads/Demon/include/common/Defines.h:238` | `#define H_FUNC_SYSALLOCSTRING` |
| `H_FUNC_SYSTEMFUNCTION032` | macro | `payloads/Demon/include/common/Defines.h:125` | `#define H_FUNC_SYSTEMFUNCTION032` |
| `H_FUNC_SYSTEMFUNCTION032` | macro | `payloads/Demon/include/common/Defines.h:215` | `#define H_FUNC_SYSTEMFUNCTION032` |
| `H_FUNC_SYSTEMTIMETOTZSPECIFICLOCALTIME` | macro | `payloads/Demon/include/common/Defines.h:122` | `#define H_FUNC_SYSTEMTIMETOTZSPECIFICLOCALTIME` |
| `H_FUNC_SYSTEMTIMETOTZSPECIFICLOCALTIME` | macro | `payloads/Demon/include/common/Defines.h:186` | `#define H_FUNC_SYSTEMTIMETOTZSPECIFICLOCALTIME` |
| `H_FUNC_TERMINATEPROCESS` | macro | `payloads/Demon/include/common/Defines.h:201` | `#define H_FUNC_TERMINATEPROCESS` |
| `H_FUNC_VIRTUALALLOCEX` | macro | `payloads/Demon/include/common/Defines.h:160` | `#define H_FUNC_VIRTUALALLOCEX` |
| `H_FUNC_VIRTUALPROTECT` | macro | `payloads/Demon/include/common/Defines.h:114` | `#define H_FUNC_VIRTUALPROTECT` |
| `H_FUNC_VIRTUALPROTECT` | macro | `payloads/Demon/include/common/Defines.h:202` | `#define H_FUNC_VIRTUALPROTECT` |
| `H_FUNC_VIRTUALPROTECTEX` | macro | `payloads/Demon/include/common/Defines.h:142` | `#define H_FUNC_VIRTUALPROTECTEX` |
| `H_FUNC_VSNPRINTF` | macro | `payloads/Demon/include/common/Defines.h:128` | `#define H_FUNC_VSNPRINTF` |
| `H_FUNC_WAITFORSINGLEOBJECTEX` | macro | `payloads/Demon/include/common/Defines.h:113` | `#define H_FUNC_WAITFORSINGLEOBJECTEX` |
| `H_FUNC_WAITFORSINGLEOBJECTEX` | macro | `payloads/Demon/include/common/Defines.h:161` | `#define H_FUNC_WAITFORSINGLEOBJECTEX` |
| `H_FUNC_WAITNAMEDPIPEW` | macro | `payloads/Demon/include/common/Defines.h:174` | `#define H_FUNC_WAITNAMEDPIPEW` |
| `H_FUNC_WINHTTPADDREQUESTHEADERS` | macro | `payloads/Demon/include/common/Defines.h:136` | `#define H_FUNC_WINHTTPADDREQUESTHEADERS` |
| `H_FUNC_WINHTTPCLOSEHANDLE` | macro | `payloads/Demon/include/common/Defines.h:139` | `#define H_FUNC_WINHTTPCLOSEHANDLE` |
| `H_FUNC_WINHTTPCONNECT` | macro | `payloads/Demon/include/common/Defines.h:131` | `#define H_FUNC_WINHTTPCONNECT` |
| `H_FUNC_WINHTTPGETIEPROXYCONFIGFORCURRENTUSER` | macro | `payloads/Demon/include/common/Defines.h:140` | `#define H_FUNC_WINHTTPGETIEPROXYCONFIGFORCURRENTUSER` |
| `H_FUNC_WINHTTPGETPROXYFORURL` | macro | `payloads/Demon/include/common/Defines.h:141` | `#define H_FUNC_WINHTTPGETPROXYFORURL` |
| `H_FUNC_WINHTTPOPEN` | macro | `payloads/Demon/include/common/Defines.h:130` | `#define H_FUNC_WINHTTPOPEN` |
| `H_FUNC_WINHTTPOPENREQUEST` | macro | `payloads/Demon/include/common/Defines.h:132` | `#define H_FUNC_WINHTTPOPENREQUEST` |
| `H_FUNC_WINHTTPQUERYHEADERS` | macro | `payloads/Demon/include/common/Defines.h:138` | `#define H_FUNC_WINHTTPQUERYHEADERS` |
| `H_FUNC_WINHTTPREADDATA` | macro | `payloads/Demon/include/common/Defines.h:137` | `#define H_FUNC_WINHTTPREADDATA` |
| `H_FUNC_WINHTTPRECEIVERESPONSE` | macro | `payloads/Demon/include/common/Defines.h:135` | `#define H_FUNC_WINHTTPRECEIVERESPONSE` |
| `H_FUNC_WINHTTPSENDREQUEST` | macro | `payloads/Demon/include/common/Defines.h:134` | `#define H_FUNC_WINHTTPSENDREQUEST` |
| `H_FUNC_WINHTTPSETOPTION` | macro | `payloads/Demon/include/common/Defines.h:133` | `#define H_FUNC_WINHTTPSETOPTION` |
| `H_FUNC_WOW64DISABLEWOW64FSREDIRECTION` | macro | `payloads/Demon/include/common/Defines.h:193` | `#define H_FUNC_WOW64DISABLEWOW64FSREDIRECTION` |
| `H_FUNC_WOW64REVERTWOW64FSREDIRECTION` | macro | `payloads/Demon/include/common/Defines.h:194` | `#define H_FUNC_WOW64REVERTWOW64FSREDIRECTION` |
| `H_FUNC_WRITECONSOLEA` | macro | `payloads/Demon/include/common/Defines.h:200` | `#define H_FUNC_WRITECONSOLEA` |
| `H_FUNC_WRITEFILE` | macro | `payloads/Demon/include/common/Defines.h:177` | `#define H_FUNC_WRITEFILE` |
| `H_FUNC_WSACLEANUP` | macro | `payloads/Demon/include/common/Defines.h:263` | `#define H_FUNC_WSACLEANUP` |
| `H_FUNC_WSAGETLASTERROR` | macro | `payloads/Demon/include/common/Defines.h:265` | `#define H_FUNC_WSAGETLASTERROR` |
| `H_FUNC_WSASOCKETA` | macro | `payloads/Demon/include/common/Defines.h:264` | `#define H_FUNC_WSASOCKETA` |
| `H_FUNC_WSASTARTUP` | macro | `payloads/Demon/include/common/Defines.h:262` | `#define H_FUNC_WSASTARTUP` |
| `H_MODULE_KERNEL32` | macro | `payloads/Demon/include/common/Defines.h:368` | `#define H_MODULE_KERNEL32` |
| `H_MODULE_NTDLL` | macro | `payloads/Demon/include/common/Defines.h:369` | `#define H_MODULE_NTDLL` |
| `LDR_GADGET_HEADER_SIZE` | macro | `payloads/Demon/include/common/Defines.h:32` | `#define LDR_GADGET_HEADER_SIZE` |
| `LDR_GADGET_MODULE_SIZE` | macro | `payloads/Demon/include/common/Defines.h:31` | `#define LDR_GADGET_MODULE_SIZE` |
| `PROCESS_AGENT_ARCH` | macro | `payloads/Demon/include/common/Defines.h:10` | `#define PROCESS_AGENT_ARCH` |
| `PROCESS_AGENT_ARCH` | macro | `payloads/Demon/include/common/Defines.h:12` | `#define PROCESS_AGENT_ARCH` |
| `PROCESS_ARCH_IA64` | macro | `payloads/Demon/include/common/Defines.h:7` | `#define PROCESS_ARCH_IA64` |
| `PROCESS_ARCH_UNKNOWN` | macro | `payloads/Demon/include/common/Defines.h:4` | `#define PROCESS_ARCH_UNKNOWN` |
| `PROCESS_ARCH_X64` | macro | `payloads/Demon/include/common/Defines.h:6` | `#define PROCESS_ARCH_X64` |
| `PROCESS_ARCH_X86` | macro | `payloads/Demon/include/common/Defines.h:5` | `#define PROCESS_ARCH_X86` |
| `PROXYLOAD_NONE` | macro | `payloads/Demon/include/common/Defines.h:34` | `#define PROXYLOAD_NONE` |
| `PROXYLOAD_RTLCREATETIMER` | macro | `payloads/Demon/include/common/Defines.h:36` | `#define PROXYLOAD_RTLCREATETIMER` |
| `PROXYLOAD_RTLQUEUEWORKITEM` | macro | `payloads/Demon/include/common/Defines.h:37` | `#define PROXYLOAD_RTLQUEUEWORKITEM` |
| `PROXYLOAD_RTLREGISTERWAIT` | macro | `payloads/Demon/include/common/Defines.h:35` | `#define PROXYLOAD_RTLREGISTERWAIT` |
| `WIN_VERSION_10` | macro | `payloads/Demon/include/common/Defines.h:28` | `#define WIN_VERSION_10` |
| `WIN_VERSION_2008` | macro | `payloads/Demon/include/common/Defines.h:20` | `#define WIN_VERSION_2008` |
| `WIN_VERSION_2008_R2` | macro | `payloads/Demon/include/common/Defines.h:22` | `#define WIN_VERSION_2008_R2` |
| `WIN_VERSION_2008_R2` | macro | `payloads/Demon/include/common/Defines.h:23` | `#define WIN_VERSION_2008_R2` |
| `WIN_VERSION_2012` | macro | `payloads/Demon/include/common/Defines.h:24` | `#define WIN_VERSION_2012` |
| `WIN_VERSION_2012_R2` | macro | `payloads/Demon/include/common/Defines.h:27` | `#define WIN_VERSION_2012_R2` |
| `WIN_VERSION_2016_X` | macro | `payloads/Demon/include/common/Defines.h:29` | `#define WIN_VERSION_2016_X` |
| `WIN_VERSION_7` | macro | `payloads/Demon/include/common/Defines.h:21` | `#define WIN_VERSION_7` |
| `WIN_VERSION_8` | macro | `payloads/Demon/include/common/Defines.h:25` | `#define WIN_VERSION_8` |
| `WIN_VERSION_8_1` | macro | `payloads/Demon/include/common/Defines.h:26` | `#define WIN_VERSION_8_1` |
| `WIN_VERSION_UNKNOWN` | macro | `payloads/Demon/include/common/Defines.h:17` | `#define WIN_VERSION_UNKNOWN` |
| `WIN_VERSION_VISTA` | macro | `payloads/Demon/include/common/Defines.h:19` | `#define WIN_VERSION_VISTA` |
| `WIN_VERSION_XP` | macro | `payloads/Demon/include/common/Defines.h:18` | `#define WIN_VERSION_XP` |
| `B_PTR` | macro | `payloads/Demon/include/common/Macros.h:33` | `#define B_PTR( x )` |
| `C_PTR` | macro | `payloads/Demon/include/common/Macros.h:32` | `#define C_PTR( x )` |
| `DATA_FREE` | macro | `payloads/Demon/include/common/Macros.h:23` | `#define DATA_FREE( d, l )` |
| `DEMON_MACROS_H` | macro | `payloads/Demon/include/common/Macros.h:2` | `#define DEMON_MACROS_H` |
| `DLLEXPORT` | macro | `payloads/Demon/include/common/Macros.h:20` | `#define DLLEXPORT` |
| `DREF_U16` | macro | `payloads/Demon/include/common/Macros.h:35` | `#define DREF_U16( x )` |
| `DREF_U8` | macro | `payloads/Demon/include/common/Macros.h:34` | `#define DREF_U8( x )` |
| `HTONS16` | macro | `payloads/Demon/include/common/Macros.h:37` | `#define HTONS16( x )` |
| `HTONS32` | macro | `payloads/Demon/include/common/Macros.h:36` | `#define HTONS32( x )` |
| `IMAGE_SIZE` | macro | `payloads/Demon/include/common/Macros.h:38` | `#define IMAGE_SIZE( IM )` |
| `NT_SUCCESS` | macro | `payloads/Demon/include/common/Macros.h:12` | `#define NT_SUCCESS(Status)` |
| `NtCurrentProcess` | macro | `payloads/Demon/include/common/Macros.h:13` | `#define NtCurrentProcess()` |
| `NtCurrentThread` | macro | `payloads/Demon/include/common/Macros.h:14` | `#define NtCurrentThread()` |
| `NtGetLastError` | macro | `payloads/Demon/include/common/Macros.h:15` | `#define NtGetLastError()` |
| `NtProcessHeap` | macro | `payloads/Demon/include/common/Macros.h:19` | `#define NtProcessHeap()` |
| `NtSetLastError` | macro | `payloads/Demon/include/common/Macros.h:16` | `#define NtSetLastError(x)` |
| `PPEB_PTR` | macro | `payloads/Demon/include/common/Macros.h:7` | `#define PPEB_PTR` |
| `PPEB_PTR` | macro | `payloads/Demon/include/common/Macros.h:9` | `#define PPEB_PTR` |
| `PRINTF` | macro | `payloads/Demon/include/common/Macros.h:44` | `#define PRINTF( f, ... )` |
| `PRINTF` | macro | `payloads/Demon/include/common/Macros.h:47` | `#define PRINTF( f, ... )` |
| `PRINTF` | macro | `payloads/Demon/include/common/Macros.h:50` | `#define PRINTF( f, ... )` |
| `PRINTF` | macro | `payloads/Demon/include/common/Macros.h:53` | `#define PRINTF( f, ... )` |
| `PRINTF` | macro | `payloads/Demon/include/common/Macros.h:57` | `#define PRINTF( f, ... )` |
| `PRINTF_DONT_SEND` | macro | `payloads/Demon/include/common/Macros.h:45` | `#define PRINTF_DONT_SEND( f, ... )` |
| `PRINTF_DONT_SEND` | macro | `payloads/Demon/include/common/Macros.h:48` | `#define PRINTF_DONT_SEND( f, ... )` |
| `PRINTF_DONT_SEND` | macro | `payloads/Demon/include/common/Macros.h:51` | `#define PRINTF_DONT_SEND( f, ... )` |
| `PRINTF_DONT_SEND` | macro | `payloads/Demon/include/common/Macros.h:54` | `#define PRINTF_DONT_SEND( f, ... )` |
| `PRINTF_DONT_SEND` | macro | `payloads/Demon/include/common/Macros.h:58` | `#define PRINTF_DONT_SEND( f, ... )` |
| `PRINT_HEX` | macro | `payloads/Demon/include/common/Macros.h:78` | `#define PRINT_HEX( b, l )` |
| `PRINT_HEX` | macro | `payloads/Demon/include/common/Macros.h:86` | `#define PRINT_HEX( b, l )` |
| `PUTS` | macro | `payloads/Demon/include/common/Macros.h:63` | `#define PUTS( s )` |
| `PUTS` | macro | `payloads/Demon/include/common/Macros.h:66` | `#define PUTS( s )` |
| `PUTS` | macro | `payloads/Demon/include/common/Macros.h:69` | `#define PUTS( s )` |
| `PUTS` | macro | `payloads/Demon/include/common/Macros.h:73` | `#define PUTS( s )` |
| `PUTS_DONT_SEND` | macro | `payloads/Demon/include/common/Macros.h:64` | `#define PUTS_DONT_SEND( s )` |
| `PUTS_DONT_SEND` | macro | `payloads/Demon/include/common/Macros.h:67` | `#define PUTS_DONT_SEND( s )` |
| `PUTS_DONT_SEND` | macro | `payloads/Demon/include/common/Macros.h:70` | `#define PUTS_DONT_SEND( s )` |
| `PUTS_DONT_SEND` | macro | `payloads/Demon/include/common/Macros.h:74` | `#define PUTS_DONT_SEND( s )` |
| `RVA` | macro | `payloads/Demon/include/common/Macros.h:22` | `#define RVA( TYPE, DLLBASE, RVA )` |
| `SEC_DATA` | macro | `payloads/Demon/include/common/Macros.h:30` | `#define SEC_DATA` |
| `U_PTR` | macro | `payloads/Demon/include/common/Macros.h:31` | `#define U_PTR( x )` |
| `1` | type_alias | `payloads/Demon/include/common/Native.h:3330` | `typedef struct _MEMORY_WORKING_SET_EX_BLOCK { ULONG_PTR Valid : 1;` |
| `5` | type_alias | `payloads/Demon/include/common/Native.h:3312` | `typedef struct _MEMORY_WORKING_SET_BLOCK { ULONG_PTR Protection : 5;` |
| `ABSOLUTE_TIME` | macro | `payloads/Demon/include/common/Native.h:67` | `#define ABSOLUTE_TIME(wait)` |
| `ACTIVATION_CONTEXT_STACK_FLAG_QUERIES_DISABLED` | macro | `payloads/Demon/include/common/Native.h:6893` | `#define ACTIVATION_CONTEXT_STACK_FLAG_QUERIES_DISABLED` |
| `ALIGN_BYTE` | macro | `payloads/Demon/include/common/Native.h:668` | `#define ALIGN_BYTE` |
| `ALIGN_CHAR` | macro | `payloads/Demon/include/common/Native.h:669` | `#define ALIGN_CHAR` |
| `ALIGN_DESC_CHAR` | macro | `payloads/Demon/include/common/Native.h:670` | `#define ALIGN_DESC_CHAR` |
| `ALIGN_DWORD` | macro | `payloads/Demon/include/common/Native.h:671` | `#define ALIGN_DWORD` |
| `ALIGN_LONG` | macro | `payloads/Demon/include/common/Native.h:672` | `#define ALIGN_LONG` |
| `ALIGN_LPBYTE` | macro | `payloads/Demon/include/common/Native.h:673` | `#define ALIGN_LPBYTE` |
| `ALIGN_LPDWORD` | macro | `payloads/Demon/include/common/Native.h:674` | `#define ALIGN_LPDWORD` |
| `ALIGN_LPSTR` | macro | `payloads/Demon/include/common/Native.h:675` | `#define ALIGN_LPSTR` |
| `ALIGN_LPTSTR` | macro | `payloads/Demon/include/common/Native.h:676` | `#define ALIGN_LPTSTR` |
| `ALIGN_LPVOID` | macro | `payloads/Demon/include/common/Native.h:677` | `#define ALIGN_LPVOID` |
| `ALIGN_LPWORD` | macro | `payloads/Demon/include/common/Native.h:678` | `#define ALIGN_LPWORD` |
| `ALIGN_QUAD` | macro | `payloads/Demon/include/common/Native.h:682` | `#define ALIGN_QUAD` |
| `ALIGN_TCHAR` | macro | `payloads/Demon/include/common/Native.h:679` | `#define ALIGN_TCHAR` |
| `ALIGN_TO_POWER2` | macro | `payloads/Demon/include/common/Native.h:88` | `#define ALIGN_TO_POWER2( x, n )` |
| `ALIGN_WCHAR` | macro | `payloads/Demon/include/common/Native.h:680` | `#define ALIGN_WCHAR` |
| `ALIGN_WORD` | macro | `payloads/Demon/include/common/Native.h:681` | `#define ALIGN_WORD` |
| `ALIGN_WORST` | macro | `payloads/Demon/include/common/Native.h:684` | `#define ALIGN_WORST` |
| `ANSI_NULL` | macro | `payloads/Demon/include/common/Native.h:389` | `#define ANSI_NULL` |
| `ANSI_NULL` | macro | `payloads/Demon/include/common/Native.h:543` | `#define ANSI_NULL` |
| `ANSI_STRING` | type_alias | `payloads/Demon/include/common/Native.h:374` | `typedef STRING ANSI_STRING;` |
| `ANSI_STRING32` | type_alias | `payloads/Demon/include/common/Native.h:413` | `typedef STRING32 ANSI_STRING32;` |
| `ANSI_STRING64` | type_alias | `payloads/Demon/include/common/Native.h:428` | `typedef STRING64 ANSI_STRING64;` |
| `ARGUMENT_PRESENT` | macro | `payloads/Demon/include/common/Native.h:78` | `#define ARGUMENT_PRESENT(ArgumentPointer)` |
| `ASSERT` | macro | `payloads/Demon/include/common/Native.h:113` | `#define ASSERT( exp )` |
| `A_SHAFinal` | function | `payloads/Demon/include/common/Native.h:21318` | `void NTAPI A_SHAFinal( PSHA_CTX Context, PULONG Result );` |
| `AccessFlags` | type_alias | `payloads/Demon/include/common/Native.h:3978` | `typedef struct _FILE_ACCESS_INFORMATION { ACCESS_MASK AccessFlags;` |
| `AccessMask` | type_alias | `payloads/Demon/include/common/Native.h:8730` | `typedef struct _SE_ADT_ACCESS_REASON{ ACCESS_MASK AccessMask;` |
| `ActiveFrame` | type_alias | `payloads/Demon/include/common/Native.h:6901` | `typedef struct _ACTIVATION_CONTEXT_STACK { struct _RTL_ACTIVATION_CONTEXT_STACK_FRAME * ActiveFrame;` |
| `Address` | type_alias | `payloads/Demon/include/common/Native.h:2507` | `typedef struct _SYSDBG_VIRTUAL { PVOID Address;` |
| `Address` | type_alias | `payloads/Demon/include/common/Native.h:2514` | `typedef struct _SYSDBG_PHYSICAL { PHYSICAL_ADDRESS Address;` |
| `Address` | type_alias | `payloads/Demon/include/common/Native.h:2521` | `typedef struct _SYSDBG_CONTROL_SPACE { ULONG64 Address;` |
| `Address` | type_alias | `payloads/Demon/include/common/Native.h:2534` | `typedef struct _SYSDBG_IO_SPACE { ULONG64 Address;` |
| `Address` | type_alias | `payloads/Demon/include/common/Native.h:2568` | `typedef struct _SYSDBG_BUS_DATA { ULONG Address;` |
| `Address` | type_alias | `payloads/Demon/include/common/Native.h:7245` | `typedef struct _RTL_PROCESS_LOCK_INFORMATION { PVOID Address;` |
| `Address` | type_alias | `payloads/Demon/include/common/Native.h:9871` | `typedef struct _RTL_STACK_CONTEXT_ENTRY { ULONG_PTR Address;` |
| `Alignment` | type_alias | `payloads/Demon/include/common/Native.h:11646` | `typedef struct DECLSPEC_ALIGN(16) _SLIST_HEADER { ULONGLONG Alignment;` |
| `AlignmentFixupCount` | type_alias | `payloads/Demon/include/common/Native.h:4302` | `typedef struct _SYSTEM_EXCEPTION_INFORMATION { ULONG AlignmentFixupCount;` |
| `AlignmentRequirement` | type_alias | `payloads/Demon/include/common/Native.h:3990` | `typedef struct _FILE_ALIGNMENT_INFORMATION { // ntddk nthal ULONG AlignmentRequirement;` |
| `Allocated` | type_alias | `payloads/Demon/include/common/Native.h:4393` | `typedef struct _SYSTEM_POOL_ENTRY { BOOLEAN Allocated;` |
| `AllocationBase` | type_alias | `payloads/Demon/include/common/Native.h:3347` | `typedef struct _MEMORY_REGION_INFORMATION { PVOID AllocationBase;` |
| `AllocationSize` | type_alias | `payloads/Demon/include/common/Native.h:3961` | `typedef struct _FILE_STANDARD_INFORMATION { LARGE_INTEGER AllocationSize;` |
| `AllocationSize` | type_alias | `payloads/Demon/include/common/Native.h:4027` | `typedef struct _FILE_ALLOCATION_INFORMATION { LARGE_INTEGER AllocationSize;` |
| `AllocatorBackTraceIndex` | type_alias | `payloads/Demon/include/common/Native.h:10580` | `typedef struct _HEAP_ENTRY_EXTRA { USHORT AllocatorBackTraceIndex;` |
| `Allocs` | type_alias | `payloads/Demon/include/common/Native.h:10455` | `typedef struct _HEAP_PSEUDO_TAG_ENTRY { ULONG Allocs;` |
| `Allocs` | type_alias | `payloads/Demon/include/common/Native.h:10462` | `typedef struct _HEAP_TAG_ENTRY { ULONG Allocs;` |
| `ApiNumberBase` | type_alias | `payloads/Demon/include/common/Native.h:5998` | `typedef struct _CSR_CALLBACK_INFO { ULONG ApiNumberBase;` |
| `Attributes` | type_alias | `payloads/Demon/include/common/Native.h:3472` | `typedef struct _OBJECT_BASIC_INFORMATION { ULONG Attributes;` |
| `AuditLogPercentFull` | type_alias | `payloads/Demon/include/common/Native.h:8960` | `typedef struct _POLICY_AUDIT_LOG_INFO { ULONG AuditLogPercentFull;` |
| `Audit_AccountLogon_CredentialValidation_defined` | macro | `payloads/Demon/include/common/Native.h:8315` | `#define Audit_AccountLogon_CredentialValidation_defined` |
| `Audit_AccountLogon_KerbCredentialValidation_defined` | macro | `payloads/Demon/include/common/Native.h:8351` | `#define Audit_AccountLogon_KerbCredentialValidation_defined` |
| `Audit_AccountLogon_Kerberos_defined` | macro | `payloads/Demon/include/common/Native.h:8327` | `#define Audit_AccountLogon_Kerberos_defined` |
| `Audit_AccountLogon_Others_defined` | macro | `payloads/Demon/include/common/Native.h:8339` | `#define Audit_AccountLogon_Others_defined` |
| `Audit_AccountLogon_defined` | macro | `payloads/Demon/include/common/Native.h:8492` | `#define Audit_AccountLogon_defined` |
| `Audit_AccountManagement_ApplicationGroup_defined` | macro | `payloads/Demon/include/common/Native.h:8243` | `#define Audit_AccountManagement_ApplicationGroup_defined` |
| `Audit_AccountManagement_ComputerAccount_defined` | macro | `payloads/Demon/include/common/Native.h:8207` | `#define Audit_AccountManagement_ComputerAccount_defined` |
| `Audit_AccountManagement_DistributionGroup_defined` | macro | `payloads/Demon/include/common/Native.h:8231` | `#define Audit_AccountManagement_DistributionGroup_defined` |
| `Audit_AccountManagement_Others_defined` | macro | `payloads/Demon/include/common/Native.h:8255` | `#define Audit_AccountManagement_Others_defined` |
| `Audit_AccountManagement_SecurityGroup_defined` | macro | `payloads/Demon/include/common/Native.h:8219` | `#define Audit_AccountManagement_SecurityGroup_defined` |
| `Audit_AccountManagement_UserAccount_defined` | macro | `payloads/Demon/include/common/Native.h:8195` | `#define Audit_AccountManagement_UserAccount_defined` |
| `Audit_AccountManagement_defined` | macro | `payloads/Demon/include/common/Native.h:8468` | `#define Audit_AccountManagement_defined` |
| `Audit_DSAccess_DSAccess_defined` | macro | `payloads/Demon/include/common/Native.h:8267` | `#define Audit_DSAccess_DSAccess_defined` |
| `Audit_DetailedTracking_DpapiActivity_defined` | macro | `payloads/Demon/include/common/Native.h:8099` | `#define Audit_DetailedTracking_DpapiActivity_defined` |
| `Audit_DetailedTracking_ProcessCreation_defined` | macro | `payloads/Demon/include/common/Native.h:8075` | `#define Audit_DetailedTracking_ProcessCreation_defined` |
| `Audit_DetailedTracking_ProcessTermination_defined` | macro | `payloads/Demon/include/common/Native.h:8087` | `#define Audit_DetailedTracking_ProcessTermination_defined` |
| `Audit_DetailedTracking_RpcCall_defined` | macro | `payloads/Demon/include/common/Native.h:8111` | `#define Audit_DetailedTracking_RpcCall_defined` |
| `Audit_DetailedTracking_defined` | macro | `payloads/Demon/include/common/Native.h:8444` | `#define Audit_DetailedTracking_defined` |
| `Audit_DirectoryServiceAccess_defined` | macro | `payloads/Demon/include/common/Native.h:8480` | `#define Audit_DirectoryServiceAccess_defined` |
| `Audit_DsAccess_AdAuditChanges_defined` | macro | `payloads/Demon/include/common/Native.h:8279` | `#define Audit_DsAccess_AdAuditChanges_defined` |
| `Audit_Ds_DetailedReplication_defined` | macro | `payloads/Demon/include/common/Native.h:8303` | `#define Audit_Ds_DetailedReplication_defined` |
| `Audit_Ds_Replication_defined` | macro | `payloads/Demon/include/common/Native.h:8291` | `#define Audit_Ds_Replication_defined` |
| `Audit_Logon_AccountLockout_defined` | macro | `payloads/Demon/include/common/Native.h:7827` | `#define Audit_Logon_AccountLockout_defined` |
| `Audit_Logon_IPSecMainMode_defined` | macro | `payloads/Demon/include/common/Native.h:7839` | `#define Audit_Logon_IPSecMainMode_defined` |
| `Audit_Logon_IPSecQuickMode_defined` | macro | `payloads/Demon/include/common/Native.h:7851` | `#define Audit_Logon_IPSecQuickMode_defined` |
| `Audit_Logon_IPSecUserMode_defined` | macro | `payloads/Demon/include/common/Native.h:7863` | `#define Audit_Logon_IPSecUserMode_defined` |
| `Audit_Logon_Logoff_defined` | macro | `payloads/Demon/include/common/Native.h:7815` | `#define Audit_Logon_Logoff_defined` |
| `Audit_Logon_Logon_defined` | macro | `payloads/Demon/include/common/Native.h:7803` | `#define Audit_Logon_Logon_defined` |
| `Audit_Logon_NPS_defined` | macro | `payloads/Demon/include/common/Native.h:8363` | `#define Audit_Logon_NPS_defined` |
| `Audit_Logon_Others_defined` | macro | `payloads/Demon/include/common/Native.h:7887` | `#define Audit_Logon_Others_defined` |
| `Audit_Logon_SpecialLogon_defined` | macro | `payloads/Demon/include/common/Native.h:7875` | `#define Audit_Logon_SpecialLogon_defined` |
| `Audit_Logon_defined` | macro | `payloads/Demon/include/common/Native.h:8408` | `#define Audit_Logon_defined` |
| `Audit_ObjectAccess_ApplicationGenerated_defined` | macro | `payloads/Demon/include/common/Native.h:7959` | `#define Audit_ObjectAccess_ApplicationGenerated_defined` |
| `Audit_ObjectAccess_CertificationServices_defined` | macro | `payloads/Demon/include/common/Native.h:7947` | `#define Audit_ObjectAccess_CertificationServices_defined` |
| `Audit_ObjectAccess_DetailedFileShare_defined` | macro | `payloads/Demon/include/common/Native.h:8375` | `#define Audit_ObjectAccess_DetailedFileShare_defined` |
| `Audit_ObjectAccess_FileSystem_defined` | macro | `payloads/Demon/include/common/Native.h:7899` | `#define Audit_ObjectAccess_FileSystem_defined` |
| `Audit_ObjectAccess_FirewallConnection_defined` | macro | `payloads/Demon/include/common/Native.h:8015` | `#define Audit_ObjectAccess_FirewallConnection_defined` |
| `Audit_ObjectAccess_FirewallPacketDrops_defined` | macro | `payloads/Demon/include/common/Native.h:8003` | `#define Audit_ObjectAccess_FirewallPacketDrops_defined` |
| `Audit_ObjectAccess_Handle_defined` | macro | `payloads/Demon/include/common/Native.h:7979` | `#define Audit_ObjectAccess_Handle_defined` |
| `Audit_ObjectAccess_Kernel_defined` | macro | `payloads/Demon/include/common/Native.h:7923` | `#define Audit_ObjectAccess_Kernel_defined` |
| `Audit_ObjectAccess_Other_defined` | macro | `payloads/Demon/include/common/Native.h:8027` | `#define Audit_ObjectAccess_Other_defined` |
| `Audit_ObjectAccess_Registry_defined` | macro | `payloads/Demon/include/common/Native.h:7911` | `#define Audit_ObjectAccess_Registry_defined` |
| `Audit_ObjectAccess_Sam_defined` | macro | `payloads/Demon/include/common/Native.h:7935` | `#define Audit_ObjectAccess_Sam_defined` |
| `Audit_ObjectAccess_Share_defined` | macro | `payloads/Demon/include/common/Native.h:7991` | `#define Audit_ObjectAccess_Share_defined` |
| `Audit_ObjectAccess_defined` | macro | `payloads/Demon/include/common/Native.h:8420` | `#define Audit_ObjectAccess_defined` |
| `Audit_PolicyChange_AuditPolicy_defined` | macro | `payloads/Demon/include/common/Native.h:8123` | `#define Audit_PolicyChange_AuditPolicy_defined` |
| `Audit_PolicyChange_AuthenticationPolicy_defined` | macro | `payloads/Demon/include/common/Native.h:8135` | `#define Audit_PolicyChange_AuthenticationPolicy_defined` |
| `Audit_PolicyChange_AuthorizationPolicy_defined` | macro | `payloads/Demon/include/common/Native.h:8147` | `#define Audit_PolicyChange_AuthorizationPolicy_defined` |
| `Audit_PolicyChange_MpsscvRulePolicy_defined` | macro | `payloads/Demon/include/common/Native.h:8159` | `#define Audit_PolicyChange_MpsscvRulePolicy_defined` |
| `Audit_PolicyChange_Others_defined` | macro | `payloads/Demon/include/common/Native.h:8183` | `#define Audit_PolicyChange_Others_defined` |
| `Audit_PolicyChange_WfpIPSecPolicy_defined` | macro | `payloads/Demon/include/common/Native.h:8171` | `#define Audit_PolicyChange_WfpIPSecPolicy_defined` |
| `Audit_PolicyChange_defined` | macro | `payloads/Demon/include/common/Native.h:8456` | `#define Audit_PolicyChange_defined` |
| `Audit_PrivilegeUse_NonSensitive_defined` | macro | `payloads/Demon/include/common/Native.h:8051` | `#define Audit_PrivilegeUse_NonSensitive_defined` |
| `Audit_PrivilegeUse_Others_defined` | macro | `payloads/Demon/include/common/Native.h:8063` | `#define Audit_PrivilegeUse_Others_defined` |
| `Audit_PrivilegeUse_Sensitive_defined` | macro | `payloads/Demon/include/common/Native.h:8039` | `#define Audit_PrivilegeUse_Sensitive_defined` |
| `Audit_PrivilegeUse_defined` | macro | `payloads/Demon/include/common/Native.h:8432` | `#define Audit_PrivilegeUse_defined` |
| `Audit_System_IPSecDriverEvents_defined` | macro | `payloads/Demon/include/common/Native.h:7779` | `#define Audit_System_IPSecDriverEvents_defined` |
| `Audit_System_Integrity_defined` | macro | `payloads/Demon/include/common/Native.h:7767` | `#define Audit_System_Integrity_defined` |
| `Audit_System_Others_defined` | macro | `payloads/Demon/include/common/Native.h:7791` | `#define Audit_System_Others_defined` |
| `Audit_System_SecurityStateChange_defined` | macro | `payloads/Demon/include/common/Native.h:7743` | `#define Audit_System_SecurityStateChange_defined` |
| `Audit_System_SecuritySubsystemExtension_defined` | macro | `payloads/Demon/include/common/Native.h:7755` | `#define Audit_System_SecuritySubsystemExtension_defined` |
| `Audit_System_defined` | macro | `payloads/Demon/include/common/Native.h:8396` | `#define Audit_System_defined` |
| `AuditingMode` | type_alias | `payloads/Demon/include/common/Native.h:8971` | `typedef struct _POLICY_AUDIT_EVENTS_INFO { BOOLEAN AuditingMode;` |
| `AuthenticationOptions` | type_alias | `payloads/Demon/include/common/Native.h:9111` | `typedef struct _POLICY_DOMAIN_KERBEROS_TICKET_INFO { ULONG AuthenticationOptions;` |
| `BASESRV_FIRST_API_NUMBER` | macro | `payloads/Demon/include/common/Native.h:5948` | `#define BASESRV_FIRST_API_NUMBER` |
| `BASESRV_SERVERDLL_INDEX` | macro | `payloads/Demon/include/common/Native.h:5947` | `#define BASESRV_SERVERDLL_INDEX` |
| `BalancedRoot` | type_alias | `payloads/Demon/include/common/Native.h:10023` | `typedef struct _RTL_AVL_TABLE { RTL_BALANCED_LINKS BalancedRoot;` |
| `Base` | type_alias | `payloads/Demon/include/common/Native.h:5881` | `typedef struct _PORT_DATA_ENTRY { LPC_PVOID Base;` |
| `BaseAddress` | type_alias | `payloads/Demon/include/common/Native.h:4795` | `typedef struct _MEMORY_BASIC_INFORMATION { PVOID BaseAddress;` |
| `BaseAddress` | type_alias | `payloads/Demon/include/common/Native.h:7222` | `typedef struct _RTL_HEAP_INFORMATION { PVOID BaseAddress;` |
| `BaseAddress` | type_alias | `payloads/Demon/include/common/Native.h:11017` | `typedef struct _DBGKM_UNLOAD_DLL { PVOID BaseAddress;` |
| `BaseAddress` | type_alias | `payloads/Demon/include/common/Native.h:21428` | `typedef struct _RTL_UNLOAD_EVENT_TRACE { PVOID BaseAddress;` |
| `BaseAddress` | type_alias | `payloads/Demon/include/common/Native.h:21437` | `typedef struct _RTL_UNLOAD_EVENT_TRACE64 { ULONGLONG BaseAddress;` |
| `BaseAddress` | type_alias | `payloads/Demon/include/common/Native.h:21446` | `typedef struct _RTL_UNLOAD_EVENT_TRACE32 { ULONG BaseAddress;` |
| `BasicContext` | type_alias | `payloads/Demon/include/common/Native.h:6923` | `typedef struct _TEB_ACTIVE_FRAME_CONTEXT_EX { TEB_ACTIVE_FRAME_CONTEXT BasicContext;` |
| `BasicFrame` | type_alias | `payloads/Demon/include/common/Native.h:6943` | `typedef struct _TEB_ACTIVE_FRAME_EX { TEB_ACTIVE_FRAME BasicFrame;` |
| `BasicInformation` | type_alias | `payloads/Demon/include/common/Native.h:3999` | `typedef struct _FILE_ALL_INFORMATION { FILE_BASIC_INFORMATION BasicInformation;` |
| `Bias` | type_alias | `payloads/Demon/include/common/Native.h:3637` | `typedef struct _RTL_TIME_ZONE_INFORMATION { LONG Bias;` |
| `BootSectorCount` | type_alias | `payloads/Demon/include/common/Native.h:2196` | `typedef struct _BOOT_AREA_INFO { ULONG BootSectorCount;` |
| `BootTime` | type_alias | `payloads/Demon/include/common/Native.h:4627` | `typedef struct _SYSTEM_TIMEOFDAY_INFORMATION { LARGE_INTEGER BootTime;` |
| `Buffer` | type_alias | `payloads/Demon/include/common/Native.h:2103` | `typedef struct _TXFS_WRITE_BACKUP_INFORMATION { UCHAR Buffer[1];` |
| `BufferLength` | type_alias | `payloads/Demon/include/common/Native.h:2080` | `typedef struct _TXFS_READ_BACKUP_INFORMATION_OUT { union { // // Used to return the required buffer size if return code ` |
| `ByteOffset` | type_alias | `payloads/Demon/include/common/Native.h:1501` | `typedef struct _PLEX_READ_DATA_REQUEST { LARGE_INTEGER ByteOffset;` |
| `BytesRequired` | type_alias | `payloads/Demon/include/common/Native.h:1699` | `typedef struct _TXFS_QUERY_RM_INFORMATION { ULONG BytesRequired;` |
| `CACHE_FULLY_ASSOCIATIVE` | macro | `payloads/Demon/include/common/Native.h:4714` | `#define CACHE_FULLY_ASSOCIATIVE` |
| `CANSI_STRING` | type_alias | `payloads/Demon/include/common/Native.h:390` | `typedef STRING CANSI_STRING;` |
| `CCHAR` | type_alias | `payloads/Demon/include/common/Native.h:353` | `typedef char CCHAR;` |
| `CLONG` | type_alias | `payloads/Demon/include/common/Native.h:358` | `typedef ULONG CLONG;` |
| `COMPRESSION_ENGINE_HIBER` | macro | `payloads/Demon/include/common/Native.h:10108` | `#define COMPRESSION_ENGINE_HIBER` |
| `COMPRESSION_ENGINE_MAXIMUM` | macro | `payloads/Demon/include/common/Native.h:10107` | `#define COMPRESSION_ENGINE_MAXIMUM` |
| `COMPRESSION_ENGINE_STANDARD` | macro | `payloads/Demon/include/common/Native.h:10106` | `#define COMPRESSION_ENGINE_STANDARD` |
| `COMPRESSION_FORMAT_DEFAULT` | macro | `payloads/Demon/include/common/Native.h:10103` | `#define COMPRESSION_FORMAT_DEFAULT` |
| `COMPRESSION_FORMAT_LZNT1` | macro | `payloads/Demon/include/common/Native.h:10104` | `#define COMPRESSION_FORMAT_LZNT1` |
| `COMPRESSION_FORMAT_NONE` | macro | `payloads/Demon/include/common/Native.h:10102` | `#define COMPRESSION_FORMAT_NONE` |
| `COMPRESSION_FORMAT_SPARSE` | macro | `payloads/Demon/include/common/Native.h:1464` | `#define COMPRESSION_FORMAT_SPARSE` |
| `CONSRV_FIRST_API_NUMBER` | macro | `payloads/Demon/include/common/Native.h:5951` | `#define CONSRV_FIRST_API_NUMBER` |
| `CONSRV_SERVERDLL_INDEX` | macro | `payloads/Demon/include/common/Native.h:5950` | `#define CONSRV_SERVERDLL_INDEX` |
| `CONTAINING_RECORD` | macro | `payloads/Demon/include/common/Native.h:451` | `#define CONTAINING_RECORD(address, type, field)` |
| `COPYFILE_SIS_FLAGS` | macro | `payloads/Demon/include/common/Native.h:1522` | `#define COPYFILE_SIS_FLAGS` |
| `COPYFILE_SIS_LINK` | macro | `payloads/Demon/include/common/Native.h:1520` | `#define COPYFILE_SIS_LINK` |
| `COPYFILE_SIS_REPLACE` | macro | `payloads/Demon/include/common/Native.h:1521` | `#define COPYFILE_SIS_REPLACE` |
| `COUNT_IS_ALIGNED` | macro | `payloads/Demon/include/common/Native.h:627` | `#define COUNT_IS_ALIGNED(Count,Pow2)` |
| `CSHORT` | type_alias | `payloads/Demon/include/common/Native.h:355` | `typedef short CSHORT;` |
| `CSRSRV_FIRST_API_NUMBER` | macro | `payloads/Demon/include/common/Native.h:5945` | `#define CSRSRV_FIRST_API_NUMBER` |
| `CSRSRV_SERVERDLL_INDEX` | macro | `payloads/Demon/include/common/Native.h:5944` | `#define CSRSRV_SERVERDLL_INDEX` |
| `CSR_APINUMBER_TO_APITABLEINDEX` | macro | `payloads/Demon/include/common/Native.h:5962` | `#define CSR_APINUMBER_TO_APITABLEINDEX( ApiNumber )` |
| `CSR_APINUMBER_TO_SERVERDLLINDEX` | macro | `payloads/Demon/include/common/Native.h:5959` | `#define CSR_APINUMBER_TO_SERVERDLLINDEX( ApiNumber )` |
| `CSR_API_NUMBER` | type_alias | `payloads/Demon/include/common/Native.h:5895` | `typedef ULONG CSR_API_NUMBER;` |
| `CSR_API_PORT_NAME` | macro | `payloads/Demon/include/common/Native.h:5898` | `#define CSR_API_PORT_NAME` |
| `CSR_HIGH_PRIORITY_CLASS` | macro | `payloads/Demon/include/common/Native.h:5931` | `#define CSR_HIGH_PRIORITY_CLASS` |
| `CSR_IDLE_PRIORITY_CLASS` | macro | `payloads/Demon/include/common/Native.h:5930` | `#define CSR_IDLE_PRIORITY_CLASS` |
| `CSR_MAKE_API_NUMBER` | macro | `payloads/Demon/include/common/Native.h:5956` | `#define CSR_MAKE_API_NUMBER( DllIndex, ApiIndex )` |
| `CSR_NORMAL_PRIORITY_CLASS` | macro | `payloads/Demon/include/common/Native.h:5929` | `#define CSR_NORMAL_PRIORITY_CLASS` |
| `CSR_REALTIME_PRIORITY_CLASS` | macro | `payloads/Demon/include/common/Native.h:5932` | `#define CSR_REALTIME_PRIORITY_CLASS` |
| `CSV_INVALID_DEVICE_NUMBER` | macro | `payloads/Demon/include/common/Native.h:898` | `#define CSV_INVALID_DEVICE_NUMBER` |
| `CSV_NAMESPACE_INFO_V1` | macro | `payloads/Demon/include/common/Native.h:897` | `#define CSV_NAMESPACE_INFO_V1` |
| `CategoryId` | type_alias | `payloads/Demon/include/common/Native.h:8742` | `typedef struct _SE_ADT_PARAMETER_ARRAY { ULONG CategoryId;` |
| `Checksum` | type_alias | `payloads/Demon/include/common/Native.h:10051` | `typedef struct _GENERATE_NAME_CONTEXT { USHORT Checksum;` |
| `ClientId` | type_alias | `payloads/Demon/include/common/Native.h:6187` | `typedef struct _BASE_DEFERREDCREATEPROCESS_MSG { struct _CLIENT_ID* ClientId;` |
| `CloseDisc` | type_alias | `payloads/Demon/include/common/Native.h:1526` | `typedef struct _FILE_MAKE_COMPATIBLE_BUFFER { BOOLEAN CloseDisc;` |
| `ClusterCount` | type_alias | `payloads/Demon/include/common/Native.h:4058` | `typedef struct _FILE_MOVE_CLUSTER_INFORMATION { ULONG ClusterCount;` |
| `CodePage` | type_alias | `payloads/Demon/include/common/Native.h:3687` | `typedef struct _CPTABLEINFO { USHORT CodePage;` |
| `CollectDataTime` | type_alias | `payloads/Demon/include/common/Native.h:4109` | `typedef struct _FILE_PIPE_REMOTE_INFORMATION { LARGE_INTEGER CollectDataTime;` |
| `CommittThresholdShift` | type_alias | `payloads/Demon/include/common/Native.h:10449` | `typedef struct _HEAP_TUNING_PARAMETERS { ULONG CommittThresholdShift;` |
| `CommittedMemory` | type_alias | `payloads/Demon/include/common/Native.h:11247` | `typedef struct _RTL_PROCESS_BACKTRACES { ULONG CommittedMemory;` |
| `CompressedFileSize` | type_alias | `payloads/Demon/include/common/Native.h:4030` | `typedef struct _FILE_COMPRESSION_INFORMATION { LARGE_INTEGER CompressedFileSize;` |
| `CompressionFormatAndEngine` | type_alias | `payloads/Demon/include/common/Native.h:10109` | `typedef struct _COMPRESSED_DATA_INFO { USHORT CompressionFormatAndEngine;` |
| `ConsoleHandle` | type_alias | `payloads/Demon/include/common/Native.h:6180` | `typedef struct _BASE_GET_VDM_EXIT_CODE_MSG { PVOID ConsoleHandle;` |
| `ConsoleHandle` | type_alias | `payloads/Demon/include/common/Native.h:6197` | `typedef struct _BASE_GET_SET_VDM_CUR_DIRS_MSG { PVOID ConsoleHandle;` |
| `ConsoleHandle` | type_alias | `payloads/Demon/include/common/Native.h:6204` | `typedef struct _BASE_SET_REENTER_COUNT { PVOID ConsoleHandle;` |
| `ConsoleHandle` | type_alias | `payloads/Demon/include/common/Native.h:6275` | `typedef struct _BASE_EXIT_VDM_MSG { PVOID ConsoleHandle;` |
| `ConsoleHandle` | type_alias | `payloads/Demon/include/common/Native.h:6289` | `typedef struct _BASE_SET_REENTER_COUNT_MSG { PVOID ConsoleHandle;` |
| `ConsoleHandle` | type_alias | `payloads/Demon/include/common/Native.h:6296` | `typedef struct _BASE_BAT_NOTIFICATION_MSG { PVOID ConsoleHandle;` |
| `ContextFlags` | type_alias | `payloads/Demon/include/common/Native.h:3204` | `typedef struct _X86_CONTEXT { ULONG ContextFlags;` |
| `ContextFlags` | type_alias | `payloads/Demon/include/common/Native.h:7362` | `typedef struct _CONTEXT { // // The flags values within this flag control the contents of // a CONTEXT record. // // If ` |
| `ContextSwitches` | type_alias | `payloads/Demon/include/common/Native.h:4532` | `typedef struct _SYSTEM_CONTEXT_SWITCH_INFORMATION { ULONG ContextSwitches;` |
| `ContextSwitches` | type_alias | `payloads/Demon/include/common/Native.h:4555` | `typedef struct _SYSTEM_INTERRUPT_INFORMATION { ULONG ContextSwitches;` |
| `ControlWord` | type_alias | `payloads/Demon/include/common/Native.h:3191` | `typedef struct _X86_FLOATING_SAVE_AREA { ULONG ControlWord;` |
| `Count` | type_alias | `payloads/Demon/include/common/Native.h:4440` | `typedef struct _SYSTEM_POOLTAG_INFORMATION { ULONG Count;` |
| `Count` | type_alias | `payloads/Demon/include/common/Native.h:4453` | `typedef struct _SYSTEM_BIGPOOL_INFORMATION { ULONG Count;` |
| `CountDataEntries` | type_alias | `payloads/Demon/include/common/Native.h:5886` | `typedef struct _PORT_DATA_INFORMATION { ULONG CountDataEntries;` |
| `CreateHits` | type_alias | `payloads/Demon/include/common/Native.h:1254` | `typedef struct _FAT_STATISTICS { ULONG CreateHits;` |
| `CreateHits` | type_alias | `payloads/Demon/include/common/Native.h:1267` | `typedef struct _EXFAT_STATISTICS { ULONG CreateHits;` |
| `CreateTime` | type_alias | `payloads/Demon/include/common/Native.h:5153` | `typedef struct _KERNEL_USER_TIMES { LARGE_INTEGER CreateTime;` |
| `CreationTime` | type_alias | `payloads/Demon/include/common/Native.h:3953` | `typedef struct _FILE_BASIC_INFORMATION { // ntddk wdm nthal LARGE_INTEGER CreationTime;` |
| `CreationTime` | type_alias | `payloads/Demon/include/common/Native.h:4011` | `typedef struct _FILE_NETWORK_OPEN_INFORMATION { // ntddk wdm nthal LARGE_INTEGER CreationTime;` |
| `CriticalSection` | type_alias | `payloads/Demon/include/common/Native.h:10270` | `typedef struct _RTL_RESOURCE { RTL_CRITICAL_SECTION CriticalSection;` |
| `CriticalSection` | type_alias | `payloads/Demon/include/common/Native.h:10440` | `typedef struct _HEAP_LOCK { union { RTL_CRITICAL_SECTION CriticalSection;` |
| `CurrentByteOffset` | type_alias | `payloads/Demon/include/common/Native.h:3982` | `typedef struct _FILE_POSITION_INFORMATION { // ntddk wdm nthal LARGE_INTEGER CurrentByteOffset;` |
| `CurrentCount` | type_alias | `payloads/Demon/include/common/Native.h:3408` | `typedef struct _SEMAPHORE_BASIC_INFORMATION { LONG CurrentCount;` |
| `CurrentCount` | type_alias | `payloads/Demon/include/common/Native.h:3422` | `typedef struct _MUTANT_BASIC_INFORMATION { LONG CurrentCount;` |
| `CurrentDepth` | type_alias | `payloads/Demon/include/common/Native.h:4572` | `typedef struct _SYSTEM_LOOKASIDE_INFORMATION { USHORT CurrentDepth;` |
| `CurrentFrequency` | type_alias | `payloads/Demon/include/common/Native.h:4808` | `typedef struct _SYSTEM_PROCESSOR_POWER_INFORMATION { UCHAR CurrentFrequency;` |
| `CurrentMachineSIDOffset` | type_alias | `payloads/Demon/include/common/Native.h:2283` | `typedef struct _SD_CHANGE_MACHINE_SID_INPUT { USHORT CurrentMachineSIDOffset;` |
| `CurrentSize` | type_alias | `payloads/Demon/include/common/Native.h:5069` | `typedef struct _SYSTEM_FILECACHE_INFORMATION { SIZE_T CurrentSize;` |
| `DBG_TEB_RESERVED_1` | macro | `payloads/Demon/include/common/Native.h:7525` | `#define DBG_TEB_RESERVED_1` |
| `DBG_TEB_RESERVED_2` | macro | `payloads/Demon/include/common/Native.h:7526` | `#define DBG_TEB_RESERVED_2` |
| `DBG_TEB_RESERVED_3` | macro | `payloads/Demon/include/common/Native.h:7527` | `#define DBG_TEB_RESERVED_3` |
| `DBG_TEB_RESERVED_4` | macro | `payloads/Demon/include/common/Native.h:7528` | `#define DBG_TEB_RESERVED_4` |
| `DBG_TEB_RESERVED_5` | macro | `payloads/Demon/include/common/Native.h:7529` | `#define DBG_TEB_RESERVED_5` |
| `DBG_TEB_RESERVED_6` | macro | `payloads/Demon/include/common/Native.h:7530` | `#define DBG_TEB_RESERVED_6` |
| `DBG_TEB_RESERVED_7` | macro | `payloads/Demon/include/common/Native.h:7531` | `#define DBG_TEB_RESERVED_7` |
| `DBG_TEB_RESERVED_8` | macro | `payloads/Demon/include/common/Native.h:7532` | `#define DBG_TEB_RESERVED_8` |
| `DBG_TEB_THREADNAME` | macro | `payloads/Demon/include/common/Native.h:7524` | `#define DBG_TEB_THREADNAME` |
| `DEBUGDIR_SIZE` | macro | `payloads/Demon/include/common/Native.h:703` | `#define DEBUGDIR_SIZE(x)` |
| `DEBUGDIR_VA` | macro | `payloads/Demon/include/common/Native.h:702` | `#define DEBUGDIR_VA(x)` |
| `DEBUG_ALL_ACCESS` | macro | `payloads/Demon/include/common/Native.h:11071` | `#define DEBUG_ALL_ACCESS` |
| `DEBUG_KILL_ON_CLOSE` | macro | `payloads/Demon/include/common/Native.h:11075` | `#define DEBUG_KILL_ON_CLOSE` |
| `DEBUG_PROCESS_ASSIGN` | macro | `payloads/Demon/include/common/Native.h:11068` | `#define DEBUG_PROCESS_ASSIGN` |
| `DEBUG_QUERY_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:11070` | `#define DEBUG_QUERY_INFORMATION` |
| `DEBUG_READ_EVENT` | macro | `payloads/Demon/include/common/Native.h:11067` | `#define DEBUG_READ_EVENT` |
| `DEBUG_SET_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:11069` | `#define DEBUG_SET_INFORMATION` |
| `DECLARE_CONST_UNICODE_STRING` | macro | `payloads/Demon/include/common/Native.h:552` | `#define DECLARE_CONST_UNICODE_STRING(_variablename, _string)` |
| `DIRECTORY_ALL_ACCESS` | macro | `payloads/Demon/include/common/Native.h:3459` | `#define DIRECTORY_ALL_ACCESS` |
| `DIRECTORY_CREATE_OBJECT` | macro | `payloads/Demon/include/common/Native.h:3456` | `#define DIRECTORY_CREATE_OBJECT` |
| `DIRECTORY_CREATE_SUBDIRECTORY` | macro | `payloads/Demon/include/common/Native.h:3457` | `#define DIRECTORY_CREATE_SUBDIRECTORY` |
| `DIRECTORY_QUERY` | macro | `payloads/Demon/include/common/Native.h:3454` | `#define DIRECTORY_QUERY` |
| `DIRECTORY_TRAVERSE` | macro | `payloads/Demon/include/common/Native.h:3455` | `#define DIRECTORY_TRAVERSE` |
| `DOS_MAX_COMPONENT_LENGTH` | macro | `payloads/Demon/include/common/Native.h:5330` | `#define DOS_MAX_COMPONENT_LENGTH` |
| `DOS_MAX_COMPONENT_LENGTH` | macro | `payloads/Demon/include/common/Native.h:6720` | `#define DOS_MAX_COMPONENT_LENGTH` |
| `DOS_MAX_PATH_LENGTH` | macro | `payloads/Demon/include/common/Native.h:5331` | `#define DOS_MAX_PATH_LENGTH` |
| `DOS_MAX_PATH_LENGTH` | macro | `payloads/Demon/include/common/Native.h:6721` | `#define DOS_MAX_PATH_LENGTH` |
| `DataAddress` | type_alias | `payloads/Demon/include/common/Native.h:11125` | `typedef struct _RTL_HEAP_WALK_ENTRY { PVOID DataAddress;` |
| `DataLength` | type_alias | `payloads/Demon/include/common/Native.h:5843` | `typedef struct _PORT_MESSAGE { union { struct { CSHORT DataLength;` |
| `Database` | type_alias | `payloads/Demon/include/common/Native.h:10305` | `typedef struct _RTL_TRACE_ENUMERATE { PRTL_TRACE_DATABASE Database;` |
| `DeleteFile` | type_alias | `payloads/Demon/include/common/Native.h:4039` | `typedef struct _FILE_DISPOSITION_INFORMATION { // ntddk nthal BOOLEAN DeleteFile;` |
| `DestinationFile` | type_alias | `payloads/Demon/include/common/Native.h:4080` | `typedef struct _FILE_TRACKING_INFORMATION { HANDLE DestinationFile;` |
| `DirectoryCount` | type_alias | `payloads/Demon/include/common/Native.h:1543` | `typedef struct _FILE_QUERY_ON_DISK_VOL_INFO_BUFFER { LARGE_INTEGER DirectoryCount;` |
| `DirectoryHandle` | type_alias | `payloads/Demon/include/common/Native.h:7128` | `typedef struct _PROCESS_DEVICEMAP_INFORMATION { union { struct { HANDLE DirectoryHandle;` |
| `DirectoryHandle` | type_alias | `payloads/Demon/include/common/Native.h:7139` | `typedef struct _PROCESS_DEVICEMAP_INFORMATION_EX { union { struct { HANDLE DirectoryHandle;` |
| `Disable` | type_alias | `payloads/Demon/include/common/Native.h:1530` | `typedef struct _FILE_SET_DEFECT_MGMT_BUFFER { BOOLEAN Disable;` |
| `DomainName` | type_alias | `payloads/Demon/include/common/Native.h:8563` | `typedef struct _POLICY_ACCOUNT_DOMAIN_INFO { LSA_UNICODE_STRING DomainName;` |
| `DosPath` | type_alias | `payloads/Demon/include/common/Native.h:5332` | `typedef struct _CURDIR { UNICODE_STRING DosPath;` |
| `DosPath` | type_alias | `payloads/Demon/include/common/Native.h:5488` | `typedef struct _CURDIR32 { UNICODE_STRING32 DosPath;` |
| `DriverName` | type_alias | `payloads/Demon/include/common/Native.h:4292` | `typedef struct _SYSTEM_GDI_DRIVER_INFORMATION { UNICODE_STRING DriverName;` |
| `EFI_DRIVER_ENTRY_VERSION` | macro | `payloads/Demon/include/common/Native.h:9869` | `#define EFI_DRIVER_ENTRY_VERSION` |
| `ENCRYPTED_DATA_INFO_SPARSE_FILE` | macro | `payloads/Demon/include/common/Native.h:2403` | `#define ENCRYPTED_DATA_INFO_SPARSE_FILE` |
| `ENCRYPTION_FORMAT_DEFAULT` | macro | `payloads/Demon/include/common/Native.h:1462` | `#define ENCRYPTION_FORMAT_DEFAULT` |
| `EVENT_ACTIVITY_CTRL_CREATE_ID` | macro | `payloads/Demon/include/common/Native.h:11491` | `#define EVENT_ACTIVITY_CTRL_CREATE_ID` |
| `EVENT_ACTIVITY_CTRL_CREATE_SET_ID` | macro | `payloads/Demon/include/common/Native.h:11493` | `#define EVENT_ACTIVITY_CTRL_CREATE_SET_ID` |
| `EVENT_ACTIVITY_CTRL_GET_ID` | macro | `payloads/Demon/include/common/Native.h:11489` | `#define EVENT_ACTIVITY_CTRL_GET_ID` |
| `EVENT_ACTIVITY_CTRL_GET_SET_ID` | macro | `payloads/Demon/include/common/Native.h:11492` | `#define EVENT_ACTIVITY_CTRL_GET_SET_ID` |
| `EVENT_ACTIVITY_CTRL_SET_ID` | macro | `payloads/Demon/include/common/Native.h:11490` | `#define EVENT_ACTIVITY_CTRL_SET_ID` |
| `EVENT_MAX_LEVEL` | macro | `payloads/Demon/include/common/Native.h:11487` | `#define EVENT_MAX_LEVEL` |
| `EVENT_MIN_LEVEL` | macro | `payloads/Demon/include/common/Native.h:11486` | `#define EVENT_MIN_LEVEL` |
| `EXCEPTION_CHAIN_END` | macro | `payloads/Demon/include/common/Native.h:7517` | `#define EXCEPTION_CHAIN_END` |
| `EXPORT_FN` | macro | `payloads/Demon/include/common/Native.h:49` | `#define EXPORT_FN` |
| `EXPORT_SIZE` | macro | `payloads/Demon/include/common/Native.h:698` | `#define EXPORT_SIZE(x)` |
| `EXPORT_VA` | macro | `payloads/Demon/include/common/Native.h:693` | `#define EXPORT_VA(x)` |
| `EXTERNAL` | macro | `payloads/Demon/include/common/Native.h:54` | `#define EXTERNAL` |
| `EaSize` | type_alias | `payloads/Demon/include/common/Native.h:3974` | `typedef struct _FILE_EA_INFORMATION { ULONG EaSize;` |
| `EnabledFeatures` | type_alias | `payloads/Demon/include/common/Native.h:10678` | `typedef struct _XSTATE_CONFIGURATION { // Mask of enabled features DWORD64 EnabledFeatures;` |
| `EncryptionOperation` | type_alias | `payloads/Demon/include/common/Native.h:1441` | `typedef struct _ENCRYPTION_BUFFER { ULONG EncryptionOperation;` |
| `EndOfFile` | type_alias | `payloads/Demon/include/common/Native.h:4044` | `typedef struct _FILE_END_OF_FILE_INFORMATION { // ntddk nthal LARGE_INTEGER EndOfFile;` |
| `Entries` | type_alias | `payloads/Demon/include/common/Native.h:8543` | `typedef struct _LSA_REFERENCED_DOMAIN_LIST { ULONG Entries;` |
| `Entries` | type_alias | `payloads/Demon/include/common/Native.h:9160` | `typedef struct _TRUSTED_CONTROLLERS_INFO { ULONG Entries;` |
| `Entry` | type_alias | `payloads/Demon/include/common/Native.h:10517` | `typedef struct _HEAP { HEAP_ENTRY Entry;` |
| `Entry` | type_alias | `payloads/Demon/include/common/Native.h:10588` | `typedef struct _HEAP_VIRTUAL_ALLOC_ENTRY { LIST_ENTRY Entry;` |
| `EventGuid` | type_alias | `payloads/Demon/include/common/Native.h:3557` | `typedef struct _PLUGPLAY_EVENT_BLOCK { // // Common event data // GUID EventGuid;` |
| `ExceptionCode` | type_alias | `payloads/Demon/include/common/Native.h:7449` | `typedef struct _EXCEPTION_RECORD { DWORD ExceptionCode;` |
| `ExceptionCode` | type_alias | `payloads/Demon/include/common/Native.h:7465` | `typedef struct _EXCEPTION_RECORD32 { DWORD ExceptionCode;` |
| `ExceptionCode` | type_alias | `payloads/Demon/include/common/Native.h:7474` | `typedef struct _EXCEPTION_RECORD64 { DWORD ExceptionCode;` |
| `ExceptionList` | type_alias | `payloads/Demon/include/common/Native.h:5655` | `typedef struct _NT_TIB32 { DWORD ExceptionList;` |
| `ExceptionList` | type_alias | `payloads/Demon/include/common/Native.h:5667` | `typedef struct _NT_TIB64 { DWORD64 ExceptionList;` |
| `ExceptionRecord` | type_alias | `payloads/Demon/include/common/Native.h:7488` | `typedef struct _EXCEPTION_POINTERS { PEXCEPTION_RECORD ExceptionRecord;` |
| `ExceptionRecord` | type_alias | `payloads/Demon/include/common/Native.h:10976` | `typedef struct _DBGKM_EXCEPTION { EXCEPTION_RECORD ExceptionRecord;` |
| `ExitStatus` | type_alias | `payloads/Demon/include/common/Native.h:7112` | `typedef struct _THREAD_BASIC_INFORMATION { NTSTATUS ExitStatus;` |
| `ExitStatus` | type_alias | `payloads/Demon/include/common/Native.h:7153` | `typedef struct _PROCESS_BASIC_INFORMATION { NTSTATUS ExitStatus;` |
| `ExitStatus` | type_alias | `payloads/Demon/include/common/Native.h:10998` | `typedef struct _DBGKM_EXIT_THREAD { NTSTATUS ExitStatus;` |
| `ExitStatus` | type_alias | `payloads/Demon/include/common/Native.h:11003` | `typedef struct _DBGKM_EXIT_PROCESS { NTSTATUS ExitStatus;` |
| `ExpectedVersion` | type_alias | `payloads/Demon/include/common/Native.h:6022` | `typedef struct _BASESRV_API_CONNECTINFO { ULONG ExpectedVersion;` |
| `ExtendedCode` | type_alias | `payloads/Demon/include/common/Native.h:2404` | `typedef struct _EXTENDED_ENCRYPTED_DATA_INFO { ULONG ExtendedCode;` |
| `ExtentCount` | type_alias | `payloads/Demon/include/common/Native.h:970` | `typedef struct RETRIEVAL_POINTERS_BUFFER { ULONG ExtentCount;` |
| `FIELD_OFFSET` | macro | `payloads/Demon/include/common/Native.h:449` | `#define FIELD_OFFSET(type, field)` |
| `FILESYSTEM_STATISTICS_TYPE_EXFAT` | macro | `payloads/Demon/include/common/Native.h:1253` | `#define FILESYSTEM_STATISTICS_TYPE_EXFAT` |
| `FILESYSTEM_STATISTICS_TYPE_FAT` | macro | `payloads/Demon/include/common/Native.h:1252` | `#define FILESYSTEM_STATISTICS_TYPE_FAT` |
| `FILESYSTEM_STATISTICS_TYPE_NTFS` | macro | `payloads/Demon/include/common/Native.h:1251` | `#define FILESYSTEM_STATISTICS_TYPE_NTFS` |
| `FILE_CLEAR_ENCRYPTION` | macro | `payloads/Demon/include/common/Native.h:1450` | `#define FILE_CLEAR_ENCRYPTION` |
| `FILE_COMPLETE_IF_OPLOCKED` | macro | `payloads/Demon/include/common/Native.h:3251` | `#define FILE_COMPLETE_IF_OPLOCKED` |
| `FILE_COPY_STRUCTURED_STORAGE` | macro | `payloads/Demon/include/common/Native.h:3267` | `#define FILE_COPY_STRUCTURED_STORAGE` |
| `FILE_CREATE` | macro | `payloads/Demon/include/common/Native.h:3235` | `#define FILE_CREATE` |
| `FILE_CREATE_TREE_CONNECTION` | macro | `payloads/Demon/include/common/Native.h:3249` | `#define FILE_CREATE_TREE_CONNECTION` |
| `FILE_DELETE_ON_CLOSE` | macro | `payloads/Demon/include/common/Native.h:3256` | `#define FILE_DELETE_ON_CLOSE` |
| `FILE_DIRECTORY_FILE` | macro | `payloads/Demon/include/common/Native.h:3241` | `#define FILE_DIRECTORY_FILE` |
| `FILE_MAXIMUM_DISPOSITION` | macro | `payloads/Demon/include/common/Native.h:3239` | `#define FILE_MAXIMUM_DISPOSITION` |
| `FILE_NON_DIRECTORY_FILE` | macro | `payloads/Demon/include/common/Native.h:3248` | `#define FILE_NON_DIRECTORY_FILE` |
| `FILE_NO_COMPRESSION` | macro | `payloads/Demon/include/common/Native.h:3259` | `#define FILE_NO_COMPRESSION` |
| `FILE_NO_EA_KNOWLEDGE` | macro | `payloads/Demon/include/common/Native.h:3252` | `#define FILE_NO_EA_KNOWLEDGE` |
| `FILE_NO_INTERMEDIATE_BUFFERING` | macro | `payloads/Demon/include/common/Native.h:3244` | `#define FILE_NO_INTERMEDIATE_BUFFERING` |
| `FILE_OPEN` | macro | `payloads/Demon/include/common/Native.h:3234` | `#define FILE_OPEN` |
| `FILE_OPEN_BY_FILE_ID` | macro | `payloads/Demon/include/common/Native.h:3257` | `#define FILE_OPEN_BY_FILE_ID` |
| `FILE_OPEN_FOR_BACKUP_INTENT` | macro | `payloads/Demon/include/common/Native.h:3258` | `#define FILE_OPEN_FOR_BACKUP_INTENT` |
| `FILE_OPEN_FOR_FREE_SPACE_QUERY` | macro | `payloads/Demon/include/common/Native.h:3264` | `#define FILE_OPEN_FOR_FREE_SPACE_QUERY` |
| `FILE_OPEN_FOR_RECOVERY` | macro | `payloads/Demon/include/common/Native.h:3253` | `#define FILE_OPEN_FOR_RECOVERY` |
| `FILE_OPEN_IF` | macro | `payloads/Demon/include/common/Native.h:3236` | `#define FILE_OPEN_IF` |
| `FILE_OPEN_NO_RECALL` | macro | `payloads/Demon/include/common/Native.h:3263` | `#define FILE_OPEN_NO_RECALL` |
| `FILE_OPEN_REPARSE_POINT` | macro | `payloads/Demon/include/common/Native.h:3262` | `#define FILE_OPEN_REPARSE_POINT` |
| `FILE_OVERWRITE` | macro | `payloads/Demon/include/common/Native.h:3237` | `#define FILE_OVERWRITE` |
| `FILE_OVERWRITE_IF` | macro | `payloads/Demon/include/common/Native.h:3238` | `#define FILE_OVERWRITE_IF` |
| `FILE_PATH_TYPE_ARC` | macro | `payloads/Demon/include/common/Native.h:7561` | `#define FILE_PATH_TYPE_ARC` |
| `FILE_PATH_TYPE_ARC_SIGNATURE` | macro | `payloads/Demon/include/common/Native.h:7562` | `#define FILE_PATH_TYPE_ARC_SIGNATURE` |
| `FILE_PATH_TYPE_EFI` | macro | `payloads/Demon/include/common/Native.h:7564` | `#define FILE_PATH_TYPE_EFI` |
| `FILE_PATH_TYPE_MAX` | macro | `payloads/Demon/include/common/Native.h:7567` | `#define FILE_PATH_TYPE_MAX` |
| `FILE_PATH_TYPE_MIN` | macro | `payloads/Demon/include/common/Native.h:7566` | `#define FILE_PATH_TYPE_MIN` |
| `FILE_PATH_TYPE_NT` | macro | `payloads/Demon/include/common/Native.h:7563` | `#define FILE_PATH_TYPE_NT` |
| `FILE_PATH_VERSION` | macro | `payloads/Demon/include/common/Native.h:7559` | `#define FILE_PATH_VERSION` |
| `FILE_PREFETCH_TYPE_FOR_CREATE` | macro | `payloads/Demon/include/common/Native.h:1218` | `#define FILE_PREFETCH_TYPE_FOR_CREATE` |
| `FILE_PREFETCH_TYPE_FOR_CREATE_EX` | macro | `payloads/Demon/include/common/Native.h:1220` | `#define FILE_PREFETCH_TYPE_FOR_CREATE_EX` |
| `FILE_PREFETCH_TYPE_FOR_DIRENUM` | macro | `payloads/Demon/include/common/Native.h:1219` | `#define FILE_PREFETCH_TYPE_FOR_DIRENUM` |
| `FILE_PREFETCH_TYPE_FOR_DIRENUM_EX` | macro | `payloads/Demon/include/common/Native.h:1221` | `#define FILE_PREFETCH_TYPE_FOR_DIRENUM_EX` |
| `FILE_PREFETCH_TYPE_MAX` | macro | `payloads/Demon/include/common/Native.h:1223` | `#define FILE_PREFETCH_TYPE_MAX` |
| `FILE_RANDOM_ACCESS` | macro | `payloads/Demon/include/common/Native.h:3254` | `#define FILE_RANDOM_ACCESS` |
| `FILE_READ_ACCESS` | macro | `payloads/Demon/include/common/Native.h:2947` | `#define FILE_READ_ACCESS` |
| `FILE_RESERVE_OPFILTER` | macro | `payloads/Demon/include/common/Native.h:3261` | `#define FILE_RESERVE_OPFILTER` |
| `FILE_SEQUENTIAL_ONLY` | macro | `payloads/Demon/include/common/Native.h:3243` | `#define FILE_SEQUENTIAL_ONLY` |
| `FILE_SET_ENCRYPTION` | macro | `payloads/Demon/include/common/Native.h:1449` | `#define FILE_SET_ENCRYPTION` |
| `FILE_STRUCTURED_STORAGE` | macro | `payloads/Demon/include/common/Native.h:3268` | `#define FILE_STRUCTURED_STORAGE` |
| `FILE_SUPERSEDE` | macro | `payloads/Demon/include/common/Native.h:3233` | `#define FILE_SUPERSEDE` |
| `FILE_SYNCHRONOUS_IO_ALERT` | macro | `payloads/Demon/include/common/Native.h:3246` | `#define FILE_SYNCHRONOUS_IO_ALERT` |
| `FILE_SYNCHRONOUS_IO_NONALERT` | macro | `payloads/Demon/include/common/Native.h:3247` | `#define FILE_SYNCHRONOUS_IO_NONALERT` |
| `FILE_TYPE_NOTIFICATION_FLAG_USAGE_BEGIN` | macro | `payloads/Demon/include/common/Native.h:2453` | `#define FILE_TYPE_NOTIFICATION_FLAG_USAGE_BEGIN` |
| `FILE_TYPE_NOTIFICATION_FLAG_USAGE_END` | macro | `payloads/Demon/include/common/Native.h:2454` | `#define FILE_TYPE_NOTIFICATION_FLAG_USAGE_END` |
| `FILE_VALID_MAILSLOT_OPTION_FLAGS` | macro | `payloads/Demon/include/common/Native.h:3272` | `#define FILE_VALID_MAILSLOT_OPTION_FLAGS` |
| `FILE_VALID_OPTION_FLAGS` | macro | `payloads/Demon/include/common/Native.h:3270` | `#define FILE_VALID_OPTION_FLAGS` |
| `FILE_VALID_PIPE_OPTION_FLAGS` | macro | `payloads/Demon/include/common/Native.h:3271` | `#define FILE_VALID_PIPE_OPTION_FLAGS` |
| `FILE_VALID_SET_FLAGS` | macro | `payloads/Demon/include/common/Native.h:3273` | `#define FILE_VALID_SET_FLAGS` |
| `FILE_WRITE_THROUGH` | macro | `payloads/Demon/include/common/Native.h:3242` | `#define FILE_WRITE_THROUGH` |
| `FIRSTBYTE` | macro | `payloads/Demon/include/common/Native.h:126` | `#define FIRSTBYTE(VALUE)` |
| `FLG_HOTPATCH_ACTIVE` | macro | `payloads/Demon/include/common/Native.h:5089` | `#define FLG_HOTPATCH_ACTIVE` |
| `FLG_HOTPATCH_KERNEL` | macro | `payloads/Demon/include/common/Native.h:5082` | `#define FLG_HOTPATCH_KERNEL` |
| `FLG_HOTPATCH_MAP_ATOMIC_SWAP` | macro | `payloads/Demon/include/common/Native.h:5086` | `#define FLG_HOTPATCH_MAP_ATOMIC_SWAP` |
| `FLG_HOTPATCH_NAME_INFO` | macro | `payloads/Demon/include/common/Native.h:5084` | `#define FLG_HOTPATCH_NAME_INFO` |
| `FLG_HOTPATCH_RELOAD_NTDLL` | macro | `payloads/Demon/include/common/Native.h:5083` | `#define FLG_HOTPATCH_RELOAD_NTDLL` |
| `FLG_HOTPATCH_RENAME_INFO` | macro | `payloads/Demon/include/common/Native.h:5085` | `#define FLG_HOTPATCH_RENAME_INFO` |
| `FLG_HOTPATCH_STATUS_FLAGS` | macro | `payloads/Demon/include/common/Native.h:5090` | `#define FLG_HOTPATCH_STATUS_FLAGS` |
| `FLG_HOTPATCH_VERIFICATION_ERROR` | macro | `payloads/Demon/include/common/Native.h:5092` | `#define FLG_HOTPATCH_VERIFICATION_ERROR` |
| `FLG_HOTPATCH_WOW64` | macro | `payloads/Demon/include/common/Native.h:5087` | `#define FLG_HOTPATCH_WOW64` |
| `FLS_MAXIMUM_AVAILABLE` | macro | `payloads/Demon/include/common/Native.h:5326` | `#define FLS_MAXIMUM_AVAILABLE` |
| `FOREGROUND_BASE_PRIORITY` | macro | `payloads/Demon/include/common/Native.h:2943` | `#define FOREGROUND_BASE_PRIORITY` |
| `FOURTHBYTE` | macro | `payloads/Demon/include/common/Native.h:129` | `#define FOURTHBYTE(VALUE)` |
| `FSCTL_ALLOW_EXTENDED_DASD_IO` | macro | `payloads/Demon/include/common/Native.h:748` | `#define FSCTL_ALLOW_EXTENDED_DASD_IO` |
| `FSCTL_CREATE_OR_GET_OBJECT_ID` | macro | `payloads/Demon/include/common/Native.h:767` | `#define FSCTL_CREATE_OR_GET_OBJECT_ID` |
| `FSCTL_CREATE_USN_JOURNAL` | macro | `payloads/Demon/include/common/Native.h:777` | `#define FSCTL_CREATE_USN_JOURNAL` |
| `FSCTL_CSC_INTERNAL` | macro | `payloads/Demon/include/common/Native.h:827` | `#define FSCTL_CSC_INTERNAL` |
| `FSCTL_CSV_GET_VOLUME_NAME_FOR_VOLUME_MOUNT_POINT` | macro | `payloads/Demon/include/common/Native.h:877` | `#define FSCTL_CSV_GET_VOLUME_NAME_FOR_VOLUME_MOUNT_POINT` |
| `FSCTL_CSV_GET_VOLUME_PATH_NAME` | macro | `payloads/Demon/include/common/Native.h:876` | `#define FSCTL_CSV_GET_VOLUME_PATH_NAME` |
| `FSCTL_CSV_GET_VOLUME_PATH_NAMES_FOR_VOLUME_NAME` | macro | `payloads/Demon/include/common/Native.h:878` | `#define FSCTL_CSV_GET_VOLUME_PATH_NAMES_FOR_VOLUME_NAME` |
| `FSCTL_CSV_TUNNEL_REQUEST` | macro | `payloads/Demon/include/common/Native.h:872` | `#define FSCTL_CSV_TUNNEL_REQUEST` |
| `FSCTL_DELETE_OBJECT_ID` | macro | `payloads/Demon/include/common/Native.h:759` | `#define FSCTL_DELETE_OBJECT_ID` |
| `FSCTL_DELETE_REPARSE_POINT` | macro | `payloads/Demon/include/common/Native.h:762` | `#define FSCTL_DELETE_REPARSE_POINT` |
| `FSCTL_DELETE_USN_JOURNAL` | macro | `payloads/Demon/include/common/Native.h:782` | `#define FSCTL_DELETE_USN_JOURNAL` |
| `FSCTL_DFSR_SET_GHOST_HANDLE_STATE` | macro | `payloads/Demon/include/common/Native.h:830` | `#define FSCTL_DFSR_SET_GHOST_HANDLE_STATE` |
| `FSCTL_DISMOUNT_VOLUME` | macro | `payloads/Demon/include/common/Native.h:722` | `#define FSCTL_DISMOUNT_VOLUME` |
| `FSCTL_ENABLE_UPGRADE` | macro | `payloads/Demon/include/common/Native.h:771` | `#define FSCTL_ENABLE_UPGRADE` |
| `FSCTL_ENCRYPTION_FSCTL_IO` | macro | `payloads/Demon/include/common/Native.h:774` | `#define FSCTL_ENCRYPTION_FSCTL_IO` |
| `FSCTL_ENUM_USN_DATA` | macro | `payloads/Demon/include/common/Native.h:763` | `#define FSCTL_ENUM_USN_DATA` |
| `FSCTL_EXTEND_VOLUME` | macro | `payloads/Demon/include/common/Native.h:780` | `#define FSCTL_EXTEND_VOLUME` |
| `FSCTL_FILESYSTEM_GET_STATISTICS` | macro | `payloads/Demon/include/common/Native.h:738` | `#define FSCTL_FILESYSTEM_GET_STATISTICS` |
| `FSCTL_FILE_PREFETCH` | macro | `payloads/Demon/include/common/Native.h:792` | `#define FSCTL_FILE_PREFETCH` |
| `FSCTL_FILE_TYPE_NOTIFICATION` | macro | `payloads/Demon/include/common/Native.h:858` | `#define FSCTL_FILE_TYPE_NOTIFICATION` |
| `FSCTL_FIND_FILES_BY_SID` | macro | `payloads/Demon/include/common/Native.h:754` | `#define FSCTL_FIND_FILES_BY_SID` |
| `FSCTL_GET_BOOT_AREA_INFO` | macro | `payloads/Demon/include/common/Native.h:865` | `#define FSCTL_GET_BOOT_AREA_INFO` |
| `FSCTL_GET_COMPRESSION` | macro | `payloads/Demon/include/common/Native.h:729` | `#define FSCTL_GET_COMPRESSION` |
| `FSCTL_GET_NTFS_FILE_RECORD` | macro | `payloads/Demon/include/common/Native.h:742` | `#define FSCTL_GET_NTFS_FILE_RECORD` |
| `FSCTL_GET_NTFS_VOLUME_DATA` | macro | `payloads/Demon/include/common/Native.h:741` | `#define FSCTL_GET_NTFS_VOLUME_DATA` |
| `FSCTL_GET_OBJECT_ID` | macro | `payloads/Demon/include/common/Native.h:758` | `#define FSCTL_GET_OBJECT_ID` |
| `FSCTL_GET_REPAIR` | macro | `payloads/Demon/include/common/Native.h:823` | `#define FSCTL_GET_REPAIR` |
| `FSCTL_GET_REPARSE_POINT` | macro | `payloads/Demon/include/common/Native.h:761` | `#define FSCTL_GET_REPARSE_POINT` |
| `FSCTL_GET_RETRIEVAL_POINTERS` | macro | `payloads/Demon/include/common/Native.h:744` | `#define FSCTL_GET_RETRIEVAL_POINTERS` |
| `FSCTL_GET_RETRIEVAL_POINTER_BASE` | macro | `payloads/Demon/include/common/Native.h:866` | `#define FSCTL_GET_RETRIEVAL_POINTER_BASE` |
| `FSCTL_GET_VOLUME_BITMAP` | macro | `payloads/Demon/include/common/Native.h:743` | `#define FSCTL_GET_VOLUME_BITMAP` |
| `FSCTL_INITIATE_REPAIR` | macro | `payloads/Demon/include/common/Native.h:826` | `#define FSCTL_INITIATE_REPAIR` |
| `FSCTL_INVALIDATE_VOLUMES` | macro | `payloads/Demon/include/common/Native.h:735` | `#define FSCTL_INVALIDATE_VOLUMES` |
| `FSCTL_IS_CSV_FILE` | macro | `payloads/Demon/include/common/Native.h:873` | `#define FSCTL_IS_CSV_FILE` |
| `FSCTL_IS_FILE_ON_CSV_VOLUME` | macro | `payloads/Demon/include/common/Native.h:879` | `#define FSCTL_IS_FILE_ON_CSV_VOLUME` |
| `FSCTL_IS_PATHNAME_VALID` | macro | `payloads/Demon/include/common/Native.h:725` | `#define FSCTL_IS_PATHNAME_VALID` |
| `FSCTL_IS_VOLUME_DIRTY` | macro | `payloads/Demon/include/common/Native.h:746` | `#define FSCTL_IS_VOLUME_DIRTY` |
| `FSCTL_IS_VOLUME_MOUNTED` | macro | `payloads/Demon/include/common/Native.h:724` | `#define FSCTL_IS_VOLUME_MOUNTED` |
| `FSCTL_LOCK_VOLUME` | macro | `payloads/Demon/include/common/Native.h:720` | `#define FSCTL_LOCK_VOLUME` |
| `FSCTL_LOOKUP_STREAM_FROM_CLUSTER` | macro | `payloads/Demon/include/common/Native.h:856` | `#define FSCTL_LOOKUP_STREAM_FROM_CLUSTER` |
| `FSCTL_MAKE_MEDIA_COMPATIBLE` | macro | `payloads/Demon/include/common/Native.h:796` | `#define FSCTL_MAKE_MEDIA_COMPATIBLE` |
| `FSCTL_MARK_AS_SYSTEM_HIVE` | macro | `payloads/Demon/include/common/Native.h:883` | `#define FSCTL_MARK_AS_SYSTEM_HIVE` |
| `FSCTL_MARK_HANDLE` | macro | `payloads/Demon/include/common/Native.h:783` | `#define FSCTL_MARK_HANDLE` |
| `FSCTL_MARK_VOLUME_DIRTY` | macro | `payloads/Demon/include/common/Native.h:726` | `#define FSCTL_MARK_VOLUME_DIRTY` |
| `FSCTL_MOVE_FILE` | macro | `payloads/Demon/include/common/Native.h:745` | `#define FSCTL_MOVE_FILE` |
| `FSCTL_OPBATCH_ACK_CLOSE_PENDING` | macro | `payloads/Demon/include/common/Native.h:718` | `#define FSCTL_OPBATCH_ACK_CLOSE_PENDING` |
| `FSCTL_OPLOCK_BREAK_ACKNOWLEDGE` | macro | `payloads/Demon/include/common/Native.h:717` | `#define FSCTL_OPLOCK_BREAK_ACKNOWLEDGE` |
| `FSCTL_OPLOCK_BREAK_ACK_NO_2` | macro | `payloads/Demon/include/common/Native.h:734` | `#define FSCTL_OPLOCK_BREAK_ACK_NO_2` |
| `FSCTL_OPLOCK_BREAK_NOTIFY` | macro | `payloads/Demon/include/common/Native.h:719` | `#define FSCTL_OPLOCK_BREAK_NOTIFY` |
| `FSCTL_QUERY_ALLOCATED_RANGES` | macro | `payloads/Demon/include/common/Native.h:770` | `#define FSCTL_QUERY_ALLOCATED_RANGES` |
| `FSCTL_QUERY_DEPENDENT_VOLUME` | macro | `payloads/Demon/include/common/Native.h:847` | `#define FSCTL_QUERY_DEPENDENT_VOLUME` |
| `FSCTL_QUERY_FAT_BPB` | macro | `payloads/Demon/include/common/Native.h:736` | `#define FSCTL_QUERY_FAT_BPB` |
| `FSCTL_QUERY_FILE_SYSTEM_RECOGNITION` | macro | `payloads/Demon/include/common/Native.h:875` | `#define FSCTL_QUERY_FILE_SYSTEM_RECOGNITION` |
| `FSCTL_QUERY_ON_DISK_VOLUME_INFO` | macro | `payloads/Demon/include/common/Native.h:799` | `#define FSCTL_QUERY_ON_DISK_VOLUME_INFO` |
| `FSCTL_QUERY_PAGEFILE_ENCRYPTION` | macro | `payloads/Demon/include/common/Native.h:839` | `#define FSCTL_QUERY_PAGEFILE_ENCRYPTION` |
| `FSCTL_QUERY_PERSISTENT_VOLUME_STATE` | macro | `payloads/Demon/include/common/Native.h:868` | `#define FSCTL_QUERY_PERSISTENT_VOLUME_STATE` |
| `FSCTL_QUERY_RETRIEVAL_POINTERS` | macro | `payloads/Demon/include/common/Native.h:728` | `#define FSCTL_QUERY_RETRIEVAL_POINTERS` |
| `FSCTL_QUERY_SPARING_INFO` | macro | `payloads/Demon/include/common/Native.h:798` | `#define FSCTL_QUERY_SPARING_INFO` |
| `FSCTL_QUERY_USN_JOURNAL` | macro | `payloads/Demon/include/common/Native.h:781` | `#define FSCTL_QUERY_USN_JOURNAL` |
| `FSCTL_READ_FILE_USN_DATA` | macro | `payloads/Demon/include/common/Native.h:778` | `#define FSCTL_READ_FILE_USN_DATA` |
| `FSCTL_READ_FROM_PLEX` | macro | `payloads/Demon/include/common/Native.h:791` | `#define FSCTL_READ_FROM_PLEX` |
| `FSCTL_READ_RAW_ENCRYPTED` | macro | `payloads/Demon/include/common/Native.h:776` | `#define FSCTL_READ_RAW_ENCRYPTED` |
| `FSCTL_READ_USN_JOURNAL` | macro | `payloads/Demon/include/common/Native.h:765` | `#define FSCTL_READ_USN_JOURNAL` |
| `FSCTL_RECALL_FILE` | macro | `payloads/Demon/include/common/Native.h:789` | `#define FSCTL_RECALL_FILE` |
| `FSCTL_REQUEST_BATCH_OPLOCK` | macro | `payloads/Demon/include/common/Native.h:716` | `#define FSCTL_REQUEST_BATCH_OPLOCK` |
| `FSCTL_REQUEST_FILTER_OPLOCK` | macro | `payloads/Demon/include/common/Native.h:737` | `#define FSCTL_REQUEST_FILTER_OPLOCK` |
| `FSCTL_REQUEST_OPLOCK` | macro | `payloads/Demon/include/common/Native.h:870` | `#define FSCTL_REQUEST_OPLOCK` |
| `FSCTL_REQUEST_OPLOCK_LEVEL_1` | macro | `payloads/Demon/include/common/Native.h:714` | `#define FSCTL_REQUEST_OPLOCK_LEVEL_1` |
| `FSCTL_REQUEST_OPLOCK_LEVEL_2` | macro | `payloads/Demon/include/common/Native.h:715` | `#define FSCTL_REQUEST_OPLOCK_LEVEL_2` |
| `FSCTL_RESET_VOLUME_ALLOCATION_HINTS` | macro | `payloads/Demon/include/common/Native.h:843` | `#define FSCTL_RESET_VOLUME_ALLOCATION_HINTS` |
| `FSCTL_SD_GLOBAL_CHANGE` | macro | `payloads/Demon/include/common/Native.h:848` | `#define FSCTL_SD_GLOBAL_CHANGE` |
| `FSCTL_SECURITY_ID_CHECK` | macro | `payloads/Demon/include/common/Native.h:764` | `#define FSCTL_SECURITY_ID_CHECK` |
| `FSCTL_SET_BOOTLOADER_ACCESSED` | macro | `payloads/Demon/include/common/Native.h:733` | `#define FSCTL_SET_BOOTLOADER_ACCESSED` |
| `FSCTL_SET_COMPRESSION` | macro | `payloads/Demon/include/common/Native.h:730` | `#define FSCTL_SET_COMPRESSION` |
| `FSCTL_SET_DEFECT_MANAGEMENT` | macro | `payloads/Demon/include/common/Native.h:797` | `#define FSCTL_SET_DEFECT_MANAGEMENT` |
| `FSCTL_SET_ENCRYPTION` | macro | `payloads/Demon/include/common/Native.h:773` | `#define FSCTL_SET_ENCRYPTION` |
| `FSCTL_SET_OBJECT_ID` | macro | `payloads/Demon/include/common/Native.h:757` | `#define FSCTL_SET_OBJECT_ID` |
| `FSCTL_SET_OBJECT_ID_EXTENDED` | macro | `payloads/Demon/include/common/Native.h:766` | `#define FSCTL_SET_OBJECT_ID_EXTENDED` |
| `FSCTL_SET_PERSISTENT_VOLUME_STATE` | macro | `payloads/Demon/include/common/Native.h:867` | `#define FSCTL_SET_PERSISTENT_VOLUME_STATE` |
| `FSCTL_SET_REPAIR` | macro | `payloads/Demon/include/common/Native.h:822` | `#define FSCTL_SET_REPAIR` |
| `FSCTL_SET_REPARSE_POINT` | macro | `payloads/Demon/include/common/Native.h:760` | `#define FSCTL_SET_REPARSE_POINT` |
| `FSCTL_SET_SHORT_NAME_BEHAVIOR` | macro | `payloads/Demon/include/common/Native.h:829` | `#define FSCTL_SET_SHORT_NAME_BEHAVIOR` |
| `FSCTL_SET_SPARSE` | macro | `payloads/Demon/include/common/Native.h:768` | `#define FSCTL_SET_SPARSE` |
| `FSCTL_SET_VOLUME_COMPRESSION_STATE` | macro | `payloads/Demon/include/common/Native.h:800` | `#define FSCTL_SET_VOLUME_COMPRESSION_STATE` |
| `FSCTL_SET_ZERO_DATA` | macro | `payloads/Demon/include/common/Native.h:769` | `#define FSCTL_SET_ZERO_DATA` |
| `FSCTL_SET_ZERO_ON_DEALLOCATION` | macro | `payloads/Demon/include/common/Native.h:821` | `#define FSCTL_SET_ZERO_ON_DEALLOCATION` |
| `FSCTL_SHRINK_VOLUME` | macro | `payloads/Demon/include/common/Native.h:828` | `#define FSCTL_SHRINK_VOLUME` |
| `FSCTL_SIS_COPYFILE` | macro | `payloads/Demon/include/common/Native.h:784` | `#define FSCTL_SIS_COPYFILE` |
| `FSCTL_SIS_LINK_FILES` | macro | `payloads/Demon/include/common/Native.h:785` | `#define FSCTL_SIS_LINK_FILES` |
| `FSCTL_TXFS_CREATE_MINIVERSION` | macro | `payloads/Demon/include/common/Native.h:816` | `#define FSCTL_TXFS_CREATE_MINIVERSION` |
| `FSCTL_TXFS_CREATE_SECONDARY_RM` | macro | `payloads/Demon/include/common/Native.h:811` | `#define FSCTL_TXFS_CREATE_SECONDARY_RM` |
| `FSCTL_TXFS_GET_METADATA_INFO` | macro | `payloads/Demon/include/common/Native.h:812` | `#define FSCTL_TXFS_GET_METADATA_INFO` |
| `FSCTL_TXFS_GET_TRANSACTED_VERSION` | macro | `payloads/Demon/include/common/Native.h:813` | `#define FSCTL_TXFS_GET_TRANSACTED_VERSION` |
| `FSCTL_TXFS_LIST_TRANSACTIONS` | macro | `payloads/Demon/include/common/Native.h:838` | `#define FSCTL_TXFS_LIST_TRANSACTIONS` |
| `FSCTL_TXFS_LIST_TRANSACTION_LOCKED_FILES` | macro | `payloads/Demon/include/common/Native.h:836` | `#define FSCTL_TXFS_LIST_TRANSACTION_LOCKED_FILES` |
| `FSCTL_TXFS_MODIFY_RM` | macro | `payloads/Demon/include/common/Native.h:802` | `#define FSCTL_TXFS_MODIFY_RM` |
| `FSCTL_TXFS_QUERY_RM_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:803` | `#define FSCTL_TXFS_QUERY_RM_INFORMATION` |
| `FSCTL_TXFS_READ_BACKUP_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:809` | `#define FSCTL_TXFS_READ_BACKUP_INFORMATION` |
| `FSCTL_TXFS_READ_BACKUP_INFORMATION2` | macro | `payloads/Demon/include/common/Native.h:852` | `#define FSCTL_TXFS_READ_BACKUP_INFORMATION2` |
| `FSCTL_TXFS_ROLLFORWARD_REDO` | macro | `payloads/Demon/include/common/Native.h:805` | `#define FSCTL_TXFS_ROLLFORWARD_REDO` |
| `FSCTL_TXFS_ROLLFORWARD_UNDO` | macro | `payloads/Demon/include/common/Native.h:806` | `#define FSCTL_TXFS_ROLLFORWARD_UNDO` |
| `FSCTL_TXFS_SAVEPOINT_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:815` | `#define FSCTL_TXFS_SAVEPOINT_INFORMATION` |
| `FSCTL_TXFS_SHUTDOWN_RM` | macro | `payloads/Demon/include/common/Native.h:808` | `#define FSCTL_TXFS_SHUTDOWN_RM` |
| `FSCTL_TXFS_START_RM` | macro | `payloads/Demon/include/common/Native.h:807` | `#define FSCTL_TXFS_START_RM` |
| `FSCTL_TXFS_TRANSACTION_ACTIVE` | macro | `payloads/Demon/include/common/Native.h:820` | `#define FSCTL_TXFS_TRANSACTION_ACTIVE` |
| `FSCTL_TXFS_WRITE_BACKUP_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:810` | `#define FSCTL_TXFS_WRITE_BACKUP_INFORMATION` |
| `FSCTL_TXFS_WRITE_BACKUP_INFORMATION2` | macro | `payloads/Demon/include/common/Native.h:857` | `#define FSCTL_TXFS_WRITE_BACKUP_INFORMATION2` |
| `FSCTL_UNLOCK_VOLUME` | macro | `payloads/Demon/include/common/Native.h:721` | `#define FSCTL_UNLOCK_VOLUME` |
| `FSCTL_WAIT_FOR_REPAIR` | macro | `payloads/Demon/include/common/Native.h:824` | `#define FSCTL_WAIT_FOR_REPAIR` |
| `FSCTL_WRITE_RAW_ENCRYPTED` | macro | `payloads/Demon/include/common/Native.h:775` | `#define FSCTL_WRITE_RAW_ENCRYPTED` |
| `FSCTL_WRITE_USN_CLOSE_RECORD` | macro | `payloads/Demon/include/common/Native.h:779` | `#define FSCTL_WRITE_USN_CLOSE_RECORD` |
| `File` | type_alias | `payloads/Demon/include/common/Native.h:6266` | `typedef struct _BASE_MSG_SXS_HANDLES { PVOID File;` |
| `FileAreaOffset` | type_alias | `payloads/Demon/include/common/Native.h:2205` | `typedef struct _RETRIEVAL_POINTER_BASE { LARGE_INTEGER FileAreaOffset;` |
| `FileAttributes` | type_alias | `payloads/Demon/include/common/Native.h:4022` | `typedef struct _FILE_ATTRIBUTE_TAG_INFORMATION { // ntddk nthal ULONG FileAttributes;` |
| `FileHandle` | type_alias | `payloads/Demon/include/common/Native.h:1021` | `typedef struct _MOVE_FILE_DATA32 { UINT32 FileHandle;` |
| `FileHandle` | type_alias | `payloads/Demon/include/common/Native.h:11008` | `typedef struct _DBGKM_LOAD_DLL { HANDLE FileHandle;` |
| `FileNameLength` | type_alias | `payloads/Demon/include/common/Native.h:3995` | `typedef struct _FILE_NAME_INFORMATION { // ntddk ULONG FileNameLength;` |
| `FileNames` | type_alias | `payloads/Demon/include/common/Native.h:5831` | `typedef struct _INIFILE_MAPPING { struct _INIFILE_MAPPING_FILENAME* FileNames;` |
| `FileOffset` | type_alias | `payloads/Demon/include/common/Native.h:1420` | `typedef struct _FILE_ZERO_DATA_INFORMATION { LARGE_INTEGER FileOffset;` |
| `FileOffset` | type_alias | `payloads/Demon/include/common/Native.h:1430` | `typedef struct _FILE_ALLOCATED_RANGE_BUFFER { LARGE_INTEGER FileOffset;` |
| `FileOffset` | type_alias | `payloads/Demon/include/common/Native.h:1465` | `typedef struct _REQUEST_RAW_ENCRYPTED_DATA { LONGLONG FileOffset;` |
| `FileReference` | type_alias | `payloads/Demon/include/common/Native.h:4126` | `typedef struct _FILE_REPARSE_POINT_INFORMATION { LONGLONG FileReference;` |
| `FileReference` | type_alias | `payloads/Demon/include/common/Native.h:4274` | `typedef struct _FILE_OBJECTID_INFORMATION { LONGLONG FileReference;` |
| `FileSystem` | type_alias | `payloads/Demon/include/common/Native.h:2219` | `typedef struct _FILE_SYSTEM_RECOGNITION_INFORMATION { CHAR FileSystem[9];` |
| `FileSystemType` | type_alias | `payloads/Demon/include/common/Native.h:1226` | `typedef struct _FILESYSTEM_STATISTICS { USHORT FileSystemType;` |
| `FileType` | type_alias | `payloads/Demon/include/common/Native.h:6344` | `typedef struct _BASE_MSG_SXS_STREAM { UCHAR FileType;` |
| `First0x24BytesOfBootSector` | type_alias | `payloads/Demon/include/common/Native.h:908` | `typedef struct _FSCTL_QUERY_FAT_BPB_BUFFER { UCHAR First0x24BytesOfBootSector[0x24];` |
| `FirstVDM` | type_alias | `payloads/Demon/include/common/Native.h:6283` | `typedef struct _BASE_IS_FIRST_VDM_MSG { __int32 FirstVDM;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:1627` | `typedef struct _TXFS_MODIFY_RM { // // TXFS_RM_FLAG_* flags // ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:1839` | `typedef struct _TXFS_START_RM_INFORMATION { // // TXFS_START_RM_FLAG_* flags. // ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:2348` | `typedef struct _SD_GLOBAL_CHANGE_INPUT { // // Input flags (none currently defined) // ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:2370` | `typedef struct _SD_GLOBAL_CHANGE_OUTPUT { // // Output State Flags (none currently defined) // ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:2413` | `typedef struct _LOOKUP_STREAM_FROM_CLUSTER_INPUT { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:2444` | `typedef struct _FILE_TYPE_NOTIFICATION_INPUT { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:2578` | `typedef struct _SYSDBG_TRIAGE_DUMP { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:4988` | `typedef struct _SYSTEM_FLAGS_INFORMATION { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:5104` | `typedef struct _SYSTEM_HOTPATCH_CODE_INFORMATION { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:5341` | `typedef struct _RTL_DRIVE_LETTER_CURDIR { USHORT Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:5494` | `typedef struct _RTL_DRIVE_LETTER_CURDIR32 { USHORT Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:6231` | `typedef struct _BASE_SXS_CREATEPROCESS_MSG { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:6336` | `typedef struct _BASE_DEFINEDOSDEVICE_MSG { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:6356` | `typedef struct _BASE_SXS_CREATE_ACTIVATION_CONTEXT_MSG { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:6472` | `typedef struct _ASSEMBLY_STORAGE_MAP_ENTRY { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:6479` | `typedef struct _ASSEMBLY_STORAGE_MAP { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:6597` | `typedef struct _LDR_DLL_LOADED_NOTIFICATION_DATA { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:6606` | `typedef struct _LDR_DLL_UNLOADED_NOTIFICATION_DATA { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:6915` | `typedef struct _TEB_ACTIVE_FRAME_CONTEXT { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:6935` | `typedef struct _TEB_ACTIVE_FRAME { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:9379` | `typedef struct _LSA_FOREST_TRUST_RECORD { ULONG Flags;` |
| `Flags` | type_alias | `payloads/Demon/include/common/Native.h:11328` | `typedef struct _RTL_HANDLE_TABLE_ENTRY { union { ULONG Flags;` |
| `Flink` | type_alias | `payloads/Demon/include/common/Native.h:455` | `typedef struct _TRIPLE_LIST_ENTRY { struct _TRIPLE_LIST_ENTRY* Flink[ 3 ];` |
| `Flink` | type_alias | `payloads/Demon/include/common/Native.h:5422` | `typedef struct LIST_ENTRY32 { DWORD Flink;` |
| `Flink` | type_alias | `payloads/Demon/include/common/Native.h:5427` | `typedef struct LIST_ENTRY64 { ULONGLONG Flink;` |
| `Foreground` | type_alias | `payloads/Demon/include/common/Native.h:7542` | `typedef struct _PROCESS_PRIORITY_CLASS { BOOLEAN Foreground;` |
| `Foreground` | type_alias | `payloads/Demon/include/common/Native.h:7547` | `typedef struct _PROCESS_FOREGROUND_BACKGROUND { BOOLEAN Foreground;` |
| `GDI_ALTTYPE_1` | macro | `payloads/Demon/include/common/Native.h:5278` | `#define GDI_ALTTYPE_1` |
| `GDI_ALTTYPE_2` | macro | `payloads/Demon/include/common/Native.h:5279` | `#define GDI_ALTTYPE_2` |
| `GDI_ALTTYPE_3` | macro | `payloads/Demon/include/common/Native.h:5280` | `#define GDI_ALTTYPE_3` |
| `GDI_BATCH_BUFFER_SIZE` | macro | `payloads/Demon/include/common/Native.h:5642` | `#define GDI_BATCH_BUFFER_SIZE` |
| `GDI_BATCH_BUFFER_SIZE` | macro | `payloads/Demon/include/common/Native.h:6440` | `#define GDI_BATCH_BUFFER_SIZE` |
| `GDI_BMFD_TYPE` | macro | `payloads/Demon/include/common/Native.h:5263` | `#define GDI_BMFD_TYPE` |
| `GDI_BRUSH_TYPE` | macro | `payloads/Demon/include/common/Native.h:5256` | `#define GDI_BRUSH_TYPE` |
| `GDI_CACHE_TYPE` | macro | `payloads/Demon/include/common/Native.h:5258` | `#define GDI_CACHE_TYPE` |
| `GDI_CLIENTOBJ_TYPE` | macro | `payloads/Demon/include/common/Native.h:5246` | `#define GDI_CLIENTOBJ_TYPE` |
| `GDI_CLIENT_ALTDC_TYPE` | macro | `payloads/Demon/include/common/Native.h:5290` | `#define GDI_CLIENT_ALTDC_TYPE` |
| `GDI_CLIENT_BITMAP_TYPE` | macro | `payloads/Demon/include/common/Native.h:5282` | `#define GDI_CLIENT_BITMAP_TYPE` |
| `GDI_CLIENT_BRUSH_TYPE` | macro | `payloads/Demon/include/common/Native.h:5283` | `#define GDI_CLIENT_BRUSH_TYPE` |
| `GDI_CLIENT_CLIENTOBJ_TYPE` | macro | `payloads/Demon/include/common/Native.h:5284` | `#define GDI_CLIENT_CLIENTOBJ_TYPE` |
| `GDI_CLIENT_DC_TYPE` | macro | `payloads/Demon/include/common/Native.h:5285` | `#define GDI_CLIENT_DC_TYPE` |
| `GDI_CLIENT_DIBSECTION_TYPE` | macro | `payloads/Demon/include/common/Native.h:5291` | `#define GDI_CLIENT_DIBSECTION_TYPE` |
| `GDI_CLIENT_EXTPEN_TYPE` | macro | `payloads/Demon/include/common/Native.h:5292` | `#define GDI_CLIENT_EXTPEN_TYPE` |
| `GDI_CLIENT_FONT_TYPE` | macro | `payloads/Demon/include/common/Native.h:5286` | `#define GDI_CLIENT_FONT_TYPE` |
| `GDI_CLIENT_METADC16_TYPE` | macro | `payloads/Demon/include/common/Native.h:5293` | `#define GDI_CLIENT_METADC16_TYPE` |
| `GDI_CLIENT_METAFILE16_TYPE` | macro | `payloads/Demon/include/common/Native.h:5295` | `#define GDI_CLIENT_METAFILE16_TYPE` |
| `GDI_CLIENT_METAFILE_TYPE` | macro | `payloads/Demon/include/common/Native.h:5294` | `#define GDI_CLIENT_METAFILE_TYPE` |
| `GDI_CLIENT_PALETTE_TYPE` | macro | `payloads/Demon/include/common/Native.h:5287` | `#define GDI_CLIENT_PALETTE_TYPE` |
| `GDI_CLIENT_PEN_TYPE` | macro | `payloads/Demon/include/common/Native.h:5296` | `#define GDI_CLIENT_PEN_TYPE` |
| `GDI_CLIENT_REGION_TYPE` | macro | `payloads/Demon/include/common/Native.h:5288` | `#define GDI_CLIENT_REGION_TYPE` |
| `GDI_CLIENT_TYPE_FROM_HANDLE` | macro | `payloads/Demon/include/common/Native.h:5274` | `#define GDI_CLIENT_TYPE_FROM_HANDLE(Handle)` |
| `GDI_CLIENT_TYPE_FROM_UNIQUE` | macro | `payloads/Demon/include/common/Native.h:5276` | `#define GDI_CLIENT_TYPE_FROM_UNIQUE(Unique)` |
| `GDI_DBRUSH_TYPE` | macro | `payloads/Demon/include/common/Native.h:5260` | `#define GDI_DBRUSH_TYPE` |
| `GDI_DCIOBJ_TYPE` | macro | `payloads/Demon/include/common/Native.h:5269` | `#define GDI_DCIOBJ_TYPE` |
| `GDI_DC_TYPE` | macro | `payloads/Demon/include/common/Native.h:5241` | `#define GDI_DC_TYPE` |
| `GDI_DD_DIRECTDRAW_TYPE` | macro | `payloads/Demon/include/common/Native.h:5242` | `#define GDI_DD_DIRECTDRAW_TYPE` |
| `GDI_DD_SURFACE_TYPE` | macro | `payloads/Demon/include/common/Native.h:5243` | `#define GDI_DD_SURFACE_TYPE` |
| `GDI_DEF_TYPE` | macro | `payloads/Demon/include/common/Native.h:5240` | `#define GDI_DEF_TYPE` |
| `GDI_DRVOBJ_TYPE` | macro | `payloads/Demon/include/common/Native.h:5268` | `#define GDI_DRVOBJ_TYPE` |
| `GDI_EFSTATE_TYPE` | macro | `payloads/Demon/include/common/Native.h:5262` | `#define GDI_EFSTATE_TYPE` |
| `GDI_HANDLE_ALTTYPE` | macro | `payloads/Demon/include/common/Native.h:5233` | `#define GDI_HANDLE_ALTTYPE(Handle)` |
| `GDI_HANDLE_ALTTYPE_BITS` | macro | `payloads/Demon/include/common/Native.h:5220` | `#define GDI_HANDLE_ALTTYPE_BITS` |
| `GDI_HANDLE_ALTTYPE_MASK` | macro | `payloads/Demon/include/common/Native.h:5221` | `#define GDI_HANDLE_ALTTYPE_MASK` |
| `GDI_HANDLE_ALTTYPE_SHIFT` | macro | `payloads/Demon/include/common/Native.h:5219` | `#define GDI_HANDLE_ALTTYPE_SHIFT` |
| `GDI_HANDLE_BUFFER` | type_alias | `payloads/Demon/include/common/Native.h:2941` | `typedef ULONG GDI_HANDLE_BUFFER[GDI_HANDLE_BUFFER_SIZE];` |
| `GDI_HANDLE_BUFFER32` | type_alias | `payloads/Demon/include/common/Native.h:2938` | `typedef ULONG GDI_HANDLE_BUFFER32[GDI_HANDLE_BUFFER_SIZE32];` |
| `GDI_HANDLE_BUFFER64` | type_alias | `payloads/Demon/include/common/Native.h:2940` | `typedef ULONG GDI_HANDLE_BUFFER64[GDI_HANDLE_BUFFER_SIZE64];` |
| `GDI_HANDLE_BUFFER_SIZE` | macro | `payloads/Demon/include/common/Native.h:2934` | `#define GDI_HANDLE_BUFFER_SIZE` |
| `GDI_HANDLE_BUFFER_SIZE` | macro | `payloads/Demon/include/common/Native.h:2936` | `#define GDI_HANDLE_BUFFER_SIZE` |
| `GDI_HANDLE_BUFFER_SIZE32` | macro | `payloads/Demon/include/common/Native.h:2930` | `#define GDI_HANDLE_BUFFER_SIZE32` |
| `GDI_HANDLE_BUFFER_SIZE64` | macro | `payloads/Demon/include/common/Native.h:2931` | `#define GDI_HANDLE_BUFFER_SIZE64` |
| `GDI_HANDLE_INDEX` | macro | `payloads/Demon/include/common/Native.h:5231` | `#define GDI_HANDLE_INDEX(Handle)` |
| `GDI_HANDLE_INDEX_BITS` | macro | `payloads/Demon/include/common/Native.h:5212` | `#define GDI_HANDLE_INDEX_BITS` |
| `GDI_HANDLE_INDEX_MASK` | macro | `payloads/Demon/include/common/Native.h:5213` | `#define GDI_HANDLE_INDEX_MASK` |
| `GDI_HANDLE_INDEX_SHIFT` | macro | `payloads/Demon/include/common/Native.h:5211` | `#define GDI_HANDLE_INDEX_SHIFT` |
| `GDI_HANDLE_STOCK` | macro | `payloads/Demon/include/common/Native.h:5234` | `#define GDI_HANDLE_STOCK(Handle)` |
| `GDI_HANDLE_STOCK_BITS` | macro | `payloads/Demon/include/common/Native.h:5224` | `#define GDI_HANDLE_STOCK_BITS` |
| `GDI_HANDLE_STOCK_MASK` | macro | `payloads/Demon/include/common/Native.h:5225` | `#define GDI_HANDLE_STOCK_MASK` |
| `GDI_HANDLE_STOCK_SHIFT` | macro | `payloads/Demon/include/common/Native.h:5223` | `#define GDI_HANDLE_STOCK_SHIFT` |
| `GDI_HANDLE_TYPE` | macro | `payloads/Demon/include/common/Native.h:5232` | `#define GDI_HANDLE_TYPE(Handle)` |
| `GDI_HANDLE_TYPE_BITS` | macro | `payloads/Demon/include/common/Native.h:5216` | `#define GDI_HANDLE_TYPE_BITS` |
| `GDI_HANDLE_TYPE_MASK` | macro | `payloads/Demon/include/common/Native.h:5217` | `#define GDI_HANDLE_TYPE_MASK` |
| `GDI_HANDLE_TYPE_SHIFT` | macro | `payloads/Demon/include/common/Native.h:5215` | `#define GDI_HANDLE_TYPE_SHIFT` |
| `GDI_HANDLE_UNIQUE_BITS` | macro | `payloads/Demon/include/common/Native.h:5228` | `#define GDI_HANDLE_UNIQUE_BITS` |
| `GDI_HANDLE_UNIQUE_MASK` | macro | `payloads/Demon/include/common/Native.h:5229` | `#define GDI_HANDLE_UNIQUE_MASK` |
| `GDI_HANDLE_UNIQUE_SHIFT` | macro | `payloads/Demon/include/common/Native.h:5227` | `#define GDI_HANDLE_UNIQUE_SHIFT` |
| `GDI_ICMCXF_TYPE` | macro | `payloads/Demon/include/common/Native.h:5254` | `#define GDI_ICMCXF_TYPE` |
| `GDI_ICMDLL_TYPE` | macro | `payloads/Demon/include/common/Native.h:5255` | `#define GDI_ICMDLL_TYPE` |
| `GDI_ICMLCS_TYPE` | macro | `payloads/Demon/include/common/Native.h:5249` | `#define GDI_ICMLCS_TYPE` |
| `GDI_LFONT_TYPE` | macro | `payloads/Demon/include/common/Native.h:5250` | `#define GDI_LFONT_TYPE` |
| `GDI_MAKE_HANDLE` | macro | `payloads/Demon/include/common/Native.h:5236` | `#define GDI_MAKE_HANDLE(Index, Unique)` |
| `GDI_MAX_HANDLE_COUNT` | macro | `payloads/Demon/include/common/Native.h:5209` | `#define GDI_MAX_HANDLE_COUNT` |
| `GDI_META_TYPE` | macro | `payloads/Demon/include/common/Native.h:5261` | `#define GDI_META_TYPE` |
| `GDI_PAL_TYPE` | macro | `payloads/Demon/include/common/Native.h:5248` | `#define GDI_PAL_TYPE` |
| `GDI_PATH_TYPE` | macro | `payloads/Demon/include/common/Native.h:5247` | `#define GDI_PATH_TYPE` |
| `GDI_PFE_TYPE` | macro | `payloads/Demon/include/common/Native.h:5252` | `#define GDI_PFE_TYPE` |
| `GDI_PFF_TYPE` | macro | `payloads/Demon/include/common/Native.h:5257` | `#define GDI_PFF_TYPE` |
| `GDI_PFT_TYPE` | macro | `payloads/Demon/include/common/Native.h:5253` | `#define GDI_PFT_TYPE` |
| `GDI_RC_TYPE` | macro | `payloads/Demon/include/common/Native.h:5266` | `#define GDI_RC_TYPE` |
| `GDI_RFONT_TYPE` | macro | `payloads/Demon/include/common/Native.h:5251` | `#define GDI_RFONT_TYPE` |
| `GDI_RGN_TYPE` | macro | `payloads/Demon/include/common/Native.h:5244` | `#define GDI_RGN_TYPE` |
| `GDI_SPACE_TYPE` | macro | `payloads/Demon/include/common/Native.h:5259` | `#define GDI_SPACE_TYPE` |
| `GDI_SPOOL_TYPE` | macro | `payloads/Demon/include/common/Native.h:5270` | `#define GDI_SPOOL_TYPE` |
| `GDI_SURF_TYPE` | macro | `payloads/Demon/include/common/Native.h:5245` | `#define GDI_SURF_TYPE` |
| `GDI_TEMP_TYPE` | macro | `payloads/Demon/include/common/Native.h:5267` | `#define GDI_TEMP_TYPE` |
| `GDI_TTFD_TYPE` | macro | `payloads/Demon/include/common/Native.h:5265` | `#define GDI_TTFD_TYPE` |
| `GDI_VTFD_TYPE` | macro | `payloads/Demon/include/common/Native.h:5264` | `#define GDI_VTFD_TYPE` |
| `GET_JMP` | macro | `payloads/Demon/include/common/Native.h:111` | `#define GET_JMP( from )` |
| `GetKUserSharedData` | function | `payloads/Demon/include/common/Native.h:10905` | `__inline struct _KUSER_SHARED_DATA * GetKUserSharedData()` |
| `Group` | type_alias | `payloads/Demon/include/common/Native.h:534` | `typedef struct _PROCESSOR_NUMBER { WORD Group;` |
| `HEAP_CLASS_0` | macro | `payloads/Demon/include/common/Native.h:9910` | `#define HEAP_CLASS_0` |
| `HEAP_CLASS_1` | macro | `payloads/Demon/include/common/Native.h:9911` | `#define HEAP_CLASS_1` |
| `HEAP_CLASS_2` | macro | `payloads/Demon/include/common/Native.h:9912` | `#define HEAP_CLASS_2` |
| `HEAP_CLASS_3` | macro | `payloads/Demon/include/common/Native.h:9913` | `#define HEAP_CLASS_3` |
| `HEAP_CLASS_4` | macro | `payloads/Demon/include/common/Native.h:9914` | `#define HEAP_CLASS_4` |
| `HEAP_CLASS_5` | macro | `payloads/Demon/include/common/Native.h:9915` | `#define HEAP_CLASS_5` |
| `HEAP_CLASS_6` | macro | `payloads/Demon/include/common/Native.h:9916` | `#define HEAP_CLASS_6` |
| `HEAP_CLASS_7` | macro | `payloads/Demon/include/common/Native.h:9917` | `#define HEAP_CLASS_7` |
| `HEAP_CLASS_8` | macro | `payloads/Demon/include/common/Native.h:9918` | `#define HEAP_CLASS_8` |
| `HEAP_CLASS_MASK` | macro | `payloads/Demon/include/common/Native.h:9919` | `#define HEAP_CLASS_MASK` |
| `HEAP_ENTRY_BUSY` | macro | `payloads/Demon/include/common/Native.h:10431` | `#define HEAP_ENTRY_BUSY` |
| `HEAP_ENTRY_EXTRA_PRESENT` | macro | `payloads/Demon/include/common/Native.h:10432` | `#define HEAP_ENTRY_EXTRA_PRESENT` |
| `HEAP_ENTRY_FILL_PATTERN` | macro | `payloads/Demon/include/common/Native.h:10433` | `#define HEAP_ENTRY_FILL_PATTERN` |
| `HEAP_ENTRY_LAST_ENTRY` | macro | `payloads/Demon/include/common/Native.h:10435` | `#define HEAP_ENTRY_LAST_ENTRY` |
| `HEAP_ENTRY_SETTABLE_FLAG1` | macro | `payloads/Demon/include/common/Native.h:10436` | `#define HEAP_ENTRY_SETTABLE_FLAG1` |
| `HEAP_ENTRY_SETTABLE_FLAG2` | macro | `payloads/Demon/include/common/Native.h:10437` | `#define HEAP_ENTRY_SETTABLE_FLAG2` |
| `HEAP_ENTRY_SETTABLE_FLAG3` | macro | `payloads/Demon/include/common/Native.h:10438` | `#define HEAP_ENTRY_SETTABLE_FLAG3` |
| `HEAP_ENTRY_SETTABLE_FLAGS` | macro | `payloads/Demon/include/common/Native.h:10439` | `#define HEAP_ENTRY_SETTABLE_FLAGS` |
| `HEAP_ENTRY_VIRTUAL_ALLOC` | macro | `payloads/Demon/include/common/Native.h:10434` | `#define HEAP_ENTRY_VIRTUAL_ALLOC` |
| `HEAP_GRANULARITY` | macro | `payloads/Demon/include/common/Native.h:10423` | `#define HEAP_GRANULARITY` |
| `HEAP_GRANULARITY_SHIFT` | macro | `payloads/Demon/include/common/Native.h:10424` | `#define HEAP_GRANULARITY_SHIFT` |
| `HEAP_MAKE_TAG_FLAGS` | macro | `payloads/Demon/include/common/Native.h:3622` | `#define HEAP_MAKE_TAG_FLAGS( b, o )` |
| `HEAP_MAXIMUM_BLOCK_SIZE` | macro | `payloads/Demon/include/common/Native.h:10426` | `#define HEAP_MAXIMUM_BLOCK_SIZE` |
| `HEAP_MAXIMUM_FREELISTS` | macro | `payloads/Demon/include/common/Native.h:10428` | `#define HEAP_MAXIMUM_FREELISTS` |
| `HEAP_MAXIMUM_SEGMENTS` | macro | `payloads/Demon/include/common/Native.h:10429` | `#define HEAP_MAXIMUM_SEGMENTS` |
| `HEAP_SETTABLE_USER_FLAG1` | macro | `payloads/Demon/include/common/Native.h:9905` | `#define HEAP_SETTABLE_USER_FLAG1` |
| `HEAP_SETTABLE_USER_FLAG2` | macro | `payloads/Demon/include/common/Native.h:9906` | `#define HEAP_SETTABLE_USER_FLAG2` |
| `HEAP_SETTABLE_USER_FLAG3` | macro | `payloads/Demon/include/common/Native.h:9907` | `#define HEAP_SETTABLE_USER_FLAG3` |
| `HEAP_SETTABLE_USER_FLAGS` | macro | `payloads/Demon/include/common/Native.h:9908` | `#define HEAP_SETTABLE_USER_FLAGS` |
| `HEAP_SETTABLE_USER_VALUE` | macro | `payloads/Demon/include/common/Native.h:9904` | `#define HEAP_SETTABLE_USER_VALUE` |
| `HEAP_USAGE_ALLOCATED_BLOCKS` | macro | `payloads/Demon/include/common/Native.h:11123` | `#define HEAP_USAGE_ALLOCATED_BLOCKS` |
| `HEAP_USAGE_FREE_BUFFER` | macro | `payloads/Demon/include/common/Native.h:11124` | `#define HEAP_USAGE_FREE_BUFFER` |
| `HandleToProcess` | type_alias | `payloads/Demon/include/common/Native.h:11043` | `typedef struct _DBGUI_CREATE_PROCESS { HANDLE HandleToProcess;` |
| `HandleToThread` | type_alias | `payloads/Demon/include/common/Native.h:11037` | `typedef struct _DBGUI_CREATE_THREAD { HANDLE HandleToThread;` |
| `Handles` | type_alias | `payloads/Demon/include/common/Native.h:5320` | `typedef struct _GDI_SHARED_MEMORY { GDI_HANDLE_ENTRY Handles[GDI_MAX_HANDLE_COUNT];` |
| `Header` | type_alias | `payloads/Demon/include/common/Native.h:10379` | `typedef struct _KEVENT { DISPATCHER_HEADER Header;` |
| `Header` | type_alias | `payloads/Demon/include/common/Native.h:10384` | `typedef struct _KGATE { DISPATCHER_HEADER Header;` |
| `Header` | type_alias | `payloads/Demon/include/common/Native.h:10389` | `typedef struct _KSEMAPHORE { DISPATCHER_HEADER Header;` |
| `HeapDebuggingInformation` | macro | `payloads/Demon/include/common/Native.h:11152` | `#define HeapDebuggingInformation` |
| `HighestNodeNumber` | type_alias | `payloads/Demon/include/common/Native.h:4686` | `typedef struct _SYSTEM_NUMA_INFORMATION { ULONG HighestNodeNumber;` |
| `HookType` | type_alias | `payloads/Demon/include/common/Native.h:11584` | `typedef struct _HOTPATCH_HOOK { USHORT HookType;` |
| `HotpatchImageNameLength` | type_alias | `payloads/Demon/include/common/Native.h:11571` | `typedef struct _HOTPATCH_MODULE_DATA { USHORT HotpatchImageNameLength;` |
| `IMPORT_FN` | macro | `payloads/Demon/include/common/Native.h:50` | `#define IMPORT_FN` |
| `IMPORT_SIZE` | macro | `payloads/Demon/include/common/Native.h:699` | `#define IMPORT_SIZE(x)` |
| `IMPORT_VA` | macro | `payloads/Demon/include/common/Native.h:694` | `#define IMPORT_VA(x)` |
| `IN_REGION` | macro | `payloads/Demon/include/common/Native.h:462` | `#define IN_REGION(x, Base, Size)` |
| `IO_COMPLETION_ALL_ACCESS` | macro | `payloads/Demon/include/common/Native.h:3296` | `#define IO_COMPLETION_ALL_ACCESS` |
| `IO_COMPLETION_MODIFY_STATE` | macro | `payloads/Demon/include/common/Native.h:3295` | `#define IO_COMPLETION_MODIFY_STATE` |
| `IO_COMPLETION_QUERY_STATE` | macro | `payloads/Demon/include/common/Native.h:3294` | `#define IO_COMPLETION_QUERY_STATE` |
| `IS_DOT` | macro | `payloads/Demon/include/common/Native.h:93` | `#define IS_DOT(s)` |
| `IS_DOT_DOT` | macro | `payloads/Demon/include/common/Native.h:94` | `#define IS_DOT_DOT(s)` |
| `IS_DOT_DOT_U` | macro | `payloads/Demon/include/common/Native.h:98` | `#define IS_DOT_DOT_U(s)` |
| `IS_DOT_U` | macro | `payloads/Demon/include/common/Native.h:97` | `#define IS_DOT_U(s)` |
| `IS_PATH_SEPARATOR` | macro | `payloads/Demon/include/common/Native.h:92` | `#define IS_PATH_SEPARATOR(ch)` |
| `IS_PATH_SEPARATOR_U` | macro | `payloads/Demon/include/common/Native.h:96` | `#define IS_PATH_SEPARATOR_U(ch)` |
| `IS_VALID_HANDLE` | macro | `payloads/Demon/include/common/Native.h:706` | `#define IS_VALID_HANDLE(hHandle)` |
| `Id` | type_alias | `payloads/Demon/include/common/Native.h:11511` | `typedef struct _EVENT_DESCRIPTOR { USHORT Id;` |
| `IdleProcessTime` | type_alias | `payloads/Demon/include/common/Native.h:4841` | `typedef struct _SYSTEM_PERFORMANCE_INFORMATION { LARGE_INTEGER IdleProcessTime;` |
| `IdleTime` | type_alias | `payloads/Demon/include/common/Native.h:4666` | `typedef struct _SYSTEM_PROCESSOR_PERFORMANCE_INFORMATION { LARGE_INTEGER IdleTime;` |
| `IdleTime` | type_alias | `payloads/Demon/include/common/Native.h:4675` | `typedef struct _SYSTEM_PROCESSOR_IDLE_INFORMATION { ULONGLONG IdleTime;` |
| `InLoadOrderLinks` | type_alias | `payloads/Demon/include/common/Native.h:5451` | `typedef struct _LDR_DATA_TABLE_ENTRY32 { LIST_ENTRY32 InLoadOrderLinks;` |
| `InLoadOrderLinks` | type_alias | `payloads/Demon/include/common/Native.h:6670` | `typedef struct _LDR_DATA_TABLE_ENTRY { LIST_ENTRY InLoadOrderLinks;` |
| `InLoadOrderLinks` | type_alias | `payloads/Demon/include/common/Native.h:10311` | `typedef struct _KLDR_DATA_TABLE_ENTRY { LIST_ENTRY InLoadOrderLinks;` |
| `IncomingAuthInfos` | type_alias | `payloads/Demon/include/common/Native.h:9276` | `typedef struct _TRUSTED_DOMAIN_AUTH_INFORMATION { ULONG IncomingAuthInfos;` |
| `Index` | type_alias | `payloads/Demon/include/common/Native.h:9434` | `typedef struct _LSA_FOREST_TRUST_COLLISION_RECORD { ULONG Index;` |
| `IndexNumber` | type_alias | `payloads/Demon/include/common/Native.h:3970` | `typedef struct _FILE_INTERNAL_INFORMATION { LARGE_INTEGER IndexNumber;` |
| `InfoLength` | type_alias | `payloads/Demon/include/common/Native.h:9102` | `typedef struct _POLICY_DOMAIN_EFS_INFO { ULONG InfoLength;` |
| `InfoSize` | type_alias | `payloads/Demon/include/common/Native.h:4968` | `typedef struct _SYSTEM_MEMORY_INFORMATION { ULONG InfoSize;` |
| `Information` | type_alias | `payloads/Demon/include/common/Native.h:9287` | `typedef struct _TRUSTED_DOMAIN_FULL_INFORMATION { TRUSTED_DOMAIN_INFORMATION_EX Information;` |
| `Information` | type_alias | `payloads/Demon/include/common/Native.h:9295` | `typedef struct _TRUSTED_DOMAIN_FULL_INFORMATION2 { TRUSTED_DOMAIN_INFORMATION_EX2 Information;` |
| `Inherit` | type_alias | `payloads/Demon/include/common/Native.h:3521` | `typedef struct _OBJECT_HANDLE_FLAG_INFORMATION { BOOLEAN Inherit;` |
| `InheritedAddressSpace` | type_alias | `payloads/Demon/include/common/Native.h:5542` | `typedef struct _PEB32 { BOOLEAN InheritedAddressSpace;` |
| `InheritedAddressSpace` | type_alias | `payloads/Demon/include/common/Native.h:6757` | `typedef struct _PEB { BOOLEAN InheritedAddressSpace;` |
| `IniFileName` | type_alias | `payloads/Demon/include/common/Native.h:6310` | `typedef struct _BASE_REFRESHINIFILEMAPPING_MSG { UNICODE_STRING IniFileName;` |
| `InitializeListHead` | macro | `payloads/Demon/include/common/Native.h:561` | `#define InitializeListHead(ListHead)` |
| `InitializeObjectAttributes` | macro | `payloads/Demon/include/common/Native.h:517` | `#define InitializeObjectAttributes( p, n, a, r, s )` |
| `InsertHeadList` | macro | `payloads/Demon/include/common/Native.h:610` | `#define InsertHeadList(ListHead,Entry)` |
| `InsertTailList` | macro | `payloads/Demon/include/common/Native.h:594` | `#define InsertTailList(ListHead,Entry)` |
| `InterceptorFunction` | type_alias | `payloads/Demon/include/common/Native.h:11162` | `typedef struct _HEAP_DEBUGGING_INFORMATION { PVOID InterceptorFunction;` |
| `IsListEmpty` | macro | `payloads/Demon/include/common/Native.h:558` | `#define IsListEmpty(ListHead)` |
| `IsListEmpty` | macro | `payloads/Demon/include/common/Native.h:564` | `#define IsListEmpty(ListHead)` |
| `JOB_OBJECT_ALL_ACCESS` | macro | `payloads/Demon/include/common/Native.h:2922` | `#define JOB_OBJECT_ALL_ACCESS` |
| `JOB_OBJECT_ASSIGN_PROCESS` | macro | `payloads/Demon/include/common/Native.h:2916` | `#define JOB_OBJECT_ASSIGN_PROCESS` |
| `JOB_OBJECT_QUERY` | macro | `payloads/Demon/include/common/Native.h:2918` | `#define JOB_OBJECT_QUERY` |
| `JOB_OBJECT_SET_ATTRIBUTES` | macro | `payloads/Demon/include/common/Native.h:2917` | `#define JOB_OBJECT_SET_ATTRIBUTES` |
| `JOB_OBJECT_SET_SECURITY_ATTRIBUTES` | macro | `payloads/Demon/include/common/Native.h:2920` | `#define JOB_OBJECT_SET_SECURITY_ATTRIBUTES` |
| `JOB_OBJECT_TERMINATE` | macro | `payloads/Demon/include/common/Native.h:2919` | `#define JOB_OBJECT_TERMINATE` |
| `JobHandle` | type_alias | `payloads/Demon/include/common/Native.h:11353` | `typedef struct _JOB_SET_ARRAY { HANDLE JobHandle;` |
| `KIRQL` | type_alias | `payloads/Demon/include/common/Native.h:434` | `typedef UCHAR KIRQL;` |
| `KPRIORITY` | type_alias | `payloads/Demon/include/common/Native.h:363` | `typedef LONG KPRIORITY;` |
| `KernelDebuggerEnabled` | type_alias | `payloads/Demon/include/common/Native.h:4521` | `typedef struct _SYSTEM_KERNEL_DEBUGGER_INFORMATION { BOOLEAN KernelDebuggerEnabled;` |
| `KernelTime` | type_alias | `payloads/Demon/include/common/Native.h:4369` | `typedef struct _SYSTEM_THREAD_INFORMATION { LARGE_INTEGER KernelTime;` |
| `KtmTransaction` | type_alias | `payloads/Demon/include/common/Native.h:2000` | `typedef struct _TXFS_LIST_TRANSACTION_LOCKED_FILES { // // GUID name of the KTM transaction that files should be enumera` |
| `KtmTransaction` | type_alias | `payloads/Demon/include/common/Native.h:2171` | `typedef struct _TXFS_SAVEPOINT_INFORMATION { HANDLE KtmTransaction;` |
| `LCType` | type_alias | `payloads/Demon/include/common/Native.h:6067` | `typedef struct _BASE_NLS_SET_USER_INFO_MSG { ULONG LCType;` |
| `LDRP_COMPAT_DATABASE_PROCESSED` | macro | `payloads/Demon/include/common/Native.h:6577` | `#define LDRP_COMPAT_DATABASE_PROCESSED` |
| `LDRP_COR_IMAGE` | macro | `payloads/Demon/include/common/Native.h:6568` | `#define LDRP_COR_IMAGE` |
| `LDRP_COR_OWNS_UNMAP` | macro | `payloads/Demon/include/common/Native.h:6569` | `#define LDRP_COR_OWNS_UNMAP` |
| `LDRP_CURRENT_LOAD` | macro | `payloads/Demon/include/common/Native.h:6562` | `#define LDRP_CURRENT_LOAD` |
| `LDRP_DEBUG_SYMBOLS_LOADED` | macro | `payloads/Demon/include/common/Native.h:6566` | `#define LDRP_DEBUG_SYMBOLS_LOADED` |
| `LDRP_DONT_CALL_FOR_THREADS` | macro | `payloads/Demon/include/common/Native.h:6564` | `#define LDRP_DONT_CALL_FOR_THREADS` |
| `LDRP_DRIVER_DEPENDENT_DLL` | macro | `payloads/Demon/include/common/Native.h:6572` | `#define LDRP_DRIVER_DEPENDENT_DLL` |
| `LDRP_ENTRY_INSERTED` | macro | `payloads/Demon/include/common/Native.h:6561` | `#define LDRP_ENTRY_INSERTED` |
| `LDRP_ENTRY_NATIVE` | macro | `payloads/Demon/include/common/Native.h:6573` | `#define LDRP_ENTRY_NATIVE` |
| `LDRP_ENTRY_PROCESSED` | macro | `payloads/Demon/include/common/Native.h:6560` | `#define LDRP_ENTRY_PROCESSED` |
| `LDRP_FAILED_BUILTIN_LOAD` | macro | `payloads/Demon/include/common/Native.h:6563` | `#define LDRP_FAILED_BUILTIN_LOAD` |
| `LDRP_IMAGE_DLL` | macro | `payloads/Demon/include/common/Native.h:6557` | `#define LDRP_IMAGE_DLL` |
| `LDRP_IMAGE_NOT_AT_BASE` | macro | `payloads/Demon/include/common/Native.h:6567` | `#define LDRP_IMAGE_NOT_AT_BASE` |
| `LDRP_IMAGE_VERIFYING` | macro | `payloads/Demon/include/common/Native.h:6571` | `#define LDRP_IMAGE_VERIFYING` |
| `LDRP_LOAD_IN_PROGRESS` | macro | `payloads/Demon/include/common/Native.h:6558` | `#define LDRP_LOAD_IN_PROGRESS` |
| `LDRP_MM_LOADED` | macro | `payloads/Demon/include/common/Native.h:6576` | `#define LDRP_MM_LOADED` |
| `LDRP_NON_PAGED_DEBUG_INFO` | macro | `payloads/Demon/include/common/Native.h:6575` | `#define LDRP_NON_PAGED_DEBUG_INFO` |
| `LDRP_PROCESS_ATTACH_CALLED` | macro | `payloads/Demon/include/common/Native.h:6565` | `#define LDRP_PROCESS_ATTACH_CALLED` |
| `LDRP_REDIRECTED` | macro | `payloads/Demon/include/common/Native.h:6574` | `#define LDRP_REDIRECTED` |
| `LDRP_STATIC_LINK` | macro | `payloads/Demon/include/common/Native.h:6556` | `#define LDRP_STATIC_LINK` |
| `LDRP_SYSTEM_MAPPED` | macro | `payloads/Demon/include/common/Native.h:6570` | `#define LDRP_SYSTEM_MAPPED` |
| `LDRP_UNLOAD_IN_PROGRESS` | macro | `payloads/Demon/include/common/Native.h:6559` | `#define LDRP_UNLOAD_IN_PROGRESS` |
| `LDR_ADDREF_DLL_PIN` | macro | `payloads/Demon/include/common/Native.h:6582` | `#define LDR_ADDREF_DLL_PIN` |
| `LDR_DATA_TABLE_ENTRY_SIZE_WINXP32` | macro | `payloads/Demon/include/common/Native.h:5450` | `#define LDR_DATA_TABLE_ENTRY_SIZE_WINXP32` |
| `LDR_DLL_NOTIFICATION_REASON_LOADED` | macro | `payloads/Demon/include/common/Native.h:6595` | `#define LDR_DLL_NOTIFICATION_REASON_LOADED` |
| `LDR_DLL_NOTIFICATION_REASON_UNLOADED` | macro | `payloads/Demon/include/common/Native.h:6596` | `#define LDR_DLL_NOTIFICATION_REASON_UNLOADED` |
| `LDR_GET_DLL_HANDLE_EX_PIN` | macro | `payloads/Demon/include/common/Native.h:6580` | `#define LDR_GET_DLL_HANDLE_EX_PIN` |
| `LDR_GET_DLL_HANDLE_EX_UNCHANGED_REFCOUNT` | macro | `payloads/Demon/include/common/Native.h:6579` | `#define LDR_GET_DLL_HANDLE_EX_UNCHANGED_REFCOUNT` |
| `LDR_GET_PROCEDURE_ADDRESS_DONT_RECORD_FORWARDER` | macro | `payloads/Demon/include/common/Native.h:6584` | `#define LDR_GET_PROCEDURE_ADDRESS_DONT_RECORD_FORWARDER` |
| `LDR_LOCK_LOADER_LOCK_DISPOSITION_INVALID` | macro | `payloads/Demon/include/common/Native.h:6589` | `#define LDR_LOCK_LOADER_LOCK_DISPOSITION_INVALID` |
| `LDR_LOCK_LOADER_LOCK_DISPOSITION_LOCK_ACQUIRED` | macro | `payloads/Demon/include/common/Native.h:6590` | `#define LDR_LOCK_LOADER_LOCK_DISPOSITION_LOCK_ACQUIRED` |
| `LDR_LOCK_LOADER_LOCK_DISPOSITION_LOCK_NOT_ACQUIRED` | macro | `payloads/Demon/include/common/Native.h:6591` | `#define LDR_LOCK_LOADER_LOCK_DISPOSITION_LOCK_NOT_ACQUIRED` |
| `LDR_LOCK_LOADER_LOCK_FLAG_RAISE_ON_ERRORS` | macro | `payloads/Demon/include/common/Native.h:6586` | `#define LDR_LOCK_LOADER_LOCK_FLAG_RAISE_ON_ERRORS` |
| `LDR_LOCK_LOADER_LOCK_FLAG_TRY_ONLY` | macro | `payloads/Demon/include/common/Native.h:6587` | `#define LDR_LOCK_LOADER_LOCK_FLAG_TRY_ONLY` |
| `LDR_RELOCATE_IMAGE_RETURN_TYPE` | type_alias | `payloads/Demon/include/common/Native.h:6709` | `typedef NTSTATUS LDR_RELOCATE_IMAGE_RETURN_TYPE;` |
| `LDR_UNLOCK_LOADER_LOCK_FLAG_RAISE_ON_ERRORS` | macro | `payloads/Demon/include/common/Native.h:6593` | `#define LDR_UNLOCK_LOADER_LOCK_FLAG_RAISE_ON_ERRORS` |
| `LIST_ENTRY32` | struct | `payloads/Demon/include/common/Native.h:5422` | `` |
| `LIST_ENTRY64` | struct | `payloads/Demon/include/common/Native.h:5428` | `` |
| `LOCK_QUEUE_OWNER` | macro | `payloads/Demon/include/common/Native.h:2717` | `#define LOCK_QUEUE_OWNER` |
| `LOCK_QUEUE_OWNER_BIT` | macro | `payloads/Demon/include/common/Native.h:2718` | `#define LOCK_QUEUE_OWNER_BIT` |
| `LOCK_QUEUE_TIMER_LOCK_SHIFT` | macro | `payloads/Demon/include/common/Native.h:2720` | `#define LOCK_QUEUE_TIMER_LOCK_SHIFT` |
| `LOCK_QUEUE_TIMER_TABLE_LOCKS` | macro | `payloads/Demon/include/common/Native.h:2721` | `#define LOCK_QUEUE_TIMER_TABLE_LOCKS` |
| `LOCK_QUEUE_WAIT` | macro | `payloads/Demon/include/common/Native.h:2714` | `#define LOCK_QUEUE_WAIT` |
| `LOCK_QUEUE_WAIT_BIT` | macro | `payloads/Demon/include/common/Native.h:2715` | `#define LOCK_QUEUE_WAIT_BIT` |
| `LOGICAL` | type_alias | `payloads/Demon/include/common/Native.h:360` | `typedef ULONG LOGICAL;` |
| `LONG_2ND_MOST_SIGNIFICANT_BIT` | macro | `payloads/Demon/include/common/Native.h:140` | `#define LONG_2ND_MOST_SIGNIFICANT_BIT` |
| `LONG_3RD_MOST_SIGNIFICANT_BIT` | macro | `payloads/Demon/include/common/Native.h:139` | `#define LONG_3RD_MOST_SIGNIFICANT_BIT` |
| `LONG_LEAST_SIGNIFICANT_BIT` | macro | `payloads/Demon/include/common/Native.h:138` | `#define LONG_LEAST_SIGNIFICANT_BIT` |
| `LONG_MASK` | macro | `payloads/Demon/include/common/Native.h:123` | `#define LONG_MASK` |
| `LONG_MOST_SIGNIFICANT_BIT` | macro | `payloads/Demon/include/common/Native.h:141` | `#define LONG_MOST_SIGNIFICANT_BIT` |
| `LONG_SIZE` | macro | `payloads/Demon/include/common/Native.h:122` | `#define LONG_SIZE` |
| `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_ATTRIBUTE_DATA` | macro | `payloads/Demon/include/common/Native.h:2433` | `#define LOOKUP_STREAM_FROM_CLUSTER_ENTRY_ATTRIBUTE_DATA` |
| `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_ATTRIBUTE_INDEX` | macro | `payloads/Demon/include/common/Native.h:2434` | `#define LOOKUP_STREAM_FROM_CLUSTER_ENTRY_ATTRIBUTE_INDEX` |
| `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_ATTRIBUTE_MASK` | macro | `payloads/Demon/include/common/Native.h:2432` | `#define LOOKUP_STREAM_FROM_CLUSTER_ENTRY_ATTRIBUTE_MASK` |
| `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_ATTRIBUTE_SYSTEM` | macro | `payloads/Demon/include/common/Native.h:2435` | `#define LOOKUP_STREAM_FROM_CLUSTER_ENTRY_ATTRIBUTE_SYSTEM` |
| `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_FLAG_DENY_DEFRAG_SET` | macro | `payloads/Demon/include/common/Native.h:2428` | `#define LOOKUP_STREAM_FROM_CLUSTER_ENTRY_FLAG_DENY_DEFRAG_SET` |
| `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_FLAG_FS_SYSTEM_FILE` | macro | `payloads/Demon/include/common/Native.h:2429` | `#define LOOKUP_STREAM_FROM_CLUSTER_ENTRY_FLAG_FS_SYSTEM_FILE` |
| `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_FLAG_PAGE_FILE` | macro | `payloads/Demon/include/common/Native.h:2427` | `#define LOOKUP_STREAM_FROM_CLUSTER_ENTRY_FLAG_PAGE_FILE` |
| `LOOKUP_STREAM_FROM_CLUSTER_ENTRY_FLAG_TXF_SYSTEM_FILE` | macro | `payloads/Demon/include/common/Native.h:2430` | `#define LOOKUP_STREAM_FROM_CLUSTER_ENTRY_FLAG_TXF_SYSTEM_FILE` |
| `LOOKUP_TRANSLATE_NAMES` | macro | `payloads/Demon/include/common/Native.h:8579` | `#define LOOKUP_TRANSLATE_NAMES` |
| `LOOKUP_VIEW_LOCAL_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:8578` | `#define LOOKUP_VIEW_LOCAL_INFORMATION` |
| `LOWBYTE_MASK` | macro | `payloads/Demon/include/common/Native.h:124` | `#define LOWBYTE_MASK` |
| `LPC_BUFFER_SIZE` | macro | `payloads/Demon/include/common/Native.h:10975` | `#define LPC_BUFFER_SIZE` |
| `LPC_CLIENT_ID` | macro | `payloads/Demon/include/common/Native.h:474` | `#define LPC_CLIENT_ID` |
| `LPC_CLIENT_ID` | macro | `payloads/Demon/include/common/Native.h:479` | `#define LPC_CLIENT_ID` |
| `LPC_HANDLE` | macro | `payloads/Demon/include/common/Native.h:477` | `#define LPC_HANDLE` |
| `LPC_HANDLE` | macro | `payloads/Demon/include/common/Native.h:482` | `#define LPC_HANDLE` |
| `LPC_PVOID` | macro | `payloads/Demon/include/common/Native.h:476` | `#define LPC_PVOID` |
| `LPC_PVOID` | macro | `payloads/Demon/include/common/Native.h:481` | `#define LPC_PVOID` |
| `LPC_SIZE_T` | macro | `payloads/Demon/include/common/Native.h:475` | `#define LPC_SIZE_T` |
| `LPC_SIZE_T` | macro | `payloads/Demon/include/common/Native.h:480` | `#define LPC_SIZE_T` |
| `LSAP_SE_ADT_PARAMETER_ARRAY_TRUE_SIZE` | macro | `payloads/Demon/include/common/Native.h:8762` | `#define LSAP_SE_ADT_PARAMETER_ARRAY_TRUE_SIZE(AuditParameters)` |
| `LSA_FOREST_TRUST_RECORD_TYPE_UNRECOGNIZED` | macro | `payloads/Demon/include/common/Native.h:9320` | `#define LSA_FOREST_TRUST_RECORD_TYPE_UNRECOGNIZED` |
| `LSA_FTRECORD_DISABLED_REASONS` | macro | `payloads/Demon/include/common/Native.h:9327` | `#define LSA_FTRECORD_DISABLED_REASONS` |
| `LSA_MODE_INDIVIDUAL_ACCOUNTS` | macro | `payloads/Demon/include/common/Native.h:8636` | `#define LSA_MODE_INDIVIDUAL_ACCOUNTS` |
| `LSA_MODE_LOG_FULL` | macro | `payloads/Demon/include/common/Native.h:8638` | `#define LSA_MODE_LOG_FULL` |
| `LSA_MODE_MANDATORY_ACCESS` | macro | `payloads/Demon/include/common/Native.h:8637` | `#define LSA_MODE_MANDATORY_ACCESS` |
| `LSA_MODE_PASSWORD_PROTECTED` | macro | `payloads/Demon/include/common/Native.h:8635` | `#define LSA_MODE_PASSWORD_PROTECTED` |
| `LSA_NB_DISABLED_ADMIN` | macro | `payloads/Demon/include/common/Native.h:9343` | `#define LSA_NB_DISABLED_ADMIN` |
| `LSA_NB_DISABLED_CONFLICT` | macro | `payloads/Demon/include/common/Native.h:9344` | `#define LSA_NB_DISABLED_CONFLICT` |
| `LSA_SID_DISABLED_ADMIN` | macro | `payloads/Demon/include/common/Native.h:9341` | `#define LSA_SID_DISABLED_ADMIN` |
| `LSA_SID_DISABLED_CONFLICT` | macro | `payloads/Demon/include/common/Native.h:9342` | `#define LSA_SID_DISABLED_CONFLICT` |
| `LSA_SUCCESS` | macro | `payloads/Demon/include/common/Native.h:8794` | `#define LSA_SUCCESS(Error)` |
| `LSA_TLN_DISABLED_ADMIN` | macro | `payloads/Demon/include/common/Native.h:9334` | `#define LSA_TLN_DISABLED_ADMIN` |
| `LSA_TLN_DISABLED_CONFLICT` | macro | `payloads/Demon/include/common/Native.h:9335` | `#define LSA_TLN_DISABLED_CONFLICT` |
| `LSA_TLN_DISABLED_NEW` | macro | `payloads/Demon/include/common/Native.h:9333` | `#define LSA_TLN_DISABLED_NEW` |
| `LastSuccessfulLogon` | type_alias | `payloads/Demon/include/common/Native.h:9492` | `typedef struct _LSA_LAST_INTER_LOGON_INFO { LARGE_INTEGER LastSuccessfulLogon;` |
| `LastUpdateTime` | type_alias | `payloads/Demon/include/common/Native.h:9268` | `typedef struct _LSA_AUTH_INFORMATION { LARGE_INTEGER LastUpdateTime;` |
| `LastVirtualClock` | type_alias | `payloads/Demon/include/common/Native.h:1801` | `typedef struct _TXFS_ROLLFORWARD_REDO_INFORMATION { LARGE_INTEGER LastVirtualClock;` |
| `LastWriteTime` | type_alias | `payloads/Demon/include/common/Native.h:3778` | `typedef struct _KEY_BASIC_INFORMATION { LARGE_INTEGER LastWriteTime;` |
| `LdrInitShimEngineDynamic` | function | `payloads/Demon/include/common/Native.h:22118` | `int NTAPI LdrInitShimEngineDynamic( PVOID pShimEngineModule);` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:365` | `typedef struct _STRING { USHORT Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:381` | `typedef struct _CSTRING { USHORT Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:393` | `typedef struct _UNICODE_STRING { USHORT Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:401` | `typedef struct _STRING32 { USHORT Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:416` | `typedef struct _STRING64 { USHORT Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:504` | `typedef struct _OBJECT_ATTRIBUTES { ULONG Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:3278` | `typedef struct _PORT_VIEW { ULONG Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:3287` | `typedef struct _REMOTE_PORT_VIEW { ULONG Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:4974` | `typedef struct _SYSTEM_CALL_COUNT_INFORMATION { ULONG Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:4992` | `typedef struct _SYSTEM_CALL_TIME_INFORMATION { ULONG Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:5436` | `typedef struct _PEB_LDR_DATA32 { ULONG Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:5933` | `typedef struct _CSR_CAPTURE_HEADER { ULONG Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:6519` | `typedef struct _PEB_LDR_DATA { ULONG Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:8512` | `typedef struct _LSA_UNICODE_STRING { USHORT Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:8521` | `typedef struct _LSA_STRING { USHORT Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:8527` | `typedef struct _LSA_OBJECT_ATTRIBUTES { ULONG Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:9367` | `typedef struct _LSA_FOREST_TRUST_BINARY_DATA { #ifdef MIDL_PASS [range(0, MAX_FOREST_TRUST_BINARY_DATA_SIZE)] ULONG Leng` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:9888` | `typedef struct _RTL_HEAP_PARAMETERS { ULONG Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:10249` | `typedef struct _RTL_USER_PROCESS_INFORMATION { ULONG Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:10257` | `typedef struct _RTL_USER_PROCESS_INFORMATION64 { ULONG Length;` |
| `Length` | type_alias | `payloads/Demon/include/common/Native.h:11109` | `typedef struct _RTL_HEAP_USAGE { ULONG Length;` |
| `Level` | type_alias | `payloads/Demon/include/common/Native.h:4715` | `typedef struct _CACHE_DESCRIPTOR { BYTE Level;` |
| `ListEntry` | type_alias | `payloads/Demon/include/common/Native.h:11578` | `typedef struct _HOTPATCH_MODULE_ENTRY { struct _TRIPLE_LIST_ENTRY ListEntry;` |
| `ListHead` | type_alias | `payloads/Demon/include/common/Native.h:10197` | `typedef struct _RTL_RANGE_LIST { LIST_ENTRY ListHead;` |
| `LogFileFullExceptions` | type_alias | `payloads/Demon/include/common/Native.h:1281` | `typedef struct _NTFS_STATISTICS { ULONG LogFileFullExceptions;` |
| `LongAlignPtr` | macro | `payloads/Demon/include/common/Native.h:7627` | `#define LongAlignPtr(Ptr)` |
| `LongAlignSize` | macro | `payloads/Demon/include/common/Native.h:7628` | `#define LongAlignSize(Size)` |
| `LowPart` | type_alias | `payloads/Demon/include/common/Native.h:1929` | `typedef struct _TXFS_GET_METADATA_INFO_OUT { // // Returns the TxfId of the file referenced by the handle used to call t` |
| `LowPart` | type_alias | `payloads/Demon/include/common/Native.h:3939` | `typedef struct _KSYSTEM_TIME { ULONG LowPart;` |
| `LsaServerRole` | type_alias | `payloads/Demon/include/common/Native.h:9024` | `typedef struct _POLICY_LSA_SERVER_ROLE_INFO { POLICY_LSA_SERVER_ROLE LsaServerRole;` |
| `MAJOR_VERSION` | macro | `payloads/Demon/include/common/Native.h:7519` | `#define MAJOR_VERSION` |
| `MAKE_TAG` | macro | `payloads/Demon/include/common/Native.h:11094` | `#define MAKE_TAG( t )` |
| `MARK_HANDLE_NOT_REALTIME` | macro | `payloads/Demon/include/common/Native.h:1177` | `#define MARK_HANDLE_NOT_REALTIME` |
| `MARK_HANDLE_NOT_TXF_SYSTEM_LOG` | macro | `payloads/Demon/include/common/Native.h:1170` | `#define MARK_HANDLE_NOT_TXF_SYSTEM_LOG` |
| `MARK_HANDLE_PROTECT_CLUSTERS` | macro | `payloads/Demon/include/common/Native.h:1168` | `#define MARK_HANDLE_PROTECT_CLUSTERS` |
| `MARK_HANDLE_REALTIME` | macro | `payloads/Demon/include/common/Native.h:1176` | `#define MARK_HANDLE_REALTIME` |
| `MARK_HANDLE_TXF_SYSTEM_LOG` | macro | `payloads/Demon/include/common/Native.h:1169` | `#define MARK_HANDLE_TXF_SYSTEM_LOG` |
| `MAXIMUM_ENCRYPTION_VALUE` | macro | `payloads/Demon/include/common/Native.h:1454` | `#define MAXIMUM_ENCRYPTION_VALUE` |
| `MAXIMUM_LEADBYTES` | macro | `payloads/Demon/include/common/Native.h:3686` | `#define MAXIMUM_LEADBYTES` |
| `MAXIMUM_XSTATE_FEATURES` | macro | `payloads/Demon/include/common/Native.h:10668` | `#define MAXIMUM_XSTATE_FEATURES` |
| `MAX_EVENT_DATA_DESCRIPTORS` | macro | `payloads/Demon/include/common/Native.h:11497` | `#define MAX_EVENT_DATA_DESCRIPTORS` |
| `MAX_EVENT_FILTER_DATA_SIZE` | macro | `payloads/Demon/include/common/Native.h:11498` | `#define MAX_EVENT_FILTER_DATA_SIZE` |
| `MAX_FOREST_TRUST_BINARY_DATA_SIZE` | macro | `payloads/Demon/include/common/Native.h:9365` | `#define MAX_FOREST_TRUST_BINARY_DATA_SIZE` |
| `MAX_RECORDS_IN_FOREST_TRUST_INFO` | macro | `payloads/Demon/include/common/Native.h:9412` | `#define MAX_RECORDS_IN_FOREST_TRUST_INFO` |
| `MAX_STACK_DEPTH` | macro | `payloads/Demon/include/common/Native.h:9870` | `#define MAX_STACK_DEPTH` |
| `MAX_STACK_DEPTH` | macro | `payloads/Demon/include/common/Native.h:11238` | `#define MAX_STACK_DEPTH` |
| `MAX_WOW64_SHARED_ENTRIES` | macro | `payloads/Demon/include/common/Native.h:10655` | `#define MAX_WOW64_SHARED_ENTRIES` |
| `MDL_HASH_INDEX` | macro | `payloads/Demon/include/common/Native.h:3619` | `#define MDL_HASH_INDEX(wch)` |
| `MDL_HASH_MASK` | macro | `payloads/Demon/include/common/Native.h:3618` | `#define MDL_HASH_MASK` |
| `MDL_HASH_TABLE_SIZE` | macro | `payloads/Demon/include/common/Native.h:3617` | `#define MDL_HASH_TABLE_SIZE` |
| `MICROSECONDS` | macro | `payloads/Demon/include/common/Native.h:71` | `#define MICROSECONDS(micros)` |
| `MILLISECONDS` | macro | `payloads/Demon/include/common/Native.h:73` | `#define MILLISECONDS(milli)` |
| `MINOR_VERSION` | macro | `payloads/Demon/include/common/Native.h:7520` | `#define MINOR_VERSION` |
| `MM_WORKING_SET_MAX_HARD_DISABLE` | macro | `payloads/Demon/include/common/Native.h:5066` | `#define MM_WORKING_SET_MAX_HARD_DISABLE` |
| `MM_WORKING_SET_MAX_HARD_ENABLE` | macro | `payloads/Demon/include/common/Native.h:5065` | `#define MM_WORKING_SET_MAX_HARD_ENABLE` |
| `MM_WORKING_SET_MIN_HARD_DISABLE` | macro | `payloads/Demon/include/common/Native.h:5068` | `#define MM_WORKING_SET_MIN_HARD_DISABLE` |
| `MM_WORKING_SET_MIN_HARD_ENABLE` | macro | `payloads/Demon/include/common/Native.h:5067` | `#define MM_WORKING_SET_MIN_HARD_ENABLE` |
| `MODIFYBYTE` | macro | `payloads/Demon/include/common/Native.h:103` | `#define MODIFYBYTE( _base, _offset, _byte )` |
| `MODIFYDWORD` | macro | `payloads/Demon/include/common/Native.h:105` | `#define MODIFYDWORD( _base, _offset, _dword )` |
| `MODIFYQWORD` | macro | `payloads/Demon/include/common/Native.h:106` | `#define MODIFYQWORD( _base, _offset, _qword )` |
| `MODIFYWORD` | macro | `payloads/Demon/include/common/Native.h:104` | `#define MODIFYWORD( _base, _offset, _word )` |
| `MUTANT_ALL_ACCESS` | macro | `payloads/Demon/include/common/Native.h:3416` | `#define MUTANT_ALL_ACCESS` |
| `MUTANT_QUERY_STATE` | macro | `payloads/Demon/include/common/Native.h:3414` | `#define MUTANT_QUERY_STATE` |
| `Magic` | type_alias | `payloads/Demon/include/common/Native.h:6486` | `typedef struct _ACTIVATION_CONTEXT_DATA { ULONG Magic;` |
| `Magic` | type_alias | `payloads/Demon/include/common/Native.h:10289` | `typedef struct _RTL_TRACE_BLOCK { ULONG Magic;` |
| `MaximumCategoryCount` | type_alias | `payloads/Demon/include/common/Native.h:8986` | `typedef struct _POLICY_AUDIT_CATEGORIES_INFO { ULONG MaximumCategoryCount;` |
| `MaximumLength` | type_alias | `payloads/Demon/include/common/Native.h:5352` | `typedef struct _RTL_USER_PROCESS_PARAMETERS { ULONG MaximumLength;` |
| `MaximumLength` | type_alias | `payloads/Demon/include/common/Native.h:5502` | `typedef struct _RTL_USER_PROCESS_PARAMETERS32 { ULONG MaximumLength;` |
| `MaximumMessageSize` | type_alias | `payloads/Demon/include/common/Native.h:4114` | `typedef struct _FILE_MAILSLOT_QUERY_INFORMATION { ULONG MaximumMessageSize;` |
| `MaximumNumberOfHandles` | type_alias | `payloads/Demon/include/common/Native.h:11340` | `typedef struct _RTL_HANDLE_TABLE { ULONG MaximumNumberOfHandles;` |
| `MaximumSubCategoryCount` | type_alias | `payloads/Demon/include/common/Native.h:8979` | `typedef struct _POLICY_AUDIT_SUBCATEGORIES_INFO { ULONG MaximumSubCategoryCount;` |
| `Mode` | type_alias | `payloads/Demon/include/common/Native.h:3987` | `typedef struct _FILE_MODE_INFORMATION { ULONG Mode;` |
| `ModifiedId` | type_alias | `payloads/Demon/include/common/Native.h:9043` | `typedef struct _POLICY_MODIFICATION_INFO { LARGE_INTEGER ModifiedId;` |
| `Msr` | type_alias | `payloads/Demon/include/common/Native.h:2544` | `typedef struct _SYSDBG_MSR { ULONG Msr;` |
| `NANOSECONDS` | macro | `payloads/Demon/include/common/Native.h:69` | `#define NANOSECONDS(nanos)` |
| `NOP_FUNCTION` | macro | `payloads/Demon/include/common/Native.h:469` | `#define NOP_FUNCTION` |
| `NORMAL_BASE_PRIORITY` | macro | `payloads/Demon/include/common/Native.h:2944` | `#define NORMAL_BASE_PRIORITY` |
| `NO_8DOT3_NAME_PRESENT` | macro | `payloads/Demon/include/common/Native.h:1179` | `#define NO_8DOT3_NAME_PRESENT` |
| `NTSTATUS` | variable | `payloads/Demon/include/common/Native.h:34` | `extern "C" { #endif #include <wtypes.h> #include <basetsd.h> #if !defined(NTSTATUS) typedef LONG NTSTATUS;` |
| `NTSTATUS` | type_alias | `payloads/Demon/include/common/Native.h:41` | `typedef LONG NTSTATUS;` |
| `NT_ERROR` | macro | `payloads/Demon/include/common/Native.h:65` | `#define NT_ERROR(Status)` |
| `NT_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:63` | `#define NT_INFORMATION(Status)` |
| `NT_SUCCESS` | macro | `payloads/Demon/include/common/Native.h:62` | `#define NT_SUCCESS(Status)` |
| `NT_WARNING` | macro | `payloads/Demon/include/common/Native.h:64` | `#define NT_WARNING(Status)` |
| `NX_SUPPORT_POLICY_ALWAYSOFF` | macro | `payloads/Demon/include/common/Native.h:10649` | `#define NX_SUPPORT_POLICY_ALWAYSOFF` |
| `NX_SUPPORT_POLICY_ALWAYSON` | macro | `payloads/Demon/include/common/Native.h:10650` | `#define NX_SUPPORT_POLICY_ALWAYSON` |
| `NX_SUPPORT_POLICY_OPTIN` | macro | `payloads/Demon/include/common/Native.h:10651` | `#define NX_SUPPORT_POLICY_OPTIN` |
| `NX_SUPPORT_POLICY_OPTOUT` | macro | `payloads/Demon/include/common/Native.h:10652` | `#define NX_SUPPORT_POLICY_OPTOUT` |
| `Name` | type_alias | `payloads/Demon/include/common/Native.h:527` | `typedef struct _OBJECT_DIRECTORY_INFORMATION { UNICODE_STRING Name;` |
| `Name` | type_alias | `payloads/Demon/include/common/Native.h:3486` | `typedef struct _OBJECT_NAME_INFORMATION { UNICODE_STRING Name;` |
| `Name` | type_alias | `payloads/Demon/include/common/Native.h:8538` | `typedef struct _LSA_TRUST_INFORMATION { LSA_UNICODE_STRING Name;` |
| `Name` | type_alias | `payloads/Demon/include/common/Native.h:8568` | `typedef struct _POLICY_DNS_DOMAIN_INFO { LSA_UNICODE_STRING Name;` |
| `Name` | type_alias | `payloads/Demon/include/common/Native.h:9011` | `typedef struct _POLICY_PRIMARY_DOMAIN_INFO { LSA_UNICODE_STRING Name;` |
| `Name` | type_alias | `payloads/Demon/include/common/Native.h:9018` | `typedef struct _POLICY_PD_ACCOUNT_INFO { LSA_UNICODE_STRING Name;` |
| `Name` | type_alias | `payloads/Demon/include/common/Native.h:9154` | `typedef struct _TRUSTED_DOMAIN_NAME_INFO { LSA_UNICODE_STRING Name;` |
| `Name` | type_alias | `payloads/Demon/include/common/Native.h:9236` | `typedef struct _TRUSTED_DOMAIN_INFORMATION_EX { LSA_UNICODE_STRING Name;` |
| `Name` | type_alias | `payloads/Demon/include/common/Native.h:9247` | `typedef struct _TRUSTED_DOMAIN_INFORMATION_EX2 { LSA_UNICODE_STRING Name;` |
| `NamedPipeType` | type_alias | `payloads/Demon/include/common/Native.h:4096` | `typedef struct _FILE_PIPE_LOCAL_INFORMATION { ULONG NamedPipeType;` |
| `NewState` | type_alias | `payloads/Demon/include/common/Native.h:11050` | `typedef struct _DBGUI_WAIT_STATE_CHANGE { DBG_STATE NewState;` |
| `Next` | type_alias | `payloads/Demon/include/common/Native.h:5801` | `typedef struct _INIFILE_MAPPING_TARGET { struct _INIFILE_MAPPING_TARGET* Next;` |
| `Next` | type_alias | `payloads/Demon/include/common/Native.h:5807` | `typedef struct _INIFILE_MAPPING_VARNAME { struct _INIFILE_MAPPING_VARNAME* Next;` |
| `Next` | type_alias | `payloads/Demon/include/common/Native.h:5815` | `typedef struct _INIFILE_MAPPING_APPNAME { struct _INIFILE_MAPPING_APPNAME* Next;` |
| `Next` | type_alias | `payloads/Demon/include/common/Native.h:5823` | `typedef struct _INIFILE_MAPPING_FILENAME { struct _INIFILE_MAPPING_FILENAME* Next;` |
| `Next` | type_alias | `payloads/Demon/include/common/Native.h:11632` | `typedef struct DECLSPEC_ALIGN(16) _SLIST_ENTRY { PSLIST_ENTRY Next;` |
| `NextEntryDelta` | type_alias | `payloads/Demon/include/common/Native.h:10953` | `typedef struct _SYSTEM_PROCESSES_INFORMATION { ULONG NextEntryDelta;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4072` | `typedef struct _FILE_STREAM_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4139` | `typedef struct _FILE_FULL_EA_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4149` | `typedef struct _FILE_GET_EA_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4159` | `typedef struct _FILE_GET_QUOTA_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4165` | `typedef struct _FILE_QUOTA_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4187` | `typedef struct _FILE_DIRECTORY_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4201` | `typedef struct _FILE_FULL_DIR_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4216` | `typedef struct _FILE_ID_FULL_DIR_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4232` | `typedef struct _FILE_BOTH_DIR_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4249` | `typedef struct _FILE_ID_BOTH_DIR_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4267` | `typedef struct _FILE_NAMES_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4446` | `typedef struct _SYSTEM_SESSION_POOLTAG_INFORMATION { SIZE_T NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4500` | `typedef struct _SYSTEM_OBJECTTYPE_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4547` | `typedef struct _SYSTEM_SESSION_MAPPED_VIEW_INFORMATION { SIZE_T NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4918` | `typedef struct _SYSTEM_PROCESS_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:4998` | `typedef struct _SYSTEM_OBJECT_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:5013` | `typedef struct _SYSTEM_PAGEFILE_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:5021` | `typedef struct _SYSTEM_VERIFIER_INFORMATION { ULONG NextEntryOffset;` |
| `NextEntryOffset` | type_alias | `payloads/Demon/include/common/Native.h:9863` | `typedef struct _EFI_DRIVER_ENTRY_LIST { ULONG NextEntryOffset;` |
| `NextOffset` | type_alias | `payloads/Demon/include/common/Native.h:6647` | `typedef struct _RTL_PROCESS_MODULE_INFORMATION_EX { USHORT NextOffset;` |
| `NoEncryptedStreams` | type_alias | `payloads/Demon/include/common/Native.h:1455` | `typedef struct _DECRYPTION_STATUS_BUFFER { BOOLEAN NoEncryptedStreams;` |
| `NodeTypeCode` | type_alias | `payloads/Demon/include/common/Native.h:10067` | `typedef struct _PREFIX_TABLE_ENTRY { CSHORT NodeTypeCode;` |
| `NodeTypeCode` | type_alias | `payloads/Demon/include/common/Native.h:10076` | `typedef struct _PREFIX_TABLE { CSHORT NodeTypeCode;` |
| `NodeTypeCode` | type_alias | `payloads/Demon/include/common/Native.h:10083` | `typedef struct _UNICODE_PREFIX_TABLE_ENTRY { CSHORT NodeTypeCode;` |
| `NodeTypeCode` | type_alias | `payloads/Demon/include/common/Native.h:10093` | `typedef struct _UNICODE_PREFIX_TABLE { CSHORT NodeTypeCode;` |
| `NtCurrentPID` | macro | `payloads/Demon/include/common/Native.h:2900` | `#define NtCurrentPID()` |
| `NtCurrentPID` | macro | `payloads/Demon/include/common/Native.h:2902` | `#define NtCurrentPID()` |
| `NtCurrentPeb` | function | `payloads/Demon/include/common/Native.h:7104` | `__inline struct _PEB * NtCurrentPeb()` |
| `NtCurrentProcess` | macro | `payloads/Demon/include/common/Native.h:2891` | `#define NtCurrentProcess()` |
| `NtCurrentThread` | macro | `payloads/Demon/include/common/Native.h:2890` | `#define NtCurrentThread()` |
| `NtGetTickCount` | function | `payloads/Demon/include/common/Native.h:10907` | `__forceinline ULONG NtGetTickCount()` |
| `NtLastError` | macro | `payloads/Demon/include/common/Native.h:2896` | `#define NtLastError()` |
| `NtLastStatus` | macro | `payloads/Demon/include/common/Native.h:2897` | `#define NtLastStatus()` |
| `NtTib` | type_alias | `payloads/Demon/include/common/Native.h:5681` | `typedef struct _TEB32 { NT_TIB32 NtTib;` |
| `NtTib` | type_alias | `payloads/Demon/include/common/Native.h:6953` | `typedef struct _TEB { NT_TIB NtTib;` |
| `NumSDChangedSuccess` | type_alias | `payloads/Demon/include/common/Native.h:2293` | `typedef struct _SD_CHANGE_MACHINE_SID_OUTPUT { // // How many entries were successfully changed in the $Secure stream //` |
| `NumberOfAllocations` | type_alias | `payloads/Demon/include/common/Native.h:7212` | `typedef struct _RTL_HEAP_TAG { ULONG NumberOfAllocations;` |
| `NumberOfAllocations` | type_alias | `payloads/Demon/include/common/Native.h:11086` | `typedef struct _RTL_HEAP_TAG_INFO { ULONG NumberOfAllocations;` |
| `NumberOfAtoms` | type_alias | `payloads/Demon/include/common/Native.h:3393` | `typedef struct _ATOM_TABLE_INFORMATION { ULONG NumberOfAtoms;` |
| `NumberOfDisks` | type_alias | `payloads/Demon/include/common/Native.h:4979` | `typedef struct _SYSTEM_DEVICE_INFORMATION { ULONG NumberOfDisks;` |
| `NumberOfEntries` | type_alias | `payloads/Demon/include/common/Native.h:3324` | `typedef struct _MEMORY_WORKING_SET_INFORMATION { ULONG_PTR NumberOfEntries;` |
| `NumberOfEntries` | type_alias | `payloads/Demon/include/common/Native.h:9876` | `typedef struct _RTL_STACK_CONTEXT { ULONG NumberOfEntries;` |
| `NumberOfHandles` | type_alias | `payloads/Demon/include/common/Native.h:4469` | `typedef struct _SYSTEM_HANDLE_INFORMATION { ULONG NumberOfHandles;` |
| `NumberOfHandles` | type_alias | `payloads/Demon/include/common/Native.h:4487` | `typedef struct _SYSTEM_HANDLE_INFORMATION_EX { ULONG NumberOfHandles;` |
| `NumberOfHeaps` | type_alias | `payloads/Demon/include/common/Native.h:7239` | `typedef struct _RTL_PROCESS_HEAPS { ULONG NumberOfHeaps;` |
| `NumberOfLocks` | type_alias | `payloads/Demon/include/common/Native.h:11232` | `typedef struct _RTL_PROCESS_LOCKS { ULONG NumberOfLocks;` |
| `NumberOfMcbPairs` | type_alias | `payloads/Demon/include/common/Native.h:4515` | `typedef struct _SYSTEM_HIBERFILE_INFORMATION { ULONG NumberOfMcbPairs;` |
| `NumberOfModules` | type_alias | `payloads/Demon/include/common/Native.h:6641` | `typedef struct _RTL_PROCESS_MODULES { ULONG NumberOfModules;` |
| `NumberOfTransactions` | type_alias | `payloads/Demon/include/common/Native.h:2057` | `typedef struct _TXFS_LIST_TRANSACTIONS { // // On output, the number of transactions involved in this RM. // ULONGLONG N` |
| `NumberOfTypes` | type_alias | `payloads/Demon/include/common/Native.h:3515` | `typedef struct _OBJECT_TYPES_INFORMATION { ULONG NumberOfTypes;` |
| `OBJECT_TYPE_ALL_ACCESS` | macro | `payloads/Demon/include/common/Native.h:3452` | `#define OBJECT_TYPE_ALL_ACCESS` |
| `OBJECT_TYPE_CREATE` | macro | `payloads/Demon/include/common/Native.h:3451` | `#define OBJECT_TYPE_CREATE` |
| `OBJ_CASE_INSENSITIVE` | macro | `payloads/Demon/include/common/Native.h:489` | `#define OBJ_CASE_INSENSITIVE` |
| `OBJ_EXCLUSIVE` | macro | `payloads/Demon/include/common/Native.h:488` | `#define OBJ_EXCLUSIVE` |
| `OBJ_FORCE_ACCESS_CHECK` | macro | `payloads/Demon/include/common/Native.h:493` | `#define OBJ_FORCE_ACCESS_CHECK` |
| `OBJ_HANDLE_TAGBITS` | macro | `payloads/Demon/include/common/Native.h:486` | `#define OBJ_HANDLE_TAGBITS` |
| `OBJ_INHERIT` | macro | `payloads/Demon/include/common/Native.h:485` | `#define OBJ_INHERIT` |
| `OBJ_KERNEL_HANDLE` | macro | `payloads/Demon/include/common/Native.h:492` | `#define OBJ_KERNEL_HANDLE` |
| `OBJ_MAX_REPARSE_ATTEMPTS` | macro | `payloads/Demon/include/common/Native.h:3450` | `#define OBJ_MAX_REPARSE_ATTEMPTS` |
| `OBJ_NAME_PATH_SEPARATOR` | macro | `payloads/Demon/include/common/Native.h:3449` | `#define OBJ_NAME_PATH_SEPARATOR` |
| `OBJ_OPENIF` | macro | `payloads/Demon/include/common/Native.h:490` | `#define OBJ_OPENIF` |
| `OBJ_OPENLINK` | macro | `payloads/Demon/include/common/Native.h:491` | `#define OBJ_OPENLINK` |
| `OBJ_PERMANENT` | macro | `payloads/Demon/include/common/Native.h:487` | `#define OBJ_PERMANENT` |
| `OBJ_VALID_ATTRIBUTES` | macro | `payloads/Demon/include/common/Native.h:494` | `#define OBJ_VALID_ATTRIBUTES` |
| `OEM_STRING` | type_alias | `payloads/Demon/include/common/Native.h:377` | `typedef STRING OEM_STRING;` |
| `OPLOCK_LEVEL_CACHE_HANDLE` | macro | `payloads/Demon/include/common/Native.h:2227` | `#define OPLOCK_LEVEL_CACHE_HANDLE` |
| `OPLOCK_LEVEL_CACHE_READ` | macro | `payloads/Demon/include/common/Native.h:2226` | `#define OPLOCK_LEVEL_CACHE_READ` |
| `OPLOCK_LEVEL_CACHE_WRITE` | macro | `payloads/Demon/include/common/Native.h:2228` | `#define OPLOCK_LEVEL_CACHE_WRITE` |
| `OS2_VERSION` | macro | `payloads/Demon/include/common/Native.h:7521` | `#define OS2_VERSION` |
| `Object` | type_alias | `payloads/Demon/include/common/Native.h:4475` | `typedef struct _SYSTEM_HANDLE_TABLE_ENTRY_INFO_EX { PVOID Object;` |
| `Object` | type_alias | `payloads/Demon/include/common/Native.h:5297` | `typedef struct _GDI_HANDLE_ENTRY { union { PVOID Object;` |
| `ObjectDirectory` | type_alias | `payloads/Demon/include/common/Native.h:5905` | `typedef struct _CSR_API_CONNECTINFO { HANDLE ObjectDirectory;` |
| `ObjectId` | type_alias | `payloads/Demon/include/common/Native.h:1383` | `typedef struct _FILE_OBJECTID_BUFFER { UCHAR ObjectId[16];` |
| `ObjectType` | type_alias | `payloads/Demon/include/common/Native.h:8714` | `typedef struct _SE_ADT_OBJECT_TYPE { GUID ObjectType;` |
| `OemTableInfo` | type_alias | `payloads/Demon/include/common/Native.h:3702` | `typedef struct _NLSTABLEINFO { CPTABLEINFO OemTableInfo;` |
| `Offset` | type_alias | `payloads/Demon/include/common/Native.h:1963` | `typedef struct _TXFS_LIST_TRANSACTION_LOCKED_FILES_ENTRY { // // Offset in bytes from the beginning of the TXFS_LIST_TRA` |
| `Offset` | type_alias | `payloads/Demon/include/common/Native.h:2420` | `typedef struct _LOOKUP_STREAM_FROM_CLUSTER_OUTPUT { ULONG Offset;` |
| `Offset` | type_alias | `payloads/Demon/include/common/Native.h:5643` | `typedef struct _GDI_TEB_BATCH32 { ULONG Offset;` |
| `Offset` | type_alias | `payloads/Demon/include/common/Native.h:6441` | `typedef struct _GDI_TEB_BATCH { ULONG Offset;` |
| `Offset` | type_alias | `payloads/Demon/include/common/Native.h:9167` | `typedef struct _TRUSTED_POSIX_OFFSET_INFO { ULONG Offset;` |
| `Offset` | type_alias | `payloads/Demon/include/common/Native.h:10674` | `typedef struct _XSTATE_FEATURE { DWORD Offset;` |
| `OffsetToNext` | type_alias | `payloads/Demon/include/common/Native.h:2436` | `typedef struct _LOOKUP_STREAM_FROM_CLUSTER_ENTRY { ULONG OffsetToNext;` |
| `OldStackBase` | type_alias | `payloads/Demon/include/common/Native.h:6532` | `typedef struct _INITIAL_TEB { struct { PVOID OldStackBase;` |
| `OperationCount` | type_alias | `payloads/Demon/include/common/Native.h:3669` | `typedef struct _RTL_RXACT_LOG { ULONG OperationCount;` |
| `OwnerThread` | type_alias | `payloads/Demon/include/common/Native.h:10395` | `typedef struct _OWNER_ENTRY { ULONG OwnerThread;` |
| `PAGED_CODE` | macro | `payloads/Demon/include/common/Native.h:471` | `#define PAGED_CODE()` |
| `PAGE_SIZE` | macro | `payloads/Demon/include/common/Native.h:52` | `#define PAGE_SIZE` |
| `PANSI_STRING` | type_alias | `payloads/Demon/include/common/Native.h:376` | `typedef PSTRING PANSI_STRING;` |
| `PCACTIVATION_CONTEXT_RUN_LEVEL_INFORMATION` | type_alias | `payloads/Demon/include/common/Native.h:6226` | `typedef const struct _ACTIVATION_CONTEXT_RUN_LEVEL_INFORMATION * PCACTIVATION_CONTEXT_RUN_LEVEL_INFORMATION;` |
| `PCACTIVATION_CONTEXT_STACK` | type_alias | `payloads/Demon/include/common/Native.h:6911` | `typedef const ACTIVATION_CONTEXT_STACK * PCACTIVATION_CONTEXT_STACK;` |
| `PCANSI_STRING` | type_alias | `payloads/Demon/include/common/Native.h:392` | `typedef PSTRING PCANSI_STRING;` |
| `PCOEM_STRING` | type_alias | `payloads/Demon/include/common/Native.h:380` | `typedef CONST STRING* PCOEM_STRING;` |
| `PEB_STDIO_HANDLE_NATIVE` | macro | `payloads/Demon/include/common/Native.h:2925` | `#define PEB_STDIO_HANDLE_NATIVE` |
| `PEB_STDIO_HANDLE_PM` | macro | `payloads/Demon/include/common/Native.h:2927` | `#define PEB_STDIO_HANDLE_PM` |
| `PEB_STDIO_HANDLE_RESERVED` | macro | `payloads/Demon/include/common/Native.h:2928` | `#define PEB_STDIO_HANDLE_RESERVED` |
| `PEB_STDIO_HANDLE_SUBSYS` | macro | `payloads/Demon/include/common/Native.h:2926` | `#define PEB_STDIO_HANDLE_SUBSYS` |
| `PERSISTENT_VOLUME_STATE_SHORT_NAME_CREATION_DISABLED` | macro | `payloads/Demon/include/common/Native.h:1182` | `#define PERSISTENT_VOLUME_STATE_SHORT_NAME_CREATION_DISABLED` |
| `PER_USER_AUDIT_FAILURE_EXCLUDE` | macro | `payloads/Demon/include/common/Native.h:9002` | `#define PER_USER_AUDIT_FAILURE_EXCLUDE` |
| `PER_USER_AUDIT_FAILURE_INCLUDE` | macro | `payloads/Demon/include/common/Native.h:9001` | `#define PER_USER_AUDIT_FAILURE_INCLUDE` |
| `PER_USER_AUDIT_NONE` | macro | `payloads/Demon/include/common/Native.h:9003` | `#define PER_USER_AUDIT_NONE` |
| `PER_USER_AUDIT_SUCCESS_EXCLUDE` | macro | `payloads/Demon/include/common/Native.h:9000` | `#define PER_USER_AUDIT_SUCCESS_EXCLUDE` |
| `PER_USER_AUDIT_SUCCESS_INCLUDE` | macro | `payloads/Demon/include/common/Native.h:8999` | `#define PER_USER_AUDIT_SUCCESS_INCLUDE` |
| `PER_USER_POLICY_UNCHANGED` | macro | `payloads/Demon/include/common/Native.h:8998` | `#define PER_USER_POLICY_UNCHANGED` |
| `PF_3DNOW_INSTRUCTIONS_AVAILABLE` | macro | `payloads/Demon/include/common/Native.h:4785` | `#define PF_3DNOW_INSTRUCTIONS_AVAILABLE` |
| `PF_ALPHA_BYTE_INSTRUCTIONS` | macro | `payloads/Demon/include/common/Native.h:4783` | `#define PF_ALPHA_BYTE_INSTRUCTIONS` |
| `PF_CHANNELS_ENABLED` | macro | `payloads/Demon/include/common/Native.h:4794` | `#define PF_CHANNELS_ENABLED` |
| `PF_COMPARE64_EXCHANGE128` | macro | `payloads/Demon/include/common/Native.h:4793` | `#define PF_COMPARE64_EXCHANGE128` |
| `PF_COMPARE_EXCHANGE128` | macro | `payloads/Demon/include/common/Native.h:4792` | `#define PF_COMPARE_EXCHANGE128` |
| `PF_COMPARE_EXCHANGE_DOUBLE` | macro | `payloads/Demon/include/common/Native.h:4780` | `#define PF_COMPARE_EXCHANGE_DOUBLE` |
| `PF_FLOATING_POINT_EMULATED` | macro | `payloads/Demon/include/common/Native.h:4779` | `#define PF_FLOATING_POINT_EMULATED` |
| `PF_FLOATING_POINT_PRECISION_ERRATA` | macro | `payloads/Demon/include/common/Native.h:4778` | `#define PF_FLOATING_POINT_PRECISION_ERRATA` |
| `PF_MMX_INSTRUCTIONS_AVAILABLE` | macro | `payloads/Demon/include/common/Native.h:4781` | `#define PF_MMX_INSTRUCTIONS_AVAILABLE` |
| `PF_NX_ENABLED` | macro | `payloads/Demon/include/common/Native.h:4790` | `#define PF_NX_ENABLED` |
| `PF_PAE_ENABLED` | macro | `payloads/Demon/include/common/Native.h:4787` | `#define PF_PAE_ENABLED` |
| `PF_PPC_MOVEMEM_64BIT_OK` | macro | `payloads/Demon/include/common/Native.h:4782` | `#define PF_PPC_MOVEMEM_64BIT_OK` |
| `PF_RDTSC_INSTRUCTION_AVAILABLE` | macro | `payloads/Demon/include/common/Native.h:4786` | `#define PF_RDTSC_INSTRUCTION_AVAILABLE` |
| `PF_SSE3_INSTRUCTIONS_AVAILABLE` | macro | `payloads/Demon/include/common/Native.h:4791` | `#define PF_SSE3_INSTRUCTIONS_AVAILABLE` |
| `PF_SSE_DAZ_MODE_AVAILABLE` | macro | `payloads/Demon/include/common/Native.h:4789` | `#define PF_SSE_DAZ_MODE_AVAILABLE` |
| `PF_XMMI64_INSTRUCTIONS_AVAILABLE` | macro | `payloads/Demon/include/common/Native.h:4788` | `#define PF_XMMI64_INSTRUCTIONS_AVAILABLE` |
| `PF_XMMI_INSTRUCTIONS_AVAILABLE` | macro | `payloads/Demon/include/common/Native.h:4784` | `#define PF_XMMI_INSTRUCTIONS_AVAILABLE` |
| `PIO_APC_ROUTINE_DEFINED` | macro | `payloads/Demon/include/common/Native.h:3277` | `#define PIO_APC_ROUTINE_DEFINED` |
| `POEM_STRING` | type_alias | `payloads/Demon/include/common/Native.h:379` | `typedef PSTRING POEM_STRING;` |
| `POI` | macro | `payloads/Demon/include/common/Native.h:90` | `#define POI(addr)` |
| `POINTER_32` | macro | `payloads/Demon/include/common/Native.h:7305` | `#define POINTER_32` |
| `POINTER_32` | macro | `payloads/Demon/include/common/Native.h:7307` | `#define POINTER_32` |
| `POINTER_64` | macro | `payloads/Demon/include/common/Native.h:7302` | `#define POINTER_64` |
| `POINTER_64_INT` | type_alias | `payloads/Demon/include/common/Native.h:7303` | `typedef unsigned __int64 POINTER_64_INT;` |
| `POINTER_IS_ALIGNED` | macro | `payloads/Demon/include/common/Native.h:636` | `#define POINTER_IS_ALIGNED(Ptr,Pow2)` |
| `POLICY_ALL_ACCESS` | macro | `payloads/Demon/include/common/Native.h:8881` | `#define POLICY_ALL_ACCESS` |
| `POLICY_AUDIT_EVENT_FAILURE` | macro | `payloads/Demon/include/common/Native.h:8785` | `#define POLICY_AUDIT_EVENT_FAILURE` |
| `POLICY_AUDIT_EVENT_MASK` | macro | `payloads/Demon/include/common/Native.h:8788` | `#define POLICY_AUDIT_EVENT_MASK` |
| `POLICY_AUDIT_EVENT_NONE` | macro | `payloads/Demon/include/common/Native.h:8786` | `#define POLICY_AUDIT_EVENT_NONE` |
| `POLICY_AUDIT_EVENT_SUCCESS` | macro | `payloads/Demon/include/common/Native.h:8784` | `#define POLICY_AUDIT_EVENT_SUCCESS` |
| `POLICY_AUDIT_EVENT_UNCHANGED` | macro | `payloads/Demon/include/common/Native.h:8783` | `#define POLICY_AUDIT_EVENT_UNCHANGED` |
| `POLICY_AUDIT_LOG_ADMIN` | macro | `payloads/Demon/include/common/Native.h:8876` | `#define POLICY_AUDIT_LOG_ADMIN` |
| `POLICY_CREATE_ACCOUNT` | macro | `payloads/Demon/include/common/Native.h:8871` | `#define POLICY_CREATE_ACCOUNT` |
| `POLICY_CREATE_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:8873` | `#define POLICY_CREATE_PRIVILEGE` |
| `POLICY_CREATE_SECRET` | macro | `payloads/Demon/include/common/Native.h:8872` | `#define POLICY_CREATE_SECRET` |
| `POLICY_EXECUTE` | macro | `payloads/Demon/include/common/Native.h:8910` | `#define POLICY_EXECUTE` |
| `POLICY_GET_PRIVATE_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:8869` | `#define POLICY_GET_PRIVATE_INFORMATION` |
| `POLICY_KERBEROS_VALIDATE_CLIENT` | macro | `payloads/Demon/include/common/Native.h:9110` | `#define POLICY_KERBEROS_VALIDATE_CLIENT` |
| `POLICY_LOOKUP_NAMES` | macro | `payloads/Demon/include/common/Native.h:8878` | `#define POLICY_LOOKUP_NAMES` |
| `POLICY_NOTIFICATION` | macro | `payloads/Demon/include/common/Native.h:8879` | `#define POLICY_NOTIFICATION` |
| `POLICY_QOS_ALLOW_LOCAL_ROOT_CERT_STORE` | macro | `payloads/Demon/include/common/Native.h:9085` | `#define POLICY_QOS_ALLOW_LOCAL_ROOT_CERT_STORE` |
| `POLICY_QOS_DHCP_SERVER_ALLOWED` | macro | `payloads/Demon/include/common/Native.h:9087` | `#define POLICY_QOS_DHCP_SERVER_ALLOWED` |
| `POLICY_QOS_INBOUND_CONFIDENTIALITY` | macro | `payloads/Demon/include/common/Native.h:9084` | `#define POLICY_QOS_INBOUND_CONFIDENTIALITY` |
| `POLICY_QOS_INBOUND_INTEGRITY` | macro | `payloads/Demon/include/common/Native.h:9083` | `#define POLICY_QOS_INBOUND_INTEGRITY` |
| `POLICY_QOS_OUTBOUND_CONFIDENTIALITY` | macro | `payloads/Demon/include/common/Native.h:9082` | `#define POLICY_QOS_OUTBOUND_CONFIDENTIALITY` |
| `POLICY_QOS_OUTBOUND_INTEGRITY` | macro | `payloads/Demon/include/common/Native.h:9081` | `#define POLICY_QOS_OUTBOUND_INTEGRITY` |
| `POLICY_QOS_RAS_SERVER_ALLOWED` | macro | `payloads/Demon/include/common/Native.h:9086` | `#define POLICY_QOS_RAS_SERVER_ALLOWED` |
| `POLICY_QOS_SCHANNEL_REQUIRED` | macro | `payloads/Demon/include/common/Native.h:9080` | `#define POLICY_QOS_SCHANNEL_REQUIRED` |
| `POLICY_READ` | macro | `payloads/Demon/include/common/Native.h:8896` | `#define POLICY_READ` |
| `POLICY_SERVER_ADMIN` | macro | `payloads/Demon/include/common/Native.h:8877` | `#define POLICY_SERVER_ADMIN` |
| `POLICY_SET_AUDIT_REQUIREMENTS` | macro | `payloads/Demon/include/common/Native.h:8875` | `#define POLICY_SET_AUDIT_REQUIREMENTS` |
| `POLICY_SET_DEFAULT_QUOTA_LIMITS` | macro | `payloads/Demon/include/common/Native.h:8874` | `#define POLICY_SET_DEFAULT_QUOTA_LIMITS` |
| `POLICY_TRUST_ADMIN` | macro | `payloads/Demon/include/common/Native.h:8870` | `#define POLICY_TRUST_ADMIN` |
| `POLICY_VIEW_AUDIT_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:8868` | `#define POLICY_VIEW_AUDIT_INFORMATION` |
| `POLICY_VIEW_LOCAL_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:8867` | `#define POLICY_VIEW_LOCAL_INFORMATION` |
| `POLICY_WRITE` | macro | `payloads/Demon/include/common/Native.h:8900` | `#define POLICY_WRITE` |
| `PORT_ALL_ACCESS` | macro | `payloads/Demon/include/common/Native.h:5842` | `#define PORT_ALL_ACCESS` |
| `PORT_CONNECT` | macro | `payloads/Demon/include/common/Native.h:5840` | `#define PORT_CONNECT` |
| `POWER_INFORMATION_LEVEL` | enum | `payloads/Demon/include/common/Native.h:3133` | `` |
| `PPVOID` | type_alias | `payloads/Demon/include/common/Native.h:6468` | `typedef PVOID* PPVOID;` |
| `PREALLOCATE_EVENT_MASK` | macro | `payloads/Demon/include/common/Native.h:11175` | `#define PREALLOCATE_EVENT_MASK` |
| `PROCESSOR_ALPHA_21064` | macro | `payloads/Demon/include/common/Native.h:4746` | `#define PROCESSOR_ALPHA_21064` |
| `PROCESSOR_AMD_X8664` | macro | `payloads/Demon/include/common/Native.h:4744` | `#define PROCESSOR_AMD_X8664` |
| `PROCESSOR_ARCHITECTURE_ALPHA` | macro | `payloads/Demon/include/common/Native.h:4766` | `#define PROCESSOR_ARCHITECTURE_ALPHA` |
| `PROCESSOR_ARCHITECTURE_ALPHA64` | macro | `payloads/Demon/include/common/Native.h:4771` | `#define PROCESSOR_ARCHITECTURE_ALPHA64` |
| `PROCESSOR_ARCHITECTURE_AMD64` | macro | `payloads/Demon/include/common/Native.h:4773` | `#define PROCESSOR_ARCHITECTURE_AMD64` |
| `PROCESSOR_ARCHITECTURE_ARM` | macro | `payloads/Demon/include/common/Native.h:4769` | `#define PROCESSOR_ARCHITECTURE_ARM` |
| `PROCESSOR_ARCHITECTURE_IA32_ON_WIN64` | macro | `payloads/Demon/include/common/Native.h:4774` | `#define PROCESSOR_ARCHITECTURE_IA32_ON_WIN64` |
| `PROCESSOR_ARCHITECTURE_IA64` | macro | `payloads/Demon/include/common/Native.h:4770` | `#define PROCESSOR_ARCHITECTURE_IA64` |
| `PROCESSOR_ARCHITECTURE_INTEL` | macro | `payloads/Demon/include/common/Native.h:4764` | `#define PROCESSOR_ARCHITECTURE_INTEL` |
| `PROCESSOR_ARCHITECTURE_MIPS` | macro | `payloads/Demon/include/common/Native.h:4765` | `#define PROCESSOR_ARCHITECTURE_MIPS` |
| `PROCESSOR_ARCHITECTURE_MSIL` | macro | `payloads/Demon/include/common/Native.h:4772` | `#define PROCESSOR_ARCHITECTURE_MSIL` |
| `PROCESSOR_ARCHITECTURE_PPC` | macro | `payloads/Demon/include/common/Native.h:4767` | `#define PROCESSOR_ARCHITECTURE_PPC` |
| `PROCESSOR_ARCHITECTURE_SHX` | macro | `payloads/Demon/include/common/Native.h:4768` | `#define PROCESSOR_ARCHITECTURE_SHX` |
| `PROCESSOR_ARCHITECTURE_UNKNOWN` | macro | `payloads/Demon/include/common/Native.h:4776` | `#define PROCESSOR_ARCHITECTURE_UNKNOWN` |
| `PROCESSOR_ARM720` | macro | `payloads/Demon/include/common/Native.h:4758` | `#define PROCESSOR_ARM720` |
| `PROCESSOR_ARM820` | macro | `payloads/Demon/include/common/Native.h:4759` | `#define PROCESSOR_ARM820` |
| `PROCESSOR_ARM920` | macro | `payloads/Demon/include/common/Native.h:4760` | `#define PROCESSOR_ARM920` |
| `PROCESSOR_ARM_7TDMI` | macro | `payloads/Demon/include/common/Native.h:4761` | `#define PROCESSOR_ARM_7TDMI` |
| `PROCESSOR_FEATURE_MAX` | macro | `payloads/Demon/include/common/Native.h:10654` | `#define PROCESSOR_FEATURE_MAX` |
| `PROCESSOR_HITACHI_SH3` | macro | `payloads/Demon/include/common/Native.h:4751` | `#define PROCESSOR_HITACHI_SH3` |
| `PROCESSOR_HITACHI_SH3E` | macro | `payloads/Demon/include/common/Native.h:4752` | `#define PROCESSOR_HITACHI_SH3E` |
| `PROCESSOR_HITACHI_SH4` | macro | `payloads/Demon/include/common/Native.h:4753` | `#define PROCESSOR_HITACHI_SH4` |
| `PROCESSOR_INTEL_386` | macro | `payloads/Demon/include/common/Native.h:4740` | `#define PROCESSOR_INTEL_386` |
| `PROCESSOR_INTEL_486` | macro | `payloads/Demon/include/common/Native.h:4741` | `#define PROCESSOR_INTEL_486` |
| `PROCESSOR_INTEL_IA64` | macro | `payloads/Demon/include/common/Native.h:4743` | `#define PROCESSOR_INTEL_IA64` |
| `PROCESSOR_INTEL_PENTIUM` | macro | `payloads/Demon/include/common/Native.h:4742` | `#define PROCESSOR_INTEL_PENTIUM` |
| `PROCESSOR_MIPS_R4000` | macro | `payloads/Demon/include/common/Native.h:4745` | `#define PROCESSOR_MIPS_R4000` |
| `PROCESSOR_MOTOROLA_821` | macro | `payloads/Demon/include/common/Native.h:4754` | `#define PROCESSOR_MOTOROLA_821` |
| `PROCESSOR_OPTIL` | macro | `payloads/Demon/include/common/Native.h:4762` | `#define PROCESSOR_OPTIL` |
| `PROCESSOR_PPC_601` | macro | `payloads/Demon/include/common/Native.h:4747` | `#define PROCESSOR_PPC_601` |
| `PROCESSOR_PPC_603` | macro | `payloads/Demon/include/common/Native.h:4748` | `#define PROCESSOR_PPC_603` |
| `PROCESSOR_PPC_604` | macro | `payloads/Demon/include/common/Native.h:4749` | `#define PROCESSOR_PPC_604` |
| `PROCESSOR_PPC_620` | macro | `payloads/Demon/include/common/Native.h:4750` | `#define PROCESSOR_PPC_620` |
| `PROCESSOR_SHx_SH3` | macro | `payloads/Demon/include/common/Native.h:4755` | `#define PROCESSOR_SHx_SH3` |
| `PROCESSOR_SHx_SH4` | macro | `payloads/Demon/include/common/Native.h:4756` | `#define PROCESSOR_SHx_SH4` |
| `PROCESSOR_STRONGARM` | macro | `payloads/Demon/include/common/Native.h:4757` | `#define PROCESSOR_STRONGARM` |
| `PROCESS_CREATE_PROCESS` | macro | `payloads/Demon/include/common/Native.h:2883` | `#define PROCESS_CREATE_PROCESS` |
| `PROCESS_CREATE_THREAD` | macro | `payloads/Demon/include/common/Native.h:2877` | `#define PROCESS_CREATE_THREAD` |
| `PROCESS_DUP_HANDLE` | macro | `payloads/Demon/include/common/Native.h:2882` | `#define PROCESS_DUP_HANDLE` |
| `PROCESS_PRIORITY_CLASS_ABOVE_NORMAL` | macro | `payloads/Demon/include/common/Native.h:7541` | `#define PROCESS_PRIORITY_CLASS_ABOVE_NORMAL` |
| `PROCESS_PRIORITY_CLASS_BELOW_NORMAL` | macro | `payloads/Demon/include/common/Native.h:7540` | `#define PROCESS_PRIORITY_CLASS_BELOW_NORMAL` |
| `PROCESS_PRIORITY_CLASS_HIGH` | macro | `payloads/Demon/include/common/Native.h:7538` | `#define PROCESS_PRIORITY_CLASS_HIGH` |
| `PROCESS_PRIORITY_CLASS_IDLE` | macro | `payloads/Demon/include/common/Native.h:7536` | `#define PROCESS_PRIORITY_CLASS_IDLE` |
| `PROCESS_PRIORITY_CLASS_NORMAL` | macro | `payloads/Demon/include/common/Native.h:7537` | `#define PROCESS_PRIORITY_CLASS_NORMAL` |
| `PROCESS_PRIORITY_CLASS_REALTIME` | macro | `payloads/Demon/include/common/Native.h:7539` | `#define PROCESS_PRIORITY_CLASS_REALTIME` |
| `PROCESS_PRIORITY_CLASS_UNKNOWN` | macro | `payloads/Demon/include/common/Native.h:7535` | `#define PROCESS_PRIORITY_CLASS_UNKNOWN` |
| `PROCESS_QUERY_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:2886` | `#define PROCESS_QUERY_INFORMATION` |
| `PROCESS_SET_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:2885` | `#define PROCESS_SET_INFORMATION` |
| `PROCESS_SET_PORT` | macro | `payloads/Demon/include/common/Native.h:2887` | `#define PROCESS_SET_PORT` |
| `PROCESS_SET_QUOTA` | macro | `payloads/Demon/include/common/Native.h:2884` | `#define PROCESS_SET_QUOTA` |
| `PROCESS_SET_SESSIONID` | macro | `payloads/Demon/include/common/Native.h:2878` | `#define PROCESS_SET_SESSIONID` |
| `PROCESS_SUSPEND_RESUME` | macro | `payloads/Demon/include/common/Native.h:2888` | `#define PROCESS_SUSPEND_RESUME` |
| `PROCESS_TERMINATE` | macro | `payloads/Demon/include/common/Native.h:2876` | `#define PROCESS_TERMINATE` |
| `PROCESS_VM_OPERATION` | macro | `payloads/Demon/include/common/Native.h:2879` | `#define PROCESS_VM_OPERATION` |
| `PROCESS_VM_READ` | macro | `payloads/Demon/include/common/Native.h:2880` | `#define PROCESS_VM_READ` |
| `PROCESS_VM_WRITE` | macro | `payloads/Demon/include/common/Native.h:2881` | `#define PROCESS_VM_WRITE` |
| `PRTL_OSVERSIONINFOEXW` | type_alias | `payloads/Demon/include/common/Native.h:14763` | `typedef POSVERSIONINFOEXW PRTL_OSVERSIONINFOEXW;` |
| `PRTL_OSVERSIONINFOW` | type_alias | `payloads/Demon/include/common/Native.h:14762` | `typedef POSVERSIONINFOW PRTL_OSVERSIONINFOW;` |
| `PRTL_TRACE_DATABASE` | type_alias | `payloads/Demon/include/common/Native.h:10304` | `typedef struct _RTL_TRACE_DATABASE * PRTL_TRACE_DATABASE;` |
| `PSLIST_ENTRY` | macro | `payloads/Demon/include/common/Native.h:11641` | `#define PSLIST_ENTRY` |
| `PTRUSTED_DOMAIN_INFORMATION_BASIC` | type_alias | `payloads/Demon/include/common/Native.h:9180` | `typedef PLSA_TRUST_INFORMATION PTRUSTED_DOMAIN_INFORMATION_BASIC;` |
| `PTR_ADD_OFFSET` | macro | `payloads/Demon/include/common/Native.h:108` | `#define PTR_ADD_OFFSET(Pointer, Offset)` |
| `Password` | type_alias | `payloads/Demon/include/common/Native.h:9173` | `typedef struct _TRUSTED_PASSWORD_INFO { LSA_UNICODE_STRING Password;` |
| `PatchList` | type_alias | `payloads/Demon/include/common/Native.h:11593` | `typedef struct _RTL_PATCH_HEADER { LIST_ENTRY PatchList;` |
| `PathNameLength` | type_alias | `payloads/Demon/include/common/Native.h:901` | `typedef struct _PATHNAME_BUFFER { ULONG PathNameLength;` |
| `PcTeb` | macro | `payloads/Demon/include/common/Native.h:7096` | `#define PcTeb` |
| `PeakVirtualSize` | type_alias | `payloads/Demon/include/common/Native.h:10923` | `typedef struct _VM_COUNTERS { SIZE_T PeakVirtualSize;` |
| `PoolTag` | type_alias | `payloads/Demon/include/common/Native.h:4494` | `typedef struct _SYSTEM_SPECIAL_POOL_INFORMATION { ULONG PoolTag;` |
| `Port` | type_alias | `payloads/Demon/include/common/Native.h:4086` | `typedef struct _FILE_COMPLETION_INFORMATION { HANDLE Port;` |
| `Previous` | type_alias | `payloads/Demon/include/common/Native.h:6894` | `typedef struct _RTL_ACTIVATION_CONTEXT_STACK_FRAME { struct _RTL_ACTIVATION_CONTEXT_STACK_FRAME* Previous;` |
| `Process` | type_alias | `payloads/Demon/include/common/Native.h:10915` | `typedef struct _RTL_PROCESS_REFLECTION_INFORMATION { HANDLE Process;` |
| `ProcessHandle` | type_alias | `payloads/Demon/include/common/Native.h:6243` | `typedef struct _BASE_CREATEPROCESS_MSG { PVOID ProcessHandle;` |
| `ProcessorArchitecture` | type_alias | `payloads/Demon/include/common/Native.h:4658` | `typedef struct _SYSTEM_PROCESSOR_INFORMATION { USHORT ProcessorArchitecture;` |
| `ProcessorMask` | type_alias | `payloads/Demon/include/common/Native.h:4724` | `typedef struct _SYSTEM_LOGICAL_PROCESSOR_INFORMATION { ULONG_PTR ProcessorMask;` |
| `Ptr` | type_alias | `payloads/Demon/include/common/Native.h:11191` | `typedef struct _RTL_SRWLOCK { PVOID Ptr;` |
| `Ptr` | type_alias | `payloads/Demon/include/common/Native.h:11504` | `typedef struct _EVENT_DATA_DESCRIPTOR { ULONG_PTR Ptr;` |
| `Ptr` | type_alias | `payloads/Demon/include/common/Native.h:11528` | `typedef struct _EVENT_FILTER_DESCRIPTOR { ULONG_PTR Ptr;` |
| `QUAD_ALIGN` | macro | `payloads/Demon/include/common/Native.h:687` | `#define QUAD_ALIGN(VALUE)` |
| `QualityOfService` | type_alias | `payloads/Demon/include/common/Native.h:9095` | `typedef struct _POLICY_DOMAIN_QUALITY_OF_SERVICE_INFO { ULONG QualityOfService;` |
| `QueryRoutine` | type_alias | `payloads/Demon/include/common/Native.h:7505` | `typedef struct _RTL_QUERY_REGISTRY_TABLE { PRTL_QUERY_REGISTRY_ROUTINE QueryRoutine;` |
| `QuotaLimits` | type_alias | `payloads/Demon/include/common/Native.h:9037` | `typedef struct _POLICY_DEFAULT_QUOTA_INFO { QUOTA_LIMITS QuotaLimits;` |
| `RELATIVE_TIME` | macro | `payloads/Demon/include/common/Native.h:68` | `#define RELATIVE_TIME(wait)` |
| `RELOC_SIZE` | macro | `payloads/Demon/include/common/Native.h:700` | `#define RELOC_SIZE(x)` |
| `RELOC_VA` | macro | `payloads/Demon/include/common/Native.h:695` | `#define RELOC_VA(x)` |
| `REMOVED_8DOT3_NAME` | macro | `payloads/Demon/include/common/Native.h:1180` | `#define REMOVED_8DOT3_NAME` |
| `REQUEST_OPLOCK_CURRENT_VERSION` | macro | `payloads/Demon/include/common/Native.h:2234` | `#define REQUEST_OPLOCK_CURRENT_VERSION` |
| `REQUEST_OPLOCK_INPUT_FLAG_ACK` | macro | `payloads/Demon/include/common/Native.h:2231` | `#define REQUEST_OPLOCK_INPUT_FLAG_ACK` |
| `REQUEST_OPLOCK_INPUT_FLAG_COMPLETE_ACK_ON_CLOSE` | macro | `payloads/Demon/include/common/Native.h:2232` | `#define REQUEST_OPLOCK_INPUT_FLAG_COMPLETE_ACK_ON_CLOSE` |
| `REQUEST_OPLOCK_INPUT_FLAG_REQUEST` | macro | `payloads/Demon/include/common/Native.h:2230` | `#define REQUEST_OPLOCK_INPUT_FLAG_REQUEST` |
| `REQUEST_OPLOCK_OUTPUT_FLAG_ACK_REQUIRED` | macro | `payloads/Demon/include/common/Native.h:2260` | `#define REQUEST_OPLOCK_OUTPUT_FLAG_ACK_REQUIRED` |
| `REQUEST_OPLOCK_OUTPUT_FLAG_MODES_PROVIDED` | macro | `payloads/Demon/include/common/Native.h:2261` | `#define REQUEST_OPLOCK_OUTPUT_FLAG_MODES_PROVIDED` |
| `RESOURCE_SIZE` | macro | `payloads/Demon/include/common/Native.h:701` | `#define RESOURCE_SIZE(x)` |
| `RESOURCE_VA` | macro | `payloads/Demon/include/common/Native.h:696` | `#define RESOURCE_VA(x)` |
| `RESTORE_LIST` | macro | `payloads/Demon/include/common/Native.h:81` | `#define RESTORE_LIST(ListEntry)` |
| `RETRIEVAL_POINTERS_BUFFER` | struct | `payloads/Demon/include/common/Native.h:971` | `` |
| `ROUND_DOWN_COUNT` | macro | `payloads/Demon/include/common/Native.h:640` | `#define ROUND_DOWN_COUNT(Count,Pow2)` |
| `ROUND_DOWN_POINTER` | macro | `payloads/Demon/include/common/Native.h:643` | `#define ROUND_DOWN_POINTER(Ptr,Pow2)` |
| `ROUND_UP_COUNT` | macro | `payloads/Demon/include/common/Native.h:655` | `#define ROUND_UP_COUNT(Count,Pow2)` |
| `ROUND_UP_POINTER` | macro | `payloads/Demon/include/common/Native.h:665` | `#define ROUND_UP_POINTER(Ptr,Pow2)` |
| `RTL_ATOM` | type_alias | `payloads/Demon/include/common/Native.h:431` | `typedef USHORT RTL_ATOM;` |
| `RTL_ATOM_INVALID_ATOM` | macro | `payloads/Demon/include/common/Native.h:11404` | `#define RTL_ATOM_INVALID_ATOM` |
| `RTL_ATOM_MAXIMUM_INTEGER_ATOM` | macro | `payloads/Demon/include/common/Native.h:11403` | `#define RTL_ATOM_MAXIMUM_INTEGER_ATOM` |
| `RTL_ATOM_MAXIMUM_NAME_LENGTH` | macro | `payloads/Demon/include/common/Native.h:11406` | `#define RTL_ATOM_MAXIMUM_NAME_LENGTH` |
| `RTL_ATOM_PINNED` | macro | `payloads/Demon/include/common/Native.h:11407` | `#define RTL_ATOM_PINNED` |
| `RTL_ATOM_TABLE_DEFAULT_NUMBER_OF_BUCKETS` | macro | `payloads/Demon/include/common/Native.h:11405` | `#define RTL_ATOM_TABLE_DEFAULT_NUMBER_OF_BUCKETS` |
| `RTL_CLONE_PROCESS_FLAGS_CREATE_SUSPENDED` | macro | `payloads/Demon/include/common/Native.h:10910` | `#define RTL_CLONE_PROCESS_FLAGS_CREATE_SUSPENDED` |
| `RTL_CLONE_PROCESS_FLAGS_INHERIT_HANDLES` | macro | `payloads/Demon/include/common/Native.h:10911` | `#define RTL_CLONE_PROCESS_FLAGS_INHERIT_HANDLES` |
| `RTL_CLONE_PROCESS_FLAGS_NO_SYNCHRONIZE` | macro | `payloads/Demon/include/common/Native.h:10912` | `#define RTL_CLONE_PROCESS_FLAGS_NO_SYNCHRONIZE` |
| `RTL_DRIVE_LETTER_VALID` | macro | `payloads/Demon/include/common/Native.h:5351` | `#define RTL_DRIVE_LETTER_VALID` |
| `RTL_DRIVE_LETTER_VALID` | macro | `payloads/Demon/include/common/Native.h:6754` | `#define RTL_DRIVE_LETTER_VALID` |
| `RTL_HANDLE_ALLOCATED` | macro | `payloads/Demon/include/common/Native.h:11339` | `#define RTL_HANDLE_ALLOCATED` |
| `RTL_HEAP_BUSY` | macro | `payloads/Demon/include/common/Native.h:7203` | `#define RTL_HEAP_BUSY` |
| `RTL_HEAP_BUSY` | macro | `payloads/Demon/include/common/Native.h:10335` | `#define RTL_HEAP_BUSY` |
| `RTL_HEAP_MAKE_TAG` | macro | `payloads/Demon/include/common/Native.h:3624` | `#define RTL_HEAP_MAKE_TAG` |
| `RTL_HEAP_MAKE_TAG` | macro | `payloads/Demon/include/common/Native.h:11093` | `#define RTL_HEAP_MAKE_TAG` |
| `RTL_HEAP_PROTECTED_ENTRY` | macro | `payloads/Demon/include/common/Native.h:7211` | `#define RTL_HEAP_PROTECTED_ENTRY` |
| `RTL_HEAP_PROTECTED_ENTRY` | macro | `payloads/Demon/include/common/Native.h:10343` | `#define RTL_HEAP_PROTECTED_ENTRY` |
| `RTL_HEAP_SEGMENT` | macro | `payloads/Demon/include/common/Native.h:7204` | `#define RTL_HEAP_SEGMENT` |
| `RTL_HEAP_SEGMENT` | macro | `payloads/Demon/include/common/Native.h:10336` | `#define RTL_HEAP_SEGMENT` |
| `RTL_HEAP_SETTABLE_FLAG1` | macro | `payloads/Demon/include/common/Native.h:7206` | `#define RTL_HEAP_SETTABLE_FLAG1` |
| `RTL_HEAP_SETTABLE_FLAG1` | macro | `payloads/Demon/include/common/Native.h:10338` | `#define RTL_HEAP_SETTABLE_FLAG1` |
| `RTL_HEAP_SETTABLE_FLAG2` | macro | `payloads/Demon/include/common/Native.h:7207` | `#define RTL_HEAP_SETTABLE_FLAG2` |
| `RTL_HEAP_SETTABLE_FLAG2` | macro | `payloads/Demon/include/common/Native.h:10339` | `#define RTL_HEAP_SETTABLE_FLAG2` |
| `RTL_HEAP_SETTABLE_FLAG3` | macro | `payloads/Demon/include/common/Native.h:7208` | `#define RTL_HEAP_SETTABLE_FLAG3` |
| `RTL_HEAP_SETTABLE_FLAG3` | macro | `payloads/Demon/include/common/Native.h:10340` | `#define RTL_HEAP_SETTABLE_FLAG3` |
| `RTL_HEAP_SETTABLE_FLAGS` | macro | `payloads/Demon/include/common/Native.h:7209` | `#define RTL_HEAP_SETTABLE_FLAGS` |
| `RTL_HEAP_SETTABLE_FLAGS` | macro | `payloads/Demon/include/common/Native.h:10341` | `#define RTL_HEAP_SETTABLE_FLAGS` |
| `RTL_HEAP_SETTABLE_VALUE` | macro | `payloads/Demon/include/common/Native.h:7205` | `#define RTL_HEAP_SETTABLE_VALUE` |
| `RTL_HEAP_SETTABLE_VALUE` | macro | `payloads/Demon/include/common/Native.h:10337` | `#define RTL_HEAP_SETTABLE_VALUE` |
| `RTL_HEAP_UNCOMMITTED_RANGE` | macro | `payloads/Demon/include/common/Native.h:7210` | `#define RTL_HEAP_UNCOMMITTED_RANGE` |
| `RTL_HEAP_UNCOMMITTED_RANGE` | macro | `payloads/Demon/include/common/Native.h:10342` | `#define RTL_HEAP_UNCOMMITTED_RANGE` |
| `RTL_MAX_DRIVE_LETTERS` | macro | `payloads/Demon/include/common/Native.h:5350` | `#define RTL_MAX_DRIVE_LETTERS` |
| `RTL_MAX_DRIVE_LETTERS` | macro | `payloads/Demon/include/common/Native.h:6753` | `#define RTL_MAX_DRIVE_LETTERS` |
| `RTL_QUERY_PROCESS_BACKTRACES` | macro | `payloads/Demon/include/common/Native.h:497` | `#define RTL_QUERY_PROCESS_BACKTRACES` |
| `RTL_QUERY_PROCESS_HEAP_ENTRIES` | macro | `payloads/Demon/include/common/Native.h:500` | `#define RTL_QUERY_PROCESS_HEAP_ENTRIES` |
| `RTL_QUERY_PROCESS_HEAP_SUMMARY` | macro | `payloads/Demon/include/common/Native.h:498` | `#define RTL_QUERY_PROCESS_HEAP_SUMMARY` |
| `RTL_QUERY_PROCESS_HEAP_TAGS` | macro | `payloads/Demon/include/common/Native.h:499` | `#define RTL_QUERY_PROCESS_HEAP_TAGS` |
| `RTL_QUERY_PROCESS_LOCKS` | macro | `payloads/Demon/include/common/Native.h:501` | `#define RTL_QUERY_PROCESS_LOCKS` |
| `RTL_QUERY_PROCESS_MODULES` | macro | `payloads/Demon/include/common/Native.h:496` | `#define RTL_QUERY_PROCESS_MODULES` |
| `RTL_QUERY_PROCESS_MODULES32` | macro | `payloads/Demon/include/common/Native.h:502` | `#define RTL_QUERY_PROCESS_MODULES32` |
| `RTL_QUERY_PROCESS_NONINVASIVE` | macro | `payloads/Demon/include/common/Native.h:503` | `#define RTL_QUERY_PROCESS_NONINVASIVE` |
| `RTL_RANGE_CONFLICT` | macro | `payloads/Demon/include/common/Native.h:10196` | `#define RTL_RANGE_CONFLICT` |
| `RTL_RANGE_LIST_NULL_CONFLICT_OK` | macro | `payloads/Demon/include/common/Native.h:3711` | `#define RTL_RANGE_LIST_NULL_CONFLICT_OK` |
| `RTL_RANGE_LIST_SHARED_OK` | macro | `payloads/Demon/include/common/Native.h:3710` | `#define RTL_RANGE_LIST_SHARED_OK` |
| `RTL_RANGE_SHARED` | macro | `payloads/Demon/include/common/Native.h:10195` | `#define RTL_RANGE_SHARED` |
| `RTL_RESOURCE_FLAG_LONG_TERM` | macro | `payloads/Demon/include/common/Native.h:10288` | `#define RTL_RESOURCE_FLAG_LONG_TERM` |
| `RTL_TRACE_IN_KERNEL_MODE` | macro | `payloads/Demon/include/common/Native.h:10267` | `#define RTL_TRACE_IN_KERNEL_MODE` |
| `RTL_TRACE_IN_USER_MODE` | macro | `payloads/Demon/include/common/Native.h:10266` | `#define RTL_TRACE_IN_USER_MODE` |
| `RTL_TRACE_USE_NONPAGED_POOL` | macro | `payloads/Demon/include/common/Native.h:10268` | `#define RTL_TRACE_USE_NONPAGED_POOL` |
| `RTL_TRACE_USE_PAGED_POOL` | macro | `payloads/Demon/include/common/Native.h:10269` | `#define RTL_TRACE_USE_PAGED_POOL` |
| `RTL_UNLOAD_EVENT_TRACE_NUMBER` | macro | `payloads/Demon/include/common/Native.h:21427` | `#define RTL_UNLOAD_EVENT_TRACE_NUMBER` |
| `RTL_USER_PROC_APP_MANIFEST_PRESENT` | macro | `payloads/Demon/include/common/Native.h:10238` | `#define RTL_USER_PROC_APP_MANIFEST_PRESENT` |
| `RTL_USER_PROC_CASE_SENSITIVE` | macro | `payloads/Demon/include/common/Native.h:10235` | `#define RTL_USER_PROC_CASE_SENSITIVE` |
| `RTL_USER_PROC_CURDIR_CLOSE` | macro | `payloads/Demon/include/common/Native.h:5339` | `#define RTL_USER_PROC_CURDIR_CLOSE` |
| `RTL_USER_PROC_CURDIR_CLOSE` | macro | `payloads/Demon/include/common/Native.h:6723` | `#define RTL_USER_PROC_CURDIR_CLOSE` |
| `RTL_USER_PROC_CURDIR_CLOSE` | macro | `payloads/Demon/include/common/Native.h:10192` | `#define RTL_USER_PROC_CURDIR_CLOSE` |
| `RTL_USER_PROC_CURDIR_INHERIT` | macro | `payloads/Demon/include/common/Native.h:5340` | `#define RTL_USER_PROC_CURDIR_INHERIT` |
| `RTL_USER_PROC_CURDIR_INHERIT` | macro | `payloads/Demon/include/common/Native.h:6724` | `#define RTL_USER_PROC_CURDIR_INHERIT` |
| `RTL_USER_PROC_CURDIR_INHERIT` | macro | `payloads/Demon/include/common/Native.h:10193` | `#define RTL_USER_PROC_CURDIR_INHERIT` |
| `RTL_USER_PROC_DISABLE_HEAP_DECOMMIT` | macro | `payloads/Demon/include/common/Native.h:10236` | `#define RTL_USER_PROC_DISABLE_HEAP_DECOMMIT` |
| `RTL_USER_PROC_DLL_REDIRECTION_LOCAL` | macro | `payloads/Demon/include/common/Native.h:10237` | `#define RTL_USER_PROC_DLL_REDIRECTION_LOCAL` |
| `RTL_USER_PROC_IMAGE_KEY_MISSING` | macro | `payloads/Demon/include/common/Native.h:10239` | `#define RTL_USER_PROC_IMAGE_KEY_MISSING` |
| `RTL_USER_PROC_OPTIN_PROCESS` | macro | `payloads/Demon/include/common/Native.h:10240` | `#define RTL_USER_PROC_OPTIN_PROCESS` |
| `RTL_USER_PROC_PARAMS_NORMALIZED` | macro | `payloads/Demon/include/common/Native.h:10229` | `#define RTL_USER_PROC_PARAMS_NORMALIZED` |
| `RTL_USER_PROC_PROFILE_KERNEL` | macro | `payloads/Demon/include/common/Native.h:10231` | `#define RTL_USER_PROC_PROFILE_KERNEL` |
| `RTL_USER_PROC_PROFILE_SERVER` | macro | `payloads/Demon/include/common/Native.h:10232` | `#define RTL_USER_PROC_PROFILE_SERVER` |
| `RTL_USER_PROC_PROFILE_USER` | macro | `payloads/Demon/include/common/Native.h:10230` | `#define RTL_USER_PROC_PROFILE_USER` |
| `RTL_USER_PROC_RESERVE_16MB` | macro | `payloads/Demon/include/common/Native.h:10234` | `#define RTL_USER_PROC_RESERVE_16MB` |
| `RTL_USER_PROC_RESERVE_1MB` | macro | `payloads/Demon/include/common/Native.h:10233` | `#define RTL_USER_PROC_RESERVE_1MB` |
| `RVATOVA` | macro | `payloads/Demon/include/common/Native.h:465` | `#define RVATOVA(base, offset)` |
| `RangeListHead` | type_alias | `payloads/Demon/include/common/Native.h:10214` | `typedef struct _RANGE_LIST_ITERATOR { PLIST_ENTRY RangeListHead;` |
| `ReadMode` | type_alias | `payloads/Demon/include/common/Native.h:4091` | `typedef struct _FILE_PIPE_INFORMATION { ULONG ReadMode;` |
| `ReadOperationCount` | type_alias | `payloads/Demon/include/common/Native.h:10940` | `typedef struct _IO_COUNTERS { ULONGLONG ReadOperationCount;` |
| `ReadTimeout` | type_alias | `payloads/Demon/include/common/Native.h:4122` | `typedef struct _FILE_MAILSLOT_SET_INFORMATION { PLARGE_INTEGER ReadTimeout;` |
| `RecordCount` | type_alias | `payloads/Demon/include/common/Native.h:9414` | `typedef struct _LSA_FOREST_TRUST_INFORMATION { #ifdef MIDL_PASS [range(0, MAX_RECORDS_IN_FOREST_TRUST_INFO)] ULONG Recor` |
| `RecordCount` | type_alias | `payloads/Demon/include/common/Native.h:9443` | `typedef struct _LSA_FOREST_TRUST_COLLISION_INFORMATION { ULONG RecordCount;` |
| `RefCount` | type_alias | `payloads/Demon/include/common/Native.h:6497` | `typedef struct _ACTIVATION_CONTEXT { LONG RefCount;` |
| `RegistryQuotaAllowed` | type_alias | `payloads/Demon/include/common/Native.h:4526` | `typedef struct _SYSTEM_REGISTRY_QUOTA_INFORMATION { ULONG RegistryQuotaAllowed;` |
| `RelativeName` | type_alias | `payloads/Demon/include/common/Native.h:6725` | `typedef struct _RTL_RELATIVE_NAME { STRING RelativeName;` |
| `RelativeName` | type_alias | `payloads/Demon/include/common/Native.h:6733` | `typedef struct _RTL_RELATIVE_NAME_U { UNICODE_STRING RelativeName;` |
| `RemainingTime` | type_alias | `payloads/Demon/include/common/Native.h:3437` | `typedef struct _TIMER_BASIC_INFORMATION { LARGE_INTEGER RemainingTime;` |
| `RemoveEntryList` | macro | `payloads/Demon/include/common/Native.h:579` | `#define RemoveEntryList(Entry)` |
| `RemoveHeadList` | macro | `payloads/Demon/include/common/Native.h:567` | `#define RemoveHeadList(ListHead)` |
| `RemoveTailList` | macro | `payloads/Demon/include/common/Native.h:571` | `#define RemoveTailList(ListHead)` |
| `ReplaceIfExists` | type_alias | `payloads/Demon/include/common/Native.h:4051` | `typedef struct _FILE_LINK_INFORMATION { BOOLEAN ReplaceIfExists;` |
| `ReplaceIfExists` | type_alias | `payloads/Demon/include/common/Native.h:4065` | `typedef struct _FILE_RENAME_INFORMATION { BOOLEAN ReplaceIfExists;` |
| `ReplicaSource` | type_alias | `payloads/Demon/include/common/Native.h:9030` | `typedef struct _POLICY_REPLICA_SOURCE_INFO { LSA_UNICODE_STRING ReplicaSource;` |
| `Reserved` | type_alias | `payloads/Demon/include/common/Native.h:4644` | `typedef struct _SYSTEM_BASIC_INFORMATION { ULONG Reserved;` |
| `Reserved` | type_alias | `payloads/Demon/include/common/Native.h:6080` | `typedef struct _BASE_NLS_UPDATE_CACHE_COUNT_MSG { ULONG Reserved;` |
| `RootRegistryKey` | type_alias | `payloads/Demon/include/common/Native.h:3678` | `typedef struct _RTL_RXACT_CONTEXT { HANDLE RootRegistryKey;` |
| `RtlAcquireLockRoutine` | macro | `payloads/Demon/include/common/Native.h:7109` | `#define RtlAcquireLockRoutine(L)` |
| `RtlAcquireLockRoutine` | macro | `payloads/Demon/include/common/Native.h:11178` | `#define RtlAcquireLockRoutine(L)` |
| `RtlCopyMemory` | macro | `payloads/Demon/include/common/Native.h:21677` | `#define RtlCopyMemory(Destination,Source,Length)` |
| `RtlDeleteLockRoutine` | macro | `payloads/Demon/include/common/Native.h:11180` | `#define RtlDeleteLockRoutine(L)` |
| `RtlEqualMemory` | macro | `payloads/Demon/include/common/Native.h:21675` | `#define RtlEqualMemory(Destination,Source,Length)` |
| `RtlFillMemory` | macro | `payloads/Demon/include/common/Native.h:21678` | `#define RtlFillMemory(Destination,Length,Fill)` |
| `RtlGetCurrentProcessId` | macro | `payloads/Demon/include/common/Native.h:7098` | `#define RtlGetCurrentProcessId()` |
| `RtlGetCurrentThreadId` | macro | `payloads/Demon/include/common/Native.h:7099` | `#define RtlGetCurrentThreadId()` |
| `RtlInitString` | function | `payloads/Demon/include/common/Native.h:21963` | `void NTAPI RtlInitString( PSTRING DestinationString, PCSZ SourceString );` |
| `RtlInitializeLockRoutine` | macro | `payloads/Demon/include/common/Native.h:11177` | `#define RtlInitializeLockRoutine(L)` |
| `RtlMoveMemory` | macro | `payloads/Demon/include/common/Native.h:21676` | `#define RtlMoveMemory(Destination,Source,Length)` |
| `RtlOffsetToPointer` | macro | `payloads/Demon/include/common/Native.h:316` | `#define RtlOffsetToPointer(B,O)` |
| `RtlPointerToOffset` | macro | `payloads/Demon/include/common/Native.h:347` | `#define RtlPointerToOffset(B,P)` |
| `RtlProcessHeap` | macro | `payloads/Demon/include/common/Native.h:7106` | `#define RtlProcessHeap()` |
| `RtlReleaseLockRoutine` | macro | `payloads/Demon/include/common/Native.h:11179` | `#define RtlReleaseLockRoutine(L)` |
| `RtlRetrieveUlong` | macro | `payloads/Demon/include/common/Native.h:277` | `#define RtlRetrieveUlong(DEST_ADDRESS,SRC_ADDRESS)` |
| `RtlRetrieveUshort` | macro | `payloads/Demon/include/common/Native.h:240` | `#define RtlRetrieveUshort(DEST_ADDRESS,SRC_ADDRESS)` |
| `RtlStoreUlong` | macro | `payloads/Demon/include/common/Native.h:205` | `#define RtlStoreUlong(ADDRESS,VALUE)` |
| `RtlStoreUshort` | macro | `payloads/Demon/include/common/Native.h:167` | `#define RtlStoreUshort(ADDRESS,VALUE)` |
| `RtlUpdateClonedCriticalSection` | function | `payloads/Demon/include/common/Native.h:22100` | `void NTAPI RtlUpdateClonedCriticalSection( PRTL_CRITICAL_SECTION CriticalSection );` |
| `RtlZeroMemory` | macro | `payloads/Demon/include/common/Native.h:21679` | `#define RtlZeroMemory(Destination,Length)` |
| `RtlpAreControlBitsSet` | macro | `payloads/Demon/include/common/Native.h:7704` | `#define RtlpAreControlBitsSet( SD, Bits )` |
| `RtlpClearControlBits` | macro | `payloads/Demon/include/common/Native.h:7723` | `#define RtlpClearControlBits( SD, Bits )` |
| `RtlpDaclAddrSecurityDescriptor` | macro | `payloads/Demon/include/common/Native.h:7665` | `#define RtlpDaclAddrSecurityDescriptor( SD )` |
| `RtlpGroupAddrSecurityDescriptor` | macro | `payloads/Demon/include/common/Native.h:7646` | `#define RtlpGroupAddrSecurityDescriptor( SD )` |
| `RtlpIdAssignableAsOwner` | macro | `payloads/Demon/include/common/Native.h:7683` | `#define RtlpIdAssignableAsOwner( G )` |
| `RtlpOwnerAddrSecurityDescriptor` | macro | `payloads/Demon/include/common/Native.h:7638` | `#define RtlpOwnerAddrSecurityDescriptor( SD )` |
| `RtlpPropagateControlBits` | macro | `payloads/Demon/include/common/Native.h:7692` | `#define RtlpPropagateControlBits( NewSD, OldSD, Bits )` |
| `RtlpSaclAddrSecurityDescriptor` | macro | `payloads/Demon/include/common/Native.h:7654` | `#define RtlpSaclAddrSecurityDescriptor( SD )` |
| `RtlpSetControlBits` | macro | `payloads/Demon/include/common/Native.h:7714` | `#define RtlpSetControlBits( SD, Bits )` |
| `SD_GLOBAL_CHANGE_TYPE_MACHINE_SID` | macro | `payloads/Demon/include/common/Native.h:2282` | `#define SD_GLOBAL_CHANGE_TYPE_MACHINE_SID` |
| `SECONDBYTE` | macro | `payloads/Demon/include/common/Native.h:127` | `#define SECONDBYTE(VALUE)` |
| `SECONDS` | macro | `payloads/Demon/include/common/Native.h:75` | `#define SECONDS(seconds)` |
| `SECURITY_STATUS` | type_alias | `payloads/Demon/include/common/Native.h:46` | `typedef LONG SECURITY_STATUS;` |
| `SEMAPHORE_ALL_ACCESS` | macro | `payloads/Demon/include/common/Native.h:3403` | `#define SEMAPHORE_ALL_ACCESS` |
| `SEMAPHORE_MODIFY_STATE` | macro | `payloads/Demon/include/common/Native.h:3401` | `#define SEMAPHORE_MODIFY_STATE` |
| `SEMAPHORE_QUERY_STATE` | macro | `payloads/Demon/include/common/Native.h:3400` | `#define SEMAPHORE_QUERY_STATE` |
| `SET_LAST_STATUS` | macro | `payloads/Demon/include/common/Native.h:5416` | `#define SET_LAST_STATUS(S)` |
| `SET_LAST_STATUS` | macro | `payloads/Demon/include/common/Native.h:10421` | `#define SET_LAST_STATUS(S)` |
| `SET_REPAIR_DELETE_CROSSLINK` | macro | `payloads/Demon/include/common/Native.h:1562` | `#define SET_REPAIR_DELETE_CROSSLINK` |
| `SET_REPAIR_DISABLED_AND_BUGCHECK_ON_CORRUPT` | macro | `payloads/Demon/include/common/Native.h:1564` | `#define SET_REPAIR_DISABLED_AND_BUGCHECK_ON_CORRUPT` |
| `SET_REPAIR_ENABLED` | macro | `payloads/Demon/include/common/Native.h:1560` | `#define SET_REPAIR_ENABLED` |
| `SET_REPAIR_VALID_MASK` | macro | `payloads/Demon/include/common/Native.h:1565` | `#define SET_REPAIR_VALID_MASK` |
| `SET_REPAIR_VOLUME_BITMAP_SCAN` | macro | `payloads/Demon/include/common/Native.h:1561` | `#define SET_REPAIR_VOLUME_BITMAP_SCAN` |
| `SET_REPAIR_WARN_ABOUT_DATA_LOSS` | macro | `payloads/Demon/include/common/Native.h:1563` | `#define SET_REPAIR_WARN_ABOUT_DATA_LOSS` |
| `SE_ADT_OBJECT_ONLY` | macro | `payloads/Demon/include/common/Native.h:8718` | `#define SE_ADT_OBJECT_ONLY` |
| `SE_ADT_PARAMETERS_SELF_RELATIVE` | macro | `payloads/Demon/include/common/Native.h:8756` | `#define SE_ADT_PARAMETERS_SELF_RELATIVE` |
| `SE_ADT_PARAMETERS_SEND_TO_LSA` | macro | `payloads/Demon/include/common/Native.h:8757` | `#define SE_ADT_PARAMETERS_SEND_TO_LSA` |
| `SE_ADT_PARAMETER_EXTENSIBLE_AUDIT` | macro | `payloads/Demon/include/common/Native.h:8758` | `#define SE_ADT_PARAMETER_EXTENSIBLE_AUDIT` |
| `SE_ADT_PARAMETER_GENERIC_AUDIT` | macro | `payloads/Demon/include/common/Native.h:8759` | `#define SE_ADT_PARAMETER_GENERIC_AUDIT` |
| `SE_ADT_PARAMETER_WRITE_SYNCHRONOUS` | macro | `payloads/Demon/include/common/Native.h:8760` | `#define SE_ADT_PARAMETER_WRITE_SYNCHRONOUS` |
| `SE_ASSIGNPRIMARYTOKEN_NAME` | macro | `payloads/Demon/include/common/Native.h:3847` | `#define SE_ASSIGNPRIMARYTOKEN_NAME` |
| `SE_ASSIGNPRIMARYTOKEN_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3884` | `#define SE_ASSIGNPRIMARYTOKEN_PRIVILEGE` |
| `SE_AUDIT_NAME` | macro | `payloads/Demon/include/common/Native.h:3866` | `#define SE_AUDIT_NAME` |
| `SE_AUDIT_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3903` | `#define SE_AUDIT_PRIVILEGE` |
| `SE_BACKUP_NAME` | macro | `payloads/Demon/include/common/Native.h:3862` | `#define SE_BACKUP_NAME` |
| `SE_BACKUP_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3899` | `#define SE_BACKUP_PRIVILEGE` |
| `SE_BATCH_LOGON_NAME` | macro | `payloads/Demon/include/common/Native.h:9652` | `#define SE_BATCH_LOGON_NAME` |
| `SE_CHANGE_NOTIFY_NAME` | macro | `payloads/Demon/include/common/Native.h:3868` | `#define SE_CHANGE_NOTIFY_NAME` |
| `SE_CHANGE_NOTIFY_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3905` | `#define SE_CHANGE_NOTIFY_PRIVILEGE` |
| `SE_CREATE_GLOBAL_NAME` | macro | `payloads/Demon/include/common/Native.h:3878` | `#define SE_CREATE_GLOBAL_NAME` |
| `SE_CREATE_GLOBAL_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3912` | `#define SE_CREATE_GLOBAL_PRIVILEGE` |
| `SE_CREATE_PAGEFILE_NAME` | macro | `payloads/Demon/include/common/Native.h:3860` | `#define SE_CREATE_PAGEFILE_NAME` |
| `SE_CREATE_PAGEFILE_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3897` | `#define SE_CREATE_PAGEFILE_PRIVILEGE` |
| `SE_CREATE_PERMANENT_NAME` | macro | `payloads/Demon/include/common/Native.h:3861` | `#define SE_CREATE_PERMANENT_NAME` |
| `SE_CREATE_PERMANENT_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3898` | `#define SE_CREATE_PERMANENT_PRIVILEGE` |
| `SE_CREATE_SYMBOLIC_LINK_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3917` | `#define SE_CREATE_SYMBOLIC_LINK_PRIVILEGE` |
| `SE_CREATE_TOKEN_NAME` | macro | `payloads/Demon/include/common/Native.h:3846` | `#define SE_CREATE_TOKEN_NAME` |
| `SE_CREATE_TOKEN_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3883` | `#define SE_CREATE_TOKEN_PRIVILEGE` |
| `SE_DEBUG_NAME` | macro | `payloads/Demon/include/common/Native.h:3865` | `#define SE_DEBUG_NAME` |
| `SE_DEBUG_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3902` | `#define SE_DEBUG_PRIVILEGE` |
| `SE_DENY_BATCH_LOGON_NAME` | macro | `payloads/Demon/include/common/Native.h:9656` | `#define SE_DENY_BATCH_LOGON_NAME` |
| `SE_DENY_INTERACTIVE_LOGON_NAME` | macro | `payloads/Demon/include/common/Native.h:9654` | `#define SE_DENY_INTERACTIVE_LOGON_NAME` |
| `SE_DENY_NETWORK_LOGON_NAME` | macro | `payloads/Demon/include/common/Native.h:9655` | `#define SE_DENY_NETWORK_LOGON_NAME` |
| `SE_DENY_REMOTE_INTERACTIVE_LOGON_NAME` | macro | `payloads/Demon/include/common/Native.h:9660` | `#define SE_DENY_REMOTE_INTERACTIVE_LOGON_NAME` |
| `SE_DENY_SERVICE_LOGON_NAME` | macro | `payloads/Demon/include/common/Native.h:9657` | `#define SE_DENY_SERVICE_LOGON_NAME` |
| `SE_ENABLE_DELEGATION_NAME` | macro | `payloads/Demon/include/common/Native.h:3872` | `#define SE_ENABLE_DELEGATION_NAME` |
| `SE_ENABLE_DELEGATION_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3909` | `#define SE_ENABLE_DELEGATION_PRIVILEGE` |
| `SE_IMPERSONATE_NAME` | macro | `payloads/Demon/include/common/Native.h:3874` | `#define SE_IMPERSONATE_NAME` |
| `SE_IMPERSONATE_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3911` | `#define SE_IMPERSONATE_PRIVILEGE` |
| `SE_INCREASE_QUOTA_NAME` | macro | `payloads/Demon/include/common/Native.h:3849` | `#define SE_INCREASE_QUOTA_NAME` |
| `SE_INCREASE_QUOTA_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3886` | `#define SE_INCREASE_QUOTA_PRIVILEGE` |
| `SE_INC_BASE_PRIORITY_NAME` | macro | `payloads/Demon/include/common/Native.h:3859` | `#define SE_INC_BASE_PRIORITY_NAME` |
| `SE_INC_BASE_PRIORITY_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3896` | `#define SE_INC_BASE_PRIORITY_PRIVILEGE` |
| `SE_INC_WORKING_SET_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3915` | `#define SE_INC_WORKING_SET_PRIVILEGE` |
| `SE_INTERACTIVE_LOGON_NAME` | macro | `payloads/Demon/include/common/Native.h:9650` | `#define SE_INTERACTIVE_LOGON_NAME` |
| `SE_LOAD_DRIVER_NAME` | macro | `payloads/Demon/include/common/Native.h:3855` | `#define SE_LOAD_DRIVER_NAME` |
| `SE_LOAD_DRIVER_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3892` | `#define SE_LOAD_DRIVER_PRIVILEGE` |
| `SE_LOCK_MEMORY_NAME` | macro | `payloads/Demon/include/common/Native.h:3848` | `#define SE_LOCK_MEMORY_NAME` |
| `SE_LOCK_MEMORY_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3885` | `#define SE_LOCK_MEMORY_PRIVILEGE` |
| `SE_MACHINE_ACCOUNT_NAME` | macro | `payloads/Demon/include/common/Native.h:3851` | `#define SE_MACHINE_ACCOUNT_NAME` |
| `SE_MACHINE_ACCOUNT_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3888` | `#define SE_MACHINE_ACCOUNT_PRIVILEGE` |
| `SE_MANAGE_VOLUME_NAME` | macro | `payloads/Demon/include/common/Native.h:3873` | `#define SE_MANAGE_VOLUME_NAME` |
| `SE_MANAGE_VOLUME_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3910` | `#define SE_MANAGE_VOLUME_PRIVILEGE` |
| `SE_MAX_AUDIT_PARAMETERS` | macro | `payloads/Demon/include/common/Native.h:8740` | `#define SE_MAX_AUDIT_PARAMETERS` |
| `SE_MAX_GENERIC_AUDIT_PARAMETERS` | macro | `payloads/Demon/include/common/Native.h:8741` | `#define SE_MAX_GENERIC_AUDIT_PARAMETERS` |
| `SE_MAX_WELL_KNOWN_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3918` | `#define SE_MAX_WELL_KNOWN_PRIVILEGE` |
| `SE_MIN_WELL_KNOWN_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3882` | `#define SE_MIN_WELL_KNOWN_PRIVILEGE` |
| `SE_NETWORK_LOGON_NAME` | macro | `payloads/Demon/include/common/Native.h:9651` | `#define SE_NETWORK_LOGON_NAME` |
| `SE_PROF_SINGLE_PROCESS_NAME` | macro | `payloads/Demon/include/common/Native.h:3858` | `#define SE_PROF_SINGLE_PROCESS_NAME` |
| `SE_PROF_SINGLE_PROCESS_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3895` | `#define SE_PROF_SINGLE_PROCESS_PRIVILEGE` |
| `SE_RELABEL_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3914` | `#define SE_RELABEL_PRIVILEGE` |
| `SE_REMOTE_INTERACTIVE_LOGON_NAME` | macro | `payloads/Demon/include/common/Native.h:9659` | `#define SE_REMOTE_INTERACTIVE_LOGON_NAME` |
| `SE_REMOTE_SHUTDOWN_NAME` | macro | `payloads/Demon/include/common/Native.h:3869` | `#define SE_REMOTE_SHUTDOWN_NAME` |
| `SE_REMOTE_SHUTDOWN_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3906` | `#define SE_REMOTE_SHUTDOWN_PRIVILEGE` |
| `SE_RESTORE_NAME` | macro | `payloads/Demon/include/common/Native.h:3863` | `#define SE_RESTORE_NAME` |
| `SE_RESTORE_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3900` | `#define SE_RESTORE_PRIVILEGE` |
| `SE_SECURITY_NAME` | macro | `payloads/Demon/include/common/Native.h:3853` | `#define SE_SECURITY_NAME` |
| `SE_SECURITY_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3890` | `#define SE_SECURITY_PRIVILEGE` |
| `SE_SERVICE_LOGON_NAME` | macro | `payloads/Demon/include/common/Native.h:9653` | `#define SE_SERVICE_LOGON_NAME` |
| `SE_SHUTDOWN_NAME` | macro | `payloads/Demon/include/common/Native.h:3864` | `#define SE_SHUTDOWN_NAME` |
| `SE_SHUTDOWN_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3901` | `#define SE_SHUTDOWN_PRIVILEGE` |
| `SE_SYNC_AGENT_NAME` | macro | `payloads/Demon/include/common/Native.h:3871` | `#define SE_SYNC_AGENT_NAME` |
| `SE_SYNC_AGENT_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3908` | `#define SE_SYNC_AGENT_PRIVILEGE` |
| `SE_SYSTEMTIME_NAME` | macro | `payloads/Demon/include/common/Native.h:3857` | `#define SE_SYSTEMTIME_NAME` |
| `SE_SYSTEMTIME_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3894` | `#define SE_SYSTEMTIME_PRIVILEGE` |
| `SE_SYSTEM_ENVIRONMENT_NAME` | macro | `payloads/Demon/include/common/Native.h:3867` | `#define SE_SYSTEM_ENVIRONMENT_NAME` |
| `SE_SYSTEM_ENVIRONMENT_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3904` | `#define SE_SYSTEM_ENVIRONMENT_PRIVILEGE` |
| `SE_SYSTEM_PROFILE_NAME` | macro | `payloads/Demon/include/common/Native.h:3856` | `#define SE_SYSTEM_PROFILE_NAME` |
| `SE_SYSTEM_PROFILE_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3893` | `#define SE_SYSTEM_PROFILE_PRIVILEGE` |
| `SE_TAKE_OWNERSHIP_NAME` | macro | `payloads/Demon/include/common/Native.h:3854` | `#define SE_TAKE_OWNERSHIP_NAME` |
| `SE_TAKE_OWNERSHIP_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3891` | `#define SE_TAKE_OWNERSHIP_PRIVILEGE` |
| `SE_TCB_NAME` | macro | `payloads/Demon/include/common/Native.h:3852` | `#define SE_TCB_NAME` |
| `SE_TCB_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3889` | `#define SE_TCB_PRIVILEGE` |
| `SE_TIME_ZONE_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3916` | `#define SE_TIME_ZONE_PRIVILEGE` |
| `SE_TRUSTED_CREDMAN_ACCESS_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3913` | `#define SE_TRUSTED_CREDMAN_ACCESS_PRIVILEGE` |
| `SE_UNDOCK_NAME` | macro | `payloads/Demon/include/common/Native.h:3870` | `#define SE_UNDOCK_NAME` |
| `SE_UNDOCK_PRIVILEGE` | macro | `payloads/Demon/include/common/Native.h:3907` | `#define SE_UNDOCK_PRIVILEGE` |
| `SE_UNSOLICITED_INPUT_NAME` | macro | `payloads/Demon/include/common/Native.h:3850` | `#define SE_UNSOLICITED_INPUT_NAME` |
| `SHARED_USER_DATA_VA` | macro | `payloads/Demon/include/common/Native.h:10902` | `#define SHARED_USER_DATA_VA` |
| `SHORT_LEAST_SIGNIFICANT_BIT` | macro | `payloads/Demon/include/common/Native.h:135` | `#define SHORT_LEAST_SIGNIFICANT_BIT` |
| `SHORT_MASK` | macro | `payloads/Demon/include/common/Native.h:121` | `#define SHORT_MASK` |
| `SHORT_MOST_SIGNIFICANT_BIT` | macro | `payloads/Demon/include/common/Native.h:136` | `#define SHORT_MOST_SIGNIFICANT_BIT` |
| `SHORT_SIZE` | macro | `payloads/Demon/include/common/Native.h:120` | `#define SHORT_SIZE` |
| `SIZEOF_ARRAY` | macro | `payloads/Demon/include/common/Native.h:707` | `#define SIZEOF_ARRAY(arr)` |
| `SIZEOF_BP_BUFFER` | macro | `payloads/Demon/include/common/Native.h:10974` | `#define SIZEOF_BP_BUFFER` |
| `SLIST_ENTRY` | macro | `payloads/Demon/include/common/Native.h:11639` | `#define SLIST_ENTRY` |
| `STATIC_UNICODE_BUFFER_LENGTH` | macro | `payloads/Demon/include/common/Native.h:6464` | `#define STATIC_UNICODE_BUFFER_LENGTH` |
| `STREAM_CLEAR_ENCRYPTION` | macro | `payloads/Demon/include/common/Native.h:1452` | `#define STREAM_CLEAR_ENCRYPTION` |
| `STREAM_SET_ENCRYPTION` | macro | `payloads/Demon/include/common/Native.h:1451` | `#define STREAM_SET_ENCRYPTION` |
| `SYMBOLIC_LINK_ALL_ACCESS` | macro | `payloads/Demon/include/common/Native.h:3461` | `#define SYMBOLIC_LINK_ALL_ACCESS` |
| `SYMBOLIC_LINK_QUERY` | macro | `payloads/Demon/include/common/Native.h:3460` | `#define SYMBOLIC_LINK_QUERY` |
| `SYSINF_PAGE_COUNT` | type_alias | `payloads/Demon/include/common/Native.h:4640` | `typedef ULONG SYSINF_PAGE_COUNT;` |
| `SYSINF_PAGE_COUNT` | type_alias | `payloads/Demon/include/common/Native.h:4642` | `typedef SIZE_T SYSINF_PAGE_COUNT;` |
| `Section` | type_alias | `payloads/Demon/include/common/Native.h:6627` | `typedef struct _RTL_PROCESS_MODULE_INFORMATION { HANDLE Section;` |
| `SectionHandleClient` | type_alias | `payloads/Demon/include/common/Native.h:11255` | `typedef struct _RTL_DEBUG_INFORMATION { HANDLE SectionHandleClient;` |
| `Segment` | type_alias | `payloads/Demon/include/common/Native.h:11195` | `typedef struct _RTL_MEMORY_ZONE { RTL_MEMORY_ZONE_SEGMENT Segment;` |
| `SegmentNotPresent` | type_alias | `payloads/Demon/include/common/Native.h:4589` | `typedef struct _SYSTEM_VDM_INSTEMUL_INFO { ULONG SegmentNotPresent;` |
| `ServerDllIndex` | type_alias | `payloads/Demon/include/common/Native.h:5921` | `typedef struct _CSR_CLIENTCONNECT_MSG { ULONG ServerDllIndex;` |
| `SessionId` | type_alias | `payloads/Demon/include/common/Native.h:4954` | `typedef struct _SYSTEM_SESSION_PROCESS_INFORMATION { ULONG SessionId;` |
| `SessionLink` | type_alias | `payloads/Demon/include/common/Native.h:5964` | `typedef struct _CSR_NT_SESSION { struct _LIST_ENTRY SessionLink;` |
| `SetSparse` | type_alias | `payloads/Demon/include/common/Native.h:1409` | `typedef struct _FILE_SET_SPARSE_BUFFER { BOOLEAN SetSparse;` |
| `ShrinkRequestType` | type_alias | `payloads/Demon/include/common/Native.h:1574` | `typedef struct _SHRINK_VOLUME_INFORMATION { SHRINK_VOLUME_REQUEST_TYPES ShrinkRequestType;` |
| `ShutDownOnFull` | type_alias | `payloads/Demon/include/common/Native.h:9051` | `typedef struct _POLICY_AUDIT_FULL_SET_INFO { BOOLEAN ShutDownOnFull;` |
| `ShutDownOnFull` | type_alias | `payloads/Demon/include/common/Native.h:9058` | `typedef struct _POLICY_AUDIT_FULL_QUERY_INFO { BOOLEAN ShutDownOnFull;` |
| `ShutdownLevel` | type_alias | `payloads/Demon/include/common/Native.h:6129` | `typedef struct _BASE_SHUTDOWNPARAM_MSG { ULONG ShutdownLevel;` |
| `Sid` | type_alias | `payloads/Demon/include/common/Native.h:9345` | `typedef struct _LSA_FOREST_TRUST_DOMAIN_INFO { #ifdef MIDL_PASS PISID Sid;` |
| `Sid` | type_alias | `payloads/Demon/include/common/Native.h:9464` | `typedef struct _LSA_ENUMERATION_INFORMATION { PSID Sid;` |
| `Signature` | type_alias | `payloads/Demon/include/common/Native.h:7568` | `typedef struct _WINDOWS_OS_OPTIONS { UCHAR Signature[8];` |
| `Signature` | type_alias | `payloads/Demon/include/common/Native.h:11552` | `typedef struct _HOTPATCH_HEADER { ULONG Signature;` |
| `Size` | type_alias | `payloads/Demon/include/common/Native.h:7164` | `typedef struct _PROCESS_EXTENDED_BASIC_INFORMATION { SIZE_T Size;` |
| `Size` | type_alias | `payloads/Demon/include/common/Native.h:7182` | `typedef struct _RTL_HEAP_ENTRY { SIZE_T Size;` |
| `Size` | type_alias | `payloads/Demon/include/common/Native.h:9502` | `typedef struct _SECURITY_LOGON_SESSION_DATA { ULONG Size;` |
| `Size` | type_alias | `payloads/Demon/include/common/Native.h:10472` | `typedef struct _HEAP_ENTRY { USHORT Size;` |
| `SizeOfBitMap` | type_alias | `payloads/Demon/include/common/Native.h:10184` | `typedef struct _RTL_BITMAP { ULONG SizeOfBitMap;` |
| `SizeStruct` | type_alias | `payloads/Demon/include/common/Native.h:11203` | `typedef struct _RTL_PROCESS_VERIFIER_OPTIONS { ULONG SizeStruct;` |
| `SourceFileNameLength` | type_alias | `payloads/Demon/include/common/Native.h:1512` | `typedef struct _SI_COPYFILE { ULONG SourceFileNameLength;` |
| `Spare` | type_alias | `payloads/Demon/include/common/Native.h:4564` | `typedef struct _SYSTEM_DPC_BEHAVIOR_INFORMATION { ULONG Spare;` |
| `SparingUnitBytes` | type_alias | `payloads/Demon/include/common/Native.h:1535` | `typedef struct _FILE_QUERY_SPARING_BUFFER { ULONG SparingUnitBytes;` |
| `Start` | type_alias | `payloads/Demon/include/common/Native.h:3712` | `typedef struct _RTL_RANGE { ULONGLONG Start;` |
| `StartingFileOffset` | type_alias | `payloads/Demon/include/common/Native.h:1472` | `typedef struct _ENCRYPTED_DATA_INFO { ULONGLONG StartingFileOffset;` |
| `StartingIndex` | type_alias | `payloads/Demon/include/common/Native.h:3647` | `typedef struct _RTL_BITMAP_RUN { ULONG StartingIndex;` |
| `Status` | type_alias | `payloads/Demon/include/common/Native.h:3177` | `typedef struct _IO_STATUS_BLOCK { union { NTSTATUS Status;` |
| `StringOffset` | type_alias | `payloads/Demon/include/common/Native.h:4960` | `typedef struct _SYSTEM_MEMORY_INFO { PUCHAR StringOffset;` |
| `StructureVersion` | type_alias | `payloads/Demon/include/common/Native.h:2177` | `typedef struct _TXFS_CREATE_MINIVERSION_INFO { USHORT StructureVersion;` |
| `StructureVersion` | type_alias | `payloads/Demon/include/common/Native.h:2235` | `typedef struct _REQUEST_OPLOCK_INPUT_BUFFER { // // This should be set to REQUEST_OPLOCK_CURRENT_VERSION. // USHORT Stru` |
| `StructureVersion` | type_alias | `payloads/Demon/include/common/Native.h:2262` | `typedef struct _REQUEST_OPLOCK_OUTPUT_BUFFER { USHORT StructureVersion;` |
| `SubSystemKey` | type_alias | `payloads/Demon/include/common/Native.h:10982` | `typedef struct _DBGKM_CREATE_THREAD { ULONG SubSystemKey;` |
| `SubSystemKey` | type_alias | `payloads/Demon/include/common/Native.h:10988` | `typedef struct _DBGKM_CREATE_PROCESS { ULONG SubSystemKey;` |
| `SupportedEncryptionTypes` | type_alias | `payloads/Demon/include/common/Native.h:9303` | `typedef struct _TRUSTED_DOMAIN_SUPPORTED_ENCRYPTION_TYPES { ULONG SupportedEncryptionTypes;` |
| `SymbolicBackTrace` | type_alias | `payloads/Demon/include/common/Native.h:11239` | `typedef struct _RTL_PROCESS_BACKTRACE_INFORMATION { PCHAR SymbolicBackTrace;` |
| `SystemResourcesList` | type_alias | `payloads/Demon/include/common/Native.h:10402` | `typedef struct _ERESOURCE { LIST_ENTRY SystemResourcesList;` |
| `TEB_ACTIVE_FRAME_CONTEXT_FLAG_EXTENDED` | macro | `payloads/Demon/include/common/Native.h:6914` | `#define TEB_ACTIVE_FRAME_CONTEXT_FLAG_EXTENDED` |
| `TEB_ACTIVE_FRAME_FLAG_EXTENDED` | macro | `payloads/Demon/include/common/Native.h:6932` | `#define TEB_ACTIVE_FRAME_FLAG_EXTENDED` |
| `THIRDBYTE` | macro | `payloads/Demon/include/common/Native.h:128` | `#define THIRDBYTE(VALUE)` |
| `THREAD_ALERT` | macro | `payloads/Demon/include/common/Native.h:2907` | `#define THREAD_ALERT` |
| `THREAD_DIRECT_IMPERSONATION` | macro | `payloads/Demon/include/common/Native.h:2914` | `#define THREAD_DIRECT_IMPERSONATION` |
| `THREAD_GET_CONTEXT` | macro | `payloads/Demon/include/common/Native.h:2908` | `#define THREAD_GET_CONTEXT` |
| `THREAD_IMPERSONATE` | macro | `payloads/Demon/include/common/Native.h:2913` | `#define THREAD_IMPERSONATE` |
| `THREAD_QUERY_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:2911` | `#define THREAD_QUERY_INFORMATION` |
| `THREAD_SET_CONTEXT` | macro | `payloads/Demon/include/common/Native.h:2909` | `#define THREAD_SET_CONTEXT` |
| `THREAD_SET_INFORMATION` | macro | `payloads/Demon/include/common/Native.h:2910` | `#define THREAD_SET_INFORMATION` |
| `THREAD_SET_THREAD_TOKEN` | macro | `payloads/Demon/include/common/Native.h:2912` | `#define THREAD_SET_THREAD_TOKEN` |
| `THREAD_SUSPEND_RESUME` | macro | `payloads/Demon/include/common/Native.h:2906` | `#define THREAD_SUSPEND_RESUME` |
| `THREAD_TERMINATE` | macro | `payloads/Demon/include/common/Native.h:2905` | `#define THREAD_TERMINATE` |
| `TIMER_ALL_ACCESS` | macro | `payloads/Demon/include/common/Native.h:3432` | `#define TIMER_ALL_ACCESS` |
| `TIMER_MODIFY_STATE` | macro | `payloads/Demon/include/common/Native.h:3430` | `#define TIMER_MODIFY_STATE` |
| `TIMER_QUERY_STATE` | macro | `payloads/Demon/include/common/Native.h:3429` | `#define TIMER_QUERY_STATE` |
| `TLS_EXPANSION_SLOTS` | macro | `payloads/Demon/include/common/Native.h:5328` | `#define TLS_EXPANSION_SLOTS` |
| `TLS_MINIMUM_AVAILABLE` | macro | `payloads/Demon/include/common/Native.h:5327` | `#define TLS_MINIMUM_AVAILABLE` |
| `TLS_MINIMUM_AVAILABLE` | macro | `payloads/Demon/include/common/Native.h:6471` | `#define TLS_MINIMUM_AVAILABLE` |
| `TRUSTED_DOMAIN_INFORMATION_BASIC` | type_alias | `payloads/Demon/include/common/Native.h:9178` | `typedef LSA_TRUST_INFORMATION TRUSTED_DOMAIN_INFORMATION_BASIC;` |
| `TRUST_ATTRIBUTES_USER` | macro | `payloads/Demon/include/common/Native.h:9235` | `#define TRUST_ATTRIBUTES_USER` |
| `TRUST_ATTRIBUTES_VALID` | macro | `payloads/Demon/include/common/Native.h:9208` | `#define TRUST_ATTRIBUTES_VALID` |
| `TRUST_ATTRIBUTES_VALID` | macro | `payloads/Demon/include/common/Native.h:9233` | `#define TRUST_ATTRIBUTES_VALID` |
| `TRUST_ATTRIBUTE_CROSS_ORGANIZATION` | macro | `payloads/Demon/include/common/Native.h:9220` | `#define TRUST_ATTRIBUTE_CROSS_ORGANIZATION` |
| `TRUST_ATTRIBUTE_FILTER_SIDS` | macro | `payloads/Demon/include/common/Native.h:9212` | `#define TRUST_ATTRIBUTE_FILTER_SIDS` |
| `TRUST_ATTRIBUTE_FOREST_TRANSITIVE` | macro | `payloads/Demon/include/common/Native.h:9218` | `#define TRUST_ATTRIBUTE_FOREST_TRANSITIVE` |
| `TRUST_ATTRIBUTE_NON_TRANSITIVE` | macro | `payloads/Demon/include/common/Native.h:9198` | `#define TRUST_ATTRIBUTE_NON_TRANSITIVE` |
| `TRUST_ATTRIBUTE_QUARANTINED_DOMAIN` | macro | `payloads/Demon/include/common/Native.h:9214` | `#define TRUST_ATTRIBUTE_QUARANTINED_DOMAIN` |
| `TRUST_ATTRIBUTE_TREAT_AS_EXTERNAL` | macro | `payloads/Demon/include/common/Native.h:9222` | `#define TRUST_ATTRIBUTE_TREAT_AS_EXTERNAL` |
| `TRUST_ATTRIBUTE_TREE_PARENT` | macro | `payloads/Demon/include/common/Native.h:9201` | `#define TRUST_ATTRIBUTE_TREE_PARENT` |
| `TRUST_ATTRIBUTE_TREE_ROOT` | macro | `payloads/Demon/include/common/Native.h:9203` | `#define TRUST_ATTRIBUTE_TREE_ROOT` |
| `TRUST_ATTRIBUTE_TRUST_USES_AES_KEYS` | macro | `payloads/Demon/include/common/Native.h:9225` | `#define TRUST_ATTRIBUTE_TRUST_USES_AES_KEYS` |
| `TRUST_ATTRIBUTE_TRUST_USES_RC4_ENCRYPTION` | macro | `payloads/Demon/include/common/Native.h:9224` | `#define TRUST_ATTRIBUTE_TRUST_USES_RC4_ENCRYPTION` |
| `TRUST_ATTRIBUTE_UPLEVEL_ONLY` | macro | `payloads/Demon/include/common/Native.h:9199` | `#define TRUST_ATTRIBUTE_UPLEVEL_ONLY` |
| `TRUST_ATTRIBUTE_WITHIN_FOREST` | macro | `payloads/Demon/include/common/Native.h:9221` | `#define TRUST_ATTRIBUTE_WITHIN_FOREST` |
| `TRUST_AUTH_TYPE_CLEAR` | macro | `payloads/Demon/include/common/Native.h:9266` | `#define TRUST_AUTH_TYPE_CLEAR` |
| `TRUST_AUTH_TYPE_NONE` | macro | `payloads/Demon/include/common/Native.h:9264` | `#define TRUST_AUTH_TYPE_NONE` |
| `TRUST_AUTH_TYPE_NT4OWF` | macro | `payloads/Demon/include/common/Native.h:9265` | `#define TRUST_AUTH_TYPE_NT4OWF` |
| `TRUST_AUTH_TYPE_VERSION` | macro | `payloads/Demon/include/common/Native.h:9267` | `#define TRUST_AUTH_TYPE_VERSION` |
| `TRUST_DIRECTION_BIDIRECTIONAL` | macro | `payloads/Demon/include/common/Native.h:9185` | `#define TRUST_DIRECTION_BIDIRECTIONAL` |
| `TRUST_DIRECTION_DISABLED` | macro | `payloads/Demon/include/common/Native.h:9182` | `#define TRUST_DIRECTION_DISABLED` |
| `TRUST_DIRECTION_INBOUND` | macro | `payloads/Demon/include/common/Native.h:9183` | `#define TRUST_DIRECTION_INBOUND` |
| `TRUST_DIRECTION_OUTBOUND` | macro | `payloads/Demon/include/common/Native.h:9184` | `#define TRUST_DIRECTION_OUTBOUND` |
| `TRUST_TYPE_DCE` | macro | `payloads/Demon/include/common/Native.h:9192` | `#define TRUST_TYPE_DCE` |
| `TRUST_TYPE_DOWNLEVEL` | macro | `payloads/Demon/include/common/Native.h:9187` | `#define TRUST_TYPE_DOWNLEVEL` |
| `TRUST_TYPE_MIT` | macro | `payloads/Demon/include/common/Native.h:9189` | `#define TRUST_TYPE_MIT` |
| `TRUST_TYPE_UPLEVEL` | macro | `payloads/Demon/include/common/Native.h:9188` | `#define TRUST_TYPE_UPLEVEL` |
| `TXFS_LIST_TRANSACTION_LOCKED_FILES_ENTRY_FLAG_CREATED` | macro | `payloads/Demon/include/common/Native.h:1961` | `#define TXFS_LIST_TRANSACTION_LOCKED_FILES_ENTRY_FLAG_CREATED` |
| `TXFS_LIST_TRANSACTION_LOCKED_FILES_ENTRY_FLAG_DELETED` | macro | `payloads/Demon/include/common/Native.h:1962` | `#define TXFS_LIST_TRANSACTION_LOCKED_FILES_ENTRY_FLAG_DELETED` |
| `TXFS_LOGGING_MODE_FULL` | macro | `payloads/Demon/include/common/Native.h:1602` | `#define TXFS_LOGGING_MODE_FULL` |
| `TXFS_LOGGING_MODE_SIMPLE` | macro | `payloads/Demon/include/common/Native.h:1601` | `#define TXFS_LOGGING_MODE_SIMPLE` |
| `TXFS_MODIFY_RM_VALID_FLAGS` | macro | `payloads/Demon/include/common/Native.h:1609` | `#define TXFS_MODIFY_RM_VALID_FLAGS` |
| `TXFS_QUERY_RM_INFORMATION_VALID_FLAGS` | macro | `payloads/Demon/include/common/Native.h:1690` | `#define TXFS_QUERY_RM_INFORMATION_VALID_FLAGS` |
| `TXFS_RM_FLAG_DO_NOT_RESET_RM_AT_NEXT_START` | macro | `payloads/Demon/include/common/Native.h:1597` | `#define TXFS_RM_FLAG_DO_NOT_RESET_RM_AT_NEXT_START` |
| `TXFS_RM_FLAG_ENFORCE_MINIMUM_SIZE` | macro | `payloads/Demon/include/common/Native.h:1594` | `#define TXFS_RM_FLAG_ENFORCE_MINIMUM_SIZE` |
| `TXFS_RM_FLAG_GROW_LOG` | macro | `payloads/Demon/include/common/Native.h:1592` | `#define TXFS_RM_FLAG_GROW_LOG` |
| `TXFS_RM_FLAG_LOGGING_MODE` | macro | `payloads/Demon/include/common/Native.h:1583` | `#define TXFS_RM_FLAG_LOGGING_MODE` |
| `TXFS_RM_FLAG_LOG_AUTO_SHRINK_PERCENTAGE` | macro | `payloads/Demon/include/common/Native.h:1589` | `#define TXFS_RM_FLAG_LOG_AUTO_SHRINK_PERCENTAGE` |
| `TXFS_RM_FLAG_LOG_CONTAINER_COUNT_MAX` | macro | `payloads/Demon/include/common/Native.h:1585` | `#define TXFS_RM_FLAG_LOG_CONTAINER_COUNT_MAX` |
| `TXFS_RM_FLAG_LOG_CONTAINER_COUNT_MIN` | macro | `payloads/Demon/include/common/Native.h:1586` | `#define TXFS_RM_FLAG_LOG_CONTAINER_COUNT_MIN` |
| `TXFS_RM_FLAG_LOG_GROWTH_INCREMENT_NUM_CONTAINERS` | macro | `payloads/Demon/include/common/Native.h:1587` | `#define TXFS_RM_FLAG_LOG_GROWTH_INCREMENT_NUM_CONTAINERS` |
| `TXFS_RM_FLAG_LOG_GROWTH_INCREMENT_PERCENT` | macro | `payloads/Demon/include/common/Native.h:1588` | `#define TXFS_RM_FLAG_LOG_GROWTH_INCREMENT_PERCENT` |
| `TXFS_RM_FLAG_LOG_NO_CONTAINER_COUNT_MAX` | macro | `payloads/Demon/include/common/Native.h:1590` | `#define TXFS_RM_FLAG_LOG_NO_CONTAINER_COUNT_MAX` |
| `TXFS_RM_FLAG_LOG_NO_CONTAINER_COUNT_MIN` | macro | `payloads/Demon/include/common/Native.h:1591` | `#define TXFS_RM_FLAG_LOG_NO_CONTAINER_COUNT_MIN` |
| `TXFS_RM_FLAG_PREFER_AVAILABILITY` | macro | `payloads/Demon/include/common/Native.h:1599` | `#define TXFS_RM_FLAG_PREFER_AVAILABILITY` |
| `TXFS_RM_FLAG_PREFER_CONSISTENCY` | macro | `payloads/Demon/include/common/Native.h:1598` | `#define TXFS_RM_FLAG_PREFER_CONSISTENCY` |
| `TXFS_RM_FLAG_PRESERVE_CHANGES` | macro | `payloads/Demon/include/common/Native.h:1595` | `#define TXFS_RM_FLAG_PRESERVE_CHANGES` |
| `TXFS_RM_FLAG_RENAME_RM` | macro | `payloads/Demon/include/common/Native.h:1584` | `#define TXFS_RM_FLAG_RENAME_RM` |
| `TXFS_RM_FLAG_RESET_RM_AT_NEXT_START` | macro | `payloads/Demon/include/common/Native.h:1596` | `#define TXFS_RM_FLAG_RESET_RM_AT_NEXT_START` |
| `TXFS_RM_FLAG_SHRINK_LOG` | macro | `payloads/Demon/include/common/Native.h:1593` | `#define TXFS_RM_FLAG_SHRINK_LOG` |
| `TXFS_RM_STATE_ACTIVE` | macro | `payloads/Demon/include/common/Native.h:1687` | `#define TXFS_RM_STATE_ACTIVE` |
| `TXFS_RM_STATE_NOT_STARTED` | macro | `payloads/Demon/include/common/Native.h:1685` | `#define TXFS_RM_STATE_NOT_STARTED` |
| `TXFS_RM_STATE_SHUTTING_DOWN` | macro | `payloads/Demon/include/common/Native.h:1688` | `#define TXFS_RM_STATE_SHUTTING_DOWN` |
| `TXFS_RM_STATE_STARTING` | macro | `payloads/Demon/include/common/Native.h:1686` | `#define TXFS_RM_STATE_STARTING` |
| `TXFS_ROLLFORWARD_REDO_FLAG_USE_LAST_REDO_LSN` | macro | `payloads/Demon/include/common/Native.h:1795` | `#define TXFS_ROLLFORWARD_REDO_FLAG_USE_LAST_REDO_LSN` |
| `TXFS_ROLLFORWARD_REDO_FLAG_USE_LAST_VIRTUAL_CLOCK` | macro | `payloads/Demon/include/common/Native.h:1796` | `#define TXFS_ROLLFORWARD_REDO_FLAG_USE_LAST_VIRTUAL_CLOCK` |
| `TXFS_ROLLFORWARD_REDO_VALID_FLAGS` | macro | `payloads/Demon/include/common/Native.h:1798` | `#define TXFS_ROLLFORWARD_REDO_VALID_FLAGS` |
| `TXFS_SAVEPOINT_CLEAR` | macro | `payloads/Demon/include/common/Native.h:2164` | `#define TXFS_SAVEPOINT_CLEAR` |
| `TXFS_SAVEPOINT_CLEAR_ALL` | macro | `payloads/Demon/include/common/Native.h:2170` | `#define TXFS_SAVEPOINT_CLEAR_ALL` |
| `TXFS_SAVEPOINT_ROLLBACK` | macro | `payloads/Demon/include/common/Native.h:2157` | `#define TXFS_SAVEPOINT_ROLLBACK` |
| `TXFS_SAVEPOINT_SET` | macro | `payloads/Demon/include/common/Native.h:2151` | `#define TXFS_SAVEPOINT_SET` |
| `TXFS_START_RM_FLAG_LOGGING_MODE` | macro | `payloads/Demon/include/common/Native.h:1820` | `#define TXFS_START_RM_FLAG_LOGGING_MODE` |
| `TXFS_START_RM_FLAG_LOG_AUTO_SHRINK_PERCENTAGE` | macro | `payloads/Demon/include/common/Native.h:1815` | `#define TXFS_START_RM_FLAG_LOG_AUTO_SHRINK_PERCENTAGE` |
| `TXFS_START_RM_FLAG_LOG_CONTAINER_COUNT_MAX` | macro | `payloads/Demon/include/common/Native.h:1810` | `#define TXFS_START_RM_FLAG_LOG_CONTAINER_COUNT_MAX` |
| `TXFS_START_RM_FLAG_LOG_CONTAINER_COUNT_MIN` | macro | `payloads/Demon/include/common/Native.h:1811` | `#define TXFS_START_RM_FLAG_LOG_CONTAINER_COUNT_MIN` |
| `TXFS_START_RM_FLAG_LOG_CONTAINER_SIZE` | macro | `payloads/Demon/include/common/Native.h:1812` | `#define TXFS_START_RM_FLAG_LOG_CONTAINER_SIZE` |
| `TXFS_START_RM_FLAG_LOG_GROWTH_INCREMENT_NUM_CONTAINERS` | macro | `payloads/Demon/include/common/Native.h:1813` | `#define TXFS_START_RM_FLAG_LOG_GROWTH_INCREMENT_NUM_CONTAINERS` |
| `TXFS_START_RM_FLAG_LOG_GROWTH_INCREMENT_PERCENT` | macro | `payloads/Demon/include/common/Native.h:1814` | `#define TXFS_START_RM_FLAG_LOG_GROWTH_INCREMENT_PERCENT` |
| `TXFS_START_RM_FLAG_LOG_NO_CONTAINER_COUNT_MAX` | macro | `payloads/Demon/include/common/Native.h:1816` | `#define TXFS_START_RM_FLAG_LOG_NO_CONTAINER_COUNT_MAX` |
| `TXFS_START_RM_FLAG_LOG_NO_CONTAINER_COUNT_MIN` | macro | `payloads/Demon/include/common/Native.h:1817` | `#define TXFS_START_RM_FLAG_LOG_NO_CONTAINER_COUNT_MIN` |
| `TXFS_START_RM_FLAG_PREFER_AVAILABILITY` | macro | `payloads/Demon/include/common/Native.h:1824` | `#define TXFS_START_RM_FLAG_PREFER_AVAILABILITY` |
| `TXFS_START_RM_FLAG_PREFER_CONSISTENCY` | macro | `payloads/Demon/include/common/Native.h:1823` | `#define TXFS_START_RM_FLAG_PREFER_CONSISTENCY` |
| `TXFS_START_RM_FLAG_PRESERVE_CHANGES` | macro | `payloads/Demon/include/common/Native.h:1821` | `#define TXFS_START_RM_FLAG_PRESERVE_CHANGES` |
| `TXFS_START_RM_FLAG_RECOVER_BEST_EFFORT` | macro | `payloads/Demon/include/common/Native.h:1819` | `#define TXFS_START_RM_FLAG_RECOVER_BEST_EFFORT` |
| `TXFS_START_RM_VALID_FLAGS` | macro | `payloads/Demon/include/common/Native.h:1826` | `#define TXFS_START_RM_VALID_FLAGS` |
| `TXFS_TRANSACTED_VERSION_NONTRANSACTED` | macro | `payloads/Demon/include/common/Native.h:2108` | `#define TXFS_TRANSACTED_VERSION_NONTRANSACTED` |
| `TXFS_TRANSACTED_VERSION_UNCOMMITTED` | macro | `payloads/Demon/include/common/Native.h:2109` | `#define TXFS_TRANSACTED_VERSION_UNCOMMITTED` |
| `TXFS_TRANSACTION_STATE_ACTIVE` | macro | `payloads/Demon/include/common/Native.h:1605` | `#define TXFS_TRANSACTION_STATE_ACTIVE` |
| `TXFS_TRANSACTION_STATE_NONE` | macro | `payloads/Demon/include/common/Native.h:1604` | `#define TXFS_TRANSACTION_STATE_NONE` |
| `TXFS_TRANSACTION_STATE_NOTACTIVE` | macro | `payloads/Demon/include/common/Native.h:1607` | `#define TXFS_TRANSACTION_STATE_NOTACTIVE` |
| `TXFS_TRANSACTION_STATE_PREPARED` | macro | `payloads/Demon/include/common/Native.h:1606` | `#define TXFS_TRANSACTION_STATE_PREPARED` |
| `TableRoot` | type_alias | `payloads/Demon/include/common/Native.h:10038` | `typedef struct _RTL_GENERIC_TABLE { PRTL_SPLAY_LINKS TableRoot;` |
| `Tag` | type_alias | `payloads/Demon/include/common/Native.h:4415` | `typedef struct _SYSTEM_POOLTAG { union { UCHAR Tag[4];` |
| `TagIndex` | type_alias | `payloads/Demon/include/common/Native.h:10574` | `typedef struct _HEAP_FREE_ENTRY_EXTRA { USHORT TagIndex;` |
| `TargetAddress` | type_alias | `payloads/Demon/include/common/Native.h:5093` | `typedef struct _HOTPATCH_HOOK_DESCRIPTOR { ULONG_PTR TargetAddress;` |
| `Text` | type_alias | `payloads/Demon/include/common/Native.h:11540` | `typedef struct _CHANNEL_MESSAGE { PVOID Text;` |
| `ThisBaseVersion` | type_alias | `payloads/Demon/include/common/Native.h:2110` | `typedef struct _TXFS_GET_TRANSACTED_VERSION { // // The version that this handle is opened to. This will be // TXFS_TRAN` |
| `ThreadHandle` | type_alias | `payloads/Demon/include/common/Native.h:6259` | `typedef struct _BASE_CREATETHREAD_MSG { PVOID ThreadHandle;` |
| `ThreadInfo` | type_alias | `payloads/Demon/include/common/Native.h:4382` | `typedef struct _SYSTEM_EXTENDED_THREAD_INFORMATION { SYSTEM_THREAD_INFORMATION ThreadInfo;` |
| `TickCountLowDeprecated` | type_alias | `payloads/Demon/include/common/Native.h:10701` | `typedef struct _KUSER_SHARED_DATA { ULONG TickCountLowDeprecated;` |
| `TimeAdjustment` | type_alias | `payloads/Demon/include/common/Native.h:4830` | `typedef struct _SYSTEM_QUERY_TIME_ADJUST_INFORMATION { ULONG TimeAdjustment;` |
| `TimeAdjustment` | type_alias | `payloads/Demon/include/common/Native.h:4836` | `typedef struct _SYSTEM_SET_TIME_ADJUST_INFORMATION { ULONG TimeAdjustment;` |
| `TitleIndex` | type_alias | `payloads/Demon/include/common/Native.h:3798` | `typedef struct _KEY_VALUE_BASIC_INFORMATION { ULONG TitleIndex;` |
| `TitleIndex` | type_alias | `payloads/Demon/include/common/Native.h:3805` | `typedef struct _KEY_VALUE_FULL_INFORMATION { ULONG TitleIndex;` |
| `TitleIndex` | type_alias | `payloads/Demon/include/common/Native.h:3815` | `typedef struct _KEY_VALUE_PARTIAL_INFORMATION { ULONG TitleIndex;` |
| `TotalMemoryReserved` | type_alias | `payloads/Demon/include/common/Native.h:10495` | `typedef struct _HEAP_COUNTERS { ULONG TotalMemoryReserved;` |
| `TotalSize` | type_alias | `payloads/Demon/include/common/Native.h:4405` | `typedef struct _SYSTEM_POOL_INFORMATION { SIZE_T TotalSize;` |
| `TransactionId` | type_alias | `payloads/Demon/include/common/Native.h:2034` | `typedef struct _TXFS_LIST_TRANSACTIONS_ENTRY { // // Transaction GUID. // GUID TransactionId;` |
| `TransactionsActiveAtSnapshot` | type_alias | `payloads/Demon/include/common/Native.h:2186` | `typedef struct _TXFS_TRANSACTION_ACTIVE_INFO { BOOLEAN TransactionsActiveAtSnapshot;` |
| `TransferAddress` | type_alias | `payloads/Demon/include/common/Native.h:10123` | `typedef struct _SECTION_IMAGE_INFORMATION { PVOID TransferAddress;` |
| `TransferAddress` | type_alias | `payloads/Demon/include/common/Native.h:10160` | `typedef struct _SECTION_IMAGE_INFORMATION64 { ULONGLONG TransferAddress;` |
| `Type` | type_alias | `payloads/Demon/include/common/Native.h:1204` | `typedef struct _FILE_PREFETCH { ULONG Type;` |
| `Type` | type_alias | `payloads/Demon/include/common/Native.h:1210` | `typedef struct _FILE_PREFETCH_EX { ULONG Type;` |
| `Type` | type_alias | `payloads/Demon/include/common/Native.h:3822` | `typedef struct _KEY_VALUE_PARTIAL_INFORMATION_ALIGN64 { ULONG Type;` |
| `Type` | type_alias | `payloads/Demon/include/common/Native.h:8722` | `typedef struct _SE_ADT_PARAMETER_ARRAY_ENTRY { SE_ADT_PARAMETER_TYPE Type;` |
| `Type` | type_alias | `payloads/Demon/include/common/Native.h:10346` | `typedef struct _DISPATCHER_HEADER { union { struct { UCHAR Type;` |
| `TypeName` | type_alias | `payloads/Demon/include/common/Native.h:3490` | `typedef struct _OBJECT_TYPE_INFORMATION { UNICODE_STRING TypeName;` |
| `UNICODE_NULL` | macro | `payloads/Demon/include/common/Native.h:412` | `#define UNICODE_NULL` |
| `UNICODE_NULL` | macro | `payloads/Demon/include/common/Native.h:544` | `#define UNICODE_NULL` |
| `UNICODE_STRING32` | type_alias | `payloads/Demon/include/common/Native.h:409` | `typedef STRING32 UNICODE_STRING32;` |
| `UNICODE_STRING64` | type_alias | `payloads/Demon/include/common/Native.h:425` | `typedef STRING64 UNICODE_STRING64;` |
| `UNICODE_STRING_MAX_BYTES` | macro | `payloads/Demon/include/common/Native.h:547` | `#define UNICODE_STRING_MAX_BYTES` |
| `UNICODE_STRING_MAX_CHARS` | macro | `payloads/Demon/include/common/Native.h:550` | `#define UNICODE_STRING_MAX_CHARS` |
| `UNLINK` | macro | `payloads/Demon/include/common/Native.h:85` | `#define UNLINK(x)` |
| `UNREFERENCED_PARAMETER` | macro | `payloads/Demon/include/common/Native.h:57` | `#define UNREFERENCED_PARAMETER(P)` |
| `USERSRV_FIRST_API_NUMBER` | macro | `payloads/Demon/include/common/Native.h:5954` | `#define USERSRV_FIRST_API_NUMBER` |
| `USERSRV_SERVERDLL_INDEX` | macro | `payloads/Demon/include/common/Native.h:5953` | `#define USERSRV_SERVERDLL_INDEX` |
| `USER_SHARED_DATA` | macro | `payloads/Demon/include/common/Native.h:10903` | `#define USER_SHARED_DATA` |
| `USN_DELETE_FLAG_DELETE` | macro | `payloads/Demon/include/common/Native.h:1140` | `#define USN_DELETE_FLAG_DELETE` |
| `USN_DELETE_FLAG_NOTIFY` | macro | `payloads/Demon/include/common/Native.h:1141` | `#define USN_DELETE_FLAG_NOTIFY` |
| `USN_DELETE_VALID_FLAGS` | macro | `payloads/Demon/include/common/Native.h:1143` | `#define USN_DELETE_VALID_FLAGS` |
| `USN_PAGE_SIZE` | macro | `payloads/Demon/include/common/Native.h:1096` | `#define USN_PAGE_SIZE` |
| `USN_REASON_BASIC_INFO_CHANGE` | macro | `payloads/Demon/include/common/Native.h:1111` | `#define USN_REASON_BASIC_INFO_CHANGE` |
| `USN_REASON_CLOSE` | macro | `payloads/Demon/include/common/Native.h:1119` | `#define USN_REASON_CLOSE` |
| `USN_REASON_COMPRESSION_CHANGE` | macro | `payloads/Demon/include/common/Native.h:1113` | `#define USN_REASON_COMPRESSION_CHANGE` |
| `USN_REASON_DATA_EXTEND` | macro | `payloads/Demon/include/common/Native.h:1099` | `#define USN_REASON_DATA_EXTEND` |
| `USN_REASON_DATA_OVERWRITE` | macro | `payloads/Demon/include/common/Native.h:1098` | `#define USN_REASON_DATA_OVERWRITE` |
| `USN_REASON_DATA_TRUNCATION` | macro | `payloads/Demon/include/common/Native.h:1100` | `#define USN_REASON_DATA_TRUNCATION` |
| `USN_REASON_EA_CHANGE` | macro | `payloads/Demon/include/common/Native.h:1106` | `#define USN_REASON_EA_CHANGE` |
| `USN_REASON_ENCRYPTION_CHANGE` | macro | `payloads/Demon/include/common/Native.h:1114` | `#define USN_REASON_ENCRYPTION_CHANGE` |
| `USN_REASON_FILE_CREATE` | macro | `payloads/Demon/include/common/Native.h:1104` | `#define USN_REASON_FILE_CREATE` |
| `USN_REASON_FILE_DELETE` | macro | `payloads/Demon/include/common/Native.h:1105` | `#define USN_REASON_FILE_DELETE` |
| `USN_REASON_HARD_LINK_CHANGE` | macro | `payloads/Demon/include/common/Native.h:1112` | `#define USN_REASON_HARD_LINK_CHANGE` |
| `USN_REASON_INDEXABLE_CHANGE` | macro | `payloads/Demon/include/common/Native.h:1110` | `#define USN_REASON_INDEXABLE_CHANGE` |
| `USN_REASON_NAMED_DATA_EXTEND` | macro | `payloads/Demon/include/common/Native.h:1102` | `#define USN_REASON_NAMED_DATA_EXTEND` |
| `USN_REASON_NAMED_DATA_OVERWRITE` | macro | `payloads/Demon/include/common/Native.h:1101` | `#define USN_REASON_NAMED_DATA_OVERWRITE` |
| `USN_REASON_NAMED_DATA_TRUNCATION` | macro | `payloads/Demon/include/common/Native.h:1103` | `#define USN_REASON_NAMED_DATA_TRUNCATION` |
| `USN_REASON_OBJECT_ID_CHANGE` | macro | `payloads/Demon/include/common/Native.h:1115` | `#define USN_REASON_OBJECT_ID_CHANGE` |
| `USN_REASON_RENAME_NEW_NAME` | macro | `payloads/Demon/include/common/Native.h:1109` | `#define USN_REASON_RENAME_NEW_NAME` |
| `USN_REASON_RENAME_OLD_NAME` | macro | `payloads/Demon/include/common/Native.h:1108` | `#define USN_REASON_RENAME_OLD_NAME` |
| `USN_REASON_REPARSE_POINT_CHANGE` | macro | `payloads/Demon/include/common/Native.h:1116` | `#define USN_REASON_REPARSE_POINT_CHANGE` |
| `USN_REASON_SECURITY_CHANGE` | macro | `payloads/Demon/include/common/Native.h:1107` | `#define USN_REASON_SECURITY_CHANGE` |
| `USN_REASON_STREAM_CHANGE` | macro | `payloads/Demon/include/common/Native.h:1117` | `#define USN_REASON_STREAM_CHANGE` |
| `USN_REASON_TRANSACTED_CHANGE` | macro | `payloads/Demon/include/common/Native.h:1118` | `#define USN_REASON_TRANSACTED_CHANGE` |
| `USN_SOURCE_AUXILIARY_DATA` | macro | `payloads/Demon/include/common/Native.h:1165` | `#define USN_SOURCE_AUXILIARY_DATA` |
| `USN_SOURCE_DATA_MANAGEMENT` | macro | `payloads/Demon/include/common/Native.h:1164` | `#define USN_SOURCE_DATA_MANAGEMENT` |
| `USN_SOURCE_REPLICATION_MANAGEMENT` | macro | `payloads/Demon/include/common/Native.h:1166` | `#define USN_SOURCE_REPLICATION_MANAGEMENT` |
| `UniqueProcess` | type_alias | `payloads/Demon/include/common/Native.h:3919` | `typedef struct _CLIENT_ID { HANDLE UniqueProcess;` |
| `UniqueProcess` | type_alias | `payloads/Demon/include/common/Native.h:3925` | `typedef struct _CLIENT_ID32 { ULONG UniqueProcess;` |
| `UniqueProcess` | type_alias | `payloads/Demon/include/common/Native.h:3931` | `typedef struct _CLIENT_ID64 { ULONGLONG UniqueProcess;` |
| `UniqueProcessId` | type_alias | `payloads/Demon/include/common/Native.h:4458` | `typedef struct _SYSTEM_HANDLE_TABLE_ENTRY_INFO { USHORT UniqueProcessId;` |
| `Unknown` | type_alias | `payloads/Demon/include/common/Native.h:10221` | `typedef struct _STARTUP_ARGUMENT { //ULONG Unknown[ 3 ];` |
| `UsageCount` | type_alias | `payloads/Demon/include/common/Native.h:3385` | `typedef struct _ATOM_BASIC_INFORMATION { USHORT UsageCount;` |
| `Use` | type_alias | `payloads/Demon/include/common/Native.h:8550` | `typedef struct _LSA_TRANSLATED_SID2 { SID_NAME_USE Use;` |
| `Use` | type_alias | `payloads/Demon/include/common/Native.h:8557` | `typedef struct _LSA_TRANSLATED_NAME { SID_NAME_USE Use;` |
| `Use` | type_alias | `payloads/Demon/include/common/Native.h:8913` | `typedef struct _LSA_TRANSLATED_SID { SID_NAME_USE Use;` |
| `UserSid` | type_alias | `payloads/Demon/include/common/Native.h:7615` | `typedef struct _USER_PERMISSION { USER_SID UserSid;` |
| `VALID_PER_USER_AUDIT_POLICY_FLAG` | macro | `payloads/Demon/include/common/Native.h:9006` | `#define VALID_PER_USER_AUDIT_POLICY_FLAG` |
| `VER_SERVER_NT` | macro | `payloads/Demon/include/common/Native.h:7339` | `#define VER_SERVER_NT` |
| `VER_SUITE_BACKOFFICE` | macro | `payloads/Demon/include/common/Native.h:7343` | `#define VER_SUITE_BACKOFFICE` |
| `VER_SUITE_BLADE` | macro | `payloads/Demon/include/common/Native.h:7351` | `#define VER_SUITE_BLADE` |
| `VER_SUITE_COMMUNICATIONS` | macro | `payloads/Demon/include/common/Native.h:7344` | `#define VER_SUITE_COMMUNICATIONS` |
| `VER_SUITE_COMPUTE_SERVER` | macro | `payloads/Demon/include/common/Native.h:7355` | `#define VER_SUITE_COMPUTE_SERVER` |
| `VER_SUITE_DATACENTER` | macro | `payloads/Demon/include/common/Native.h:7348` | `#define VER_SUITE_DATACENTER` |
| `VER_SUITE_EMBEDDEDNT` | macro | `payloads/Demon/include/common/Native.h:7347` | `#define VER_SUITE_EMBEDDEDNT` |
| `VER_SUITE_EMBEDDED_RESTRICTED` | macro | `payloads/Demon/include/common/Native.h:7352` | `#define VER_SUITE_EMBEDDED_RESTRICTED` |
| `VER_SUITE_ENTERPRISE` | macro | `payloads/Demon/include/common/Native.h:7342` | `#define VER_SUITE_ENTERPRISE` |
| `VER_SUITE_PERSONAL` | macro | `payloads/Demon/include/common/Native.h:7350` | `#define VER_SUITE_PERSONAL` |
| `VER_SUITE_SECURITY_APPLIANCE` | macro | `payloads/Demon/include/common/Native.h:7353` | `#define VER_SUITE_SECURITY_APPLIANCE` |
| `VER_SUITE_SINGLEUSERTS` | macro | `payloads/Demon/include/common/Native.h:7349` | `#define VER_SUITE_SINGLEUSERTS` |
| `VER_SUITE_SMALLBUSINESS` | macro | `payloads/Demon/include/common/Native.h:7341` | `#define VER_SUITE_SMALLBUSINESS` |
| `VER_SUITE_SMALLBUSINESS_RESTRICTED` | macro | `payloads/Demon/include/common/Native.h:7346` | `#define VER_SUITE_SMALLBUSINESS_RESTRICTED` |
| `VER_SUITE_STORAGE_SERVER` | macro | `payloads/Demon/include/common/Native.h:7354` | `#define VER_SUITE_STORAGE_SERVER` |
| `VER_SUITE_TERMINAL` | macro | `payloads/Demon/include/common/Native.h:7345` | `#define VER_SUITE_TERMINAL` |
| `VER_WORKSTATION_NT` | macro | `payloads/Demon/include/common/Native.h:7340` | `#define VER_WORKSTATION_NT` |
| `VOLUME_IS_DIRTY` | macro | `payloads/Demon/include/common/Native.h:1198` | `#define VOLUME_IS_DIRTY` |
| `VOLUME_SESSION_OPEN` | macro | `payloads/Demon/include/common/Native.h:1200` | `#define VOLUME_SESSION_OPEN` |
| `VOLUME_UPGRADE_SCHEDULED` | macro | `payloads/Demon/include/common/Native.h:1199` | `#define VOLUME_UPGRADE_SCHEDULED` |
| `ValidDataLength` | type_alias | `payloads/Demon/include/common/Native.h:4048` | `typedef struct _FILE_VALID_DATA_LENGTH_INFORMATION { // ntddk nthal LARGE_INTEGER ValidDataLength;` |
| `ValueName` | type_alias | `payloads/Demon/include/common/Native.h:3828` | `typedef struct _KEY_VALUE_ENTRY { PUNICODE_STRING ValueName;` |
| `VerifyMode` | type_alias | `payloads/Demon/include/common/Native.h:5056` | `typedef struct _SYSTEM_VERIFIER_INFORMATION_EX { ULONG VerifyMode;` |
| `Version` | type_alias | `payloads/Demon/include/common/Native.h:887` | `typedef struct _CSV_NAMESPACE_INFO { ULONG Version;` |
| `Version` | type_alias | `payloads/Demon/include/common/Native.h:7551` | `typedef struct _FILE_PATH { ULONG Version;` |
| `Version` | type_alias | `payloads/Demon/include/common/Native.h:7581` | `typedef struct _BOOT_ENTRY { ULONG Version;` |
| `Version` | type_alias | `payloads/Demon/include/common/Native.h:7594` | `typedef struct _BOOT_OPTIONS { ULONG Version;` |
| `Version` | type_alias | `payloads/Demon/include/common/Native.h:9853` | `typedef struct _EFI_DRIVER_ENTRY { ULONG Version;` |
| `VetoType` | type_alias | `payloads/Demon/include/common/Native.h:4584` | `typedef struct _SYSTEM_LEGACY_DRIVER_INFORMATION { ULONG VetoType;` |
| `VideoMode` | type_alias | `payloads/Demon/include/common/Native.h:6330` | `typedef struct _BASE_SOUNDSENTRY_NOTIFICATION_MSG { ULONG VideoMode;` |
| `VirtualAddress` | type_alias | `payloads/Demon/include/common/Native.h:3355` | `typedef struct _MEMORY_WORKING_SET_EX_INFORMATION { PVOID VirtualAddress;` |
| `VirtualAddress` | type_alias | `payloads/Demon/include/common/Native.h:4428` | `typedef struct _SYSTEM_BIGPOOL_ENTRY { union { PVOID VirtualAddress;` |
| `VirtualAddress` | type_alias | `payloads/Demon/include/common/Native.h:11226` | `typedef struct _MEMORY_RANGE_ENTRY { PVOID VirtualAddress;` |
| `VolumeFlags` | type_alias | `payloads/Demon/include/common/Native.h:2210` | `typedef struct _FILE_FS_PERSISTENT_VOLUME_INFORMATION { ULONG VolumeFlags;` |
| `WDSTATE_FIRED` | macro | `payloads/Demon/include/common/Native.h:5199` | `#define WDSTATE_FIRED` |
| `WDSTATE_HARDWARE_ENABLED` | macro | `payloads/Demon/include/common/Native.h:5200` | `#define WDSTATE_HARDWARE_ENABLED` |
| `WDSTATE_HARDWARE_PRESENT` | macro | `payloads/Demon/include/common/Native.h:5202` | `#define WDSTATE_HARDWARE_PRESENT` |
| `WDSTATE_STARTED` | macro | `payloads/Demon/include/common/Native.h:5201` | `#define WDSTATE_STARTED` |
| `WIN32_CLIENT_INFO_LENGTH` | macro | `payloads/Demon/include/common/Native.h:3275` | `#define WIN32_CLIENT_INFO_LENGTH` |
| `WIN32_CLIENT_INFO_LENGTH` | macro | `payloads/Demon/include/common/Native.h:6465` | `#define WIN32_CLIENT_INFO_LENGTH` |
| `WIN32_CLIENT_INFO_SPIN_COUNT` | macro | `payloads/Demon/include/common/Native.h:6467` | `#define WIN32_CLIENT_INFO_SPIN_COUNT` |
| `WINDOWS_OS_OPTIONS_SIGNATURE` | macro | `payloads/Demon/include/common/Native.h:7578` | `#define WINDOWS_OS_OPTIONS_SIGNATURE` |
| `WINDOWS_OS_OPTIONS_VERSION` | macro | `payloads/Demon/include/common/Native.h:7580` | `#define WINDOWS_OS_OPTIONS_VERSION` |
| `WINSS_OBJECT_DIRECTORY_NAME` | macro | `payloads/Demon/include/common/Native.h:5942` | `#define WINSS_OBJECT_DIRECTORY_NAME` |
| `WOW64_POINTER` | macro | `payloads/Demon/include/common/Native.h:5435` | `#define WOW64_POINTER(Type)` |
| `WOW64_SYSTEM_DIRECTORY` | macro | `payloads/Demon/include/common/Native.h:5393` | `#define WOW64_SYSTEM_DIRECTORY` |
| `WOW64_SYSTEM_DIRECTORY_U` | macro | `payloads/Demon/include/common/Native.h:5394` | `#define WOW64_SYSTEM_DIRECTORY_U` |
| `WOW64_X86_TAG` | macro | `payloads/Demon/include/common/Native.h:5395` | `#define WOW64_X86_TAG` |
| `WOW64_X86_TAG_U` | macro | `payloads/Demon/include/common/Native.h:5396` | `#define WOW64_X86_TAG_U` |
| `WOWAddress` | macro | `payloads/Demon/include/common/Native.h:7105` | `#define WOWAddress()` |
| `WRITE_JMP` | macro | `payloads/Demon/include/common/Native.h:110` | `#define WRITE_JMP( from, to )` |
| `WdHandler` | type_alias | `payloads/Demon/include/common/Native.h:5193` | `typedef struct _SYSTEM_WATCHDOG_HANDLER_INFORMATION { PWD_HANDLER WdHandler;` |
| `WdInfoClass` | type_alias | `payloads/Demon/include/common/Native.h:5203` | `typedef struct _SYSTEM_WATCHDOG_TIMER_INFORMATION { WATCHDOG_INFORMATION_CLASS WdInfoClass;` |
| `WindowsDirectory` | type_alias | `payloads/Demon/include/common/Native.h:6413` | `typedef struct _BASE_STATIC_SERVER_DATA { UNICODE_STRING WindowsDirectory;` |
| `Wow64` | type_alias | `payloads/Demon/include/common/Native.h:6546` | `typedef struct _WOW64_PROCESS { PVOID Wow64;` |
| `XSTATE_GSSE` | macro | `payloads/Demon/include/common/Native.h:10661` | `#define XSTATE_GSSE` |
| `XSTATE_LEGACY_FLOATING_POINT` | macro | `payloads/Demon/include/common/Native.h:10659` | `#define XSTATE_LEGACY_FLOATING_POINT` |
| `XSTATE_LEGACY_SSE` | macro | `payloads/Demon/include/common/Native.h:10660` | `#define XSTATE_LEGACY_SSE` |
| `XSTATE_MASK_GSSE` | macro | `payloads/Demon/include/common/Native.h:10666` | `#define XSTATE_MASK_GSSE` |
| `XSTATE_MASK_LEGACY` | macro | `payloads/Demon/include/common/Native.h:10665` | `#define XSTATE_MASK_LEGACY` |
| `XSTATE_MASK_LEGACY_FLOATING_POINT` | macro | `payloads/Demon/include/common/Native.h:10663` | `#define XSTATE_MASK_LEGACY_FLOATING_POINT` |
| `XSTATE_MASK_LEGACY_SSE` | macro | `payloads/Demon/include/common/Native.h:10664` | `#define XSTATE_MASK_LEGACY_SSE` |
| `Year` | type_alias | `payloads/Demon/include/common/Native.h:3625` | `typedef struct _TIME_FIELDS { CSHORT Year;` |
| `ZwCurrentProcess` | macro | `payloads/Demon/include/common/Native.h:2892` | `#define ZwCurrentProcess()` |
| `ZwCurrentProcess` | macro | `payloads/Demon/include/common/Native.h:7101` | `#define ZwCurrentProcess()` |
| `ZwCurrentThread` | macro | `payloads/Demon/include/common/Native.h:2893` | `#define ZwCurrentThread()` |
| `ZwWow64CsrCaptureMessageBuffer` | function | `payloads/Demon/include/common/Native.h:22224` | `void NTAPI ZwWow64CsrCaptureMessageBuffer( _Inout_ PCSR_CAPTURE_HEADER CaptureBuffer, IN PVOID Buffer OPTIONAL, IN ULONG` |
| `ZwWow64CsrCaptureMessageString` | function | `payloads/Demon/include/common/Native.h:22233` | `void NTAPI ZwWow64CsrCaptureMessageString( _Inout_ PCSR_CAPTURE_HEADER CaptureBuffer, IN PCSTR String, IN ULONG Length, ` |
| `ZwWow64CsrFreeCaptureBuffer` | function | `payloads/Demon/include/common/Native.h:22254` | `void NTAPI ZwWow64CsrFreeCaptureBuffer( IN PCSR_CAPTURE_HEADER CaptureBuffer );` |
| `ZwWow64GetCurrentProcessorNumberEx` | function | `payloads/Demon/include/common/Native.h:22202` | `void NTAPI ZwWow64GetCurrentProcessorNumberEx( OUT PPROCESSOR_NUMBER ProcNumber );` |
| `_ACTIVATION_CONTEXT` | struct | `payloads/Demon/include/common/Native.h:6498` | `` |
| `_ACTIVATION_CONTEXT_DATA` | struct | `payloads/Demon/include/common/Native.h:6487` | `` |
| `_ACTIVATION_CONTEXT_RUN_LEVEL_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:6221` | `` |
| `_ACTIVATION_CONTEXT_STACK` | struct | `payloads/Demon/include/common/Native.h:6903` | `` |
| `_ALTERNATIVE_ARCHITECTURE_TYPE` | enum | `payloads/Demon/include/common/Native.h:10642` | `` |
| `_ASSEMBLY_STORAGE_MAP` | struct | `payloads/Demon/include/common/Native.h:6480` | `` |
| `_ASSEMBLY_STORAGE_MAP_ENTRY` | struct | `payloads/Demon/include/common/Native.h:6473` | `` |
| `_ATOM_BASIC_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3386` | `` |
| `_ATOM_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3380` | `` |
| `_ATOM_TABLE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3394` | `` |
| `_BASESRV_API_CONNECTINFO` | struct | `payloads/Demon/include/common/Native.h:6023` | `` |
| `_BASESRV_API_NUMBER` | enum | `payloads/Demon/include/common/Native.h:6034` | `` |
| `_BASE_API_MSG` | struct | `payloads/Demon/include/common/Native.h:6376` | `` |
| `_BASE_BAT_NOTIFICATION_MSG` | struct | `payloads/Demon/include/common/Native.h:6298` | `` |
| `_BASE_CHECKVDM_MSG` | struct | `payloads/Demon/include/common/Native.h:6148` | `` |
| `_BASE_CREATEPROCESS_MSG` | struct | `payloads/Demon/include/common/Native.h:6245` | `` |
| `_BASE_CREATETHREAD_MSG` | struct | `payloads/Demon/include/common/Native.h:6261` | `` |
| `_BASE_DEBUGPROCESS_MSG` | struct | `payloads/Demon/include/common/Native.h:6141` | `` |
| `_BASE_DEFERREDCREATEPROCESS_MSG` | struct | `payloads/Demon/include/common/Native.h:6188` | `` |
| `_BASE_DEFINEDOSDEVICE_MSG` | struct | `payloads/Demon/include/common/Native.h:6338` | `` |
| `_BASE_EXITPROCESS_MSG` | struct | `payloads/Demon/include/common/Native.h:6194` | `` |
| `_BASE_EXIT_VDM_MSG` | struct | `payloads/Demon/include/common/Native.h:6277` | `` |
| `_BASE_GETTEMPFILE_MSG` | struct | `payloads/Demon/include/common/Native.h:6136` | `` |
| `_BASE_GET_NEXT_VDM_COMMAND_MSG` | struct | `payloads/Demon/include/common/Native.h:6097` | `` |
| `_BASE_GET_SET_VDM_CUR_DIRS_MSG` | struct | `payloads/Demon/include/common/Native.h:6198` | `` |
| `_BASE_GET_VDM_EXIT_CODE_MSG` | struct | `payloads/Demon/include/common/Native.h:6181` | `` |
| `_BASE_IS_FIRST_VDM_MSG` | struct | `payloads/Demon/include/common/Native.h:6285` | `` |
| `_BASE_MSG_SXS_HANDLES` | struct | `payloads/Demon/include/common/Native.h:6268` | `` |
| `_BASE_MSG_SXS_STREAM` | struct | `payloads/Demon/include/common/Native.h:6345` | `` |
| `_BASE_NLS_GET_USER_INFO_MSG` | struct | `payloads/Demon/include/common/Native.h:6075` | `` |
| `_BASE_NLS_SET_USER_INFO_MSG` | struct | `payloads/Demon/include/common/Native.h:6068` | `` |
| `_BASE_NLS_UPDATE_CACHE_COUNT_MSG` | struct | `payloads/Demon/include/common/Native.h:6081` | `` |
| `_BASE_REFRESHINIFILEMAPPING_MSG` | struct | `payloads/Demon/include/common/Native.h:6312` | `` |
| `_BASE_REGISTER_WOWEXEC_MSG` | struct | `payloads/Demon/include/common/Native.h:6305` | `` |
| `_BASE_SET_REENTER_COUNT` | struct | `payloads/Demon/include/common/Native.h:6205` | `` |
| `_BASE_SET_REENTER_COUNT_MSG` | struct | `payloads/Demon/include/common/Native.h:6291` | `` |
| `_BASE_SET_TERMSRVAPPINSTALLMODE` | struct | `payloads/Demon/include/common/Native.h:6326` | `` |
| `_BASE_SET_TERMSRVCLIENTTIMEZONE` | struct | `payloads/Demon/include/common/Native.h:6318` | `` |
| `_BASE_SHUTDOWNPARAM_MSG` | struct | `payloads/Demon/include/common/Native.h:6130` | `` |
| `_BASE_SOUNDSENTRY_NOTIFICATION_MSG` | struct | `payloads/Demon/include/common/Native.h:6332` | `` |
| `_BASE_STATIC_SERVER_DATA` | struct | `payloads/Demon/include/common/Native.h:6414` | `` |
| `_BASE_SXS_CREATEPROCESS_MSG` | struct | `payloads/Demon/include/common/Native.h:6232` | `` |
| `_BASE_SXS_CREATE_ACTIVATION_CONTEXT_MSG` | struct | `payloads/Demon/include/common/Native.h:6358` | `` |
| `_BASE_UPDATE_VDM_ENTRY_MSG` | struct | `payloads/Demon/include/common/Native.h:6086` | `` |
| `_BOOT_AREA_INFO` | struct | `payloads/Demon/include/common/Native.h:2197` | `` |
| `_BOOT_ENTRY` | struct | `payloads/Demon/include/common/Native.h:7582` | `` |
| `_BOOT_OPTIONS` | struct | `payloads/Demon/include/common/Native.h:7595` | `` |
| `_BUS_DATA_TYPE` | enum | `payloads/Demon/include/common/Native.h:2551` | `` |
| `_CACHE_DESCRIPTOR` | struct | `payloads/Demon/include/common/Native.h:4716` | `` |
| `_CHANNEL_MESSAGE` | struct | `payloads/Demon/include/common/Native.h:11540` | `` |
| `_CLIENT_ID` | struct | `payloads/Demon/include/common/Native.h:3920` | `` |
| `_CLIENT_ID32` | struct | `payloads/Demon/include/common/Native.h:3926` | `` |
| `_CLIENT_ID64` | struct | `payloads/Demon/include/common/Native.h:3932` | `` |
| `_COMPRESSED_DATA_INFO` | struct | `payloads/Demon/include/common/Native.h:10110` | `` |
| `_CONTEXT` | struct | `payloads/Demon/include/common/Native.h:7279` | `` |
| `_CONTEXT` | struct | `payloads/Demon/include/common/Native.h:7363` | `` |
| `_CPTABLEINFO` | struct | `payloads/Demon/include/common/Native.h:3688` | `` |
| `_CSR_API_CONNECTINFO` | struct | `payloads/Demon/include/common/Native.h:5906` | `` |
| `_CSR_API_MSG` | struct | `payloads/Demon/include/common/Native.h:5973` | `` |
| `_CSR_CALLBACK_INFO` | struct | `payloads/Demon/include/common/Native.h:5999` | `` |
| `_CSR_CAPTURE_HEADER` | struct | `payloads/Demon/include/common/Native.h:5934` | `` |
| `_CSR_CLIENTCONNECT_MSG` | struct | `payloads/Demon/include/common/Native.h:5922` | `` |
| `_CSR_NT_SESSION` | struct | `payloads/Demon/include/common/Native.h:5965` | `` |
| `_CSTRING` | struct | `payloads/Demon/include/common/Native.h:382` | `` |
| `_CSV_NAMESPACE_INFO` | struct | `payloads/Demon/include/common/Native.h:888` | `` |
| `_CURDIR` | struct | `payloads/Demon/include/common/Native.h:5333` | `` |
| `_CURDIR32` | struct | `payloads/Demon/include/common/Native.h:5489` | `` |
| `_DBGKM_CREATE_PROCESS` | struct | `payloads/Demon/include/common/Native.h:10989` | `` |
| `_DBGKM_CREATE_THREAD` | struct | `payloads/Demon/include/common/Native.h:10983` | `` |
| `_DBGKM_EXCEPTION` | struct | `payloads/Demon/include/common/Native.h:10977` | `` |
| `_DBGKM_EXIT_PROCESS` | struct | `payloads/Demon/include/common/Native.h:11004` | `` |
| `_DBGKM_EXIT_THREAD` | struct | `payloads/Demon/include/common/Native.h:10999` | `` |
| `_DBGKM_LOAD_DLL` | struct | `payloads/Demon/include/common/Native.h:11009` | `` |
| `_DBGKM_UNLOAD_DLL` | struct | `payloads/Demon/include/common/Native.h:11018` | `` |
| `_DBGUI_CREATE_PROCESS` | struct | `payloads/Demon/include/common/Native.h:11044` | `` |
| `_DBGUI_CREATE_THREAD` | struct | `payloads/Demon/include/common/Native.h:11038` | `` |
| `_DBGUI_WAIT_STATE_CHANGE` | struct | `payloads/Demon/include/common/Native.h:11051` | `` |
| `_DBG_STATE` | enum | `payloads/Demon/include/common/Native.h:11023` | `` |
| `_DEBUGOBJECTINFOCLASS` | enum | `payloads/Demon/include/common/Native.h:11077` | `` |
| `_DECRYPTION_STATUS_BUFFER` | struct | `payloads/Demon/include/common/Native.h:1456` | `` |
| `_DISPATCHER_HEADER` | struct | `payloads/Demon/include/common/Native.h:10347` | `` |
| `_EFI_DRIVER_ENTRY` | struct | `payloads/Demon/include/common/Native.h:9854` | `` |
| `_EFI_DRIVER_ENTRY_LIST` | struct | `payloads/Demon/include/common/Native.h:9864` | `` |
| `_ENCRYPTED_DATA_INFO` | struct | `payloads/Demon/include/common/Native.h:1473` | `` |
| `_ENCRYPTION_BUFFER` | struct | `payloads/Demon/include/common/Native.h:1442` | `` |
| `_ERESOURCE` | struct | `payloads/Demon/include/common/Native.h:10403` | `` |
| `_EVENT_DATA_DESCRIPTOR` | struct | `payloads/Demon/include/common/Native.h:11505` | `` |
| `_EVENT_DESCRIPTOR` | struct | `payloads/Demon/include/common/Native.h:11512` | `` |
| `_EVENT_FILTER_DESCRIPTOR` | struct | `payloads/Demon/include/common/Native.h:11528` | `` |
| `_EVENT_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3729` | `` |
| `_EVENT_TRACE_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:2704` | `` |
| `_EVENT_TYPE` | enum | `payloads/Demon/include/common/Native.h:6449` | `` |
| `_EXCEPTION_POINTERS` | struct | `payloads/Demon/include/common/Native.h:7489` | `` |
| `_EXCEPTION_RECORD` | struct | `payloads/Demon/include/common/Native.h:7280` | `` |
| `_EXCEPTION_RECORD` | struct | `payloads/Demon/include/common/Native.h:7450` | `` |
| `_EXCEPTION_RECORD32` | struct | `payloads/Demon/include/common/Native.h:7466` | `` |
| `_EXCEPTION_RECORD64` | struct | `payloads/Demon/include/common/Native.h:7475` | `` |
| `_EXCEPTION_REGISTRATION_RECORD` | struct | `payloads/Demon/include/common/Native.h:7293` | `` |
| `_EXFAT_STATISTICS` | struct | `payloads/Demon/include/common/Native.h:1268` | `` |
| `_EXTENDED_ENCRYPTED_DATA_INFO` | struct | `payloads/Demon/include/common/Native.h:2405` | `` |
| `_FAT_STATISTICS` | struct | `payloads/Demon/include/common/Native.h:1254` | `` |
| `_FILESYSTEMFSCTL_` | macro | `payloads/Demon/include/common/Native.h:712` | `#define _FILESYSTEMFSCTL_` |
| `_FILESYSTEM_STATISTICS` | struct | `payloads/Demon/include/common/Native.h:1227` | `` |
| `_FILE_ACCESS_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3979` | `` |
| `_FILE_ALIGNMENT_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3991` | `` |
| `_FILE_ALLOCATED_RANGE_BUFFER` | struct | `payloads/Demon/include/common/Native.h:1431` | `` |
| `_FILE_ALLOCATION_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4027` | `` |
| `_FILE_ALL_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4000` | `` |
| `_FILE_ATTRIBUTE_TAG_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4022` | `` |
| `_FILE_BASIC_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3954` | `` |
| `_FILE_BOTH_DIR_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4233` | `` |
| `_FILE_COMPLETION_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4087` | `` |
| `_FILE_COMPRESSION_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4031` | `` |
| `_FILE_DIRECTORY_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4188` | `` |
| `_FILE_DISPOSITION_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4040` | `` |
| `_FILE_EA_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3975` | `` |
| `_FILE_END_OF_FILE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4044` | `` |
| `_FILE_FS_PERSISTENT_VOLUME_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:2211` | `` |
| `_FILE_FULL_DIR_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4202` | `` |
| `_FILE_FULL_EA_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4140` | `` |
| `_FILE_GET_EA_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4150` | `` |
| `_FILE_GET_QUOTA_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4160` | `` |
| `_FILE_ID_BOTH_DIR_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4250` | `` |
| `_FILE_ID_FULL_DIR_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4217` | `` |
| `_FILE_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:2950` | `` |
| `_FILE_INTERNAL_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3971` | `` |
| `_FILE_LINK_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4052` | `` |
| `_FILE_MAILSLOT_QUERY_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4115` | `` |
| `_FILE_MAILSLOT_SET_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4123` | `` |
| `_FILE_MAKE_COMPATIBLE_BUFFER` | struct | `payloads/Demon/include/common/Native.h:1527` | `` |
| `_FILE_MODE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3987` | `` |
| `_FILE_MOVE_CLUSTER_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4059` | `` |
| `_FILE_NAMES_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4268` | `` |
| `_FILE_NAME_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3995` | `` |
| `_FILE_NETWORK_OPEN_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4012` | `` |
| `_FILE_OBJECTID_BUFFER` | struct | `payloads/Demon/include/common/Native.h:1384` | `` |
| `_FILE_OBJECTID_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4275` | `` |
| `_FILE_PATH` | struct | `payloads/Demon/include/common/Native.h:7552` | `` |
| `_FILE_PIPE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4092` | `` |
| `_FILE_PIPE_LOCAL_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4097` | `` |
| `_FILE_PIPE_REMOTE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4110` | `` |
| `_FILE_POSITION_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3983` | `` |
| `_FILE_PREFETCH` | struct | `payloads/Demon/include/common/Native.h:1205` | `` |
| `_FILE_PREFETCH_EX` | struct | `payloads/Demon/include/common/Native.h:1211` | `` |
| `_FILE_QUERY_ON_DISK_VOL_INFO_BUFFER` | struct | `payloads/Demon/include/common/Native.h:1545` | `` |
| `_FILE_QUERY_SPARING_BUFFER` | struct | `payloads/Demon/include/common/Native.h:1537` | `` |
| `_FILE_QUOTA_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4166` | `` |
| `_FILE_RENAME_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4066` | `` |
| `_FILE_REPARSE_POINT_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4127` | `` |
| `_FILE_SET_DEFECT_MGMT_BUFFER` | struct | `payloads/Demon/include/common/Native.h:1532` | `` |
| `_FILE_SET_SPARSE_BUFFER` | struct | `payloads/Demon/include/common/Native.h:1410` | `` |
| `_FILE_STANDARD_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3962` | `` |
| `_FILE_STREAM_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4073` | `` |
| `_FILE_SYSTEM_RECOGNITION_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:2220` | `` |
| `_FILE_TRACKING_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4081` | `` |
| `_FILE_TYPE_NOTIFICATION_INPUT` | struct | `payloads/Demon/include/common/Native.h:2445` | `` |
| `_FILE_VALID_DATA_LENGTH_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4048` | `` |
| `_FILE_ZERO_DATA_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:1421` | `` |
| `_FLS_CALLBACK_INFO` | struct | `payloads/Demon/include/common/Native.h:6712` | `` |
| `_FSCTL_QUERY_FAT_BPB_BUFFER` | struct | `payloads/Demon/include/common/Native.h:909` | `` |
| `_FSINFOCLASS` | enum | `payloads/Demon/include/common/Native.h:3005` | `` |
| `_GDI_HANDLE_ENTRY` | struct | `payloads/Demon/include/common/Native.h:5298` | `` |
| `_GDI_SHARED_MEMORY` | struct | `payloads/Demon/include/common/Native.h:5321` | `` |
| `_GDI_TEB_BATCH` | struct | `payloads/Demon/include/common/Native.h:6442` | `` |
| `_GDI_TEB_BATCH32` | struct | `payloads/Demon/include/common/Native.h:5644` | `` |
| `_GENERATE_NAME_CONTEXT` | struct | `payloads/Demon/include/common/Native.h:10052` | `` |
| `_HAL_QUERY_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3103` | `` |
| `_HARDERROR_RESPONSE` | enum | `payloads/Demon/include/common/Native.h:10627` | `` |
| `_HARDERROR_RESPONSE_OPTION` | enum | `payloads/Demon/include/common/Native.h:10614` | `` |
| `_HEAP` | struct | `payloads/Demon/include/common/Native.h:10518` | `` |
| `_HEAP_COUNTERS` | struct | `payloads/Demon/include/common/Native.h:10496` | `` |
| `_HEAP_DEBUGGING_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:11163` | `` |
| `_HEAP_ENTRY` | struct | `payloads/Demon/include/common/Native.h:10473` | `` |
| `_HEAP_ENTRY_EXTRA` | struct | `payloads/Demon/include/common/Native.h:10581` | `` |
| `_HEAP_FREE_ENTRY_EXTRA` | struct | `payloads/Demon/include/common/Native.h:10575` | `` |
| `_HEAP_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:10695` | `` |
| `_HEAP_LOCK` | struct | `payloads/Demon/include/common/Native.h:10441` | `` |
| `_HEAP_PSEUDO_TAG_ENTRY` | struct | `payloads/Demon/include/common/Native.h:10456` | `` |
| `_HEAP_TAG_ENTRY` | struct | `payloads/Demon/include/common/Native.h:10463` | `` |
| `_HEAP_TUNING_PARAMETERS` | struct | `payloads/Demon/include/common/Native.h:10450` | `` |
| `_HEAP_VIRTUAL_ALLOC_ENTRY` | struct | `payloads/Demon/include/common/Native.h:10589` | `` |
| `_HOTPATCH_HEADER` | struct | `payloads/Demon/include/common/Native.h:11553` | `` |
| `_HOTPATCH_HOOK` | struct | `payloads/Demon/include/common/Native.h:11585` | `` |
| `_HOTPATCH_HOOK_DESCRIPTOR` | struct | `payloads/Demon/include/common/Native.h:5094` | `` |
| `_HOTPATCH_MODULE_DATA` | struct | `payloads/Demon/include/common/Native.h:11572` | `` |
| `_HOTPATCH_MODULE_ENTRY` | struct | `payloads/Demon/include/common/Native.h:11579` | `` |
| `_INIFILE_MAPPING` | struct | `payloads/Demon/include/common/Native.h:5832` | `` |
| `_INIFILE_MAPPING_APPNAME` | struct | `payloads/Demon/include/common/Native.h:5816` | `` |
| `_INIFILE_MAPPING_FILENAME` | struct | `payloads/Demon/include/common/Native.h:5824` | `` |
| `_INIFILE_MAPPING_TARGET` | struct | `payloads/Demon/include/common/Native.h:5802` | `` |
| `_INIFILE_MAPPING_VARNAME` | struct | `payloads/Demon/include/common/Native.h:5808` | `` |
| `_INITIAL_TEB` | struct | `payloads/Demon/include/common/Native.h:6533` | `` |
| `_INTERFACE_TYPE` | enum | `payloads/Demon/include/common/Native.h:2530` | `` |
| `_IO_COMPLETION_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3298` | `` |
| `_IO_COUNTERS` | struct | `payloads/Demon/include/common/Native.h:10940` | `` |
| `_IO_STATUS_BLOCK` | struct | `payloads/Demon/include/common/Native.h:3178` | `` |
| `_JOB_SET_ARRAY` | struct | `payloads/Demon/include/common/Native.h:11353` | `` |
| `_KERNEL_USER_TIMES` | struct | `payloads/Demon/include/common/Native.h:5154` | `` |
| `_KEVENT` | struct | `payloads/Demon/include/common/Native.h:10380` | `` |
| `_KEY_BASIC_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3779` | `` |
| `_KEY_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3769` | `` |
| `_KEY_SET_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3840` | `` |
| `_KEY_VALUE_BASIC_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3799` | `` |
| `_KEY_VALUE_ENTRY` | struct | `payloads/Demon/include/common/Native.h:3829` | `` |
| `_KEY_VALUE_FULL_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3806` | `` |
| `_KEY_VALUE_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3786` | `` |
| `_KEY_VALUE_PARTIAL_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3816` | `` |
| `_KEY_VALUE_PARTIAL_INFORMATION_ALIGN64` | struct | `payloads/Demon/include/common/Native.h:3823` | `` |
| `_KGATE` | struct | `payloads/Demon/include/common/Native.h:10385` | `` |
| `_KLDR_DATA_TABLE_ENTRY` | struct | `payloads/Demon/include/common/Native.h:10312` | `` |
| `_KPROFILE_SOURCE` | enum | `payloads/Demon/include/common/Native.h:2745` | `` |
| `_KSEMAPHORE` | struct | `payloads/Demon/include/common/Native.h:10390` | `` |
| `_KSPIN_LOCK_QUEUE_NUMBER` | enum | `payloads/Demon/include/common/Native.h:2723` | `` |
| `_KSYSTEM_TIME` | struct | `payloads/Demon/include/common/Native.h:3940` | `` |
| `_KUSER_SHARED_DATA` | struct | `payloads/Demon/include/common/Native.h:10702` | `` |
| `_KWAIT_REASON` | enum | `payloads/Demon/include/common/Native.h:4327` | `` |
| `_LDR_DATA_TABLE_ENTRY` | struct | `payloads/Demon/include/common/Native.h:6671` | `` |
| `_LDR_DATA_TABLE_ENTRY32` | struct | `payloads/Demon/include/common/Native.h:5452` | `` |
| `_LDR_DLL_LOADED_NOTIFICATION_DATA` | struct | `payloads/Demon/include/common/Native.h:6598` | `` |
| `_LDR_DLL_NOTIFICATION_DATA` | union | `payloads/Demon/include/common/Native.h:6616` | `` |
| `_LDR_DLL_UNLOADED_NOTIFICATION_DATA` | struct | `payloads/Demon/include/common/Native.h:6607` | `` |
| `_LIST_ENTRY` | struct | `payloads/Demon/include/common/Native.h:444` | `` |
| `_LOGICAL_PROCESSOR_RELATIONSHIP` | enum | `payloads/Demon/include/common/Native.h:4698` | `` |
| `_LOOKUP_STREAM_FROM_CLUSTER_ENTRY` | struct | `payloads/Demon/include/common/Native.h:2437` | `` |
| `_LOOKUP_STREAM_FROM_CLUSTER_INPUT` | struct | `payloads/Demon/include/common/Native.h:2415` | `` |
| `_LOOKUP_STREAM_FROM_CLUSTER_OUTPUT` | struct | `payloads/Demon/include/common/Native.h:2421` | `` |
| `_LSALOOKUP_` | macro | `payloads/Demon/include/common/Native.h:8503` | `#define _LSALOOKUP_` |
| `_LSA_AUTH_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:9269` | `` |
| `_LSA_ENUMERATION_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:9465` | `` |
| `_LSA_FOREST_TRUST_BINARY_DATA` | struct | `payloads/Demon/include/common/Native.h:9368` | `` |
| `_LSA_FOREST_TRUST_COLLISION_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:9444` | `` |
| `_LSA_FOREST_TRUST_COLLISION_RECORD` | struct | `payloads/Demon/include/common/Native.h:9435` | `` |
| `_LSA_FOREST_TRUST_DOMAIN_INFO` | struct | `payloads/Demon/include/common/Native.h:9346` | `` |
| `_LSA_FOREST_TRUST_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:9415` | `` |
| `_LSA_FOREST_TRUST_RECORD` | struct | `payloads/Demon/include/common/Native.h:9380` | `` |
| `_LSA_LAST_INTER_LOGON_INFO` | struct | `payloads/Demon/include/common/Native.h:9493` | `` |
| `_LSA_LOOKUP_DOMAIN_INFO_CLASS` | enum | `payloads/Demon/include/common/Native.h:8581` | `` |
| `_LSA_OBJECT_ATTRIBUTES` | struct | `payloads/Demon/include/common/Native.h:8528` | `` |
| `_LSA_REFERENCED_DOMAIN_LIST` | struct | `payloads/Demon/include/common/Native.h:8544` | `` |
| `_LSA_STRING` | struct | `payloads/Demon/include/common/Native.h:8522` | `` |
| `_LSA_TRANSLATED_NAME` | struct | `payloads/Demon/include/common/Native.h:8558` | `` |
| `_LSA_TRANSLATED_SID` | struct | `payloads/Demon/include/common/Native.h:8914` | `` |
| `_LSA_TRANSLATED_SID2` | struct | `payloads/Demon/include/common/Native.h:8550` | `` |
| `_LSA_TRUST_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:8539` | `` |
| `_LSA_UNICODE_STRING` | struct | `payloads/Demon/include/common/Native.h:8513` | `` |
| `_MEMORY_BASIC_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4796` | `` |
| `_MEMORY_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3037` | `` |
| `_MEMORY_RANGE_ENTRY` | struct | `payloads/Demon/include/common/Native.h:11227` | `` |
| `_MEMORY_REGION_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3348` | `` |
| `_MEMORY_WORKING_SET_BLOCK` | struct | `payloads/Demon/include/common/Native.h:3312` | `` |
| `_MEMORY_WORKING_SET_EX_BLOCK` | struct | `payloads/Demon/include/common/Native.h:3331` | `` |
| `_MEMORY_WORKING_SET_EX_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3356` | `` |
| `_MEMORY_WORKING_SET_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3325` | `` |
| `_MOVE_FILE_DATA32` | struct | `payloads/Demon/include/common/Native.h:1022` | `` |
| `_MUTANT_BASIC_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3423` | `` |
| `_MUTANT_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3419` | `` |
| `_NLSTABLEINFO` | struct | `payloads/Demon/include/common/Native.h:3703` | `` |
| `_NLS_USER_INFO` | struct | `payloads/Demon/include/common/Native.h:5760` | `` |
| `_NTDLL_` | macro | `payloads/Demon/include/common/Native.h:21` | `#define _NTDLL_` |
| `_NTFS_STATISTICS` | struct | `payloads/Demon/include/common/Native.h:1282` | `` |
| `_NTLSA_AUDIT_` | macro | `payloads/Demon/include/common/Native.h:8665` | `#define _NTLSA_AUDIT_` |
| `_NTLSA_IFS_` | macro | `payloads/Demon/include/common/Native.h:8500` | `#define _NTLSA_IFS_` |
| `_NT_PRODUCT_TYPE` | enum | `payloads/Demon/include/common/Native.h:7311` | `` |
| `_NT_TIB32` | struct | `payloads/Demon/include/common/Native.h:5655` | `` |
| `_NT_TIB64` | struct | `payloads/Demon/include/common/Native.h:5668` | `` |
| `_OBJECT_ATTRIBUTES` | struct | `payloads/Demon/include/common/Native.h:505` | `` |
| `_OBJECT_BASIC_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3473` | `` |
| `_OBJECT_DIRECTORY_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:527` | `` |
| `_OBJECT_HANDLE_FLAG_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3522` | `` |
| `_OBJECT_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3463` | `` |
| `_OBJECT_NAME_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3487` | `` |
| `_OBJECT_TYPES_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3516` | `` |
| `_OBJECT_TYPE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3491` | `` |
| `_OWNER_ENTRY` | struct | `payloads/Demon/include/common/Native.h:10396` | `` |
| `_PARSE_MESSAGE_CONTEXT` | struct | `payloads/Demon/include/common/Native.h:3654` | `` |
| `_PATHNAME_BUFFER` | struct | `payloads/Demon/include/common/Native.h:902` | `` |
| `_PEB` | struct | `payloads/Demon/include/common/Native.h:6757` | `` |
| `_PEB32` | struct | `payloads/Demon/include/common/Native.h:5543` | `` |
| `_PEB_FREE_BLOCK` | struct | `payloads/Demon/include/common/Native.h:6515` | `` |
| `_PEB_LDR_DATA` | struct | `payloads/Demon/include/common/Native.h:6520` | `` |
| `_PEB_LDR_DATA32` | struct | `payloads/Demon/include/common/Native.h:5437` | `` |
| `_PLEX_READ_DATA_REQUEST` | struct | `payloads/Demon/include/common/Native.h:1502` | `` |
| `_PLUGPLAY_CONTROL_CLASS` | enum | `payloads/Demon/include/common/Native.h:3734` | `` |
| `_PLUGPLAY_EVENT_BLOCK` | struct | `payloads/Demon/include/common/Native.h:3558` | `` |
| `_PLUGPLAY_EVENT_CATEGORY` | enum | `payloads/Demon/include/common/Native.h:3528` | `` |
| `_PNP_VETO_TYPE` | enum | `payloads/Demon/include/common/Native.h:3542` | `` |
| `_POLICY_ACCOUNT_DOMAIN_INFO` | struct | `payloads/Demon/include/common/Native.h:8564` | `` |
| `_POLICY_AUDIT_CATEGORIES_INFO` | struct | `payloads/Demon/include/common/Native.h:8987` | `` |
| `_POLICY_AUDIT_EVENTS_INFO` | struct | `payloads/Demon/include/common/Native.h:8972` | `` |
| `_POLICY_AUDIT_EVENT_TYPE` | enum | `payloads/Demon/include/common/Native.h:8769` | `` |
| `_POLICY_AUDIT_FULL_QUERY_INFO` | struct | `payloads/Demon/include/common/Native.h:9060` | `` |
| `_POLICY_AUDIT_FULL_SET_INFO` | struct | `payloads/Demon/include/common/Native.h:9053` | `` |
| `_POLICY_AUDIT_LOG_INFO` | struct | `payloads/Demon/include/common/Native.h:8961` | `` |
| `_POLICY_AUDIT_SUBCATEGORIES_INFO` | struct | `payloads/Demon/include/common/Native.h:8980` | `` |
| `_POLICY_DEFAULT_QUOTA_INFO` | struct | `payloads/Demon/include/common/Native.h:9038` | `` |
| `_POLICY_DNS_DOMAIN_INFO` | struct | `payloads/Demon/include/common/Native.h:8569` | `` |
| `_POLICY_DOMAIN_EFS_INFO` | struct | `payloads/Demon/include/common/Native.h:9103` | `` |
| `_POLICY_DOMAIN_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:9068` | `` |
| `_POLICY_DOMAIN_KERBEROS_TICKET_INFO` | struct | `payloads/Demon/include/common/Native.h:9112` | `` |
| `_POLICY_DOMAIN_QUALITY_OF_SERVICE_INFO` | struct | `payloads/Demon/include/common/Native.h:9095` | `` |
| `_POLICY_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:8941` | `` |
| `_POLICY_LSA_SERVER_ROLE` | enum | `payloads/Demon/include/common/Native.h:8922` | `` |
| `_POLICY_LSA_SERVER_ROLE_INFO` | struct | `payloads/Demon/include/common/Native.h:9025` | `` |
| `_POLICY_MODIFICATION_INFO` | struct | `payloads/Demon/include/common/Native.h:9045` | `` |
| `_POLICY_NOTIFICATION_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:9122` | `` |
| `_POLICY_PD_ACCOUNT_INFO` | struct | `payloads/Demon/include/common/Native.h:9019` | `` |
| `_POLICY_PRIMARY_DOMAIN_INFO` | struct | `payloads/Demon/include/common/Native.h:9012` | `` |
| `_POLICY_REPLICA_SOURCE_INFO` | struct | `payloads/Demon/include/common/Native.h:9031` | `` |
| `_POLICY_SERVER_ENABLE_STATE` | enum | `payloads/Demon/include/common/Native.h:8931` | `` |
| `_POOL_TYPE` | enum | `payloads/Demon/include/common/Native.h:3019` | `` |
| `_PORT_DATA_ENTRY` | struct | `payloads/Demon/include/common/Native.h:5882` | `` |
| `_PORT_DATA_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:5887` | `` |
| `_PORT_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3302` | `` |
| `_PORT_MESSAGE` | struct | `payloads/Demon/include/common/Native.h:5844` | `` |
| `_PORT_VIEW` | struct | `payloads/Demon/include/common/Native.h:3279` | `` |
| `_PREFIX_TABLE` | struct | `payloads/Demon/include/common/Native.h:10077` | `` |
| `_PREFIX_TABLE_ENTRY` | struct | `payloads/Demon/include/common/Native.h:10068` | `` |
| `_PROCESSINFOCLASS` | enum | `payloads/Demon/include/common/Native.h:2773` | `` |
| `_PROCESSOR_CACHE_TYPE` | enum | `payloads/Demon/include/common/Native.h:4706` | `` |
| `_PROCESSOR_NUMBER` | struct | `payloads/Demon/include/common/Native.h:534` | `` |
| `_PROCESS_BASIC_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:7154` | `` |
| `_PROCESS_DEVICEMAP_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:7128` | `` |
| `_PROCESS_DEVICEMAP_INFORMATION_EX` | struct | `payloads/Demon/include/common/Native.h:7140` | `` |
| `_PROCESS_EXTENDED_BASIC_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:7165` | `` |
| `_PROCESS_FOREGROUND_BACKGROUND` | struct | `payloads/Demon/include/common/Native.h:7548` | `` |
| `_PROCESS_PRIORITY_CLASS` | struct | `payloads/Demon/include/common/Native.h:7543` | `` |
| `_PROCESS_TLS_INFORMATION_TYPE` | enum | `payloads/Demon/include/common/Native.h:2868` | `` |
| `_RANGE_LIST_ITERATOR` | struct | `payloads/Demon/include/common/Native.h:10215` | `` |
| `_REG_NOTIFY_CLASS` | enum | `payloads/Demon/include/common/Native.h:3046` | `` |
| `_REMOTE_PORT_VIEW` | struct | `payloads/Demon/include/common/Native.h:3288` | `` |
| `_REQUEST_OPLOCK_INPUT_BUFFER` | struct | `payloads/Demon/include/common/Native.h:2236` | `` |
| `_REQUEST_OPLOCK_OUTPUT_BUFFER` | struct | `payloads/Demon/include/common/Native.h:2263` | `` |
| `_REQUEST_RAW_ENCRYPTED_DATA` | struct | `payloads/Demon/include/common/Native.h:1466` | `` |
| `_RETRIEVAL_POINTER_BASE` | struct | `payloads/Demon/include/common/Native.h:2206` | `` |
| `_RTL_ACTIVATION_CONTEXT_STACK_FRAME` | struct | `payloads/Demon/include/common/Native.h:6895` | `` |
| `_RTL_AVL_TABLE` | struct | `payloads/Demon/include/common/Native.h:9921` | `` |
| `_RTL_AVL_TABLE` | struct | `payloads/Demon/include/common/Native.h:9945` | `` |
| `_RTL_AVL_TABLE` | struct | `payloads/Demon/include/common/Native.h:10024` | `` |
| `_RTL_BALANCED_LINKS` | struct | `payloads/Demon/include/common/Native.h:10015` | `` |
| `_RTL_BITMAP` | struct | `payloads/Demon/include/common/Native.h:10185` | `` |
| `_RTL_BITMAP_RUN` | struct | `payloads/Demon/include/common/Native.h:3648` | `` |
| `_RTL_DEBUG_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:11256` | `` |
| `_RTL_DRIVE_LETTER_CURDIR` | struct | `payloads/Demon/include/common/Native.h:5342` | `` |
| `_RTL_DRIVE_LETTER_CURDIR32` | struct | `payloads/Demon/include/common/Native.h:5495` | `` |
| `_RTL_DYNAMIC_TIME_ZONE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:6013` | `` |
| `_RTL_GENERIC_COMPARE_RESULTS` | enum | `payloads/Demon/include/common/Native.h:9938` | `` |
| `_RTL_GENERIC_TABLE` | struct | `payloads/Demon/include/common/Native.h:10039` | `` |
| `_RTL_HANDLE_TABLE` | struct | `payloads/Demon/include/common/Native.h:11341` | `` |
| `_RTL_HANDLE_TABLE_ENTRY` | struct | `payloads/Demon/include/common/Native.h:11330` | `` |
| `_RTL_HEAP_ENTRY` | struct | `payloads/Demon/include/common/Native.h:7183` | `` |
| `_RTL_HEAP_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:7223` | `` |
| `_RTL_HEAP_PARAMETERS` | struct | `payloads/Demon/include/common/Native.h:9889` | `` |
| `_RTL_HEAP_TAG` | struct | `payloads/Demon/include/common/Native.h:7213` | `` |
| `_RTL_HEAP_TAG_INFO` | struct | `payloads/Demon/include/common/Native.h:11086` | `` |
| `_RTL_HEAP_USAGE` | struct | `payloads/Demon/include/common/Native.h:11110` | `` |
| `_RTL_HEAP_USAGE_ENTRY` | struct | `payloads/Demon/include/common/Native.h:11101` | `` |
| `_RTL_HEAP_WALK_ENTRY` | struct | `payloads/Demon/include/common/Native.h:11126` | `` |
| `_RTL_MEMORY_ZONE` | struct | `payloads/Demon/include/common/Native.h:11196` | `` |
| `_RTL_MEMORY_ZONE_SEGMENT` | struct | `payloads/Demon/include/common/Native.h:11182` | `` |
| `_RTL_PATCH_HEADER` | struct | `payloads/Demon/include/common/Native.h:11594` | `` |
| `_RTL_PATH_TYPE` | enum | `payloads/Demon/include/common/Native.h:6741` | `` |
| `_RTL_PROCESS_BACKTRACES` | struct | `payloads/Demon/include/common/Native.h:11248` | `` |
| `_RTL_PROCESS_BACKTRACE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:11240` | `` |
| `_RTL_PROCESS_HEAPS` | struct | `payloads/Demon/include/common/Native.h:7240` | `` |
| `_RTL_PROCESS_LOCKS` | struct | `payloads/Demon/include/common/Native.h:11233` | `` |
| `_RTL_PROCESS_LOCK_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:7246` | `` |
| `_RTL_PROCESS_MODULES` | struct | `payloads/Demon/include/common/Native.h:6642` | `` |
| `_RTL_PROCESS_MODULE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:6628` | `` |
| `_RTL_PROCESS_MODULE_INFORMATION_EX` | struct | `payloads/Demon/include/common/Native.h:6648` | `` |
| `_RTL_PROCESS_REFLECTION_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:10915` | `` |
| `_RTL_PROCESS_VERIFIER_OPTIONS` | struct | `payloads/Demon/include/common/Native.h:11204` | `` |
| `_RTL_QUERY_REGISTRY_TABLE` | struct | `payloads/Demon/include/common/Native.h:7506` | `` |
| `_RTL_RANGE` | struct | `payloads/Demon/include/common/Native.h:3713` | `` |
| `_RTL_RANGE_LIST` | struct | `payloads/Demon/include/common/Native.h:10198` | `` |
| `_RTL_RELATIVE_NAME` | struct | `payloads/Demon/include/common/Native.h:6726` | `` |
| `_RTL_RELATIVE_NAME_U` | struct | `payloads/Demon/include/common/Native.h:6734` | `` |
| `_RTL_RESOURCE` | struct | `payloads/Demon/include/common/Native.h:10271` | `` |
| `_RTL_RXACT_CONTEXT` | struct | `payloads/Demon/include/common/Native.h:3679` | `` |
| `_RTL_RXACT_LOG` | struct | `payloads/Demon/include/common/Native.h:3670` | `` |
| `_RTL_RXACT_OPERATION` | enum | `payloads/Demon/include/common/Native.h:3663` | `` |
| `_RTL_SPLAY_LINKS` | struct | `payloads/Demon/include/common/Native.h:9923` | `` |
| `_RTL_SRWLOCK` | struct | `payloads/Demon/include/common/Native.h:11191` | `` |
| `_RTL_STACK_CONTEXT` | struct | `payloads/Demon/include/common/Native.h:9877` | `` |
| `_RTL_STACK_CONTEXT_ENTRY` | struct | `payloads/Demon/include/common/Native.h:9872` | `` |
| `_RTL_TIME_ZONE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3638` | `` |
| `_RTL_TRACE_BLOCK` | struct | `payloads/Demon/include/common/Native.h:10290` | `` |
| `_RTL_TRACE_ENUMERATE` | struct | `payloads/Demon/include/common/Native.h:10306` | `` |
| `_RTL_UNLOAD_EVENT_TRACE` | struct | `payloads/Demon/include/common/Native.h:21429` | `` |
| `_RTL_UNLOAD_EVENT_TRACE32` | struct | `payloads/Demon/include/common/Native.h:21447` | `` |
| `_RTL_UNLOAD_EVENT_TRACE64` | struct | `payloads/Demon/include/common/Native.h:21438` | `` |
| `_RTL_USER_PROCESS_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:10250` | `` |
| `_RTL_USER_PROCESS_INFORMATION64` | struct | `payloads/Demon/include/common/Native.h:10258` | `` |
| `_RTL_USER_PROCESS_PARAMETERS` | struct | `payloads/Demon/include/common/Native.h:5353` | `` |
| `_RTL_USER_PROCESS_PARAMETERS32` | struct | `payloads/Demon/include/common/Native.h:5503` | `` |
| `_SD_CHANGE_MACHINE_SID_INPUT` | struct | `payloads/Demon/include/common/Native.h:2284` | `` |
| `_SD_CHANGE_MACHINE_SID_OUTPUT` | struct | `payloads/Demon/include/common/Native.h:2294` | `` |
| `_SD_GLOBAL_CHANGE_INPUT` | struct | `payloads/Demon/include/common/Native.h:2349` | `` |
| `_SD_GLOBAL_CHANGE_OUTPUT` | struct | `payloads/Demon/include/common/Native.h:2371` | `` |
| `_SECTION_IMAGE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:10124` | `` |
| `_SECTION_IMAGE_INFORMATION64` | struct | `payloads/Demon/include/common/Native.h:10161` | `` |
| `_SECTION_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3443` | `` |
| `_SECTION_INHERIT` | enum | `payloads/Demon/include/common/Native.h:3306` | `` |
| `_SECURITY_LOGON_SESSION_DATA` | struct | `payloads/Demon/include/common/Native.h:9502` | `` |
| `_SECURITY_LOGON_TYPE` | enum | `payloads/Demon/include/common/Native.h:8640` | `` |
| `_SEMAPHORE_BASIC_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3409` | `` |
| `_SEMAPHORE_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3405` | `` |
| `_SE_ADT_ACCESS_REASON` | struct | `payloads/Demon/include/common/Native.h:8732` | `` |
| `_SE_ADT_OBJECT_TYPE` | struct | `payloads/Demon/include/common/Native.h:8715` | `` |
| `_SE_ADT_PARAMETER_ARRAY` | struct | `payloads/Demon/include/common/Native.h:8743` | `` |
| `_SE_ADT_PARAMETER_ARRAY_ENTRY` | struct | `payloads/Demon/include/common/Native.h:8723` | `` |
| `_SE_ADT_PARAMETER_TYPE` | enum | `payloads/Demon/include/common/Native.h:8676` | `` |
| `_SHRINK_VOLUME_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:1575` | `` |
| `_SHRINK_VOLUME_REQUEST_TYPES` | enum | `payloads/Demon/include/common/Native.h:1567` | `` |
| `_SHUTDOWN_ACTION` | enum | `payloads/Demon/include/common/Native.h:3374` | `` |
| `_SI_COPYFILE` | struct | `payloads/Demon/include/common/Native.h:1513` | `` |
| `_SLIST_ENTRY` | macro | `payloads/Demon/include/common/Native.h:11640` | `#define _SLIST_ENTRY` |
| `_SLIST_HEADER` | union | `payloads/Demon/include/common/Native.h:11656` | `` |
| `_SLIST_HEADER_` | macro | `payloads/Demon/include/common/Native.h:11616` | `#define _SLIST_HEADER_` |
| `_STARTUP_ARGUMENT` | struct | `payloads/Demon/include/common/Native.h:10222` | `` |
| `_STRING` | struct | `payloads/Demon/include/common/Native.h:366` | `` |
| `_STRING32` | struct | `payloads/Demon/include/common/Native.h:402` | `` |
| `_STRING64` | struct | `payloads/Demon/include/common/Native.h:417` | `` |
| `_SUITE_TYPE` | enum | `payloads/Demon/include/common/Native.h:7319` | `` |
| `_SYSDBG_BUS_DATA` | struct | `payloads/Demon/include/common/Native.h:2569` | `` |
| `_SYSDBG_COMMAND` | enum | `payloads/Demon/include/common/Native.h:2467` | `` |
| `_SYSDBG_CONTROL_SPACE` | struct | `payloads/Demon/include/common/Native.h:2522` | `` |
| `_SYSDBG_IO_SPACE` | struct | `payloads/Demon/include/common/Native.h:2535` | `` |
| `_SYSDBG_MSR` | struct | `payloads/Demon/include/common/Native.h:2545` | `` |
| `_SYSDBG_PHYSICAL` | struct | `payloads/Demon/include/common/Native.h:2515` | `` |
| `_SYSDBG_TRIAGE_DUMP` | struct | `payloads/Demon/include/common/Native.h:2579` | `` |
| `_SYSDBG_VIRTUAL` | struct | `payloads/Demon/include/common/Native.h:2508` | `` |
| `_SYSTEM_BASIC_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4645` | `` |
| `_SYSTEM_BIGPOOL_ENTRY` | struct | `payloads/Demon/include/common/Native.h:4429` | `` |
| `_SYSTEM_BIGPOOL_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4454` | `` |
| `_SYSTEM_CALL_COUNT_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4975` | `` |
| `_SYSTEM_CALL_TIME_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4993` | `` |
| `_SYSTEM_CONTEXT_SWITCH_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4533` | `` |
| `_SYSTEM_DEVICE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4980` | `` |
| `_SYSTEM_DPC_BEHAVIOR_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4565` | `` |
| `_SYSTEM_EXCEPTION_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4303` | `` |
| `_SYSTEM_EXTENDED_THREAD_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4383` | `` |
| `_SYSTEM_FILECACHE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:5070` | `` |
| `_SYSTEM_FLAGS_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4989` | `` |
| `_SYSTEM_GDI_DRIVER_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4293` | `` |
| `_SYSTEM_HANDLE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4470` | `` |
| `_SYSTEM_HANDLE_INFORMATION_EX` | struct | `payloads/Demon/include/common/Native.h:4488` | `` |
| `_SYSTEM_HANDLE_TABLE_ENTRY_INFO` | struct | `payloads/Demon/include/common/Native.h:4459` | `` |
| `_SYSTEM_HANDLE_TABLE_ENTRY_INFO_EX` | struct | `payloads/Demon/include/common/Native.h:4476` | `` |
| `_SYSTEM_HIBERFILE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4516` | `` |
| `_SYSTEM_HOTPATCH_CODE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:5105` | `` |
| `_SYSTEM_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:2592` | `` |
| `_SYSTEM_INTERRUPT_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4556` | `` |
| `_SYSTEM_KERNEL_DEBUGGER_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4522` | `` |
| `_SYSTEM_LEGACY_DRIVER_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4585` | `` |
| `_SYSTEM_LOGICAL_PROCESSOR_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4725` | `` |
| `_SYSTEM_LOOKASIDE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4573` | `` |
| `_SYSTEM_MEMORY_INFO` | struct | `payloads/Demon/include/common/Native.h:4961` | `` |
| `_SYSTEM_MEMORY_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4969` | `` |
| `_SYSTEM_NUMA_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4687` | `` |
| `_SYSTEM_OBJECTTYPE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4501` | `` |
| `_SYSTEM_OBJECT_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4999` | `` |
| `_SYSTEM_PAGEFILE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:5014` | `` |
| `_SYSTEM_PERFORMANCE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4842` | `` |
| `_SYSTEM_POOLTAG` | struct | `payloads/Demon/include/common/Native.h:4416` | `` |
| `_SYSTEM_POOLTAG_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4441` | `` |
| `_SYSTEM_POOL_ENTRY` | struct | `payloads/Demon/include/common/Native.h:4394` | `` |
| `_SYSTEM_POOL_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4406` | `` |
| `_SYSTEM_PROCESSES_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:10953` | `` |
| `_SYSTEM_PROCESSOR_IDLE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4676` | `` |
| `_SYSTEM_PROCESSOR_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4659` | `` |
| `_SYSTEM_PROCESSOR_PERFORMANCE_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4667` | `` |
| `_SYSTEM_PROCESSOR_POWER_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4809` | `` |
| `_SYSTEM_PROCESS_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4919` | `` |
| `_SYSTEM_QUERY_TIME_ADJUST_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4831` | `` |
| `_SYSTEM_REGISTRY_QUOTA_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4527` | `` |
| `_SYSTEM_SESSION_MAPPED_VIEW_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4548` | `` |
| `_SYSTEM_SESSION_POOLTAG_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4447` | `` |
| `_SYSTEM_SESSION_PROCESS_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4955` | `` |
| `_SYSTEM_SET_TIME_ADJUST_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4837` | `` |
| `_SYSTEM_SPECIAL_POOL_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4495` | `` |
| `_SYSTEM_THREAD_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4369` | `` |
| `_SYSTEM_TIMEOFDAY_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:4628` | `` |
| `_SYSTEM_VDM_INSTEMUL_INFO` | struct | `payloads/Demon/include/common/Native.h:4590` | `` |
| `_SYSTEM_VERIFIER_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:5022` | `` |
| `_SYSTEM_VERIFIER_INFORMATION_EX` | struct | `payloads/Demon/include/common/Native.h:5057` | `` |
| `_SYSTEM_WATCHDOG_HANDLER_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:5194` | `` |
| `_SYSTEM_WATCHDOG_TIMER_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:5204` | `` |
| `_TABLE_SEARCH_RESULT` | enum | `payloads/Demon/include/common/Native.h:9930` | `` |
| `_TEB` | struct | `payloads/Demon/include/common/Native.h:6953` | `` |
| `_TEB32` | struct | `payloads/Demon/include/common/Native.h:5682` | `` |
| `_TEB_ACTIVE_FRAME` | struct | `payloads/Demon/include/common/Native.h:6935` | `` |
| `_TEB_ACTIVE_FRAME_CONTEXT` | struct | `payloads/Demon/include/common/Native.h:6916` | `` |
| `_TEB_ACTIVE_FRAME_CONTEXT_EX` | struct | `payloads/Demon/include/common/Native.h:6924` | `` |
| `_TEB_ACTIVE_FRAME_EX` | struct | `payloads/Demon/include/common/Native.h:6944` | `` |
| `_THREADINFOCLASS` | enum | `payloads/Demon/include/common/Native.h:2829` | `` |
| `_THREAD_BASIC_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:7112` | `` |
| `_THREAD_STATE` | enum | `payloads/Demon/include/common/Native.h:4315` | `` |
| `_TIB` | struct | `payloads/Demon/include/common/Native.h:5738` | `` |
| `_TIMER_BASIC_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:3438` | `` |
| `_TIMER_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:3434` | `` |
| `_TIMER_TYPE` | enum | `payloads/Demon/include/common/Native.h:6454` | `` |
| `_TIME_FIELDS` | struct | `payloads/Demon/include/common/Native.h:3626` | `` |
| `_TRIPLE_LIST_ENTRY` | struct | `payloads/Demon/include/common/Native.h:456` | `` |
| `_TRUSTED_CONTROLLERS_INFO` | struct | `payloads/Demon/include/common/Native.h:9161` | `` |
| `_TRUSTED_DOMAIN_AUTH_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:9277` | `` |
| `_TRUSTED_DOMAIN_FULL_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:9288` | `` |
| `_TRUSTED_DOMAIN_FULL_INFORMATION2` | struct | `payloads/Demon/include/common/Native.h:9296` | `` |
| `_TRUSTED_DOMAIN_INFORMATION_EX` | struct | `payloads/Demon/include/common/Native.h:9237` | `` |
| `_TRUSTED_DOMAIN_INFORMATION_EX2` | struct | `payloads/Demon/include/common/Native.h:9248` | `` |
| `_TRUSTED_DOMAIN_NAME_INFO` | struct | `payloads/Demon/include/common/Native.h:9155` | `` |
| `_TRUSTED_DOMAIN_SUPPORTED_ENCRYPTION_TYPES` | struct | `payloads/Demon/include/common/Native.h:9304` | `` |
| `_TRUSTED_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:9138` | `` |
| `_TRUSTED_PASSWORD_INFO` | struct | `payloads/Demon/include/common/Native.h:9174` | `` |
| `_TRUSTED_POSIX_OFFSET_INFO` | struct | `payloads/Demon/include/common/Native.h:9168` | `` |
| `_TXFS_CREATE_MINIVERSION_INFO` | struct | `payloads/Demon/include/common/Native.h:2179` | `` |
| `_TXFS_GET_METADATA_INFO_OUT` | struct | `payloads/Demon/include/common/Native.h:1930` | `` |
| `_TXFS_GET_TRANSACTED_VERSION` | struct | `payloads/Demon/include/common/Native.h:2111` | `` |
| `_TXFS_LIST_TRANSACTIONS` | struct | `payloads/Demon/include/common/Native.h:2058` | `` |
| `_TXFS_LIST_TRANSACTIONS_ENTRY` | struct | `payloads/Demon/include/common/Native.h:2035` | `` |
| `_TXFS_LIST_TRANSACTION_LOCKED_FILES` | struct | `payloads/Demon/include/common/Native.h:2002` | `` |
| `_TXFS_LIST_TRANSACTION_LOCKED_FILES_ENTRY` | struct | `payloads/Demon/include/common/Native.h:1964` | `` |
| `_TXFS_MODIFY_RM` | struct | `payloads/Demon/include/common/Native.h:1628` | `` |
| `_TXFS_QUERY_RM_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:1700` | `` |
| `_TXFS_READ_BACKUP_INFORMATION_OUT` | struct | `payloads/Demon/include/common/Native.h:2081` | `` |
| `_TXFS_ROLLFORWARD_REDO_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:1802` | `` |
| `_TXFS_SAVEPOINT_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:2172` | `` |
| `_TXFS_START_RM_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:1840` | `` |
| `_TXFS_TRANSACTION_ACTIVE_INFO` | struct | `payloads/Demon/include/common/Native.h:2188` | `` |
| `_TXFS_WRITE_BACKUP_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:2104` | `` |
| `_UNICODE_PREFIX_TABLE` | struct | `payloads/Demon/include/common/Native.h:10094` | `` |
| `_UNICODE_PREFIX_TABLE_ENTRY` | struct | `payloads/Demon/include/common/Native.h:10084` | `` |
| `_UNICODE_STRING` | struct | `payloads/Demon/include/common/Native.h:394` | `` |
| `_USER_PERMISSION` | struct | `payloads/Demon/include/common/Native.h:7617` | `` |
| `_USER_SID` | struct | `payloads/Demon/include/common/Native.h:7609` | `` |
| `_VIRTUAL_MEMORY_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:11211` | `` |
| `_VM_COUNTERS` | struct | `payloads/Demon/include/common/Native.h:10923` | `` |
| `_VM_INFORMATION` | struct | `payloads/Demon/include/common/Native.h:11218` | `` |
| `_WAIT_TYPE` | enum | `payloads/Demon/include/common/Native.h:6459` | `` |
| `_WATCHDOG_HANDLER_ACTION` | enum | `payloads/Demon/include/common/Native.h:5162` | `` |
| `_WATCHDOG_INFORMATION_CLASS` | enum | `payloads/Demon/include/common/Native.h:5176` | `` |
| `_WINDOWS_OS_OPTIONS` | struct | `payloads/Demon/include/common/Native.h:7569` | `` |
| `_WOW64_PROCESS` | struct | `payloads/Demon/include/common/Native.h:6547` | `` |
| `_WOW64_SHARED_INFORMATION` | enum | `payloads/Demon/include/common/Native.h:5398` | `` |
| `_X86_CONTEXT` | struct | `payloads/Demon/include/common/Native.h:3205` | `` |
| `_X86_FLOATING_SAVE_AREA` | struct | `payloads/Demon/include/common/Native.h:3192` | `` |
| `_XSTATE_CONFIGURATION` | struct | `payloads/Demon/include/common/Native.h:10679` | `` |
| `_XSTATE_FEATURE` | struct | `payloads/Demon/include/common/Native.h:10674` | `` |
| `___PROCESSOR_NUMBER_DEFINED` | macro | `payloads/Demon/include/common/Native.h:533` | `#define ___PROCESSOR_NUMBER_DEFINED` |
| `_wcsicmp` | function | `payloads/Demon/include/common/Native.h:22541` | `IMPORT_FN int __cdecl _wcsicmp(const wchar_t *, const wchar_t *);` |
| `_wcslwr` | function | `payloads/Demon/include/common/Native.h:22543` | `IMPORT_FN wchar_t * __cdecl _wcslwr(wchar_t *);` |
| `_wcsnicmp` | function | `payloads/Demon/include/common/Native.h:22542` | `IMPORT_FN int __cdecl _wcsnicmp(const wchar_t *, const wchar_t *, size_t);` |
| `_wcsupr` | function | `payloads/Demon/include/common/Native.h:22544` | `IMPORT_FN wchar_t * __cdecl _wcsupr(wchar_t *);` |
| `addrinfo` | struct | `payloads/Demon/include/common/Native.h:22497` | `` |
| `ai_flags` | type_alias | `payloads/Demon/include/common/Native.h:22497` | `typedef struct addrinfo { int ai_flags;` |
| `bState` | type_alias | `payloads/Demon/include/common/Native.h:6325` | `typedef struct _BASE_SET_TERMSRVAPPINSTALLMODE { __int32 bState;` |
| `dwNumberOfOffsets` | type_alias | `payloads/Demon/include/common/Native.h:11217` | `typedef struct _VM_INFORMATION { DWORD dwNumberOfOffsets;` |
| `dwProcessId` | type_alias | `payloads/Demon/include/common/Native.h:6140` | `typedef struct _BASE_DEBUGPROCESS_MSG { ULONG dwProcessId;` |
| `fFlags` | type_alias | `payloads/Demon/include/common/Native.h:3653` | `typedef struct _PARSE_MESSAGE_CONTEXT { ULONG fFlags;` |
| `h` | type_alias | `payloads/Demon/include/common/Native.h:5972` | `typedef struct _CSR_API_MSG { PORT_MESSAGE h;` |
| `h` | type_alias | `payloads/Demon/include/common/Native.h:6373` | `typedef struct _BASE_API_MSG { PORT_MESSAGE h;` |
| `hEventWowExec` | type_alias | `payloads/Demon/include/common/Native.h:6303` | `typedef struct _BASE_REGISTER_WOWEXEC_MSG { PVOID hEventWowExec;` |
| `iCountry` | type_alias | `payloads/Demon/include/common/Native.h:5759` | `typedef struct _NLS_USER_INFO { /*<thisrel this+0x0>*/ /*\|0xa0\|*/ WCHAR iCountry[80];` |
| `iTask` | type_alias | `payloads/Demon/include/common/Native.h:6085` | `typedef struct _BASE_UPDATE_VDM_ENTRY_MSG { ULONG iTask;` |
| `iTask` | type_alias | `payloads/Demon/include/common/Native.h:6096` | `typedef struct _BASE_GET_NEXT_VDM_COMMAND_MSG { ULONG iTask;` |
| `iTask` | type_alias | `payloads/Demon/include/common/Native.h:6147` | `typedef struct _BASE_CHECKVDM_MSG { ULONG iTask;` |
| `jmp_length` | macro | `payloads/Demon/include/common/Native.h:100` | `#define jmp_length(y,x)` |
| `pDTZInfo` | type_alias | `payloads/Demon/include/common/Native.h:6316` | `typedef struct _BASE_SET_TERMSRVCLIENTTIMEZONE { struct _RTL_DYNAMIC_TIME_ZONE_INFORMATION* pDTZInfo;` |
| `pData` | type_alias | `payloads/Demon/include/common/Native.h:6074` | `typedef struct _BASE_NLS_GET_USER_INFO_MSG { struct _NLS_USER_INFO* pData;` |
| `sidAuthority` | type_alias | `payloads/Demon/include/common/Native.h:7608` | `typedef struct _USER_SID { SID_IDENTIFIER_AUTHORITY sidAuthority;` |
| `stc_jc` | macro | `payloads/Demon/include/common/Native.h:101` | `#define stc_jc(y,x)` |
| `tzi` | type_alias | `payloads/Demon/include/common/Native.h:6012` | `typedef struct _RTL_DYNAMIC_TIME_ZONE_INFORMATION { struct _RTL_TIME_ZONE_INFORMATION tzi;` |
| `uExitCode` | type_alias | `payloads/Demon/include/common/Native.h:6193` | `typedef struct _BASE_EXITPROCESS_MSG { NTSTATUS uExitCode;` |
| `uUnique` | type_alias | `payloads/Demon/include/common/Native.h:6135` | `typedef struct _BASE_GETTEMPFILE_MSG { ULONG uUnique;` |
| `ulFlags` | type_alias | `payloads/Demon/include/common/Native.h:6220` | `typedef struct _ACTIVATION_CONTEXT_RUN_LEVEL_INFORMATION { DWORD ulFlags;` |
| `wcscat` | function | `payloads/Demon/include/common/Native.h:22539` | `IMPORT_FN wchar_t * __cdecl wcscat(wchar_t *dst, const wchar_t *src);` |
| `wcschr` | function | `payloads/Demon/include/common/Native.h:22545` | `IMPORT_FN wchar_t * __cdecl wcschr(const wchar_t *string, wchar_t ch);` |
| `wcscmp` | function | `payloads/Demon/include/common/Native.h:22540` | `IMPORT_FN int __cdecl wcscmp(const wchar_t *src, const wchar_t *dst);` |
| `wcscpy` | function | `payloads/Demon/include/common/Native.h:22546` | `IMPORT_FN wchar_t * __cdecl wcscpy(wchar_t *dst, const wchar_t *src);` |
| `wcslen` | function | `payloads/Demon/include/common/Native.h:22538` | `IMPORT_FN size_t __cdecl wcslen(const wchar_t *);` |
| `wcsncat` | function | `payloads/Demon/include/common/Native.h:22547` | `IMPORT_FN wchar_t * __cdecl wcsncat(wchar_t *front, const wchar_t *back, size_t count);` |
| `wcsncpy` | function | `payloads/Demon/include/common/Native.h:22548` | `IMPORT_FN wchar_t * __cdecl wcsncpy(wchar_t *dest, const wchar_t *source, size_t count);` |
| `COFFEE_KEY_VALUE_MAX_KEY` | macro | `payloads/Demon/include/core/CoffeeLdr.h:106` | `#define COFFEE_KEY_VALUE_MAX_KEY` |
| `DEMON_DOF_H` | macro | `payloads/Demon/include/core/CoffeeLdr.h:6` | `#define DEMON_DOF_H` |
| `Data` | type_alias | `payloads/Demon/include/core/CoffeeLdr.h:87` | `typedef struct _COFFEE { PVOID Data;` |
| `EntryName` | type_alias | `payloads/Demon/include/core/CoffeeLdr.h:18` | `typedef struct _COFFEE_PARAMS { PCHAR EntryName;` |
| `IMAGE_SCN_MEM_EXECUTE` | macro | `payloads/Demon/include/core/CoffeeLdr.h:12` | `#define IMAGE_SCN_MEM_EXECUTE` |
| `IMAGE_SCN_MEM_NOT_CACHED` | macro | `payloads/Demon/include/core/CoffeeLdr.h:11` | `#define IMAGE_SCN_MEM_NOT_CACHED` |
| `IMAGE_SCN_MEM_READ` | macro | `payloads/Demon/include/core/CoffeeLdr.h:13` | `#define IMAGE_SCN_MEM_READ` |
| `IMAGE_SCN_MEM_WRITE` | macro | `payloads/Demon/include/core/CoffeeLdr.h:14` | `#define IMAGE_SCN_MEM_WRITE` |
| `Key` | type_alias | `payloads/Demon/include/core/CoffeeLdr.h:107` | `typedef struct _COFFEE_KEY_VALUE { CHAR Key[COFFEE_KEY_VALUE_MAX_KEY];` |
| `MACHINETYPE_AMD64` | macro | `payloads/Demon/include/core/CoffeeLdr.h:42` | `#define MACHINETYPE_AMD64` |
| `Machine` | type_alias | `payloads/Demon/include/core/CoffeeLdr.h:29` | `typedef struct _COFF_FILE_HEADER { UINT16 Machine;` |
| `Name` | type_alias | `payloads/Demon/include/core/CoffeeLdr.h:45` | `typedef struct _COFF_SECTION { CHAR Name[ 8 ];` |
| `Name` | type_alias | `payloads/Demon/include/core/CoffeeLdr.h:66` | `typedef struct _COFF_SYMBOL { union { CHAR Name[ 8 ];` |
| `PAGE_ALLIGN` | macro | `payloads/Demon/include/core/CoffeeLdr.h:9` | `#define PAGE_ALLIGN( x )` |
| `Ptr` | type_alias | `payloads/Demon/include/core/CoffeeLdr.h:81` | `typedef struct _SECTION_MAP { PCHAR Ptr;` |
| `SIZE_OF_PAGE` | macro | `payloads/Demon/include/core/CoffeeLdr.h:8` | `#define SIZE_OF_PAGE` |
| `SYMBOL_IS_A_FUNCTION` | macro | `payloads/Demon/include/core/CoffeeLdr.h:17` | `#define SYMBOL_IS_A_FUNCTION` |
| `VirtualAddress` | type_alias | `payloads/Demon/include/core/CoffeeLdr.h:59` | `typedef struct _COFF_RELOC { UINT32 VirtualAddress;` |
| `_COFFEE` | struct | `payloads/Demon/include/core/CoffeeLdr.h:88` | `` |
| `_COFFEE_KEY_VALUE` | struct | `payloads/Demon/include/core/CoffeeLdr.h:108` | `` |
| `_COFFEE_PARAMS` | struct | `payloads/Demon/include/core/CoffeeLdr.h:19` | `` |
| `_COFF_FILE_HEADER` | struct | `payloads/Demon/include/core/CoffeeLdr.h:30` | `` |
| `_COFF_RELOC` | struct | `payloads/Demon/include/core/CoffeeLdr.h:60` | `` |
| `_COFF_SECTION` | struct | `payloads/Demon/include/core/CoffeeLdr.h:46` | `` |
| `_COFF_SYMBOL` | struct | `payloads/Demon/include/core/CoffeeLdr.h:67` | `` |
| `_SECTION_MAP` | struct | `payloads/Demon/include/core/CoffeeLdr.h:82` | `` |
| `thread` | function | `payloads/Demon/include/core/CoffeeLdr.h:118` | `* CoffeeLdr * Simply executes an object file in the current thread (blocking) * @param EntryName * @param CoffeeData * @` |
| `BEACON_OUTPUT` | macro | `payloads/Demon/include/core/Command.h:37` | `#define BEACON_OUTPUT` |
| `CALLBACK_ERROR_COFFEXEC` | macro | `payloads/Demon/include/core/Command.h:52` | `#define CALLBACK_ERROR_COFFEXEC` |
| `CALLBACK_ERROR_TOKEN` | macro | `payloads/Demon/include/core/Command.h:53` | `#define CALLBACK_ERROR_TOKEN` |
| `CALLBACK_ERROR_WIN32` | macro | `payloads/Demon/include/core/Command.h:51` | `#define CALLBACK_ERROR_WIN32` |
| `DEMON_CHECKIN_OPTION_PIVOTS` | macro | `payloads/Demon/include/core/Command.h:97` | `#define DEMON_CHECKIN_OPTION_PIVOTS` |
| `DEMON_COMMAND` | struct | `payloads/Demon/include/core/Command.h:139` | `` |
| `DEMON_COMMAND_ASSEMBLY_INLINE_EXECUTE` | macro | `payloads/Demon/include/core/Command.h:20` | `#define DEMON_COMMAND_ASSEMBLY_INLINE_EXECUTE` |
| `DEMON_COMMAND_ASSEMBLY_VERSIONS` | macro | `payloads/Demon/include/core/Command.h:21` | `#define DEMON_COMMAND_ASSEMBLY_VERSIONS` |
| `DEMON_COMMAND_CHECKIN` | macro | `payloads/Demon/include/core/Command.h:7` | `#define DEMON_COMMAND_CHECKIN` |
| `DEMON_COMMAND_CONFIG` | macro | `payloads/Demon/include/core/Command.h:23` | `#define DEMON_COMMAND_CONFIG` |
| `DEMON_COMMAND_FS` | macro | `payloads/Demon/include/core/Command.h:13` | `#define DEMON_COMMAND_FS` |
| `DEMON_COMMAND_FS_CAT` | macro | `payloads/Demon/include/core/Command.h:136` | `#define DEMON_COMMAND_FS_CAT` |
| `DEMON_COMMAND_FS_CD` | macro | `payloads/Demon/include/core/Command.h:130` | `#define DEMON_COMMAND_FS_CD` |
| `DEMON_COMMAND_FS_COPY` | macro | `payloads/Demon/include/core/Command.h:133` | `#define DEMON_COMMAND_FS_COPY` |
| `DEMON_COMMAND_FS_DIR` | macro | `payloads/Demon/include/core/Command.h:127` | `#define DEMON_COMMAND_FS_DIR` |
| `DEMON_COMMAND_FS_DOWNLOAD` | macro | `payloads/Demon/include/core/Command.h:128` | `#define DEMON_COMMAND_FS_DOWNLOAD` |
| `DEMON_COMMAND_FS_GET_PWD` | macro | `payloads/Demon/include/core/Command.h:135` | `#define DEMON_COMMAND_FS_GET_PWD` |
| `DEMON_COMMAND_FS_MKDIR` | macro | `payloads/Demon/include/core/Command.h:132` | `#define DEMON_COMMAND_FS_MKDIR` |
| `DEMON_COMMAND_FS_MOVE` | macro | `payloads/Demon/include/core/Command.h:134` | `#define DEMON_COMMAND_FS_MOVE` |
| `DEMON_COMMAND_FS_REMOVE` | macro | `payloads/Demon/include/core/Command.h:131` | `#define DEMON_COMMAND_FS_REMOVE` |
| `DEMON_COMMAND_FS_UPLOAD` | macro | `payloads/Demon/include/core/Command.h:129` | `#define DEMON_COMMAND_FS_UPLOAD` |
| `DEMON_COMMAND_GET_JOB` | macro | `payloads/Demon/include/core/Command.h:8` | `#define DEMON_COMMAND_GET_JOB` |
| `DEMON_COMMAND_H` | macro | `payloads/Demon/include/core/Command.h:2` | `#define DEMON_COMMAND_H` |
| `DEMON_COMMAND_INJECT_DLL` | macro | `payloads/Demon/include/core/Command.h:16` | `#define DEMON_COMMAND_INJECT_DLL` |
| `DEMON_COMMAND_INJECT_SHELLCODE` | macro | `payloads/Demon/include/core/Command.h:17` | `#define DEMON_COMMAND_INJECT_SHELLCODE` |
| `DEMON_COMMAND_INLINE_EXECUTE` | macro | `payloads/Demon/include/core/Command.h:14` | `#define DEMON_COMMAND_INLINE_EXECUTE` |
| `DEMON_COMMAND_INLINE_EXECUTE_COULD_NO_RUN` | macro | `payloads/Demon/include/core/Command.h:43` | `#define DEMON_COMMAND_INLINE_EXECUTE_COULD_NO_RUN` |
| `DEMON_COMMAND_INLINE_EXECUTE_EXCEPTION` | macro | `payloads/Demon/include/core/Command.h:40` | `#define DEMON_COMMAND_INLINE_EXECUTE_EXCEPTION` |
| `DEMON_COMMAND_INLINE_EXECUTE_RAN_OK` | macro | `payloads/Demon/include/core/Command.h:42` | `#define DEMON_COMMAND_INLINE_EXECUTE_RAN_OK` |
| `DEMON_COMMAND_INLINE_EXECUTE_SYMBOL_NOT_FOUND` | macro | `payloads/Demon/include/core/Command.h:41` | `#define DEMON_COMMAND_INLINE_EXECUTE_SYMBOL_NOT_FOUND` |
| `DEMON_COMMAND_JOB` | macro | `payloads/Demon/include/core/Command.h:15` | `#define DEMON_COMMAND_JOB` |
| `DEMON_COMMAND_JOB_DIED` | macro | `payloads/Demon/include/core/Command.h:103` | `#define DEMON_COMMAND_JOB_DIED` |
| `DEMON_COMMAND_JOB_KILL_REMOVE` | macro | `payloads/Demon/include/core/Command.h:102` | `#define DEMON_COMMAND_JOB_KILL_REMOVE` |
| `DEMON_COMMAND_JOB_LIST` | macro | `payloads/Demon/include/core/Command.h:99` | `#define DEMON_COMMAND_JOB_LIST` |
| `DEMON_COMMAND_JOB_RESUME` | macro | `payloads/Demon/include/core/Command.h:101` | `#define DEMON_COMMAND_JOB_RESUME` |
| `DEMON_COMMAND_JOB_SUSPEND` | macro | `payloads/Demon/include/core/Command.h:100` | `#define DEMON_COMMAND_JOB_SUSPEND` |
| `DEMON_COMMAND_KERBEROS` | macro | `payloads/Demon/include/core/Command.h:28` | `#define DEMON_COMMAND_KERBEROS` |
| `DEMON_COMMAND_MEM_FILE` | macro | `payloads/Demon/include/core/Command.h:29` | `#define DEMON_COMMAND_MEM_FILE` |
| `DEMON_COMMAND_NET` | macro | `payloads/Demon/include/core/Command.h:22` | `#define DEMON_COMMAND_NET` |
| `DEMON_COMMAND_NO_JOB` | macro | `payloads/Demon/include/core/Command.h:9` | `#define DEMON_COMMAND_NO_JOB` |
| `DEMON_COMMAND_PIVOT` | macro | `payloads/Demon/include/core/Command.h:25` | `#define DEMON_COMMAND_PIVOT` |
| `DEMON_COMMAND_PROC` | macro | `payloads/Demon/include/core/Command.h:11` | `#define DEMON_COMMAND_PROC` |
| `DEMON_COMMAND_PROC_CREATE` | macro | `payloads/Demon/include/core/Command.h:112` | `#define DEMON_COMMAND_PROC_CREATE` |
| `DEMON_COMMAND_PROC_GREP` | macro | `payloads/Demon/include/core/Command.h:111` | `#define DEMON_COMMAND_PROC_GREP` |
| `DEMON_COMMAND_PROC_KILL` | macro | `payloads/Demon/include/core/Command.h:114` | `#define DEMON_COMMAND_PROC_KILL` |
| `DEMON_COMMAND_PROC_LIST` | macro | `payloads/Demon/include/core/Command.h:12` | `#define DEMON_COMMAND_PROC_LIST` |
| `DEMON_COMMAND_PROC_MEMORY` | macro | `payloads/Demon/include/core/Command.h:113` | `#define DEMON_COMMAND_PROC_MEMORY` |
| `DEMON_COMMAND_PROC_MODULES` | macro | `payloads/Demon/include/core/Command.h:110` | `#define DEMON_COMMAND_PROC_MODULES` |
| `DEMON_COMMAND_SCREENSHOT` | macro | `payloads/Demon/include/core/Command.h:24` | `#define DEMON_COMMAND_SCREENSHOT` |
| `DEMON_COMMAND_SLEEP` | macro | `payloads/Demon/include/core/Command.h:10` | `#define DEMON_COMMAND_SLEEP` |
| `DEMON_COMMAND_SOCKET` | macro | `payloads/Demon/include/core/Command.h:27` | `#define DEMON_COMMAND_SOCKET` |
| `DEMON_COMMAND_SPAWN_DLL` | macro | `payloads/Demon/include/core/Command.h:18` | `#define DEMON_COMMAND_SPAWN_DLL` |
| `DEMON_COMMAND_TOKEN` | macro | `payloads/Demon/include/core/Command.h:19` | `#define DEMON_COMMAND_TOKEN` |
| `DEMON_COMMAND_TOKEN_CLEAR` | macro | `payloads/Demon/include/core/Command.h:124` | `#define DEMON_COMMAND_TOKEN_CLEAR` |
| `DEMON_COMMAND_TOKEN_FIND_TOKENS` | macro | `payloads/Demon/include/core/Command.h:125` | `#define DEMON_COMMAND_TOKEN_FIND_TOKENS` |
| `DEMON_COMMAND_TOKEN_GET_UID` | macro | `payloads/Demon/include/core/Command.h:121` | `#define DEMON_COMMAND_TOKEN_GET_UID` |
| `DEMON_COMMAND_TOKEN_IMPERSONATE` | macro | `payloads/Demon/include/core/Command.h:116` | `#define DEMON_COMMAND_TOKEN_IMPERSONATE` |
| `DEMON_COMMAND_TOKEN_LIST` | macro | `payloads/Demon/include/core/Command.h:118` | `#define DEMON_COMMAND_TOKEN_LIST` |
| `DEMON_COMMAND_TOKEN_MAKE` | macro | `payloads/Demon/include/core/Command.h:120` | `#define DEMON_COMMAND_TOKEN_MAKE` |
| `DEMON_COMMAND_TOKEN_PRIVSGET_OR_LIST` | macro | `payloads/Demon/include/core/Command.h:119` | `#define DEMON_COMMAND_TOKEN_PRIVSGET_OR_LIST` |
| `DEMON_COMMAND_TOKEN_REMOVE` | macro | `payloads/Demon/include/core/Command.h:123` | `#define DEMON_COMMAND_TOKEN_REMOVE` |
| `DEMON_COMMAND_TOKEN_REVERT` | macro | `payloads/Demon/include/core/Command.h:122` | `#define DEMON_COMMAND_TOKEN_REVERT` |
| `DEMON_COMMAND_TOKEN_STEAL` | macro | `payloads/Demon/include/core/Command.h:117` | `#define DEMON_COMMAND_TOKEN_STEAL` |
| `DEMON_COMMAND_TRANSFER` | macro | `payloads/Demon/include/core/Command.h:26` | `#define DEMON_COMMAND_TRANSFER` |
| `DEMON_COMMAND_TRANSFER_LIST` | macro | `payloads/Demon/include/core/Command.h:105` | `#define DEMON_COMMAND_TRANSFER_LIST` |
| `DEMON_COMMAND_TRANSFER_REMOVE` | macro | `payloads/Demon/include/core/Command.h:108` | `#define DEMON_COMMAND_TRANSFER_REMOVE` |
| `DEMON_COMMAND_TRANSFER_RESUME` | macro | `payloads/Demon/include/core/Command.h:107` | `#define DEMON_COMMAND_TRANSFER_RESUME` |
| `DEMON_COMMAND_TRANSFER_STOP` | macro | `payloads/Demon/include/core/Command.h:106` | `#define DEMON_COMMAND_TRANSFER_STOP` |
| `DEMON_CONFIG_IMPLANT_COFFEE_THREADED` | macro | `payloads/Demon/include/core/Command.h:62` | `#define DEMON_CONFIG_IMPLANT_COFFEE_THREADED` |
| `DEMON_CONFIG_IMPLANT_COFFEE_VEH` | macro | `payloads/Demon/include/core/Command.h:63` | `#define DEMON_CONFIG_IMPLANT_COFFEE_VEH` |
| `DEMON_CONFIG_IMPLANT_SLEEPMASK` | macro | `payloads/Demon/include/core/Command.h:58` | `#define DEMON_CONFIG_IMPLANT_SLEEPMASK` |
| `DEMON_CONFIG_IMPLANT_SLEEP_TECHNIQUE` | macro | `payloads/Demon/include/core/Command.h:61` | `#define DEMON_CONFIG_IMPLANT_SLEEP_TECHNIQUE` |
| `DEMON_CONFIG_IMPLANT_SPFTHREADADDR` | macro | `payloads/Demon/include/core/Command.h:59` | `#define DEMON_CONFIG_IMPLANT_SPFTHREADADDR` |
| `DEMON_CONFIG_IMPLANT_VERBOSE` | macro | `payloads/Demon/include/core/Command.h:60` | `#define DEMON_CONFIG_IMPLANT_VERBOSE` |
| `DEMON_CONFIG_INJECTION_SPAWN32` | macro | `payloads/Demon/include/core/Command.h:72` | `#define DEMON_CONFIG_INJECTION_SPAWN32` |
| `DEMON_CONFIG_INJECTION_SPAWN64` | macro | `payloads/Demon/include/core/Command.h:71` | `#define DEMON_CONFIG_INJECTION_SPAWN64` |
| `DEMON_CONFIG_INJECTION_SPOOFADDR` | macro | `payloads/Demon/include/core/Command.h:69` | `#define DEMON_CONFIG_INJECTION_SPOOFADDR` |
| `DEMON_CONFIG_INJECTION_TECHNIQUE` | macro | `payloads/Demon/include/core/Command.h:68` | `#define DEMON_CONFIG_INJECTION_TECHNIQUE` |
| `DEMON_CONFIG_KILLDATE` | macro | `payloads/Demon/include/core/Command.h:73` | `#define DEMON_CONFIG_KILLDATE` |
| `DEMON_CONFIG_MEMORY_ALLOC` | macro | `payloads/Demon/include/core/Command.h:65` | `#define DEMON_CONFIG_MEMORY_ALLOC` |
| `DEMON_CONFIG_MEMORY_EXECUTE` | macro | `payloads/Demon/include/core/Command.h:66` | `#define DEMON_CONFIG_MEMORY_EXECUTE` |
| `DEMON_CONFIG_SHOW_ALL` | macro | `payloads/Demon/include/core/Command.h:56` | `#define DEMON_CONFIG_SHOW_ALL` |
| `DEMON_CONFIG_WORKINGHOURS` | macro | `payloads/Demon/include/core/Command.h:74` | `#define DEMON_CONFIG_WORKINGHOURS` |
| `DEMON_ERROR` | macro | `payloads/Demon/include/core/Command.h:34` | `#define DEMON_ERROR` |
| `DEMON_EXIT` | macro | `payloads/Demon/include/core/Command.h:35` | `#define DEMON_EXIT` |
| `DEMON_INFO` | macro | `payloads/Demon/include/core/Command.h:32` | `#define DEMON_INFO` |
| `DEMON_INFO_MEM_ALLOC` | macro | `payloads/Demon/include/core/Command.h:92` | `#define DEMON_INFO_MEM_ALLOC` |
| `DEMON_INFO_MEM_EXEC` | macro | `payloads/Demon/include/core/Command.h:93` | `#define DEMON_INFO_MEM_EXEC` |
| `DEMON_INFO_MEM_PROTECT` | macro | `payloads/Demon/include/core/Command.h:94` | `#define DEMON_INFO_MEM_PROTECT` |
| `DEMON_INFO_PROC_CREATE` | macro | `payloads/Demon/include/core/Command.h:95` | `#define DEMON_INFO_PROC_CREATE` |
| `DEMON_INITIALIZE` | macro | `payloads/Demon/include/core/Command.h:38` | `#define DEMON_INITIALIZE` |
| `DEMON_KILL_DATE` | macro | `payloads/Demon/include/core/Command.h:36` | `#define DEMON_KILL_DATE` |
| `DEMON_NET_COMMAND_COMPUTER` | macro | `payloads/Demon/include/core/Command.h:79` | `#define DEMON_NET_COMMAND_COMPUTER` |
| `DEMON_NET_COMMAND_DCLIST` | macro | `payloads/Demon/include/core/Command.h:80` | `#define DEMON_NET_COMMAND_DCLIST` |
| `DEMON_NET_COMMAND_DOMAIN` | macro | `payloads/Demon/include/core/Command.h:76` | `#define DEMON_NET_COMMAND_DOMAIN` |
| `DEMON_NET_COMMAND_GROUP` | macro | `payloads/Demon/include/core/Command.h:83` | `#define DEMON_NET_COMMAND_GROUP` |
| `DEMON_NET_COMMAND_LOCALGROUP` | macro | `payloads/Demon/include/core/Command.h:82` | `#define DEMON_NET_COMMAND_LOCALGROUP` |
| `DEMON_NET_COMMAND_LOGONS` | macro | `payloads/Demon/include/core/Command.h:77` | `#define DEMON_NET_COMMAND_LOGONS` |
| `DEMON_NET_COMMAND_SESSIONS` | macro | `payloads/Demon/include/core/Command.h:78` | `#define DEMON_NET_COMMAND_SESSIONS` |
| `DEMON_NET_COMMAND_SHARE` | macro | `payloads/Demon/include/core/Command.h:81` | `#define DEMON_NET_COMMAND_SHARE` |
| `DEMON_NET_COMMAND_USER` | macro | `payloads/Demon/include/core/Command.h:84` | `#define DEMON_NET_COMMAND_USER` |
| `DEMON_OUTPUT` | macro | `payloads/Demon/include/core/Command.h:33` | `#define DEMON_OUTPUT` |
| `DEMON_PACKAGE_DROPPED` | macro | `payloads/Demon/include/core/Command.h:30` | `#define DEMON_PACKAGE_DROPPED` |
| `DEMON_PIVOT_LIST` | macro | `payloads/Demon/include/core/Command.h:86` | `#define DEMON_PIVOT_LIST` |
| `DEMON_PIVOT_SMB_COMMAND` | macro | `payloads/Demon/include/core/Command.h:90` | `#define DEMON_PIVOT_SMB_COMMAND` |
| `DEMON_PIVOT_SMB_CONNECT` | macro | `payloads/Demon/include/core/Command.h:88` | `#define DEMON_PIVOT_SMB_CONNECT` |
| `DEMON_PIVOT_SMB_DISCONNECT` | macro | `payloads/Demon/include/core/Command.h:89` | `#define DEMON_PIVOT_SMB_DISCONNECT` |
| `DOTNET_INFO_ENTRYPOINT_EXECUTED` | macro | `payloads/Demon/include/core/Command.h:47` | `#define DOTNET_INFO_ENTRYPOINT_EXECUTED` |
| `DOTNET_INFO_FAILED` | macro | `payloads/Demon/include/core/Command.h:49` | `#define DOTNET_INFO_FAILED` |
| `DOTNET_INFO_FINISHED` | macro | `payloads/Demon/include/core/Command.h:48` | `#define DOTNET_INFO_FINISHED` |
| `DOTNET_INFO_NET_VERSION` | macro | `payloads/Demon/include/core/Command.h:46` | `#define DOTNET_INFO_NET_VERSION` |
| `DOTNET_INFO_PATCHED` | macro | `payloads/Demon/include/core/Command.h:45` | `#define DOTNET_INFO_PATCHED` |
| `DEMON_FILETRANFER_H` | macro | `payloads/Demon/include/core/Download.h:2` | `#define DEMON_FILETRANFER_H` |
| `DOWNLOAD_MODE_CLOSE` | macro | `payloads/Demon/include/core/Download.h:8` | `#define DOWNLOAD_MODE_CLOSE` |
| `DOWNLOAD_MODE_OPEN` | macro | `payloads/Demon/include/core/Download.h:6` | `#define DOWNLOAD_MODE_OPEN` |
| `DOWNLOAD_MODE_WRITE` | macro | `payloads/Demon/include/core/Download.h:7` | `#define DOWNLOAD_MODE_WRITE` |
| `DOWNLOAD_REASON_FINISHED` | macro | `payloads/Demon/include/core/Download.h:10` | `#define DOWNLOAD_REASON_FINISHED` |
| `DOWNLOAD_REASON_REMOVED` | macro | `payloads/Demon/include/core/Download.h:11` | `#define DOWNLOAD_REASON_REMOVED` |
| `DOWNLOAD_STATE_REMOVE` | macro | `payloads/Demon/include/core/Download.h:15` | `#define DOWNLOAD_STATE_REMOVE` |
| `DOWNLOAD_STATE_RUNNING` | macro | `payloads/Demon/include/core/Download.h:13` | `#define DOWNLOAD_STATE_RUNNING` |
| `DOWNLOAD_STATE_STOPPED` | macro | `payloads/Demon/include/core/Download.h:14` | `#define DOWNLOAD_STATE_STOPPED` |
| `FileID` | type_alias | `payloads/Demon/include/core/Download.h:22` | `typedef struct _DOWNLOAD_DATA { /* Some random ID so both teamserver and agent knows what file it is */ DWORD FileID;` |
| `ID` | type_alias | `payloads/Demon/include/core/Download.h:48` | `typedef struct _MEM_FILE { /* Some random ID so both teamserver and agent knows what MemFile it is */ ULONG32 ID;` |
| `_DOWNLOAD_DATA` | struct | `payloads/Demon/include/core/Download.h:23` | `` |
| `_MEM_FILE` | struct | `payloads/Demon/include/core/Download.h:48` | `` |
| `DEMON_HWBPENGINE_H` | macro | `payloads/Demon/include/core/HwBpEngine.h:2` | `#define DEMON_HWBPENGINE_H` |
| `Tid` | type_alias | `payloads/Demon/include/core/HwBpEngine.h:6` | `typedef struct _BP_LIST { DWORD Tid;` |
| `Veh` | type_alias | `payloads/Demon/include/core/HwBpEngine.h:17` | `typedef struct _HWBP_ENGINE { /* Veh (Vectored Exception Handling) handle */ HANDLE Veh;` |
| `_BP_LIST` | struct | `payloads/Demon/include/core/HwBpEngine.h:7` | `` |
| `_HWBP_ENGINE` | struct | `payloads/Demon/include/core/HwBpEngine.h:18` | `` |
| `DEMON_HWBPEXCEPTIONS_H` | macro | `payloads/Demon/include/core/HwBpExceptions.h:2` | `#define DEMON_HWBPEXCEPTIONS_H` |
| `EXCEPTION_ADJ_STACK` | macro | `payloads/Demon/include/core/HwBpExceptions.h:33` | `#define EXCEPTION_ADJ_STACK( e, i )` |
| `EXCEPTION_ARG_1` | macro | `payloads/Demon/include/core/HwBpExceptions.h:34` | `#define EXCEPTION_ARG_1( e )` |
| `EXCEPTION_ARG_1` | macro | `payloads/Demon/include/core/HwBpExceptions.h:44` | `#define EXCEPTION_ARG_1( e )` |
| `EXCEPTION_ARG_2` | macro | `payloads/Demon/include/core/HwBpExceptions.h:35` | `#define EXCEPTION_ARG_2( e )` |
| `EXCEPTION_ARG_2` | macro | `payloads/Demon/include/core/HwBpExceptions.h:45` | `#define EXCEPTION_ARG_2( e )` |
| `EXCEPTION_ARG_3` | macro | `payloads/Demon/include/core/HwBpExceptions.h:36` | `#define EXCEPTION_ARG_3( e )` |
| `EXCEPTION_ARG_3` | macro | `payloads/Demon/include/core/HwBpExceptions.h:46` | `#define EXCEPTION_ARG_3( e )` |
| `EXCEPTION_ARG_4` | macro | `payloads/Demon/include/core/HwBpExceptions.h:37` | `#define EXCEPTION_ARG_4( e )` |
| `EXCEPTION_ARG_4` | macro | `payloads/Demon/include/core/HwBpExceptions.h:47` | `#define EXCEPTION_ARG_4( e )` |
| `EXCEPTION_ARG_5` | macro | `payloads/Demon/include/core/HwBpExceptions.h:38` | `#define EXCEPTION_ARG_5( e )` |
| `EXCEPTION_ARG_5` | macro | `payloads/Demon/include/core/HwBpExceptions.h:48` | `#define EXCEPTION_ARG_5( e )` |
| `EXCEPTION_ARG_6` | macro | `payloads/Demon/include/core/HwBpExceptions.h:39` | `#define EXCEPTION_ARG_6( e )` |
| `EXCEPTION_ARG_6` | macro | `payloads/Demon/include/core/HwBpExceptions.h:49` | `#define EXCEPTION_ARG_6( e )` |
| `EXCEPTION_ARG_7` | macro | `payloads/Demon/include/core/HwBpExceptions.h:40` | `#define EXCEPTION_ARG_7( e )` |
| `EXCEPTION_ARG_7` | macro | `payloads/Demon/include/core/HwBpExceptions.h:50` | `#define EXCEPTION_ARG_7( e )` |
| `EXCEPTION_DUMP` | macro | `payloads/Demon/include/core/HwBpExceptions.h:8` | `#define EXCEPTION_DUMP( e )` |
| `EXCEPTION_GET_RET` | macro | `payloads/Demon/include/core/HwBpExceptions.h:32` | `#define EXCEPTION_GET_RET( e )` |
| `EXCEPTION_RESUME` | macro | `payloads/Demon/include/core/HwBpExceptions.h:31` | `#define EXCEPTION_RESUME( e )` |
| `EXCEPTION_SET_RET` | macro | `payloads/Demon/include/core/HwBpExceptions.h:30` | `#define EXCEPTION_SET_RET( e, r )` |
| `EXCEPTION_SET_RIP` | macro | `payloads/Demon/include/core/HwBpExceptions.h:29` | `#define EXCEPTION_SET_RIP( e, p )` |
| `DEMON_JOBS_HPP` | macro | `payloads/Demon/include/core/Jobs.h:2` | `#define DEMON_JOBS_HPP` |
| `JOB_STATE_DEAD` | macro | `payloads/Demon/include/core/Jobs.h:12` | `#define JOB_STATE_DEAD` |
| `JOB_STATE_RUNNING` | macro | `payloads/Demon/include/core/Jobs.h:10` | `#define JOB_STATE_RUNNING` |
| `JOB_STATE_SUSPENDED` | macro | `payloads/Demon/include/core/Jobs.h:11` | `#define JOB_STATE_SUSPENDED` |
| `JOB_TYPE_PROCESS` | macro | `payloads/Demon/include/core/Jobs.h:7` | `#define JOB_TYPE_PROCESS` |
| `JOB_TYPE_THREAD` | macro | `payloads/Demon/include/core/Jobs.h:6` | `#define JOB_TYPE_THREAD` |
| `JOB_TYPE_TRACK_PROCESS` | macro | `payloads/Demon/include/core/Jobs.h:8` | `#define JOB_TYPE_TRACK_PROCESS` |
| `RequestID` | type_alias | `payloads/Demon/include/core/Jobs.h:13` | `typedef struct _JOB_DATA { UINT32 RequestID;` |
| `_JOB_DATA` | struct | `payloads/Demon/include/core/Jobs.h:14` | `` |
| `ClientName` | type_alias | `payloads/Demon/include/core/Kerberos.h:25` | `typedef struct _TICKET_INFORMATION { WCHAR ClientName[FIELD_LENGTH];` |
| `ClientName` | type_alias | `payloads/Demon/include/core/Kerberos.h:123` | `typedef struct _KERB_TICKET_CACHE_INFO_EX { UNICODE_STRING ClientName;` |
| `DEMON_KERBEROS_H` | macro | `payloads/Demon/include/core/Kerberos.h:3` | `#define DEMON_KERBEROS_H` |
| `FIELD_LENGTH` | macro | `payloads/Demon/include/core/Kerberos.h:24` | `#define FIELD_LENGTH` |
| `GetLUID` | function | `payloads/Demon/include/core/Kerberos.h:203` | `LUID* GetLUID( HANDLE hToken );` |
| `KERBEROS_COMMAND_KLIST` | macro | `payloads/Demon/include/core/Kerberos.h:8` | `#define KERBEROS_COMMAND_KLIST` |
| `KERBEROS_COMMAND_LUID` | macro | `payloads/Demon/include/core/Kerberos.h:7` | `#define KERBEROS_COMMAND_LUID` |
| `KERBEROS_COMMAND_PTT` | macro | `payloads/Demon/include/core/Kerberos.h:10` | `#define KERBEROS_COMMAND_PTT` |
| `KERBEROS_COMMAND_PURGE` | macro | `payloads/Demon/include/core/Kerberos.h:9` | `#define KERBEROS_COMMAND_PURGE` |
| `KERB_CRYPTO_KEY` | struct | `payloads/Demon/include/core/Kerberos.h:96` | `` |
| `KERB_CRYPTO_KEY32` | struct | `payloads/Demon/include/core/Kerberos.h:102` | `` |
| `KERB_RETRIEVE_TICKET_AS_KERB_CRED` | macro | `payloads/Demon/include/core/Kerberos.h:20` | `#define KERB_RETRIEVE_TICKET_AS_KERB_CRED` |
| `KERB_RETRIEVE_TICKET_CACHE_TICKET` | macro | `payloads/Demon/include/core/Kerberos.h:22` | `#define KERB_RETRIEVE_TICKET_CACHE_TICKET` |
| `KERB_RETRIEVE_TICKET_DEFAULT` | macro | `payloads/Demon/include/core/Kerberos.h:16` | `#define KERB_RETRIEVE_TICKET_DEFAULT` |
| `KERB_RETRIEVE_TICKET_DONT_USE_CACHE` | macro | `payloads/Demon/include/core/Kerberos.h:17` | `#define KERB_RETRIEVE_TICKET_DONT_USE_CACHE` |
| `KERB_RETRIEVE_TICKET_USE_CACHE_ONLY` | macro | `payloads/Demon/include/core/Kerberos.h:18` | `#define KERB_RETRIEVE_TICKET_USE_CACHE_ONLY` |
| `KERB_RETRIEVE_TICKET_USE_CREDHANDLE` | macro | `payloads/Demon/include/core/Kerberos.h:19` | `#define KERB_RETRIEVE_TICKET_USE_CREDHANDLE` |
| `KERB_RETRIEVE_TICKET_WITH_SEC_CRED` | macro | `payloads/Demon/include/core/Kerberos.h:21` | `#define KERB_RETRIEVE_TICKET_WITH_SEC_CRED` |
| `KERB_USE_DEFAULT_TICKET_FLAGS` | macro | `payloads/Demon/include/core/Kerberos.h:14` | `#define KERB_USE_DEFAULT_TICKET_FLAGS` |
| `KeyType` | type_alias | `payloads/Demon/include/core/Kerberos.h:95` | `typedef struct KERB_CRYPTO_KEY { LONG KeyType;` |
| `KeyType` | type_alias | `payloads/Demon/include/core/Kerberos.h:101` | `typedef struct KERB_CRYPTO_KEY32 { LONG KeyType;` |
| `MessageType` | type_alias | `payloads/Demon/include/core/Kerberos.h:107` | `typedef struct _KERB_SUBMIT_TKT_REQUEST { KERB_PROTOCOL_MESSAGE_TYPE MessageType;` |
| `MessageType` | type_alias | `payloads/Demon/include/core/Kerberos.h:116` | `typedef struct _KERB_PURGE_TKT_CACHE_REQUEST { KERB_PROTOCOL_MESSAGE_TYPE MessageType;` |
| `MessageType` | type_alias | `payloads/Demon/include/core/Kerberos.h:135` | `typedef struct _KERB_QUERY_TKT_CACHE_EX_RESPONSE { KERB_PROTOCOL_MESSAGE_TYPE MessageType;` |
| `MessageType` | type_alias | `payloads/Demon/include/core/Kerberos.h:150` | `typedef struct _KERB_RETRIEVE_TKT_REQUEST { KERB_PROTOCOL_MESSAGE_TYPE MessageType;` |
| `MessageType` | type_alias | `payloads/Demon/include/core/Kerberos.h:189` | `typedef struct _KERB_QUERY_TKT_CACHE_REQUEST { KERB_PROTOCOL_MESSAGE_TYPE MessageType;` |
| `NameType` | type_alias | `payloads/Demon/include/core/Kerberos.h:160` | `typedef struct _KERB_EXTERNAL_NAME { SHORT NameType;` |
| `ServiceName` | type_alias | `payloads/Demon/include/core/Kerberos.h:166` | `typedef struct _KERB_EXTERNAL_TICKET { PKERB_EXTERNAL_NAME ServiceName;` |
| `Ticket` | type_alias | `payloads/Demon/include/core/Kerberos.h:185` | `typedef struct _KERB_RETRIEVE_TKT_RESPONSE { KERB_EXTERNAL_TICKET Ticket;` |
| `UserName` | type_alias | `payloads/Demon/include/core/Kerberos.h:39` | `typedef struct _SESSION_INFORMATION { WCHAR UserName[FIELD_LENGTH];` |
| `_KERB_EXTERNAL_NAME` | struct | `payloads/Demon/include/core/Kerberos.h:161` | `` |
| `_KERB_EXTERNAL_TICKET` | struct | `payloads/Demon/include/core/Kerberos.h:167` | `` |
| `_KERB_PROTOCOL_MESSAGE_TYPE` | enum | `payloads/Demon/include/core/Kerberos.h:56` | `` |
| `_KERB_PURGE_TKT_CACHE_REQUEST` | struct | `payloads/Demon/include/core/Kerberos.h:117` | `` |
| `_KERB_QUERY_TKT_CACHE_EX_RESPONSE` | struct | `payloads/Demon/include/core/Kerberos.h:136` | `` |
| `_KERB_QUERY_TKT_CACHE_REQUEST` | struct | `payloads/Demon/include/core/Kerberos.h:190` | `` |
| `_KERB_RETRIEVE_TKT_REQUEST` | struct | `payloads/Demon/include/core/Kerberos.h:151` | `` |
| `_KERB_RETRIEVE_TKT_RESPONSE` | struct | `payloads/Demon/include/core/Kerberos.h:186` | `` |
| `_KERB_SUBMIT_TKT_REQUEST` | struct | `payloads/Demon/include/core/Kerberos.h:108` | `` |
| `_KERB_TICKET_CACHE_INFO_EX` | struct | `payloads/Demon/include/core/Kerberos.h:124` | `` |
| `_KerbSubmitTicketMessage` | macro | `payloads/Demon/include/core/Kerberos.h:12` | `#define _KerbSubmitTicketMessage` |
| `_LOGON_SESSION_DATA` | struct | `payloads/Demon/include/core/Kerberos.h:195` | `` |
| `_SESSION_INFORMATION` | struct | `payloads/Demon/include/core/Kerberos.h:40` | `` |
| `_SecHandle` | struct | `payloads/Demon/include/core/Kerberos.h:143` | `` |
| `_TICKET_INFORMATION` | struct | `payloads/Demon/include/core/Kerberos.h:26` | `` |
| `__SECHANDLE_DEFINED__` | macro | `payloads/Demon/include/core/Kerberos.h:148` | `#define __SECHANDLE_DEFINED__` |
| `dwLower` | type_alias | `payloads/Demon/include/core/Kerberos.h:143` | `typedef struct _SecHandle { ULONG_PTR dwLower;` |
| `sessionData` | type_alias | `payloads/Demon/include/core/Kerberos.h:194` | `typedef struct _LOGON_SESSION_DATA { PSECURITY_LOGON_SESSION_DATA* sessionData;` |
| `DEMON_MEMORY_H` | macro | `payloads/Demon/include/core/Memory.h:2` | `#define DEMON_MEMORY_H` |
| `_DX_MEMORY` | enum | `payloads/Demon/include/core/Memory.h:6` | `` |
| `DEMON_DSTDIO_H` | macro | `payloads/Demon/include/core/MiniStd.h:2` | `#define DEMON_DSTDIO_H` |
| `MemCopy` | macro | `payloads/Demon/include/core/MiniStd.h:6` | `#define MemCopy` |
| `MemSet` | macro | `payloads/Demon/include/core/MiniStd.h:7` | `#define MemSet` |
| `MemZero` | macro | `payloads/Demon/include/core/MiniStd.h:8` | `#define MemZero( p, l )` |
| `NO_INLINE` | macro | `payloads/Demon/include/core/MiniStd.h:9` | `#define NO_INLINE` |
| `BEACON_INFO` | struct | `payloads/Demon/include/core/ObjectApi.h:35` | `` |
| `BeaconApi` | variable | `payloads/Demon/include/core/ObjectApi.h:12` | `extern COFFAPIFUNC BeaconApi[];` |
| `BeaconApiCounter` | variable | `payloads/Demon/include/core/ObjectApi.h:13` | `extern DWORD BeaconApiCounter;` |
| `CALLBACK_ERROR` | macro | `payloads/Demon/include/core/ObjectApi.h:19` | `#define CALLBACK_ERROR` |
| `CALLBACK_OUTPUT` | macro | `payloads/Demon/include/core/ObjectApi.h:17` | `#define CALLBACK_OUTPUT` |
| `CALLBACK_OUTPUT_OEM` | macro | `payloads/Demon/include/core/ObjectApi.h:18` | `#define CALLBACK_OUTPUT_OEM` |
| `CALLBACK_OUTPUT_UTF8` | macro | `payloads/Demon/include/core/ObjectApi.h:20` | `#define CALLBACK_OUTPUT_UTF8` |
| `COFFAPIFUNC` | struct | `payloads/Demon/include/core/ObjectApi.h:6` | `` |
| `DATA_STORE_TYPE_EMPTY` | macro | `payloads/Demon/include/core/ObjectApi.h:46` | `#define DATA_STORE_TYPE_EMPTY` |
| `DATA_STORE_TYPE_GENERAL_FILE` | macro | `payloads/Demon/include/core/ObjectApi.h:47` | `#define DATA_STORE_TYPE_GENERAL_FILE` |
| `DEMON_OBJECTAPI_H` | macro | `payloads/Demon/include/core/ObjectApi.h:2` | `#define DEMON_OBJECTAPI_H` |
| `HEAP_RECORD` | struct | `payloads/Demon/include/core/ObjectApi.h:29` | `` |
| `LdrApi` | variable | `payloads/Demon/include/core/ObjectApi.h:14` | `extern COFFAPIFUNC LdrApi[];` |
| `MASK_SIZE` | macro | `payloads/Demon/include/core/ObjectApi.h:33` | `#define MASK_SIZE` |
| `NtApi` | variable | `payloads/Demon/include/core/ObjectApi.h:15` | `extern COFFAPIFUNC NtApi[];` |
| `CALLBACK_PACKAGE_H` | macro | `payloads/Demon/include/core/Package.h:2` | `#define CALLBACK_PACKAGE_H` |
| `DEMON_MAX_REQUEST_LENGTH` | macro | `payloads/Demon/include/core/Package.h:6` | `#define DEMON_MAX_REQUEST_LENGTH` |
| `PACKAGE_ERROR_NTSTATUS` | macro | `payloads/Demon/include/core/Package.h:103` | `#define PACKAGE_ERROR_NTSTATUS( s )` |
| `PACKAGE_ERROR_WIN32` | macro | `payloads/Demon/include/core/Package.h:102` | `#define PACKAGE_ERROR_WIN32` |
| `RequestID` | type_alias | `payloads/Demon/include/core/Package.h:7` | `typedef struct _PACKAGE { UINT32 RequestID;` |
| `_PACKAGE` | struct | `payloads/Demon/include/core/Package.h:8` | `` |
| `DEMON_PARSER_H` | macro | `payloads/Demon/include/core/Parser.h:2` | `#define DEMON_PARSER_H` |
| `DEMON_PIVOT_H` | macro | `payloads/Demon/include/core/Pivot.h:2` | `#define DEMON_PIVOT_H` |
| `DemonID` | type_alias | `payloads/Demon/include/core/Pivot.h:7` | `typedef struct _PIVOT_DATA { UINT32 DemonID;` |
| `MAX_SMB_PACKETS_PER_LOOP` | macro | `payloads/Demon/include/core/Pivot.h:6` | `#define MAX_SMB_PACKETS_PER_LOOP` |
| `_PIVOT_DATA` | struct | `payloads/Demon/include/core/Pivot.h:8` | `` |
| `DEMON_PROCESS_H` | macro | `payloads/Demon/include/core/Process.h:2` | `#define DEMON_PROCESS_H` |
| `DEMON_RUNTIME_H` | macro | `payloads/Demon/include/core/Runtime.h:2` | `#define DEMON_RUNTIME_H` |
| `DEMON_SLEEPOBF_H` | macro | `payloads/Demon/include/core/SleepObf.h:3` | `#define DEMON_SLEEPOBF_H` |
| `OBF_JMP` | macro | `payloads/Demon/include/core/SleepObf.h:16` | `#define OBF_JMP( i, p )` |
| `SLEEPOBF_BYPASS_JMPRAX` | macro | `payloads/Demon/include/core/SleepObf.h:13` | `#define SLEEPOBF_BYPASS_JMPRAX` |
| `SLEEPOBF_BYPASS_JMPRBX` | macro | `payloads/Demon/include/core/SleepObf.h:14` | `#define SLEEPOBF_BYPASS_JMPRBX` |
| `SLEEPOBF_BYPASS_NONE` | macro | `payloads/Demon/include/core/SleepObf.h:12` | `#define SLEEPOBF_BYPASS_NONE` |
| `SLEEPOBF_EKKO` | macro | `payloads/Demon/include/core/SleepObf.h:8` | `#define SLEEPOBF_EKKO` |
| `SLEEPOBF_FOLIAGE` | macro | `payloads/Demon/include/core/SleepObf.h:10` | `#define SLEEPOBF_FOLIAGE` |
| `SLEEPOBF_NO_OBF` | macro | `payloads/Demon/include/core/SleepObf.h:7` | `#define SLEEPOBF_NO_OBF` |
| `SLEEPOBF_ZILEAN` | macro | `payloads/Demon/include/core/SleepObf.h:9` | `#define SLEEPOBF_ZILEAN` |
| `TimeOut` | type_alias | `payloads/Demon/include/core/SleepObf.h:31` | `typedef struct _SLEEP_PARAM { UINT32 TimeOut;` |
| `USTRING` | struct | `payloads/Demon/include/core/SleepObf.h:25` | `` |
| `_SLEEP_PARAM` | struct | `payloads/Demon/include/core/SleepObf.h:32` | `` |
| `HTTP` | function | `payloads/Demon/include/core/Socket.h:66` | `* This is needed for Socks5 and HTTP(S) agents. * @return TRUE or FALSE */ BOOL InitWSA( VOID );` |
| `ID` | type_alias | `payloads/Demon/include/core/Socket.h:38` | `typedef struct _SOCKET_DATA { DWORD ID;` |
| `SOCKET_COMMAND_CLOSE` | macro | `payloads/Demon/include/core/Socket.h:22` | `#define SOCKET_COMMAND_CLOSE` |
| `SOCKET_COMMAND_CONNECT` | macro | `payloads/Demon/include/core/Socket.h:23` | `#define SOCKET_COMMAND_CONNECT` |
| `SOCKET_COMMAND_OPEN` | macro | `payloads/Demon/include/core/Socket.h:19` | `#define SOCKET_COMMAND_OPEN` |
| `SOCKET_COMMAND_READ` | macro | `payloads/Demon/include/core/Socket.h:20` | `#define SOCKET_COMMAND_READ` |
| `SOCKET_COMMAND_RPORTFWD_ADD` | macro | `payloads/Demon/include/core/Socket.h:8` | `#define SOCKET_COMMAND_RPORTFWD_ADD` |
| `SOCKET_COMMAND_RPORTFWD_ADDLCL` | macro | `payloads/Demon/include/core/Socket.h:9` | `#define SOCKET_COMMAND_RPORTFWD_ADDLCL` |
| `SOCKET_COMMAND_RPORTFWD_CLEAR` | macro | `payloads/Demon/include/core/Socket.h:11` | `#define SOCKET_COMMAND_RPORTFWD_CLEAR` |
| `SOCKET_COMMAND_RPORTFWD_LIST` | macro | `payloads/Demon/include/core/Socket.h:10` | `#define SOCKET_COMMAND_RPORTFWD_LIST` |
| `SOCKET_COMMAND_RPORTFWD_REMOVE` | macro | `payloads/Demon/include/core/Socket.h:12` | `#define SOCKET_COMMAND_RPORTFWD_REMOVE` |
| `SOCKET_COMMAND_SOCKSPROXY_ADD` | macro | `payloads/Demon/include/core/Socket.h:14` | `#define SOCKET_COMMAND_SOCKSPROXY_ADD` |
| `SOCKET_COMMAND_SOCKSPROXY_CLEAR` | macro | `payloads/Demon/include/core/Socket.h:17` | `#define SOCKET_COMMAND_SOCKSPROXY_CLEAR` |
| `SOCKET_COMMAND_SOCKSPROXY_LIST` | macro | `payloads/Demon/include/core/Socket.h:15` | `#define SOCKET_COMMAND_SOCKSPROXY_LIST` |
| `SOCKET_COMMAND_SOCKSPROXY_REMOVE` | macro | `payloads/Demon/include/core/Socket.h:16` | `#define SOCKET_COMMAND_SOCKSPROXY_REMOVE` |
| `SOCKET_COMMAND_WRITE` | macro | `payloads/Demon/include/core/Socket.h:21` | `#define SOCKET_COMMAND_WRITE` |
| `SOCKET_ERROR_ALREADY_BOUND` | macro | `payloads/Demon/include/core/Socket.h:26` | `#define SOCKET_ERROR_ALREADY_BOUND` |
| `SOCKET_TYPE_CLIENT` | macro | `payloads/Demon/include/core/Socket.h:6` | `#define SOCKET_TYPE_CLIENT` |
| `SOCKET_TYPE_NONE` | macro | `payloads/Demon/include/core/Socket.h:3` | `#define SOCKET_TYPE_NONE` |
| `SOCKET_TYPE_REVERSE_PORTFWD` | macro | `payloads/Demon/include/core/Socket.h:4` | `#define SOCKET_TYPE_REVERSE_PORTFWD` |
| `SOCKET_TYPE_REVERSE_PROXY` | macro | `payloads/Demon/include/core/Socket.h:5` | `#define SOCKET_TYPE_REVERSE_PROXY` |
| `_SOCKET_DATA` | struct | `payloads/Demon/include/core/Socket.h:39` | `` |
| `sin6_family` | type_alias | `payloads/Demon/include/core/Socket.h:27` | `typedef struct sockaddr_in6 { ADDRESS_FAMILY sin6_family;` |
| `sockaddr_in6` | struct | `payloads/Demon/include/core/Socket.h:28` | `` |
| `DEMON_SPOOF_H` | macro | `payloads/Demon/include/core/Spoof.h:2` | `#define DEMON_SPOOF_H` |
| `SETUP_ARGS` | macro | `payloads/Demon/include/core/Spoof.h:28` | `#define SETUP_ARGS(arg1, arg2, arg3, arg4, arg5, arg6, arg7, arg8, arg9, arg10, arg11, arg12, ...)` |
| `SPOOF_A` | macro | `payloads/Demon/include/core/Spoof.h:20` | `#define SPOOF_A( function, module, size, a )` |
| `SPOOF_B` | macro | `payloads/Demon/include/core/Spoof.h:21` | `#define SPOOF_B( function, module, size, a, b )` |
| `SPOOF_C` | macro | `payloads/Demon/include/core/Spoof.h:22` | `#define SPOOF_C( function, module, size, a, b, c )` |
| `SPOOF_D` | macro | `payloads/Demon/include/core/Spoof.h:23` | `#define SPOOF_D( function, module, size, a, b, c, d )` |
| `SPOOF_E` | macro | `payloads/Demon/include/core/Spoof.h:24` | `#define SPOOF_E( function, module, size, a, b, c, d, e )` |
| `SPOOF_F` | macro | `payloads/Demon/include/core/Spoof.h:25` | `#define SPOOF_F( function, module, size, a, b, c, d, e, f )` |
| `SPOOF_G` | macro | `payloads/Demon/include/core/Spoof.h:26` | `#define SPOOF_G( function, module, size, a, b, c, d, e, f, g )` |
| `SPOOF_H` | macro | `payloads/Demon/include/core/Spoof.h:27` | `#define SPOOF_H( function, module, size, a, b, c, d, e, f, g, h )` |
| `SPOOF_MACRO_CHOOSER` | macro | `payloads/Demon/include/core/Spoof.h:29` | `#define SPOOF_MACRO_CHOOSER(...)` |
| `SPOOF_X` | macro | `payloads/Demon/include/core/Spoof.h:19` | `#define SPOOF_X( function, module, size )` |
| `Spoof` | function | `payloads/Demon/include/core/Spoof.h:17` | `static ULONG_PTR Spoof();` |
| `SpoofFunc` | macro | `payloads/Demon/include/core/Spoof.h:30` | `#define SpoofFunc(...)` |
| `DEMON_SYSNATIVE_H` | macro | `payloads/Demon/include/core/SysNative.h:2` | `#define DEMON_SYSNATIVE_H` |
| `OPT` | macro | `payloads/Demon/include/core/SysNative.h:9` | `#define OPT` |
| `SYSCALL_INVOKE` | macro | `payloads/Demon/include/core/SysNative.h:12` | `#define SYSCALL_INVOKE( SYS_NAME, ... )` |
| `Adr` | type_alias | `payloads/Demon/include/core/Syscalls.h:31` | `typedef struct _SYS_CONFIG { PVOID Adr;` |
| `DEMON_SYSCALLS_H` | macro | `payloads/Demon/include/core/Syscalls.h:3` | `#define DEMON_SYSCALLS_H` |
| `SSN_OFFSET_1` | macro | `payloads/Demon/include/core/Syscalls.h:13` | `#define SSN_OFFSET_1` |
| `SSN_OFFSET_1` | macro | `payloads/Demon/include/core/Syscalls.h:17` | `#define SSN_OFFSET_1` |
| `SSN_OFFSET_2` | macro | `payloads/Demon/include/core/Syscalls.h:14` | `#define SSN_OFFSET_2` |
| `SSN_OFFSET_2` | macro | `payloads/Demon/include/core/Syscalls.h:18` | `#define SSN_OFFSET_2` |
| `SYSCALL_ASM` | macro | `payloads/Demon/include/core/Syscalls.h:12` | `#define SYSCALL_ASM` |
| `SYSCALL_ASM` | macro | `payloads/Demon/include/core/Syscalls.h:16` | `#define SYSCALL_ASM` |
| `SYS_ASM_RET` | macro | `payloads/Demon/include/core/Syscalls.h:9` | `#define SYS_ASM_RET` |
| `SYS_EXTRACT` | macro | `payloads/Demon/include/core/Syscalls.h:21` | `#define SYS_EXTRACT( NtName )` |
| `SYS_RANGE` | macro | `payloads/Demon/include/core/Syscalls.h:10` | `#define SYS_RANGE` |
| `_SYS_CONFIG` | struct | `payloads/Demon/include/core/Syscalls.h:32` | `` |
| `DEMON_THREAD_H` | macro | `payloads/Demon/include/core/Thread.h:2` | `#define DEMON_THREAD_H` |
| `THREAD_METHOD_CREATEREMOTETHREAD` | macro | `payloads/Demon/include/core/Thread.h:9` | `#define THREAD_METHOD_CREATEREMOTETHREAD` |
| `THREAD_METHOD_DEFAULT` | macro | `payloads/Demon/include/core/Thread.h:8` | `#define THREAD_METHOD_DEFAULT` |
| `THREAD_METHOD_NTCREATEHREADEX` | macro | `payloads/Demon/include/core/Thread.h:10` | `#define THREAD_METHOD_NTCREATEHREADEX` |
| `THREAD_METHOD_NTQUEUEAPCTHREAD` | macro | `payloads/Demon/include/core/Thread.h:11` | `#define THREAD_METHOD_NTQUEUEAPCTHREAD` |
| `_WOW64CONTEXT` | struct | `payloads/Demon/include/core/Thread.h:25` | `` |
| `hProcess` | type_alias | `payloads/Demon/include/core/Thread.h:25` | `typedef struct _WOW64CONTEXT { union { HANDLE hProcess;` |
| `ALIGN_UP` | macro | `payloads/Demon/include/core/Token.h:25` | `#define ALIGN_UP(Address, Type)` |
| `ALIGN_UP_TYPE` | macro | `payloads/Demon/include/core/Token.h:21` | `#define ALIGN_UP_TYPE(Address, Align)` |
| `BUF_SIZE` | macro | `payloads/Demon/include/core/Token.h:15` | `#define BUF_SIZE` |
| `Count` | type_alias | `payloads/Demon/include/core/Token.h:36` | `typedef struct _PROCESS_LIST { ULONG Count;` |
| `DEMON_TOKEN_H` | macro | `payloads/Demon/include/core/Token.h:2` | `#define DEMON_TOKEN_H` |
| `Handle` | type_alias | `payloads/Demon/include/core/Token.h:80` | `typedef struct _TOKEN_LIST_DATA { HANDLE Handle;` |
| `MAX_PROCESSES` | macro | `payloads/Demon/include/core/Token.h:14` | `#define MAX_PROCESSES` |
| `MAX_USERNAME` | macro | `payloads/Demon/include/core/Token.h:16` | `#define MAX_USERNAME` |
| `OBJECT_TYPES_FIRST_ENTRY` | macro | `payloads/Demon/include/core/Token.h:30` | `#define OBJECT_TYPES_FIRST_ENTRY(ObjectTypes)` |
| `OBJECT_TYPES_NEXT_ENTRY` | macro | `payloads/Demon/include/core/Token.h:33` | `#define OBJECT_TYPES_NEXT_ENTRY(ObjectType)` |
| `ObjectTypesInformation` | macro | `payloads/Demon/include/core/Token.h:28` | `#define ObjectTypesInformation` |
| `RtlOffsetToPointer` | macro | `payloads/Demon/include/core/Token.h:18` | `#define RtlOffsetToPointer(B,O)` |
| `SEC_IMP_LEVEL` | type_alias | `payloads/Demon/include/core/Token.h:94` | `typedef SECURITY_IMPERSONATION_LEVEL SEC_IMP_LEVEL;` |
| `TOKEN_OWNER_FLAG_DEFAULT` | macro | `payloads/Demon/include/core/Token.h:10` | `#define TOKEN_OWNER_FLAG_DEFAULT` |
| `TOKEN_OWNER_FLAG_DOMAIN` | macro | `payloads/Demon/include/core/Token.h:12` | `#define TOKEN_OWNER_FLAG_DOMAIN` |
| `TOKEN_OWNER_FLAG_USER` | macro | `payloads/Demon/include/core/Token.h:11` | `#define TOKEN_OWNER_FLAG_USER` |
| `TOKEN_TYPE_MAKE_NETWORK` | macro | `payloads/Demon/include/core/Token.h:8` | `#define TOKEN_TYPE_MAKE_NETWORK` |
| `TOKEN_TYPE_STOLEN` | macro | `payloads/Demon/include/core/Token.h:7` | `#define TOKEN_TYPE_STOLEN` |
| `TypeName` | type_alias | `payloads/Demon/include/core/Token.h:52` | `typedef struct _OBJECT_TYPE_INFORMATION_V2 { UNICODE_STRING TypeName;` |
| `_OBJECT_TYPE_INFORMATION_V2` | struct | `payloads/Demon/include/core/Token.h:53` | `` |
| `_PROCESS_LIST` | struct | `payloads/Demon/include/core/Token.h:37` | `` |
| `_TOKEN_LIST_DATA` | struct | `payloads/Demon/include/core/Token.h:80` | `` |
| `_USER_TOKEN_DATA` | struct | `payloads/Demon/include/core/Token.h:43` | `` |
| `username` | type_alias | `payloads/Demon/include/core/Token.h:42` | `typedef struct _USER_TOKEN_DATA { WCHAR username[MAX_USERNAME];` |
| `DEMON_INTERNET_H` | macro | `payloads/Demon/include/core/Transport.h:2` | `#define DEMON_INTERNET_H` |
| `PIPE_BUFFER_MAX` | macro | `payloads/Demon/include/core/Transport.h:8` | `#define PIPE_BUFFER_MAX` |
| `DEMON_TRANSPORTHTTP_H` | macro | `payloads/Demon/include/core/TransportHttp.h:2` | `#define DEMON_TRANSPORTHTTP_H` |
| `ERROR_INTERNET_CANNOT_CONNECT` | macro | `payloads/Demon/include/core/TransportHttp.h:13` | `#define ERROR_INTERNET_CANNOT_CONNECT` |
| `Host` | type_alias | `payloads/Demon/include/core/TransportHttp.h:14` | `typedef struct _HOST_DATA { /* Host Data */ LPWSTR Host;` |
| `TRANSPORT_HTTP_ROTATION_RANDOM` | macro | `payloads/Demon/include/core/TransportHttp.h:12` | `#define TRANSPORT_HTTP_ROTATION_RANDOM` |
| `TRANSPORT_HTTP_ROTATION_ROUND_ROBIN` | macro | `payloads/Demon/include/core/TransportHttp.h:11` | `#define TRANSPORT_HTTP_ROTATION_ROUND_ROBIN` |
| `_HOST_DATA` | struct | `payloads/Demon/include/core/TransportHttp.h:15` | `` |
| `DEMON_TRANSPORTSMB_H` | macro | `payloads/Demon/include/core/TransportSmb.h:2` | `#define DEMON_TRANSPORTSMB_H` |
| `Attribute` | type_alias | `payloads/Demon/include/core/Win32.h:92` | `typedef struct _PROC_THREAD_ATTRIBUTE_ENTRY { ULONG_PTR Attribute;` |
| `Buffer` | type_alias | `payloads/Demon/include/core/Win32.h:63` | `typedef struct _BUFFER { PVOID Buffer;` |
| `DEMON_WIN32_H` | macro | `payloads/Demon/include/core/Win32.h:2` | `#define DEMON_WIN32_H` |
| `DEREF` | macro | `payloads/Demon/include/core/Win32.h:21` | `#define DEREF( name )` |
| `DEREF_16` | macro | `payloads/Demon/include/core/Win32.h:23` | `#define DEREF_16( name )` |
| `DEREF_32` | macro | `payloads/Demon/include/core/Win32.h:22` | `#define DEREF_32( name )` |
| `ExtendedProcessInfo` | type_alias | `payloads/Demon/include/core/Win32.h:100` | `typedef struct __attribute__((packed)) { ULONG ExtendedProcessInfo;` |
| `FileName` | type_alias | `payloads/Demon/include/core/Win32.h:27` | `typedef struct _DIR_OR_FILE { WCHAR FileName[MAX_PATH+1];` |
| `HASH_KEY` | macro | `payloads/Demon/include/core/Win32.h:18` | `#define HASH_KEY` |
| `Length` | type_alias | `payloads/Demon/include/core/Win32.h:106` | `typedef struct _PROC_THREAD_ATTRIBUTE_LIST { ULONG_PTR Length;` |
| `MAX` | macro | `payloads/Demon/include/core/Win32.h:25` | `#define MAX( a, b )` |
| `MIN` | macro | `payloads/Demon/include/core/Win32.h:26` | `#define MIN( a, b )` |
| `OBJ_ATTR` | type_alias | `payloads/Demon/include/core/Win32.h:115` | `typedef OBJECT_ATTRIBUTES OBJ_ATTR;` |
| `OBJ_ATTR` | type_alias | `payloads/Demon/include/core/Win32.h:116` | `typedef OBJECT_ATTRIBUTES OBJ_ATTR;` |
| `PROC_INFO` | type_alias | `payloads/Demon/include/core/Win32.h:118` | `typedef PROCESS_INFORMATION PROC_INFO;` |
| `PSYS_PROC_INFO` | type_alias | `payloads/Demon/include/core/Win32.h:112` | `typedef PSYSTEM_PROCESS_INFORMATION PSYS_PROC_INFO;` |
| `Path` | type_alias | `payloads/Demon/include/core/Win32.h:38` | `typedef struct _SUB_DIR { WCHAR Path[MAX_PATH+1];` |
| `Path` | type_alias | `payloads/Demon/include/core/Win32.h:45` | `typedef struct _ROOT_DIR { WCHAR Path[MAX_PATH+1];` |
| `SEC_QUALITY_SERVICE` | type_alias | `payloads/Demon/include/core/Win32.h:114` | `typedef SECURITY_QUALITY_OF_SERVICE SEC_QUALITY_SERVICE;` |
| `StdOutRead` | type_alias | `payloads/Demon/include/core/Win32.h:69` | `typedef struct _ANONPIPE { HANDLE StdOutRead;` |
| `THD_ATTR_LIST` | type_alias | `payloads/Demon/include/core/Win32.h:117` | `typedef PROC_THREAD_ATTRIBUTE_LIST THD_ATTR_LIST;` |
| `THREAD_TEB_INFORMATION` | struct | `payloads/Demon/include/core/Win32.h:57` | `` |
| `WIN_FUNC` | macro | `payloads/Demon/include/core/Win32.h:19` | `#define WIN_FUNC(x)` |
| `_ANONPIPE` | struct | `payloads/Demon/include/core/Win32.h:70` | `` |
| `_BUFFER` | struct | `payloads/Demon/include/core/Win32.h:64` | `` |
| `_DIR_OR_FILE` | struct | `payloads/Demon/include/core/Win32.h:28` | `` |
| `_PROC_THREAD_ATTRIBUTE_ENTRY` | struct | `payloads/Demon/include/core/Win32.h:93` | `` |
| `_PROC_THREAD_ATTRIBUTE_LIST` | struct | `payloads/Demon/include/core/Win32.h:107` | `` |
| `_PS_ATTRIBUTE_NUM` | enum | `payloads/Demon/include/core/Win32.h:76` | `` |
| `_ROOT_DIR` | struct | `payloads/Demon/include/core/Win32.h:46` | `` |
| `_SUB_DIR` | struct | `payloads/Demon/include/core/Win32.h:39` | `` |
| `__attribute__` | function | `payloads/Demon/include/core/Win32.h:101` | `typedef struct __attribute__((packed))` |
| `AES256` | macro | `payloads/Demon/include/crypt/AesCrypt.h:7` | `#define AES256` |
| `AES_BLOCKLEN` | macro | `payloads/Demon/include/crypt/AesCrypt.h:13` | `#define AES_BLOCKLEN` |
| `AES_KEYLEN` | macro | `payloads/Demon/include/crypt/AesCrypt.h:14` | `#define AES_KEYLEN` |
| `AES_keyExpSize` | macro | `payloads/Demon/include/crypt/AesCrypt.h:15` | `#define AES_keyExpSize` |
| `AesInit` | function | `payloads/Demon/include/crypt/AesCrypt.h:22` | `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv);` |
| `AesXCryptBuffer` | function | `payloads/Demon/include/crypt/AesCrypt.h:23` | `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length);` |
| `CTR` | macro | `payloads/Demon/include/crypt/AesCrypt.h:6` | `#define CTR` |
| `CTR` | macro | `payloads/Demon/include/crypt/AesCrypt.h:10` | `#define CTR` |
| `_AES_H_` | macro | `payloads/Demon/include/crypt/AesCrypt.h:2` | `#define _AES_H_` |
| `DEMON_BASEINJECT_H` | macro | `payloads/Demon/include/inject/Inject.h:3` | `#define DEMON_BASEINJECT_H` |
| `INJECTION_CTX` | struct | `payloads/Demon/include/inject/Inject.h:31` | `` |
| `INJECTION_TECHNIQUE_APC` | macro | `payloads/Demon/include/inject/Inject.h:12` | `#define INJECTION_TECHNIQUE_APC` |
| `INJECTION_TECHNIQUE_DEFAULT` | macro | `payloads/Demon/include/inject/Inject.h:19` | `#define INJECTION_TECHNIQUE_DEFAULT` |
| `INJECTION_TECHNIQUE_SYSCALL` | macro | `payloads/Demon/include/inject/Inject.h:11` | `#define INJECTION_TECHNIQUE_SYSCALL` |
| `INJECTION_TECHNIQUE_WIN32` | macro | `payloads/Demon/include/inject/Inject.h:10` | `#define INJECTION_TECHNIQUE_WIN32` |
| `INJECT_ERROR_FAILED` | macro | `payloads/Demon/include/inject/Inject.h:49` | `#define INJECT_ERROR_FAILED` |
| `INJECT_ERROR_INVALID_PARAM` | macro | `payloads/Demon/include/inject/Inject.h:50` | `#define INJECT_ERROR_INVALID_PARAM` |
| `INJECT_ERROR_PROCESS_ARCH_MISMATCH` | macro | `payloads/Demon/include/inject/Inject.h:51` | `#define INJECT_ERROR_PROCESS_ARCH_MISMATCH` |
| `INJECT_ERROR_SUCCESS` | macro | `payloads/Demon/include/inject/Inject.h:48` | `#define INJECT_ERROR_SUCCESS` |
| `INJECT_WAY_EXECUTE` | macro | `payloads/Demon/include/inject/Inject.h:55` | `#define INJECT_WAY_EXECUTE` |
| `INJECT_WAY_INJECT` | macro | `payloads/Demon/include/inject/Inject.h:54` | `#define INJECT_WAY_INJECT` |
| `INJECT_WAY_SPAWN` | macro | `payloads/Demon/include/inject/Inject.h:53` | `#define INJECT_WAY_SPAWN` |
| `SPAWN_TECHNIQUE_APC` | macro | `payloads/Demon/include/inject/Inject.h:15` | `#define SPAWN_TECHNIQUE_APC` |
| `SPAWN_TECHNIQUE_DEFAULT` | macro | `payloads/Demon/include/inject/Inject.h:18` | `#define SPAWN_TECHNIQUE_DEFAULT` |
| `SPAWN_TECHNIQUE_SYSCALL` | macro | `payloads/Demon/include/inject/Inject.h:14` | `#define SPAWN_TECHNIQUE_SYSCALL` |
| `_DX_CREATE_THREAD` | enum | `payloads/Demon/include/inject/Inject.h:21` | `` |
| `hProcess` | type_alias | `payloads/Demon/include/inject/Inject.h:30` | `typedef struct INJECTION_CTX { HANDLE hProcess;` |
| `DEMON_INJECTUTIL_H` | macro | `payloads/Demon/include/inject/InjectUtil.h:2` | `#define DEMON_INJECTUTIL_H` |
| `DEREF_16` | macro | `payloads/Demon/include/inject/InjectUtil.h:8` | `#define DEREF_16( name )` |
| `DEREF_32` | macro | `payloads/Demon/include/inject/InjectUtil.h:7` | `#define DEREF_32( name )` |
| `ERROR_INJECT_FAILED_TO_SPAWN_TARGET_PROCESS` | macro | `payloads/Demon/include/inject/InjectUtil.h:27` | `#define ERROR_INJECT_FAILED_TO_SPAWN_TARGET_PROCESS` |
| `ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X64_TO_X86` | macro | `payloads/Demon/include/inject/InjectUtil.h:25` | `#define ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X64_TO_X86` |
| `ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X86_TO_X64` | macro | `payloads/Demon/include/inject/InjectUtil.h:26` | `#define ERROR_INJECT_PROC_PAYLOAD_ARCH_DONT_MATCH_X86_TO_X64` |
| `PROC_THREAD_ATTRIBUTE_ADDITIVE` | macro | `payloads/Demon/include/inject/InjectUtil.h:15` | `#define PROC_THREAD_ATTRIBUTE_ADDITIVE` |
| `PROC_THREAD_ATTRIBUTE_INPUT` | macro | `payloads/Demon/include/inject/InjectUtil.h:14` | `#define PROC_THREAD_ATTRIBUTE_INPUT` |
| `PROC_THREAD_ATTRIBUTE_NUMBER` | macro | `payloads/Demon/include/inject/InjectUtil.h:12` | `#define PROC_THREAD_ATTRIBUTE_NUMBER` |
| `PROC_THREAD_ATTRIBUTE_THREAD` | macro | `payloads/Demon/include/inject/InjectUtil.h:13` | `#define PROC_THREAD_ATTRIBUTE_THREAD` |
| `ProcThreadAttributeValue` | macro | `payloads/Demon/include/inject/InjectUtil.h:17` | `#define ProcThreadAttributeValue(Number, Thread, Input, Additive)` |
| `hash_coffapi` | function | `payloads/Demon/scripts/hash_func.py:18` | `def hash_coffapi(string)` |
| `hash_string` | function | `payloads/Demon/scripts/hash_func.py:7` | `def hash_string(string)` |
| `DemonInit` | function | `payloads/Demon/src/Demon.c:267` | `VOID DemonInit( PVOID ModuleInst, PKAYN_ARGS KArgs )` |
| `DemonMain` | function | `payloads/Demon/src/Demon.c:34` | `VOID DemonMain( PVOID ModuleInst, PKAYN_ARGS KArgs )` |
| `DemonMetaData` | function | `payloads/Demon/src/Demon.c:95` | `VOID DemonMetaData( PPACKAGE* MetaData, BOOL Header )` |
| `DemonRoutine` | function | `payloads/Demon/src/Demon.c:64` | `_Noreturn
VOID DemonRoutine()` |
| `PRINTF` | function | `payloads/Demon/src/Demon.c:570` | `PRINTF( "Instance DemonID => %x\n", Instance->Session.AgentID )
}

VOID DemonConfig()` |
| `PRINTF` | function | `payloads/Demon/src/Demon.c:645` | `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...` |
| `PRINTF` | function | `payloads/Demon/src/Demon.c:673` | `PRINTF( " - %ls:%ld\n", Buffer, Temp )

        /* if our host address is longer than 0 then lets...` |
| `PRINTF` | function | `payloads/Demon/src/Demon.c:775` | `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...` |
| `PUTS` | function | `payloads/Demon/src/Demon.c:290` | `PUTS( "TRANSPORT_HTTP" )
#endif

#ifdef TRANSPORT_SMB
    PUTS( "TRANSPORT_SMB" )
#endif


    /*...` |
| `Spoof` | function | `payloads/Demon/src/asm/Spoof.x64.asm:8` | `` |
| `fixup` | function | `payloads/Demon/src/asm/Spoof.x64.asm:22` | `` |
| `_Spoof` | function | `payloads/Demon/src/asm/Spoof.x86.asm:8` | `` |
| `COFF_INSTANCE` | macro | `payloads/Demon/src/core/CoffeeLdr.c:18` | `#define COFF_INSTANCE` |
| `COFF_INSTANCE` | macro | `payloads/Demon/src/core/CoffeeLdr.c:27` | `#define COFF_INSTANCE` |
| `COFF_PREP_BEACON` | macro | `payloads/Demon/src/core/CoffeeLdr.c:15` | `#define COFF_PREP_BEACON` |
| `COFF_PREP_BEACON` | macro | `payloads/Demon/src/core/CoffeeLdr.c:24` | `#define COFF_PREP_BEACON` |
| `COFF_PREP_BEACON_SIZE` | macro | `payloads/Demon/src/core/CoffeeLdr.c:16` | `#define COFF_PREP_BEACON_SIZE` |
| `COFF_PREP_BEACON_SIZE` | macro | `payloads/Demon/src/core/CoffeeLdr.c:25` | `#define COFF_PREP_BEACON_SIZE` |
| `COFF_PREP_SYMBOL` | macro | `payloads/Demon/src/core/CoffeeLdr.c:12` | `#define COFF_PREP_SYMBOL` |
| `COFF_PREP_SYMBOL` | macro | `payloads/Demon/src/core/CoffeeLdr.c:21` | `#define COFF_PREP_SYMBOL` |
| `COFF_PREP_SYMBOL_SIZE` | macro | `payloads/Demon/src/core/CoffeeLdr.c:13` | `#define COFF_PREP_SYMBOL_SIZE` |
| `COFF_PREP_SYMBOL_SIZE` | macro | `payloads/Demon/src/core/CoffeeLdr.c:22` | `#define COFF_PREP_SYMBOL_SIZE` |
| `CoffeeCleanup` | function | `payloads/Demon/src/core/CoffeeLdr.c:394` | `VOID CoffeeCleanup( PCOFFEE Coffee )` |
| `CoffeeFunction` | function | `payloads/Demon/src/core/CoffeeLdr.c:242` | `VOID CoffeeFunction( PVOID Address, PVOID Argument, SIZE_T Size )` |
| `CoffeeGetFunMapSize` | function | `payloads/Demon/src/core/CoffeeLdr.c:602` | `SIZE_T CoffeeGetFunMapSize( PCOFFEE Coffee )` |
| `CoffeeProcessSections` | function | `payloads/Demon/src/core/CoffeeLdr.c:423` | `BOOL CoffeeProcessSections( PCOFFEE Coffee )` |
| `CoffeeProcessSymbol` | function | `payloads/Demon/src/core/CoffeeLdr.c:87` | `BOOL CoffeeProcessSymbol( PCOFFEE Coffee, LPSTR SymbolName, UINT16 SymbolType, PVOID* pFuncAddr )` |
| `CoffeeRunner` | function | `payloads/Demon/src/core/CoffeeLdr.c:821` | `VOID CoffeeRunner( PCHAR EntryName, DWORD EntryNameSize, PVOID CoffeeData, SIZE_T CoffeeDataSize,...` |
| `CoffeeRunnerThread` | function | `payloads/Demon/src/core/CoffeeLdr.c:799` | `VOID CoffeeRunnerThread( PCOFFEE_PARAMS Param )` |
| `PRINTF` | function | `payloads/Demon/src/core/CoffeeLdr.c:678` | `PRINTF( "[EntryName: %s] [CoffeeData: %p] [ArgData: %p] [ArgSize: %ld]\n", EntryName, CoffeeData,...` |
| `PUTS` | function | `payloads/Demon/src/core/CoffeeLdr.c:251` | `PUTS( "Finished" )
}

BOOL CoffeeExecuteFunction( PCOFFEE Coffee, PCHAR Function, PVOID Argument,...` |
| `PUTS` | function | `payloads/Demon/src/core/CoffeeLdr.c:669` | `PUTS( "Coffe entry was not found" )
}

VOID CoffeeLdr( PCHAR EntryName, PVOID CoffeeData, PVOID A...` |
| `RemoveCoffeeFromInstance` | function | `payloads/Demon/src/core/CoffeeLdr.c:642` | `VOID RemoveCoffeeFromInstance( PCOFFEE Coffee )` |
| `SymbolIncludesLibrary` | function | `payloads/Demon/src/core/CoffeeLdr.c:64` | `BOOL SymbolIncludesLibrary( LPSTR Symbol )` |
| `SymbolIsImport` | function | `payloads/Demon/src/core/CoffeeLdr.c:81` | `BOOL SymbolIsImport( LPSTR Symbol )` |
| `VehDebugger` | function | `payloads/Demon/src/core/CoffeeLdr.c:32` | `LONG WINAPI VehDebugger( PEXCEPTION_POINTERS Exception )` |
| `CommandAssemblyInlineExecute` | function | `payloads/Demon/src/core/Command.c:1708` | `VOID CommandAssemblyInlineExecute( PPARSER Parser )` |
| `CommandConfig` | function | `payloads/Demon/src/core/Command.c:1865` | `VOID CommandConfig( PPARSER Parser )` |
| `CommandDispatcher` | function | `payloads/Demon/src/core/Command.c:48` | `VOID CommandDispatcher( VOID )` |
| `CommandExit` | function | `payloads/Demon/src/core/Command.c:3315` | `VOID CommandExit( PPARSER Parser )` |
| `CommandInjectDLL` | function | `payloads/Demon/src/core/Command.c:1203` | `VOID CommandInjectDLL( PPARSER Parser )` |
| `CommandInjectShellcode` | function | `payloads/Demon/src/core/Command.c:1266` | `VOID CommandInjectShellcode(
    IN PPARSER Parser
)` |
| `CommandInlineExecute` | function | `payloads/Demon/src/core/Command.c:1114` | `VOID CommandInlineExecute( PPARSER Parser )` |
| `CommandJob` | function | `payloads/Demon/src/core/Command.c:188` | `VOID CommandJob( PPARSER Parser )` |
| `CommandKerberos` | function | `payloads/Demon/src/core/Command.c:3077` | `VOID CommandKerberos(
    IN PPARSER Parser
)` |
| `CommandMemFile` | function | `payloads/Demon/src/core/Command.c:3237` | `VOID CommandMemFile( PPARSER Parser )` |
| `CommandNet` | function | `payloads/Demon/src/core/Command.c:2109` | `VOID CommandNet( PPARSER Parser )` |
| `CommandPivot` | function | `payloads/Demon/src/core/Command.c:2463` | `VOID CommandPivot( PPARSER Parser )` |
| `CommandProc` | function | `payloads/Demon/src/core/Command.c:263` | `VOID CommandProc( PPARSER Parser )` |
| `CommandProcList` | function | `payloads/Demon/src/core/Command.c:562` | `VOID CommandProcList(
    IN PPARSER Parser
)` |
| `CommandScreenshot` | function | `payloads/Demon/src/core/Command.c:2084` | `VOID CommandScreenshot( PPARSER Parser )` |
| `CommandSleep` | function | `payloads/Demon/src/core/Command.c:174` | `VOID CommandSleep( PPARSER Parser )` |
| `CommandSocket` | function | `payloads/Demon/src/core/Command.c:2739` | `VOID CommandSocket( PPARSER Parser )` |
| `CommandSpawnDLL` | function | `payloads/Demon/src/core/Command.c:1247` | `VOID CommandSpawnDLL( PPARSER Parser )` |
| `CommandToken` | function | `payloads/Demon/src/core/Command.c:1373` | `VOID CommandToken( PPARSER Parser )` |
| `CommandTransfer` | function | `payloads/Demon/src/core/Command.c:2608` | `VOID CommandTransfer( PPARSER Parser )` |
| `Data` | function | `payloads/Demon/src/core/Command.c:844` | `* * Data (Open): * [ File Size ] * [ File Name ] * * Data (Write) * [ Chunk Data ] Size + FileChunk * * Data (Close): * ` |
| `InWorkingHours` | function | `payloads/Demon/src/core/Command.c:3263` | `BOOL InWorkingHours( )` |
| `KillDate` | function | `payloads/Demon/src/core/Command.c:3300` | `VOID KillDate( )` |
| `PACKAGE_ERROR_NTSTATUS` | function | `payloads/Demon/src/core/Command.c:671` | `PACKAGE_ERROR_NTSTATUS( NtStatus )
    }
}

VOID CommandFS( PPARSER Parser )` |
| `PRINTF` | function | `payloads/Demon/src/core/Command.c:107` | `PRINTF( "Task => RequestID:[%d : %x] CommandID:[%d : %x] TaskBuffer:[%x : %d]\n", RequestID, Requ...` |
| `PRINTF` | function | `payloads/Demon/src/core/Command.c:824` | `PRINTF( "FilePath.Buffer[%d]: %ls\n", PathSize, FilePath )

            if ( ! Instance->Win32.Ge...` |
| `PRINTF` | function | `payloads/Demon/src/core/Command.c:1293` | `PRINTF(
        "Injection Args:      \n"
        " - Way     : %d      \n"
        " - Method  :...` |
| `PRINTF` | function | `payloads/Demon/src/core/Command.c:1320` | `PRINTF( "Target spawn process: %ls\n", Spawn )

            /* create process */
            if (...` |
| `PRINTF` | function | `payloads/Demon/src/core/Command.c:1761` | `PRINTF(
            "Parsed Arguments:         \n"
            " - PipeName     [%d]: %ls \n"
   ...` |
| `PRINTF` | function | `payloads/Demon/src/core/Command.c:2997` | `PRINTF( "Socket ID: %x\n", ScId )

            /* check if address is not 0 */
            if ( I...` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:160` | `PUTS( "Out of while loop" )
}

VOID CommandCheckin( PPARSER Parser )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:272` | `case DEMON_COMMAND_PROC_MODULES: PUTS( "Proc::Modules" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:337` | `case DEMON_COMMAND_PROC_GREP: PUTS("Proc::Grep")` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:423` | `case DEMON_COMMAND_PROC_CREATE: PUTS( "Proc::Create" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:468` | `case DEMON_COMMAND_PROC_MEMORY: PUTS( "Proc::Memory" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:528` | `case DEMON_COMMAND_PROC_KILL: PUTS( "Proc::Kill" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:684` | `case DEMON_COMMAND_FS_DIR: PUTS( "FS::Dir" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:794` | `case DEMON_COMMAND_FS_DOWNLOAD: PUTS( "FS::Download" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:867` | `CleanupDownload:
            PUTS( "CleanupDownload" )

            if ( FileName.Buffer )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:882` | `case DEMON_COMMAND_FS_UPLOAD: PUTS( "FS::Upload" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:949` | `case DEMON_COMMAND_FS_CD: PUTS( "FS::Cd" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:964` | `case DEMON_COMMAND_FS_REMOVE: PUTS( "FS::Remove" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:994` | `case DEMON_COMMAND_FS_MKDIR: PUTS( "FS::Mkdir" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1010` | `case DEMON_COMMAND_FS_COPY: PUTS( "FS::Copy" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1035` | `case DEMON_COMMAND_FS_MOVE: PUTS( "FS::Move" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1060` | `case DEMON_COMMAND_FS_GET_PWD: PUTS( "FS::GetPwd" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1075` | `case DEMON_COMMAND_FS_CAT: PUTS( "FS::Cat" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1181` | `PUTS( "Use default (from config) CoffeeLdr" )

            if ( Instance->Config.Implant.CoffeeTh...` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1312` | `case INJECT_WAY_SPAWN: PUTS( "INJECT_WAY_SPAWN" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1353` | `case INJECT_WAY_INJECT: PUTS( "INJECT_WAY_INJECT" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1358` | `case INJECT_WAY_EXECUTE: PUTS( "INJECT_WAY_EXECUTE" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1383` | `case DEMON_COMMAND_TOKEN_IMPERSONATE: PUTS( "Token::Impersonate" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1406` | `case DEMON_COMMAND_TOKEN_STEAL: PUTS( "Token::Steal" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1450` | `case DEMON_COMMAND_TOKEN_LIST: PUTS( "Token::List" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1477` | `case DEMON_COMMAND_TOKEN_PRIVSGET_OR_LIST: PUTS( "Token::PrivsGetOrList" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1532` | `case DEMON_COMMAND_TOKEN_MAKE: PUTS( "Token::Make" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1595` | `case DEMON_COMMAND_TOKEN_GET_UID: PUTS( "Token::GetUID" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1635` | `case DEMON_COMMAND_TOKEN_REVERT: PUTS( "Token::Revert" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1650` | `case DEMON_COMMAND_TOKEN_REMOVE: PUTS( "Token::Remove" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1660` | `case DEMON_COMMAND_TOKEN_CLEAR: PUTS( "Token::Clear" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1668` | `case DEMON_COMMAND_TOKEN_FIND_TOKENS: PUTS( "Token::Find" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1788` | `PUTS( "Dotnet instance already running." )
    }
}

VOID CommandAssemblyListVersion( PPARSER Pars...` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:1841` | `else
        PUTS("Failed to load mscoree.dll")


    if ( pClrMetaHost )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2350` | `PUTS( "NetLocalGroupEnum => Success" )
                if ( GroupInfo )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2624` | `case DEMON_COMMAND_TRANSFER_LIST: PUTS( "Transfer::list" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2641` | `case DEMON_COMMAND_TRANSFER_STOP: PUTS( "Transfer::stop" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2668` | `case DEMON_COMMAND_TRANSFER_RESUME: PUTS( "Transfer::resume" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2696` | `case DEMON_COMMAND_TRANSFER_REMOVE: PUTS( "Transfer::remove" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2751` | `case SOCKET_COMMAND_RPORTFWD_ADD: PUTS( "Socket::RPortFwdAdd" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2786` | `case SOCKET_COMMAND_RPORTFWD_LIST: PUTS( "Socket::RPortFwdList" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2819` | `case SOCKET_COMMAND_RPORTFWD_REMOVE: PUTS( "Socket::RPortFwdRemove" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2850` | `case SOCKET_COMMAND_RPORTFWD_CLEAR: PUTS( "Socket::RPortFwdClear" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2871` | `case SOCKET_COMMAND_SOCKSPROXY_ADD: PUTS( "Socket::SocksProxyAdd" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2878` | `case SOCKET_COMMAND_WRITE: PUTS( "Socket::Write" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:2942` | `case SOCKET_COMMAND_CONNECT: PUTS( "Socket::Connect" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:3036` | `case SOCKET_COMMAND_CLOSE: PUTS( "Socket::Close" )` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:3090` | `case KERBEROS_COMMAND_LUID: PUTS("Kerberos::LUID")` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:3117` | `case KERBEROS_COMMAND_KLIST: PUTS("Kerberos::Klist")` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:3205` | `case KERBEROS_COMMAND_PURGE: PUTS("Kerberos::Purge")` |
| `PUTS` | function | `payloads/Demon/src/core/Command.c:3216` | `case KERBEROS_COMMAND_PTT: PUTS("Kerberos::Ptt")` |
| `ReachedKillDate` | function | `payloads/Demon/src/core/Command.c:3295` | `BOOL ReachedKillDate()` |
| `ClrCreateInstance` | function | `payloads/Demon/src/core/Dotnet.c:524` | `DWORD ClrCreateInstance( LPCWSTR dotNetVersion, PICLRMetaHost *ppClrMetaHost, PICLRRuntimeInfo *p...` |
| `DotnetClose` | function | `payloads/Demon/src/core/Dotnet.c:379` | `VOID DotnetClose()` |
| `DotnetExecute` | function | `payloads/Demon/src/core/Dotnet.c:19` | `BOOL DotnetExecute( BUFFER Assembly, BUFFER Arguments )` |
| `DotnetPush` | function | `payloads/Demon/src/core/Dotnet.c:347` | `VOID DotnetPush()` |
| `DotnetPushPipe` | function | `payloads/Demon/src/core/Dotnet.c:312` | `VOID DotnetPushPipe()` |
| `FindVersion` | function | `payloads/Demon/src/core/Dotnet.c:501` | `BOOL FindVersion( PVOID Assembly, DWORD length )` |
| `PIPE_BUFFER` | macro | `payloads/Demon/src/core/Dotnet.c:8` | `#define PIPE_BUFFER` |
| `PRINTF` | function | `payloads/Demon/src/core/Dotnet.c:169` | `PRINTF("SafeArrayUnaccessData Failed: %x\n", Result )
        PACKAGE_ERROR_WIN32
    }

    PUTS...` |
| `PRINTF` | function | `payloads/Demon/src/core/Dotnet.c:352` | `PRINTF( "Instance->Dotnet->Invoked: %s\n", Instance->Dotnet->Invoked ? "TRUE" : "FALSE" )
    if ...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:101` | `PUTS( "Init HwBp Engine" )
        /* use global engine */
        if ( ! NT_SUCCESS( HwBpEngineI...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:112` | `PUTS( "HwBp Engine add AmsiScanBuffer bypass" )
            if ( ! NT_SUCCESS( Status = HwBpEngin...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:120` | `PUTS( "HwBp Engine add NtTraceEvent bypass" )
        if ( ! NT_SUCCESS( HwBpEngineAdd( NULL, Thr...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:148` | `PUTS( "CreateDomain..." )
    if ( ( Result = Instance->Dotnet->ICorRuntimeHost->lpVtbl->CreateDo...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:154` | `PUTS( "QueryInterface..." )
    if ( ( Result = Instance->Dotnet->AppDomainThunk->lpVtbl->QueryIn...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:179` | `PUTS( "Assembly EntryPoint..." )
    if ( ( Result = Instance->Dotnet->Assembly->lpVtbl->EntryPoi...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:237` | `PUTS( "Creating events..." )
    if ( NT_SUCCESS( Instance->Win32.NtCreateEvent( &Instance->Dotne...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:286` | `PUTS( "Resume Thread..." )
                if ( NT_SUCCESS( Instance->Win32.NtAlertResumeThread( ...` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:428` | `PUTS( "Free Output" )
    if ( Instance->Dotnet->Output.Buffer )` |
| `PUTS` | function | `payloads/Demon/src/core/Dotnet.c:436` | `PUTS( "Unload and free CLR" )
    if ( Instance->Dotnet->MethodArgs )` |
| `DownloadAdd` | function | `payloads/Demon/src/core/Download.c:6` | `PDOWNLOAD_DATA DownloadAdd( HANDLE hFile, LONGLONG MaxSize )` |
| `DownloadFree` | function | `payloads/Demon/src/core/Download.c:41` | `VOID DownloadFree( PDOWNLOAD_DATA Download )` |
| `DownloadGet` | function | `payloads/Demon/src/core/Download.c:27` | `PDOWNLOAD_DATA DownloadGet( DWORD FileID )` |
| `DownloadPush` | function | `payloads/Demon/src/core/Download.c:94` | `VOID DownloadPush()` |
| `DownloadRemove` | function | `payloads/Demon/src/core/Download.c:56` | `BOOL DownloadRemove( DWORD FileID )` |
| `GetMemFile` | function | `payloads/Demon/src/core/Download.c:287` | `PMEM_FILE GetMemFile( ULONG32 ID )` |
| `MemFileFree` | function | `payloads/Demon/src/core/Download.c:339` | `VOID MemFileFree( PMEM_FILE MemFile )` |
| `MemFileIsNew` | function | `payloads/Demon/src/core/Download.c:238` | `BOOL MemFileIsNew( ULONG32 ID )` |
| `MemFileReadChunk` | function | `payloads/Demon/src/core/Download.c:318` | `PMEM_FILE MemFileReadChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )` |
| `NewMemFile` | function | `payloads/Demon/src/core/Download.c:254` | `PMEM_FILE NewMemFile( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )` |
| `PRINTF` | function | `payloads/Demon/src/core/Download.c:129` | `PRINTF( "Allocated memory for DownloadChunk. Buffer:[%p] Size:[%d]\n", Instance->DownloadChunk.Bu...` |
| `ProcessMemFileChunk` | function | `payloads/Demon/src/core/Download.c:302` | `PMEM_FILE ProcessMemFileChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )` |
| `RemoveMemFile` | function | `payloads/Demon/src/core/Download.c:355` | `BOOL RemoveMemFile( ULONG32 ID )` |
| `ExceptionHandler` | function | `payloads/Demon/src/core/HwBpEngine.c:320` | `LONG ExceptionHandler(
    _Inout_ PEXCEPTION_POINTERS Exception
)` |
| `HwBpEngineAdd` | function | `payloads/Demon/src/core/HwBpEngine.c:152` | `NTSTATUS HwBpEngineAdd(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID        ...` |
| `HwBpEngineDestroy` | function | `payloads/Demon/src/core/HwBpEngine.c:261` | `NTSTATUS HwBpEngineDestroy(
    IN PHWBP_ENGINE Engine
)` |
| `HwBpEngineInit` | function | `payloads/Demon/src/core/HwBpEngine.c:18` | `NTSTATUS HwBpEngineInit(
    OUT PHWBP_ENGINE Engine,
    IN  PVOID        Handler
)` |
| `HwBpEngineRemove` | function | `payloads/Demon/src/core/HwBpEngine.c:209` | `NTSTATUS HwBpEngineRemove(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID     ...` |
| `HwBpEngineSetBp` | function | `payloads/Demon/src/core/HwBpEngine.c:61` | `NTSTATUS HwBpEngineSetBp(
    IN DWORD Tid,
    IN PVOID Address,
    IN BYTE  Position,
    IN B...` |
| `PRINTF` | function | `payloads/Demon/src/core/HwBpEngine.c:116` | `PRINTF(
                "Dr Registers:  \n"
                "- Dr0[%d]: %p  \n"
                "...` |
| `PRINTF` | function | `payloads/Demon/src/core/HwBpEngine.c:162` | `PRINTF( "Engine:[%p] Tid:[%d] Address:[%p] Function:[%p] Position:[%d]\n", Engine, Tid, Address, ...` |
| `PRINTF` | function | `payloads/Demon/src/core/HwBpEngine.c:355` | `PRINTF( "Found exception handler: %s\n", Found ? "TRUE" : "FALSE" )
        if ( Found )` |
| `HwBpExAmsiScanBuffer` | function | `payloads/Demon/src/core/HwBpExceptions.c:6` | `VOID HwBpExAmsiScanBuffer(
    _Inout_ PEXCEPTION_POINTERS Exception
)` |
| `HwBpExNtTraceEvent` | function | `payloads/Demon/src/core/HwBpExceptions.c:23` | `VOID HwBpExNtTraceEvent(
    _Inout_ PEXCEPTION_POINTERS Exception
)` |
| `JobAdd` | function | `payloads/Demon/src/core/Jobs.c:17` | `VOID JobAdd( UINT32 RequestID, DWORD JobID, SHORT Type, SHORT State, HANDLE Handle, PVOID Data )` |
| `JobCheckList` | function | `payloads/Demon/src/core/Jobs.c:63` | `VOID JobCheckList()` |
| `JobKill` | function | `payloads/Demon/src/core/Jobs.c:277` | `BOOL JobKill( DWORD JobID )` |
| `JobRemove` | function | `payloads/Demon/src/core/Jobs.c:383` | `VOID JobRemove( DWORD JobID )` |
| `JobResume` | function | `payloads/Demon/src/core/Jobs.c:230` | `BOOL JobResume( DWORD JobID )` |
| `JobSuspend` | function | `payloads/Demon/src/core/Jobs.c:184` | `BOOL JobSuspend( DWORD JobID )` |
| `PRINTF` | function | `payloads/Demon/src/core/Jobs.c:192` | `PRINTF( "Found Job ID: %d", JobID )

            if ( JobList->Type == JOB_TYPE_THREAD )` |
| `PRINTF` | function | `payloads/Demon/src/core/Jobs.c:238` | `PRINTF( "Found Job ID: %d", JobID )

            if ( JobList->Type == JOB_TYPE_THREAD )` |
| `PRINTF` | function | `payloads/Demon/src/core/Jobs.c:287` | `PRINTF( "Found Job ID: %d\n", JobID )

            switch ( JobList->Type )` |
| `PUTS` | function | `payloads/Demon/src/core/Jobs.c:300` | `PUTS( "Kill using handle" )

                            if ( ! NT_SUCCESS( NtStatus = Instance->...` |
| `CopySessionInfo` | function | `payloads/Demon/src/core/Kerberos.c:337` | `VOID CopySessionInfo( PSESSION_INFORMATION Session, PSECURITY_LOGON_SESSION_DATA Data )` |
| `CopyTicketInfo` | function | `payloads/Demon/src/core/Kerberos.c:371` | `VOID CopyTicketInfo( PTICKET_INFORMATION TicketInfo, PKERB_TICKET_CACHE_INFO_EX Data )` |
| `ElevateToSystem` | function | `payloads/Demon/src/core/Kerberos.c:61` | `BOOL ElevateToSystem()` |
| `ExtractTicket` | function | `payloads/Demon/src/core/Kerberos.c:283` | `VOID ExtractTicket( HANDLE hLsa, ULONG authPackage, LUID luid, UNICODE_STRING targetName, PUCHAR*...` |
| `GetLUID` | function | `payloads/Demon/src/core/Kerberos.c:752` | `LUID* GetLUID( HANDLE hToken )` |
| `GetLogonSessionData` | function | `payloads/Demon/src/core/Kerberos.c:218` | `NTSTATUS GetLogonSessionData( LUID luid, PLOGON_SESSION_DATA* data )` |
| `GetLsaHandle` | function | `payloads/Demon/src/core/Kerberos.c:155` | `NTSTATUS GetLsaHandle( HANDLE hToken, BOOL highIntegrity, PHANDLE hLsa )` |
| `GetProcessIdByName` | function | `payloads/Demon/src/core/Kerberos.c:29` | `DWORD GetProcessIdByName(WCHAR* processName)` |
| `IsHighIntegrity` | function | `payloads/Demon/src/core/Kerberos.c:8` | `BOOL IsHighIntegrity(HANDLE TokenHandle)` |
| `IsSystem` | function | `payloads/Demon/src/core/Kerberos.c:131` | `BOOL IsSystem( HANDLE TokenHandle )` |
| `Klist` | function | `payloads/Demon/src/core/Kerberos.c:585` | `PSESSION_INFORMATION Klist( HANDLE hToken, LUID luid )` |
| `Ptt` | function | `payloads/Demon/src/core/Kerberos.c:399` | `BOOL Ptt( HANDLE hToken, PBYTE Ticket, DWORD TicketSize, LUID luid )` |
| `Purge` | function | `payloads/Demon/src/core/Kerberos.c:494` | `BOOL Purge( HANDLE hToken, LUID luid )` |
| `FreeReflectiveLoader` | function | `payloads/Demon/src/core/Memory.c:269` | `BOOL FreeReflectiveLoader(
    IN PVOID BaseAddress
)` |
| `MmGadgetFind` | function | `payloads/Demon/src/core/Memory.c:240` | `PVOID MmGadgetFind(
    _In_ PVOID  Memory,
    _In_ SIZE_T Length,
    _In_ PVOID  PatternBuffer...` |
| `MmHeapAlloc` | function | `payloads/Demon/src/core/Memory.c:15` | `PVOID MmHeapAlloc(
    _In_ ULONG Length
)` |
| `MmHeapFree` | function | `payloads/Demon/src/core/Memory.c:48` | `BOOL MmHeapFree(
    _In_ PVOID Memory
)` |
| `MmHeapReAlloc` | function | `payloads/Demon/src/core/Memory.c:31` | `PVOID MmHeapReAlloc(
    _In_ PVOID Memory,
    _In_ ULONG Length
)` |
| `MmVirtualAlloc` | function | `payloads/Demon/src/core/Memory.c:62` | `PVOID MmVirtualAlloc(
    IN DX_MEMORY Methode,
    IN HANDLE    Process,
    IN SIZE_T    Size,
...` |
| `MmVirtualFree` | function | `payloads/Demon/src/core/Memory.c:209` | `BOOL MmVirtualFree(
    IN HANDLE Process,
    IN PVOID  Memory
)` |
| `MmVirtualProtect` | function | `payloads/Demon/src/core/Memory.c:133` | `BOOL MmVirtualProtect(
    IN DX_MEMORY Method,
    IN HANDLE    Process,
    IN PVOID     Memory...` |
| `MmVirtualWrite` | function | `payloads/Demon/src/core/Memory.c:189` | `BOOL MmVirtualWrite(
    IN  HANDLE Process,
    OUT PVOID  Memory,
    IN  PVOID  Buffer,
    IN...` |
| `PUTS` | function | `payloads/Demon/src/core/Memory.c:79` | `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )` |
| `PUTS` | function | `payloads/Demon/src/core/Memory.c:147` | `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )` |
| `CharStringToWCharString` | function | `payloads/Demon/src/core/MiniStd.c:242` | `SIZE_T CharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )` |
| `EndsWithIW` | function | `payloads/Demon/src/core/MiniStd.c:80` | `BOOL EndsWithIW( LPWSTR String, LPWSTR Ending )` |
| `GetSystemFileTime` | function | `payloads/Demon/src/core/MiniStd.c:300` | `UINT64 GetSystemFileTime( )` |
| `HashStringA` | function | `payloads/Demon/src/core/MiniStd.c:100` | `DWORD HashStringA( PCHAR String )` |
| `HideChar` | function | `payloads/Demon/src/core/MiniStd.c:313` | `BYTE NO_INLINE HideChar( BYTE C )` |
| `MemCompare` | function | `payloads/Demon/src/core/MiniStd.c:205` | `INT MemCompare( PVOID s1, PVOID s2, INT len)` |
| `StringCompareA` | function | `payloads/Demon/src/core/MiniStd.c:9` | `INT StringCompareA( LPCSTR String1, LPCSTR String2 )` |
| `StringCompareIW` | function | `payloads/Demon/src/core/MiniStd.c:53` | `INT StringCompareIW( LPWSTR String1, LPWSTR String2 )` |
| `StringCompareW` | function | `payloads/Demon/src/core/MiniStd.c:21` | `INT StringCompareW( LPWSTR String1, LPWSTR String2 )` |
| `StringConcatA` | function | `payloads/Demon/src/core/MiniStd.c:151` | `PCHAR StringConcatA(PCHAR String, PCHAR String2)` |
| `StringConcatW` | function | `payloads/Demon/src/core/MiniStd.c:158` | `PWCHAR StringConcatW(PWCHAR String, PWCHAR String2)` |
| `StringCopyA` | function | `payloads/Demon/src/core/MiniStd.c:112` | `PCHAR StringCopyA(PCHAR String1, PCHAR String2)` |
| `StringCopyW` | function | `payloads/Demon/src/core/MiniStd.c:121` | `PWCHAR StringCopyW(PWCHAR String1, PWCHAR String2)` |
| `StringLengthA` | function | `payloads/Demon/src/core/MiniStd.c:130` | `SIZE_T StringLengthA(LPCSTR String)` |
| `StringLengthW` | function | `payloads/Demon/src/core/MiniStd.c:142` | `SIZE_T StringLengthW(LPCWSTR String)` |
| `StringNCompareIW` | function | `payloads/Demon/src/core/MiniStd.c:65` | `INT StringNCompareIW( LPWSTR String1, LPWSTR String2, INT Length )` |
| `StringNCompareW` | function | `payloads/Demon/src/core/MiniStd.c:33` | `INT StringNCompareW( LPWSTR String1, LPWSTR String2, INT Length )` |
| `StringTokenA` | function | `payloads/Demon/src/core/MiniStd.c:255` | `PCHAR StringTokenA(PCHAR String, CONST PCHAR Delim)` |
| `ToLowerCaseW` | function | `payloads/Demon/src/core/MiniStd.c:48` | `WCHAR ToLowerCaseW( WCHAR C )` |
| `WCharStringToCharString` | function | `payloads/Demon/src/core/MiniStd.c:229` | `SIZE_T WCharStringToCharString(PCHAR Destination, PWCHAR Source, SIZE_T MaximumAllowed)` |
| `WcsIStr` | function | `payloads/Demon/src/core/MiniStd.c:185` | `LPWSTR WcsIStr( PWCHAR String, PWCHAR String2 )` |
| `WcsStr` | function | `payloads/Demon/src/core/MiniStd.c:165` | `LPWSTR WcsStr( PWCHAR String, PWCHAR String2 )` |
| `FoliageObf` | function | `payloads/Demon/src/core/Obf.c:22` | `VOID FoliageObf(
    IN PSLEEP_PARAM Param
)` |
| `PRINTF` | function | `payloads/Demon/src/core/Obf.c:603` | `PRINTF( "RtlCreateTimerQueue/NtCreateEvent Failed: %lx\n", NtStatus )
    }

LEAVE: /* cleanup */...` |
| `SleepObf` | function | `payloads/Demon/src/core/Obf.c:714` | `VOID SleepObf(
    VOID
)` |
| `SleepTime` | function | `payloads/Demon/src/core/Obf.c:650` | `UINT32 SleepTime(
    VOID
)` |
| `BeaconAddValue` | function | `payloads/Demon/src/core/ObjectApi.c:584` | `BOOL BeaconAddValue(const char * key, void * ptr)` |
| `BeaconCleanupProcess` | function | `payloads/Demon/src/core/ObjectApi.c:564` | `VOID BeaconCleanupProcess( PROCESS_INFORMATION* pInfo )` |
| `BeaconDataExtract` | function | `payloads/Demon/src/core/ObjectApi.c:190` | `PCHAR BeaconDataExtract( PDATA parser, PINT size )` |
| `BeaconDataInt` | function | `payloads/Demon/src/core/ObjectApi.c:155` | `INT BeaconDataInt( PDATA parser )` |
| `BeaconDataLength` | function | `payloads/Demon/src/core/ObjectApi.c:185` | `INT BeaconDataLength( PDATA parser )` |
| `BeaconDataParse` | function | `payloads/Demon/src/core/ObjectApi.c:143` | `VOID BeaconDataParse( PDATA parser, PCHAR buffer, INT size )` |
| `BeaconDataShort` | function | `payloads/Demon/src/core/ObjectApi.c:170` | `SHORT BeaconDataShort( datap* parser )` |
| `BeaconDataStoreGetItem` | function | `payloads/Demon/src/core/ObjectApi.c:690` | `PDATA_STORE_OBJECT BeaconDataStoreGetItem(SIZE_T index)` |
| `BeaconDataStoreMaxEntries` | function | `payloads/Demon/src/core/ObjectApi.c:711` | `SIZE_T BeaconDataStoreMaxEntries()` |
| `BeaconDataStoreProtectItem` | function | `payloads/Demon/src/core/ObjectApi.c:697` | `VOID BeaconDataStoreProtectItem(SIZE_T index)` |
| `BeaconDataStoreUnprotectItem` | function | `payloads/Demon/src/core/ObjectApi.c:704` | `VOID BeaconDataStoreUnprotectItem(SIZE_T index)` |
| `BeaconFormatAlloc` | function | `payloads/Demon/src/core/ObjectApi.c:343` | `VOID BeaconFormatAlloc( PFORMAT format, int maxsz )` |
| `BeaconFormatAppend` | function | `payloads/Demon/src/core/ObjectApi.c:377` | `VOID BeaconFormatAppend( PFORMAT format, char* text, int len )` |
| `BeaconFormatFree` | function | `payloads/Demon/src/core/ObjectApi.c:361` | `VOID BeaconFormatFree( PFORMAT format )` |
| `BeaconFormatInt` | function | `payloads/Demon/src/core/ObjectApi.c:411` | `VOID BeaconFormatInt( PFORMAT format, int value)` |
| `BeaconFormatPrintf` | function | `payloads/Demon/src/core/ObjectApi.c:384` | `VOID BeaconFormatPrintf( PFORMAT format, char* fmt, ... )` |
| `BeaconFormatReset` | function | `payloads/Demon/src/core/ObjectApi.c:354` | `VOID BeaconFormatReset( PFORMAT format )` |
| `BeaconFormatToString` | function | `payloads/Demon/src/core/ObjectApi.c:405` | `char* BeaconFormatToString( PFORMAT format, int* size)` |
| `BeaconGetCustomUserData` | function | `payloads/Demon/src/core/ObjectApi.c:718` | `PCHAR BeaconGetCustomUserData()` |
| `BeaconGetSpawnTo` | function | `payloads/Demon/src/core/ObjectApi.c:440` | `VOID BeaconGetSpawnTo( BOOL x86, char* buffer, int length )` |
| `BeaconGetValue` | function | `payloads/Demon/src/core/ObjectApi.c:633` | `PVOID BeaconGetValue(const char * key)` |
| `BeaconInformation` | function | `payloads/Demon/src/core/ObjectApi.c:578` | `VOID BeaconInformation(BEACON_INFO * info)` |
| `BeaconInjectProcess` | function | `payloads/Demon/src/core/ObjectApi.c:487` | `VOID BeaconInjectProcess( HANDLE hProc, int pid, char* payload, int p_len, int p_offset, char * a...` |
| `BeaconInjectTemporaryProcess` | function | `payloads/Demon/src/core/ObjectApi.c:530` | `VOID BeaconInjectTemporaryProcess( PROCESS_INFORMATION* pInfo, char* payload, int p_len, int p_of...` |
| `BeaconIsAdmin` | function | `payloads/Demon/src/core/ObjectApi.c:324` | `BOOL BeaconIsAdmin(
    VOID
)` |
| `BeaconOutput` | function | `payloads/Demon/src/core/ObjectApi.c:305` | `VOID BeaconOutput( INT Type, PCHAR data, INT len )` |
| `BeaconPrintf` | function | `payloads/Demon/src/core/ObjectApi.c:248` | `VOID BeaconPrintf( INT Type, PCHAR fmt, ... )` |
| `BeaconRemoveValue` | function | `payloads/Demon/src/core/ObjectApi.c:656` | `BOOL BeaconRemoveValue(const char * key)` |
| `BeaconSpawnTemporaryProcess` | function | `payloads/Demon/src/core/ObjectApi.c:463` | `BOOL BeaconSpawnTemporaryProcess( BOOL x86, BOOL ignoreToken, STARTUPINFO* sInfo, PROCESS_INFORMA...` |
| `BeaconUseToken` | function | `payloads/Demon/src/core/ObjectApi.c:425` | `BOOL BeaconUseToken( HANDLE token )` |
| `GetRequestIDForCallingObjectFile` | function | `payloads/Demon/src/core/ObjectApi.c:224` | `BOOL GetRequestIDForCallingObjectFile( PVOID CoffeeFunctionReturn, PUINT32 RequestID )` |
| `LdrFreeLibrary` | function | `payloads/Demon/src/core/ObjectApi.c:32` | `BOOL LdrFreeLibrary( HMODULE hLibModule )` |
| `LdrFunctionAddrString` | function | `payloads/Demon/src/core/ObjectApi.c:26` | `PVOID LdrFunctionAddrString( PVOID Module, PCHAR Function )` |
| `LdrLocalFree` | function | `payloads/Demon/src/core/ObjectApi.c:37` | `HLOCAL LdrLocalFree( PVOID hMem )` |
| `LdrModulePebString` | function | `payloads/Demon/src/core/ObjectApi.c:20` | `PVOID LdrModulePebString( PCHAR ModuleString )` |
| `bufsize` | macro | `payloads/Demon/src/core/ObjectApi.c:16` | `#define bufsize` |
| `swap_endianess` | function | `payloads/Demon/src/core/ObjectApi.c:131` | `uint32_t swap_endianess(uint32_t indata)` |
| `toWideChar` | function | `payloads/Demon/src/core/ObjectApi.c:724` | `BOOL toWideChar( char* src, wchar_t* dst, int max )` |
| `AES256` | macro | `payloads/Demon/src/core/Package.c:10` | `#define AES256` |
| `CTR` | macro | `payloads/Demon/src/core/Package.c:9` | `#define CTR` |
| `Int32ToBuffer` | function | `payloads/Demon/src/core/Package.c:39` | `VOID Int32ToBuffer(
    OUT PUCHAR Buffer,
    IN  UINT32 Size
)` |
| `Int64ToBuffer` | function | `payloads/Demon/src/core/Package.c:13` | `VOID Int64ToBuffer( PUCHAR Buffer, UINT64 Value )` |
| `PUTS_DONT_SEND` | function | `payloads/Demon/src/core/Package.c:264` | `PUTS_DONT_SEND("TransportSend failed!")
        }

        if ( Package->Destroy )` |
| `PackageAddBool` | function | `payloads/Demon/src/core/Package.c:85` | `VOID PackageAddBool(
    _Inout_ PPACKAGE Package,
    IN     BOOLEAN  Data
)` |
| `PackageAddBytes` | function | `payloads/Demon/src/core/Package.c:125` | `VOID PackageAddBytes( PPACKAGE Package, PBYTE Data, SIZE_T Size )` |
| `PackageAddInt32` | function | `payloads/Demon/src/core/Package.c:49` | `VOID PackageAddInt32(
    _Inout_ PPACKAGE Package,
    IN     UINT32   Data
)` |
| `PackageAddInt64` | function | `payloads/Demon/src/core/Package.c:68` | `VOID PackageAddInt64( PPACKAGE Package, UINT64 dataInt )` |
| `PackageAddPad` | function | `payloads/Demon/src/core/Package.c:109` | `VOID PackageAddPad( PPACKAGE Package, PCHAR Data, SIZE_T Size )` |
| `PackageAddPtr` | function | `payloads/Demon/src/core/Package.c:104` | `VOID PackageAddPtr( PPACKAGE Package, PVOID pointer )` |
| `PackageAddString` | function | `payloads/Demon/src/core/Package.c:147` | `VOID PackageAddString( PPACKAGE package, PCHAR data )` |
| `PackageAddWString` | function | `payloads/Demon/src/core/Package.c:152` | `VOID PackageAddWString( PPACKAGE package, PWCHAR data )` |
| `PackageCreate` | function | `payloads/Demon/src/core/Package.c:157` | `PPACKAGE PackageCreate( UINT32 CommandID )` |
| `PackageCreateWithMetaData` | function | `payloads/Demon/src/core/Package.c:174` | `PPACKAGE PackageCreateWithMetaData( UINT32 CommandID )` |
| `PackageCreateWithRequestID` | function | `payloads/Demon/src/core/Package.c:187` | `PPACKAGE PackageCreateWithRequestID( UINT32 CommandID, UINT32 RequestID )` |
| `PackageDestroy` | function | `payloads/Demon/src/core/Package.c:196` | `VOID PackageDestroy(
    IN PPACKAGE Package
)` |
| `PackageTransmit` | function | `payloads/Demon/src/core/Package.c:281` | `VOID PackageTransmit(
    IN PPACKAGE Package
)` |
| `PackageTransmitAll` | function | `payloads/Demon/src/core/Package.c:333` | `BOOL PackageTransmitAll(
    OUT    PVOID*   Response,
    OUT    PSIZE_T  Size
)` |
| `PackageTransmitError` | function | `payloads/Demon/src/core/Package.c:471` | `VOID PackageTransmitError(
    IN UINT32 ID,
    IN UINT32 ErrorCode
)` |
| `PackageTransmitNow` | function | `payloads/Demon/src/core/Package.c:229` | `BOOL PackageTransmitNow(
    _Inout_ PPACKAGE Package,
    OUT    PVOID*   Response,
    OUT    P...` |
| `ParserDecrypt` | function | `payloads/Demon/src/core/Parser.c:21` | `VOID ParserDecrypt( PPARSER parser, PBYTE Key, PBYTE IV )` |
| `ParserDestroy` | function | `payloads/Demon/src/core/Parser.c:168` | `VOID ParserDestroy( PPARSER Parser )` |
| `ParserGetBool` | function | `payloads/Demon/src/core/Parser.c:106` | `BOOL ParserGetBool( PPARSER parser )` |
| `ParserGetByte` | function | `payloads/Demon/src/core/Parser.c:48` | `BYTE ParserGetByte( PPARSER parser )` |
| `ParserGetBytes` | function | `payloads/Demon/src/core/Parser.c:127` | `PBYTE ParserGetBytes( PPARSER parser, PUINT32 size )` |
| `ParserGetInt16` | function | `payloads/Demon/src/core/Parser.c:33` | `INT16 ParserGetInt16( PPARSER parser )` |
| `ParserGetInt32` | function | `payloads/Demon/src/core/Parser.c:64` | `INT ParserGetInt32( PPARSER parser )` |
| `ParserGetInt64` | function | `payloads/Demon/src/core/Parser.c:85` | `INT64 ParserGetInt64( PPARSER parser )` |
| `ParserGetString` | function | `payloads/Demon/src/core/Parser.c:158` | `PCHAR  ParserGetString( PPARSER parser, PUINT32 size )` |
| `ParserGetWString` | function | `payloads/Demon/src/core/Parser.c:163` | `PWCHAR  ParserGetWString( PPARSER parser, PUINT32 size )` |
| `ParserNew` | function | `payloads/Demon/src/core/Parser.c:7` | `VOID ParserNew( PPARSER parser, PBYTE Buffer, UINT32 size )` |
| `PivotAdd` | function | `payloads/Demon/src/core/Pivot.c:24` | `BOOL PivotAdd( BUFFER NamedPipe, PVOID* Output, PDWORD BytesSize )` |
| `PivotCount` | function | `payloads/Demon/src/core/Pivot.c:218` | `DWORD PivotCount()` |
| `PivotGet` | function | `payloads/Demon/src/core/Pivot.c:121` | `PPIVOT_DATA PivotGet( DWORD AgentID )` |
| `PivotParseDemonID` | function | `payloads/Demon/src/core/Pivot.c:331` | `UINT32 PivotParseDemonID( PVOID Response, SIZE_T Size )` |
| `PivotPush` | function | `payloads/Demon/src/core/Pivot.c:235` | `VOID PivotPush()` |
| `PivotRemove` | function | `payloads/Demon/src/core/Pivot.c:139` | `BOOL PivotRemove( DWORD AgentId )` |
| `RtAdvapi32` | function | `payloads/Demon/src/core/Runtime.c:6` | `BOOL RtAdvapi32(
    VOID
)` |
| `RtAmsi` | function | `payloads/Demon/src/core/Runtime.c:433` | `BOOL RtAmsi(
    VOID
)` |
| `RtGdi32` | function | `payloads/Demon/src/core/Runtime.c:273` | `BOOL RtGdi32(
    VOID
)` |
| `RtIphlpapi` | function | `payloads/Demon/src/core/Runtime.c:240` | `BOOL RtIphlpapi(
    VOID
)` |
| `RtMscoree` | function | `payloads/Demon/src/core/Runtime.c:68` | `BOOL RtMscoree(
    VOID
)` |
| `RtMsvcrt` | function | `payloads/Demon/src/core/Runtime.c:208` | `BOOL RtMsvcrt(
    VOID
)` |
| `RtNetApi32` | function | `payloads/Demon/src/core/Runtime.c:310` | `BOOL RtNetApi32(
    VOID
)` |
| `RtOleaut32` | function | `payloads/Demon/src/core/Runtime.c:103` | `BOOL RtOleaut32(
    VOID
)` |
| `RtShell32` | function | `payloads/Demon/src/core/Runtime.c:176` | `BOOL RtShell32(
    VOID
)` |
| `RtSspicli` | function | `payloads/Demon/src/core/Runtime.c:394` | `BOOL RtSspicli(
    VOID
)` |
| `RtUser32` | function | `payloads/Demon/src/core/Runtime.c:142` | `BOOL RtUser32(
    VOID
)` |
| `RtWinHttp` | function | `payloads/Demon/src/core/Runtime.c:463` | `BOOL RtWinHttp(
    VOID
)` |
| `RtWs2_32` | function | `payloads/Demon/src/core/Runtime.c:349` | `BOOL RtWs2_32(
    VOID
)` |
| `DnsQueryIPv4` | function | `payloads/Demon/src/core/Socket.c:539` | `DWORD DnsQueryIPv4( LPSTR Domain )` |
| `DnsQueryIPv6` | function | `payloads/Demon/src/core/Socket.c:580` | `PBYTE DnsQueryIPv6( LPSTR Domain )` |
| `InitWSA` | function | `payloads/Demon/src/core/Socket.c:33` | `BOOL InitWSA( VOID )` |
| `PRINTF` | function | `payloads/Demon/src/core/Socket.c:112` | `PRINTF( "SockAddr6: %02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%d\n"...` |
| `PRINTF` | function | `payloads/Demon/src/core/Socket.c:429` | `PRINTF( "Closing socket %x\n", Socket->ID )

    /* do we want to remove a reverse port forward c...` |
| `PUTS` | function | `payloads/Demon/src/core/Socket.c:41` | `PUTS( "Init Windows Socket..." )

        if ( ( Result = Instance->Win32.WSAStartup( MAKEWORD( 2...` |
| `PUTS` | function | `payloads/Demon/src/core/Socket.c:74` | `PUTS( "Create Socket..." )

        if ( UseIpv4 )` |
| `RecvAll` | function | `payloads/Demon/src/core/Socket.c:7` | `BOOL RecvAll( SOCKET Socket, PVOID Buffer, DWORD Length, PDWORD BytesRead )` |
| `SocketCleanDead` | function | `payloads/Demon/src/core/Socket.c:482` | `VOID SocketCleanDead()` |
| `SocketClients` | function | `payloads/Demon/src/core/Socket.c:213` | `VOID SocketClients()` |
| `SocketFree` | function | `payloads/Demon/src/core/Socket.c:425` | `VOID SocketFree( PSOCKET_DATA Socket )` |
| `SocketNew` | function | `payloads/Demon/src/core/Socket.c:59` | `PSOCKET_DATA SocketNew( SOCKET WinSock, DWORD Type, BOOL UseIpv4, DWORD IPv4, PBYTE IPv6, DWORD L...` |
| `SocketPush` | function | `payloads/Demon/src/core/Socket.c:522` | `VOID SocketPush()` |
| `SocketRead` | function | `payloads/Demon/src/core/Socket.c:281` | `VOID SocketRead()` |
| `SpoofRetAddr` | function | `payloads/Demon/src/core/Spoof.c:6` | `PVOID SpoofRetAddr(
    _In_    PVOID  Module,
    _In_    ULONG  Size,
    _In_    HANDLE Functi...` |
| `SysNtAlertResumeThread` | function | `payloads/Demon/src/core/SysNative.c:358` | `NTSTATUS NTAPI SysNtAlertResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG Previo...` |
| `SysNtAllocateVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:259` | `NTSTATUS NTAPI SysNtAllocateVirtualMemory(
    IN     HANDLE    ProcessHandle,
    _Inout_ PVOID*...` |
| `SysNtClose` | function | `payloads/Demon/src/core/SysNative.c:445` | `NTSTATUS NTAPI SysNtClose (
    IN HANDLE Handle
)` |
| `SysNtCreateEvent` | function | `payloads/Demon/src/core/SysNative.c:128` | `NTSTATUS NTAPI SysNtCreateEvent (
    OUT    PHANDLE            EventHandle,
    IN     ACCESS_MA...` |
| `SysNtCreateThreadEx` | function | `payloads/Demon/src/core/SysNative.c:143` | `NTSTATUS NTAPI SysNtCreateThreadEx(
    OUT PHANDLE     hThread,
    IN  ACCESS_MASK DesiredAcces...` |
| `SysNtDuplicateObject` | function | `payloads/Demon/src/core/SysNative.c:176` | `NTSTATUS NTAPI SysNtDuplicateObject(
    IN     HANDLE      SourceProcessHandle,
    IN     HANDL...` |
| `SysNtDuplicateToken` | function | `payloads/Demon/src/core/SysNative.c:73` | `NTSTATUS NTAPI SysNtDuplicateToken(
    IN  HANDLE             ExistingTokenHandle,
    IN  ACCES...` |
| `SysNtFreeVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:290` | `NTSTATUS NTAPI SysNtFreeVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  Base...` |
| `SysNtGetContextThread` | function | `payloads/Demon/src/core/SysNative.c:193` | `NTSTATUS NTAPI SysNtGetContextThread (
    IN     HANDLE   ThreadHandle,
    _Inout_ PCONTEXT Thr...` |
| `SysNtGetNextThread` | function | `payloads/Demon/src/core/SysNative.c:486` | `NTSTATUS NTAPI SysNtGetNextThread(
    IN  HANDLE      ProcessHandle,
    IN  HANDLE      ThreadH...` |
| `SysNtOpenProcess` | function | `payloads/Demon/src/core/SysNative.c:20` | `NTSTATUS NTAPI SysNtOpenProcess(
    OUT    PHANDLE             ProcessHandle,
    IN     ACCESS_...` |
| `SysNtOpenProcessToken` | function | `payloads/Demon/src/core/SysNative.c:60` | `NTSTATUS NTAPI SysNtOpenProcessToken(
    IN  HANDLE      ProcessHandle,
    IN  ACCESS_MASK Desi...` |
| `SysNtOpenThread` | function | `payloads/Demon/src/core/SysNative.c:6` | `NTSTATUS NTAPI SysNtOpenThread(
    OUT    PHANDLE            ThreadHandle,
    IN     ACCESS_MAS...` |
| `SysNtOpenThreadToken` | function | `payloads/Demon/src/core/SysNative.c:46` | `NTSTATUS NTAPI SysNtOpenThreadToken(
    IN  HANDLE      ThreadHandle,
    IN  ACCESS_MASK Desire...` |
| `SysNtProtectVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:316` | `NTSTATUS NTAPI SysNtProtectVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  B...` |
| `SysNtQueryInformationProcess` | function | `payloads/Demon/src/core/SysNative.c:217` | `NTSTATUS NTAPI SysNtQueryInformationProcess(
    IN      HANDLE           ProcessHandle,
    IN  ...` |
| `SysNtQueryInformationThread` | function | `payloads/Demon/src/core/SysNative.c:415` | `NTSTATUS NTAPI SysNtQueryInformationThread(
    IN      HANDLE          ThreadHandle,
    IN     ...` |
| `SysNtQueryInformationToken` | function | `payloads/Demon/src/core/SysNative.c:400` | `NTSTATUS NTAPI SysNtQueryInformationToken (
    IN  HANDLE                  TokenHandle,
    IN  ...` |
| `SysNtQueryObject` | function | `payloads/Demon/src/core/SysNative.c:430` | `NTSTATUS NTAPI SysNtQueryObject(
    IN  HANDLE                   Handle,
    IN  OBJECT_INFORMAT...` |
| `SysNtQuerySystemInformation` | function | `payloads/Demon/src/core/SysNative.c:232` | `NTSTATUS NTAPI SysNtQuerySystemInformation (
    IN      SYSTEM_INFORMATION_CLASS SystemInformati...` |
| `SysNtQueryVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:384` | `NTSTATUS NTAPI SysNtQueryVirtualMemory(
    IN      HANDLE                   ProcessHandle,
    I...` |
| `SysNtQueueApcThread` | function | `payloads/Demon/src/core/SysNative.c:89` | `NTSTATUS NTAPI SysNtQueueApcThread(
    IN     HANDLE          ThreadHandle,
    IN     PPS_APC_R...` |
| `SysNtReadVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:331` | `NTSTATUS NTAPI SysNtReadVirtualMemory (
    IN      HANDLE  ProcessHandle,
    IN OPT  PVOID   Ba...` |
| `SysNtResumeThread` | function | `payloads/Demon/src/core/SysNative.c:116` | `NTSTATUS NTAPI SysNtResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSus...` |
| `SysNtSetContextThread` | function | `payloads/Demon/src/core/SysNative.c:205` | `NTSTATUS NTAPI SysNtSetContextThread(
    IN HANDLE   ThreadHandle,
    IN PCONTEXT ThreadContext
)` |
| `SysNtSetInformationThread` | function | `payloads/Demon/src/core/SysNative.c:456` | `NTSTATUS NTAPI SysNtSetInformationThread (
    IN HANDLE          ThreadHandle,
    IN THREADINFO...` |
| `SysNtSetInformationVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:470` | `NTSTATUS NTAPI SysNtSetInformationVirtualMemory(
    IN HANDLE                           ProcessH...` |
| `SysNtSignalAndWaitForSingleObject` | function | `payloads/Demon/src/core/SysNative.c:370` | `NTSTATUS NTAPI SysNtSignalAndWaitForSingleObject(
    IN     HANDLE         SignalHandle,
    IN ...` |
| `SysNtSuspendThread` | function | `payloads/Demon/src/core/SysNative.c:104` | `NTSTATUS NTAPI SysNtSuspendThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSu...` |
| `SysNtTerminateProcess` | function | `payloads/Demon/src/core/SysNative.c:34` | `NTSTATUS NTAPI SysNtTerminateProcess(
    IN OPTIONAL HANDLE   ProcessHandle,
    IN          NTS...` |
| `SysNtTerminateThread` | function | `payloads/Demon/src/core/SysNative.c:346` | `NTSTATUS NTAPI SysNtTerminateThread (
    IN OPT HANDLE   ThreadHandle,
    IN     NTSTATUS ExitS...` |
| `SysNtUnmapViewOfSection` | function | `payloads/Demon/src/core/SysNative.c:304` | `NTSTATUS NTAPI SysNtUnmapViewOfSection(
    IN HANDLE ProcessHandle,
    IN PVOID  BaseAddress
)` |
| `SysNtWaitForSingleObject` | function | `payloads/Demon/src/core/SysNative.c:246` | `NTSTATUS NTAPI SysNtWaitForSingleObject(
    IN     HANDLE         Handle,
    IN     BOOLEAN    ...` |
| `SysNtWriteVirtualMemory` | function | `payloads/Demon/src/core/SysNative.c:275` | `NTSTATUS NTAPI SysNtWriteVirtualMemory(
    IN       HANDLE  ProcessHandle,
    IN OPT   PVOID   ...` |
| `FindSsnOfHookedSyscall` | function | `payloads/Demon/src/core/Syscalls.c:201` | `BOOL FindSsnOfHookedSyscall(
    IN  PVOID  Function,
    OUT PWORD  Ssn
)` |
| `PRINTF` | function | `payloads/Demon/src/core/Syscalls.c:184` | `PRINTF( "Could not resolve the Ssn of function at 0x%p\n", Function )
        }

        if ( Sys...` |
| `PRINTF` | function | `payloads/Demon/src/core/Syscalls.c:209` | `PRINTF( "The syscall at address 0x%p seems to be hooked, trying to resolve its Ssn via neighbouri...` |
| `SYS_EXTRACT` | function | `payloads/Demon/src/core/Syscalls.c:44` | `SYS_EXTRACT( NtOpenThread )
    SYS_EXTRACT( NtOpenThreadToken )
    SYS_EXTRACT( NtOpenProcess )...` |
| `SysInitialize` | function | `payloads/Demon/src/core/Syscalls.c:12` | `BOOL SysInitialize(
    IN PVOID Ntdll
)` |
| `PUTS` | function | `payloads/Demon/src/core/Thread.c:185` | `PUTS( "calling RtlCreateUserThread( ctx->h.hProcess, NULL, TRUE, 0, NULL, NULL, ctx->s.lpStartAdd...` |
| `ThreadCreate` | function | `payloads/Demon/src/core/Thread.c:217` | `HANDLE ThreadCreate(
    IN  BYTE   Method,
    IN  HANDLE Process,
    IN  BOOL   x64,
    IN  P...` |
| `ThreadCreateWoW64` | function | `payloads/Demon/src/core/Thread.c:118` | `HANDLE ThreadCreateWoW64(
    IN  BYTE   Method,
    IN  HANDLE Process,
    IN  PVOID  Entry,
  ...` |
| `ThreadQueryTib` | function | `payloads/Demon/src/core/Thread.c:20` | `BOOL ThreadQueryTib(
    IN  PVOID   Adr,
    OUT PNT_TIB Tib
)` |
| `AddUserToken` | function | `payloads/Demon/src/core/Token.c:733` | `VOID AddUserToken(
    _Inout_ PUSER_TOKEN_DATA NewToken,
    _Inout_ PUSER_TOKEN_DATA Tokens,
  ...` |
| `CanTokenBeImpersonated` | function | `payloads/Demon/src/core/Token.c:802` | `BOOL CanTokenBeImpersonated( IN HANDLE hToken )` |
| `DATA_FREE` | function | `payloads/Demon/src/core/Token.c:182` | `DATA_FREE( UserInfo, UserSize )
    }

    if ( Flags == TOKEN_OWNER_FLAG_USER )` |
| `GetAllHandles` | function | `payloads/Demon/src/core/Token.c:1076` | `BOOL GetAllHandles( OUT PSYSTEM_HANDLE_INFORMATION* phandle_table, OUT PULONG phandle_table_size )` |
| `GetProcessesFromHandleTable` | function | `payloads/Demon/src/core/Token.c:1040` | `BOOL GetProcessesFromHandleTable( IN PSYSTEM_HANDLE_INFORMATION handleTableInformation, OUT PPROC...` |
| `GetTokenInfo` | function | `payloads/Demon/src/core/Token.c:949` | `BOOL GetTokenInfo(
    IN HANDLE hToken,
    OUT PDWORD pTokenType,
    OUT PDWORD pIntegrity,
  ...` |
| `GetTypeIndexToken` | function | `payloads/Demon/src/core/Token.c:910` | `BOOL GetTypeIndexToken( OUT PULONG TokenTypeIndex )` |
| `ImpersonateTokenFromVault` | function | `payloads/Demon/src/core/Token.c:1257` | `BOOL ImpersonateTokenFromVault(
    IN DWORD TokenID
)` |
| `ImpersonateTokenInStore` | function | `payloads/Demon/src/core/Token.c:1361` | `BOOL ImpersonateTokenInStore(
    IN PTOKEN_LIST_DATA TokenData
)` |
| `IsImpersonationToken` | function | `payloads/Demon/src/core/Token.c:771` | `BOOL IsImpersonationToken( HANDLE token )` |
| `IsNotCurrentUser` | function | `payloads/Demon/src/core/Token.c:1122` | `BOOL IsNotCurrentUser( BOOL DoCheck, PBUFFER UserA, PBUFFER UserB )` |
| `ListTokens` | function | `payloads/Demon/src/core/Token.c:1130` | `BOOL ListTokens( PUSER_TOKEN_DATA* pTokens, PDWORD pNumTokens )` |
| `PRINTF` | function | `payloads/Demon/src/core/Token.c:463` | `PRINTF( "ProcessOpen: Failed:[%ld]\n", NtGetLastError() )
        PACKAGE_ERROR_WIN32
    }

    ...` |
| `PRINTF` | function | `payloads/Demon/src/core/Token.c:602` | `PRINTF( "TokenMake( %ls, %ls, %ls, %d )\n", User, Password, Domain, LogonType )

    if ( ! Token...` |
| `PRINTF` | function | `payloads/Demon/src/core/Token.c:606` | `PRINTF( "Failed to revert to self: Error:[%d]\n", NtGetLastError() )
        PACKAGE_ERROR_WIN32
...` |
| `PUTS` | function | `payloads/Demon/src/core/Token.c:177` | `PUTS( "Unexpected successful call to NtQueryInformationToken.\n" )
    }

LEAVE:
    if ( UserInfo )` |
| `PUTS` | function | `payloads/Demon/src/core/Token.c:991` | `PUTS( "GetTokenInformation failed" )
            }
        }
        else if (TokenStatisticsInfo...` |
| `ProcessIsIncluded` | function | `payloads/Demon/src/core/Token.c:1029` | `BOOL ProcessIsIncluded( IN PPROCESS_LIST process_list, IN ULONG ProcessId )` |
| `ProcessUserToken` | function | `payloads/Demon/src/core/Token.c:830` | `VOID ProcessUserToken(
    IN HANDLE hToken,
    IN DWORD ProcessId,
    IN HANDLE handle,
    IN...` |
| `QueryObjectTypesInfo` | function | `payloads/Demon/src/core/Token.c:878` | `BOOL QueryObjectTypesInfo( POBJECT_TYPES_INFORMATION* pObjectTypes, PULONG pObjectTypesSize )` |
| `SysDuplicateTokenEx` | function | `payloads/Demon/src/core/Token.c:365` | `BOOL SysDuplicateTokenEx(
    IN HANDLE ExistingTokenHandle,
    IN DWORD dwDesiredAccess,
    IN...` |
| `SysImpersonateLoggedOnUser` | function | `payloads/Demon/src/core/Token.c:1281` | `BOOL SysImpersonateLoggedOnUser( HANDLE hToken )` |
| `TokenAdd` | function | `payloads/Demon/src/core/Token.c:323` | `DWORD TokenAdd(
    IN HANDLE hToken,
    IN LPWSTR DomainUser,
    IN SHORT  Type,
    IN DWORD ...` |
| `TokenClear` | function | `payloads/Demon/src/core/Token.c:681` | `VOID TokenClear(
    VOID
)` |
| `TokenCurrentHandle` | function | `payloads/Demon/src/core/Token.c:624` | `HANDLE TokenCurrentHandle(
    VOID
)` |
| `TokenDuplicate` | function | `payloads/Demon/src/core/Token.c:37` | `BOOL TokenDuplicate(
    IN  HANDLE        TokenOriginal,
    IN  DWORD         Access,
    IN  S...` |
| `TokenElevated` | function | `payloads/Demon/src/core/Token.c:650` | `BOOL TokenElevated(
    IN HANDLE Token
)` |
| `TokenGet` | function | `payloads/Demon/src/core/Token.c:664` | `PTOKEN_LIST_DATA TokenGet(
    IN DWORD TokenID
)` |
| `TokenImpersonate` | function | `payloads/Demon/src/core/Token.c:707` | `BOOL TokenImpersonate(
    IN BOOL Impersonate
)` |
| `TokenMake` | function | `payloads/Demon/src/core/Token.c:598` | `HANDLE TokenMake( LPWSTR User, LPWSTR Password, LPWSTR Domain, DWORD LogonType )` |
| `TokenQueryOwner` | function | `payloads/Demon/src/core/Token.c:103` | `BOOL TokenQueryOwner(
    IN  HANDLE  Token,
    OUT PBUFFER UserDomain,
    IN  DWORD   Flags
)` |
| `TokenRemove` | function | `payloads/Demon/src/core/Token.c:474` | `BOOL TokenRemove( DWORD TokenID )` |
| `TokenRevSelf` | function | `payloads/Demon/src/core/Token.c:74` | `BOOL TokenRevSelf(
    VOID
)` |
| `TokenSetPrivilege` | function | `payloads/Demon/src/core/Token.c:203` | `BOOL TokenSetPrivilege(
    IN LPSTR Privilege,
    IN BOOL  Enable
)` |
| `TokenSetSeDebugPriv` | function | `payloads/Demon/src/core/Token.c:240` | `BOOL TokenSetSeDebugPriv(
    IN BOOL  Enable
)` |
| `TokenSetSeImpersonatePriv` | function | `payloads/Demon/src/core/Token.c:271` | `BOOL TokenSetSeImpersonatePriv(
    IN BOOL  Enable
)` |
| `TokenSteal` | function | `payloads/Demon/src/core/Token.c:414` | `HANDLE TokenSteal(
    IN DWORD  ProcessID,
    IN HANDLE TargetHandle
)` |
| `SMBGetJob` | function | `payloads/Demon/src/core/Transport.c:89` | `BOOL SMBGetJob( PVOID* RecvData, PSIZE_T RecvSize )` |
| `TransportInit` | function | `payloads/Demon/src/core/Transport.c:13` | `BOOL TransportInit( )` |
| `TransportSend` | function | `payloads/Demon/src/core/Transport.c:52` | `BOOL TransportSend( LPVOID Data, SIZE_T Size, PVOID* RecvData, PSIZE_T RecvSize )` |
| `HostAdd` | function | `payloads/Demon/src/core/TransportHttp.c:356` | `PHOST_DATA HostAdd(
    _In_ LPWSTR Host, SIZE_T Size, DWORD Port )` |
| `HostCheckup` | function | `payloads/Demon/src/core/TransportHttp.c:541` | `BOOL HostCheckup()` |
| `HostCount` | function | `payloads/Demon/src/core/TransportHttp.c:514` | `DWORD HostCount()` |
| `HostFailure` | function | `payloads/Demon/src/core/TransportHttp.c:378` | `PHOST_DATA HostFailure( PHOST_DATA Host )` |
| `HostRandom` | function | `payloads/Demon/src/core/TransportHttp.c:402` | `PHOST_DATA HostRandom()` |
| `HostRotation` | function | `payloads/Demon/src/core/TransportHttp.c:437` | `PHOST_DATA HostRotation( SHORT Strategy )` |
| `HttpQueryStatus` | function | `payloads/Demon/src/core/TransportHttp.c:336` | `DWORD HttpQueryStatus(
    _In_ HANDLE Request
)` |
| `HttpSend` | function | `payloads/Demon/src/core/TransportHttp.c:21` | `BOOL HttpSend(
    _In_      PBUFFER Send,
    _Out_opt_ PBUFFER Resp
)` |
| `PRINTF_DONT_SEND` | function | `payloads/Demon/src/core/TransportHttp.c:291` | `PRINTF_DONT_SEND( "HTTP Error: %d\n", NtGetLastError() )
    }

LEAVE:
    if ( Connect )` |
| `PRINTF` | function | `payloads/Demon/src/core/TransportSmb.c:107` | `PRINTF( "PipeRead failed with to read 0x%x bytes from pipe\n", Resp->Length )
                if ...` |
| `SmbRecv` | function | `payloads/Demon/src/core/TransportSmb.c:65` | `BOOL SmbRecv( PBUFFER Resp )` |
| `SmbSecurityAttrFree` | function | `payloads/Demon/src/core/TransportSmb.c:213` | `VOID SmbSecurityAttrFree( PSMB_PIPE_SEC_ATTR SmbSecAttr )` |
| `SmbSecurityAttrOpen` | function | `payloads/Demon/src/core/TransportSmb.c:142` | `VOID SmbSecurityAttrOpen( PSMB_PIPE_SEC_ATTR SmbSecAttr, PSECURITY_ATTRIBUTES SecurityAttr )` |
| `SmbSend` | function | `payloads/Demon/src/core/TransportSmb.c:8` | `BOOL SmbSend( PBUFFER Send )` |
| `AnonPipesInit` | function | `payloads/Demon/src/core/Win32.c:981` | `BOOL AnonPipesInit(
    IN PANONPIPE AnonPipes
)` |
| `AnonPipesRead` | function | `payloads/Demon/src/core/Win32.c:1000` | `VOID AnonPipesRead(
    IN PANONPIPE AnonPipes,
    IN UINT32 RequestID
)` |
| `BypassPatchAMSI` | function | `payloads/Demon/src/core/Win32.c:930` | `BOOL BypassPatchAMSI(
    VOID
)` |
| `CfgAddressAdd` | function | `payloads/Demon/src/core/Win32.c:1259` | `VOID CfgAddressAdd(
    IN PVOID ImageBase,
    IN PVOID Function
)` |
| `CfgQueryEnforced` | function | `payloads/Demon/src/core/Win32.c:1227` | `BOOL CfgQueryEnforced(
    VOID
)` |
| `DemonPrintf` | function | `payloads/Demon/src/core/Win32.c:1402` | `VOID DemonPrintf( PCHAR fmt, ... )` |
| `EventSet` | function | `payloads/Demon/src/core/Win32.c:1293` | `BOOL EventSet(
    IN HANDLE Event
)` |
| `GetSyscallSize` | function | `payloads/Demon/src/core/Win32.c:440` | `UINT32 GetSyscallSize(
    VOID
)` |
| `HashEx` | function | `payloads/Demon/src/core/Win32.c:17` | `ULONG HashEx(
    IN PVOID String,
    IN ULONG Length,
    IN BOOL  Upper
)` |
| `LdrFunctionAddr` | function | `payloads/Demon/src/core/Win32.c:377` | `PVOID LdrFunctionAddr(
    IN PVOID Module,
    IN DWORD Hash
)` |
| `LdrModuleLoad` | function | `payloads/Demon/src/core/Win32.c:215` | `PVOID LdrModuleLoad(
    IN LPSTR ModuleName
)` |
| `LdrModulePeb` | function | `payloads/Demon/src/core/Win32.c:65` | `PVOID LdrModulePeb(
    IN DWORD Hash
)` |
| `LdrModulePebByString` | function | `payloads/Demon/src/core/Win32.c:99` | `PVOID LdrModulePebByString(
    IN LPWSTR Module
)` |
| `LdrModuleSearch` | function | `payloads/Demon/src/core/Win32.c:165` | `PVOID LdrModuleSearch(
    IN LPWSTR ModuleName)` |
| `LogToConsole` | function | `payloads/Demon/src/core/Win32.c:1434` | `VOID LogToConsole(
    IN LPCSTR fmt,
    ...)` |
| `PRINTF` | function | `payloads/Demon/src/core/Win32.c:354` | `PRINTF( "Module \"%s\": %p\n", ModuleName, Module )

    /* close event end */
    if ( Event )` |
| `PRINTF` | function | `payloads/Demon/src/core/Win32.c:654` | `PRINTF( "CmdLine           : %ls\n", CmdLine )
        PRINTF( "lpCurrentDirectory: %ls\n", lpCur...` |
| `PRINTF` | function | `payloads/Demon/src/core/Win32.c:1023` | `PRINTF( "dwRead => %d\n", dwRead )

        if ( dwRead == 0 )` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:252` | `PUTS( "Loading module using RtlRegisterWait" )

            /* create an event for end of module ...` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:269` | `PUTS( "Loading module using RtlCreateTimer" )

            /* create timer queue */
            i...` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:286` | `PUTS( "Loading module using RtlQueueWorkItem" )

            /* call LoadLibraryW and load specif...` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:626` | `PUTS( "Enable Wow64 process support" )
        if ( ! Instance->Win32.Wow64DisableWow64FsRedirect...` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:671` | `PUTS( "CreateProcessWithTokenW" )
            if ( ! Instance->Win32.CreateProcessWithTokenW(
   ...` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:693` | `PUTS( "CreateProcessWithLogonW" )
            PRINTF( "lpUser[%s] lpDomain[%s] lpPassword[%s]", I...` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:739` | `PUTS( "Send info back" )
        if ( ! CmdLine )` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:831` | `PUTS( "Failed to terminate process" )
    }

END:
    if ( OpenedHandle )` |
| `PUTS` | function | `payloads/Demon/src/core/Win32.c:1011` | `PUTS( "Start reading anon pipe" )
    PRINTF( "AnonPipes->StdOutRead => %x\n", AnonPipes->StdOutR...` |
| `PipeRead` | function | `payloads/Demon/src/core/Win32.c:1175` | `BOOL PipeRead(
    IN HANDLE  Handle,
    IN PBUFFER Buffer
)` |
| `PipeWrite` | function | `payloads/Demon/src/core/Win32.c:1202` | `BOOL PipeWrite(
    IN  HANDLE   Handle,
    OUT PBUFFER Buffer
)` |
| `ProcessCreate` | function | `payloads/Demon/src/core/Win32.c:579` | `BOOL ProcessCreate(
    IN  BOOL                 x86,
    IN  LPWSTR               App,
    IN  L...` |
| `ProcessIsWow` | function | `payloads/Demon/src/core/Win32.c:544` | `BOOL ProcessIsWow(
    IN HANDLE Process
)` |
| `ProcessOpen` | function | `payloads/Demon/src/core/Win32.c:515` | `HANDLE ProcessOpen(
    IN DWORD Pid,
    IN DWORD Access
)` |
| `ProcessSnapShot` | function | `payloads/Demon/src/core/Win32.c:848` | `NTSTATUS ProcessSnapShot(
    OUT PSYSTEM_PROCESS_INFORMATION* SnapShot,
    OUT PSIZE_T         ...` |
| `ProcessTerminate` | function | `payloads/Demon/src/core/Win32.c:806` | `BOOL ProcessTerminate(
    IN HANDLE hProcess,
    IN DWORD  Pid)` |
| `RandomBool` | function | `payloads/Demon/src/core/Win32.c:1321` | `BOOL RandomBool(
    VOID
)` |
| `RandomNumber32` | function | `payloads/Demon/src/core/Win32.c:1304` | `ULONG RandomNumber32(
    VOID
)` |
| `ReadLocalFile` | function | `payloads/Demon/src/core/Win32.c:886` | `BOOL ReadLocalFile(
    IN  LPCWSTR FileName,
    OUT PVOID*  FileContent,
    OUT PDWORD  FileSi...` |
| `SharedSleep` | function | `payloads/Demon/src/core/Win32.c:1357` | `VOID SharedSleep(
    ULONG64 Delay
)` |
| `SharedTimestamp` | function | `payloads/Demon/src/core/Win32.c:1337` | `ULONG64 SharedTimestamp(
    VOID
)` |
| `ShuffleArray` | function | `payloads/Demon/src/core/Win32.c:1379` | `VOID ShuffleArray(
    _Inout_ PVOID* array,
    IN     SIZE_T n
)` |
| `WinScreenshot` | function | `payloads/Demon/src/core/Win32.c:1052` | `BOOL WinScreenshot(
    OUT PVOID*  ImagePointer,
    OUT PSIZE_T ImageSize
)` |
| `___chkstk_ms` | function | `payloads/Demon/src/core/Win32.c:1396` | `VOID volatile ___chkstk_ms(
        VOID
)` |
| `listDir` | function | `payloads/Demon/src/core/Win32.c:1478` | `PROOT_DIR listDir(
    IN LPWSTR StartPath,
    IN BOOL   SubDirs,
    IN BOOL   FilesOnly,
    I...` |
| `AddRoundKey` | function | `payloads/Demon/src/crypt/AesCrypt.c:111` | `static void AddRoundKey(UINT8 round, state_t* state, const UINT8* RoundKey)` |
| `AesInit` | function | `payloads/Demon/src/crypt/AesCrypt.c:103` | `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv)` |
| `AesXCryptBuffer` | function | `payloads/Demon/src/crypt/AesCrypt.c:217` | `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length)` |
| `KeyExpansion` | function | `payloads/Demon/src/crypt/AesCrypt.c:47` | `void KeyExpansion(UINT8* RoundKey, const UINT8* Key)` |
| `MULTIPLY_AS_A_FUNCTION` | macro | `payloads/Demon/src/crypt/AesCrypt.c:18` | `#define MULTIPLY_AS_A_FUNCTION` |
| `MixColumns` | function | `payloads/Demon/src/crypt/AesCrypt.c:174` | `static void MixColumns(state_t* state)` |
| `Nb` | macro | `payloads/Demon/src/crypt/AesCrypt.c:4` | `#define Nb` |
| `Nk` | macro | `payloads/Demon/src/crypt/AesCrypt.c:7` | `#define Nk` |
| `Nk` | macro | `payloads/Demon/src/crypt/AesCrypt.c:10` | `#define Nk` |
| `Nk` | macro | `payloads/Demon/src/crypt/AesCrypt.c:13` | `#define Nk` |
| `Nr` | macro | `payloads/Demon/src/crypt/AesCrypt.c:8` | `#define Nr` |
| `Nr` | macro | `payloads/Demon/src/crypt/AesCrypt.c:11` | `#define Nr` |
| `Nr` | macro | `payloads/Demon/src/crypt/AesCrypt.c:14` | `#define Nr` |
| `ShiftRows` | function | `payloads/Demon/src/crypt/AesCrypt.c:140` | `static void ShiftRows(state_t* state)` |
| `SubBytes` | function | `payloads/Demon/src/crypt/AesCrypt.c:125` | `static void SubBytes(state_t* state)` |
| `getSBoxValue` | macro | `payloads/Demon/src/crypt/AesCrypt.c:45` | `#define getSBoxValue(num)` |
| `xtime` | function | `payloads/Demon/src/crypt/AesCrypt.c:168` | `static UINT8 xtime(UINT8 x)` |
| `DllInjectReflective` | function | `payloads/Demon/src/inject/Inject.c:172` | `DWORD DllInjectReflective( HANDLE hTargetProcess, LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuff...` |
| `DllSpawnReflective` | function | `payloads/Demon/src/inject/Inject.c:322` | `DWORD DllSpawnReflective( LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuffer, DWORD DllLength, PVO...` |
| `Inject` | function | `payloads/Demon/src/inject/Inject.c:27` | `DWORD Inject(
    IN BYTE   Method,
    IN HANDLE Handle,
    IN DWORD  Pid,
    IN BOOL   x64,
 ...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:64` | `PRINTF( "[INJECT] Using specified process handle: %x\n", Process )
    }

    /* check the archit...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:91` | `PRINTF( "[INJECT] Allocated memory in the remote process: %p\n", Memory )
    }

    /* write pay...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:99` | `PRINTF( "[INJECT] Wrote payload into remote process: %d written\n", Size )
    }

    /* change a...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:118` | `PRINTF( "[INJECT] Allocated argument memory in the remote process: %p\n", Param )
        }

    ...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:126` | `PRINTF( "[INJECT] Wrote argument into remote process: %d written\n", Argc )
        }
    }

    ...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:135` | `PRINTF( "[INJECT] Failed to create a new thread: %d\n", NtGetLastError() )
    }

END:
    PUTS( ...` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:232` | `PRINTF( "Params: Size:[%d] Pointer:[%p]\n", ParamSize, Parameter )
    if ( ParamSize > 0 )` |
| `PRINTF` | function | `payloads/Demon/src/inject/Inject.c:278` | `PRINTF( "ctx->Parameter: %p\n", ctx->Parameter )

                if ( ! ThreadCreate( THREAD_MET...` |
| `PUTS` | function | `payloads/Demon/src/inject/Inject.c:107` | `PUTS( "[INJECT] Changed memory protection from RW to RX" )
    }

    /* check if any args has be...` |
| `GetPeArch` | function | `payloads/Demon/src/inject/InjectUtil.c:72` | `DWORD GetPeArch( PVOID PeBytes )` |
| `GetReflectiveLoaderOffset` | function | `payloads/Demon/src/inject/InjectUtil.c:36` | `DWORD GetReflectiveLoaderOffset( PVOID ReflectiveLdrAddr )` |
| `NTSTATUS` | type_alias | `payloads/Demon/src/inject/InjectUtil.c:9` | `typedef ULONG NTSTATUS;` |
| `Rva2Offset` | function | `payloads/Demon/src/inject/InjectUtil.c:12` | `DWORD Rva2Offset( DWORD dwRva, UINT_PTR uiBaseAddress )` |
| `DllMain` | function | `payloads/Demon/src/main/MainDll.c:24` | `DLLEXPORT BOOL WINAPI DllMain(
    IN     HINSTANCE hDllBase,
    IN     DWORD     Reason,
    _I...` |
| `Start` | function | `payloads/Demon/src/main/MainDll.c:8` | `DLLEXPORT VOID Start(  )` |
| `WinMain` | function | `payloads/Demon/src/main/MainExe.c:3` | `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )` |
| `SrvCtrlHandler` | function | `payloads/Demon/src/main/MainSvc.c:41` | `VOID WINAPI SrvCtrlHandler( DWORD CtrlCode )` |
| `SvcMain` | function | `payloads/Demon/src/main/MainSvc.c:31` | `VOID WINAPI SvcMain( DWORD dwArgc, LPTSTR* Argv )` |
| `WinMain` | function | `payloads/Demon/src/main/MainSvc.c:16` | `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )` |
| `C_PTR` | macro | `payloads/DllLdr/Include/Core.h:18` | `#define C_PTR( x )` |
| `DLLEXPORT` | macro | `payloads/DllLdr/Include/Core.h:12` | `#define DLLEXPORT` |
| `DLL_QUERY_HMODULE` | macro | `payloads/DllLdr/Include/Core.h:21` | `#define DLL_QUERY_HMODULE` |
| `FORCE_INLINE` | macro | `payloads/DllLdr/Include/Core.h:14` | `#define FORCE_INLINE` |
| `IMAGE_REL_TYPE` | macro | `payloads/DllLdr/Include/Core.h:24` | `#define IMAGE_REL_TYPE` |
| `IMAGE_REL_TYPE` | macro | `payloads/DllLdr/Include/Core.h:26` | `#define IMAGE_REL_TYPE` |
| `Modules` | struct | `payloads/DllLdr/Include/Core.h:36` | `` |
| `NAKED` | macro | `payloads/DllLdr/Include/Core.h:13` | `#define NAKED` |
| `NTDLL_HASH` | macro | `payloads/DllLdr/Include/Core.h:5` | `#define NTDLL_HASH` |
| `RVA2VA` | macro | `payloads/DllLdr/Include/Core.h:19` | `#define RVA2VA(type, base, rva)` |
| `SYS_LDRLOADDLL` | macro | `payloads/DllLdr/Include/Core.h:7` | `#define SYS_LDRLOADDLL` |
| `SYS_NTALLOCATEVIRTUALMEMORY` | macro | `payloads/DllLdr/Include/Core.h:8` | `#define SYS_NTALLOCATEVIRTUALMEMORY` |
| `SYS_NTFLUSHINSTRUCTIONCACHE` | macro | `payloads/DllLdr/Include/Core.h:10` | `#define SYS_NTFLUSHINSTRUCTIONCACHE` |
| `SYS_NTPROTECTEDVIRTUALMEMORY` | macro | `payloads/DllLdr/Include/Core.h:9` | `#define SYS_NTPROTECTEDVIRTUALMEMORY` |
| `U_PTR` | macro | `payloads/DllLdr/Include/Core.h:17` | `#define U_PTR( x )` |
| `WIN32_FUNC` | macro | `payloads/DllLdr/Include/Core.h:15` | `#define WIN32_FUNC( x )` |
| `C_PTR` | macro | `payloads/DllLdr/Include/Macro.h:14` | `#define C_PTR( x )` |
| `GET_SYMBOL` | macro | `payloads/DllLdr/Include/Macro.h:17` | `#define GET_SYMBOL( x )` |
| `HASH_KEY` | macro | `payloads/DllLdr/Include/Macro.h:4` | `#define HASH_KEY` |
| `NtCurrentProcess` | macro | `payloads/DllLdr/Include/Macro.h:15` | `#define NtCurrentProcess()` |
| `PPEB_PTR` | macro | `payloads/DllLdr/Include/Macro.h:7` | `#define PPEB_PTR` |
| `PPEB_PTR` | macro | `payloads/DllLdr/Include/Macro.h:9` | `#define PPEB_PTR` |
| `SEC` | macro | `payloads/DllLdr/Include/Macro.h:12` | `#define SEC( s, x )` |
| `U_PTR` | macro | `payloads/DllLdr/Include/Macro.h:13` | `#define U_PTR( x )` |
| `DosPath` | type_alias | `payloads/DllLdr/Include/Native.h:8` | `typedef struct _CURDIR { myUNICODE_STRING DosPath;` |
| `GDI_HANDLE_BUFFER` | type_alias | `payloads/DllLdr/Include/Native.h:26` | `typedef ULONG GDI_HANDLE_BUFFER[GDI_HANDLE_BUFFER_SIZE];` |
| `GDI_HANDLE_BUFFER32` | type_alias | `payloads/DllLdr/Include/Native.h:23` | `typedef ULONG GDI_HANDLE_BUFFER32[GDI_HANDLE_BUFFER_SIZE32];` |
| `GDI_HANDLE_BUFFER64` | type_alias | `payloads/DllLdr/Include/Native.h:25` | `typedef ULONG GDI_HANDLE_BUFFER64[GDI_HANDLE_BUFFER_SIZE64];` |
| `GDI_HANDLE_BUFFER_SIZE` | macro | `payloads/DllLdr/Include/Native.h:19` | `#define GDI_HANDLE_BUFFER_SIZE` |
| `GDI_HANDLE_BUFFER_SIZE` | macro | `payloads/DllLdr/Include/Native.h:21` | `#define GDI_HANDLE_BUFFER_SIZE` |
| `GDI_HANDLE_BUFFER_SIZE32` | macro | `payloads/DllLdr/Include/Native.h:15` | `#define GDI_HANDLE_BUFFER_SIZE32` |
| `GDI_HANDLE_BUFFER_SIZE64` | macro | `payloads/DllLdr/Include/Native.h:16` | `#define GDI_HANDLE_BUFFER_SIZE64` |
| `InLoadOrderLinks` | type_alias | `payloads/DllLdr/Include/Native.h:172` | `typedef struct _LDR_DATA_TABLE_ENTRY { LIST_ENTRY InLoadOrderLinks;` |
| `InheritedAddressSpace` | type_alias | `payloads/DllLdr/Include/Native.h:40` | `typedef struct _PEB { BOOLEAN InheritedAddressSpace;` |
| `Length` | type_alias | `payloads/DllLdr/Include/Native.h:1` | `typedef struct _myUNICODE_STRING { USHORT Length;` |
| `Length` | type_alias | `payloads/DllLdr/Include/Native.h:27` | `typedef struct _PEB_LDR_DATA { ULONG Length;` |
| `_CURDIR` | struct | `payloads/DllLdr/Include/Native.h:9` | `` |
| `_LDR_DATA_TABLE_ENTRY` | struct | `payloads/DllLdr/Include/Native.h:173` | `` |
| `_PEB` | struct | `payloads/DllLdr/Include/Native.h:41` | `` |
| `_PEB_LDR_DATA` | struct | `payloads/DllLdr/Include/Native.h:28` | `` |
| `_myUNICODE_STRING` | struct | `payloads/DllLdr/Include/Native.h:2` | `` |
| `main` | function | `payloads/DllLdr/Scripts/extract.py:8` | `def main(options)` |
| `CopyDotStr` | function | `payloads/DllLdr/Source/Entry.c:206` | `FORCE_INLINE UINT32 CopyDotStr( PCHAR String )` |
| `KCharStringToWCharString` | function | `payloads/DllLdr/Source/Entry.c:409` | `SIZE_T KCharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )` |
| `KGetModuleByHash` | function | `payloads/DllLdr/Source/Entry.c:185` | `PVOID KGetModuleByHash( DWORD ModuleHash )` |
| `KGetProcAddressByHash` | function | `payloads/DllLdr/Source/Entry.c:215` | `PVOID KGetProcAddressByHash( PINSTANCE Instance, PVOID DllModuleBase, DWORD FunctionHash, DWORD O...` |
| `KHashString` | function | `payloads/DllLdr/Source/Entry.c:364` | `DWORD KHashString( PVOID String, SIZE_T Length )` |
| `KLoadLibrary` | function | `payloads/DllLdr/Source/Entry.c:331` | `PVOID KLoadLibrary( PINSTANCE Instance, LPSTR ModuleName )` |
| `KReAllocSections` | function | `payloads/DllLdr/Source/Entry.c:306` | `VOID KReAllocSections( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir )` |
| `KResolveIAT` | function | `payloads/DllLdr/Source/Entry.c:265` | `VOID KResolveIAT( PINSTANCE Instance, LPVOID KaynImage, LPVOID IatDir )` |
| `KStringLengthA` | function | `payloads/DllLdr/Source/Entry.c:393` | `SIZE_T KStringLengthA( LPCSTR String )` |
| `KStringLengthW` | function | `payloads/DllLdr/Source/Entry.c:400` | `SIZE_T KStringLengthW(LPCWSTR String)` |
| `KaynCaller` | function | `payloads/DllLdr/Source/Entry.c:144` | `NAKED LPVOID KaynCaller( PVOID StartAddress )` |
| `KaynLoader` | function | `payloads/DllLdr/Source/Entry.c:5` | `DLLEXPORT VOID KaynLoader( LPVOID lpParameter )` |
| `Memcpy` | function | `payloads/DllLdr/Source/Entry.c:166` | `NAKED VOID Memcpy( PVOID Destination, PVOID source, SIZE_T Size )` |
| `MemCopy` | macro | `payloads/Shellcode/Include/Core.h:10` | `#define MemCopy` |
| `Modules` | struct | `payloads/Shellcode/Include/Core.h:29` | `` |
| `NTDLL_HASH` | macro | `payloads/Shellcode/Include/Core.h:11` | `#define NTDLL_HASH` |
| `PAGE_SIZE` | macro | `payloads/Shellcode/Include/Core.h:9` | `#define PAGE_SIZE` |
| `SYS_LDRLOADDLL` | macro | `payloads/Shellcode/Include/Core.h:13` | `#define SYS_LDRLOADDLL` |
| `SYS_NTALLOCATEVIRTUALMEMORY` | macro | `payloads/Shellcode/Include/Core.h:14` | `#define SYS_NTALLOCATEVIRTUALMEMORY` |
| `SYS_NTPROTECTEDVIRTUALMEMORY` | macro | `payloads/Shellcode/Include/Core.h:15` | `#define SYS_NTPROTECTEDVIRTUALMEMORY` |
| `C_PTR` | macro | `payloads/Shellcode/Include/Macro.h:12` | `#define C_PTR( x )` |
| `GET_SYMBOL` | macro | `payloads/Shellcode/Include/Macro.h:15` | `#define GET_SYMBOL( x )` |
| `NtCurrentProcess` | macro | `payloads/Shellcode/Include/Macro.h:13` | `#define NtCurrentProcess()` |
| `PPEB_PTR` | macro | `payloads/Shellcode/Include/Macro.h:5` | `#define PPEB_PTR` |
| `PPEB_PTR` | macro | `payloads/Shellcode/Include/Macro.h:7` | `#define PPEB_PTR` |
| `SEC` | macro | `payloads/Shellcode/Include/Macro.h:10` | `#define SEC( s, x )` |
| `U_PTR` | macro | `payloads/Shellcode/Include/Macro.h:11` | `#define U_PTR( x )` |
| `Hash` | function | `payloads/Shellcode/Scripts/Hasher.c:4` | `long Hash( char* String )` |
| `ToUpperString` | function | `payloads/Shellcode/Scripts/Hasher.c:15` | `void ToUpperString(char * temp)` |
| `main` | function | `payloads/Shellcode/Scripts/Hasher.c:24` | `int main(int argc, char** argv)` |
| `IMAGE_REL_TYPE` | macro | `payloads/Shellcode/Source/Entry.c:6` | `#define IMAGE_REL_TYPE` |
| `IMAGE_REL_TYPE` | macro | `payloads/Shellcode/Source/Entry.c:8` | `#define IMAGE_REL_TYPE` |
| `KaynLdrReloc` | function | `payloads/Shellcode/Source/Entry.c:104` | `VOID KaynLdrReloc( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir, DWORD KHdrSize )` |
| `SEC` | function | `payloads/Shellcode/Source/Entry.c:11` | `SEC( text, B ) VOID Entry( VOID )` |
| `SEC` | function | `payloads/Shellcode/Source/Utils.c:4` | `SEC( text, B ) UINT_PTR HashString( LPVOID String, UINT_PTR Length )` |
| `SEC` | function | `payloads/Shellcode/Source/Win32.c:5` | `SEC( text, B ) UINT_PTR LdrModulePeb( UINT_PTR hModuleHash )` |
| `SEC` | function | `payloads/Shellcode/Source/Win32.c:23` | `SEC( text, B ) PVOID LdrFunctionAddr( UINT_PTR Module, UINT_PTR FunctionHash )` |
| `init` | function | `teamserver/cmd/cmd.go:29` | `func init(` |
| `startMenu` | function | `teamserver/cmd/cmd.go:61` | `func startMenu(` |
| `teamserverFunc` | function | `teamserver/cmd/cmd.go:47` | `func teamserverFunc(` |
| `AgentAdd` | function | `teamserver/cmd/server/agent.go:108` | `func (t *Teamserver) AgentAdd(` |
| `AgentCallback` | function | `teamserver/cmd/server/agent.go:220` | `func (t *Teamserver) AgentCallback(` |
| `AgentCallbackSize` | function | `teamserver/cmd/server/agent.go:138` | `func (t *Teamserver) AgentCallbackSize(` |
| `AgentConsole` | function | `teamserver/cmd/server/agent.go:198` | `func (t *Teamserver) AgentConsole(` |
| `AgentExist` | function | `teamserver/cmd/server/agent.go:183` | `func (t *Teamserver) AgentExist(` |
| `AgentHasDied` | function | `teamserver/cmd/server/agent.go:102` | `func (t *Teamserver) AgentHasDied(` |
| `AgentInstance` | function | `teamserver/cmd/server/agent.go:155` | `func (t *Teamserver) AgentInstance(` |
| `AgentLastTimeCalled` | function | `teamserver/cmd/server/agent.go:166` | `func (t *Teamserver) AgentLastTimeCalled(` |
| `AgentSendNotify` | function | `teamserver/cmd/server/agent.go:123` | `func (t *Teamserver) AgentSendNotify(` |
| `AgentUpdate` | function | `teamserver/cmd/server/agent.go:16` | `func (t *Teamserver) AgentUpdate(` |
| `Died` | function | `teamserver/cmd/server/agent.go:23` | `func (t *Teamserver) Died(` |
| `GetDotNetPipeTemplate` | function | `teamserver/cmd/server/agent.go:237` | `func (t *Teamserver) GetDotNetPipeTemplate(` |
| `LinkAdd` | function | `teamserver/cmd/server/agent.go:66` | `func (t *Teamserver) LinkAdd(` |
| `LinkRemove` | function | `teamserver/cmd/server/agent.go:78` | `func (t *Teamserver) LinkRemove(` |
| `LinksOf` | function | `teamserver/cmd/server/agent.go:60` | `func (t *Teamserver) LinksOf(` |
| `ParentOf` | function | `teamserver/cmd/server/agent.go:53` | `func (t *Teamserver) ParentOf(` |
| `PythonModuleCallback` | function | `teamserver/cmd/server/agent.go:208` | `func (t *Teamserver) PythonModuleCallback(` |
| `SendLogs` | function | `teamserver/cmd/server/agent.go:233` | `func (t *Teamserver) SendLogs(` |
| `UnlinkFromAll` | function | `teamserver/cmd/server/agent.go:30` | `func (t *Teamserver) UnlinkFromAll(` |
| `DispatchEvent` | function | `teamserver/cmd/server/dispatch.go:20` | `func (t *Teamserver) DispatchEvent(` |
| `ListenerAdd` | function | `teamserver/cmd/server/listener.go:220` | `func (t *Teamserver) ListenerAdd(` |
| `ListenerEdit` | function | `teamserver/cmd/server/listener.go:192` | `func (t *Teamserver) ListenerEdit(` |
| `ListenerExist` | function | `teamserver/cmd/server/listener.go:113` | `func (t *Teamserver) ListenerExist(` |
| `ListenerGetInfo` | function | `teamserver/cmd/server/listener.go:124` | `func (t *Teamserver) ListenerGetInfo(` |
| `ListenerRemove` | function | `teamserver/cmd/server/listener.go:144` | `func (t *Teamserver) ListenerRemove(` |
| `ListenerServiceExc2Add` | function | `teamserver/cmd/server/listener.go:337` | `func (t *Teamserver) ListenerServiceExc2Add(` |
| `ListenerStart` | function | `teamserver/cmd/server/listener.go:19` | `func (t *Teamserver) ListenerStart(` |
| `ListenerStartNotify` | function | `teamserver/cmd/server/listener.go:378` | `func (t *Teamserver) ListenerStartNotify(` |
| `ServiceAgent` | function | `teamserver/cmd/server/service.go:9` | `func (t *Teamserver) ServiceAgent(` |
| `ServiceAgentExist` | function | `teamserver/cmd/server/service.go:20` | `func (t *Teamserver) ServiceAgentExist(` |
| `ClientAuthenticate` | function | `teamserver/cmd/server/teamserver.go:637` | `func (t *Teamserver) ClientAuthenticate(` |
| `EndpointAdd` | function | `teamserver/cmd/server/teamserver.go:933` | `func (t *Teamserver) EndpointAdd(` |
| `EndpointRemove` | function | `teamserver/cmd/server/teamserver.go:945` | `func (t *Teamserver) EndpointRemove(` |
| `EventAgentMark` | function | `teamserver/cmd/server/teamserver.go:713` | `func (t *Teamserver) EventAgentMark(` |
| `EventAppend` | function | `teamserver/cmd/server/teamserver.go:797` | `func (t *Teamserver) EventAppend(` |
| `EventBroadcast` | function | `teamserver/cmd/server/teamserver.go:690` | `func (t *Teamserver) EventBroadcast(` |
| `EventListenerError` | function | `teamserver/cmd/server/teamserver.go:720` | `func (t *Teamserver) EventListenerError(` |
| `EventNewDemon` | function | `teamserver/cmd/server/teamserver.go:709` | `func (t *Teamserver) EventNewDemon(` |
| `EventRemove` | function | `teamserver/cmd/server/teamserver.go:812` | `func (t *Teamserver) EventRemove(` |
| `FindSystemPackages` | function | `teamserver/cmd/server/teamserver.go:842` | `func (t *Teamserver) FindSystemPackages(` |
| `NewTeamserver` | function | `teamserver/cmd/server/teamserver.go:37` | `func NewTeamserver(` |
| `RemoveClient` | function | `teamserver/cmd/server/teamserver.go:773` | `func (t *Teamserver) RemoveClient(` |
| `SendAllPackagesToNewClient` | function | `teamserver/cmd/server/teamserver.go:818` | `func (t *Teamserver) SendAllPackagesToNewClient(` |
| `SendEvent` | function | `teamserver/cmd/server/teamserver.go:741` | `func (t *Teamserver) SendEvent(` |
| `SetProfile` | function | `teamserver/cmd/server/teamserver.go:626` | `func (t *Teamserver) SetProfile(` |
| `SetServerFlags` | function | `teamserver/cmd/server/teamserver.go:48` | `func (t *Teamserver) SetServerFlags(` |
| `Start` | function | `teamserver/cmd/server/teamserver.go:52` | `func (t *Teamserver) Start(` |
| `handleRequest` | function | `teamserver/cmd/server/teamserver.go:497` | `func (t *Teamserver) handleRequest(` |
| `Client` | struct | `teamserver/cmd/server/types.go:22` | `` |
| `Endpoint` | struct | `teamserver/cmd/server/types.go:68` | `` |
| `Listener` | struct | `teamserver/cmd/server/types.go:16` | `` |
| `Teamserver` | struct | `teamserver/cmd/server/types.go:73` | `` |
| `TeamserverFlags` | struct | `teamserver/cmd/server/types.go:63` | `` |
| `Users` | struct | `teamserver/cmd/server/types.go:34` | `` |
| `serverFlags` | struct | `teamserver/cmd/server/types.go:41` | `` |
| `utilFlags` | struct | `teamserver/cmd/server/types.go:53` | `` |
| `main` | function | `teamserver/main.go:6` | `func main(` |
| `AddJobToQueue` | function | `teamserver/pkg/agent/agent.go:647` | `func (a *Agent) AddJobToQueue(` |
| `AddRequest` | function | `teamserver/pkg/agent/agent.go:632` | `func (a *Agent) AddRequest(` |
| `AgentsAppend` | function | `teamserver/pkg/agent/agent.go:1238` | `func (agents *Agents) AgentsAppend(` |
| `BuildPayloadMessage` | function | `teamserver/pkg/agent/agent.go:29` | `func BuildPayloadMessage(` |
| `DownloadAdd` | function | `teamserver/pkg/agent/agent.go:816` | `func (a *Agent) DownloadAdd(` |
| `DownloadClose` | function | `teamserver/pkg/agent/agent.go:888` | `func (a *Agent) DownloadClose(` |
| `DownloadGet` | function | `teamserver/pkg/agent/agent.go:902` | `func (a *Agent) DownloadGet(` |
| `DownloadWrite` | function | `teamserver/pkg/agent/agent.go:865` | `func (a *Agent) DownloadWrite(` |
| `GetQueuedJobs` | function | `teamserver/pkg/agent/agent.go:661` | `func (a *Agent) GetQueuedJobs(` |
| `IsKnownRequestID` | function | `teamserver/pkg/agent/agent.go:609` | `func (a *Agent) IsKnownRequestID(` |
| `ParseDemonRegisterRequest` | function | `teamserver/pkg/agent/agent.go:328` | `func ParseDemonRegisterRequest(` |
| `ParseHeader` | function | `teamserver/pkg/agent/agent.go:181` | `func ParseHeader(` |
| `PivotAddJob` | function | `teamserver/pkg/agent/agent.go:746` | `func (a *Agent) PivotAddJob(` |
| `PortFwdClose` | function | `teamserver/pkg/agent/agent.go:1023` | `func (a *Agent) PortFwdClose(` |
| `PortFwdGet` | function | `teamserver/pkg/agent/agent.go:929` | `func (a *Agent) PortFwdGet(` |
| `PortFwdIsOpen` | function | `teamserver/pkg/agent/agent.go:948` | `func (a *Agent) PortFwdIsOpen(` |
| `PortFwdNew` | function | `teamserver/pkg/agent/agent.go:911` | `func (a *Agent) PortFwdNew(` |
| `PortFwdOpen` | function | `teamserver/pkg/agent/agent.go:958` | `func (a *Agent) PortFwdOpen(` |
| `PortFwdRead` | function | `teamserver/pkg/agent/agent.go:997` | `func (a *Agent) PortFwdRead(` |
| `PortFwdWrite` | function | `teamserver/pkg/agent/agent.go:979` | `func (a *Agent) PortFwdWrite(` |
| `RegisterInfoToInstance` | function | `teamserver/pkg/agent/agent.go:215` | `func RegisterInfoToInstance(` |
| `RequestCompleted` | function | `teamserver/pkg/agent/agent.go:638` | `func (a *Agent) RequestCompleted(` |
| `SocksClientAdd` | function | `teamserver/pkg/agent/agent.go:1053` | `func (a *Agent) SocksClientAdd(` |
| `SocksClientClose` | function | `teamserver/pkg/agent/agent.go:1130` | `func (a *Agent) SocksClientClose(` |
| `SocksClientGet` | function | `teamserver/pkg/agent/agent.go:1073` | `func (a *Agent) SocksClientGet(` |
| `SocksClientRead` | function | `teamserver/pkg/agent/agent.go:1096` | `func (a *Agent) SocksClientRead(` |
| `SocksServerRemove` | function | `teamserver/pkg/agent/agent.go:1163` | `func (a *Agent) SocksServerRemove(` |
| `ToJson` | function | `teamserver/pkg/agent/agent.go:1224` | `func (a *Agent) ToJson(` |
| `ToMap` | function | `teamserver/pkg/agent/agent.go:1193` | `func (a *Agent) ToMap(` |
| `UpdateLastCallback` | function | `teamserver/pkg/agent/agent.go:739` | `func (a *Agent) UpdateLastCallback(` |
| `getWindowsVersionString` | function | `teamserver/pkg/agent/agent.go:1243` | `func getWindowsVersionString(` |
| `Console` | function | `teamserver/pkg/agent/demons.go:6430` | `func (a *Agent) Console(` |
| `TaskDispatch` | function | `teamserver/pkg/agent/demons.go:2285` | `func (a *Agent) TaskDispatch(` |
| `TaskPrepare` | function | `teamserver/pkg/agent/demons.go:128` | `func (a *Agent) TaskPrepare(` |
| `TeamserverTaskPrepare` | function | `teamserver/pkg/agent/demons.go:64` | `func (a *Agent) TeamserverTaskPrepare(` |
| `UploadMemFileInChunks` | function | `teamserver/pkg/agent/demons.go:31` | `func (a *Agent) UploadMemFileInChunks(` |
| `Agent` | struct | `teamserver/pkg/agent/types.go:139` | `` |
| `AgentInfo` | struct | `teamserver/pkg/agent/types.go:174` | `` |
| `Agents` | struct | `teamserver/pkg/agent/types.go:212` | `` |
| `BofCallback` | struct | `teamserver/pkg/agent/types.go:104` | `` |
| `DemonInterface` | interface | `teamserver/pkg/agent/types.go:19` | `` |
| `Download` | struct | `teamserver/pkg/agent/types.go:94` | `` |
| `EventInterface` | interface | `teamserver/pkg/agent/types.go:23` | `` |
| `Header` | struct | `teamserver/pkg/agent/types.go:26` | `` |
| `Job` | struct | `teamserver/pkg/agent/types.go:73` | `` |
| `Pivots` | struct | `teamserver/pkg/agent/types.go:89` | `` |
| `PortFwd` | struct | `teamserver/pkg/agent/types.go:111` | `` |
| `ServiceAgentInterface` | interface | `teamserver/pkg/agent/types.go:33` | `` |
| `SocksClient` | struct | `teamserver/pkg/agent/types.go:124` | `` |
| `SocksServer` | struct | `teamserver/pkg/agent/types.go:133` | `` |
| `TeamServer` | interface | `teamserver/pkg/agent/types.go:40` | `` |
| `Build` | function | `teamserver/pkg/common/builder/builder.go:217` | `func (b *Builder) Build(` |
| `Builder` | struct | `teamserver/pkg/common/builder/builder.go:78` | `` |
| `BuilderConfig` | struct | `teamserver/pkg/common/builder/builder.go:70` | `` |
| `Cmd` | function | `teamserver/pkg/common/builder/builder.go:1064` | `func (b *Builder) Cmd(` |
| `CompileCmd` | function | `teamserver/pkg/common/builder/builder.go:1090` | `func (b *Builder) CompileCmd(` |
| `DeletePayload` | function | `teamserver/pkg/common/builder/builder.go:1122` | `func (b *Builder) DeletePayload(` |
| `GetListenerDefines` | function | `teamserver/pkg/common/builder/builder.go:1102` | `func (b *Builder) GetListenerDefines(` |
| `GetOutputPath` | function | `teamserver/pkg/common/builder/builder.go:509` | `func (b *Builder) GetOutputPath(` |
| `GetPayloadBytes` | function | `teamserver/pkg/common/builder/builder.go:1024` | `func (b *Builder) GetPayloadBytes(` |
| `NewBuilder` | function | `teamserver/pkg/common/builder/builder.go:141` | `func NewBuilder(` |
| `Patch` | function | `teamserver/pkg/common/builder/builder.go:513` | `func (b *Builder) Patch(` |
| `PatchConfig` | function | `teamserver/pkg/common/builder/builder.go:561` | `func (b *Builder) PatchConfig(` |
| `SetArch` | function | `teamserver/pkg/common/builder/builder.go:485` | `func (b *Builder) SetArch(` |
| `SetConfig` | function | `teamserver/pkg/common/builder/builder.go:489` | `func (b *Builder) SetConfig(` |
| `SetExtension` | function | `teamserver/pkg/common/builder/builder.go:505` | `func (b *Builder) SetExtension(` |
| `SetFormat` | function | `teamserver/pkg/common/builder/builder.go:481` | `func (b *Builder) SetFormat(` |
| `SetListener` | function | `teamserver/pkg/common/builder/builder.go:459` | `func (b *Builder) SetListener(` |
| `SetOutputPath` | function | `teamserver/pkg/common/builder/builder.go:501` | `func (b *Builder) SetOutputPath(` |
| `SetPatchConfig` | function | `teamserver/pkg/common/builder/builder.go:464` | `func (b *Builder) SetPatchConfig(` |
| `SetSilent` | function | `teamserver/pkg/common/builder/builder.go:213` | `func (b *Builder) SetSilent(` |
| `HTTPSGenerateRSACertificate` | function | `teamserver/pkg/common/certs/https.go:300` | `func HTTPSGenerateRSACertificate(` |
| `generateCertificate` | function | `teamserver/pkg/common/certs/https.go:216` | `func generateCertificate(` |
| `pemBlockForKey` | function | `teamserver/pkg/common/certs/https.go:200` | `func pemBlockForKey(` |
| `publicKey` | function | `teamserver/pkg/common/certs/https.go:182` | `func publicKey(` |
| `randomInt` | function | `teamserver/pkg/common/certs/https.go:193` | `func randomInt(` |
| `randomLocality` | function | `teamserver/pkg/common/certs/https.go:123` | `func randomLocality(` |
| `randomOrganization` | function | `teamserver/pkg/common/certs/https.go:166` | `func randomOrganization(` |
| `randomPostalCode` | function | `teamserver/pkg/common/certs/https.go:144` | `func randomPostalCode(` |
| `randomProvinceLocalityStreetAddress` | function | `teamserver/pkg/common/certs/https.go:137` | `func randomProvinceLocalityStreetAddress(` |
| `randomState` | function | `teamserver/pkg/common/certs/https.go:115` | `func randomState(` |
| `randomStreetAddress` | function | `teamserver/pkg/common/certs/https.go:132` | `func randomStreetAddress(` |
| `randomSubject` | function | `teamserver/pkg/common/certs/https.go:153` | `func randomSubject(` |
| `XCryptBytesAES256` | function | `teamserver/pkg/common/crypt/aes.go:10` | `func XCryptBytesAES256(` |
| `AddBytes` | function | `teamserver/pkg/common/packer/packer.go:70` | `func (p *Packer) AddBytes(` |
| `AddInt` | function | `teamserver/pkg/common/packer/packer.go:45` | `func (p *Packer) AddInt(` |
| `AddInt32` | function | `teamserver/pkg/common/packer/packer.go:37` | `func (p *Packer) AddInt32(` |
| `AddInt64` | function | `teamserver/pkg/common/packer/packer.go:29` | `func (p *Packer) AddInt64(` |
| `AddOwnSizeFirst` | function | `teamserver/pkg/common/packer/packer.go:103` | `func (p *Packer) AddOwnSizeFirst(` |
| `AddString` | function | `teamserver/pkg/common/packer/packer.go:62` | `func (p *Packer) AddString(` |
| `AddUInt32` | function | `teamserver/pkg/common/packer/packer.go:54` | `func (p *Packer) AddUInt32(` |
| `AddWString` | function | `teamserver/pkg/common/packer/packer.go:66` | `func (p *Packer) AddWString(` |
| `Buffer` | function | `teamserver/pkg/common/packer/packer.go:95` | `func (p *Packer) Buffer(` |
| `Build` | function | `teamserver/pkg/common/packer/packer.go:80` | `func (p *Packer) Build(` |
| `NewPacker` | function | `teamserver/pkg/common/packer/packer.go:22` | `func NewPacker(` |
| `Packer` | struct | `teamserver/pkg/common/packer/packer.go:14` | `` |
| `Size` | function | `teamserver/pkg/common/packer/packer.go:99` | `func (p *Packer) Size(` |
| `Buffer` | function | `teamserver/pkg/common/parser/parser.go:201` | `func (p *Parser) Buffer(` |
| `CanIRead` | function | `teamserver/pkg/common/parser/parser.go:31` | `func (p *Parser) CanIRead(` |
| `DecryptBuffer` | function | `teamserver/pkg/common/parser/parser.go:205` | `func (p *Parser) DecryptBuffer(` |
| `Length` | function | `teamserver/pkg/common/parser/parser.go:197` | `func (p *Parser) Length(` |
| `NewParser` | function | `teamserver/pkg/common/parser/parser.go:24` | `func NewParser(` |
| `ParseAtLeastBytes` | function | `teamserver/pkg/common/parser/parser.go:177` | `func (p *Parser) ParseAtLeastBytes(` |
| `ParseBool` | function | `teamserver/pkg/common/parser/parser.go:130` | `func (p *Parser) ParseBool(` |
| `ParseBytes` | function | `teamserver/pkg/common/parser/parser.go:162` | `func (p *Parser) ParseBytes(` |
| `ParseInt32` | function | `teamserver/pkg/common/parser/parser.go:82` | `func (p *Parser) ParseInt32(` |
| `ParseInt64` | function | `teamserver/pkg/common/parser/parser.go:106` | `func (p *Parser) ParseInt64(` |
| `ParsePointer` | function | `teamserver/pkg/common/parser/parser.go:154` | `func (p *Parser) ParsePointer(` |
| `ParseString` | function | `teamserver/pkg/common/parser/parser.go:193` | `func (p *Parser) ParseString(` |
| `ParseUTF16String` | function | `teamserver/pkg/common/parser/parser.go:189` | `func (p *Parser) ParseUTF16String(` |
| `Parser` | struct | `teamserver/pkg/common/parser/parser.go:19` | `` |
| `SetBigEndian` | function | `teamserver/pkg/common/parser/parser.go:158` | `func (p *Parser) SetBigEndian(` |
| `Bmp2Png` | function | `teamserver/pkg/common/util.go:76` | `func Bmp2Png(` |
| `ByteCountSI` | function | `teamserver/pkg/common/util.go:144` | `func ByteCountSI(` |
| `DecodeUTF16` | function | `teamserver/pkg/common/util.go:99` | `func DecodeUTF16(` |
| `EncodeUTF16` | function | `teamserver/pkg/common/util.go:118` | `func EncodeUTF16(` |
| `EncodeUTF8` | function | `teamserver/pkg/common/util.go:135` | `func EncodeUTF8(` |
| `EpochTimeToSystemTime` | function | `teamserver/pkg/common/util.go:209` | `func EpochTimeToSystemTime(` |
| `GeneratePipeName` | function | `teamserver/pkg/common/util.go:227` | `func GeneratePipeName(` |
| `GetInterfaceIpv4Addr` | function | `teamserver/pkg/common/util.go:279` | `func GetInterfaceIpv4Addr(` |
| `GetRandomChar` | function | `teamserver/pkg/common/util.go:222` | `func GetRandomChar(` |
| `Int32ToIpString` | function | `teamserver/pkg/common/util.go:198` | `func Int32ToIpString(` |
| `Int32ToLittle` | function | `teamserver/pkg/common/util.go:175` | `func Int32ToLittle(` |
| `IpStringToInt32` | function | `teamserver/pkg/common/util.go:189` | `func IpStringToInt32(` |
| `ParseWorkingHours` | function | `teamserver/pkg/common/util.go:26` | `func ParseWorkingHours(` |
| `PercentageChange` | function | `teamserver/pkg/common/util.go:185` | `func PercentageChange(` |
| `RandomString` | function | `teamserver/pkg/common/util.go:166` | `func RandomString(` |
| `StripNull` | function | `teamserver/pkg/common/util.go:181` | `func StripNull(` |
| `XorCipher` | function | `teamserver/pkg/common/util.go:158` | `func XorCipher(` |
| `AgentAdd` | function | `teamserver/pkg/db/agents.go:12` | `func (db *DB) AgentAdd(` |
| `AgentAll` | function | `teamserver/pkg/db/agents.go:211` | `func (db *DB) AgentAll(` |
| `AgentExist` | function | `teamserver/pkg/db/agents.go:163` | `func (db *DB) AgentExist(` |
| `AgentHasDied` | function | `teamserver/pkg/db/agents.go:145` | `func (db *DB) AgentHasDied(` |
| `AgentRemove` | function | `teamserver/pkg/db/agents.go:192` | `func (db *DB) AgentRemove(` |
| `AgentUpdate` | function | `teamserver/pkg/db/agents.go:81` | `func (db *DB) AgentUpdate(` |
| `DB` | struct | `teamserver/pkg/db/db.go:10` | `` |
| `DatabaseNew` | function | `teamserver/pkg/db/db.go:16` | `func DatabaseNew(` |
| `Existed` | function | `teamserver/pkg/db/db.go:69` | `func (db *DB) Existed(` |
| `Path` | function | `teamserver/pkg/db/db.go:73` | `func (db *DB) Path(` |
| `init` | function | `teamserver/pkg/db/db.go:48` | `func (db *DB) init(` |
| `LinkAdd` | function | `teamserver/pkg/db/links.go:8` | `func (db *DB) LinkAdd(` |
| `LinkExist` | function | `teamserver/pkg/db/links.go:46` | `func (db *DB) LinkExist(` |
| `LinkRemove` | function | `teamserver/pkg/db/links.go:136` | `func (db *DB) LinkRemove(` |
| `LinksOf` | function | `teamserver/pkg/db/links.go:104` | `func (db *DB) LinksOf(` |
| `ParentOf` | function | `teamserver/pkg/db/links.go:75` | `func (db *DB) ParentOf(` |
| `ListenerAdd` | function | `teamserver/pkg/db/listeners.go:8` | `func (db *DB) ListenerAdd(` |
| `ListenerAll` | function | `teamserver/pkg/db/listeners.go:66` | `func (db *DB) ListenerAll(` |
| `ListenerCount` | function | `teamserver/pkg/db/listeners.go:107` | `func (db *DB) ListenerCount(` |
| `ListenerExist` | function | `teamserver/pkg/db/listeners.go:46` | `func (db *DB) ListenerExist(` |
| `ListenerNames` | function | `teamserver/pkg/db/listeners.go:126` | `func (db *DB) ListenerNames(` |
| `ListenerRemove` | function | `teamserver/pkg/db/listeners.go:152` | `func (db *DB) ListenerRemove(` |
| `NewUserConnected` | function | `teamserver/pkg/events/chatlog.go:11` | `func (chatLog) NewUserConnected(` |
| `UserDisconnected` | function | `teamserver/pkg/events/chatlog.go:27` | `func (chatLog) UserDisconnected(` |
| `CallBack` | function | `teamserver/pkg/events/demons.go:105` | `func (demons) CallBack(` |
| `DemonOutput` | function | `teamserver/pkg/events/demons.go:83` | `func (demons) DemonOutput(` |
| `MarkAs` | function | `teamserver/pkg/events/demons.go:121` | `func (demons) MarkAs(` |
| `NewDemon` | function | `teamserver/pkg/events/demons.go:19` | `func (demons) NewDemon(` |
| `Authenticated` | function | `teamserver/pkg/events/events.go:22` | `func Authenticated(` |
| `SendProfile` | function | `teamserver/pkg/events/events.go:88` | `func SendProfile(` |
| `UserAlreadyExits` | function | `teamserver/pkg/events/events.go:56` | `func UserAlreadyExits(` |
| `UserDoNotExists` | function | `teamserver/pkg/events/events.go:72` | `func UserDoNotExists(` |
| `SendConsoleMessage` | function | `teamserver/pkg/events/gate.go:30` | `func (g gate) SendConsoleMessage(` |
| `SendStageless` | function | `teamserver/pkg/events/gate.go:12` | `func (g gate) SendStageless(` |
| `ListenerAdd` | function | `teamserver/pkg/events/listeners.go:15` | `func (listeners) ListenerAdd(` |
| `ListenerEdit` | function | `teamserver/pkg/events/listeners.go:97` | `func (listeners) ListenerEdit(` |
| `ListenerError` | function | `teamserver/pkg/events/listeners.go:154` | `func (listeners) ListenerError(` |
| `ListenerMark` | function | `teamserver/pkg/events/listeners.go:187` | `func (listeners) ListenerMark(` |
| `ListenerRemove` | function | `teamserver/pkg/events/listeners.go:173` | `func (listeners) ListenerRemove(` |
| `AgentRegister` | function | `teamserver/pkg/events/service.go:11` | `func (service) AgentRegister(` |
| `ListenerRegister` | function | `teamserver/pkg/events/service.go:25` | `func (service) ListenerRegister(` |
| `Logger` | function | `teamserver/pkg/events/teamserver.go:11` | `func (teamserver) Logger(` |
| `Profile` | function | `teamserver/pkg/events/teamserver.go:25` | `func (teamserver) Profile(` |
| `NewExternal` | function | `teamserver/pkg/handlers/external.go:15` | `func NewExternal(` |
| `Request` | function | `teamserver/pkg/handlers/external.go:37` | `func (e *External) Request(` |
| `Start` | function | `teamserver/pkg/handlers/external.go:24` | `func (e *External) Start(` |
| `handleDemonAgent` | function | `teamserver/pkg/handlers/handlers.go:56` | `func handleDemonAgent(` |
| `handleServiceAgent` | function | `teamserver/pkg/handlers/handlers.go:311` | `func handleServiceAgent(` |
| `notifyTaskSize` | function | `teamserver/pkg/handlers/handlers.go:349` | `func notifyTaskSize(` |
| `parseAgentRequest` | function | `teamserver/pkg/handlers/handlers.go:23` | `func parseAgentRequest(` |
| `NewConfigHttp` | function | `teamserver/pkg/handlers/http.go:24` | `func NewConfigHttp(` |
| `Start` | function | `teamserver/pkg/handlers/http.go:203` | `func (h *HTTP) Start(` |
| `Stop` | function | `teamserver/pkg/handlers/http.go:277` | `func (h *HTTP) Stop(` |
| `fake404` | function | `teamserver/pkg/handlers/http.go:80` | `func (h *HTTP) fake404(` |
| `generateCertFiles` | function | `teamserver/pkg/handlers/http.go:32` | `func (h *HTTP) generateCertFiles(` |
| `request` | function | `teamserver/pkg/handlers/http.go:93` | `func (h *HTTP) request(` |
| `NewPivotSmb` | function | `teamserver/pkg/handlers/smb.go:8` | `func NewPivotSmb(` |
| `Start` | function | `teamserver/pkg/handlers/smb.go:14` | `func (s *SMB) Start(` |
| `Debug` | function | `teamserver/pkg/logger/global.go:35` | `func Debug(` |
| `DebugError` | function | `teamserver/pkg/logger/global.go:39` | `func DebugError(` |
| `Error` | function | `teamserver/pkg/logger/global.go:47` | `func Error(` |
| `Fatal` | function | `teamserver/pkg/logger/global.go:51` | `func Fatal(` |
| `Good` | function | `teamserver/pkg/logger/global.go:31` | `func Good(` |
| `Info` | function | `teamserver/pkg/logger/global.go:27` | `func Info(` |
| `NewLogger` | function | `teamserver/pkg/logger/global.go:15` | `func NewLogger(` |
| `Panic` | function | `teamserver/pkg/logger/global.go:55` | `func Panic(` |
| `SetDebug` | function | `teamserver/pkg/logger/global.go:59` | `func SetDebug(` |
| `SetStdOut` | function | `teamserver/pkg/logger/global.go:67` | `func SetStdOut(` |
| `ShowTime` | function | `teamserver/pkg/logger/global.go:63` | `func ShowTime(` |
| `Warn` | function | `teamserver/pkg/logger/global.go:43` | `func Warn(` |
| `init` | function | `teamserver/pkg/logger/global.go:11` | `func init(` |
| `Debug` | function | `teamserver/pkg/logger/logger.go:61` | `func (logger *Logger) Debug(` |
| `DebugError` | function | `teamserver/pkg/logger/logger.go:74` | `func (logger *Logger) DebugError(` |
| `Error` | function | `teamserver/pkg/logger/logger.go:96` | `func (logger *Logger) Error(` |
| `Fatal` | function | `teamserver/pkg/logger/logger.go:105` | `func (logger *Logger) Fatal(` |
| `FunctionTrace` | function | `teamserver/pkg/logger/logger.go:15` | `func FunctionTrace(` |
| `Good` | function | `teamserver/pkg/logger/logger.go:52` | `func (logger *Logger) Good(` |
| `Info` | function | `teamserver/pkg/logger/logger.go:43` | `func (logger *Logger) Info(` |
| `Logger` | struct | `teamserver/pkg/logger/logger.go:34` | `` |
| `Panic` | function | `teamserver/pkg/logger/logger.go:115` | `func (logger *Logger) Panic(` |
| `SetDebug` | function | `teamserver/pkg/logger/logger.go:125` | `func (logger *Logger) SetDebug(` |
| `ShowTime` | function | `teamserver/pkg/logger/logger.go:129` | `func (logger *Logger) ShowTime(` |
| `Warn` | function | `teamserver/pkg/logger/logger.go:87` | `func (logger *Logger) Warn(` |
| `AddAgentInput` | function | `teamserver/pkg/logr/demon.go:15` | `func (l Logr) AddAgentInput(` |
| `AddAgentRaw` | function | `teamserver/pkg/logr/demon.go:50` | `func (l Logr) AddAgentRaw(` |
| `DemonAddDownloadedFile` | function | `teamserver/pkg/logr/demon.go:134` | `func (l Logr) DemonAddDownloadedFile(` |
| `DemonAddOutput` | function | `teamserver/pkg/logr/demon.go:82` | `func (l Logr) DemonAddOutput(` |
| `DemonSaveScreenshot` | function | `teamserver/pkg/logr/demon.go:177` | `func (l Logr) DemonSaveScreenshot(` |
| `ListenerAddKeyCert` | function | `teamserver/pkg/logr/listener.go:3` | `func (l Logr) ListenerAddKeyCert(` |
| `Logr` | struct | `teamserver/pkg/logr/logr.go:9` | `` |
| `NewLogr` | function | `teamserver/pkg/logr/logr.go:21` | `func NewLogr(` |
| `ServerStdOutInit` | function | `teamserver/pkg/logr/server.go:21` | `func (l Logr) ServerStdOutInit(` |
| `strip` | function | `teamserver/pkg/logr/server.go:12` | `func strip(` |
| `CreatePackage` | function | `teamserver/pkg/packager/packages.go:13` | `func (p Packager) CreatePackage(` |
| `NewPackager` | function | `teamserver/pkg/packager/packages.go:9` | `func NewPackager(` |
| `Binary` | struct | `teamserver/pkg/profile/config.go:127` | `` |
| `BuildConfig` | struct | `teamserver/pkg/profile/config.go:22` | `` |
| `Demon` | struct | `teamserver/pkg/profile/config.go:139` | `` |
| `HavocConfig` | struct | `teamserver/pkg/profile/config.go:3` | `` |
| `HeaderBlock` | struct | `teamserver/pkg/profile/config.go:118` | `` |
| `ListenerExternal` | struct | `teamserver/pkg/profile/config.go:97` | `` |
| `ListenerHTTP` | struct | `teamserver/pkg/profile/config.go:57` | `` |
| `ListenerHttpCerts` | struct | `teamserver/pkg/profile/config.go:113` | `` |
| `ListenerHttpProxy` | struct | `teamserver/pkg/profile/config.go:106` | `` |
| `ListenerHttpResponse` | struct | `teamserver/pkg/profile/config.go:102` | `` |
| `ListenerSMB` | struct | `teamserver/pkg/profile/config.go:87` | `` |
| `Listeners` | struct | `teamserver/pkg/profile/config.go:51` | `` |
| `OperatorsBlock` | struct | `teamserver/pkg/profile/config.go:42` | `` |
| `ProcessInjectionBlock` | struct | `teamserver/pkg/profile/config.go:134` | `` |
| `ServerProfile` | struct | `teamserver/pkg/profile/config.go:33` | `` |
| `ServiceConfig` | struct | `teamserver/pkg/profile/config.go:28` | `` |
| `UsersBlock` | struct | `teamserver/pkg/profile/config.go:46` | `` |
| `WebHookConfig` | struct | `teamserver/pkg/profile/config.go:18` | `` |
| `WebHookDiscordConfig` | struct | `teamserver/pkg/profile/config.go:12` | `` |
| `ListOfUsernames` | function | `teamserver/pkg/profile/profile.go:46` | `func (p *Profile) ListOfUsernames(` |
| `NewProfile` | function | `teamserver/pkg/profile/profile.go:13` | `func NewProfile(` |
| `Profile` | struct | `teamserver/pkg/profile/profile.go:9` | `` |
| `ServerHost` | function | `teamserver/pkg/profile/profile.go:32` | `func (p *Profile) ServerHost(` |
| `ServerPort` | function | `teamserver/pkg/profile/profile.go:39` | `func (p *Profile) ServerPort(` |
| `SetProfile` | function | `teamserver/pkg/profile/profile.go:17` | `func (p *Profile) SetProfile(` |
| `Append` | function | `teamserver/pkg/profile/yaotl/diagnostic.go:104` | `func (d Diagnostics) Append(` |
| `Diagnostic` | struct | `teamserver/pkg/profile/yaotl/diagnostic.go:26` | `` |
| `DiagnosticWriter` | interface | `teamserver/pkg/profile/yaotl/diagnostic.go:140` | `` |
| `Error` | function | `teamserver/pkg/profile/yaotl/diagnostic.go:76` | `func (d *Diagnostic) Error(` |
| `Error` | function | `teamserver/pkg/profile/yaotl/diagnostic.go:82` | `func (d Diagnostics) Error(` |
| `Errs` | function | `teamserver/pkg/profile/yaotl/diagnostic.go:128` | `func (d Diagnostics) Errs(` |
| `Extend` | function | `teamserver/pkg/profile/yaotl/diagnostic.go:113` | `func (d Diagnostics) Extend(` |
| `HasErrors` | function | `teamserver/pkg/profile/yaotl/diagnostic.go:119` | `func (d Diagnostics) HasErrors(` |
| `NewDiagnosticTextWriter` | function | `teamserver/pkg/profile/yaotl/diagnostic_text.go:34` | `func NewDiagnosticTextWriter(` |
| `WriteDiagnostic` | function | `teamserver/pkg/profile/yaotl/diagnostic_text.go:43` | `func (w *diagnosticTextWriter) WriteDiagnostic(` |
| `WriteDiagnostics` | function | `teamserver/pkg/profile/yaotl/diagnostic_text.go:208` | `func (w *diagnosticTextWriter) WriteDiagnostics(` |
| `contextString` | function | `teamserver/pkg/profile/yaotl/diagnostic_text.go:302` | `func contextString(` |
| `diagnosticTextWriter` | struct | `teamserver/pkg/profile/yaotl/diagnostic_text.go:15` | `` |
| `traversalStr` | function | `teamserver/pkg/profile/yaotl/diagnostic_text.go:218` | `func (w *diagnosticTextWriter) traversalStr(` |
| `valueStr` | function | `teamserver/pkg/profile/yaotl/diagnostic_text.go:246` | `func (w *diagnosticTextWriter) valueStr(` |
| `nameSuggestion` | function | `teamserver/pkg/profile/yaotl/didyoumean.go:16` | `func nameSuggestion(` |
| `EvalContext` | struct | `teamserver/pkg/profile/yaotl/eval_context.go:10` | `` |
| `NewChild` | function | `teamserver/pkg/profile/yaotl/eval_context.go:17` | `func (ctx *EvalContext) NewChild(` |
| `Parent` | function | `teamserver/pkg/profile/yaotl/eval_context.go:23` | `func (ctx *EvalContext) Parent(` |
| `ExprCall` | function | `teamserver/pkg/profile/yaotl/expr_call.go:14` | `func ExprCall(` |
| `StaticCall` | struct | `teamserver/pkg/profile/yaotl/expr_call.go:41` | `` |
| `ExprList` | function | `teamserver/pkg/profile/yaotl/expr_list.go:14` | `func ExprList(` |
| `ExprMap` | function | `teamserver/pkg/profile/yaotl/expr_map.go:14` | `func ExprMap(` |
| `KeyValuePair` | struct | `teamserver/pkg/profile/yaotl/expr_map.go:41` | `` |
| `UnwrapExpression` | function | `teamserver/pkg/profile/yaotl/expr_unwrap.go:28` | `func UnwrapExpression(` |
| `UnwrapExpressionUntil` | function | `teamserver/pkg/profile/yaotl/expr_unwrap.go:54` | `func UnwrapExpressionUntil(` |
| `unwrapExpression` | interface | `teamserver/pkg/profile/yaotl/expr_unwrap.go:3` | `` |
| `CustomExpressionDecoderForType` | function | `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go:48` | `func CustomExpressionDecoderForType(` |
| `ExpressionClosure` | struct | `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:51` | `` |
| `ExpressionClosureFromVal` | function | `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:75` | `func ExpressionClosureFromVal(` |
| `ExpressionClosureVal` | function | `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:58` | `func ExpressionClosureVal(` |
| `ExpressionFromVal` | function | `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:33` | `func ExpressionFromVal(` |
| `ExpressionVal` | function | `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:27` | `func ExpressionVal(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:64` | `func (c *ExpressionClosure) Value(` |
| `init` | function | `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:82` | `func init(` |
| `Content` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:29` | `func (b *expandBody) Content(` |
| `JustAttributes` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:239` | `func (b *expandBody) JustAttributes(` |
| `MissingItemRange` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:246` | `func (b *expandBody) MissingItemRange(` |
| `PartialContent` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:46` | `func (b *expandBody) PartialContent(` |
| `expandBlocks` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:151` | `func (b *expandBody) expandBlocks(` |
| `expandBody` | struct | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:12` | `` |
| `expandChild` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:232` | `func (b *expandBody) expandChild(` |
| `extendSchema` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:85` | `func (b *expandBody) extendSchema(` |
| `prepareAttributes` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:121` | `func (b *expandBody) prepareAttributes(` |
| `TestExpand` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body_test.go:13` | `func TestExpand(` |
| `TestExpandUnknownBodies` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body_test.go:336` | `func TestExpandUnknownBodies(` |
| `decodeSpec` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_spec.go:22` | `func (b *expandBody) decodeSpec(` |
| `expandSpec` | struct | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_spec.go:11` | `` |
| `newBlock` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expand_spec.go:153` | `func (s *expandSpec) newBlock(` |
| `UnwrapExpression` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go:40` | `func (e exprWrap) UnwrapExpression(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go:33` | `func (e exprWrap) Value(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go:13` | `func (e exprWrap) Variables(` |
| `exprWrap` | struct | `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go:8` | `` |
| `EvalContext` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:31` | `func (i *iteration) EvalContext(` |
| `MakeChild` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:45` | `func (i *iteration) MakeChild(` |
| `MakeIteration` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:15` | `func (s *expandSpec) MakeIteration(` |
| `Object` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:24` | `func (i *iteration) Object(` |
| `iteration` | struct | `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:8` | `` |
| `Expand` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/public.go:42` | `func Expand(` |
| `Content` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:28` | `func (b unknownBody) Content(` |
| `JustAttributes` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:49` | `func (b unknownBody) JustAttributes(` |
| `MissingItemRange` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:59` | `func (b unknownBody) MissingItemRange(` |
| `PartialContent` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:38` | `func (b unknownBody) PartialContent(` |
| `Unknown` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:24` | `func (b unknownBody) Unknown(` |
| `fixupAttrs` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:78` | `func (b unknownBody) fixupAttrs(` |
| `fixupContent` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:63` | `func (b unknownBody) fixupContent(` |
| `unknownBody` | struct | `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:17` | `` |
| `Body` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:58` | `func (c WalkVariablesChild) Body(` |
| `Visit` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:70` | `func (n WalkVariablesNode) Visit(` |
| `WalkExpandVariables` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:32` | `func WalkExpandVariables(` |
| `WalkVariables` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:19` | `func WalkVariables(` |
| `WalkVariablesChild` | struct | `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:45` | `` |
| `WalkVariablesNode` | struct | `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:38` | `` |
| `extendSchema` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:172` | `func (n WalkVariablesNode) extendSchema(` |
| `ExpandVariablesHCLDec` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go:25` | `func ExpandVariablesHCLDec(` |
| `VariablesHCLDec` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go:16` | `func VariablesHCLDec(` |
| `walkVariablesWithHCLDec` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go:30` | `func walkVariablesWithHCLDec(` |
| `TestVariables` | function | `teamserver/pkg/profile/yaotl/ext/dynblock/variables_test.go:16` | `func TestVariables(` |
| `BodyWithDiagnostics` | function | `teamserver/pkg/profile/yaotl/ext/transform/error.go:39` | `func BodyWithDiagnostics(` |
| `Content` | function | `teamserver/pkg/profile/yaotl/ext/transform/error.go:56` | `func (b diagBody) Content(` |
| `JustAttributes` | function | `teamserver/pkg/profile/yaotl/ext/transform/error.go:80` | `func (b diagBody) JustAttributes(` |
| `MissingItemRange` | function | `teamserver/pkg/profile/yaotl/ext/transform/error.go:92` | `func (b diagBody) MissingItemRange(` |
| `NewErrorBody` | function | `teamserver/pkg/profile/yaotl/ext/transform/error.go:17` | `func NewErrorBody(` |
| `PartialContent` | function | `teamserver/pkg/profile/yaotl/ext/transform/error.go:68` | `func (b diagBody) PartialContent(` |
| `diagBody` | struct | `teamserver/pkg/profile/yaotl/ext/transform/error.go:51` | `` |
| `emptyContent` | function | `teamserver/pkg/profile/yaotl/ext/transform/error.go:104` | `func (b diagBody) emptyContent(` |
| `Content` | function | `teamserver/pkg/profile/yaotl/ext/transform/transform.go:39` | `func (w deepWrapper) Content(` |
| `Deep` | function | `teamserver/pkg/profile/yaotl/ext/transform/transform.go:24` | `func Deep(` |
| `JustAttributes` | function | `teamserver/pkg/profile/yaotl/ext/transform/transform.go:76` | `func (w deepWrapper) JustAttributes(` |
| `MissingItemRange` | function | `teamserver/pkg/profile/yaotl/ext/transform/transform.go:81` | `func (w deepWrapper) MissingItemRange(` |
| `PartialContent` | function | `teamserver/pkg/profile/yaotl/ext/transform/transform.go:45` | `func (w deepWrapper) PartialContent(` |
| `Shallow` | function | `teamserver/pkg/profile/yaotl/ext/transform/transform.go:9` | `func Shallow(` |
| `deepWrapper` | struct | `teamserver/pkg/profile/yaotl/ext/transform/transform.go:34` | `` |
| `transformContent` | function | `teamserver/pkg/profile/yaotl/ext/transform/transform.go:51` | `func (w deepWrapper) transformContent(` |
| `TestDeep` | function | `teamserver/pkg/profile/yaotl/ext/transform/transform_test.go:16` | `func TestDeep(` |
| `Chain` | function | `teamserver/pkg/profile/yaotl/ext/transform/transformer.go:31` | `func Chain(` |
| `TransformBody` | function | `teamserver/pkg/profile/yaotl/ext/transform/transformer.go:23` | `func (f TransformerFunc) TransformBody(` |
| `TransformBody` | function | `teamserver/pkg/profile/yaotl/ext/transform/transformer.go:35` | `func (c chain) TransformBody(` |
| `Transformer` | interface | `teamserver/pkg/profile/yaotl/ext/transform/transformer.go:15` | `` |
| `can` | function | `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:109` | `func can(` |
| `dependsOnUnknowns` | function | `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:130` | `func dependsOnUnknowns(` |
| `init` | function | `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:30` | `func init(` |
| `try` | function | `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:61` | `func try(` |
| `TestCanFunc` | function | `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc_test.go:169` | `func TestCanFunc(` |
| `TestTryFunc` | function | `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc_test.go:12` | `func TestTryFunc(` |
| `getType` | function | `teamserver/pkg/profile/yaotl/ext/typeexpr/get_type.go:15` | `func getType(` |
| `TestGetType` | function | `teamserver/pkg/profile/yaotl/ext/typeexpr/get_type_test.go:14` | `func TestGetType(` |
| `TestGetTypeJSON` | function | `teamserver/pkg/profile/yaotl/ext/typeexpr/get_type_test.go:282` | `func TestGetTypeJSON(` |
| `Type` | function | `teamserver/pkg/profile/yaotl/ext/typeexpr/public.go:17` | `func Type(` |
| `TypeConstraint` | function | `teamserver/pkg/profile/yaotl/ext/typeexpr/public.go:28` | `func TypeConstraint(` |
| `TypeString` | function | `teamserver/pkg/profile/yaotl/ext/typeexpr/public.go:44` | `func TypeString(` |
| `TestTypeString` | function | `teamserver/pkg/profile/yaotl/ext/typeexpr/type_string_test.go:9` | `func TestTypeString(` |
| `TypeConstraintFromVal` | function | `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:35` | `func TypeConstraintFromVal(` |
| `TypeConstraintVal` | function | `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:26` | `func TypeConstraintVal(` |
| `init` | function | `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:57` | `func init(` |
| `TestConvertFunc` | function | `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type_test.go:30` | `func TestConvertFunc(` |
| `TestTypeConstraintType` | function | `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type_test.go:10` | `func TestTypeConstraintType(` |
| `decodeUserFunctions` | function | `teamserver/pkg/profile/yaotl/ext/userfunc/decode.go:26` | `func decodeUserFunctions(` |
| `TestDecodeUserFunctions` | function | `teamserver/pkg/profile/yaotl/ext/userfunc/decode_test.go:12` | `func TestDecodeUserFunctions(` |
| `DecodeUserFunctions` | function | `teamserver/pkg/profile/yaotl/ext/userfunc/public.go:40` | `func DecodeUserFunctions(` |
| `DecodeBody` | function | `teamserver/pkg/profile/yaotl/gohcl/decode.go:30` | `func DecodeBody(` |
| `DecodeExpression` | function | `teamserver/pkg/profile/yaotl/gohcl/decode.go:306` | `func DecodeExpression(` |
| `decodeBlockToValue` | function | `teamserver/pkg/profile/yaotl/gohcl/decode.go:260` | `func decodeBlockToValue(` |
| `decodeBodyToMap` | function | `teamserver/pkg/profile/yaotl/gohcl/decode.go:234` | `func decodeBodyToMap(` |
| `decodeBodyToStruct` | function | `teamserver/pkg/profile/yaotl/gohcl/decode.go:51` | `func decodeBodyToStruct(` |
| `decodeBodyToValue` | function | `teamserver/pkg/profile/yaotl/gohcl/decode.go:39` | `func decodeBodyToValue(` |
| `EncodeAsBlock` | function | `teamserver/pkg/profile/yaotl/gohcl/encode.go:60` | `func EncodeAsBlock(` |
| `EncodeIntoBody` | function | `teamserver/pkg/profile/yaotl/gohcl/encode.go:36` | `func EncodeIntoBody(` |
| `populateBody` | function | `teamserver/pkg/profile/yaotl/gohcl/encode.go:85` | `func populateBody(` |
| `ImpliedBodySchema` | function | `teamserver/pkg/profile/yaotl/gohcl/schema.go:22` | `func ImpliedBodySchema(` |
| `fieldTags` | struct | `teamserver/pkg/profile/yaotl/gohcl/schema.go:111` | `` |
| `getFieldTags` | function | `teamserver/pkg/profile/yaotl/gohcl/schema.go:125` | `func getFieldTags(` |
| `labelField` | struct | `teamserver/pkg/profile/yaotl/gohcl/schema.go:120` | `` |
| `blockLabel` | struct | `teamserver/pkg/profile/yaotl/hcldec/block_labels.go:7` | `` |
| `labelsForBlock` | function | `teamserver/pkg/profile/yaotl/hcldec/block_labels.go:12` | `func labelsForBlock(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/decode.go:8` | `func decode(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/decode.go:27` | `func impliedType(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/decode.go:31` | `func sourceRange(` |
| `init` | function | `teamserver/pkg/profile/yaotl/hcldec/gob.go:7` | `func init(` |
| `ChildBlockTypes` | function | `teamserver/pkg/profile/yaotl/hcldec/public.go:58` | `func ChildBlockTypes(` |
| `Decode` | function | `teamserver/pkg/profile/yaotl/hcldec/public.go:14` | `func Decode(` |
| `ImpliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/public.go:31` | `func ImpliedType(` |
| `PartialDecode` | function | `teamserver/pkg/profile/yaotl/hcldec/public.go:25` | `func PartialDecode(` |
| `SourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/public.go:51` | `func SourceRange(` |
| `TestDecode` | function | `teamserver/pkg/profile/yaotl/hcldec/public_test.go:13` | `func TestDecode(` |
| `TestSourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/public_test.go:1046` | `func TestSourceRange(` |
| `ImpliedSchema` | function | `teamserver/pkg/profile/yaotl/hcldec/schema.go:10` | `func ImpliedSchema(` |
| `AttrSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:156` | `` |
| `BlockAttrsSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1177` | `` |
| `BlockLabelSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1343` | `` |
| `BlockListSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:416` | `` |
| `BlockMapSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:862` | `` |
| `BlockObjectSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1019` | `` |
| `BlockSetSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:700` | `` |
| `BlockSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:301` | `` |
| `BlockTupleSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:578` | `` |
| `DefaultSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1425` | `` |
| `ExprSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:269` | `` |
| `LiteralSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:243` | `` |
| `Spec` | interface | `teamserver/pkg/profile/yaotl/hcldec/spec.go:20` | `` |
| `TransformExprSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1496` | `` |
| `TransformFuncSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1554` | `` |
| `UnknownBody` | interface | `teamserver/pkg/profile/yaotl/hcldec/spec.go:69` | `` |
| `ValidateSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1614` | `` |
| `attrSchemata` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:177` | `func (s *AttrSpec) attrSchemata(` |
| `attrSchemata` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1450` | `func (s *DefaultSpec) attrSchemata(` |
| `attrSpec` | interface | `teamserver/pkg/profile/yaotl/hcldec/spec.go:51` | `` |
| `blockHeaderSchemata` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:312` | `func (s *BlockSpec) blockHeaderSchemata(` |
| `blockHeaderSchemata` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:428` | `func (s *BlockListSpec) blockHeaderSchemata(` |
| `blockHeaderSchemata` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:590` | `func (s *BlockTupleSpec) blockHeaderSchemata(` |
| `blockHeaderSchemata` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:712` | `func (s *BlockSetSpec) blockHeaderSchemata(` |
| `blockHeaderSchemata` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:873` | `func (s *BlockMapSpec) blockHeaderSchemata(` |
| `blockHeaderSchemata` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1030` | `func (s *BlockObjectSpec) blockHeaderSchemata(` |
| `blockHeaderSchemata` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1188` | `func (s *BlockAttrsSpec) blockHeaderSchemata(` |
| `blockHeaderSchemata` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1464` | `func (s *DefaultSpec) blockHeaderSchemata(` |
| `blockSpec` | interface | `teamserver/pkg/profile/yaotl/hcldec/spec.go:56` | `` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:79` | `func (s ObjectSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:121` | `func (s TupleSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:195` | `func (s *AttrSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:251` | `func (s *LiteralSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:282` | `func (s *ExprSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:345` | `func (s *BlockSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:457` | `func (s *BlockListSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:619` | `func (s *BlockTupleSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:741` | `func (s *BlockSetSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:902` | `func (s *BlockMapSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1059` | `func (s *BlockObjectSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1235` | `func (s *BlockAttrsSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1352` | `func (s *BlockLabelSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1435` | `func (s *DefaultSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1507` | `func (s *TransformExprSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1563` | `func (s *TransformFuncSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1623` | `func (s *ValidateSpec) decode(` |
| `decode` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1658` | `func (s noopSpec) decode(` |
| `findBlock` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1318` | `func (s *BlockAttrsSpec) findBlock(` |
| `findLabelSpecs` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1372` | `func findLabelSpecs(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:92` | `func (s ObjectSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:134` | `func (s TupleSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:237` | `func (s *AttrSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:255` | `func (s *LiteralSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:286` | `func (s *ExprSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:392` | `func (s *BlockSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:547` | `func (s *BlockListSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:671` | `func (s *BlockTupleSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:832` | `func (s *BlockSetSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:981` | `func (s *BlockMapSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1135` | `func (s *BlockObjectSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1306` | `func (s *BlockAttrsSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1360` | `func (s *BlockLabelSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1445` | `func (s *DefaultSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1525` | `func (s *TransformExprSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1589` | `func (s *TransformFuncSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1644` | `func (s *ValidateSpec) impliedType(` |
| `impliedType` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1662` | `func (s noopSpec) impliedType(` |
| `nestedSpec` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:322` | `func (s *BlockSpec) nestedSpec(` |
| `nestedSpec` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:438` | `func (s *BlockListSpec) nestedSpec(` |
| `nestedSpec` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:600` | `func (s *BlockTupleSpec) nestedSpec(` |
| `nestedSpec` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:722` | `func (s *BlockSetSpec) nestedSpec(` |
| `nestedSpec` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:883` | `func (s *BlockMapSpec) nestedSpec(` |
| `nestedSpec` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1040` | `func (s *BlockObjectSpec) nestedSpec(` |
| `nestedSpec` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1198` | `func (s *BlockAttrsSpec) nestedSpec(` |
| `nestedSpec` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1474` | `func (s *DefaultSpec) nestedSpec(` |
| `noopSpec` | struct | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1655` | `` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:104` | `func (s ObjectSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:146` | `func (s TupleSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:186` | `func (s *AttrSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:259` | `func (s *LiteralSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:291` | `func (s *ExprSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:396` | `func (s *BlockSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:551` | `func (s *BlockListSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:677` | `func (s *BlockTupleSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:836` | `func (s *BlockSetSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:989` | `func (s *BlockMapSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1141` | `func (s *BlockObjectSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1310` | `func (s *BlockAttrsSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1364` | `func (s *BlockLabelSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1481` | `func (s *DefaultSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1535` | `func (s *TransformExprSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1600` | `func (s *TransformFuncSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1648` | `func (s *ValidateSpec) sourceRange(` |
| `sourceRange` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1670` | `func (s noopSpec) sourceRange(` |
| `specNeedingVariables` | interface | `teamserver/pkg/profile/yaotl/hcldec/spec.go:63` | `` |
| `variablesNeeded` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:167` | `func (s *AttrSpec) variablesNeeded(` |
| `variablesNeeded` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:278` | `func (s *ExprSpec) variablesNeeded(` |
| `variablesNeeded` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:327` | `func (s *BlockSpec) variablesNeeded(` |
| `variablesNeeded` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:443` | `func (s *BlockListSpec) variablesNeeded(` |
| `variablesNeeded` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:605` | `func (s *BlockTupleSpec) variablesNeeded(` |
| `variablesNeeded` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:727` | `func (s *BlockSetSpec) variablesNeeded(` |
| `variablesNeeded` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:888` | `func (s *BlockMapSpec) variablesNeeded(` |
| `variablesNeeded` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1045` | `func (s *BlockObjectSpec) variablesNeeded(` |
| `variablesNeeded` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1208` | `func (s *BlockAttrsSpec) variablesNeeded(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:73` | `func (s ObjectSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:115` | `func (s TupleSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:162` | `func (s *AttrSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:247` | `func (s *LiteralSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:273` | `func (s *ExprSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:307` | `func (s *BlockSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:423` | `func (s *BlockListSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:585` | `func (s *BlockTupleSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:707` | `func (s *BlockSetSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:868` | `func (s *BlockMapSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1025` | `func (s *BlockObjectSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1183` | `func (s *BlockAttrsSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1348` | `func (s *BlockLabelSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1430` | `func (s *DefaultSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1503` | `func (s *TransformExprSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1559` | `func (s *TransformFuncSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1619` | `func (s *ValidateSpec) visitSameBodyChildren(` |
| `visitSameBodyChildren` | function | `teamserver/pkg/profile/yaotl/hcldec/spec.go:1666` | `func (s noopSpec) visitSameBodyChildren(` |
| `TestDefaultSpec` | function | `teamserver/pkg/profile/yaotl/hcldec/spec_test.go:49` | `func TestDefaultSpec(` |
| `TestValidateFuncSpec` | function | `teamserver/pkg/profile/yaotl/hcldec/spec_test.go:145` | `func TestValidateFuncSpec(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hcldec/variables.go:17` | `func Variables(` |
| `TestVariables` | function | `teamserver/pkg/profile/yaotl/hcldec/variables_test.go:13` | `func TestVariables(` |
| `ContextDefRange` | function | `teamserver/pkg/profile/yaotl/hcled/navigation.go:26` | `func ContextDefRange(` |
| `ContextString` | function | `teamserver/pkg/profile/yaotl/hcled/navigation.go:15` | `func ContextString(` |
| `contextDefRanger` | interface | `teamserver/pkg/profile/yaotl/hcled/navigation.go:22` | `` |
| `contextStringer` | interface | `teamserver/pkg/profile/yaotl/hcled/navigation.go:7` | `` |
| `AddFile` | function | `teamserver/pkg/profile/yaotl/hclparse/parser.go:110` | `func (p *Parser) AddFile(` |
| `Files` | function | `teamserver/pkg/profile/yaotl/hclparse/parser.go:133` | `func (p *Parser) Files(` |
| `NewParser` | function | `teamserver/pkg/profile/yaotl/hclparse/parser.go:43` | `func NewParser(` |
| `ParseHCL` | function | `teamserver/pkg/profile/yaotl/hclparse/parser.go:52` | `func (p *Parser) ParseHCL(` |
| `ParseHCLFile` | function | `teamserver/pkg/profile/yaotl/hclparse/parser.go:65` | `func (p *Parser) ParseHCLFile(` |
| `ParseJSON` | function | `teamserver/pkg/profile/yaotl/hclparse/parser.go:86` | `func (p *Parser) ParseJSON(` |
| `ParseJSONFile` | function | `teamserver/pkg/profile/yaotl/hclparse/parser.go:98` | `func (p *Parser) ParseJSONFile(` |
| `Parser` | struct | `teamserver/pkg/profile/yaotl/hclparse/parser.go:38` | `` |
| `Sources` | function | `teamserver/pkg/profile/yaotl/hclparse/parser.go:119` | `func (p *Parser) Sources(` |
| `Decode` | function | `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go:53` | `func Decode(` |
| `DecodeFile` | function | `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go:72` | `func DecodeFile(` |
| `setDiagEvalContext` | function | `teamserver/pkg/profile/yaotl/hclsyntax/diagnostics.go:16` | `func setDiagEvalContext(` |
| `nameSuggestion` | function | `teamserver/pkg/profile/yaotl/hclsyntax/didyoumean.go:16` | `func nameSuggestion(` |
| `AnonSymbolExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1546` | `` |
| `AsTraversal` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:79` | `func (e *LiteralValueExpr) AsTraversal(` |
| `AsTraversal` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:149` | `func (e *ScopeTraversalExpr) AsTraversal(` |
| `AsTraversal` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:182` | `func (e *RelativeTraversalExpr) AsTraversal(` |
| `AsTraversal` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:980` | `func (e *ObjectConsKeyExpr) AsTraversal(` |
| `ConditionalExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:564` | `` |
| `ExprCall` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:550` | `func (e *FunctionCallExpr) ExprCall(` |
| `ExprList` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:794` | `func (e *TupleConsExpr) ExprList(` |
| `ExprMap` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:906` | `func (e *ObjectConsExpr) ExprMap(` |
| `Expression` | interface | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:15` | `` |
| `ForExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1005` | `` |
| `FunctionCallExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:197` | `` |
| `IndexExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:723` | `` |
| `LiteralValueExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:57` | `` |
| `ObjectConsExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:802` | `` |
| `ObjectConsItem` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:809` | `` |
| `ObjectConsKeyExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:920` | `` |
| `ParenthesesExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:38` | `` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:45` | `func (e *ParenthesesExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:70` | `func (e *LiteralValueExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:140` | `func (e *ScopeTraversalExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:173` | `func (e *RelativeTraversalExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:541` | `func (e *FunctionCallExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:715` | `func (e *ConditionalExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:750` | `func (e *IndexExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:785` | `func (e *TupleConsExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:897` | `func (e *ObjectConsExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:971` | `func (e *ObjectConsKeyExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1375` | `func (e *ForExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1527` | `func (e *SplatExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1605` | `func (e *AnonSymbolExpr) Range(` |
| `RelativeTraversalExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:155` | `` |
| `ScopeTraversalExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:125` | `` |
| `SplatExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1383` | `` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:74` | `func (e *LiteralValueExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:144` | `func (e *ScopeTraversalExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:177` | `func (e *RelativeTraversalExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:545` | `func (e *FunctionCallExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:719` | `func (e *ConditionalExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:754` | `func (e *IndexExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:789` | `func (e *TupleConsExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:901` | `func (e *ObjectConsExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:975` | `func (e *ObjectConsKeyExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1379` | `func (e *ForExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1531` | `func (e *SplatExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1609` | `func (e *AnonSymbolExpr) StartRange(` |
| `TupleConsExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:758` | `` |
| `UnwrapExpression` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:996` | `func (e *ObjectConsKeyExpr) UnwrapExpression(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:66` | `func (e *LiteralValueExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:134` | `func (e *ScopeTraversalExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:165` | `func (e *RelativeTraversalExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:216` | `func (e *FunctionCallExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:578` | `func (e *ConditionalExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:737` | `func (e *IndexExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:771` | `func (e *TupleConsExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:821` | `func (e *ObjectConsExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:942` | `func (e *ObjectConsKeyExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1022` | `func (e *ForExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1392` | `func (e *SplatExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1558` | `func (e *AnonSymbolExpr) Value(` |
| `clearValue` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1588` | `func (e *AnonSymbolExpr) clearValue(` |
| `literalName` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:925` | `func (e *ObjectConsKeyExpr) literalName(` |
| `setValue` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1575` | `func (e *AnonSymbolExpr) setValue(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:49` | `func (e *ParenthesesExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:62` | `func (e *LiteralValueExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:130` | `func (e *ScopeTraversalExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:161` | `func (e *RelativeTraversalExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:210` | `func (e *FunctionCallExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:572` | `func (e *ConditionalExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:732` | `func (e *IndexExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:765` | `func (e *TupleConsExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:814` | `func (e *ObjectConsExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:934` | `func (e *ObjectConsKeyExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1346` | `func (e *ForExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1522` | `func (e *SplatExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1601` | `func (e *AnonSymbolExpr) walkChildNodes(` |
| `BinaryOpExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:123` | `` |
| `Operation` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:13` | `` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:198` | `func (e *BinaryOpExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:262` | `func (e *UnaryOpExpr) Range(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:202` | `func (e *BinaryOpExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:266` | `func (e *UnaryOpExpr) StartRange(` |
| `UnaryOpExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:206` | `` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:136` | `func (e *BinaryOpExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:218` | `func (e *UnaryOpExpr) Value(` |
| `init` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:86` | `func init(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:131` | `func (e *BinaryOpExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:214` | `func (e *UnaryOpExpr) walkChildNodes(` |
| `IsStringLiteral` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:117` | `func (e *TemplateExpr) IsStringLiteral(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:97` | `func (e *TemplateExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:207` | `func (e *TemplateJoinExpr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:233` | `func (e *TemplateWrapExpr) Range(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:101` | `func (e *TemplateExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:211` | `func (e *TemplateJoinExpr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:237` | `func (e *TemplateWrapExpr) StartRange(` |
| `TemplateExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:12` | `` |
| `TemplateJoinExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:129` | `` |
| `TemplateWrapExpr` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:219` | `` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:24` | `func (e *TemplateExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:137` | `func (e *TemplateJoinExpr) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:229` | `func (e *TemplateWrapExpr) Value(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:18` | `func (e *TemplateExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:133` | `func (e *TemplateJoinExpr) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:225` | `func (e *TemplateWrapExpr) walkChildNodes(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:10` | `func (e *AnonSymbolExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:14` | `func (e *BinaryOpExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:18` | `func (e *ConditionalExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:22` | `func (e *ForExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:26` | `func (e *FunctionCallExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:30` | `func (e *IndexExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:34` | `func (e *LiteralValueExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:38` | `func (e *ObjectConsExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:42` | `func (e *ObjectConsKeyExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:46` | `func (e *RelativeTraversalExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:50` | `func (e *ScopeTraversalExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:54` | `func (e *SplatExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:58` | `func (e *TemplateExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:62` | `func (e *TemplateJoinExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:66` | `func (e *TemplateWrapExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:70` | `func (e *TupleConsExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:74` | `func (e *UnaryOpExpr) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go:97` | `func (e %s) Variables(` |
| `main` | function | `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go:20` | `func main(` |
| `AsHCLFile` | function | `teamserver/pkg/profile/yaotl/hclsyntax/file.go:13` | `func (f *File) AsHCLFile(` |
| `File` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/file.go:8` | `` |
| `Fuzz` | function | `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/config/fuzz.go:8` | `func Fuzz(` |
| `Fuzz` | function | `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/expr/fuzz.go:8` | `func Fuzz(` |
| `Fuzz` | function | `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/template/fuzz.go:8` | `func Fuzz(` |
| `Fuzz` | function | `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/traversal/fuzz.go:8` | `func Fuzz(` |
| `TokenMatches` | function | `teamserver/pkg/profile/yaotl/hclsyntax/keywords.go:16` | `func (kw Keyword) TokenMatches(` |
| `ContextDefRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/navigation.go:45` | `func (n navigation) ContextDefRange(` |
| `ContextString` | function | `teamserver/pkg/profile/yaotl/hclsyntax/navigation.go:15` | `func (n navigation) ContextString(` |
| `navigation` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/navigation.go:10` | `` |
| `Node` | interface | `teamserver/pkg/profile/yaotl/hclsyntax/node.go:11` | `` |
| `ParseBody` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:25` | `func (p *parser) ParseBody(` |
| `ParseBodyItem` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:116` | `func (p *parser) ParseBodyItem(` |
| `ParseExpression` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:444` | `func (p *parser) ParseExpression(` |
| `ParseStringLiteralToken` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1745` | `func ParseStringLiteralToken(` |
| `errPlaceholderExpr` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:2067` | `func errPlaceholderExpr(` |
| `finishParsingBodyAttribute` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:217` | `func (p *parser) finishParsingBodyAttribute(` |
| `finishParsingBodyBlock` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:274` | `func (p *parser) finishParsingBodyBlock(` |
| `finishParsingForExpr` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1427` | `func (p *parser) finishParsingForExpr(` |
| `finishParsingFunctionCall` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1105` | `func (p *parser) finishParsingFunctionCall(` |
| `makeRelativeTraversal` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:891` | `func makeRelativeTraversal(` |
| `numberLitValue` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1081` | `func (p *parser) numberLitValue(` |
| `oppositeBracket` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:2028` | `func (p *parser) oppositeBracket(` |
| `parseBinaryOps` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:512` | `func (p *parser) parseBinaryOps(` |
| `parseExpressionTerm` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:910` | `func (p *parser) parseExpressionTerm(` |
| `parseExpressionTraversals` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:591` | `func (p *parser) parseExpressionTraversals(` |
| `parseExpressionWithTraversals` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:584` | `func (p *parser) parseExpressionWithTraversals(` |
| `parseObjectCons` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1270` | `func (p *parser) parseObjectCons(` |
| `parseQuotedStringLiteral` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1650` | `func (p *parser) parseQuotedStringLiteral(` |
| `parseSingleAttrBody` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:156` | `func (p *parser) parseSingleAttrBody(` |
| `parseTernaryConditional` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:448` | `func (p *parser) parseTernaryConditional(` |
| `parseTupleCons` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1200` | `func (p *parser) parseTupleCons(` |
| `parser` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:15` | `` |
| `recover` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1924` | `func (p *parser) recover(` |
| `recoverAfterBodyItem` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1981` | `func (p *parser) recoverAfterBodyItem(` |
| `recoverOver` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1963` | `func (p *parser) recoverOver(` |
| `setRecovery` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1912` | `func (p *parser) setRecovery(` |
| `Name` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:787` | `func (t *templateEndCtrlToken) Name(` |
| `ParseTemplate` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:13` | `func (p *parser) ParseTemplate(` |
| `Peek` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:344` | `func (p *templateParser) Peek(` |
| `Read` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:348` | `func (p *templateParser) Read(` |
| `flushHeredocTemplateParts` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:675` | `func flushHeredocTemplateParts(` |
| `parseExpr` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:83` | `func (p *templateParser) parseExpr(` |
| `parseFor` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:247` | `func (p *templateParser) parseFor(` |
| `parseIf` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:135` | `func (p *templateParser) parseIf(` |
| `parseRoot` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:65` | `func (p *templateParser) parseRoot(` |
| `parseTemplate` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:17` | `func (p *parser) parseTemplate(` |
| `parseTemplateInner` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:36` | `func (p *parser) parseTemplateInner(` |
| `parseTemplateParts` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:361` | `func (p *parser) parseTemplateParts(` |
| `templateEndCtrlToken` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:781` | `` |
| `templateEndToken` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:801` | `` |
| `templateForToken` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:765` | `` |
| `templateIfToken` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:759` | `` |
| `templateInterpToken` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:753` | `` |
| `templateLiteralToken` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:747` | `` |
| `templateParser` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:58` | `` |
| `templateParts` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:734` | `` |
| `templateToken` | interface | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:743` | `` |
| `templateToken` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:808` | `func (t isTemplateToken) templateToken(` |
| `ParseTraversalAbs` | function | `teamserver/pkg/profile/yaotl/hclsyntax/parser_traversal.go:12` | `func (p *parser) ParseTraversalAbs(` |
| `AssertEmptyIncludeNewlinesStack` | function | `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:168` | `func (p *peeker) AssertEmptyIncludeNewlinesStack(` |
| `NextRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:58` | `func (p *peeker) NextRange(` |
| `Peek` | function | `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:47` | `func (p *peeker) Peek(` |
| `PopIncludeNewlines` | function | `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:138` | `func (p *peeker) PopIncludeNewlines(` |
| `PrevRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:62` | `func (p *peeker) PrevRange(` |
| `PushIncludeNewlines` | function | `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:122` | `func (p *peeker) PushIncludeNewlines(` |
| `Read` | function | `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:52` | `func (p *peeker) Read(` |
| `formatPeekerNewlineStackChanges` | function | `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:184` | `func formatPeekerNewlineStackChanges(` |
| `includingNewlines` | function | `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:118` | `func (p *peeker) includingNewlines(` |
| `newPeeker` | function | `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:38` | `func newPeeker(` |
| `nextToken` | function | `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:70` | `func (p *peeker) nextToken(` |
| `peeker` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:20` | `` |
| `peekerNewlineStackChange` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:32` | `` |
| `LexConfig` | function | `teamserver/pkg/profile/yaotl/hclsyntax/public.go:125` | `func LexConfig(` |
| `LexExpression` | function | `teamserver/pkg/profile/yaotl/hclsyntax/public.go:138` | `func LexExpression(` |
| `LexTemplate` | function | `teamserver/pkg/profile/yaotl/hclsyntax/public.go:153` | `func LexTemplate(` |
| `ParseConfig` | function | `teamserver/pkg/profile/yaotl/hclsyntax/public.go:17` | `func ParseConfig(` |
| `ParseExpression` | function | `teamserver/pkg/profile/yaotl/hclsyntax/public.go:41` | `func ParseExpression(` |
| `ParseTemplate` | function | `teamserver/pkg/profile/yaotl/hclsyntax/public.go:75` | `func ParseTemplate(` |
| `ParseTraversalAbs` | function | `teamserver/pkg/profile/yaotl/hclsyntax/public.go:96` | `func ParseTraversalAbs(` |
| `ValidIdentifier` | function | `teamserver/pkg/profile/yaotl/hclsyntax/public.go:165` | `func ValidIdentifier(` |
| `scanStringLit` | function | `teamserver/pkg/profile/yaotl/hclsyntax/scan_string_lit.go:119` | `func scanStringLit(` |
| `scanTokens` | function | `teamserver/pkg/profile/yaotl/hclsyntax/scan_tokens.go:4220` | `func scanTokens(` |
| `AsHCLAttribute` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:336` | `func (a *Attribute) AsHCLAttribute(` |
| `AsHCLBlock` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:11` | `func (b *Block) AsHCLBlock(` |
| `Attribute` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:318` | `` |
| `Block` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:373` | `` |
| `Body` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:33` | `` |
| `Content` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:58` | `func (b *Body) Content(` |
| `DefRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:392` | `func (b *Block) DefRange(` |
| `JustAttributes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:250` | `func (b *Body) JustAttributes(` |
| `MissingItemRange` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:281` | `func (b *Body) MissingItemRange(` |
| `PartialContent` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:128` | `func (b *Body) PartialContent(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:54` | `func (b *Body) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:303` | `func (a Attributes) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:331` | `func (a *Attribute) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:363` | `func (bs Blocks) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:388` | `func (b *Block) Range(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:49` | `func (b *Body) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:292` | `func (a Attributes) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:327` | `func (a *Attribute) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:352` | `func (bs Blocks) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:384` | `func (b *Block) walkChildNodes(` |
| `AttributeAtPos` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:84` | `func (b *Body) AttributeAtPos(` |
| `BlocksAtPos` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:15` | `func (b *Body) BlocksAtPos(` |
| `InnermostBlockAtPos` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:22` | `func (b *Body) InnermostBlockAtPos(` |
| `OutermostBlockAtPos` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:29` | `func (b *Body) OutermostBlockAtPos(` |
| `OutermostExprAtPos` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:109` | `func (b *Body) OutermostExprAtPos(` |
| `attributeAtPos` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:91` | `func (b *Body) attributeAtPos(` |
| `blocksAtPos` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:40` | `func (b *Body) blocksAtPos(` |
| `outermostBlockAtPos` | function | `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:68` | `func (b *Body) outermostBlockAtPos(` |
| `GoString` | function | `teamserver/pkg/profile/yaotl/hclsyntax/token.go:107` | `func (t TokenType) GoString(` |
| `Token` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/token.go:13` | `` |
| `checkInvalidTokens` | function | `teamserver/pkg/profile/yaotl/hclsyntax/token.go:182` | `func checkInvalidTokens(` |
| `emitToken` | function | `teamserver/pkg/profile/yaotl/hclsyntax/token.go:127` | `func (f *tokenAccum) emitToken(` |
| `heredocInProgress` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/token.go:162` | `` |
| `stripUTF8BOM` | function | `teamserver/pkg/profile/yaotl/hclsyntax/token.go:326` | `func stripUTF8BOM(` |
| `tokenAccum` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/token.go:119` | `` |
| `tokenOpensFlushHeredoc` | function | `teamserver/pkg/profile/yaotl/hclsyntax/token.go:167` | `func tokenOpensFlushHeredoc(` |
| `String` | function | `teamserver/pkg/profile/yaotl/hclsyntax/token_type_string.go:126` | `func (i TokenType) String(` |
| `_` | function | `teamserver/pkg/profile/yaotl/hclsyntax/token_type_string.go:7` | `func _(` |
| `build_range` | method | `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:197` | `` |
| `count_codepoints` | method | `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:259` | `` |
| `each_alpha` | method | `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:80` | `` |
| `from_utf8_enc` | method | `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:150` | `` |
| `generate_machine` | method | `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:285` | `` |
| `is_valid` | method | `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:273` | `` |
| `to_hex` | method | `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:103` | `` |
| `to_ucs4` | method | `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:112` | `` |
| `to_utf8` | method | `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:246` | `` |
| `to_utf8_enc` | method | `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:126` | `` |
| `utf8_ranges` | method | `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:181` | `` |
| `ChildScope` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:73` | `` |
| `Enter` | function | `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:32` | `func (w *variablesWalker) Enter(` |
| `Exit` | function | `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:55` | `func (w *variablesWalker) Exit(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:84` | `func (e ChildScope) Range(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:11` | `func Variables(` |
| `variablesWalker` | struct | `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:27` | `` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:78` | `func (e ChildScope) walkChildNodes(` |
| `VisitAll` | function | `teamserver/pkg/profile/yaotl/hclsyntax/walk.go:16` | `func VisitAll(` |
| `Walk` | function | `teamserver/pkg/profile/yaotl/hclsyntax/walk.go:33` | `func Walk(` |
| `Walker` | interface | `teamserver/pkg/profile/yaotl/hclsyntax/walk.go:25` | `` |
| `AsTraversal` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:236` | `func (e mockExprVariable) AsTraversal(` |
| `AsTraversal` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:287` | `func (e mockExprTraversal) AsTraversal(` |
| `Content` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:23` | `func (b mockBody) Content(` |
| `ExprList` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:155` | `func (e mockExprLiteral) ExprList(` |
| `ExprList` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:336` | `func (e mockExprList) ExprList(` |
| `ExprMap` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:170` | `func (e mockExprLiteral) ExprMap(` |
| `JustAttributes` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:108` | `func (b mockBody) JustAttributes(` |
| `MissingItemRange` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:122` | `func (b mockBody) MissingItemRange(` |
| `MockAttrs` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:345` | `func MockAttrs(` |
| `MockBody` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:15` | `func MockBody(` |
| `MockExprList` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:291` | `func MockExprList(` |
| `MockExprLiteral` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:128` | `func MockExprLiteral(` |
| `MockExprTraversal` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:247` | `func MockExprTraversal(` |
| `MockExprTraversalSrc` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:258` | `func MockExprTraversalSrc(` |
| `MockExprVariable` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:189` | `func MockExprVariable(` |
| `PartialContent` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:45` | `func (b mockBody) PartialContent(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:144` | `func (e mockExprLiteral) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:225` | `func (e mockExprVariable) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:278` | `func (e mockExprTraversal) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:325` | `func (e mockExprList) Range(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:150` | `func (e mockExprLiteral) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:231` | `func (e mockExprVariable) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:282` | `func (e mockExprTraversal) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:331` | `func (e mockExprList) StartRange(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:136` | `func (e mockExprLiteral) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:195` | `func (e mockExprVariable) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:270` | `func (e mockExprTraversal) Value(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:301` | `func (e mockExprList) Value(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:140` | `func (e mockExprLiteral) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:214` | `func (e mockExprVariable) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:274` | `func (e mockExprTraversal) Variables(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hcltest/mock.go:317` | `func (e mockExprList) Variables(` |
| `mockBody` | struct | `teamserver/pkg/profile/yaotl/hcltest/mock.go:19` | `` |
| `mockExprList` | struct | `teamserver/pkg/profile/yaotl/hcltest/mock.go:297` | `` |
| `mockExprLiteral` | struct | `teamserver/pkg/profile/yaotl/hcltest/mock.go:132` | `` |
| `mockExprTraversal` | struct | `teamserver/pkg/profile/yaotl/hcltest/mock.go:266` | `` |
| `TestExprList` | function | `teamserver/pkg/profile/yaotl/hcltest/mock_test.go:271` | `func TestExprList(` |
| `TestExprMap` | function | `teamserver/pkg/profile/yaotl/hcltest/mock_test.go:328` | `func TestExprMap(` |
| `TestMockBodyPartialContent` | function | `teamserver/pkg/profile/yaotl/hcltest/mock_test.go:17` | `func TestMockBodyPartialContent(` |
| `Body` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:28` | `func (f *File) Body(` |
| `BuildTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:64` | `func (c *comments) BuildTokens(` |
| `BuildTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:81` | `func (i *identifier) BuildTokens(` |
| `BuildTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:102` | `func (n *number) BuildTokens(` |
| `BuildTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:119` | `func (q *quoted) BuildTokens(` |
| `Bytes` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:45` | `func (f *File) Bytes(` |
| `File` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:8` | `` |
| `NewEmptyFile` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:17` | `func NewEmptyFile(` |
| `WriteTo` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:36` | `func (f *File) WriteTo(` |
| `comments` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:51` | `` |
| `hasName` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:85` | `func (i *identifier) hasName(` |
| `identifier` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:68` | `` |
| `newComments` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:58` | `func newComments(` |
| `newIdentifier` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:75` | `func newIdentifier(` |
| `newNumber` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:96` | `func newNumber(` |
| `newQuoted` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:113` | `func newQuoted(` |
| `number` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:89` | `` |
| `quoted` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast.go:106` | `` |
| `Attribute` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go:7` | `` |
| `Expr` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go:46` | `func (a *Attribute) Expr(` |
| `init` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go:22` | `func (a *Attribute) init(` |
| `newAttribute` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go:16` | `func newAttribute(` |
| `Block` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:8` | `` |
| `Body` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:67` | `func (b *Block) Body(` |
| `Current` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:136` | `func (bl *blockLabels) Current(` |
| `Labels` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:85` | `func (b *Block) Labels(` |
| `NewBlock` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:26` | `func NewBlock(` |
| `Replace` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:121` | `func (bl *blockLabels) Replace(` |
| `SetLabels` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:92` | `func (b *Block) SetLabels(` |
| `SetType` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:78` | `func (b *Block) SetType(` |
| `Type` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:72` | `func (b *Block) Type(` |
| `blockLabels` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:105` | `` |
| `init` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:32` | `func (b *Block) init(` |
| `labelsObj` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:101` | `func (b *Block) labelsObj(` |
| `newBlock` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:19` | `func newBlock(` |
| `newBlockLabels` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:111` | `func newBlockLabels(` |
| `TestBlockLabels` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go:49` | `func TestBlockLabels(` |
| `TestBlockSetLabels` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go:198` | `func TestBlockSetLabels(` |
| `TestBlockSetType` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go:138` | `func TestBlockSetType(` |
| `TestBlockType` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go:15` | `func TestBlockType(` |
| `AppendBlock` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:215` | `func (b *Body) AppendBlock(` |
| `AppendNewBlock` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:222` | `func (b *Body) AppendNewBlock(` |
| `AppendNewline` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:232` | `func (b *Body) AppendNewline(` |
| `AppendUnstructuredTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:42` | `func (b *Body) AppendUnstructuredTokens(` |
| `Attributes` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:48` | `func (b *Body) Attributes(` |
| `Blocks` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:61` | `func (b *Body) Blocks(` |
| `Body` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:11` | `` |
| `Clear` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:38` | `func (b *Body) Clear(` |
| `FirstMatchingBlock` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:106` | `func (b *Body) FirstMatchingBlock(` |
| `GetAttribute` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:73` | `func (b *Body) GetAttribute(` |
| `RemoveAttribute` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:203` | `func (b *Body) RemoveAttribute(` |
| `RemoveBlock` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:126` | `func (b *Body) RemoveBlock(` |
| `SetAttributeRaw` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:144` | `func (b *Body) SetAttributeRaw(` |
| `SetAttributeTraversal` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:186` | `func (b *Body) SetAttributeTraversal(` |
| `SetAttributeValue` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:165` | `func (b *Body) SetAttributeValue(` |
| `appendItem` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:24` | `func (b *Body) appendItem(` |
| `appendItemNode` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:30` | `func (b *Body) appendItemNode(` |
| `getAttributeNode` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:89` | `func (b *Body) getAttributeNode(` |
| `newBody` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:17` | `func newBody(` |
| `TestBodyAppendBlock` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:1149` | `func TestBodyAppendBlock(` |
| `TestBodyFirstMatchingBlock` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:220` | `func TestBodyFirstMatchingBlock(` |
| `TestBodyGetAttribute` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:16` | `func TestBodyGetAttribute(` |
| `TestBodyRemoveAttribute` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:1036` | `func TestBodyRemoveAttribute(` |
| `TestBodyRemoveBlock` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:1392` | `func TestBodyRemoveBlock(` |
| `TestBodySetAttributeRaw` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:769` | `func TestBodySetAttributeRaw(` |
| `TestBodySetAttributeTraversal` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:543` | `func TestBodySetAttributeTraversal(` |
| `TestBodySetAttributeValue` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:345` | `func TestBodySetAttributeValue(` |
| `TestBodySetAttributeValueInBlock` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:933` | `func TestBodySetAttributeValueInBlock(` |
| `TestBodySetAttributeValueInNestedBlock` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:981` | `func TestBodySetAttributeValueInNestedBlock(` |
| `Expression` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:11` | `` |
| `NewExpressionAbsTraversal` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:69` | `func NewExpressionAbsTraversal(` |
| `NewExpressionLiteral` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:60` | `func NewExpressionLiteral(` |
| `NewExpressionRaw` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:36` | `func NewExpressionRaw(` |
| `RenameVariablePrefix` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:150` | `func (e *Expression) RenameVariablePrefix(` |
| `Traversal` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:189` | `` |
| `TraverseIndex` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:214` | `` |
| `TraverseName` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:202` | `` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:129` | `func (e *Expression) Variables(` |
| `newExpression` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:17` | `func newExpression(` |
| `newTraversal` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:195` | `func newTraversal(` |
| `newTraverseIndex` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:220` | `func newTraverseIndex(` |
| `newTraverseName` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:208` | `func newTraverseName(` |
| `TestTreeNode` | struct | `teamserver/pkg/profile/yaotl/hclwrite/ast_test.go:8` | `` |
| `makeTestTree` | function | `teamserver/pkg/profile/yaotl/hclwrite/ast_test.go:15` | `func makeTestTree(` |
| `ExampleExpression_RenameVariablePrefix` | function | `teamserver/pkg/profile/yaotl/hclwrite/examples_test.go:74` | `func ExampleExpression_RenameVariablePrefix(` |
| `Example_generateFromScratch` | function | `teamserver/pkg/profile/yaotl/hclwrite/examples_test.go:11` | `func Example_generateFromScratch(` |
| `format` | function | `teamserver/pkg/profile/yaotl/hclwrite/format.go:19` | `func format(` |
| `formatCells` | function | `teamserver/pkg/profile/yaotl/hclwrite/format.go:158` | `func formatCells(` |
| `formatIndent` | function | `teamserver/pkg/profile/yaotl/hclwrite/format.go:40` | `func formatIndent(` |
| `formatLine` | struct | `teamserver/pkg/profile/yaotl/hclwrite/format.go:463` | `` |
| `formatSpaces` | function | `teamserver/pkg/profile/yaotl/hclwrite/format.go:110` | `func formatSpaces(` |
| `linesForFormat` | function | `teamserver/pkg/profile/yaotl/hclwrite/format.go:342` | `func linesForFormat(` |
| `spaceAfterToken` | function | `teamserver/pkg/profile/yaotl/hclwrite/format.go:227` | `func spaceAfterToken(` |
| `tokenBracketChange` | function | `teamserver/pkg/profile/yaotl/hclwrite/format.go:440` | `func tokenBracketChange(` |
| `tokenIsNewline` | function | `teamserver/pkg/profile/yaotl/hclwrite/format.go:427` | `func tokenIsNewline(` |
| `TestFormat` | function | `teamserver/pkg/profile/yaotl/hclwrite/format_test.go:13` | `func TestFormat(` |
| `TestLinesForFormat` | function | `teamserver/pkg/profile/yaotl/hclwrite/format_test.go:632` | `func TestLinesForFormat(` |
| `Fuzz` | function | `teamserver/pkg/profile/yaotl/hclwrite/fuzz/config/fuzz.go:10` | `func Fuzz(` |
| `TokensForTraversal` | function | `teamserver/pkg/profile/yaotl/hclwrite/generate.go:36` | `func TokensForTraversal(` |
| `TokensForValue` | function | `teamserver/pkg/profile/yaotl/hclwrite/generate.go:23` | `func TokensForValue(` |
| `appendRune` | function | `teamserver/pkg/profile/yaotl/hclwrite/generate.go:248` | `func appendRune(` |
| `appendTokensForTraversal` | function | `teamserver/pkg/profile/yaotl/hclwrite/generate.go:164` | `func appendTokensForTraversal(` |
| `appendTokensForTraversalStep` | function | `teamserver/pkg/profile/yaotl/hclwrite/generate.go:171` | `func appendTokensForTraversalStep(` |
| `appendTokensForValue` | function | `teamserver/pkg/profile/yaotl/hclwrite/generate.go:42` | `func appendTokensForValue(` |
| `escapeQuotedStringLit` | function | `teamserver/pkg/profile/yaotl/hclwrite/generate.go:207` | `func escapeQuotedStringLit(` |
| `TestTokensForTraversal` | function | `teamserver/pkg/profile/yaotl/hclwrite/generate_test.go:498` | `func TestTokensForTraversal(` |
| `TestTokensForValue` | function | `teamserver/pkg/profile/yaotl/hclwrite/generate_test.go:14` | `func TestTokensForValue(` |
| `Len` | function | `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go:11` | `func (s nativeNodeSorter) Len(` |
| `Less` | function | `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go:15` | `func (s nativeNodeSorter) Less(` |
| `Swap` | function | `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go:21` | `func (s nativeNodeSorter) Swap(` |
| `nativeNodeSorter` | struct | `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go:7` | `` |
| `Add` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:202` | `func (ns nodeSet) Add(` |
| `Append` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:112` | `func (ns *nodes) Append(` |
| `AppendNode` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:121` | `func (ns *nodes) AppendNode(` |
| `AppendUnstructuredTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:163` | `func (ns *nodes) AppendUnstructuredTokens(` |
| `BuildTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:27` | `func (n *node) BuildTokens(` |
| `BuildTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:100` | `func (ns *nodes) BuildTokens(` |
| `BuildTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:283` | `func (it *inTree) BuildTokens(` |
| `Clear` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:107` | `func (ns *nodes) Clear(` |
| `Clear` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:210` | `func (ns nodeSet) Clear(` |
| `Detach` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:33` | `func (n *node) Detach(` |
| `Equal` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:23` | `func (n *node) Equal(` |
| `FindNodeWithContent` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:176` | `func (ns *nodes) FindNodeWithContent(` |
| `FindNodeWithContent` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:246` | `func (ns nodeSet) FindNodeWithContent(` |
| `Has` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:194` | `func (ns nodeSet) Has(` |
| `Insert` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:135` | `func (ns *nodes) Insert(` |
| `InsertNode` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:147` | `func (ns *nodes) InsertNode(` |
| `List` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:216` | `func (ns nodeSet) List(` |
| `Remove` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:206` | `func (ns nodeSet) Remove(` |
| `ReplaceWith` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:60` | `func (n *node) ReplaceWith(` |
| `assertUnattached` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:83` | `func (n *node) assertUnattached(` |
| `assertUnattached` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:271` | `func (it *inTree) assertUnattached(` |
| `inTree` | struct | `teamserver/pkg/profile/yaotl/hclwrite/node.go:260` | `` |
| `leafNode` | struct | `teamserver/pkg/profile/yaotl/hclwrite/node.go:292` | `` |
| `newInTree` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:265` | `func newInTree(` |
| `newNode` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:17` | `func newNode(` |
| `newNodeSet` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:190` | `func newNodeSet(` |
| `node` | struct | `teamserver/pkg/profile/yaotl/hclwrite/node.go:10` | `` |
| `nodeContent` | interface | `teamserver/pkg/profile/yaotl/hclwrite/node.go:90` | `` |
| `nodes` | struct | `teamserver/pkg/profile/yaotl/hclwrite/node.go:96` | `` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:277` | `func (it *inTree) walkChildNodes(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclwrite/node.go:295` | `func (n *leafNode) walkChildNodes(` |
| `Len` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:162` | `func (it inputTokens) Len(` |
| `Partition` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:74` | `func (it inputTokens) Partition(` |
| `PartitionBlockItem` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:128` | `func (it inputTokens) PartitionBlockItem(` |
| `PartitionIncludingComments` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:111` | `func (it inputTokens) PartitionIncludingComments(` |
| `PartitionLeadComments` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:135` | `func (it inputTokens) PartitionLeadComments(` |
| `PartitionLineEndTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:142` | `func (it inputTokens) PartitionLineEndTokens(` |
| `PartitionType` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:82` | `func (it inputTokens) PartitionType(` |
| `PartitionTypeOk` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:91` | `func (it inputTokens) PartitionTypeOk(` |
| `PartitionTypeSingle` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:101` | `func (it inputTokens) PartitionTypeSingle(` |
| `Slice` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:150` | `func (it inputTokens) Slice(` |
| `Tokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:166` | `func (it inputTokens) Tokens(` |
| `Types` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:170` | `func (it inputTokens) Types(` |
| `inputTokens` | struct | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:69` | `` |
| `lexConfig` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:635` | `func lexConfig(` |
| `parse` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:29` | `func parse(` |
| `parseAttribute` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:238` | `func parseAttribute(` |
| `parseBlock` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:289` | `func parseBlock(` |
| `parseBlockLabels` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:347` | `func parseBlockLabels(` |
| `parseBody` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:181` | `func parseBody(` |
| `parseBodyItem` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:220` | `func parseBodyItem(` |
| `parseExpression` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:375` | `func parseExpression(` |
| `parseTraversal` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:396` | `func parseTraversal(` |
| `parseTraversalStep` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:413` | `func parseTraversalStep(` |
| `partitionLeadCommentTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:577` | `func partitionLeadCommentTokens(` |
| `partitionLineEndTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:600` | `func partitionLineEndTokens(` |
| `partitionTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:539` | `func partitionTokens(` |
| `writerTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser.go:482` | `func writerTokens(` |
| `TestLexConfig` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser_test.go:1458` | `func TestLexConfig(` |
| `TestParse` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser_test.go:18` | `func TestParse(` |
| `TestPartitionLeadCommentTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser_test.go:1382` | `func TestPartitionLeadCommentTokens(` |
| `TestPartitionTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/parser_test.go:1232` | `func TestPartitionTokens(` |
| `Format` | function | `teamserver/pkg/profile/yaotl/hclwrite/public.go:38` | `func Format(` |
| `NewFile` | function | `teamserver/pkg/profile/yaotl/hclwrite/public.go:11` | `func NewFile(` |
| `ParseConfig` | function | `teamserver/pkg/profile/yaotl/hclwrite/public.go:26` | `func ParseConfig(` |
| `TestRoundTripFormat` | function | `teamserver/pkg/profile/yaotl/hclwrite/round_trip_test.go:82` | `func TestRoundTripFormat(` |
| `TestRoundTripVerbatim` | function | `teamserver/pkg/profile/yaotl/hclwrite/round_trip_test.go:16` | `func TestRoundTripVerbatim(` |
| `BuildTokens` | function | `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:113` | `func (ts Tokens) BuildTokens(` |
| `Bytes` | function | `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:46` | `func (ts Tokens) Bytes(` |
| `Columns` | function | `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:59` | `func (ts Tokens) Columns(` |
| `Token` | struct | `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:15` | `` |
| `WriteTo` | function | `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:72` | `func (ts Tokens) WriteTo(` |
| `asHCLSyntax` | function | `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:33` | `func (t *Token) asHCLSyntax(` |
| `newIdentToken` | function | `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:117` | `func newIdentToken(` |
| `testValue` | function | `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:52` | `func (ts Tokens) testValue(` |
| `walkChildNodes` | function | `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:109` | `func (ts Tokens) walkChildNodes(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/json/ast.go:21` | `func (n *objectVal) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/json/ast.go:35` | `func (n *objectAttr) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/json/ast.go:49` | `func (n *arrayVal) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/json/ast.go:62` | `func (n *booleanVal) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/json/ast.go:75` | `func (n *numberVal) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/json/ast.go:88` | `func (n *stringVal) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/json/ast.go:100` | `func (n *nullVal) Range(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/json/ast.go:115` | `func (n invalidVal) Range(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/json/ast.go:25` | `func (n *objectVal) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/json/ast.go:39` | `func (n *objectAttr) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/json/ast.go:53` | `func (n *arrayVal) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/json/ast.go:66` | `func (n *booleanVal) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/json/ast.go:79` | `func (n *numberVal) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/json/ast.go:92` | `func (n *stringVal) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/json/ast.go:104` | `func (n *nullVal) StartRange(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/json/ast.go:119` | `func (n invalidVal) StartRange(` |
| `arrayVal` | struct | `teamserver/pkg/profile/yaotl/json/ast.go:43` | `` |
| `booleanVal` | struct | `teamserver/pkg/profile/yaotl/json/ast.go:57` | `` |
| `invalidVal` | struct | `teamserver/pkg/profile/yaotl/json/ast.go:111` | `` |
| `node` | interface | `teamserver/pkg/profile/yaotl/json/ast.go:9` | `` |
| `nullVal` | struct | `teamserver/pkg/profile/yaotl/json/ast.go:96` | `` |
| `numberVal` | struct | `teamserver/pkg/profile/yaotl/json/ast.go:70` | `` |
| `objectAttr` | struct | `teamserver/pkg/profile/yaotl/json/ast.go:29` | `` |
| `objectVal` | struct | `teamserver/pkg/profile/yaotl/json/ast.go:14` | `` |
| `stringVal` | struct | `teamserver/pkg/profile/yaotl/json/ast.go:83` | `` |
| `keywordSuggestion` | function | `teamserver/pkg/profile/yaotl/json/didyoumean.go:12` | `func keywordSuggestion(` |
| `nameSuggestion` | function | `teamserver/pkg/profile/yaotl/json/didyoumean.go:25` | `func nameSuggestion(` |
| `TestKeywordSuggestion` | function | `teamserver/pkg/profile/yaotl/json/didyoumean_test.go:5` | `func TestKeywordSuggestion(` |
| `Fuzz` | function | `teamserver/pkg/profile/yaotl/json/fuzz/config/fuzz.go:7` | `func Fuzz(` |
| `ContextString` | function | `teamserver/pkg/profile/yaotl/json/navigation.go:13` | `func (n navigation) ContextString(` |
| `navigation` | struct | `teamserver/pkg/profile/yaotl/json/navigation.go:8` | `` |
| `navigationStepsRev` | function | `teamserver/pkg/profile/yaotl/json/navigation.go:32` | `func navigationStepsRev(` |
| `TestNavigationContextString` | function | `teamserver/pkg/profile/yaotl/json/navigation_test.go:9` | `func TestNavigationContextString(` |
| `parseArray` | function | `teamserver/pkg/profile/yaotl/json/parser.go:261` | `func parseArray(` |
| `parseExpression` | function | `teamserver/pkg/profile/yaotl/json/parser.go:26` | `func parseExpression(` |
| `parseFileContent` | function | `teamserver/pkg/profile/yaotl/json/parser.go:11` | `func parseFileContent(` |
| `parseKeyword` | function | `teamserver/pkg/profile/yaotl/json/parser.go:461` | `func parseKeyword(` |
| `parseNumber` | function | `teamserver/pkg/profile/yaotl/json/parser.go:363` | `func parseNumber(` |
| `parseObject` | function | `teamserver/pkg/profile/yaotl/json/parser.go:110` | `func parseObject(` |
| `parseString` | function | `teamserver/pkg/profile/yaotl/json/parser.go:406` | `func parseString(` |
| `parseValue` | function | `teamserver/pkg/profile/yaotl/json/parser.go:41` | `func parseValue(` |
| `tokenCanStartValue` | function | `teamserver/pkg/profile/yaotl/json/parser.go:101` | `func tokenCanStartValue(` |
| `TestParse` | function | `teamserver/pkg/profile/yaotl/json/parser_test.go:15` | `func TestParse(` |
| `TestParseWithPos` | function | `teamserver/pkg/profile/yaotl/json/parser_test.go:619` | `func TestParseWithPos(` |
| `init` | function | `teamserver/pkg/profile/yaotl/json/parser_test.go:11` | `func init(` |
| `mustBigFloat` | function | `teamserver/pkg/profile/yaotl/json/parser_test.go:661` | `func mustBigFloat(` |
| `Peek` | function | `teamserver/pkg/profile/yaotl/json/peeker.go:15` | `func (p *peeker) Peek(` |
| `Read` | function | `teamserver/pkg/profile/yaotl/json/peeker.go:19` | `func (p *peeker) Read(` |
| `newPeeker` | function | `teamserver/pkg/profile/yaotl/json/peeker.go:8` | `func newPeeker(` |
| `peeker` | struct | `teamserver/pkg/profile/yaotl/json/peeker.go:3` | `` |
| `Parse` | function | `teamserver/pkg/profile/yaotl/json/public.go:20` | `func Parse(` |
| `ParseExpression` | function | `teamserver/pkg/profile/yaotl/json/public.go:76` | `func ParseExpression(` |
| `ParseExpressionWithStartPos` | function | `teamserver/pkg/profile/yaotl/json/public.go:83` | `func ParseExpressionWithStartPos(` |
| `ParseFile` | function | `teamserver/pkg/profile/yaotl/json/public.go:92` | `func ParseFile(` |
| `ParseWithStartPos` | function | `teamserver/pkg/profile/yaotl/json/public.go:29` | `func ParseWithStartPos(` |
| `TestParseExpression` | function | `teamserver/pkg/profile/yaotl/json/public_test.go:187` | `func TestParseExpression(` |
| `TestParseExpressionWithStartPos` | function | `teamserver/pkg/profile/yaotl/json/public_test.go:274` | `func TestParseExpressionWithStartPos(` |
| `TestParseExpression_malformed` | function | `teamserver/pkg/profile/yaotl/json/public_test.go:260` | `func TestParseExpression_malformed(` |
| `TestParseTemplate` | function | `teamserver/pkg/profile/yaotl/json/public_test.go:29` | `func TestParseTemplate(` |
| `TestParseTemplateUnwrap` | function | `teamserver/pkg/profile/yaotl/json/public_test.go:65` | `func TestParseTemplateUnwrap(` |
| `TestParseWithStartPos` | function | `teamserver/pkg/profile/yaotl/json/public_test.go:117` | `func TestParseWithStartPos(` |
| `TestParse_malformed` | function | `teamserver/pkg/profile/yaotl/json/public_test.go:101` | `func TestParse_malformed(` |
| `TestParse_nonObject` | function | `teamserver/pkg/profile/yaotl/json/public_test.go:12` | `func TestParse_nonObject(` |
| `GoString` | function | `teamserver/pkg/profile/yaotl/json/scanner.go:300` | `func (t token) GoString(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/json/scanner.go:280` | `func (p *pos) Range(` |
| `byteCanStartKeyword` | function | `teamserver/pkg/profile/yaotl/json/scanner.go:157` | `func byteCanStartKeyword(` |
| `byteCanStartNumber` | function | `teamserver/pkg/profile/yaotl/json/scanner.go:124` | `func byteCanStartNumber(` |
| `isAlphabetical` | function | `teamserver/pkg/profile/yaotl/json/scanner.go:304` | `func isAlphabetical(` |
| `pos` | struct | `teamserver/pkg/profile/yaotl/json/scanner.go:275` | `` |
| `posRange` | function | `teamserver/pkg/profile/yaotl/json/scanner.go:292` | `func posRange(` |
| `scan` | function | `teamserver/pkg/profile/yaotl/json/scanner.go:41` | `func scan(` |
| `scanKeyword` | function | `teamserver/pkg/profile/yaotl/json/scanner.go:172` | `func scanKeyword(` |
| `scanNumber` | function | `teamserver/pkg/profile/yaotl/json/scanner.go:138` | `func scanNumber(` |
| `scanString` | function | `teamserver/pkg/profile/yaotl/json/scanner.go:189` | `func scanString(` |
| `skipWhitespace` | function | `teamserver/pkg/profile/yaotl/json/scanner.go:241` | `func skipWhitespace(` |
| `token` | struct | `teamserver/pkg/profile/yaotl/json/scanner.go:28` | `` |
| `TestScan` | function | `teamserver/pkg/profile/yaotl/json/scanner_test.go:12` | `func TestScan(` |
| `AsTraversal` | function | `teamserver/pkg/profile/yaotl/json/structure.go:566` | `func (e *expression) AsTraversal(` |
| `Content` | function | `teamserver/pkg/profile/yaotl/json/structure.go:29` | `func (b *body) Content(` |
| `ExprCall` | function | `teamserver/pkg/profile/yaotl/json/structure.go:583` | `func (e *expression) ExprCall(` |
| `ExprList` | function | `teamserver/pkg/profile/yaotl/json/structure.go:606` | `func (e *expression) ExprList(` |
| `ExprMap` | function | `teamserver/pkg/profile/yaotl/json/structure.go:620` | `func (e *expression) ExprMap(` |
| `JustAttributes` | function | `teamserver/pkg/profile/yaotl/json/structure.go:169` | `func (b *body) JustAttributes(` |
| `MissingItemRange` | function | `teamserver/pkg/profile/yaotl/json/structure.go:219` | `func (b *body) MissingItemRange(` |
| `PartialContent` | function | `teamserver/pkg/profile/yaotl/json/structure.go:77` | `func (b *body) PartialContent(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/json/structure.go:557` | `func (e *expression) Range(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/json/structure.go:561` | `func (e *expression) StartRange(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/json/structure.go:381` | `func (e *expression) Value(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/json/structure.go:513` | `func (e *expression) Variables(` |
| `body` | struct | `teamserver/pkg/profile/yaotl/json/structure.go:14` | `` |
| `collectDeepAttrs` | function | `teamserver/pkg/profile/yaotl/json/structure.go:325` | `func (b *body) collectDeepAttrs(` |
| `expression` | struct | `teamserver/pkg/profile/yaotl/json/structure.go:25` | `` |
| `unpackBlock` | function | `teamserver/pkg/profile/yaotl/json/structure.go:232` | `func (b *body) unpackBlock(` |
| `TestBodyContent` | function | `teamserver/pkg/profile/yaotl/json/structure_test.go:1080` | `func TestBodyContent(` |
| `TestBodyPartialContent` | function | `teamserver/pkg/profile/yaotl/json/structure_test.go:15` | `func TestBodyPartialContent(` |
| `TestExpressionAsTraversal` | function | `teamserver/pkg/profile/yaotl/json/structure_test.go:1326` | `func TestExpressionAsTraversal(` |
| `TestExpressionValue_Diags` | function | `teamserver/pkg/profile/yaotl/json/structure_test.go:1418` | `func TestExpressionValue_Diags(` |
| `TestExpressionVariables` | function | `teamserver/pkg/profile/yaotl/json/structure_test.go:1237` | `func TestExpressionVariables(` |
| `TestExpression_Value` | function | `teamserver/pkg/profile/yaotl/json/structure_test.go:1357` | `func TestExpression_Value(` |
| `TestJustAttributes` | function | `teamserver/pkg/profile/yaotl/json/structure_test.go:1139` | `func TestJustAttributes(` |
| `TestStaticExpressionList` | function | `teamserver/pkg/profile/yaotl/json/structure_test.go:1338` | `func TestStaticExpressionList(` |
| `String` | function | `teamserver/pkg/profile/yaotl/json/tokentype_string.go:24` | `func (i tokenType) String(` |
| `Content` | function | `teamserver/pkg/profile/yaotl/merged.go:85` | `func (mb mergedBodies) Content(` |
| `EmptyBody` | function | `teamserver/pkg/profile/yaotl/merged.go:71` | `func EmptyBody(` |
| `JustAttributes` | function | `teamserver/pkg/profile/yaotl/merged.go:96` | `func (mb mergedBodies) JustAttributes(` |
| `MergeBodies` | function | `teamserver/pkg/profile/yaotl/merged.go:25` | `func MergeBodies(` |
| `MergeFiles` | function | `teamserver/pkg/profile/yaotl/merged.go:15` | `func MergeFiles(` |
| `MissingItemRange` | function | `teamserver/pkg/profile/yaotl/merged.go:130` | `func (mb mergedBodies) MissingItemRange(` |
| `PartialContent` | function | `teamserver/pkg/profile/yaotl/merged.go:92` | `func (mb mergedBodies) PartialContent(` |
| `mergedContent` | function | `teamserver/pkg/profile/yaotl/merged.go:142` | `func (mb mergedBodies) mergedContent(` |
| `ApplyPath` | function | `teamserver/pkg/profile/yaotl/ops.go:404` | `func ApplyPath(` |
| `GetAttr` | function | `teamserver/pkg/profile/yaotl/ops.go:262` | `func GetAttr(` |
| `Index` | function | `teamserver/pkg/profile/yaotl/ops.go:23` | `func Index(` |
| `CanSliceBytes` | function | `teamserver/pkg/profile/yaotl/pos.go:155` | `func (r Range) CanSliceBytes(` |
| `ContainsOffset` | function | `teamserver/pkg/profile/yaotl/pos.go:112` | `func (r Range) ContainsOffset(` |
| `ContainsPos` | function | `teamserver/pkg/profile/yaotl/pos.go:106` | `func (r Range) ContainsPos(` |
| `Empty` | function | `teamserver/pkg/profile/yaotl/pos.go:145` | `func (r Range) Empty(` |
| `Overlap` | function | `teamserver/pkg/profile/yaotl/pos.go:219` | `func (r Range) Overlap(` |
| `Overlaps` | function | `teamserver/pkg/profile/yaotl/pos.go:197` | `func (r Range) Overlaps(` |
| `PartitionAround` | function | `teamserver/pkg/profile/yaotl/pos.go:257` | `func (r Range) PartitionAround(` |
| `Pos` | struct | `teamserver/pkg/profile/yaotl/pos.go:10` | `` |
| `Ptr` | function | `teamserver/pkg/profile/yaotl/pos.go:120` | `func (r Range) Ptr(` |
| `Range` | struct | `teamserver/pkg/profile/yaotl/pos.go:43` | `` |
| `RangeBetween` | function | `teamserver/pkg/profile/yaotl/pos.go:58` | `func RangeBetween(` |
| `RangeOver` | function | `teamserver/pkg/profile/yaotl/pos.go:74` | `func RangeOver(` |
| `SliceBytes` | function | `teamserver/pkg/profile/yaotl/pos.go:176` | `func (r Range) SliceBytes(` |
| `String` | function | `teamserver/pkg/profile/yaotl/pos.go:127` | `func (r Range) String(` |
| `Bytes` | function | `teamserver/pkg/profile/yaotl/pos_scanner.go:144` | `func (sc *RangeScanner) Bytes(` |
| `Err` | function | `teamserver/pkg/profile/yaotl/pos_scanner.go:150` | `func (sc *RangeScanner) Err(` |
| `NewRangeScanner` | function | `teamserver/pkg/profile/yaotl/pos_scanner.go:41` | `func NewRangeScanner(` |
| `NewRangeScannerFragment` | function | `teamserver/pkg/profile/yaotl/pos_scanner.go:49` | `func NewRangeScannerFragment(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/pos_scanner.go:138` | `func (sc *RangeScanner) Range(` |
| `RangeScanner` | struct | `teamserver/pkg/profile/yaotl/pos_scanner.go:21` | `` |
| `Scan` | function | `teamserver/pkg/profile/yaotl/pos_scanner.go:58` | `func (sc *RangeScanner) Scan(` |
| `AttributeSchema` | struct | `teamserver/pkg/profile/yaotl/schema.go:12` | `` |
| `BlockHeaderSchema` | struct | `teamserver/pkg/profile/yaotl/schema.go:5` | `` |
| `BodySchema` | struct | `teamserver/pkg/profile/yaotl/schema.go:18` | `` |
| `TestMain` | function | `teamserver/pkg/profile/yaotl/specsuite/spec_test.go:15` | `func TestMain(` |
| `TestSpec` | function | `teamserver/pkg/profile/yaotl/specsuite/spec_test.go:44` | `func TestSpec(` |
| `build` | function | `teamserver/pkg/profile/yaotl/specsuite/spec_test.go:30` | `func build(` |
| `goBuild` | function | `teamserver/pkg/profile/yaotl/specsuite/spec_test.go:91` | `func goBuild(` |
| `Range` | function | `teamserver/pkg/profile/yaotl/static_expr.go:34` | `func (e staticExpr) Range(` |
| `StartRange` | function | `teamserver/pkg/profile/yaotl/static_expr.go:38` | `func (e staticExpr) StartRange(` |
| `StaticExpr` | function | `teamserver/pkg/profile/yaotl/static_expr.go:22` | `func StaticExpr(` |
| `Value` | function | `teamserver/pkg/profile/yaotl/static_expr.go:26` | `func (e staticExpr) Value(` |
| `Variables` | function | `teamserver/pkg/profile/yaotl/static_expr.go:30` | `func (e staticExpr) Variables(` |
| `staticExpr` | struct | `teamserver/pkg/profile/yaotl/static_expr.go:7` | `` |
| `Attribute` | struct | `teamserver/pkg/profile/yaotl/structure.go:85` | `` |
| `Block` | struct | `teamserver/pkg/profile/yaotl/structure.go:19` | `` |
| `Body` | interface | `teamserver/pkg/profile/yaotl/structure.go:41` | `` |
| `BodyContent` | struct | `teamserver/pkg/profile/yaotl/structure.go:77` | `` |
| `ByType` | function | `teamserver/pkg/profile/yaotl/structure.go:141` | `func (els Blocks) ByType(` |
| `Expression` | interface | `teamserver/pkg/profile/yaotl/structure.go:95` | `` |
| `File` | struct | `teamserver/pkg/profile/yaotl/structure.go:8` | `` |
| `OfType` | function | `teamserver/pkg/profile/yaotl/structure.go:129` | `func (els Blocks) OfType(` |
| `AttributeAtPos` | function | `teamserver/pkg/profile/yaotl/structure_at_pos.go:105` | `func (f *File) AttributeAtPos(` |
| `BlocksAtPos` | function | `teamserver/pkg/profile/yaotl/structure_at_pos.go:25` | `func (f *File) BlocksAtPos(` |
| `InnermostBlockAtPos` | function | `teamserver/pkg/profile/yaotl/structure_at_pos.go:64` | `func (f *File) InnermostBlockAtPos(` |
| `OutermostBlockAtPos` | function | `teamserver/pkg/profile/yaotl/structure_at_pos.go:44` | `func (f *File) OutermostBlockAtPos(` |
| `OutermostExprAtPos` | function | `teamserver/pkg/profile/yaotl/structure_at_pos.go:86` | `func (f *File) OutermostExprAtPos(` |
| `IsRelative` | function | `teamserver/pkg/profile/yaotl/traversal.go:122` | `func (t Traversal) IsRelative(` |
| `Join` | function | `teamserver/pkg/profile/yaotl/traversal.go:208` | `func (t TraversalSplit) Join(` |
| `RootName` | function | `teamserver/pkg/profile/yaotl/traversal.go:151` | `func (t Traversal) RootName(` |
| `RootName` | function | `teamserver/pkg/profile/yaotl/traversal.go:213` | `func (t TraversalSplit) RootName(` |
| `SimpleSplit` | function | `teamserver/pkg/profile/yaotl/traversal.go:139` | `func (t Traversal) SimpleSplit(` |
| `SourceRange` | function | `teamserver/pkg/profile/yaotl/traversal.go:160` | `func (t Traversal) SourceRange(` |
| `SourceRange` | function | `teamserver/pkg/profile/yaotl/traversal.go:246` | `func (tn TraverseRoot) SourceRange(` |
| `SourceRange` | function | `teamserver/pkg/profile/yaotl/traversal.go:261` | `func (tn TraverseAttr) SourceRange(` |
| `SourceRange` | function | `teamserver/pkg/profile/yaotl/traversal.go:276` | `func (tn TraverseIndex) SourceRange(` |
| `SourceRange` | function | `teamserver/pkg/profile/yaotl/traversal.go:291` | `func (tn TraverseSplat) SourceRange(` |
| `TraversalJoin` | function | `teamserver/pkg/profile/yaotl/traversal.go:24` | `func TraversalJoin(` |
| `TraversalSplit` | struct | `teamserver/pkg/profile/yaotl/traversal.go:177` | `` |
| `TraversalStep` | function | `teamserver/pkg/profile/yaotl/traversal.go:242` | `func (tn TraverseRoot) TraversalStep(` |
| `TraversalStep` | function | `teamserver/pkg/profile/yaotl/traversal.go:257` | `func (tn TraverseAttr) TraversalStep(` |
| `TraversalStep` | function | `teamserver/pkg/profile/yaotl/traversal.go:272` | `func (tn TraverseIndex) TraversalStep(` |
| `TraversalStep` | function | `teamserver/pkg/profile/yaotl/traversal.go:287` | `func (tn TraverseSplat) TraversalStep(` |
| `Traverse` | function | `teamserver/pkg/profile/yaotl/traversal.go:196` | `func (t TraversalSplit) Traverse(` |
| `TraverseAbs` | function | `teamserver/pkg/profile/yaotl/traversal.go:62` | `func (t Traversal) TraverseAbs(` |
| `TraverseAbs` | function | `teamserver/pkg/profile/yaotl/traversal.go:184` | `func (t TraversalSplit) TraverseAbs(` |
| `TraverseAttr` | struct | `teamserver/pkg/profile/yaotl/traversal.go:251` | `` |
| `TraverseIndex` | struct | `teamserver/pkg/profile/yaotl/traversal.go:266` | `` |
| `TraverseRel` | function | `teamserver/pkg/profile/yaotl/traversal.go:41` | `func (t Traversal) TraverseRel(` |
| `TraverseRel` | function | `teamserver/pkg/profile/yaotl/traversal.go:190` | `func (t TraversalSplit) TraverseRel(` |
| `TraverseRoot` | struct | `teamserver/pkg/profile/yaotl/traversal.go:234` | `` |
| `TraverseSplat` | struct | `teamserver/pkg/profile/yaotl/traversal.go:281` | `` |
| `Traverser` | interface | `teamserver/pkg/profile/yaotl/traversal.go:218` | `` |
| `isTraverser` | struct | `teamserver/pkg/profile/yaotl/traversal.go:225` | `` |
| `isTraverserSigil` | function | `teamserver/pkg/profile/yaotl/traversal.go:228` | `func (tr isTraverser) isTraverserSigil(` |
| `AbsTraversalForExpr` | function | `teamserver/pkg/profile/yaotl/traversal_for_expr.go:20` | `func AbsTraversalForExpr(` |
| `ExprAsKeyword` | function | `teamserver/pkg/profile/yaotl/traversal_for_expr.go:108` | `func ExprAsKeyword(` |
| `RelTraversalForExpr` | function | `teamserver/pkg/profile/yaotl/traversal_for_expr.go:52` | `func RelTraversalForExpr(` |
| `AgentService` | struct | `teamserver/pkg/service/agent.go:28` | `` |
| `Command` | struct | `teamserver/pkg/service/agent.go:19` | `` |
| `CommandParam` | struct | `teamserver/pkg/service/agent.go:13` | `` |
| `Json` | function | `teamserver/pkg/service/agent.go:58` | `func (a *AgentService) Json(` |
| `NewAgentService` | function | `teamserver/pkg/service/agent.go:45` | `func NewAgentService(` |
| `SendAgentBuildRequest` | function | `teamserver/pkg/service/agent.go:140` | `func (a *AgentService) SendAgentBuildRequest(` |
| `SendResponse` | function | `teamserver/pkg/service/agent.go:87` | `func (a *AgentService) SendResponse(` |
| `SendTask` | function | `teamserver/pkg/service/agent.go:67` | `func (a *AgentService) SendTask(` |
| `Json` | function | `teamserver/pkg/service/listener.go:37` | `func (l *ListenerService) Json(` |
| `ListenerService` | struct | `teamserver/pkg/service/listener.go:8` | `` |
| `Start` | function | `teamserver/pkg/service/listener.go:17` | `func (l *ListenerService) Start(` |
| `AgentExist` | function | `teamserver/pkg/service/service.go:703` | `func (s *Service) AgentExist(` |
| `ClientClose` | function | `teamserver/pkg/service/service.go:713` | `func (s *Service) ClientClose(` |
| `ListenerAdd` | function | `teamserver/pkg/service/service.go:775` | `func (s *Service) ListenerAdd(` |
| `ListenerExist` | function | `teamserver/pkg/service/service.go:763` | `func (s *Service) ListenerExist(` |
| `NewService` | function | `teamserver/pkg/service/service.go:27` | `func NewService(` |
| `Start` | function | `teamserver/pkg/service/service.go:35` | `func (s *Service) Start(` |
| `authenticate` | function | `teamserver/pkg/service/service.go:75` | `func (s *Service) authenticate(` |
| `dispatch` | function | `teamserver/pkg/service/service.go:166` | `func (s *Service) dispatch(` |
| `handleConnection` | function | `teamserver/pkg/service/service.go:50` | `func (s *Service) handleConnection(` |
| `routine` | function | `teamserver/pkg/service/service.go:144` | `func (s *Service) routine(` |
| `ClientService` | struct | `teamserver/pkg/service/types.go:13` | `` |
| `ConfigService` | struct | `teamserver/pkg/service/types.go:30` | `` |
| `Service` | struct | `teamserver/pkg/service/types.go:36` | `` |
| `Teamserver` | interface | `teamserver/pkg/service/types.go:19` | `` |
| `WriteJson` | function | `teamserver/pkg/service/types.go:69` | `func (c *ClientService) WriteJson(` |
| `Close` | function | `teamserver/pkg/socks/socks.go:62` | `func (s *Socks) Close(` |
| `NewSocks` | function | `teamserver/pkg/socks/socks.go:17` | `func NewSocks(` |
| `SetHandler` | function | `teamserver/pkg/socks/socks.go:29` | `func (s *Socks) SetHandler(` |
| `Socks` | struct | `teamserver/pkg/socks/socks.go:9` | `` |
| `Start` | function | `teamserver/pkg/socks/socks.go:35` | `func (s *Socks) Start(` |
| `CreateResponsePackage` | function | `teamserver/pkg/socks/util.go:239` | `func CreateResponsePackage(` |
| `NegotiationHeader` | struct | `teamserver/pkg/socks/util.go:64` | `` |
| `ReadSocksHeader` | function | `teamserver/pkg/socks/util.go:114` | `func ReadSocksHeader(` |
| `SendAddressTypeNotSupported` | function | `teamserver/pkg/socks/util.go:260` | `func SendAddressTypeNotSupported(` |
| `SendCommandNotSupported` | function | `teamserver/pkg/socks/util.go:265` | `func SendCommandNotSupported(` |
| `SendConnectFailure` | function | `teamserver/pkg/socks/util.go:270` | `func SendConnectFailure(` |
| `SendConnectSuccess` | function | `teamserver/pkg/socks/util.go:255` | `func SendConnectSuccess(` |
| `SocksHeader` | struct | `teamserver/pkg/socks/util.go:55` | `` |
| `SubNegotiationClient` | function | `teamserver/pkg/socks/util.go:70` | `func SubNegotiationClient(` |
| `ByteCountSI` | function | `teamserver/pkg/utils/utils.go:90` | `func ByteCountSI(` |
| `EncodeCommand` | function | `teamserver/pkg/utils/utils.go:65` | `func EncodeCommand(` |
| `GenerateID` | function | `teamserver/pkg/utils/utils.go:34` | `func GenerateID(` |
| `GenerateString` | function | `teamserver/pkg/utils/utils.go:53` | `func GenerateString(` |
| `GetTeamserverPath` | function | `teamserver/pkg/utils/utils.go:104` | `func GetTeamserverPath(` |
| `HexIntToBigEndian` | function | `teamserver/pkg/utils/utils.go:141` | `func HexIntToBigEndian(` |
| `HexIntToString` | function | `teamserver/pkg/utils/utils.go:135` | `func HexIntToString(` |
| `IP2Inet` | function | `teamserver/pkg/utils/utils.go:70` | `func IP2Inet(` |
| `IntToHexString` | function | `teamserver/pkg/utils/utils.go:131` | `func IntToHexString(` |
| `Port2Htons` | function | `teamserver/pkg/utils/utils.go:84` | `func Port2Htons(` |
| `UTF16BytesToString` | function | `teamserver/pkg/utils/utils.go:25` | `func UTF16BytesToString(` |
| `Author` | struct | `teamserver/pkg/webhook/discord.go:22` | `` |
| `Embed` | struct | `teamserver/pkg/webhook/discord.go:10` | `` |
| `Field` | struct | `teamserver/pkg/webhook/discord.go:28` | `` |
| `Footer` | struct | `teamserver/pkg/webhook/discord.go:42` | `` |
| `Image` | struct | `teamserver/pkg/webhook/discord.go:38` | `` |
| `Message` | struct | `teamserver/pkg/webhook/discord.go:3` | `` |
| `Thumbnail` | struct | `teamserver/pkg/webhook/discord.go:34` | `` |
| `BoolPtr` | function | `teamserver/pkg/webhook/webhook.go:24` | `func BoolPtr(` |
| `NewAgent` | function | `teamserver/pkg/webhook/webhook.go:32` | `func (w *WebHook) NewAgent(` |
| `NewWebHook` | function | `teamserver/pkg/webhook/webhook.go:28` | `func NewWebHook(` |
| `SetDiscord` | function | `teamserver/pkg/webhook/webhook.go:134` | `func (w *WebHook) SetDiscord(` |
| `StringPtr` | function | `teamserver/pkg/webhook/webhook.go:20` | `func StringPtr(` |
| `WebHook` | struct | `teamserver/pkg/webhook/webhook.go:12` | `` |
| `StatusToString` | function | `teamserver/pkg/win32/types.go:78` | `func StatusToString(` |
