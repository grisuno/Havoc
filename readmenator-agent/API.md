# API (page 1 of 8)
Pages: [API.md](API.md), [API_p2.md](API_p2.md), [API_p3.md](API_p3.md), [API_p4.md](API_p4.md), [API_p5.md](API_p5.md), [API_p6.md](API_p6.md), [API_p7.md](API_p7.md), [API_p8.md](API_p8.md)

## client/include/Havoc/CmdLine.hpp
Imported by: `client/src/Havoc/Havoc.cc`
- `cast` (function) `client/include/Havoc/CmdLine.hpp:47` `public:
            static Target cast(const Source &arg)`
- `cast` (function) `client/include/Havoc/CmdLine.hpp:60` `public:
            static Target cast(const Source &arg)`
- `cast` (function) `client/include/Havoc/CmdLine.hpp:68` `public:
            static std::string cast(const Source &arg)`
- `cast` (function) `client/include/Havoc/CmdLine.hpp:78` `public:
            static Target cast(const std::string &arg)`
- `lexical_cast` (function) `client/include/Havoc/CmdLine.hpp:98` `Target lexical_cast(const Source &arg)`
- `demangle` (function) `client/include/Havoc/CmdLine.hpp:103` `static inline std::string demangle(const std::string &name)`
- `readable_typename` (function) `client/include/Havoc/CmdLine.hpp:113` `template <class T>
        std::string readable_typename()`
- `default_value` (function) `client/include/Havoc/CmdLine.hpp:119` `template <class T>
        std::string default_value(T def)`
- `cmdline_error` (function) `client/include/Havoc/CmdLine.hpp:136` `public:
        cmdline_error(const std::string &msg): msg(msg)`
- `what` (function) `client/include/Havoc/CmdLine.hpp:138` `const char *what() const throw()`
- `operator` (function) `client/include/Havoc/CmdLine.hpp:145` `T operator()(const std::string &str)`
- `range_reader` (function) `client/include/Havoc/CmdLine.hpp:152` `range_reader(const T &low, const T &high): low(low), high(high)`
- `operator` (function) `client/include/Havoc/CmdLine.hpp:153` `T operator()(const std::string &s) const`
- `range` (function) `client/include/Havoc/CmdLine.hpp:163` `template <class T>
    range_reader<T> range(const T &low, const T &high)`
- `operator` (function) `client/include/Havoc/CmdLine.hpp:170` `T operator()(const std::string &s)`
- `add` (function) `client/include/Havoc/CmdLine.hpp:176` `void add(const T &v)`
- `oneof` (function) `client/include/Havoc/CmdLine.hpp:182` `template <class T>
    oneof_reader<T> oneof(T a1)`
- `oneof` (function) `client/include/Havoc/CmdLine.hpp:190` `template <class T>
    oneof_reader<T> oneof(T a1, T a2)`
- `oneof` (function) `client/include/Havoc/CmdLine.hpp:199` `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3)`
- `oneof` (function) `client/include/Havoc/CmdLine.hpp:209` `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4)`
- `oneof` (function) `client/include/Havoc/CmdLine.hpp:220` `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5)`
- `oneof` (function) `client/include/Havoc/CmdLine.hpp:232` `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6)`
- `oneof` (function) `client/include/Havoc/CmdLine.hpp:245` `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7)`
- `oneof` (function) `client/include/Havoc/CmdLine.hpp:259` `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8)`
- `oneof` (function) `client/include/Havoc/CmdLine.hpp:274` `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9)`
- `oneof` (function) `client/include/Havoc/CmdLine.hpp:290` `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9...`
- `parser` (function) `client/include/Havoc/CmdLine.hpp:310` `public:
        parser()`
- `add` (function) `client/include/Havoc/CmdLine.hpp:318` `void add(const std::string &name,
                 char short_name=0,
                 const std:...`
- `add` (function) `client/include/Havoc/CmdLine.hpp:327` `template <class T>
        void add(const std::string &name,
                 char short_name=0,
...`
- `add` (function) `client/include/Havoc/CmdLine.hpp:336` `void add(const std::string &name,
                 char short_name=0,
                 const std:...`
- `footer` (function) `client/include/Havoc/CmdLine.hpp:347` `void footer(const std::string &f)`
- `set_program_name` (function) `client/include/Havoc/CmdLine.hpp:351` `void set_program_name(const std::string &name)`
- `exist` (function) `client/include/Havoc/CmdLine.hpp:355` `bool exist(const std::string &name) const`
- `get` (function) `client/include/Havoc/CmdLine.hpp:361` `template <class T>
        const T &get(const std::string &name) const`
- `rest` (function) `client/include/Havoc/CmdLine.hpp:368` `const std::vector<std::string> &rest() const`
- `parse` (function) `client/include/Havoc/CmdLine.hpp:372` `bool parse(const std::string &arg)`
- `parse` (function) `client/include/Havoc/CmdLine.hpp:414` `bool parse(const std::vector<std::string> &args)`
- `argv` (function) `client/include/Havoc/CmdLine.hpp:416` `std::vector<const char*> argv(argc);`
- `parse` (function) `client/include/Havoc/CmdLine.hpp:424` `bool parse(int argc, const char * const argv[])`
- `parse_check` (function) `client/include/Havoc/CmdLine.hpp:525` `void parse_check(const std::string &arg)`
- `parse_check` (function) `client/include/Havoc/CmdLine.hpp:531` `void parse_check(const std::vector<std::string> &args)`
- `parse_check` (function) `client/include/Havoc/CmdLine.hpp:537` `void parse_check(int argc, char *argv[])`
- `error` (function) `client/include/Havoc/CmdLine.hpp:543` `std::string error() const`
- `error_full` (function) `client/include/Havoc/CmdLine.hpp:547` `std::string error_full() const`
- `usage` (function) `client/include/Havoc/CmdLine.hpp:554` `std::string usage() const`
- `check` (function) `client/include/Havoc/CmdLine.hpp:587` `private:

        void check(int argc, bool ok)`
