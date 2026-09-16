# Subsystem: dynblock

## teamserver/pkg/profile/yaotl/ext/dynblock/expand_body.go
- Layer: utility
- Language: go
- Symbols:
  - `Content` (function, line 29) `func (b *expandBody) Content(`
  - `PartialContent` (function, line 46) `func (b *expandBody) PartialContent(`
  - `extendSchema` (function, line 85) `func (b *expandBody) extendSchema(`
  - `prepareAttributes` (function, line 121) `func (b *expandBody) prepareAttributes(`
  - `expandBlocks` (function, line 151) `func (b *expandBody) expandBlocks(`
  - `expandChild` (function, line 232) `func (b *expandBody) expandChild(`
  - `JustAttributes` (function, line 239) `func (b *expandBody) JustAttributes(`
  - `MissingItemRange` (function, line 246) `func (b *expandBody) MissingItemRange(`
  - `expandBody` (struct, line 12)

## teamserver/pkg/profile/yaotl/ext/dynblock/expand_body_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestExpand` (function, line 13) `func TestExpand(`
  - `TestExpandUnknownBodies` (function, line 336) `func TestExpandUnknownBodies(`

## teamserver/pkg/profile/yaotl/ext/dynblock/expand_spec.go
- Layer: testing
- Language: go
- Symbols:
  - `decodeSpec` (function, line 22) `func (b *expandBody) decodeSpec(`
  - `newBlock` (function, line 153) `func (s *expandSpec) newBlock(`
  - `expandSpec` (struct, line 11)

## teamserver/pkg/profile/yaotl/ext/dynblock/expr_wrap.go
- Layer: utility
- Language: go
- Symbols:
  - `Variables` (function, line 13) `func (e exprWrap) Variables(`
  - `Value` (function, line 33) `func (e exprWrap) Value(`
  - `UnwrapExpression` (function, line 40) `func (e exprWrap) UnwrapExpression(`
  - `exprWrap` (struct, line 8)

## teamserver/pkg/profile/yaotl/ext/dynblock/iteration.go
- Layer: utility
- Language: go
- Symbols:
  - `MakeIteration` (function, line 15) `func (s *expandSpec) MakeIteration(`
  - `Object` (function, line 24) `func (i *iteration) Object(`
  - `EvalContext` (function, line 31) `func (i *iteration) EvalContext(`
  - `MakeChild` (function, line 45) `func (i *iteration) MakeChild(`
  - `iteration` (struct, line 8)

## teamserver/pkg/profile/yaotl/ext/dynblock/public.go
- Layer: utility
- Doc: Package dynblock provides an extension to HCL that allows dynamic declaration of nested blocks in certain contexts via a
- Language: go
- Symbols:
  - `Expand` (function, line 42) `func Expand(`

## teamserver/pkg/profile/yaotl/ext/dynblock/schema.go
- Layer: utility
- Language: go

## teamserver/pkg/profile/yaotl/ext/dynblock/unknown_body.go
- Layer: utility
- Language: go
- Symbols:
  - `Unknown` (function, line 24) `func (b unknownBody) Unknown(`
  - `Content` (function, line 28) `func (b unknownBody) Content(`
  - `PartialContent` (function, line 38) `func (b unknownBody) PartialContent(`
  - `JustAttributes` (function, line 49) `func (b unknownBody) JustAttributes(`
  - `MissingItemRange` (function, line 59) `func (b unknownBody) MissingItemRange(`
  - `fixupContent` (function, line 63) `func (b unknownBody) fixupContent(`
  - `fixupAttrs` (function, line 78) `func (b unknownBody) fixupAttrs(`
  - `unknownBody` (struct, line 17)

## teamserver/pkg/profile/yaotl/ext/dynblock/variables.go
- Layer: utility
- Language: go
- Symbols:
  - `WalkVariables` (function, line 19) `func WalkVariables(`
  - `WalkExpandVariables` (function, line 32) `func WalkExpandVariables(`
  - `Body` (function, line 58) `func (c WalkVariablesChild) Body(`
  - `Visit` (function, line 70) `func (n WalkVariablesNode) Visit(`
  - `extendSchema` (function, line 172) `func (n WalkVariablesNode) extendSchema(`
  - `WalkVariablesNode` (struct, line 38)
  - `WalkVariablesChild` (struct, line 45)

## teamserver/pkg/profile/yaotl/ext/dynblock/variables_hcldec.go
- Layer: utility
- Language: go
- Symbols:
  - `VariablesHCLDec` (function, line 16) `func VariablesHCLDec(`
  - `ExpandVariablesHCLDec` (function, line 25) `func ExpandVariablesHCLDec(`
  - `walkVariablesWithHCLDec` (function, line 30) `func walkVariablesWithHCLDec(`

## teamserver/pkg/profile/yaotl/ext/dynblock/variables_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestVariables` (function, line 16) `func TestVariables(`
