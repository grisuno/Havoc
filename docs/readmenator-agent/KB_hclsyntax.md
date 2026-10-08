# Subsystem: hclsyntax

## teamserver/pkg/profile/yaotl/hclsyntax/diagnostics.go
- Doc: setDiagEvalContext: setDiagEvalContext is an internal helper that will impose a particular...
- Layer: utility
- Language: go
- Symbols:
  - `setDiagEvalContext` (function, line 16) `func setDiagEvalContext(`

## teamserver/pkg/profile/yaotl/hclsyntax/didyoumean.go
- Doc: nameSuggestion: nameSuggestion tries to find a name from the given slice of suggested names that...
- Layer: utility
- Language: go
- Symbols:
  - `nameSuggestion` (function, line 16) `func nameSuggestion(`

## teamserver/pkg/profile/yaotl/hclsyntax/doc.go
- Doc: Package hclsyntax contains the parser, AST, etc for HCL's native language, as opposed to the...
- Layer: utility
- Language: go

## teamserver/pkg/profile/yaotl/hclsyntax/expression.go
- Doc: ParenthesesExpr: ParenthesesExpr represents an expression written in grouping parentheses.
- Layer: utility
- Language: go
- Symbols:
  - `Range` (function, line 45) `func (e *ParenthesesExpr) Range(`
  - `walkChildNodes` (function, line 49) `func (e *ParenthesesExpr) walkChildNodes(`
  - `walkChildNodes` (function, line 62) `func (e *LiteralValueExpr) walkChildNodes(`
  - `Value` (function, line 66) `func (e *LiteralValueExpr) Value(`
  - `Range` (function, line 70) `func (e *LiteralValueExpr) Range(`
  - `StartRange` (function, line 74) `func (e *LiteralValueExpr) StartRange(`
  - `AsTraversal` (function, line 79) `func (e *LiteralValueExpr) AsTraversal(`
  - `walkChildNodes` (function, line 130) `func (e *ScopeTraversalExpr) walkChildNodes(`
  - `Value` (function, line 134) `func (e *ScopeTraversalExpr) Value(`
  - `Range` (function, line 140) `func (e *ScopeTraversalExpr) Range(`
  - `StartRange` (function, line 144) `func (e *ScopeTraversalExpr) StartRange(`
  - `AsTraversal` (function, line 149) `func (e *ScopeTraversalExpr) AsTraversal(`
  - `walkChildNodes` (function, line 161) `func (e *RelativeTraversalExpr) walkChildNodes(`
  - `Value` (function, line 165) `func (e *RelativeTraversalExpr) Value(`
  - `Range` (function, line 173) `func (e *RelativeTraversalExpr) Range(`
  - `StartRange` (function, line 177) `func (e *RelativeTraversalExpr) StartRange(`
  - `AsTraversal` (function, line 182) `func (e *RelativeTraversalExpr) AsTraversal(`
  - `walkChildNodes` (function, line 210) `func (e *FunctionCallExpr) walkChildNodes(`
  - `Value` (function, line 216) `func (e *FunctionCallExpr) Value(`
  - `Range` (function, line 541) `func (e *FunctionCallExpr) Range(`
  - `StartRange` (function, line 545) `func (e *FunctionCallExpr) StartRange(`
  - `ExprCall` (function, line 550) `func (e *FunctionCallExpr) ExprCall(`
  - `walkChildNodes` (function, line 572) `func (e *ConditionalExpr) walkChildNodes(`
  - `Value` (function, line 578) `func (e *ConditionalExpr) Value(`
  - `Range` (function, line 715) `func (e *ConditionalExpr) Range(`
  - `StartRange` (function, line 719) `func (e *ConditionalExpr) StartRange(`
  - `walkChildNodes` (function, line 732) `func (e *IndexExpr) walkChildNodes(`
  - `Value` (function, line 737) `func (e *IndexExpr) Value(`
  - `Range` (function, line 750) `func (e *IndexExpr) Range(`
  - `StartRange` (function, line 754) `func (e *IndexExpr) StartRange(`
  - `walkChildNodes` (function, line 765) `func (e *TupleConsExpr) walkChildNodes(`
  - `Value` (function, line 771) `func (e *TupleConsExpr) Value(`
  - `Range` (function, line 785) `func (e *TupleConsExpr) Range(`
  - `StartRange` (function, line 789) `func (e *TupleConsExpr) StartRange(`
  - `ExprList` (function, line 794) `func (e *TupleConsExpr) ExprList(`
  - `walkChildNodes` (function, line 814) `func (e *ObjectConsExpr) walkChildNodes(`
  - `Value` (function, line 821) `func (e *ObjectConsExpr) Value(`
  - `Range` (function, line 897) `func (e *ObjectConsExpr) Range(`
  - `StartRange` (function, line 901) `func (e *ObjectConsExpr) StartRange(`
  - `ExprMap` (function, line 906) `func (e *ObjectConsExpr) ExprMap(`
  - `literalName` (function, line 925) `func (e *ObjectConsKeyExpr) literalName(`
  - `walkChildNodes` (function, line 934) `func (e *ObjectConsKeyExpr) walkChildNodes(`
  - `Value` (function, line 942) `func (e *ObjectConsKeyExpr) Value(`
  - `Range` (function, line 971) `func (e *ObjectConsKeyExpr) Range(`
  - `StartRange` (function, line 975) `func (e *ObjectConsKeyExpr) StartRange(`
  - `AsTraversal` (function, line 980) `func (e *ObjectConsKeyExpr) AsTraversal(`
  - `UnwrapExpression` (function, line 996) `func (e *ObjectConsKeyExpr) UnwrapExpression(`
  - `Value` (function, line 1022) `func (e *ForExpr) Value(`
  - `walkChildNodes` (function, line 1346) `func (e *ForExpr) walkChildNodes(`
  - `Range` (function, line 1375) `func (e *ForExpr) Range(`
  - `StartRange` (function, line 1379) `func (e *ForExpr) StartRange(`
  - `Value` (function, line 1392) `func (e *SplatExpr) Value(`
  - `walkChildNodes` (function, line 1522) `func (e *SplatExpr) walkChildNodes(`
  - `Range` (function, line 1527) `func (e *SplatExpr) Range(`
  - `StartRange` (function, line 1531) `func (e *SplatExpr) StartRange(`
  - `Value` (function, line 1558) `func (e *AnonSymbolExpr) Value(`
  - `setValue` (function, line 1575) `func (e *AnonSymbolExpr) setValue(`
  - `clearValue` (function, line 1588) `func (e *AnonSymbolExpr) clearValue(`
  - `walkChildNodes` (function, line 1601) `func (e *AnonSymbolExpr) walkChildNodes(`
  - `Range` (function, line 1605) `func (e *AnonSymbolExpr) Range(`
  - `StartRange` (function, line 1609) `func (e *AnonSymbolExpr) StartRange(`
  - `Expression` (interface, line 15)
  - `ParenthesesExpr` (struct, line 38)
  - `LiteralValueExpr` (struct, line 57)
  - `ScopeTraversalExpr` (struct, line 125)
  - `RelativeTraversalExpr` (struct, line 155)
  - `FunctionCallExpr` (struct, line 197)
  - `ConditionalExpr` (struct, line 564)
  - `IndexExpr` (struct, line 723)
  - `TupleConsExpr` (struct, line 758)
  - `ObjectConsExpr` (struct, line 802)
  - `ObjectConsItem` (struct, line 809)
  - `ObjectConsKeyExpr` (struct, line 920)
  - `ForExpr` (struct, line 1005)
  - `SplatExpr` (struct, line 1383)
  - `AnonSymbolExpr` (struct, line 1546)
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go
- Layer: utility
- Language: go
- Symbols:
  - `init` (function, line 86) `func init(`
  - `walkChildNodes` (function, line 131) `func (e *BinaryOpExpr) walkChildNodes(`
  - `Value` (function, line 136) `func (e *BinaryOpExpr) Value(`
  - `Range` (function, line 198) `func (e *BinaryOpExpr) Range(`
  - `StartRange` (function, line 202) `func (e *BinaryOpExpr) StartRange(`
  - `walkChildNodes` (function, line 214) `func (e *UnaryOpExpr) walkChildNodes(`
  - `Value` (function, line 218) `func (e *UnaryOpExpr) Value(`
  - `Range` (function, line 262) `func (e *UnaryOpExpr) Range(`
  - `StartRange` (function, line 266) `func (e *UnaryOpExpr) StartRange(`
  - `Operation` (struct, line 13)
  - `BinaryOpExpr` (struct, line 123)
  - `UnaryOpExpr` (struct, line 206)

## teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go
- Doc: TemplateJoinExpr: TemplateJoinExpr is used to convert tuples of strings produced by template...
- Layer: presentation
- Language: go
- Symbols:
  - `walkChildNodes` (function, line 18) `func (e *TemplateExpr) walkChildNodes(`
  - `Value` (function, line 24) `func (e *TemplateExpr) Value(`
  - `Range` (function, line 97) `func (e *TemplateExpr) Range(`
  - `StartRange` (function, line 101) `func (e *TemplateExpr) StartRange(`
  - `IsStringLiteral` (function, line 117) `func (e *TemplateExpr) IsStringLiteral(`
  - `walkChildNodes` (function, line 133) `func (e *TemplateJoinExpr) walkChildNodes(`
  - `Value` (function, line 137) `func (e *TemplateJoinExpr) Value(`
  - `Range` (function, line 207) `func (e *TemplateJoinExpr) Range(`
  - `StartRange` (function, line 211) `func (e *TemplateJoinExpr) StartRange(`
  - `walkChildNodes` (function, line 225) `func (e *TemplateWrapExpr) walkChildNodes(`
  - `Value` (function, line 229) `func (e *TemplateWrapExpr) Value(`
  - `Range` (function, line 233) `func (e *TemplateWrapExpr) Range(`
  - `StartRange` (function, line 237) `func (e *TemplateWrapExpr) StartRange(`
  - `TemplateExpr` (struct, line 12)
  - `TemplateJoinExpr` (struct, line 129)
  - `TemplateWrapExpr` (struct, line 219)

## teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go
- Layer: utility
- Language: go
- Symbols:
  - `Variables` (function, line 10) `func (e *AnonSymbolExpr) Variables(`
  - `Variables` (function, line 14) `func (e *BinaryOpExpr) Variables(`
  - `Variables` (function, line 18) `func (e *ConditionalExpr) Variables(`
  - `Variables` (function, line 22) `func (e *ForExpr) Variables(`
  - `Variables` (function, line 26) `func (e *FunctionCallExpr) Variables(`
  - `Variables` (function, line 30) `func (e *IndexExpr) Variables(`
  - `Variables` (function, line 34) `func (e *LiteralValueExpr) Variables(`
  - `Variables` (function, line 38) `func (e *ObjectConsExpr) Variables(`
  - `Variables` (function, line 42) `func (e *ObjectConsKeyExpr) Variables(`
  - `Variables` (function, line 46) `func (e *RelativeTraversalExpr) Variables(`
  - `Variables` (function, line 50) `func (e *ScopeTraversalExpr) Variables(`
  - `Variables` (function, line 54) `func (e *SplatExpr) Variables(`
  - `Variables` (function, line 58) `func (e *TemplateExpr) Variables(`
  - `Variables` (function, line 62) `func (e *TemplateJoinExpr) Variables(`
  - `Variables` (function, line 66) `func (e *TemplateWrapExpr) Variables(`
  - `Variables` (function, line 70) `func (e *TupleConsExpr) Variables(`
  - `Variables` (function, line 74) `func (e *UnaryOpExpr) Variables(`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go
- Doc: This is a 'go generate'-oriented program for producing the "Variables" method on every...
- Layer: utility
- Language: go
- Symbols:
  - `main` (function, line 20) `func main(`
  - `Variables` (function, line 97) `func (e %s) Variables(`
- Depends on: `teamserver/pkg/profile/yaotl/hclsyntax/token.go`

## teamserver/pkg/profile/yaotl/hclsyntax/file.go
- Doc: File: File is the top-level object resulting from parsing a configuration file.
- Layer: utility
- Language: go
- Symbols:
  - `AsHCLFile` (function, line 13) `func (f *File) AsHCLFile(`
  - `File` (struct, line 8)

## teamserver/pkg/profile/yaotl/hclsyntax/generate.go
- Layer: utility
- Language: go

## teamserver/pkg/profile/yaotl/hclsyntax/keywords.go
- Layer: utility
- Language: go
- Symbols:
  - `TokenMatches` (function, line 16) `func (kw Keyword) TokenMatches(`

## teamserver/pkg/profile/yaotl/hclsyntax/navigation.go
- Doc: ContextString: Implementation of hcled.ContextString
- Layer: utility
- Language: go
- Symbols:
  - `ContextString` (function, line 15) `func (n navigation) ContextString(`
  - `ContextDefRange` (function, line 45) `func (n navigation) ContextDefRange(`
  - `navigation` (struct, line 10)

