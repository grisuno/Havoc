# Subsystem: customdecode

## teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go
- Layer: utility
- Doc: Package customdecode contains a HCL extension that allows, in certain contexts, expression evaluation to be overridden b
- Language: go
- Symbols:
  - `CustomExpressionDecoderForType` (function, line 48) `func CustomExpressionDecoderForType(`
- Imported by: `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go`, `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go`, `teamserver/pkg/profile/yaotl/hcldec/spec.go`, `teamserver/pkg/profile/yaotl/hclsyntax/expression.go`

## teamserver/pkg/profile/yaotl/ext/customdecode/expression_type.go
- Layer: utility
- Language: go
- Symbols:
  - `ExpressionVal` (function, line 27) `func ExpressionVal(`
  - `ExpressionFromVal` (function, line 33) `func ExpressionFromVal(`
  - `ExpressionClosureVal` (function, line 58) `func ExpressionClosureVal(`
  - `Value` (function, line 64) `func (c *ExpressionClosure) Value(`
  - `ExpressionClosureFromVal` (function, line 75) `func ExpressionClosureFromVal(`
  - `init` (function, line 82) `func init(`
  - `ExpressionClosure` (struct, line 51)
