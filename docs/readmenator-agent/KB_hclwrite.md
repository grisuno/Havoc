# Subsystem: hclwrite

## teamserver/pkg/profile/yaotl/hclwrite/ast.go
- Doc: NewEmptyFile: NewEmptyFile constructs a new file with no content, ready to be mutated by other...
- Layer: utility
- Language: go
- Symbols:
  - `NewEmptyFile` (function, line 17) `func NewEmptyFile(`
  - `Body` (function, line 28) `func (f *File) Body(`
  - `WriteTo` (function, line 36) `func (f *File) WriteTo(`
  - `Bytes` (function, line 45) `func (f *File) Bytes(`
  - `newComments` (function, line 58) `func newComments(`
  - `BuildTokens` (function, line 64) `func (c *comments) BuildTokens(`
  - `newIdentifier` (function, line 75) `func newIdentifier(`
  - `BuildTokens` (function, line 81) `func (i *identifier) BuildTokens(`
  - `hasName` (function, line 85) `func (i *identifier) hasName(`
  - `newNumber` (function, line 96) `func newNumber(`
  - `BuildTokens` (function, line 102) `func (n *number) BuildTokens(`
  - `newQuoted` (function, line 113) `func newQuoted(`
  - `BuildTokens` (function, line 119) `func (q *quoted) BuildTokens(`
  - `File` (struct, line 8)
  - `comments` (struct, line 51)
  - `identifier` (struct, line 68)
  - `number` (struct, line 89)
  - `quoted` (struct, line 106)

## teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go
- Layer: utility
- Language: go
- Symbols:
  - `newAttribute` (function, line 16) `func newAttribute(`
  - `init` (function, line 22) `func (a *Attribute) init(`
  - `Expr` (function, line 46) `func (a *Attribute) Expr(`
  - `Attribute` (struct, line 7)

## teamserver/pkg/profile/yaotl/hclwrite/ast_block.go
- Doc: NewBlock: NewBlock constructs a new, empty block with the given type name and labels.
- Layer: utility
- Language: go
- Symbols:
  - `newBlock` (function, line 19) `func newBlock(`
  - `NewBlock` (function, line 26) `func NewBlock(`
  - `init` (function, line 32) `func (b *Block) init(`
  - `Body` (function, line 67) `func (b *Block) Body(`
  - `Type` (function, line 72) `func (b *Block) Type(`
  - `SetType` (function, line 78) `func (b *Block) SetType(`
  - `Labels` (function, line 85) `func (b *Block) Labels(`
  - `SetLabels` (function, line 92) `func (b *Block) SetLabels(`
  - `labelsObj` (function, line 101) `func (b *Block) labelsObj(`
  - `newBlockLabels` (function, line 111) `func newBlockLabels(`
  - `Replace` (function, line 121) `func (bl *blockLabels) Replace(`
  - `Current` (function, line 136) `func (bl *blockLabels) Current(`
  - `Block` (struct, line 8)
  - `blockLabels` (struct, line 105)

## teamserver/pkg/profile/yaotl/hclwrite/ast_block_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestBlockType` (function, line 15) `func TestBlockType(`
  - `TestBlockLabels` (function, line 49) `func TestBlockLabels(`
  - `TestBlockSetType` (function, line 138) `func TestBlockSetType(`
  - `TestBlockSetLabels` (function, line 198) `func TestBlockSetLabels(`

## teamserver/pkg/profile/yaotl/hclwrite/ast_body.go
- Doc: Clear: Clear removes all of the items from the body, making it empty.
- Layer: utility
- Language: go
- Symbols:
  - `newBody` (function, line 17) `func newBody(`
  - `appendItem` (function, line 24) `func (b *Body) appendItem(`
  - `appendItemNode` (function, line 30) `func (b *Body) appendItemNode(`
  - `Clear` (function, line 38) `func (b *Body) Clear(`
  - `AppendUnstructuredTokens` (function, line 42) `func (b *Body) AppendUnstructuredTokens(`
  - `Attributes` (function, line 48) `func (b *Body) Attributes(`
  - `Blocks` (function, line 61) `func (b *Body) Blocks(`
  - `GetAttribute` (function, line 73) `func (b *Body) GetAttribute(`
  - `getAttributeNode` (function, line 89) `func (b *Body) getAttributeNode(`
  - `FirstMatchingBlock` (function, line 106) `func (b *Body) FirstMatchingBlock(`
  - `RemoveBlock` (function, line 126) `func (b *Body) RemoveBlock(`
  - `SetAttributeRaw` (function, line 144) `func (b *Body) SetAttributeRaw(`
  - `SetAttributeValue` (function, line 165) `func (b *Body) SetAttributeValue(`
  - `SetAttributeTraversal` (function, line 186) `func (b *Body) SetAttributeTraversal(`
  - `RemoveAttribute` (function, line 203) `func (b *Body) RemoveAttribute(`
  - `AppendBlock` (function, line 215) `func (b *Body) AppendBlock(`
  - `AppendNewBlock` (function, line 222) `func (b *Body) AppendNewBlock(`
  - `AppendNewline` (function, line 232) `func (b *Body) AppendNewline(`
  - `Body` (struct, line 11)

