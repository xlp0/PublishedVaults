---
Aliases: Attention, attention, Attention mechanism
---
#linguistic_thinking #triplet #transformer

## Prelude
By observing how linguists thinks, I realized that they are paying attention to words at a level that surpasses most other people. They can identify patterns in a methodical manner, in languages and expressions that seems to be obscure to most other people. This also implies that there might be some generalized ways to describe how linguistic thinks. More specifically, there might be a mathematical model on how to replicate the [[Attention|attention]] mechanism of linguistics. Such paper actually exists, and that is this famous paper:[[@vaswaniAttentionAllYou2023|Attention Is All You Need]] which gave birth to the massive adoption of [[Large Language Model|Large Language Models]]([[Large Language Model|LLMs]]).
## The most important paper on Attention
In the context of "[[@vaswaniAttentionAllYou2023|Attention Is All You Need]]," attention refers to a mechanism that allows the model to focus on specific parts of the input sequence when making predictions. It is a crucial component in the Transformer architecture, which is a neural network model introduced in the paper "Attention is all you need" by Vaswani et al.
### The pattern of triplets
In the paper, three crucial vectors for computing attention: $Q, K, V$ are universally applied in all stages of computation and used to measure attention across and amongst all words. The three letters represent: [[Query, Key, and Value]] respectively. These vectors are computed for each word in a sentence so that every word has a vector triplet associated with it.

This triple mechanism is similar to [[Lambda Calculus]], where all expressions are composed of only three types of sub-expressions. the $Q, K, V$ triplet is the quintessential building block for assessing where the attention is. Maybe the best analogy of these triplets is like the [[Shape Function|shape functions]] in [[Finite Element Method]]. These triplets are used to assess the attraction or repelling forces amongst all tokens/nodes or just words or phrases in this context of language processing. It can be considered to be the mathematical formulation of [[Hub/Theory/Category Theory/Meta knowledge|Meta knowledge]] or [[Meta Cognitive Functions]].

Attention can be seen as a way for the model to assign importance weights to different elements of the input sequence based on their relevance to each other. In other words, it helps the model determine which parts of the input sequence should receive more attention or have more influence on the predictions.

[[Self-attention]], also known as intra-attention or internal attention, is a specific type of attention mechanism used within Transformers. It allows each element in the input sequence to attend or pay attention to every other element within that same sequence. This means that self-attention captures dependencies and relationships between different positions in the input sequence.

The key difference between attention and self-attention lies in what they attend to. While attention mechanisms in general can attend to any external information, self-attention attends solely to the same input sequence. Self-attention allows each position in the sequence to consider all other positions when determining its own representation, enabling it to capture long-range dependencies efficiently.

Self-attention operates by computing three vectors for every position in an input sequence: Query, Key, and Value vectors. These vectors are used to calculate attention scores between positions and compute weighted sums of values based on these scores. It is also related or comparable to an idea called: [[Cross Attention]]. There is also a notion of [[Multi-Head Attention]].

## My interpretation of what Attention is
Linguistic [[Attention]] in a mathematical sense, is a sequential structure, often one-dimensional, that uses the topological positioning of words to create an order/sequence-induced filtering function to identify possible words connecting to the unfilled slots of a sentence. This order-induced, or permutation-induced combinatorial expressiveness, is the reason why languages are so effective, and so natural to be used for communication, and for inferences. By putting this structure in a computer, where multi-dimensional structures can be manipulated using generalized matrix multiplication methods to construct arbitrary complex filtering functions, the ability to use nothing but high-powered matrix multiplication computers becomes a self-evidence instrument to perform language processing and language manipulation, or sentence generation.

# Conclusion
In summary, attention refers to a mechanism that focuses on specific parts of an input sequence during prediction. Self-attention is a specific type of attention mechanism used within Transformers where each position attends to all other positions in the same sequence, capturing relationships and dependencies effectively.


## References
[[@vaswaniAttentionAllYou2023]]