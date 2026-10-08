# API (page 7 of 8)
Previous: [API_p6.md](API_p6.md)

## teamserver/pkg/profile/yaotl/hclparse/parser.go
- `NewParser` (function) `teamserver/pkg/profile/yaotl/hclparse/parser.go:43` `func NewParser(` -- NewParser creates a new parser, ready to parse configuration files.
- `ParseHCL` (function) `teamserver/pkg/profile/yaotl/hclparse/parser.go:52` `func (p *Parser) ParseHCL(` -- ParseHCL parses the given buffer (which is assumed to have been loaded from the given filename) as a native-syntax...
- `ParseHCLFile` (function) `teamserver/pkg/profile/yaotl/hclparse/parser.go:65` `func (p *Parser) ParseHCLFile(` -- ParseHCLFile reads the given filename and parses it as a native-syntax HCL configuration file.
- `ParseJSON` (function) `teamserver/pkg/profile/yaotl/hclparse/parser.go:86` `func (p *Parser) ParseJSON(` -- ParseJSON parses the given JSON buffer (which is assumed to have been loaded from the given filename) and returns...
- `ParseJSONFile` (function) `teamserver/pkg/profile/yaotl/hclparse/parser.go:98` `func (p *Parser) ParseJSONFile(` -- ParseJSONFile reads the given filename and parses it as JSON, similarly to ParseJSON.
- `AddFile` (function) `teamserver/pkg/profile/yaotl/hclparse/parser.go:110` `func (p *Parser) AddFile(` -- AddFile allows a caller to record in a parser a file that was parsed some other way, thus allowing it to be included...
- `Sources` (function) `teamserver/pkg/profile/yaotl/hclparse/parser.go:119` `func (p *Parser) Sources(` -- Sources returns a map from filenames to the raw source code that was read from them.
- `Files` (function) `teamserver/pkg/profile/yaotl/hclparse/parser.go:133` `func (p *Parser) Files(` -- Files returns a map from filenames to the File objects produced from them.

## teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go
Imported by: `teamserver/pkg/profile/profile.go`, `teamserver/pkg/profile/yaotl/doc.go`
- `Decode` (function) `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go:53` `func Decode(` -- can just pass nil.
- `DecodeFile` (function) `teamserver/pkg/profile/yaotl/hclsimple/hclsimple.go:72` `func DecodeFile(` -- DecodeFile is a wrapper around Decode that first reads the given filename from disk.

## teamserver/pkg/profile/yaotl/hclsyntax/diagnostics.go
- `setDiagEvalContext` (function) `teamserver/pkg/profile/yaotl/hclsyntax/diagnostics.go:16` `func setDiagEvalContext(` -- setDiagEvalContext is an internal helper that will impose a particular EvalContext on a set of diagnostics in-place...

## teamserver/pkg/profile/yaotl/hclsyntax/didyoumean.go
- `nameSuggestion` (function) `teamserver/pkg/profile/yaotl/hclsyntax/didyoumean.go:16` `func nameSuggestion(` -- nameSuggestion tries to find a name from the given slice of suggested names that is close to the given name and...