## teamserver/pkg/profile/yaotl/hclwrite/ast_body_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestBodyGetAttribute` (function, line 16) `func TestBodyGetAttribute(`
  - `TestBodyFirstMatchingBlock` (function, line 220) `func TestBodyFirstMatchingBlock(`
  - `TestBodySetAttributeValue` (function, line 345) `func TestBodySetAttributeValue(`
  - `TestBodySetAttributeTraversal` (function, line 543) `func TestBodySetAttributeTraversal(`
  - `TestBodySetAttributeRaw` (function, line 769) `func TestBodySetAttributeRaw(`
  - `TestBodySetAttributeValueInBlock` (function, line 933) `func TestBodySetAttributeValueInBlock(`
  - `TestBodySetAttributeValueInNestedBlock` (function, line 981) `func TestBodySetAttributeValueInNestedBlock(`
  - `TestBodyRemoveAttribute` (function, line 1036) `func TestBodyRemoveAttribute(`
  - `TestBodyAppendBlock` (function, line 1149) `func TestBodyAppendBlock(`
  - `TestBodyRemoveBlock` (function, line 1392) `func TestBodyRemoveBlock(`

## teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go
- Doc: Traversal: Traversal represents a sequence of variable, attribute, and/or index operations.
- Layer: utility
- Language: go
- Symbols:
  - `newExpression` (function, line 17) `func newExpression(`
  - `NewExpressionRaw` (function, line 36) `func NewExpressionRaw(`
  - `NewExpressionLiteral` (function, line 60) `func NewExpressionLiteral(`
  - `NewExpressionAbsTraversal` (function, line 69) `func NewExpressionAbsTraversal(`
  - `Variables` (function, line 129) `func (e *Expression) Variables(`
  - `RenameVariablePrefix` (function, line 150) `func (e *Expression) RenameVariablePrefix(`
  - `newTraversal` (function, line 195) `func newTraversal(`
  - `newTraverseName` (function, line 208) `func newTraverseName(`
  - `newTraverseIndex` (function, line 220) `func newTraverseIndex(`
  - `Expression` (struct, line 11)
  - `Traversal` (struct, line 189)
  - `TraverseName` (struct, line 202)
  - `TraverseIndex` (struct, line 214)

## teamserver/pkg/profile/yaotl/hclwrite/ast_test.go
- Layer: testing
- Language: go
- Symbols:
  - `makeTestTree` (function, line 15) `func makeTestTree(`
  - `TestTreeNode` (struct, line 8)

## teamserver/pkg/profile/yaotl/hclwrite/doc.go
- Doc: Package hclwrite deals with the problem of generating HCL configuration and of making specific...
- Layer: utility
- Language: go

## teamserver/pkg/profile/yaotl/hclwrite/examples_test.go
- Layer: testing
- Language: go
- Symbols:
  - `Example_generateFromScratch` (function, line 11) `func Example_generateFromScratch(`
  - `ExampleExpression_RenameVariablePrefix` (function, line 74) `func ExampleExpression_RenameVariablePrefix(`

## teamserver/pkg/profile/yaotl/hclwrite/format.go
- Doc: formatLine: formatLine represents a single line of source code for formatting purposes...
- Layer: utility
- Language: go
- Symbols:
  - `format` (function, line 19) `func format(`
  - `formatIndent` (function, line 40) `func formatIndent(`
  - `formatSpaces` (function, line 110) `func formatSpaces(`
  - `formatCells` (function, line 158) `func formatCells(`
  - `spaceAfterToken` (function, line 227) `func spaceAfterToken(`
  - `linesForFormat` (function, line 342) `func linesForFormat(`
  - `tokenIsNewline` (function, line 427) `func tokenIsNewline(`
  - `tokenBracketChange` (function, line 440) `func tokenBracketChange(`
  - `formatLine` (struct, line 463)

