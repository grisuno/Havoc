# Subsystem: Dialogs

## client/src/UserInterface/Dialogs/About.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `About` (function, line 4) `About::About( QDialog* dialog )`
  - `setupUi` (function, line 49) `void About::setupUi()`
  - `onButtonClose` (function, line 54) `void About::onButtonClose()`
- Depends on: `client/include/UserInterface/Dialogs/About.hpp`, `client/include/global.hpp`

## client/src/UserInterface/Dialogs/Connect.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `setupUi` (function, line 9) `void HavocNamespace::UserInterface::Dialogs::Connect::setupUi( QDialog* Form )`
  - `connect` (function, line 142) `connect( lineEdit_Name, &QLineEdit::returnPressed, this, [&]()`
  - `connect` (function, line 146) `connect( lineEdit_User, &QLineEdit::returnPressed, this, [&]()`
  - `connect` (function, line 150) `connect( lineEdit_Host, &QLineEdit::returnPressed, this, [&]()`
  - `connect` (function, line 154) `connect( lineEdit_Port, &QLineEdit::returnPressed, this, [&]()`
  - `connect` (function, line 158) `connect( lineEdit_Password, &QLineEdit::returnPressed, this, [&]()`
  - `StartDialog` (function, line 165) `Util::ConnectionInfo HavocNamespace::UserInterface::Dialogs::Connect::StartDialog( bool FromAction )`
  - `passDB` (function, line 229) `void HavocNamespace::UserInterface::Dialogs::Connect::passDB(HavocNamespace::HavocSpace::DBManage...`
  - `onButton_Connect` (function, line 234) `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_Connect()`
  - `itemSelected` (function, line 318) `void HavocNamespace::UserInterface::Dialogs::Connect::itemSelected()`
  - `onButton_NewProfile` (function, line 340) `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_NewProfile()`
  - `handleContextMenu` (function, line 356) `void HavocNamespace::UserInterface::Dialogs::Connect::handleContextMenu( const QPoint &pos )`
  - `itemRemove` (function, line 362) `void HavocNamespace::UserInterface::Dialogs::Connect::itemRemove()`
  - `itemsClear` (function, line 376) `void HavocNamespace::UserInterface::Dialogs::Connect::itemsClear()`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/Dialogs/Connect.hpp`, `client/include/global.hpp`

## client/src/UserInterface/Dialogs/Listener.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `is_number` (function, line 17) `bool is_number( const std::string& s )`
  - `NewListener` (function, line 24) `NewListener::NewListener( QDialog* Dialog )`
  - `connect` (function, line 331) `QObject::connect( ButtonClose, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 339) `QObject::connect( ButtonHostsGroupAdd, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 356) `QObject::connect( ButtonHostsGroupClear, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 366) `QObject::connect( ButtonUriGroupAdd, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 377) `QObject::connect( ButtonUriGroupClear, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 387) `QObject::connect( ButtonHeaderGroupAdd, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 398) `QObject::connect( ButtonHeaderGroupClear, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 408) `QObject::connect( ComboPayload, &QComboBox::currentTextChanged, this, [&]( const QString& text )`
  - `Start` (function, line 450) `MapStrStr NewListener::Start( Util::ListenerItem Item, bool Edit )`
  - `onButton_Save` (function, line 817) `void HavocNamespace::UserInterface::Dialogs::NewListener::onButton_Save()`
  - `onProxyEnabled` (function, line 947) `void HavocNamespace::UserInterface::Dialogs::NewListener::onProxyEnabled()`
- Depends on: `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/global.hpp`

## client/src/UserInterface/Dialogs/Payload.cc
- Layer: infrastructure
- Language: cc
- Symbols:
  - `setupUi` (function, line 17) `void Payload::setupUi( QDialog* Dialog )`
  - `connect` (function, line 124) `connect( ComboFormat, &QComboBox::currentTextChanged, this, [&]( const QString& text )`
  - `buttonGenerate` (function, line 190) `void Payload::buttonGenerate()`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
