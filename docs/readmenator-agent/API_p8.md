# API (page 8 of 8)
Previous: [API_p7.md](API_p7.md)

## teamserver/pkg/profile/yaotl/json/parser.go
- `parseFileContent` (function) `teamserver/pkg/profile/yaotl/json/parser.go:11` `func parseFileContent(`
- `parseExpression` (function) `teamserver/pkg/profile/yaotl/json/parser.go:26` `func parseExpression(`
- `parseValue` (function) `teamserver/pkg/profile/yaotl/json/parser.go:41` `func parseValue(`
- `tokenCanStartValue` (function) `teamserver/pkg/profile/yaotl/json/parser.go:101` `func tokenCanStartValue(`
- `parseObject` (function) `teamserver/pkg/profile/yaotl/json/parser.go:110` `func parseObject(`
- `parseArray` (function) `teamserver/pkg/profile/yaotl/json/parser.go:261` `func parseArray(`
- `parseNumber` (function) `teamserver/pkg/profile/yaotl/json/parser.go:363` `func parseNumber(`
- `parseString` (function) `teamserver/pkg/profile/yaotl/json/parser.go:406` `func parseString(`
- `parseKeyword` (function) `teamserver/pkg/profile/yaotl/json/parser.go:461` `func parseKeyword(`

## teamserver/pkg/profile/yaotl/json/peeker.go
- `newPeeker` (function) `teamserver/pkg/profile/yaotl/json/peeker.go:8` `func newPeeker(`
- `Peek` (function) `teamserver/pkg/profile/yaotl/json/peeker.go:15` `func (p *peeker) Peek(`
- `Read` (function) `teamserver/pkg/profile/yaotl/json/peeker.go:19` `func (p *peeker) Read(`

## teamserver/pkg/profile/yaotl/json/public.go
- `Parse` (function) `teamserver/pkg/profile/yaotl/json/public.go:20` `func Parse(` -- Parse attempts to parse the given buffer as JSON and, if successful, returns a hcl.File for the HCL configuration...
- `ParseWithStartPos` (function) `teamserver/pkg/profile/yaotl/json/public.go:29` `func ParseWithStartPos(` -- ParseWithStartPos attempts to parse like json.Parse, but unlike json.Parse you can pass a start position of the...
- `ParseExpression` (function) `teamserver/pkg/profile/yaotl/json/public.go:76` `func ParseExpression(` -- ParseExpression parses the given buffer as a standalone JSON expression, returning it as an instance of Expression.
- `ParseExpressionWithStartPos` (function) `teamserver/pkg/profile/yaotl/json/public.go:83` `func ParseExpressionWithStartPos(` -- ParseExpressionWithStartPos parses like json.ParseExpression, but unlike json.ParseExpression you can pass a start...
- `ParseFile` (function) `teamserver/pkg/profile/yaotl/json/public.go:92` `func ParseFile(` -- ParseFile is a convenience wrapper around Parse that first attempts to load data from the given filename, passing...

## teamserver/pkg/profile/yaotl/json/scanner.go
- `scan` (function) `teamserver/pkg/profile/yaotl/json/scanner.go:41` `func scan(` -- scan returns the primary tokens for the given JSON buffer in sequence.
- `byteCanStartNumber` (function) `teamserver/pkg/profile/yaotl/json/scanner.go:124` `func byteCanStartNumber(`
- `scanNumber` (function) `teamserver/pkg/profile/yaotl/json/scanner.go:138` `func scanNumber(`
- `byteCanStartKeyword` (function) `teamserver/pkg/profile/yaotl/json/scanner.go:157` `func byteCanStartKeyword(`
- `scanKeyword` (function) `teamserver/pkg/profile/yaotl/json/scanner.go:172` `func scanKeyword(`
- `scanString` (function) `teamserver/pkg/profile/yaotl/json/scanner.go:189` `func scanString(`
- `skipWhitespace` (function) `teamserver/pkg/profile/yaotl/json/scanner.go:241` `func skipWhitespace(`
- `Range` (function) `teamserver/pkg/profile/yaotl/json/scanner.go:280` `func (p *pos) Range(`
- `posRange` (function) `teamserver/pkg/profile/yaotl/json/scanner.go:292` `func posRange(`
- `GoString` (function) `teamserver/pkg/profile/yaotl/json/scanner.go:300` `func (t token) GoString(`
- `isAlphabetical` (function) `teamserver/pkg/profile/yaotl/json/scanner.go:304` `func isAlphabetical(`

