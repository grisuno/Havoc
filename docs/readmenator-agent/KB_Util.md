# Subsystem: Util

## client/include/Util/Base.hpp
- Layer: infrastructure
- Language: hpp
- Symbols:
  - `HAVOC_BASE_HPP` (macro, line 2) `#define HAVOC_BASE_HPP`
- Imported by: `client/include/global.hpp`, `client/src/Havoc/Packager.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/Util/Base.cpp`

## client/include/Util/Base64.h
- Layer: infrastructure
- Language: h
- Symbols:
  - `HAVOC_BASE64_H` (macro, line 2) `#define HAVOC_BASE64_H`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandSend.cc`

## client/include/Util/ColorText.h
- Layer: infrastructure
- Language: h
- Symbols:
  - `Colors` (struct, line 8)
  - `Hex` (struct, line 9)
  - `SetDraculaDark` (function, line 33) `static void SetDraculaDark();`
  - `SetDraculaLight` (function, line 34) `static void SetDraculaLight();`
  - `Color` (function, line 36) `static QString Color(const QString& color, const QString& text);`
  - `Background` (function, line 37) `static QString Background(const QString&);`
  - `Foreground` (function, line 38) `static QString Foreground(const QString&);`
  - `Comment` (function, line 39) `static QString Comment(const QString&);`
  - `Cyan` (function, line 40) `static QString Cyan(const QString&);`
  - `Green` (function, line 41) `static QString Green(const QString&);`
  - `Orange` (function, line 42) `static QString Orange(const QString&);`
  - `Pink` (function, line 43) `static QString Pink(const QString&);`
  - `Purple` (function, line 44) `static QString Purple(const QString&);`
  - `Red` (function, line 45) `static QString Red(const QString&);`
  - `Yellow` (function, line 46) `static QString Yellow(const QString&);`
  - `Underline` (function, line 48) `static QString Underline(const QString& text);`
  - `UnderlineBackground` (function, line 49) `static QString UnderlineBackground(const QString& text);`
  - `UnderlineForeground` (function, line 50) `static QString UnderlineForeground(const QString& text);`
  - `UnderlineComment` (function, line 51) `static QString UnderlineComment(const QString& text);`
  - `UnderlineCyan` (function, line 52) `static QString UnderlineCyan(const QString& text);`
  - `UnderlineGreen` (function, line 53) `static QString UnderlineGreen(const QString& text);`
  - `UnderlineOrange` (function, line 54) `static QString UnderlineOrange(const QString& text);`
  - `UnderlinePink` (function, line 55) `static QString UnderlinePink(const QString& text);`
  - `UnderlinePurple` (function, line 56) `static QString UnderlinePurple(const QString& text);`
  - `UnderlineRed` (function, line 57) `static QString UnderlineRed(const QString& text);`
  - `UnderlineYellow` (function, line 58) `static QString UnderlineYellow(const QString& text);`
  - `Bold` (function, line 60) `static QString Bold(const QString& text);`
  - `HAVOC_COLORTEXT_H` (macro, line 2) `#define HAVOC_COLORTEXT_H`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/SmallWidgets/EventViewer.cc`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`, `client/src/Util/ColorText.cpp`
