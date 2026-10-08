# Subsystem: include

## client/include/External.h
- Layer: infrastructure
- Language: h
- Symbols:
  - `HAVOC_EXTERNAL_H` (macro, line 2) `#define HAVOC_EXTERNAL_H`
- Imported by: `client/include/global.hpp`

## client/include/global.hpp
- Doc: u32: pragma push_macro("slots") undef slots include <Python.h> pragma pop_macro("slots")
- Layer: infrastructure
- Language: hpp
- Symbols:
  - `RegisteredCommand` (struct, line 78)
  - `RegisteredModule` (struct, line 93)
  - `ListenerItem` (struct, line 106)
  - `Listener` (struct, line 145)
  - `HTTP` (struct, line 152)
  - `SMB` (struct, line 172)
  - `External` (struct, line 177)
  - `SessionItem` (struct, line 209)
  - `ConnectionInfo` (struct, line 248)
  - `u32` (type_alias, line 46) `typedef uint32_t u32;`
  - `u64` (type_alias, line 48) `typedef uint64_t u64;`
  - `PCHAR` (type_alias, line 51) `typedef char* PCHAR;`
  - `BYTE` (type_alias, line 52) `typedef char BYTE;`
  - `PVOID` (type_alias, line 53) `typedef void* PVOID;`
  - `LPVOID` (type_alias, line 54) `typedef void* LPVOID;`
  - `UINT_PTR` (type_alias, line 55) `typedef unsigned long int UINT_PTR;`
  - `MapStrStr` (type_alias, line 58) `typedef std::map<std::string, std::string> MapStrStr;`
  - `MapStrAny` (type_alias, line 59) `typedef std::map<std::string, std::any> MapStrAny;`
  - `Agent` (type_alias, line 77) `typedef struct RegisteredCommand { /* for what agent is it this command */ std::string Agent;`
  - `Agent` (type_alias, line 92) `typedef struct RegisteredModule { /* for what agent is it this command */ std::string Agent;`
  - `Name` (type_alias, line 105) `typedef struct ListenerItem { std::string Name;`
  - `Service` (type_alias, line 181) `typedef MapStrStr Service;`
  - `Export` (function, line 245) `void Export();`
  - `Version` (variable, line 68) `extern std::string Version;`
  - `CodeName` (variable, line 69) `extern std::string CodeName;`
  - `HavocApplication` (variable, line 190) `extern HavocNamespace::HavocSpace::Havoc* HavocApplication;`
  - `DebugMode` (variable, line 277) `extern bool DebugMode;`
  - `GateGUI` (variable, line 278) `extern bool GateGUI;`
  - `callbackGate` (variable, line 279) `extern PyObject* callbackGate;`
  - `callbackMessage` (variable, line 280) `extern PyObject* callbackMessage;`
  - `Teamserver` (variable, line 281) `extern HavocNamespace::Util::ConnectionInfo Teamserver;`
  - `HavocUserInterface` (variable, line 282) `extern HavocNamespace::UserInterface::HavocUi* HavocUserInterface;`
  - `Connector` (variable, line 283) `extern HavocNamespace::Connector* Connector;`
  - `HAVOC_GLOBAL_HPP` (macro, line 2) `#define HAVOC_GLOBAL_HPP`
- Depends on: `client/include/External.h`, `client/include/Havoc/Service.hpp`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`
- Imported by: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/DemonCmdDispatch.h`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/Dialogs/About.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/Base64.h`, `client/include/Util/ColorText.h`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Main.cc`, `client/src/UserInterface/Dialogs/About.cc`, `client/src/UserInterface/Dialogs/Connect.cc`, `client/src/UserInterface/Dialogs/Listener.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/Store.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/Base64.cpp`, `client/src/global.cc`
