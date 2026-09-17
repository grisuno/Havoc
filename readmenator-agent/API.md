# API

## client/include/Havoc/CmdLine.hpp

### cast (function) `public:
            static Target cast(const Source &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:47`
- Imported by: `client/src/Havoc/Havoc.cc`

### cast (function) `public:
            static Target cast(const Source &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:60`
- Imported by: `client/src/Havoc/Havoc.cc`

### cast (function) `public:
            static std::string cast(const Source &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:68`
- Imported by: `client/src/Havoc/Havoc.cc`

### cast (function) `public:
            static Target cast(const std::string &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:78`
- Imported by: `client/src/Havoc/Havoc.cc`

### lexical_cast (function) `Target lexical_cast(const Source &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:98`
- Imported by: `client/src/Havoc/Havoc.cc`

### demangle (function) `static inline std::string demangle(const std::string &name)`
- Defined: `client/include/Havoc/CmdLine.hpp:103`
- Imported by: `client/src/Havoc/Havoc.cc`

### readable_typename (function) `template <class T>
        std::string readable_typename()`
- Defined: `client/include/Havoc/CmdLine.hpp:113`
- Imported by: `client/src/Havoc/Havoc.cc`

### default_value (function) `template <class T>
        std::string default_value(T def)`
- Defined: `client/include/Havoc/CmdLine.hpp:119`
- Imported by: `client/src/Havoc/Havoc.cc`

### cmdline_error (function) `public:
        cmdline_error(const std::string &msg): msg(msg)`
- Defined: `client/include/Havoc/CmdLine.hpp:136`
- Imported by: `client/src/Havoc/Havoc.cc`

### what (function) `const char *what() const throw()`
- Defined: `client/include/Havoc/CmdLine.hpp:138`
- Imported by: `client/src/Havoc/Havoc.cc`

### operator (function) `T operator()(const std::string &str)`
- Defined: `client/include/Havoc/CmdLine.hpp:145`
- Imported by: `client/src/Havoc/Havoc.cc`

### range_reader (function) `range_reader(const T &low, const T &high): low(low), high(high)`
- Defined: `client/include/Havoc/CmdLine.hpp:152`
- Imported by: `client/src/Havoc/Havoc.cc`

### operator (function) `T operator()(const std::string &s) const`
- Defined: `client/include/Havoc/CmdLine.hpp:153`
- Imported by: `client/src/Havoc/Havoc.cc`

### range (function) `template <class T>
    range_reader<T> range(const T &low, const T &high)`
- Defined: `client/include/Havoc/CmdLine.hpp:163`
- Imported by: `client/src/Havoc/Havoc.cc`

### operator (function) `T operator()(const std::string &s)`
- Defined: `client/include/Havoc/CmdLine.hpp:170`
- Imported by: `client/src/Havoc/Havoc.cc`

### add (function) `void add(const T &v)`
- Defined: `client/include/Havoc/CmdLine.hpp:176`
- Imported by: `client/src/Havoc/Havoc.cc`

### oneof (function) `template <class T>
    oneof_reader<T> oneof(T a1)`
- Defined: `client/include/Havoc/CmdLine.hpp:182`
- Imported by: `client/src/Havoc/Havoc.cc`

### oneof (function) `template <class T>
    oneof_reader<T> oneof(T a1, T a2)`
- Defined: `client/include/Havoc/CmdLine.hpp:190`
- Imported by: `client/src/Havoc/Havoc.cc`

### oneof (function) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3)`
- Defined: `client/include/Havoc/CmdLine.hpp:199`
- Imported by: `client/src/Havoc/Havoc.cc`

### oneof (function) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4)`
- Defined: `client/include/Havoc/CmdLine.hpp:209`
- Imported by: `client/src/Havoc/Havoc.cc`

### oneof (function) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5)`
- Defined: `client/include/Havoc/CmdLine.hpp:220`
- Imported by: `client/src/Havoc/Havoc.cc`

### oneof (function) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6)`
- Defined: `client/include/Havoc/CmdLine.hpp:232`
- Imported by: `client/src/Havoc/Havoc.cc`

### oneof (function) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7)`
- Defined: `client/include/Havoc/CmdLine.hpp:245`
- Imported by: `client/src/Havoc/Havoc.cc`

### oneof (function) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8)`
- Defined: `client/include/Havoc/CmdLine.hpp:259`
- Imported by: `client/src/Havoc/Havoc.cc`

### oneof (function) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9)`
- Defined: `client/include/Havoc/CmdLine.hpp:274`
- Imported by: `client/src/Havoc/Havoc.cc`

### oneof (function) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9...`
- Defined: `client/include/Havoc/CmdLine.hpp:290`
- Imported by: `client/src/Havoc/Havoc.cc`

### parser (function) `public:
        parser()`
- Defined: `client/include/Havoc/CmdLine.hpp:310`
- Imported by: `client/src/Havoc/Havoc.cc`

### add (function) `void add(const std::string &name,
                 char short_name=0,
                 const std:...`
- Defined: `client/include/Havoc/CmdLine.hpp:318`
- Imported by: `client/src/Havoc/Havoc.cc`

### add (function) `template <class T>
        void add(const std::string &name,
                 char short_name=0,
...`
- Defined: `client/include/Havoc/CmdLine.hpp:327`
- Imported by: `client/src/Havoc/Havoc.cc`

### add (function) `void add(const std::string &name,
                 char short_name=0,
                 const std:...`
- Defined: `client/include/Havoc/CmdLine.hpp:336`
- Imported by: `client/src/Havoc/Havoc.cc`

### footer (function) `void footer(const std::string &f)`
- Defined: `client/include/Havoc/CmdLine.hpp:347`
- Imported by: `client/src/Havoc/Havoc.cc`

### set_program_name (function) `void set_program_name(const std::string &name)`
- Defined: `client/include/Havoc/CmdLine.hpp:351`
- Imported by: `client/src/Havoc/Havoc.cc`

### exist (function) `bool exist(const std::string &name) const`
- Defined: `client/include/Havoc/CmdLine.hpp:355`
- Imported by: `client/src/Havoc/Havoc.cc`

### get (function) `template <class T>
        const T &get(const std::string &name) const`
- Defined: `client/include/Havoc/CmdLine.hpp:361`
- Imported by: `client/src/Havoc/Havoc.cc`

### rest (function) `const std::vector<std::string> &rest() const`
- Defined: `client/include/Havoc/CmdLine.hpp:368`
- Imported by: `client/src/Havoc/Havoc.cc`

### parse (function) `bool parse(const std::string &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:372`
- Imported by: `client/src/Havoc/Havoc.cc`

### parse (function) `bool parse(const std::vector<std::string> &args)`
- Defined: `client/include/Havoc/CmdLine.hpp:414`
- Imported by: `client/src/Havoc/Havoc.cc`

### parse (function) `bool parse(int argc, const char * const argv[])`
- Defined: `client/include/Havoc/CmdLine.hpp:424`
- Imported by: `client/src/Havoc/Havoc.cc`

### parse_check (function) `void parse_check(const std::string &arg)`
- Defined: `client/include/Havoc/CmdLine.hpp:525`
- Imported by: `client/src/Havoc/Havoc.cc`

### parse_check (function) `void parse_check(const std::vector<std::string> &args)`
- Defined: `client/include/Havoc/CmdLine.hpp:531`
- Imported by: `client/src/Havoc/Havoc.cc`

### parse_check (function) `void parse_check(int argc, char *argv[])`
- Defined: `client/include/Havoc/CmdLine.hpp:537`
- Imported by: `client/src/Havoc/Havoc.cc`

### error (function) `std::string error() const`
- Defined: `client/include/Havoc/CmdLine.hpp:543`
- Imported by: `client/src/Havoc/Havoc.cc`

### error_full (function) `std::string error_full() const`
- Defined: `client/include/Havoc/CmdLine.hpp:547`
- Imported by: `client/src/Havoc/Havoc.cc`

### usage (function) `std::string usage() const`
- Defined: `client/include/Havoc/CmdLine.hpp:554`
- Imported by: `client/src/Havoc/Havoc.cc`

### check (function) `private:

        void check(int argc, bool ok)`
- Defined: `client/include/Havoc/CmdLine.hpp:587`
- Imported by: `client/src/Havoc/Havoc.cc`

### set_option (function) `void set_option(const std::string &name)`
- Defined: `client/include/Havoc/CmdLine.hpp:599`
- Imported by: `client/src/Havoc/Havoc.cc`

### set_option (function) `void set_option(const std::string &name, const std::string &value)`
- Defined: `client/include/Havoc/CmdLine.hpp:610`
- Imported by: `client/src/Havoc/Havoc.cc`

### option_without_value (function) `public:
            option_without_value(const std::string &name,
                               ...`
- Defined: `client/include/Havoc/CmdLine.hpp:640`
- Imported by: `client/src/Havoc/Havoc.cc`

### has_value (function) `bool has_value() const`
- Defined: `client/include/Havoc/CmdLine.hpp:647`
- Imported by: `client/src/Havoc/Havoc.cc`

### set (function) `bool set()`
- Defined: `client/include/Havoc/CmdLine.hpp:649`
- Imported by: `client/src/Havoc/Havoc.cc`

### set (function) `bool set(const std::string &)`
- Defined: `client/include/Havoc/CmdLine.hpp:654`
- Imported by: `client/src/Havoc/Havoc.cc`

### has_set (function) `bool has_set() const`
- Defined: `client/include/Havoc/CmdLine.hpp:658`
- Imported by: `client/src/Havoc/Havoc.cc`

### valid (function) `bool valid() const`
- Defined: `client/include/Havoc/CmdLine.hpp:662`
- Imported by: `client/src/Havoc/Havoc.cc`

### must (function) `bool must() const`
- Defined: `client/include/Havoc/CmdLine.hpp:666`
- Imported by: `client/src/Havoc/Havoc.cc`

### name (function) `const std::string &name() const`
- Defined: `client/include/Havoc/CmdLine.hpp:670`
- Imported by: `client/src/Havoc/Havoc.cc`

### short_name (function) `char short_name() const`
- Defined: `client/include/Havoc/CmdLine.hpp:674`
- Imported by: `client/src/Havoc/Havoc.cc`

### description (function) `const std::string &description() const`
- Defined: `client/include/Havoc/CmdLine.hpp:678`
- Imported by: `client/src/Havoc/Havoc.cc`

### short_description (function) `std::string short_description() const`
- Defined: `client/include/Havoc/CmdLine.hpp:682`
- Imported by: `client/src/Havoc/Havoc.cc`

### option_with_value (function) `public:
            option_with_value(const std::string &name,
                              char...`
- Defined: `client/include/Havoc/CmdLine.hpp:696`
- Imported by: `client/src/Havoc/Havoc.cc`

### get (function) `const T &get() const`
- Defined: `client/include/Havoc/CmdLine.hpp:707`
- Imported by: `client/src/Havoc/Havoc.cc`

### has_value (function) `bool has_value() const`
- Defined: `client/include/Havoc/CmdLine.hpp:711`
- Imported by: `client/src/Havoc/Havoc.cc`

### set (function) `bool set()`
- Defined: `client/include/Havoc/CmdLine.hpp:713`
- Imported by: `client/src/Havoc/Havoc.cc`

### set (function) `bool set(const std::string &value)`
- Defined: `client/include/Havoc/CmdLine.hpp:717`
- Imported by: `client/src/Havoc/Havoc.cc`

### has_set (function) `bool has_set() const`
- Defined: `client/include/Havoc/CmdLine.hpp:728`
- Imported by: `client/src/Havoc/Havoc.cc`

### valid (function) `bool valid() const`
- Defined: `client/include/Havoc/CmdLine.hpp:732`
- Imported by: `client/src/Havoc/Havoc.cc`

### must (function) `bool must() const`
- Defined: `client/include/Havoc/CmdLine.hpp:737`
- Imported by: `client/src/Havoc/Havoc.cc`

### name (function) `const std::string &name() const`
- Defined: `client/include/Havoc/CmdLine.hpp:741`
- Imported by: `client/src/Havoc/Havoc.cc`

### short_name (function) `char short_name() const`
- Defined: `client/include/Havoc/CmdLine.hpp:745`
- Imported by: `client/src/Havoc/Havoc.cc`

### description (function) `const std::string &description() const`
- Defined: `client/include/Havoc/CmdLine.hpp:749`
- Imported by: `client/src/Havoc/Havoc.cc`

### short_description (function) `std::string short_description() const`
- Defined: `client/include/Havoc/CmdLine.hpp:753`
- Imported by: `client/src/Havoc/Havoc.cc`

### full_description (function) `protected:
            std::string full_description(const std::string &desc)`
- Defined: `client/include/Havoc/CmdLine.hpp:758`
- Imported by: `client/src/Havoc/Havoc.cc`

### option_with_value_with_reader (function) `public:
            option_with_value_with_reader(const std::string &name,
                      ...`
- Defined: `client/include/Havoc/CmdLine.hpp:780`
- Imported by: `client/src/Havoc/Havoc.cc`

### read (function) `private:
            T read(const std::string &s)`
- Defined: `client/include/Havoc/CmdLine.hpp:790`
- Imported by: `client/src/Havoc/Havoc.cc`

### argv (function) `std::vector<const char*> argv(argc);`
- Defined: `client/include/Havoc/CmdLine.hpp:416`
- Imported by: `client/src/Havoc/Havoc.cc`

## client/include/Havoc/Connector.hpp

### Disconnect (function) `bool Disconnect();`
- Defined: `client/include/Havoc/Connector.hpp:27`
- Depends on: `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Connector.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Havoc.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/global.cc`

### SendLogin (function) `void SendLogin();`
- Defined: `client/include/Havoc/Connector.hpp:29`
- Depends on: `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Connector.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Havoc.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/global.cc`

### SendPackage (function) `void SendPackage( Util::Packager::PPackage package );`
- Defined: `client/include/Havoc/Connector.hpp:30`
- Depends on: `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Connector.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Havoc.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/global.cc`

## client/include/Havoc/DBManager/DBManager.hpp

### createNewDatabase (function) `bool createNewDatabase();`
- Defined: `client/include/Havoc/DBManager/DBManager.hpp:17`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/DBManger/DBManager.cc`, `client/src/Havoc/DBManger/Scripts.cc`, `client/src/Havoc/DBManger/Teamserver.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### addTeamserverInfo (function) `bool addTeamserverInfo( const Util::ConnectionInfo& );`
- Defined: `client/include/Havoc/DBManager/DBManager.hpp:27`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/DBManger/DBManager.cc`, `client/src/Havoc/DBManger/Scripts.cc`, `client/src/Havoc/DBManger/Teamserver.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### checkTeamserverExists (function) `bool checkTeamserverExists( const QString& ProfileName );`
- Defined: `client/include/Havoc/DBManager/DBManager.hpp:28`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/DBManger/DBManager.cc`, `client/src/Havoc/DBManger/Scripts.cc`, `client/src/Havoc/DBManger/Teamserver.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### removeTeamserverInfo (function) `bool removeTeamserverInfo( const QString& ProfileName );`
- Defined: `client/include/Havoc/DBManager/DBManager.hpp:29`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/DBManger/DBManager.cc`, `client/src/Havoc/DBManger/Scripts.cc`, `client/src/Havoc/DBManger/Teamserver.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### removeAllTeamservers (function) `bool removeAllTeamservers();`
- Defined: `client/include/Havoc/DBManager/DBManager.hpp:30`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/DBManger/DBManager.cc`, `client/src/Havoc/DBManger/Scripts.cc`, `client/src/Havoc/DBManger/Teamserver.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### AddScript (function) `bool AddScript( QString Path );`
- Defined: `client/include/Havoc/DBManager/DBManager.hpp:33`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/DBManger/DBManager.cc`, `client/src/Havoc/DBManger/Scripts.cc`, `client/src/Havoc/DBManger/Teamserver.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### RemoveScript (function) `bool RemoveScript( QString Path );`
- Defined: `client/include/Havoc/DBManager/DBManager.hpp:34`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/DBManger/DBManager.cc`, `client/src/Havoc/DBManger/Scripts.cc`, `client/src/Havoc/DBManger/Teamserver.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### CheckScript (function) `bool CheckScript( QString Path );`
- Defined: `client/include/Havoc/DBManager/DBManager.hpp:35`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/DBManger/DBManager.cc`, `client/src/Havoc/DBManger/Scripts.cc`, `client/src/Havoc/DBManger/Teamserver.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

## client/include/Havoc/Havoc.hpp

### Init (function) `void Init( int argc, char** argv );`
- Defined: `client/include/Havoc/Havoc.hpp:25`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Connector.cc`, `client/src/Havoc/Havoc.cc`, `client/src/Havoc/Packager.cc`, `client/src/Main.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`

### Start (function) `void Start();`
- Defined: `client/include/Havoc/Havoc.hpp:26`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Connector.cc`, `client/src/Havoc/Havoc.cc`, `client/src/Havoc/Packager.cc`, `client/src/Main.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`

### Exit (function) `static void Exit();`
- Defined: `client/include/Havoc/Havoc.hpp:28`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Connector.cc`, `client/src/Havoc/Havoc.cc`, `client/src/Havoc/Packager.cc`, `client/src/Main.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`

## client/include/Havoc/Packager.hpp

### DecodePackage (function) `public: static Util::Packager::PPackage DecodePackage(const QString& Package );`
- Defined: `client/include/Havoc/Packager.hpp:106`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Connector.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### DispatchPackage (function) `bool DispatchPackage( Util::Packager::PPackage Package );`
- Defined: `client/include/Havoc/Packager.hpp:109`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Connector.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### setTeamserver (function) `void setTeamserver(QString Name);`
- Defined: `client/include/Havoc/Packager.hpp:110`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Connector.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### DispatchInitConnection (function) `public: bool DispatchInitConnection( Util::Packager::PPackage Package );`
- Defined: `client/include/Havoc/Packager.hpp:113`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Connector.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### DispatchListener (function) `bool DispatchListener( Util::Packager::PPackage Package );`
- Defined: `client/include/Havoc/Packager.hpp:114`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Connector.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### DispatchChat (function) `bool DispatchChat( Util::Packager::PPackage Package );`
- Defined: `client/include/Havoc/Packager.hpp:115`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Connector.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### DispatchSession (function) `bool DispatchSession( Util::Packager::PPackage Package );`
- Defined: `client/include/Havoc/Packager.hpp:116`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Connector.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### DispatchGate (function) `bool DispatchGate( Util::Packager::PPackage Package );`
- Defined: `client/include/Havoc/Packager.hpp:117`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Connector.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### DispatchService (function) `bool DispatchService( Util::Packager::PPackage Package );`
- Defined: `client/include/Havoc/Packager.hpp:118`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Connector.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### DispatchTeamserver (function) `bool DispatchTeamserver( Util::Packager::PPackage Package );`
- Defined: `client/include/Havoc/Packager.hpp:119`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Connector.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/Havoc/PythonApi/Event.h

### EventClass_dealloc (function) `void EventClass_dealloc( PPyEvents self );`
- Defined: `client/include/Havoc/PythonApi/Event.h:16`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Event.cc`, `client/src/Havoc/PythonApi/Havoc.cc`

### EventClass_new (function) `PyObject* EventClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/Event.h:17`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Event.cc`, `client/src/Havoc/PythonApi/Havoc.cc`

### EventClass_init (function) `int EventClass_init( PPyEvents self, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/Event.h:18`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Event.cc`, `client/src/Havoc/PythonApi/Havoc.cc`

### EventClass_OnNewSession (function) `PyObject* EventClass_OnNewSession( PPyEvents self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/Event.h:22`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Event.cc`, `client/src/Havoc/PythonApi/Havoc.cc`

### EventClass_OnDemonOutput (function) `PyObject* EventClass_OnDemonOutput( PPyEvents self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/Event.h:23`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Event.cc`, `client/src/Havoc/PythonApi/Havoc.cc`

## client/include/Havoc/PythonApi/PyAgentClass.hpp

### AgentClass_dealloc (function) `void AgentClass_dealloc( PPyAgentClass self );`
- Defined: `client/include/Havoc/PythonApi/PyAgentClass.hpp:27`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`

### AgentClass_new (function) `PyObject* AgentClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/PyAgentClass.hpp:28`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`

### AgentClass_init (function) `int AgentClass_init( PPyAgentClass self, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/PyAgentClass.hpp:29`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`

### AgentClass_ConsoleWrite (function) `PyObject* AgentClass_ConsoleWrite( PPyAgentClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/PyAgentClass.hpp:30`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`

### AgentClass_Command (function) `PyObject* AgentClass_Command( PPyAgentClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/PyAgentClass.hpp:31`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`

## client/include/Havoc/PythonApi/PyDemonClass.h

### DemonClass_dealloc (function) `void DemonClass_dealloc( PPyDemonClass self );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:36`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

### DemonClass_new (function) `PyObject* DemonClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:37`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

### DemonClass_init (function) `int DemonClass_init( PPyDemonClass self, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:38`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

### DemonClass_ProcessCreate (function) `PyObject* DemonClass_ProcessCreate( PPyDemonClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:45`
- Doc: Command
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

### DemonClass_DllInject (function) `PyObject* DemonClass_DllInject( PPyDemonClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:46`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

### DemonClass_DllSpawn (function) `PyObject* DemonClass_DllSpawn( PPyDemonClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:47`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

### DemonClass_InlineExecute (function) `PyObject* DemonClass_InlineExecute( PPyDemonClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:48`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

### DemonClass_InlineExecuteGetOutput (function) `PyObject* DemonClass_InlineExecuteGetOutput( PPyDemonClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:49`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

### DemonClass_DotnetInlineExecute (function) `PyObject* DemonClass_DotnetInlineExecute( PPyDemonClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:50`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

### DemonClass_RegisterCallback (function) `PyObject* DemonClass_RegisterCallback( PPyDemonClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:51`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

### DemonClass_Command (function) `PyObject* DemonClass_Command( PPyDemonClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:52`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

### DemonClass_CommandGetOutput (function) `PyObject* DemonClass_CommandGetOutput( PPyDemonClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:53`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

### DemonClass_ShellcodeSpawn (function) `PyObject* DemonClass_ShellcodeSpawn( PPyDemonClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:54`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

### DemonClass_ConsoleWrite (function) `PyObject* DemonClass_ConsoleWrite( PPyDemonClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/PyDemonClass.h:57`
- Doc: Utils
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

## client/include/Havoc/PythonApi/PythonApi.h

### Stdout_write (function) `PyObject* Stdout_write(PyObject* self, PyObject* args);`
- Defined: `client/include/Havoc/PythonApi/PythonApi.h:76`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/Havoc/PythonApi/PythonApi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`

### Stdout_flush (function) `PyObject* Stdout_flush(PyObject* self, PyObject* args);`
- Defined: `client/include/Havoc/PythonApi/PythonApi.h:77`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/Havoc/PythonApi/PythonApi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`

### set_stdout (function) `void set_stdout(stdout_write_type write);`
- Defined: `client/include/Havoc/PythonApi/PythonApi.h:79`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/Havoc/PythonApi/PythonApi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`

### reset_stdout (function) `void reset_stdout();`
- Defined: `client/include/Havoc/PythonApi/PythonApi.h:80`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/Havoc/PythonApi/PythonApi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`

## client/include/Havoc/PythonApi/UI/PyDialogClass.hpp

### DialogClass_dealloc (function) `void DialogClass_dealloc( PPyDialogClass self );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:41`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_new (function) `PyObject* DialogClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:42`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_init (function) `int DialogClass_init( PPyDialogClass self, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:43`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_exec (function) `PyObject* DialogClass_exec( PPyDialogClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:47`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_close (function) `PyObject* DialogClass_close( PPyDialogClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:48`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_clear (function) `PyObject* DialogClass_clear( PPyDialogClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:49`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_addLabel (function) `PyObject* DialogClass_addLabel( PPyDialogClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:50`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_addButton (function) `PyObject* DialogClass_addButton( PPyDialogClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:51`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_addCheckbox (function) `PyObject* DialogClass_addCheckbox( PPyDialogClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:52`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_addCombobox (function) `PyObject* DialogClass_addCombobox( PPyDialogClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:53`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_addLineedit (function) `PyObject* DialogClass_addLineedit( PPyDialogClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:54`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_addCalendar (function) `PyObject* DialogClass_addCalendar( PPyDialogClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:55`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_replaceLabel (function) `PyObject* DialogClass_replaceLabel( PPyDialogClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:56`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_addImage (function) `PyObject* DialogClass_addImage( PPyDialogClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:57`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_addDial (function) `PyObject* DialogClass_addDial( PPyDialogClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:58`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

### DialogClass_addSlider (function) `PyObject* DialogClass_addSlider( PPyDialogClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:59`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

## client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp

### LoggerClass_dealloc (function) `void LoggerClass_dealloc( PPyLoggerClass self );`
- Defined: `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:32`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`

### LoggerClass_new (function) `PyObject* LoggerClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:33`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`

### LoggerClass_init (function) `int LoggerClass_init( PPyLoggerClass self, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:34`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`

### LoggerClass_setBottomTab (function) `PyObject* LoggerClass_setBottomTab( PPyLoggerClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:38`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`

### LoggerClass_setSmallTab (function) `PyObject* LoggerClass_setSmallTab( PPyLoggerClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:39`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`

### LoggerClass_addText (function) `PyObject* LoggerClass_addText( PPyLoggerClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:40`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`

### LoggerClass_clear (function) `PyObject* LoggerClass_clear( PPyLoggerClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp:41`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`

## client/include/Havoc/PythonApi/UI/PyTreeClass.hpp

### TreeClass_dealloc (function) `void TreeClass_dealloc( PPyTreeClass self );`
- Defined: `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:48`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`

### TreeClass_new (function) `PyObject* TreeClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:49`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`

### TreeClass_init (function) `int TreeClass_init( PPyTreeClass self, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:50`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`

### TreeClass_setBottomTab (function) `PyObject* TreeClass_setBottomTab( PPyTreeClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:54`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`

### TreeClass_setSmallTab (function) `PyObject* TreeClass_setSmallTab( PPyTreeClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:55`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`

### TreeClass_addRow (function) `PyObject* TreeClass_addRow( PPyTreeClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:56`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`

### TreeClass_setItem (function) `PyObject* TreeClass_setItem( PPyTreeClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:57`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`

### TreeClass_setPanel (function) `PyObject* TreeClass_setPanel( PPyTreeClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp:58`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`

## client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp

### WidgetClass_dealloc (function) `void WidgetClass_dealloc( PPyWidgetClass self );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:41`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_new (function) `PyObject* WidgetClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:42`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_init (function) `int WidgetClass_init( PPyWidgetClass self, PyObject *args, PyObject *kwds );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:43`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_addLabel (function) `PyObject* WidgetClass_addLabel( PPyWidgetClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:47`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_setBottomTab (function) `PyObject* WidgetClass_setBottomTab( PPyWidgetClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:48`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_setSmallTab (function) `PyObject* WidgetClass_setSmallTab( PPyWidgetClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:49`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_addButton (function) `PyObject* WidgetClass_addButton( PPyWidgetClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:50`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_addCheckbox (function) `PyObject* WidgetClass_addCheckbox( PPyWidgetClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:51`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_addCombobox (function) `PyObject* WidgetClass_addCombobox( PPyWidgetClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:52`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_addLineedit (function) `PyObject* WidgetClass_addLineedit( PPyWidgetClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:53`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_addCalendar (function) `PyObject* WidgetClass_addCalendar( PPyWidgetClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:54`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_replaceLabel (function) `PyObject* WidgetClass_replaceLabel( PPyWidgetClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:55`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_clear (function) `PyObject* WidgetClass_clear( PPyWidgetClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:56`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_addImage (function) `PyObject* WidgetClass_addImage( PPyWidgetClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:57`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_addDial (function) `PyObject* WidgetClass_addDial( PPyWidgetClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:58`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

### WidgetClass_addSlider (function) `PyObject* WidgetClass_addSlider( PPyWidgetClass self, PyObject *args );`
- Defined: `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp:59`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`

## client/include/UserInterface/Dialogs/About.hpp

### setupUi (function) `void setupUi();`
- Defined: `client/include/UserInterface/Dialogs/About.hpp:19`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/About.cc`

### onButtonClose (function) `public slots: void onButtonClose();`
- Defined: `client/include/UserInterface/Dialogs/About.hpp:23`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/About.cc`

## client/include/UserInterface/Dialogs/Connect.hpp

### setupUi (function) `void setupUi( QDialog* Form );`
- Defined: `client/include/UserInterface/Dialogs/Connect.hpp:49`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Connect.cc`

### passDB (function) `void passDB( HavocNamespace::HavocSpace::DBManager* db );`
- Defined: `client/include/UserInterface/Dialogs/Connect.hpp:51`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Connect.cc`

### onButton_Connect (function) `private slots: void onButton_Connect();`
- Defined: `client/include/UserInterface/Dialogs/Connect.hpp:54`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Connect.cc`

### onButton_NewProfile (function) `void onButton_NewProfile();`
- Defined: `client/include/UserInterface/Dialogs/Connect.hpp:55`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Connect.cc`

### itemSelected (function) `void itemSelected();`
- Defined: `client/include/UserInterface/Dialogs/Connect.hpp:57`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Connect.cc`

### handleContextMenu (function) `void handleContextMenu(const QPoint &pos);`
- Defined: `client/include/UserInterface/Dialogs/Connect.hpp:58`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Connect.cc`

### itemRemove (function) `void itemRemove();`
- Defined: `client/include/UserInterface/Dialogs/Connect.hpp:60`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Connect.cc`

### itemsClear (function) `void itemsClear();`
- Defined: `client/include/UserInterface/Dialogs/Connect.hpp:61`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Connect.cc`

## client/include/UserInterface/Dialogs/Listener.hpp

### onButton_Save (function) `protected slots: void onButton_Save();`
- Defined: `client/include/UserInterface/Dialogs/Listener.hpp:156`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Listener.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`

### onProxyEnabled (function) `void onProxyEnabled();`
- Defined: `client/include/UserInterface/Dialogs/Listener.hpp:158`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Listener.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`

## client/include/UserInterface/HavocUI.hpp

### MarkSessionAs (function) `public: void MarkSessionAs( HavocNamespace::Util::SessionItem session, QString Mark );`
- Defined: `client/include/UserInterface/HavocUI.hpp:68`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`

### UpdateSessionsHealth (function) `void UpdateSessionsHealth();`
- Defined: `client/include/UserInterface/HavocUI.hpp:69`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`

### setupUi (function) `void setupUi( QMainWindow *Havoc );`
- Defined: `client/include/UserInterface/HavocUI.hpp:70`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`

### retranslateUi (function) `void retranslateUi( QMainWindow *Havoc ) const;`
- Defined: `client/include/UserInterface/HavocUI.hpp:71`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`

### setDBManager (function) `void setDBManager( HavocSpace::DBManager* dbManager );`
- Defined: `client/include/UserInterface/HavocUI.hpp:72`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`

### NewTeamserverTab (function) `void NewTeamserverTab( HavocNamespace::Util::ConnectionInfo* );`
- Defined: `client/include/UserInterface/HavocUI.hpp:73`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`

### NewBottomTab (function) `void NewBottomTab( QWidget* TabWidget, const std::string& TitleName, const QString IconPath = "" ) const;`
- Defined: `client/include/UserInterface/HavocUI.hpp:75`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`

### NewSmallTab (function) `void NewSmallTab( QWidget* TabWidget, const std::string& TitleName ) const;`
- Defined: `client/include/UserInterface/HavocUI.hpp:76`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`

### ConnectEvents (function) `void ConnectEvents();`
- Defined: `client/include/UserInterface/HavocUI.hpp:77`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`

### PythonPrepare (function) `void PythonPrepare();`
- Defined: `client/include/UserInterface/HavocUI.hpp:78`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`

### OneSecondTick (function) `public slots: void OneSecondTick();`
- Defined: `client/include/UserInterface/HavocUI.hpp:81`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/global.hpp`
- Imported by: `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/UserInterface/HavocUi.cc`

## client/include/UserInterface/SmallWidgets/EventViewer.hpp

### setupUi (function) `void setupUi(QWidget* Widget);`
- Defined: `client/include/UserInterface/SmallWidgets/EventViewer.hpp:12`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AppendText (function) `void AppendText(const QString& Time, const QString &text) const;`
- Defined: `client/include/UserInterface/SmallWidgets/EventViewer.hpp:13`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/Chat.hpp

### setupUi (function) `void setupUi( QWidget* widget );`
- Defined: `client/include/UserInterface/Widgets/Chat.hpp:18`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AppendText (function) `void AppendText( const QString& Time, const QString& text ) const;`
- Defined: `client/include/UserInterface/Widgets/Chat.hpp:19`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AddUserMessage (function) `void AddUserMessage( const QString Time, QString User, QString text ) const;`
- Defined: `client/include/UserInterface/Widgets/Chat.hpp:21`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AppendFromInput (function) `public slots: void AppendFromInput();`
- Defined: `client/include/UserInterface/Widgets/Chat.hpp:24`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/DemonInteracted.h

### AddCommand (function) `void AddCommand( const QString& Command );`
- Defined: `client/include/UserInterface/Widgets/DemonInteracted.h:33`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### handleKeyPress (function) `private: bool handleKeyPress(QKeyEvent* eventKey);`
- Defined: `client/include/UserInterface/Widgets/DemonInteracted.h:39`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### handleTabKey (function) `void handleTabKey();`
- Defined: `client/include/UserInterface/Widgets/DemonInteracted.h:40`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### handleUpKey (function) `void handleUpKey();`
- Defined: `client/include/UserInterface/Widgets/DemonInteracted.h:41`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### handleDownKey (function) `void handleDownKey();`
- Defined: `client/include/UserInterface/Widgets/DemonInteracted.h:42`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### setupUi (function) `void setupUi( QWidget* Form );`
- Defined: `client/include/UserInterface/Widgets/DemonInteracted.h:46`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AppendText (function) `void AppendText( const QString& text );`
- Defined: `client/include/UserInterface/Widgets/DemonInteracted.h:47`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AppendRaw (function) `void AppendRaw( const QString& text = "" );`
- Defined: `client/include/UserInterface/Widgets/DemonInteracted.h:48`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AppendNoNL (function) `void AppendNoNL( const QString& test );`
- Defined: `client/include/UserInterface/Widgets/DemonInteracted.h:49`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AutoCompleteAdd (function) `void AutoCompleteAdd( QString text );`
- Defined: `client/include/UserInterface/Widgets/DemonInteracted.h:54`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AutoCompleteAddList (function) `void AutoCompleteAddList( QStringList list );`
- Defined: `client/include/UserInterface/Widgets/DemonInteracted.h:55`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AutoCompleteClear (function) `void AutoCompleteClear();`
- Defined: `client/include/UserInterface/Widgets/DemonInteracted.h:56`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AppendFromInput (function) `private slots: void AppendFromInput();`
- Defined: `client/include/UserInterface/Widgets/DemonInteracted.h:59`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/FileBrowser.hpp

### setupUi (function) `void setupUi( QWidget* FileBrowser );`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:82`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### retranslateUi (function) `void retranslateUi( );`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:83`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AddData (function) `void AddData( QJsonDocument JsonData );`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:85`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### TreeAddData (function) `private: void TreeAddData( FileData Data );`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:88`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### TreeUpdate (function) `void TreeUpdate( );`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:89`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### TreeClear (function) `void TreeClear( );`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:90`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### TreeAddDisk (function) `void TreeAddDisk( QString Disk );`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:93`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### TreeAddChildToParent (function) `void TreeAddChildToParent( QString ParentPath, FileBrowserTreeItem* DataItem );`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:94`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### TableAddData (function) `void TableAddData( FileData Data );`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:97`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### TableClear (function) `void TableClear();`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:98`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### ChangePathAndSendRequest (function) `void ChangePathAndSendRequest( QString Path );`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:100`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTableMenuMkdir (function) `private slots: void onTableMenuMkdir();`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:103`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTableMenuReload (function) `void onTableMenuReload();`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:104`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTableMenuRemove (function) `void onTableMenuRemove();`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:105`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTableDoubleClick (function) `void onTableDoubleClick( int row, int column );`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:107`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTableContextMenu (function) `void onTableContextMenu( const QPoint &pos );`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:108`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTreeMenuListDrives (function) `void onTreeMenuListDrives();`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:110`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTreeMenuMkdir (function) `void onTreeMenuMkdir();`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:111`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTreeMenuReload (function) `void onTreeMenuReload();`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:112`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTreeMenuRemove (function) `void onTreeMenuRemove();`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:113`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTreeDoubleClick (function) `void onTreeDoubleClick();`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:115`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTreeContextMenu (function) `void onTreeContextMenu( const QPoint &pos );`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:116`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTableMenuDownload (function) `void onTableMenuDownload();`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:118`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onButtonUp (function) `void onButtonUp();`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:119`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onInputPath (function) `void onInputPath();`
- Defined: `client/include/UserInterface/Widgets/FileBrowser.hpp:120`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/ListenerTable.hpp

### setupUi (function) `void setupUi( QWidget* widget );`
- Defined: `client/include/UserInterface/Widgets/ListenerTable.hpp:25`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/ListenersTable.cc`

### ButtonsInit (function) `void ButtonsInit();`
- Defined: `client/include/UserInterface/Widgets/ListenerTable.hpp:26`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/ListenersTable.cc`

### setDBManager (function) `void setDBManager( HavocSpace::DBManager* dbManager );`
- Defined: `client/include/UserInterface/Widgets/ListenerTable.hpp:27`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/ListenersTable.cc`

### ListenerAdd (function) `void ListenerAdd( Util::ListenerItem item ) const;`
- Defined: `client/include/UserInterface/Widgets/ListenerTable.hpp:31`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/ListenersTable.cc`

### ListenerEdit (function) `void ListenerEdit( Util::ListenerItem item ) const;`
- Defined: `client/include/UserInterface/Widgets/ListenerTable.hpp:32`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/ListenersTable.cc`

### ListenerRemove (function) `void ListenerRemove( QString ListenerName ) const;`
- Defined: `client/include/UserInterface/Widgets/ListenerTable.hpp:33`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/ListenersTable.cc`

### ListenerError (function) `void ListenerError( QString ListenerName, QString Error ) const;`
- Defined: `client/include/UserInterface/Widgets/ListenerTable.hpp:34`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/ListenersTable.cc`

## client/include/UserInterface/Widgets/LootWidget.h

### pixmap (function) `const QPixmap* pixmap() const;`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:23`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### setPixmap (function) `public slots: void setPixmap(const QPixmap&);`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:26`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### resizeEvent (function) `protected: void resizeEvent(QResizeEvent *);`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:29`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### keyReleaseEvent (function) `void keyReleaseEvent( QKeyEvent* event );`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:30`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### wheelEvent (function) `void wheelEvent(QWheelEvent *ev);`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:32`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### resizeImage (function) `public slots: void resizeImage();`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:35`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### Reload (function) `void Reload();`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:94`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AddSessionSection (function) `void AddSessionSection( const QString& DemonID );`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:96`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AddScreenshot (function) `void AddScreenshot( const QString& DemonID, const QString& Name, const QString& Date, const QByteArray& Data );`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:97`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AddDownload (function) `void AddDownload( const QString &DemonID, const QString &Name, const QString& Size, const QString &Date, const QByteArray &Data );`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:98`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### AddText (function) `void AddText( const QString& DemonID, const QString& Name, const QByteArray& Data );`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:99`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### ScreenshotTableAdd (function) `void ScreenshotTableAdd( const QString& Name, const QString& Date );`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:101`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### DownloadTableAdd (function) `void DownloadTableAdd( const QString& Name, const QString& Size, const QString& Date );`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:102`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onAgentChange (function) `private Q_SLOTS: void onAgentChange( const QString& text );`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:105`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onShowChange (function) `void onShowChange( const QString& text );`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:106`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onScreenshotTableClick (function) `void onScreenshotTableClick( const QModelIndex &index );`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:107`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onDownloadTableClick (function) `void onDownloadTableClick( const QModelIndex &index );`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:108`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onScreenshotTableCtx (function) `void onScreenshotTableCtx( const QPoint &pos );`
- Defined: `client/include/UserInterface/Widgets/LootWidget.h:109`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/ProcessList.hpp

### setupUi (function) `void setupUi(QWidget* Widget);`
- Defined: `client/include/UserInterface/Widgets/ProcessList.hpp:43`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### UpdateProcessListJson (function) `void UpdateProcessListJson(QJsonDocument ProcessListData);`
- Defined: `client/include/UserInterface/Widgets/ProcessList.hpp:44`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### NewTableProcess (function) `void NewTableProcess(std::map<QString, QString> ProcessInfo);`
- Defined: `client/include/UserInterface/Widgets/ProcessList.hpp:45`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### NewTreeProcess (function) `void NewTreeProcess(std::map<QString, QString> ProcessInfo);`
- Defined: `client/include/UserInterface/Widgets/ProcessList.hpp:46`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onButton_Refresh (function) `private slots: void onButton_Refresh() const;`
- Defined: `client/include/UserInterface/Widgets/ProcessList.hpp:49`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTableChange (function) `void onTableChange();`
- Defined: `client/include/UserInterface/Widgets/ProcessList.hpp:51`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onTreeChange (function) `void onTreeChange();`
- Defined: `client/include/UserInterface/Widgets/ProcessList.hpp:52`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### handleTableListMenuContext (function) `void handleTableListMenuContext(const QPoint &pos);`
- Defined: `client/include/UserInterface/Widgets/ProcessList.hpp:54`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### handleTreeListMenuContext (function) `void handleTreeListMenuContext(const QPoint &pos);`
- Defined: `client/include/UserInterface/Widgets/ProcessList.hpp:55`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onActionCopyPID (function) `void onActionCopyPID();`
- Defined: `client/include/UserInterface/Widgets/ProcessList.hpp:57`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### onActionSetParentProcess (function) `void onActionSetParentProcess();`
- Defined: `client/include/UserInterface/Widgets/ProcessList.hpp:58`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/PythonScript.hpp

### setupUi (function) `void setupUi(QWidget *WindowWidget);`
- Defined: `client/include/UserInterface/Widgets/PythonScript.hpp:24`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`

### RunCode (function) `void RunCode(QString code);`
- Defined: `client/include/UserInterface/Widgets/PythonScript.hpp:25`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`

### AppendOutput (function) `void AppendOutput( QString output );`
- Defined: `client/include/UserInterface/Widgets/PythonScript.hpp:26`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`

### AppendFromInput (function) `private slots: void AppendFromInput();`
- Defined: `client/include/UserInterface/Widgets/PythonScript.hpp:29`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`

## client/include/UserInterface/Widgets/ScriptManager.h

### SetupUi (function) `void SetupUi( QWidget *Form );`
- Defined: `client/include/UserInterface/Widgets/ScriptManager.h:20`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### RetranslateUi (function) `void RetranslateUi( void );`
- Defined: `client/include/UserInterface/Widgets/ScriptManager.h:21`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### AddScript (function) `static bool AddScript( QString Path );`
- Defined: `client/include/UserInterface/Widgets/ScriptManager.h:23`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### AddScriptTable (function) `void AddScriptTable( QString Path );`
- Defined: `client/include/UserInterface/Widgets/ScriptManager.h:24`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### b_LoadScript (function) `private slots: void b_LoadScript();`
- Defined: `client/include/UserInterface/Widgets/ScriptManager.h:27`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### menu_ScriptMenu (function) `void menu_ScriptMenu( const QPoint &pos ) const;`
- Defined: `client/include/UserInterface/Widgets/ScriptManager.h:28`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### ReloadScript (function) `void ReloadScript() const;`
- Defined: `client/include/UserInterface/Widgets/ScriptManager.h:30`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

### RemoveScript (function) `void RemoveScript() const;`
- Defined: `client/include/UserInterface/Widgets/ScriptManager.h:31`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

## client/include/UserInterface/Widgets/SessionGraph.hpp

### type (function) `int type() const override`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:52`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### type (function) `int type() const override`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:153`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### appendChild (function) `void appendChild( Node* child );`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:45`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### removeChild (function) `void removeChild( Node* child );`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:46`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### addEdge (function) `void addEdge( Edge* edge );`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:48`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### edges (function) `QVector<Edge*> edges() const;`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:49`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### calculateForces (function) `void calculateForces();`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:54`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### advancePosition (function) `bool advancePosition();`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:55`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### itemMoved (function) `void itemMoved();`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:93`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### GraphNodeAdd (function) `Node* GraphNodeAdd( HavocNamespace::Util::SessionItem Session );`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:95`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### GraphNodeRemove (function) `void GraphNodeRemove( HavocNamespace::Util::SessionItem Session );`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:96`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### GraphNodeGet (function) `Node* GraphNodeGet( QString AgentID );`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:97`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### GraphPivotNodeAdd (function) `void GraphPivotNodeAdd( QString AgentID, HavocNamespace::Util::SessionItem Session );`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:99`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### GraphPivotNodeDisconnect (function) `void GraphPivotNodeDisconnect( QString AgentID );`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:100`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### GraphPivotNodeReconnect (function) `void GraphPivotNodeReconnect( QString ParentAgentID, QString ChildAgentID );`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:101`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### shuffle (function) `public slots: void shuffle();`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:104`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### zoomIn (function) `void zoomIn();`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:105`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### zoomOut (function) `void zoomOut();`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:106`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### scaleView (function) `void scaleView( qreal scaleFactor );`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:118`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### initNode (function) `void initNode(Node* v);`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:126`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### layout (function) `void layout(Node* T);`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:127`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### firstWalk (function) `void firstWalk(Node* v);`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:128`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### apportion (function) `void apportion(Node* v, Node*& defaultAncestor);`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:129`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### moveSubtree (function) `void moveSubtree(Node* wm, Node* wp, double shift);`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:130`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### nextLeft (function) `Node* nextLeft(Node* v);`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:131`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### nextRight (function) `Node* nextRight(Node* v);`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:132`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### ancestor (function) `Node* ancestor(Node* vim, Node* v, Node*& defaultAncestor);`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:133`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### executeShifts (function) `void executeShifts(Node* v);`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:134`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### secondWalk (function) `void secondWalk(Node* v, double m, double depth);`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:135`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### sourceNode (function) `Node* sourceNode() const;`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:146`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### destNode (function) `Node* destNode() const;`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:147`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### adjust (function) `void adjust();`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:149`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### Color (function) `void Color( QColor color );`
- Defined: `client/include/UserInterface/Widgets/SessionGraph.hpp:150`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/SessionTable.hpp

### setupUi (function) `void setupUi( QWidget* widget, QString TeamserverName );`
- Defined: `client/include/UserInterface/Widgets/SessionTable.hpp:28`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### NewSessionItem (function) `void NewSessionItem( Util::SessionItem item ) const;`
- Defined: `client/include/UserInterface/Widgets/SessionTable.hpp:29`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### ChangeSessionValue (function) `void ChangeSessionValue( QString DemonID, int key, QString value );`
- Defined: `client/include/UserInterface/Widgets/SessionTable.hpp:30`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### updateRow (function) `void updateRow();`
- Defined: `client/include/UserInterface/Widgets/SessionTable.hpp:31`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/Store.hpp

### setupUi (function) `void setupUi( QWidget* Store );`
- Defined: `client/include/UserInterface/Widgets/Store.hpp:62`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/Store.cc`

### displayData (function) `void displayData( int position );`
- Defined: `client/include/UserInterface/Widgets/Store.hpp:63`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/Store.cc`

### installScript (function) `void installScript( int position );`
- Defined: `client/include/UserInterface/Widgets/Store.hpp:64`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/Store.cc`

### AddScript (function) `bool AddScript( QString Path );`
- Defined: `client/include/UserInterface/Widgets/Store.hpp:65`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/Store.cc`

### retranslateUi (function) `void retranslateUi( );`
- Defined: `client/include/UserInterface/Widgets/Store.hpp:66`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/Store.cc`

## client/include/UserInterface/Widgets/Teamserver.hpp

### setupUi (function) `void setupUi( QWidget* Teamserver );`
- Defined: `client/include/UserInterface/Widgets/Teamserver.hpp:23`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/Teamserver.cc`

### retranslateUi (function) `void retranslateUi( );`
- Defined: `client/include/UserInterface/Widgets/Teamserver.hpp:24`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/Teamserver.cc`

### AddLoggerText (function) `void AddLoggerText( const QString& Text ) const;`
- Defined: `client/include/UserInterface/Widgets/Teamserver.hpp:26`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/Teamserver.cc`

## client/include/UserInterface/Widgets/TeamserverTabSession.h

### setupUi (function) `void setupUi( QWidget* Page, QString TeamserverName );`
- Defined: `client/include/UserInterface/Widgets/TeamserverTabSession.h:52`
- Depends on: `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/Teamserver.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/Store.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### NewBottomTab (function) `void NewBottomTab( QWidget* TabWidget, const std::string& TitleName, QString IconPath = "" ) const;`
- Defined: `client/include/UserInterface/Widgets/TeamserverTabSession.h:53`
- Depends on: `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/Teamserver.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/Store.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### NewWidgetTab (function) `void NewWidgetTab( QWidget* TabWidget, const std::string& TitleName ) const;`
- Defined: `client/include/UserInterface/Widgets/TeamserverTabSession.h:54`
- Depends on: `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/Teamserver.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/Store.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### handleDemonContextMenu (function) `protected slots: void handleDemonContextMenu( const QPoint& pos );`
- Defined: `client/include/UserInterface/Widgets/TeamserverTabSession.h:57`
- Depends on: `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/Teamserver.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/Store.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

### removeTabSmall (function) `void removeTabSmall( int ) const;`
- Defined: `client/include/UserInterface/Widgets/TeamserverTabSession.h:58`
- Depends on: `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/Teamserver.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/Store.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/Util/ColorText.h

### SetDraculaDark (function) `static void SetDraculaDark();`
- Defined: `client/include/Util/ColorText.h:33`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### SetDraculaLight (function) `static void SetDraculaLight();`
- Defined: `client/include/Util/ColorText.h:34`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### Color (function) `static QString Color(const QString& color, const QString& text);`
- Defined: `client/include/Util/ColorText.h:36`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### Background (function) `static QString Background(const QString&);`
- Defined: `client/include/Util/ColorText.h:37`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### Foreground (function) `static QString Foreground(const QString&);`
- Defined: `client/include/Util/ColorText.h:38`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### Comment (function) `static QString Comment(const QString&);`
- Defined: `client/include/Util/ColorText.h:39`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### Cyan (function) `static QString Cyan(const QString&);`
- Defined: `client/include/Util/ColorText.h:40`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### Green (function) `static QString Green(const QString&);`
- Defined: `client/include/Util/ColorText.h:41`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### Orange (function) `static QString Orange(const QString&);`
- Defined: `client/include/Util/ColorText.h:42`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### Pink (function) `static QString Pink(const QString&);`
- Defined: `client/include/Util/ColorText.h:43`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### Purple (function) `static QString Purple(const QString&);`
- Defined: `client/include/Util/ColorText.h:44`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### Red (function) `static QString Red(const QString&);`
- Defined: `client/include/Util/ColorText.h:45`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### Yellow (function) `static QString Yellow(const QString&);`
- Defined: `client/include/Util/ColorText.h:46`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### Underline (function) `static QString Underline(const QString& text);`
- Defined: `client/include/Util/ColorText.h:48`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### UnderlineBackground (function) `static QString UnderlineBackground(const QString& text);`
- Defined: `client/include/Util/ColorText.h:49`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### UnderlineForeground (function) `static QString UnderlineForeground(const QString& text);`
- Defined: `client/include/Util/ColorText.h:50`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### UnderlineComment (function) `static QString UnderlineComment(const QString& text);`
- Defined: `client/include/Util/ColorText.h:51`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### UnderlineCyan (function) `static QString UnderlineCyan(const QString& text);`
- Defined: `client/include/Util/ColorText.h:52`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### UnderlineGreen (function) `static QString UnderlineGreen(const QString& text);`
- Defined: `client/include/Util/ColorText.h:53`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### UnderlineOrange (function) `static QString UnderlineOrange(const QString& text);`
- Defined: `client/include/Util/ColorText.h:54`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### UnderlinePink (function) `static QString UnderlinePink(const QString& text);`
- Defined: `client/include/Util/ColorText.h:55`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### UnderlinePurple (function) `static QString UnderlinePurple(const QString& text);`
- Defined: `client/include/Util/ColorText.h:56`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### UnderlineRed (function) `static QString UnderlineRed(const QString& text);`
- Defined: `client/include/Util/ColorText.h:57`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### UnderlineYellow (function) `static QString UnderlineYellow(const QString& text);`
- Defined: `client/include/Util/ColorText.h:58`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

### Bold (function) `static QString Bold(const QString& text);`
- Defined: `client/include/Util/ColorText.h:60`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`

## client/include/global.hpp

### Export (function) `void Export();`
- Defined: `client/include/global.hpp:245`
- Depends on: `client/include/External.h`, `client/include/Havoc/Service.hpp`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`
- Imported by: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base64.h`, `client/include/Util/ColorText.h`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Main.cc`, `client/src/UserInterface/Dialogs/About.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Dialogs/Listener.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/Store.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/Base64.cpp`, `client/src/global.cc`

## client/src/Havoc/Connector.cc

### Connector (function) `Connector::Connector( Util::ConnectionInfo* ConnectionInfo )`
- Defined: `client/src/Havoc/Connector.cc:7`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

### connect (function) `QObject::connect( Socket, &QWebSocket::binaryMessageReceived, this, [&]( const QByteArray& Message )`
- Defined: `client/src/Havoc/Connector.cc:19`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

### connect (function) `QObject::connect( Socket, &QWebSocket::connected, this, [&]()`
- Defined: `client/src/Havoc/Connector.cc:36`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

### connect (function) `QObject::connect( Socket, &QWebSocket::disconnected, this, [&]()`
- Defined: `client/src/Havoc/Connector.cc:44`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

### Disconnect (function) `bool Connector::Disconnect()`
- Defined: `client/src/Havoc/Connector.cc:56`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

### SendLogin (function) `void Connector::SendLogin()`
- Defined: `client/src/Havoc/Connector.cc:72`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

### SendPackage (function) `void Connector::SendPackage( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Connector.cc:93`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

## client/src/Havoc/DBManger/DBManager.cc

### DBManager (function) `DBManager::DBManager( const QString& FilePath, int OpenFlag )`
- Defined: `client/src/Havoc/DBManger/DBManager.cc:9`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

### createNewDatabase (function) `bool DBManager::createNewDatabase()`
- Defined: `client/src/Havoc/DBManger/DBManager.cc:32`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

## client/src/Havoc/DBManger/Scripts.cc

### AddScript (function) `bool HavocNamespace::HavocSpace::DBManager::AddScript( QString Path )`
- Defined: `client/src/Havoc/DBManger/Scripts.cc:3`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

### RemoveScript (function) `bool HavocNamespace::HavocSpace::DBManager::RemoveScript( QString Path )`
- Defined: `client/src/Havoc/DBManger/Scripts.cc:20`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

### CheckScript (function) `bool HavocNamespace::HavocSpace::DBManager::CheckScript( QString Path )`
- Defined: `client/src/Havoc/DBManger/Scripts.cc:41`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

### GetScripts (function) `vector<QString> HavocNamespace::HavocSpace::DBManager::GetScripts()`
- Defined: `client/src/Havoc/DBManger/Scripts.cc:63`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

## client/src/Havoc/DBManger/Teamserver.cc

### addTeamserverInfo (function) `bool HavocSpace::DBManager::addTeamserverInfo( const Util::ConnectionInfo& connection )`
- Defined: `client/src/Havoc/DBManger/Teamserver.cc:6`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

### checkTeamserverExists (function) `bool HavocSpace::DBManager::checkTeamserverExists( const QString& ProfileName )`
- Defined: `client/src/Havoc/DBManger/Teamserver.cc:31`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

### removeTeamserverInfo (function) `bool HavocSpace::DBManager::removeTeamserverInfo( const QString& ProfileName )`
- Defined: `client/src/Havoc/DBManger/Teamserver.cc:55`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

### listTeamservers (function) `vector<Util::ConnectionInfo> HavocSpace::DBManager::listTeamservers()`
- Defined: `client/src/Havoc/DBManger/Teamserver.cc:75`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

### removeAllTeamservers (function) `bool HavocSpace::DBManager::removeAllTeamservers()`
- Defined: `client/src/Havoc/DBManger/Teamserver.cc:104`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`

## client/src/Havoc/Demon/CommandOutput.cc

### MessageOutput (function) `void DispatchOutput::MessageOutput( QString JsonString, const QString& Date = "" ) const`
- Defined: `client/src/Havoc/Demon/CommandOutput.cc:15`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`

## client/src/Havoc/Demon/ConsoleInput.cc

### is_number (function) `static bool is_number( const std::string& s )`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:28`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### compareQString (function) `bool compareQString(const QString &a, const QString &b)`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:183`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### DemonCommands (function) `DemonCommands::DemonCommands( )`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:188`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Checkin( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "task" ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:611`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Job( TaskID, "list", "0" ) )
            }
            else if ( InputCommands[ 1 ]...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:654`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### CONSOLE_ERROR (function) `CONSOLE_ERROR( "Not enough arguments" )
                }
            }
            else if ( Inp...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:667`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### CONSOLE_ERROR (function) `CONSOLE_ERROR( "Not enough arguments" )
                }
            }
            else if ( Inp...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:681`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### CONSOLE_ERROR (function) `CONSOLE_ERROR( "Sub command not found: " + InputCommands[ 1 ] )
            }
        }
        e...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:700`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.DllInject( TaskID, Pid, Path, Args ) )
            }
            else if ( InputCom...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1138`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.DllSpawn( TaskID, Path, Args.toLocal8Bit() ) )

            }
        }
        els...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1166`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### CONSOLE_ERROR (function) `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1225`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### CONSOLE_ERROR (function) `CONSOLE_ERROR( "Incorrect process arch specified: " + TargetArch )
                    }

       ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1260`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Token( TaskID, "clear", "" ) )
            }
            else if ( InputCommands[ 1...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1452`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Token( TaskID, "getuid", "" ) )
            }
            else if ( InputCommands[ ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1459`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Socket( TaskID, "rportfwd list", "" ) )
            }
            else if ( InputCo...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1607`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Socket( TaskID, "rportfwd remove", InputCommands[ 2 ] ) )
            }
           ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1620`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Socket( TaskID, "rportfwd clear", "" ) )
            }

        }
        else if (...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1627`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Socket( TaskID, "socks add", Port ) )
            }
            else if ( InputComm...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1654`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Socket( TaskID, "socks list", "" ) )
            }
            else if ( InputComma...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1661`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Socket( TaskID, "socks kill", InputCommands[ 2 ] ) )
            }
            else...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1674`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Socket( TaskID, "socks clear", "" ) )
            }

        }
        else if ( In...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1681`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Transfer( TaskID, "list", "" ) )
            }
            else if ( InputCommands[...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1698`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Transfer( TaskID, "stop", InputCommands[ 2 ] ) )
            }
            else if ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1711`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Transfer( TaskID, "resume", InputCommands[ 2 ] ) )
            }
            else i...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1724`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Transfer( TaskID, "remove", InputCommands[ 2 ] ) )
            }
        }
        ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1737`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### CONSOLE_ERROR (function) `CONSOLE_ERROR( "Not enough arguments" )
            }
        }
        else if ( InputCommands[ ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:1830`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Screenshot( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "net...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:2037`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### CONSOLE_ERROR (function) `CONSOLE_ERROR( "No sub command specified" )
            }
        }
        else if ( InputComman...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:2131`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Pivot( TaskID, Command, Param ) )
            }
        }
        else if ( InputCo...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:2184`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Luid( TaskID ) )
        }
        else if ( InputCommands[ 0 ].compare( "klist" ) ...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:2192`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### SEND (function) `SEND( Execute.Exit( TaskID, "thread" ) )
            }
            else if ( InputCommands[ 1 ].c...`
- Defined: `client/src/Havoc/Demon/ConsoleInput.cc:2324`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/Havoc/Havoc.cc

### Havoc (function) `HavocSpace::Havoc::Havoc( QMainWindow* w )`
- Defined: `client/src/Havoc/Havoc.cc:7`
- Depends on: `client/include/Havoc/CmdLine.hpp`, `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

### Init (function) `void HavocSpace::Havoc::Init( int argc, char** argv )`
- Defined: `client/src/Havoc/Havoc.cc:22`
- Depends on: `client/include/Havoc/CmdLine.hpp`, `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

### singleShot (function) `QTimer::singleShot( 10, [&]()`
- Defined: `client/src/Havoc/Havoc.cc:70`
- Depends on: `client/include/Havoc/CmdLine.hpp`, `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

### Start (function) `void HavocSpace::Havoc::Start()`
- Defined: `client/src/Havoc/Havoc.cc:85`
- Depends on: `client/include/Havoc/CmdLine.hpp`, `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

### Exit (function) `void HavocSpace::Havoc::Exit()`
- Defined: `client/src/Havoc/Havoc.cc:93`
- Depends on: `client/include/Havoc/CmdLine.hpp`, `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`

## client/src/Havoc/Packager.cc

### DecodePackage (function) `Util::Packager::PPackage Packager::DecodePackage( const QString& Package )`
- Defined: `client/src/Havoc/Packager.cc:63`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### foreach (function) `foreach( const QString& key, BodyObject[ "Info" ].toObject().keys() )`
- Defined: `client/src/Havoc/Packager.cc:90`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### EncodePackage (function) `QJsonDocument Packager::EncodePackage( Util::Packager::Package Package )`
- Defined: `client/src/Havoc/Packager.cc:106`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### DispatchInitConnection (function) `bool Packager::DispatchInitConnection( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Packager.cc:166`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### DispatchListener (function) `bool Packager::DispatchListener( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Packager.cc:220`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### DispatchChat (function) `bool Packager::DispatchChat( Util::Packager::PPackage Package)`
- Defined: `client/src/Havoc/Packager.cc:483`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### DispatchGate (function) `bool Packager::DispatchGate( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Packager.cc:532`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### DispatchSession (function) `bool Packager::DispatchSession( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Packager.cc:581`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### DispatchService (function) `bool Packager::DispatchService( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Packager.cc:865`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### DispatchTeamserver (function) `bool Packager::DispatchTeamserver( Util::Packager::PPackage Package )`
- Defined: `client/src/Havoc/Packager.cc:961`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### setTeamserver (function) `void Packager::setTeamserver( QString Name )`
- Defined: `client/src/Havoc/Packager.cc:987`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/Havoc/PythonApi/Event.cc

### EventClass_dealloc (function) `void EventClass_dealloc( PPyEvents self )`
- Defined: `client/src/Havoc/PythonApi/Event.cc:70`
- Depends on: `client/include/Havoc/PythonApi/Event.h`

### EventClass_new (function) `PyObject* EventClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/Event.cc:77`
- Depends on: `client/include/Havoc/PythonApi/Event.h`

### EventClass_init (function) `int EventClass_init( PPyEvents self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/Event.cc:86`
- Depends on: `client/include/Havoc/PythonApi/Event.h`

### EventClass_OnNewSession (function) `PyObject* EventClass_OnNewSession( PPyEvents self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Event.cc:96`
- Depends on: `client/include/Havoc/PythonApi/Event.h`

### EventClass_OnDemonOutput (function) `PyObject* EventClass_OnDemonOutput( PPyEvents self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Event.cc:112`
- Depends on: `client/include/Havoc/PythonApi/Event.h`

## client/src/Havoc/PythonApi/Havoc.cc

### PyInit_Havoc (function) `PyMODINIT_FUNC PythonAPI::Havoc::PyInit_Havoc( void )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:45`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/global.hpp`

### Load (function) `PyObject* PythonAPI::Havoc::Core::Load( PyObject *self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:67`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/global.hpp`

### GetListeners (function) `PyObject* PythonAPI::Havoc::Core::GetListeners( PyObject *self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:89`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/global.hpp`

### GetAgents (function) `PyObject* PythonAPI::Havoc::Core::GetAgents( PyObject *self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:105`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/global.hpp`

### GetDemons (function) `PyObject* PythonAPI::Havoc::Core::GetDemons( PyObject *self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:123`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/global.hpp`

### GeneratePayload (function) `PyObject* PythonAPI::Havoc::Core::GeneratePayload( PyObject *self, PyObject *args, PyObject* kwar...`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:139`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/global.hpp`

### RegisterCommand (function) `PyObject* PythonAPI::Havoc::Core::RegisterCommand( PyObject *self, PyObject *args, PyObject* kwar...`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:188`
- Doc: RegisterCommand( PyFunction: func, Module: str, Command: str, Description: str, Behavior: int, Usage: str, Example: str 
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/global.hpp`

### RegisterModule (function) `PyObject* PythonAPI::Havoc::Core::RegisterModule( PyObject *self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:265`
- Doc: RegisterModule( Name: str, Description: str, Behavior: str, Usage: str, Example: str, Options: str )
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/global.hpp`

### RegisterCallback (function) `PyObject* PythonAPI::Havoc::Core::RegisterCallback( PyObject *self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/Havoc.cc:321`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/global.hpp`

## client/src/Havoc/PythonApi/HavocUi.cc

### CreateTab (function) `PyObject* PythonAPI::HavocUI::Core::CreateTab(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:46`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

### connect (function) `QMainWindow::connect( tupleCallback, &QAction::triggered, HavocX::HavocUserInterface->HavocWindow...`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:76`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

### MessageBox (function) `PyObject* PythonAPI::HavocUI::Core::MessageBox(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:84`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

### ErrorMessage (function) `PyObject* PythonAPI::HavocUI::Core::ErrorMessage(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:108`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

### QuestionDialog (function) `PyObject* PythonAPI::HavocUI::Core::QuestionDialog(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:123`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

### InputDialog (function) `PyObject* PythonAPI::HavocUI::Core::InputDialog(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:141`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

### OpenFileDialog (function) `PyObject* PythonAPI::HavocUI::Core::OpenFileDialog(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:154`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

### SaveFileDialog (function) `PyObject* PythonAPI::HavocUI::Core::SaveFileDialog(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:167`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

### ColorDialog (function) `PyObject* PythonAPI::HavocUI::Core::ColorDialog(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:180`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

### ProgressDialog (function) `PyObject* PythonAPI::HavocUI::Core::ProgressDialog(PyObject *self, PyObject *args)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:192`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

### connect (function) `QMainWindow::connect( timer, &QTimer::timeout, HavocX::HavocUserInterface->HavocWindow, [callable...`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:212`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

### connect (function) `QMainWindow::connect( cancelButton, &QPushButton::clicked, HavocX::HavocUserInterface->HavocWindo...`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:231`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

### PyInit_HavocUI (function) `PyMODINIT_FUNC PythonAPI::HavocUI::PyInit_HavocUI(void)`
- Defined: `client/src/Havoc/PythonApi/HavocUi.cc:241`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

## client/src/Havoc/PythonApi/PyAgentClass.cc

### AgentClass_dealloc (function) `void AgentClass_dealloc( PPyAgentClass self )`
- Defined: `client/src/Havoc/PythonApi/PyAgentClass.cc:69`
- Depends on: `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### AgentClass_new (function) `PyObject* AgentClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/PyAgentClass.cc:76`
- Depends on: `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### AgentClass_init (function) `int AgentClass_init( PPyAgentClass self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/PyAgentClass.cc:85`
- Depends on: `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### AgentClass_ConsoleWrite (function) `PyObject* AgentClass_ConsoleWrite( PPyAgentClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyAgentClass.cc:112`
- Depends on: `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### AgentClass_Command (function) `PyObject* AgentClass_Command( PPyAgentClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyAgentClass.cc:149`
- Depends on: `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

## client/src/Havoc/PythonApi/PyDemonClass.cc

### DemonClass_dealloc (function) `void DemonClass_dealloc( PPyDemonClass self )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:100`
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### DemonClass_new (function) `PyObject* DemonClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:119`
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### DemonClass_init (function) `int DemonClass_init( PPyDemonClass self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:128`
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### DemonClass_Shell (function) `PyObject* DemonClass_Shell( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:179`
- Doc: Demon.shell( TaskID: str, ShellCommands: str )
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### DemonClass_InlineExecute (function) `PyObject* DemonClass_InlineExecute( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:200`
- Doc: Demon.InlineExecute( TaskID: str, EntryFunc: str, Path: str, Args: str, Threaded: bool )
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### DemonClass_InlineExecuteGetOutput (function) `PyObject* DemonClass_InlineExecuteGetOutput( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:250`
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### DemonClass_DotnetInlineExecute (function) `PyObject* DemonClass_DotnetInlineExecute( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:312`
- Doc: Demon.DotnetInlineExecute( TaskID: str, Path: str, Args: str )
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### DemonClass_Command (function) `PyObject* DemonClass_Command( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:333`
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### DemonClass_CommandGetOutput (function) `PyObject* DemonClass_CommandGetOutput( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:353`
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### DemonClass_ShellcodeSpawn (function) `PyObject* DemonClass_ShellcodeSpawn( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:389`
- Doc: ShellcodeSpawn( QString TaskID, QString InjectionTechnique, QString TargetArch, QString Path, QString Arguments )
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### DemonClass_DllInject (function) `PyObject* DemonClass_DllInject( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:430`
- Doc: Demon.DllInject( TaskID: str, Pid: str, DllPath: str, DllArgs: str )
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### DemonClass_DllSpawn (function) `PyObject* DemonClass_DllSpawn( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:453`
- Doc: Demon.DllInject( TaskID: str, DllPath: str, DllArgs: str )
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### DemonClass_ProcessCreate (function) `PyObject* DemonClass_ProcessCreate( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:491`
- Doc: Demon.ProcessCreate( TaskID: str App: str, Cmdline: str, Suspended: bool, Piped: bool, Verbose: bool )
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

### DemonClass_ConsoleWrite (function) `PyObject* DemonClass_ConsoleWrite( PPyDemonClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/PyDemonClass.cc:539`
- Doc: Other Methods
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

## client/src/Havoc/PythonApi/PythonApi.cc

### Stdout_write (function) `PyObject* Stdout_write(PyObject* self, PyObject* args)`
- Defined: `client/src/Havoc/PythonApi/PythonApi.cc:5`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`

### Stdout_flush (function) `PyObject* Stdout_flush(PyObject* self, PyObject* args)`
- Defined: `client/src/Havoc/PythonApi/PythonApi.cc:22`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`

### PyInit_emb (function) `PyMODINIT_FUNC PyInit_emb(void)`
- Defined: `client/src/Havoc/PythonApi/PythonApi.cc:87`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`

### set_stdout (function) `void set_stdout(stdout_write_type write)`
- Defined: `client/src/Havoc/PythonApi/PythonApi.cc:105`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`

### reset_stdout (function) `void reset_stdout()`
- Defined: `client/src/Havoc/PythonApi/PythonApi.cc:118`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`

### written (function) `std::size_t written(0);`
- Defined: `client/src/Havoc/PythonApi/PythonApi.cc:7`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`

## client/src/Havoc/PythonApi/UI/PyDialogClass.cc

### DialogClass_dealloc (function) `void DialogClass_dealloc( PPyDialogClass self )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:86`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_new (function) `PyObject* DialogClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:99`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_init (function) `int DialogClass_init( PPyDialogClass self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:121`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_exec (function) `PyObject* DialogClass_exec( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:155`
- Doc: Methods
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_addLabel (function) `PyObject* DialogClass_addLabel( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:163`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_addImage (function) `PyObject* DialogClass_addImage( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:177`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_addButton (function) `PyObject* DialogClass_addButton( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:193`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### connect (function) `QObject::connect(button, &QPushButton::clicked, self->DialogWindow->window, [button_callback]()`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:212`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_addCheckbox (function) `PyObject* DialogClass_addCheckbox( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:219`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### connect (function) `QObject::connect(checkbox, &QCheckBox::clicked, self->DialogWindow->window, [checkbox_callback]()`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:241`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_addCombobox (function) `PyObject* DialogClass_addCombobox( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:248`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### connect (function) `QObject::connect(comboBox, QOverload<int>::of(&QComboBox::activated), [callable_obj](int index)`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:265`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_addLineedit (function) `PyObject* DialogClass_addLineedit( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:272`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### connect (function) `QObject::connect(line, &QLineEdit::editingFinished, self->DialogWindow->window, [line, line_callb...`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:289`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_addCalendar (function) `PyObject* DialogClass_addCalendar( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:300`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### connect (function) `QObject::connect(cal, &QCalendarWidget::selectionChanged, self->DialogWindow->window, [cal, cal_c...`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:317`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_addDial (function) `PyObject* DialogClass_addDial( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:329`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### connect (function) `QObject::connect(dial, &QDial::valueChanged, self->DialogWindow->window, [cal_callback](long value)`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:345`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_addSlider (function) `PyObject* DialogClass_addSlider( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:352`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### connect (function) `QObject::connect(slider, &QSlider::valueChanged, self->DialogWindow->window, [cal_callback](long ...`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:374`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_replaceLabel (function) `PyObject* DialogClass_replaceLabel( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:381`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_close (function) `PyObject* DialogClass_close( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:405`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

### DialogClass_clear (function) `PyObject* DialogClass_clear( PPyDialogClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc:412`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`

## client/src/Havoc/PythonApi/UI/PyLoggerClass.cc

### LoggerClass_dealloc (function) `void LoggerClass_dealloc( PPyLoggerClass self )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:77`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`

### LoggerClass_new (function) `PyObject* LoggerClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:86`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`

### LoggerClass_init (function) `int LoggerClass_init( PPyLoggerClass self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:95`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`

### LoggerClass_setBottomTab (function) `PyObject* LoggerClass_setBottomTab( PPyLoggerClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:123`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`

### LoggerClass_setSmallTab (function) `PyObject* LoggerClass_setSmallTab( PPyLoggerClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:130`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`

### LoggerClass_addText (function) `PyObject* LoggerClass_addText( PPyLoggerClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:137`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`

### LoggerClass_clear (function) `PyObject* LoggerClass_clear( PPyLoggerClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc:149`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`

## client/src/Havoc/PythonApi/UI/PyTreeClass.cc

### TreeClass_dealloc (function) `void TreeClass_dealloc( PPyTreeClass self )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:78`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`

### TreeClass_new (function) `PyObject* TreeClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:91`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`

### TreeClass_init (function) `int TreeClass_init( PPyTreeClass self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:112`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`

### connect (function) `QObject::connect(self->TreeWindow->tree_view->selectionModel(), &QItemSelectionModel::selectionCh...`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:165`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`

### TreeClass_setBottomTab (function) `PyObject* TreeClass_setBottomTab( PPyTreeClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:181`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`

### TreeClass_setSmallTab (function) `PyObject* TreeClass_setSmallTab( PPyTreeClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:188`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`

### TreeClass_addRow (function) `PyObject* TreeClass_addRow( PPyTreeClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:195`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`

### TreeClass_setItem (function) `PyObject* TreeClass_setItem( PPyTreeClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:218`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`

### TreeClass_setPanel (function) `PyObject* TreeClass_setPanel( PPyTreeClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyTreeClass.cc:233`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`

## client/src/Havoc/PythonApi/UI/PyWidgetClass.cc

### WidgetClass_dealloc (function) `void WidgetClass_dealloc( PPyWidgetClass self )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:86`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_new (function) `PyObject* WidgetClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:99`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_init (function) `int WidgetClass_init( PPyWidgetClass self, PyObject *args, PyObject *kwds )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:119`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_addLabel (function) `PyObject* WidgetClass_addLabel( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:149`
- Doc: Methods
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_addImage (function) `PyObject* WidgetClass_addImage( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:163`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_setBottomTab (function) `PyObject* WidgetClass_setBottomTab( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:179`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_setSmallTab (function) `PyObject* WidgetClass_setSmallTab( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:186`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_addButton (function) `PyObject* WidgetClass_addButton( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:193`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### connect (function) `QObject::connect(button, &QPushButton::clicked, self->WidgetWindow->window, [button_callback]()`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:212`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_addCheckbox (function) `PyObject* WidgetClass_addCheckbox( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:219`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### connect (function) `QObject::connect(checkbox, &QCheckBox::clicked, self->WidgetWindow->window, [checkbox_callback]()`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:241`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_addCombobox (function) `PyObject* WidgetClass_addCombobox( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:248`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### connect (function) `QObject::connect(comboBox, QOverload<int>::of(&QComboBox::activated), [callable_obj](int index)`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:265`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_addLineedit (function) `PyObject* WidgetClass_addLineedit( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:272`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### connect (function) `QObject::connect(line, &QLineEdit::editingFinished, self->WidgetWindow->window, [line, line_callb...`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:289`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_addCalendar (function) `PyObject* WidgetClass_addCalendar( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:300`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### connect (function) `QObject::connect(cal, &QCalendarWidget::selectionChanged, self->WidgetWindow->window, [cal, cal_c...`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:317`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_addDial (function) `PyObject* WidgetClass_addDial( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:329`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### connect (function) `QObject::connect(dial, &QDial::valueChanged, self->WidgetWindow->window, [cal_callback](long value)`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:345`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_addSlider (function) `PyObject* WidgetClass_addSlider( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:352`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### connect (function) `QObject::connect(slider, &QSlider::valueChanged, self->WidgetWindow->window, [cal_callback](long ...`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:374`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_replaceLabel (function) `PyObject* WidgetClass_replaceLabel( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:381`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

### WidgetClass_clear (function) `PyObject* WidgetClass_clear( PPyWidgetClass self, PyObject *args )`
- Defined: `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc:405`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`

## client/src/UserInterface/Dialogs/About.cc

### About (function) `About::About( QDialog* dialog )`
- Defined: `client/src/UserInterface/Dialogs/About.cc:4`
- Depends on: `client/include/UserInterface/Dialogs/About.hpp`, `client/include/global.hpp`

### setupUi (function) `void About::setupUi()`
- Defined: `client/src/UserInterface/Dialogs/About.cc:49`
- Depends on: `client/include/UserInterface/Dialogs/About.hpp`, `client/include/global.hpp`

### onButtonClose (function) `void About::onButtonClose()`
- Defined: `client/src/UserInterface/Dialogs/About.cc:54`
- Depends on: `client/include/UserInterface/Dialogs/About.hpp`, `client/include/global.hpp`

## client/src/UserInterface/Dialogs/Connect.cc

### setupUi (function) `void HavocNamespace::UserInterface::Dialogs::Connect::setupUi( QDialog* Form )`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:9`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

### connect (function) `connect( lineEdit_Name, &QLineEdit::returnPressed, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:142`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

### connect (function) `connect( lineEdit_User, &QLineEdit::returnPressed, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:146`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

### connect (function) `connect( lineEdit_Host, &QLineEdit::returnPressed, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:150`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

### connect (function) `connect( lineEdit_Port, &QLineEdit::returnPressed, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:154`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

### connect (function) `connect( lineEdit_Password, &QLineEdit::returnPressed, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:158`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

### StartDialog (function) `Util::ConnectionInfo HavocNamespace::UserInterface::Dialogs::Connect::StartDialog( bool FromAction )`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:165`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

### passDB (function) `void HavocNamespace::UserInterface::Dialogs::Connect::passDB(HavocNamespace::HavocSpace::DBManage...`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:229`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

### onButton_Connect (function) `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_Connect()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:234`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

### itemSelected (function) `void HavocNamespace::UserInterface::Dialogs::Connect::itemSelected()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:318`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

### onButton_NewProfile (function) `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_NewProfile()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:340`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

### handleContextMenu (function) `void HavocNamespace::UserInterface::Dialogs::Connect::handleContextMenu( const QPoint &pos )`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:356`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

### itemRemove (function) `void HavocNamespace::UserInterface::Dialogs::Connect::itemRemove()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:362`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

### itemsClear (function) `void HavocNamespace::UserInterface::Dialogs::Connect::itemsClear()`
- Defined: `client/src/UserInterface/Dialogs/Connect.cc:376`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

## client/src/UserInterface/Dialogs/Listener.cc

### is_number (function) `bool is_number( const std::string& s )`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:17`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

### NewListener (function) `NewListener::NewListener( QDialog* Dialog )`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:24`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

### connect (function) `QObject::connect( ButtonClose, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:331`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

### connect (function) `QObject::connect( ButtonHostsGroupAdd, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:339`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

### connect (function) `QObject::connect( ButtonHostsGroupClear, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:356`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

### connect (function) `QObject::connect( ButtonUriGroupAdd, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:366`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

### connect (function) `QObject::connect( ButtonUriGroupClear, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:377`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

### connect (function) `QObject::connect( ButtonHeaderGroupAdd, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:387`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

### connect (function) `QObject::connect( ButtonHeaderGroupClear, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:398`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

### connect (function) `QObject::connect( ComboPayload, &QComboBox::currentTextChanged, this, [&]( const QString& text )`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:408`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

### Start (function) `MapStrStr NewListener::Start( Util::ListenerItem Item, bool Edit )`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:450`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

### onButton_Save (function) `void HavocNamespace::UserInterface::Dialogs::NewListener::onButton_Save()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:817`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

### onProxyEnabled (function) `void HavocNamespace::UserInterface::Dialogs::NewListener::onProxyEnabled()`
- Defined: `client/src/UserInterface/Dialogs/Listener.cc:947`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

## client/src/UserInterface/Dialogs/Payload.cc

### setupUi (function) `void Payload::setupUi( QDialog* Dialog )`
- Defined: `client/src/UserInterface/Dialogs/Payload.cc:17`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `connect( ComboFormat, &QComboBox::currentTextChanged, this, [&]( const QString& text )`
- Defined: `client/src/UserInterface/Dialogs/Payload.cc:124`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### buttonGenerate (function) `void Payload::buttonGenerate()`
- Defined: `client/src/UserInterface/Dialogs/Payload.cc:190`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/HavocUi.cc

### setupUi (function) `void HavocNamespace::UserInterface::HavocUi::setupUi(QMainWindow *Havoc)`
- Defined: `client/src/UserInterface/HavocUi.cc:28`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### OneSecondTick (function) `void HavocNamespace::UserInterface::HavocUi::OneSecondTick()`
- Defined: `client/src/UserInterface/HavocUi.cc:200`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### MarkSessionAs (function) `void HavocNamespace::UserInterface::HavocUi::MarkSessionAs(HavocNamespace::Util::SessionItem Sess...`
- Defined: `client/src/UserInterface/HavocUi.cc:205`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### UpdateSessionsHealth (function) `void HavocNamespace::UserInterface::HavocUi::UpdateSessionsHealth()`
- Defined: `client/src/UserInterface/HavocUi.cc:263`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### retranslateUi (function) `void HavocNamespace::UserInterface::HavocUi::retranslateUi(QMainWindow* Havoc ) const`
- Defined: `client/src/UserInterface/HavocUi.cc:361`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### ConnectEvents (function) `void HavocNamespace::UserInterface::HavocUi::ConnectEvents()`
- Defined: `client/src/UserInterface/HavocUi.cc:395`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( OneSecondTimer, &QTimer::timeout, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:399`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionNew_Client, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:404`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionChat, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:408`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionDisconnect, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:422`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionExit, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:431`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionSessionsTable, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:435`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionListeners, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:439`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionTeamserver, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:455`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionStore, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:467`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionSessionsGraph, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:479`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionLogs, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:483`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionLoot, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:498`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionGeneratePayload, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:506`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionPythonConsole, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:516`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionLoad_Script, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:530`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionAbout, &QAction::triggered, this, [&]()`
- Defined: `client/src/UserInterface/HavocUi.cc:549`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionGithub_Repository, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:558`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QMainWindow::connect( actionOpen_Help_Documentation, &QAction::triggered, this, []()`
- Defined: `client/src/UserInterface/HavocUi.cc:562`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### NewBottomTab (function) `void HavocNamespace::UserInterface::HavocUi::NewBottomTab(QWidget* TabWidget, const std::string& ...`
- Defined: `client/src/UserInterface/HavocUi.cc:567`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### setDBManager (function) `void HavocNamespace::UserInterface::HavocUi::setDBManager(HavocSpace::DBManager* dbManager)`
- Defined: `client/src/UserInterface/HavocUi.cc:572`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### NewTeamserverTab (function) `void UserInterface::HavocUi::NewTeamserverTab(HavocNamespace::Util::ConnectionInfo* Connection )`
- Defined: `client/src/UserInterface/HavocUi.cc:577`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### NewTeamserverTab (function) `void UserInterface::HavocUi::NewTeamserverTab(QString Name )`
- Defined: `client/src/UserInterface/HavocUi.cc:587`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### NewSmallTab (function) `void UserInterface::HavocUi::NewSmallTab(QWidget *TabWidget, const string &TitleName ) const`
- Defined: `client/src/UserInterface/HavocUi.cc:596`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### PythonPrepare (function) `void UserInterface::HavocUi::PythonPrepare()`
- Defined: `client/src/UserInterface/HavocUi.cc:602`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/SmallWidgets/EventViewer.cc

### setupUi (function) `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::setupUi(QWidget *Widget)`
- Defined: `client/src/UserInterface/SmallWidgets/EventViewer.cc:4`
- Depends on: `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/Util/ColorText.h`

### AppendText (function) `void HavocNamespace::UserInterface::SmallWidgets::EventViewer::AppendText(const QString& Time, co...`
- Defined: `client/src/UserInterface/SmallWidgets/EventViewer.cc:23`
- Depends on: `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/Util/ColorText.h`

## client/src/UserInterface/Widgets/Chat.cc

### setupUi (function) `void HavocNamespace::UserInterface::Widgets::Chat::setupUi( QWidget *Form )`
- Defined: `client/src/UserInterface/Widgets/Chat.cc:11`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### AppendText (function) `void HavocNamespace::UserInterface::Widgets::Chat::AppendText(const QString& Time, const QString&...`
- Defined: `client/src/UserInterface/Widgets/Chat.cc:63`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### AddUserMessage (function) `void HavocNamespace::UserInterface::Widgets::Chat::AddUserMessage(const QString Time, QString Use...`
- Defined: `client/src/UserInterface/Widgets/Chat.cc:70`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### AppendFromInput (function) `void HavocNamespace::UserInterface::Widgets::Chat::AppendFromInput()`
- Defined: `client/src/UserInterface/Widgets/Chat.cc:78`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/DemonInteracted.cc

### DemonInput (function) `DemonInteracted::DemonInput::DemonInput( QWidget* parent ) : QLineEdit( parent )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:16`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### handleKeyPress (function) `bool DemonInteracted::DemonInput::handleKeyPress( QKeyEvent* eventKey )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:21`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### handleTabKey (function) `void DemonInteracted::DemonInput::handleTabKey()`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:39`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### handleUpKey (function) `void DemonInteracted::DemonInput::handleUpKey()`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:47`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### handleDownKey (function) `void DemonInteracted::DemonInput::handleDownKey()`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:67`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### event (function) `bool DemonInteracted::DemonInput::event( QEvent* e )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:78`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### AddCommand (function) `void DemonInteracted::DemonInput::AddCommand( const QString &Command )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:90`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### setupUi (function) `void DemonInteracted::setupUi( QWidget *Form )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:95`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### AppendFromInput (function) `void DemonInteracted::AppendFromInput()`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:209`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### AppendText (function) `void DemonInteracted::AppendText( const QString& text )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:214`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### TaskInfo (function) `QString DemonInteracted::TaskInfo( bool Show, QString TaskID, const QString &text ) const`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:281`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### TaskError (function) `QString DemonInteracted::TaskError( const QString &text ) const`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:296`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### AppendRaw (function) `void UserInterface::Widgets::DemonInteracted::AppendRaw(const QString& text)`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:303`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### AppendNoNL (function) `void DemonInteracted::AppendNoNL( const QString &text )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:308`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### AutoCompleteAdd (function) `void DemonInteracted::AutoCompleteAdd( QString text )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:317`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### AutoCompleteClear (function) `void DemonInteracted::AutoCompleteClear()`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:326`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### AutoCompleteAddList (function) `void DemonInteracted::AutoCompleteAddList( QStringList list )`
- Defined: `client/src/UserInterface/Widgets/DemonInteracted.cc:336`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/FileBrowser.cc

### setupUi (function) `void FileBrowser::setupUi( QWidget* FileBrowser )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:40`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### retranslateUi (function) `void FileBrowser::retranslateUi()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:148`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### AddData (function) `void FileBrowser::AddData( QJsonDocument JsonData )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:159`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### TreeAddData (function) `void FileBrowser::TreeAddData( FileData Data )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:234`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### TableAddData (function) `void FileBrowser::TableAddData( FileData Data )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:239`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onTableDoubleClick (function) `void FileBrowser::onTableDoubleClick( int row, int column )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:276`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onTreeDoubleClick (function) `void FileBrowser::onTreeDoubleClick()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:292`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### ChangePathAndSendRequest (function) `void FileBrowser::ChangePathAndSendRequest( QString Path )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:297`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### TableClear (function) `void FileBrowser::TableClear()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:313`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onButtonUp (function) `void FileBrowser::onButtonUp()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:320`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onTableMenuDownload (function) `void FileBrowser::onTableMenuDownload()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:327`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onTableContextMenu (function) `void FileBrowser::onTableContextMenu( const QPoint &pos )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:363`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onTreeContextMenu (function) `void FileBrowser::onTreeContextMenu( const QPoint &pos )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:371`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onTableMenuMkdir (function) `void FileBrowser::onTableMenuMkdir()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:379`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onTableMenuReload (function) `void FileBrowser::onTableMenuReload()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:384`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onTableMenuRemove (function) `void FileBrowser::onTableMenuRemove()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:405`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onTreeMenuListDrives (function) `void FileBrowser::onTreeMenuListDrives()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:410`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onTreeMenuMkdir (function) `void FileBrowser::onTreeMenuMkdir()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:415`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onTreeMenuReload (function) `void FileBrowser::onTreeMenuReload()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:420`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onTreeMenuRemove (function) `void FileBrowser::onTreeMenuRemove()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:425`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### onInputPath (function) `void FileBrowser::onInputPath()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:430`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### TreeUpdate (function) `void FileBrowser::TreeUpdate()`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:438`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### TreeClear (function) `void FileBrowser::TreeClear( )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:500`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### TreeAddDisk (function) `void FileBrowser::TreeAddDisk( QString Disk )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:523`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

### TreeAddChildToParent (function) `void FileBrowser::TreeAddChildToParent( QString ParentPath, FileBrowserTreeItem* DataItem )`
- Defined: `client/src/UserInterface/Widgets/FileBrowser.cc:537`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/ListenersTable.cc

### setupUi (function) `void HavocNamespace::UserInterface::Widgets::ListenersTable::setupUi( QWidget* Form )`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:15`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### ButtonsInit (function) `void HavocNamespace::UserInterface::Widgets::ListenersTable::ButtonsInit()`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:85`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QObject::connect( buttonAdd, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:87`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QObject::connect( buttonEdit, &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:108`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `QObject::connect( buttonRemove,  &QPushButton::clicked, this, [&]()`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:152`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### ListenerAdd (function) `void HavocNamespace::UserInterface::Widgets::ListenersTable::ListenerAdd( Util::ListenerItem item...`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:178`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### setDBManager (function) `void HavocNamespace::UserInterface::Widgets::ListenersTable::setDBManager( HavocSpace::DBManager*...`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:284`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### CreateNewPackage (function) `Util::Packager::Package UserInterface::Widgets::ListenersTable::CreateNewPackage( int EventID, ma...`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:289`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### ListenerEdit (function) `void UserInterface::Widgets::ListenersTable::ListenerEdit( Util::ListenerItem item ) const`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:312`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### ListenerRemove (function) `void UserInterface::Widgets::ListenersTable::ListenerRemove( QString ListenerName ) const`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:323`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### ListenerError (function) `void UserInterface::Widgets::ListenersTable::ListenerError( QString ListenerName, QString Error )...`
- Defined: `client/src/UserInterface/Widgets/ListenersTable.cc:357`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/LootWidget.cc

### ImageLabel (function) `ImageLabel::ImageLabel( QWidget* parent ) : QWidget( parent )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:17`
- Doc: imagelabel.cpp
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### resizeEvent (function) `void ImageLabel::resizeEvent( QResizeEvent* event )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:33`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### pixmap (function) `const QPixmap* ImageLabel::pixmap() const`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:39`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### event (function) `bool ImageLabel::event( QEvent* e )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:44`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### keyReleaseEvent (function) `void ImageLabel::keyReleaseEvent( QKeyEvent* event )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:60`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### wheelEvent (function) `void ImageLabel::wheelEvent( QWheelEvent* ev )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:71`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### setPixmap (function) `void ImageLabel::setPixmap( const QPixmap &pixmap )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:78`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### resizeImage (function) `void ImageLabel::resizeImage()`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:85`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### LootWidget (function) `LootWidget::LootWidget()`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:92`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### AddScreenshot (function) `void LootWidget::AddScreenshot( const QString& DemonID, const QString& Name, const QString& Date,...`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:253`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### AddDownload (function) `void LootWidget::AddDownload( const QString &DemonID, const QString &Name, const QString& Size, c...`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:273`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### Reload (function) `void LootWidget::Reload()`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:292`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### onScreenshotTableClick (function) `void LootWidget::onScreenshotTableClick( const QModelIndex &index )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:305`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### onDownloadTableClick (function) `void LootWidget::onDownloadTableClick( const QModelIndex &index )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:329`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### onAgentChange (function) `void LootWidget::onAgentChange( const QString& text )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:334`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### AddSessionSection (function) `void LootWidget::AddSessionSection( const QString& AgentID )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:364`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### onShowChange (function) `void LootWidget::onShowChange( const QString& text )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:377`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### ScreenshotTableAdd (function) `void LootWidget::ScreenshotTableAdd( const QString &Name, const QString &Date )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:389`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### DownloadTableAdd (function) `void LootWidget::DownloadTableAdd( const QString &Name, const QString &Size, const QString &Date )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:414`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

### onScreenshotTableCtx (function) `void LootWidget::onScreenshotTableCtx( const QPoint &pos )`
- Defined: `client/src/UserInterface/Widgets/LootWidget.cc:436`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/ProcessList.cc

### setupUi (function) `void HavocNamespace::UserInterface::Widgets::ProcessList::setupUi(QWidget *Widget)`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:5`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`

### UpdateProcessListJson (function) `void HavocNamespace::UserInterface::Widgets::ProcessList::UpdateProcessListJson( QJsonDocument Pr...`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:201`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`

### NewTableProcess (function) `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTableProcess(std::map<QString, QStri...`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:231`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`

### NewTreeProcess (function) `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTreeProcess( std::map<QString,QStrin...`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:279`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`

### onButton_Refresh (function) `void HavocNamespace::UserInterface::Widgets::ProcessList::onButton_Refresh() const`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:299`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`

### onTableChange (function) `void HavocNamespace::UserInterface::Widgets::ProcessList::onTableChange()`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:314`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`

### onTreeChange (function) `void HavocNamespace::UserInterface::Widgets::ProcessList::onTreeChange()`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:330`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`

### handleTableListMenuContext (function) `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTableListMenuContext( const QPoin...`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:343`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`

### handleTreeListMenuContext (function) `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTreeListMenuContext( const QPoint...`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:351`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`

### onActionCopyPID (function) `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionCopyPID()`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:359`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`

### onActionSetParentProcess (function) `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionSetParentProcess()`
- Defined: `client/src/UserInterface/Widgets/ProcessList.cc:367`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`

## client/src/UserInterface/Widgets/PythonScript.cc

### setupUi (function) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::setupUi(QWidget *WindowWidget)`
- Defined: `client/src/UserInterface/Widgets/PythonScript.cc:9`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/Util/ColorText.h`

### RunCode (function) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::RunCode( QString code )`
- Defined: `client/src/UserInterface/Widgets/PythonScript.cc:48`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/Util/ColorText.h`

### AppendFromInput (function) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendFromInput()`
- Defined: `client/src/UserInterface/Widgets/PythonScript.cc:64`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/Util/ColorText.h`

### AppendOutput (function) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendOutput( QString output )`
- Defined: `client/src/UserInterface/Widgets/PythonScript.cc:76`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/Util/ColorText.h`

## client/src/UserInterface/Widgets/ScriptManager.cc

### SetupUi (function) `void ScriptManager::SetupUi( QWidget *Form )`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:13`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`

### RetranslateUi (function) `void ScriptManager::RetranslateUi( )`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:104`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`

### AddScript (function) `bool ScriptManager::AddScript( QString Path )`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:111`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`

### AddScriptTable (function) `void ScriptManager::AddScriptTable( QString Path )`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:140`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`

### b_LoadScript (function) `void ScriptManager::b_LoadScript()`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:155`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`

### menu_ScriptMenu (function) `void ScriptManager::menu_ScriptMenu( const QPoint &pos ) const`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:186`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`

### ReloadScript (function) `void ScriptManager::ReloadScript() const`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:195`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`

### RemoveScript (function) `void ScriptManager::RemoveScript() const`
- Defined: `client/src/UserInterface/Widgets/ScriptManager.cc:204`
- Doc: TODO: clear python interpreter and reload every script except the one that got removed
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`

## client/src/UserInterface/Widgets/SessionGraph.cc

### GraphWidget (function) `GraphWidget::GraphWidget( QWidget* parent ) : QGraphicsView( parent )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:28`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### GraphNodeAdd (function) `Node* GraphWidget::GraphNodeAdd( SessionItem Session )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:54`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### GraphNodeRemove (function) `void GraphWidget::GraphNodeRemove( SessionItem Session )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:84`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### GraphPivotNodeAdd (function) `void GraphWidget::GraphPivotNodeAdd( QString AgentID, SessionItem Session )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:105`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### GraphPivotNodeDisconnect (function) `void GraphWidget::GraphPivotNodeDisconnect( QString AgentID )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:147`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### GraphPivotNodeReconnect (function) `void GraphWidget::GraphPivotNodeReconnect( QString ParentAgentID, QString ChildAgentID )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:170`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### itemMoved (function) `void GraphWidget::itemMoved()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:198`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### keyPressEvent (function) `void GraphWidget::keyPressEvent( QKeyEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:204`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### timerEvent (function) `void GraphWidget::timerEvent( QTimerEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:221`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### resizeEvent (function) `void GraphWidget::resizeEvent( QResizeEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:251`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### wheelEvent (function) `void GraphWidget::wheelEvent( QWheelEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:258`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### drawBackground (function) `void GraphWidget::drawBackground( QPainter* painter, const QRectF& rect )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:263`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### scaleView (function) `void GraphWidget::scaleView( qreal scaleFactor )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:279`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### shuffle (function) `void GraphWidget::shuffle()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:288`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### zoomIn (function) `void GraphWidget::zoomIn()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:299`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### zoomOut (function) `void GraphWidget::zoomOut()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:304`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### GraphNodeGet (function) `Node *GraphWidget::GraphNodeGet( QString AgentID )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:309`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### initNode (function) `void GraphWidget::initNode(Node* v)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:329`
- Doc: Initialize node properties for layout
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### layout (function) `void GraphWidget::layout(Node* T)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:340`
- Doc: Entry function for layout
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### firstWalk (function) `void GraphWidget::firstWalk(Node* v)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:350`
- Doc: Calculate preliminary x-coordinates for all nodes
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### apportion (function) `void GraphWidget::apportion(Node* v, Node*& defaultAncestor)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:383`
- Doc: Adjusts spacing between subtrees to ensure they don't overlap
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### moveSubtree (function) `void GraphWidget::moveSubtree(Node* wm, Node* wp, double shift)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:434`
- Doc: Move the subtree rooted at wp so it's shifted away from the subtree rooted at wm
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### nextLeft (function) `Node* GraphWidget::nextLeft(Node* v)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:453`
- Doc: Helper function to get the leftmost child or thread (left contour)
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### nextRight (function) `Node* GraphWidget::nextRight(Node* v)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:462`
- Doc: Helper function to get the rightmost child or thread (right contour)
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### ancestor (function) `Node* GraphWidget::ancestor(Node* vim, Node* v, Node*& defaultAncestor)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:471`
- Doc: Get the ancestor of vim that is in the same subtree as v, or return defaultAncestor
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### executeShifts (function) `void GraphWidget::executeShifts(Node* v)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:481`
- Doc: Propagate the shifts down to ensure subtrees are moved accordingly
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### secondWalk (function) `void GraphWidget::secondWalk(Node* v, double m, double depth)`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:496`
- Doc: Walk the tree again to assign final x and y coordinates to each node
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### Edge (function) `Edge::Edge( Node* sourceNode, Node* destNode, QColor Color )
    : source( sourceNode ), dest( de...`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:508`
- Doc: ================================================== =================== Edge Class =================== ==================
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### sourceNode (function) `Node* Edge::sourceNode() const`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:519`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### destNode (function) `Node* Edge::destNode() const`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:524`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### contextMenuEvent (function) `void Node::contextMenuEvent( QGraphicsSceneContextMenuEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:529`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### adjust (function) `void Edge::adjust()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:798`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### boundingRect (function) `QRectF Edge::boundingRect() const`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:822`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### paint (function) `void Edge::paint( QPainter* painter, const QStyleOptionGraphicsItem*, QWidget* )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:835`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### Color (function) `void Edge::Color( QColor color )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:863`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### Node (function) `Node::Node( NodeItemType NodeType, QString NodeLabel, GraphWidget* graphWidget ) : graph( graphWi...`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:871`
- Doc: ================================================== =================== Node Class =================== ==================
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### appendChild (function) `void Node::appendChild( Node* child )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:887`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### removeChild (function) `void Node::removeChild( Node* child )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:892`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### boundingRect (function) `QRectF Node::boundingRect() const`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:899`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### addEdge (function) `void Node::addEdge( Edge* edge )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:904`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### edges (function) `QVector<Edge*> Node::edges() const`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:910`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### calculateForces (function) `void Node::calculateForces()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:915`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### mouseMoveEvent (function) `void Node::mouseMoveEvent( QGraphicsSceneMouseEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:936`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### advancePosition (function) `bool Node::advancePosition()`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:941`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### shape (function) `QPainterPath Node::shape() const`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:950`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### paint (function) `void Node::paint( QPainter *painter, const QStyleOptionGraphicsItem* option, QWidget* )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:959`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### itemChange (function) `QVariant Node::itemChange( GraphicsItemChange change, const QVariant& value )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:1007`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### mousePressEvent (function) `void Node::mousePressEvent( QGraphicsSceneMouseEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:1026`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### mouseReleaseEvent (function) `void Node::mouseReleaseEvent( QGraphicsSceneMouseEvent* event )`
- Defined: `client/src/UserInterface/Widgets/SessionGraph.cc:1032`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/SessionTable.cc

### setupUi (function) `void HavocNamespace::UserInterface::Widgets::SessionTable::setupUi(QWidget *Form, QString Teamser...`
- Defined: `client/src/UserInterface/Widgets/SessionTable.cc:16`
- Depends on: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### NewSessionItem (function) `void HavocNamespace::UserInterface::Widgets::SessionTable::NewSessionItem( Util::SessionItem item...`
- Defined: `client/src/UserInterface/Widgets/SessionTable.cc:82`
- Depends on: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### ChangeSessionValue (function) `void UserInterface::Widgets::SessionTable::ChangeSessionValue( QString DemonID, int key, QString ...`
- Defined: `client/src/UserInterface/Widgets/SessionTable.cc:211`
- Depends on: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### updateRow (function) `void HavocNamespace::UserInterface::Widgets::SessionTable::updateRow()`
- Defined: `client/src/UserInterface/Widgets/SessionTable.cc:220`
- Depends on: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/Store.cc

### setupUi (function) `void Store::setupUi( QWidget* Store)`
- Defined: `client/src/UserInterface/Widgets/Store.cc:10`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/global.hpp`

### connect (function) `QObject::connect(reply, &QNetworkReply::finished, [reply, this]()`
- Defined: `client/src/UserInterface/Widgets/Store.cc:76`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/global.hpp`

### connect (function) `QObject::connect(StoreTable, &QTableWidget::itemSelectionChanged, [this]()`
- Defined: `client/src/UserInterface/Widgets/Store.cc:109`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/global.hpp`

### connect (function) `QObject::connect(installButton, &QPushButton::clicked, [this]()`
- Defined: `client/src/UserInterface/Widgets/Store.cc:116`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/global.hpp`

### displayData (function) `void Store::displayData(int position)`
- Defined: `client/src/UserInterface/Widgets/Store.cc:134`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/global.hpp`

### AddScript (function) `bool Store::AddScript( QString Path )`
- Defined: `client/src/UserInterface/Widgets/Store.cc:147`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/global.hpp`

### installScript (function) `void Store::installScript(int position)`
- Defined: `client/src/UserInterface/Widgets/Store.cc:176`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/global.hpp`

### retranslateUi (function) `void Store::retranslateUi()`
- Defined: `client/src/UserInterface/Widgets/Store.cc:224`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/Teamserver.cc

### setupUi (function) `void Teamserver::setupUi( QWidget* Teamserver )`
- Defined: `client/src/UserInterface/Widgets/Teamserver.cc:5`
- Depends on: `client/include/UserInterface/Widgets/Teamserver.hpp`

### retranslateUi (function) `void Teamserver::retranslateUi()`
- Defined: `client/src/UserInterface/Widgets/Teamserver.cc:26`
- Depends on: `client/include/UserInterface/Widgets/Teamserver.hpp`

### AddLoggerText (function) `void Teamserver::AddLoggerText( const QString& Text ) const`
- Defined: `client/src/UserInterface/Widgets/Teamserver.cc:31`
- Depends on: `client/include/UserInterface/Widgets/Teamserver.hpp`

## client/src/UserInterface/Widgets/TeamserverTabSession.cc

### setupUi (function) `void HavocNamespace::UserInterface::Widgets::TeamserverTabSession::setupUi( QWidget* Page, QStrin...`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:27`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `connect( tabWidget->tabBar(), &QTabBar::tabCloseRequested, this, [&]( int index )`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:121`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### connect (function) `connect( SessionTableWidget->SessionTableWidget, &QTableWidget::doubleClicked, this, [&]( const Q...`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:141`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### handleDemonContextMenu (function) `void UserInterface::Widgets::TeamserverTabSession::handleDemonContextMenu( const QPoint &pos )`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:165`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### NewBottomTab (function) `void UserInterface::Widgets::TeamserverTabSession::NewBottomTab( QWidget* TabWidget, const string...`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:469`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### NewWidgetTab (function) `void UserInterface::Widgets::TeamserverTabSession::NewWidgetTab( QWidget *TabWidget, const std::s...`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:488`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

### removeTabSmall (function) `void UserInterface::Widgets::TeamserverTabSession::removeTabSmall( int index ) const`
- Defined: `client/src/UserInterface/Widgets/TeamserverTabSession.cc:509`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/Util/Base64.cpp

### base64_encode (function) `std::string HavocNamespace::Util::base64_encode(const char* buf, unsigned int bufLen)`
- Defined: `client/src/Util/Base64.cpp:9`
- Depends on: `client/include/global.hpp`

## client/src/Util/ColorText.cpp

### SetDraculaDark (function) `void HavocNamespace::Util::ColorText::SetDraculaDark()`
- Defined: `client/src/Util/ColorText.cpp:24`
- Depends on: `client/include/Util/ColorText.h`

### SetDraculaLight (function) `void HavocNamespace::Util::ColorText::SetDraculaLight()`
- Defined: `client/src/Util/ColorText.cpp:40`
- Depends on: `client/include/Util/ColorText.h`

### Color (function) `QString HavocNamespace::Util::ColorText::Color(const QString& color, const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:45`
- Depends on: `client/include/Util/ColorText.h`

### Background (function) `QString HavocNamespace::Util::ColorText::Background(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:50`
- Depends on: `client/include/Util/ColorText.h`

### Foreground (function) `QString HavocNamespace::Util::ColorText::Foreground(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:55`
- Depends on: `client/include/Util/ColorText.h`

### Comment (function) `QString HavocNamespace::Util::ColorText::Comment(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:59`
- Depends on: `client/include/Util/ColorText.h`

### Cyan (function) `QString HavocNamespace::Util::ColorText::Cyan(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:63`
- Depends on: `client/include/Util/ColorText.h`

### Green (function) `QString HavocNamespace::Util::ColorText::Green(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:67`
- Depends on: `client/include/Util/ColorText.h`

### Orange (function) `QString HavocNamespace::Util::ColorText::Orange(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:71`
- Depends on: `client/include/Util/ColorText.h`

### Pink (function) `QString HavocNamespace::Util::ColorText::Pink(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:75`
- Depends on: `client/include/Util/ColorText.h`

### Purple (function) `QString HavocNamespace::Util::ColorText::Purple(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:79`
- Depends on: `client/include/Util/ColorText.h`

### Red (function) `QString HavocNamespace::Util::ColorText::Red(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:83`
- Depends on: `client/include/Util/ColorText.h`

### Yellow (function) `QString HavocNamespace::Util::ColorText::Yellow(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:87`
- Depends on: `client/include/Util/ColorText.h`

### Bold (function) `QString HavocNamespace::Util::ColorText::Bold(const QString& text)`
- Defined: `client/src/Util/ColorText.cpp:91`
- Depends on: `client/include/Util/ColorText.h`

### Underline (function) `QString HavocNamespace::Util::ColorText::Underline(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:95`
- Depends on: `client/include/Util/ColorText.h`

### UnderlineBackground (function) `QString HavocNamespace::Util::ColorText::UnderlineBackground(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:99`
- Depends on: `client/include/Util/ColorText.h`

### UnderlineForeground (function) `QString HavocNamespace::Util::ColorText::UnderlineForeground(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:103`
- Depends on: `client/include/Util/ColorText.h`

### UnderlineComment (function) `QString HavocNamespace::Util::ColorText::UnderlineComment(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:107`
- Depends on: `client/include/Util/ColorText.h`

### UnderlineCyan (function) `QString HavocNamespace::Util::ColorText::UnderlineCyan(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:111`
- Depends on: `client/include/Util/ColorText.h`

### UnderlineGreen (function) `QString HavocNamespace::Util::ColorText::UnderlineGreen(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:115`
- Depends on: `client/include/Util/ColorText.h`

### UnderlineOrange (function) `QString HavocNamespace::Util::ColorText::UnderlineOrange(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:119`
- Depends on: `client/include/Util/ColorText.h`

### UnderlinePink (function) `QString HavocNamespace::Util::ColorText::UnderlinePink(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:123`
- Depends on: `client/include/Util/ColorText.h`

### UnderlinePurple (function) `QString HavocNamespace::Util::ColorText::UnderlinePurple(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:127`
- Depends on: `client/include/Util/ColorText.h`

### UnderlineRed (function) `QString HavocNamespace::Util::ColorText::UnderlineRed(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:131`
- Depends on: `client/include/Util/ColorText.h`

### UnderlineYellow (function) `QString HavocNamespace::Util::ColorText::UnderlineYellow(const QString &text)`
- Defined: `client/src/Util/ColorText.cpp:135`
- Depends on: `client/include/Util/ColorText.h`

## client/src/global.cc

### gen_random (function) `std::string Util::gen_random( const int len )`
- Defined: `client/src/global.cc:31`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/global.hpp`

### Export (function) `void Util::SessionItem::Export()`
- Defined: `client/src/global.cc:42`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/global.hpp`

## payloads/Demon/include/common/Native.h

### NtCurrentPeb (function) `__inline struct _PEB * NtCurrentPeb()`
- Defined: `payloads/Demon/include/common/Native.h:7104`
- Doc: 17/3/2011 added
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### GetKUserSharedData (function) `__inline struct _KUSER_SHARED_DATA * GetKUserSharedData()`
- Defined: `payloads/Demon/include/common/Native.h:10905`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### NtGetTickCount (function) `__forceinline ULONG NtGetTickCount()`
- Defined: `payloads/Demon/include/common/Native.h:10907`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### A_SHAFinal (function) `void NTAPI A_SHAFinal( PSHA_CTX Context, PULONG Result );`
- Defined: `payloads/Demon/include/common/Native.h:21318`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### RtlInitString (function) `void NTAPI RtlInitString( PSTRING DestinationString, PCSZ SourceString );`
- Defined: `payloads/Demon/include/common/Native.h:21963`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### RtlUpdateClonedCriticalSection (function) `void NTAPI RtlUpdateClonedCriticalSection( PRTL_CRITICAL_SECTION CriticalSection );`
- Defined: `payloads/Demon/include/common/Native.h:22100`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### LdrInitShimEngineDynamic (function) `int NTAPI LdrInitShimEngineDynamic( PVOID pShimEngineModule);`
- Defined: `payloads/Demon/include/common/Native.h:22118`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### ZwWow64GetCurrentProcessorNumberEx (function) `void NTAPI ZwWow64GetCurrentProcessorNumberEx( OUT PPROCESSOR_NUMBER ProcNumber );`
- Defined: `payloads/Demon/include/common/Native.h:22202`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### ZwWow64CsrCaptureMessageBuffer (function) `void NTAPI ZwWow64CsrCaptureMessageBuffer( _Inout_ PCSR_CAPTURE_HEADER CaptureBuffer, IN PVOID Buffer OPTIONAL, IN ULONG Length, OUT PVOID *CapturedBuffer );`
- Defined: `payloads/Demon/include/common/Native.h:22224`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### ZwWow64CsrCaptureMessageString (function) `void NTAPI ZwWow64CsrCaptureMessageString( _Inout_ PCSR_CAPTURE_HEADER CaptureBuffer, IN PCSTR String, IN ULONG Length, IN ULONG MaximumLength, OUT PSTRING CapturedString );`
- Defined: `payloads/Demon/include/common/Native.h:22233`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### ZwWow64CsrFreeCaptureBuffer (function) `void NTAPI ZwWow64CsrFreeCaptureBuffer( IN PCSR_CAPTURE_HEADER CaptureBuffer );`
- Defined: `payloads/Demon/include/common/Native.h:22254`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### wcslen (function) `IMPORT_FN size_t __cdecl wcslen(const wchar_t *);`
- Defined: `payloads/Demon/include/common/Native.h:22538`
- Doc: readded 4 jan 2012 win64 mode does not need this for using this routines ntdllp.lib is required if !defined(_M_X64)
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### wcscat (function) `IMPORT_FN wchar_t * __cdecl wcscat(wchar_t *dst, const wchar_t *src);`
- Defined: `payloads/Demon/include/common/Native.h:22539`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### wcscmp (function) `IMPORT_FN int __cdecl wcscmp(const wchar_t *src, const wchar_t *dst);`
- Defined: `payloads/Demon/include/common/Native.h:22540`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### _wcsicmp (function) `IMPORT_FN int __cdecl _wcsicmp(const wchar_t *, const wchar_t *);`
- Defined: `payloads/Demon/include/common/Native.h:22541`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### _wcsnicmp (function) `IMPORT_FN int __cdecl _wcsnicmp(const wchar_t *, const wchar_t *, size_t);`
- Defined: `payloads/Demon/include/common/Native.h:22542`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### _wcslwr (function) `IMPORT_FN wchar_t * __cdecl _wcslwr(wchar_t *);`
- Defined: `payloads/Demon/include/common/Native.h:22543`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### _wcsupr (function) `IMPORT_FN wchar_t * __cdecl _wcsupr(wchar_t *);`
- Defined: `payloads/Demon/include/common/Native.h:22544`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### wcschr (function) `IMPORT_FN wchar_t * __cdecl wcschr(const wchar_t *string, wchar_t ch);`
- Defined: `payloads/Demon/include/common/Native.h:22545`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### wcscpy (function) `IMPORT_FN wchar_t * __cdecl wcscpy(wchar_t *dst, const wchar_t *src);`
- Defined: `payloads/Demon/include/common/Native.h:22546`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### wcsncat (function) `IMPORT_FN wchar_t * __cdecl wcsncat(wchar_t *front, const wchar_t *back, size_t count);`
- Defined: `payloads/Demon/include/common/Native.h:22547`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

### wcsncpy (function) `IMPORT_FN wchar_t * __cdecl wcsncpy(wchar_t *dest, const wchar_t *source, size_t count);`
- Defined: `payloads/Demon/include/common/Native.h:22548`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`

## payloads/Demon/include/core/CoffeeLdr.h

### thread (function) `* CoffeeLdr * Simply executes an object file in the current thread (blocking) * @param EntryName * @param CoffeeData * @param ArgData * @param ArgSize * @param RequestID * @return */ VOID CoffeeLdr( P`
- Defined: `payloads/Demon/include/core/CoffeeLdr.h:118`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/src/core/CoffeeLdr.c`, `payloads/Demon/src/core/Command.c`

## payloads/Demon/include/core/Kerberos.h

### GetLUID (function) `LUID* GetLUID( HANDLE hToken );`
- Defined: `payloads/Demon/include/core/Kerberos.h:203`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/src/core/Command.c`, `payloads/Demon/src/core/Kerberos.c`

## payloads/Demon/include/core/Socket.h

### HTTP (function) `* This is needed for Socks5 and HTTP(S) agents. * @return TRUE or FALSE */ BOOL InitWSA( VOID );`
- Defined: `payloads/Demon/include/core/Socket.h:66`
- Imported by: `payloads/Demon/include/Demon.h`

## payloads/Demon/include/core/Spoof.h

### Spoof (function) `static ULONG_PTR Spoof();`
- Defined: `payloads/Demon/include/core/Spoof.h:17`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/src/core/Spoof.c`

## payloads/Demon/include/core/Win32.h

### __attribute__ (function) `typedef struct __attribute__((packed))`
- Defined: `payloads/Demon/include/core/Win32.h:101`
- Depends on: `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/Syscalls.h`
- Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Clr.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/TransportHttp.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/src/Demon.c`, `payloads/Demon/src/core/CoffeeLdr.c`, `payloads/Demon/src/core/Kerberos.c`, `payloads/Demon/src/core/Obf.c`, `payloads/Demon/src/core/ObjectApi.c`, `payloads/Demon/src/core/Syscalls.c`, `payloads/Demon/src/core/Thread.c`, `payloads/Demon/src/core/Token.c`, `payloads/Demon/src/core/Win32.c`, `payloads/Demon/src/inject/Inject.c`

## payloads/Demon/include/crypt/AesCrypt.h

### AesInit (function) `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv);`
- Defined: `payloads/Demon/include/crypt/AesCrypt.h:22`
- Imported by: `payloads/Demon/src/core/Package.c`, `payloads/Demon/src/core/Parser.c`, `payloads/Demon/src/core/Transport.c`, `payloads/Demon/src/crypt/AesCrypt.c`

### AesXCryptBuffer (function) `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length);`
- Defined: `payloads/Demon/include/crypt/AesCrypt.h:23`
- Imported by: `payloads/Demon/src/core/Package.c`, `payloads/Demon/src/core/Parser.c`, `payloads/Demon/src/core/Transport.c`, `payloads/Demon/src/crypt/AesCrypt.c`

## payloads/Demon/scripts/hash_func.py

### hash_string (function) `def hash_string(string)`
- Defined: `payloads/Demon/scripts/hash_func.py:7`

### hash_coffapi (function) `def hash_coffapi(string)`
- Defined: `payloads/Demon/scripts/hash_func.py:18`

## payloads/Demon/src/Demon.c

### DemonMain (function) `VOID DemonMain( PVOID ModuleInst, PKAYN_ARGS KArgs )`
- Defined: `payloads/Demon/src/Demon.c:34`
- Doc: In DemonMain it should go as followed:  1. Initialize pointer, modules and win32 api 2. Initialize metadata 3. Parse con
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Runtime.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`

### DemonRoutine (function) `_Noreturn
VOID DemonRoutine()`
- Defined: `payloads/Demon/src/Demon.c:64`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Runtime.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`

### DemonMetaData (function) `VOID DemonMetaData( PPACKAGE* MetaData, BOOL Header )`
- Defined: `payloads/Demon/src/Demon.c:95`
- Doc: } if ( Instance->Session.Connected ) { /* Enter tasking routine CommandDispatcher(); } /* Sleep for a while (with encryp
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Runtime.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`

### DemonInit (function) `VOID DemonInit( PVOID ModuleInst, PKAYN_ARGS KArgs )`
- Defined: `payloads/Demon/src/Demon.c:267`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Runtime.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `PUTS( "TRANSPORT_HTTP" )
#endif

#ifdef TRANSPORT_SMB
    PUTS( "TRANSPORT_SMB" )
#endif


    /*...`
- Defined: `payloads/Demon/src/Demon.c:290`
- Doc: ifdef TRANSPORT_HTTP
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Runtime.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`

### PRINTF (function) `PRINTF( "Instance DemonID => %x\n", Instance->Session.AgentID )
}

VOID DemonConfig()`
- Defined: `payloads/Demon/src/Demon.c:570`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Runtime.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`

### PRINTF (function) `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...`
- Defined: `payloads/Demon/src/Demon.c:645`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Runtime.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`

### PRINTF (function) `PRINTF( " - %ls:%ld\n", Buffer, Temp )

        /* if our host address is longer than 0 then lets...`
- Defined: `payloads/Demon/src/Demon.c:673`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Runtime.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`

### PRINTF (function) `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...`
- Defined: `payloads/Demon/src/Demon.c:775`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Runtime.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`

## payloads/Demon/src/asm/Spoof.x64.asm

### Spoof (function)
- Defined: `payloads/Demon/src/asm/Spoof.x64.asm:8`

### fixup (function)
- Defined: `payloads/Demon/src/asm/Spoof.x64.asm:22`

## payloads/Demon/src/asm/Spoof.x86.asm

### _Spoof (function)
- Defined: `payloads/Demon/src/asm/Spoof.x86.asm:8`

## payloads/Demon/src/core/CoffeeLdr.c

### VehDebugger (function) `LONG WINAPI VehDebugger( PEXCEPTION_POINTERS Exception )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:32`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

### SymbolIncludesLibrary (function) `BOOL SymbolIncludesLibrary( LPSTR Symbol )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:64`
- Doc: check if the symbol is on the form: __imp_LIBNAME$FUNCNAME
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

### SymbolIsImport (function) `BOOL SymbolIsImport( LPSTR Symbol )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:81`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

### CoffeeProcessSymbol (function) `BOOL CoffeeProcessSymbol( PCOFFEE Coffee, LPSTR SymbolName, UINT16 SymbolType, PVOID* pFuncAddr )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:87`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

### CoffeeFunction (function) `VOID CoffeeFunction( PVOID Address, PVOID Argument, SIZE_T Size )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:242`
- Doc: This is our function where we can control/get the return address of it to use it in case of a Veh exception
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

### PUTS (function) `PUTS( "Finished" )
}

BOOL CoffeeExecuteFunction( PCOFFEE Coffee, PCHAR Function, PVOID Argument,...`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:251`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

### CoffeeCleanup (function) `VOID CoffeeCleanup( PCOFFEE Coffee )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:394`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

### CoffeeProcessSections (function) `BOOL CoffeeProcessSections( PCOFFEE Coffee )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:423`
- Doc: Process sections relocation and symbols
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

### CoffeeGetFunMapSize (function) `SIZE_T CoffeeGetFunMapSize( PCOFFEE Coffee )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:602`
- Doc: calculate how many __imp_* function there are
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

### RemoveCoffeeFromInstance (function) `VOID RemoveCoffeeFromInstance( PCOFFEE Coffee )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:642`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

### PUTS (function) `PUTS( "Coffe entry was not found" )
}

VOID CoffeeLdr( PCHAR EntryName, PVOID CoffeeData, PVOID A...`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:669`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

### PRINTF (function) `PRINTF( "[EntryName: %s] [CoffeeData: %p] [ArgData: %p] [ArgSize: %ld]\n", EntryName, CoffeeData,...`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:678`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

### CoffeeRunnerThread (function) `VOID CoffeeRunnerThread( PCOFFEE_PARAMS Param )`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:799`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

### CoffeeRunner (function) `VOID CoffeeRunner( PCHAR EntryName, DWORD EntryNameSize, PVOID CoffeeData, SIZE_T CoffeeDataSize,...`
- Defined: `payloads/Demon/src/core/CoffeeLdr.c:821`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`

## payloads/Demon/src/core/Command.c

### CommandDispatcher (function) `VOID CommandDispatcher( VOID )`
- Defined: `payloads/Demon/src/core/Command.c:48`
- Doc: TODO: rewrite this part and move it into the Demon.c file
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PRINTF (function) `PRINTF( "Task => RequestID:[%d : %x] CommandID:[%d : %x] TaskBuffer:[%x : %d]\n", RequestID, Requ...`
- Defined: `payloads/Demon/src/core/Command.c:107`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `PUTS( "Out of while loop" )
}

VOID CommandCheckin( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:160`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandSleep (function) `VOID CommandSleep( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:174`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandJob (function) `VOID CommandJob( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:188`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandProc (function) `VOID CommandProc( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:263`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_PROC_MODULES: PUTS( "Proc::Modules" )`
- Defined: `payloads/Demon/src/core/Command.c:272`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_PROC_GREP: PUTS("Proc::Grep")`
- Defined: `payloads/Demon/src/core/Command.c:337`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_PROC_CREATE: PUTS( "Proc::Create" )`
- Defined: `payloads/Demon/src/core/Command.c:423`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_PROC_MEMORY: PUTS( "Proc::Memory" )`
- Defined: `payloads/Demon/src/core/Command.c:468`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_PROC_KILL: PUTS( "Proc::Kill" )`
- Defined: `payloads/Demon/src/core/Command.c:528`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandProcList (function) `VOID CommandProcList(
    IN PPARSER Parser
)`
- Defined: `payloads/Demon/src/core/Command.c:562`
- Doc: ! get current list of running processes and sends it back to the server.  TODO: refactor this.  @param Parser
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PACKAGE_ERROR_NTSTATUS (function) `PACKAGE_ERROR_NTSTATUS( NtStatus )
    }
}

VOID CommandFS( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:671`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_FS_DIR: PUTS( "FS::Dir" )`
- Defined: `payloads/Demon/src/core/Command.c:684`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_FS_DOWNLOAD: PUTS( "FS::Download" )`
- Defined: `payloads/Demon/src/core/Command.c:794`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PRINTF (function) `PRINTF( "FilePath.Buffer[%d]: %ls\n", PathSize, FilePath )

            if ( ! Instance->Win32.Ge...`
- Defined: `payloads/Demon/src/core/Command.c:824`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `CleanupDownload:
            PUTS( "CleanupDownload" )

            if ( FileName.Buffer )`
- Defined: `payloads/Demon/src/core/Command.c:867`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_FS_UPLOAD: PUTS( "FS::Upload" )`
- Defined: `payloads/Demon/src/core/Command.c:882`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_FS_CD: PUTS( "FS::Cd" )`
- Defined: `payloads/Demon/src/core/Command.c:949`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_FS_REMOVE: PUTS( "FS::Remove" )`
- Defined: `payloads/Demon/src/core/Command.c:964`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_FS_MKDIR: PUTS( "FS::Mkdir" )`
- Defined: `payloads/Demon/src/core/Command.c:994`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_FS_COPY: PUTS( "FS::Copy" )`
- Defined: `payloads/Demon/src/core/Command.c:1010`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_FS_MOVE: PUTS( "FS::Move" )`
- Defined: `payloads/Demon/src/core/Command.c:1035`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_FS_GET_PWD: PUTS( "FS::GetPwd" )`
- Defined: `payloads/Demon/src/core/Command.c:1060`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_FS_CAT: PUTS( "FS::Cat" )`
- Defined: `payloads/Demon/src/core/Command.c:1075`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandInlineExecute (function) `VOID CommandInlineExecute( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:1114`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `PUTS( "Use default (from config) CoffeeLdr" )

            if ( Instance->Config.Implant.CoffeeTh...`
- Defined: `payloads/Demon/src/core/Command.c:1181`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandInjectDLL (function) `VOID CommandInjectDLL( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:1203`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandSpawnDLL (function) `VOID CommandSpawnDLL( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:1247`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandInjectShellcode (function) `VOID CommandInjectShellcode(
    IN PPARSER Parser
)`
- Defined: `payloads/Demon/src/core/Command.c:1266`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PRINTF (function) `PRINTF(
        "Injection Args:      \n"
        " - Way     : %d      \n"
        " - Method  :...`
- Defined: `payloads/Demon/src/core/Command.c:1293`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case INJECT_WAY_SPAWN: PUTS( "INJECT_WAY_SPAWN" )`
- Defined: `payloads/Demon/src/core/Command.c:1312`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PRINTF (function) `PRINTF( "Target spawn process: %ls\n", Spawn )

            /* create process */
            if (...`
- Defined: `payloads/Demon/src/core/Command.c:1320`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case INJECT_WAY_INJECT: PUTS( "INJECT_WAY_INJECT" )`
- Defined: `payloads/Demon/src/core/Command.c:1353`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case INJECT_WAY_EXECUTE: PUTS( "INJECT_WAY_EXECUTE" )`
- Defined: `payloads/Demon/src/core/Command.c:1358`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandToken (function) `VOID CommandToken( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:1373`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TOKEN_IMPERSONATE: PUTS( "Token::Impersonate" )`
- Defined: `payloads/Demon/src/core/Command.c:1383`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TOKEN_STEAL: PUTS( "Token::Steal" )`
- Defined: `payloads/Demon/src/core/Command.c:1406`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TOKEN_LIST: PUTS( "Token::List" )`
- Defined: `payloads/Demon/src/core/Command.c:1450`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TOKEN_PRIVSGET_OR_LIST: PUTS( "Token::PrivsGetOrList" )`
- Defined: `payloads/Demon/src/core/Command.c:1477`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TOKEN_MAKE: PUTS( "Token::Make" )`
- Defined: `payloads/Demon/src/core/Command.c:1532`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TOKEN_GET_UID: PUTS( "Token::GetUID" )`
- Defined: `payloads/Demon/src/core/Command.c:1595`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TOKEN_REVERT: PUTS( "Token::Revert" )`
- Defined: `payloads/Demon/src/core/Command.c:1635`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TOKEN_REMOVE: PUTS( "Token::Remove" )`
- Defined: `payloads/Demon/src/core/Command.c:1650`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TOKEN_CLEAR: PUTS( "Token::Clear" )`
- Defined: `payloads/Demon/src/core/Command.c:1660`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TOKEN_FIND_TOKENS: PUTS( "Token::Find" )`
- Defined: `payloads/Demon/src/core/Command.c:1668`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandAssemblyInlineExecute (function) `VOID CommandAssemblyInlineExecute( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:1708`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PRINTF (function) `PRINTF(
            "Parsed Arguments:         \n"
            " - PipeName     [%d]: %ls \n"
   ...`
- Defined: `payloads/Demon/src/core/Command.c:1761`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `PUTS( "Dotnet instance already running." )
    }
}

VOID CommandAssemblyListVersion( PPARSER Pars...`
- Defined: `payloads/Demon/src/core/Command.c:1788`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `else
        PUTS("Failed to load mscoree.dll")


    if ( pClrMetaHost )`
- Defined: `payloads/Demon/src/core/Command.c:1841`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandConfig (function) `VOID CommandConfig( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:1865`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandScreenshot (function) `VOID CommandScreenshot( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:2084`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandNet (function) `VOID CommandNet( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:2109`
- Doc: TODO: The Net module is unstable so fix those issues to work on normal workstation and domain server
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `PUTS( "NetLocalGroupEnum => Success" )
                if ( GroupInfo )`
- Defined: `payloads/Demon/src/core/Command.c:2350`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandPivot (function) `VOID CommandPivot( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:2463`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandTransfer (function) `VOID CommandTransfer( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:2608`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TRANSFER_LIST: PUTS( "Transfer::list" )`
- Defined: `payloads/Demon/src/core/Command.c:2624`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TRANSFER_STOP: PUTS( "Transfer::stop" )`
- Defined: `payloads/Demon/src/core/Command.c:2641`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TRANSFER_RESUME: PUTS( "Transfer::resume" )`
- Defined: `payloads/Demon/src/core/Command.c:2668`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case DEMON_COMMAND_TRANSFER_REMOVE: PUTS( "Transfer::remove" )`
- Defined: `payloads/Demon/src/core/Command.c:2696`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandSocket (function) `VOID CommandSocket( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:2739`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case SOCKET_COMMAND_RPORTFWD_ADD: PUTS( "Socket::RPortFwdAdd" )`
- Defined: `payloads/Demon/src/core/Command.c:2751`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case SOCKET_COMMAND_RPORTFWD_LIST: PUTS( "Socket::RPortFwdList" )`
- Defined: `payloads/Demon/src/core/Command.c:2786`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case SOCKET_COMMAND_RPORTFWD_REMOVE: PUTS( "Socket::RPortFwdRemove" )`
- Defined: `payloads/Demon/src/core/Command.c:2819`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case SOCKET_COMMAND_RPORTFWD_CLEAR: PUTS( "Socket::RPortFwdClear" )`
- Defined: `payloads/Demon/src/core/Command.c:2850`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case SOCKET_COMMAND_SOCKSPROXY_ADD: PUTS( "Socket::SocksProxyAdd" )`
- Defined: `payloads/Demon/src/core/Command.c:2871`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case SOCKET_COMMAND_WRITE: PUTS( "Socket::Write" )`
- Defined: `payloads/Demon/src/core/Command.c:2878`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case SOCKET_COMMAND_CONNECT: PUTS( "Socket::Connect" )`
- Defined: `payloads/Demon/src/core/Command.c:2942`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PRINTF (function) `PRINTF( "Socket ID: %x\n", ScId )

            /* check if address is not 0 */
            if ( I...`
- Defined: `payloads/Demon/src/core/Command.c:2997`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case SOCKET_COMMAND_CLOSE: PUTS( "Socket::Close" )`
- Defined: `payloads/Demon/src/core/Command.c:3036`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandKerberos (function) `VOID CommandKerberos(
    IN PPARSER Parser
)`
- Defined: `payloads/Demon/src/core/Command.c:3077`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case KERBEROS_COMMAND_LUID: PUTS("Kerberos::LUID")`
- Defined: `payloads/Demon/src/core/Command.c:3090`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case KERBEROS_COMMAND_KLIST: PUTS("Kerberos::Klist")`
- Defined: `payloads/Demon/src/core/Command.c:3117`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case KERBEROS_COMMAND_PURGE: PUTS("Kerberos::Purge")`
- Defined: `payloads/Demon/src/core/Command.c:3205`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### PUTS (function) `case KERBEROS_COMMAND_PTT: PUTS("Kerberos::Ptt")`
- Defined: `payloads/Demon/src/core/Command.c:3216`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandMemFile (function) `VOID CommandMemFile( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:3237`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### InWorkingHours (function) `BOOL InWorkingHours( )`
- Defined: `payloads/Demon/src/core/Command.c:3263`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### ReachedKillDate (function) `BOOL ReachedKillDate()`
- Defined: `payloads/Demon/src/core/Command.c:3295`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### KillDate (function) `VOID KillDate( )`
- Defined: `payloads/Demon/src/core/Command.c:3300`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### CommandExit (function) `VOID CommandExit( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Command.c:3315`
- Doc: TODO: rewrite this. disconnect all pivots. kill our threads. release memory and free itself.
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

### Data (function) `* * Data (Open): * [ File Size ] * [ File Name ] * * Data (Write) * [ Chunk Data ] Size + FileChunk * * Data (Close): * [ Reason ] Removed or Finished * */ /* Download Header */ PackageAddInt32( Packa`
- Defined: `payloads/Demon/src/core/Command.c:844`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`

## payloads/Demon/src/core/Dotnet.c

### DotnetExecute (function) `BOOL DotnetExecute( BUFFER Assembly, BUFFER Arguments )`
- Defined: `payloads/Demon/src/core/Dotnet.c:19`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### PUTS (function) `PUTS( "Init HwBp Engine" )
        /* use global engine */
        if ( ! NT_SUCCESS( HwBpEngineI...`
- Defined: `payloads/Demon/src/core/Dotnet.c:101`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### PUTS (function) `PUTS( "HwBp Engine add AmsiScanBuffer bypass" )
            if ( ! NT_SUCCESS( Status = HwBpEngin...`
- Defined: `payloads/Demon/src/core/Dotnet.c:112`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### PUTS (function) `PUTS( "HwBp Engine add NtTraceEvent bypass" )
        if ( ! NT_SUCCESS( HwBpEngineAdd( NULL, Thr...`
- Defined: `payloads/Demon/src/core/Dotnet.c:120`
- Doc: ThreadId = U_PTR( Instance->Teb->ClientId.UniqueThread ); /* add Amsi bypass if ( AmsiIsLoaded ) { PUTS( "HwBp Engine ad
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### PUTS (function) `PUTS( "CreateDomain..." )
    if ( ( Result = Instance->Dotnet->ICorRuntimeHost->lpVtbl->CreateDo...`
- Defined: `payloads/Demon/src/core/Dotnet.c:148`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### PUTS (function) `PUTS( "QueryInterface..." )
    if ( ( Result = Instance->Dotnet->AppDomainThunk->lpVtbl->QueryIn...`
- Defined: `payloads/Demon/src/core/Dotnet.c:154`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### PRINTF (function) `PRINTF("SafeArrayUnaccessData Failed: %x\n", Result )
        PACKAGE_ERROR_WIN32
    }

    PUTS...`
- Defined: `payloads/Demon/src/core/Dotnet.c:169`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### PUTS (function) `PUTS( "Assembly EntryPoint..." )
    if ( ( Result = Instance->Dotnet->Assembly->lpVtbl->EntryPoi...`
- Defined: `payloads/Demon/src/core/Dotnet.c:179`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### PUTS (function) `PUTS( "Creating events..." )
    if ( NT_SUCCESS( Instance->Win32.NtCreateEvent( &Instance->Dotne...`
- Defined: `payloads/Demon/src/core/Dotnet.c:237`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### PUTS (function) `PUTS( "Resume Thread..." )
                if ( NT_SUCCESS( Instance->Win32.NtAlertResumeThread( ...`
- Defined: `payloads/Demon/src/core/Dotnet.c:286`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### DotnetPushPipe (function) `VOID DotnetPushPipe()`
- Defined: `payloads/Demon/src/core/Dotnet.c:312`
- Doc: } else PUTS( "NtAlertResumeThread failed" ) } else PUTS( "NtGetThreadContext failed" ) } else PUTS( "NtCreateThreadEx fa
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### DotnetPush (function) `VOID DotnetPush()`
- Defined: `payloads/Demon/src/core/Dotnet.c:347`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### PRINTF (function) `PRINTF( "Instance->Dotnet->Invoked: %s\n", Instance->Dotnet->Invoked ? "TRUE" : "FALSE" )
    if ...`
- Defined: `payloads/Demon/src/core/Dotnet.c:352`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### DotnetClose (function) `VOID DotnetClose()`
- Defined: `payloads/Demon/src/core/Dotnet.c:379`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### PUTS (function) `PUTS( "Free Output" )
    if ( Instance->Dotnet->Output.Buffer )`
- Defined: `payloads/Demon/src/core/Dotnet.c:428`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### PUTS (function) `PUTS( "Unload and free CLR" )
    if ( Instance->Dotnet->MethodArgs )`
- Defined: `payloads/Demon/src/core/Dotnet.c:436`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### FindVersion (function) `BOOL FindVersion( PVOID Assembly, DWORD length )`
- Defined: `payloads/Demon/src/core/Dotnet.c:501`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### ClrCreateInstance (function) `DWORD ClrCreateInstance( LPCWSTR dotNetVersion, PICLRMetaHost *ppClrMetaHost, PICLRRuntimeInfo *p...`
- Defined: `payloads/Demon/src/core/Dotnet.c:524`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

## payloads/Demon/src/core/Download.c

### DownloadAdd (function) `PDOWNLOAD_DATA DownloadAdd( HANDLE hFile, LONGLONG MaxSize )`
- Defined: `payloads/Demon/src/core/Download.c:6`
- Doc: #include <Demon.h> #include <core/MiniStd.h> /* Add file to linked list with type (upload/download)
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### DownloadGet (function) `PDOWNLOAD_DATA DownloadGet( DWORD FileID )`
- Defined: `payloads/Demon/src/core/Download.c:27`
- Doc: Download->Size      = MaxSize; Download->State     = DOWNLOAD_STATE_RUNNING; Download->Next      = Instance->Downloads; 
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### DownloadFree (function) `VOID DownloadFree( PDOWNLOAD_DATA Download )`
- Defined: `payloads/Demon/src/core/Download.c:41`
- Doc: PDOWNLOAD_DATA DownloadGet( DWORD FileID ) { PDOWNLOAD_DATA Download = NULL; for ( Download = Instance->Downloads; Downl
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### DownloadRemove (function) `BOOL DownloadRemove( DWORD FileID )`
- Defined: `payloads/Demon/src/core/Download.c:56`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### DownloadPush (function) `VOID DownloadPush()`
- Defined: `payloads/Demon/src/core/Download.c:94`
- Doc: /* return that we succeeded. Success = TRUE; break; } Last     = Download; Download = Download->Next; } return Success; 
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### PRINTF (function) `PRINTF( "Allocated memory for DownloadChunk. Buffer:[%p] Size:[%d]\n", Instance->DownloadChunk.Bu...`
- Defined: `payloads/Demon/src/core/Download.c:129`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### MemFileIsNew (function) `BOOL MemFileIsNew( ULONG32 ID )`
- Defined: `payloads/Demon/src/core/Download.c:238`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### NewMemFile (function) `PMEM_FILE NewMemFile( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
- Defined: `payloads/Demon/src/core/Download.c:254`
- Doc: PMEM_FILE MemFile = Instance->MemFiles; while ( MemFile ) { if ( MemFile->ID == ID ) return FALSE; MemFile = MemFile->Ne
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### GetMemFile (function) `PMEM_FILE GetMemFile( ULONG32 ID )`
- Defined: `payloads/Demon/src/core/Download.c:287`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### ProcessMemFileChunk (function) `PMEM_FILE ProcessMemFileChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
- Defined: `payloads/Demon/src/core/Download.c:302`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### MemFileReadChunk (function) `PMEM_FILE MemFileReadChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
- Defined: `payloads/Demon/src/core/Download.c:318`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### MemFileFree (function) `VOID MemFileFree( PMEM_FILE MemFile )`
- Defined: `payloads/Demon/src/core/Download.c:339`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### RemoveMemFile (function) `BOOL RemoveMemFile( ULONG32 ID )`
- Defined: `payloads/Demon/src/core/Download.c:355`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

## payloads/Demon/src/core/HwBpEngine.c

### HwBpEngineInit (function) `NTSTATUS HwBpEngineInit(
    OUT PHWBP_ENGINE Engine,
    IN  PVOID        Handler
)`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:18`
- Doc: ! Init Hardware breakpoint engine by registering a Vectored exception handler @param Engine   if empty global handler go
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`

### HwBpEngineSetBp (function) `NTSTATUS HwBpEngineSetBp(
    IN DWORD Tid,
    IN PVOID Address,
    IN BYTE  Position,
    IN B...`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:61`
- Doc: ! Set hardware breakpoint on specified address @param Tib @param Address @param Position @param Add @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`

### PRINTF (function) `PRINTF(
                "Dr Registers:  \n"
                "- Dr0[%d]: %p  \n"
                "...`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:116`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`

### HwBpEngineAdd (function) `NTSTATUS HwBpEngineAdd(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID        ...`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:152`
- Doc: ! Set an hardware breakpoint to an address and adds it to the engine breakpoints list linked @param Engine @param Thread
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`

### PRINTF (function) `PRINTF( "Engine:[%p] Tid:[%d] Address:[%p] Function:[%p] Position:[%d]\n", Engine, Tid, Address, ...`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:162`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`

### HwBpEngineRemove (function) `NTSTATUS HwBpEngineRemove(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID     ...`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:209`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`

### HwBpEngineDestroy (function) `NTSTATUS HwBpEngineDestroy(
    IN PHWBP_ENGINE Engine
)`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:261`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`

### ExceptionHandler (function) `LONG ExceptionHandler(
    _Inout_ PEXCEPTION_POINTERS Exception
)`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:320`
- Doc: ! Global exception handler @param Exception @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`

### PRINTF (function) `PRINTF( "Found exception handler: %s\n", Found ? "TRUE" : "FALSE" )
        if ( Found )`
- Defined: `payloads/Demon/src/core/HwBpEngine.c:355`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`

## payloads/Demon/src/core/HwBpExceptions.c

### HwBpExAmsiScanBuffer (function) `VOID HwBpExAmsiScanBuffer(
    _Inout_ PEXCEPTION_POINTERS Exception
)`
- Defined: `payloads/Demon/src/core/HwBpExceptions.c:6`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpExceptions.h`

### HwBpExNtTraceEvent (function) `VOID HwBpExNtTraceEvent(
    _Inout_ PEXCEPTION_POINTERS Exception
)`
- Defined: `payloads/Demon/src/core/HwBpExceptions.c:23`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpExceptions.h`

## payloads/Demon/src/core/Jobs.c

### JobAdd (function) `VOID JobAdd( UINT32 RequestID, DWORD JobID, SHORT Type, SHORT State, HANDLE Handle, PVOID Data )`
- Defined: `payloads/Demon/src/core/Jobs.c:17`
- Doc: ! JobAdd Adds a job to the job linked list @param JobID @param Type type of job: thread or process @param State current 
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`

### JobCheckList (function) `VOID JobCheckList()`
- Defined: `payloads/Demon/src/core/Jobs.c:63`
- Doc: ! Check if all jobs are still running and exists @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`

### JobSuspend (function) `BOOL JobSuspend( DWORD JobID )`
- Defined: `payloads/Demon/src/core/Jobs.c:184`
- Doc: ! JobSuspend Suspends the specified job @param JobID @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`

### PRINTF (function) `PRINTF( "Found Job ID: %d", JobID )

            if ( JobList->Type == JOB_TYPE_THREAD )`
- Defined: `payloads/Demon/src/core/Jobs.c:192`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`

### JobResume (function) `BOOL JobResume( DWORD JobID )`
- Defined: `payloads/Demon/src/core/Jobs.c:230`
- Doc: ! JobSuspend Suspends the specified job @param JobID @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`

### PRINTF (function) `PRINTF( "Found Job ID: %d", JobID )

            if ( JobList->Type == JOB_TYPE_THREAD )`
- Defined: `payloads/Demon/src/core/Jobs.c:238`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`

### JobKill (function) `BOOL JobKill( DWORD JobID )`
- Defined: `payloads/Demon/src/core/Jobs.c:277`
- Doc: ! JobKill Kills and remove the specified job @param JobID @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`

### PRINTF (function) `PRINTF( "Found Job ID: %d\n", JobID )

            switch ( JobList->Type )`
- Defined: `payloads/Demon/src/core/Jobs.c:287`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`

### PUTS (function) `PUTS( "Kill using handle" )

                            if ( ! NT_SUCCESS( NtStatus = Instance->...`
- Defined: `payloads/Demon/src/core/Jobs.c:300`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`

### JobRemove (function) `VOID JobRemove( DWORD JobID )`
- Defined: `payloads/Demon/src/core/Jobs.c:383`
- Doc: ! JobRemove Remove the specified job @param ThreadID @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Jobs.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`

## payloads/Demon/src/core/Kerberos.c

### IsHighIntegrity (function) `BOOL IsHighIntegrity(HANDLE TokenHandle)`
- Defined: `payloads/Demon/src/core/Kerberos.c:8`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### GetProcessIdByName (function) `DWORD GetProcessIdByName(WCHAR* processName)`
- Defined: `payloads/Demon/src/core/Kerberos.c:29`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### ElevateToSystem (function) `BOOL ElevateToSystem()`
- Defined: `payloads/Demon/src/core/Kerberos.c:61`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### IsSystem (function) `BOOL IsSystem( HANDLE TokenHandle )`
- Defined: `payloads/Demon/src/core/Kerberos.c:131`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### GetLsaHandle (function) `NTSTATUS GetLsaHandle( HANDLE hToken, BOOL highIntegrity, PHANDLE hLsa )`
- Defined: `payloads/Demon/src/core/Kerberos.c:155`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### GetLogonSessionData (function) `NTSTATUS GetLogonSessionData( LUID luid, PLOGON_SESSION_DATA* data )`
- Defined: `payloads/Demon/src/core/Kerberos.c:218`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### ExtractTicket (function) `VOID ExtractTicket( HANDLE hLsa, ULONG authPackage, LUID luid, UNICODE_STRING targetName, PUCHAR*...`
- Defined: `payloads/Demon/src/core/Kerberos.c:283`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### CopySessionInfo (function) `VOID CopySessionInfo( PSESSION_INFORMATION Session, PSECURITY_LOGON_SESSION_DATA Data )`
- Defined: `payloads/Demon/src/core/Kerberos.c:337`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### CopyTicketInfo (function) `VOID CopyTicketInfo( PTICKET_INFORMATION TicketInfo, PKERB_TICKET_CACHE_INFO_EX Data )`
- Defined: `payloads/Demon/src/core/Kerberos.c:371`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### Ptt (function) `BOOL Ptt( HANDLE hToken, PBYTE Ticket, DWORD TicketSize, LUID luid )`
- Defined: `payloads/Demon/src/core/Kerberos.c:399`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### Purge (function) `BOOL Purge( HANDLE hToken, LUID luid )`
- Defined: `payloads/Demon/src/core/Kerberos.c:494`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### Klist (function) `PSESSION_INFORMATION Klist( HANDLE hToken, LUID luid )`
- Defined: `payloads/Demon/src/core/Kerberos.c:585`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### GetLUID (function) `LUID* GetLUID( HANDLE hToken )`
- Defined: `payloads/Demon/src/core/Kerberos.c:752`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Memory.c

### MmHeapAlloc (function) `PVOID MmHeapAlloc(
    _In_ ULONG Length
)`
- Defined: `payloads/Demon/src/core/Memory.c:15`
- Doc: ! @brief allocate memory on the heap  @param Length size of memory to allocate  @return allocated buffer pointer on the 
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`

### MmHeapReAlloc (function) `PVOID MmHeapReAlloc(
    _In_ PVOID Memory,
    _In_ ULONG Length
)`
- Defined: `payloads/Demon/src/core/Memory.c:31`
- Doc: ! @brief allocate memory on the heap  @param Length size of memory to reallocate  @return allocated buffer pointer on th
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`

### MmHeapFree (function) `BOOL MmHeapFree(
    _In_ PVOID Memory
)`
- Defined: `payloads/Demon/src/core/Memory.c:48`
- Doc: ! @brief free memory on the heap  @param Memory memory to free  @return if successfully freed memory on the heap
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`

### MmVirtualAlloc (function) `PVOID MmVirtualAlloc(
    IN DX_MEMORY Methode,
    IN HANDLE    Process,
    IN SIZE_T    Size,
...`
- Defined: `payloads/Demon/src/core/Memory.c:62`
- Doc: ! Allocates virtual memory @param Method @param Process @param Size @param Protect @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`

### PUTS (function) `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )`
- Defined: `payloads/Demon/src/core/Memory.c:79`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`

### MmVirtualProtect (function) `BOOL MmVirtualProtect(
    IN DX_MEMORY Method,
    IN HANDLE    Process,
    IN PVOID     Memory...`
- Defined: `payloads/Demon/src/core/Memory.c:133`
- Doc: ! Changes the protection of a virtual memory. @param Method @param Process @param Memory @param Size @param Protect @ret
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`

### PUTS (function) `case DX_MEM_DEFAULT: PUTS( "DX_MEM_DEFAULT" )`
- Defined: `payloads/Demon/src/core/Memory.c:147`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`

### MmVirtualWrite (function) `BOOL MmVirtualWrite(
    IN  HANDLE Process,
    OUT PVOID  Memory,
    IN  PVOID  Buffer,
    IN...`
- Defined: `payloads/Demon/src/core/Memory.c:189`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`

### MmVirtualFree (function) `BOOL MmVirtualFree(
    IN HANDLE Process,
    IN PVOID  Memory
)`
- Defined: `payloads/Demon/src/core/Memory.c:209`
- Doc: ! Frees virtual memory @param Process @param Memory @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`

### MmGadgetFind (function) `PVOID MmGadgetFind(
    _In_ PVOID  Memory,
    _In_ SIZE_T Length,
    _In_ PVOID  PatternBuffer...`
- Defined: `payloads/Demon/src/core/Memory.c:240`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`

### FreeReflectiveLoader (function) `BOOL FreeReflectiveLoader(
    IN PVOID BaseAddress
)`
- Defined: `payloads/Demon/src/core/Memory.c:269`
- Doc: ! Frees the reflective loader @param BaseAddress @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`

## payloads/Demon/src/core/MiniStd.c

### StringCompareA (function) `INT StringCompareA( LPCSTR String1, LPCSTR String2 )`
- Defined: `payloads/Demon/src/core/MiniStd.c:9`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### StringCompareW (function) `INT StringCompareW( LPWSTR String1, LPWSTR String2 )`
- Defined: `payloads/Demon/src/core/MiniStd.c:21`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### StringNCompareW (function) `INT StringNCompareW( LPWSTR String1, LPWSTR String2, INT Length )`
- Defined: `payloads/Demon/src/core/MiniStd.c:33`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### ToLowerCaseW (function) `WCHAR ToLowerCaseW( WCHAR C )`
- Defined: `payloads/Demon/src/core/MiniStd.c:48`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### StringCompareIW (function) `INT StringCompareIW( LPWSTR String1, LPWSTR String2 )`
- Defined: `payloads/Demon/src/core/MiniStd.c:53`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### StringNCompareIW (function) `INT StringNCompareIW( LPWSTR String1, LPWSTR String2, INT Length )`
- Defined: `payloads/Demon/src/core/MiniStd.c:65`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### EndsWithIW (function) `BOOL EndsWithIW( LPWSTR String, LPWSTR Ending )`
- Defined: `payloads/Demon/src/core/MiniStd.c:80`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### HashStringA (function) `DWORD HashStringA( PCHAR String )`
- Defined: `payloads/Demon/src/core/MiniStd.c:100`
- Doc: return FALSE; Length1 = StringLengthW( String ); Length2 = StringLengthW( Ending ); if ( Length1 < Length2 ) return FALS
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### StringCopyA (function) `PCHAR StringCopyA(PCHAR String1, PCHAR String2)`
- Defined: `payloads/Demon/src/core/MiniStd.c:112`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### StringCopyW (function) `PWCHAR StringCopyW(PWCHAR String1, PWCHAR String2)`
- Defined: `payloads/Demon/src/core/MiniStd.c:121`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### StringLengthA (function) `SIZE_T StringLengthA(LPCSTR String)`
- Defined: `payloads/Demon/src/core/MiniStd.c:130`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### StringLengthW (function) `SIZE_T StringLengthW(LPCWSTR String)`
- Defined: `payloads/Demon/src/core/MiniStd.c:142`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### StringConcatA (function) `PCHAR StringConcatA(PCHAR String, PCHAR String2)`
- Defined: `payloads/Demon/src/core/MiniStd.c:151`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### StringConcatW (function) `PWCHAR StringConcatW(PWCHAR String, PWCHAR String2)`
- Defined: `payloads/Demon/src/core/MiniStd.c:158`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### WcsStr (function) `LPWSTR WcsStr( PWCHAR String, PWCHAR String2 )`
- Defined: `payloads/Demon/src/core/MiniStd.c:165`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### WcsIStr (function) `LPWSTR WcsIStr( PWCHAR String, PWCHAR String2 )`
- Defined: `payloads/Demon/src/core/MiniStd.c:185`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### MemCompare (function) `INT MemCompare( PVOID s1, PVOID s2, INT len)`
- Defined: `payloads/Demon/src/core/MiniStd.c:205`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### WCharStringToCharString (function) `SIZE_T WCharStringToCharString(PCHAR Destination, PWCHAR Source, SIZE_T MaximumAllowed)`
- Defined: `payloads/Demon/src/core/MiniStd.c:229`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### CharStringToWCharString (function) `SIZE_T CharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )`
- Defined: `payloads/Demon/src/core/MiniStd.c:242`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### StringTokenA (function) `PCHAR StringTokenA(PCHAR String, CONST PCHAR Delim)`
- Defined: `payloads/Demon/src/core/MiniStd.c:255`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### GetSystemFileTime (function) `UINT64 GetSystemFileTime( )`
- Defined: `payloads/Demon/src/core/MiniStd.c:300`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### HideChar (function) `BYTE NO_INLINE HideChar( BYTE C )`
- Defined: `payloads/Demon/src/core/MiniStd.c:313`
- Doc: UINT64 GetSystemFileTime( ) { FILETIME ft; LARGE_INTEGER li; Instance->Win32.GetSystemTimeAsFileTime(&ft); //returns tic
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

## payloads/Demon/src/core/Obf.c

### FoliageObf (function) `VOID FoliageObf(
    IN PSLEEP_PARAM Param
)`
- Defined: `payloads/Demon/src/core/Obf.c:22`
- Doc: ! @brief foliage is a sleep obfuscation technique that is using APC calls to obfuscate itself in memory  @param Param @r
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`

### PRINTF (function) `PRINTF( "RtlCreateTimerQueue/NtCreateEvent Failed: %lx\n", NtStatus )
    }

LEAVE: /* cleanup */...`
- Defined: `payloads/Demon/src/core/Obf.c:603`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`

### SleepTime (function) `UINT32 SleepTime(
    VOID
)`
- Defined: `payloads/Demon/src/core/Obf.c:650`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`

### SleepObf (function) `VOID SleepObf(
    VOID
)`
- Defined: `payloads/Demon/src/core/Obf.c:714`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/ObjectApi.c

### LdrModulePebString (function) `PVOID LdrModulePebString( PCHAR ModuleString )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:20`
- Doc: Meh some wrapper functions for internal demon GetProcAddress and GetModuleHandleA functions.
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### LdrFunctionAddrString (function) `PVOID LdrFunctionAddrString( PVOID Module, PCHAR Function )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:26`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### LdrFreeLibrary (function) `BOOL LdrFreeLibrary( HMODULE hLibModule )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:32`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### LdrLocalFree (function) `HLOCAL LdrLocalFree( PVOID hMem )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:37`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### swap_endianess (function) `uint32_t swap_endianess(uint32_t indata)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:131`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconDataParse (function) `VOID BeaconDataParse( PDATA parser, PCHAR buffer, INT size )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:143`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconDataInt (function) `INT BeaconDataInt( PDATA parser )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:155`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconDataShort (function) `SHORT BeaconDataShort( datap* parser )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:170`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconDataLength (function) `INT BeaconDataLength( PDATA parser )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:185`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconDataExtract (function) `PCHAR BeaconDataExtract( PDATA parser, PINT size )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:190`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### GetRequestIDForCallingObjectFile (function) `BOOL GetRequestIDForCallingObjectFile( PVOID CoffeeFunctionReturn, PUINT32 RequestID )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:224`
- Doc: This function is called by BeaconPrintf and BeaconOutput. It loops over all the COFFEE structs saved on the Instance obj
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconPrintf (function) `VOID BeaconPrintf( INT Type, PCHAR fmt, ... )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:248`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconOutput (function) `VOID BeaconOutput( INT Type, PCHAR data, INT len )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:305`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconIsAdmin (function) `BOOL BeaconIsAdmin(
    VOID
)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:324`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconFormatAlloc (function) `VOID BeaconFormatAlloc( PFORMAT format, int maxsz )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:343`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconFormatReset (function) `VOID BeaconFormatReset( PFORMAT format )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:354`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconFormatFree (function) `VOID BeaconFormatFree( PFORMAT format )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:361`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconFormatAppend (function) `VOID BeaconFormatAppend( PFORMAT format, char* text, int len )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:377`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconFormatPrintf (function) `VOID BeaconFormatPrintf( PFORMAT format, char* fmt, ... )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:384`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconFormatToString (function) `char* BeaconFormatToString( PFORMAT format, int* size)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:405`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconFormatInt (function) `VOID BeaconFormatInt( PFORMAT format, int value)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:411`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconUseToken (function) `BOOL BeaconUseToken( HANDLE token )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:425`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconGetSpawnTo (function) `VOID BeaconGetSpawnTo( BOOL x86, char* buffer, int length )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:440`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconSpawnTemporaryProcess (function) `BOOL BeaconSpawnTemporaryProcess( BOOL x86, BOOL ignoreToken, STARTUPINFO* sInfo, PROCESS_INFORMA...`
- Defined: `payloads/Demon/src/core/ObjectApi.c:463`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconInjectProcess (function) `VOID BeaconInjectProcess( HANDLE hProc, int pid, char* payload, int p_len, int p_offset, char * a...`
- Defined: `payloads/Demon/src/core/ObjectApi.c:487`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconInjectTemporaryProcess (function) `VOID BeaconInjectTemporaryProcess( PROCESS_INFORMATION* pInfo, char* payload, int p_len, int p_of...`
- Defined: `payloads/Demon/src/core/ObjectApi.c:530`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconCleanupProcess (function) `VOID BeaconCleanupProcess( PROCESS_INFORMATION* pInfo )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:564`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconInformation (function) `VOID BeaconInformation(BEACON_INFO * info)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:578`
- Doc: not implemented
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconAddValue (function) `BOOL BeaconAddValue(const char * key, void * ptr)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:584`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconGetValue (function) `PVOID BeaconGetValue(const char * key)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:633`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconRemoveValue (function) `BOOL BeaconRemoveValue(const char * key)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:656`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconDataStoreGetItem (function) `PDATA_STORE_OBJECT BeaconDataStoreGetItem(SIZE_T index)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:690`
- Doc: not implemented
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconDataStoreProtectItem (function) `VOID BeaconDataStoreProtectItem(SIZE_T index)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:697`
- Doc: not implemented
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconDataStoreUnprotectItem (function) `VOID BeaconDataStoreUnprotectItem(SIZE_T index)`
- Defined: `payloads/Demon/src/core/ObjectApi.c:704`
- Doc: not implemented
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconDataStoreMaxEntries (function) `SIZE_T BeaconDataStoreMaxEntries()`
- Defined: `payloads/Demon/src/core/ObjectApi.c:711`
- Doc: not implemented
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### BeaconGetCustomUserData (function) `PCHAR BeaconGetCustomUserData()`
- Defined: `payloads/Demon/src/core/ObjectApi.c:718`
- Doc: not implemented
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

### toWideChar (function) `BOOL toWideChar( char* src, wchar_t* dst, int max )`
- Defined: `payloads/Demon/src/core/ObjectApi.c:724`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Package.c

### Int64ToBuffer (function) `VOID Int64ToBuffer( PUCHAR Buffer, UINT64 Value )`
- Defined: `payloads/Demon/src/core/Package.c:13`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### Int32ToBuffer (function) `VOID Int32ToBuffer(
    OUT PUCHAR Buffer,
    IN  UINT32 Size
)`
- Defined: `payloads/Demon/src/core/Package.c:39`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageAddInt32 (function) `VOID PackageAddInt32(
    _Inout_ PPACKAGE Package,
    IN     UINT32   Data
)`
- Defined: `payloads/Demon/src/core/Package.c:49`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageAddInt64 (function) `VOID PackageAddInt64( PPACKAGE Package, UINT64 dataInt )`
- Defined: `payloads/Demon/src/core/Package.c:68`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageAddBool (function) `VOID PackageAddBool(
    _Inout_ PPACKAGE Package,
    IN     BOOLEAN  Data
)`
- Defined: `payloads/Demon/src/core/Package.c:85`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageAddPtr (function) `VOID PackageAddPtr( PPACKAGE Package, PVOID pointer )`
- Defined: `payloads/Demon/src/core/Package.c:104`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageAddPad (function) `VOID PackageAddPad( PPACKAGE Package, PCHAR Data, SIZE_T Size )`
- Defined: `payloads/Demon/src/core/Package.c:109`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageAddBytes (function) `VOID PackageAddBytes( PPACKAGE Package, PBYTE Data, SIZE_T Size )`
- Defined: `payloads/Demon/src/core/Package.c:125`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageAddString (function) `VOID PackageAddString( PPACKAGE package, PCHAR data )`
- Defined: `payloads/Demon/src/core/Package.c:147`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageAddWString (function) `VOID PackageAddWString( PPACKAGE package, PWCHAR data )`
- Defined: `payloads/Demon/src/core/Package.c:152`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageCreate (function) `PPACKAGE PackageCreate( UINT32 CommandID )`
- Defined: `payloads/Demon/src/core/Package.c:157`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageCreateWithMetaData (function) `PPACKAGE PackageCreateWithMetaData( UINT32 CommandID )`
- Defined: `payloads/Demon/src/core/Package.c:174`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageCreateWithRequestID (function) `PPACKAGE PackageCreateWithRequestID( UINT32 CommandID, UINT32 RequestID )`
- Defined: `payloads/Demon/src/core/Package.c:187`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageDestroy (function) `VOID PackageDestroy(
    IN PPACKAGE Package
)`
- Defined: `payloads/Demon/src/core/Package.c:196`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageTransmitNow (function) `BOOL PackageTransmitNow(
    _Inout_ PPACKAGE Package,
    OUT    PVOID*   Response,
    OUT    P...`
- Defined: `payloads/Demon/src/core/Package.c:229`
- Doc: used to send the demon's metadata
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PUTS_DONT_SEND (function) `PUTS_DONT_SEND("TransportSend failed!")
        }

        if ( Package->Destroy )`
- Defined: `payloads/Demon/src/core/Package.c:264`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageTransmit (function) `VOID PackageTransmit(
    IN PPACKAGE Package
)`
- Defined: `payloads/Demon/src/core/Package.c:281`
- Doc: don't transmit right away, simply store the package. Will be sent when PackageTransmitAll is called
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageTransmitAll (function) `BOOL PackageTransmitAll(
    OUT    PVOID*   Response,
    OUT    PSIZE_T  Size
)`
- Defined: `payloads/Demon/src/core/Package.c:333`
- Doc: transmit all stored packages in a single request
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### PackageTransmitError (function) `VOID PackageTransmitError(
    IN UINT32 ID,
    IN UINT32 ErrorCode
)`
- Defined: `payloads/Demon/src/core/Package.c:471`
- Depends on: `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

## payloads/Demon/src/core/Parser.c

### ParserNew (function) `VOID ParserNew( PPARSER parser, PBYTE Buffer, UINT32 size )`
- Defined: `payloads/Demon/src/core/Parser.c:7`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### ParserDecrypt (function) `VOID ParserDecrypt( PPARSER parser, PBYTE Key, PBYTE IV )`
- Defined: `payloads/Demon/src/core/Parser.c:21`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### ParserGetInt16 (function) `INT16 ParserGetInt16( PPARSER parser )`
- Defined: `payloads/Demon/src/core/Parser.c:33`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### ParserGetByte (function) `BYTE ParserGetByte( PPARSER parser )`
- Defined: `payloads/Demon/src/core/Parser.c:48`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### ParserGetInt32 (function) `INT ParserGetInt32( PPARSER parser )`
- Defined: `payloads/Demon/src/core/Parser.c:64`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### ParserGetInt64 (function) `INT64 ParserGetInt64( PPARSER parser )`
- Defined: `payloads/Demon/src/core/Parser.c:85`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### ParserGetBool (function) `BOOL ParserGetBool( PPARSER parser )`
- Defined: `payloads/Demon/src/core/Parser.c:106`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### ParserGetBytes (function) `PBYTE ParserGetBytes( PPARSER parser, PUINT32 size )`
- Defined: `payloads/Demon/src/core/Parser.c:127`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### ParserGetString (function) `PCHAR  ParserGetString( PPARSER parser, PUINT32 size )`
- Defined: `payloads/Demon/src/core/Parser.c:158`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### ParserGetWString (function) `PWCHAR  ParserGetWString( PPARSER parser, PUINT32 size )`
- Defined: `payloads/Demon/src/core/Parser.c:163`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### ParserDestroy (function) `VOID ParserDestroy( PPARSER Parser )`
- Defined: `payloads/Demon/src/core/Parser.c:168`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Parser.h`, `payloads/Demon/include/crypt/AesCrypt.h`

## payloads/Demon/src/core/Pivot.c

### PivotAdd (function) `BOOL PivotAdd( BUFFER NamedPipe, PVOID* Output, PDWORD BytesSize )`
- Defined: `payloads/Demon/src/core/Pivot.c:24`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Parser.h`

### PivotGet (function) `PPIVOT_DATA PivotGet( DWORD AgentID )`
- Defined: `payloads/Demon/src/core/Pivot.c:121`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Parser.h`

### PivotRemove (function) `BOOL PivotRemove( DWORD AgentId )`
- Defined: `payloads/Demon/src/core/Pivot.c:139`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Parser.h`

### PivotCount (function) `DWORD PivotCount()`
- Defined: `payloads/Demon/src/core/Pivot.c:218`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Parser.h`

### PivotPush (function) `VOID PivotPush()`
- Defined: `payloads/Demon/src/core/Pivot.c:235`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Parser.h`

### PivotParseDemonID (function) `UINT32 PivotParseDemonID( PVOID Response, SIZE_T Size )`
- Defined: `payloads/Demon/src/core/Pivot.c:331`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Parser.h`

## payloads/Demon/src/core/Runtime.c

### RtAdvapi32 (function) `BOOL RtAdvapi32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:6`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### RtMscoree (function) `BOOL RtMscoree(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:68`
- Doc: we delay loading mscoree.dll
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### RtOleaut32 (function) `BOOL RtOleaut32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:103`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### RtUser32 (function) `BOOL RtUser32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:142`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### RtShell32 (function) `BOOL RtShell32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:176`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### RtMsvcrt (function) `BOOL RtMsvcrt(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:208`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### RtIphlpapi (function) `BOOL RtIphlpapi(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:240`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### RtGdi32 (function) `BOOL RtGdi32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:273`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### RtNetApi32 (function) `BOOL RtNetApi32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:310`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### RtWs2_32 (function) `BOOL RtWs2_32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:349`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### RtSspicli (function) `BOOL RtSspicli(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:394`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### RtAmsi (function) `BOOL RtAmsi(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:433`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

### RtWinHttp (function) `BOOL RtWinHttp(
    VOID
)`
- Defined: `payloads/Demon/src/core/Runtime.c:463`
- Doc: ifdef TRANSPORT_HTTP
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`

## payloads/Demon/src/core/Socket.c

### RecvAll (function) `BOOL RecvAll( SOCKET Socket, PVOID Buffer, DWORD Length, PDWORD BytesRead )`
- Defined: `payloads/Demon/src/core/Socket.c:7`
- Doc: attempt to receive all the requested data from the socket * Took it from: https://github.com/rsmudge/metasploit-loader/b
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### InitWSA (function) `BOOL InitWSA( VOID )`
- Defined: `payloads/Demon/src/core/Socket.c:33`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### PUTS (function) `PUTS( "Init Windows Socket..." )

        if ( ( Result = Instance->Win32.WSAStartup( MAKEWORD( 2...`
- Defined: `payloads/Demon/src/core/Socket.c:41`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### SocketNew (function) `PSOCKET_DATA SocketNew( SOCKET WinSock, DWORD Type, BOOL UseIpv4, DWORD IPv4, PBYTE IPv6, DWORD L...`
- Defined: `payloads/Demon/src/core/Socket.c:59`
- Doc: PRINTF( "WSAStartup Failed: %d\n", Result ) /* cleanup and be gone. Instance->Win32.WSACleanup(); return FALSE; } Instan
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### PUTS (function) `PUTS( "Create Socket..." )

        if ( UseIpv4 )`
- Defined: `payloads/Demon/src/core/Socket.c:74`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### PRINTF (function) `PRINTF( "SockAddr6: %02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%02x%02x:%d\n"...`
- Defined: `payloads/Demon/src/core/Socket.c:112`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### SocketClients (function) `VOID SocketClients()`
- Defined: `payloads/Demon/src/core/Socket.c:213`
- Doc: CLEANUP: if ( WinSock && WinSock != INVALID_SOCKET ) { close the socket preserving the last error code ErrorCode = NtGet
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### SocketRead (function) `VOID SocketRead()`
- Defined: `payloads/Demon/src/core/Socket.c:281`
- Doc: { PRINTF( "ioctlsocket failed: %d\n", NtGetLastError() ) /* close socket. Instance->Win32.closesocket( WinSock ); } } } 
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### SocketFree (function) `VOID SocketFree( PSOCKET_DATA Socket )`
- Defined: `payloads/Demon/src/core/Socket.c:425`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### PRINTF (function) `PRINTF( "Closing socket %x\n", Socket->ID )

    /* do we want to remove a reverse port forward c...`
- Defined: `payloads/Demon/src/core/Socket.c:429`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### SocketCleanDead (function) `VOID SocketCleanDead()`
- Defined: `payloads/Demon/src/core/Socket.c:482`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### SocketPush (function) `VOID SocketPush()`
- Defined: `payloads/Demon/src/core/Socket.c:522`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### DnsQueryIPv4 (function) `DWORD DnsQueryIPv4( LPSTR Domain )`
- Defined: `payloads/Demon/src/core/Socket.c:539`
- Doc: ! Query the IPv4 from the specified domain @param Domain @return IPv4 address
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

### DnsQueryIPv6 (function) `PBYTE DnsQueryIPv6( LPSTR Domain )`
- Defined: `payloads/Demon/src/core/Socket.c:580`
- Doc: ! Query the IPv6 from the specified domain @param Domain @return IPv6 address
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`

## payloads/Demon/src/core/Spoof.c

### SpoofRetAddr (function) `PVOID SpoofRetAddr(
    _In_    PVOID  Module,
    _In_    ULONG  Size,
    _In_    HANDLE Functi...`
- Defined: `payloads/Demon/src/core/Spoof.c:6`
- Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Spoof.h`

## payloads/Demon/src/core/SysNative.c

### SysNtOpenThread (function) `NTSTATUS NTAPI SysNtOpenThread(
    OUT    PHANDLE            ThreadHandle,
    IN     ACCESS_MAS...`
- Defined: `payloads/Demon/src/core/SysNative.c:6`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtOpenProcess (function) `NTSTATUS NTAPI SysNtOpenProcess(
    OUT    PHANDLE             ProcessHandle,
    IN     ACCESS_...`
- Defined: `payloads/Demon/src/core/SysNative.c:20`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtTerminateProcess (function) `NTSTATUS NTAPI SysNtTerminateProcess(
    IN OPTIONAL HANDLE   ProcessHandle,
    IN          NTS...`
- Defined: `payloads/Demon/src/core/SysNative.c:34`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtOpenThreadToken (function) `NTSTATUS NTAPI SysNtOpenThreadToken(
    IN  HANDLE      ThreadHandle,
    IN  ACCESS_MASK Desire...`
- Defined: `payloads/Demon/src/core/SysNative.c:46`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtOpenProcessToken (function) `NTSTATUS NTAPI SysNtOpenProcessToken(
    IN  HANDLE      ProcessHandle,
    IN  ACCESS_MASK Desi...`
- Defined: `payloads/Demon/src/core/SysNative.c:60`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtDuplicateToken (function) `NTSTATUS NTAPI SysNtDuplicateToken(
    IN  HANDLE             ExistingTokenHandle,
    IN  ACCES...`
- Defined: `payloads/Demon/src/core/SysNative.c:73`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtQueueApcThread (function) `NTSTATUS NTAPI SysNtQueueApcThread(
    IN     HANDLE          ThreadHandle,
    IN     PPS_APC_R...`
- Defined: `payloads/Demon/src/core/SysNative.c:89`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtSuspendThread (function) `NTSTATUS NTAPI SysNtSuspendThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSu...`
- Defined: `payloads/Demon/src/core/SysNative.c:104`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtResumeThread (function) `NTSTATUS NTAPI SysNtResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG PreviousSus...`
- Defined: `payloads/Demon/src/core/SysNative.c:116`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtCreateEvent (function) `NTSTATUS NTAPI SysNtCreateEvent (
    OUT    PHANDLE            EventHandle,
    IN     ACCESS_MA...`
- Defined: `payloads/Demon/src/core/SysNative.c:128`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtCreateThreadEx (function) `NTSTATUS NTAPI SysNtCreateThreadEx(
    OUT PHANDLE     hThread,
    IN  ACCESS_MASK DesiredAcces...`
- Defined: `payloads/Demon/src/core/SysNative.c:143`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtDuplicateObject (function) `NTSTATUS NTAPI SysNtDuplicateObject(
    IN     HANDLE      SourceProcessHandle,
    IN     HANDL...`
- Defined: `payloads/Demon/src/core/SysNative.c:176`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtGetContextThread (function) `NTSTATUS NTAPI SysNtGetContextThread (
    IN     HANDLE   ThreadHandle,
    _Inout_ PCONTEXT Thr...`
- Defined: `payloads/Demon/src/core/SysNative.c:193`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtSetContextThread (function) `NTSTATUS NTAPI SysNtSetContextThread(
    IN HANDLE   ThreadHandle,
    IN PCONTEXT ThreadContext
)`
- Defined: `payloads/Demon/src/core/SysNative.c:205`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtQueryInformationProcess (function) `NTSTATUS NTAPI SysNtQueryInformationProcess(
    IN      HANDLE           ProcessHandle,
    IN  ...`
- Defined: `payloads/Demon/src/core/SysNative.c:217`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtQuerySystemInformation (function) `NTSTATUS NTAPI SysNtQuerySystemInformation (
    IN      SYSTEM_INFORMATION_CLASS SystemInformati...`
- Defined: `payloads/Demon/src/core/SysNative.c:232`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtWaitForSingleObject (function) `NTSTATUS NTAPI SysNtWaitForSingleObject(
    IN     HANDLE         Handle,
    IN     BOOLEAN    ...`
- Defined: `payloads/Demon/src/core/SysNative.c:246`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtAllocateVirtualMemory (function) `NTSTATUS NTAPI SysNtAllocateVirtualMemory(
    IN     HANDLE    ProcessHandle,
    _Inout_ PVOID*...`
- Defined: `payloads/Demon/src/core/SysNative.c:259`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtWriteVirtualMemory (function) `NTSTATUS NTAPI SysNtWriteVirtualMemory(
    IN       HANDLE  ProcessHandle,
    IN OPT   PVOID   ...`
- Defined: `payloads/Demon/src/core/SysNative.c:275`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtFreeVirtualMemory (function) `NTSTATUS NTAPI SysNtFreeVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  Base...`
- Defined: `payloads/Demon/src/core/SysNative.c:290`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtUnmapViewOfSection (function) `NTSTATUS NTAPI SysNtUnmapViewOfSection(
    IN HANDLE ProcessHandle,
    IN PVOID  BaseAddress
)`
- Defined: `payloads/Demon/src/core/SysNative.c:304`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtProtectVirtualMemory (function) `NTSTATUS NTAPI SysNtProtectVirtualMemory(
    IN     HANDLE  ProcessHandle,
    _Inout_ PVOID*  B...`
- Defined: `payloads/Demon/src/core/SysNative.c:316`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtReadVirtualMemory (function) `NTSTATUS NTAPI SysNtReadVirtualMemory (
    IN      HANDLE  ProcessHandle,
    IN OPT  PVOID   Ba...`
- Defined: `payloads/Demon/src/core/SysNative.c:331`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtTerminateThread (function) `NTSTATUS NTAPI SysNtTerminateThread (
    IN OPT HANDLE   ThreadHandle,
    IN     NTSTATUS ExitS...`
- Defined: `payloads/Demon/src/core/SysNative.c:346`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtAlertResumeThread (function) `NTSTATUS NTAPI SysNtAlertResumeThread(
    IN      HANDLE ThreadHandle,
    OUT OPT PULONG Previo...`
- Defined: `payloads/Demon/src/core/SysNative.c:358`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtSignalAndWaitForSingleObject (function) `NTSTATUS NTAPI SysNtSignalAndWaitForSingleObject(
    IN     HANDLE         SignalHandle,
    IN ...`
- Defined: `payloads/Demon/src/core/SysNative.c:370`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtQueryVirtualMemory (function) `NTSTATUS NTAPI SysNtQueryVirtualMemory(
    IN      HANDLE                   ProcessHandle,
    I...`
- Defined: `payloads/Demon/src/core/SysNative.c:384`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtQueryInformationToken (function) `NTSTATUS NTAPI SysNtQueryInformationToken (
    IN  HANDLE                  TokenHandle,
    IN  ...`
- Defined: `payloads/Demon/src/core/SysNative.c:400`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtQueryInformationThread (function) `NTSTATUS NTAPI SysNtQueryInformationThread(
    IN      HANDLE          ThreadHandle,
    IN     ...`
- Defined: `payloads/Demon/src/core/SysNative.c:415`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtQueryObject (function) `NTSTATUS NTAPI SysNtQueryObject(
    IN  HANDLE                   Handle,
    IN  OBJECT_INFORMAT...`
- Defined: `payloads/Demon/src/core/SysNative.c:430`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtClose (function) `NTSTATUS NTAPI SysNtClose (
    IN HANDLE Handle
)`
- Defined: `payloads/Demon/src/core/SysNative.c:445`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtSetInformationThread (function) `NTSTATUS NTAPI SysNtSetInformationThread (
    IN HANDLE          ThreadHandle,
    IN THREADINFO...`
- Defined: `payloads/Demon/src/core/SysNative.c:456`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtSetInformationVirtualMemory (function) `NTSTATUS NTAPI SysNtSetInformationVirtualMemory(
    IN HANDLE                           ProcessH...`
- Defined: `payloads/Demon/src/core/SysNative.c:470`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

### SysNtGetNextThread (function) `NTSTATUS NTAPI SysNtGetNextThread(
    IN  HANDLE      ProcessHandle,
    IN  HANDLE      ThreadH...`
- Defined: `payloads/Demon/src/core/SysNative.c:486`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`

## payloads/Demon/src/core/Syscalls.c

### SysInitialize (function) `BOOL SysInitialize(
    IN PVOID Ntdll
)`
- Defined: `payloads/Demon/src/core/Syscalls.c:12`
- Doc: ! Initialize syscall addr + ssn @param Ntdll @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### SYS_EXTRACT (function) `SYS_EXTRACT( NtOpenThread )
    SYS_EXTRACT( NtOpenThreadToken )
    SYS_EXTRACT( NtOpenProcess )...`
- Defined: `payloads/Demon/src/core/Syscalls.c:44`
- Doc: Instance->Syscall.SysAddress = SysIndirectAddr; } else { PUTS_DONT_SEND( "Failed to resolve SysIndirectAddr" ); } } #if 
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PRINTF (function) `PRINTF( "Could not resolve the Ssn of function at 0x%p\n", Function )
        }

        if ( Sys...`
- Defined: `payloads/Demon/src/core/Syscalls.c:184`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### FindSsnOfHookedSyscall (function) `BOOL FindSsnOfHookedSyscall(
    IN  PVOID  Function,
    OUT PWORD  Ssn
)`
- Defined: `payloads/Demon/src/core/Syscalls.c:201`
- Doc: If a function is hooked, we can't obtain the Ssn directly. Instead, we look for the Ssn of a neighbouring syscalls and a
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PRINTF (function) `PRINTF( "The syscall at address 0x%p seems to be hooked, trying to resolve its Ssn via neighbouri...`
- Defined: `payloads/Demon/src/core/Syscalls.c:209`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Thread.c

### ThreadQueryTib (function) `BOOL ThreadQueryTib(
    IN  PVOID   Adr,
    OUT PNT_TIB Tib
)`
- Defined: `payloads/Demon/src/core/Thread.c:20`
- Doc: ! queries the NT_TIB from the specified leaked thread RSP address  NOTE: this function is entirely taken from Austins Hu
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`

### ThreadCreateWoW64 (function) `HANDLE ThreadCreateWoW64(
    IN  BYTE   Method,
    IN  HANDLE Process,
    IN  PVOID  Entry,
  ...`
- Defined: `payloads/Demon/src/core/Thread.c:118`
- Doc: https://github.com/rapid7/meterpreter/blob/5e309596e53ead0f64564fe77e0cad70908f6739/source/common/arch/win/i386/base_inj
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`

### PUTS (function) `PUTS( "calling RtlCreateUserThread( ctx->h.hProcess, NULL, TRUE, 0, NULL, NULL, ctx->s.lpStartAdd...`
- Defined: `payloads/Demon/src/core/Thread.c:185`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`

### ThreadCreate (function) `HANDLE ThreadCreate(
    IN  BYTE   Method,
    IN  HANDLE Process,
    IN  BOOL   x64,
    IN  P...`
- Defined: `payloads/Demon/src/core/Thread.c:217`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Token.c

### TokenDuplicate (function) `BOOL TokenDuplicate(
    IN  HANDLE        TokenOriginal,
    IN  DWORD         Access,
    IN  S...`
- Defined: `payloads/Demon/src/core/Token.c:37`
- Doc: ! @brief Duplicate given token  @param TokenOriginal @param Access @param ImpersonateLevel @param TokenType @param Token
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenRevSelf (function) `BOOL TokenRevSelf(
    VOID
)`
- Defined: `payloads/Demon/src/core/Token.c:74`
- Doc: ! @brief reverse to the original process user token  @return if successful reverse to original token
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenQueryOwner (function) `BOOL TokenQueryOwner(
    IN  HANDLE  Token,
    OUT PBUFFER UserDomain,
    IN  DWORD   Flags
)`
- Defined: `payloads/Demon/src/core/Token.c:103`
- Doc: ! @brief queries the username and or domain  @note the queried memory should be freed after used using HeapFree/RtlFreeH
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### PUTS (function) `PUTS( "Unexpected successful call to NtQueryInformationToken.\n" )
    }

LEAVE:
    if ( UserInfo )`
- Defined: `payloads/Demon/src/core/Token.c:177`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### DATA_FREE (function) `DATA_FREE( UserInfo, UserSize )
    }

    if ( Flags == TOKEN_OWNER_FLAG_USER )`
- Defined: `payloads/Demon/src/core/Token.c:182`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenSetPrivilege (function) `BOOL TokenSetPrivilege(
    IN LPSTR Privilege,
    IN BOOL  Enable
)`
- Defined: `payloads/Demon/src/core/Token.c:203`
- Doc: ! sets a privilege  TODO: change it to use wide strings.  @param Privilege @param Enable @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenSetSeDebugPriv (function) `BOOL TokenSetSeDebugPriv(
    IN BOOL  Enable
)`
- Defined: `payloads/Demon/src/core/Token.c:240`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenSetSeImpersonatePriv (function) `BOOL TokenSetSeImpersonatePriv(
    IN BOOL  Enable
)`
- Defined: `payloads/Demon/src/core/Token.c:271`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenAdd (function) `DWORD TokenAdd(
    IN HANDLE hToken,
    IN LPWSTR DomainUser,
    IN SHORT  Type,
    IN DWORD ...`
- Defined: `payloads/Demon/src/core/Token.c:323`
- Doc: Adds an token to the vault.  TODO: rewrite the function param. accept token object + STOLEN PID or MAKE data as a struct
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### SysDuplicateTokenEx (function) `BOOL SysDuplicateTokenEx(
    IN HANDLE ExistingTokenHandle,
    IN DWORD dwDesiredAccess,
    IN...`
- Defined: `payloads/Demon/src/core/Token.c:365`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenSteal (function) `HANDLE TokenSteal(
    IN DWORD  ProcessID,
    IN HANDLE TargetHandle
)`
- Defined: `payloads/Demon/src/core/Token.c:414`
- Doc: ! Steals the process token from the specified pid @param ProcessID @param TargetHandle @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### PRINTF (function) `PRINTF( "ProcessOpen: Failed:[%ld]\n", NtGetLastError() )
        PACKAGE_ERROR_WIN32
    }

    ...`
- Defined: `payloads/Demon/src/core/Token.c:463`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenRemove (function) `BOOL TokenRemove( DWORD TokenID )`
- Defined: `payloads/Demon/src/core/Token.c:474`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenMake (function) `HANDLE TokenMake( LPWSTR User, LPWSTR Password, LPWSTR Domain, DWORD LogonType )`
- Defined: `payloads/Demon/src/core/Token.c:598`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### PRINTF (function) `PRINTF( "TokenMake( %ls, %ls, %ls, %d )\n", User, Password, Domain, LogonType )

    if ( ! Token...`
- Defined: `payloads/Demon/src/core/Token.c:602`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### PRINTF (function) `PRINTF( "Failed to revert to self: Error:[%d]\n", NtGetLastError() )
        PACKAGE_ERROR_WIN32
...`
- Defined: `payloads/Demon/src/core/Token.c:606`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenCurrentHandle (function) `HANDLE TokenCurrentHandle(
    VOID
)`
- Defined: `payloads/Demon/src/core/Token.c:624`
- Doc: ! get current process/thread token @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenElevated (function) `BOOL TokenElevated(
    IN HANDLE Token
)`
- Defined: `payloads/Demon/src/core/Token.c:650`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenGet (function) `PTOKEN_LIST_DATA TokenGet(
    IN DWORD TokenID
)`
- Defined: `payloads/Demon/src/core/Token.c:664`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenClear (function) `VOID TokenClear(
    VOID
)`
- Defined: `payloads/Demon/src/core/Token.c:681`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### TokenImpersonate (function) `BOOL TokenImpersonate(
    IN BOOL Impersonate
)`
- Defined: `payloads/Demon/src/core/Token.c:707`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### AddUserToken (function) `VOID AddUserToken(
    _Inout_ PUSER_TOKEN_DATA NewToken,
    _Inout_ PUSER_TOKEN_DATA Tokens,
  ...`
- Defined: `payloads/Demon/src/core/Token.c:733`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### IsImpersonationToken (function) `BOOL IsImpersonationToken( HANDLE token )`
- Defined: `payloads/Demon/src/core/Token.c:771`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### CanTokenBeImpersonated (function) `BOOL CanTokenBeImpersonated( IN HANDLE hToken )`
- Defined: `payloads/Demon/src/core/Token.c:802`
- Doc: https://github.com/rapid7/metasploit-payloads/blob/master/c/meterpreter/source/extensions/incognito/list_tokens.c
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### ProcessUserToken (function) `VOID ProcessUserToken(
    IN HANDLE hToken,
    IN DWORD ProcessId,
    IN HANDLE handle,
    IN...`
- Defined: `payloads/Demon/src/core/Token.c:830`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### QueryObjectTypesInfo (function) `BOOL QueryObjectTypesInfo( POBJECT_TYPES_INFORMATION* pObjectTypes, PULONG pObjectTypesSize )`
- Defined: `payloads/Demon/src/core/Token.c:878`
- Doc: call NtQueryObject with ObjectTypesInformation
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### GetTypeIndexToken (function) `BOOL GetTypeIndexToken( OUT PULONG TokenTypeIndex )`
- Defined: `payloads/Demon/src/core/Token.c:910`
- Doc: get index of object type 'Token'
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### GetTokenInfo (function) `BOOL GetTokenInfo(
    IN HANDLE hToken,
    OUT PDWORD pTokenType,
    OUT PDWORD pIntegrity,
  ...`
- Defined: `payloads/Demon/src/core/Token.c:949`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### PUTS (function) `PUTS( "GetTokenInformation failed" )
            }
        }
        else if (TokenStatisticsInfo...`
- Defined: `payloads/Demon/src/core/Token.c:991`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### ProcessIsIncluded (function) `BOOL ProcessIsIncluded( IN PPROCESS_LIST process_list, IN ULONG ProcessId )`
- Defined: `payloads/Demon/src/core/Token.c:1029`
- Doc: check if a PID is included in the process list
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### GetProcessesFromHandleTable (function) `BOOL GetProcessesFromHandleTable( IN PSYSTEM_HANDLE_INFORMATION handleTableInformation, OUT PPROC...`
- Defined: `payloads/Demon/src/core/Token.c:1040`
- Doc: obtain a list of PIDs from a handle table
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### GetAllHandles (function) `BOOL GetAllHandles( OUT PSYSTEM_HANDLE_INFORMATION* phandle_table, OUT PULONG phandle_table_size )`
- Defined: `payloads/Demon/src/core/Token.c:1076`
- Doc: get all handles in the system
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### IsNotCurrentUser (function) `BOOL IsNotCurrentUser( BOOL DoCheck, PBUFFER UserA, PBUFFER UserB )`
- Defined: `payloads/Demon/src/core/Token.c:1122`
- Doc: phandle_table = (PSYSTEM_HANDLE_INFORMATION)handleTableInformation; phandle_table_size = buffer_size; ret_val = TRUE; cl
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### ListTokens (function) `BOOL ListTokens( PUSER_TOKEN_DATA* pTokens, PDWORD pNumTokens )`
- Defined: `payloads/Demon/src/core/Token.c:1130`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### ImpersonateTokenFromVault (function) `BOOL ImpersonateTokenFromVault(
    IN DWORD TokenID
)`
- Defined: `payloads/Demon/src/core/Token.c:1257`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### SysImpersonateLoggedOnUser (function) `BOOL SysImpersonateLoggedOnUser( HANDLE hToken )`
- Defined: `payloads/Demon/src/core/Token.c:1281`
- Doc: https://doxygen.reactos.org/d1/d72/dll_2win32_2advapi32_2sec_2misc_8c_source.html#l00152
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

### ImpersonateTokenInStore (function) `BOOL ImpersonateTokenInStore(
    IN PTOKEN_LIST_DATA TokenData
)`
- Defined: `payloads/Demon/src/core/Token.c:1361`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/core/Transport.c

### TransportInit (function) `BOOL TransportInit( )`
- Defined: `payloads/Demon/src/core/Transport.c:13`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportHttp.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### TransportSend (function) `BOOL TransportSend( LPVOID Data, SIZE_T Size, PVOID* RecvData, PSIZE_T RecvSize )`
- Defined: `payloads/Demon/src/core/Transport.c:52`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportHttp.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### SMBGetJob (function) `BOOL SMBGetJob( PVOID* RecvData, PSIZE_T RecvSize )`
- Defined: `payloads/Demon/src/core/Transport.c:89`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/TransportHttp.h`, `payloads/Demon/include/core/TransportSmb.h`, `payloads/Demon/include/crypt/AesCrypt.h`

## payloads/Demon/src/core/TransportHttp.c

### HttpSend (function) `BOOL HttpSend(
    _In_      PBUFFER Send,
    _Out_opt_ PBUFFER Resp
)`
- Defined: `payloads/Demon/src/core/TransportHttp.c:21`
- Doc: ! @brief send a http request  @param Send buffer to send  @param Resp buffer response  @return if successful send reques
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportHttp.h`

### PRINTF_DONT_SEND (function) `PRINTF_DONT_SEND( "HTTP Error: %d\n", NtGetLastError() )
    }

LEAVE:
    if ( Connect )`
- Defined: `payloads/Demon/src/core/TransportHttp.c:291`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportHttp.h`

### HttpQueryStatus (function) `DWORD HttpQueryStatus(
    _In_ HANDLE Request
)`
- Defined: `payloads/Demon/src/core/TransportHttp.c:336`
- Doc: ! @brief Query the Http Status code from the request response.  @param hRequest request handle  @return Http status code
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportHttp.h`

### HostAdd (function) `PHOST_DATA HostAdd(
    _In_ LPWSTR Host, SIZE_T Size, DWORD Port )`
- Defined: `payloads/Demon/src/core/TransportHttp.c:356`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportHttp.h`

### HostFailure (function) `PHOST_DATA HostFailure( PHOST_DATA Host )`
- Defined: `payloads/Demon/src/core/TransportHttp.c:378`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportHttp.h`

### HostRandom (function) `PHOST_DATA HostRandom()`
- Defined: `payloads/Demon/src/core/TransportHttp.c:402`
- Doc: /* Get our next host based on our rotation strategy. return HostRotation( Instance->Config.Transport.HostRotation ); } /
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportHttp.h`

### HostRotation (function) `PHOST_DATA HostRotation( SHORT Strategy )`
- Defined: `payloads/Demon/src/core/TransportHttp.c:437`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportHttp.h`

### HostCount (function) `DWORD HostCount()`
- Defined: `payloads/Demon/src/core/TransportHttp.c:514`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportHttp.h`

### HostCheckup (function) `BOOL HostCheckup()`
- Defined: `payloads/Demon/src/core/TransportHttp.c:541`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportHttp.h`

## payloads/Demon/src/core/TransportSmb.c

### SmbSend (function) `BOOL SmbSend( PBUFFER Send )`
- Defined: `payloads/Demon/src/core/TransportSmb.c:8`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportSmb.h`

### SmbRecv (function) `BOOL SmbRecv( PBUFFER Resp )`
- Defined: `payloads/Demon/src/core/TransportSmb.c:65`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportSmb.h`

### PRINTF (function) `PRINTF( "PipeRead failed with to read 0x%x bytes from pipe\n", Resp->Length )
                if ...`
- Defined: `payloads/Demon/src/core/TransportSmb.c:107`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportSmb.h`

### SmbSecurityAttrOpen (function) `VOID SmbSecurityAttrOpen( PSMB_PIPE_SEC_ATTR SmbSecAttr, PSECURITY_ATTRIBUTES SecurityAttr )`
- Defined: `payloads/Demon/src/core/TransportSmb.c:142`
- Doc: Took it from https://github.com/rapid7/metasploit-payloads/blob/master/c/meterpreter/source/metsrv/server_pivot_named_pi
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportSmb.h`

### SmbSecurityAttrFree (function) `VOID SmbSecurityAttrFree( PSMB_PIPE_SEC_ATTR SmbSecAttr )`
- Defined: `payloads/Demon/src/core/TransportSmb.c:213`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/TransportSmb.h`

## payloads/Demon/src/core/Win32.c

### HashEx (function) `ULONG HashEx(
    IN PVOID String,
    IN ULONG Length,
    IN BOOL  Upper
)`
- Defined: `payloads/Demon/src/core/Win32.c:17`
- Doc: ! Extended String Hasher @param String @param Length @param Upper @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### LdrModulePeb (function) `PVOID LdrModulePeb(
    IN DWORD Hash
)`
- Defined: `payloads/Demon/src/core/Win32.c:65`
- Doc: ! load module from PEB InLoadOrderModuleList by Hash @param Hash @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### LdrModulePebByString (function) `PVOID LdrModulePebByString(
    IN LPWSTR Module
)`
- Defined: `payloads/Demon/src/core/Win32.c:99`
- Doc: ! load module from PEB InLoadOrderModuleList by String @param Module name of module (needs to be upper case: MODULE.DLL)
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### LdrModuleSearch (function) `PVOID LdrModuleSearch(
    IN LPWSTR ModuleName)`
- Defined: `payloads/Demon/src/core/Win32.c:165`
- Doc: ! Search for a DLL on the PEB module list  @param ModuleName module name @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### LdrModuleLoad (function) `PVOID LdrModuleLoad(
    IN LPSTR ModuleName
)`
- Defined: `payloads/Demon/src/core/Win32.c:215`
- Doc: ! Load Library by string name.  @note based on how it is configured to load the module it either proxy calls LoadLibrary
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PUTS (function) `PUTS( "Loading module using RtlRegisterWait" )

            /* create an event for end of module ...`
- Defined: `payloads/Demon/src/core/Win32.c:252`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PUTS (function) `PUTS( "Loading module using RtlCreateTimer" )

            /* create timer queue */
            i...`
- Defined: `payloads/Demon/src/core/Win32.c:269`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PUTS (function) `PUTS( "Loading module using RtlQueueWorkItem" )

            /* call LoadLibraryW and load specif...`
- Defined: `payloads/Demon/src/core/Win32.c:286`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PRINTF (function) `PRINTF( "Module \"%s\": %p\n", ModuleName, Module )

    /* close event end */
    if ( Event )`
- Defined: `payloads/Demon/src/core/Win32.c:354`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### LdrFunctionAddr (function) `PVOID LdrFunctionAddr(
    IN PVOID Module,
    IN DWORD Hash
)`
- Defined: `payloads/Demon/src/core/Win32.c:377`
- Doc: ! gets the function pointer @param Module @param FunctionHash @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### GetSyscallSize (function) `UINT32 GetSyscallSize(
    VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:440`
- Doc: Get the size of an NtApi by finding two consecutive syscalls and returning the difference of their addresses. This can't
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### ProcessOpen (function) `HANDLE ProcessOpen(
    IN DWORD Pid,
    IN DWORD Access
)`
- Defined: `payloads/Demon/src/core/Win32.c:515`
- Doc: ! opens a handle to the specified pid with specified access @param ProcessID @param Access @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### ProcessIsWow (function) `BOOL ProcessIsWow(
    IN HANDLE Process
)`
- Defined: `payloads/Demon/src/core/Win32.c:544`
- Doc: ! checks if a process runs under Wow64 @param Process @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### ProcessCreate (function) `BOOL ProcessCreate(
    IN  BOOL                 x86,
    IN  LPWSTR               App,
    IN  L...`
- Defined: `payloads/Demon/src/core/Win32.c:579`
- Doc: ! Starts a Process  @param x86 start 32-bit/wow64 process @param App App path @param CmdLine Process to run @param Flags
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PUTS (function) `PUTS( "Enable Wow64 process support" )
        if ( ! Instance->Win32.Wow64DisableWow64FsRedirect...`
- Defined: `payloads/Demon/src/core/Win32.c:626`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PRINTF (function) `PRINTF( "CmdLine           : %ls\n", CmdLine )
        PRINTF( "lpCurrentDirectory: %ls\n", lpCur...`
- Defined: `payloads/Demon/src/core/Win32.c:654`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PUTS (function) `PUTS( "CreateProcessWithTokenW" )
            if ( ! Instance->Win32.CreateProcessWithTokenW(
   ...`
- Defined: `payloads/Demon/src/core/Win32.c:671`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PUTS (function) `PUTS( "CreateProcessWithLogonW" )
            PRINTF( "lpUser[%s] lpDomain[%s] lpPassword[%s]", I...`
- Defined: `payloads/Demon/src/core/Win32.c:693`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PUTS (function) `PUTS( "Send info back" )
        if ( ! CmdLine )`
- Defined: `payloads/Demon/src/core/Win32.c:739`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### ProcessTerminate (function) `BOOL ProcessTerminate(
    IN HANDLE hProcess,
    IN DWORD  Pid)`
- Defined: `payloads/Demon/src/core/Win32.c:806`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PUTS (function) `PUTS( "Failed to terminate process" )
    }

END:
    if ( OpenedHandle )`
- Defined: `payloads/Demon/src/core/Win32.c:831`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### ProcessSnapShot (function) `NTSTATUS ProcessSnapShot(
    OUT PSYSTEM_PROCESS_INFORMATION* SnapShot,
    OUT PSIZE_T         ...`
- Defined: `payloads/Demon/src/core/Win32.c:848`
- Doc: ! takes a snapshot of current running processes @param SnapShot @param Size @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### ReadLocalFile (function) `BOOL ReadLocalFile(
    IN  LPCWSTR FileName,
    OUT PVOID*  FileContent,
    OUT PDWORD  FileSi...`
- Defined: `payloads/Demon/src/core/Win32.c:886`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### BypassPatchAMSI (function) `BOOL BypassPatchAMSI(
    VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:930`
- Doc: Patch AMSI * TODO: remove this and replace it with hardware breakpoints
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### AnonPipesInit (function) `BOOL AnonPipesInit(
    IN PANONPIPE AnonPipes
)`
- Defined: `payloads/Demon/src/core/Win32.c:981`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### AnonPipesRead (function) `VOID AnonPipesRead(
    IN PANONPIPE AnonPipes,
    IN UINT32 RequestID
)`
- Defined: `payloads/Demon/src/core/Win32.c:1000`
- Doc: ! reads from the specified anonymous pipe and sends the result back to the teamserver @param AnonPipes @param RequestID
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PUTS (function) `PUTS( "Start reading anon pipe" )
    PRINTF( "AnonPipes->StdOutRead => %x\n", AnonPipes->StdOutR...`
- Defined: `payloads/Demon/src/core/Win32.c:1011`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PRINTF (function) `PRINTF( "dwRead => %d\n", dwRead )

        if ( dwRead == 0 )`
- Defined: `payloads/Demon/src/core/Win32.c:1023`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### WinScreenshot (function) `BOOL WinScreenshot(
    OUT PVOID*  ImagePointer,
    OUT PSIZE_T ImageSize
)`
- Defined: `payloads/Demon/src/core/Win32.c:1052`
- Doc: ! takes a BMP screenshot of the current desktop @param ImagePointer @param ImageSize @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PipeRead (function) `BOOL PipeRead(
    IN HANDLE  Handle,
    IN PBUFFER Buffer
)`
- Defined: `payloads/Demon/src/core/Win32.c:1175`
- Doc: ! Read from the pipe and writes it to the specified buffer @param Handle handle to the pipe @param Buffer buffer to save
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### PipeWrite (function) `BOOL PipeWrite(
    IN  HANDLE   Handle,
    OUT PBUFFER Buffer
)`
- Defined: `payloads/Demon/src/core/Win32.c:1202`
- Doc: ! Write the specified buffer to the specified pipe @param Handle handle to the pipe @param Buffer buffer to write @retur
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### CfgQueryEnforced (function) `BOOL CfgQueryEnforced(
    VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:1227`
- Doc: ! @brief check if CFG is enforced in this current process.  @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### CfgAddressAdd (function) `VOID CfgAddressAdd(
    IN PVOID ImageBase,
    IN PVOID Function
)`
- Defined: `payloads/Demon/src/core/Win32.c:1259`
- Doc: ! @brief add module + function to CFG exception list.  @param ImageBase @param Function
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### EventSet (function) `BOOL EventSet(
    IN HANDLE Event
)`
- Defined: `payloads/Demon/src/core/Win32.c:1293`
- Doc: ! Sets an event @param Event
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### RandomNumber32 (function) `ULONG RandomNumber32(
    VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:1304`
- Doc: ! generates a random unsigned 32-bit integer @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### RandomBool (function) `BOOL RandomBool(
    VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:1321`
- Doc: ! generates a random bool @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### SharedTimestamp (function) `ULONG64 SharedTimestamp(
    VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:1337`
- Doc: ! get current timestamp since unix epoch from KUSER_SHARED_DATA @return
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### SharedSleep (function) `VOID SharedSleep(
    ULONG64 Delay
)`
- Defined: `payloads/Demon/src/core/Win32.c:1357`
- Doc: ! Sleep using KUSER_SHARED_DATA.SystemTime @param Delay
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### ShuffleArray (function) `VOID ShuffleArray(
    _Inout_ PVOID* array,
    IN     SIZE_T n
)`
- Defined: `payloads/Demon/src/core/Win32.c:1379`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### ___chkstk_ms (function) `VOID volatile ___chkstk_ms(
        VOID
)`
- Defined: `payloads/Demon/src/core/Win32.c:1396`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### DemonPrintf (function) `VOID DemonPrintf( PCHAR fmt, ... )`
- Defined: `payloads/Demon/src/core/Win32.c:1402`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### LogToConsole (function) `VOID LogToConsole(
    IN LPCSTR fmt,
    ...)`
- Defined: `payloads/Demon/src/core/Win32.c:1434`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

### listDir (function) `PROOT_DIR listDir(
    IN LPWSTR StartPath,
    IN BOOL   SubDirs,
    IN BOOL   FilesOnly,
    I...`
- Defined: `payloads/Demon/src/core/Win32.c:1478`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/common/Native.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Win32.h`

## payloads/Demon/src/crypt/AesCrypt.c

### KeyExpansion (function) `void KeyExpansion(UINT8* RoundKey, const UINT8* Key)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:47`
- Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### AesInit (function) `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:103`
- Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### AddRoundKey (function) `static void AddRoundKey(UINT8 round, state_t* state, const UINT8* RoundKey)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:111`
- Doc: This function adds the round key to state. The round key is added to the state by an XOR function.
- Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### SubBytes (function) `static void SubBytes(state_t* state)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:125`
- Doc: The SubBytes Function Substitutes the values in the state matrix with values in an S-box.
- Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### ShiftRows (function) `static void ShiftRows(state_t* state)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:140`
- Doc: The ShiftRows() function shifts the rows in the state to the left. Each row is shifted with different offset. Offset = R
- Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### xtime (function) `static UINT8 xtime(UINT8 x)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:168`
- Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### MixColumns (function) `static void MixColumns(state_t* state)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:174`
- Doc: MixColumns function mixes the columns of the state matrix
- Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/crypt/AesCrypt.h`

### AesXCryptBuffer (function) `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length)`
- Defined: `payloads/Demon/src/crypt/AesCrypt.c:217`
- Depends on: `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/crypt/AesCrypt.h`

## payloads/Demon/src/inject/Inject.c

### Inject (function) `DWORD Inject(
    IN BYTE   Method,
    IN HANDLE Handle,
    IN DWORD  Pid,
    IN BOOL   x64,
 ...`
- Defined: `payloads/Demon/src/inject/Inject.c:27`
- Doc: Inject code into a remote process  @param Method    thread execution method. @param Handle    opened handle to the remot
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/include/inject/InjectUtil.h`

### PRINTF (function) `PRINTF( "[INJECT] Using specified process handle: %x\n", Process )
    }

    /* check the archit...`
- Defined: `payloads/Demon/src/inject/Inject.c:64`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/include/inject/InjectUtil.h`

### PRINTF (function) `PRINTF( "[INJECT] Allocated memory in the remote process: %p\n", Memory )
    }

    /* write pay...`
- Defined: `payloads/Demon/src/inject/Inject.c:91`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/include/inject/InjectUtil.h`

### PRINTF (function) `PRINTF( "[INJECT] Wrote payload into remote process: %d written\n", Size )
    }

    /* change a...`
- Defined: `payloads/Demon/src/inject/Inject.c:99`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/include/inject/InjectUtil.h`

### PUTS (function) `PUTS( "[INJECT] Changed memory protection from RW to RX" )
    }

    /* check if any args has be...`
- Defined: `payloads/Demon/src/inject/Inject.c:107`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/include/inject/InjectUtil.h`

### PRINTF (function) `PRINTF( "[INJECT] Allocated argument memory in the remote process: %p\n", Param )
        }

    ...`
- Defined: `payloads/Demon/src/inject/Inject.c:118`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/include/inject/InjectUtil.h`

### PRINTF (function) `PRINTF( "[INJECT] Wrote argument into remote process: %d written\n", Argc )
        }
    }

    ...`
- Defined: `payloads/Demon/src/inject/Inject.c:126`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/include/inject/InjectUtil.h`

### PRINTF (function) `PRINTF( "[INJECT] Failed to create a new thread: %d\n", NtGetLastError() )
    }

END:
    PUTS( ...`
- Defined: `payloads/Demon/src/inject/Inject.c:135`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/include/inject/InjectUtil.h`

### DllInjectReflective (function) `DWORD DllInjectReflective( HANDLE hTargetProcess, LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuff...`
- Defined: `payloads/Demon/src/inject/Inject.c:172`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/include/inject/InjectUtil.h`

### PRINTF (function) `PRINTF( "Params: Size:[%d] Pointer:[%p]\n", ParamSize, Parameter )
    if ( ParamSize > 0 )`
- Defined: `payloads/Demon/src/inject/Inject.c:232`
- Doc: Alloc and write remote params
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/include/inject/InjectUtil.h`

### PRINTF (function) `PRINTF( "ctx->Parameter: %p\n", ctx->Parameter )

                if ( ! ThreadCreate( THREAD_MET...`
- Defined: `payloads/Demon/src/inject/Inject.c:278`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/include/inject/InjectUtil.h`

### DllSpawnReflective (function) `DWORD DllSpawnReflective( LPVOID DllLdr, DWORD DllLdrSize, LPVOID DllBuffer, DWORD DllLength, PVO...`
- Defined: `payloads/Demon/src/inject/Inject.c:322`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`, `payloads/Demon/include/inject/InjectUtil.h`

## payloads/Demon/src/inject/InjectUtil.c

### Rva2Offset (function) `DWORD Rva2Offset( DWORD dwRva, UINT_PTR uiBaseAddress )`
- Defined: `payloads/Demon/src/inject/InjectUtil.c:12`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/inject/InjectUtil.h`

### GetReflectiveLoaderOffset (function) `DWORD GetReflectiveLoaderOffset( PVOID ReflectiveLdrAddr )`
- Defined: `payloads/Demon/src/inject/InjectUtil.c:36`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/inject/InjectUtil.h`

### GetPeArch (function) `DWORD GetPeArch( PVOID PeBytes )`
- Defined: `payloads/Demon/src/inject/InjectUtil.c:72`
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/inject/InjectUtil.h`

## payloads/Demon/src/main/MainDll.c

### Start (function) `DLLEXPORT VOID Start(  )`
- Defined: `payloads/Demon/src/main/MainDll.c:8`
- Doc: Export this for rundll32 or any other program that requires and exported functions... * TODO: make this function name op
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`

### DllMain (function) `DLLEXPORT BOOL WINAPI DllMain(
    IN     HINSTANCE hDllBase,
    IN     DWORD     Reason,
    _I...`
- Defined: `payloads/Demon/src/main/MainDll.c:24`
- Doc: /* prevent exiting if started using rundll32 or something PVOID Kernel32  = LdrModulePeb( H_MODULE_KERNEL32 ); VOID ( WI
- Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`

## payloads/Demon/src/main/MainExe.c

### WinMain (function) `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )`
- Defined: `payloads/Demon/src/main/MainExe.c:3`
- Depends on: `payloads/Demon/include/Demon.h`

## payloads/Demon/src/main/MainSvc.c

### WinMain (function) `INT WINAPI WinMain( HINSTANCE hInstance, HINSTANCE hPrevInstance, LPSTR lpCmdLine, INT nShowCmd )`
- Defined: `payloads/Demon/src/main/MainSvc.c:16`
- Doc: /* Service handle and status variable SERVICE_STATUS_HANDLE StatusHandle = { 0 }; SERVICE_STATUS        SvcStatus    = {
- Depends on: `payloads/Demon/include/Demon.h`

### SvcMain (function) `VOID WINAPI SvcMain( DWORD dwArgc, LPTSTR* Argv )`
- Defined: `payloads/Demon/src/main/MainSvc.c:31`
- Doc: { PRINTF( "WinMain (Service Main): hInstance:[%p]\n", hInstance ) SERVICE_TABLE_ENTRY DispatchTable[ ] = { { SERVICE_NAM
- Depends on: `payloads/Demon/include/Demon.h`

### SrvCtrlHandler (function) `VOID WINAPI SrvCtrlHandler( DWORD CtrlCode )`
- Defined: `payloads/Demon/src/main/MainSvc.c:41`
- Depends on: `payloads/Demon/include/Demon.h`

## payloads/DllLdr/Scripts/extract.py

### main (function) `def main(options)`
- Defined: `payloads/DllLdr/Scripts/extract.py:8`

## payloads/DllLdr/Source/Entry.c

### KaynLoader (function) `DLLEXPORT VOID KaynLoader( LPVOID lpParameter )`
- Defined: `payloads/DllLdr/Source/Entry.c:5`

### KaynCaller (function) `NAKED LPVOID KaynCaller( PVOID StartAddress )`
- Defined: `payloads/DllLdr/Source/Entry.c:144`

### Memcpy (function) `NAKED VOID Memcpy( PVOID Destination, PVOID source, SIZE_T Size )`
- Defined: `payloads/DllLdr/Source/Entry.c:166`

### KGetModuleByHash (function) `PVOID KGetModuleByHash( DWORD ModuleHash )`
- Defined: `payloads/DllLdr/Source/Entry.c:185`

### CopyDotStr (function) `FORCE_INLINE UINT32 CopyDotStr( PCHAR String )`
- Defined: `payloads/DllLdr/Source/Entry.c:206`

### KGetProcAddressByHash (function) `PVOID KGetProcAddressByHash( PINSTANCE Instance, PVOID DllModuleBase, DWORD FunctionHash, DWORD O...`
- Defined: `payloads/DllLdr/Source/Entry.c:215`

### KResolveIAT (function) `VOID KResolveIAT( PINSTANCE Instance, LPVOID KaynImage, LPVOID IatDir )`
- Defined: `payloads/DllLdr/Source/Entry.c:265`

### KReAllocSections (function) `VOID KReAllocSections( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir )`
- Defined: `payloads/DllLdr/Source/Entry.c:306`

### KLoadLibrary (function) `PVOID KLoadLibrary( PINSTANCE Instance, LPSTR ModuleName )`
- Defined: `payloads/DllLdr/Source/Entry.c:331`

### KHashString (function) `DWORD KHashString( PVOID String, SIZE_T Length )`
- Defined: `payloads/DllLdr/Source/Entry.c:364`

### KStringLengthA (function) `SIZE_T KStringLengthA( LPCSTR String )`
- Defined: `payloads/DllLdr/Source/Entry.c:393`

### KStringLengthW (function) `SIZE_T KStringLengthW(LPCWSTR String)`
- Defined: `payloads/DllLdr/Source/Entry.c:400`

### KCharStringToWCharString (function) `SIZE_T KCharStringToWCharString( PWCHAR Destination, PCHAR Source, SIZE_T MaximumAllowed )`
- Defined: `payloads/DllLdr/Source/Entry.c:409`

## payloads/Shellcode/Scripts/Hasher.c

### Hash (function) `long Hash( char* String )`
- Defined: `payloads/Shellcode/Scripts/Hasher.c:4`

### ToUpperString (function) `void ToUpperString(char * temp)`
- Defined: `payloads/Shellcode/Scripts/Hasher.c:15`

### main (function) `int main(int argc, char** argv)`
- Defined: `payloads/Shellcode/Scripts/Hasher.c:24`

## payloads/Shellcode/Source/Entry.c

### SEC (function) `SEC( text, B ) VOID Entry( VOID )`
- Defined: `payloads/Shellcode/Source/Entry.c:11`

### KaynLdrReloc (function) `VOID KaynLdrReloc( PVOID KaynImage, PVOID ImageBase, PVOID BaseRelocDir, DWORD KHdrSize )`
- Defined: `payloads/Shellcode/Source/Entry.c:104`

## payloads/Shellcode/Source/Utils.c

### SEC (function) `SEC( text, B ) UINT_PTR HashString( LPVOID String, UINT_PTR Length )`
- Defined: `payloads/Shellcode/Source/Utils.c:4`
- Depends on: `payloads/Shellcode/Include/Utils.h`

## payloads/Shellcode/Source/Win32.c

### SEC (function) `SEC( text, B ) UINT_PTR LdrModulePeb( UINT_PTR hModuleHash )`
- Defined: `payloads/Shellcode/Source/Win32.c:5`
- Depends on: `payloads/Shellcode/Include/Utils.h`

### SEC (function) `SEC( text, B ) PVOID LdrFunctionAddr( UINT_PTR Module, UINT_PTR FunctionHash )`
- Defined: `payloads/Shellcode/Source/Win32.c:23`
- Depends on: `payloads/Shellcode/Include/Utils.h`

## teamserver/cmd/cmd.go

### init (function) `func init(`
- Defined: `teamserver/cmd/cmd.go:29`
- Doc: init all flags
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/main.go`

### teamserverFunc (function) `func teamserverFunc(`
- Defined: `teamserver/cmd/cmd.go:47`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/main.go`

### startMenu (function) `func startMenu(`
- Defined: `teamserver/cmd/cmd.go:61`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/main.go`

## teamserver/cmd/server/agent.go

### AgentUpdate (function) `func (t *Teamserver) AgentUpdate(`
- Defined: `teamserver/cmd/server/agent.go:16`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### Died (function) `func (t *Teamserver) Died(`
- Defined: `teamserver/cmd/server/agent.go:23`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### UnlinkFromAll (function) `func (t *Teamserver) UnlinkFromAll(`
- Defined: `teamserver/cmd/server/agent.go:30`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### ParentOf (function) `func (t *Teamserver) ParentOf(`
- Defined: `teamserver/cmd/server/agent.go:53`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### LinksOf (function) `func (t *Teamserver) LinksOf(`
- Defined: `teamserver/cmd/server/agent.go:60`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### LinkAdd (function) `func (t *Teamserver) LinkAdd(`
- Defined: `teamserver/cmd/server/agent.go:66`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### LinkRemove (function) `func (t *Teamserver) LinkRemove(`
- Defined: `teamserver/cmd/server/agent.go:78`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentHasDied (function) `func (t *Teamserver) AgentHasDied(`
- Defined: `teamserver/cmd/server/agent.go:102`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentAdd (function) `func (t *Teamserver) AgentAdd(`
- Defined: `teamserver/cmd/server/agent.go:108`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentSendNotify (function) `func (t *Teamserver) AgentSendNotify(`
- Defined: `teamserver/cmd/server/agent.go:123`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentCallbackSize (function) `func (t *Teamserver) AgentCallbackSize(`
- Defined: `teamserver/cmd/server/agent.go:138`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentInstance (function) `func (t *Teamserver) AgentInstance(`
- Defined: `teamserver/cmd/server/agent.go:155`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentLastTimeCalled (function) `func (t *Teamserver) AgentLastTimeCalled(`
- Defined: `teamserver/cmd/server/agent.go:166`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentExist (function) `func (t *Teamserver) AgentExist(`
- Defined: `teamserver/cmd/server/agent.go:183`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentConsole (function) `func (t *Teamserver) AgentConsole(`
- Defined: `teamserver/cmd/server/agent.go:198`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### PythonModuleCallback (function) `func (t *Teamserver) PythonModuleCallback(`
- Defined: `teamserver/cmd/server/agent.go:208`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### AgentCallback (function) `func (t *Teamserver) AgentCallback(`
- Defined: `teamserver/cmd/server/agent.go:220`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### SendLogs (function) `func (t *Teamserver) SendLogs(`
- Defined: `teamserver/cmd/server/agent.go:233`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

### GetDotNetPipeTemplate (function) `func (t *Teamserver) GetDotNetPipeTemplate(`
- Defined: `teamserver/cmd/server/agent.go:237`
- Depends on: `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`

## teamserver/cmd/server/dispatch.go

### DispatchEvent (function) `func (t *Teamserver) DispatchEvent(`
- Defined: `teamserver/cmd/server/dispatch.go:20`
- Depends on: `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

## teamserver/cmd/server/listener.go

### ListenerStart (function) `func (t *Teamserver) ListenerStart(`
- Defined: `teamserver/cmd/server/listener.go:19`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerExist (function) `func (t *Teamserver) ListenerExist(`
- Defined: `teamserver/cmd/server/listener.go:113`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerGetInfo (function) `func (t *Teamserver) ListenerGetInfo(`
- Defined: `teamserver/cmd/server/listener.go:124`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerRemove (function) `func (t *Teamserver) ListenerRemove(`
- Defined: `teamserver/cmd/server/listener.go:144`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerEdit (function) `func (t *Teamserver) ListenerEdit(`
- Defined: `teamserver/cmd/server/listener.go:192`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerAdd (function) `func (t *Teamserver) ListenerAdd(`
- Defined: `teamserver/cmd/server/listener.go:220`
- Doc: ListenerAdd creates a package for the client that a new listener has been added.
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerServiceExc2Add (function) `func (t *Teamserver) ListenerServiceExc2Add(`
- Defined: `teamserver/cmd/server/listener.go:337`
- Doc: ListenerServiceExc2Add adds an external c2 listener that has been started from a service script to the teamserver listen
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

### ListenerStartNotify (function) `func (t *Teamserver) ListenerStartNotify(`
- Defined: `teamserver/cmd/server/listener.go:378`
- Doc: ListenerStartNotify Notifies the clients of a new listener that is available to use.
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`

## teamserver/cmd/server/service.go

### ServiceAgent (function) `func (t *Teamserver) ServiceAgent(`
- Defined: `teamserver/cmd/server/service.go:9`
- Depends on: `teamserver/pkg/logger/logger.go`

### ServiceAgentExist (function) `func (t *Teamserver) ServiceAgentExist(`
- Defined: `teamserver/cmd/server/service.go:20`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/cmd/server/teamserver.go

### NewTeamserver (function) `func NewTeamserver(`
- Defined: `teamserver/cmd/server/teamserver.go:37`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### SetServerFlags (function) `func (t *Teamserver) SetServerFlags(`
- Defined: `teamserver/cmd/server/teamserver.go:48`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### Start (function) `func (t *Teamserver) Start(`
- Defined: `teamserver/cmd/server/teamserver.go:52`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### handleRequest (function) `func (t *Teamserver) handleRequest(`
- Defined: `teamserver/cmd/server/teamserver.go:497`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### SetProfile (function) `func (t *Teamserver) SetProfile(`
- Defined: `teamserver/cmd/server/teamserver.go:626`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### ClientAuthenticate (function) `func (t *Teamserver) ClientAuthenticate(`
- Defined: `teamserver/cmd/server/teamserver.go:637`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EventBroadcast (function) `func (t *Teamserver) EventBroadcast(`
- Defined: `teamserver/cmd/server/teamserver.go:690`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EventNewDemon (function) `func (t *Teamserver) EventNewDemon(`
- Defined: `teamserver/cmd/server/teamserver.go:709`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EventAgentMark (function) `func (t *Teamserver) EventAgentMark(`
- Defined: `teamserver/cmd/server/teamserver.go:713`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EventListenerError (function) `func (t *Teamserver) EventListenerError(`
- Defined: `teamserver/cmd/server/teamserver.go:720`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### SendEvent (function) `func (t *Teamserver) SendEvent(`
- Defined: `teamserver/cmd/server/teamserver.go:741`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### RemoveClient (function) `func (t *Teamserver) RemoveClient(`
- Defined: `teamserver/cmd/server/teamserver.go:773`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EventAppend (function) `func (t *Teamserver) EventAppend(`
- Defined: `teamserver/cmd/server/teamserver.go:797`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EventRemove (function) `func (t *Teamserver) EventRemove(`
- Defined: `teamserver/cmd/server/teamserver.go:812`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### SendAllPackagesToNewClient (function) `func (t *Teamserver) SendAllPackagesToNewClient(`
- Defined: `teamserver/cmd/server/teamserver.go:818`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### FindSystemPackages (function) `func (t *Teamserver) FindSystemPackages(`
- Defined: `teamserver/cmd/server/teamserver.go:842`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EndpointAdd (function) `func (t *Teamserver) EndpointAdd(`
- Defined: `teamserver/cmd/server/teamserver.go:933`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

### EndpointRemove (function) `func (t *Teamserver) EndpointRemove(`
- Defined: `teamserver/cmd/server/teamserver.go:945`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/db/db.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`, `teamserver/pkg/webhook/webhook.go`

## teamserver/main.go

### main (function) `func main(`
- Defined: `teamserver/main.go:6`
- Depends on: `teamserver/cmd/cmd.go`, `teamserver/pkg/logger/logger.go`

## teamserver/pkg/agent/agent.go

### BuildPayloadMessage (function) `func BuildPayloadMessage(`
- Defined: `teamserver/pkg/agent/agent.go:29`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ParseHeader (function) `func ParseHeader(`
- Defined: `teamserver/pkg/agent/agent.go:181`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### RegisterInfoToInstance (function) `func RegisterInfoToInstance(`
- Defined: `teamserver/pkg/agent/agent.go:215`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ParseDemonRegisterRequest (function) `func ParseDemonRegisterRequest(`
- Defined: `teamserver/pkg/agent/agent.go:328`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### IsKnownRequestID (function) `func (a *Agent) IsKnownRequestID(`
- Defined: `teamserver/pkg/agent/agent.go:609`
- Doc: check that the request the agent is valid
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### AddRequest (function) `func (a *Agent) AddRequest(`
- Defined: `teamserver/pkg/agent/agent.go:632`
- Doc: the operator added a new request/command
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### RequestCompleted (function) `func (a *Agent) RequestCompleted(`
- Defined: `teamserver/pkg/agent/agent.go:638`
- Doc: after a request has been completed, we can forget about the RequestID so that it is no longer valid
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### AddJobToQueue (function) `func (a *Agent) AddJobToQueue(`
- Defined: `teamserver/pkg/agent/agent.go:647`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### GetQueuedJobs (function) `func (a *Agent) GetQueuedJobs(`
- Defined: `teamserver/pkg/agent/agent.go:661`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### UpdateLastCallback (function) `func (a *Agent) UpdateLastCallback(`
- Defined: `teamserver/pkg/agent/agent.go:739`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PivotAddJob (function) `func (a *Agent) PivotAddJob(`
- Defined: `teamserver/pkg/agent/agent.go:746`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### DownloadAdd (function) `func (a *Agent) DownloadAdd(`
- Defined: `teamserver/pkg/agent/agent.go:816`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### DownloadWrite (function) `func (a *Agent) DownloadWrite(`
- Defined: `teamserver/pkg/agent/agent.go:865`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### DownloadClose (function) `func (a *Agent) DownloadClose(`
- Defined: `teamserver/pkg/agent/agent.go:888`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### DownloadGet (function) `func (a *Agent) DownloadGet(`
- Defined: `teamserver/pkg/agent/agent.go:902`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdNew (function) `func (a *Agent) PortFwdNew(`
- Defined: `teamserver/pkg/agent/agent.go:911`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdGet (function) `func (a *Agent) PortFwdGet(`
- Defined: `teamserver/pkg/agent/agent.go:929`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdIsOpen (function) `func (a *Agent) PortFwdIsOpen(`
- Defined: `teamserver/pkg/agent/agent.go:948`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdOpen (function) `func (a *Agent) PortFwdOpen(`
- Defined: `teamserver/pkg/agent/agent.go:958`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdWrite (function) `func (a *Agent) PortFwdWrite(`
- Defined: `teamserver/pkg/agent/agent.go:979`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdRead (function) `func (a *Agent) PortFwdRead(`
- Defined: `teamserver/pkg/agent/agent.go:997`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### PortFwdClose (function) `func (a *Agent) PortFwdClose(`
- Defined: `teamserver/pkg/agent/agent.go:1023`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### SocksClientAdd (function) `func (a *Agent) SocksClientAdd(`
- Defined: `teamserver/pkg/agent/agent.go:1053`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### SocksClientGet (function) `func (a *Agent) SocksClientGet(`
- Defined: `teamserver/pkg/agent/agent.go:1073`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### SocksClientRead (function) `func (a *Agent) SocksClientRead(`
- Defined: `teamserver/pkg/agent/agent.go:1096`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### SocksClientClose (function) `func (a *Agent) SocksClientClose(`
- Defined: `teamserver/pkg/agent/agent.go:1130`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### SocksServerRemove (function) `func (a *Agent) SocksServerRemove(`
- Defined: `teamserver/pkg/agent/agent.go:1163`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ToMap (function) `func (a *Agent) ToMap(`
- Defined: `teamserver/pkg/agent/agent.go:1193`
- Doc: ToMap returns the agent info as a map
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ToJson (function) `func (a *Agent) ToJson(`
- Defined: `teamserver/pkg/agent/agent.go:1224`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### AgentsAppend (function) `func (agents *Agents) AgentsAppend(`
- Defined: `teamserver/pkg/agent/agent.go:1238`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### getWindowsVersionString (function) `func getWindowsVersionString(`
- Defined: `teamserver/pkg/agent/agent.go:1243`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

## teamserver/pkg/agent/demons.go

### UploadMemFileInChunks (function) `func (a *Agent) UploadMemFileInChunks(`
- Defined: `teamserver/pkg/agent/demons.go:31`
- Doc: we upload heavy files to the implant in chunks, so SMB agents can handle the size
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/socks/socks.go`, `teamserver/pkg/utils/utils.go`

### TeamserverTaskPrepare (function) `func (a *Agent) TeamserverTaskPrepare(`
- Defined: `teamserver/pkg/agent/demons.go:64`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/socks/socks.go`, `teamserver/pkg/utils/utils.go`

### TaskPrepare (function) `func (a *Agent) TaskPrepare(`
- Defined: `teamserver/pkg/agent/demons.go:128`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/socks/socks.go`, `teamserver/pkg/utils/utils.go`

### TaskDispatch (function) `func (a *Agent) TaskDispatch(`
- Defined: `teamserver/pkg/agent/demons.go:2285`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/socks/socks.go`, `teamserver/pkg/utils/utils.go`

### Console (function) `func (a *Agent) Console(`
- Defined: `teamserver/pkg/agent/demons.go:6430`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/socks/socks.go`, `teamserver/pkg/utils/utils.go`

## teamserver/pkg/common/builder/builder.go

### NewBuilder (function) `func NewBuilder(`
- Defined: `teamserver/pkg/common/builder/builder.go:141`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetSilent (function) `func (b *Builder) SetSilent(`
- Defined: `teamserver/pkg/common/builder/builder.go:213`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### Build (function) `func (b *Builder) Build(`
- Defined: `teamserver/pkg/common/builder/builder.go:217`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetListener (function) `func (b *Builder) SetListener(`
- Defined: `teamserver/pkg/common/builder/builder.go:459`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetPatchConfig (function) `func (b *Builder) SetPatchConfig(`
- Defined: `teamserver/pkg/common/builder/builder.go:464`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetFormat (function) `func (b *Builder) SetFormat(`
- Defined: `teamserver/pkg/common/builder/builder.go:481`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetArch (function) `func (b *Builder) SetArch(`
- Defined: `teamserver/pkg/common/builder/builder.go:485`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetConfig (function) `func (b *Builder) SetConfig(`
- Defined: `teamserver/pkg/common/builder/builder.go:489`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetOutputPath (function) `func (b *Builder) SetOutputPath(`
- Defined: `teamserver/pkg/common/builder/builder.go:501`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### SetExtension (function) `func (b *Builder) SetExtension(`
- Defined: `teamserver/pkg/common/builder/builder.go:505`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### GetOutputPath (function) `func (b *Builder) GetOutputPath(`
- Defined: `teamserver/pkg/common/builder/builder.go:509`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### Patch (function) `func (b *Builder) Patch(`
- Defined: `teamserver/pkg/common/builder/builder.go:513`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### PatchConfig (function) `func (b *Builder) PatchConfig(`
- Defined: `teamserver/pkg/common/builder/builder.go:561`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### GetPayloadBytes (function) `func (b *Builder) GetPayloadBytes(`
- Defined: `teamserver/pkg/common/builder/builder.go:1024`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### Cmd (function) `func (b *Builder) Cmd(`
- Defined: `teamserver/pkg/common/builder/builder.go:1064`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### CompileCmd (function) `func (b *Builder) CompileCmd(`
- Defined: `teamserver/pkg/common/builder/builder.go:1090`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### GetListenerDefines (function) `func (b *Builder) GetListenerDefines(`
- Defined: `teamserver/pkg/common/builder/builder.go:1102`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

### DeletePayload (function) `func (b *Builder) DeletePayload(`
- Defined: `teamserver/pkg/common/builder/builder.go:1122`
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/utils/utils.go`
- Imported by: `teamserver/cmd/server/dispatch.go`

## teamserver/pkg/common/certs/https.go

### randomState (function) `func randomState(`
- Defined: `teamserver/pkg/common/certs/https.go:115`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomLocality (function) `func randomLocality(`
- Defined: `teamserver/pkg/common/certs/https.go:123`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomStreetAddress (function) `func randomStreetAddress(`
- Defined: `teamserver/pkg/common/certs/https.go:132`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomProvinceLocalityStreetAddress (function) `func randomProvinceLocalityStreetAddress(`
- Defined: `teamserver/pkg/common/certs/https.go:137`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomPostalCode (function) `func randomPostalCode(`
- Defined: `teamserver/pkg/common/certs/https.go:144`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomSubject (function) `func randomSubject(`
- Defined: `teamserver/pkg/common/certs/https.go:153`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomOrganization (function) `func randomOrganization(`
- Defined: `teamserver/pkg/common/certs/https.go:166`
- Depends on: `teamserver/pkg/logger/logger.go`

### publicKey (function) `func publicKey(`
- Defined: `teamserver/pkg/common/certs/https.go:182`
- Depends on: `teamserver/pkg/logger/logger.go`

### randomInt (function) `func randomInt(`
- Defined: `teamserver/pkg/common/certs/https.go:193`
- Depends on: `teamserver/pkg/logger/logger.go`

### pemBlockForKey (function) `func pemBlockForKey(`
- Defined: `teamserver/pkg/common/certs/https.go:200`
- Depends on: `teamserver/pkg/logger/logger.go`

### generateCertificate (function) `func generateCertificate(`
- Defined: `teamserver/pkg/common/certs/https.go:216`
- Depends on: `teamserver/pkg/logger/logger.go`

### HTTPSGenerateRSACertificate (function) `func HTTPSGenerateRSACertificate(`
- Defined: `teamserver/pkg/common/certs/https.go:300`
- Doc: HTTPSGenerateRSACertificate - Generate a server certificate signed with a given CA
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/common/crypt/aes.go

### XCryptBytesAES256 (function) `func XCryptBytesAES256(`
- Defined: `teamserver/pkg/common/crypt/aes.go:10`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/common/packer/packer.go

### NewPacker (function) `func NewPacker(`
- Defined: `teamserver/pkg/common/packer/packer.go:22`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddInt64 (function) `func (p *Packer) AddInt64(`
- Defined: `teamserver/pkg/common/packer/packer.go:29`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddInt32 (function) `func (p *Packer) AddInt32(`
- Defined: `teamserver/pkg/common/packer/packer.go:37`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddInt (function) `func (p *Packer) AddInt(`
- Defined: `teamserver/pkg/common/packer/packer.go:45`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddUInt32 (function) `func (p *Packer) AddUInt32(`
- Defined: `teamserver/pkg/common/packer/packer.go:54`
- Doc: AddUInt32 use a much as possible this function
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddString (function) `func (p *Packer) AddString(`
- Defined: `teamserver/pkg/common/packer/packer.go:62`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddWString (function) `func (p *Packer) AddWString(`
- Defined: `teamserver/pkg/common/packer/packer.go:66`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddBytes (function) `func (p *Packer) AddBytes(`
- Defined: `teamserver/pkg/common/packer/packer.go:70`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### Build (function) `func (p *Packer) Build(`
- Defined: `teamserver/pkg/common/packer/packer.go:80`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### Buffer (function) `func (p *Packer) Buffer(`
- Defined: `teamserver/pkg/common/packer/packer.go:95`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### Size (function) `func (p *Packer) Size(`
- Defined: `teamserver/pkg/common/packer/packer.go:99`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

### AddOwnSizeFirst (function) `func (p *Packer) AddOwnSizeFirst(`
- Defined: `teamserver/pkg/common/packer/packer.go:103`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/pkg/agent/agent.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/handlers/handlers.go`

## teamserver/pkg/common/parser/parser.go

### NewParser (function) `func NewParser(`
- Defined: `teamserver/pkg/common/parser/parser.go:24`

### CanIRead (function) `func (p *Parser) CanIRead(`
- Defined: `teamserver/pkg/common/parser/parser.go:31`

### ParseInt32 (function) `func (p *Parser) ParseInt32(`
- Defined: `teamserver/pkg/common/parser/parser.go:82`

### ParseInt64 (function) `func (p *Parser) ParseInt64(`
- Defined: `teamserver/pkg/common/parser/parser.go:106`

### ParseBool (function) `func (p *Parser) ParseBool(`
- Defined: `teamserver/pkg/common/parser/parser.go:130`

### ParsePointer (function) `func (p *Parser) ParsePointer(`
- Defined: `teamserver/pkg/common/parser/parser.go:154`

### SetBigEndian (function) `func (p *Parser) SetBigEndian(`
- Defined: `teamserver/pkg/common/parser/parser.go:158`

### ParseBytes (function) `func (p *Parser) ParseBytes(`
- Defined: `teamserver/pkg/common/parser/parser.go:162`

### ParseAtLeastBytes (function) `func (p *Parser) ParseAtLeastBytes(`
- Defined: `teamserver/pkg/common/parser/parser.go:177`

### ParseUTF16String (function) `func (p *Parser) ParseUTF16String(`
- Defined: `teamserver/pkg/common/parser/parser.go:189`

### ParseString (function) `func (p *Parser) ParseString(`
- Defined: `teamserver/pkg/common/parser/parser.go:193`

### Length (function) `func (p *Parser) Length(`
- Defined: `teamserver/pkg/common/parser/parser.go:197`

### Buffer (function) `func (p *Parser) Buffer(`
- Defined: `teamserver/pkg/common/parser/parser.go:201`

### DecryptBuffer (function) `func (p *Parser) DecryptBuffer(`
- Defined: `teamserver/pkg/common/parser/parser.go:205`

## teamserver/pkg/common/util.go

### ParseWorkingHours (function) `func ParseWorkingHours(`
- Defined: `teamserver/pkg/common/util.go:26`
- Depends on: `teamserver/pkg/logger/logger.go`

### Bmp2Png (function) `func Bmp2Png(`
- Defined: `teamserver/pkg/common/util.go:76`
- Depends on: `teamserver/pkg/logger/logger.go`

### DecodeUTF16 (function) `func DecodeUTF16(`
- Defined: `teamserver/pkg/common/util.go:99`
- Depends on: `teamserver/pkg/logger/logger.go`

### EncodeUTF16 (function) `func EncodeUTF16(`
- Defined: `teamserver/pkg/common/util.go:118`
- Depends on: `teamserver/pkg/logger/logger.go`

### EncodeUTF8 (function) `func EncodeUTF8(`
- Defined: `teamserver/pkg/common/util.go:135`
- Depends on: `teamserver/pkg/logger/logger.go`

### ByteCountSI (function) `func ByteCountSI(`
- Defined: `teamserver/pkg/common/util.go:144`
- Depends on: `teamserver/pkg/logger/logger.go`

### XorCipher (function) `func XorCipher(`
- Defined: `teamserver/pkg/common/util.go:158`
- Depends on: `teamserver/pkg/logger/logger.go`

### RandomString (function) `func RandomString(`
- Defined: `teamserver/pkg/common/util.go:166`
- Depends on: `teamserver/pkg/logger/logger.go`

### Int32ToLittle (function) `func Int32ToLittle(`
- Defined: `teamserver/pkg/common/util.go:175`
- Depends on: `teamserver/pkg/logger/logger.go`

### StripNull (function) `func StripNull(`
- Defined: `teamserver/pkg/common/util.go:181`
- Depends on: `teamserver/pkg/logger/logger.go`

### PercentageChange (function) `func PercentageChange(`
- Defined: `teamserver/pkg/common/util.go:185`
- Depends on: `teamserver/pkg/logger/logger.go`

### IpStringToInt32 (function) `func IpStringToInt32(`
- Defined: `teamserver/pkg/common/util.go:189`
- Depends on: `teamserver/pkg/logger/logger.go`

### Int32ToIpString (function) `func Int32ToIpString(`
- Defined: `teamserver/pkg/common/util.go:198`
- Depends on: `teamserver/pkg/logger/logger.go`

### EpochTimeToSystemTime (function) `func EpochTimeToSystemTime(`
- Defined: `teamserver/pkg/common/util.go:209`
- Depends on: `teamserver/pkg/logger/logger.go`

### GetRandomChar (function) `func GetRandomChar(`
- Defined: `teamserver/pkg/common/util.go:222`
- Depends on: `teamserver/pkg/logger/logger.go`

### GeneratePipeName (function) `func GeneratePipeName(`
- Defined: `teamserver/pkg/common/util.go:227`
- Doc: generate a PipeName from a name template
- Depends on: `teamserver/pkg/logger/logger.go`

### GetInterfaceIpv4Addr (function) `func GetInterfaceIpv4Addr(`
- Defined: `teamserver/pkg/common/util.go:279`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/db/agents.go

### AgentAdd (function) `func (db *DB) AgentAdd(`
- Defined: `teamserver/pkg/db/agents.go:12`

### AgentUpdate (function) `func (db *DB) AgentUpdate(`
- Defined: `teamserver/pkg/db/agents.go:81`

### AgentHasDied (function) `func (db *DB) AgentHasDied(`
- Defined: `teamserver/pkg/db/agents.go:145`

### AgentExist (function) `func (db *DB) AgentExist(`
- Defined: `teamserver/pkg/db/agents.go:163`

### AgentRemove (function) `func (db *DB) AgentRemove(`
- Defined: `teamserver/pkg/db/agents.go:192`

### AgentAll (function) `func (db *DB) AgentAll(`
- Defined: `teamserver/pkg/db/agents.go:211`

## teamserver/pkg/db/db.go

### DatabaseNew (function) `func DatabaseNew(`
- Defined: `teamserver/pkg/db/db.go:16`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### init (function) `func (db *DB) init(`
- Defined: `teamserver/pkg/db/db.go:48`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### Existed (function) `func (db *DB) Existed(`
- Defined: `teamserver/pkg/db/db.go:69`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### Path (function) `func (db *DB) Path(`
- Defined: `teamserver/pkg/db/db.go:73`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

## teamserver/pkg/db/links.go

### LinkAdd (function) `func (db *DB) LinkAdd(`
- Defined: `teamserver/pkg/db/links.go:8`

### LinkExist (function) `func (db *DB) LinkExist(`
- Defined: `teamserver/pkg/db/links.go:46`

### ParentOf (function) `func (db *DB) ParentOf(`
- Defined: `teamserver/pkg/db/links.go:75`

### LinksOf (function) `func (db *DB) LinksOf(`
- Defined: `teamserver/pkg/db/links.go:104`

### LinkRemove (function) `func (db *DB) LinkRemove(`
- Defined: `teamserver/pkg/db/links.go:136`

## teamserver/pkg/db/listeners.go

### ListenerAdd (function) `func (db *DB) ListenerAdd(`
- Defined: `teamserver/pkg/db/listeners.go:8`

### ListenerExist (function) `func (db *DB) ListenerExist(`
- Defined: `teamserver/pkg/db/listeners.go:46`

### ListenerAll (function) `func (db *DB) ListenerAll(`
- Defined: `teamserver/pkg/db/listeners.go:66`

### ListenerCount (function) `func (db *DB) ListenerCount(`
- Defined: `teamserver/pkg/db/listeners.go:107`

### ListenerNames (function) `func (db *DB) ListenerNames(`
- Defined: `teamserver/pkg/db/listeners.go:126`

### ListenerRemove (function) `func (db *DB) ListenerRemove(`
- Defined: `teamserver/pkg/db/listeners.go:152`

## teamserver/pkg/events/chatlog.go

### NewUserConnected (function) `func (chatLog) NewUserConnected(`
- Defined: `teamserver/pkg/events/chatlog.go:11`

### UserDisconnected (function) `func (chatLog) UserDisconnected(`
- Defined: `teamserver/pkg/events/chatlog.go:27`

## teamserver/pkg/events/demons.go

### NewDemon (function) `func (demons) NewDemon(`
- Defined: `teamserver/pkg/events/demons.go:19`
- Depends on: `teamserver/pkg/logr/logr.go`

### DemonOutput (function) `func (demons) DemonOutput(`
- Defined: `teamserver/pkg/events/demons.go:83`
- Depends on: `teamserver/pkg/logr/logr.go`

### CallBack (function) `func (demons) CallBack(`
- Defined: `teamserver/pkg/events/demons.go:105`
- Depends on: `teamserver/pkg/logr/logr.go`

### MarkAs (function) `func (demons) MarkAs(`
- Defined: `teamserver/pkg/events/demons.go:121`
- Depends on: `teamserver/pkg/logr/logr.go`

## teamserver/pkg/events/events.go

### Authenticated (function) `func Authenticated(`
- Defined: `teamserver/pkg/events/events.go:22`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/service/service.go`

### UserAlreadyExits (function) `func UserAlreadyExits(`
- Defined: `teamserver/pkg/events/events.go:56`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/service/service.go`

### UserDoNotExists (function) `func UserDoNotExists(`
- Defined: `teamserver/pkg/events/events.go:72`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/service/service.go`

### SendProfile (function) `func SendProfile(`
- Defined: `teamserver/pkg/events/events.go:88`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/profile.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/service/service.go`

## teamserver/pkg/events/gate.go

### SendStageless (function) `func (g gate) SendStageless(`
- Defined: `teamserver/pkg/events/gate.go:12`

### SendConsoleMessage (function) `func (g gate) SendConsoleMessage(`
- Defined: `teamserver/pkg/events/gate.go:30`

## teamserver/pkg/events/listeners.go

### ListenerAdd (function) `func (listeners) ListenerAdd(`
- Defined: `teamserver/pkg/events/listeners.go:15`
- Depends on: `teamserver/pkg/handlers/handlers.go`

### ListenerEdit (function) `func (listeners) ListenerEdit(`
- Defined: `teamserver/pkg/events/listeners.go:97`
- Depends on: `teamserver/pkg/handlers/handlers.go`

### ListenerError (function) `func (listeners) ListenerError(`
- Defined: `teamserver/pkg/events/listeners.go:154`
- Depends on: `teamserver/pkg/handlers/handlers.go`

### ListenerRemove (function) `func (listeners) ListenerRemove(`
- Defined: `teamserver/pkg/events/listeners.go:173`
- Depends on: `teamserver/pkg/handlers/handlers.go`

### ListenerMark (function) `func (listeners) ListenerMark(`
- Defined: `teamserver/pkg/events/listeners.go:187`
- Depends on: `teamserver/pkg/handlers/handlers.go`

## teamserver/pkg/events/service.go

### AgentRegister (function) `func (service) AgentRegister(`
- Defined: `teamserver/pkg/events/service.go:11`

### ListenerRegister (function) `func (service) ListenerRegister(`
- Defined: `teamserver/pkg/events/service.go:25`

## teamserver/pkg/events/teamserver.go

### Logger (function) `func (teamserver) Logger(`
- Defined: `teamserver/pkg/events/teamserver.go:11`

### Profile (function) `func (teamserver) Profile(`
- Defined: `teamserver/pkg/events/teamserver.go:25`

## teamserver/pkg/handlers/external.go

### NewExternal (function) `func NewExternal(`
- Defined: `teamserver/pkg/handlers/external.go:15`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`

### Start (function) `func (e *External) Start(`
- Defined: `teamserver/pkg/handlers/external.go:24`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`

### Request (function) `func (e *External) Request(`
- Defined: `teamserver/pkg/handlers/external.go:37`
- Doc: Request The way the external c2 handles or parses the request is like the HTTP listener. Only one agent package can be p
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/logger/logger.go`

## teamserver/pkg/handlers/handlers.go

### parseAgentRequest (function) `func parseAgentRequest(`
- Defined: `teamserver/pkg/handlers/handlers.go:23`
- Doc: parseAgentRequest parses the agent request and handles the given data. return 2 types. Response is the data/bytes once t
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/listeners.go`

### handleDemonAgent (function) `func handleDemonAgent(`
- Defined: `teamserver/pkg/handlers/handlers.go:56`
- Doc: handleDemonAgent parse the demon agent request return 2 types:  Response bytes.Buffer Success  bool
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/listeners.go`

### handleServiceAgent (function) `func handleServiceAgent(`
- Defined: `teamserver/pkg/handlers/handlers.go:311`
- Doc: handleServiceAgent handles and parses a service agent request return 2 types:  Response bytes.Buffer Success  bool
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/listeners.go`

### notifyTaskSize (function) `func notifyTaskSize(`
- Defined: `teamserver/pkg/handlers/handlers.go:349`
- Doc: notifyTaskSize notifies every connected operator client how much we send to agent.
- Depends on: `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/listeners.go`

## teamserver/pkg/handlers/http.go

### NewConfigHttp (function) `func NewConfigHttp(`
- Defined: `teamserver/pkg/handlers/http.go:24`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`

### generateCertFiles (function) `func (h *HTTP) generateCertFiles(`
- Defined: `teamserver/pkg/handlers/http.go:32`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`

### fake404 (function) `func (h *HTTP) fake404(`
- Defined: `teamserver/pkg/handlers/http.go:80`
- Doc: fake nginx 404 page
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`

### request (function) `func (h *HTTP) request(`
- Defined: `teamserver/pkg/handlers/http.go:93`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`

### Start (function) `func (h *HTTP) Start(`
- Defined: `teamserver/pkg/handlers/http.go:203`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`

### Stop (function) `func (h *HTTP) Stop(`
- Defined: `teamserver/pkg/handlers/http.go:277`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/types.go`, `teamserver/pkg/webhook/webhook.go`

## teamserver/pkg/handlers/smb.go

### NewPivotSmb (function) `func NewPivotSmb(`
- Defined: `teamserver/pkg/handlers/smb.go:8`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`

### Start (function) `func (s *SMB) Start(`
- Defined: `teamserver/pkg/handlers/smb.go:14`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`

## teamserver/pkg/logger/global.go

### init (function) `func init(`
- Defined: `teamserver/pkg/logger/global.go:11`

### NewLogger (function) `func NewLogger(`
- Defined: `teamserver/pkg/logger/global.go:15`

### Info (function) `func Info(`
- Defined: `teamserver/pkg/logger/global.go:27`

### Good (function) `func Good(`
- Defined: `teamserver/pkg/logger/global.go:31`

### Debug (function) `func Debug(`
- Defined: `teamserver/pkg/logger/global.go:35`

### DebugError (function) `func DebugError(`
- Defined: `teamserver/pkg/logger/global.go:39`

### Warn (function) `func Warn(`
- Defined: `teamserver/pkg/logger/global.go:43`

### Error (function) `func Error(`
- Defined: `teamserver/pkg/logger/global.go:47`

### Fatal (function) `func Fatal(`
- Defined: `teamserver/pkg/logger/global.go:51`

### Panic (function) `func Panic(`
- Defined: `teamserver/pkg/logger/global.go:55`

### SetDebug (function) `func SetDebug(`
- Defined: `teamserver/pkg/logger/global.go:59`

### ShowTime (function) `func ShowTime(`
- Defined: `teamserver/pkg/logger/global.go:63`

### SetStdOut (function) `func SetStdOut(`
- Defined: `teamserver/pkg/logger/global.go:67`

## teamserver/pkg/logger/logger.go

### FunctionTrace (function) `func FunctionTrace(`
- Defined: `teamserver/pkg/logger/logger.go:15`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Info (function) `func (logger *Logger) Info(`
- Defined: `teamserver/pkg/logger/logger.go:43`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Good (function) `func (logger *Logger) Good(`
- Defined: `teamserver/pkg/logger/logger.go:52`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Debug (function) `func (logger *Logger) Debug(`
- Defined: `teamserver/pkg/logger/logger.go:61`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### DebugError (function) `func (logger *Logger) DebugError(`
- Defined: `teamserver/pkg/logger/logger.go:74`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Warn (function) `func (logger *Logger) Warn(`
- Defined: `teamserver/pkg/logger/logger.go:87`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Error (function) `func (logger *Logger) Error(`
- Defined: `teamserver/pkg/logger/logger.go:96`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Fatal (function) `func (logger *Logger) Fatal(`
- Defined: `teamserver/pkg/logger/logger.go:105`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### Panic (function) `func (logger *Logger) Panic(`
- Defined: `teamserver/pkg/logger/logger.go:115`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### SetDebug (function) `func (logger *Logger) SetDebug(`
- Defined: `teamserver/pkg/logger/logger.go:125`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

### ShowTime (function) `func (logger *Logger) ShowTime(`
- Defined: `teamserver/pkg/logger/logger.go:129`
- Depends on: `teamserver/pkg/colors/colors.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/agent.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/cmd/server/listener.go`, `teamserver/cmd/server/service.go`, `teamserver/cmd/server/teamserver.go`, `teamserver/main.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/common/certs/https.go`, `teamserver/pkg/common/crypt/aes.go`, `teamserver/pkg/common/packer/packer.go`, `teamserver/pkg/common/util.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/handlers/external.go`, `teamserver/pkg/handlers/handlers.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/handlers/smb.go`, `teamserver/pkg/logr/demon.go`, `teamserver/pkg/logr/logr.go`, `teamserver/pkg/logr/server.go`, `teamserver/pkg/packager/packages.go`, `teamserver/pkg/profile/profile.go`, `teamserver/pkg/service/agent.go`, `teamserver/pkg/service/listener.go`, `teamserver/pkg/service/service.go`, `teamserver/pkg/socks/util.go`, `teamserver/pkg/utils/utils.go`

## teamserver/pkg/logr/demon.go

### AddAgentInput (function) `func (l Logr) AddAgentInput(`
- Defined: `teamserver/pkg/logr/demon.go:15`
- Depends on: `teamserver/pkg/logger/logger.go`

### AddAgentRaw (function) `func (l Logr) AddAgentRaw(`
- Defined: `teamserver/pkg/logr/demon.go:50`
- Depends on: `teamserver/pkg/logger/logger.go`

### DemonAddOutput (function) `func (l Logr) DemonAddOutput(`
- Defined: `teamserver/pkg/logr/demon.go:82`
- Depends on: `teamserver/pkg/logger/logger.go`

### DemonAddDownloadedFile (function) `func (l Logr) DemonAddDownloadedFile(`
- Defined: `teamserver/pkg/logr/demon.go:134`
- Depends on: `teamserver/pkg/logger/logger.go`

### DemonSaveScreenshot (function) `func (l Logr) DemonSaveScreenshot(`
- Defined: `teamserver/pkg/logr/demon.go:177`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/logr/listener.go

### ListenerAddKeyCert (function) `func (l Logr) ListenerAddKeyCert(`
- Defined: `teamserver/pkg/logr/listener.go:3`

## teamserver/pkg/logr/logr.go

### NewLogr (function) `func NewLogr(`
- Defined: `teamserver/pkg/logr/logr.go:21`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server.go`, `teamserver/cmd/server/dispatch.go`, `teamserver/pkg/agent/agent.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/events/demons.go`, `teamserver/pkg/handlers/http.go`, `teamserver/pkg/service/service.go`

## teamserver/pkg/logr/server.go

### strip (function) `func strip(`
- Defined: `teamserver/pkg/logr/server.go:12`
- Depends on: `teamserver/pkg/logger/logger.go`

### ServerStdOutInit (function) `func (l Logr) ServerStdOutInit(`
- Defined: `teamserver/pkg/logr/server.go:21`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/packager/packages.go

### NewPackager (function) `func NewPackager(`
- Defined: `teamserver/pkg/packager/packages.go:9`
- Depends on: `teamserver/pkg/logger/logger.go`

### CreatePackage (function) `func (p Packager) CreatePackage(`
- Defined: `teamserver/pkg/packager/packages.go:13`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/profile/profile.go

### NewProfile (function) `func NewProfile(`
- Defined: `teamserver/pkg/profile/profile.go:13`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/service/types.go`

### SetProfile (function) `func (p *Profile) SetProfile(`
- Defined: `teamserver/pkg/profile/profile.go:17`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/service/types.go`

### ServerHost (function) `func (p *Profile) ServerHost(`
- Defined: `teamserver/pkg/profile/profile.go:32`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/service/types.go`

### ServerPort (function) `func (p *Profile) ServerPort(`
- Defined: `teamserver/pkg/profile/profile.go:39`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/service/types.go`

### ListOfUsernames (function) `func (p *Profile) ListOfUsernames(`
- Defined: `teamserver/pkg/profile/profile.go:46`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/service/types.go`

## teamserver/pkg/profile/yaotl/diagnostic.go

### Error (function) `func (d *Diagnostic) Error(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic.go:76`
- Doc: error implementation, so that diagnostics can be returned via APIs that normally deal in vanilla Go errors.  This presen

### Error (function) `func (d Diagnostics) Error(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic.go:82`
- Doc: error implementation, so that sets of diagnostics can be returned via APIs that normally deal in vanilla Go errors.

### Append (function) `func (d Diagnostics) Append(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic.go:104`
- Doc: Append appends a new error to a Diagnostics and return the whole Diagnostics.  This is provided as a convenience for ret

### Extend (function) `func (d Diagnostics) Extend(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic.go:113`
- Doc: Extend concatenates the given Diagnostics with the receiver and returns the whole new Diagnostics.  This is similar to A

### HasErrors (function) `func (d Diagnostics) HasErrors(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic.go:119`
- Doc: HasErrors returns true if the receiver contains any diagnostics of severity DiagError.

### Errs (function) `func (d Diagnostics) Errs(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic.go:128`

## teamserver/pkg/profile/yaotl/diagnostic_text.go

### NewDiagnosticTextWriter (function) `func NewDiagnosticTextWriter(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic_text.go:34`
- Doc: NewDiagnosticTextWriter creates a DiagnosticWriter that writes diagnostics to the given writer as formatted text.  It is

### WriteDiagnostic (function) `func (w *diagnosticTextWriter) WriteDiagnostic(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic_text.go:43`

### WriteDiagnostics (function) `func (w *diagnosticTextWriter) WriteDiagnostics(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic_text.go:208`

### traversalStr (function) `func (w *diagnosticTextWriter) traversalStr(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic_text.go:218`

### valueStr (function) `func (w *diagnosticTextWriter) valueStr(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic_text.go:246`

### contextString (function) `func contextString(`
- Defined: `teamserver/pkg/profile/yaotl/diagnostic_text.go:302`

## teamserver/pkg/profile/yaotl/didyoumean.go

### nameSuggestion (function) `func nameSuggestion(`
- Defined: `teamserver/pkg/profile/yaotl/didyoumean.go:16`
- Doc: nameSuggestion tries to find a name from the given slice of suggested names that is close to the given name and returns 

## teamserver/pkg/profile/yaotl/eval_context.go

### NewChild (function) `func (ctx *EvalContext) NewChild(`
- Defined: `teamserver/pkg/profile/yaotl/eval_context.go:17`
- Doc: NewChild returns a new EvalContext that is a child of the receiver.

### Parent (function) `func (ctx *EvalContext) Parent(`
- Defined: `teamserver/pkg/profile/yaotl/eval_context.go:23`
- Doc: Parent returns the parent of the receiver, or nil if the receiver has no parent.

## teamserver/pkg/profile/yaotl/expr_call.go

### ExprCall (function) `func ExprCall(`
- Defined: `teamserver/pkg/profile/yaotl/expr_call.go:14`
- Doc: ExprCall tests if the given expression is a function call and, if so, extracts the function name and the expressions tha

## teamserver/pkg/profile/yaotl/expr_list.go

### ExprList (function) `func ExprList(`
- Defined: `teamserver/pkg/profile/yaotl/expr_list.go:14`
- Doc: ExprList tests if the given expression is a static list construct and, if so, extracts the expressions that represent th

## teamserver/pkg/profile/yaotl/expr_map.go

### ExprMap (function) `func ExprMap(`
- Defined: `teamserver/pkg/profile/yaotl/expr_map.go:14`
- Doc: ExprMap tests if the given expression is a static map construct and, if so, extracts the expressions that represent the 

## teamserver/pkg/profile/yaotl/expr_unwrap.go

### UnwrapExpression (function) `func UnwrapExpression(`
- Defined: `teamserver/pkg/profile/yaotl/expr_unwrap.go:28`
- Doc: type-assert on the physical AST types used by the underlying syntax.  Unwrapping an expression may modify its behavior b

### UnwrapExpressionUntil (function) `func UnwrapExpressionUntil(`
- Defined: `teamserver/pkg/profile/yaotl/expr_unwrap.go:54`
- Doc: UnwrapExpressionUntil is similar to UnwrapExpression except it gives the caller an opportunity to test each level of unw

## teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go

### CustomExpressionDecoderForType (function) `func CustomExpressionDecoderForType(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go:48`
- Doc: CustomExpressionDecoderForType takes any cty type and returns its custom expression decoder implementation if it has one
- Imported by: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go`, `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go`, `teamserver/pkg/profile/yaotl/hcldec/spec.go`, `teamserver/pkg/profile/yaotl/hclsyntax/expression.go`

## teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go

### ExpressionVal (function) `func ExpressionVal(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:27`
- Doc: ExpressionVal returns a new cty value of type ExpressionType, wrapping the given expression.

### ExpressionFromVal (function) `func ExpressionFromVal(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:33`
- Doc: ExpressionFromVal returns the expression encapsulated in the given value, or panics if the value is not a known value of

### ExpressionClosureVal (function) `func ExpressionClosureVal(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:58`
- Doc: ExpressionClosureVal returns a new cty value of type ExpressionClosureType, wrapping the given expression closure.

### Value (function) `func (c *ExpressionClosure) Value(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:64`
- Doc: Value evaluates the closure's expression using the closure's EvalContext, returning the result.

### ExpressionClosureFromVal (function) `func ExpressionClosureFromVal(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:75`
- Doc: ExpressionClosureFromVal returns the expression closure encapsulated in the given value, or panics if the value is not a

### init (function) `func init(`
- Defined: `teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go:82`

## teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go

### Content (function) `func (b *expandBody) Content(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:29`

### PartialContent (function) `func (b *expandBody) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:46`

### extendSchema (function) `func (b *expandBody) extendSchema(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:85`

### prepareAttributes (function) `func (b *expandBody) prepareAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:121`

### expandBlocks (function) `func (b *expandBody) expandBlocks(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:151`

### expandChild (function) `func (b *expandBody) expandChild(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:232`

### JustAttributes (function) `func (b *expandBody) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:239`

### MissingItemRange (function) `func (b *expandBody) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go:246`

## teamserver/pkg/profile/yaotl/ext/dynblock/expand_body_test.go

### TestExpand (function) `func TestExpand(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body_test.go:13`

### TestExpandUnknownBodies (function) `func TestExpandUnknownBodies(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_body_test.go:336`

## teamserver/pkg/profile/yaotl/ext/dynblock/expand_spec.go

### decodeSpec (function) `func (b *expandBody) decodeSpec(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_spec.go:22`

### newBlock (function) `func (s *expandSpec) newBlock(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expand_spec.go:153`

## teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go

### Variables (function) `func (e exprWrap) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go:13`

### Value (function) `func (e exprWrap) Value(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go:33`

### UnwrapExpression (function) `func (e exprWrap) UnwrapExpression(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go:40`
- Doc: UnwrapExpression returns the expression being wrapped by this instance. This allows the original expression to be recove

## teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go

### MakeIteration (function) `func (s *expandSpec) MakeIteration(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:15`

### Object (function) `func (i *iteration) Object(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:24`

### EvalContext (function) `func (i *iteration) EvalContext(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:31`

### MakeChild (function) `func (i *iteration) MakeChild(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go:45`

## teamserver/pkg/profile/yaotl/ext/dynblock/public.go

### Expand (function) `func Expand(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/public.go:42`
- Doc: dynamic "child" { for_each = child_objs content { dynamic "grandchild" { for_each = child.value.children labels   = [gra

## teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go

### Unknown (function) `func (b unknownBody) Unknown(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:24`
- Doc: hcldec.UnkownBody impl

### Content (function) `func (b unknownBody) Content(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:28`

### PartialContent (function) `func (b unknownBody) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:38`

### JustAttributes (function) `func (b unknownBody) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:49`

### MissingItemRange (function) `func (b unknownBody) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:59`

### fixupContent (function) `func (b unknownBody) fixupContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:63`

### fixupAttrs (function) `func (b unknownBody) fixupAttrs(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go:78`

## teamserver/pkg/profile/yaotl/ext/dynblock/variables.go

### WalkVariables (function) `func WalkVariables(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:19`
- Doc: WalkVariables begins the recursive process of walking all expressions and nested blocks in the given body and its child 

### WalkExpandVariables (function) `func WalkExpandVariables(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:32`
- Doc: WalkExpandVariables is like Variables but it includes only the variables required for successful block expansion, ignori

### Body (function) `func (c WalkVariablesChild) Body(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:58`
- Doc: Body returns the HCL Body associated with the child node, in case the caller wants to do some sort of inspection of it i

### Visit (function) `func (n WalkVariablesNode) Visit(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:70`
- Doc: Visit returns the variable traversals required for any "dynamic" blocks directly in the body associated with this node, 

### extendSchema (function) `func (n WalkVariablesNode) extendSchema(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables.go:172`

## teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go

### VariablesHCLDec (function) `func VariablesHCLDec(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go:16`
- Doc: VariablesHCLDec is a wrapper around WalkVariables that uses the given hcldec specification to automatically drive the re

### ExpandVariablesHCLDec (function) `func ExpandVariablesHCLDec(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go:25`
- Doc: ExpandVariablesHCLDec is like VariablesHCLDec but it includes only the minimal set of variables required to call Expand,

### walkVariablesWithHCLDec (function) `func walkVariablesWithHCLDec(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go:30`

## teamserver/pkg/profile/yaotl/ext/dynblock/variables_test.go

### TestVariables (function) `func TestVariables(`
- Defined: `teamserver/pkg/profile/yaotl/ext/dynblock/variables_test.go:16`

## teamserver/pkg/profile/yaotl/ext/transform/error.go

### NewErrorBody (function) `func NewErrorBody(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:17`
- Doc: NewErrorBody returns a hcl.Body that returns the given diagnostics whenever any of its content-access methods are called

### BodyWithDiagnostics (function) `func BodyWithDiagnostics(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:39`
- Doc: BodyWithDiagnostics returns a hcl.Body that wraps another hcl.Body and emits the given diagnostics for any content-extra

### Content (function) `func (b diagBody) Content(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:56`

### PartialContent (function) `func (b diagBody) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:68`

### JustAttributes (function) `func (b diagBody) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:80`

### MissingItemRange (function) `func (b diagBody) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:92`

### emptyContent (function) `func (b diagBody) emptyContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/error.go:104`

## teamserver/pkg/profile/yaotl/ext/transform/transform.go

### Shallow (function) `func Shallow(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:9`
- Doc: Shallow is equivalent to calling transformer.TransformBody(body), and is provided only for completeness of the top-level

### Deep (function) `func Deep(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:24`
- Doc: Deep applies the given transform to the given body and then wraps the result such that any descendent blocks that are de

### Content (function) `func (w deepWrapper) Content(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:39`

### PartialContent (function) `func (w deepWrapper) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:45`

### transformContent (function) `func (w deepWrapper) transformContent(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:51`

### JustAttributes (function) `func (w deepWrapper) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:76`

### MissingItemRange (function) `func (w deepWrapper) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform.go:81`

## teamserver/pkg/profile/yaotl/ext/transform/transform_test.go

### TestDeep (function) `func TestDeep(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transform_test.go:16`

## teamserver/pkg/profile/yaotl/ext/transform/transformer.go

### TransformBody (function) `func (f TransformerFunc) TransformBody(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transformer.go:23`
- Doc: TransformBody is an implementation of Transformer.TransformBody.

### Chain (function) `func Chain(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transformer.go:31`
- Doc: Chain takes a slice of transformers and returns a single new Transformer that applies each of the given transformers in 

### TransformBody (function) `func (c chain) TransformBody(`
- Defined: `teamserver/pkg/profile/yaotl/ext/transform/transformer.go:35`

## teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go

### init (function) `func init(`
- Defined: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:30`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### try (function) `func try(`
- Defined: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:61`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### can (function) `func can(`
- Defined: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:109`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### dependsOnUnknowns (function) `func dependsOnUnknowns(`
- Defined: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:130`
- Doc: dependsOnUnknowns returns true if any of the variables that the given expression might access are unknown values or cont
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

## teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc_test.go

### TestTryFunc (function) `func TestTryFunc(`
- Defined: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc_test.go:12`

### TestCanFunc (function) `func TestCanFunc(`
- Defined: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc_test.go:169`

## teamserver/pkg/profile/yaotl/ext/typeexpr/get_type.go

### getType (function) `func getType(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/get_type.go:15`
- Doc: getType is the internal implementation of both Type and TypeConstraint, using the passed flag to distinguish. When const

## teamserver/pkg/profile/yaotl/ext/typeexpr/get_type_test.go

### TestGetType (function) `func TestGetType(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/get_type_test.go:14`

### TestGetTypeJSON (function) `func TestGetTypeJSON(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/get_type_test.go:282`

## teamserver/pkg/profile/yaotl/ext/typeexpr/public.go

### Type (function) `func Type(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/public.go:17`
- Doc: Type attempts to process the given expression as a type expression and, if successful, returns the resulting type. If un

### TypeConstraint (function) `func TypeConstraint(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/public.go:28`
- Doc: TypeConstraint attempts to parse the given expression as a type constraint and, if successful, returns the resulting typ

### TypeString (function) `func TypeString(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/public.go:44`
- Doc: TypeString returns a string rendering of the given type as it would be expected to appear in the HCL native syntax.  Thi

## teamserver/pkg/profile/yaotl/ext/typeexpr/type_string_test.go

### TestTypeString (function) `func TestTypeString(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/type_string_test.go:9`

## teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go

### TypeConstraintVal (function) `func TypeConstraintVal(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:26`
- Doc: TypeConstraintVal constructs a cty.Value whose type is TypeConstraintType.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### TypeConstraintFromVal (function) `func TypeConstraintFromVal(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:35`
- Doc: TypeConstraintFromVal extracts the type from a cty.Value of TypeConstraintType that was previously constructed using Typ
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### init (function) `func init(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:57`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

## teamserver/pkg/profile/yaotl/ext/typeexpr/type_type_test.go

### TestTypeConstraintType (function) `func TestTypeConstraintType(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type_test.go:10`

### TestConvertFunc (function) `func TestConvertFunc(`
- Defined: `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type_test.go:30`

## teamserver/pkg/profile/yaotl/ext/userfunc/decode.go

### decodeUserFunctions (function) `func decodeUserFunctions(`
- Defined: `teamserver/pkg/profile/yaotl/ext/userfunc/decode.go:26`

## teamserver/pkg/profile/yaotl/ext/userfunc/decode_test.go

### TestDecodeUserFunctions (function) `func TestDecodeUserFunctions(`
- Defined: `teamserver/pkg/profile/yaotl/ext/userfunc/decode_test.go:12`

## teamserver/pkg/profile/yaotl/ext/userfunc/public.go

### DecodeUserFunctions (function) `func DecodeUserFunctions(`
- Defined: `teamserver/pkg/profile/yaotl/ext/userfunc/public.go:40`
- Doc: along with a new body that represents the remaining content of the given body which can be used for further processing. 

## teamserver/pkg/profile/yaotl/gohcl/decode.go

### DecodeBody (function) `func DecodeBody(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/decode.go:30`
- Doc: a map, where in the former case the configuration will be decoded using struct tags and in the latter case only attribut

### decodeBodyToValue (function) `func decodeBodyToValue(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/decode.go:39`

### decodeBodyToStruct (function) `func decodeBodyToStruct(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/decode.go:51`

### decodeBodyToMap (function) `func decodeBodyToMap(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/decode.go:234`

### decodeBlockToValue (function) `func decodeBlockToValue(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/decode.go:260`

### DecodeExpression (function) `func DecodeExpression(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/decode.go:306`
- Doc: DecodeExpression extracts the value of the given expression into the given value. This value must be something that goct

## teamserver/pkg/profile/yaotl/gohcl/encode.go

### EncodeIntoBody (function) `func EncodeIntoBody(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/encode.go:36`
- Doc: Any fields tagged as "label" are ignored by this function. Use EncodeAsBlock to produce a whole hclwrite.Block including

### EncodeAsBlock (function) `func EncodeAsBlock(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/encode.go:60`
- Doc: EncodeAsBlock creates a new hclwrite.Block populated with the data from the given value, which must be a struct or point

### populateBody (function) `func populateBody(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/encode.go:85`

## teamserver/pkg/profile/yaotl/gohcl/schema.go

### ImpliedBodySchema (function) `func ImpliedBodySchema(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/schema.go:22`
- Doc: ImpliedBodySchema produces a hcl.BodySchema derived from the type of the given value, which must be a struct value or a 

### getFieldTags (function) `func getFieldTags(`
- Defined: `teamserver/pkg/profile/yaotl/gohcl/schema.go:125`

## teamserver/pkg/profile/yaotl/hcldec/block_labels.go

### labelsForBlock (function) `func labelsForBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/block_labels.go:12`

## teamserver/pkg/profile/yaotl/hcldec/decode.go

### decode (function) `func decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/decode.go:8`

### impliedType (function) `func impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/decode.go:27`

### sourceRange (function) `func sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/decode.go:31`

## teamserver/pkg/profile/yaotl/hcldec/gob.go

### init (function) `func init(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/gob.go:7`

## teamserver/pkg/profile/yaotl/hcldec/public.go

### Decode (function) `func Decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public.go:14`
- Doc: Decode interprets the given body using the given specification and returns the resulting value. If the given body is not

### PartialDecode (function) `func PartialDecode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public.go:25`
- Doc: PartialDecode is like Decode except that it permits "leftover" items in the top-level body, which are returned as a new 

### ImpliedType (function) `func ImpliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public.go:31`
- Doc: ImpliedType returns the value type that should result from decoding the given spec.

### SourceRange (function) `func SourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public.go:51`
- Doc: fulfill the spec.  This can be used if application-level validation detects value errors, to obtain a reasonable SourceR

### ChildBlockTypes (function) `func ChildBlockTypes(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public.go:58`
- Doc: ChildBlockTypes returns a map of all of the child block types declared by the given spec, with block type names as keys 

## teamserver/pkg/profile/yaotl/hcldec/public_test.go

### TestDecode (function) `func TestDecode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public_test.go:13`

### TestSourceRange (function) `func TestSourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/public_test.go:1046`

## teamserver/pkg/profile/yaotl/hcldec/schema.go

### ImpliedSchema (function) `func ImpliedSchema(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/schema.go:10`
- Doc: ImpliedSchema returns the *hcl.BodySchema implied by the given specification. This is the schema that the Decode functio

## teamserver/pkg/profile/yaotl/hcldec/spec.go

### visitSameBodyChildren (function) `func (s ObjectSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:73`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s ObjectSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:79`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s ObjectSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:92`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s ObjectSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:104`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s TupleSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:115`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s TupleSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:121`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s TupleSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:134`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s TupleSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:146`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *AttrSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:162`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded (function) `func (s *AttrSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:167`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### attrSchemata (function) `func (s *AttrSpec) attrSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:177`
- Doc: attrSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *AttrSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:186`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *AttrSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:195`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *AttrSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:237`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *LiteralSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:247`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *LiteralSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:251`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *LiteralSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:255`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *LiteralSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:259`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *ExprSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:273`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded (function) `func (s *ExprSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:278`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *ExprSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:282`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *ExprSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:286`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *ExprSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:291`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *BlockSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:307`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata (function) `func (s *BlockSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:312`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec (function) `func (s *BlockSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:322`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded (function) `func (s *BlockSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:327`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *BlockSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:345`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *BlockSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:392`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *BlockSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:396`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *BlockListSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:423`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata (function) `func (s *BlockListSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:428`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec (function) `func (s *BlockListSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:438`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded (function) `func (s *BlockListSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:443`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *BlockListSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:457`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *BlockListSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:547`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *BlockListSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:551`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *BlockTupleSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:585`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata (function) `func (s *BlockTupleSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:590`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec (function) `func (s *BlockTupleSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:600`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded (function) `func (s *BlockTupleSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:605`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *BlockTupleSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:619`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *BlockTupleSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:671`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *BlockTupleSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:677`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *BlockSetSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:707`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata (function) `func (s *BlockSetSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:712`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec (function) `func (s *BlockSetSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:722`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded (function) `func (s *BlockSetSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:727`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *BlockSetSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:741`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *BlockSetSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:832`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *BlockSetSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:836`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *BlockMapSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:868`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata (function) `func (s *BlockMapSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:873`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec (function) `func (s *BlockMapSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:883`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded (function) `func (s *BlockMapSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:888`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *BlockMapSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:902`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *BlockMapSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:981`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *BlockMapSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:989`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *BlockObjectSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1025`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata (function) `func (s *BlockObjectSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1030`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec (function) `func (s *BlockObjectSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1040`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded (function) `func (s *BlockObjectSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1045`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *BlockObjectSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1059`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *BlockObjectSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1135`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *BlockObjectSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1141`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *BlockAttrsSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1183`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata (function) `func (s *BlockAttrsSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1188`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec (function) `func (s *BlockAttrsSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1198`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### variablesNeeded (function) `func (s *BlockAttrsSpec) variablesNeeded(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1208`
- Doc: specNeedingVariables implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *BlockAttrsSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1235`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *BlockAttrsSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1306`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *BlockAttrsSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1310`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### findBlock (function) `func (s *BlockAttrsSpec) findBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1318`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *BlockLabelSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1348`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *BlockLabelSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1352`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *BlockLabelSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1360`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *BlockLabelSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1364`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### findLabelSpecs (function) `func findLabelSpecs(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1372`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *DefaultSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1430`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *DefaultSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1435`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *DefaultSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1445`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### attrSchemata (function) `func (s *DefaultSpec) attrSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1450`
- Doc: attrSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### blockHeaderSchemata (function) `func (s *DefaultSpec) blockHeaderSchemata(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1464`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### nestedSpec (function) `func (s *DefaultSpec) nestedSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1474`
- Doc: blockSpec implementation
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *DefaultSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1481`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *TransformExprSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1503`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *TransformExprSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1507`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *TransformExprSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1525`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *TransformExprSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1535`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *TransformFuncSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1559`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *TransformFuncSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1563`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *TransformFuncSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1589`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *TransformFuncSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1600`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s *ValidateSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1619`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s *ValidateSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1623`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s *ValidateSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1644`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s *ValidateSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1648`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### decode (function) `func (s noopSpec) decode(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1658`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### impliedType (function) `func (s noopSpec) impliedType(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1662`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### visitSameBodyChildren (function) `func (s noopSpec) visitSameBodyChildren(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1666`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### sourceRange (function) `func (s noopSpec) sourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec.go:1670`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

## teamserver/pkg/profile/yaotl/hcldec/spec_test.go

### TestDefaultSpec (function) `func TestDefaultSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec_test.go:49`

### TestValidateFuncSpec (function) `func TestValidateFuncSpec(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/spec_test.go:145`

## teamserver/pkg/profile/yaotl/hcldec/variables.go

### Variables (function) `func Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/variables.go:17`
- Doc: Variables processes the given body with the given spec and returns a list of the variable traversals that would be requi

## teamserver/pkg/profile/yaotl/hcldec/variables_test.go

### TestVariables (function) `func TestVariables(`
- Defined: `teamserver/pkg/profile/yaotl/hcldec/variables_test.go:13`

## teamserver/pkg/profile/yaotl/hcled/navigation.go

### ContextString (function) `func ContextString(`
- Defined: `teamserver/pkg/profile/yaotl/hcled/navigation.go:15`
- Doc: ContextString returns a string describing the context of the given byte offset, if available. An empty string is returne

### ContextDefRange (function) `func ContextDefRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcled/navigation.go:26`

## teamserver/pkg/profile/yaotl/hclparse/parser.go

### NewParser (function) `func NewParser(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:43`
- Doc: NewParser creates a new parser, ready to parse configuration files.

### ParseHCL (function) `func (p *Parser) ParseHCL(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:52`
- Doc: ParseHCL parses the given buffer (which is assumed to have been loaded from the given filename) as a native-syntax confi

### ParseHCLFile (function) `func (p *Parser) ParseHCLFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:65`
- Doc: ParseHCLFile reads the given filename and parses it as a native-syntax HCL configuration file. An error diagnostic is re

### ParseJSON (function) `func (p *Parser) ParseJSON(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:86`
- Doc: ParseJSON parses the given JSON buffer (which is assumed to have been loaded from the given filename) and returns the hc

### ParseJSONFile (function) `func (p *Parser) ParseJSONFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:98`
- Doc: ParseJSONFile reads the given filename and parses it as JSON, similarly to ParseJSON. An error diagnostic is returned if

### AddFile (function) `func (p *Parser) AddFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:110`
- Doc: AddFile allows a caller to record in a parser a file that was parsed some other way, thus allowing it to be included in 

### Sources (function) `func (p *Parser) Sources(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:119`
- Doc: Sources returns a map from filenames to the raw source code that was read from them. This is intended to be used, for ex

### Files (function) `func (p *Parser) Files(`
- Defined: `teamserver/pkg/profile/yaotl/hclparse/parser.go:133`
- Doc: Files returns a map from filenames to the File objects produced from them. This is intended to be used, for example, to 

## teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go

### Decode (function) `func Decode(`
- Defined: `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go:53`
- Doc: can just pass nil.  The "target" argument must be a pointer to a value of a struct type, with struct tags as defined by 
- Imported by: `teamserver/pkg/profile/profile.go`, `teamserver/pkg/profile/yaotl/doc.go`

### DecodeFile (function) `func DecodeFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go:72`
- Doc: DecodeFile is a wrapper around Decode that first reads the given filename from disk. See the Decode documentation for mo
- Imported by: `teamserver/pkg/profile/profile.go`, `teamserver/pkg/profile/yaotl/doc.go`

## teamserver/pkg/profile/yaotl/hclsyntax/diagnostics.go

### setDiagEvalContext (function) `func setDiagEvalContext(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/diagnostics.go:16`
- Doc: setDiagEvalContext is an internal helper that will impose a particular EvalContext on a set of diagnostics in-place, for

## teamserver/pkg/profile/yaotl/hclsyntax/didyoumean.go

### nameSuggestion (function) `func nameSuggestion(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/didyoumean.go:16`
- Doc: nameSuggestion tries to find a name from the given slice of suggested names that is close to the given name and returns 

## teamserver/pkg/profile/yaotl/hclsyntax/expression.go

### Range (function) `func (e *ParenthesesExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:45`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes (function) `func (e *ParenthesesExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:49`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes (function) `func (e *LiteralValueExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:62`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value (function) `func (e *LiteralValueExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:66`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range (function) `func (e *LiteralValueExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:70`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange (function) `func (e *LiteralValueExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:74`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### AsTraversal (function) `func (e *LiteralValueExpr) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:79`
- Doc: Implementation for hcl.AbsTraversalForExpr.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes (function) `func (e *ScopeTraversalExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:130`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value (function) `func (e *ScopeTraversalExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:134`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range (function) `func (e *ScopeTraversalExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:140`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange (function) `func (e *ScopeTraversalExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:144`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### AsTraversal (function) `func (e *ScopeTraversalExpr) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:149`
- Doc: Implementation for hcl.AbsTraversalForExpr.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes (function) `func (e *RelativeTraversalExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:161`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value (function) `func (e *RelativeTraversalExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:165`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range (function) `func (e *RelativeTraversalExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:173`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange (function) `func (e *RelativeTraversalExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:177`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### AsTraversal (function) `func (e *RelativeTraversalExpr) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:182`
- Doc: Implementation for hcl.AbsTraversalForExpr.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes (function) `func (e *FunctionCallExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:210`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value (function) `func (e *FunctionCallExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:216`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range (function) `func (e *FunctionCallExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:541`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange (function) `func (e *FunctionCallExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:545`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### ExprCall (function) `func (e *FunctionCallExpr) ExprCall(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:550`
- Doc: Implementation for hcl.ExprCall.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes (function) `func (e *ConditionalExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:572`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value (function) `func (e *ConditionalExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:578`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range (function) `func (e *ConditionalExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:715`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange (function) `func (e *ConditionalExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:719`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes (function) `func (e *IndexExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:732`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value (function) `func (e *IndexExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:737`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range (function) `func (e *IndexExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:750`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange (function) `func (e *IndexExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:754`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes (function) `func (e *TupleConsExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:765`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value (function) `func (e *TupleConsExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:771`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range (function) `func (e *TupleConsExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:785`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange (function) `func (e *TupleConsExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:789`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### ExprList (function) `func (e *TupleConsExpr) ExprList(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:794`
- Doc: Implementation for hcl.ExprList
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes (function) `func (e *ObjectConsExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:814`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value (function) `func (e *ObjectConsExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:821`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range (function) `func (e *ObjectConsExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:897`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange (function) `func (e *ObjectConsExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:901`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### ExprMap (function) `func (e *ObjectConsExpr) ExprMap(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:906`
- Doc: Implementation for hcl.ExprMap
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### literalName (function) `func (e *ObjectConsKeyExpr) literalName(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:925`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes (function) `func (e *ObjectConsKeyExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:934`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value (function) `func (e *ObjectConsKeyExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:942`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range (function) `func (e *ObjectConsKeyExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:971`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange (function) `func (e *ObjectConsKeyExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:975`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### AsTraversal (function) `func (e *ObjectConsKeyExpr) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:980`
- Doc: Implementation for hcl.AbsTraversalForExpr.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### UnwrapExpression (function) `func (e *ObjectConsKeyExpr) UnwrapExpression(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:996`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value (function) `func (e *ForExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1022`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes (function) `func (e *ForExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1346`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range (function) `func (e *ForExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1375`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange (function) `func (e *ForExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1379`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value (function) `func (e *SplatExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1392`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes (function) `func (e *SplatExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1522`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range (function) `func (e *SplatExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1527`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange (function) `func (e *SplatExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1531`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Value (function) `func (e *AnonSymbolExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1558`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### setValue (function) `func (e *AnonSymbolExpr) setValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1575`
- Doc: setValue sets a temporary local value for the expression when evaluated in the given context, which must be non-nil.
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### clearValue (function) `func (e *AnonSymbolExpr) clearValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1588`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### walkChildNodes (function) `func (e *AnonSymbolExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1601`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### Range (function) `func (e *AnonSymbolExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1605`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

### StartRange (function) `func (e *AnonSymbolExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1609`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go

### init (function) `func init(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:86`

### walkChildNodes (function) `func (e *BinaryOpExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:131`

### Value (function) `func (e *BinaryOpExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:136`

### Range (function) `func (e *BinaryOpExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:198`

### StartRange (function) `func (e *BinaryOpExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:202`

### walkChildNodes (function) `func (e *UnaryOpExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:214`

### Value (function) `func (e *UnaryOpExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:218`

### Range (function) `func (e *UnaryOpExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:262`

### StartRange (function) `func (e *UnaryOpExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:266`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go

### walkChildNodes (function) `func (e *TemplateExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:18`

### Value (function) `func (e *TemplateExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:24`

### Range (function) `func (e *TemplateExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:97`

### StartRange (function) `func (e *TemplateExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:101`

### IsStringLiteral (function) `func (e *TemplateExpr) IsStringLiteral(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:117`
- Doc: IsStringLiteral returns true if and only if the template consists only of single string literal, as would be created for

### walkChildNodes (function) `func (e *TemplateJoinExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:133`

### Value (function) `func (e *TemplateJoinExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:137`

### Range (function) `func (e *TemplateJoinExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:207`

### StartRange (function) `func (e *TemplateJoinExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:211`

### walkChildNodes (function) `func (e *TemplateWrapExpr) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:225`

### Value (function) `func (e *TemplateWrapExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:229`

### Range (function) `func (e *TemplateWrapExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:233`

### StartRange (function) `func (e *TemplateWrapExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:237`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go

### Variables (function) `func (e *AnonSymbolExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:10`

### Variables (function) `func (e *BinaryOpExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:14`

### Variables (function) `func (e *ConditionalExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:18`

### Variables (function) `func (e *ForExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:22`

### Variables (function) `func (e *FunctionCallExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:26`

### Variables (function) `func (e *IndexExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:30`

### Variables (function) `func (e *LiteralValueExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:34`

### Variables (function) `func (e *ObjectConsExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:38`

### Variables (function) `func (e *ObjectConsKeyExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:42`

### Variables (function) `func (e *RelativeTraversalExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:46`

### Variables (function) `func (e *ScopeTraversalExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:50`

### Variables (function) `func (e *SplatExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:54`

### Variables (function) `func (e *TemplateExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:58`

### Variables (function) `func (e *TemplateJoinExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:62`

### Variables (function) `func (e *TemplateWrapExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:66`

### Variables (function) `func (e *TupleConsExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:70`

### Variables (function) `func (e *UnaryOpExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:74`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go

### main (function) `func main(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go:20`
- Depends on: `teamserver/pkg/profile/yaotl/hclsyntax/token.go`

### Variables (function) `func (e %s) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go:97`
- Depends on: `teamserver/pkg/profile/yaotl/hclsyntax/token.go`

## teamserver/pkg/profile/yaotl/hclsyntax/file.go

### AsHCLFile (function) `func (f *File) AsHCLFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/file.go:13`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/config/fuzz.go

### Fuzz (function) `func Fuzz(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/config/fuzz.go:8`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/expr/fuzz.go

### Fuzz (function) `func Fuzz(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/expr/fuzz.go:8`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/template/fuzz.go

### Fuzz (function) `func Fuzz(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/template/fuzz.go:8`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/traversal/fuzz.go

### Fuzz (function) `func Fuzz(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/traversal/fuzz.go:8`

## teamserver/pkg/profile/yaotl/hclsyntax/keywords.go

### TokenMatches (function) `func (kw Keyword) TokenMatches(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/keywords.go:16`

## teamserver/pkg/profile/yaotl/hclsyntax/navigation.go

### ContextString (function) `func (n navigation) ContextString(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/navigation.go:15`
- Doc: Implementation of hcled.ContextString

### ContextDefRange (function) `func (n navigation) ContextDefRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/navigation.go:45`

## teamserver/pkg/profile/yaotl/hclsyntax/parser.go

### ParseBody (function) `func (p *parser) ParseBody(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:25`

### ParseBodyItem (function) `func (p *parser) ParseBodyItem(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:116`

### parseSingleAttrBody (function) `func (p *parser) parseSingleAttrBody(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:156`
- Doc: parseSingleAttrBody is a weird variant of ParseBody that deals with the body of a nested block containing only one attri

### finishParsingBodyAttribute (function) `func (p *parser) finishParsingBodyAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:217`

### finishParsingBodyBlock (function) `func (p *parser) finishParsingBodyBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:274`

### ParseExpression (function) `func (p *parser) ParseExpression(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:444`

### parseTernaryConditional (function) `func (p *parser) parseTernaryConditional(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:448`

### parseBinaryOps (function) `func (p *parser) parseBinaryOps(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:512`
- Doc: parseBinaryOps calls itself recursively to work through all of the operator precedence groups, and then eventually calls

### parseExpressionWithTraversals (function) `func (p *parser) parseExpressionWithTraversals(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:584`

### parseExpressionTraversals (function) `func (p *parser) parseExpressionTraversals(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:591`

### makeRelativeTraversal (function) `func makeRelativeTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:891`
- Doc: makeRelativeTraversal takes an expression and a traverser and returns a traversal expression that combines the two. If t

### parseExpressionTerm (function) `func (p *parser) parseExpressionTerm(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:910`

### numberLitValue (function) `func (p *parser) numberLitValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1081`

### finishParsingFunctionCall (function) `func (p *parser) finishParsingFunctionCall(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1105`
- Doc: finishParsingFunctionCall parses a function call assuming that the function name was already read, and so the peeker sho

### parseTupleCons (function) `func (p *parser) parseTupleCons(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1200`

### parseObjectCons (function) `func (p *parser) parseObjectCons(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1270`

### finishParsingForExpr (function) `func (p *parser) finishParsingForExpr(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1427`

### parseQuotedStringLiteral (function) `func (p *parser) parseQuotedStringLiteral(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1650`
- Doc: parseQuotedStringLiteral is a helper for parsing quoted strings that aren't allowed to contain any interpolations, such 

### ParseStringLiteralToken (function) `func ParseStringLiteralToken(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1745`
- Doc: ParseStringLiteralToken processes the given token, which must be either a TokenQuotedLit or a TokenStringLit, returning 

### setRecovery (function) `func (p *parser) setRecovery(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1912`
- Doc: setRecovery turns on recovery mode without actually doing any recovery. This can be used when a parser knowingly leaves 

### recover (function) `func (p *parser) recover(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1924`
- Doc: recover seeks forward in the token stream until it finds TokenType "end", then returns with the peeker pointed at the fo

### recoverOver (function) `func (p *parser) recoverOver(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1963`
- Doc: recoverOver seeks forward in the token stream until it finds a block starting with TokenType "start", then finds the cor

### recoverAfterBodyItem (function) `func (p *parser) recoverAfterBodyItem(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1981`

### oppositeBracket (function) `func (p *parser) oppositeBracket(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:2028`
- Doc: oppositeBracket finds the bracket that opposes the given bracketer, or NilToken if the given token isn't a bracketer.  "

### errPlaceholderExpr (function) `func errPlaceholderExpr(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:2067`

## teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go

### ParseTemplate (function) `func (p *parser) ParseTemplate(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:13`

### parseTemplate (function) `func (p *parser) parseTemplate(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:17`

### parseTemplateInner (function) `func (p *parser) parseTemplateInner(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:36`

### parseRoot (function) `func (p *templateParser) parseRoot(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:65`

### parseExpr (function) `func (p *templateParser) parseExpr(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:83`

### parseIf (function) `func (p *templateParser) parseIf(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:135`

### parseFor (function) `func (p *templateParser) parseFor(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:247`

### Peek (function) `func (p *templateParser) Peek(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:344`

### Read (function) `func (p *templateParser) Read(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:348`

### parseTemplateParts (function) `func (p *parser) parseTemplateParts(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:361`
- Doc: parseTemplateParts produces a flat sequence of "template tokens", which are either literal values (with any "trimming" a

### flushHeredocTemplateParts (function) `func flushHeredocTemplateParts(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:675`
- Doc: flushHeredocTemplateParts modifies in-place the line-leading literal strings to apply the flush heredoc processing rule:

### Name (function) `func (t *templateEndCtrlToken) Name(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:787`

### templateToken (function) `func (t isTemplateToken) templateToken(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:808`

## teamserver/pkg/profile/yaotl/hclsyntax/parser_traversal.go

### ParseTraversalAbs (function) `func (p *parser) ParseTraversalAbs(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/parser_traversal.go:12`
- Doc: ParseTraversalAbs parses an absolute traversal that is assumed to consume all of the remaining tokens in the peeker. The

## teamserver/pkg/profile/yaotl/hclsyntax/peeker.go

### newPeeker (function) `func newPeeker(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:38`

### Peek (function) `func (p *peeker) Peek(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:47`

### Read (function) `func (p *peeker) Read(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:52`

### NextRange (function) `func (p *peeker) NextRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:58`

### PrevRange (function) `func (p *peeker) PrevRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:62`

### nextToken (function) `func (p *peeker) nextToken(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:70`

### includingNewlines (function) `func (p *peeker) includingNewlines(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:118`

### PushIncludeNewlines (function) `func (p *peeker) PushIncludeNewlines(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:122`

### PopIncludeNewlines (function) `func (p *peeker) PopIncludeNewlines(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:138`

### AssertEmptyIncludeNewlinesStack (function) `func (p *peeker) AssertEmptyIncludeNewlinesStack(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:168`
- Doc: AssertEmptyNewlinesStack checks if the IncludeNewlinesStack is empty, doing panicking if it is not. This can be used to 

### formatPeekerNewlineStackChanges (function) `func formatPeekerNewlineStackChanges(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:184`

## teamserver/pkg/profile/yaotl/hclsyntax/public.go

### ParseConfig (function) `func ParseConfig(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:17`
- Doc: ParseConfig parses the given buffer as a whole HCL config file, returning a *hcl.File representing its contents. If HasE

### ParseExpression (function) `func ParseExpression(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:41`
- Doc: ParseExpression parses the given buffer as a standalone HCL expression, returning it as an instance of Expression.

### ParseTemplate (function) `func ParseTemplate(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:75`
- Doc: ParseTemplate parses the given buffer as a standalone HCL template, returning it as an instance of Expression.

### ParseTraversalAbs (function) `func ParseTraversalAbs(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:96`
- Doc: ParseTraversalAbs parses the given buffer as a standalone absolute traversal.  Parsing as a traversal is more limited th

### LexConfig (function) `func LexConfig(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:125`
- Doc: LexConfig performs lexical analysis on the given buffer, treating it as a whole HCL config file, and returns the resulti

### LexExpression (function) `func LexExpression(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:138`
- Doc: LexExpression performs lexical analysis on the given buffer, treating it as a standalone HCL expression, and returns the

### LexTemplate (function) `func LexTemplate(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:153`
- Doc: LexTemplate performs lexical analysis on the given buffer, treating it as a standalone HCL template, and returns the res

### ValidIdentifier (function) `func ValidIdentifier(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/public.go:165`
- Doc: ValidIdentifier tests if the given string could be a valid identifier in a native syntax expression.  This is useful whe

## teamserver/pkg/profile/yaotl/hclsyntax/scan_string_lit.go

### scanStringLit (function) `func scanStringLit(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/scan_string_lit.go:119`

## teamserver/pkg/profile/yaotl/hclsyntax/scan_tokens.go

### scanTokens (function) `func scanTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/scan_tokens.go:4220`

## teamserver/pkg/profile/yaotl/hclsyntax/structure.go

### AsHCLBlock (function) `func (b *Block) AsHCLBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:11`
- Doc: AsHCLBlock returns the block data expressed as a *hcl.Block.

### walkChildNodes (function) `func (b *Body) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:49`

### Range (function) `func (b *Body) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:54`

### Content (function) `func (b *Body) Content(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:58`

### PartialContent (function) `func (b *Body) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:128`

### JustAttributes (function) `func (b *Body) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:250`

### MissingItemRange (function) `func (b *Body) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:281`

### walkChildNodes (function) `func (a Attributes) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:292`

### Range (function) `func (a Attributes) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:303`
- Doc: Range returns the range of some arbitrary point within the set of attributes, or an invalid range if there are no attrib

### walkChildNodes (function) `func (a *Attribute) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:327`

### Range (function) `func (a *Attribute) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:331`

### AsHCLAttribute (function) `func (a *Attribute) AsHCLAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:336`
- Doc: AsHCLAttribute returns the block data expressed as a *hcl.Attribute.

### walkChildNodes (function) `func (bs Blocks) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:352`

### Range (function) `func (bs Blocks) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:363`
- Doc: Range returns the range of some arbitrary point within the list of blocks, or an invalid range if there are no blocks.  

### walkChildNodes (function) `func (b *Block) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:384`

### Range (function) `func (b *Block) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:388`

### DefRange (function) `func (b *Block) DefRange(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:392`

## teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go

### BlocksAtPos (function) `func (b *Body) BlocksAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:15`
- Doc: BlocksAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.

### InnermostBlockAtPos (function) `func (b *Body) InnermostBlockAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:22`
- Doc: InnermostBlockAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.

### OutermostBlockAtPos (function) `func (b *Body) OutermostBlockAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:29`
- Doc: OutermostBlockAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.

### blocksAtPos (function) `func (b *Body) blocksAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:40`
- Doc: blocksAtPos is the internal engine of both BlocksAtPos and InnermostBlockAtPos, which both need to do the same logic but

### outermostBlockAtPos (function) `func (b *Body) outermostBlockAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:68`
- Doc: outermostBlockAtPos is the internal version of OutermostBlockAtPos that returns a hclsyntax.Block rather than an hcl.Blo

### AttributeAtPos (function) `func (b *Body) AttributeAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:84`
- Doc: AttributeAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.

### attributeAtPos (function) `func (b *Body) attributeAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:91`
- Doc: attributeAtPos is the internal version of AttributeAtPos that returns a hclsyntax.Block rather than an hcl.Block, allowi

### OutermostExprAtPos (function) `func (b *Body) OutermostExprAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:109`
- Doc: OutermostExprAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.

## teamserver/pkg/profile/yaotl/hclsyntax/token.go

### GoString (function) `func (t TokenType) GoString(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token.go:107`
- Imported by: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go`

### emitToken (function) `func (f *tokenAccum) emitToken(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token.go:127`
- Imported by: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go`

### tokenOpensFlushHeredoc (function) `func tokenOpensFlushHeredoc(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token.go:167`
- Imported by: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go`

### checkInvalidTokens (function) `func checkInvalidTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token.go:182`
- Doc: checkInvalidTokens does a simple pass across the given tokens and generates diagnostics for tokens that should _never_ a
- Imported by: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go`

### stripUTF8BOM (function) `func stripUTF8BOM(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token.go:326`
- Doc: stripUTF8BOM checks whether the given buffer begins with a UTF-8 byte order mark (0xEF 0xBB 0xBF) and, if so, returns a 
- Imported by: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go`

## teamserver/pkg/profile/yaotl/hclsyntax/token_type_string.go

### _ (function) `func _(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token_type_string.go:7`

### String (function) `func (i TokenType) String(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/token_type_string.go:126`

## teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb

### each_alpha (method)
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:80`
- Doc: # Downloads the document at url and yields every alpha line's hex range and description.

### to_hex (method)
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:103`
- Doc: ## Formats to hex at minimum width

### to_ucs4 (method)
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:112`
- Doc: ## UCS4 is just a straight hex conversion of the unicode codepoint.

### to_utf8_enc (method)
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:126`

### from_utf8_enc (method)
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:150`

### utf8_ranges (method)
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:181`
- Doc: ## Given a range, splits it up into ranges that can be continuously encoded into utf8.  Eg: 0x00 .. 0xff => [0x00..0x7f,

### build_range (method)
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:197`

### to_utf8 (method)
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:246`

### count_codepoints (method)
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:259`
- Doc: # Perform a 3-way comparison of the number of codepoints advertised by the unicode spec for the given range, the origina

### is_valid (method)
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:273`

### generate_machine (method)
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:285`
- Doc: # Generate the state matching to stdout

## teamserver/pkg/profile/yaotl/hclsyntax/variables.go

### Variables (function) `func Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:11`
- Doc: Variables returns all of the variables referenced within a given expression.  This is the implementation of the "Variabl

### Enter (function) `func (w *variablesWalker) Enter(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:32`

### Exit (function) `func (w *variablesWalker) Exit(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:55`

### walkChildNodes (function) `func (e ChildScope) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:78`

### Range (function) `func (e ChildScope) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:84`
- Doc: Range returns the range of the expression that the ChildScope is encapsulating. It isn't really very useful to call Rang

## teamserver/pkg/profile/yaotl/hclsyntax/walk.go

### VisitAll (function) `func VisitAll(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/walk.go:16`
- Doc: VisitAll is a basic way to traverse the AST beginning with a particular node. The given function will be called once for

### Walk (function) `func Walk(`
- Defined: `teamserver/pkg/profile/yaotl/hclsyntax/walk.go:33`
- Doc: Walk is a more complex way to traverse the AST starting with a particular node, which provides information about the tre

## teamserver/pkg/profile/yaotl/hcltest/mock.go

### MockBody (function) `func MockBody(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:15`
- Doc: MockBody returns a hcl.Body implementation that works in terms of a caller-constructed hcl.BodyContent, thus avoiding th

### Content (function) `func (b mockBody) Content(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:23`

### PartialContent (function) `func (b mockBody) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:45`

### JustAttributes (function) `func (b mockBody) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:108`

### MissingItemRange (function) `func (b mockBody) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:122`

### MockExprLiteral (function) `func MockExprLiteral(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:128`
- Doc: MockExprLiteral returns a hcl.Expression that evaluates to the given literal value.

### Value (function) `func (e mockExprLiteral) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:136`

### Variables (function) `func (e mockExprLiteral) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:140`

### Range (function) `func (e mockExprLiteral) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:144`

### StartRange (function) `func (e mockExprLiteral) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:150`

### ExprList (function) `func (e mockExprLiteral) ExprList(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:155`
- Doc: Implementation for hcl.ExprList

### ExprMap (function) `func (e mockExprLiteral) ExprMap(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:170`
- Doc: Implementation for hcl.ExprMap

### MockExprVariable (function) `func MockExprVariable(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:189`
- Doc: MockExprVariable returns a hcl.Expression that evaluates to the value of the variable with the given name.

### Value (function) `func (e mockExprVariable) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:195`

### Variables (function) `func (e mockExprVariable) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:214`

### Range (function) `func (e mockExprVariable) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:225`

### StartRange (function) `func (e mockExprVariable) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:231`

### AsTraversal (function) `func (e mockExprVariable) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:236`
- Doc: Implementation for hcl.AbsTraversalForExpr and hcl.RelTraversalForExpr.

### MockExprTraversal (function) `func MockExprTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:247`
- Doc: MockExprTraversal returns a hcl.Expression that evaluates the given absolute traversal.

### MockExprTraversalSrc (function) `func MockExprTraversalSrc(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:258`
- Doc: MockExprTraversalSrc is like MockExprTraversal except it takes a traversal string as defined by the native syntax and pa

### Value (function) `func (e mockExprTraversal) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:270`

### Variables (function) `func (e mockExprTraversal) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:274`

### Range (function) `func (e mockExprTraversal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:278`

### StartRange (function) `func (e mockExprTraversal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:282`

### AsTraversal (function) `func (e mockExprTraversal) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:287`
- Doc: Implementation for hcl.AbsTraversalForExpr and hcl.RelTraversalForExpr.

### MockExprList (function) `func MockExprList(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:291`

### Value (function) `func (e mockExprList) Value(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:301`

### Variables (function) `func (e mockExprList) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:317`

### Range (function) `func (e mockExprList) Range(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:325`

### StartRange (function) `func (e mockExprList) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:331`

### ExprList (function) `func (e mockExprList) ExprList(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:336`
- Doc: Implementation for hcl.ExprList

### MockAttrs (function) `func MockAttrs(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock.go:345`
- Doc: MockAttrs constructs and returns a hcl.Attributes map with attributes derived from the given expression map.  Each entry

## teamserver/pkg/profile/yaotl/hcltest/mock_test.go

### TestMockBodyPartialContent (function) `func TestMockBodyPartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock_test.go:17`

### TestExprList (function) `func TestExprList(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock_test.go:271`

### TestExprMap (function) `func TestExprMap(`
- Defined: `teamserver/pkg/profile/yaotl/hcltest/mock_test.go:328`

## teamserver/pkg/profile/yaotl/hclwrite/ast.go

### NewEmptyFile (function) `func NewEmptyFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:17`
- Doc: NewEmptyFile constructs a new file with no content, ready to be mutated by other calls that append to its body.

### Body (function) `func (f *File) Body(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:28`
- Doc: Body returns the root body of the file, which contains the top-level attributes and blocks.

### WriteTo (function) `func (f *File) WriteTo(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:36`
- Doc: WriteTo writes the tokens underlying the receiving file to the given writer.  The tokens first have a simple formatting 

### Bytes (function) `func (f *File) Bytes(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:45`
- Doc: Bytes returns a buffer containing the source code resulting from the tokens underlying the receiving file. If any update

### newComments (function) `func newComments(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:58`

### BuildTokens (function) `func (c *comments) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:64`

### newIdentifier (function) `func newIdentifier(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:75`

### BuildTokens (function) `func (i *identifier) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:81`

### hasName (function) `func (i *identifier) hasName(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:85`

### newNumber (function) `func newNumber(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:96`

### BuildTokens (function) `func (n *number) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:102`

### newQuoted (function) `func newQuoted(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:113`

### BuildTokens (function) `func (q *quoted) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast.go:119`

## teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go

### newAttribute (function) `func newAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go:16`

### init (function) `func (a *Attribute) init(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go:22`

### Expr (function) `func (a *Attribute) Expr(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go:46`

## teamserver/pkg/profile/yaotl/hclwrite/ast_block.go

### newBlock (function) `func newBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:19`

### NewBlock (function) `func NewBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:26`
- Doc: NewBlock constructs a new, empty block with the given type name and labels.

### init (function) `func (b *Block) init(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:32`

### Body (function) `func (b *Block) Body(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:67`
- Doc: Body returns the body that represents the content of the receiving block.  Appending to or otherwise modifying this body

### Type (function) `func (b *Block) Type(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:72`
- Doc: Type returns the type name of the block.

### SetType (function) `func (b *Block) SetType(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:78`
- Doc: SetType updates the type name of the block to a given name.

### Labels (function) `func (b *Block) Labels(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:85`
- Doc: Labels returns the labels of the block.

### SetLabels (function) `func (b *Block) SetLabels(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:92`
- Doc: SetLabels updates the labels of the block to given labels. Since we cannot assume that old and new labels are equal in l

### labelsObj (function) `func (b *Block) labelsObj(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:101`
- Doc: labelsObj returns the internal node content representation of the block labels. This is not part of the public API becau

### newBlockLabels (function) `func newBlockLabels(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:111`

### Replace (function) `func (bl *blockLabels) Replace(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:121`

### Current (function) `func (bl *blockLabels) Current(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:136`

## teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go

### TestBlockType (function) `func TestBlockType(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go:15`

### TestBlockLabels (function) `func TestBlockLabels(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go:49`

### TestBlockSetType (function) `func TestBlockSetType(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go:138`

### TestBlockSetLabels (function) `func TestBlockSetLabels(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go:198`

## teamserver/pkg/profile/yaotl/hclwrite/ast_body.go

### newBody (function) `func newBody(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:17`

### appendItem (function) `func (b *Body) appendItem(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:24`

### appendItemNode (function) `func (b *Body) appendItemNode(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:30`

### Clear (function) `func (b *Body) Clear(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:38`
- Doc: Clear removes all of the items from the body, making it empty.

### AppendUnstructuredTokens (function) `func (b *Body) AppendUnstructuredTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:42`

### Attributes (function) `func (b *Body) Attributes(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:48`
- Doc: Attributes returns a new map of all of the attributes in the body, with the attribute names as the keys.

### Blocks (function) `func (b *Body) Blocks(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:61`
- Doc: Blocks returns a new slice of all the blocks in the body.

### GetAttribute (function) `func (b *Body) GetAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:73`
- Doc: GetAttribute returns the attribute from the body that has the given name, or returns nil if there is currently no matchi

### getAttributeNode (function) `func (b *Body) getAttributeNode(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:89`
- Doc: getAttributeNode is like GetAttribute but it returns the node containing the selected attribute (if one is found) rather

### FirstMatchingBlock (function) `func (b *Body) FirstMatchingBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:106`
- Doc: FirstMatchingBlock returns a first matching block from the body that has the given name and labels or returns nil if the

### RemoveBlock (function) `func (b *Body) RemoveBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:126`
- Doc: RemoveBlock removes the given block from the body, if it's in that body. If it isn't present, this is a no-op.  Returns 

### SetAttributeRaw (function) `func (b *Body) SetAttributeRaw(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:144`
- Doc: SetAttributeRaw either replaces the expression of an existing attribute of the given name or adds a new attribute defini

### SetAttributeValue (function) `func (b *Body) SetAttributeValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:165`
- Doc: SetAttributeValue either replaces the expression of an existing attribute of the given name or adds a new attribute defi

### SetAttributeTraversal (function) `func (b *Body) SetAttributeTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:186`
- Doc: SetAttributeTraversal either replaces the expression of an existing attribute of the given name or adds a new attribute 

### RemoveAttribute (function) `func (b *Body) RemoveAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:203`
- Doc: RemoveAttribute removes the attribute with the given name from the body.  The return value is the attribute that was rem

### AppendBlock (function) `func (b *Body) AppendBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:215`
- Doc: AppendBlock appends an existing block (which must not be already attached to a body) to the end of the receiving body.

### AppendNewBlock (function) `func (b *Body) AppendNewBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:222`
- Doc: AppendNewBlock appends a new nested block to the end of the receiving body with the given type name and labels.

### AppendNewline (function) `func (b *Body) AppendNewline(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:232`
- Doc: AppendNewline appends a newline token to th end of the receiving body, which generally serves as a separator between dif

## teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go

### TestBodyGetAttribute (function) `func TestBodyGetAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:16`

### TestBodyFirstMatchingBlock (function) `func TestBodyFirstMatchingBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:220`

### TestBodySetAttributeValue (function) `func TestBodySetAttributeValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:345`

### TestBodySetAttributeTraversal (function) `func TestBodySetAttributeTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:543`

### TestBodySetAttributeRaw (function) `func TestBodySetAttributeRaw(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:769`

### TestBodySetAttributeValueInBlock (function) `func TestBodySetAttributeValueInBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:933`

### TestBodySetAttributeValueInNestedBlock (function) `func TestBodySetAttributeValueInNestedBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:981`

### TestBodyRemoveAttribute (function) `func TestBodyRemoveAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:1036`

### TestBodyAppendBlock (function) `func TestBodyAppendBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:1149`

### TestBodyRemoveBlock (function) `func TestBodyRemoveBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go:1392`

## teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go

### newExpression (function) `func newExpression(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:17`

### NewExpressionRaw (function) `func NewExpressionRaw(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:36`
- Doc: NewExpressionRaw constructs an expression containing the given raw tokens.  There is no automatic validation that the gi

### NewExpressionLiteral (function) `func NewExpressionLiteral(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:60`
- Doc: NewExpressionLiteral constructs an an expression that represents the given literal value.  Since an unknown value cannot

### NewExpressionAbsTraversal (function) `func NewExpressionAbsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:69`
- Doc: NewExpressionAbsTraversal constructs an expression that represents the given traversal, which must be absolute or this f

### Variables (function) `func (e *Expression) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:129`
- Doc: Variables returns the absolute traversals that exist within the receiving expression.

### RenameVariablePrefix (function) `func (e *Expression) RenameVariablePrefix(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:150`
- Doc: RenameVariablePrefix examines each of the absolute traversals in the receiving expression to see if they have the given 

### newTraversal (function) `func newTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:195`

### newTraverseName (function) `func newTraverseName(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:208`

### newTraverseIndex (function) `func newTraverseIndex(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:220`

## teamserver/pkg/profile/yaotl/hclwrite/ast_test.go

### makeTestTree (function) `func makeTestTree(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/ast_test.go:15`

## teamserver/pkg/profile/yaotl/hclwrite/examples_test.go

### Example_generateFromScratch (function) `func Example_generateFromScratch(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/examples_test.go:11`

### ExampleExpression_RenameVariablePrefix (function) `func ExampleExpression_RenameVariablePrefix(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/examples_test.go:74`

## teamserver/pkg/profile/yaotl/hclwrite/format.go

### format (function) `func format(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:19`
- Doc: format rewrites tokens within the given sequence, in-place, to adjust the whitespace around their content to achieve can

### formatIndent (function) `func formatIndent(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:40`

### formatSpaces (function) `func formatSpaces(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:110`

### formatCells (function) `func formatCells(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:158`

### spaceAfterToken (function) `func spaceAfterToken(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:227`
- Doc: spaceAfterToken decides whether a particular subject token should have a space after it when surrounded by the given bef

### linesForFormat (function) `func linesForFormat(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:342`

### tokenIsNewline (function) `func tokenIsNewline(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:427`

### tokenBracketChange (function) `func tokenBracketChange(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format.go:440`

## teamserver/pkg/profile/yaotl/hclwrite/format_test.go

### TestFormat (function) `func TestFormat(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format_test.go:13`

### TestLinesForFormat (function) `func TestLinesForFormat(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/format_test.go:632`

## teamserver/pkg/profile/yaotl/hclwrite/fuzz/config/fuzz.go

### Fuzz (function) `func Fuzz(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/fuzz/config/fuzz.go:10`

## teamserver/pkg/profile/yaotl/hclwrite/generate.go

### TokensForValue (function) `func TokensForValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:23`
- Doc: TokensForValue returns a sequence of tokens that represents the given constant value.  This function only supports types

### TokensForTraversal (function) `func TokensForTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:36`
- Doc: TokensForTraversal returns a sequence of tokens that represents the given traversal.  If the traversal is absolute then 

### appendTokensForValue (function) `func appendTokensForValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:42`

### appendTokensForTraversal (function) `func appendTokensForTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:164`

### appendTokensForTraversalStep (function) `func appendTokensForTraversalStep(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:171`

### escapeQuotedStringLit (function) `func escapeQuotedStringLit(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:207`

### appendRune (function) `func appendRune(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate.go:248`

## teamserver/pkg/profile/yaotl/hclwrite/generate_test.go

### TestTokensForValue (function) `func TestTokensForValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate_test.go:14`

### TestTokensForTraversal (function) `func TestTokensForTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/generate_test.go:498`

## teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go

### Len (function) `func (s nativeNodeSorter) Len(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go:11`

### Less (function) `func (s nativeNodeSorter) Less(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go:15`

### Swap (function) `func (s nativeNodeSorter) Swap(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go:21`

## teamserver/pkg/profile/yaotl/hclwrite/node.go

### newNode (function) `func newNode(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:17`

### Equal (function) `func (n *node) Equal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:23`

### BuildTokens (function) `func (n *node) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:27`

### Detach (function) `func (n *node) Detach(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:33`
- Doc: Detach removes the receiver from the list it currently belongs to. If the node is not currently in a list, this is a no-

### ReplaceWith (function) `func (n *node) ReplaceWith(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:60`
- Doc: ReplaceWith removes the receiver from the list it currently belongs to and inserts a new node with the given content in 

### assertUnattached (function) `func (n *node) assertUnattached(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:83`

### BuildTokens (function) `func (ns *nodes) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:100`

### Clear (function) `func (ns *nodes) Clear(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:107`

### Append (function) `func (ns *nodes) Append(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:112`

### AppendNode (function) `func (ns *nodes) AppendNode(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:121`

### Insert (function) `func (ns *nodes) Insert(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:135`
- Doc: Insert inserts a nodeContent at a given position. This is just a wrapper for InsertNode. See InsertNode for details.

### InsertNode (function) `func (ns *nodes) InsertNode(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:147`
- Doc: InsertNode inserts a node at a given position. The first argument is a node reference before which to insert. To insert 

### AppendUnstructuredTokens (function) `func (ns *nodes) AppendUnstructuredTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:163`

### FindNodeWithContent (function) `func (ns *nodes) FindNodeWithContent(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:176`
- Doc: FindNodeWithContent searches the nodes for a node whose content equals the given content. If it finds one then it return

### newNodeSet (function) `func newNodeSet(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:190`

### Has (function) `func (ns nodeSet) Has(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:194`

### Add (function) `func (ns nodeSet) Add(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:202`

### Remove (function) `func (ns nodeSet) Remove(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:206`

### Clear (function) `func (ns nodeSet) Clear(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:210`

### List (function) `func (ns nodeSet) List(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:216`

### FindNodeWithContent (function) `func (ns nodeSet) FindNodeWithContent(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:246`
- Doc: FindNodeWithContent searches the nodes for a node whose content equals the given content. If it finds one then it return

### newInTree (function) `func newInTree(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:265`

### assertUnattached (function) `func (it *inTree) assertUnattached(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:271`

### walkChildNodes (function) `func (it *inTree) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:277`

### BuildTokens (function) `func (it *inTree) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:283`

### walkChildNodes (function) `func (n *leafNode) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/node.go:295`

## teamserver/pkg/profile/yaotl/hclwrite/parser.go

### parse (function) `func parse(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:29`
- Doc: up to AST nodes.  This strategy feels somewhat counter-intuitive, since most of the work the parser does is thrown away 

### Partition (function) `func (it inputTokens) Partition(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:74`

### PartitionType (function) `func (it inputTokens) PartitionType(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:82`

### PartitionTypeOk (function) `func (it inputTokens) PartitionTypeOk(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:91`

### PartitionTypeSingle (function) `func (it inputTokens) PartitionTypeSingle(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:101`

### PartitionIncludingComments (function) `func (it inputTokens) PartitionIncludingComments(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:111`
- Doc: PartitionIncludeComments is like Partition except the returned "within" range includes any lead and line comments associ

### PartitionBlockItem (function) `func (it inputTokens) PartitionBlockItem(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:128`
- Doc: PartitionBlockItem is similar to PartitionIncludeComments but it returns the comments as separate token sequences so tha

### PartitionLeadComments (function) `func (it inputTokens) PartitionLeadComments(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:135`

### PartitionLineEndTokens (function) `func (it inputTokens) PartitionLineEndTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:142`

### Slice (function) `func (it inputTokens) Slice(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:150`

### Len (function) `func (it inputTokens) Len(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:162`

### Tokens (function) `func (it inputTokens) Tokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:166`

### Types (function) `func (it inputTokens) Types(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:170`

### parseBody (function) `func parseBody(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:181`
- Doc: parseBody locates the given body within the given input tokens and returns the resulting *Body object as well as the tok

### parseBodyItem (function) `func parseBodyItem(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:220`

### parseAttribute (function) `func parseAttribute(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:238`

### parseBlock (function) `func parseBlock(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:289`

### parseBlockLabels (function) `func parseBlockLabels(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:347`

### parseExpression (function) `func parseExpression(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:375`

### parseTraversal (function) `func parseTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:396`

### parseTraversalStep (function) `func parseTraversalStep(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:413`

### writerTokens (function) `func writerTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:482`
- Doc: writerTokens takes a sequence of tokens as produced by the main hclsyntax package and transforms it into an equivalent s

### partitionTokens (function) `func partitionTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:539`
- Doc: This works best when the range is aligned with token boundaries (e.g. because it was produced in terms of the scanner's 

### partitionLeadCommentTokens (function) `func partitionLeadCommentTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:577`
- Doc: partitionLeadCommentTokens takes a sequence of tokens that is assumed to immediately precede a construct that can have l

### partitionLineEndTokens (function) `func partitionLineEndTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:600`
- Doc: partitionLineEndTokens takes a sequence of tokens that is assumed to immediately follow a construct that can have a line

### lexConfig (function) `func lexConfig(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser.go:635`
- Doc: lexConfig uses the hclsyntax scanner to get a token stream and then rewrites it into this package's token model.  Any er

## teamserver/pkg/profile/yaotl/hclwrite/parser_test.go

### TestParse (function) `func TestParse(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser_test.go:18`

### TestPartitionTokens (function) `func TestPartitionTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser_test.go:1232`

### TestPartitionLeadCommentTokens (function) `func TestPartitionLeadCommentTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser_test.go:1382`

### TestLexConfig (function) `func TestLexConfig(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/parser_test.go:1458`

## teamserver/pkg/profile/yaotl/hclwrite/public.go

### NewFile (function) `func NewFile(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/public.go:11`
- Doc: NewFile creates a new file object that is empty and ready to have constructs added t it.

### ParseConfig (function) `func ParseConfig(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/public.go:26`
- Doc: ParseConfig interprets the given source bytes into a *hclwrite.File. The resulting AST can be used to perform surgical e

### Format (function) `func Format(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/public.go:38`
- Doc: Format takes source code and performs simple whitespace changes to transform it to a canonical layout style.  Format ski

## teamserver/pkg/profile/yaotl/hclwrite/round_trip_test.go

### TestRoundTripVerbatim (function) `func TestRoundTripVerbatim(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/round_trip_test.go:16`

### TestRoundTripFormat (function) `func TestRoundTripFormat(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/round_trip_test.go:82`

## teamserver/pkg/profile/yaotl/hclwrite/tokens.go

### asHCLSyntax (function) `func (t *Token) asHCLSyntax(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:33`
- Doc: asHCLSyntax returns the receiver expressed as an incomplete hclsyntax.Token. A complete token is not possible since we d

### Bytes (function) `func (ts Tokens) Bytes(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:46`

### testValue (function) `func (ts Tokens) testValue(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:52`

### Columns (function) `func (ts Tokens) Columns(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:59`
- Doc: Columns returns the number of columns (grapheme clusters) the token sequence occupies. The result is not meaningful if t

### WriteTo (function) `func (ts Tokens) WriteTo(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:72`
- Doc: WriteTo takes an io.Writer and writes the bytes for each token to it, along with the spacing that separates each token. 

### walkChildNodes (function) `func (ts Tokens) walkChildNodes(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:109`

### BuildTokens (function) `func (ts Tokens) BuildTokens(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:113`

### newIdentToken (function) `func newIdentToken(`
- Defined: `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:117`

## teamserver/pkg/profile/yaotl/json/ast.go

### Range (function) `func (n *objectVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:21`

### StartRange (function) `func (n *objectVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:25`

### Range (function) `func (n *objectAttr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:35`

### StartRange (function) `func (n *objectAttr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:39`

### Range (function) `func (n *arrayVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:49`

### StartRange (function) `func (n *arrayVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:53`

### Range (function) `func (n *booleanVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:62`

### StartRange (function) `func (n *booleanVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:66`

### Range (function) `func (n *numberVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:75`

### StartRange (function) `func (n *numberVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:79`

### Range (function) `func (n *stringVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:88`

### StartRange (function) `func (n *stringVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:92`

### Range (function) `func (n *nullVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:100`

### StartRange (function) `func (n *nullVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:104`

### Range (function) `func (n invalidVal) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:115`

### StartRange (function) `func (n invalidVal) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/ast.go:119`

## teamserver/pkg/profile/yaotl/json/didyoumean.go

### keywordSuggestion (function) `func keywordSuggestion(`
- Defined: `teamserver/pkg/profile/yaotl/json/didyoumean.go:12`
- Doc: keywordSuggestion tries to find a valid JSON keyword that is close to the given string and returns it if found. If no ke

### nameSuggestion (function) `func nameSuggestion(`
- Defined: `teamserver/pkg/profile/yaotl/json/didyoumean.go:25`
- Doc: nameSuggestion tries to find a name from the given slice of suggested names that is close to the given name and returns 

## teamserver/pkg/profile/yaotl/json/didyoumean_test.go

### TestKeywordSuggestion (function) `func TestKeywordSuggestion(`
- Defined: `teamserver/pkg/profile/yaotl/json/didyoumean_test.go:5`

## teamserver/pkg/profile/yaotl/json/fuzz/config/fuzz.go

### Fuzz (function) `func Fuzz(`
- Defined: `teamserver/pkg/profile/yaotl/json/fuzz/config/fuzz.go:7`

## teamserver/pkg/profile/yaotl/json/navigation.go

### ContextString (function) `func (n navigation) ContextString(`
- Defined: `teamserver/pkg/profile/yaotl/json/navigation.go:13`
- Doc: Implementation of hcled.ContextString

### navigationStepsRev (function) `func navigationStepsRev(`
- Defined: `teamserver/pkg/profile/yaotl/json/navigation.go:32`

## teamserver/pkg/profile/yaotl/json/navigation_test.go

### TestNavigationContextString (function) `func TestNavigationContextString(`
- Defined: `teamserver/pkg/profile/yaotl/json/navigation_test.go:9`

## teamserver/pkg/profile/yaotl/json/parser.go

### parseFileContent (function) `func parseFileContent(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:11`

### parseExpression (function) `func parseExpression(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:26`

### parseValue (function) `func parseValue(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:41`

### tokenCanStartValue (function) `func tokenCanStartValue(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:101`

### parseObject (function) `func parseObject(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:110`

### parseArray (function) `func parseArray(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:261`

### parseNumber (function) `func parseNumber(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:363`

### parseString (function) `func parseString(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:406`

### parseKeyword (function) `func parseKeyword(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser.go:461`

## teamserver/pkg/profile/yaotl/json/parser_test.go

### init (function) `func init(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser_test.go:11`

### TestParse (function) `func TestParse(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser_test.go:15`

### TestParseWithPos (function) `func TestParseWithPos(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser_test.go:619`

### mustBigFloat (function) `func mustBigFloat(`
- Defined: `teamserver/pkg/profile/yaotl/json/parser_test.go:661`

## teamserver/pkg/profile/yaotl/json/peeker.go

### newPeeker (function) `func newPeeker(`
- Defined: `teamserver/pkg/profile/yaotl/json/peeker.go:8`

### Peek (function) `func (p *peeker) Peek(`
- Defined: `teamserver/pkg/profile/yaotl/json/peeker.go:15`

### Read (function) `func (p *peeker) Read(`
- Defined: `teamserver/pkg/profile/yaotl/json/peeker.go:19`

## teamserver/pkg/profile/yaotl/json/public.go

### Parse (function) `func Parse(`
- Defined: `teamserver/pkg/profile/yaotl/json/public.go:20`
- Doc: Parse attempts to parse the given buffer as JSON and, if successful, returns a hcl.File for the HCL configuration repres

### ParseWithStartPos (function) `func ParseWithStartPos(`
- Defined: `teamserver/pkg/profile/yaotl/json/public.go:29`
- Doc: ParseWithStartPos attempts to parse like json.Parse, but unlike json.Parse you can pass a start position of the given JS

### ParseExpression (function) `func ParseExpression(`
- Defined: `teamserver/pkg/profile/yaotl/json/public.go:76`
- Doc: ParseExpression parses the given buffer as a standalone JSON expression, returning it as an instance of Expression.

### ParseExpressionWithStartPos (function) `func ParseExpressionWithStartPos(`
- Defined: `teamserver/pkg/profile/yaotl/json/public.go:83`
- Doc: ParseExpressionWithStartPos parses like json.ParseExpression, but unlike json.ParseExpression you can pass a start posit

### ParseFile (function) `func ParseFile(`
- Defined: `teamserver/pkg/profile/yaotl/json/public.go:92`
- Doc: ParseFile is a convenience wrapper around Parse that first attempts to load data from the given filename, passing the re

## teamserver/pkg/profile/yaotl/json/public_test.go

### TestParse_nonObject (function) `func TestParse_nonObject(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:12`

### TestParseTemplate (function) `func TestParseTemplate(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:29`

### TestParseTemplateUnwrap (function) `func TestParseTemplateUnwrap(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:65`

### TestParse_malformed (function) `func TestParse_malformed(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:101`

### TestParseWithStartPos (function) `func TestParseWithStartPos(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:117`

### TestParseExpression (function) `func TestParseExpression(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:187`

### TestParseExpression_malformed (function) `func TestParseExpression_malformed(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:260`

### TestParseExpressionWithStartPos (function) `func TestParseExpressionWithStartPos(`
- Defined: `teamserver/pkg/profile/yaotl/json/public_test.go:274`

## teamserver/pkg/profile/yaotl/json/scanner.go

### scan (function) `func scan(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:41`
- Doc: scan returns the primary tokens for the given JSON buffer in sequence.  The responsibility of this pass is to just mark 

### byteCanStartNumber (function) `func byteCanStartNumber(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:124`

### scanNumber (function) `func scanNumber(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:138`

### byteCanStartKeyword (function) `func byteCanStartKeyword(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:157`

### scanKeyword (function) `func scanKeyword(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:172`

### scanString (function) `func scanString(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:189`

### skipWhitespace (function) `func skipWhitespace(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:241`

### Range (function) `func (p *pos) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:280`

### posRange (function) `func posRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:292`

### GoString (function) `func (t token) GoString(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:300`

### isAlphabetical (function) `func isAlphabetical(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner.go:304`

## teamserver/pkg/profile/yaotl/json/scanner_test.go

### TestScan (function) `func TestScan(`
- Defined: `teamserver/pkg/profile/yaotl/json/scanner_test.go:12`

## teamserver/pkg/profile/yaotl/json/structure.go

### Content (function) `func (b *body) Content(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:29`

### PartialContent (function) `func (b *body) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:77`

### JustAttributes (function) `func (b *body) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:169`
- Doc: JustAttributes for JSON bodies interprets all properties of the wrapped JSON object as attributes and returns them.

### MissingItemRange (function) `func (b *body) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:219`

### unpackBlock (function) `func (b *body) unpackBlock(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:232`

### collectDeepAttrs (function) `func (b *body) collectDeepAttrs(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:325`
- Doc: collectDeepAttrs takes either a single object or an array of objects and flattens it into a list of object attributes, c

### Value (function) `func (e *expression) Value(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:381`

### Variables (function) `func (e *expression) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:513`

### Range (function) `func (e *expression) Range(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:557`

### StartRange (function) `func (e *expression) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:561`

### AsTraversal (function) `func (e *expression) AsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:566`
- Doc: Implementation for hcl.AbsTraversalForExpr.

### ExprCall (function) `func (e *expression) ExprCall(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:583`
- Doc: Implementation for hcl.ExprCall.

### ExprList (function) `func (e *expression) ExprList(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:606`
- Doc: Implementation for hcl.ExprList.

### ExprMap (function) `func (e *expression) ExprMap(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure.go:620`
- Doc: Implementation for hcl.ExprMap.

## teamserver/pkg/profile/yaotl/json/structure_test.go

### TestBodyPartialContent (function) `func TestBodyPartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:15`

### TestBodyContent (function) `func TestBodyContent(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1080`

### TestJustAttributes (function) `func TestJustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1139`

### TestExpressionVariables (function) `func TestExpressionVariables(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1237`

### TestExpressionAsTraversal (function) `func TestExpressionAsTraversal(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1326`

### TestStaticExpressionList (function) `func TestStaticExpressionList(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1338`

### TestExpression_Value (function) `func TestExpression_Value(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1357`

### TestExpressionValue_Diags (function) `func TestExpressionValue_Diags(`
- Defined: `teamserver/pkg/profile/yaotl/json/structure_test.go:1418`
- Doc: TestExpressionValue_Diags asserts that Value() returns diagnostics from nested evaluations for complex objects (e.g. Obj

## teamserver/pkg/profile/yaotl/json/tokentype_string.go

### String (function) `func (i tokenType) String(`
- Defined: `teamserver/pkg/profile/yaotl/json/tokentype_string.go:24`

## teamserver/pkg/profile/yaotl/merged.go

### MergeFiles (function) `func MergeFiles(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:15`
- Doc: MergeFiles combines the given files to produce a single body that contains configuration from all of the given files.  T

### MergeBodies (function) `func MergeBodies(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:25`
- Doc: MergeBodies is like MergeFiles except it deals directly with bodies, rather than with entire files.

### EmptyBody (function) `func EmptyBody(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:71`
- Doc: EmptyBody returns a body with no content. This body can be used as a placeholder when a body is required but no body con

### Content (function) `func (mb mergedBodies) Content(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:85`
- Doc: Content returns the content produced by applying the given schema to all of the merged bodies and merging the result.  A

### PartialContent (function) `func (mb mergedBodies) PartialContent(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:92`

### JustAttributes (function) `func (mb mergedBodies) JustAttributes(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:96`

### MissingItemRange (function) `func (mb mergedBodies) MissingItemRange(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:130`

### mergedContent (function) `func (mb mergedBodies) mergedContent(`
- Defined: `teamserver/pkg/profile/yaotl/merged.go:142`

## teamserver/pkg/profile/yaotl/ops.go

### Index (function) `func Index(`
- Defined: `teamserver/pkg/profile/yaotl/ops.go:23`
- Doc: Index is a helper function that performs the same operation as the index operator in the HCL expression language. That i

### GetAttr (function) `func GetAttr(`
- Defined: `teamserver/pkg/profile/yaotl/ops.go:262`
- Doc: GetAttr is a helper function that performs the same operation as the attribute access in the HCL expression language. Th

### ApplyPath (function) `func ApplyPath(`
- Defined: `teamserver/pkg/profile/yaotl/ops.go:404`
- Doc: ApplyPath is a helper function that applies a cty.Path to a value using the indexing and attribute access operations fro

## teamserver/pkg/profile/yaotl/pos.go

### RangeBetween (function) `func RangeBetween(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:58`
- Doc: RangeBetween returns a new range that spans from the beginning of the start range to the end of the end range.  The resu

### RangeOver (function) `func RangeOver(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:74`
- Doc: RangeOver returns a new range that covers both of the given ranges and possibly additional content between them if the t

### ContainsPos (function) `func (r Range) ContainsPos(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:106`
- Doc: ContainsPos returns true if and only if the given position is contained within the receiving range.  In the unlikely cas

### ContainsOffset (function) `func (r Range) ContainsOffset(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:112`
- Doc: ContainsOffset returns true if and only if the given byte offset is within the receiving Range.

### Ptr (function) `func (r Range) Ptr(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:120`
- Doc: Ptr returns a pointer to a copy of the receiver. This is a convenience when ranges in places where pointers are required

### String (function) `func (r Range) String(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:127`
- Doc: String returns a compact string representation of the receiver. Callers should generally prefer to present a range more 

### Empty (function) `func (r Range) Empty(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:145`

### CanSliceBytes (function) `func (r Range) CanSliceBytes(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:155`
- Doc: CanSliceBytes returns true if SliceBytes could return an accurate sub-slice of the given slice.  This effectively tests 

### SliceBytes (function) `func (r Range) SliceBytes(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:176`
- Doc: SliceBytes returns a sub-slice of the given slice that is covered by the receiving range, assuming that the given slice 

### Overlaps (function) `func (r Range) Overlaps(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:197`
- Doc: Overlaps returns true if the receiver and the other given range share any characters in common.

### Overlap (function) `func (r Range) Overlap(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:219`
- Doc: Overlap finds a range that is either identical to or a sub-range of both the receiver and the other given range. It retu

### PartitionAround (function) `func (r Range) PartitionAround(`
- Defined: `teamserver/pkg/profile/yaotl/pos.go:257`
- Doc: PartitionAround finds the portion of the given range that overlaps with the receiver and returns three ranges: the porti

## teamserver/pkg/profile/yaotl/pos_scanner.go

### NewRangeScanner (function) `func NewRangeScanner(`
- Defined: `teamserver/pkg/profile/yaotl/pos_scanner.go:41`
- Doc: NewRangeScanner creates a new RangeScanner for the given buffer, producing ranges for the given filename.  Since ranges 

### NewRangeScannerFragment (function) `func NewRangeScannerFragment(`
- Defined: `teamserver/pkg/profile/yaotl/pos_scanner.go:49`
- Doc: NewRangeScannerFragment is like NewRangeScanner but the ranges it produces will be offset by the given starting position

### Scan (function) `func (sc *RangeScanner) Scan(`
- Defined: `teamserver/pkg/profile/yaotl/pos_scanner.go:58`

### Range (function) `func (sc *RangeScanner) Range(`
- Defined: `teamserver/pkg/profile/yaotl/pos_scanner.go:138`
- Doc: Range returns a range that covers the latest token obtained after a call to Scan returns true.

### Bytes (function) `func (sc *RangeScanner) Bytes(`
- Defined: `teamserver/pkg/profile/yaotl/pos_scanner.go:144`
- Doc: Bytes returns the slice of the input buffer that is covered by the range that would be returned by Range.

### Err (function) `func (sc *RangeScanner) Err(`
- Defined: `teamserver/pkg/profile/yaotl/pos_scanner.go:150`
- Doc: Err can be called after Scan returns false to determine if the latest read resulted in an error, and obtain that error i

## teamserver/pkg/profile/yaotl/specsuite/spec_test.go

### TestMain (function) `func TestMain(`
- Defined: `teamserver/pkg/profile/yaotl/specsuite/spec_test.go:15`

### build (function) `func build(`
- Defined: `teamserver/pkg/profile/yaotl/specsuite/spec_test.go:30`

### TestSpec (function) `func TestSpec(`
- Defined: `teamserver/pkg/profile/yaotl/specsuite/spec_test.go:44`

### goBuild (function) `func goBuild(`
- Defined: `teamserver/pkg/profile/yaotl/specsuite/spec_test.go:91`

## teamserver/pkg/profile/yaotl/static_expr.go

### StaticExpr (function) `func StaticExpr(`
- Defined: `teamserver/pkg/profile/yaotl/static_expr.go:22`
- Doc: StaticExpr returns an Expression that always evaluates to the given value.  This is useful to substitute default values 

### Value (function) `func (e staticExpr) Value(`
- Defined: `teamserver/pkg/profile/yaotl/static_expr.go:26`

### Variables (function) `func (e staticExpr) Variables(`
- Defined: `teamserver/pkg/profile/yaotl/static_expr.go:30`

### Range (function) `func (e staticExpr) Range(`
- Defined: `teamserver/pkg/profile/yaotl/static_expr.go:34`

### StartRange (function) `func (e staticExpr) StartRange(`
- Defined: `teamserver/pkg/profile/yaotl/static_expr.go:38`

## teamserver/pkg/profile/yaotl/structure.go

### OfType (function) `func (els Blocks) OfType(`
- Defined: `teamserver/pkg/profile/yaotl/structure.go:129`
- Doc: OfType filters the receiving block sequence by block type name, returning a new block sequence including only the blocks

### ByType (function) `func (els Blocks) ByType(`
- Defined: `teamserver/pkg/profile/yaotl/structure.go:141`
- Doc: ByType transforms the receiving block sequence into a map from type name to block sequences of only that type.

## teamserver/pkg/profile/yaotl/structure_at_pos.go

### BlocksAtPos (function) `func (f *File) BlocksAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/structure_at_pos.go:25`
- Doc: BlocksAtPos attempts to find all of the blocks that contain the given position, ordered so that the outermost block is f

### OutermostBlockAtPos (function) `func (f *File) OutermostBlockAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/structure_at_pos.go:44`
- Doc: OutermostBlockAtPos attempts to find a top-level block in the receiving file that contains the given position. This is a

### InnermostBlockAtPos (function) `func (f *File) InnermostBlockAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/structure_at_pos.go:64`
- Doc: InnermostBlockAtPos attempts to find the most deeply-nested block in the receiving file that contains the given position

### OutermostExprAtPos (function) `func (f *File) OutermostExprAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/structure_at_pos.go:86`
- Doc: OutermostExprAtPos attempts to find an expression in the receiving file that contains the given position. This is a best

### AttributeAtPos (function) `func (f *File) AttributeAtPos(`
- Defined: `teamserver/pkg/profile/yaotl/structure_at_pos.go:105`
- Doc: AttributeAtPos attempts to find an attribute definition in the receiving file that contains the given position. This is 

## teamserver/pkg/profile/yaotl/traversal.go

### TraversalJoin (function) `func TraversalJoin(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:24`
- Doc: TraversalJoin appends a relative traversal to an absolute traversal to produce a new absolute traversal.

### TraverseRel (function) `func (t Traversal) TraverseRel(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:41`
- Doc: TraverseRel applies the receiving traversal to the given value, returning the resulting value. This is supported only fo

### TraverseAbs (function) `func (t Traversal) TraverseAbs(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:62`
- Doc: TraverseAbs applies the receiving traversal to the given eval context, returning the resulting value. This is supported 

### IsRelative (function) `func (t Traversal) IsRelative(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:122`
- Doc: IsRelative returns true if the receiver is a relative traversal, or false otherwise.

### SimpleSplit (function) `func (t Traversal) SimpleSplit(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:139`
- Doc: SimpleSplit returns a TraversalSplit where the name lookup is the absolute part and the remainder is the relative part. 

### RootName (function) `func (t Traversal) RootName(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:151`
- Doc: RootName returns the root name for a absolute traversal. Will panic if called on a relative traversal.

### SourceRange (function) `func (t Traversal) SourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:160`
- Doc: SourceRange returns the source range for the traversal.

### TraverseAbs (function) `func (t TraversalSplit) TraverseAbs(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:184`
- Doc: TraverseAbs traverses from a scope to the value resulting from the absolute traversal.

### TraverseRel (function) `func (t TraversalSplit) TraverseRel(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:190`
- Doc: TraverseRel traverses from a given value, assumed to be the result of TraverseAbs on some scope, to a final result for t

### Traverse (function) `func (t TraversalSplit) Traverse(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:196`
- Doc: Traverse is a convenience function to apply TraverseAbs followed by TraverseRel.

### Join (function) `func (t TraversalSplit) Join(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:208`
- Doc: Join concatenates together the Abs and Rel parts to produce a single absolute traversal.

### RootName (function) `func (t TraversalSplit) RootName(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:213`
- Doc: RootName returns the root name for the absolute part of the split.

### isTraverserSigil (function) `func (tr isTraverser) isTraverserSigil(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:228`

### TraversalStep (function) `func (tn TraverseRoot) TraversalStep(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:242`
- Doc: TraversalStep on a TraverseName immediately panics, because absolute traversals cannot be directly traversed.

### SourceRange (function) `func (tn TraverseRoot) SourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:246`

### TraversalStep (function) `func (tn TraverseAttr) TraversalStep(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:257`

### SourceRange (function) `func (tn TraverseAttr) SourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:261`

### TraversalStep (function) `func (tn TraverseIndex) TraversalStep(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:272`

### SourceRange (function) `func (tn TraverseIndex) SourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:276`

### TraversalStep (function) `func (tn TraverseSplat) TraversalStep(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:287`

### SourceRange (function) `func (tn TraverseSplat) SourceRange(`
- Defined: `teamserver/pkg/profile/yaotl/traversal.go:291`

## teamserver/pkg/profile/yaotl/traversal_for_expr.go

### AbsTraversalForExpr (function) `func AbsTraversalForExpr(`
- Defined: `teamserver/pkg/profile/yaotl/traversal_for_expr.go:20`
- Doc: A particular Expression implementation can support this function by offering a method called AsTraversal that takes no a

### RelTraversalForExpr (function) `func RelTraversalForExpr(`
- Defined: `teamserver/pkg/profile/yaotl/traversal_for_expr.go:52`
- Doc: RelTraversalForExpr is similar to AbsTraversalForExpr but it returns a relative traversal instead. Due to the nature of 

### ExprAsKeyword (function) `func ExprAsKeyword(`
- Defined: `teamserver/pkg/profile/yaotl/traversal_for_expr.go:108`
- Doc: The above approach will generate the same message for both the use of an unrecognized keyword and for not using a keywor

## teamserver/pkg/service/agent.go

### NewAgentService (function) `func NewAgentService(`
- Defined: `teamserver/pkg/service/agent.go:45`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/utils/utils.go`

### Json (function) `func (a *AgentService) Json(`
- Defined: `teamserver/pkg/service/agent.go:58`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/utils/utils.go`

### SendTask (function) `func (a *AgentService) SendTask(`
- Defined: `teamserver/pkg/service/agent.go:67`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/utils/utils.go`

### SendResponse (function) `func (a *AgentService) SendResponse(`
- Defined: `teamserver/pkg/service/agent.go:87`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/utils/utils.go`

### SendAgentBuildRequest (function) `func (a *AgentService) SendAgentBuildRequest(`
- Defined: `teamserver/pkg/service/agent.go:140`
- Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/utils/utils.go`

## teamserver/pkg/service/listener.go

### Start (function) `func (l *ListenerService) Start(`
- Defined: `teamserver/pkg/service/listener.go:17`
- Depends on: `teamserver/pkg/logger/logger.go`

### Json (function) `func (l *ListenerService) Json(`
- Defined: `teamserver/pkg/service/listener.go:37`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/service/service.go

### NewService (function) `func NewService(`
- Defined: `teamserver/pkg/service/service.go:27`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### Start (function) `func (s *Service) Start(`
- Defined: `teamserver/pkg/service/service.go:35`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### handleConnection (function) `func (s *Service) handleConnection(`
- Defined: `teamserver/pkg/service/service.go:50`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### authenticate (function) `func (s *Service) authenticate(`
- Defined: `teamserver/pkg/service/service.go:75`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### routine (function) `func (s *Service) routine(`
- Defined: `teamserver/pkg/service/service.go:144`
- Doc: the main service routine
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### dispatch (function) `func (s *Service) dispatch(`
- Defined: `teamserver/pkg/service/service.go:166`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### AgentExist (function) `func (s *Service) AgentExist(`
- Defined: `teamserver/pkg/service/service.go:703`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ClientClose (function) `func (s *Service) ClientClose(`
- Defined: `teamserver/pkg/service/service.go:713`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ListenerExist (function) `func (s *Service) ListenerExist(`
- Defined: `teamserver/pkg/service/service.go:763`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

### ListenerAdd (function) `func (s *Service) ListenerAdd(`
- Defined: `teamserver/pkg/service/service.go:775`
- Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`

## teamserver/pkg/service/types.go

### WriteJson (function) `func (c *ClientService) WriteJson(`
- Defined: `teamserver/pkg/service/types.go:69`
- Depends on: `teamserver/pkg/profile/profile.go`

## teamserver/pkg/socks/socks.go

### NewSocks (function) `func NewSocks(`
- Defined: `teamserver/pkg/socks/socks.go:17`
- Imported by: `teamserver/pkg/agent/demons.go`, `teamserver/pkg/agent/types.go`

### SetHandler (function) `func (s *Socks) SetHandler(`
- Defined: `teamserver/pkg/socks/socks.go:29`
- Imported by: `teamserver/pkg/agent/demons.go`, `teamserver/pkg/agent/types.go`

### Start (function) `func (s *Socks) Start(`
- Defined: `teamserver/pkg/socks/socks.go:35`
- Imported by: `teamserver/pkg/agent/demons.go`, `teamserver/pkg/agent/types.go`

### Close (function) `func (s *Socks) Close(`
- Defined: `teamserver/pkg/socks/socks.go:62`
- Imported by: `teamserver/pkg/agent/demons.go`, `teamserver/pkg/agent/types.go`

## teamserver/pkg/socks/util.go

### SubNegotiationClient (function) `func SubNegotiationClient(`
- Defined: `teamserver/pkg/socks/util.go:70`
- Depends on: `teamserver/pkg/logger/logger.go`

### ReadSocksHeader (function) `func ReadSocksHeader(`
- Defined: `teamserver/pkg/socks/util.go:114`
- Depends on: `teamserver/pkg/logger/logger.go`

### CreateResponsePackage (function) `func CreateResponsePackage(`
- Defined: `teamserver/pkg/socks/util.go:239`
- Depends on: `teamserver/pkg/logger/logger.go`

### SendConnectSuccess (function) `func SendConnectSuccess(`
- Defined: `teamserver/pkg/socks/util.go:255`
- Depends on: `teamserver/pkg/logger/logger.go`

### SendAddressTypeNotSupported (function) `func SendAddressTypeNotSupported(`
- Defined: `teamserver/pkg/socks/util.go:260`
- Depends on: `teamserver/pkg/logger/logger.go`

### SendCommandNotSupported (function) `func SendCommandNotSupported(`
- Defined: `teamserver/pkg/socks/util.go:265`
- Depends on: `teamserver/pkg/logger/logger.go`

### SendConnectFailure (function) `func SendConnectFailure(`
- Defined: `teamserver/pkg/socks/util.go:270`
- Depends on: `teamserver/pkg/logger/logger.go`

## teamserver/pkg/utils/utils.go

### UTF16BytesToString (function) `func UTF16BytesToString(`
- Defined: `teamserver/pkg/utils/utils.go:25`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### GenerateID (function) `func GenerateID(`
- Defined: `teamserver/pkg/utils/utils.go:34`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### GenerateString (function) `func GenerateString(`
- Defined: `teamserver/pkg/utils/utils.go:53`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### EncodeCommand (function) `func EncodeCommand(`
- Defined: `teamserver/pkg/utils/utils.go:65`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### IP2Inet (function) `func IP2Inet(`
- Defined: `teamserver/pkg/utils/utils.go:70`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### Port2Htons (function) `func Port2Htons(`
- Defined: `teamserver/pkg/utils/utils.go:84`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### ByteCountSI (function) `func ByteCountSI(`
- Defined: `teamserver/pkg/utils/utils.go:90`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### GetTeamserverPath (function) `func GetTeamserverPath(`
- Defined: `teamserver/pkg/utils/utils.go:104`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### IntToHexString (function) `func IntToHexString(`
- Defined: `teamserver/pkg/utils/utils.go:131`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### HexIntToString (function) `func HexIntToString(`
- Defined: `teamserver/pkg/utils/utils.go:135`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

### HexIntToBigEndian (function) `func HexIntToBigEndian(`
- Defined: `teamserver/pkg/utils/utils.go:141`
- Depends on: `teamserver/pkg/logger/logger.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`

## teamserver/pkg/webhook/webhook.go

### StringPtr (function) `func StringPtr(`
- Defined: `teamserver/pkg/webhook/webhook.go:20`
- Depends on: `teamserver/pkg/handlers/http.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### BoolPtr (function) `func BoolPtr(`
- Defined: `teamserver/pkg/webhook/webhook.go:24`
- Depends on: `teamserver/pkg/handlers/http.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### NewWebHook (function) `func NewWebHook(`
- Defined: `teamserver/pkg/webhook/webhook.go:28`
- Depends on: `teamserver/pkg/handlers/http.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### NewAgent (function) `func (w *WebHook) NewAgent(`
- Defined: `teamserver/pkg/webhook/webhook.go:32`
- Depends on: `teamserver/pkg/handlers/http.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

### SetDiscord (function) `func (w *WebHook) SetDiscord(`
- Defined: `teamserver/pkg/webhook/webhook.go:134`
- Depends on: `teamserver/pkg/handlers/http.go`
- Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`

## teamserver/pkg/win32/types.go

### StatusToString (function) `func StatusToString(`
- Defined: `teamserver/pkg/win32/types.go:78`
