---
Aliases: QKV, Query, Key, and Value
---
#triplet

In the "Attention is All You Need" paper, Query, Key, and Value ($Q, K, V$) are three vectors used in the assessment of attention. These vectors are strategically important because they enable the model to effectively capture the relationships between different words in a sequence.

The Query vector represents the word that we want to focus on or pay attention to. It is compared with other words in the sequence to determine their relevance or importance. 

The Key vector represents each word in the sequence and is used to compute similarity scores with the Query vector. These similarity scores indicate how relevant each word is to the Query word.

Finally, the Value vector holds information about each word's representation or meaning. It contains useful contextual information that can be extracted when attention is applied. The [[Attention|attention mechanism]] uses these similarity scores, obtained by comparing Query ($Q$) and Key ($K$) vectors, to weight the corresponding Value ($V$) vectors.

By utilizing these three vectors together, attention mechanisms can effectively identify which words are most relevant or important given a specific context. This approach allows models to focus on different parts of a sequence dynamically, depending on what information is most salient for a given task or computation.

Overall, Query, Key, and Value ($Q,K,V$) vectors play a crucial role in performing assessment of attention by enabling models to selectively attend to specific parts of a sequence and extract relevant information for various natural language processing tasks. The idea of three kinds of assessment metrics, on [[Relevance]], [[Similarity]], and [[Weight]] respectively. This means that 

# References

[[@vaswaniAttentionAllYou2023]]