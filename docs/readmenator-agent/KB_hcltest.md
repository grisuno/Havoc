# Subsystem: hcltest

## teamserver/pkg/profile/yaotl/hcltest/doc.go
- Doc: Package hcltest contains utilities that aim to make it more convenient to write tests for code...
- Layer: utility
- Language: go

## teamserver/pkg/profile/yaotl/hcltest/mock.go
- Doc: MockBody: MockBody returns a hcl.Body implementation that works in terms of a caller-constructed...
- Layer: testing
- Language: go
- Symbols:
  - `MockBody` (function, line 15) `func MockBody(`
  - `Content` (function, line 23) `func (b mockBody) Content(`
  - `PartialContent` (function, line 45) `func (b mockBody) PartialContent(`
  - `JustAttributes` (function, line 108) `func (b mockBody) JustAttributes(`
  - `MissingItemRange` (function, line 122) `func (b mockBody) MissingItemRange(`
  - `MockExprLiteral` (function, line 128) `func MockExprLiteral(`
  - `Value` (function, line 136) `func (e mockExprLiteral) Value(`
  - `Variables` (function, line 140) `func (e mockExprLiteral) Variables(`
  - `Range` (function, line 144) `func (e mockExprLiteral) Range(`
  - `StartRange` (function, line 150) `func (e mockExprLiteral) StartRange(`
  - `ExprList` (function, line 155) `func (e mockExprLiteral) ExprList(`
  - `ExprMap` (function, line 170) `func (e mockExprLiteral) ExprMap(`
  - `MockExprVariable` (function, line 189) `func MockExprVariable(`
  - `Value` (function, line 195) `func (e mockExprVariable) Value(`
  - `Variables` (function, line 214) `func (e mockExprVariable) Variables(`
  - `Range` (function, line 225) `func (e mockExprVariable) Range(`
  - `StartRange` (function, line 231) `func (e mockExprVariable) StartRange(`
  - `AsTraversal` (function, line 236) `func (e mockExprVariable) AsTraversal(`
  - `MockExprTraversal` (function, line 247) `func MockExprTraversal(`
  - `MockExprTraversalSrc` (function, line 258) `func MockExprTraversalSrc(`
  - `Value` (function, line 270) `func (e mockExprTraversal) Value(`
  - `Variables` (function, line 274) `func (e mockExprTraversal) Variables(`
  - `Range` (function, line 278) `func (e mockExprTraversal) Range(`
  - `StartRange` (function, line 282) `func (e mockExprTraversal) StartRange(`
  - `AsTraversal` (function, line 287) `func (e mockExprTraversal) AsTraversal(`
  - `MockExprList` (function, line 291) `func MockExprList(`
  - `Value` (function, line 301) `func (e mockExprList) Value(`
  - `Variables` (function, line 317) `func (e mockExprList) Variables(`
  - `Range` (function, line 325) `func (e mockExprList) Range(`
  - `StartRange` (function, line 331) `func (e mockExprList) StartRange(`
  - `ExprList` (function, line 336) `func (e mockExprList) ExprList(`
  - `MockAttrs` (function, line 345) `func MockAttrs(`
  - `mockBody` (struct, line 19)
  - `mockExprLiteral` (struct, line 132)
  - `mockExprTraversal` (struct, line 266)
  - `mockExprList` (struct, line 297)

## teamserver/pkg/profile/yaotl/hcltest/mock_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestMockBodyPartialContent` (function, line 17) `func TestMockBodyPartialContent(`
  - `TestExprList` (function, line 271) `func TestExprList(`
  - `TestExprMap` (function, line 328) `func TestExprMap(`