## teamserver/pkg/profile/yaotl/hclsyntax/node.go
- Doc: Node: Node is the abstract type that every AST node implements.
- Layer: utility
- Language: go
- Symbols:
  - `Node` (interface, line 11)

## teamserver/pkg/profile/yaotl/hclsyntax/parser.go
- Doc: parseSingleAttrBody: parseSingleAttrBody is a weird variant of ParseBody that deals with the...
- Layer: utility
- Language: go
- Symbols:
  - `ParseBody` (function, line 25) `func (p *parser) ParseBody(`
  - `ParseBodyItem` (function, line 116) `func (p *parser) ParseBodyItem(`
  - `parseSingleAttrBody` (function, line 156) `func (p *parser) parseSingleAttrBody(`
  - `finishParsingBodyAttribute` (function, line 217) `func (p *parser) finishParsingBodyAttribute(`
  - `finishParsingBodyBlock` (function, line 274) `func (p *parser) finishParsingBodyBlock(`
  - `ParseExpression` (function, line 444) `func (p *parser) ParseExpression(`
  - `parseTernaryConditional` (function, line 448) `func (p *parser) parseTernaryConditional(`
  - `parseBinaryOps` (function, line 512) `func (p *parser) parseBinaryOps(`
  - `parseExpressionWithTraversals` (function, line 584) `func (p *parser) parseExpressionWithTraversals(`
  - `parseExpressionTraversals` (function, line 591) `func (p *parser) parseExpressionTraversals(`
  - `makeRelativeTraversal` (function, line 891) `func makeRelativeTraversal(`
  - `parseExpressionTerm` (function, line 910) `func (p *parser) parseExpressionTerm(`
  - `numberLitValue` (function, line 1081) `func (p *parser) numberLitValue(`
  - `finishParsingFunctionCall` (function, line 1105) `func (p *parser) finishParsingFunctionCall(`
  - `parseTupleCons` (function, line 1200) `func (p *parser) parseTupleCons(`
  - `parseObjectCons` (function, line 1270) `func (p *parser) parseObjectCons(`
  - `finishParsingForExpr` (function, line 1427) `func (p *parser) finishParsingForExpr(`
  - `parseQuotedStringLiteral` (function, line 1650) `func (p *parser) parseQuotedStringLiteral(`
  - `ParseStringLiteralToken` (function, line 1745) `func ParseStringLiteralToken(`
  - `setRecovery` (function, line 1912) `func (p *parser) setRecovery(`
  - `recover` (function, line 1924) `func (p *parser) recover(`
  - `recoverOver` (function, line 1963) `func (p *parser) recoverOver(`
  - `recoverAfterBodyItem` (function, line 1981) `func (p *parser) recoverAfterBodyItem(`
  - `oppositeBracket` (function, line 2028) `func (p *parser) oppositeBracket(`
  - `errPlaceholderExpr` (function, line 2067) `func errPlaceholderExpr(`
  - `parser` (struct, line 15)

## teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go
- Doc: templateToken: templateToken is a higher-level token that represents a single atom within the...
- Layer: presentation
- Language: go
- Symbols:
  - `ParseTemplate` (function, line 13) `func (p *parser) ParseTemplate(`
  - `parseTemplate` (function, line 17) `func (p *parser) parseTemplate(`
  - `parseTemplateInner` (function, line 36) `func (p *parser) parseTemplateInner(`
  - `parseRoot` (function, line 65) `func (p *templateParser) parseRoot(`
  - `parseExpr` (function, line 83) `func (p *templateParser) parseExpr(`
  - `parseIf` (function, line 135) `func (p *templateParser) parseIf(`
  - `parseFor` (function, line 247) `func (p *templateParser) parseFor(`
  - `Peek` (function, line 344) `func (p *templateParser) Peek(`
  - `Read` (function, line 348) `func (p *templateParser) Read(`
  - `parseTemplateParts` (function, line 361) `func (p *parser) parseTemplateParts(`
  - `flushHeredocTemplateParts` (function, line 675) `func flushHeredocTemplateParts(`
  - `Name` (function, line 787) `func (t *templateEndCtrlToken) Name(`
  - `templateToken` (function, line 808) `func (t isTemplateToken) templateToken(`
  - `templateParser` (struct, line 58)
  - `templateParts` (struct, line 734)
  - `templateToken` (interface, line 743)
  - `templateLiteralToken` (struct, line 747)
  - `templateInterpToken` (struct, line 753)
  - `templateIfToken` (struct, line 759)
  - `templateForToken` (struct, line 765)
  - `templateEndCtrlToken` (struct, line 781)
  - `templateEndToken` (struct, line 801)

