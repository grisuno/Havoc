# Subsystem: Havoc

## client/include/Havoc/CmdLine.hpp
- Layer: infrastructure
- Language: hpp
- Symbols:
  - `is_same` (struct, line 88)
  - `default_reader` (struct, line 144)
  - `range_reader` (struct, line 151)
  - `oneof_reader` (struct, line 169)
  - `lexical_cast_t` (class, line 45)
  - `parser` (class, line 308)
  - `option_base` (class, line 621)
  - `option_without_value` (class, line 638)
  - `option_with_value` (class, line 694)
  - `cast` (function, line 47) `public:
            static Target cast(const Source &arg)`
  - `cast` (function, line 60) `public:
            static Target cast(const Source &arg)`
  - `cast` (function, line 68) `public:
            static std::string cast(const Source &arg)`
  - `cast` (function, line 78) `public:
            static Target cast(const std::string &arg)`
  - `lexical_cast` (function, line 98) `Target lexical_cast(const Source &arg)`
  - `demangle` (function, line 103) `static inline std::string demangle(const std::string &name)`
  - `readable_typename` (function, line 113) `template <class T>
        std::string readable_typename()`
  - `default_value` (function, line 119) `template <class T>
        std::string default_value(T def)`
  - `cmdline_error` (function, line 136) `public:
        cmdline_error(const std::string &msg): msg(msg)`
  - `what` (function, line 138) `const char *what() const throw()`
  - `operator` (function, line 145) `T operator()(const std::string &str)`
  - `range_reader` (function, line 152) `range_reader(const T &low, const T &high): low(low), high(high)`
  - `operator` (function, line 153) `T operator()(const std::string &s) const`
  - `range` (function, line 163) `template <class T>
    range_reader<T> range(const T &low, const T &high)`
  - `operator` (function, line 170) `T operator()(const std::string &s)`
  - `add` (function, line 176) `void add(const T &v)`
  - `oneof` (function, line 182) `template <class T>
    oneof_reader<T> oneof(T a1)`
  - `oneof` (function, line 190) `template <class T>
    oneof_reader<T> oneof(T a1, T a2)`
  - `oneof` (function, line 199) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3)`
  - `oneof` (function, line 209) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4)`
  - `oneof` (function, line 220) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5)`
  - `oneof` (function, line 232) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6)`
  - `oneof` (function, line 245) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7)`
  - `oneof` (function, line 259) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8)`
  - `oneof` (function, line 274) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9)`
  - `oneof` (function, line 290) `template <class T>
    oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6, T a7, T a8, T a9...`
  - `parser` (function, line 310) `public:
        parser()`
  - `add` (function, line 318) `void add(const std::string &name,
                 char short_name=0,
                 const std:...`
  - `add` (function, line 327) `template <class T>
        void add(const std::string &name,
                 char short_name=0,
...`
  - `add` (function, line 336) `void add(const std::string &name,
                 char short_name=0,
                 const std:...`
  - `footer` (function, line 347) `void footer(const std::string &f)`
  - `set_program_name` (function, line 351) `void set_program_name(const std::string &name)`
  - `exist` (function, line 355) `bool exist(const std::string &name) const`
  - `get` (function, line 361) `template <class T>
        const T &get(const std::string &name) const`
  - `rest` (function, line 368) `const std::vector<std::string> &rest() const`
  - `parse` (function, line 372) `bool parse(const std::string &arg)`
  - `parse` (function, line 414) `bool parse(const std::vector<std::string> &args)`
  - `parse` (function, line 424) `bool parse(int argc, const char * const argv[])`
  - `parse_check` (function, line 525) `void parse_check(const std::string &arg)`
  - `parse_check` (function, line 531) `void parse_check(const std::vector<std::string> &args)`
  - `parse_check` (function, line 537) `void parse_check(int argc, char *argv[])`
  - `error` (function, line 543) `std::string error() const`
  - `error_full` (function, line 547) `std::string error_full() const`
  - `usage` (function, line 554) `std::string usage() const`
  - `check` (function, line 587) `private:

        void check(int argc, bool ok)`
  - `set_option` (function, line 599) `void set_option(const std::string &name)`
  - `set_option` (function, line 610) `void set_option(const std::string &name, const std::string &value)`
  - `option_without_value` (function, line 640) `public:
            option_without_value(const std::string &name,
                               ...`
  - `has_value` (function, line 647) `bool has_value() const`
  - `set` (function, line 649) `bool set()`
  - `set` (function, line 654) `bool set(const std::string &)`
  - `has_set` (function, line 658) `bool has_set() const`
  - `valid` (function, line 662) `bool valid() const`
  - `must` (function, line 666) `bool must() const`
  - `name` (function, line 670) `const std::string &name() const`
  - `short_name` (function, line 674) `char short_name() const`
  - `description` (function, line 678) `const std::string &description() const`
  - `short_description` (function, line 682) `std::string short_description() const`
  - `option_with_value` (function, line 696) `public:
            option_with_value(const std::string &name,
                              char...`
  - `get` (function, line 707) `const T &get() const`
  - `has_value` (function, line 711) `bool has_value() const`
  - `set` (function, line 713) `bool set()`
  - `set` (function, line 717) `bool set(const std::string &value)`
  - `has_set` (function, line 728) `bool has_set() const`
  - `valid` (function, line 732) `bool valid() const`
  - `must` (function, line 737) `bool must() const`
  - `name` (function, line 741) `const std::string &name() const`
  - `short_name` (function, line 745) `char short_name() const`
  - `description` (function, line 749) `const std::string &description() const`
  - `short_description` (function, line 753) `std::string short_description() const`
  - `full_description` (function, line 758) `protected:
            std::string full_description(const std::string &desc)`
  - `option_with_value_with_reader` (function, line 780) `public:
            option_with_value_with_reader(const std::string &name,
                      ...`
  - `read` (function, line 790) `private:
            T read(const std::string &s)`
  - `argv` (function, line 416) `std::vector<const char*> argv(argc);`
- Imported by: `client/src/Havoc/Havoc.cc`

## client/include/Havoc/Connector.hpp
- Layer: infrastructure
- Language: hpp
- Symbols:
  - `Connector` (class, line 14)
  - `Disconnect` (function, line 27) `bool Disconnect();`
  - `SendLogin` (function, line 29) `void SendLogin();`
  - `SendPackage` (function, line 30) `void SendPackage( Util::Packager::PPackage package );`
  - `HAVOC_CONNECTOR_HPP` (macro, line 2) `#define HAVOC_CONNECTOR_HPP`
- Depends on: `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Connector.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Havoc.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/global.cc`

## client/include/Havoc/DemonCmdDispatch.h
- Layer: infrastructure
- Language: h
- Symbols:
  - `SubCommand` (struct, line 118)
  - `Command` (struct, line 130)
  - `Commands` (enum, line 23)
  - `CommandString` (type_alias, line 117) `typedef struct SubCommand { QString CommandString;`
  - `CommandString` (type_alias, line 129) `typedef struct Command { QString CommandString;`
  - `Commands` (class, line 23)
  - `DispatchOutput` (class, line 53)
  - `CommandExecute` (class, line 61)
  - `HAVOC_DEMONCMDDISPATCH_H` (macro, line 2) `#define HAVOC_DEMONCMDDISPATCH_H`
  - `SEND` (macro, line 12) `#define SEND( f )`
  - `CONSOLE_ERROR` (macro, line 15) `#define CONSOLE_ERROR( x )`
  - `CONSOLE_INFO` (macro, line 20) `#define CONSOLE_INFO( x )`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/Commands.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`

## client/include/Havoc/Havoc.hpp
- Layer: infrastructure
- Language: hpp
- Symbols:
  - `Init` (function, line 25) `void Init( int argc, char** argv );`
  - `Start` (function, line 26) `void Start();`
  - `Exit` (function, line 28) `static void Exit();`
  - `HAVOC_HAVOC_HPP` (macro, line 2) `#define HAVOC_HAVOC_HPP`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Connector.cc`, `client/src/Havoc/Havoc.cc`, `client/src/Havoc/Packager.cc`, `client/src/Main.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`

## client/include/Havoc/Packager.hpp
- Layer: infrastructure
- Language: hpp
- Symbols:
  - `Package` (struct, line 27)
  - `Head_t` (struct, line 12)
  - `Body_t` (struct, line 21)
  - `Head` (type_alias, line 26) `typedef struct Package { Head_t Head;`
  - `DecodePackage` (function, line 106) `public: static Util::Packager::PPackage DecodePackage(const QString& Package );`
  - `DispatchPackage` (function, line 109) `bool DispatchPackage( Util::Packager::PPackage Package );`
  - `setTeamserver` (function, line 110) `void setTeamserver(QString Name);`
  - `DispatchInitConnection` (function, line 113) `public: bool DispatchInitConnection( Util::Packager::PPackage Package );`
  - `DispatchListener` (function, line 114) `bool DispatchListener( Util::Packager::PPackage Package );`
  - `DispatchChat` (function, line 115) `bool DispatchChat( Util::Packager::PPackage Package );`
  - `DispatchSession` (function, line 116) `bool DispatchSession( Util::Packager::PPackage Package );`
  - `DispatchGate` (function, line 117) `bool DispatchGate( Util::Packager::PPackage Package );`
  - `DispatchService` (function, line 118) `bool DispatchService( Util::Packager::PPackage Package );`
  - `DispatchTeamserver` (function, line 119) `bool DispatchTeamserver( Util::Packager::PPackage Package );`
  - `Type` (variable, line 36) `extern const int Type;`
  - `Success` (variable, line 37) `extern const int Success;`
  - `Error` (variable, line 38) `extern const int Error;`
  - `Login` (variable, line 39) `extern const int Login;`
  - `Type` (variable, line 44) `extern const int Type;`
  - `Add` (variable, line 46) `extern const int Add;`
  - `Remove` (variable, line 47) `extern const int Remove;`
  - `Edit` (variable, line 48) `extern const int Edit;`
  - `Mark` (variable, line 49) `extern const int Mark;`
  - `Error` (variable, line 50) `extern const int Error;`
  - `Type` (variable, line 55) `extern const int Type;`
  - `NewMessage` (variable, line 57) `extern const int NewMessage;`
  - `NewListener` (variable, line 58) `extern const int NewListener;`
  - `NewUser` (variable, line 59) `extern const int NewUser;`
  - `UserDisconnect` (variable, line 60) `extern const int UserDisconnect;`
  - `NewSession` (variable, line 61) `extern const int NewSession;`
  - `Type` (variable, line 66) `extern const int Type;`
  - `Staged` (variable, line 68) `extern const int Staged;`
  - `Stageless` (variable, line 69) `extern const int Stageless;`
  - `MSOffice` (variable, line 70) `extern const int MSOffice;`
  - `Type` (variable, line 75) `extern const int Type;`
  - `NewSession` (variable, line 77) `extern const int NewSession;`
  - `SendCommand` (variable, line 78) `extern const int SendCommand;`
  - `ReceiveCommand` (variable, line 79) `extern const int ReceiveCommand;`
  - `MarkAs` (variable, line 80) `extern const int MarkAs;`
  - `Remove` (variable, line 81) `extern const int Remove;`
  - `Type` (variable, line 86) `extern const int Type;`
  - `AgentRegister` (variable, line 87) `extern const int AgentRegister;`
  - `ListenerRegister` (variable, line 88) `extern const int ListenerRegister;`
  - `Type` (variable, line 93) `extern const int Type;`
  - `Logger` (variable, line 94) `extern const int Logger;`
  - `Profile` (variable, line 95) `extern const int Profile;`
  - `HAVOC_PACKAGER_H` (macro, line 2) `#define HAVOC_PACKAGER_H`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/Havoc/Connector.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/Havoc/Service.hpp
- Layer: business_logic
- Language: hpp
- Symbols:
  - `CommandParam` (struct, line 10)
  - `AgentFormat` (struct, line 17)
  - `AgentCommands` (struct, line 23)
  - `ServiceAgent` (struct, line 34)
  - `DemonMagicValue` (variable, line 48) `extern uint64_t DemonMagicValue;`
  - `HAVOC_SERVICE_HPP` (macro, line 2) `#define HAVOC_SERVICE_HPP`
- Imported by: `client/include/global.hpp`, `client/src/Havoc/Service.cc`
