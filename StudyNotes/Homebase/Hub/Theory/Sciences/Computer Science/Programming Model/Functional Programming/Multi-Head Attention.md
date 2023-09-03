
#attention 
In the paper "Attention is All You Need" by Vaswani et al., multi-head attention is introduced as a key component of the transformer model for sequence-to-sequence tasks such as machine translation. 

[[Attention|Attention mechanisms]] allow the model to focus on different parts of the input sequence when making predictions. In traditional attention, a single attention function is used to compute the relevance or importance of each token in the input sequence with respect to a query token. However, the authors propose using multiple parallel attention functions, known as heads, to capture different types of dependencies and information.

Each head has its own set of learnable parameters and operates independently. The input to each head is linearly transformed into three different representations: queries, keys, and values. These transformations are learned during training.

The computation for each head follows three steps:
1. Query-key similarity calculation: Each query is compared with all keys using dot product and scaled by square root of the dimensionality for stability.
2. Attention weight calculation: The similarities are passed through a softmax function which produces attention weights indicating how much each key contributes to a given query.
3. Weighted sum of values: The attention weights are applied to their corresponding values and summed up to produce an output representation.

After applying multi-head attention, the outputs from all heads are concatenated and linearly transformed again to obtain the final output representation.

By using multiple heads, the model can capture different types of dependencies or patterns at different positions in the sequence more effectively. Each head has its own perspective on how to attend over the input tokens and can focus on different aspects such as syntactic structure or semantic meaning.

Multi-head attention allows for parallelization since each head can be computed independently, which leads to faster training and inference compared to traditional sequential attention mechanisms.

Overall, multi-head attention is a crucial component in transformer models that enables them to effectively model relationships between tokens in an input sequence by capturing various types of dependencies in a parallel and efficient manner.

## References
[[@vaswaniAttentionAllYou2023]]