# API (page 3 of 8)
Previous: [API_p2.md](API_p2.md)

## client/src/UserInterface/Widgets/LootWidget.cc
Depends on: `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/global.hpp`
- `ImageLabel` (function) `client/src/UserInterface/Widgets/LootWidget.cc:17` `ImageLabel::ImageLabel( QWidget* parent ) : QWidget( parent )` -- imagelabel.cpp
- `resizeEvent` (function) `client/src/UserInterface/Widgets/LootWidget.cc:33` `void ImageLabel::resizeEvent( QResizeEvent* event )`
- `pixmap` (function) `client/src/UserInterface/Widgets/LootWidget.cc:39` `const QPixmap* ImageLabel::pixmap() const`
- `event` (function) `client/src/UserInterface/Widgets/LootWidget.cc:44` `bool ImageLabel::event( QEvent* e )`
- `keyReleaseEvent` (function) `client/src/UserInterface/Widgets/LootWidget.cc:60` `void ImageLabel::keyReleaseEvent( QKeyEvent* event )`
- `wheelEvent` (function) `client/src/UserInterface/Widgets/LootWidget.cc:71` `void ImageLabel::wheelEvent( QWheelEvent* ev )`
- `setPixmap` (function) `client/src/UserInterface/Widgets/LootWidget.cc:78` `void ImageLabel::setPixmap( const QPixmap &pixmap )`
- `resizeImage` (function) `client/src/UserInterface/Widgets/LootWidget.cc:85` `void ImageLabel::resizeImage()`
- `LootWidget` (function) `client/src/UserInterface/Widgets/LootWidget.cc:92` `LootWidget::LootWidget()`
- `AddScreenshot` (function) `client/src/UserInterface/Widgets/LootWidget.cc:253` `void LootWidget::AddScreenshot( const QString& DemonID, const QString& Name, const QString& Date,...`
- `AddDownload` (function) `client/src/UserInterface/Widgets/LootWidget.cc:273` `void LootWidget::AddDownload( const QString &DemonID, const QString &Name, const QString& Size, c...`
- `Reload` (function) `client/src/UserInterface/Widgets/LootWidget.cc:292` `void LootWidget::Reload()`
- `onScreenshotTableClick` (function) `client/src/UserInterface/Widgets/LootWidget.cc:305` `void LootWidget::onScreenshotTableClick( const QModelIndex &index )`
- `onDownloadTableClick` (function) `client/src/UserInterface/Widgets/LootWidget.cc:329` `void LootWidget::onDownloadTableClick( const QModelIndex &index )`
- `onAgentChange` (function) `client/src/UserInterface/Widgets/LootWidget.cc:334` `void LootWidget::onAgentChange( const QString& text )`
- `AddSessionSection` (function) `client/src/UserInterface/Widgets/LootWidget.cc:364` `void LootWidget::AddSessionSection( const QString& AgentID )`
- `onShowChange` (function) `client/src/UserInterface/Widgets/LootWidget.cc:377` `void LootWidget::onShowChange( const QString& text )`
- `ScreenshotTableAdd` (function) `client/src/UserInterface/Widgets/LootWidget.cc:389` `void LootWidget::ScreenshotTableAdd( const QString &Name, const QString &Date )`
- `DownloadTableAdd` (function) `client/src/UserInterface/Widgets/LootWidget.cc:414` `void LootWidget::DownloadTableAdd( const QString &Name, const QString &Size, const QString &Date )`
- `onScreenshotTableCtx` (function) `client/src/UserInterface/Widgets/LootWidget.cc:436` `void LootWidget::onScreenshotTableCtx( const QPoint &pos )`

## client/src/UserInterface/Widgets/ProcessList.cc
Depends on: `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`
- `setupUi` (function) `client/src/UserInterface/Widgets/ProcessList.cc:5` `void HavocNamespace::UserInterface::Widgets::ProcessList::setupUi(QWidget *Widget)`
- `UpdateProcessListJson` (function) `client/src/UserInterface/Widgets/ProcessList.cc:201` `void HavocNamespace::UserInterface::Widgets::ProcessList::UpdateProcessListJson( QJsonDocument Pr...`
- `NewTableProcess` (function) `client/src/UserInterface/Widgets/ProcessList.cc:231` `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTableProcess(std::map<QString, QStri...`
- `NewTreeProcess` (function) `client/src/UserInterface/Widgets/ProcessList.cc:279` `void HavocNamespace::UserInterface::Widgets::ProcessList::NewTreeProcess( std::map<QString,QStrin...`
- `onButton_Refresh` (function) `client/src/UserInterface/Widgets/ProcessList.cc:299` `void HavocNamespace::UserInterface::Widgets::ProcessList::onButton_Refresh() const`
- `onTableChange` (function) `client/src/UserInterface/Widgets/ProcessList.cc:314` `void HavocNamespace::UserInterface::Widgets::ProcessList::onTableChange()`
- `onTreeChange` (function) `client/src/UserInterface/Widgets/ProcessList.cc:330` `void HavocNamespace::UserInterface::Widgets::ProcessList::onTreeChange()`
- `handleTableListMenuContext` (function) `client/src/UserInterface/Widgets/ProcessList.cc:343` `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTableListMenuContext( const QPoin...`
- `handleTreeListMenuContext` (function) `client/src/UserInterface/Widgets/ProcessList.cc:351` `void HavocNamespace::UserInterface::Widgets::ProcessList::handleTreeListMenuContext( const QPoint...`
- `onActionCopyPID` (function) `client/src/UserInterface/Widgets/ProcessList.cc:359` `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionCopyPID()`
- `onActionSetParentProcess` (function) `client/src/UserInterface/Widgets/ProcessList.cc:367` `void HavocNamespace::UserInterface::Widgets::ProcessList::onActionSetParentProcess()`

## client/src/UserInterface/Widgets/PythonScript.cc
Depends on: `client/include/Havoc/PythonApi/PythonApi.h`, `client/include/UserInterface/Widgets/PythonScript.hpp`, `client/include/Util/ColorText.h`
- `setupUi` (function) `client/src/UserInterface/Widgets/PythonScript.cc:9` `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::setupUi(QWidget *WindowWidget)`
- `RunCode` (function) `client/src/UserInterface/Widgets/PythonScript.cc:48` `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::RunCode( QString code )`
- `AppendFromInput` (function) `client/src/UserInterface/Widgets/PythonScript.cc:64` `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendFromInput()`
- `AppendOutput` (function) `client/src/UserInterface/Widgets/PythonScript.cc:76` `void HavocNamespace::UserInterface::Widgets::PythonScriptInterpreter::AppendOutput( QString output )`

