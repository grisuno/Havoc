# Subsystem: PythonApi

## client/include/Havoc/PythonApi/Event.h
- Layer: infrastructure
- Doc: ifndef HAVOC_EVENT_H define HAVOC_EVENT_H  include <global.hpp>
- Language: h
- Symbols:
  - `EventClass_dealloc` (function, line 15) `void EventClass_dealloc( PPyEvents self );`
  - `EventClass_new` (function, line 17) `PyObject* EventClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
  - `EventClass_init` (function, line 18) `int EventClass_init( PPyEvents self, PyObject *args, PyObject *kwds );`
  - `EventClass_OnNewSession` (function, line 21) `PyObject* EventClass_OnNewSession( PPyEvents self, PyObject *args );`
  - `EventClass_OnDemonOutput` (function, line 23) `PyObject* EventClass_OnDemonOutput( PPyEvents self, PyObject *args );`
  - `PyEventClass_Type` (variable, line 13) `extern PyTypeObject PyEventClass_Type;`
  - `HAVOC_EVENT_H` (macro, line 2) `#define HAVOC_EVENT_H`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Event.cc`, `client/src/Havoc/PythonApi/Havoc.cc`

## client/include/Havoc/PythonApi/HavocUi.h
- Layer: presentation
- Doc: ifndef HAVOC_HAVOCUI_H define HAVOC_HAVOCUI_H  endif
- Language: h
- Symbols:
  - `HAVOC_HAVOCUI_H` (macro, line 2) `#define HAVOC_HAVOCUI_H`

## client/include/Havoc/PythonApi/PyAgentClass.hpp
- Layer: presentation
- Doc: ifndef HAVOC_PYAGENTCLASS_HPP define HAVOC_PYAGENTCLASS_HPP  include <global.hpp>  define AllocMov( des, src, size )    
- Language: hpp
- Symbols:
  - `memset` (function, line 10) `memset( des, 0, size );`
  - `strcpy` (function, line 11) `std::strcpy( des, src );`
  - `AgentClass_dealloc` (function, line 26) `void AgentClass_dealloc( PPyAgentClass self );`
  - `AgentClass_new` (function, line 28) `PyObject* AgentClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
  - `AgentClass_init` (function, line 29) `int AgentClass_init( PPyAgentClass self, PyObject *args, PyObject *kwds );`
  - `AgentClass_ConsoleWrite` (function, line 30) `PyObject* AgentClass_ConsoleWrite( PPyAgentClass self, PyObject *args );`
  - `AgentClass_Command` (function, line 31) `PyObject* AgentClass_Command( PPyAgentClass self, PyObject *args );`
  - `PyAgentClass_Type` (variable, line 24) `extern PyTypeObject PyAgentClass_Type;`
  - `HAVOC_PYAGENTCLASS_HPP` (macro, line 2) `#define HAVOC_PYAGENTCLASS_HPP`
  - `AllocMov` (macro, line 5) `#define AllocMov( des, src, size )`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`

## client/include/Havoc/PythonApi/PyDemonClass.h
- Layer: presentation
- Doc: ifndef HAVOC_PYDEMONCLASS_H define HAVOC_PYDEMONCLASS_H  include <global.hpp>
- Language: h
- Symbols:
  - `DemonClass_dealloc` (function, line 35) `void DemonClass_dealloc( PPyDemonClass self );`
  - `DemonClass_new` (function, line 37) `PyObject* DemonClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
  - `DemonClass_init` (function, line 38) `int DemonClass_init( PPyDemonClass self, PyObject *args, PyObject *kwds );`
  - `DemonClass_ProcessCreate` (function, line 45) `PyObject* DemonClass_ProcessCreate( PPyDemonClass self, PyObject *args );`
  - `DemonClass_DllInject` (function, line 46) `PyObject* DemonClass_DllInject( PPyDemonClass self, PyObject *args );`
  - `DemonClass_DllSpawn` (function, line 47) `PyObject* DemonClass_DllSpawn( PPyDemonClass self, PyObject *args );`
  - `DemonClass_InlineExecute` (function, line 48) `PyObject* DemonClass_InlineExecute( PPyDemonClass self, PyObject *args );`
  - `DemonClass_InlineExecuteGetOutput` (function, line 49) `PyObject* DemonClass_InlineExecuteGetOutput( PPyDemonClass self, PyObject *args );`
  - `DemonClass_DotnetInlineExecute` (function, line 50) `PyObject* DemonClass_DotnetInlineExecute( PPyDemonClass self, PyObject *args );`
  - `DemonClass_RegisterCallback` (function, line 51) `PyObject* DemonClass_RegisterCallback( PPyDemonClass self, PyObject *args );`
  - `DemonClass_Command` (function, line 52) `PyObject* DemonClass_Command( PPyDemonClass self, PyObject *args );`
  - `DemonClass_CommandGetOutput` (function, line 53) `PyObject* DemonClass_CommandGetOutput( PPyDemonClass self, PyObject *args );`
  - `DemonClass_ShellcodeSpawn` (function, line 54) `PyObject* DemonClass_ShellcodeSpawn( PPyDemonClass self, PyObject *args );`
  - `DemonClass_ConsoleWrite` (function, line 57) `PyObject* DemonClass_ConsoleWrite( PPyDemonClass self, PyObject *args );`
  - `PyDemonClass_Type` (variable, line 33) `extern PyTypeObject PyDemonClass_Type;`
  - `HAVOC_PYDEMONCLASS_H` (macro, line 2) `#define HAVOC_PYDEMONCLASS_H`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`

## client/include/Havoc/PythonApi/PythonApi.h
- Layer: presentation
- Doc: ifndef HAVOC_PYTHONAPI_H define HAVOC_PYTHONAPI_H  include <global.hpp> pragma push_macro("slots") undef slots include <
- Language: h
- Symbols:
  - `Stdout` (struct, line 70)
  - `stdout_write_type` (type_alias, line 68) `typedef std::function<void(std::string)> stdout_write_type;`
  - `PyInit_Havoc` (function, line 35) `PyMODINIT_FUNC PyInit_Havoc(void);`
  - `PyInit_HavocUI` (function, line 60) `PyMODINIT_FUNC PyInit_HavocUI(void);`
  - `Stdout_write` (function, line 75) `PyObject* Stdout_write(PyObject* self, PyObject* args);`
  - `Stdout_flush` (function, line 77) `PyObject* Stdout_flush(PyObject* self, PyObject* args);`
  - `PyInit_emb` (function, line 78) `PyMODINIT_FUNC PyInit_emb(void);`
  - `set_stdout` (function, line 79) `void set_stdout(stdout_write_type write);`
  - `reset_stdout` (function, line 80) `void reset_stdout();`
  - `PyMethode_Havoc` (variable, line 17) `extern PyMethodDef PyMethode_Havoc[];`
  - `havoc` (variable, line 33) `extern struct PyModuleDef havoc;`
  - `PyMethode_HavocUI` (variable, line 41) `extern PyMethodDef PyMethode_HavocUI[];`
  - `havocui` (variable, line 58) `extern struct PyModuleDef havocui;`
  - `HAVOC_PYTHONAPI_H` (macro, line 2) `#define HAVOC_PYTHONAPI_H`
  - `PY_FUNCTION` (macro, line 9) `#define PY_FUNCTION( x )`
  - `PY_FUNCTION_KW` (macro, line 11) `#define PY_FUNCTION_KW( x )`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/Havoc/PythonApi/PythonApi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`
