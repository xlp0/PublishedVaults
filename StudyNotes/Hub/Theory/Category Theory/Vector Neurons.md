#triplet #invariant #symmetry #NN #quarternions 


[[Vector Neurons]] is a general framework for creating SO(3) equivariant neural networks, introduced by [[Congyue Deng]], Or Litany, Yueqi Duan, Adrien Poulenard, Andrea Tagliasacchi, and Leonidas Guibas in their paper "Vector Neurons: A General Framework for SO(3)-Equivariant Networks" (2021).

SO(3) is the group of 3D rotations, and equivariance means that a neural network will produce the same output if its input is rotated. This is important for tasks such as object recognition and scene understanding, where the objects in the scene may be rotated in different ways.

Vector Neurons achieve equivariance by extending neurons from single scalars to 3D vectors. This allows them to represent the full rotation group, and to transport SO(3) actions to latent spaces. Vector Neurons can be used to build equivariant versions of common neural operations, such as linear layers, non-linearities, pooling, and normalization. 
## Unique Features of Vector Neurons

Vector Neurons have been shown to be effective for a variety of tasks, including object recognition, scene understanding, and robotics. They are a promising new approach to building equivariant neural networks, and they are likely to be used in a variety of applications in the future.

Here are some of the key benefits of Vector Neurons:

- They are a general framework that can be used to create [[equivariant neural networks]] for a variety of tasks.
- They are efficient and scalable, making them suitable for large-scale datasets.
- They are easy to implement and use, making them accessible to a wide range of researchers and practitioners.

### Can Vector Neurons' expressiveness can be likened to Quaternions

According to ChatGPT 3
> No, vector neurons' expressiveness cannot be directly likened to quaternions.
>  
Vector neurons are computational units used in artificial neural networks to process and represent vector data. They are typically used for tasks such as pattern recognition, classification, and regression. Vector neurons operate on real-valued inputs and can perform various mathematical operations like addition, subtraction, and multiplication. However, their expressiveness is limited to these operations and the transformations they can perform on the input vectors. 
   
>On the other hand, quaternions are a mathematical concept that extends the properties of complex numbers to four dimensions. They are used in various applications such as computer graphics, robotics, and control systems due to their ability to represent spatial rotations and orientations in three-dimensional space. Quaternions have additional properties like non-commutativity and a more complex algebraic structure compared to real-valued vectors.
   
   > While both vector neurons and quaternions deal with multidimensional data, their underlying mathematical concepts and operations are fundamentally different. Quaternions provide a way to represent rotations in 3D space while vector neurons focus on processing and transforming real-valued vectors for machine-learning tasks. Therefore, it is not appropriate to directly compare or liken the expressiveness of vector neurons to quaternions.
   
It is still worth our while to study [[Quaternions]] and [[William Hamilton]]'s work on [[@hamiltonTHEORYCONJUGATEFUNCTIONS|Algebraic Couples]] or [[Algebra as the Science of Pure Time]].

# Conclusion
Vector Neurons are a promising new approach to building equivariant neural networks. They are efficient, scalable, and easy to implement, making them a valuable tool for a variety of tasks.



# References

[[@congyuedengVectorNeuronsGeneral2021]]

[[@congyuedengVectorNeuronsGeneral2021a]]

[[@michaelbronsteinLectureEquivariantCNNs2022|Lecture on Equivariant CNN]]

[[@kathylovesphysics&historyQuaternionsAreAmazing2023]]

