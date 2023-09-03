---
Aliases: Correctness, correctness, correct, System Correctness, system correctness
---
#correctness #worse_than_all_wrong

From a logical viewpoint, correctness refers to the property of a program or system that guarantees its behavior is in accordance with its intended specification or requirements. In other words, it means that the program does what it is supposed to do and produces the desired outcomes.

[[Antony Hoare]], a British computer scientist and Turing Award recipient, defines [[Correctness|correctness]] in terms of partial correctness and total correctness. According to Hoare's definition:

1. Partial Correctness: A program is partially correct if whenever it terminates, it satisfies its postcondition. The postcondition specifies the desired outcome or state that should hold true after the program execution.

2. Total Correctness: A program is totally correct if it is both partially correct and guaranteed to terminate for any input within a finite amount of time.

Hoare introduced the concept of preconditions and postconditions as well. Preconditions define the conditions that must be met before executing a program, while postconditions define the conditions that should hold true after executing the program. By ensuring that these conditions are satisfied, one can reason about the correctness of a program using formal methods such as Hoare logic or axiomatic semantics.

## Safety and Liveness
What are safety and liveness in the literature of logical correctness

[[Safety]] and [[Liveness|liveness]] are two important concepts in the literature of logical correctness, specifically in the field of formal verification and concurrent systems.

[[Safety]]: Safety properties refer to the absence of certain undesirable states or behaviors in a system. They define what should never happen during the execution of a system. A safety property ensures that no matter how a system evolves, it will never enter an invalid state or violate certain predefined conditions. Safety properties are typically expressed as logical formulas that specify constraints on the system's behavior.

For example, in a concurrent system, safety properties can guarantee mutual exclusion, meaning that only one process can access a shared resource at a time. Violating such safety properties may lead to race conditions or data corruption.

[[Liveness]]: Liveness properties, on the other hand, describe desirable behaviors that should eventually occur in a system. They ensure progress and state that something good will happen eventually. Liveness properties focus on reaching certain states or events without specifying any particular order or timing.

## Correctness in AI and Machine Learning (LLM)
In a talk by [[Thomas G. Dietterich]], the notion that AI/ML in the form of [[ChatGPT]] and [[LLM]]s can easily mislead people at scale, and it is a form and constant and present danger. Therefore, developing tools and infrastructures that focuses on [[Correctness|correctness]] at the content level is very important.

## Approximating Correctness
[[Patrick Cousot]] developed [[Abstract Interpretation]], a static program analysis technique that aims to approximate the behaviors and properties of a program, in other words, approximating [[Correctness|correctness]] computationally. One of the key aspects of abstract interpretation is handling the trade-off between precision and efficiency. Correctness approximation is an inherent part of this trade-off.

In abstract interpretation, the concrete semantics of a program, which represents the exact behavior of the program, is abstracted into an abstract domain. The abstract domain provides an over-approximation or approximation of the concrete behaviors. This approximation allows for more efficient analysis but sacrifices some precision.


## Applications

For example, liveness properties can specify that every request for a shared resource should eventually be granted (eventual progress). Violating liveness properties may result in deadlocks or livelocks where processes become blocked and cannot make any progress.

Another example is that data can be intentionally hacked to induce incorrect answers. By intentionally mixing results that are sometimes good, and sometimes bad, causing even more damage than just having all bad answers, the ultimate challenge to [[Correctness|correctness]] verification. See the following video on [[@matthewbermanPoisonGPTHackingAI2023|PoisonGPT - Hacking AI Just Became Reality]]. A major concern of the [[Generative Artificial Intelligence|Generative AI]] driven world.

### An Automation Scheme for Multi-scale Correctness Verification
With the massive content data provided by [[Large Language Model]] and [[Generative Artificial Intelligence|Generative AI]], it is plausible to significantly streamline the automated workflow of complex/freeformed data content and algorithm verification. The verification workflow can be constructed as a [[DevOps]] process that utilizes a generalized, multi-scale data processing kernel that leverages [[REPL]] at its core, and tools such as interactive mind mapping software, such as [[Obsidian]] at the front end. The composition of these software components can be integrated using [[Langchain]], and data exchange formats can be based on textual streams that follows the [[Open API]] standard. Recent work in [[Generative Artificial Intelligence|Generative AI]] that uses [[Tool-LLM]] to dynamically generate [[SOTA]] solutions using [[DFSDT]] is a promising concept in operationalizing approximation with [[State of the Art]]([[SOTA]]) results.

## Conclusion

In summary, safety and liveness properties are used to formally reason about the correctness of complex systems by defining what should not happen ([[Safety|safety]]) and what should eventually happen ([[Liveness|liveness]]). Both safety and liveness play crucial roles in ensuring the logical correctness of systems and are often checked using formal [[Verification|verification]] techniques like model checking or theorem proving.

## References

[[@matthewbermanPoisonGPTHackingAI2023]]

[[@dijkstraCrueltyReallyTeaching2022]]

[[Correctness of Distributive Accountability.canvas|Correctness of Distributive Accountability]]