- `set_option` (function) `client/include/Havoc/CmdLine.hpp:599` `void set_option(const std::string &name)`
- `set_option` (function) `client/include/Havoc/CmdLine.hpp:610` `void set_option(const std::string &name, const std::string &value)`
- `option_without_value` (function) `client/include/Havoc/CmdLine.hpp:640` `public:
            option_without_value(const std::string &name,
                               ...`
- `has_value` (function) `client/include/Havoc/CmdLine.hpp:647` `bool has_value() const`
- `set` (function) `client/include/Havoc/CmdLine.hpp:649` `bool set()`
- `set` (function) `client/include/Havoc/CmdLine.hpp:654` `bool set(const std::string &)`
- `has_set` (function) `client/include/Havoc/CmdLine.hpp:658` `bool has_set() const`
- `valid` (function) `client/include/Havoc/CmdLine.hpp:662` `bool valid() const`
- `must` (function) `client/include/Havoc/CmdLine.hpp:666` `bool must() const`
- `name` (function) `client/include/Havoc/CmdLine.hpp:670` `const std::string &name() const`
- `short_name` (function) `client/include/Havoc/CmdLine.hpp:674` `char short_name() const`
- `description` (function) `client/include/Havoc/CmdLine.hpp:678` `const std::string &description() const`
- `short_description` (function) `client/include/Havoc/CmdLine.hpp:682` `std::string short_description() const`
- `option_with_value` (function) `client/include/Havoc/CmdLine.hpp:696` `public:
            option_with_value(const std::string &name,
                              char...`
- `get` (function) `client/include/Havoc/CmdLine.hpp:707` `const T &get() const`
- `has_value` (function) `client/include/Havoc/CmdLine.hpp:711` `bool has_value() const`
- `set` (function) `client/include/Havoc/CmdLine.hpp:713` `bool set()`
- `set` (function) `client/include/Havoc/CmdLine.hpp:717` `bool set(const std::string &value)`
- `has_set` (function) `client/include/Havoc/CmdLine.hpp:728` `bool has_set() const`
- `valid` (function) `client/include/Havoc/CmdLine.hpp:732` `bool valid() const`
- `must` (function) `client/include/Havoc/CmdLine.hpp:737` `bool must() const`
- `name` (function) `client/include/Havoc/CmdLine.hpp:741` `const std::string &name() const`
- `short_name` (function) `client/include/Havoc/CmdLine.hpp:745` `char short_name() const`
- `description` (function) `client/include/Havoc/CmdLine.hpp:749` `const std::string &description() const`
- `short_description` (function) `client/include/Havoc/CmdLine.hpp:753` `std::string short_description() const`
- `full_description` (function) `client/include/Havoc/CmdLine.hpp:758` `protected:
            std::string full_description(const std::string &desc)`
- `option_with_value_with_reader` (function) `client/include/Havoc/CmdLine.hpp:780` `public:
            option_with_value_with_reader(const std::string &name,
                      ...`
- `read` (function) `client/include/Havoc/CmdLine.hpp:790` `private:
            T read(const std::string &s)`

## client/include/Havoc/Connector.hpp
Depends on: `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
Imported by: `client/src/Havoc/Connector.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Havoc.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/global.cc`
- `Disconnect` (function) `client/include/Havoc/Connector.hpp:27` `bool Disconnect();`
- `SendLogin` (function) `client/include/Havoc/Connector.hpp:29` `void SendLogin();`
- `SendPackage` (function) `client/include/Havoc/Connector.hpp:30` `void SendPackage( Util::Packager::PPackage package );`

## client/include/Havoc/DBManager/DBManager.hpp
Depends on: `client/include/global.hpp`
Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/DBManger/DBManager.cc`, `client/src/Havoc/DBManger/Scripts.cc`, `client/src/Havoc/DBManger/Teamserver.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`
- `createNewDatabase` (function) `client/include/Havoc/DBManager/DBManager.hpp:17` `bool createNewDatabase();`
- `addTeamserverInfo` (function) `client/include/Havoc/DBManager/DBManager.hpp:27` `bool addTeamserverInfo( const Util::ConnectionInfo& );`
- `checkTeamserverExists` (function) `client/include/Havoc/DBManager/DBManager.hpp:28` `bool checkTeamserverExists( const QString& ProfileName );`
- `removeTeamserverInfo` (function) `client/include/Havoc/DBManager/DBManager.hpp:29` `bool removeTeamserverInfo( const QString& ProfileName );`
- `removeAllTeamservers` (function) `client/include/Havoc/DBManager/DBManager.hpp:30` `bool removeAllTeamservers();`
- `AddScript` (function) `client/include/Havoc/DBManager/DBManager.hpp:33` `bool AddScript( QString Path );`
- `RemoveScript` (function) `client/include/Havoc/DBManager/DBManager.hpp:34` `bool RemoveScript( QString Path );`
- `CheckScript` (function) `client/include/Havoc/DBManager/DBManager.hpp:35` `bool CheckScript( QString Path );`

## client/include/Havoc/Havoc.hpp
Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
Imported by: `client/src/Havoc/Connector.cc`, `client/src/Havoc/Havoc.cc`, `client/src/Havoc/Packager.cc`, `client/src/Main.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`
- `Init` (function) `client/include/Havoc/Havoc.hpp:25` `void Init( int argc, char** argv );`
- `Start` (function) `client/include/Havoc/Havoc.hpp:26` `void Start();`
- `Exit` (function) `client/include/Havoc/Havoc.hpp:28` `static void Exit();`

## client/include/Havoc/Packager.hpp
Depends on: `client/include/global.hpp`
Imported by: `client/include/Havoc/Connector.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`
- `DecodePackage` (function) `client/include/Havoc/Packager.hpp:106` `public: static Util::Packager::PPackage DecodePackage(const QString& Package );`
- `DispatchPackage` (function) `client/include/Havoc/Packager.hpp:109` `bool DispatchPackage( Util::Packager::PPackage Package );`
- `setTeamserver` (function) `client/include/Havoc/Packager.hpp:110` `void setTeamserver(QString Name);`
- `DispatchInitConnection` (function) `client/include/Havoc/Packager.hpp:113` `public: bool DispatchInitConnection( Util::Packager::PPackage Package );`
- `DispatchListener` (function) `client/include/Havoc/Packager.hpp:114` `bool DispatchListener( Util::Packager::PPackage Package );`
- `DispatchChat` (function) `client/include/Havoc/Packager.hpp:115` `bool DispatchChat( Util::Packager::PPackage Package );`
- `DispatchSession` (function) `client/include/Havoc/Packager.hpp:116` `bool DispatchSession( Util::Packager::PPackage Package );`
- `DispatchGate` (function) `client/include/Havoc/Packager.hpp:117` `bool DispatchGate( Util::Packager::PPackage Package );`
- `DispatchService` (function) `client/include/Havoc/Packager.hpp:118` `bool DispatchService( Util::Packager::PPackage Package );`
- `DispatchTeamserver` (function) `client/include/Havoc/Packager.hpp:119` `bool DispatchTeamserver( Util::Packager::PPackage Package );`

## client/include/Havoc/PythonApi/Event.h
Depends on: `client/include/global.hpp`
Imported by: `client/src/Havoc/PythonApi/Event.cc`, `client/src/Havoc/PythonApi/Havoc.cc`
- `EventClass_dealloc` (function) `client/include/Havoc/PythonApi/Event.h:16` `void EventClass_dealloc( PPyEvents self );`
- `EventClass_new` (function) `client/include/Havoc/PythonApi/Event.h:17` `PyObject* EventClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- `EventClass_init` (function) `client/include/Havoc/PythonApi/Event.h:18` `int EventClass_init( PPyEvents self, PyObject *args, PyObject *kwds );`
- `EventClass_OnNewSession` (function) `client/include/Havoc/PythonApi/Event.h:22` `PyObject* EventClass_OnNewSession( PPyEvents self, PyObject *args );`
- `EventClass_OnDemonOutput` (function) `client/include/Havoc/PythonApi/Event.h:23` `PyObject* EventClass_OnDemonOutput( PPyEvents self, PyObject *args );`

## client/include/Havoc/PythonApi/PyAgentClass.hpp
Depends on: `client/include/global.hpp`
Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`
- `AgentClass_dealloc` (function) `client/include/Havoc/PythonApi/PyAgentClass.hpp:27` `void AgentClass_dealloc( PPyAgentClass self );`
- `AgentClass_new` (function) `client/include/Havoc/PythonApi/PyAgentClass.hpp:28` `PyObject* AgentClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- `AgentClass_init` (function) `client/include/Havoc/PythonApi/PyAgentClass.hpp:29` `int AgentClass_init( PPyAgentClass self, PyObject *args, PyObject *kwds );`
- `AgentClass_ConsoleWrite` (function) `client/include/Havoc/PythonApi/PyAgentClass.hpp:30` `PyObject* AgentClass_ConsoleWrite( PPyAgentClass self, PyObject *args );`
- `AgentClass_Command` (function) `client/include/Havoc/PythonApi/PyAgentClass.hpp:31` `PyObject* AgentClass_Command( PPyAgentClass self, PyObject *args );`

## client/include/Havoc/PythonApi/PyDemonClass.h
Depends on: `client/include/global.hpp`
Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`
- `DemonClass_dealloc` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:36` `void DemonClass_dealloc( PPyDemonClass self );`
- `DemonClass_new` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:37` `PyObject* DemonClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- `DemonClass_init` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:38` `int DemonClass_init( PPyDemonClass self, PyObject *args, PyObject *kwds );`
- `DemonClass_ProcessCreate` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:45` `PyObject* DemonClass_ProcessCreate( PPyDemonClass self, PyObject *args );` -- Command
- `DemonClass_DllInject` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:46` `PyObject* DemonClass_DllInject( PPyDemonClass self, PyObject *args );`
- `DemonClass_DllSpawn` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:47` `PyObject* DemonClass_DllSpawn( PPyDemonClass self, PyObject *args );`
- `DemonClass_InlineExecute` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:48` `PyObject* DemonClass_InlineExecute( PPyDemonClass self, PyObject *args );`
- `DemonClass_InlineExecuteGetOutput` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:49` `PyObject* DemonClass_InlineExecuteGetOutput( PPyDemonClass self, PyObject *args );`
- `DemonClass_DotnetInlineExecute` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:50` `PyObject* DemonClass_DotnetInlineExecute( PPyDemonClass self, PyObject *args );`
- `DemonClass_RegisterCallback` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:51` `PyObject* DemonClass_RegisterCallback( PPyDemonClass self, PyObject *args );`
- `DemonClass_Command` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:52` `PyObject* DemonClass_Command( PPyDemonClass self, PyObject *args );`
- `DemonClass_CommandGetOutput` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:53` `PyObject* DemonClass_CommandGetOutput( PPyDemonClass self, PyObject *args );`
- `DemonClass_ShellcodeSpawn` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:54` `PyObject* DemonClass_ShellcodeSpawn( PPyDemonClass self, PyObject *args );`
- `DemonClass_ConsoleWrite` (function) `client/include/Havoc/PythonApi/PyDemonClass.h:57` `PyObject* DemonClass_ConsoleWrite( PPyDemonClass self, PyObject *args );` -- Utils

