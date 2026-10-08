# client/include/UserInterface/Widgets

*Community 1 | 64 files | cohesion 0.86*

## Definition

This community groups 64 file(s) rooted at `client/include/UserInterface/Widgets` with dominant language cc (cohesion 0.86). Central symbols: `Add`, `AddCommand`, `AddData`, `AddDownload`, `AddLoggerText`, `AddScreenshot`, `AddScript`, `AddScriptTable`. Core file: `client/include/Havoc/CmdLine.hpp` (83 symbols). Documented purpose: TODO: refactor this.

## Files

### `client/include/UserInterface/Widgets` (13 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/include/UserInterface/Widgets/Chat.hpp` | hpp | presentation | 5 | no |
| `client/include/UserInterface/Widgets/DemonInteracted.h` | h | presentation | 16 | no |

### `client/src/UserInterface/Widgets` (13 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/src/UserInterface/Widgets/Chat.cc` | cc | presentation | 4 | no |
| `client/src/UserInterface/Widgets/DemonInteracted.cc` | cc | presentation | 17 | no |

### `client/include/Havoc` (6 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/include/Havoc/CmdLine.hpp` | hpp | infrastructure | 83 | no |
| `client/include/Havoc/Connector.hpp` | hpp | infrastructure | 5 | no |

### `client/src/Havoc` (4 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/src/Havoc/Connector.cc` | cc | infrastructure | 7 | no |
| `client/src/Havoc/Havoc.cc` | cc | infrastructure | 5 | no |

### `client/src/Havoc/Demon` (4 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/src/Havoc/Demon/CommandOutput.cc` | cc | infrastructure | 1 | no |

### `client/src/Havoc/PythonApi` (4 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/src/Havoc/PythonApi/Event.cc` | cc | infrastructure | 6 | yes |

### `client/include/Havoc/PythonApi` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/include/Havoc/PythonApi/Event.h` | h | infrastructure | 7 | no |

### `client/include/Util` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/include/Util/Base.hpp` | hpp | infrastructure | 1 | no |

### `client/src/Util` (3 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/src/Util/Base.cpp` | cpp | infrastructure | 0 | no |

### `client/include` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/include/External.h` | h | infrastructure | 1 | no |

### `client/include/UserInterface/Dialogs` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/include/UserInterface/Dialogs/Listener.hpp` | hpp | infrastructure | 5 | no |

### `client/src` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/src/Main.cc` | cc | infrastructure | 0 | no |

### `client/src/UserInterface/Dialogs` (2 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/src/UserInterface/Dialogs/Listener.cc` | cc | infrastructure | 13 | no |

### `client/include/UserInterface/SmallWidgets` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/include/UserInterface/SmallWidgets/EventViewer.hpp` | hpp | presentation | 3 | no |

### `client/src/UserInterface` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/src/UserInterface/HavocUi.cc` | cc | presentation | 30 | yes |

### `client/src/UserInterface/SmallWidgets` (1 files)

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `client/src/UserInterface/SmallWidgets/EventViewer.cc` | cc | presentation | 2 | no |

*... and 44 more files in this community.*


## Key Symbols

- `HAVOC_EXTERNAL_H` (macro, `client/include/External.h:2`) `#define HAVOC_EXTERNAL_H`
- `lexical_cast_t` (class, `client/include/Havoc/CmdLine.hpp:45`)
- `cast` (function, `client/include/Havoc/CmdLine.hpp:47`) `public:             static Target cast(const Source &arg)`
- `cast` (function, `client/include/Havoc/CmdLine.hpp:60`) `public:             static Target cast(const Source &arg)`
- `cast` (function, `client/include/Havoc/CmdLine.hpp:68`) `public:             static std::string cast(const Source &arg)`
- `cast` (function, `client/include/Havoc/CmdLine.hpp:78`) `public:             static Target cast(const std::string &arg)`
- `is_same` (struct, `client/include/Havoc/CmdLine.hpp:88`)
- `lexical_cast` (function, `client/include/Havoc/CmdLine.hpp:98`) `Target lexical_cast(const Source &arg)`
- `demangle` (function, `client/include/Havoc/CmdLine.hpp:103`) `static inline std::string demangle(const std::string &name)`
- `readable_typename` (function, `client/include/Havoc/CmdLine.hpp:113`) `template <class T>         std::string readable_typename()`
- `default_value` (function, `client/include/Havoc/CmdLine.hpp:119`) `template <class T>         std::string default_value(T def)`
- `cmdline_error` (function, `client/include/Havoc/CmdLine.hpp:136`) `public:         cmdline_error(const std::string &msg): msg(msg)`
- `what` (function, `client/include/Havoc/CmdLine.hpp:138`) `const char *what() const throw()`
- `default_reader` (struct, `client/include/Havoc/CmdLine.hpp:144`)
- `operator` (function, `client/include/Havoc/CmdLine.hpp:145`) `T operator()(const std::string &str)`
- `range_reader` (struct, `client/include/Havoc/CmdLine.hpp:151`)
- `range_reader` (function, `client/include/Havoc/CmdLine.hpp:152`) `range_reader(const T &low, const T &high): low(low), high(high)`
- `operator` (function, `client/include/Havoc/CmdLine.hpp:153`) `T operator()(const std::string &s) const`
- `range` (function, `client/include/Havoc/CmdLine.hpp:163`) `template <class T>     range_reader<T> range(const T &low, const T &high)`
- `oneof_reader` (struct, `client/include/Havoc/CmdLine.hpp:169`)
- `operator` (function, `client/include/Havoc/CmdLine.hpp:170`) `T operator()(const std::string &s)`
- `add` (function, `client/include/Havoc/CmdLine.hpp:176`) `void add(const T &v)`
- `oneof` (function, `client/include/Havoc/CmdLine.hpp:182`) `template <class T>     oneof_reader<T> oneof(T a1)`
- `oneof` (function, `client/include/Havoc/CmdLine.hpp:190`) `template <class T>     oneof_reader<T> oneof(T a1, T a2)`
- `oneof` (function, `client/include/Havoc/CmdLine.hpp:199`) `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3)`
- `oneof` (function, `client/include/Havoc/CmdLine.hpp:209`) `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3, T a4)`
- `oneof` (function, `client/include/Havoc/CmdLine.hpp:220`) `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5)`
- `oneof` (function, `client/include/Havoc/CmdLine.hpp:232`) `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6)`
- `oneof` (function, `client/include/Havoc/CmdLine.hpp:245`) `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6,`
- `oneof` (function, `client/include/Havoc/CmdLine.hpp:259`) `template <class T>     oneof_reader<T> oneof(T a1, T a2, T a3, T a4, T a5, T a6,`

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 173
- Cross-boundary resolved imports (EXTRACTED): 28

