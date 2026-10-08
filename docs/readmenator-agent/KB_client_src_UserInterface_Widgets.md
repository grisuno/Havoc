# Subsystem: client_src_UserInterface_Widgets

## client/src/UserInterface/Widgets/Chat.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `setupUi` (function, line 11) `void HavocNamespace::UserInterface::Widgets::Chat::setupUi( QWidget *Form )`
  - `AppendText` (function, line 63) `void HavocNamespace::UserInterface::Widgets::Chat::AppendText(const QString& Time, const QString&...`
  - `AddUserMessage` (function, line 70) `void HavocNamespace::UserInterface::Widgets::Chat::AddUserMessage(const QString Time, QString Use...`
  - `AppendFromInput` (function, line 78) `void HavocNamespace::UserInterface::Widgets::Chat::AppendFromInput()`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/DemonInteracted.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `DemonInput` (function, line 16) `DemonInteracted::DemonInput::DemonInput( QWidget* parent ) : QLineEdit( parent )`
  - `handleKeyPress` (function, line 21) `bool DemonInteracted::DemonInput::handleKeyPress( QKeyEvent* eventKey )`
  - `handleTabKey` (function, line 39) `void DemonInteracted::DemonInput::handleTabKey()`
  - `handleUpKey` (function, line 47) `void DemonInteracted::DemonInput::handleUpKey()`
  - `handleDownKey` (function, line 67) `void DemonInteracted::DemonInput::handleDownKey()`
  - `event` (function, line 78) `bool DemonInteracted::DemonInput::event( QEvent* e )`
  - `AddCommand` (function, line 90) `void DemonInteracted::DemonInput::AddCommand( const QString &Command )`
  - `setupUi` (function, line 95) `void DemonInteracted::setupUi( QWidget *Form )`
  - `AppendFromInput` (function, line 209) `void DemonInteracted::AppendFromInput()`
  - `AppendText` (function, line 214) `void DemonInteracted::AppendText( const QString& text )`
  - `TaskInfo` (function, line 281) `QString DemonInteracted::TaskInfo( bool Show, QString TaskID, const QString &text ) const`
  - `TaskError` (function, line 296) `QString DemonInteracted::TaskError( const QString &text ) const`
  - `AppendRaw` (function, line 303) `void UserInterface::Widgets::DemonInteracted::AppendRaw(const QString& text)`
  - `AppendNoNL` (function, line 308) `void DemonInteracted::AppendNoNL( const QString &text )`
  - `AutoCompleteAdd` (function, line 317) `void DemonInteracted::AutoCompleteAdd( QString text )`
  - `AutoCompleteClear` (function, line 326) `void DemonInteracted::AutoCompleteClear()`
  - `AutoCompleteAddList` (function, line 336) `void DemonInteracted::AutoCompleteAddList( QStringList list )`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/FileBrowser.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `setupUi` (function, line 40) `void FileBrowser::setupUi( QWidget* FileBrowser )`
  - `retranslateUi` (function, line 148) `void FileBrowser::retranslateUi()`
  - `AddData` (function, line 159) `void FileBrowser::AddData( QJsonDocument JsonData )`
  - `TreeAddData` (function, line 234) `void FileBrowser::TreeAddData( FileData Data )`
  - `TableAddData` (function, line 239) `void FileBrowser::TableAddData( FileData Data )`
  - `onTableDoubleClick` (function, line 276) `void FileBrowser::onTableDoubleClick( int row, int column )`
  - `onTreeDoubleClick` (function, line 292) `void FileBrowser::onTreeDoubleClick()`
  - `ChangePathAndSendRequest` (function, line 297) `void FileBrowser::ChangePathAndSendRequest( QString Path )`
  - `TableClear` (function, line 313) `void FileBrowser::TableClear()`
  - `onButtonUp` (function, line 320) `void FileBrowser::onButtonUp()`
  - `onTableMenuDownload` (function, line 327) `void FileBrowser::onTableMenuDownload()`
  - `onTableContextMenu` (function, line 363) `void FileBrowser::onTableContextMenu( const QPoint &pos )`
  - `onTreeContextMenu` (function, line 371) `void FileBrowser::onTreeContextMenu( const QPoint &pos )`
  - `onTableMenuMkdir` (function, line 379) `void FileBrowser::onTableMenuMkdir()`
  - `onTableMenuReload` (function, line 384) `void FileBrowser::onTableMenuReload()`
  - `onTableMenuRemove` (function, line 405) `void FileBrowser::onTableMenuRemove()`
  - `onTreeMenuListDrives` (function, line 410) `void FileBrowser::onTreeMenuListDrives()`
  - `onTreeMenuMkdir` (function, line 415) `void FileBrowser::onTreeMenuMkdir()`
  - `onTreeMenuReload` (function, line 420) `void FileBrowser::onTreeMenuReload()`
  - `onTreeMenuRemove` (function, line 425) `void FileBrowser::onTreeMenuRemove()`
  - `onInputPath` (function, line 430) `void FileBrowser::onInputPath()`
  - `TreeUpdate` (function, line 438) `void FileBrowser::TreeUpdate()`
  - `TreeClear` (function, line 500) `void FileBrowser::TreeClear( )`
  - `TreeAddDisk` (function, line 523) `void FileBrowser::TreeAddDisk( QString Disk )`
  - `TreeAddChildToParent` (function, line 537) `void FileBrowser::TreeAddChildToParent( QString ParentPath, FileBrowserTreeItem* DataItem )`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/Util/Base.hpp`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/ListenersTable.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `setupUi` (function, line 15) `void HavocNamespace::UserInterface::Widgets::ListenersTable::setupUi( QWidget* Form )`
  - `ButtonsInit` (function, line 85) `void HavocNamespace::UserInterface::Widgets::ListenersTable::ButtonsInit()`
  - `connect` (function, line 87) `QObject::connect( buttonAdd, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 108) `QObject::connect( buttonEdit, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 152) `QObject::connect( buttonRemove,  &QPushButton::clicked, this, [&]()`
  - `ListenerAdd` (function, line 178) `void HavocNamespace::UserInterface::Widgets::ListenersTable::ListenerAdd( Util::ListenerItem item...`
  - `setDBManager` (function, line 284) `void HavocNamespace::UserInterface::Widgets::ListenersTable::setDBManager( HavocSpace::DBManager*...`
  - `CreateNewPackage` (function, line 289) `Util::Packager::Package UserInterface::Widgets::ListenersTable::CreateNewPackage( int EventID, ma...`
  - `ListenerEdit` (function, line 312) `void UserInterface::Widgets::ListenersTable::ListenerEdit( Util::ListenerItem item ) const`
  - `ListenerRemove` (function, line 323) `void UserInterface::Widgets::ListenersTable::ListenerRemove( QString ListenerName ) const`
  - `ListenerError` (function, line 357) `void UserInterface::Widgets::ListenersTable::ListenerError( QString ListenerName, QString Error )...`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Dialogs/Listener.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/ListenerTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/LootWidget.cc
- Doc: imagelabel.cpp
- Layer: presentation
- Language: cc
- Symbols:
  - `ImageLabel` (function, line 17) `ImageLabel::ImageLabel( QWidget* parent ) : QWidget( parent )`
  - `resizeEvent` (function, line 33) `void ImageLabel::resizeEvent( QResizeEvent* event )`
  - `pixmap` (function, line 39) `const QPixmap* ImageLabel::pixmap() const`
  - `event` (function, line 44) `bool ImageLabel::event( QEvent* e )`
  - `keyReleaseEvent` (function, line 60) `void ImageLabel::keyReleaseEvent( QKeyEvent* event )`
  - `wheelEvent` (function, line 71) `void ImageLabel::wheelEvent( QWheelEvent* ev )`
  - `setPixmap` (function, line 78) `void ImageLabel::setPixmap( const QPixmap &pixmap )`
  - `resizeImage` (function, line 85) `void ImageLabel::resizeImage()`
  - `LootWidget` (function, line 92) `LootWidget::LootWidget()`
  - `AddScreenshot` (function, line 253) `void LootWidget::AddScreenshot( const QString& DemonID, const QString& Name, const QString& Date,...`
  - `AddDownload` (function, line 273) `void LootWidget::AddDownload( const QString &DemonID, const QString &Name, const QString& Size, c...`
  - `Reload` (function, line 292) `void LootWidget::Reload()`
  - `onScreenshotTableClick` (function, line 305) `void LootWidget::onScreenshotTableClick( const QModelIndex &index )`
  - `onDownloadTableClick` (function, line 329) `void LootWidget::onDownloadTableClick( const QModelIndex &index )`
  - `onAgentChange` (function, line 334) `void LootWidget::onAgentChange( const QString& text )`
  - `AddSessionSection` (function, line 364) `void LootWidget::AddSessionSection( const QString& AgentID )`
  - `onShowChange` (function, line 377) `void LootWidget::onShowChange( const QString& text )`
  - `ScreenshotTableAdd` (function, line 389) `void LootWidget::ScreenshotTableAdd( const QString &Name, const QString &Date )`
  - `DownloadTableAdd` (function, line 414) `void LootWidget::DownloadTableAdd( const QString &Name, const QString &Size, const QString &Date )`
  - `onScreenshotTableCtx` (function, line 436) `void LootWidget::onScreenshotTableCtx( const QPoint &pos )`
- Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/ProcessList.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `setupUi` (function, line 5) `void HavocNamespace::UserInterface::Widgets::ProcessList::setupUi(QWidget *Widget)`
  - `UpdateProcessListJson` (function, line 201) `void HavocNamespace::UserInterface::Widgets::ProcessList::UpdateProcessListJson( QJsonDocument Pr...`
  - `NewTableProcess` (function, line 231) `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTableProcess(std::map<QString, QStri...`
  - `NewTreeProcess` (function, line 279) `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTreeProcess( std::map<QString,QStrin...`
  - `onButton_Refresh` (function, line 299) `void HavocNamespace::UserInterface::Widgets::ProcessList::onButton_Refresh() const`
  - `onTableChange` (function, line 314) `void HavocNamespace::UserInterface::Widgets::ProcessList::onTableChange()`
  - `onTreeChange` (function, line 330) `void HavocNamespace::UserInterface::Widgets::ProcessList::onTreeChange()`
  - `handleTableListMenuContext` (function, line 343) `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTableListMenuContext( const QPoin...`
  - `handleTreeListMenuContext` (function, line 351) `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTreeListMenuContext( const QPoint...`
  - `onActionCopyPID` (function, line 359) `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionCopyPID()`
  - `onActionSetParentProcess` (function, line 367) `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionSetParentProcess()`
- Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`

## client/src/UserInterface/Widgets/PythonScript.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `setupUi` (function, line 9) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::setupUi(QWidget *WindowWidget)`
  - `RunCode` (function, line 48) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::RunCode( QString code )`
  - `AppendFromInput` (function, line 64) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendFromInput()`
  - `AppendOutput` (function, line 76) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendOutput( QString output )`
- Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/Util/ColorText.h`

## client/src/UserInterface/Widgets/ScriptManager.cc
- Doc: RemoveScript: TODO: clear python interpreter and reload every script except the one that got removed
- Layer: presentation
- Language: cc
- Symbols:
  - `SetupUi` (function, line 13) `void ScriptManager::SetupUi( QWidget *Form )`
  - `RetranslateUi` (function, line 104) `void ScriptManager::RetranslateUi( )`
  - `AddScript` (function, line 111) `bool ScriptManager::AddScript( QString Path )`
  - `AddScriptTable` (function, line 140) `void ScriptManager::AddScriptTable( QString Path )`
  - `b_LoadScript` (function, line 155) `void ScriptManager::b_LoadScript()`
  - `menu_ScriptMenu` (function, line 186) `void ScriptManager::menu_ScriptMenu( const QPoint &pos ) const`
  - `ReloadScript` (function, line 195) `void ScriptManager::ReloadScript() const`
  - `RemoveScript` (function, line 204) `void ScriptManager::RemoveScript() const`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`

## client/src/UserInterface/Widgets/SessionGraph.cc
- Doc: initNode: Initialize node properties for layout
- Layer: presentation
- Language: cc
- Symbols:
  - `GraphWidget` (function, line 28) `GraphWidget::GraphWidget( QWidget* parent ) : QGraphicsView( parent )`
  - `GraphNodeAdd` (function, line 54) `Node* GraphWidget::GraphNodeAdd( SessionItem Session )`
  - `GraphNodeRemove` (function, line 84) `void GraphWidget::GraphNodeRemove( SessionItem Session )`
  - `GraphPivotNodeAdd` (function, line 105) `void GraphWidget::GraphPivotNodeAdd( QString AgentID, SessionItem Session )`
  - `GraphPivotNodeDisconnect` (function, line 147) `void GraphWidget::GraphPivotNodeDisconnect( QString AgentID )`
  - `GraphPivotNodeReconnect` (function, line 170) `void GraphWidget::GraphPivotNodeReconnect( QString ParentAgentID, QString ChildAgentID )`
  - `itemMoved` (function, line 198) `void GraphWidget::itemMoved()`
  - `keyPressEvent` (function, line 204) `void GraphWidget::keyPressEvent( QKeyEvent* event )`
  - `timerEvent` (function, line 221) `void GraphWidget::timerEvent( QTimerEvent* event )`
  - `resizeEvent` (function, line 251) `void GraphWidget::resizeEvent( QResizeEvent* event )`
  - `wheelEvent` (function, line 258) `void GraphWidget::wheelEvent( QWheelEvent* event )`
  - `drawBackground` (function, line 263) `void GraphWidget::drawBackground( QPainter* painter, const QRectF& rect )`
  - `scaleView` (function, line 279) `void GraphWidget::scaleView( qreal scaleFactor )`
  - `shuffle` (function, line 288) `void GraphWidget::shuffle()`
  - `zoomIn` (function, line 299) `void GraphWidget::zoomIn()`
  - `zoomOut` (function, line 304) `void GraphWidget::zoomOut()`
  - `GraphNodeGet` (function, line 309) `Node *GraphWidget::GraphNodeGet( QString AgentID )`
  - `initNode` (function, line 329) `void GraphWidget::initNode(Node* v)`
  - `layout` (function, line 340) `void GraphWidget::layout(Node* T)`
  - `firstWalk` (function, line 350) `void GraphWidget::firstWalk(Node* v)`
  - `apportion` (function, line 383) `void GraphWidget::apportion(Node* v, Node*& defaultAncestor)`
  - `moveSubtree` (function, line 434) `void GraphWidget::moveSubtree(Node* wm, Node* wp, double shift)`
  - `nextLeft` (function, line 453) `Node* GraphWidget::nextLeft(Node* v)`
  - `nextRight` (function, line 462) `Node* GraphWidget::nextRight(Node* v)`
  - `ancestor` (function, line 471) `Node* GraphWidget::ancestor(Node* vim, Node* v, Node*& defaultAncestor)`
  - `executeShifts` (function, line 481) `void GraphWidget::executeShifts(Node* v)`
  - `secondWalk` (function, line 496) `void GraphWidget::secondWalk(Node* v, double m, double depth)`
  - `Edge` (function, line 508) `Edge::Edge( Node* sourceNode, Node* destNode, QColor Color )
    : source( sourceNode ), dest( de...`
  - `sourceNode` (function, line 519) `Node* Edge::sourceNode() const`
  - `destNode` (function, line 524) `Node* Edge::destNode() const`
  - `contextMenuEvent` (function, line 529) `void Node::contextMenuEvent( QGraphicsSceneContextMenuEvent* event )`
  - `adjust` (function, line 798) `void Edge::adjust()`
  - `boundingRect` (function, line 822) `QRectF Edge::boundingRect() const`
  - `paint` (function, line 835) `void Edge::paint( QPainter* painter, const QStyleOptionGraphicsItem*, QWidget* )`
  - `Color` (function, line 863) `void Edge::Color( QColor color )`
  - `Node` (function, line 871) `Node::Node( NodeItemType NodeType, QString NodeLabel, GraphWidget* graphWidget ) : graph( graphWi...`
  - `appendChild` (function, line 887) `void Node::appendChild( Node* child )`
  - `removeChild` (function, line 892) `void Node::removeChild( Node* child )`
  - `boundingRect` (function, line 899) `QRectF Node::boundingRect() const`
  - `addEdge` (function, line 904) `void Node::addEdge( Edge* edge )`
  - `edges` (function, line 910) `QVector<Edge*> Node::edges() const`
  - `calculateForces` (function, line 915) `void Node::calculateForces()`
  - `mouseMoveEvent` (function, line 936) `void Node::mouseMoveEvent( QGraphicsSceneMouseEvent* event )`
  - `advancePosition` (function, line 941) `bool Node::advancePosition()`
  - `shape` (function, line 950) `QPainterPath Node::shape() const`
  - `paint` (function, line 959) `void Node::paint( QPainter *painter, const QStyleOptionGraphicsItem* option, QWidget* )`
  - `itemChange` (function, line 1007) `QVariant Node::itemChange( GraphicsItemChange change, const QVariant& value )`
  - `mousePressEvent` (function, line 1026) `void Node::mousePressEvent( QGraphicsSceneMouseEvent* event )`
  - `mouseReleaseEvent` (function, line 1032) `void Node::mouseReleaseEvent( QGraphicsSceneMouseEvent* event )`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/SessionTable.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `setupUi` (function, line 16) `void HavocNamespace::UserInterface::Widgets::SessionTable::setupUi(QWidget *Form, QString Teamser...`
  - `NewSessionItem` (function, line 82) `void HavocNamespace::UserInterface::Widgets::SessionTable::NewSessionItem( Util::SessionItem item...`
  - `ChangeSessionValue` (function, line 211) `void UserInterface::Widgets::SessionTable::ChangeSessionValue( QString DemonID, int key, QString ...`
  - `updateRow` (function, line 220) `void HavocNamespace::UserInterface::Widgets::SessionTable::updateRow()`
- Depends on: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/Store.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `setupUi` (function, line 10) `void Store::setupUi( QWidget* Store)`
  - `connect` (function, line 76) `QObject::connect(reply, &QNetworkReply::finished, [reply, this]()`
  - `connect` (function, line 109) `QObject::connect(StoreTable, &QTableWidget::itemSelectionChanged, [this]()`
  - `connect` (function, line 116) `QObject::connect(installButton, &QPushButton::clicked, [this]()`
  - `displayData` (function, line 134) `void Store::displayData(int position)`
  - `AddScript` (function, line 147) `bool Store::AddScript( QString Path )`
  - `installScript` (function, line 176) `void Store::installScript(int position)`
  - `retranslateUi` (function, line 224) `void Store::retranslateUi()`
- Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/global.hpp`

## client/src/UserInterface/Widgets/Teamserver.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `setupUi` (function, line 5) `void Teamserver::setupUi( QWidget* Teamserver )`
  - `retranslateUi` (function, line 26) `void Teamserver::retranslateUi()`
  - `AddLoggerText` (function, line 31) `void Teamserver::AddLoggerText( const QString& Text ) const`
- Depends on: `client/include/UserInterface/Widgets/Teamserver.hpp`

## client/src/UserInterface/Widgets/TeamserverTabSession.cc
- Layer: presentation
- Language: cc
- Symbols:
  - `setupUi` (function, line 27) `void HavocNamespace::UserInterface::Widgets::TeamserverTabSession::setupUi( QWidget* Page, QStrin...`
  - `connect` (function, line 121) `connect( tabWidget->tabBar(), &QTabBar::tabCloseRequested, this, [&]( int index )`
  - `connect` (function, line 141) `connect( SessionTableWidget->SessionTableWidget, &QTableWidget::doubleClicked, this, [&]( const Q...`
  - `handleDemonContextMenu` (function, line 165) `void UserInterface::Widgets::TeamserverTabSession::handleDemonContextMenu( const QPoint &pos )`
  - `NewBottomTab` (function, line 469) `void UserInterface::Widgets::TeamserverTabSession::NewBottomTab( QWidget* TabWidget, const string...`
  - `NewWidgetTab` (function, line 488) `void UserInterface::Widgets::TeamserverTabSession::NewWidgetTab( QWidget *TabWidget, const std::s...`
  - `removeTabSmall` (function, line 509) `void UserInterface::Widgets::TeamserverTabSession::removeTabSmall( int index ) const`
- Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
