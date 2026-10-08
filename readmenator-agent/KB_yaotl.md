# Subsystem: yaotl

## teamserver/pkg/profile/yaotl/diagnostic.go
- Doc: Diagnostic: Diagnostic represents information to be presented to a user about an error or...
- Layer: utility
- Language: go
- Symbols:
  - `Error` (function, line 76) `func (d *Diagnostic) Error(`
  - `Error` (function, line 82) `func (d Diagnostics) Error(`
  - `Append` (function, line 104) `func (d Diagnostics) Append(`
  - `Extend` (function, line 113) `func (d Diagnostics) Extend(`
  - `HasErrors` (function, line 119) `func (d Diagnostics) HasErrors(`
  - `Errs` (function, line 128) `func (d Diagnostics) Errs(`
  - `Diagnostic` (struct, line 26)
  - `DiagnosticWriter` (interface, line 140)

## teamserver/pkg/profile/yaotl/diagnostic_text.go
- Doc: NewDiagnosticTextWriter: NewDiagnosticTextWriter creates a DiagnosticWriter that writes...
- Layer: utility
- Language: go
- Symbols:
  - `NewDiagnosticTextWriter` (function, line 34) `func NewDiagnosticTextWriter(`
  - `WriteDiagnostic` (function, line 43) `func (w *diagnosticTextWriter) WriteDiagnostic(`
  - `WriteDiagnostics` (function, line 208) `func (w *diagnosticTextWriter) WriteDiagnostics(`
  - `traversalStr` (function, line 218) `func (w *diagnosticTextWriter) traversalStr(`
  - `valueStr` (function, line 246) `func (w *diagnosticTextWriter) valueStr(`
  - `contextString` (function, line 302) `func contextString(`
  - `diagnosticTextWriter` (struct, line 15)

## teamserver/pkg/profile/yaotl/didyoumean.go
- Doc: nameSuggestion: nameSuggestion tries to find a name from the given slice of suggested names that...
- Layer: utility
- Language: go
- Symbols:
  - `nameSuggestion` (function, line 16) `func nameSuggestion(`

## teamserver/pkg/profile/yaotl/doc.go
- Doc: Package hcl contains the main modelling types and general utility functions for HCL.
- Layer: utility
- Language: go
- Depends on: `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go`

## teamserver/pkg/profile/yaotl/eval_context.go
- Doc: EvalContext: An EvalContext provides the variables and functions that should be used to evaluate...
- Layer: utility
- Language: go
- Symbols:
  - `NewChild` (function, line 17) `func (ctx *EvalContext) NewChild(`
  - `Parent` (function, line 23) `func (ctx *EvalContext) Parent(`
  - `EvalContext` (struct, line 10)

## teamserver/pkg/profile/yaotl/expr_call.go
- Doc: StaticCall: StaticCall represents a function call that was extracted statically from an...
- Layer: utility
- Language: go
- Symbols:
  - `ExprCall` (function, line 14) `func ExprCall(`
  - `StaticCall` (struct, line 41)

## teamserver/pkg/profile/yaotl/expr_list.go
- Doc: ExprList: ExprList tests if the given expression is a static list construct and, if so, extracts...
- Layer: utility
- Language: go
- Symbols:
  - `ExprList` (function, line 14) `func ExprList(`

## teamserver/pkg/profile/yaotl/expr_map.go
- Doc: KeyValuePair: KeyValuePair represents a pair of expressions that serve as a single item within a...
- Layer: utility
- Language: go
- Symbols:
  - `ExprMap` (function, line 14) `func ExprMap(`
  - `KeyValuePair` (struct, line 41)

## teamserver/pkg/profile/yaotl/expr_unwrap.go
- Doc: UnwrapExpression: type-assert on the physical AST types used by the underlying syntax.
- Layer: utility
- Language: go
- Symbols:
  - `UnwrapExpression` (function, line 28) `func UnwrapExpression(`
  - `UnwrapExpressionUntil` (function, line 54) `func UnwrapExpressionUntil(`
  - `unwrapExpression` (interface, line 3)

