# K-Means Clustering

An unsupervised learning algorithm that partitions a dataset into K distinct clusters based on feature similarity. 

In this section, K-means was applied to customer marketing data to explore patterns in spending behavior and purchasing trends.

## Application

The used dataset is publicly available on Kaggle.com and it is customers records from a groceries firm's database.
The selected features were 1. number of purchases a customer makes with a discount and 2. their total spending across product categories.


The data was preprocessed through dropping missing values, computing a new feature from the existing features in the dataset, and standardizing the used features.

Then, the optimal K value was determined by using the "elboew method" which helped us find the point where adding more clusters yield diminishing returns.

With the optimal K, we fit the model with the chosen K and predicted cluster assignments. Lastly, visualized the clusters and centroids on a graph.


Customer segmentation is the practice of separating customers into groups that reflect similarities among customers in each cluster. K-means provided a way to segment customers based on their engagement with deals and overall expenditure. This appraoch has applications to marketing, through targeted promotions or altering offers for customers.

### Dependencies

Install the required packages:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn

