
In category theory, Kan extensions are a way to extend functors along other functors. They provide a general framework for understanding and formalizing various concepts in mathematics and computer science. 

The concept of Kan extensions was introduced by [[Daniel Kan]] in the 1950s as an extension of the Yoneda embedding, which is a fundamental result in category theory. The Yoneda embedding allows us to represent objects in a category as functors from that category to the category of sets. 

Kan extensions generalize this idea by allowing us to extend functors along other functors. Given two categories A and B, and two functors F: A → B and G: A → C, where C is another category, a left Kan extension of F along G is a functor L: C → B that extends F in a certain way.

Intuitively, this means that for any object c in C, the functor L maps it to an object L(c) in B such that there exists a natural transformation from F to L composed with G. This natural transformation captures the relationship between F and L when restricted to objects in A.

Similarly, a right Kan extension is defined when we reverse the direction of the functors involved.

Kan extensions have many applications across different areas of mathematics such as algebraic topology, algebraic geometry, and computer science. They provide a powerful tool for studying universal properties, adjunctions, limits, colimits, and representable functors.

The origin of this mathematical formulation of concepts can be traced back to the desire for abstracting fundamental ideas across different branches of mathematics. Category theory emerged as an attempt to unify various mathematical structures and theories under one framework. The concept of [[Kan extensions]] is one of the many formalisms developed within category theory with the goal of providing general tools for analyzing mathematical concepts and their relationships.

Overall, Kan extensions play a crucial role in understanding concepts within category theory and provide a powerful tool for analyzing and generalizing ideas across different mathematical domains.

# References

[[@lehnerAllConceptsAre|All Concepts are Kan Extensions: the "Most" Universal Construct]]