## teamserver/pkg/profile/yaotl/json/structure.go
- `Content` (function) `teamserver/pkg/profile/yaotl/json/structure.go:29` `func (b *body) Content(`
- `PartialContent` (function) `teamserver/pkg/profile/yaotl/json/structure.go:77` `func (b *body) PartialContent(`
- `JustAttributes` (function) `teamserver/pkg/profile/yaotl/json/structure.go:169` `func (b *body) JustAttributes(` -- JustAttributes for JSON bodies interprets all properties of the wrapped JSON object as attributes and returns them.
- `MissingItemRange` (function) `teamserver/pkg/profile/yaotl/json/structure.go:219` `func (b *body) MissingItemRange(`
- `unpackBlock` (function) `teamserver/pkg/profile/yaotl/json/structure.go:232` `func (b *body) unpackBlock(`
- `collectDeepAttrs` (function) `teamserver/pkg/profile/yaotl/json/structure.go:325` `func (b *body) collectDeepAttrs(` -- collectDeepAttrs takes either a single object or an array of objects and flattens it into a list of object...
- `Value` (function) `teamserver/pkg/profile/yaotl/json/structure.go:381` `func (e *expression) Value(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/json/structure.go:513` `func (e *expression) Variables(`
- `Range` (function) `teamserver/pkg/profile/yaotl/json/structure.go:557` `func (e *expression) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/json/structure.go:561` `func (e *expression) StartRange(`
- `AsTraversal` (function) `teamserver/pkg/profile/yaotl/json/structure.go:566` `func (e *expression) AsTraversal(` -- Implementation for hcl.AbsTraversalForExpr.
- `ExprCall` (function) `teamserver/pkg/profile/yaotl/json/structure.go:583` `func (e *expression) ExprCall(` -- Implementation for hcl.ExprCall.
- `ExprList` (function) `teamserver/pkg/profile/yaotl/json/structure.go:606` `func (e *expression) ExprList(` -- Implementation for hcl.ExprList.
- `ExprMap` (function) `teamserver/pkg/profile/yaotl/json/structure.go:620` `func (e *expression) ExprMap(` -- Implementation for hcl.ExprMap.

## teamserver/pkg/profile/yaotl/json/tokentype_string.go
- `String` (function) `teamserver/pkg/profile/yaotl/json/tokentype_string.go:24` `func (i tokenType) String(`

## teamserver/pkg/profile/yaotl/merged.go
- `MergeFiles` (function) `teamserver/pkg/profile/yaotl/merged.go:15` `func MergeFiles(` -- MergeFiles combines the given files to produce a single body that contains configuration from all of the given files.
- `MergeBodies` (function) `teamserver/pkg/profile/yaotl/merged.go:25` `func MergeBodies(` -- MergeBodies is like MergeFiles except it deals directly with bodies, rather than with entire files.
- `EmptyBody` (function) `teamserver/pkg/profile/yaotl/merged.go:71` `func EmptyBody(` -- EmptyBody returns a body with no content.
- `Content` (function) `teamserver/pkg/profile/yaotl/merged.go:85` `func (mb mergedBodies) Content(` -- Content returns the content produced by applying the given schema to all of the merged bodies and merging the result.
- `PartialContent` (function) `teamserver/pkg/profile/yaotl/merged.go:92` `func (mb mergedBodies) PartialContent(`
- `JustAttributes` (function) `teamserver/pkg/profile/yaotl/merged.go:96` `func (mb mergedBodies) JustAttributes(`
- `MissingItemRange` (function) `teamserver/pkg/profile/yaotl/merged.go:130` `func (mb mergedBodies) MissingItemRange(`
- `mergedContent` (function) `teamserver/pkg/profile/yaotl/merged.go:142` `func (mb mergedBodies) mergedContent(`

## teamserver/pkg/profile/yaotl/ops.go
- `Index` (function) `teamserver/pkg/profile/yaotl/ops.go:23` `func Index(` -- Index is a helper function that performs the same operation as the index operator in the HCL expression language.
- `GetAttr` (function) `teamserver/pkg/profile/yaotl/ops.go:262` `func GetAttr(` -- GetAttr is a helper function that performs the same operation as the attribute access in the HCL expression language.
- `ApplyPath` (function) `teamserver/pkg/profile/yaotl/ops.go:404` `func ApplyPath(` -- ApplyPath is a helper function that applies a cty.Path to a value using the indexing and attribute access operations...

## teamserver/pkg/profile/yaotl/pos.go
- `RangeBetween` (function) `teamserver/pkg/profile/yaotl/pos.go:58` `func RangeBetween(` -- RangeBetween returns a new range that spans from the beginning of the start range to the end of the end range.
- `RangeOver` (function) `teamserver/pkg/profile/yaotl/pos.go:74` `func RangeOver(` -- RangeOver returns a new range that covers both of the given ranges and possibly additional content between them if...
- `ContainsPos` (function) `teamserver/pkg/profile/yaotl/pos.go:106` `func (r Range) ContainsPos(` -- ContainsPos returns true if and only if the given position is contained within the receiving range.
- `ContainsOffset` (function) `teamserver/pkg/profile/yaotl/pos.go:112` `func (r Range) ContainsOffset(` -- ContainsOffset returns true if and only if the given byte offset is within the receiving Range.
- `Ptr` (function) `teamserver/pkg/profile/yaotl/pos.go:120` `func (r Range) Ptr(` -- Ptr returns a pointer to a copy of the receiver.
- `String` (function) `teamserver/pkg/profile/yaotl/pos.go:127` `func (r Range) String(` -- String returns a compact string representation of the receiver.
- `Empty` (function) `teamserver/pkg/profile/yaotl/pos.go:145` `func (r Range) Empty(`
- `CanSliceBytes` (function) `teamserver/pkg/profile/yaotl/pos.go:155` `func (r Range) CanSliceBytes(` -- CanSliceBytes returns true if SliceBytes could return an accurate sub-slice of the given slice.
- `SliceBytes` (function) `teamserver/pkg/profile/yaotl/pos.go:176` `func (r Range) SliceBytes(` -- SliceBytes returns a sub-slice of the given slice that is covered by the receiving range, assuming that the given...
- `Overlaps` (function) `teamserver/pkg/profile/yaotl/pos.go:197` `func (r Range) Overlaps(` -- Overlaps returns true if the receiver and the other given range share any characters in common.
- `Overlap` (function) `teamserver/pkg/profile/yaotl/pos.go:219` `func (r Range) Overlap(` -- Overlap finds a range that is either identical to or a sub-range of both the receiver and the other given range.
- `PartitionAround` (function) `teamserver/pkg/profile/yaotl/pos.go:257` `func (r Range) PartitionAround(` -- PartitionAround finds the portion of the given range that overlaps with the receiver and returns three ranges: the...

## teamserver/pkg/profile/yaotl/pos_scanner.go
- `NewRangeScanner` (function) `teamserver/pkg/profile/yaotl/pos_scanner.go:41` `func NewRangeScanner(` -- NewRangeScanner creates a new RangeScanner for the given buffer, producing ranges for the given filename.
- `NewRangeScannerFragment` (function) `teamserver/pkg/profile/yaotl/pos_scanner.go:49` `func NewRangeScannerFragment(` -- NewRangeScannerFragment is like NewRangeScanner but the ranges it produces will be offset by the given starting...
- `Scan` (function) `teamserver/pkg/profile/yaotl/pos_scanner.go:58` `func (sc *RangeScanner) Scan(`
- `Range` (function) `teamserver/pkg/profile/yaotl/pos_scanner.go:138` `func (sc *RangeScanner) Range(` -- Range returns a range that covers the latest token obtained after a call to Scan returns true.
- `Bytes` (function) `teamserver/pkg/profile/yaotl/pos_scanner.go:144` `func (sc *RangeScanner) Bytes(` -- Bytes returns the slice of the input buffer that is covered by the range that would be returned by Range.
- `Err` (function) `teamserver/pkg/profile/yaotl/pos_scanner.go:150` `func (sc *RangeScanner) Err(` -- Err can be called after Scan returns false to determine if the latest read resulted in an error, and obtain that...

## teamserver/pkg/profile/yaotl/static_expr.go
- `StaticExpr` (function) `teamserver/pkg/profile/yaotl/static_expr.go:22` `func StaticExpr(` -- StaticExpr returns an Expression that always evaluates to the given value.
- `Value` (function) `teamserver/pkg/profile/yaotl/static_expr.go:26` `func (e staticExpr) Value(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/static_expr.go:30` `func (e staticExpr) Variables(`
- `Range` (function) `teamserver/pkg/profile/yaotl/static_expr.go:34` `func (e staticExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/static_expr.go:38` `func (e staticExpr) StartRange(`