## teamserver/pkg/profile/yaotl/hclwrite/format_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestFormat` (function, line 13) `func TestFormat(`
  - `TestLinesForFormat` (function, line 632) `func TestLinesForFormat(`

## teamserver/pkg/profile/yaotl/hclwrite/generate.go
- Doc: TokensForValue: TokensForValue returns a sequence of tokens that represents the given constant...
- Layer: utility
- Language: go
- Symbols:
  - `TokensForValue` (function, line 23) `func TokensForValue(`
  - `TokensForTraversal` (function, line 36) `func TokensForTraversal(`
  - `appendTokensForValue` (function, line 42) `func appendTokensForValue(`
  - `appendTokensForTraversal` (function, line 164) `func appendTokensForTraversal(`
  - `appendTokensForTraversalStep` (function, line 171) `func appendTokensForTraversalStep(`
  - `escapeQuotedStringLit` (function, line 207) `func escapeQuotedStringLit(`
  - `appendRune` (function, line 248) `func appendRune(`

## teamserver/pkg/profile/yaotl/hclwrite/generate_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestTokensForValue` (function, line 14) `func TestTokensForValue(`
  - `TestTokensForTraversal` (function, line 498) `func TestTokensForTraversal(`

## teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go
- Layer: utility
- Language: go
- Symbols:
  - `Len` (function, line 11) `func (s nativeNodeSorter) Len(`
  - `Less` (function, line 15) `func (s nativeNodeSorter) Less(`
  - `Swap` (function, line 21) `func (s nativeNodeSorter) Swap(`
  - `nativeNodeSorter` (struct, line 7)

## teamserver/pkg/profile/yaotl/hclwrite/node.go
- Doc: node: node represents a node in the AST.
- Layer: utility
- Language: go
- Symbols:
  - `newNode` (function, line 17) `func newNode(`
  - `Equal` (function, line 23) `func (n *node) Equal(`
  - `BuildTokens` (function, line 27) `func (n *node) BuildTokens(`
  - `Detach` (function, line 33) `func (n *node) Detach(`
  - `ReplaceWith` (function, line 60) `func (n *node) ReplaceWith(`
  - `assertUnattached` (function, line 83) `func (n *node) assertUnattached(`
  - `BuildTokens` (function, line 100) `func (ns *nodes) BuildTokens(`
  - `Clear` (function, line 107) `func (ns *nodes) Clear(`
  - `Append` (function, line 112) `func (ns *nodes) Append(`
  - `AppendNode` (function, line 121) `func (ns *nodes) AppendNode(`
  - `Insert` (function, line 135) `func (ns *nodes) Insert(`
  - `InsertNode` (function, line 147) `func (ns *nodes) InsertNode(`
  - `AppendUnstructuredTokens` (function, line 163) `func (ns *nodes) AppendUnstructuredTokens(`
  - `FindNodeWithContent` (function, line 176) `func (ns *nodes) FindNodeWithContent(`
  - `newNodeSet` (function, line 190) `func newNodeSet(`
  - `Has` (function, line 194) `func (ns nodeSet) Has(`
  - `Add` (function, line 202) `func (ns nodeSet) Add(`
  - `Remove` (function, line 206) `func (ns nodeSet) Remove(`
  - `Clear` (function, line 210) `func (ns nodeSet) Clear(`
  - `List` (function, line 216) `func (ns nodeSet) List(`
  - `FindNodeWithContent` (function, line 246) `func (ns nodeSet) FindNodeWithContent(`
  - `newInTree` (function, line 265) `func newInTree(`
  - `assertUnattached` (function, line 271) `func (it *inTree) assertUnattached(`
  - `walkChildNodes` (function, line 277) `func (it *inTree) walkChildNodes(`
  - `BuildTokens` (function, line 283) `func (it *inTree) BuildTokens(`
  - `walkChildNodes` (function, line 295) `func (n *leafNode) walkChildNodes(`
  - `node` (struct, line 10)
  - `nodeContent` (interface, line 90)
  - `nodes` (struct, line 96)
  - `inTree` (struct, line 260)
  - `leafNode` (struct, line 292)

