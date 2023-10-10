Choosing between Gini Impurity and Entropy as a criterion for splitting nodes in a decision tree is a fundamental decision in model development. Both measures aim to quantify the "messiness" of the data, helping to identify the best possible splits.

### When to Use:

1. **Gini Impurity**: Often preferred for computational reasons as it does not involve logarithmic calculations. Gini is a good default option and particularly useful when you need quicker computations.
   
2. **Entropy**: When you require a more balanced tree and are willing to incur the computational cost. Entropy tends to produce slightly more balanced trees as it aims to maximize the mutual information in the tree.

### Why to Use:

#### Gini Impurity:

1. **Computational Efficiency**: Gini impurity doesn't require the calculation of logarithms, making it computationally faster, especially for large datasets.

2. **Bias Towards Larger Partitions**: Gini tends to isolate the most frequent class in its own branch of the tree, which can be useful depending on the problem context.

3. **Industry Standard**: Due to its computational efficiency and good performance, Gini impurity is widely used in many applications as a default setting.

4. **Papers & Frameworks**: Gini is well-supported in many machine learning frameworks like scikit-learn, making it a convenient choice.

#### Entropy:

1. **Information Gain**: Entropy uses the concept of information gain for splitting, striving for splits that offer the most additional information. This can result in more balanced trees.

2. **Less Bias**: Entropy does not favor the more frequent classes as explicitly as Gini, potentially providing more balanced classification.

3. **Explicitness in Uncertainty**: Entropy-based models can offer additional insights in the form of the amount of "information" obtained in each split, which may be useful depending on the specific application.

4. **Historical Context**: Originating from Claude Shannon's Information Theory, it has a robust theoretical foundation.

### Trade-offs:

- **Gini Impurity**: Generally faster but may lead to a slightly biased tree.
  
- **Entropy**: May produce a more balanced tree but at the cost of computational efficiency.

Empirical comparisons between Gini impurity and Entropy often show negligible differences in the performance of the resulting models. Consequently, the choice may also be influenced by the specific constraints and requirements of your data science project, such as computational resources or the need for model interpretability.

Would you like more details or references on this topic?