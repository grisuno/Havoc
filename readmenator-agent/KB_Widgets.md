# Subsystem: Widgets

## client/src/UserInterface/Widgets/Chat.cc
- Layer: presentation
- Doc: include <global.hpp> include <UserInterface/Widgets/Chat.hpp> include <Util/ColorText.h> include <QtCore> include <QComp
- Language: cc
- Symbols:
  - `setupUi` (function, line 10) `void HavocNamespace::UserInterface::Widgets::Chat::setupUi( QWidget *Form )`
  - `AppendText` (function, line 62) `void HavocNamespace::UserInterface::Widgets::Chat::AppendText(const QString& Time, const QString&...`
  - `AddUserMessage` (function, line 69) `void HavocNamespace::UserInterface::Widgets::Chat::AddUserMessage(const QString Time, QString Use...`
  - `AppendFromInput` (function, line 77) `void HavocNamespace::UserInterface::Widgets::Chat::AppendFromInput()`

## client/src/UserInterface/Widgets/DemonInteracted.cc
- Layer: presentation
- Doc: include <global.hpp> include <UserInterface/Widgets/DemonInteracted.h> include <Util/ColorText.h>  include <QDate> inclu
- Language: cc
- Symbols:
  - `DemonInput` (function, line 15) `DemonInteracted::DemonInput::DemonInput( QWidget* parent ) : QLineEdit( parent )`
  - `handleKeyPress` (function, line 20) `bool DemonInteracted::DemonInput::handleKeyPress( QKeyEvent* eventKey )`
  - `handleTabKey` (function, line 38) `void DemonInteracted::DemonInput::handleTabKey()`
  - `handleUpKey` (function, line 46) `void DemonInteracted::DemonInput::handleUpKey()`
  - `handleDownKey` (function, line 66) `void DemonInteracted::DemonInput::handleDownKey()`
  - `event` (function, line 77) `bool DemonInteracted::DemonInput::event( QEvent* e )`
  - `AddCommand` (function, line 89) `void DemonInteracted::DemonInput::AddCommand( const QString &Command )`
  - `setupUi` (function, line 94) `void DemonInteracted::setupUi( QWidget *Form )`
  - `AppendFromInput` (function, line 208) `void DemonInteracted::AppendFromInput()`
  - `AppendText` (function, line 213) `void DemonInteracted::AppendText( const QString& text )`
  - `TaskInfo` (function, line 280) `QString DemonInteracted::TaskInfo( bool Show, QString TaskID, const QString &text ) const`
  - `TaskError` (function, line 295) `QString DemonInteracted::TaskError( const QString &text ) const`
  - `AppendRaw` (function, line 302) `void UserInterface::Widgets::DemonInteracted::AppendRaw(const QString& text)`
  - `AppendNoNL` (function, line 307) `void DemonInteracted::AppendNoNL( const QString &text )`
  - `AutoCompleteAdd` (function, line 316) `void DemonInteracted::AutoCompleteAdd( QString text )`
  - `AutoCompleteClear` (function, line 325) `void DemonInteracted::AutoCompleteClear()`
  - `AutoCompleteAddList` (function, line 335) `void DemonInteracted::AutoCompleteAddList( QStringList list )`

