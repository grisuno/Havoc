# client/include/Havoc/PythonApi/UI

*Community 3 | 20 files | cohesion 0.50*

## Definition

This community groups 20 file(s) rooted at `client/include/Havoc/PythonApi/UI` with dominant language cc (cohesion 0.50). Central symbols: `About`, `AddScript`, `AllocMov`, `CheckScript`, `ColorDialog`, `ConnectEvents`, `CreateTab`, `DBManager`. Core file: `client/src/Havoc/PythonApi/UI/PyDialogClass.cc` (25 symbols). Documented purpose: QT libraries.

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/include/Havoc/DBManager/DBManager.hpp` | hpp | infrastructure | 9 | no |
| `client/include/Havoc/PythonApi/PythonApi.h` | h | presentation | 13 | no |
| `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp` | hpp | presentation | 18 | no |
| `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp` | hpp | presentation | 9 | no |
| `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp` | hpp | presentation | 10 | no |
| `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp` | hpp | presentation | 18 | no |
| `client/include/UserInterface/Dialogs/About.hpp` | hpp | infrastructure | 4 | no |
| `client/include/UserInterface/Dialogs/Connect.hpp` | hpp | infrastructure | 9 | no |
| `client/include/UserInterface/HavocUI.hpp` | hpp | presentation | 12 | yes |
| `client/src/Havoc/DBManger/DBManager.cc` | cc | infrastructure | 2 | no |
| `client/src/Havoc/DBManger/Scripts.cc` | cc | infrastructure | 4 | no |
| `client/src/Havoc/DBManger/Teamserver.cc` | cc | infrastructure | 5 | no |
| `client/src/Havoc/PythonApi/HavocUi.cc` | cc | presentation | 13 | no |
| `client/src/Havoc/PythonApi/PythonApi.cc` | cc | presentation | 6 | no |
| `client/src/Havoc/PythonApi/UI/PyDialogClass.cc` | cc | presentation | 25 | no |
| `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc` | cc | presentation | 9 | no |
| `client/src/Havoc/PythonApi/UI/PyTreeClass.cc` | cc | presentation | 11 | no |
| `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc` | cc | presentation | 25 | no |
| `client/src/UserInterface/Dialogs/About.cc` | cc | infrastructure | 3 | no |
| `client/src/UserInterface/Dialogs/Connect.cc` | cc | infrastructure | 14 | no |

## Key Symbols

- `HAVOC_DBMANAGER_HPP` (macro, `client/include/Havoc/DBManager/DBManager.hpp:2`) `#define HAVOC_DBMANAGER_HPP`
- `createNewDatabase` (function, `client/include/Havoc/DBManager/DBManager.hpp:17`) `bool createNewDatabase();`
- `addTeamserverInfo` (function, `client/include/Havoc/DBManager/DBManager.hpp:27`) `bool addTeamserverInfo( const Util::ConnectionInfo& );`
- `checkTeamserverExists` (function, `client/include/Havoc/DBManager/DBManager.hpp:28`) `bool checkTeamserverExists( const QString& ProfileName );`
- `removeTeamserverInfo` (function, `client/include/Havoc/DBManager/DBManager.hpp:29`) `bool removeTeamserverInfo( const QString& ProfileName );`
- `removeAllTeamservers` (function, `client/include/Havoc/DBManager/DBManager.hpp:30`) `bool removeAllTeamservers();`
- `AddScript` (function, `client/include/Havoc/DBManager/DBManager.hpp:33`) `bool AddScript( QString Path );`
- `RemoveScript` (function, `client/include/Havoc/DBManager/DBManager.hpp:34`) `bool RemoveScript( QString Path );`
- `CheckScript` (function, `client/include/Havoc/DBManager/DBManager.hpp:35`) `bool CheckScript( QString Path );`
- `HAVOC_PYTHONAPI_H` (macro, `client/include/Havoc/PythonApi/PythonApi.h:2`) `#define HAVOC_PYTHONAPI_H`
- `PY_FUNCTION` (macro, `client/include/Havoc/PythonApi/PythonApi.h:10`) `#define PY_FUNCTION( x )`
- `PY_FUNCTION_KW` (macro, `client/include/Havoc/PythonApi/PythonApi.h:11`) `#define PY_FUNCTION_KW( x )`
- `PyMethode_Havoc` (variable, `client/include/Havoc/PythonApi/PythonApi.h:17`) `extern PyMethodDef PyMethode_Havoc[];`
- `havoc` (variable, `client/include/Havoc/PythonApi/PythonApi.h:33`) `extern struct PyModuleDef havoc;`
- `PyMethode_HavocUI` (variable, `client/include/Havoc/PythonApi/PythonApi.h:41`) `extern PyMethodDef PyMethode_HavocUI[];`
- `havocui` (variable, `client/include/Havoc/PythonApi/PythonApi.h:58`) `extern struct PyModuleDef havocui;`
- `stdout_write_type` (type_alias, `client/include/Havoc/PythonApi/PythonApi.h:68`) `typedef std::function<void(std::string)> stdout_write_type;`
- `Stdout` (struct, `client/include/Havoc/PythonApi/PythonApi.h:70`)
- `Stdout_write` (function, `client/include/Havoc/PythonApi/PythonApi.h:76`) `PyObject* Stdout_write(PyObject* self, PyObject* args);`
- `Stdout_flush` (function, `client/include/Havoc/PythonApi/PythonApi.h:77`) `PyObject* Stdout_flush(PyObject* self, PyObject* args);`
- `set_stdout` (function, `client/include/Havoc/PythonApi/PythonApi.h:79`) `void set_stdout(stdout_write_type write);`
- `reset_stdout` (function, `client/include/Havoc/PythonApi/PythonApi.h:80`) `void reset_stdout();`
- `HAVOC_PYDIALOGCLASS_H` (macro, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:2`) `#define HAVOC_PYDIALOGCLASS_H`
- `PyDialogClass_Type` (variable, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:39`) `extern PyTypeObject PyDialogClass_Type;`
- `DialogClass_dealloc` (function, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:41`) `void DialogClass_dealloc( PPyDialogClass self );`
- `DialogClass_new` (function, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:42`) `PyObject* DialogClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
- `DialogClass_init` (function, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:43`) `int DialogClass_init( PPyDialogClass self, PyObject *args, PyObject *kwds );`
- `DialogClass_exec` (function, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:47`) `PyObject* DialogClass_exec( PPyDialogClass self, PyObject *args );`
- `DialogClass_close` (function, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:48`) `PyObject* DialogClass_close( PPyDialogClass self, PyObject *args );`
- `DialogClass_clear` (function, `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp:49`) `PyObject* DialogClass_clear( PPyDialogClass self, PyObject *args );`

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 28
- Cross-boundary resolved imports (EXTRACTED): 28

## Connections

- [EXTRACTED] depends_on community 3 <-> 1 (strength 0.9): Extracted import edge crosses communities: client/include/Havoc/DBManager/DBManager.hpp imports client/include/global.hpp.
- [INFERRED] bridges community 1 <-> 3 (strength 0.5): Inferred cross-community bridge: client/include/Havoc/CmdLine.hpp reaches client/src/Havoc/PythonApi/PythonApi.cc in 5 hops.
- [INFERRED] bridges community 1 <-> 3 (strength 0.5): Inferred cross-community bridge: client/include/Havoc/CmdLine.hpp reaches client/src/Havoc/PythonApi/UI/PyDialogClass.cc in 5 hops.
- [INFERRED] bridges community 1 <-> 3 (strength 0.5): Inferred cross-community bridge: client/include/Havoc/CmdLine.hpp reaches client/src/Havoc/PythonApi/UI/PyLoggerClass.cc in 5 hops.
- [INFERRED] bridges community 1 <-> 3 (strength 0.5): Inferred cross-community bridge: client/include/Havoc/CmdLine.hpp reaches client/src/Havoc/PythonApi/UI/PyTreeClass.cc in 5 hops.
- [INFERRED] bridges community 1 <-> 3 (strength 0.5): Inferred cross-community bridge: client/include/Havoc/CmdLine.hpp reaches client/src/Havoc/PythonApi/UI/PyWidgetClass.cc in 5 hops.

## Risks

- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/src/Havoc/PythonApi/HavocUi.cc` via `input` (0 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/Havoc/PythonApi/PythonApi.h` via `input` (1 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp` via `input` (1 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp` via `input` (1 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp` via `input` (1 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp` via `input` (1 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/UserInterface/HavocUI.hpp` via `input` (1 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/global.hpp` via `input` (2 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/UserInterface/Widgets/Chat.hpp` via `input` (2 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/UserInterface/Dialogs/Connect.hpp` via `input` (2 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/UserInterface/Widgets/ListenerTable.hpp` via `input` (2 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/Havoc/DBManager/DBManager.hpp` via `input` (2 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/UserInterface/Dialogs/Listener.hpp` via `input` (2 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/UserInterface/Widgets/SessionTable.hpp` via `input` (2 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/UserInterface/Dialogs/Payload.hpp` via `input` (2 hops)

## Open Questions

- Why do 19 file(s) lack file-level docs (e.g. `client/include/Havoc/DBManager/DBManager.hpp`)? What purpose do they serve?
- Is the dangerous import `input` in `client/src/Havoc/PythonApi/HavocUi.cc` still required, or can it be isolated?
- What would break if the most connected file in client/include/Havoc/PythonApi/UI changed?
- Should client/include/Havoc/PythonApi/UI be split, given cohesion 0.50?

## Sources

- `client/include/Havoc/DBManager/DBManager.hpp`
- `client/include/Havoc/PythonApi/PythonApi.h`
- `client/include/Havoc/PythonApi/UI/PyDialogClass.hpp`
- `client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp`
- `client/include/Havoc/PythonApi/UI/PyTreeClass.hpp`
- `client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp`
- `client/include/UserInterface/Dialogs/About.hpp`
- `client/include/UserInterface/Dialogs/Connect.hpp`
- `client/include/UserInterface/HavocUI.hpp`
- `client/src/Havoc/DBManger/DBManager.cc`
- `client/src/Havoc/DBManger/Scripts.cc`
- `client/src/Havoc/DBManger/Teamserver.cc`
- `client/src/Havoc/PythonApi/HavocUi.cc`
- `client/src/Havoc/PythonApi/PythonApi.cc`
- `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`
- `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`
- `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`
- `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`
- `client/src/UserInterface/Dialogs/About.cc`
- `client/src/UserInterface/Dialogs/Connect.cc`
