# Subsystem: Dialogs

## client/include/UserInterface/Dialogs/About.hpp
- Layer: infrastructure
- Language: hpp
- Symbols:
  - `About` (class, line 7)
  - `setupUi` (function, line 19) `void setupUi();`
  - `onButtonClose` (function, line 23) `public slots: void onButtonClose();`
  - `HAVOC_ABOUTDIALOG_H` (macro, line 2) `#define HAVOC_ABOUTDIALOG_H`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/About.cc`

## client/include/UserInterface/Dialogs/Connect.hpp
- Layer: infrastructure
- Language: hpp
- Symbols:
  - `setupUi` (function, line 49) `void setupUi( QDialog* Form );`
  - `passDB` (function, line 51) `void passDB( HavocNamespace::HavocSpace::DBManager* db );`
  - `onButton_Connect` (function, line 54) `private slots: void onButton_Connect();`
  - `onButton_NewProfile` (function, line 55) `void onButton_NewProfile();`
  - `itemSelected` (function, line 57) `void itemSelected();`
  - `handleContextMenu` (function, line 58) `void handleContextMenu(const QPoint &pos);`
  - `itemRemove` (function, line 60) `void itemRemove();`
  - `itemsClear` (function, line 61) `void itemsClear();`
  - `HAVOC_CONNECTDIALOG_H` (macro, line 2) `#define HAVOC_CONNECTDIALOG_H`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Connect.cc`

## client/include/UserInterface/Dialogs/Listener.hpp
- Layer: infrastructure
- Language: hpp
- Symbols:
  - `Data` (struct, line 30)
  - `ServiceListener` (struct, line 35)
  - `onButton_Save` (function, line 156) `protected slots: void onButton_Save();`
  - `onProxyEnabled` (function, line 158) `void onProxyEnabled();`
  - `HAVOC_LISTENER_HPP` (macro, line 3) `#define HAVOC_LISTENER_HPP`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Dialogs/Listener.cc`, `client/src/UserInterface/Dialogs/Payload.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`

## client/include/UserInterface/Dialogs/Payload.hpp
- Layer: infrastructure
- Language: hpp
- Symbols:
  - `Payload` (class, line 21)
  - `HAVOC_STAGELESSDIALOG_H` (macro, line 2) `#define HAVOC_STAGELESSDIALOG_H`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Dialogs/Payload.cc`
