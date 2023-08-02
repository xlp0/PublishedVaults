---
Aliases: Tensor Product, Tensor product, tensor product, tensor products
---
#symmetry

In [[Representation theory|representation theory]], [[Tensor Product|tensor products]] play a crucial role in studying the [[Symmetry|symmetries]] and [[Transformation|transformations]] of mathematical structures. A tensor product is a way to combine two or more representations to obtain a new representation.

In general, let V and W be vector spaces over a field F, and let ρ₁: G → GL(V) and ρ₂: G → GL(W) be two representations of a group G on V and W respectively. The tensor product of these representations, denoted as ρ₁ ⊗ ρ₂, is another representation of G on the vector space V ⊗ W.

The tensor product combines the individual actions of G on V and W to construct a new action on the combined space V ⊗ W. This allows us to study symmetries that arise from both representations simultaneously.

To define the action of G on V ⊗ W, we consider basis elements v ⊗ w in V ⊗ W. The action of g ∈ G on this basis element is given by (ρ₁ ⊗ ρ₂)(g)(v ⊗ w) = ρ₁(g)(v) ⊗ ρ₂(g)(w), where ρ₁(g) and ρ₂(g) are the respective actions of g on v and w.

The resulting representation has several important properties:

1. Associativity: (ρ₁ ⊗ (ρ₂ ⊗ ρ₃)) ≅ ((ρ₁ ⊗ ρ₂) ⊗ ρ₃), where ≅ denotes an isomorphism.
2. Commutativity: (ρ₁ ⊗ ρ₂) ≅ (ρ₂ ⊗ ρ₁), meaning that the order in which we take tensor products does not matter.
3. Compatibility with direct sums: If V = ⨁ᵢVᵢ and W = ⨁ⱼWⱼ are decompositions of V and W, then V ⊗ W = ⨁ᵢⱼ(Vᵢ ⊗ Wⱼ).

Tensor products have many applications in representation theory. They help in understanding the [[Irreducibility|Irreducible]] representations of a group by decomposing tensor products into a direct sum of irreducible representations. They also provide an avenue to study the symmetry properties of composite systems, such as particles with spin or multiple quantum systems.

Overall, tensor products in representation theory provide a powerful tool to investigate the interplay between different symmetries