

**🌳 What is a Decision Tree and What Does It Do?**
A Decision Tree is a supervised learning algorithm used for both classification and regression tasks. It works by successively splitting the dataset into smaller groups based on feature-driven rules. Each internal node represents a decision condition on a feature, each branch represents an outcome of that condition, and each leaf node represents the final predicted class or value.

Instead of learning a linear relationship, a Decision Tree learns **hierarchical decision rules** that segment the feature space into interpretable regions. This makes it useful in domains where transparency and explainability matter — such as finance, healthcare, risk analysis, and operational decision systems.

---

**✔ Advantages of Decision Trees**

* Simple to understand — model decisions can be interpreted as human-readable rules
* Handles both numerical and categorical features without heavy preprocessing
* Can model non-linear relationships and feature interactions naturally
* Requires minimal assumptions about data distribution
* Works well as a baseline model and as a foundation for ensemble methods (Random Forest, Gradient Boosting)

---

**✘ Disadvantages of Decision Trees**

* Highly prone to overfitting if not pruned or regularized
* Small variations in data can change the structure of the tree (high variance)
* Deep trees become complex and lose interpretability
* Bias toward features with many split levels or high cardinality
* Probability estimates at leaves are often poorly calibrated