## teamserver/pkg/profile/yaotl/hclsyntax/parser_traversal.go
- Doc: ParseTraversalAbs: ParseTraversalAbs parses an absolute traversal that is assumed to consume all...
- Layer: utility
- Language: go
- Symbols:
  - `ParseTraversalAbs` (function, line 12) `func (p *parser) ParseTraversalAbs(`

## teamserver/pkg/profile/yaotl/hclsyntax/peeker.go
- Doc: peekerNewlineStackChange: for use in debugging the stack usage only
- Layer: utility
- Language: go
- Symbols:
  - `newPeeker` (function, line 38) `func newPeeker(`
  - `Peek` (function, line 47) `func (p *peeker) Peek(`
  - `Read` (function, line 52) `func (p *peeker) Read(`
  - `NextRange` (function, line 58) `func (p *peeker) NextRange(`
  - `PrevRange` (function, line 62) `func (p *peeker) PrevRange(`
  - `nextToken` (function, line 70) `func (p *peeker) nextToken(`
  - `includingNewlines` (function, line 118) `func (p *peeker) includingNewlines(`
  - `PushIncludeNewlines` (function, line 122) `func (p *peeker) PushIncludeNewlines(`
  - `PopIncludeNewlines` (function, line 138) `func (p *peeker) PopIncludeNewlines(`
  - `AssertEmptyIncludeNewlinesStack` (function, line 168) `func (p *peeker) AssertEmptyIncludeNewlinesStack(`
  - `formatPeekerNewlineStackChanges` (function, line 184) `func formatPeekerNewlineStackChanges(`
  - `peeker` (struct, line 20)
  - `peekerNewlineStackChange` (struct, line 32)

## teamserver/pkg/profile/yaotl/hclsyntax/public.go
- Doc: ParseConfig: ParseConfig parses the given buffer as a whole HCL config file, returning a...
- Layer: utility
- Language: go
- Symbols:
  - `ParseConfig` (function, line 17) `func ParseConfig(`
  - `ParseExpression` (function, line 41) `func ParseExpression(`
  - `ParseTemplate` (function, line 75) `func ParseTemplate(`
  - `ParseTraversalAbs` (function, line 96) `func ParseTraversalAbs(`
  - `LexConfig` (function, line 125) `func LexConfig(`
  - `LexExpression` (function, line 138) `func LexExpression(`
  - `LexTemplate` (function, line 153) `func LexTemplate(`
  - `ValidIdentifier` (function, line 165) `func ValidIdentifier(`

## teamserver/pkg/profile/yaotl/hclsyntax/scan_string_lit.go
- Doc: line scan_string_lit.rl:1
- Layer: utility
- Language: go
- Symbols:
  - `scanStringLit` (function, line 119) `func scanStringLit(`

## teamserver/pkg/profile/yaotl/hclsyntax/scan_tokens.go
- Doc: line scan_tokens.rl:1
- Layer: utility
- Language: go
- Symbols:
  - `scanTokens` (function, line 4220) `func scanTokens(`

## teamserver/pkg/profile/yaotl/hclsyntax/structure.go
- Doc: Body: Body is the implementation of hcl.Body for the HCL native syntax.
- Layer: utility
- Language: go
- Symbols:
  - `AsHCLBlock` (function, line 11) `func (b *Block) AsHCLBlock(`
  - `walkChildNodes` (function, line 49) `func (b *Body) walkChildNodes(`
  - `Range` (function, line 54) `func (b *Body) Range(`
  - `Content` (function, line 58) `func (b *Body) Content(`
  - `PartialContent` (function, line 128) `func (b *Body) PartialContent(`
  - `JustAttributes` (function, line 250) `func (b *Body) JustAttributes(`
  - `MissingItemRange` (function, line 281) `func (b *Body) MissingItemRange(`
  - `walkChildNodes` (function, line 292) `func (a Attributes) walkChildNodes(`
  - `Range` (function, line 303) `func (a Attributes) Range(`
  - `walkChildNodes` (function, line 327) `func (a *Attribute) walkChildNodes(`
  - `Range` (function, line 331) `func (a *Attribute) Range(`
  - `AsHCLAttribute` (function, line 336) `func (a *Attribute) AsHCLAttribute(`
  - `walkChildNodes` (function, line 352) `func (bs Blocks) walkChildNodes(`
  - `Range` (function, line 363) `func (bs Blocks) Range(`
  - `walkChildNodes` (function, line 384) `func (b *Block) walkChildNodes(`
  - `Range` (function, line 388) `func (b *Block) Range(`
  - `DefRange` (function, line 392) `func (b *Block) DefRange(`
  - `Body` (struct, line 33)
  - `Attribute` (struct, line 318)
  - `Block` (struct, line 373)

## teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go
- Doc: BlocksAtPos: BlocksAtPos implements the method of the same name for an *hcl.File that is backed...
- Layer: utility
- Language: go
- Symbols:
  - `BlocksAtPos` (function, line 15) `func (b *Body) BlocksAtPos(`
  - `InnermostBlockAtPos` (function, line 22) `func (b *Body) InnermostBlockAtPos(`
  - `OutermostBlockAtPos` (function, line 29) `func (b *Body) OutermostBlockAtPos(`
  - `blocksAtPos` (function, line 40) `func (b *Body) blocksAtPos(`
  - `outermostBlockAtPos` (function, line 68) `func (b *Body) outermostBlockAtPos(`
  - `AttributeAtPos` (function, line 84) `func (b *Body) AttributeAtPos(`
  - `attributeAtPos` (function, line 91) `func (b *Body) attributeAtPos(`
  - `OutermostExprAtPos` (function, line 109) `func (b *Body) OutermostExprAtPos(`

## teamserver/pkg/profile/yaotl/hclsyntax/token.go
- Doc: Token: Token represents a sequence of bytes from some HCL code that has been tagged with a type...
- Layer: utility
- Language: go
- Symbols:
  - `GoString` (function, line 107) `func (t TokenType) GoString(`
  - `emitToken` (function, line 127) `func (f *tokenAccum) emitToken(`
  - `tokenOpensFlushHeredoc` (function, line 167) `func tokenOpensFlushHeredoc(`
  - `checkInvalidTokens` (function, line 182) `func checkInvalidTokens(`
  - `stripUTF8BOM` (function, line 326) `func stripUTF8BOM(`
  - `Token` (struct, line 13)
  - `tokenAccum` (struct, line 119)
  - `heredocInProgress` (struct, line 162)
- Imported by: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go`

## teamserver/pkg/profile/yaotl/hclsyntax/token_type_string.go
- Doc: Code generated by "stringer -type TokenType -output token_type_string.go"; DO NOT EDIT.
- Layer: utility
- Language: go
- Symbols:
  - `_` (function, line 7) `func _(`
  - `String` (function, line 126) `func (i TokenType) String(`

## teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb
- Doc: This scripted has been updated to accept more command-line arguments:  -u, --url...
- Layer: utility
- Language: rb
- Symbols:
  - `each_alpha` (method, line 80)
  - `to_hex` (method, line 103)
  - `to_ucs4` (method, line 112)
  - `to_utf8_enc` (method, line 126)
  - `from_utf8_enc` (method, line 150)
  - `utf8_ranges` (method, line 181)
  - `build_range` (method, line 197)
  - `to_utf8` (method, line 246)
  - `count_codepoints` (method, line 259)
  - `is_valid` (method, line 273)
  - `generate_machine` (method, line 285)

## teamserver/pkg/profile/yaotl/hclsyntax/variables.go
- Doc: variablesWalker: variablesWalker is a Walker implementation that calls its callback for any root...
- Layer: utility
- Language: go
- Symbols:
  - `Variables` (function, line 11) `func Variables(`
  - `Enter` (function, line 32) `func (w *variablesWalker) Enter(`
  - `Exit` (function, line 55) `func (w *variablesWalker) Exit(`
  - `walkChildNodes` (function, line 78) `func (e ChildScope) walkChildNodes(`
  - `Range` (function, line 84) `func (e ChildScope) Range(`
  - `variablesWalker` (struct, line 27)
  - `ChildScope` (struct, line 73)

## teamserver/pkg/profile/yaotl/hclsyntax/walk.go
- Doc: Walker: Walker is an interface used with Walk.
- Layer: utility
- Language: go
- Symbols:
  - `VisitAll` (function, line 16) `func VisitAll(`
  - `Walk` (function, line 33) `func Walk(`
  - `Walker` (interface, line 25)
