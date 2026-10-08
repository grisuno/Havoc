# Subsystem: transform

## teamserver/pkg/profile/yaotl/ext/transform/doc.go
- Doc: Package transform is a helper package for writing extensions that work by applying transforms to...
- Layer: utility
- Language: go

## teamserver/pkg/profile/yaotl/ext/transform/error.go
- Doc: NewErrorBody: NewErrorBody returns a hcl.Body that returns the given diagnostics whenever any of...
- Layer: utility
- Language: go
- Symbols:
  - `NewErrorBody` (function, line 17) `func NewErrorBody(`
  - `BodyWithDiagnostics` (function, line 39) `func BodyWithDiagnostics(`
  - `Content` (function, line 56) `func (b diagBody) Content(`
  - `PartialContent` (function, line 68) `func (b diagBody) PartialContent(`
  - `JustAttributes` (function, line 80) `func (b diagBody) JustAttributes(`
  - `MissingItemRange` (function, line 92) `func (b diagBody) MissingItemRange(`
  - `emptyContent` (function, line 104) `func (b diagBody) emptyContent(`
  - `diagBody` (struct, line 51)

## teamserver/pkg/profile/yaotl/ext/transform/transform.go
- Doc: deepWrapper: deepWrapper is a hcl.Body implementation that ensures that a given transformer is...
- Layer: utility
- Language: go
- Symbols:
  - `Shallow` (function, line 9) `func Shallow(`
  - `Deep` (function, line 24) `func Deep(`
  - `Content` (function, line 39) `func (w deepWrapper) Content(`
  - `PartialContent` (function, line 45) `func (w deepWrapper) PartialContent(`
  - `transformContent` (function, line 51) `func (w deepWrapper) transformContent(`
  - `JustAttributes` (function, line 76) `func (w deepWrapper) JustAttributes(`
  - `MissingItemRange` (function, line 81) `func (w deepWrapper) MissingItemRange(`
  - `deepWrapper` (struct, line 34)

## teamserver/pkg/profile/yaotl/ext/transform/transform_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestDeep` (function, line 16) `func TestDeep(`

## teamserver/pkg/profile/yaotl/ext/transform/transformer.go
- Doc: Transformer: A Transformer takes a given body, applies some (possibly no-op) transform to it...
- Layer: utility
- Language: go
- Symbols:
  - `TransformBody` (function, line 23) `func (f TransformerFunc) TransformBody(`
  - `Chain` (function, line 31) `func Chain(`
  - `TransformBody` (function, line 35) `func (c chain) TransformBody(`
  - `Transformer` (interface, line 15)
