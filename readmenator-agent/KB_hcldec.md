# Subsystem: hcldec

## teamserver/pkg/profile/yaotl/hcldec/block_labels.go
- Layer: utility
- Language: go
- Symbols:
  - `labelsForBlock` (function, line 12) `func labelsForBlock(`
  - `blockLabel` (struct, line 7)

## teamserver/pkg/profile/yaotl/hcldec/decode.go
- Layer: utility
- Language: go
- Symbols:
  - `decode` (function, line 8) `func decode(`
  - `impliedType` (function, line 27) `func impliedType(`
  - `sourceRange` (function, line 31) `func sourceRange(`

## teamserver/pkg/profile/yaotl/hcldec/doc.go
- Layer: utility
- Doc: Package hcldec provides a higher-level API for unpacking the content of HCL bodies, implemented in terms of the low-leve
- Language: go

## teamserver/pkg/profile/yaotl/hcldec/gob.go
- Layer: utility
- Language: go
- Symbols:
  - `init` (function, line 7) `func init(`

## teamserver/pkg/profile/yaotl/hcldec/public.go
- Layer: utility
- Language: go
- Symbols:
  - `Decode` (function, line 14) `func Decode(`
  - `PartialDecode` (function, line 25) `func PartialDecode(`
  - `ImpliedType` (function, line 31) `func ImpliedType(`
  - `SourceRange` (function, line 51) `func SourceRange(`
  - `ChildBlockTypes` (function, line 58) `func ChildBlockTypes(`

## teamserver/pkg/profile/yaotl/hcldec/public_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestDecode` (function, line 13) `func TestDecode(`
  - `TestSourceRange` (function, line 1046) `func TestSourceRange(`

## teamserver/pkg/profile/yaotl/hcldec/schema.go
- Layer: utility
- Language: go
- Symbols:
  - `ImpliedSchema` (function, line 10) `func ImpliedSchema(`

