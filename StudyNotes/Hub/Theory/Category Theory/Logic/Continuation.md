In computer science, continuation refers to a programming construct that represents the future execution of a program. It is an abstract representation of the control state of a computer program at a specific point in its execution.

More specifically, a continuation captures the current state of a program's execution context, including the values of variables, the point from where it was called, and any pending computations. It can be thought of as a data structure that represents the "rest" of the computation that needs to be executed after a particular point in the program.

Continuations are often used in programming languages or frameworks that support advanced control-flow mechanisms such as non-local exits, exception handling, or coroutines. They allow for flexible and powerful control flow manipulation by capturing and manipulating the current execution state.

For example, continuations can be used to implement features like generators or cooperative multitasking. They can also be used for error handling by capturing an exception state and allowing it to propagate up through different levels of function calls.

## Who created the notion of Continuation?

The notion of Continuation was created by computer scientist and mathematician [[Christopher Strachey]] and extended by [[Dana Scott]].

Overall, continuations provide a way to save and restore program execution states dynamically, enabling more flexible control flow and advanced programming techniques.