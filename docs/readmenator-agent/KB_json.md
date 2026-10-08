# Subsystem: json

## teamserver/pkg/profile/yaotl/json/ast.go
- Doc: invalidVal: invalidVal is used as a placeholder where a value is needed for a valid parse tree...
- Layer: utility
- Language: go
- Symbols:
  - `Range` (function, line 21) `func (n *objectVal) Range(`
  - `StartRange` (function, line 25) `func (n *objectVal) StartRange(`
  - `Range` (function, line 35) `func (n *objectAttr) Range(`
  - `StartRange` (function, line 39) `func (n *objectAttr) StartRange(`
  - `Range` (function, line 49) `func (n *arrayVal) Range(`
  - `StartRange` (function, line 53) `func (n *arrayVal) StartRange(`
  - `Range` (function, line 62) `func (n *booleanVal) Range(`
  - `StartRange` (function, line 66) `func (n *booleanVal) StartRange(`
  - `Range` (function, line 75) `func (n *numberVal) Range(`
  - `StartRange` (function, line 79) `func (n *numberVal) StartRange(`
  - `Range` (function, line 88) `func (n *stringVal) Range(`
  - `StartRange` (function, line 92) `func (n *stringVal) StartRange(`
  - `Range` (function, line 100) `func (n *nullVal) Range(`
  - `StartRange` (function, line 104) `func (n *nullVal) StartRange(`
  - `Range` (function, line 115) `func (n invalidVal) Range(`
  - `StartRange` (function, line 119) `func (n invalidVal) StartRange(`
  - `node` (interface, line 9)
  - `objectVal` (struct, line 14)
  - `objectAttr` (struct, line 29)
  - `arrayVal` (struct, line 43)
  - `booleanVal` (struct, line 57)
  - `numberVal` (struct, line 70)
  - `stringVal` (struct, line 83)
  - `nullVal` (struct, line 96)
  - `invalidVal` (struct, line 111)

## teamserver/pkg/profile/yaotl/json/didyoumean.go
- Doc: keywordSuggestion: keywordSuggestion tries to find a valid JSON keyword that is close to the...
- Layer: utility
- Language: go
- Symbols:
  - `keywordSuggestion` (function, line 12) `func keywordSuggestion(`
  - `nameSuggestion` (function, line 25) `func nameSuggestion(`

## teamserver/pkg/profile/yaotl/json/didyoumean_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestKeywordSuggestion` (function, line 5) `func TestKeywordSuggestion(`

## teamserver/pkg/profile/yaotl/json/doc.go
- Doc: Package json is the JSON parser for HCL.
- Layer: utility
- Language: go

## teamserver/pkg/profile/yaotl/json/navigation.go
- Doc: ContextString: Implementation of hcled.ContextString
- Layer: utility
- Language: go
- Symbols:
  - `ContextString` (function, line 13) `func (n navigation) ContextString(`
  - `navigationStepsRev` (function, line 32) `func navigationStepsRev(`
  - `navigation` (struct, line 8)

## teamserver/pkg/profile/yaotl/json/navigation_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestNavigationContextString` (function, line 9) `func TestNavigationContextString(`

## teamserver/pkg/profile/yaotl/json/parser.go
- Layer: utility
- Language: go
- Symbols:
  - `parseFileContent` (function, line 11) `func parseFileContent(`
  - `parseExpression` (function, line 26) `func parseExpression(`
  - `parseValue` (function, line 41) `func parseValue(`
  - `tokenCanStartValue` (function, line 101) `func tokenCanStartValue(`
  - `parseObject` (function, line 110) `func parseObject(`
  - `parseArray` (function, line 261) `func parseArray(`
  - `parseNumber` (function, line 363) `func parseNumber(`
  - `parseString` (function, line 406) `func parseString(`
  - `parseKeyword` (function, line 461) `func parseKeyword(`

## teamserver/pkg/profile/yaotl/json/parser_test.go
- Layer: testing
- Language: go
- Symbols:
  - `init` (function, line 11) `func init(`
  - `TestParse` (function, line 15) `func TestParse(`
  - `TestParseWithPos` (function, line 619) `func TestParseWithPos(`
  - `mustBigFloat` (function, line 661) `func mustBigFloat(`

## teamserver/pkg/profile/yaotl/json/peeker.go
- Layer: utility
- Language: go
- Symbols:
  - `newPeeker` (function, line 8) `func newPeeker(`
  - `Peek` (function, line 15) `func (p *peeker) Peek(`
  - `Read` (function, line 19) `func (p *peeker) Read(`
  - `peeker` (struct, line 3)

