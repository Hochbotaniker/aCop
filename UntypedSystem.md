## Untyped System/ untyped arithmetic expressions

### Grammar
describes the structure of all prgrams as tree  
*concrete grammar* avoids ambiguity, syntactic elements for readability, relation between tree-form (if ...then... else) and linearized form of expressions (iszero(pred(succ0));  

numbers + constant zero -> numeric values  
true + false -> values  
conditional and zerto test -> terms

### Syntax by inductive definition

**DEFINITION [TERMS,INDUCTIVELY]** set of *terms* is the smallest (no other elements) set *T* such that:  
{true,false,0} in T;  
if t1 e T then {succ t1, pred t1, iszero t1} in T;  
if t1 e T, t2 e T, t3 e T then if t1 then t2 else t3 e T;  

**DEFINITION [TERMS, BY INFERENCE RULES]**  

true e T (axiom)  
  
established premise -> derive conclusion  

inference rule schemas may include metavariables

### Syntax by construction

**DEFINITION [TERMS, CONCRETELY]**  
for each i define a Set si: S0 empty, Si+1 = ...  
  
  hier sollte man nen assigment machen
  
### Equivalent definition of terms (FOLIE 10)
