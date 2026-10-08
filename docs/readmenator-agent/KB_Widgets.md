# Subsystem: Widgets

## client/include/UserInterface/Widgets/Chat.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `setupUi` (function, line 18) `void setupUi( QWidget* widget );`
  - `AppendText` (function, line 19) `void AppendText( const QString& Time, const QString& text ) const;`
  - `AddUserMessage` (function, line 21) `void AddUserMessage( const QString Time, QString User, QString text ) const;`
  - `AppendFromInput` (function, line 24) `public slots: void AppendFromInput();`
  - `HAVOC_CHATWIDGET_H` (macro, line 2) `#define HAVOC_CHATWIDGET_H`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/Chat.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/DemonInteracted.h
- Layer: presentation
- Language: h
- Symbols:
  - `DemonInteracted` (class, line 9)
  - `DemonInput` (class, line 26)
  - `AddCommand` (function, line 33) `void AddCommand( const QString& Command );`
  - `handleKeyPress` (function, line 39) `private: bool handleKeyPress(QKeyEvent* eventKey);`
  - `handleTabKey` (function, line 40) `void handleTabKey();`
  - `handleUpKey` (function, line 41) `void handleUpKey();`
  - `handleDownKey` (function, line 42) `void handleDownKey();`
  - `setupUi` (function, line 46) `void setupUi( QWidget* Form );`
  - `AppendText` (function, line 47) `void AppendText( const QString& text );`
  - `AppendRaw` (function, line 48) `void AppendRaw( const QString& text = "" );`
  - `AppendNoNL` (function, line 49) `void AppendNoNL( const QString& test );`
  - `AutoCompleteAdd` (function, line 54) `void AutoCompleteAdd( QString text );`
  - `AutoCompleteAddList` (function, line 55) `void AutoCompleteAddList( QStringList list );`
  - `AutoCompleteClear` (function, line 56) `void AutoCompleteClear();`
  - `AppendFromInput` (function, line 59) `private slots: void AppendFromInput();`
  - `HAVOC_DEMONINTERACTED_H` (macro, line 2) `#define HAVOC_DEMONINTERACTED_H`
