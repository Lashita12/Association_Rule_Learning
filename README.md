# Association_Rule_Learning
This project analyzes a retail company's transaction data using association rule learning. The dataset, sourced from Kaggle, comprises 7501 transaction records over one week. The goal is to find and visualize association rules between items using the Apriori algorithm.

A. Libraries Used-

1) Pandas: Data manipulation and preprocessing.

2) NumPy: Numerical operations.

3) mlxtend.frequent_patterns: Implementing Apriori algorithm and generating association rules.

4) Matplotlib/Seaborn: Data visualization.

B. Steps-

1) Data Preprocessing:

- Load the dataset without headers.

- Transform the dataset into a suitable format for the Apriori algorithm.

2) Generate Transactions: Create a list of transactions from the dataset.

3) Train Apriori Algorithm: Apply the Apriori algorithm to identify frequent item sets and generate association rules.

4) Visualize Rules: Plot the association rules to gain insights.

5) Adjust Hyperparameters: Modify minimum confidence values to observe changes in generated rules.