## teamserver/pkg/profile/yaotl/merged.go
- Doc: MergeFiles: MergeFiles combines the given files to produce a single body that contains...
- Layer: utility
- Language: go
- Symbols:
  - `MergeFiles` (function, line 15) `func MergeFiles(`
  - `MergeBodies` (function, line 25) `func MergeBodies(`
  - `EmptyBody` (function, line 71) `func EmptyBody(`
  - `Content` (function, line 85) `func (mb mergedBodies) Content(`
  - `PartialContent` (function, line 92) `func (mb mergedBodies) PartialContent(`
  - `JustAttributes` (function, line 96) `func (mb mergedBodies) JustAttributes(`
  - `MissingItemRange` (function, line 130) `func (mb mergedBodies) MissingItemRange(`
  - `mergedContent` (function, line 142) `func (mb mergedBodies) mergedContent(`

## teamserver/pkg/profile/yaotl/ops.go
- Doc: Index: Index is a helper function that performs the same operation as the index operator in the...
- Layer: utility
- Language: go
- Symbols:
  - `Index` (function, line 23) `func Index(`
  - `GetAttr` (function, line 262) `func GetAttr(`
  - `ApplyPath` (function, line 404) `func ApplyPath(`

## teamserver/pkg/profile/yaotl/pos.go
- Doc: Pos: Pos represents a single position in a source file, by addressing the start byte of a...
- Layer: utility
- Language: go
- Symbols:
  - `RangeBetween` (function, line 58) `func RangeBetween(`
  - `RangeOver` (function, line 74) `func RangeOver(`
  - `ContainsPos` (function, line 106) `func (r Range) ContainsPos(`
  - `ContainsOffset` (function, line 112) `func (r Range) ContainsOffset(`
  - `Ptr` (function, line 120) `func (r Range) Ptr(`
  - `String` (function, line 127) `func (r Range) String(`
  - `Empty` (function, line 145) `func (r Range) Empty(`
  - `CanSliceBytes` (function, line 155) `func (r Range) CanSliceBytes(`
  - `SliceBytes` (function, line 176) `func (r Range) SliceBytes(`
  - `Overlaps` (function, line 197) `func (r Range) Overlaps(`
  - `Overlap` (function, line 219) `func (r Range) Overlap(`
  - `PartitionAround` (function, line 257) `func (r Range) PartitionAround(`
  - `Pos` (struct, line 10)
  - `Range` (struct, line 43)

## teamserver/pkg/profile/yaotl/pos_scanner.go
- Doc: RangeScanner: RangeScanner is a helper that will scan over a buffer using a bufio.SplitFunc and...
- Layer: utility
- Language: go
- Symbols:
  - `NewRangeScanner` (function, line 41) `func NewRangeScanner(`
  - `NewRangeScannerFragment` (function, line 49) `func NewRangeScannerFragment(`
  - `Scan` (function, line 58) `func (sc *RangeScanner) Scan(`
  - `Range` (function, line 138) `func (sc *RangeScanner) Range(`
  - `Bytes` (function, line 144) `func (sc *RangeScanner) Bytes(`
  - `Err` (function, line 150) `func (sc *RangeScanner) Err(`
  - `RangeScanner` (struct, line 21)

## teamserver/pkg/profile/yaotl/schema.go
- Doc: BlockHeaderSchema: BlockHeaderSchema represents the shape of a block header, and is used for...
- Layer: utility
- Language: go
- Symbols:
  - `BlockHeaderSchema` (struct, line 5)
  - `AttributeSchema` (struct, line 12)
  - `BodySchema` (struct, line 18)

## teamserver/pkg/profile/yaotl/static_expr.go
- Doc: StaticExpr: StaticExpr returns an Expression that always evaluates to the given value.
- Layer: utility
- Language: go
- Symbols:
  - `StaticExpr` (function, line 22) `func StaticExpr(`
  - `Value` (function, line 26) `func (e staticExpr) Value(`
  - `Variables` (function, line 30) `func (e staticExpr) Variables(`
  - `Range` (function, line 34) `func (e staticExpr) Range(`
  - `StartRange` (function, line 38) `func (e staticExpr) StartRange(`
  - `staticExpr` (struct, line 7)

