# Decision Trees
A decision tree makes a sequence of “if-then” statements (splits) at each node, deciding which branch to follow based on whether the statement is true or false.

## Application
We use a dataset on heart disease and focus on two key features of `age` and `thalach`.
The target variable is `target`, indicating the presence (1) or absence(0) of heart disease.

The main aspects of my implementation in the notebook:
- Load and preprocess data

- Train a decision tree model using scikit-learn

- Visualize the full decision tree

- Compare tree depths (e.g., max_depth=4)

- Plot decision regions to interpret model behavior

- Evaluate performance using confusion matrix

### Dependencies

Need the following libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn mlxtend
