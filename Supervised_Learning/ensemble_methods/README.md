# Ensemble Methods

In the ensem.ipynb notebook, we explore how ensemble learning techniques, specifically Bagging (Bootstrap Aggregation) and Boosting (AdaBoost) improve the performance of individual weak learners, typically decision trees. 

## Implementation
We apply these methods to the Heart Disease dataset for binary classification (presence vs. absence of disease). The heart disease dataset contains several medical features, and the target variable that is 1 if disease present and 0 if absent.

Key parts:
- Train a `DecisionTreeClassifier`, evaluate accuracy and confusion matrix

- We implement BaggingClassifier, AdaBoostClassifier

- Observe accuracy and classification performance

- Visualize and compare performance using confusion matrices and classification reports

- Plot decision boundaries

### Dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
