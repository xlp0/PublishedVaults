---
Aliases: Completeness, completeness, Complete, complete, 完備，完備性
---
#completeness #correctness #reason 

In [[Abstract Interpretation|abstract interpretation]], completeness refers to the property of an analysis that ensures that all possible concrete behaviors or properties are captured by the corresponding abstract domain. It guarantees that the abstract interpretation technique can accurately represent and analyze all behaviors or properties of the program within the chosen abstraction.

Completeness is a desirable property because it provides assurance that the analysis does not miss any relevant information or introduce false negatives. It ensures that if a property holds in the concrete semantics of the program, it will also be detected by the analysis in the abstract domain.

To achieve completeness, the abstract domain used in abstract interpretation should be expressive enough to represent all possible concrete behaviors. It should be able to distinguish between different program states, behaviors, or properties that may be relevant for the analysis.

However, achieving completeness is challenging in practice. It often comes at the cost of increased computational complexity and resource requirements. A more expressive abstract domain may result in a more intricate analysis that is computationally expensive or even undecidable in some cases.

Therefore, in most cases, abstract interpretation techniques prioritize [[Soundness|soundness]] over [[Completeness|completeness]]. Soundness ensures that the analysis does not produce false positives, even if it may miss some behaviors or properties. Soundness is a critical property that guarantees the reliability and correctness of the analysis results.

It's important to note that completeness in abstract interpretation is relative to the chosen abstraction and the specific analysis goals. It is impossible to achieve absolute completeness in abstract interpretation due to the inherent trade-off between expressiveness and computational tractability.

In summary, completeness in abstract interpretation refers to the property of an analysis that ensures that all possible concrete behaviors or properties are captured within the chosen abstract domain. It guarantees that the analysis does not miss relevant information but comes at the cost of increased computational complexity. However, soundness is typically prioritized over completeness to ensure the reliability and correctness of the analysis results.