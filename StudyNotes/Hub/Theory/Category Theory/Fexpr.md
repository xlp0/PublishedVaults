---
Aliases: fexpr
tags: Lambda Calculus
---

In the context of lambda calculus, a [[fexpr]] (short for "functional expression") is a concept that was introduced by John C. Reynolds in 1972 as an extension to the traditional notion of lambda expressions. Fexprs were proposed as an alternative to macros for handling syntactic abstraction and code generation.

The idea behind fexprs is that they allow for more dynamic behavior during evaluation compared to regular lambda expressions. While lambda expressions are evaluated eagerly, meaning that arguments are evaluated before being passed to a function, fexprs delay the evaluation of their arguments until explicitly requested.

This delayed evaluation allows fexprs to have access to the unevaluated forms of their arguments and manipulate them in arbitrary ways. This makes fexprs powerful tools for implementing advanced control structures and domain-specific languages within lambda calculus.

Fexprs are typically defined as special functions that take unevaluated arguments and evaluate them within a custom environment. This environment may include additional binding rules or syntax transformations specific to the fexpr's behavior.

While fexprs provide enhanced expressive power, they also introduce challenges in terms of formal semantics and reasoning about programs. Reynolds himself acknowledged this difficulty, and subsequent research has attempted to address these issues by providing formal models and semantics for fexpr-based systems.

It's worth noting that fexprs are not commonly used in mainstream programming languages, as they introduce complexities that can make programs harder to understand and reason about. However, they remain an interesting topic of study within the realm of theoretical computer science and programming language design.

# References

[[@shuttFexprsBasisLisp2010]]

[[@okasakiPurelyFunctionalData2003]]

