# Subsystem: PythonApi

## client/src/Havoc/PythonApi/Event.cc
- Doc: TODO: finish this.
- Layer: infrastructure
- Language: cc
- Symbols:
  - `EventClass_dealloc` (function, line 70) `void EventClass_dealloc( PPyEvents self )`
  - `EventClass_new` (function, line 77) `PyObject* EventClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
  - `EventClass_init` (function, line 86) `int EventClass_init( PPyEvents self, PyObject *args, PyObject *kwds )`
  - `EventClass_OnNewSession` (function, line 96) `PyObject* EventClass_OnNewSession( PPyEvents self, PyObject *args )`
  - `EventClass_OnDemonOutput` (function, line 112) `PyObject* EventClass_OnDemonOutput( PPyEvents self, PyObject *args )`
  - `AllocMov` (macro, line 62) `#define AllocMov( des, src, size )`
- Depends on: `client/include/Havoc/PythonApi/Event.h`

## client/src/Havoc/PythonApi/Havoc.cc
- Doc: RegisterCommand: RegisterCommand( PyFunction: func, Module: str, Command: str, Description: str...
- Layer: presentation
- Language: cc
- Symbols:
  - `PyInit_Havoc` (function, line 45) `PyMODINIT_FUNC PythonAPI::Havoc::PyInit_Havoc( void )`
  - `Load` (function, line 67) `PyObject* PythonAPI::Havoc::Core::Load( PyObject *self, PyObject *args )`
  - `GetListeners` (function, line 89) `PyObject* PythonAPI::Havoc::Core::GetListeners( PyObject *self, PyObject *args )`
  - `GetAgents` (function, line 105) `PyObject* PythonAPI::Havoc::Core::GetAgents( PyObject *self, PyObject *args )`
  - `GetDemons` (function, line 123) `PyObject* PythonAPI::Havoc::Core::GetDemons( PyObject *self, PyObject *args )`
  - `GeneratePayload` (function, line 139) `PyObject* PythonAPI::Havoc::Core::GeneratePayload( PyObject *self, PyObject *args, PyObject* kwar...`
  - `RegisterCommand` (function, line 188) `PyObject* PythonAPI::Havoc::Core::RegisterCommand( PyObject *self, PyObject *args, PyObject* kwar...`
  - `RegisterModule` (function, line 265) `PyObject* PythonAPI::Havoc::Core::RegisterModule( PyObject *self, PyObject *args )`
  - `RegisterCallback` (function, line 321) `PyObject* PythonAPI::Havoc::Core::RegisterCallback( PyObject *self, PyObject *args )`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/Havoc/PythonApi/Event.h`, `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/global.hpp`

## client/src/Havoc/PythonApi/HavocUi.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `CreateTab` (function, line 46) `PyObject* PythonAPI::HavocUI::Core::CreateTab(PyObject *self, PyObject *args)`
  - `connect` (function, line 76) `QMainWindow::connect( tupleCallback, &QAction::triggered, HavocX::HavocUserInterface->HavocWindow...`
  - `MessageBox` (function, line 84) `PyObject* PythonAPI::HavocUI::Core::MessageBox(PyObject *self, PyObject *args)`
  - `ErrorMessage` (function, line 108) `PyObject* PythonAPI::HavocUI::Core::ErrorMessage(PyObject *self, PyObject *args)`
  - `QuestionDialog` (function, line 123) `PyObject* PythonAPI::HavocUI::Core::QuestionDialog(PyObject *self, PyObject *args)`
  - `InputDialog` (function, line 141) `PyObject* PythonAPI::HavocUI::Core::InputDialog(PyObject *self, PyObject *args)`
  - `OpenFileDialog` (function, line 154) `PyObject* PythonAPI::HavocUI::Core::OpenFileDialog(PyObject *self, PyObject *args)`
  - `SaveFileDialog` (function, line 167) `PyObject* PythonAPI::HavocUI::Core::SaveFileDialog(PyObject *self, PyObject *args)`
  - `ColorDialog` (function, line 180) `PyObject* PythonAPI::HavocUI::Core::ColorDialog(PyObject *self, PyObject *args)`
  - `ProgressDialog` (function, line 192) `PyObject* PythonAPI::HavocUI::Core::ProgressDialog(PyObject *self, PyObject *args)`
  - `connect` (function, line 212) `QMainWindow::connect( timer, &QTimer::timeout, HavocX::HavocUserInterface->HavocWindow, [callable...`
  - `connect` (function, line 231) `QMainWindow::connect( cancelButton, &QPushButton::clicked, HavocX::HavocUserInterface->HavocWindo...`
  - `PyInit_HavocUI` (function, line 241) `PyMODINIT_FUNC PythonAPI::HavocUI::PyInit_HavocUI(void)`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`, `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`, `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`, `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`, `client/include/UserInterface/HavocUI.hpp`

## client/src/Havoc/PythonApi/PyAgentClass.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `AgentClass_dealloc` (function, line 69) `void AgentClass_dealloc( PPyAgentClass self )`
  - `AgentClass_new` (function, line 76) `PyObject* AgentClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
  - `AgentClass_init` (function, line 85) `int AgentClass_init( PPyAgentClass self, PyObject *args, PyObject *kwds )`
  - `AgentClass_ConsoleWrite` (function, line 112) `PyObject* AgentClass_ConsoleWrite( PPyAgentClass self, PyObject *args )`
  - `AgentClass_Command` (function, line 149) `PyObject* AgentClass_Command( PPyAgentClass self, PyObject *args )`
  - `PY_SSIZE_T_CLEAN` (macro, line 2) `#define PY_SSIZE_T_CLEAN`
- Depends on: `client/include/Havoc/PythonApi/PyAgentClass.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

## client/src/Havoc/PythonApi/PyDemonClass.cc
- Doc: DemonClass_Shell: Demon.shell( TaskID: str, ShellCommands: str )
- Layer: presentation
- Language: cc
- Symbols:
  - `DemonClass_dealloc` (function, line 100) `void DemonClass_dealloc( PPyDemonClass self )`
  - `DemonClass_new` (function, line 119) `PyObject* DemonClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds )`
  - `DemonClass_init` (function, line 128) `int DemonClass_init( PPyDemonClass self, PyObject *args, PyObject *kwds )`
  - `DemonClass_Shell` (function, line 179) `PyObject* DemonClass_Shell( PPyDemonClass self, PyObject *args )`
  - `DemonClass_InlineExecute` (function, line 200) `PyObject* DemonClass_InlineExecute( PPyDemonClass self, PyObject *args )`
  - `DemonClass_InlineExecuteGetOutput` (function, line 250) `PyObject* DemonClass_InlineExecuteGetOutput( PPyDemonClass self, PyObject *args )`
  - `DemonClass_DotnetInlineExecute` (function, line 312) `PyObject* DemonClass_DotnetInlineExecute( PPyDemonClass self, PyObject *args )`
  - `DemonClass_Command` (function, line 333) `PyObject* DemonClass_Command( PPyDemonClass self, PyObject *args )`
  - `DemonClass_CommandGetOutput` (function, line 353) `PyObject* DemonClass_CommandGetOutput( PPyDemonClass self, PyObject *args )`
  - `DemonClass_ShellcodeSpawn` (function, line 389) `PyObject* DemonClass_ShellcodeSpawn( PPyDemonClass self, PyObject *args )`
  - `DemonClass_DllInject` (function, line 430) `PyObject* DemonClass_DllInject( PPyDemonClass self, PyObject *args )`
  - `DemonClass_DllSpawn` (function, line 453) `PyObject* DemonClass_DllSpawn( PPyDemonClass self, PyObject *args )`
  - `DemonClass_ProcessCreate` (function, line 491) `PyObject* DemonClass_ProcessCreate( PPyDemonClass self, PyObject *args )`
  - `DemonClass_ConsoleWrite` (function, line 539) `PyObject* DemonClass_ConsoleWrite( PPyDemonClass self, PyObject *args )`
  - `PY_SSIZE_T_CLEAN` (macro, line 2) `#define PY_SSIZE_T_CLEAN`
  - `AllocMov` (macro, line 92) `#define AllocMov( des, src, size )`
- Depends on: `client/include/Havoc/PythonApi/PyDemonClass.h`, `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`

## client/src/Havoc/PythonApi/PythonApi.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `Stdout_write` (function, line 5) `PyObject* Stdout_write(PyObject* self, PyObject* args)`
  - `Stdout_flush` (function, line 22) `PyObject* Stdout_flush(PyObject* self, PyObject* args)`
  - `PyInit_emb` (function, line 87) `PyMODINIT_FUNC PyInit_emb(void)`
  - `set_stdout` (function, line 105) `void set_stdout(stdout_write_type write)`
  - `reset_stdout` (function, line 118) `void reset_stdout()`
  - `written` (function, line 7) `std::size_t written(0);`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`
