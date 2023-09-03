
In Category Theory, a product is a notion that generalizes the Cartesian product of sets. Given two objects A and B in a category, their product, denoted as A × B, is an object C along with two projection morphisms π₁: C → A and π₂: C → B. These projection morphisms provide a way to extract elements from the product object.

To be more precise, for any other object X in the category with morphisms f: X → A and g: X → B, there exists a unique morphism h: X → C such that π₁ ∘ h = f and π₂ ∘ h = g. This means that for any object X and pair of morphisms from X to A and B respectively, there is a unique way to "factor" them through the product object C.

# What is a Coproduct?
On the other hand, a coproduct (also known as a sum or disjoint union) is the [[Dual]] notion of a product. Given two objects A and B in a category, their coproduct, denoted as A ⊕ B or sometimes A + B, is an object C along with two injection morphisms i₁: A → C and i₂: B → C. These injection morphisms provide a way to inject elements into the coproduct object.

Formally, for any other object Y in the category with morphisms f: A → Y and g: B → Y, there exists a unique morphism h: C → Y such that h ∘ i₁ = f and h ∘ i₂ = g. This means that for any object Y and pair of morphisms to Y from A and B respectively, there is a unique way to "combine" them through the coproduct object C.

In summary, products represent ways of combining objects together while preserving their individual components (via projections), whereas coproducts represent ways of combining objects together while preserving their distinctness (via injections). They are fundamental concepts in [[Category Theory]] that capture the notions of [[Multiply|multiplication]] and [[Add|addition]], respectively.