# Subsystem: typeexpr

## teamserver/pkg/profile/yaotl/ext/typeexpr/doc.go
- Doc: Package typeexpr extends HCL with a convention for describing HCL types within configuration files.
- Layer: utility
- Language: go

## teamserver/pkg/profile/yaotl/ext/typeexpr/get_type.go
- Doc: getType: getType is the internal implementation of both Type and TypeConstraint, using the...
- Layer: utility
- Language: go
- Symbols:
  - `getType` (function, line 15) `func getType(`

## teamserver/pkg/profile/yaotl/ext/typeexpr/get_type_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestGetType` (function, line 14) `func TestGetType(`
  - `TestGetTypeJSON` (function, line 282) `func TestGetTypeJSON(`

## teamserver/pkg/profile/yaotl/ext/typeexpr/public.go
- Doc: Type: Type attempts to process the given expression as a type expression and, if successful...
- Layer: utility
- Language: go
- Symbols:
  - `Type` (function, line 17) `func Type(`
  - `TypeConstraint` (function, line 28) `func TypeConstraint(`
  - `TypeString` (function, line 44) `func TypeString(`

## teamserver/pkg/profile/yaotl/ext/typeexpr/type_string_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestTypeString` (function, line 9) `func TestTypeString(`

## teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go
- Doc: TypeConstraintVal: TypeConstraintVal constructs a cty.Value whose type is TypeConstraintType.
- Layer: utility
- Language: go
- Symbols:
  - `TypeConstraintVal` (function, line 26) `func TypeConstraintVal(`
  - `TypeConstraintFromVal` (function, line 35) `func TypeConstraintFromVal(`
  - `init` (function, line 57) `func init(`
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

## teamserver/pkg/profile/yaotl/ext/typeexpr/type_type_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestTypeConstraintType` (function, line 10) `func TestTypeConstraintType(`
  - `TestConvertFunc` (function, line 30) `func TestConvertFunc(`