## teamserver/pkg/profile/yaotl/hclsyntax/expression.go
Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:45` `func (e *ParenthesesExpr) Range(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:49` `func (e *ParenthesesExpr) walkChildNodes(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:62` `func (e *LiteralValueExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:66` `func (e *LiteralValueExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:70` `func (e *LiteralValueExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:74` `func (e *LiteralValueExpr) StartRange(`
- `AsTraversal` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:79` `func (e *LiteralValueExpr) AsTraversal(` -- Implementation for hcl.AbsTraversalForExpr.
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:130` `func (e *ScopeTraversalExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:134` `func (e *ScopeTraversalExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:140` `func (e *ScopeTraversalExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:144` `func (e *ScopeTraversalExpr) StartRange(`
- `AsTraversal` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:149` `func (e *ScopeTraversalExpr) AsTraversal(` -- Implementation for hcl.AbsTraversalForExpr.
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:161` `func (e *RelativeTraversalExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:165` `func (e *RelativeTraversalExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:173` `func (e *RelativeTraversalExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:177` `func (e *RelativeTraversalExpr) StartRange(`
- `AsTraversal` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:182` `func (e *RelativeTraversalExpr) AsTraversal(` -- Implementation for hcl.AbsTraversalForExpr.
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:210` `func (e *FunctionCallExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:216` `func (e *FunctionCallExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:541` `func (e *FunctionCallExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:545` `func (e *FunctionCallExpr) StartRange(`
- `ExprCall` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:550` `func (e *FunctionCallExpr) ExprCall(` -- Implementation for hcl.ExprCall.
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:572` `func (e *ConditionalExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:578` `func (e *ConditionalExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:715` `func (e *ConditionalExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:719` `func (e *ConditionalExpr) StartRange(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:732` `func (e *IndexExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:737` `func (e *IndexExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:750` `func (e *IndexExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:754` `func (e *IndexExpr) StartRange(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:765` `func (e *TupleConsExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:771` `func (e *TupleConsExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:785` `func (e *TupleConsExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:789` `func (e *TupleConsExpr) StartRange(`
- `ExprList` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:794` `func (e *TupleConsExpr) ExprList(` -- Implementation for hcl.ExprList
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:814` `func (e *ObjectConsExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:821` `func (e *ObjectConsExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:897` `func (e *ObjectConsExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:901` `func (e *ObjectConsExpr) StartRange(`
- `ExprMap` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:906` `func (e *ObjectConsExpr) ExprMap(` -- Implementation for hcl.ExprMap
- `literalName` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:925` `func (e *ObjectConsKeyExpr) literalName(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:934` `func (e *ObjectConsKeyExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:942` `func (e *ObjectConsKeyExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:971` `func (e *ObjectConsKeyExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:975` `func (e *ObjectConsKeyExpr) StartRange(`
- `AsTraversal` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:980` `func (e *ObjectConsKeyExpr) AsTraversal(` -- Implementation for hcl.AbsTraversalForExpr.
- `UnwrapExpression` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:996` `func (e *ObjectConsKeyExpr) UnwrapExpression(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1022` `func (e *ForExpr) Value(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1346` `func (e *ForExpr) walkChildNodes(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1375` `func (e *ForExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1379` `func (e *ForExpr) StartRange(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1392` `func (e *SplatExpr) Value(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1522` `func (e *SplatExpr) walkChildNodes(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1527` `func (e *SplatExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1531` `func (e *SplatExpr) StartRange(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1558` `func (e *AnonSymbolExpr) Value(`
- `setValue` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1575` `func (e *AnonSymbolExpr) setValue(` -- setValue sets a temporary local value for the expression when evaluated in the given context, which must be non-nil.
- `clearValue` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1588` `func (e *AnonSymbolExpr) clearValue(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1601` `func (e *AnonSymbolExpr) walkChildNodes(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1605` `func (e *AnonSymbolExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression.go:1609` `func (e *AnonSymbolExpr) StartRange(`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go
- `init` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:86` `func init(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:131` `func (e *BinaryOpExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:136` `func (e *BinaryOpExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:198` `func (e *BinaryOpExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:202` `func (e *BinaryOpExpr) StartRange(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:214` `func (e *UnaryOpExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:218` `func (e *UnaryOpExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:262` `func (e *UnaryOpExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_ops.go:266` `func (e *UnaryOpExpr) StartRange(`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:18` `func (e *TemplateExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:24` `func (e *TemplateExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:97` `func (e *TemplateExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:101` `func (e *TemplateExpr) StartRange(`
- `IsStringLiteral` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:117` `func (e *TemplateExpr) IsStringLiteral(` -- IsStringLiteral returns true if and only if the template consists only of single string literal, as would be created...
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:133` `func (e *TemplateJoinExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:137` `func (e *TemplateJoinExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:207` `func (e *TemplateJoinExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:211` `func (e *TemplateJoinExpr) StartRange(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:225` `func (e *TemplateWrapExpr) walkChildNodes(`
- `Value` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:229` `func (e *TemplateWrapExpr) Value(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:233` `func (e *TemplateWrapExpr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_template.go:237` `func (e *TemplateWrapExpr) StartRange(`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:10` `func (e *AnonSymbolExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:14` `func (e *BinaryOpExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:18` `func (e *ConditionalExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:22` `func (e *ForExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:26` `func (e *FunctionCallExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:30` `func (e *IndexExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:34` `func (e *LiteralValueExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:38` `func (e *ObjectConsExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:42` `func (e *ObjectConsKeyExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:46` `func (e *RelativeTraversalExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:50` `func (e *ScopeTraversalExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:54` `func (e *SplatExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:58` `func (e *TemplateExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:62` `func (e *TemplateJoinExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:66` `func (e *TemplateWrapExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:70` `func (e *TupleConsExpr) Variables(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars.go:74` `func (e *UnaryOpExpr) Variables(`

## teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go
Depends on: `teamserver/pkg/profile/yaotl/hclsyntax/token.go`
- `main` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go:20` `func main(`
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go:97` `func (e %s) Variables(`

## teamserver/pkg/profile/yaotl/hclsyntax/file.go
- `AsHCLFile` (function) `teamserver/pkg/profile/yaotl/hclsyntax/file.go:13` `func (f *File) AsHCLFile(`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/config/fuzz.go
- `Fuzz` (function) `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/config/fuzz.go:8` `func Fuzz(`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/expr/fuzz.go
- `Fuzz` (function) `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/expr/fuzz.go:8` `func Fuzz(`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/template/fuzz.go
- `Fuzz` (function) `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/template/fuzz.go:8` `func Fuzz(`

## teamserver/pkg/profile/yaotl/hclsyntax/fuzz/traversal/fuzz.go
- `Fuzz` (function) `teamserver/pkg/profile/yaotl/hclsyntax/fuzz/traversal/fuzz.go:8` `func Fuzz(`

## teamserver/pkg/profile/yaotl/hclsyntax/keywords.go
- `TokenMatches` (function) `teamserver/pkg/profile/yaotl/hclsyntax/keywords.go:16` `func (kw Keyword) TokenMatches(`

## teamserver/pkg/profile/yaotl/hclsyntax/navigation.go
- `ContextString` (function) `teamserver/pkg/profile/yaotl/hclsyntax/navigation.go:15` `func (n navigation) ContextString(` -- Implementation of hcled.ContextString
- `ContextDefRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/navigation.go:45` `func (n navigation) ContextDefRange(`

## teamserver/pkg/profile/yaotl/hclsyntax/parser.go
- `ParseBody` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:25` `func (p *parser) ParseBody(`
- `ParseBodyItem` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:116` `func (p *parser) ParseBodyItem(`
- `parseSingleAttrBody` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:156` `func (p *parser) parseSingleAttrBody(` -- parseSingleAttrBody is a weird variant of ParseBody that deals with the body of a nested block containing only one...
- `finishParsingBodyAttribute` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:217` `func (p *parser) finishParsingBodyAttribute(`
- `finishParsingBodyBlock` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:274` `func (p *parser) finishParsingBodyBlock(`
- `ParseExpression` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:444` `func (p *parser) ParseExpression(`
- `parseTernaryConditional` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:448` `func (p *parser) parseTernaryConditional(`
- `parseBinaryOps` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:512` `func (p *parser) parseBinaryOps(` -- parseBinaryOps calls itself recursively to work through all of the operator precedence groups, and then eventually...
- `parseExpressionWithTraversals` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:584` `func (p *parser) parseExpressionWithTraversals(`
- `parseExpressionTraversals` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:591` `func (p *parser) parseExpressionTraversals(`
- `makeRelativeTraversal` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:891` `func makeRelativeTraversal(` -- makeRelativeTraversal takes an expression and a traverser and returns a traversal expression that combines the two.
- `parseExpressionTerm` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:910` `func (p *parser) parseExpressionTerm(`
- `numberLitValue` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1081` `func (p *parser) numberLitValue(`
- `finishParsingFunctionCall` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1105` `func (p *parser) finishParsingFunctionCall(` -- finishParsingFunctionCall parses a function call assuming that the function name was already read, and so the peeker...
- `parseTupleCons` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1200` `func (p *parser) parseTupleCons(`
- `parseObjectCons` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1270` `func (p *parser) parseObjectCons(`
- `finishParsingForExpr` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1427` `func (p *parser) finishParsingForExpr(`
- `parseQuotedStringLiteral` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1650` `func (p *parser) parseQuotedStringLiteral(` -- parseQuotedStringLiteral is a helper for parsing quoted strings that aren't allowed to contain any interpolations...
- `ParseStringLiteralToken` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1745` `func ParseStringLiteralToken(` -- ParseStringLiteralToken processes the given token, which must be either a TokenQuotedLit or a TokenStringLit...
- `setRecovery` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1912` `func (p *parser) setRecovery(` -- setRecovery turns on recovery mode without actually doing any recovery.
- `recover` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1924` `func (p *parser) recover(` -- recover seeks forward in the token stream until it finds TokenType "end", then returns with the peeker pointed at...
- `recoverOver` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1963` `func (p *parser) recoverOver(` -- recoverOver seeks forward in the token stream until it finds a block starting with TokenType "start", then finds the...
- `recoverAfterBodyItem` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:1981` `func (p *parser) recoverAfterBodyItem(`
- `oppositeBracket` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:2028` `func (p *parser) oppositeBracket(` -- oppositeBracket finds the bracket that opposes the given bracketer, or NilToken if the given token isn't a...
- `errPlaceholderExpr` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser.go:2067` `func errPlaceholderExpr(`

## teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go
- `ParseTemplate` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:13` `func (p *parser) ParseTemplate(`
- `parseTemplate` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:17` `func (p *parser) parseTemplate(`
- `parseTemplateInner` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:36` `func (p *parser) parseTemplateInner(`
- `parseRoot` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:65` `func (p *templateParser) parseRoot(`
- `parseExpr` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:83` `func (p *templateParser) parseExpr(`
- `parseIf` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:135` `func (p *templateParser) parseIf(`
- `parseFor` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:247` `func (p *templateParser) parseFor(`
- `Peek` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:344` `func (p *templateParser) Peek(`
- `Read` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:348` `func (p *templateParser) Read(`
- `parseTemplateParts` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:361` `func (p *parser) parseTemplateParts(` -- parseTemplateParts produces a flat sequence of "template tokens", which are either literal values (with any...
- `flushHeredocTemplateParts` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:675` `func flushHeredocTemplateParts(` -- flushHeredocTemplateParts modifies in-place the line-leading literal strings to apply the flush heredoc processing...
- `Name` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:787` `func (t *templateEndCtrlToken) Name(`
- `templateToken` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_template.go:808` `func (t isTemplateToken) templateToken(`

## teamserver/pkg/profile/yaotl/hclsyntax/parser_traversal.go
- `ParseTraversalAbs` (function) `teamserver/pkg/profile/yaotl/hclsyntax/parser_traversal.go:12` `func (p *parser) ParseTraversalAbs(` -- ParseTraversalAbs parses an absolute traversal that is assumed to consume all of the remaining tokens in the peeker.

## teamserver/pkg/profile/yaotl/hclsyntax/peeker.go
- `newPeeker` (function) `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:38` `func newPeeker(`
- `Peek` (function) `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:47` `func (p *peeker) Peek(`
- `Read` (function) `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:52` `func (p *peeker) Read(`
- `NextRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:58` `func (p *peeker) NextRange(`
- `PrevRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:62` `func (p *peeker) PrevRange(`
- `nextToken` (function) `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:70` `func (p *peeker) nextToken(`
- `includingNewlines` (function) `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:118` `func (p *peeker) includingNewlines(`
- `PushIncludeNewlines` (function) `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:122` `func (p *peeker) PushIncludeNewlines(`
- `PopIncludeNewlines` (function) `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:138` `func (p *peeker) PopIncludeNewlines(`
- `AssertEmptyIncludeNewlinesStack` (function) `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:168` `func (p *peeker) AssertEmptyIncludeNewlinesStack(` -- AssertEmptyNewlinesStack checks if the IncludeNewlinesStack is empty, doing panicking if it is not.
- `formatPeekerNewlineStackChanges` (function) `teamserver/pkg/profile/yaotl/hclsyntax/peeker.go:184` `func formatPeekerNewlineStackChanges(`

## teamserver/pkg/profile/yaotl/hclsyntax/public.go
- `ParseConfig` (function) `teamserver/pkg/profile/yaotl/hclsyntax/public.go:17` `func ParseConfig(` -- ParseConfig parses the given buffer as a whole HCL config file, returning a *hcl.File representing its contents.
- `ParseExpression` (function) `teamserver/pkg/profile/yaotl/hclsyntax/public.go:41` `func ParseExpression(` -- ParseExpression parses the given buffer as a standalone HCL expression, returning it as an instance of Expression.
- `ParseTemplate` (function) `teamserver/pkg/profile/yaotl/hclsyntax/public.go:75` `func ParseTemplate(` -- ParseTemplate parses the given buffer as a standalone HCL template, returning it as an instance of Expression.
- `ParseTraversalAbs` (function) `teamserver/pkg/profile/yaotl/hclsyntax/public.go:96` `func ParseTraversalAbs(` -- ParseTraversalAbs parses the given buffer as a standalone absolute traversal.
- `LexConfig` (function) `teamserver/pkg/profile/yaotl/hclsyntax/public.go:125` `func LexConfig(` -- LexConfig performs lexical analysis on the given buffer, treating it as a whole HCL config file, and returns the...
- `LexExpression` (function) `teamserver/pkg/profile/yaotl/hclsyntax/public.go:138` `func LexExpression(` -- LexExpression performs lexical analysis on the given buffer, treating it as a standalone HCL expression, and returns...
- `LexTemplate` (function) `teamserver/pkg/profile/yaotl/hclsyntax/public.go:153` `func LexTemplate(` -- LexTemplate performs lexical analysis on the given buffer, treating it as a standalone HCL template, and returns the...
- `ValidIdentifier` (function) `teamserver/pkg/profile/yaotl/hclsyntax/public.go:165` `func ValidIdentifier(` -- ValidIdentifier tests if the given string could be a valid identifier in a native syntax expression.

## teamserver/pkg/profile/yaotl/hclsyntax/scan_string_lit.go
- `scanStringLit` (function) `teamserver/pkg/profile/yaotl/hclsyntax/scan_string_lit.go:119` `func scanStringLit(`

## teamserver/pkg/profile/yaotl/hclsyntax/scan_tokens.go
- `scanTokens` (function) `teamserver/pkg/profile/yaotl/hclsyntax/scan_tokens.go:4220` `func scanTokens(`

## teamserver/pkg/profile/yaotl/hclsyntax/structure.go
- `AsHCLBlock` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:11` `func (b *Block) AsHCLBlock(` -- AsHCLBlock returns the block data expressed as a *hcl.Block.
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:49` `func (b *Body) walkChildNodes(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:54` `func (b *Body) Range(`
- `Content` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:58` `func (b *Body) Content(`
- `PartialContent` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:128` `func (b *Body) PartialContent(`
- `JustAttributes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:250` `func (b *Body) JustAttributes(`
- `MissingItemRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:281` `func (b *Body) MissingItemRange(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:292` `func (a Attributes) walkChildNodes(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:303` `func (a Attributes) Range(` -- Range returns the range of some arbitrary point within the set of attributes, or an invalid range if there are no...
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:327` `func (a *Attribute) walkChildNodes(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:331` `func (a *Attribute) Range(`
- `AsHCLAttribute` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:336` `func (a *Attribute) AsHCLAttribute(` -- AsHCLAttribute returns the block data expressed as a *hcl.Attribute.
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:352` `func (bs Blocks) walkChildNodes(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:363` `func (bs Blocks) Range(` -- Range returns the range of some arbitrary point within the list of blocks, or an invalid range if there are no blocks.
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:384` `func (b *Block) walkChildNodes(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:388` `func (b *Block) Range(`
- `DefRange` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure.go:392` `func (b *Block) DefRange(`

## teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go
- `BlocksAtPos` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:15` `func (b *Body) BlocksAtPos(` -- BlocksAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.
- `InnermostBlockAtPos` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:22` `func (b *Body) InnermostBlockAtPos(` -- InnermostBlockAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.
- `OutermostBlockAtPos` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:29` `func (b *Body) OutermostBlockAtPos(` -- OutermostBlockAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.
- `blocksAtPos` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:40` `func (b *Body) blocksAtPos(` -- blocksAtPos is the internal engine of both BlocksAtPos and InnermostBlockAtPos, which both need to do the same logic...
- `outermostBlockAtPos` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:68` `func (b *Body) outermostBlockAtPos(` -- outermostBlockAtPos is the internal version of OutermostBlockAtPos that returns a hclsyntax.Block rather than an...
- `AttributeAtPos` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:84` `func (b *Body) AttributeAtPos(` -- AttributeAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.
- `attributeAtPos` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:91` `func (b *Body) attributeAtPos(` -- attributeAtPos is the internal version of AttributeAtPos that returns a hclsyntax.Block rather than an hcl.Block...
- `OutermostExprAtPos` (function) `teamserver/pkg/profile/yaotl/hclsyntax/structure_at_pos.go:109` `func (b *Body) OutermostExprAtPos(` -- OutermostExprAtPos implements the method of the same name for an *hcl.File that is backed by a *Body.

## teamserver/pkg/profile/yaotl/hclsyntax/token.go
Imported by: `teamserver/pkg/profile/yaotl/hclsyntax/expression_vars_gen.go`
- `GoString` (function) `teamserver/pkg/profile/yaotl/hclsyntax/token.go:107` `func (t TokenType) GoString(`
- `emitToken` (function) `teamserver/pkg/profile/yaotl/hclsyntax/token.go:127` `func (f *tokenAccum) emitToken(`
- `tokenOpensFlushHeredoc` (function) `teamserver/pkg/profile/yaotl/hclsyntax/token.go:167` `func tokenOpensFlushHeredoc(`
- `checkInvalidTokens` (function) `teamserver/pkg/profile/yaotl/hclsyntax/token.go:182` `func checkInvalidTokens(` -- checkInvalidTokens does a simple pass across the given tokens and generates diagnostics for tokens that should...
- `stripUTF8BOM` (function) `teamserver/pkg/profile/yaotl/hclsyntax/token.go:326` `func stripUTF8BOM(` -- stripUTF8BOM checks whether the given buffer begins with a UTF-8 byte order mark (0xEF 0xBB 0xBF) and, if so...

## teamserver/pkg/profile/yaotl/hclsyntax/token_type_string.go
- `String` (function) `teamserver/pkg/profile/yaotl/hclsyntax/token_type_string.go:126` `func (i TokenType) String(`

## teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb
- `each_alpha` (method) `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:80` -- # Downloads the document at url and yields every alpha line's hex range and description.
- `to_hex` (method) `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:103` -- ## Formats to hex at minimum width
- `to_ucs4` (method) `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:112` -- ## UCS4 is just a straight hex conversion of the unicode codepoint.
- `to_utf8_enc` (method) `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:126`
- `from_utf8_enc` (method) `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:150`
- `utf8_ranges` (method) `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:181` -- ## Given a range, splits it up into ranges that can be continuously encoded into utf8.
- `build_range` (method) `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:197`
- `to_utf8` (method) `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:246`
- `count_codepoints` (method) `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:259` -- # Perform a 3-way comparison of the number of codepoints advertised by the unicode spec for the given range, the...
- `is_valid` (method) `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:273`
- `generate_machine` (method) `teamserver/pkg/profile/yaotl/hclsyntax/unicode2ragel.rb:285` -- # Generate the state matching to stdout

## teamserver/pkg/profile/yaotl/hclsyntax/variables.go
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:11` `func Variables(` -- Variables returns all of the variables referenced within a given expression.
- `Enter` (function) `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:32` `func (w *variablesWalker) Enter(`
- `Exit` (function) `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:55` `func (w *variablesWalker) Exit(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:78` `func (e ChildScope) walkChildNodes(`
- `Range` (function) `teamserver/pkg/profile/yaotl/hclsyntax/variables.go:84` `func (e ChildScope) Range(` -- Range returns the range of the expression that the ChildScope is encapsulating.

## teamserver/pkg/profile/yaotl/hclsyntax/walk.go
- `VisitAll` (function) `teamserver/pkg/profile/yaotl/hclsyntax/walk.go:16` `func VisitAll(` -- VisitAll is a basic way to traverse the AST beginning with a particular node.
- `Walk` (function) `teamserver/pkg/profile/yaotl/hclsyntax/walk.go:33` `func Walk(` -- Walk is a more complex way to traverse the AST starting with a particular node, which provides information about the...

## teamserver/pkg/profile/yaotl/hclwrite/ast.go
- `NewEmptyFile` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast.go:17` `func NewEmptyFile(` -- NewEmptyFile constructs a new file with no content, ready to be mutated by other calls that append to its body.
- `Body` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast.go:28` `func (f *File) Body(` -- Body returns the root body of the file, which contains the top-level attributes and blocks.
- `WriteTo` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast.go:36` `func (f *File) WriteTo(` -- WriteTo writes the tokens underlying the receiving file to the given writer.
- `Bytes` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast.go:45` `func (f *File) Bytes(` -- Bytes returns a buffer containing the source code resulting from the tokens underlying the receiving file.
- `newComments` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast.go:58` `func newComments(`
- `BuildTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast.go:64` `func (c *comments) BuildTokens(`
- `newIdentifier` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast.go:75` `func newIdentifier(`
- `BuildTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast.go:81` `func (i *identifier) BuildTokens(`
- `hasName` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast.go:85` `func (i *identifier) hasName(`
- `newNumber` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast.go:96` `func newNumber(`
- `BuildTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast.go:102` `func (n *number) BuildTokens(`
- `newQuoted` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast.go:113` `func newQuoted(`
- `BuildTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast.go:119` `func (q *quoted) BuildTokens(`

## teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go
- `newAttribute` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go:16` `func newAttribute(`
- `init` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go:22` `func (a *Attribute) init(`
- `Expr` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_attribute.go:46` `func (a *Attribute) Expr(`

## teamserver/pkg/profile/yaotl/hclwrite/ast_block.go
- `newBlock` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:19` `func newBlock(`
- `NewBlock` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:26` `func NewBlock(` -- NewBlock constructs a new, empty block with the given type name and labels.
- `init` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:32` `func (b *Block) init(`
- `Body` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:67` `func (b *Block) Body(` -- Body returns the body that represents the content of the receiving block.
- `Type` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:72` `func (b *Block) Type(` -- Type returns the type name of the block.
- `SetType` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:78` `func (b *Block) SetType(` -- SetType updates the type name of the block to a given name.
- `Labels` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:85` `func (b *Block) Labels(` -- Labels returns the labels of the block.
- `SetLabels` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:92` `func (b *Block) SetLabels(` -- SetLabels updates the labels of the block to given labels.
- `labelsObj` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:101` `func (b *Block) labelsObj(` -- labelsObj returns the internal node content representation of the block labels.
- `newBlockLabels` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:111` `func newBlockLabels(`
- `Replace` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:121` `func (bl *blockLabels) Replace(`
- `Current` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_block.go:136` `func (bl *blockLabels) Current(`

## teamserver/pkg/profile/yaotl/hclwrite/ast_body.go
- `newBody` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:17` `func newBody(`
- `appendItem` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:24` `func (b *Body) appendItem(`
- `appendItemNode` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:30` `func (b *Body) appendItemNode(`
- `Clear` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:38` `func (b *Body) Clear(` -- Clear removes all of the items from the body, making it empty.
- `AppendUnstructuredTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:42` `func (b *Body) AppendUnstructuredTokens(`
- `Attributes` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:48` `func (b *Body) Attributes(` -- Attributes returns a new map of all of the attributes in the body, with the attribute names as the keys.
- `Blocks` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:61` `func (b *Body) Blocks(` -- Blocks returns a new slice of all the blocks in the body.
- `GetAttribute` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:73` `func (b *Body) GetAttribute(` -- GetAttribute returns the attribute from the body that has the given name, or returns nil if there is currently no...
- `getAttributeNode` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:89` `func (b *Body) getAttributeNode(` -- getAttributeNode is like GetAttribute but it returns the node containing the selected attribute (if one is found)...
- `FirstMatchingBlock` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:106` `func (b *Body) FirstMatchingBlock(` -- FirstMatchingBlock returns a first matching block from the body that has the given name and labels or returns nil if...
- `RemoveBlock` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:126` `func (b *Body) RemoveBlock(` -- RemoveBlock removes the given block from the body, if it's in that body.
- `SetAttributeRaw` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:144` `func (b *Body) SetAttributeRaw(` -- SetAttributeRaw either replaces the expression of an existing attribute of the given name or adds a new attribute...
- `SetAttributeValue` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:165` `func (b *Body) SetAttributeValue(` -- SetAttributeValue either replaces the expression of an existing attribute of the given name or adds a new attribute...
- `SetAttributeTraversal` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:186` `func (b *Body) SetAttributeTraversal(` -- SetAttributeTraversal either replaces the expression of an existing attribute of the given name or adds a new...
- `RemoveAttribute` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:203` `func (b *Body) RemoveAttribute(` -- RemoveAttribute removes the attribute with the given name from the body.
- `AppendBlock` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:215` `func (b *Body) AppendBlock(` -- AppendBlock appends an existing block (which must not be already attached to a body) to the end of the receiving body.
- `AppendNewBlock` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:222` `func (b *Body) AppendNewBlock(` -- AppendNewBlock appends a new nested block to the end of the receiving body with the given type name and labels.
- `AppendNewline` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_body.go:232` `func (b *Body) AppendNewline(` -- AppendNewline appends a newline token to th end of the receiving body, which generally serves as a separator between...

## teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go
- `newExpression` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:17` `func newExpression(`
- `NewExpressionRaw` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:36` `func NewExpressionRaw(` -- NewExpressionRaw constructs an expression containing the given raw tokens.
- `NewExpressionLiteral` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:60` `func NewExpressionLiteral(` -- NewExpressionLiteral constructs an an expression that represents the given literal value.
- `NewExpressionAbsTraversal` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:69` `func NewExpressionAbsTraversal(` -- NewExpressionAbsTraversal constructs an expression that represents the given traversal, which must be absolute or...
- `Variables` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:129` `func (e *Expression) Variables(` -- Variables returns the absolute traversals that exist within the receiving expression.
- `RenameVariablePrefix` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:150` `func (e *Expression) RenameVariablePrefix(` -- RenameVariablePrefix examines each of the absolute traversals in the receiving expression to see if they have the...
- `newTraversal` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:195` `func newTraversal(`
- `newTraverseName` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:208` `func newTraverseName(`
- `newTraverseIndex` (function) `teamserver/pkg/profile/yaotl/hclwrite/ast_expression.go:220` `func newTraverseIndex(`

## teamserver/pkg/profile/yaotl/hclwrite/format.go
- `format` (function) `teamserver/pkg/profile/yaotl/hclwrite/format.go:19` `func format(` -- format rewrites tokens within the given sequence, in-place, to adjust the whitespace around their content to achieve...
- `formatIndent` (function) `teamserver/pkg/profile/yaotl/hclwrite/format.go:40` `func formatIndent(`
- `formatSpaces` (function) `teamserver/pkg/profile/yaotl/hclwrite/format.go:110` `func formatSpaces(`
- `formatCells` (function) `teamserver/pkg/profile/yaotl/hclwrite/format.go:158` `func formatCells(`
- `spaceAfterToken` (function) `teamserver/pkg/profile/yaotl/hclwrite/format.go:227` `func spaceAfterToken(` -- spaceAfterToken decides whether a particular subject token should have a space after it when surrounded by the given...
- `linesForFormat` (function) `teamserver/pkg/profile/yaotl/hclwrite/format.go:342` `func linesForFormat(`
- `tokenIsNewline` (function) `teamserver/pkg/profile/yaotl/hclwrite/format.go:427` `func tokenIsNewline(`
- `tokenBracketChange` (function) `teamserver/pkg/profile/yaotl/hclwrite/format.go:440` `func tokenBracketChange(`

## teamserver/pkg/profile/yaotl/hclwrite/fuzz/config/fuzz.go
- `Fuzz` (function) `teamserver/pkg/profile/yaotl/hclwrite/fuzz/config/fuzz.go:10` `func Fuzz(`

## teamserver/pkg/profile/yaotl/hclwrite/generate.go
- `TokensForValue` (function) `teamserver/pkg/profile/yaotl/hclwrite/generate.go:23` `func TokensForValue(` -- TokensForValue returns a sequence of tokens that represents the given constant value.
- `TokensForTraversal` (function) `teamserver/pkg/profile/yaotl/hclwrite/generate.go:36` `func TokensForTraversal(` -- TokensForTraversal returns a sequence of tokens that represents the given traversal.
- `appendTokensForValue` (function) `teamserver/pkg/profile/yaotl/hclwrite/generate.go:42` `func appendTokensForValue(`
- `appendTokensForTraversal` (function) `teamserver/pkg/profile/yaotl/hclwrite/generate.go:164` `func appendTokensForTraversal(`
- `appendTokensForTraversalStep` (function) `teamserver/pkg/profile/yaotl/hclwrite/generate.go:171` `func appendTokensForTraversalStep(`
- `escapeQuotedStringLit` (function) `teamserver/pkg/profile/yaotl/hclwrite/generate.go:207` `func escapeQuotedStringLit(`
- `appendRune` (function) `teamserver/pkg/profile/yaotl/hclwrite/generate.go:248` `func appendRune(`

## teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go
- `Len` (function) `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go:11` `func (s nativeNodeSorter) Len(`
- `Less` (function) `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go:15` `func (s nativeNodeSorter) Less(`
- `Swap` (function) `teamserver/pkg/profile/yaotl/hclwrite/native_node_sorter.go:21` `func (s nativeNodeSorter) Swap(`

## teamserver/pkg/profile/yaotl/hclwrite/node.go
- `newNode` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:17` `func newNode(`
- `Equal` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:23` `func (n *node) Equal(`
- `BuildTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:27` `func (n *node) BuildTokens(`
- `Detach` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:33` `func (n *node) Detach(` -- Detach removes the receiver from the list it currently belongs to.
- `ReplaceWith` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:60` `func (n *node) ReplaceWith(` -- ReplaceWith removes the receiver from the list it currently belongs to and inserts a new node with the given content...
- `assertUnattached` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:83` `func (n *node) assertUnattached(`
- `BuildTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:100` `func (ns *nodes) BuildTokens(`
- `Clear` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:107` `func (ns *nodes) Clear(`
- `Append` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:112` `func (ns *nodes) Append(`
- `AppendNode` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:121` `func (ns *nodes) AppendNode(`
- `Insert` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:135` `func (ns *nodes) Insert(` -- Insert inserts a nodeContent at a given position.
- `InsertNode` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:147` `func (ns *nodes) InsertNode(` -- InsertNode inserts a node at a given position.
- `AppendUnstructuredTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:163` `func (ns *nodes) AppendUnstructuredTokens(`
- `FindNodeWithContent` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:176` `func (ns *nodes) FindNodeWithContent(` -- FindNodeWithContent searches the nodes for a node whose content equals the given content.
- `newNodeSet` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:190` `func newNodeSet(`
- `Has` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:194` `func (ns nodeSet) Has(`
- `Add` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:202` `func (ns nodeSet) Add(`
- `Remove` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:206` `func (ns nodeSet) Remove(`
- `Clear` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:210` `func (ns nodeSet) Clear(`
- `List` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:216` `func (ns nodeSet) List(`
- `FindNodeWithContent` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:246` `func (ns nodeSet) FindNodeWithContent(` -- FindNodeWithContent searches the nodes for a node whose content equals the given content.
- `newInTree` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:265` `func newInTree(`
- `assertUnattached` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:271` `func (it *inTree) assertUnattached(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:277` `func (it *inTree) walkChildNodes(`
- `BuildTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:283` `func (it *inTree) BuildTokens(`
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclwrite/node.go:295` `func (n *leafNode) walkChildNodes(`

## teamserver/pkg/profile/yaotl/hclwrite/parser.go
- `parse` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:29` `func parse(` -- up to AST nodes.
- `Partition` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:74` `func (it inputTokens) Partition(`
- `PartitionType` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:82` `func (it inputTokens) PartitionType(`
- `PartitionTypeOk` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:91` `func (it inputTokens) PartitionTypeOk(`
- `PartitionTypeSingle` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:101` `func (it inputTokens) PartitionTypeSingle(`
- `PartitionIncludingComments` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:111` `func (it inputTokens) PartitionIncludingComments(` -- PartitionIncludeComments is like Partition except the returned "within" range includes any lead and line comments...
- `PartitionBlockItem` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:128` `func (it inputTokens) PartitionBlockItem(` -- PartitionBlockItem is similar to PartitionIncludeComments but it returns the comments as separate token sequences so...
- `PartitionLeadComments` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:135` `func (it inputTokens) PartitionLeadComments(`
- `PartitionLineEndTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:142` `func (it inputTokens) PartitionLineEndTokens(`
- `Slice` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:150` `func (it inputTokens) Slice(`
- `Len` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:162` `func (it inputTokens) Len(`
- `Tokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:166` `func (it inputTokens) Tokens(`
- `Types` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:170` `func (it inputTokens) Types(`
- `parseBody` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:181` `func parseBody(` -- parseBody locates the given body within the given input tokens and returns the resulting *Body object as well as the...
- `parseBodyItem` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:220` `func parseBodyItem(`
- `parseAttribute` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:238` `func parseAttribute(`
- `parseBlock` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:289` `func parseBlock(`
- `parseBlockLabels` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:347` `func parseBlockLabels(`
- `parseExpression` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:375` `func parseExpression(`
- `parseTraversal` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:396` `func parseTraversal(`
- `parseTraversalStep` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:413` `func parseTraversalStep(`
- `writerTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:482` `func writerTokens(` -- writerTokens takes a sequence of tokens as produced by the main hclsyntax package and transforms it into an...
- `partitionTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:539` `func partitionTokens(` -- This works best when the range is aligned with token boundaries (e.g. because it was produced in terms of the...
- `partitionLeadCommentTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:577` `func partitionLeadCommentTokens(` -- partitionLeadCommentTokens takes a sequence of tokens that is assumed to immediately precede a construct that can...
- `partitionLineEndTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:600` `func partitionLineEndTokens(` -- partitionLineEndTokens takes a sequence of tokens that is assumed to immediately follow a construct that can have a...
- `lexConfig` (function) `teamserver/pkg/profile/yaotl/hclwrite/parser.go:635` `func lexConfig(` -- lexConfig uses the hclsyntax scanner to get a token stream and then rewrites it into this package's token model.

## teamserver/pkg/profile/yaotl/hclwrite/public.go
- `NewFile` (function) `teamserver/pkg/profile/yaotl/hclwrite/public.go:11` `func NewFile(` -- NewFile creates a new file object that is empty and ready to have constructs added t it.
- `ParseConfig` (function) `teamserver/pkg/profile/yaotl/hclwrite/public.go:26` `func ParseConfig(` -- ParseConfig interprets the given source bytes into a *hclwrite.File.
- `Format` (function) `teamserver/pkg/profile/yaotl/hclwrite/public.go:38` `func Format(` -- Format takes source code and performs simple whitespace changes to transform it to a canonical layout style.

## teamserver/pkg/profile/yaotl/hclwrite/tokens.go
- `asHCLSyntax` (function) `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:33` `func (t *Token) asHCLSyntax(` -- asHCLSyntax returns the receiver expressed as an incomplete hclsyntax.Token.
- `Bytes` (function) `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:46` `func (ts Tokens) Bytes(`
- `testValue` (function) `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:52` `func (ts Tokens) testValue(`
- `Columns` (function) `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:59` `func (ts Tokens) Columns(` -- Columns returns the number of columns (grapheme clusters) the token sequence occupies.
- `WriteTo` (function) `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:72` `func (ts Tokens) WriteTo(` -- WriteTo takes an io.Writer and writes the bytes for each token to it, along with the spacing that separates each token.
- `walkChildNodes` (function) `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:109` `func (ts Tokens) walkChildNodes(`
- `BuildTokens` (function) `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:113` `func (ts Tokens) BuildTokens(`
- `newIdentToken` (function) `teamserver/pkg/profile/yaotl/hclwrite/tokens.go:117` `func newIdentToken(`

## teamserver/pkg/profile/yaotl/json/ast.go
- `Range` (function) `teamserver/pkg/profile/yaotl/json/ast.go:21` `func (n *objectVal) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/json/ast.go:25` `func (n *objectVal) StartRange(`
- `Range` (function) `teamserver/pkg/profile/yaotl/json/ast.go:35` `func (n *objectAttr) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/json/ast.go:39` `func (n *objectAttr) StartRange(`
- `Range` (function) `teamserver/pkg/profile/yaotl/json/ast.go:49` `func (n *arrayVal) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/json/ast.go:53` `func (n *arrayVal) StartRange(`
- `Range` (function) `teamserver/pkg/profile/yaotl/json/ast.go:62` `func (n *booleanVal) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/json/ast.go:66` `func (n *booleanVal) StartRange(`
- `Range` (function) `teamserver/pkg/profile/yaotl/json/ast.go:75` `func (n *numberVal) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/json/ast.go:79` `func (n *numberVal) StartRange(`
- `Range` (function) `teamserver/pkg/profile/yaotl/json/ast.go:88` `func (n *stringVal) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/json/ast.go:92` `func (n *stringVal) StartRange(`
- `Range` (function) `teamserver/pkg/profile/yaotl/json/ast.go:100` `func (n *nullVal) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/json/ast.go:104` `func (n *nullVal) StartRange(`
- `Range` (function) `teamserver/pkg/profile/yaotl/json/ast.go:115` `func (n invalidVal) Range(`
- `StartRange` (function) `teamserver/pkg/profile/yaotl/json/ast.go:119` `func (n invalidVal) StartRange(`

## teamserver/pkg/profile/yaotl/json/didyoumean.go
- `keywordSuggestion` (function) `teamserver/pkg/profile/yaotl/json/didyoumean.go:12` `func keywordSuggestion(` -- keywordSuggestion tries to find a valid JSON keyword that is close to the given string and returns it if found.
- `nameSuggestion` (function) `teamserver/pkg/profile/yaotl/json/didyoumean.go:25` `func nameSuggestion(` -- nameSuggestion tries to find a name from the given slice of suggested names that is close to the given name and...

## teamserver/pkg/profile/yaotl/json/fuzz/config/fuzz.go
- `Fuzz` (function) `teamserver/pkg/profile/yaotl/json/fuzz/config/fuzz.go:7` `func Fuzz(`

## teamserver/pkg/profile/yaotl/json/navigation.go
- `ContextString` (function) `teamserver/pkg/profile/yaotl/json/navigation.go:13` `func (n navigation) ContextString(` -- Implementation of hcled.ContextString
- `navigationStepsRev` (function) `teamserver/pkg/profile/yaotl/json/navigation.go:32` `func navigationStepsRev(`


Next: [API_p8.md](API_p8.md)
