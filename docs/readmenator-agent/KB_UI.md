# Subsystem: UI

## client/include/Havoc/PythonApi/UI/PyDialogClass.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `DialogClass_dealloc` (function, line 41) `void DialogClass_dealloc( PPyDialogClass self );`
  - `DialogClass_new` (function, line 42) `PyObject* DialogClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
  - `DialogClass_init` (function, line 43) `int DialogClass_init( PPyDialogClass self, PyObject *args, PyObject *kwds );`
  - `DialogClass_exec` (function, line 47) `PyObject* DialogClass_exec( PPyDialogClass self, PyObject *args );`
  - `DialogClass_close` (function, line 48) `PyObject* DialogClass_close( PPyDialogClass self, PyObject *args );`
  - `DialogClass_clear` (function, line 49) `PyObject* DialogClass_clear( PPyDialogClass self, PyObject *args );`
  - `DialogClass_addLabel` (function, line 50) `PyObject* DialogClass_addLabel( PPyDialogClass self, PyObject *args );`
  - `DialogClass_addButton` (function, line 51) `PyObject* DialogClass_addButton( PPyDialogClass self, PyObject *args );`
  - `DialogClass_addCheckbox` (function, line 52) `PyObject* DialogClass_addCheckbox( PPyDialogClass self, PyObject *args );`
  - `DialogClass_addCombobox` (function, line 53) `PyObject* DialogClass_addCombobox( PPyDialogClass self, PyObject *args );`
  - `DialogClass_addLineedit` (function, line 54) `PyObject* DialogClass_addLineedit( PPyDialogClass self, PyObject *args );`
  - `DialogClass_addCalendar` (function, line 55) `PyObject* DialogClass_addCalendar( PPyDialogClass self, PyObject *args );`
  - `DialogClass_replaceLabel` (function, line 56) `PyObject* DialogClass_replaceLabel( PPyDialogClass self, PyObject *args );`
  - `DialogClass_addImage` (function, line 57) `PyObject* DialogClass_addImage( PPyDialogClass self, PyObject *args );`
  - `DialogClass_addDial` (function, line 58) `PyObject* DialogClass_addDial( PPyDialogClass self, PyObject *args );`
  - `DialogClass_addSlider` (function, line 59) `PyObject* DialogClass_addSlider( PPyDialogClass self, PyObject *args );`
  - `PyDialogClass_Type` (variable, line 39) `extern PyTypeObject PyDialogClass_Type;`
  - `HAVOC_PYDIALOGCLASS_H` (macro, line 2) `#define HAVOC_PYDIALOGCLASS_H`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyDialogClass.cc`

## client/include/Havoc/PythonApi/UI/PyLoggerClass.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `LoggerClass_dealloc` (function, line 32) `void LoggerClass_dealloc( PPyLoggerClass self );`
  - `LoggerClass_new` (function, line 33) `PyObject* LoggerClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
  - `LoggerClass_init` (function, line 34) `int LoggerClass_init( PPyLoggerClass self, PyObject *args, PyObject *kwds );`
  - `LoggerClass_setBottomTab` (function, line 38) `PyObject* LoggerClass_setBottomTab( PPyLoggerClass self, PyObject *args );`
  - `LoggerClass_setSmallTab` (function, line 39) `PyObject* LoggerClass_setSmallTab( PPyLoggerClass self, PyObject *args );`
  - `LoggerClass_addText` (function, line 40) `PyObject* LoggerClass_addText( PPyLoggerClass self, PyObject *args );`
  - `LoggerClass_clear` (function, line 41) `PyObject* LoggerClass_clear( PPyLoggerClass self, PyObject *args );`
  - `PyLoggerClass_Type` (variable, line 30) `extern PyTypeObject PyLoggerClass_Type;`
  - `HAVOC_PYLOGGERCLASS_H` (macro, line 2) `#define HAVOC_PYLOGGERCLASS_H`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyLoggerClass.cc`

