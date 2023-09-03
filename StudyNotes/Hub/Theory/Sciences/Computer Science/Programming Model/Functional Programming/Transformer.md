---
Aliases: Transformer, transformer
---
#AI #ML #encoder #decoder

In the paper "[[Attention]] is All You Need," the authors introduced a novel neural network architecture called [[Transformer]], which has since become a widely used model in natural language processing tasks such as machine translation and text generation.

The Transformer model is based entirely on self-attention mechanisms and does not rely on recurrent or convolutional layers commonly used in traditional sequence-to-sequence models. It consists of an encoder and a decoder, both built with stacks of identical layers. Here, we will focus on the encoder's working mechanism.

The encoder of the Transformer consists of several identical layers, each composed of two sub-layers: a multi-head self-attention mechanism and a position-wise fully connected feed-forward network. Let's dive into these components:

1. Multi-head Self-Attention Mechanism:
This attention mechanism allows the model to weigh different words in an input sequence differently based on their relevance to each other. It computes three vectors for each word: Query (Q), Key (K), and Value (V). These vectors are linear projections of the word embeddings.
- For each word in the input sequence, attention scores are computed with respect to all other words in the same sequence using dot product between Q and K vectors.
- The attention scores are scaled by dividing them by the square root of the dimensionality of Q/K/V vectors.
- The softmax function is then applied to obtain attention weights, representing how much each word attends to others.
- Finally, weighted sum of Value (V) vectors using attention weights produces the output for each word.

2. Position-wise Feed-Forward Network:
After obtaining self-attention outputs from all words in parallel, position-wise feed-forward networks are applied individually to each word representation.
- This sub-layer consists of two linear transformations followed by a non-linear activation function like ReLU.
- It helps capture complex dependencies between different positions within sequences.

These two sub-layers use residual connections followed by layer normalization to stabilize the learning process and improve gradient flow. Additionally, the encoder also uses positional encoding to provide information about the position/order of words in the input sequence.

By stacking multiple layers of self-attention and position-wise feed-forward sub-layers, the Transformer model can capture long-range dependencies and effectively model relationships between words in a sequence. The self-attention mechanism allows it to attend to relevant parts of the input at different positions, enabling efficient parallelization during training and inference.

Overall, the Transformer's working mechanism demonstrates how attention mechanisms can be employed effectively for sequence modeling tasks without relying