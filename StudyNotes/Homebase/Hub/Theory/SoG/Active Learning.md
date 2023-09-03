---
Aliases: Active Learning, active learning, Active learning
---
#ML 

Active learning is a machine learning approach that aims to reduce the amount of labeled data required for training models. In traditional supervised learning, large amounts of labeled data are needed to train a model effectively. However, labeling data can be time-consuming and expensive, especially when dealing with large datasets.

Active learning addresses this issue by smartly selecting the most informative samples for labeling from a pool of unlabeled data. The idea is to actively query an oracle (e.g., a human expert or a pre-existing labeled dataset) to label the most uncertain or informative instances and use these labels to train the model further. By selectively labeling only the most relevant instances, active learning aims to achieve similar performance with less labeled data compared to passive learning approaches.

There are different strategies employed in active learning:

1. Uncertainty sampling: This strategy selects instances that the model is most uncertain about, typically by measuring uncertainty using metrics like entropy or margin sampling. These instances are likely to be at decision boundaries where the model needs more information.

2. Diversity sampling: This strategy aims to select instances that cover diverse regions of the input space, ensuring that all important areas are represented in the training set.

3. Query-by-committee: In this strategy, an ensemble of models is used, and instances on which models disagree are considered uncertain and queried for labeling.

4. Expected model change: This strategy selects instances that are expected to have a significant impact on the model when labeled and included in training.

Active learning has been widely studied in machine learning literature and has shown promising results in various domains such as text classification, image classification, object detection, and sentiment analysis. It has been demonstrated that active learning can significantly reduce the labeling effort while achieving comparable or even better performance compared to traditional supervised learning approaches.

However, active learning also comes with challenges such as defining appropriate selection criteria, handling noisy oracle labels, and avoiding overfitting due to biased queries. Researchers continue to explore and develop new techniques and algorithms to overcome these challenges and improve the effectiveness of active learning in real-world applications.
# References

[[@underfittedActiveLearningSecret2022]]

[[@settlesActiveLearningLiterature]]