## client/src/UserInterface/Widgets/FileBrowser.cc
- Layer: presentation
- Doc: include <global.hpp>  include <UserInterface/Widgets/FileBrowser.hpp> include <UserInterface/Widgets/DemonInteracted.h> 
- Language: cc
- Symbols:
  - `setupUi` (function, line 39) `void FileBrowser::setupUi( QWidget* FileBrowser )`
  - `retranslateUi` (function, line 147) `void FileBrowser::retranslateUi()`
  - `AddData` (function, line 158) `void FileBrowser::AddData( QJsonDocument JsonData )`
  - `TreeAddData` (function, line 233) `void FileBrowser::TreeAddData( FileData Data )`
  - `TableAddData` (function, line 238) `void FileBrowser::TableAddData( FileData Data )`
  - `onTableDoubleClick` (function, line 275) `void FileBrowser::onTableDoubleClick( int row, int column )`
  - `onTreeDoubleClick` (function, line 290) `void FileBrowser::onTreeDoubleClick()`
  - `ChangePathAndSendRequest` (function, line 296) `void FileBrowser::ChangePathAndSendRequest( QString Path )`
  - `TableClear` (function, line 312) `void FileBrowser::TableClear()`
  - `onButtonUp` (function, line 319) `void FileBrowser::onButtonUp()`
  - `onTableMenuDownload` (function, line 327) `void FileBrowser::onTableMenuDownload()`
  - `onTableContextMenu` (function, line 361) `void FileBrowser::onTableContextMenu( const QPoint &pos )`
  - `onTreeContextMenu` (function, line 370) `void FileBrowser::onTreeContextMenu( const QPoint &pos )`
  - `onTableMenuMkdir` (function, line 378) `void FileBrowser::onTableMenuMkdir()`
  - `onTableMenuReload` (function, line 383) `void FileBrowser::onTableMenuReload()`
  - `onTableMenuRemove` (function, line 404) `void FileBrowser::onTableMenuRemove()`
  - `onTreeMenuListDrives` (function, line 409) `void FileBrowser::onTreeMenuListDrives()`
  - `onTreeMenuMkdir` (function, line 414) `void FileBrowser::onTreeMenuMkdir()`
  - `onTreeMenuReload` (function, line 419) `void FileBrowser::onTreeMenuReload()`
  - `onTreeMenuRemove` (function, line 424) `void FileBrowser::onTreeMenuRemove()`
  - `onInputPath` (function, line 429) `void FileBrowser::onInputPath()`
  - `TreeUpdate` (function, line 437) `void FileBrowser::TreeUpdate()`
  - `TreeClear` (function, line 499) `void FileBrowser::TreeClear( )`
  - `TreeAddDisk` (function, line 522) `void FileBrowser::TreeAddDisk( QString Disk )`
  - `TreeAddChildToParent` (function, line 536) `void FileBrowser::TreeAddChildToParent( QString ParentPath, FileBrowserTreeItem* DataItem )`