## teamserver/pkg/profile/yaotl/structure.go
- `OfType` (function) `teamserver/pkg/profile/yaotl/structure.go:129` `func (els Blocks) OfType(` -- OfType filters the receiving block sequence by block type name, returning a new block sequence including only the...
- `ByType` (function) `teamserver/pkg/profile/yaotl/structure.go:141` `func (els Blocks) ByType(` -- ByType transforms the receiving block sequence into a map from type name to block sequences of only that type.

## teamserver/pkg/profile/yaotl/structure_at_pos.go
- `BlocksAtPos` (function) `teamserver/pkg/profile/yaotl/structure_at_pos.go:25` `func (f *File) BlocksAtPos(` -- BlocksAtPos attempts to find all of the blocks that contain the given position, ordered so that the outermost block...
- `OutermostBlockAtPos` (function) `teamserver/pkg/profile/yaotl/structure_at_pos.go:44` `func (f *File) OutermostBlockAtPos(` -- OutermostBlockAtPos attempts to find a top-level block in the receiving file that contains the given position.
- `InnermostBlockAtPos` (function) `teamserver/pkg/profile/yaotl/structure_at_pos.go:64` `func (f *File) InnermostBlockAtPos(` -- InnermostBlockAtPos attempts to find the most deeply-nested block in the receiving file that contains the given...
- `OutermostExprAtPos` (function) `teamserver/pkg/profile/yaotl/structure_at_pos.go:86` `func (f *File) OutermostExprAtPos(` -- OutermostExprAtPos attempts to find an expression in the receiving file that contains the given position.
- `AttributeAtPos` (function) `teamserver/pkg/profile/yaotl/structure_at_pos.go:105` `func (f *File) AttributeAtPos(` -- AttributeAtPos attempts to find an attribute definition in the receiving file that contains the given position.

## teamserver/pkg/profile/yaotl/traversal.go
- `TraversalJoin` (function) `teamserver/pkg/profile/yaotl/traversal.go:24` `func TraversalJoin(` -- TraversalJoin appends a relative traversal to an absolute traversal to produce a new absolute traversal.
- `TraverseRel` (function) `teamserver/pkg/profile/yaotl/traversal.go:41` `func (t Traversal) TraverseRel(` -- TraverseRel applies the receiving traversal to the given value, returning the resulting value.
- `TraverseAbs` (function) `teamserver/pkg/profile/yaotl/traversal.go:62` `func (t Traversal) TraverseAbs(` -- TraverseAbs applies the receiving traversal to the given eval context, returning the resulting value.
- `IsRelative` (function) `teamserver/pkg/profile/yaotl/traversal.go:122` `func (t Traversal) IsRelative(` -- IsRelative returns true if the receiver is a relative traversal, or false otherwise.
- `SimpleSplit` (function) `teamserver/pkg/profile/yaotl/traversal.go:139` `func (t Traversal) SimpleSplit(` -- SimpleSplit returns a TraversalSplit where the name lookup is the absolute part and the remainder is the relative part.
- `RootName` (function) `teamserver/pkg/profile/yaotl/traversal.go:151` `func (t Traversal) RootName(` -- RootName returns the root name for a absolute traversal.
- `SourceRange` (function) `teamserver/pkg/profile/yaotl/traversal.go:160` `func (t Traversal) SourceRange(` -- SourceRange returns the source range for the traversal.
- `TraverseAbs` (function) `teamserver/pkg/profile/yaotl/traversal.go:184` `func (t TraversalSplit) TraverseAbs(` -- TraverseAbs traverses from a scope to the value resulting from the absolute traversal.
- `TraverseRel` (function) `teamserver/pkg/profile/yaotl/traversal.go:190` `func (t TraversalSplit) TraverseRel(` -- TraverseRel traverses from a given value, assumed to be the result of TraverseAbs on some scope, to a final result...
- `Traverse` (function) `teamserver/pkg/profile/yaotl/traversal.go:196` `func (t TraversalSplit) Traverse(` -- Traverse is a convenience function to apply TraverseAbs followed by TraverseRel.
- `Join` (function) `teamserver/pkg/profile/yaotl/traversal.go:208` `func (t TraversalSplit) Join(` -- Join concatenates together the Abs and Rel parts to produce a single absolute traversal.
- `RootName` (function) `teamserver/pkg/profile/yaotl/traversal.go:213` `func (t TraversalSplit) RootName(` -- RootName returns the root name for the absolute part of the split.
- `isTraverserSigil` (function) `teamserver/pkg/profile/yaotl/traversal.go:228` `func (tr isTraverser) isTraverserSigil(`
- `TraversalStep` (function) `teamserver/pkg/profile/yaotl/traversal.go:242` `func (tn TraverseRoot) TraversalStep(` -- TraversalStep on a TraverseName immediately panics, because absolute traversals cannot be directly traversed.
- `SourceRange` (function) `teamserver/pkg/profile/yaotl/traversal.go:246` `func (tn TraverseRoot) SourceRange(`
- `TraversalStep` (function) `teamserver/pkg/profile/yaotl/traversal.go:257` `func (tn TraverseAttr) TraversalStep(`
- `SourceRange` (function) `teamserver/pkg/profile/yaotl/traversal.go:261` `func (tn TraverseAttr) SourceRange(`
- `TraversalStep` (function) `teamserver/pkg/profile/yaotl/traversal.go:272` `func (tn TraverseIndex) TraversalStep(`
- `SourceRange` (function) `teamserver/pkg/profile/yaotl/traversal.go:276` `func (tn TraverseIndex) SourceRange(`
- `TraversalStep` (function) `teamserver/pkg/profile/yaotl/traversal.go:287` `func (tn TraverseSplat) TraversalStep(`
- `SourceRange` (function) `teamserver/pkg/profile/yaotl/traversal.go:291` `func (tn TraverseSplat) SourceRange(`

