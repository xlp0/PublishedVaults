---
Aliases: Self-attention, self-attention
---

Self-attention, also known as intra-attention or inner attention, is a mechanism commonly used in [[Machine Learning]] Transformers. It allows the model to weigh the importance of different positions within its own input sequence in order to make predictions or generate outputs.

In traditional neural network architectures, inputs are processed independently and sequentially, which can limit their ability to capture long-range dependencies. Self-attention addresses this limitation by considering all positions of the input sequence simultaneously and allowing the model to focus on different parts of the sequence as needed.

The concept of self-attention involves three main components: queries, keys, and values. These components are derived from the input sequence using learned linear transformations. The queries represent positions that need information from other positions, while the keys and values represent all positions in the sequence.

To compute self-attention, each query is compared with all keys to determine its relevance to different positions. This is done by computing a similarity score between each query-key pair using dot product or other similarity measures. The scores are then scaled and transformed into [[Attention|attention]] weights through a softmax function, which ensures that the weights sum up to 1.

Once attention weights are obtained, they are used to weigh the corresponding values. The weighted values are then aggregated to form a weighted sum representation called the attention output. This output captures information from relevant positions in the input sequence based on their importance as determined by the attention weights.

Self-attention can be applied multiple times in parallel within a transformer model by incorporating multiple attention heads. Each attention head learns different patterns and dependencies in the input sequence, allowing for richer representations. The outputs of these heads are typically concatenated or linearly combined before being passed through subsequent layers of the transformer.

Self-attention has been widely adopted in various natural language processing tasks such as machine translation, text summarization, question answering, and sentiment analysis. It has proven effective in capturing both local and global dependencies in sequential data, leading to improved performance compared to traditional recurrent neural networks or convolutional neural networks.

## References
[[@vaswaniAttentionAllYou2023]]