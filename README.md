# K-Nearest Neighbors (KNN) Classification - Iris Dataset

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm for classifying the **Iris dataset** using Python and scikit-learn. The objective of this project is to understand and implement the KNN algorithm, experiment with different values of `K`, and evaluate the performance using accuracy and confusion matrix, along with visualizing decision boundaries.

## Features
- **Iris dataset**: A popular dataset for classification tasks.
- **Normalization**: Feature scaling is done using `StandardScaler`.
- **KNN Classification**: The model is trained and evaluated using multiple values of `K` (1, 3, 5, 7, 9).
- **Evaluation Metrics**: Accuracy, confusion matrix.
- **Visualizations**: 
  - Accuracy vs K values plot
  - Confusion matrix heatmap
  - Decision boundary plot using the first two features

## Libraries Used
This project uses the following Python libraries:
- `scikit-learn`: For building and evaluating the KNN classifier.
- `pandas`: For handling data and preprocessing.
- `numpy`: For numerical operations.
- `matplotlib`: For plotting graphs and visualizations.
- `seaborn`: For enhanced data visualization.

## Dataset
The **Iris dataset** is included with scikit-learn and contains 150 samples from three species of Iris flowers. Each sample includes four features:
- Sepal length
- Sepal width
- Petal length
- Petal width
