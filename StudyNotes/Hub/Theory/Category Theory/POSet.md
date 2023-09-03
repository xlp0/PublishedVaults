---
Aliases: POSet, Partially Ordered Set, partially ordered-set
---
#POSet #lattice 

A Partially Ordered Set ([[POSet]]) is a mathematical structure that consists of a set of elements along with a binary relation that partially orders the elements. This binary relation, denoted as ≤, must satisfy three properties: reflexivity, antisymmetry, and transitivity.

Reflexivity means that every element is related to itself: for every element a in the POSet, a ≤ a. Antisymmetry states that if two elements are related in both directions, they must be the same element: if a ≤ b and b ≤ a, then a = b. Transitivity means that if one element is related to another and the second element is related to a third, then the first element must also be related to the third: if a ≤ b and b ≤ c, then a ≤ c.

Partially Ordered Sets have many applications in various fields such as computer science, mathematics, physics, and social sciences. They provide an abstract way to represent relationships between objects or concepts where there may not always be a clear total ordering.

When it comes to universal constructs, Partially Ordered Sets play an important role. Universal constructs are mathematical structures or models that are able to capture fundamental properties or behaviors of various systems or phenomena. POSets can often serve as universal constructs by providing an abstract framework for studying orderings and relationships between objects.

[[Dana Scott]]'s [Outline of a Mathematical Theory of Computation](@scottOutlineMathematicalTheory1977) is an influential paper published by Dana Scott in 1970. In this paper, Scott introduced domain theory as an approach to formalizing computation and reasoning about programs. Domain theory utilizes Partially Ordered Sets called domains to model the behavior of programs and computations.

Scott's Outline of Theory of Computation laid the foundation for denotational semantics in programming languages and provided a theoretical framework for understanding program semantics based on Partially Ordered Sets. The paper highlighted the importance of domains as universal constructs for studying computation and introduced concepts such as continuous functions, fixed points, and algebraic structures within the domain-theoretic framework.

## What does Ordered Sets have to do with Causal structures?

[[Causation|Causal structures]] are mathematical models used to represent cause-and-effect relationships between events or variables. In the context of causal structures, ordered sets can be used to define a partial order relation among events or variables.

An ordered set is a set equipped with a binary relation that is reflexive, antisymmetric, and transitive. In the context of causal structures, this binary relation represents the causal relationship between events or variables. It defines which event or variable comes before or after another in terms of causality.

By using ordered sets in causal structures, we can represent the temporal ordering of events or variables based on their causality. This allows us to analyze and understand the causal relationships between different elements in a system. Ordered sets provide a way to establish a partial order that captures the cause-and-effect relationships within a given context or system.

# Conclusion

Overall, Partially Ordered Sets are a fundamental mathematical structure that finds applications in various fields. They also serve as universal constructs for studying relationships and orderings between objects. In the context of computation, Dana Scott's Outline of Theory of Computation introduced domain theory and highlighted the role of Partially Ordered Sets as domains for modeling program behavior and computation.

# References

[Outline of a Mathematical Theory of Computation](@scottOutlineMathematicalTheory1977) by [[Dana Scott]]

[[@hamiltonTHEORYCONJUGATEFUNCTIONS|Algebraic Couples as the Science of Pure Time]] by [[William Hamilton]]