# The k-Nearest Neighbors Algorithm #
## Overview ##
This algorithm predicts the label of a new data point by examining the labels of the k closest points in the training data, using a distance metric.

KNN:
1. Calculates the distance between a test point and all training points
2. Selects the K nearest neighbors based on this distance
3. Assigns the majority class among these neighbors as the prediction
The distance is calculated using Euclidean distance

## Wine Quality Data ##
I used the Wine Quality Dataset from the UCI Machine Learning Repository.
The data contains red wine samples each with 11 chemical properties:
Fixed acidity
Volatile acidity
Citric acid
Residual sugar
Chlorides
Free sulfur dioxide
Total sulfur dioxide
Density
pH
Sulphates
Alcohol

I selected these features: Alcohol content, Density, and pH and their relationship to the "quality" of the wine which is given a score between 0 and 10. A score greater than or equal to 7 was regarded as good (1), and bad (0) otherwise.   

### Dependencies

Make sure to install
```bash 
pip install numpy matplotlib tensorflow scikit-learn