## client/include/Havoc/PythonApi/PythonApi.h
Depends on: `client/include/global.hpp`
Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/Havoc/PythonApi/PythonApi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`
- `Stdout_write` (function) `client/include/Havoc/PythonApi/PythonApi.h:76` `PyObject* Stdout_write(PyObject* self, PyObject* args);`
- `Stdout_flush` (function) `client/include/Havoc/PythonApi/PythonApi.h:77` `PyObject* Stdout_flush(PyObject* self, PyObject* args);`
- `set_stdout` (function) `client/include/Havoc/PythonApi/PythonApi.h:79` `void set_stdout(stdout_write_type write);`
- `reset_stdout` (function) `client/include/Havoc/PythonApi/PythonApi.h:80` `void reset_stdout();`

## client/include/Havoc/PythonApi/UI/PyDialogClass.hpp
Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`
- `DialogClass_dealloc` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:41` `void DialogClass_dealloc( PPyDialogClass self );`
- `DialogClass_new` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:42` `PyObject* DialogClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- `DialogClass_init` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:43` `int DialogClass_init( PPyDialogClass self, PyObject *args, PyObject *kwds );`
- `DialogClass_exec` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:47` `PyObject* DialogClass_exec( PPyDialogClass self, PyObject *args );`
- `DialogClass_close` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:48` `PyObject* DialogClass_close( PPyDialogClass self, PyObject *args );`
- `DialogClass_clear` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:49` `PyObject* DialogClass_clear( PPyDialogClass self, PyObject *args );`
- `DialogClass_addLabel` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:50` `PyObject* DialogClass_addLabel( PPyDialogClass self, PyObject *args );`
- `DialogClass_addButton` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:51` `PyObject* DialogClass_addButton( PPyDialogClass self, PyObject *args );`
- `DialogClass_addCheckbox` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:52` `PyObject* DialogClass_addCheckbox( PPyDialogClass self, PyObject *args );`
- `DialogClass_addCombobox` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:53` `PyObject* DialogClass_addCombobox( PPyDialogClass self, PyObject *args );`
- `DialogClass_addLineedit` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:54` `PyObject* DialogClass_addLineedit( PPyDialogClass self, PyObject *args );`
- `DialogClass_addCalendar` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:55` `PyObject* DialogClass_addCalendar( PPyDialogClass self, PyObject *args );`
- `DialogClass_replaceLabel` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:56` `PyObject* DialogClass_replaceLabel( PPyDialogClass self, PyObject *args );`
- `DialogClass_addImage` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:57` `PyObject* DialogClass_addImage( PPyDialogClass self, PyObject *args );`
- `DialogClass_addDial` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:58` `PyObject* DialogClass_addDial( PPyDialogClass self, PyObject *args );`
- `DialogClass_addSlider` (function) `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:59` `PyObject* DialogClass_addSlider( PPyDialogClass self, PyObject *args );`

## client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp
Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`
- `LoggerClass_dealloc` (function) `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:32` `void LoggerClass_dealloc( PPyLoggerClass self );`
- `LoggerClass_new` (function) `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:33` `PyObject* LoggerClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- `LoggerClass_init` (function) `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:34` `int LoggerClass_init( PPyLoggerClass self, PyObject *args, PyObject *kwds );`
- `LoggerClass_setBottomTab` (function) `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:38` `PyObject* LoggerClass_setBottomTab( PPyLoggerClass self, PyObject *args );`
- `LoggerClass_setSmallTab` (function) `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:39` `PyObject* LoggerClass_setSmallTab( PPyLoggerClass self, PyObject *args );`
- `LoggerClass_addText` (function) `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:40` `PyObject* LoggerClass_addText( PPyLoggerClass self, PyObject *args );`
- `LoggerClass_clear` (function) `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:41` `PyObject* LoggerClass_clear( PPyLoggerClass self, PyObject *args );`

## client/include/Havoc/PythonApi/UI/PyTreeClass.hpp
Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`
- `TreeClass_dealloc` (function) `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:48` `void TreeClass_dealloc( PPyTreeClass self );`
- `TreeClass_new` (function) `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:49` `PyObject* TreeClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- `TreeClass_init` (function) `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:50` `int TreeClass_init( PPyTreeClass self, PyObject *args, PyObject *kwds );`
- `TreeClass_setBottomTab` (function) `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:54` `PyObject* TreeClass_setBottomTab( PPyTreeClass self, PyObject *args );`
- `TreeClass_setSmallTab` (function) `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:55` `PyObject* TreeClass_setSmallTab( PPyTreeClass self, PyObject *args );`
- `TreeClass_addRow` (function) `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:56` `PyObject* TreeClass_addRow( PPyTreeClass self, PyObject *args );`
- `TreeClass_setItem` (function) `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:57` `PyObject* TreeClass_setItem( PPyTreeClass self, PyObject *args );`
- `TreeClass_setPanel` (function) `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:58` `PyObject* TreeClass_setPanel( PPyTreeClass self, PyObject *args );`