## client/src/UserInterface/Widgets/ListenersTable.cc
- Layer: presentation
- Doc: include <global.hpp> include <QHeaderView>  include <UserInterface/Widgets/ListenerTable.hpp> include <UserInterface/Dia
- Language: cc
- Symbols:
  - `setupUi` (function, line 14) `void HavocNamespace::UserInterface::Widgets::ListenersTable::setupUi( QWidget* Form )`
  - `ButtonsInit` (function, line 84) `void HavocNamespace::UserInterface::Widgets::ListenersTable::ButtonsInit()`
  - `connect` (function, line 87) `QObject::connect( buttonAdd, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 107) `QObject::connect( buttonEdit, &QPushButton::clicked, this, [&]()`
  - `connect` (function, line 151) `QObject::connect( buttonRemove,  &QPushButton::clicked, this, [&]()`
  - `ListenerAdd` (function, line 177) `void HavocNamespace::UserInterface::Widgets::ListenersTable::ListenerAdd( Util::ListenerItem item...`
  - `setDBManager` (function, line 283) `void HavocNamespace::UserInterface::Widgets::ListenersTable::setDBManager( HavocSpace::DBManager*...`
  - `CreateNewPackage` (function, line 288) `Util::Packager::Package UserInterface::Widgets::ListenersTable::CreateNewPackage( int EventID, ma...`
  - `ListenerEdit` (function, line 311) `void UserInterface::Widgets::ListenersTable::ListenerEdit( Util::ListenerItem item ) const`
  - `ListenerRemove` (function, line 322) `void UserInterface::Widgets::ListenersTable::ListenerRemove( QString ListenerName ) const`
  - `ListenerError` (function, line 356) `void UserInterface::Widgets::ListenersTable::ListenerError( QString ListenerName, QString Error )...`

## client/src/UserInterface/Widgets/LootWidget.cc
- Layer: presentation
- Doc: include <global.hpp> include <spdlog/spdlog.h>  include <UserInterface/Widgets/LootWidget.h> include <QGraphicsScene> in
- Language: cc
- Symbols:
  - `ImageLabel` (function, line 17) `ImageLabel::ImageLabel( QWidget* parent ) : QWidget( parent )`
  - `resizeEvent` (function, line 32) `void ImageLabel::resizeEvent( QResizeEvent* event )`
  - `pixmap` (function, line 38) `const QPixmap* ImageLabel::pixmap() const`
  - `event` (function, line 43) `bool ImageLabel::event( QEvent* e )`
  - `keyReleaseEvent` (function, line 59) `void ImageLabel::keyReleaseEvent( QKeyEvent* event )`
  - `wheelEvent` (function, line 70) `void ImageLabel::wheelEvent( QWheelEvent* ev )`
  - `setPixmap` (function, line 77) `void ImageLabel::setPixmap( const QPixmap &pixmap )`
  - `resizeImage` (function, line 84) `void ImageLabel::resizeImage()`
  - `LootWidget` (function, line 91) `LootWidget::LootWidget()`
  - `AddScreenshot` (function, line 252) `void LootWidget::AddScreenshot( const QString& DemonID, const QString& Name, const QString& Date,...`
  - `AddDownload` (function, line 272) `void LootWidget::AddDownload( const QString &DemonID, const QString &Name, const QString& Size, c...`
  - `Reload` (function, line 291) `void LootWidget::Reload()`
  - `onScreenshotTableClick` (function, line 304) `void LootWidget::onScreenshotTableClick( const QModelIndex &index )`
  - `onDownloadTableClick` (function, line 328) `void LootWidget::onDownloadTableClick( const QModelIndex &index )`
  - `onAgentChange` (function, line 333) `void LootWidget::onAgentChange( const QString& text )`
  - `AddSessionSection` (function, line 363) `void LootWidget::AddSessionSection( const QString& AgentID )`
  - `onShowChange` (function, line 376) `void LootWidget::onShowChange( const QString& text )`
  - `ScreenshotTableAdd` (function, line 388) `void LootWidget::ScreenshotTableAdd( const QString &Name, const QString &Date )`
  - `DownloadTableAdd` (function, line 413) `void LootWidget::DownloadTableAdd( const QString &Name, const QString &Size, const QString &Date )`
  - `onScreenshotTableCtx` (function, line 435) `void LootWidget::onScreenshotTableCtx( const QPoint &pos )`

## client/src/UserInterface/Widgets/ProcessList.cc
- Layer: presentation
- Doc: include <UserInterface/Widgets/ProcessList.hpp> include <UserInterface/Widgets/DemonInteracted.h> include <QClipboard>
- Language: cc
- Symbols:
  - `setupUi` (function, line 4) `void HavocNamespace::UserInterface::Widgets::ProcessList::setupUi(QWidget *Widget)`
  - `UpdateProcessListJson` (function, line 200) `void HavocNamespace::UserInterface::Widgets::ProcessList::UpdateProcessListJson( QJsonDocument Pr...`
  - `NewTableProcess` (function, line 230) `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTableProcess(std::map<QString, QStri...`
  - `NewTreeProcess` (function, line 278) `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTreeProcess( std::map<QString,QStrin...`
  - `onButton_Refresh` (function, line 298) `void HavocNamespace::UserInterface::Widgets::ProcessList::onButton_Refresh() const`
  - `onTableChange` (function, line 313) `void HavocNamespace::UserInterface::Widgets::ProcessList::onTableChange()`
  - `onTreeChange` (function, line 329) `void HavocNamespace::UserInterface::Widgets::ProcessList::onTreeChange()`
  - `handleTableListMenuContext` (function, line 342) `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTableListMenuContext( const QPoin...`
  - `handleTreeListMenuContext` (function, line 350) `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTreeListMenuContext( const QPoint...`
  - `onActionCopyPID` (function, line 358) `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionCopyPID()`
  - `onActionSetParentProcess` (function, line 366) `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionSetParentProcess()`

## client/src/UserInterface/Widgets/PythonScript.cc
- Layer: presentation
- Doc: include <UserInterface/Widgets/PythonScript.hpp> include <Util/ColorText.h> include <QThread> include <thread> include <
- Language: cc
- Symbols:
  - `setupUi` (function, line 7) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::setupUi(QWidget *WindowWidget)`
  - `RunCode` (function, line 47) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::RunCode( QString code )`
  - `AppendFromInput` (function, line 63) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendFromInput()`
  - `AppendOutput` (function, line 75) `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendOutput( QString output )`

## client/src/UserInterface/Widgets/ScriptManager.cc
- Layer: presentation
- Doc: include <UserInterface/Widgets/ScriptManager.h> include <UserInterface/Widgets/TeamserverTabSession.h>  include <Havoc/D
- Language: cc
- Symbols:
  - `SetupUi` (function, line 12) `void ScriptManager::SetupUi( QWidget *Form )`
  - `RetranslateUi` (function, line 103) `void ScriptManager::RetranslateUi( )`
  - `AddScript` (function, line 110) `bool ScriptManager::AddScript( QString Path )`
  - `AddScriptTable` (function, line 139) `void ScriptManager::AddScriptTable( QString Path )`
  - `b_LoadScript` (function, line 153) `void ScriptManager::b_LoadScript()`
  - `menu_ScriptMenu` (function, line 185) `void ScriptManager::menu_ScriptMenu( const QPoint &pos ) const`
  - `ReloadScript` (function, line 194) `void ScriptManager::ReloadScript() const`
  - `RemoveScript` (function, line 204) `void ScriptManager::RemoveScript() const`

## client/src/UserInterface/Widgets/SessionGraph.cc
- Layer: presentation
- Doc: include <global.hpp>  include <Havoc/Havoc.hpp>  include <UserInterface/Widgets/SessionGraph.hpp> include <UserInterface
- Language: cc
- Symbols:
  - `GraphWidget` (function, line 27) `GraphWidget::GraphWidget( QWidget* parent ) : QGraphicsView( parent )`
  - `GraphNodeAdd` (function, line 53) `Node* GraphWidget::GraphNodeAdd( SessionItem Session )`
  - `GraphNodeRemove` (function, line 83) `void GraphWidget::GraphNodeRemove( SessionItem Session )`
  - `GraphPivotNodeAdd` (function, line 104) `void GraphWidget::GraphPivotNodeAdd( QString AgentID, SessionItem Session )`
  - `GraphPivotNodeDisconnect` (function, line 146) `void GraphWidget::GraphPivotNodeDisconnect( QString AgentID )`
  - `GraphPivotNodeReconnect` (function, line 169) `void GraphWidget::GraphPivotNodeReconnect( QString ParentAgentID, QString ChildAgentID )`
  - `itemMoved` (function, line 197) `void GraphWidget::itemMoved()`
  - `keyPressEvent` (function, line 203) `void GraphWidget::keyPressEvent( QKeyEvent* event )`
  - `timerEvent` (function, line 220) `void GraphWidget::timerEvent( QTimerEvent* event )`
  - `resizeEvent` (function, line 250) `void GraphWidget::resizeEvent( QResizeEvent* event )`
  - `wheelEvent` (function, line 257) `void GraphWidget::wheelEvent( QWheelEvent* event )`
  - `drawBackground` (function, line 262) `void GraphWidget::drawBackground( QPainter* painter, const QRectF& rect )`
  - `scaleView` (function, line 278) `void GraphWidget::scaleView( qreal scaleFactor )`
  - `shuffle` (function, line 287) `void GraphWidget::shuffle()`
  - `zoomIn` (function, line 298) `void GraphWidget::zoomIn()`
  - `zoomOut` (function, line 303) `void GraphWidget::zoomOut()`
  - `GraphNodeGet` (function, line 308) `Node *GraphWidget::GraphNodeGet( QString AgentID )`
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
  - `sourceNode` (function, line 518) `Node* Edge::sourceNode() const`
  - `destNode` (function, line 523) `Node* Edge::destNode() const`
  - `contextMenuEvent` (function, line 528) `void Node::contextMenuEvent( QGraphicsSceneContextMenuEvent* event )`
  - `adjust` (function, line 797) `void Edge::adjust()`
  - `boundingRect` (function, line 821) `QRectF Edge::boundingRect() const`
  - `paint` (function, line 834) `void Edge::paint( QPainter* painter, const QStyleOptionGraphicsItem*, QWidget* )`
  - `Color` (function, line 862) `void Edge::Color( QColor color )`
  - `Node` (function, line 871) `Node::Node( NodeItemType NodeType, QString NodeLabel, GraphWidget* graphWidget ) : graph( graphWi...`
  - `appendChild` (function, line 886) `void Node::appendChild( Node* child )`
  - `removeChild` (function, line 891) `void Node::removeChild( Node* child )`
  - `boundingRect` (function, line 898) `QRectF Node::boundingRect() const`
  - `addEdge` (function, line 903) `void Node::addEdge( Edge* edge )`
  - `edges` (function, line 909) `QVector<Edge*> Node::edges() const`
  - `calculateForces` (function, line 914) `void Node::calculateForces()`
  - `mouseMoveEvent` (function, line 935) `void Node::mouseMoveEvent( QGraphicsSceneMouseEvent* event )`
  - `advancePosition` (function, line 940) `bool Node::advancePosition()`
  - `shape` (function, line 949) `QPainterPath Node::shape() const`
  - `paint` (function, line 958) `void Node::paint( QPainter *painter, const QStyleOptionGraphicsItem* option, QWidget* )`
  - `itemChange` (function, line 1006) `QVariant Node::itemChange( GraphicsItemChange change, const QVariant& value )`
  - `mousePressEvent` (function, line 1025) `void Node::mousePressEvent( QGraphicsSceneMouseEvent* event )`
  - `mouseReleaseEvent` (function, line 1031) `void Node::mouseReleaseEvent( QGraphicsSceneMouseEvent* event )`

## client/src/UserInterface/Widgets/SessionTable.cc
- Layer: presentation
- Doc: include <Havoc/Havoc.hpp> include <global.hpp>  include <UserInterface/Widgets/SessionTable.hpp> include <UserInterface/
- Language: cc
- Symbols:
  - `setupUi` (function, line 15) `void HavocNamespace::UserInterface::Widgets::SessionTable::setupUi(QWidget *Form, QString Teamser...`
  - `NewSessionItem` (function, line 81) `void HavocNamespace::UserInterface::Widgets::SessionTable::NewSessionItem( Util::SessionItem item...`
  - `ChangeSessionValue` (function, line 210) `void UserInterface::Widgets::SessionTable::ChangeSessionValue( QString DemonID, int key, QString ...`
  - `updateRow` (function, line 219) `void HavocNamespace::UserInterface::Widgets::SessionTable::updateRow()`

## client/src/UserInterface/Widgets/Store.cc
- Layer: presentation
- Doc: include <UserInterface/Widgets/ScriptManager.h> include <UserInterface/Widgets/TeamserverTabSession.h> include <Havoc/DB
- Language: cc
- Symbols:
  - `setupUi` (function, line 9) `void Store::setupUi( QWidget* Store)`
  - `connect` (function, line 75) `QObject::connect(reply, &QNetworkReply::finished, [reply, this]()`
  - `connect` (function, line 108) `QObject::connect(StoreTable, &QTableWidget::itemSelectionChanged, [this]()`
  - `connect` (function, line 115) `QObject::connect(installButton, &QPushButton::clicked, [this]()`
  - `displayData` (function, line 133) `void Store::displayData(int position)`
  - `AddScript` (function, line 146) `bool Store::AddScript( QString Path )`
  - `installScript` (function, line 175) `void Store::installScript(int position)`
  - `retranslateUi` (function, line 223) `void Store::retranslateUi()`

## client/src/UserInterface/Widgets/Teamserver.cc
- Layer: presentation
- Doc: include <UserInterface/Widgets/Teamserver.hpp>  include <QScrollBar>
- Language: cc
- Symbols:
  - `setupUi` (function, line 4) `void Teamserver::setupUi( QWidget* Teamserver )`
  - `retranslateUi` (function, line 25) `void Teamserver::retranslateUi()`
  - `AddLoggerText` (function, line 30) `void Teamserver::AddLoggerText( const QString& Text ) const`

## client/src/UserInterface/Widgets/TeamserverTabSession.cc
- Layer: presentation
- Doc: include <global.hpp>  include <UserInterface/Widgets/TeamserverTabSession.h> include <UserInterface/Widgets/SessionTable
- Language: cc
- Symbols:
  - `setupUi` (function, line 26) `void HavocNamespace::UserInterface::Widgets::TeamserverTabSession::setupUi( QWidget* Page, QStrin...`
  - `connect` (function, line 121) `connect( tabWidget->tabBar(), &QTabBar::tabCloseRequested, this, [&]( int index )`
  - `connect` (function, line 140) `connect( SessionTableWidget->SessionTableWidget, &QTableWidget::doubleClicked, this, [&]( const Q...`
  - `handleDemonContextMenu` (function, line 164) `void UserInterface::Widgets::TeamserverTabSession::handleDemonContextMenu( const QPoint &pos )`
  - `NewBottomTab` (function, line 467) `void UserInterface::Widgets::TeamserverTabSession::NewBottomTab( QWidget* TabWidget, const string...`
  - `NewWidgetTab` (function, line 487) `void UserInterface::Widgets::TeamserverTabSession::NewWidgetTab( QWidget *TabWidget, const std::s...`
  - `removeTabSmall` (function, line 508) `void UserInterface::Widgets::TeamserverTabSession::removeTabSmall( int index ) const`
