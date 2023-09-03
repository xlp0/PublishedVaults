---
Aliases: AdaBoost, Adaptive Boosting
---
Adaboost, short for Adaptive Boosting, is a machine learning algorithm that combines multiple weak classifiers to create a strong classifier. It was proposed by [[Yoav Freund]] and [[Robert Schapire]] in 1996.

The main idea behind Adaboost is to iteratively train a series of weak classifiers on different subsets of the training data. A weak classifier is a simple model that performs slightly better than random guessing, such as decision stumps (decision trees with only one split). Each weak classifier focuses on the instances that were previously misclassified or have higher weights assigned to them.

In each iteration, Adaboost assigns higher weights to the misclassified instances from the previous iteration, making them more influential in the training process. This way, subsequent weak classifiers pay more attention to these hard-to-classify instances. The final classification decision is made by combining the predictions of all weak classifiers, usually through weighted majority voting.

One of the key advantages of Adaboost is its ability to handle complex classification problems by combining multiple simple models. It can effectively deal with data imbalance and noisy datasets. Additionally, Adaboost has good generalization performance and can be used with various types of data and learning algorithms.

However, Adaboost is sensitive to outliers as they can significantly affect the training process. Also, it may be prone to overfitting if the weak classifiers become too complex or if there are insufficient training examples.

Overall, Adaboost has been widely utilized in various applications such as face detection, object recognition, text categorization, and bioinformatics due to its effectiveness in improving classification accuracy.