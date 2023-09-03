
In [[Category theory]], "naturality" refers to a property of [[natural transformation|natural transformations]] between [[Functor|functors]]. A natural transformation is said to be natural if it commutes with the morphisms in the categories involved.

More specifically, given two categories C and D, and two functors F, G: C → D, a natural transformation α: F → G is said to be natural if for every object X in C, the following diagram commutes:

```
         F(X) ---α_X---> G(X)
          |               |
    F(f)  |               |  G(f)
          v               v
         F(Y) ---α_Y---> G(Y)
```

Here, α_X is the component of the natural transformation α at object X, and F(f), G(f) are the images of a morphism f in C under functors F and G respectively.

The naturality condition essentially means that the action of a natural transformation on objects and morphisms in a category is consistent and does not depend on specific choices made within the categories or functors. It captures the idea that a natural transformation should respect the structure of categories involved.