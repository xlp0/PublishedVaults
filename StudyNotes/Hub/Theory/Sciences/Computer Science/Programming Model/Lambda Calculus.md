---
Aliases: $\lambda$ Calculus, Lambda Calculus, λ-Calculus
---
#triplet

[[Lambda calculus]] ([[Lambda Calculus|λ-Calculus]]) is a formal system in mathematical logic and computer science that was developed by Alonzo Church in the 1930s. It is a universal model of computation, meaning that any computable function can be represented and evaluated within the lambda calculus.

At its core, lambda calculus is based on the concept of functions and function application. It uses lambda expressions, which are anonymous functions that can take one or more arguments and return a result. These expressions consist of three elements: variables, abstraction, and application.

Variables in lambda calculus are placeholders for values or arguments. Abstraction allows the creation of lambda expressions by binding variables within a function. The syntax for abstraction is λx.M, where x represents the variable being bound and M represents the body of the function.

The most fundamental operation in lambda calculus is application. It allows the evaluation of a function with specific arguments by replacing variables in an expression with those arguments. The syntax for application is (λx.M) N, where (λx.M) represents a lambda expression and N represents an argument or value to be substituted into it.

Lambda calculus has no built-in data types or constants; everything is expressed through functions and their applications. This simplicity makes it an ideal model for studying computation at its most fundamental level. In fact, lambda calculus forms the basis of functional programming languages like Haskell and forms an important part of modern computer science theory.

One notable feature of lambda calculus is its ability to define recursive functions using fixed-point combinators. These combinators allow self-reference within a function definition, enabling recursion without explicit naming.

Lambda calculus also supports higher-order functions, which means that functions can take other functions as arguments or return them as results. This higher-order functionality allows for powerful abstractions and modular programming techniques.

Overall, lambda calculus provides a theoretical framework for understanding computation through pure functional programming principles. Its simplicity yet expressive power has made it influential in various areas such as programming language design, type theory, and formal verification.
# References


![[Backus-Naur Form#How is BNF related to lambda calculus?]]