## teamserver/pkg/profile/yaotl/traversal_for_expr.go
- `AbsTraversalForExpr` (function) `teamserver/pkg/profile/yaotl/traversal_for_expr.go:20` `func AbsTraversalForExpr(` -- A particular Expression implementation can support this function by offering a method called AsTraversal that takes...
- `RelTraversalForExpr` (function) `teamserver/pkg/profile/yaotl/traversal_for_expr.go:52` `func RelTraversalForExpr(` -- RelTraversalForExpr is similar to AbsTraversalForExpr but it returns a relative traversal instead.
- `ExprAsKeyword` (function) `teamserver/pkg/profile/yaotl/traversal_for_expr.go:108` `func ExprAsKeyword(` -- The above approach will generate the same message for both the use of an unrecognized keyword and for not using a...

## teamserver/pkg/service/agent.go
Depends on: `teamserver/pkg/logger/logger.go`, `teamserver/pkg/utils/utils.go`
- `NewAgentService` (function) `teamserver/pkg/service/agent.go:45` `func NewAgentService(`
- `Json` (function) `teamserver/pkg/service/agent.go:58` `func (a *AgentService) Json(`
- `SendTask` (function) `teamserver/pkg/service/agent.go:67` `func (a *AgentService) SendTask(`
- `SendResponse` (function) `teamserver/pkg/service/agent.go:87` `func (a *AgentService) SendResponse(`
- `SendAgentBuildRequest` (function) `teamserver/pkg/service/agent.go:140` `func (a *AgentService) SendAgentBuildRequest(`

## teamserver/pkg/service/listener.go
Depends on: `teamserver/pkg/logger/logger.go`
- `Start` (function) `teamserver/pkg/service/listener.go:17` `func (l *ListenerService) Start(`
- `Json` (function) `teamserver/pkg/service/listener.go:37` `func (l *ListenerService) Json(`

## teamserver/pkg/service/service.go
Depends on: `teamserver/pkg/colors/colors.go`, `teamserver/pkg/events/events.go`, `teamserver/pkg/logger/logger.go`, `teamserver/pkg/logr/logr.go`
- `NewService` (function) `teamserver/pkg/service/service.go:27` `func NewService(`
- `Start` (function) `teamserver/pkg/service/service.go:35` `func (s *Service) Start(`
- `handleConnection` (function) `teamserver/pkg/service/service.go:50` `func (s *Service) handleConnection(`
- `authenticate` (function) `teamserver/pkg/service/service.go:75` `func (s *Service) authenticate(`
- `routine` (function) `teamserver/pkg/service/service.go:144` `func (s *Service) routine(` -- the main service routine
- `dispatch` (function) `teamserver/pkg/service/service.go:166` `func (s *Service) dispatch(`
- `AgentExist` (function) `teamserver/pkg/service/service.go:703` `func (s *Service) AgentExist(`
- `ClientClose` (function) `teamserver/pkg/service/service.go:713` `func (s *Service) ClientClose(`
- `ListenerExist` (function) `teamserver/pkg/service/service.go:763` `func (s *Service) ListenerExist(`
- `ListenerAdd` (function) `teamserver/pkg/service/service.go:775` `func (s *Service) ListenerAdd(`