## teamserver/pkg/profile/yaotl/hclwrite/parser.go
- Doc: parse: up to AST nodes.
- Layer: utility
- Language: go
- Symbols:
  - `parse` (function, line 29) `func parse(`
  - `Partition` (function, line 74) `func (it inputTokens) Partition(`
  - `PartitionType` (function, line 82) `func (it inputTokens) PartitionType(`
  - `PartitionTypeOk` (function, line 91) `func (it inputTokens) PartitionTypeOk(`
  - `PartitionTypeSingle` (function, line 101) `func (it inputTokens) PartitionTypeSingle(`
  - `PartitionIncludingComments` (function, line 111) `func (it inputTokens) PartitionIncludingComments(`
  - `PartitionBlockItem` (function, line 128) `func (it inputTokens) PartitionBlockItem(`
  - `PartitionLeadComments` (function, line 135) `func (it inputTokens) PartitionLeadComments(`
  - `PartitionLineEndTokens` (function, line 142) `func (it inputTokens) PartitionLineEndTokens(`
  - `Slice` (function, line 150) `func (it inputTokens) Slice(`
  - `Len` (function, line 162) `func (it inputTokens) Len(`
  - `Tokens` (function, line 166) `func (it inputTokens) Tokens(`
  - `Types` (function, line 170) `func (it inputTokens) Types(`
  - `parseBody` (function, line 181) `func parseBody(`
  - `parseBodyItem` (function, line 220) `func parseBodyItem(`
  - `parseAttribute` (function, line 238) `func parseAttribute(`
  - `parseBlock` (function, line 289) `func parseBlock(`
  - `parseBlockLabels` (function, line 347) `func parseBlockLabels(`
  - `parseExpression` (function, line 375) `func parseExpression(`
  - `parseTraversal` (function, line 396) `func parseTraversal(`
  - `parseTraversalStep` (function, line 413) `func parseTraversalStep(`
  - `writerTokens` (function, line 482) `func writerTokens(`
  - `partitionTokens` (function, line 539) `func partitionTokens(`
  - `partitionLeadCommentTokens` (function, line 577) `func partitionLeadCommentTokens(`
  - `partitionLineEndTokens` (function, line 600) `func partitionLineEndTokens(`
  - `lexConfig` (function, line 635) `func lexConfig(`
  - `inputTokens` (struct, line 69)

## teamserver/pkg/profile/yaotl/hclwrite/parser_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestParse` (function, line 18) `func TestParse(`
  - `TestPartitionTokens` (function, line 1232) `func TestPartitionTokens(`
  - `TestPartitionLeadCommentTokens` (function, line 1382) `func TestPartitionLeadCommentTokens(`
  - `TestLexConfig` (function, line 1458) `func TestLexConfig(`

## teamserver/pkg/profile/yaotl/hclwrite/public.go
- Doc: NewFile: NewFile creates a new file object that is empty and ready to have constructs added t it.
- Layer: utility
- Language: go
- Symbols:
  - `NewFile` (function, line 11) `func NewFile(`
  - `ParseConfig` (function, line 26) `func ParseConfig(`
  - `Format` (function, line 38) `func Format(`

## teamserver/pkg/profile/yaotl/hclwrite/round_trip_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestRoundTripVerbatim` (function, line 16) `func TestRoundTripVerbatim(`
  - `TestRoundTripFormat` (function, line 82) `func TestRoundTripFormat(`

## teamserver/pkg/profile/yaotl/hclwrite/tokens.go
- Doc: Token: Token is a single sequence of bytes annotated with a type.
- Layer: utility
- Language: go
- Symbols:
  - `asHCLSyntax` (function, line 33) `func (t *Token) asHCLSyntax(`
  - `Bytes` (function, line 46) `func (ts Tokens) Bytes(`
  - `testValue` (function, line 52) `func (ts Tokens) testValue(`
  - `Columns` (function, line 59) `func (ts Tokens) Columns(`
  - `WriteTo` (function, line 72) `func (ts Tokens) WriteTo(`
  - `walkChildNodes` (function, line 109) `func (ts Tokens) walkChildNodes(`
  - `BuildTokens` (function, line 113) `func (ts Tokens) BuildTokens(`
  - `newIdentToken` (function, line 117) `func newIdentToken(`
  - `Token` (struct, line 15)
