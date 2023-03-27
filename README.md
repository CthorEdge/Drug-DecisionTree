# Drug-DecisionTree
A brief explanation on Decision Tree Algorithm and also its implementation on drug classification dataset

# What is Decision Tree?
- One of the easiest and popular machine learning algorithms to understand and interpret
- Categorized as Supervised Learning
- Able to handle various problems:
1. Classification
2. Regression
![image](https://user-images.githubusercontent.com/128962817/227965694-1eaec27f-8248-4d2d-956d-f1578731a5e7.png)

# How Does it Work?
1. Preview the Data on Decision Node/Root Node
2. Select the best attribute/characteristics to perform splitting, various Attribute Selection Measures:
- Entropy

![image](https://user-images.githubusercontent.com/128962817/227968274-50ee4c9a-0188-4b28-991b-aba31afc3024.png)
- Information Gain
![image](https://user-images.githubusercontent.com/128962817/227968288-eaa8648e-5267-444e-af80-1095af16f541.png)
- Gini Index
- Gain Ratio
- Reduction in Variance
- Chi-Square
4. Issue splitting
5. Iterate the same process until the ideal condition is met

# What Are Its Strengths?
1. Solve Complex relations between variables
2. Requires little data preparation
3. Easy to Interpret
4. Able to handle both numerical and categorical data

# What Are Its Limits?
1. Decision tree is a Recursive Greedy Algorithm, which leads to overfitting
2. Small data variations lead to different decision tree built
3. Possibility of biased tree w/ unbalanced dataset

# How to Optimize It?
1. Pruning, by utilizing criterion, splitter, and max_depth
2. Ensemble
- Random Forest

![image](https://user-images.githubusercontent.com/128962817/227968886-8980cb8c-d825-4522-90df-1b552c4be9f9.png)
- XGBoost

![image](https://user-images.githubusercontent.com/128962817/227968913-e706deef-4b68-466d-b606-bdbff930df32.png)

5. Data Balancing
- Undersampling
- Oversampling

# References
- https://www.kdnuggets.com/2020/01/decision-tree-algorithm-explained.html 
- https://scikit-learn.org/stable/modules/tree.html 
- https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#sklearn.tree.DecisionTreeClassifier 
- https://neptune.ai/blog/how-to-deal-with-imbalanced-classification-and-regression-data 