## client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp
Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`
- `WidgetClass_dealloc` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:41` `void WidgetClass_dealloc( PPyWidgetClass self );`
- `WidgetClass_new` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:42` `PyObject* WidgetClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- `WidgetClass_init` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:43` `int WidgetClass_init( PPyWidgetClass self, PyObject *args, PyObject *kwds );`
- `WidgetClass_addLabel` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:47` `PyObject* WidgetClass_addLabel( PPyWidgetClass self, PyObject *args );`
- `WidgetClass_setBottomTab` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:48` `PyObject* WidgetClass_setBottomTab( PPyWidgetClass self, PyObject *args );`
- `WidgetClass_setSmallTab` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:49` `PyObject* WidgetClass_setSmallTab( PPyWidgetClass self, PyObject *args );`
- `WidgetClass_addButton` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:50` `PyObject* WidgetClass_addButton( PPyWidgetClass self, PyObject *args );`
- `WidgetClass_addCheckbox` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:51` `PyObject* WidgetClass_addCheckbox( PPyWidgetClass self, PyObject *args );`
- `WidgetClass_addCombobox` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:52` `PyObject* WidgetClass_addCombobox( PPyWidgetClass self, PyObject *args );`
- `WidgetClass_addLineedit` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:53` `PyObject* WidgetClass_addLineedit( PPyWidgetClass self, PyObject *args );`
- `WidgetClass_addCalendar` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:54` `PyObject* WidgetClass_addCalendar( PPyWidgetClass self, PyObject *args );`
- `WidgetClass_replaceLabel` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:55` `PyObject* WidgetClass_replaceLabel( PPyWidgetClass self, PyObject *args );`
- `WidgetClass_clear` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:56` `PyObject* WidgetClass_clear( PPyWidgetClass self, PyObject *args );`
- `WidgetClass_addImage` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:57` `PyObject* WidgetClass_addImage( PPyWidgetClass self, PyObject *args );`
- `WidgetClass_addDial` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:58` `PyObject* WidgetClass_addDial( PPyWidgetClass self, PyObject *args );`
- `WidgetClass_addSlider` (function) `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:59` `PyObject* WidgetClass_addSlider( PPyWidgetClass self, PyObject *args );`

## client/include/UserInterface/Dialogs/About.hpp
Depends on: `client/include/global.hpp`
Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/About.cc`
- `setupUi` (function) `client/include/UserInterface/Dialogs/About.hpp:19` `void setupUi();`
- `onButtonClose` (function) `client/include/UserInterface/Dialogs/About.hpp:23` `public slots: void onButtonClose();`

## client/include/UserInterface/Dialogs/Connect.hpp
Depends on: `client/include/global.hpp`
Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Connect.cc`
- `setupUi` (function) `client/include/UserInterface/Dialogs/Connect.hpp:49` `void setupUi( QDialog* Form );`
- `passDB` (function) `client/include/UserInterface/Dialogs/Connect.hpp:51` `void passDB( HavocNamespace::HavocSpace::DBManager* db );`
- `onButton_Connect` (function) `client/include/UserInterface/Dialogs/Connect.hpp:54` `private slots: void onButton_Connect();`
- `onButton_NewProfile` (function) `client/include/UserInterface/Dialogs/Connect.hpp:55` `void onButton_NewProfile();`
- `itemSelected` (function) `client/include/UserInterface/Dialogs/Connect.hpp:57` `void itemSelected();`
- `handleContextMenu` (function) `client/include/UserInterface/Dialogs/Connect.hpp:58` `void handleContextMenu(const QPoint &pos);`
- `itemRemove` (function) `client/include/UserInterface/Dialogs/Connect.hpp:60` `void itemRemove();`
- `itemsClear` (function) `client/include/UserInterface/Dialogs/Connect.hpp:61` `void itemsClear();`

## client/include/UserInterface/Dialogs/Listener.hpp
Depends on: `client/include/global.hpp`
Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Listener.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`
- `onButton_Save` (function) `client/include/UserInterface/Dialogs/Listener.hpp:156` `protected slots: void onButton_Save();`
- `onProxyEnabled` (function) `client/include/UserInterface/Dialogs/Listener.hpp:158` `void onProxyEnabled();`

## client/include/UserInterface/HavocUI.hpp
Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`
- `MarkSessionAs` (function) `client/include/UserInterface/HavocUI.hpp:68` `public: void MarkSessionAs( HavocNamespace::Util::SessionItem session, QString Mark );`
- `UpdateSessionsHealth` (function) `client/include/UserInterface/HavocUI.hpp:69` `void UpdateSessionsHealth();`
- `setupUi` (function) `client/include/UserInterface/HavocUI.hpp:70` `void setupUi( QMainWindow *Havoc );`
- `retranslateUi` (function) `client/include/UserInterface/HavocUI.hpp:71` `void retranslateUi( QMainWindow *Havoc ) const;`
- `setDBManager` (function) `client/include/UserInterface/HavocUI.hpp:72` `void setDBManager( HavocSpace::DBManager* dbManager );`
- `NewTeamserverTab` (function) `client/include/UserInterface/HavocUI.hpp:73` `void NewTeamserverTab( HavocNamespace::Util::ConnectionInfo* );`
- `NewBottomTab` (function) `client/include/UserInterface/HavocUI.hpp:75` `void NewBottomTab( QWidget* TabWidget, const std::string& TitleName, const QString IconPath = "" ) const;`
- `NewSmallTab` (function) `client/include/UserInterface/HavocUI.hpp:76` `void NewSmallTab( QWidget* TabWidget, const std::string& TitleName ) const;`
- `ConnectEvents` (function) `client/include/UserInterface/HavocUI.hpp:77` `void ConnectEvents();`
- `PythonPrepare` (function) `client/include/UserInterface/HavocUI.hpp:78` `void PythonPrepare();`
- `OneSecondTick` (function) `client/include/UserInterface/HavocUI.hpp:81` `public slots: void OneSecondTick();`

## client/include/UserInterface/SmallWidgets/EventViewer.hpp
Depends on: `client/include/global.hpp`
Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`
- `setupUi` (function) `client/include/UserInterface/SmallWidgets/EventViewer.hpp:12` `void setupUi(QWidget* Widget);`
- `AppendText` (function) `client/include/UserInterface/SmallWidgets/EventViewer.hpp:13` `void AppendText(const QString& Time, const QString &text) const;`

