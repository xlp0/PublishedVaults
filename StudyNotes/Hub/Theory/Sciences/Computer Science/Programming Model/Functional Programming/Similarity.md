---
Aliases: Similarity, similarity
---
#similarity #attention 

The paper "Attention Is All You Need" introduces the concept of a $K$ vector, which is used to measure similarity in the context of large language models. In this paper, the authors propose a novel architecture called the Transformer, which relies solely on self-attention mechanisms to capture relationships between words in a sentence.

In the Transformer model, each word has an associated K vector, which represents its content and is used to calculate attention scores. The K vector of a word is computed based on its embedding and positional encoding. By comparing the K vectors of different words, one can determine their similarity.

However, it's important to note that the notion of similarity in this context is not necessarily equivalent to semantic or syntactic similarity as traditionally defined. Instead, it refers to how likely two words are related or connected within the given language model. The similarity measured by comparing K vectors reflects the ability of the model to attend or pay attention to specific words when processing others.

For example, if two words have similar K vectors, it suggests that they share similar contextual information and may have some form of relationship within the language model. This allows the Transformer model to capture dependencies between words that are distant from each other in a sentence.

In summary, in the large language model sense, similarity refers to how closely related or connected two words are within the context of a given sentence or text. The comparison of K vectors helps identify such similarities and enables effective attention mechanisms in capturing dependencies between words across long distances.


# References

[[@vaswaniAttentionAllYou2023]]