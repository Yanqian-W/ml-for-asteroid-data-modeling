# Machine Learning for Asteroid Data Modelling

## Datasets

The sample data of asteroid rock have been tabulated in two csv files:
1. 'Asteroid_1.csv'
2. 'Asteroid_2.csv'

Data file (1) and (2) contain measurements from completely different groups of asteroids. No individual asteroid appears in both data files.

## Clustering

Data file (1) contains the results of the analysis of 4966 asteroids. Each feature represents a quantity, measured in micrograms of various types of minerals found in the asteroid.

For this task, I determine the optimal number of types for asteroid classification, and use K-means algorithm to fit the optimal number of clusters; Using principal component analysis to reduce the dimensionality of the data and fitting the dataset with a Gaussian mixture model to visualize the cluster in three-dimensional chart.

From the chart, we  found that asteroids have been well classified.

## Modelling

Data file (2) is intended to understand if a particular mixture of minerals gives an asteroid that is mechanically stable. Each feature represents a quantity in micrograms of a particular mineral. The finalcolumn in the table provides a label, with a meaning as follows:
- 0 = "The asteroid is mechanically stable"
- 1 = "The asteroid is not mechanically stable"

For this task, I modelled asteroid data using Logistic Regression, Random Forest Classifier, and Perceptron. By optimizing and evaluating model performance, finding that Logistic Regression is the best method to predict if an asteroid is mechanically stable based on its mixture of minerals.
