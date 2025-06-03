# Task-6

K-Nearest Neighbors (KNN) Classification
 Objective
The goal of this project is to understand and implement the K-Nearest Neighbors (KNN) algorithm for solving classification problems using Python and popular libraries like Scikit-learn, Pandas, and Matplotlib.

Dataset
We used the classic Iris dataset, which contains 150 samples of iris flowers with 4 features each:
Sepal length
Sepal width
Petal length
Petal width
Each sample is labeled with one of three iris species: Setosa, Versicolor, or Virginica.

Tools & Libraries
Scikit-learn – for modeling, preprocessing, and evaluation
Pandas – for data manipulation
Matplotlib – for visualization

Steps Followed
1.Data Loading & Preprocessing:
Loaded the Iris dataset using sklearn.datasets.
Split the data into training and test sets.
Normalized the features using StandardScaler to ensure fair distance calculations.

2.Model Building:
Implemented the KNeighborsClassifier from Scikit-learn.
Trained the model using different values of K (number of neighbors).

3.Model Evaluation:
Evaluated model performance using accuracy score and confusion matrix.
Identified the best K value based on test accuracy.

4.Visualization:
Plotted the accuracy vs. different K values to understand the effect of K.
Visualized the decision boundaries using two features (petal length and petal width) to illustrate how KNN classifies the data in 2D space.

Key Learnings
Normalization is crucial for distance-based algorithms like KNN.
The choice of K significantly affects model performance—lower values can overfit, and higher values may underfit.
KNN is easy to implement and interpret, especially on small datasets, but it can be computationally expensive on large datasets.

 Results
Achieved high classification accuracy on the Iris dataset.
Found the optimal value of K that balances bias and variance.
Demonstrated the model's performance through visual and quantitative metrics
