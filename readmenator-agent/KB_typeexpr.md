# Subsystem: typeexpr

## teamserver/pkg/profile/yaotl/ext/typeexpr/doc.go
- Layer: utility
- Doc: Package typeexpr extends HCL with a convention for describing HCL types within configuration files.  The type syntax is 
- Language: go

## teamserver/pkg/profile/yaotl/ext/typeexpr/get_type.go
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