## client/include/UserInterface/Widgets/Chat.hpp
Depends on: `client/include/global.hpp`
Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`
- `setupUi` (function) `client/include/UserInterface/Widgets/Chat.hpp:18` `void setupUi( QWidget* widget );`
- `AppendText` (function) `client/include/UserInterface/Widgets/Chat.hpp:19` `void AppendText( const QString& Time, const QString& text ) const;`
- `AddUserMessage` (function) `client/include/UserInterface/Widgets/Chat.hpp:21` `void AddUserMessage( const QString Time, QString User, QString text ) const;`
- `AppendFromInput` (function) `client/include/UserInterface/Widgets/Chat.hpp:24` `public slots: void AppendFromInput();`

## client/include/UserInterface/Widgets/DemonInteracted.h
Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`
- `AddCommand` (function) `client/include/UserInterface/Widgets/DemonInteracted.h:33` `void AddCommand( const QString& Command );`
- `handleKeyPress` (function) `client/include/UserInterface/Widgets/DemonInteracted.h:39` `private: bool handleKeyPress(QKeyEvent* eventKey);`
- `handleTabKey` (function) `client/include/UserInterface/Widgets/DemonInteracted.h:40` `void handleTabKey();`
- `handleUpKey` (function) `client/include/UserInterface/Widgets/DemonInteracted.h:41` `void handleUpKey();`
- `handleDownKey` (function) `client/include/UserInterface/Widgets/DemonInteracted.h:42` `void handleDownKey();`
- `setupUi` (function) `client/include/UserInterface/Widgets/DemonInteracted.h:46` `void setupUi( QWidget* Form );`
- `AppendText` (function) `client/include/UserInterface/Widgets/DemonInteracted.h:47` `void AppendText( const QString& text );`
- `AppendRaw` (function) `client/include/UserInterface/Widgets/DemonInteracted.h:48` `void AppendRaw( const QString& text = "" );`
- `AppendNoNL` (function) `client/include/UserInterface/Widgets/DemonInteracted.h:49` `void AppendNoNL( const QString& test );`
- `AutoCompleteAdd` (function) `client/include/UserInterface/Widgets/DemonInteracted.h:54` `void AutoCompleteAdd( QString text );`
- `AutoCompleteAddList` (function) `client/include/UserInterface/Widgets/DemonInteracted.h:55` `void AutoCompleteAddList( QStringList list );`
- `AutoCompleteClear` (function) `client/include/UserInterface/Widgets/DemonInteracted.h:56` `void AutoCompleteClear();`
- `AppendFromInput` (function) `client/include/UserInterface/Widgets/DemonInteracted.h:59` `private slots: void AppendFromInput();`

## client/include/UserInterface/Widgets/FileBrowser.hpp
Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`
- `setupUi` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:82` `void setupUi( QWidget* FileBrowser );`
- `retranslateUi` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:83` `void retranslateUi( );`
- `AddData` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:85` `void AddData( QJsonDocument JsonData );`
- `TreeAddData` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:88` `private: void TreeAddData( FileData Data );`
- `TreeUpdate` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:89` `void TreeUpdate( );`
- `TreeClear` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:90` `void TreeClear( );`
- `TreeAddDisk` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:93` `void TreeAddDisk( QString Disk );`
- `TreeAddChildToParent` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:94` `void TreeAddChildToParent( QString ParentPath, FileBrowserTreeItem* DataItem );`
- `TableAddData` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:97` `void TableAddData( FileData Data );`
- `TableClear` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:98` `void TableClear();`
- `ChangePathAndSendRequest` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:100` `void ChangePathAndSendRequest( QString Path );`
- `onTableMenuMkdir` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:103` `private slots: void onTableMenuMkdir();`
- `onTableMenuReload` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:104` `void onTableMenuReload();`
- `onTableMenuRemove` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:105` `void onTableMenuRemove();`
- `onTableDoubleClick` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:107` `void onTableDoubleClick( int row, int column );`
- `onTableContextMenu` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:108` `void onTableContextMenu( const QPoint &pos );`
- `onTreeMenuListDrives` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:110` `void onTreeMenuListDrives();`
- `onTreeMenuMkdir` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:111` `void onTreeMenuMkdir();`
- `onTreeMenuReload` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:112` `void onTreeMenuReload();`
- `onTreeMenuRemove` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:113` `void onTreeMenuRemove();`
- `onTreeDoubleClick` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:115` `void onTreeDoubleClick();`
- `onTreeContextMenu` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:116` `void onTreeContextMenu( const QPoint &pos );`
- `onTableMenuDownload` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:118` `void onTableMenuDownload();`
- `onButtonUp` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:119` `void onButtonUp();`
- `onInputPath` (function) `client/include/UserInterface/Widgets/FileBrowser.hpp:120` `void onInputPath();`

## client/include/UserInterface/Widgets/ListenerTable.hpp
Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/ListenersTable.cc`
- `setupUi` (function) `client/include/UserInterface/Widgets/ListenerTable.hpp:25` `void setupUi( QWidget* widget );`
- `ButtonsInit` (function) `client/include/UserInterface/Widgets/ListenerTable.hpp:26` `void ButtonsInit();`
- `setDBManager` (function) `client/include/UserInterface/Widgets/ListenerTable.hpp:27` `void setDBManager( HavocSpace::DBManager* dbManager );`
- `ListenerAdd` (function) `client/include/UserInterface/Widgets/ListenerTable.hpp:31` `void ListenerAdd( Util::ListenerItem item ) const;`
- `ListenerEdit` (function) `client/include/UserInterface/Widgets/ListenerTable.hpp:32` `void ListenerEdit( Util::ListenerItem item ) const;`
- `ListenerRemove` (function) `client/include/UserInterface/Widgets/ListenerTable.hpp:33` `void ListenerRemove( QString ListenerName ) const;`
- `ListenerError` (function) `client/include/UserInterface/Widgets/ListenerTable.hpp:34` `void ListenerError( QString ListenerName, QString Error ) const;`

