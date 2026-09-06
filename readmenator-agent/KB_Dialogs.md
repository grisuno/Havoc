# Subsystem: Dialogs

## client/src/UserInterface/Dialogs/About.cc
- Layer: infrastructure
- Doc: include <global.hpp> include <UserInterface/Dialogs/About.hpp>
- Language: cc
- Symbols:
  - `About` (function, line 3) `About::About( QDialog* dialog )`
  - `setupUi` (function, line 48) `void About::setupUi()`
  - `onButtonClose` (function, line 53) `void About::onButtonClose()`

## client/src/UserInterface/Dialogs/Connect.cc
- Layer: infrastructure
- Doc: include <global.hpp>  include <Havoc/DBManager/DBManager.hpp> include <Havoc/Connector.hpp> include <Havoc/Havoc.hpp>  i
- Language: cc
- Symbols:
  - `setupUi` (function, line 8) `void HavocNamespace::UserInterface::Dialogs::Connect::setupUi( QDialog* Form )`
  - `connect` (function, line 141) `connect( lineEdit_Name, &QLineEdit::returnPressed, this, [&]()`
  - `connect` (function, line 145) `connect( lineEdit_User, &QLineEdit::returnPressed, this, [&]()`
  - `connect` (function, line 149) `connect( lineEdit_Host, &QLineEdit::returnPressed, this, [&]()`
  - `connect` (function, line 153) `connect( lineEdit_Port, &QLineEdit::returnPressed, this, [&]()`
  - `connect` (function, line 157) `connect( lineEdit_Password, &QLineEdit::returnPressed, this, [&]()`
  - `StartDialog` (function, line 164) `Util::ConnectionInfo HavocNamespace::UserInterface::Dialogs::Connect::StartDialog( bool FromAction )`
  - `passDB` (function, line 228) `void HavocNamespace::UserInterface::Dialogs::Connect::passDB(HavocNamespace::HavocSpace::DBManage...`
  - `onButton_Connect` (function, line 233) `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_Connect()`
  - `itemSelected` (function, line 317) `void HavocNamespace::UserInterface::Dialogs::Connect::itemSelected()`
  - `onButton_NewProfile` (function, line 339) `void HavocNamespace::UserInterface::Dialogs::Connect::onButton_NewProfile()`
  - `handleContextMenu` (function, line 355) `void HavocNamespace::UserInterface::Dialogs::Connect::handleContextMenu( const QPoint &pos )`
  - `itemRemove` (function, line 361) `void HavocNamespace::UserInterface::Dialogs::Connect::itemRemove()`
  - `itemsClear` (function, line 375) `void HavocNamespace::UserInterface::Dialogs::Connect::itemsClear()`

## client/src/UserInterface/Dialogs/Listener.cc
- Layer: infrastructure
- Doc: include <global.hpp>  include <UserInterface/Dialogs/Listener.hpp>  include <QFile> include <QApplication> include <QDia
- Language: cc
- Symbols:
  - `is_number` (function, line 16) `bool is_number( const std::string& s )`
  - `NewListener` (function, line 23) `NewListener::NewListener( QDialog* Dialog )`
  - `connect` (function, line 331) `QObject::connect( ButtonClose, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 338) `QObject::connect( ButtonHostsGroupAdd, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 355) `QObject::connect( ButtonHostsGroupClear, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 365) `QObject::connect( ButtonUriGroupAdd, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 376) `QObject::connect( ButtonUriGroupClear, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 386) `QObject::connect( ButtonHeaderGroupAdd, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 397) `QObject::connect( ButtonHeaderGroupClear, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 407) `QObject::connect( ComboPayload, &QComboBox::currentTextChanged, this, [&]( const QString& text )`
  - `Start` (function, line 449) `MapStrStr NewListener::Start( Util::ListenerItem Item, bool Edit )`
  - `onButton_Save` (function, line 816) `void HavocNamespace::UserInterface::Dialogs::NewListener::onButton_Save()`
  - `onProxyEnabled` (function, line 946) `void HavocNamespace::UserInterface::Dialogs::NewListener::onProxyEnabled()`

## client/src/UserInterface/Dialogs/Payload.cc
- Layer: infrastructure
- Doc: include <global.hpp>  include <UserInterface/Dialogs/Payload.hpp> include <UserInterface/Dialogs/Listener.hpp> include <
- Language: cc
- Symbols:
  - `setupUi` (function, line 16) `void Payload::setupUi( QDialog* Dialog )`
  - `connect` (function, line 124) `connect( ComboFormat, &QComboBox::currentTextChanged, this, [&]( const QString& text )`
  - `buttonGenerate` (function, line 189) `void Payload::buttonGenerate()`
