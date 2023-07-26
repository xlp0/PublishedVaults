---
Aliases: Hilbert Space, Hilbert space
---
#Hilbert_Space #symmetry #Hermitian

Hilbert space, named after the German mathematician David Hilbert, is a fundamental concept in mathematics, particularly in functional analysis and quantum mechanics. It is a specific type of vector space with additional mathematical structures that make it particularly useful in the study of linear algebra, functional analysis, and quantum mechanics.

Formally, a Hilbert space is a complex inner product space that is complete with respect to the norm induced by the inner product. Here's what these terms mean:

1. Complex Inner Product Space: A Hilbert space H is a vector space over the field of complex numbers (denoted by C) equipped with an inner product, denoted by ⟨x, y⟩, that satisfies certain properties. The inner product is a function that takes two vectors x and y in H and maps them to a complex number, denoted by ⟨x, y⟩, satisfying the following properties for all vectors x, y, and z in H and all complex numbers a:

   a. ⟨x, y⟩ = ⟨y, x⟩ (Hermitian symmetry)
   b. ⟨x + y, z⟩ = ⟨x, z⟩ + ⟨y, z⟩ (Linearity in the first argument)
   c. ⟨ax, y⟩ = a ⟨x, y⟩ (Homogeneity in the first argument)
   d. ⟨x, x⟩ ≥ 0, with equality if and only if x = 0 (Positive-definiteness)

2. Completeness: A Hilbert space is also required to be complete with respect to the norm induced by the inner product. Completeness means that every Cauchy sequence (a sequence in which the elements get arbitrarily close to each other) of vectors in H converges to a vector also in H.

The concept of Hilbert space is particularly important in [[Quantum mechanics|quantum mechanics]], where the state of a quantum system is represented by a vector in a Hilbert space. The inner product in the Hilbert space provides a notion of "overlap" or "similarity" between quantum states, which plays a crucial role in understanding quantum interference and entanglement.

In quantum mechanics, physical observables are represented by [[Hermitian operators]], and the eigenstates of these operators correspond to the allowed measurement outcomes. The inner product allows for the calculation of probabilities of obtaining specific measurement outcomes through the Born Rule, which relates the inner product of the quantum state with the eigenstate of the observable to the probability of measuring that eigenstate.

Overall, Hilbert spaces provide a rigorous mathematical framework for understanding quantum mechanics and have applications in various other areas of mathematics and physics.