---
Aliases: Axiomatic Design
---
#matrix #compilation #subjectivity

[[Axiomatic Design]] is a framework used in engineering to systematically design complex systems. It was developed by [[MIT]] Professor [[Nam P. Suh]] in the 1980s. Suh's main contribution to the field of engineering is the development of [[Axiomatic Design]]. This design methodology provides a systematic approach for designing complex systems by establishing axioms or principles that guide the design process.

The fundamental principles of Axiomatic Design are independence axiom and information axiom. 

1. Indepedence Axiom: The independence axiom states that the design should minimize the functional dependencies between its parts to ensure robustness and flexibility. 
2. The information axiom emphasizes that designers should strive to minimize the information content or complexity ([[Change Failure Rate]]) within the system.

Suh's work on Axiomatic Design has been widely recognized and has received numerous accolades including several honorary doctorates, awards, and memberships in prestigious engineering societies. His contributions have significantly influenced engineering practice, particularly in fields like manufacturing, product development, and systems engineering.
## Dynamics of Design Evolution
When taking time into consideration, [[Axiomatic Design]]'s axiom system can be extended to have the additional axiom of Timeliness of change, which relates to the notion of periodicity and other time-based ideas in [[Nam P. Suh|Nam Suh]]'s more recent publications. In any case, these axiomatic principles should all be combined into a coherent measurement metric to pick satisfactory designs out of the space of possible designs. Similar to [[Change Failure Rate]], the other three [[DORA]] system measurement metrics can be incorporated as meta-metrics for Axiomatic Design in general. In other words, it is necessary to take [[System Dynamics]] into the theory of design, especially integrating it with [[Axiomatic Design]].

## Axiomatic Design and Computable Design Contracts
Since [[Axiomatic Design]] relies on matrix calculation, where each matrix can be considered to be a transforming function or operator. This allows all designs to be composed as sequences of matrix transforming operations. More specifically, all these transformation can be encoded in a causal relation, or a [[Hoare triple]], similar to the predicate triple (Given -> When -> Then ) of [[Zencode]] in  [[Zenroom]]. Using a database to capture all these design matrices in [[Zencode]] will provide a consistent design knowledge representation structure, so that it would be convenient in performing complexity assessment. Moreover, it is possible to design a Turing-Complete language for design, using symbolic manipulation libraries such as [[Robert Kragler]]'s [[Symbolic Fractional Part Integrals]], to perform assessment of the probability of success of each design proposition.

## A Meta Mechanism for System Composition
[[Axiomatic Design]] can also be thought of as the foundational language for specifying design, since it is purely based on subjectively selected set of requirements and design parameters, which are considered to be axiomatic. This meta level of design choices, should be linguistically respected, and therefore using something like [[LLVM]] as a foundational data manipulator to compose and decipher the intricate relationships between axiomatic assumptions of design choices.

## Linguistic Operations of Design Requirement Documents
Some parts of design requirements and design parameter statements can be written in [[Natural Language|natural languages]]. By now, it is well known that popular and  [[OSS|open sourced]] [[LLM]] libraries can easily provide assessment of the tone and degree of agreements in pairs of statements. This means that design statements written in the [[Axiomatic Design]] style of atomic components, can be iteratively assessed by [[LLM]] functions, and based on the degree of differences in the tone of design statements, filter or propose different directions in the space of design possibilities. It also can be used to create a safety net or quality control mechanism in all stages of design formulation. To realize this in a coherent data set, these tools and processes can be integrated with [[PKC]] to manage the knowledge of design choices and design knowledge libraries. Providing a generalized mechanism for capturing and refining the knowledge of design given composable linguistic statements.