## teamserver/pkg/profile/yaotl/json/public.go
- Doc: Parse: Parse attempts to parse the given buffer as JSON and, if successful, returns a hcl.File...
- Layer: utility
- Language: go
- Symbols:
  - `Parse` (function, line 20) `func Parse(`
  - `ParseWithStartPos` (function, line 29) `func ParseWithStartPos(`
  - `ParseExpression` (function, line 76) `func ParseExpression(`
  - `ParseExpressionWithStartPos` (function, line 83) `func ParseExpressionWithStartPos(`
  - `ParseFile` (function, line 92) `func ParseFile(`

## teamserver/pkg/profile/yaotl/json/public_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestParse_nonObject` (function, line 12) `func TestParse_nonObject(`
  - `TestParseTemplate` (function, line 29) `func TestParseTemplate(`
  - `TestParseTemplateUnwrap` (function, line 65) `func TestParseTemplateUnwrap(`
  - `TestParse_malformed` (function, line 101) `func TestParse_malformed(`
  - `TestParseWithStartPos` (function, line 117) `func TestParseWithStartPos(`
  - `TestParseExpression` (function, line 187) `func TestParseExpression(`
  - `TestParseExpression_malformed` (function, line 260) `func TestParseExpression_malformed(`
  - `TestParseExpressionWithStartPos` (function, line 274) `func TestParseExpressionWithStartPos(`

## teamserver/pkg/profile/yaotl/json/scanner.go
- Doc: scan: scan returns the primary tokens for the given JSON buffer in sequence.
- Layer: utility
- Language: go
- Symbols:
  - `scan` (function, line 41) `func scan(`
  - `byteCanStartNumber` (function, line 124) `func byteCanStartNumber(`
  - `scanNumber` (function, line 138) `func scanNumber(`
  - `byteCanStartKeyword` (function, line 157) `func byteCanStartKeyword(`
  - `scanKeyword` (function, line 172) `func scanKeyword(`
  - `scanString` (function, line 189) `func scanString(`
  - `skipWhitespace` (function, line 241) `func skipWhitespace(`
  - `Range` (function, line 280) `func (p *pos) Range(`
  - `posRange` (function, line 292) `func posRange(`
  - `GoString` (function, line 300) `func (t token) GoString(`
  - `isAlphabetical` (function, line 304) `func isAlphabetical(`
  - `token` (struct, line 28)
  - `pos` (struct, line 275)

## teamserver/pkg/profile/yaotl/json/scanner_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestScan` (function, line 12) `func TestScan(`

## teamserver/pkg/profile/yaotl/json/structure.go
- Doc: body: body is the implementation of "Body" used for files processed with the JSON parser.
- Layer: utility
- Language: go
- Symbols:
  - `Content` (function, line 29) `func (b *body) Content(`
  - `PartialContent` (function, line 77) `func (b *body) PartialContent(`
  - `JustAttributes` (function, line 169) `func (b *body) JustAttributes(`
  - `MissingItemRange` (function, line 219) `func (b *body) MissingItemRange(`
  - `unpackBlock` (function, line 232) `func (b *body) unpackBlock(`
  - `collectDeepAttrs` (function, line 325) `func (b *body) collectDeepAttrs(`
  - `Value` (function, line 381) `func (e *expression) Value(`
  - `Variables` (function, line 513) `func (e *expression) Variables(`
  - `Range` (function, line 557) `func (e *expression) Range(`
  - `StartRange` (function, line 561) `func (e *expression) StartRange(`
  - `AsTraversal` (function, line 566) `func (e *expression) AsTraversal(`
  - `ExprCall` (function, line 583) `func (e *expression) ExprCall(`
  - `ExprList` (function, line 606) `func (e *expression) ExprList(`
  - `ExprMap` (function, line 620) `func (e *expression) ExprMap(`
  - `body` (struct, line 14)
  - `expression` (struct, line 25)

## teamserver/pkg/profile/yaotl/json/structure_test.go
- Doc: TestExpressionValue_Diags: TestExpressionValue_Diags asserts that Value() returns diagnostics...
- Layer: testing
- Language: go
- Symbols:
  - `TestBodyPartialContent` (function, line 15) `func TestBodyPartialContent(`
  - `TestBodyContent` (function, line 1080) `func TestBodyContent(`
  - `TestJustAttributes` (function, line 1139) `func TestJustAttributes(`
  - `TestExpressionVariables` (function, line 1237) `func TestExpressionVariables(`
  - `TestExpressionAsTraversal` (function, line 1326) `func TestExpressionAsTraversal(`
  - `TestStaticExpressionList` (function, line 1338) `func TestStaticExpressionList(`
  - `TestExpression_Value` (function, line 1357) `func TestExpression_Value(`
  - `TestExpressionValue_Diags` (function, line 1418) `func TestExpressionValue_Diags(`

## teamserver/pkg/profile/yaotl/json/tokentype_string.go
- Doc: Code generated by "stringer -type tokenType scanner.go"; DO NOT EDIT.
- Layer: utility
- Language: go
- Symbols:
  - `String` (function, line 24) `func (i tokenType) String(`