## Connections

- [EXTRACTED] depends_on community 3 <-> 1 (strength 0.9): Extracted import edge crosses communities: client/include/Havoc/DBManager/DBManager.hpp imports client/include/global.hpp.
- [INFERRED] bridges community 1 <-> 3 (strength 0.5): Inferred cross-community bridge: client/include/Havoc/CmdLine.hpp reaches client/src/Havoc/PythonApi/PythonApi.cc in 5 hops.
- [INFERRED] bridges community 1 <-> 3 (strength 0.5): Inferred cross-community bridge: client/include/Havoc/CmdLine.hpp reaches client/src/Havoc/PythonApi/UI/PyDialogClass.cc in 5 hops.
- [INFERRED] bridges community 1 <-> 3 (strength 0.5): Inferred cross-community bridge: client/include/Havoc/CmdLine.hpp reaches client/src/Havoc/PythonApi/UI/PyLoggerClass.cc in 5 hops.
- [INFERRED] bridges community 1 <-> 3 (strength 0.5): Inferred cross-community bridge: client/include/Havoc/CmdLine.hpp reaches client/src/Havoc/PythonApi/UI/PyTreeClass.cc in 5 hops.
- [INFERRED] bridges community 1 <-> 3 (strength 0.5): Inferred cross-community bridge: client/include/Havoc/CmdLine.hpp reaches client/src/Havoc/PythonApi/UI/PyWidgetClass.cc in 5 hops.

## Risks

- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/global.hpp` via `input` (2 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/UserInterface/Widgets/Chat.hpp` via `input` (2 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/UserInterface/Widgets/ListenerTable.hpp` via `input` (2 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/UserInterface/Dialogs/Listener.hpp` via `input` (2 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/UserInterface/Widgets/SessionTable.hpp` via `input` (2 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/UserInterface/Dialogs/Payload.hpp` via `input` (2 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/UserInterface/Widgets/FileBrowser.hpp` via `input` (3 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/Util/Base.hpp` via `input` (3 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/Havoc/Service.hpp` via `input` (3 hops)
- [taint medium] `client/src/Havoc/PythonApi/HavocUi.cc` -> `client/include/External.h` via `input` (3 hops)
- [dataflow DEAD_STORE] `client/include/Havoc/CmdLine.hpp:415` `parse` `argc`: `argc` assigned at line 415 but never read afterwards.

## Open Questions

- Why do 60 file(s) lack file-level docs (e.g. `client/include/External.h`)? What purpose do they serve?
- What would break if the most connected file in client/include/UserInterface/Widgets changed?
- Should client/include/UserInterface/Widgets be split, given cohesion 0.86?

## Sources

- `client/include/External.h`
- `client/include/Havoc/CmdLine.hpp`
- `client/include/Havoc/Connector.hpp`
- `client/include/Havoc/DemonCmdDispatch.h`
- `client/include/Havoc/Havoc.hpp`
- `client/include/Havoc/Packager.hpp`
- `client/include/Havoc/PythonApi/Event.h`
- `client/include/Havoc/PythonApi/PyAgentClass.hpp`
- `client/include/Havoc/PythonApi/PyDemonClass.h`
- `client/include/Havoc/Service.hpp`
- `client/include/UserInterface/Dialogs/Listener.hpp`
- `client/include/UserInterface/Dialogs/Payload.hpp`
- `client/include/UserInterface/SmallWidgets/EventViewer.hpp`
- `client/include/UserInterface/Widgets/Chat.hpp`
- `client/include/UserInterface/Widgets/DemonInteracted.h`
- `client/include/UserInterface/Widgets/FileBrowser.hpp`
- `client/include/UserInterface/Widgets/ListenerTable.hpp`
- `client/include/UserInterface/Widgets/LootWidget.h`
- `client/include/UserInterface/Widgets/ProcessList.hpp`
- `client/include/UserInterface/Widgets/PythonScript.hpp`
- *... and 44 more*