## teamserver/pkg/service/types.go
Depends on: `teamserver/pkg/profile/profile.go`
- `WriteJson` (function) `teamserver/pkg/service/types.go:69` `func (c *ClientService) WriteJson(`

## teamserver/pkg/socks/socks.go
Imported by: `teamserver/pkg/agent/demons.go`, `teamserver/pkg/agent/types.go`
- `NewSocks` (function) `teamserver/pkg/socks/socks.go:17` `func NewSocks(`
- `SetHandler` (function) `teamserver/pkg/socks/socks.go:29` `func (s *Socks) SetHandler(`
- `Start` (function) `teamserver/pkg/socks/socks.go:35` `func (s *Socks) Start(`
- `Close` (function) `teamserver/pkg/socks/socks.go:62` `func (s *Socks) Close(`

## teamserver/pkg/socks/util.go
Depends on: `teamserver/pkg/logger/logger.go`
- `SubNegotiationClient` (function) `teamserver/pkg/socks/util.go:70` `func SubNegotiationClient(`
- `ReadSocksHeader` (function) `teamserver/pkg/socks/util.go:114` `func ReadSocksHeader(`
- `CreateResponsePackage` (function) `teamserver/pkg/socks/util.go:239` `func CreateResponsePackage(`
- `SendConnectSuccess` (function) `teamserver/pkg/socks/util.go:255` `func SendConnectSuccess(`
- `SendAddressTypeNotSupported` (function) `teamserver/pkg/socks/util.go:260` `func SendAddressTypeNotSupported(`
- `SendCommandNotSupported` (function) `teamserver/pkg/socks/util.go:265` `func SendCommandNotSupported(`
- `SendConnectFailure` (function) `teamserver/pkg/socks/util.go:270` `func SendConnectFailure(`

## teamserver/pkg/utils/utils.go
Depends on: `teamserver/pkg/logger/logger.go`
Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/pkg/agent/demons.go`, `teamserver/pkg/common/builder/builder.go`, `teamserver/pkg/service/agent.go`
- `UTF16BytesToString` (function) `teamserver/pkg/utils/utils.go:25` `func UTF16BytesToString(`
- `GenerateID` (function) `teamserver/pkg/utils/utils.go:34` `func GenerateID(`
- `GenerateString` (function) `teamserver/pkg/utils/utils.go:53` `func GenerateString(`
- `EncodeCommand` (function) `teamserver/pkg/utils/utils.go:65` `func EncodeCommand(`
- `IP2Inet` (function) `teamserver/pkg/utils/utils.go:70` `func IP2Inet(`
- `Port2Htons` (function) `teamserver/pkg/utils/utils.go:84` `func Port2Htons(`
- `ByteCountSI` (function) `teamserver/pkg/utils/utils.go:90` `func ByteCountSI(`
- `GetTeamserverPath` (function) `teamserver/pkg/utils/utils.go:104` `func GetTeamserverPath(`
- `IntToHexString` (function) `teamserver/pkg/utils/utils.go:131` `func IntToHexString(`
- `HexIntToString` (function) `teamserver/pkg/utils/utils.go:135` `func HexIntToString(`
- `HexIntToBigEndian` (function) `teamserver/pkg/utils/utils.go:141` `func HexIntToBigEndian(`

## teamserver/pkg/webhook/webhook.go
Depends on: `teamserver/pkg/handlers/http.go`
Imported by: `teamserver/cmd/server/teamserver.go`, `teamserver/cmd/server/types.go`
- `StringPtr` (function) `teamserver/pkg/webhook/webhook.go:20` `func StringPtr(`
- `BoolPtr` (function) `teamserver/pkg/webhook/webhook.go:24` `func BoolPtr(`
- `NewWebHook` (function) `teamserver/pkg/webhook/webhook.go:28` `func NewWebHook(`
- `NewAgent` (function) `teamserver/pkg/webhook/webhook.go:32` `func (w *WebHook) NewAgent(`
- `SetDiscord` (function) `teamserver/pkg/webhook/webhook.go:134` `func (w *WebHook) SetDiscord(`

## teamserver/pkg/win32/types.go
- `StatusToString` (function) `teamserver/pkg/win32/types.go:78` `func StatusToString(`