## client/include/UserInterface/Widgets/LootWidget.h
Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`
- `pixmap` (function) `client/include/UserInterface/Widgets/LootWidget.h:23` `const QPixmap* pixmap() const;`
- `setPixmap` (function) `client/include/UserInterface/Widgets/LootWidget.h:26` `public slots: void setPixmap(const QPixmap&);`
- `resizeEvent` (function) `client/include/UserInterface/Widgets/LootWidget.h:29` `protected: void resizeEvent(QResizeEvent *);`
- `keyReleaseEvent` (function) `client/include/UserInterface/Widgets/LootWidget.h:30` `void keyReleaseEvent( QKeyEvent* event );`
- `wheelEvent` (function) `client/include/UserInterface/Widgets/LootWidget.h:32` `void wheelEvent(QWheelEvent *ev);`
- `resizeImage` (function) `client/include/UserInterface/Widgets/LootWidget.h:35` `public slots: void resizeImage();`
- `Reload` (function) `client/include/UserInterface/Widgets/LootWidget.h:94` `void Reload();`
- `AddSessionSection` (function) `client/include/UserInterface/Widgets/LootWidget.h:96` `void AddSessionSection( const QString& DemonID );`
- `AddScreenshot` (function) `client/include/UserInterface/Widgets/LootWidget.h:97` `void AddScreenshot( const QString& DemonID, const QString& Name, const QString& Date, const QByteArray& Data );`
- `AddDownload` (function) `client/include/UserInterface/Widgets/LootWidget.h:98` `void AddDownload( const QString &DemonID, const QString &Name, const QString& Size, const QString &Date, const...`
- `AddText` (function) `client/include/UserInterface/Widgets/LootWidget.h:99` `void AddText( const QString& DemonID, const QString& Name, const QByteArray& Data );`
- `ScreenshotTableAdd` (function) `client/include/UserInterface/Widgets/LootWidget.h:101` `void ScreenshotTableAdd( const QString& Name, const QString& Date );`
- `DownloadTableAdd` (function) `client/include/UserInterface/Widgets/LootWidget.h:102` `void DownloadTableAdd( const QString& Name, const QString& Size, const QString& Date );`
- `onAgentChange` (function) `client/include/UserInterface/Widgets/LootWidget.h:105` `private Q_SLOTS: void onAgentChange( const QString& text );`
- `onShowChange` (function) `client/include/UserInterface/Widgets/LootWidget.h:106` `void onShowChange( const QString& text );`
- `onScreenshotTableClick` (function) `client/include/UserInterface/Widgets/LootWidget.h:107` `void onScreenshotTableClick( const QModelIndex &index );`
- `onDownloadTableClick` (function) `client/include/UserInterface/Widgets/LootWidget.h:108` `void onDownloadTableClick( const QModelIndex &index );`
- `onScreenshotTableCtx` (function) `client/include/UserInterface/Widgets/LootWidget.h:109` `void onScreenshotTableCtx( const QPoint &pos );`

## client/include/UserInterface/Widgets/ProcessList.hpp
Depends on: `client/include/global.hpp`
Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`
- `setupUi` (function) `client/include/UserInterface/Widgets/ProcessList.hpp:43` `void setupUi(QWidget* Widget);`
- `UpdateProcessListJson` (function) `client/include/UserInterface/Widgets/ProcessList.hpp:44` `void UpdateProcessListJson(QJsonDocument ProcessListData);`
- `NewTableProcess` (function) `client/include/UserInterface/Widgets/ProcessList.hpp:45` `void NewTableProcess(std::map<QString, QString> ProcessInfo);`
- `NewTreeProcess` (function) `client/include/UserInterface/Widgets/ProcessList.hpp:46` `void NewTreeProcess(std::map<QString, QString> ProcessInfo);`
- `onButton_Refresh` (function) `client/include/UserInterface/Widgets/ProcessList.hpp:49` `private slots: void onButton_Refresh() const;`
- `onTableChange` (function) `client/include/UserInterface/Widgets/ProcessList.hpp:51` `void onTableChange();`
- `onTreeChange` (function) `client/include/UserInterface/Widgets/ProcessList.hpp:52` `void onTreeChange();`
- `handleTableListMenuContext` (function) `client/include/UserInterface/Widgets/ProcessList.hpp:54` `void handleTableListMenuContext(const QPoint &pos);`
- `handleTreeListMenuContext` (function) `client/include/UserInterface/Widgets/ProcessList.hpp:55` `void handleTreeListMenuContext(const QPoint &pos);`
- `onActionCopyPID` (function) `client/include/UserInterface/Widgets/ProcessList.hpp:57` `void onActionCopyPID();`
- `onActionSetParentProcess` (function) `client/include/UserInterface/Widgets/ProcessList.hpp:58` `void onActionSetParentProcess();`

## client/include/UserInterface/Widgets/PythonScript.hpp
Depends on: `client/include/global.hpp`
Imported by: `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`
- `setupUi` (function) `client/include/UserInterface/Widgets/PythonScript.hpp:24` `void setupUi(QWidget *WindowWidget);`
- `RunCode` (function) `client/include/UserInterface/Widgets/PythonScript.hpp:25` `void RunCode(QString code);`
- `AppendOutput` (function) `client/include/UserInterface/Widgets/PythonScript.hpp:26` `void AppendOutput( QString output );`
- `AppendFromInput` (function) `client/include/UserInterface/Widgets/PythonScript.hpp:29` `private slots: void AppendFromInput();`

## client/include/UserInterface/Widgets/ScriptManager.h
Depends on: `client/include/global.hpp`
Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`
- `SetupUi` (function) `client/include/UserInterface/Widgets/ScriptManager.h:20` `void SetupUi( QWidget *Form );`
- `RetranslateUi` (function) `client/include/UserInterface/Widgets/ScriptManager.h:21` `void RetranslateUi( void );`
- `AddScript` (function) `client/include/UserInterface/Widgets/ScriptManager.h:23` `static bool AddScript( QString Path );`
- `AddScriptTable` (function) `client/include/UserInterface/Widgets/ScriptManager.h:24` `void AddScriptTable( QString Path );`
- `b_LoadScript` (function) `client/include/UserInterface/Widgets/ScriptManager.h:27` `private slots: void b_LoadScript();`
- `menu_ScriptMenu` (function) `client/include/UserInterface/Widgets/ScriptManager.h:28` `void menu_ScriptMenu( const QPoint &pos ) const;`
- `ReloadScript` (function) `client/include/UserInterface/Widgets/ScriptManager.h:30` `void ReloadScript() const;`
- `RemoveScript` (function) `client/include/UserInterface/Widgets/ScriptManager.h:31` `void RemoveScript() const;`

## client/include/UserInterface/Widgets/SessionGraph.hpp
Depends on: `client/include/global.hpp`
Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`
- `appendChild` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:45` `void appendChild( Node* child );`
- `removeChild` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:46` `void removeChild( Node* child );`
- `addEdge` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:48` `void addEdge( Edge* edge );`
- `edges` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:49` `QVector<Edge*> edges() const;`
- `type` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:52` `int type() const override`
- `calculateForces` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:54` `void calculateForces();`
- `advancePosition` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:55` `bool advancePosition();`
- `itemMoved` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:93` `void itemMoved();`
- `GraphNodeAdd` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:95` `Node* GraphNodeAdd( HavocNamespace::Util::SessionItem Session );`
- `GraphNodeRemove` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:96` `void GraphNodeRemove( HavocNamespace::Util::SessionItem Session );`
- `GraphNodeGet` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:97` `Node* GraphNodeGet( QString AgentID );`
- `GraphPivotNodeAdd` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:99` `void GraphPivotNodeAdd( QString AgentID, HavocNamespace::Util::SessionItem Session );`
- `GraphPivotNodeDisconnect` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:100` `void GraphPivotNodeDisconnect( QString AgentID );`
- `GraphPivotNodeReconnect` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:101` `void GraphPivotNodeReconnect( QString ParentAgentID, QString ChildAgentID );`
- `shuffle` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:104` `public slots: void shuffle();`
- `zoomIn` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:105` `void zoomIn();`
- `zoomOut` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:106` `void zoomOut();`
- `scaleView` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:118` `void scaleView( qreal scaleFactor );`
- `initNode` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:126` `void initNode(Node* v);`
- `layout` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:127` `void layout(Node* T);`
- `firstWalk` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:128` `void firstWalk(Node* v);`
- `apportion` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:129` `void apportion(Node* v, Node*& defaultAncestor);`
- `moveSubtree` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:130` `void moveSubtree(Node* wm, Node* wp, double shift);`
- `nextLeft` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:131` `Node* nextLeft(Node* v);`
- `nextRight` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:132` `Node* nextRight(Node* v);`
- `ancestor` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:133` `Node* ancestor(Node* vim, Node* v, Node*& defaultAncestor);`
- `executeShifts` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:134` `void executeShifts(Node* v);`
- `secondWalk` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:135` `void secondWalk(Node* v, double m, double depth);`
- `sourceNode` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:146` `Node* sourceNode() const;`
- `destNode` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:147` `Node* destNode() const;`
- `adjust` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:149` `void adjust();`
- `Color` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:150` `void Color( QColor color );`
- `type` (function) `client/include/UserInterface/Widgets/SessionGraph.hpp:153` `int type() const override`

## client/include/UserInterface/Widgets/SessionTable.hpp
Depends on: `client/include/global.hpp`
Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`
- `setupUi` (function) `client/include/UserInterface/Widgets/SessionTable.hpp:28` `void setupUi( QWidget* widget, QString TeamserverName );`
- `NewSessionItem` (function) `client/include/UserInterface/Widgets/SessionTable.hpp:29` `void NewSessionItem( Util::SessionItem item ) const;`
- `ChangeSessionValue` (function) `client/include/UserInterface/Widgets/SessionTable.hpp:30` `void ChangeSessionValue( QString DemonID, int key, QString value );`
- `updateRow` (function) `client/include/UserInterface/Widgets/SessionTable.hpp:31` `void updateRow();`

## client/include/UserInterface/Widgets/Store.hpp
Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/Store.cc`
- `setupUi` (function) `client/include/UserInterface/Widgets/Store.hpp:62` `void setupUi( QWidget* Store );`
- `displayData` (function) `client/include/UserInterface/Widgets/Store.hpp:63` `void displayData( int position );`
- `installScript` (function) `client/include/UserInterface/Widgets/Store.hpp:64` `void installScript( int position );`
- `AddScript` (function) `client/include/UserInterface/Widgets/Store.hpp:65` `bool AddScript( QString Path );`
- `retranslateUi` (function) `client/include/UserInterface/Widgets/Store.hpp:66` `void retranslateUi( );`

## client/include/UserInterface/Widgets/Teamserver.hpp
Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/Teamserver.cc`
- `setupUi` (function) `client/include/UserInterface/Widgets/Teamserver.hpp:23` `void setupUi( QWidget* Teamserver );`
- `retranslateUi` (function) `client/include/UserInterface/Widgets/Teamserver.hpp:24` `void retranslateUi( );`
- `AddLoggerText` (function) `client/include/UserInterface/Widgets/Teamserver.hpp:26` `void AddLoggerText( const QString& Text ) const;`

## client/include/UserInterface/Widgets/TeamserverTabSession.h
Depends on: `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/Teamserver.hpp`, `client/include/global.hpp`
Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/Store.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`
- `setupUi` (function) `client/include/UserInterface/Widgets/TeamserverTabSession.h:52` `void setupUi( QWidget* Page, QString TeamserverName );`
- `NewBottomTab` (function) `client/include/UserInterface/Widgets/TeamserverTabSession.h:53` `void NewBottomTab( QWidget* TabWidget, const std::string& TitleName, QString IconPath = "" ) const;`
- `NewWidgetTab` (function) `client/include/UserInterface/Widgets/TeamserverTabSession.h:54` `void NewWidgetTab( QWidget* TabWidget, const std::string& TitleName ) const;`
- `handleDemonContextMenu` (function) `client/include/UserInterface/Widgets/TeamserverTabSession.h:57` `protected slots: void handleDemonContextMenu( const QPoint& pos );`
- `removeTabSmall` (function) `client/include/UserInterface/Widgets/TeamserverTabSession.h:58` `void removeTabSmall( int ) const;`


Next: [API_p2.md](API_p2.md)
