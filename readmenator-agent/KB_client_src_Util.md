# Subsystem: client_src_Util

## client/src/Util/Base.cpp
- Layer: infrastructure
- Language: cpp
- Depends on: `client/include/Util/Base.hpp`

## client/src/Util/Base64.cpp
- Layer: infrastructure
- Language: cpp
- Symbols:
  - `base64_encode` (function, line 9) `std::string HavocNamespace::Util::base64_encode(const char* buf, unsigned int bufLen)`
- Depends on: `client/include/global.hpp`

## client/src/Util/ColorText.cpp
- Layer: infrastructure
- Language: cpp
- Symbols:
  - `SetDraculaDark` (function, line 24) `void HavocNamespace::Util::ColorText::SetDraculaDark()`
  - `SetDraculaLight` (function, line 40) `void HavocNamespace::Util::ColorText::SetDraculaLight()`
  - `Color` (function, line 45) `QString HavocNamespace::Util::ColorText::Color(const QString& color, const QString &text)`
  - `Background` (function, line 50) `QString HavocNamespace::Util::ColorText::Background(const QString& text)`
  - `Foreground` (function, line 55) `QString HavocNamespace::Util::ColorText::Foreground(const QString& text)`
  - `Comment` (function, line 59) `QString HavocNamespace::Util::ColorText::Comment(const QString& text)`
  - `Cyan` (function, line 63) `QString HavocNamespace::Util::ColorText::Cyan(const QString& text)`
  - `Green` (function, line 67) `QString HavocNamespace::Util::ColorText::Green(const QString& text)`
  - `Orange` (function, line 71) `QString HavocNamespace::Util::ColorText::Orange(const QString& text)`
  - `Pink` (function, line 75) `QString HavocNamespace::Util::ColorText::Pink(const QString& text)`
  - `Purple` (function, line 79) `QString HavocNamespace::Util::ColorText::Purple(const QString& text)`
  - `Red` (function, line 83) `QString HavocNamespace::Util::ColorText::Red(const QString& text)`
  - `Yellow` (function, line 87) `QString HavocNamespace::Util::ColorText::Yellow(const QString& text)`
  - `Bold` (function, line 91) `QString HavocNamespace::Util::ColorText::Bold(const QString& text)`
  - `Underline` (function, line 95) `QString HavocNamespace::Util::ColorText::Underline(const QString &text)`
  - `UnderlineBackground` (function, line 99) `QString HavocNamespace::Util::ColorText::UnderlineBackground(const QString &text)`
  - `UnderlineForeground` (function, line 103) `QString HavocNamespace::Util::ColorText::UnderlineForeground(const QString &text)`
  - `UnderlineComment` (function, line 107) `QString HavocNamespace::Util::ColorText::UnderlineComment(const QString &text)`
  - `UnderlineCyan` (function, line 111) `QString HavocNamespace::Util::ColorText::UnderlineCyan(const QString &text)`
  - `UnderlineGreen` (function, line 115) `QString HavocNamespace::Util::ColorText::UnderlineGreen(const QString &text)`
  - `UnderlineOrange` (function, line 119) `QString HavocNamespace::Util::ColorText::UnderlineOrange(const QString &text)`
  - `UnderlinePink` (function, line 123) `QString HavocNamespace::Util::ColorText::UnderlinePink(const QString &text)`
  - `UnderlinePurple` (function, line 127) `QString HavocNamespace::Util::ColorText::UnderlinePurple(const QString &text)`
  - `UnderlineRed` (function, line 131) `QString HavocNamespace::Util::ColorText::UnderlineRed(const QString &text)`
  - `UnderlineYellow` (function, line 135) `QString HavocNamespace::Util::ColorText::UnderlineYellow(const QString &text)`
- Depends on: `client/include/Util/ColorText.h`