## client/include/Havoc/PythonApi/UI/PyTreeClass.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `TreeClass_dealloc` (function, line 48) `void TreeClass_dealloc( PPyTreeClass self );`
  - `TreeClass_new` (function, line 49) `PyObject* TreeClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
  - `TreeClass_init` (function, line 50) `int TreeClass_init( PPyTreeClass self, PyObject *args, PyObject *kwds );`
  - `TreeClass_setBottomTab` (function, line 54) `PyObject* TreeClass_setBottomTab( PPyTreeClass self, PyObject *args );`
  - `TreeClass_setSmallTab` (function, line 55) `PyObject* TreeClass_setSmallTab( PPyTreeClass self, PyObject *args );`
  - `TreeClass_addRow` (function, line 56) `PyObject* TreeClass_addRow( PPyTreeClass self, PyObject *args );`
  - `TreeClass_setItem` (function, line 57) `PyObject* TreeClass_setItem( PPyTreeClass self, PyObject *args );`
  - `TreeClass_setPanel` (function, line 58) `PyObject* TreeClass_setPanel( PPyTreeClass self, PyObject *args );`
  - `PyTreeClass_Type` (variable, line 46) `extern PyTypeObject PyTreeClass_Type;`
  - `HAVOC_PYTREECLASS_H` (macro, line 2) `#define HAVOC_PYTREECLASS_H`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyTreeClass.cc`

## client/include/Havoc/PythonApi/UI/PyWidgetClass.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `WidgetClass_dealloc` (function, line 41) `void WidgetClass_dealloc( PPyWidgetClass self );`
  - `WidgetClass_new` (function, line 42) `PyObject* WidgetClass_new( PyTypeObject *type, PyObject *args, PyObject *kwds );`
  - `WidgetClass_init` (function, line 43) `int WidgetClass_init( PPyWidgetClass self, PyObject *args, PyObject *kwds );`
  - `WidgetClass_addLabel` (function, line 47) `PyObject* WidgetClass_addLabel( PPyWidgetClass self, PyObject *args );`
  - `WidgetClass_setBottomTab` (function, line 48) `PyObject* WidgetClass_setBottomTab( PPyWidgetClass self, PyObject *args );`
  - `WidgetClass_setSmallTab` (function, line 49) `PyObject* WidgetClass_setSmallTab( PPyWidgetClass self, PyObject *args );`
  - `WidgetClass_addButton` (function, line 50) `PyObject* WidgetClass_addButton( PPyWidgetClass self, PyObject *args );`
  - `WidgetClass_addCheckbox` (function, line 51) `PyObject* WidgetClass_addCheckbox( PPyWidgetClass self, PyObject *args );`
  - `WidgetClass_addCombobox` (function, line 52) `PyObject* WidgetClass_addCombobox( PPyWidgetClass self, PyObject *args );`
  - `WidgetClass_addLineedit` (function, line 53) `PyObject* WidgetClass_addLineedit( PPyWidgetClass self, PyObject *args );`
  - `WidgetClass_addCalendar` (function, line 54) `PyObject* WidgetClass_addCalendar( PPyWidgetClass self, PyObject *args );`
  - `WidgetClass_replaceLabel` (function, line 55) `PyObject* WidgetClass_replaceLabel( PPyWidgetClass self, PyObject *args );`
  - `WidgetClass_clear` (function, line 56) `PyObject* WidgetClass_clear( PPyWidgetClass self, PyObject *args );`
  - `WidgetClass_addImage` (function, line 57) `PyObject* WidgetClass_addImage( PPyWidgetClass self, PyObject *args );`
  - `WidgetClass_addDial` (function, line 58) `PyObject* WidgetClass_addDial( PPyWidgetClass self, PyObject *args );`
  - `WidgetClass_addSlider` (function, line 59) `PyObject* WidgetClass_addSlider( PPyWidgetClass self, PyObject *args );`
  - `PyWidgetClass_Type` (variable, line 39) `extern PyTypeObject PyWidgetClass_Type;`
  - `HAVOC_PYWIDGETCLASS_H` (macro, line 2) `#define HAVOC_PYWIDGETCLASS_H`
- Depends on: `client/include/UserInterface/HavocUI.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/PythonApi/HavocUi.cc`, `client/src/Havoc/PythonApi/UI/PyWidgetClass.cc`
