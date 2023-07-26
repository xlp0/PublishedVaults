---
Aliases: Hoare triple, Hoare logic, Hoare notation
---

A Hoare triple is a formal notation used to specify the correctness of a computer program or algorithm. It was introduced by British computer scientist [[Antony Hoare|Tony Hoare]] and is also known as [[Hoare triple|Hoare logic]] or [[Hoare triple|Hoare notation]].

In a Hoare triple, there are three parts: a precondition, a command, and a postcondition. The precondition describes the state of the program before executing the command, while the postcondition describes the expected state after executing the command.

The notation for a Hoare triple is {P} C {Q}, where P represents the precondition, C represents the command, and Q represents the postcondition. P and Q are logical assertions that describe properties or conditions that hold true about variables or program states.

The precondition specifies what must be true before executing the command in order for it to start correctly. It typically includes initial values of variables and any necessary conditions for execution.

The postcondition specifies what must be true after executing the command in order for it to terminate correctly. It describes any changes made to variables or program states due to the execution of the command.

Hoare triples are used in formal verification techniques such as program proving and model checking. They provide a way to reason about program correctness by mathematically specifying desired properties and verifying if those properties hold true after program execution.

By using Hoare triples, programmers can formally reason about their programs' behavior, ensure correctness, and detect potential bugs or errors early in development. They also aid in designing test cases that cover all possible scenarios according to specified preconditions and postconditions.

Overall, Hoare triples provide a powerful method for specifying and verifying program correctness using logical assertions before and after executing commands.