- Depends on: `client/include/Havoc/DemonCmdDispatch.h`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Demon/CommandSend.cc`, `client/src/Havoc/Demon/ConsoleInput.cc`, `client/src/Havoc/Packager.cc`, `client/src/Havoc/PythonApi/Havoc.cc`, `client/src/Havoc/PythonApi/PyAgentClass.cc`, `client/src/Havoc/PythonApi/PyDemonClass.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/DemonInteracted.cc`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/FileBrowser.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `_FileDirData` (struct, line 33)
  - `FileData` (struct, line 23)
  - `Path` (type_alias, line 32) `typedef struct _FileDirData { QString Path;`
  - `FileBrowserTableItem` (class, line 40)
  - `FileBrowserTreeItem` (class, line 46)
  - `FileBrowser` (class, line 53)
  - `setupUi` (function, line 82) `void setupUi( QWidget* FileBrowser );`
  - `retranslateUi` (function, line 83) `void retranslateUi( );`
  - `AddData` (function, line 85) `void AddData( QJsonDocument JsonData );`
  - `TreeAddData` (function, line 88) `private: void TreeAddData( FileData Data );`
  - `TreeUpdate` (function, line 89) `void TreeUpdate( );`
  - `TreeClear` (function, line 90) `void TreeClear( );`
  - `TreeAddDisk` (function, line 93) `void TreeAddDisk( QString Disk );`
  - `TreeAddChildToParent` (function, line 94) `void TreeAddChildToParent( QString ParentPath, FileBrowserTreeItem* DataItem );`
  - `TableAddData` (function, line 97) `void TableAddData( FileData Data );`
  - `TableClear` (function, line 98) `void TableClear();`
  - `ChangePathAndSendRequest` (function, line 100) `void ChangePathAndSendRequest( QString Path );`
  - `onTableMenuMkdir` (function, line 103) `private slots: void onTableMenuMkdir();`
  - `onTableMenuReload` (function, line 104) `void onTableMenuReload();`
  - `onTableMenuRemove` (function, line 105) `void onTableMenuRemove();`
  - `onTableDoubleClick` (function, line 107) `void onTableDoubleClick( int row, int column );`
  - `onTableContextMenu` (function, line 108) `void onTableContextMenu( const QPoint &pos );`
  - `onTreeMenuListDrives` (function, line 110) `void onTreeMenuListDrives();`
  - `onTreeMenuMkdir` (function, line 111) `void onTreeMenuMkdir();`
  - `onTreeMenuReload` (function, line 112) `void onTreeMenuReload();`
  - `onTreeMenuRemove` (function, line 113) `void onTreeMenuRemove();`
  - `onTreeDoubleClick` (function, line 115) `void onTreeDoubleClick();`
  - `onTreeContextMenu` (function, line 116) `void onTreeContextMenu( const QPoint &pos );`
  - `onTableMenuDownload` (function, line 118) `void onTableMenuDownload();`
  - `onButtonUp` (function, line 119) `void onButtonUp();`
  - `onInputPath` (function, line 120) `void onInputPath();`
  - `HAVOC_FILEBROWSER_HPP` (macro, line 2) `#define HAVOC_FILEBROWSER_HPP`
- Imported by: `client/include/global.hpp`, `client/src/UserInterface/Widgets/FileBrowser.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/ListenerTable.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `setupUi` (function, line 25) `void setupUi( QWidget* widget );`
  - `ButtonsInit` (function, line 26) `void ButtonsInit();`
  - `setDBManager` (function, line 27) `void setDBManager( HavocSpace::DBManager* dbManager );`
  - `ListenerAdd` (function, line 31) `void ListenerAdd( Util::ListenerItem item ) const;`
  - `ListenerEdit` (function, line 32) `void ListenerEdit( Util::ListenerItem item ) const;`
  - `ListenerRemove` (function, line 33) `void ListenerRemove( QString ListenerName ) const;`
  - `ListenerError` (function, line 34) `void ListenerError( QString ListenerName, QString Error ) const;`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/ListenersTable.cc`

## client/include/UserInterface/Widgets/LootWidget.h
- Layer: presentation
- Language: h
- Symbols:
  - `File` (struct, line 47)
  - `ImageLabel` (class, line 15)
  - `LootWidget` (class, line 39)
  - `pixmap` (function, line 23) `const QPixmap* pixmap() const;`
  - `setPixmap` (function, line 26) `public slots: void setPixmap(const QPixmap&);`
  - `resizeEvent` (function, line 29) `protected: void resizeEvent(QResizeEvent *);`
  - `keyReleaseEvent` (function, line 30) `void keyReleaseEvent( QKeyEvent* event );`
  - `wheelEvent` (function, line 32) `void wheelEvent(QWheelEvent *ev);`
  - `resizeImage` (function, line 35) `public slots: void resizeImage();`
  - `Reload` (function, line 94) `void Reload();`
  - `AddSessionSection` (function, line 96) `void AddSessionSection( const QString& DemonID );`
  - `AddScreenshot` (function, line 97) `void AddScreenshot( const QString& DemonID, const QString& Name, const QString& Date, const QByteArray& Data );`
  - `AddDownload` (function, line 98) `void AddDownload( const QString &DemonID, const QString &Name, const QString& Size, const QString &Date, const...`
  - `AddText` (function, line 99) `void AddText( const QString& DemonID, const QString& Name, const QByteArray& Data );`
  - `ScreenshotTableAdd` (function, line 101) `void ScreenshotTableAdd( const QString& Name, const QString& Date );`
  - `DownloadTableAdd` (function, line 102) `void DownloadTableAdd( const QString& Name, const QString& Size, const QString& Date );`
  - `onAgentChange` (function, line 105) `private Q_SLOTS: void onAgentChange( const QString& text );`
  - `onShowChange` (function, line 106) `void onShowChange( const QString& text );`
  - `onScreenshotTableClick` (function, line 107) `void onScreenshotTableClick( const QModelIndex &index );`
  - `onDownloadTableClick` (function, line 108) `void onDownloadTableClick( const QModelIndex &index );`
  - `onScreenshotTableCtx` (function, line 109) `void onScreenshotTableCtx( const QPoint &pos );`
  - `HAVOC_LOOTWIDGET_H` (macro, line 2) `#define HAVOC_LOOTWIDGET_H`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/LootWidget.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/ProcessList.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `setupUi` (function, line 43) `void setupUi(QWidget* Widget);`
  - `UpdateProcessListJson` (function, line 44) `void UpdateProcessListJson(QJsonDocument ProcessListData);`
  - `NewTableProcess` (function, line 45) `void NewTableProcess(std::map<QString, QString> ProcessInfo);`
  - `NewTreeProcess` (function, line 46) `void NewTreeProcess(std::map<QString, QString> ProcessInfo);`
  - `onButton_Refresh` (function, line 49) `private slots: void onButton_Refresh() const;`
  - `onTableChange` (function, line 51) `void onTableChange();`
  - `onTreeChange` (function, line 52) `void onTreeChange();`
  - `handleTableListMenuContext` (function, line 54) `void handleTableListMenuContext(const QPoint &pos);`
  - `handleTreeListMenuContext` (function, line 55) `void handleTreeListMenuContext(const QPoint &pos);`
  - `onActionCopyPID` (function, line 57) `void onActionCopyPID();`
  - `onActionSetParentProcess` (function, line 58) `void onActionSetParentProcess();`
  - `HAVOC_PROCESSLIST_HPP` (macro, line 2) `#define HAVOC_PROCESSLIST_HPP`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/UserInterface/Widgets/ProcessList.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/PythonScript.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `setupUi` (function, line 24) `void setupUi(QWidget *WindowWidget);`
  - `RunCode` (function, line 25) `void RunCode(QString code);`
  - `AppendOutput` (function, line 26) `void AppendOutput( QString output );`
  - `AppendFromInput` (function, line 29) `private slots: void AppendFromInput();`
  - `HAVOC_PYTHONSCRIPTWIDGET_HPP` (macro, line 3) `#define HAVOC_PYTHONSCRIPTWIDGET_HPP`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/PythonScript.cc`

## client/include/UserInterface/Widgets/ScriptManager.h
- Layer: presentation
- Language: h
- Symbols:
  - `SetupUi` (function, line 20) `void SetupUi( QWidget *Form );`
  - `RetranslateUi` (function, line 21) `void RetranslateUi( void );`
  - `AddScript` (function, line 23) `static bool AddScript( QString Path );`
  - `AddScriptTable` (function, line 24) `void AddScriptTable( QString Path );`
  - `b_LoadScript` (function, line 27) `private slots: void b_LoadScript();`
  - `menu_ScriptMenu` (function, line 28) `void menu_ScriptMenu( const QPoint &pos ) const;`
  - `ReloadScript` (function, line 30) `void ReloadScript() const;`
  - `RemoveScript` (function, line 31) `void RemoveScript() const;`
  - `SCRIPTMANAGERVVJSUY_H` (macro, line 2) `#define SCRIPTMANAGERVVJSUY_H`
- Depends on: `client/include/global.hpp`
- Imported by: `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/Store.cc`

## client/include/UserInterface/Widgets/SessionGraph.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `Member` (struct, line 80)
  - `NodeItemType` (enum, line 14)
  - `NodeItemType` (class, line 14)
  - `Node` (class, line 20)
  - `GraphWidget` (class, line 77)
  - `Edge` (class, line 138)
  - `type` (function, line 52) `int type() const override`
  - `type` (function, line 153) `int type() const override`
  - `appendChild` (function, line 45) `void appendChild( Node* child );`
  - `removeChild` (function, line 46) `void removeChild( Node* child );`
  - `addEdge` (function, line 48) `void addEdge( Edge* edge );`
  - `edges` (function, line 49) `QVector<Edge*> edges() const;`
  - `calculateForces` (function, line 54) `void calculateForces();`
  - `advancePosition` (function, line 55) `bool advancePosition();`
  - `itemMoved` (function, line 93) `void itemMoved();`
  - `GraphNodeAdd` (function, line 95) `Node* GraphNodeAdd( HavocNamespace::Util::SessionItem Session );`
  - `GraphNodeRemove` (function, line 96) `void GraphNodeRemove( HavocNamespace::Util::SessionItem Session );`
  - `GraphNodeGet` (function, line 97) `Node* GraphNodeGet( QString AgentID );`
  - `GraphPivotNodeAdd` (function, line 99) `void GraphPivotNodeAdd( QString AgentID, HavocNamespace::Util::SessionItem Session );`
  - `GraphPivotNodeDisconnect` (function, line 100) `void GraphPivotNodeDisconnect( QString AgentID );`
  - `GraphPivotNodeReconnect` (function, line 101) `void GraphPivotNodeReconnect( QString ParentAgentID, QString ChildAgentID );`
  - `shuffle` (function, line 104) `public slots: void shuffle();`
  - `zoomIn` (function, line 105) `void zoomIn();`
  - `zoomOut` (function, line 106) `void zoomOut();`
  - `scaleView` (function, line 118) `void scaleView( qreal scaleFactor );`
  - `initNode` (function, line 126) `void initNode(Node* v);`
  - `layout` (function, line 127) `void layout(Node* T);`
  - `firstWalk` (function, line 128) `void firstWalk(Node* v);`
  - `apportion` (function, line 129) `void apportion(Node* v, Node*& defaultAncestor);`
  - `moveSubtree` (function, line 130) `void moveSubtree(Node* wm, Node* wp, double shift);`
  - `nextLeft` (function, line 131) `Node* nextLeft(Node* v);`
  - `nextRight` (function, line 132) `Node* nextRight(Node* v);`
  - `ancestor` (function, line 133) `Node* ancestor(Node* vim, Node* v, Node*& defaultAncestor);`
  - `executeShifts` (function, line 134) `void executeShifts(Node* v);`
  - `secondWalk` (function, line 135) `void secondWalk(Node* v, double m, double depth);`
  - `sourceNode` (function, line 146) `Node* sourceNode() const;`
  - `destNode` (function, line 147) `Node* destNode() const;`
  - `adjust` (function, line 149) `void adjust();`
  - `Color` (function, line 150) `void Color( QColor color );`
  - `HAVOC_SESSIONGRAPH_HPP` (macro, line 2) `#define HAVOC_SESSIONGRAPH_HPP`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/SessionTable.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `setupUi` (function, line 28) `void setupUi( QWidget* widget, QString TeamserverName );`
  - `NewSessionItem` (function, line 29) `void NewSessionItem( Util::SessionItem item ) const;`
  - `ChangeSessionValue` (function, line 30) `void ChangeSessionValue( QString DemonID, int key, QString value );`
  - `updateRow` (function, line 31) `void updateRow();`
  - `HAVOC_SESSIONTABLE_HPP` (macro, line 2) `#define HAVOC_SESSIONTABLE_HPP`
- Depends on: `client/include/global.hpp`
- Imported by: `client/include/UserInterface/HavocUI.hpp`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`

## client/include/UserInterface/Widgets/Store.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `Store` (class, line 35)
  - `setupUi` (function, line 62) `void setupUi( QWidget* Store );`
  - `displayData` (function, line 63) `void displayData( int position );`
  - `installScript` (function, line 64) `void installScript( int position );`
  - `AddScript` (function, line 65) `bool AddScript( QString Path );`
  - `retranslateUi` (function, line 66) `void retranslateUi( );`
  - `HAVOC_STORE_HPP` (macro, line 2) `#define HAVOC_STORE_HPP`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/Store.cc`

## client/include/UserInterface/Widgets/Teamserver.hpp
- Layer: presentation
- Language: hpp
- Symbols:
  - `Teamserver` (class, line 16)
  - `setupUi` (function, line 23) `void setupUi( QWidget* Teamserver );`
  - `retranslateUi` (function, line 24) `void retranslateUi( );`
  - `AddLoggerText` (function, line 26) `void AddLoggerText( const QString& Text ) const;`
  - `HAVOC_TEAMSERVER_HPP` (macro, line 2) `#define HAVOC_TEAMSERVER_HPP`
- Imported by: `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/src/UserInterface/Widgets/Teamserver.cc`

## client/include/UserInterface/Widgets/TeamserverTabSession.h
- Layer: presentation
- Language: h
- Symbols:
  - `SmallAppWidgets_t` (struct, line 19)
  - `setupUi` (function, line 52) `void setupUi( QWidget* Page, QString TeamserverName );`
  - `NewBottomTab` (function, line 53) `void NewBottomTab( QWidget* TabWidget, const std::string& TitleName, QString IconPath = "" ) const;`
  - `NewWidgetTab` (function, line 54) `void NewWidgetTab( QWidget* TabWidget, const std::string& TitleName ) const;`
  - `handleDemonContextMenu` (function, line 57) `protected slots: void handleDemonContextMenu( const QPoint& pos );`
  - `removeTabSmall` (function, line 58) `void removeTabSmall( int ) const;`
  - `HAVOC_TEAMSERVERTABSESSION_H` (macro, line 2) `#define HAVOC_TEAMSERVERTABSESSION_H`
- Depends on: `client/include/UserInterface/Dialogs/Payload.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/Teamserver.hpp`, `client/include/global.hpp`
- Imported by: `client/src/Havoc/Demon/CommandOutput.cc`, `client/src/Havoc/Packager.cc`, `client/src/UserInterface/HavocUi.cc`, `client/src/UserInterface/Widgets/ListenersTable.cc`, `client/src/UserInterface/Widgets/ScriptManager.cc`, `client/src/UserInterface/Widgets/SessionGraph.cc`, `client/src/UserInterface/Widgets/SessionTable.cc`, `client/src/UserInterface/Widgets/Store.cc`, `client/src/UserInterface/Widgets/TeamserverTabSession.cc`
