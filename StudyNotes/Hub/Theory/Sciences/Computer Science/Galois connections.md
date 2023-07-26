---
Aliases: galois connections, Galois connections
---
#abstract_interpretation #reason #Symmetry 

[[Galois connections]] play a fundamental role in abstract interpretation, providing a mathematical framework for establishing relationships between concrete and abstract domains. They allow for the formal connection between the concrete semantics of a program and the abstract semantics used in abstract interpretation.

In abstract interpretation, a Galois connection is a pair of monotonic functions that establish a correspondence between two partially ordered sets, typically the concrete domain and the abstract domain.

Let's consider a Galois connection between a concrete domain C and an abstract domain A:

1. Concrete-to-Abstract Direction:
    
    - The abstraction function α: C → A takes a concrete element from the concrete domain and maps it to an abstract element in the abstract domain. The abstraction function captures the relevant information about the concrete element while ignoring irrelevant details. It abstracts the concrete semantics into a simpler and more manageable representation.
2. Abstract-to-Concrete Direction:
    
    - The concretization function γ: A → C takes an abstract element from the abstract domain and maps it back to a set of concrete elements in the concrete domain. The concretization function provides a way to obtain a set of concrete elements that are consistent with the given abstract element. It provides a bridge between the abstract domain and the concrete semantics, allowing for the interpretation of abstract values in terms of concrete values.

The Galois connection between the abstraction and concretization functions ensures that certain relationships hold:

- Galois Insertion: For any concrete element c in C and abstract element a in A, the abstraction function α is a lower adjoint of the concretization function γ if γ(a) ⊆ c if and only if a ⊑ α(c). This property captures the idea that the abstraction is a sound approximation, preserving the ordering between concrete and abstract elements.
    
- Galois Galois Connection: For any concrete element c in C and abstract element a in A, the abstraction function α is an upper adjoint of the concretization function γ if γ(a) ⊇ c if and only if a ⊒ α(c). This property captures the idea that the abstraction is a complete approximation, encompassing all possible concrete elements consistent with the abstract element.
    

Galois connections facilitate the transfer of information between the concrete and abstract domains. They provide a formal basis for reasoning about the correctness and precision of abstract interpretation techniques. By establishing a mathematical relationship between the concrete and abstract semantics, Galois connections allow for the soundness and completeness of abstract interpretation analyses.

In summary, Galois connections in abstract interpretation establish a formal correspondence between the concrete and abstract domains. They consist of an abstraction function that maps concrete elements to abstract elements and a concretization function that maps abstract elements back to sets of concrete elements. Galois connections ensure the [[Soundness|soundness]] and [[Completeness|completeness]] of the abstraction, allowing for the transfer of information between the concrete and abstract semantics.