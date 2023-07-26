---
aliases: 
- Presheaves
- presheaves
---

[[Presheaf|Presheaves]] are one of the fundamental concepts in sheaf theory, which is a branch of mathematics that studies how local data can be glued together to form global structures. 

In sheaf theory, a [[Presheaf]] is a mathematical object defined on a topological space or on any category with some notion of "open sets" or "covering". It associates to each open set in the space a set (or more generally, an object in some category) and to each inclusion of open sets a map between the associated sets (or objects) that satisfies certain compatibility conditions.

More formally, let X be a topological space and C be a category. A presheaf F on X with values in C consists of the following data:
- For each open set U in X, an object F(U) in C.
- For each inclusion of open sets V ⊆ U, a morphism F(V → U) (also denoted as resU,V: F(U) → F(V)) in C.
- These morphisms must satisfy two compatibility conditions: 
  1. The restriction maps must respect composition, i.e., if W ⊆ V ⊆ U are open sets, then resU,W = resV,W ∘ resU,V.
  2. The restriction maps must respect inclusion, i.e., if W ⊆ V ⊆ U are open sets, then resV,W ∘ resU,V = resU,W.

Intuitively, the presheaf assigns "local" information to each open set in such a way that it can be consistently glued together along overlapping regions.

[[Presheaf|Presheaves]] provide a natural framework for studying sheaves, which are presheaves satisfying additional conditions called the sheaf axioms. Sheaves capture the idea of "gluing" local data to obtain global information and have applications in various areas of mathematics such as algebraic geometry, differential geometry, and algebraic topology. It is also strongly related to [[Category theory]].