## teamserver/pkg/profile/yaotl/hcldec/spec.go
- Layer: testing
- Language: go
- Symbols:
  - `visitSameBodyChildren` (function, line 73) `func (s ObjectSpec) visitSameBodyChildren(`
  - `decode` (function, line 79) `func (s ObjectSpec) decode(`
  - `impliedType` (function, line 92) `func (s ObjectSpec) impliedType(`
  - `sourceRange` (function, line 104) `func (s ObjectSpec) sourceRange(`
  - `visitSameBodyChildren` (function, line 115) `func (s TupleSpec) visitSameBodyChildren(`
  - `decode` (function, line 121) `func (s TupleSpec) decode(`
  - `impliedType` (function, line 134) `func (s TupleSpec) impliedType(`
  - `sourceRange` (function, line 146) `func (s TupleSpec) sourceRange(`
  - `visitSameBodyChildren` (function, line 162) `func (s *AttrSpec) visitSameBodyChildren(`
  - `variablesNeeded` (function, line 167) `func (s *AttrSpec) variablesNeeded(`
  - `attrSchemata` (function, line 177) `func (s *AttrSpec) attrSchemata(`
  - `sourceRange` (function, line 186) `func (s *AttrSpec) sourceRange(`
  - `decode` (function, line 195) `func (s *AttrSpec) decode(`
  - `impliedType` (function, line 237) `func (s *AttrSpec) impliedType(`
  - `visitSameBodyChildren` (function, line 247) `func (s *LiteralSpec) visitSameBodyChildren(`
  - `decode` (function, line 251) `func (s *LiteralSpec) decode(`
  - `impliedType` (function, line 255) `func (s *LiteralSpec) impliedType(`
  - `sourceRange` (function, line 259) `func (s *LiteralSpec) sourceRange(`
  - `visitSameBodyChildren` (function, line 273) `func (s *ExprSpec) visitSameBodyChildren(`
  - `variablesNeeded` (function, line 278) `func (s *ExprSpec) variablesNeeded(`
  - `decode` (function, line 282) `func (s *ExprSpec) decode(`
  - `impliedType` (function, line 286) `func (s *ExprSpec) impliedType(`
  - `sourceRange` (function, line 291) `func (s *ExprSpec) sourceRange(`
  - `visitSameBodyChildren` (function, line 307) `func (s *BlockSpec) visitSameBodyChildren(`
  - `blockHeaderSchemata` (function, line 312) `func (s *BlockSpec) blockHeaderSchemata(`
  - `nestedSpec` (function, line 322) `func (s *BlockSpec) nestedSpec(`
  - `variablesNeeded` (function, line 327) `func (s *BlockSpec) variablesNeeded(`
  - `decode` (function, line 345) `func (s *BlockSpec) decode(`
  - `impliedType` (function, line 392) `func (s *BlockSpec) impliedType(`
  - `sourceRange` (function, line 396) `func (s *BlockSpec) sourceRange(`
  - `visitSameBodyChildren` (function, line 423) `func (s *BlockListSpec) visitSameBodyChildren(`
  - `blockHeaderSchemata` (function, line 428) `func (s *BlockListSpec) blockHeaderSchemata(`
  - `nestedSpec` (function, line 438) `func (s *BlockListSpec) nestedSpec(`
  - `variablesNeeded` (function, line 443) `func (s *BlockListSpec) variablesNeeded(`
  - `decode` (function, line 457) `func (s *BlockListSpec) decode(`
  - `impliedType` (function, line 547) `func (s *BlockListSpec) impliedType(`
  - `sourceRange` (function, line 551) `func (s *BlockListSpec) sourceRange(`
  - `visitSameBodyChildren` (function, line 585) `func (s *BlockTupleSpec) visitSameBodyChildren(`
  - `blockHeaderSchemata` (function, line 590) `func (s *BlockTupleSpec) blockHeaderSchemata(`
  - `nestedSpec` (function, line 600) `func (s *BlockTupleSpec) nestedSpec(`
  - `variablesNeeded` (function, line 605) `func (s *BlockTupleSpec) variablesNeeded(`
  - `decode` (function, line 619) `func (s *BlockTupleSpec) decode(`
  - `impliedType` (function, line 671) `func (s *BlockTupleSpec) impliedType(`
  - `sourceRange` (function, line 677) `func (s *BlockTupleSpec) sourceRange(`
  - `visitSameBodyChildren` (function, line 707) `func (s *BlockSetSpec) visitSameBodyChildren(`
  - `blockHeaderSchemata` (function, line 712) `func (s *BlockSetSpec) blockHeaderSchemata(`
  - `nestedSpec` (function, line 722) `func (s *BlockSetSpec) nestedSpec(`
  - `variablesNeeded` (function, line 727) `func (s *BlockSetSpec) variablesNeeded(`
  - `decode` (function, line 741) `func (s *BlockSetSpec) decode(`
  - `impliedType` (function, line 832) `func (s *BlockSetSpec) impliedType(`
  - `sourceRange` (function, line 836) `func (s *BlockSetSpec) sourceRange(`
  - `visitSameBodyChildren` (function, line 868) `func (s *BlockMapSpec) visitSameBodyChildren(`
  - `blockHeaderSchemata` (function, line 873) `func (s *BlockMapSpec) blockHeaderSchemata(`
  - `nestedSpec` (function, line 883) `func (s *BlockMapSpec) nestedSpec(`
  - `variablesNeeded` (function, line 888) `func (s *BlockMapSpec) variablesNeeded(`
  - `decode` (function, line 902) `func (s *BlockMapSpec) decode(`
  - `impliedType` (function, line 981) `func (s *BlockMapSpec) impliedType(`
  - `sourceRange` (function, line 989) `func (s *BlockMapSpec) sourceRange(`
  - `visitSameBodyChildren` (function, line 1025) `func (s *BlockObjectSpec) visitSameBodyChildren(`
  - `blockHeaderSchemata` (function, line 1030) `func (s *BlockObjectSpec) blockHeaderSchemata(`
  - `nestedSpec` (function, line 1040) `func (s *BlockObjectSpec) nestedSpec(`
  - `variablesNeeded` (function, line 1045) `func (s *BlockObjectSpec) variablesNeeded(`
  - `decode` (function, line 1059) `func (s *BlockObjectSpec) decode(`
  - `impliedType` (function, line 1135) `func (s *BlockObjectSpec) impliedType(`
  - `sourceRange` (function, line 1141) `func (s *BlockObjectSpec) sourceRange(`
  - `visitSameBodyChildren` (function, line 1183) `func (s *BlockAttrsSpec) visitSameBodyChildren(`
  - `blockHeaderSchemata` (function, line 1188) `func (s *BlockAttrsSpec) blockHeaderSchemata(`
  - `nestedSpec` (function, line 1198) `func (s *BlockAttrsSpec) nestedSpec(`
  - `variablesNeeded` (function, line 1208) `func (s *BlockAttrsSpec) variablesNeeded(`
  - `decode` (function, line 1235) `func (s *BlockAttrsSpec) decode(`
  - `impliedType` (function, line 1306) `func (s *BlockAttrsSpec) impliedType(`
  - `sourceRange` (function, line 1310) `func (s *BlockAttrsSpec) sourceRange(`
  - `findBlock` (function, line 1318) `func (s *BlockAttrsSpec) findBlock(`
  - `visitSameBodyChildren` (function, line 1348) `func (s *BlockLabelSpec) visitSameBodyChildren(`
  - `decode` (function, line 1352) `func (s *BlockLabelSpec) decode(`
  - `impliedType` (function, line 1360) `func (s *BlockLabelSpec) impliedType(`
  - `sourceRange` (function, line 1364) `func (s *BlockLabelSpec) sourceRange(`
  - `findLabelSpecs` (function, line 1372) `func findLabelSpecs(`
  - `visitSameBodyChildren` (function, line 1430) `func (s *DefaultSpec) visitSameBodyChildren(`
  - `decode` (function, line 1435) `func (s *DefaultSpec) decode(`
  - `impliedType` (function, line 1445) `func (s *DefaultSpec) impliedType(`
  - `attrSchemata` (function, line 1450) `func (s *DefaultSpec) attrSchemata(`
  - `blockHeaderSchemata` (function, line 1464) `func (s *DefaultSpec) blockHeaderSchemata(`
  - `nestedSpec` (function, line 1474) `func (s *DefaultSpec) nestedSpec(`
  - `sourceRange` (function, line 1481) `func (s *DefaultSpec) sourceRange(`
  - `visitSameBodyChildren` (function, line 1503) `func (s *TransformExprSpec) visitSameBodyChildren(`
  - `decode` (function, line 1507) `func (s *TransformExprSpec) decode(`
  - `impliedType` (function, line 1525) `func (s *TransformExprSpec) impliedType(`
  - `sourceRange` (function, line 1535) `func (s *TransformExprSpec) sourceRange(`
  - `visitSameBodyChildren` (function, line 1559) `func (s *TransformFuncSpec) visitSameBodyChildren(`
  - `decode` (function, line 1563) `func (s *TransformFuncSpec) decode(`
  - `impliedType` (function, line 1589) `func (s *TransformFuncSpec) impliedType(`
  - `sourceRange` (function, line 1600) `func (s *TransformFuncSpec) sourceRange(`
  - `visitSameBodyChildren` (function, line 1619) `func (s *ValidateSpec) visitSameBodyChildren(`
  - `decode` (function, line 1623) `func (s *ValidateSpec) decode(`
  - `impliedType` (function, line 1644) `func (s *ValidateSpec) impliedType(`
  - `sourceRange` (function, line 1648) `func (s *ValidateSpec) sourceRange(`
  - `decode` (function, line 1658) `func (s noopSpec) decode(`
  - `impliedType` (function, line 1662) `func (s noopSpec) impliedType(`
  - `visitSameBodyChildren` (function, line 1666) `func (s noopSpec) visitSameBodyChildren(`
  - `sourceRange` (function, line 1670) `func (s noopSpec) sourceRange(`
  - `Spec` (interface, line 20)
  - `attrSpec` (interface, line 51)
  - `blockSpec` (interface, line 56)
  - `specNeedingVariables` (interface, line 63)
  - `UnknownBody` (interface, line 69)
  - `AttrSpec` (struct, line 156)
  - `LiteralSpec` (struct, line 243)
  - `ExprSpec` (struct, line 269)
  - `BlockSpec` (struct, line 301)
  - `BlockListSpec` (struct, line 416)
  - `BlockTupleSpec` (struct, line 578)
  - `BlockSetSpec` (struct, line 700)
  - `BlockMapSpec` (struct, line 862)
  - `BlockObjectSpec` (struct, line 1019)
  - `BlockAttrsSpec` (struct, line 1177)
  - `BlockLabelSpec` (struct, line 1343)
  - `DefaultSpec` (struct, line 1425)
  - `TransformExprSpec` (struct, line 1496)
  - `TransformFuncSpec` (struct, line 1554)
  - `ValidateSpec` (struct, line 1614)
  - `noopSpec` (struct, line 1655)
- Depends on: `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`

## teamserver/pkg/profile/yaotl/hcldec/spec_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestDefaultSpec` (function, line 49) `func TestDefaultSpec(`
  - `TestValidateFuncSpec` (function, line 145) `func TestValidateFuncSpec(`

## teamserver/pkg/profile/yaotl/hcldec/variables.go
- Layer: utility
- Language: go
- Symbols:
  - `Variables` (function, line 17) `func Variables(`

## teamserver/pkg/profile/yaotl/hcldec/variables_test.go
- Layer: testing
- Language: go
- Symbols:
  - `TestVariables` (function, line 13) `func TestVariables(`
