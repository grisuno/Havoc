# teamserver/pkg/profile/yaotl/ext/customdecode

*Community 4 | 5 files | cohesion 1.00*

## Definition

This community groups 5 file(s) rooted at `teamserver/pkg/profile/yaotl/ext/customdecode` with dominant language go (cohesion 1.00). Central symbols: `AnonSymbolExpr`, `AsTraversal`, `AttrSpec`, `BlockAttrsSpec`, `BlockLabelSpec`, `BlockListSpec`, `BlockMapSpec`, `BlockObjectSpec`. Core file: `teamserver/pkg/profile/yaotl/hcldec/spec.go` (122 symbols). Documented purpose: Package customdecode contains a HCL extension that allows, in certain contexts, expression evaluation to be overridden by custom static analysis.  This mechanis.

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go` | go | utility | 1 | yes |
| `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go` | go | utility | 4 | yes |
| `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go` | go | utility | 3 | no |
| `teamserver/pkg/profile/yaotl/hcldec/spec.go` | go | testing | 122 | no |
| `teamserver/pkg/profile/yaotl/hclsyntax/expression.go` | go | utility | 76 | no |

## Key Symbols

- `CustomExpressionDecoderForType` (function, `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go:48`) `func CustomExpressionDecoderForType(` - CustomExpressionDecoderForType takes any cty type and returns its custom expression decoder implemen
- `init` (function, `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:30`) `func init(`
- `try` (function, `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:61`) `func try(`
- `can` (function, `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:109`) `func can(`
- `dependsOnUnknowns` (function, `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go:130`) `func dependsOnUnknowns(` - dependsOnUnknowns returns true if any of the variables that the given expression might access are un
- `TypeConstraintVal` (function, `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:26`) `func TypeConstraintVal(` - TypeConstraintVal constructs a cty.Value whose type is TypeConstraintType.
- `TypeConstraintFromVal` (function, `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:35`) `func TypeConstraintFromVal(` - TypeConstraintFromVal extracts the type from a cty.Value of TypeConstraintType that was previously c
- `init` (function, `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go:57`) `func init(`
- `Spec` (interface, `teamserver/pkg/profile/yaotl/hcldec/spec.go:20`) - A Spec is a description of how to decode a hcl.Body to a cty.Value.  The various other types in this
- `attrSpec` (interface, `teamserver/pkg/profile/yaotl/hcldec/spec.go:51`) - attrSpec is implemented by specs that require attributes from the body.
- `blockSpec` (interface, `teamserver/pkg/profile/yaotl/hcldec/spec.go:56`) - blockSpec is implemented by specs that require blocks from the body.
- `specNeedingVariables` (interface, `teamserver/pkg/profile/yaotl/hcldec/spec.go:63`) - specNeedingVariables is implemented by specs that can use variables from the EvalContext, to declare
- `UnknownBody` (interface, `teamserver/pkg/profile/yaotl/hcldec/spec.go:69`) - UnknownBody can be optionally implemented by an hcl.Body instance which may be entirely unknown.
- `visitSameBodyChildren` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:73`) `func (s ObjectSpec) visitSameBodyChildren(`
- `decode` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:79`) `func (s ObjectSpec) decode(`
- `impliedType` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:92`) `func (s ObjectSpec) impliedType(`
- `sourceRange` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:104`) `func (s ObjectSpec) sourceRange(`
- `visitSameBodyChildren` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:115`) `func (s TupleSpec) visitSameBodyChildren(`
- `decode` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:121`) `func (s TupleSpec) decode(`
- `impliedType` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:134`) `func (s TupleSpec) impliedType(`
- `sourceRange` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:146`) `func (s TupleSpec) sourceRange(`
- `AttrSpec` (struct, `teamserver/pkg/profile/yaotl/hcldec/spec.go:156`) - An AttrSpec is a Spec that evaluates a particular attribute expression in the body and returns its r
- `visitSameBodyChildren` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:162`) `func (s *AttrSpec) visitSameBodyChildren(`
- `variablesNeeded` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:167`) `func (s *AttrSpec) variablesNeeded(` - specNeedingVariables implementation
- `attrSchemata` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:177`) `func (s *AttrSpec) attrSchemata(` - attrSpec implementation
- `sourceRange` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:186`) `func (s *AttrSpec) sourceRange(`
- `decode` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:195`) `func (s *AttrSpec) decode(`
- `impliedType` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:237`) `func (s *AttrSpec) impliedType(`
- `LiteralSpec` (struct, `teamserver/pkg/profile/yaotl/hcldec/spec.go:243`) - A LiteralSpec is a Spec that produces the given literal value, ignoring the given body.
- `visitSameBodyChildren` (function, `teamserver/pkg/profile/yaotl/hcldec/spec.go:247`) `func (s *LiteralSpec) visitSameBodyChildren(`

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 4
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- [INFERRED] shares_context community 0 <-> 4 (strength 0.5): Inferred shared context (layer utility) with no import path between community 0 (payloads/Demon/include/core) and community 4 (teamserver/pkg/profile/yaotl/ext/customdecode).
- [INFERRED] shares_context community 2 <-> 4 (strength 0.5): Inferred shared context (language go and layer utility) with no import path between community 2 (teamserver/cmd/server) and community 4 (teamserver/pkg/profile/yaotl/ext/customdecode).

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 3 file(s) lack file-level docs (e.g. `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go`)? What purpose do they serve?
- What would break if the most connected file in teamserver/pkg/profile/yaotl/ext/customdecode changed?
- Should teamserver/pkg/profile/yaotl/ext/customdecode be split, given cohesion 1.00?

## Sources

- `teamserver/pkg/profile/yaotl/ext/customdecode/customdecode.go`
- `teamserver/pkg/profile/yaotl/ext/tryfunc/tryfunc.go`
- `teamserver/pkg/profile/yaotl/ext/typeexpr/type_type.go`
- `teamserver/pkg/profile/yaotl/hcldec/spec.go`
- `teamserver/pkg/profile/yaotl/hclsyntax/expression.go`