## teamserver/pkg/profile/yaotl/structure.go
- Doc: File: File is the top-level node that results from parsing a HCL file.
- Layer: utility
- Language: go
- Symbols:
  - `OfType` (function, line 129) `func (els Blocks) OfType(`
  - `ByType` (function, line 141) `func (els Blocks) ByType(`
  - `File` (struct, line 8)
  - `Block` (struct, line 19)
  - `Body` (interface, line 41)
  - `BodyContent` (struct, line 77)
  - `Attribute` (struct, line 85)
  - `Expression` (interface, line 95)

## teamserver/pkg/profile/yaotl/structure_at_pos.go
- Doc: BlocksAtPos: BlocksAtPos attempts to find all of the blocks that contain the given position...
- Layer: utility
- Language: go
- Symbols:
  - `BlocksAtPos` (function, line 25) `func (f *File) BlocksAtPos(`
  - `OutermostBlockAtPos` (function, line 44) `func (f *File) OutermostBlockAtPos(`
  - `InnermostBlockAtPos` (function, line 64) `func (f *File) InnermostBlockAtPos(`
  - `OutermostExprAtPos` (function, line 86) `func (f *File) OutermostExprAtPos(`
  - `AttributeAtPos` (function, line 105) `func (f *File) AttributeAtPos(`

## teamserver/pkg/profile/yaotl/traversal.go
- Doc: TraversalSplit: TraversalSplit represents a pair of traversals, the first of which is an...
- Layer: utility
- Language: go
- Symbols:
  - `TraversalJoin` (function, line 24) `func TraversalJoin(`
  - `TraverseRel` (function, line 41) `func (t Traversal) TraverseRel(`
  - `TraverseAbs` (function, line 62) `func (t Traversal) TraverseAbs(`
  - `IsRelative` (function, line 122) `func (t Traversal) IsRelative(`
  - `SimpleSplit` (function, line 139) `func (t Traversal) SimpleSplit(`
  - `RootName` (function, line 151) `func (t Traversal) RootName(`
  - `SourceRange` (function, line 160) `func (t Traversal) SourceRange(`
  - `TraverseAbs` (function, line 184) `func (t TraversalSplit) TraverseAbs(`
  - `TraverseRel` (function, line 190) `func (t TraversalSplit) TraverseRel(`
  - `Traverse` (function, line 196) `func (t TraversalSplit) Traverse(`
  - `Join` (function, line 208) `func (t TraversalSplit) Join(`
  - `RootName` (function, line 213) `func (t TraversalSplit) RootName(`
  - `isTraverserSigil` (function, line 228) `func (tr isTraverser) isTraverserSigil(`
  - `TraversalStep` (function, line 242) `func (tn TraverseRoot) TraversalStep(`
  - `SourceRange` (function, line 246) `func (tn TraverseRoot) SourceRange(`
  - `TraversalStep` (function, line 257) `func (tn TraverseAttr) TraversalStep(`
  - `SourceRange` (function, line 261) `func (tn TraverseAttr) SourceRange(`
  - `TraversalStep` (function, line 272) `func (tn TraverseIndex) TraversalStep(`
  - `SourceRange` (function, line 276) `func (tn TraverseIndex) SourceRange(`
  - `TraversalStep` (function, line 287) `func (tn TraverseSplat) TraversalStep(`
  - `SourceRange` (function, line 291) `func (tn TraverseSplat) SourceRange(`
  - `TraversalSplit` (struct, line 177)
  - `Traverser` (interface, line 218)
  - `isTraverser` (struct, line 225)
  - `TraverseRoot` (struct, line 234)
  - `TraverseAttr` (struct, line 251)
  - `TraverseIndex` (struct, line 266)
  - `TraverseSplat` (struct, line 281)

## teamserver/pkg/profile/yaotl/traversal_for_expr.go
- Doc: AbsTraversalForExpr: A particular Expression implementation can support this function by...
- Layer: utility
- Language: go
- Symbols:
  - `AbsTraversalForExpr` (function, line 20) `func AbsTraversalForExpr(`
  - `RelTraversalForExpr` (function, line 52) `func RelTraversalForExpr(`
  - `ExprAsKeyword` (function, line 108) `func ExprAsKeyword(`