## client/src/UserInterface/Widgets/ScriptManager.cc
Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`
- `SetupUi` (function) `client/src/UserInterface/Widgets/ScriptManager.cc:13` `void ScriptManager::SetupUi( QWidget *Form )`
- `RetranslateUi` (function) `client/src/UserInterface/Widgets/ScriptManager.cc:104` `void ScriptManager::RetranslateUi( )`
- `AddScript` (function) `client/src/UserInterface/Widgets/ScriptManager.cc:111` `bool ScriptManager::AddScript( QString Path )`
- `AddScriptTable` (function) `client/src/UserInterface/Widgets/ScriptManager.cc:140` `void ScriptManager::AddScriptTable( QString Path )`
- `b_LoadScript` (function) `client/src/UserInterface/Widgets/ScriptManager.cc:155` `void ScriptManager::b_LoadScript()`
- `menu_ScriptMenu` (function) `client/src/UserInterface/Widgets/ScriptManager.cc:186` `void ScriptManager::menu_ScriptMenu( const QPoint &pos ) const`
- `ReloadScript` (function) `client/src/UserInterface/Widgets/ScriptManager.cc:195` `void ScriptManager::ReloadScript() const`
- `RemoveScript` (function) `client/src/UserInterface/Widgets/ScriptManager.cc:204` `void ScriptManager::RemoveScript() const` -- TODO: clear python interpreter and reload every script except the one that got removed

## client/src/UserInterface/Widgets/SessionGraph.cc
Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Havoc.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
- `GraphWidget` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:28` `GraphWidget::GraphWidget( QWidget* parent ) : QGraphicsView( parent )`
- `GraphNodeAdd` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:54` `Node* GraphWidget::GraphNodeAdd( SessionItem Session )`
- `GraphNodeRemove` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:84` `void GraphWidget::GraphNodeRemove( SessionItem Session )`
- `GraphPivotNodeAdd` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:105` `void GraphWidget::GraphPivotNodeAdd( QString AgentID, SessionItem Session )`
- `GraphPivotNodeDisconnect` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:147` `void GraphWidget::GraphPivotNodeDisconnect( QString AgentID )`
- `GraphPivotNodeReconnect` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:170` `void GraphWidget::GraphPivotNodeReconnect( QString ParentAgentID, QString ChildAgentID )`
- `itemMoved` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:198` `void GraphWidget::itemMoved()`
- `keyPressEvent` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:204` `void GraphWidget::keyPressEvent( QKeyEvent* event )`
- `timerEvent` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:221` `void GraphWidget::timerEvent( QTimerEvent* event )`
- `resizeEvent` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:251` `void GraphWidget::resizeEvent( QResizeEvent* event )`
- `wheelEvent` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:258` `void GraphWidget::wheelEvent( QWheelEvent* event )`
- `drawBackground` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:263` `void GraphWidget::drawBackground( QPainter* painter, const QRectF& rect )`
- `scaleView` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:279` `void GraphWidget::scaleView( qreal scaleFactor )`
- `shuffle` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:288` `void GraphWidget::shuffle()`
- `zoomIn` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:299` `void GraphWidget::zoomIn()`
- `zoomOut` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:304` `void GraphWidget::zoomOut()`
- `GraphNodeGet` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:309` `Node *GraphWidget::GraphNodeGet( QString AgentID )`
- `initNode` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:329` `void GraphWidget::initNode(Node* v)` -- Initialize node properties for layout
- `layout` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:340` `void GraphWidget::layout(Node* T)` -- Entry function for layout
- `firstWalk` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:350` `void GraphWidget::firstWalk(Node* v)` -- Calculate preliminary x-coordinates for all nodes
- `apportion` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:383` `void GraphWidget::apportion(Node* v, Node*& defaultAncestor)` -- Adjusts spacing between subtrees to ensure they don't overlap
- `moveSubtree` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:434` `void GraphWidget::moveSubtree(Node* wm, Node* wp, double shift)` -- Move the subtree rooted at wp so it's shifted away from the subtree rooted at wm
- `nextLeft` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:453` `Node* GraphWidget::nextLeft(Node* v)` -- Helper function to get the leftmost child or thread (left contour)
- `nextRight` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:462` `Node* GraphWidget::nextRight(Node* v)` -- Helper function to get the rightmost child or thread (right contour)
- `ancestor` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:471` `Node* GraphWidget::ancestor(Node* vim, Node* v, Node*& defaultAncestor)` -- Get the ancestor of vim that is in the same subtree as v, or return defaultAncestor
- `executeShifts` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:481` `void GraphWidget::executeShifts(Node* v)` -- Propagate the shifts down to ensure subtrees are moved accordingly
- `secondWalk` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:496` `void GraphWidget::secondWalk(Node* v, double m, double depth)` -- Walk the tree again to assign final x and y coordinates to each node
- `Edge` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:508` `Edge::Edge( Node* sourceNode, Node* destNode, QColor Color )
    : source( sourceNode ), dest( de...`
- `sourceNode` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:519` `Node* Edge::sourceNode() const`
- `destNode` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:524` `Node* Edge::destNode() const`
- `contextMenuEvent` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:529` `void Node::contextMenuEvent( QGraphicsSceneContextMenuEvent* event )`
- `adjust` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:798` `void Edge::adjust()`
- `boundingRect` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:822` `QRectF Edge::boundingRect() const`
- `paint` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:835` `void Edge::paint( QPainter* painter, const QStyleOptionGraphicsItem*, QWidget* )`
- `Color` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:863` `void Edge::Color( QColor color )`
- `Node` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:871` `Node::Node( NodeItemType NodeType, QString NodeLabel, GraphWidget* graphWidget ) : graph( graphWi...`
- `appendChild` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:887` `void Node::appendChild( Node* child )`
- `removeChild` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:892` `void Node::removeChild( Node* child )`
- `boundingRect` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:899` `QRectF Node::boundingRect() const`
- `addEdge` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:904` `void Node::addEdge( Edge* edge )`
- `edges` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:910` `QVector<Edge*> Node::edges() const`
- `calculateForces` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:915` `void Node::calculateForces()`
- `mouseMoveEvent` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:936` `void Node::mouseMoveEvent( QGraphicsSceneMouseEvent* event )`
- `advancePosition` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:941` `bool Node::advancePosition()`
- `shape` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:950` `QPainterPath Node::shape() const`
- `paint` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:959` `void Node::paint( QPainter *painter, const QStyleOptionGraphicsItem* option, QWidget* )`
- `itemChange` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:1007` `QVariant Node::itemChange( GraphicsItemChange change, const QVariant& value )`
- `mousePressEvent` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:1026` `void Node::mousePressEvent( QGraphicsSceneMouseEvent* event )`
- `mouseReleaseEvent` (function) `client/src/UserInterface/Widgets/SessionGraph.cc:1032` `void Node::mouseReleaseEvent( QGraphicsSceneMouseEvent* event )`

## client/src/UserInterface/Widgets/SessionTable.cc
Depends on: `client/include/Havoc/Havoc.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
- `setupUi` (function) `client/src/UserInterface/Widgets/SessionTable.cc:16` `void HavocNamespace::UserInterface::Widgets::SessionTable::setupUi(QWidget *Form, QString Teamser...`
- `NewSessionItem` (function) `client/src/UserInterface/Widgets/SessionTable.cc:82` `void HavocNamespace::UserInterface::Widgets::SessionTable::NewSessionItem( Util::SessionItem item...`
- `ChangeSessionValue` (function) `client/src/UserInterface/Widgets/SessionTable.cc:211` `void UserInterface::Widgets::SessionTable::ChangeSessionValue( QString DemonID, int key, QString ...`
- `updateRow` (function) `client/src/UserInterface/Widgets/SessionTable.cc:220` `void HavocNamespace::UserInterface::Widgets::SessionTable::updateRow()`

## client/src/UserInterface/Widgets/Store.cc
Depends on: `client/include/Havoc/DBManager/DBManager.hpp`, `client/include/UserInterface/Widgets/ScriptManager.h`, `client/include/UserInterface/Widgets/Store.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/global.hpp`
- `setupUi` (function) `client/src/UserInterface/Widgets/Store.cc:10` `void Store::setupUi( QWidget* Store)`
- `connect` (function) `client/src/UserInterface/Widgets/Store.cc:76` `QObject::connect(reply, &QNetworkReply::finished, [reply, this]()`
- `connect` (function) `client/src/UserInterface/Widgets/Store.cc:109` `QObject::connect(StoreTable, &QTableWidget::itemSelectionChanged, [this]()`
- `connect` (function) `client/src/UserInterface/Widgets/Store.cc:116` `QObject::connect(installButton, &QPushButton::clicked, [this]()`
- `displayData` (function) `client/src/UserInterface/Widgets/Store.cc:134` `void Store::displayData(int position)`
- `AddScript` (function) `client/src/UserInterface/Widgets/Store.cc:147` `bool Store::AddScript( QString Path )`
- `installScript` (function) `client/src/UserInterface/Widgets/Store.cc:176` `void Store::installScript(int position)`
- `retranslateUi` (function) `client/src/UserInterface/Widgets/Store.cc:224` `void Store::retranslateUi()`

## client/src/UserInterface/Widgets/Teamserver.cc
Depends on: `client/include/UserInterface/Widgets/Teamserver.hpp`
- `setupUi` (function) `client/src/UserInterface/Widgets/Teamserver.cc:5` `void Teamserver::setupUi( QWidget* Teamserver )`
- `retranslateUi` (function) `client/src/UserInterface/Widgets/Teamserver.cc:26` `void Teamserver::retranslateUi()`
- `AddLoggerText` (function) `client/src/UserInterface/Widgets/Teamserver.cc:31` `void Teamserver::AddLoggerText( const QString& Text ) const`

## client/src/UserInterface/Widgets/TeamserverTabSession.cc
Depends on: `client/include/Havoc/Connector.hpp`, `client/include/Havoc/Packager.hpp`, `client/include/UserInterface/SmallWidgets/EventViewer.hpp`, `client/include/UserInterface/Widgets/Chat.hpp`, `client/include/UserInterface/Widgets/DemonInteracted.h`, `client/include/UserInterface/Widgets/FileBrowser.hpp`, `client/include/UserInterface/Widgets/LootWidget.h`, `client/include/UserInterface/Widgets/ProcessList.hpp`, `client/include/UserInterface/Widgets/SessionGraph.hpp`, `client/include/UserInterface/Widgets/SessionTable.hpp`, `client/include/UserInterface/Widgets/TeamserverTabSession.h`, `client/include/Util/ColorText.h`, `client/include/global.hpp`
- `setupUi` (function) `client/src/UserInterface/Widgets/TeamserverTabSession.cc:27` `void HavocNamespace::UserInterface::Widgets::TeamserverTabSession::setupUi( QWidget* Page, QStrin...`
- `connect` (function) `client/src/UserInterface/Widgets/TeamserverTabSession.cc:121` `connect( tabWidget->tabBar(), &QTabBar::tabCloseRequested, this, [&]( int index )`
- `connect` (function) `client/src/UserInterface/Widgets/TeamserverTabSession.cc:141` `connect( SessionTableWidget->SessionTableWidget, &QTableWidget::doubleClicked, this, [&]( const Q...`
- `handleDemonContextMenu` (function) `client/src/UserInterface/Widgets/TeamserverTabSession.cc:165` `void UserInterface::Widgets::TeamserverTabSession::handleDemonContextMenu( const QPoint &pos )`
- `NewBottomTab` (function) `client/src/UserInterface/Widgets/TeamserverTabSession.cc:469` `void UserInterface::Widgets::TeamserverTabSession::NewBottomTab( QWidget* TabWidget, const string...`
- `NewWidgetTab` (function) `client/src/UserInterface/Widgets/TeamserverTabSession.cc:488` `void UserInterface::Widgets::TeamserverTabSession::NewWidgetTab( QWidget *TabWidget, const std::s...`
- `removeTabSmall` (function) `client/src/UserInterface/Widgets/TeamserverTabSession.cc:509` `void UserInterface::Widgets::TeamserverTabSession::removeTabSmall( int index ) const`

## client/src/Util/Base64.cpp
Depends on: `client/include/global.hpp`
- `base64_encode` (function) `client/src/Util/Base64.cpp:9` `std::string HavocNamespace::Util::base64_encode(const char* buf, unsigned int bufLen)`

## client/src/Util/ColorText.cpp
Depends on: `client/include/Util/ColorText.h`
- `SetDraculaDark` (function) `client/src/Util/ColorText.cpp:24` `void HavocNamespace::Util::ColorText::SetDraculaDark()`
- `SetDraculaLight` (function) `client/src/Util/ColorText.cpp:40` `void HavocNamespace::Util::ColorText::SetDraculaLight()`
- `Color` (function) `client/src/Util/ColorText.cpp:45` `QString HavocNamespace::Util::ColorText::Color(const QString& color, const QString &text)`
- `Background` (function) `client/src/Util/ColorText.cpp:50` `QString HavocNamespace::Util::ColorText::Background(const QString& text)`
- `Foreground` (function) `client/src/Util/ColorText.cpp:55` `QString HavocNamespace::Util::ColorText::Foreground(const QString& text)`
- `Comment` (function) `client/src/Util/ColorText.cpp:59` `QString HavocNamespace::Util::ColorText::Comment(const QString& text)`
- `Cyan` (function) `client/src/Util/ColorText.cpp:63` `QString HavocNamespace::Util::ColorText::Cyan(const QString& text)`
- `Green` (function) `client/src/Util/ColorText.cpp:67` `QString HavocNamespace::Util::ColorText::Green(const QString& text)`
- `Orange` (function) `client/src/Util/ColorText.cpp:71` `QString HavocNamespace::Util::ColorText::Orange(const QString& text)`
- `Pink` (function) `client/src/Util/ColorText.cpp:75` `QString HavocNamespace::Util::ColorText::Pink(const QString& text)`
- `Purple` (function) `client/src/Util/ColorText.cpp:79` `QString HavocNamespace::Util::ColorText::Purple(const QString& text)`
- `Red` (function) `client/src/Util/ColorText.cpp:83` `QString HavocNamespace::Util::ColorText::Red(const QString& text)`
- `Yellow` (function) `client/src/Util/ColorText.cpp:87` `QString HavocNamespace::Util::ColorText::Yellow(const QString& text)`
- `Bold` (function) `client/src/Util/ColorText.cpp:91` `QString HavocNamespace::Util::ColorText::Bold(const QString& text)`
- `Underline` (function) `client/src/Util/ColorText.cpp:95` `QString HavocNamespace::Util::ColorText::Underline(const QString &text)`
- `UnderlineBackground` (function) `client/src/Util/ColorText.cpp:99` `QString HavocNamespace::Util::ColorText::UnderlineBackground(const QString &text)`
- `UnderlineForeground` (function) `client/src/Util/ColorText.cpp:103` `QString HavocNamespace::Util::ColorText::UnderlineForeground(const QString &text)`
- `UnderlineComment` (function) `client/src/Util/ColorText.cpp:107` `QString HavocNamespace::Util::ColorText::UnderlineComment(const QString &text)`
- `UnderlineCyan` (function) `client/src/Util/ColorText.cpp:111` `QString HavocNamespace::Util::ColorText::UnderlineCyan(const QString &text)`
- `UnderlineGreen` (function) `client/src/Util/ColorText.cpp:115` `QString HavocNamespace::Util::ColorText::UnderlineGreen(const QString &text)`
- `UnderlineOrange` (function) `client/src/Util/ColorText.cpp:119` `QString HavocNamespace::Util::ColorText::UnderlineOrange(const QString &text)`
- `UnderlinePink` (function) `client/src/Util/ColorText.cpp:123` `QString HavocNamespace::Util::ColorText::UnderlinePink(const QString &text)`
- `UnderlinePurple` (function) `client/src/Util/ColorText.cpp:127` `QString HavocNamespace::Util::ColorText::UnderlinePurple(const QString &text)`
- `UnderlineRed` (function) `client/src/Util/ColorText.cpp:131` `QString HavocNamespace::Util::ColorText::UnderlineRed(const QString &text)`
- `UnderlineYellow` (function) `client/src/Util/ColorText.cpp:135` `QString HavocNamespace::Util::ColorText::UnderlineYellow(const QString &text)`

## client/src/global.cc
Depends on: `client/include/Havoc/Connector.hpp`, `client/include/global.hpp`
- `gen_random` (function) `client/src/global.cc:31` `std::string Util::gen_random( const int len )`
- `Export` (function) `client/src/global.cc:42` `void Util::SessionItem::Export()`

## payloads/Demon/include/common/Native.h
Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Memory.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Syscalls.h`, `payloads/Demon/include/core/Thread.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/src/core/Win32.c`
- `NtCurrentPeb` (function) `payloads/Demon/include/common/Native.h:7104` `__inline struct _PEB * NtCurrentPeb()` -- 17/3/2011 added
- `GetKUserSharedData` (function) `payloads/Demon/include/common/Native.h:10905` `__inline struct _KUSER_SHARED_DATA * GetKUserSharedData()`
- `NtGetTickCount` (function) `payloads/Demon/include/common/Native.h:10907` `__forceinline ULONG NtGetTickCount()`
- `A_SHAFinal` (function) `payloads/Demon/include/common/Native.h:21318` `void NTAPI A_SHAFinal( PSHA_CTX Context, PULONG Result );`
- `RtlInitString` (function) `payloads/Demon/include/common/Native.h:21963` `void NTAPI RtlInitString( PSTRING DestinationString, PCSZ SourceString );`
- `RtlUpdateClonedCriticalSection` (function) `payloads/Demon/include/common/Native.h:22100` `void NTAPI RtlUpdateClonedCriticalSection( PRTL_CRITICAL_SECTION CriticalSection );`
- `LdrInitShimEngineDynamic` (function) `payloads/Demon/include/common/Native.h:22118` `int NTAPI LdrInitShimEngineDynamic( PVOID pShimEngineModule);`
- `ZwWow64GetCurrentProcessorNumberEx` (function) `payloads/Demon/include/common/Native.h:22202` `void NTAPI ZwWow64GetCurrentProcessorNumberEx( OUT PPROCESSOR_NUMBER ProcNumber );`
- `ZwWow64CsrCaptureMessageBuffer` (function) `payloads/Demon/include/common/Native.h:22224` `void NTAPI ZwWow64CsrCaptureMessageBuffer( _Inout_ PCSR_CAPTURE_HEADER CaptureBuffer, IN PVOID Buffer OPTIONAL, IN...`
- `ZwWow64CsrCaptureMessageString` (function) `payloads/Demon/include/common/Native.h:22233` `void NTAPI ZwWow64CsrCaptureMessageString( _Inout_ PCSR_CAPTURE_HEADER CaptureBuffer, IN PCSTR String, IN ULONG...`
- `ZwWow64CsrFreeCaptureBuffer` (function) `payloads/Demon/include/common/Native.h:22254` `void NTAPI ZwWow64CsrFreeCaptureBuffer( IN PCSR_CAPTURE_HEADER CaptureBuffer );`
- `wcslen` (function) `payloads/Demon/include/common/Native.h:22538` `IMPORT_FN size_t __cdecl wcslen(const wchar_t *);` -- readded 4 jan 2012 win64 mode does not need this for using this routines ntdllp.lib is required if !defined(_M_X64)
- `wcscat` (function) `payloads/Demon/include/common/Native.h:22539` `IMPORT_FN wchar_t * __cdecl wcscat(wchar_t *dst, const wchar_t *src);`
- `wcscmp` (function) `payloads/Demon/include/common/Native.h:22540` `IMPORT_FN int __cdecl wcscmp(const wchar_t *src, const wchar_t *dst);`
- `wcschr` (function) `payloads/Demon/include/common/Native.h:22545` `IMPORT_FN wchar_t * __cdecl wcschr(const wchar_t *string, wchar_t ch);`
- `wcscpy` (function) `payloads/Demon/include/common/Native.h:22546` `IMPORT_FN wchar_t * __cdecl wcscpy(wchar_t *dst, const wchar_t *src);`
- `wcsncat` (function) `payloads/Demon/include/common/Native.h:22547` `IMPORT_FN wchar_t * __cdecl wcsncat(wchar_t *front, const wchar_t *back, size_t count);`
- `wcsncpy` (function) `payloads/Demon/include/common/Native.h:22548` `IMPORT_FN wchar_t * __cdecl wcsncpy(wchar_t *dest, const wchar_t *source, size_t count);`

## payloads/Demon/include/core/CoffeeLdr.h
Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/src/core/CoffeeLdr.c`, `payloads/Demon/src/core/Command.c`
- `thread` (function) `payloads/Demon/include/core/CoffeeLdr.h:118` `* CoffeeLdr * Simply executes an object file in the current thread (blocking) * @param EntryName * @param CoffeeData...`

## payloads/Demon/include/core/Kerberos.h
Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/src/core/Command.c`, `payloads/Demon/src/core/Kerberos.c`
- `GetLUID` (function) `payloads/Demon/include/core/Kerberos.h:203` `LUID* GetLUID( HANDLE hToken );`

## payloads/Demon/include/core/Socket.h
Imported by: `payloads/Demon/include/Demon.h`
- `HTTP` (function) `payloads/Demon/include/core/Socket.h:66` `* This is needed for Socks5 and HTTP(S) agents. * @return TRUE or FALSE */ BOOL InitWSA( VOID );`

## payloads/Demon/include/core/Spoof.h
Imported by: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/src/core/Spoof.c`
- `Spoof` (function) `payloads/Demon/include/core/Spoof.h:17` `static ULONG_PTR Spoof();`

## payloads/Demon/include/crypt/AesCrypt.h
Imported by: `payloads/Demon/src/core/Package.c`, `payloads/Demon/src/core/Parser.c`, `payloads/Demon/src/core/Transport.c`, `payloads/Demon/src/crypt/AesCrypt.c`
- `AesInit` (function) `payloads/Demon/include/crypt/AesCrypt.h:22` `void AesInit( PAESCTX ctx, const PUINT8 key, const PUINT8 iv);`
- `AesXCryptBuffer` (function) `payloads/Demon/include/crypt/AesCrypt.h:23` `void AesXCryptBuffer( PAESCTX ctx, PUINT8 buf, SIZE_T length);`

## payloads/Demon/scripts/hash_func.py
- `hash_string` (function) `payloads/Demon/scripts/hash_func.py:7` `def hash_string(string)`
- `hash_coffapi` (function) `payloads/Demon/scripts/hash_func.py:18` `def hash_coffapi(string)`

## payloads/Demon/src/Demon.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Defines.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Runtime.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/SysNative.h`, `payloads/Demon/include/core/Transport.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/Inject.h`
- `DemonMain` (function) `payloads/Demon/src/Demon.c:34` `VOID DemonMain( PVOID ModuleInst, PKAYN_ARGS KArgs )` -- In DemonMain it should go as followed:  1.
- `DemonRoutine` (function) `payloads/Demon/src/Demon.c:64` `_Noreturn
VOID DemonRoutine()`
- `DemonMetaData` (function) `payloads/Demon/src/Demon.c:95` `VOID DemonMetaData( PPACKAGE* MetaData, BOOL Header )` -- } if ( Instance->Session.Connected ) { /* Enter tasking routine CommandDispatcher(); } /* Sleep for a while (with...
- `DemonInit` (function) `payloads/Demon/src/Demon.c:267` `VOID DemonInit( PVOID ModuleInst, PKAYN_ARGS KArgs )`
- `PUTS` (function) `payloads/Demon/src/Demon.c:290` `PUTS( "TRANSPORT_HTTP" )
#endif

#ifdef TRANSPORT_SMB
    PUTS( "TRANSPORT_SMB" )
#endif


    /*...` -- ifdef TRANSPORT_HTTP
- `PRINTF` (function) `payloads/Demon/src/Demon.c:570` `PRINTF( "Instance DemonID => %x\n", Instance->Session.AgentID )
}

VOID DemonConfig()`
- `PRINTF` (function) `payloads/Demon/src/Demon.c:645` `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...`
- `PRINTF` (function) `payloads/Demon/src/Demon.c:673` `PRINTF( " - %ls:%ld\n", Buffer, Temp )

        /* if our host address is longer than 0 then lets...`
- `PRINTF` (function) `payloads/Demon/src/Demon.c:775` `PRINTF( "KillDate: %d\n", Instance->Config.Transport.KillDate )
    // check if the kill date has...`

## payloads/Demon/src/asm/Spoof.x64.asm
- `Spoof` (function) `payloads/Demon/src/asm/Spoof.x64.asm:8`
- `fixup` (function) `payloads/Demon/src/asm/Spoof.x64.asm:22`

## payloads/Demon/src/core/CoffeeLdr.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/ObjectApi.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/Win32.h`, `payloads/Demon/include/inject/InjectUtil.h`
- `VehDebugger` (function) `payloads/Demon/src/core/CoffeeLdr.c:32` `LONG WINAPI VehDebugger( PEXCEPTION_POINTERS Exception )`
- `SymbolIncludesLibrary` (function) `payloads/Demon/src/core/CoffeeLdr.c:64` `BOOL SymbolIncludesLibrary( LPSTR Symbol )` -- check if the symbol is on the form: __imp_LIBNAME$FUNCNAME
- `SymbolIsImport` (function) `payloads/Demon/src/core/CoffeeLdr.c:81` `BOOL SymbolIsImport( LPSTR Symbol )`
- `CoffeeProcessSymbol` (function) `payloads/Demon/src/core/CoffeeLdr.c:87` `BOOL CoffeeProcessSymbol( PCOFFEE Coffee, LPSTR SymbolName, UINT16 SymbolType, PVOID* pFuncAddr )`
- `CoffeeFunction` (function) `payloads/Demon/src/core/CoffeeLdr.c:242` `VOID CoffeeFunction( PVOID Address, PVOID Argument, SIZE_T Size )` -- This is our function where we can control/get the return address of it to use it in case of a Veh exception
- `PUTS` (function) `payloads/Demon/src/core/CoffeeLdr.c:251` `PUTS( "Finished" )
}

BOOL CoffeeExecuteFunction( PCOFFEE Coffee, PCHAR Function, PVOID Argument,...`
- `CoffeeCleanup` (function) `payloads/Demon/src/core/CoffeeLdr.c:394` `VOID CoffeeCleanup( PCOFFEE Coffee )`
- `CoffeeProcessSections` (function) `payloads/Demon/src/core/CoffeeLdr.c:423` `BOOL CoffeeProcessSections( PCOFFEE Coffee )` -- Process sections relocation and symbols
- `CoffeeGetFunMapSize` (function) `payloads/Demon/src/core/CoffeeLdr.c:602` `SIZE_T CoffeeGetFunMapSize( PCOFFEE Coffee )` -- calculate how many __imp_* function there are
- `RemoveCoffeeFromInstance` (function) `payloads/Demon/src/core/CoffeeLdr.c:642` `VOID RemoveCoffeeFromInstance( PCOFFEE Coffee )`
- `PUTS` (function) `payloads/Demon/src/core/CoffeeLdr.c:669` `PUTS( "Coffe entry was not found" )
}

VOID CoffeeLdr( PCHAR EntryName, PVOID CoffeeData, PVOID A...`
- `PRINTF` (function) `payloads/Demon/src/core/CoffeeLdr.c:678` `PRINTF( "[EntryName: %s] [CoffeeData: %p] [ArgData: %p] [ArgSize: %ld]\n", EntryName, CoffeeData,...`
- `CoffeeRunnerThread` (function) `payloads/Demon/src/core/CoffeeLdr.c:799` `VOID CoffeeRunnerThread( PCOFFEE_PARAMS Param )`
- `CoffeeRunner` (function) `payloads/Demon/src/core/CoffeeLdr.c:821` `VOID CoffeeRunner( PCHAR EntryName, DWORD EntryNameSize, PVOID CoffeeData, SIZE_T CoffeeDataSize,...`

## payloads/Demon/src/core/Command.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/common/Macros.h`, `payloads/Demon/include/core/CoffeeLdr.h`, `payloads/Demon/include/core/Command.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/Download.h`, `payloads/Demon/include/core/Kerberos.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Package.h`, `payloads/Demon/include/core/SleepObf.h`, `payloads/Demon/include/core/Token.h`, `payloads/Demon/include/inject/Inject.h`
- `CommandDispatcher` (function) `payloads/Demon/src/core/Command.c:48` `VOID CommandDispatcher( VOID )` -- TODO: rewrite this part and move it into the Demon.c file
- `PRINTF` (function) `payloads/Demon/src/core/Command.c:107` `PRINTF( "Task => RequestID:[%d : %x] CommandID:[%d : %x] TaskBuffer:[%x : %d]\n", RequestID, Requ...`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:160` `PUTS( "Out of while loop" )
}

VOID CommandCheckin( PPARSER Parser )`
- `CommandSleep` (function) `payloads/Demon/src/core/Command.c:174` `VOID CommandSleep( PPARSER Parser )`
- `CommandJob` (function) `payloads/Demon/src/core/Command.c:188` `VOID CommandJob( PPARSER Parser )`
- `CommandProc` (function) `payloads/Demon/src/core/Command.c:263` `VOID CommandProc( PPARSER Parser )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:272` `case DEMON_COMMAND_PROC_MODULES: PUTS( "Proc::Modules" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:337` `case DEMON_COMMAND_PROC_GREP: PUTS("Proc::Grep")`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:423` `case DEMON_COMMAND_PROC_CREATE: PUTS( "Proc::Create" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:468` `case DEMON_COMMAND_PROC_MEMORY: PUTS( "Proc::Memory" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:528` `case DEMON_COMMAND_PROC_KILL: PUTS( "Proc::Kill" )`
- `CommandProcList` (function) `payloads/Demon/src/core/Command.c:562` `VOID CommandProcList(
    IN PPARSER Parser
)` -- ! get current list of running processes and sends it back to the server.
- `PACKAGE_ERROR_NTSTATUS` (function) `payloads/Demon/src/core/Command.c:671` `PACKAGE_ERROR_NTSTATUS( NtStatus )
    }
}

VOID CommandFS( PPARSER Parser )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:684` `case DEMON_COMMAND_FS_DIR: PUTS( "FS::Dir" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:794` `case DEMON_COMMAND_FS_DOWNLOAD: PUTS( "FS::Download" )`
- `PRINTF` (function) `payloads/Demon/src/core/Command.c:824` `PRINTF( "FilePath.Buffer[%d]: %ls\n", PathSize, FilePath )

            if ( ! Instance->Win32.Ge...`
- `Data` (function) `payloads/Demon/src/core/Command.c:844` `* * Data (Open): * [ File Size ] * [ File Name ] * * Data (Write) * [ Chunk Data ] Size + FileChunk * * Data...`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:867` `CleanupDownload:
            PUTS( "CleanupDownload" )

            if ( FileName.Buffer )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:882` `case DEMON_COMMAND_FS_UPLOAD: PUTS( "FS::Upload" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:949` `case DEMON_COMMAND_FS_CD: PUTS( "FS::Cd" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:964` `case DEMON_COMMAND_FS_REMOVE: PUTS( "FS::Remove" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:994` `case DEMON_COMMAND_FS_MKDIR: PUTS( "FS::Mkdir" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1010` `case DEMON_COMMAND_FS_COPY: PUTS( "FS::Copy" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1035` `case DEMON_COMMAND_FS_MOVE: PUTS( "FS::Move" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1060` `case DEMON_COMMAND_FS_GET_PWD: PUTS( "FS::GetPwd" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1075` `case DEMON_COMMAND_FS_CAT: PUTS( "FS::Cat" )`
- `CommandInlineExecute` (function) `payloads/Demon/src/core/Command.c:1114` `VOID CommandInlineExecute( PPARSER Parser )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1181` `PUTS( "Use default (from config) CoffeeLdr" )

            if ( Instance->Config.Implant.CoffeeTh...`
- `CommandInjectDLL` (function) `payloads/Demon/src/core/Command.c:1203` `VOID CommandInjectDLL( PPARSER Parser )`
- `CommandSpawnDLL` (function) `payloads/Demon/src/core/Command.c:1247` `VOID CommandSpawnDLL( PPARSER Parser )`
- `CommandInjectShellcode` (function) `payloads/Demon/src/core/Command.c:1266` `VOID CommandInjectShellcode(
    IN PPARSER Parser
)`
- `PRINTF` (function) `payloads/Demon/src/core/Command.c:1293` `PRINTF(
        "Injection Args:      \n"
        " - Way     : %d      \n"
        " - Method  :...`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1312` `case INJECT_WAY_SPAWN: PUTS( "INJECT_WAY_SPAWN" )`
- `PRINTF` (function) `payloads/Demon/src/core/Command.c:1320` `PRINTF( "Target spawn process: %ls\n", Spawn )

            /* create process */
            if (...`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1353` `case INJECT_WAY_INJECT: PUTS( "INJECT_WAY_INJECT" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1358` `case INJECT_WAY_EXECUTE: PUTS( "INJECT_WAY_EXECUTE" )`
- `CommandToken` (function) `payloads/Demon/src/core/Command.c:1373` `VOID CommandToken( PPARSER Parser )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1383` `case DEMON_COMMAND_TOKEN_IMPERSONATE: PUTS( "Token::Impersonate" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1406` `case DEMON_COMMAND_TOKEN_STEAL: PUTS( "Token::Steal" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1450` `case DEMON_COMMAND_TOKEN_LIST: PUTS( "Token::List" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1477` `case DEMON_COMMAND_TOKEN_PRIVSGET_OR_LIST: PUTS( "Token::PrivsGetOrList" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1532` `case DEMON_COMMAND_TOKEN_MAKE: PUTS( "Token::Make" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1595` `case DEMON_COMMAND_TOKEN_GET_UID: PUTS( "Token::GetUID" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1635` `case DEMON_COMMAND_TOKEN_REVERT: PUTS( "Token::Revert" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1650` `case DEMON_COMMAND_TOKEN_REMOVE: PUTS( "Token::Remove" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1660` `case DEMON_COMMAND_TOKEN_CLEAR: PUTS( "Token::Clear" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1668` `case DEMON_COMMAND_TOKEN_FIND_TOKENS: PUTS( "Token::Find" )`
- `CommandAssemblyInlineExecute` (function) `payloads/Demon/src/core/Command.c:1708` `VOID CommandAssemblyInlineExecute( PPARSER Parser )`
- `PRINTF` (function) `payloads/Demon/src/core/Command.c:1761` `PRINTF(
            "Parsed Arguments:         \n"
            " - PipeName     [%d]: %ls \n"
   ...`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1788` `PUTS( "Dotnet instance already running." )
    }
}

VOID CommandAssemblyListVersion( PPARSER Pars...`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:1841` `else
        PUTS("Failed to load mscoree.dll")


    if ( pClrMetaHost )`
- `CommandConfig` (function) `payloads/Demon/src/core/Command.c:1865` `VOID CommandConfig( PPARSER Parser )`
- `CommandScreenshot` (function) `payloads/Demon/src/core/Command.c:2084` `VOID CommandScreenshot( PPARSER Parser )`
- `CommandNet` (function) `payloads/Demon/src/core/Command.c:2109` `VOID CommandNet( PPARSER Parser )` -- TODO: The Net module is unstable so fix those issues to work on normal workstation and domain server
- `PUTS` (function) `payloads/Demon/src/core/Command.c:2350` `PUTS( "NetLocalGroupEnum => Success" )
                if ( GroupInfo )`
- `CommandPivot` (function) `payloads/Demon/src/core/Command.c:2463` `VOID CommandPivot( PPARSER Parser )`
- `CommandTransfer` (function) `payloads/Demon/src/core/Command.c:2608` `VOID CommandTransfer( PPARSER Parser )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:2624` `case DEMON_COMMAND_TRANSFER_LIST: PUTS( "Transfer::list" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:2641` `case DEMON_COMMAND_TRANSFER_STOP: PUTS( "Transfer::stop" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:2668` `case DEMON_COMMAND_TRANSFER_RESUME: PUTS( "Transfer::resume" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:2696` `case DEMON_COMMAND_TRANSFER_REMOVE: PUTS( "Transfer::remove" )`
- `CommandSocket` (function) `payloads/Demon/src/core/Command.c:2739` `VOID CommandSocket( PPARSER Parser )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:2751` `case SOCKET_COMMAND_RPORTFWD_ADD: PUTS( "Socket::RPortFwdAdd" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:2786` `case SOCKET_COMMAND_RPORTFWD_LIST: PUTS( "Socket::RPortFwdList" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:2819` `case SOCKET_COMMAND_RPORTFWD_REMOVE: PUTS( "Socket::RPortFwdRemove" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:2850` `case SOCKET_COMMAND_RPORTFWD_CLEAR: PUTS( "Socket::RPortFwdClear" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:2871` `case SOCKET_COMMAND_SOCKSPROXY_ADD: PUTS( "Socket::SocksProxyAdd" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:2878` `case SOCKET_COMMAND_WRITE: PUTS( "Socket::Write" )`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:2942` `case SOCKET_COMMAND_CONNECT: PUTS( "Socket::Connect" )`
- `PRINTF` (function) `payloads/Demon/src/core/Command.c:2997` `PRINTF( "Socket ID: %x\n", ScId )

            /* check if address is not 0 */
            if ( I...`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:3036` `case SOCKET_COMMAND_CLOSE: PUTS( "Socket::Close" )`
- `CommandKerberos` (function) `payloads/Demon/src/core/Command.c:3077` `VOID CommandKerberos(
    IN PPARSER Parser
)`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:3090` `case KERBEROS_COMMAND_LUID: PUTS("Kerberos::LUID")`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:3117` `case KERBEROS_COMMAND_KLIST: PUTS("Kerberos::Klist")`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:3205` `case KERBEROS_COMMAND_PURGE: PUTS("Kerberos::Purge")`
- `PUTS` (function) `payloads/Demon/src/core/Command.c:3216` `case KERBEROS_COMMAND_PTT: PUTS("Kerberos::Ptt")`
- `CommandMemFile` (function) `payloads/Demon/src/core/Command.c:3237` `VOID CommandMemFile( PPARSER Parser )`
- `InWorkingHours` (function) `payloads/Demon/src/core/Command.c:3263` `BOOL InWorkingHours( )`
- `ReachedKillDate` (function) `payloads/Demon/src/core/Command.c:3295` `BOOL ReachedKillDate()`
- `KillDate` (function) `payloads/Demon/src/core/Command.c:3300` `VOID KillDate( )`
- `CommandExit` (function) `payloads/Demon/src/core/Command.c:3315` `VOID CommandExit( PPARSER Parser )` -- TODO: rewrite this. disconnect all pivots. kill our threads. release memory and free itself.

## payloads/Demon/src/core/Dotnet.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/Dotnet.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/Runtime.h`
- `DotnetExecute` (function) `payloads/Demon/src/core/Dotnet.c:19` `BOOL DotnetExecute( BUFFER Assembly, BUFFER Arguments )`
- `PUTS` (function) `payloads/Demon/src/core/Dotnet.c:101` `PUTS( "Init HwBp Engine" )
        /* use global engine */
        if ( ! NT_SUCCESS( HwBpEngineI...`
- `PUTS` (function) `payloads/Demon/src/core/Dotnet.c:112` `PUTS( "HwBp Engine add AmsiScanBuffer bypass" )
            if ( ! NT_SUCCESS( Status = HwBpEngin...`
- `PUTS` (function) `payloads/Demon/src/core/Dotnet.c:120` `PUTS( "HwBp Engine add NtTraceEvent bypass" )
        if ( ! NT_SUCCESS( HwBpEngineAdd( NULL, Thr...` -- ThreadId = U_PTR( Instance->Teb->ClientId.UniqueThread ); /* add Amsi bypass if ( AmsiIsLoaded ) { PUTS( "HwBp...
- `PUTS` (function) `payloads/Demon/src/core/Dotnet.c:148` `PUTS( "CreateDomain..." )
    if ( ( Result = Instance->Dotnet->ICorRuntimeHost->lpVtbl->CreateDo...`
- `PUTS` (function) `payloads/Demon/src/core/Dotnet.c:154` `PUTS( "QueryInterface..." )
    if ( ( Result = Instance->Dotnet->AppDomainThunk->lpVtbl->QueryIn...`
- `PRINTF` (function) `payloads/Demon/src/core/Dotnet.c:169` `PRINTF("SafeArrayUnaccessData Failed: %x\n", Result )
        PACKAGE_ERROR_WIN32
    }

    PUTS...`
- `PUTS` (function) `payloads/Demon/src/core/Dotnet.c:179` `PUTS( "Assembly EntryPoint..." )
    if ( ( Result = Instance->Dotnet->Assembly->lpVtbl->EntryPoi...`
- `PUTS` (function) `payloads/Demon/src/core/Dotnet.c:237` `PUTS( "Creating events..." )
    if ( NT_SUCCESS( Instance->Win32.NtCreateEvent( &Instance->Dotne...`
- `PUTS` (function) `payloads/Demon/src/core/Dotnet.c:286` `PUTS( "Resume Thread..." )
                if ( NT_SUCCESS( Instance->Win32.NtAlertResumeThread( ...`
- `DotnetPushPipe` (function) `payloads/Demon/src/core/Dotnet.c:312` `VOID DotnetPushPipe()` -- } else PUTS( "NtAlertResumeThread failed" ) } else PUTS( "NtGetThreadContext failed" ) } else PUTS(...
- `DotnetPush` (function) `payloads/Demon/src/core/Dotnet.c:347` `VOID DotnetPush()`
- `PRINTF` (function) `payloads/Demon/src/core/Dotnet.c:352` `PRINTF( "Instance->Dotnet->Invoked: %s\n", Instance->Dotnet->Invoked ? "TRUE" : "FALSE" )
    if ...`
- `DotnetClose` (function) `payloads/Demon/src/core/Dotnet.c:379` `VOID DotnetClose()`
- `PUTS` (function) `payloads/Demon/src/core/Dotnet.c:428` `PUTS( "Free Output" )
    if ( Instance->Dotnet->Output.Buffer )`
- `PUTS` (function) `payloads/Demon/src/core/Dotnet.c:436` `PUTS( "Unload and free CLR" )
    if ( Instance->Dotnet->MethodArgs )`
- `FindVersion` (function) `payloads/Demon/src/core/Dotnet.c:501` `BOOL FindVersion( PVOID Assembly, DWORD length )`
- `ClrCreateInstance` (function) `payloads/Demon/src/core/Dotnet.c:524` `DWORD ClrCreateInstance( LPCWSTR dotNetVersion, PICLRMetaHost *ppClrMetaHost, PICLRRuntimeInfo *p...`

## payloads/Demon/src/core/Download.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/MiniStd.h`
- `DownloadAdd` (function) `payloads/Demon/src/core/Download.c:6` `PDOWNLOAD_DATA DownloadAdd( HANDLE hFile, LONGLONG MaxSize )` -- #include <Demon.h> #include <core/MiniStd.h> /* Add file to linked list with type (upload/download)
- `DownloadGet` (function) `payloads/Demon/src/core/Download.c:27` `PDOWNLOAD_DATA DownloadGet( DWORD FileID )` -- Download->Size      = MaxSize; Download->State     = DOWNLOAD_STATE_RUNNING; Download->Next      =...
- `DownloadFree` (function) `payloads/Demon/src/core/Download.c:41` `VOID DownloadFree( PDOWNLOAD_DATA Download )` -- PDOWNLOAD_DATA DownloadGet( DWORD FileID ) { PDOWNLOAD_DATA Download = NULL; for ( Download = Instance->Downloads...
- `DownloadRemove` (function) `payloads/Demon/src/core/Download.c:56` `BOOL DownloadRemove( DWORD FileID )`
- `DownloadPush` (function) `payloads/Demon/src/core/Download.c:94` `VOID DownloadPush()` -- /* return that we succeeded.
- `PRINTF` (function) `payloads/Demon/src/core/Download.c:129` `PRINTF( "Allocated memory for DownloadChunk. Buffer:[%p] Size:[%d]\n", Instance->DownloadChunk.Bu...`
- `MemFileIsNew` (function) `payloads/Demon/src/core/Download.c:238` `BOOL MemFileIsNew( ULONG32 ID )`
- `NewMemFile` (function) `payloads/Demon/src/core/Download.c:254` `PMEM_FILE NewMemFile( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )` -- PMEM_FILE MemFile = Instance->MemFiles; while ( MemFile ) { if ( MemFile->ID == ID ) return FALSE; MemFile =...
- `GetMemFile` (function) `payloads/Demon/src/core/Download.c:287` `PMEM_FILE GetMemFile( ULONG32 ID )`
- `ProcessMemFileChunk` (function) `payloads/Demon/src/core/Download.c:302` `PMEM_FILE ProcessMemFileChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
- `MemFileReadChunk` (function) `payloads/Demon/src/core/Download.c:318` `PMEM_FILE MemFileReadChunk( ULONG32 ID, SIZE_T Size, PVOID Data, ULONG32 ReadSize )`
- `MemFileFree` (function) `payloads/Demon/src/core/Download.c:339` `VOID MemFileFree( PMEM_FILE MemFile )`
- `RemoveMemFile` (function) `payloads/Demon/src/core/Download.c:355` `BOOL RemoveMemFile( ULONG32 ID )`

## payloads/Demon/src/core/HwBpEngine.c
Depends on: `payloads/Demon/include/Demon.h`, `payloads/Demon/include/core/HwBpEngine.h`, `payloads/Demon/include/core/HwBpExceptions.h`, `payloads/Demon/include/core/MiniStd.h`, `payloads/Demon/include/core/SysNative.h`
- `HwBpEngineInit` (function) `payloads/Demon/src/core/HwBpEngine.c:18` `NTSTATUS HwBpEngineInit(
    OUT PHWBP_ENGINE Engine,
    IN  PVOID        Handler
)` -- !
- `HwBpEngineSetBp` (function) `payloads/Demon/src/core/HwBpEngine.c:61` `NTSTATUS HwBpEngineSetBp(
    IN DWORD Tid,
    IN PVOID Address,
    IN BYTE  Position,
    IN B...` -- !
- `PRINTF` (function) `payloads/Demon/src/core/HwBpEngine.c:116` `PRINTF(
                "Dr Registers:  \n"
                "- Dr0[%d]: %p  \n"
                "...`
- `HwBpEngineAdd` (function) `payloads/Demon/src/core/HwBpEngine.c:152` `NTSTATUS HwBpEngineAdd(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID        ...` -- !
- `PRINTF` (function) `payloads/Demon/src/core/HwBpEngine.c:162` `PRINTF( "Engine:[%p] Tid:[%d] Address:[%p] Function:[%p] Position:[%d]\n", Engine, Tid, Address, ...`
- `HwBpEngineRemove` (function) `payloads/Demon/src/core/HwBpEngine.c:209` `NTSTATUS HwBpEngineRemove(
    IN PHWBP_ENGINE Engine,
    IN DWORD        Tid,
    IN PVOID     ...`
- `HwBpEngineDestroy` (function) `payloads/Demon/src/core/HwBpEngine.c:261` `NTSTATUS HwBpEngineDestroy(
    IN PHWBP_ENGINE Engine
)`
- `ExceptionHandler` (function) `payloads/Demon/src/core/HwBpEngine.c:320` `LONG ExceptionHandler(
    _Inout_ PEXCEPTION_POINTERS Exception
)` -- !
- `PRINTF` (function) `payloads/Demon/src/core/HwBpEngine.c:355` `PRINTF( "Found exception handler: %s\n", Found ? "TRUE" : "FALSE" )
        if ( Found )`


Next: [API_p4.md](API_p4.md)
