# Iris Flower Classification using K-Nearest Neighbors (KNN)

## CodeAlpha Data Science Internship Project

## Project Overview

This project implements a Machine Learning classification model using the K-Nearest Neighbors (KNN) algorithm to classify Iris flowers into three species: Iris Setosa, Iris Versicolor, and Iris Virginica. The classification is based on four flower measurements: sepal length, sepal width, petal length, and petal width.

## Dataset Information

The Iris dataset contains:

* Total Samples: 150
* Features: 4
* Classes: 3
* Samples per Class: 50
* Missing Values: None

### Features

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

### Target Classes

* Iris Setosa
* Iris Versicolor
* Iris Virginica

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

## Project Workflow

### 1. Data Loading

* Loaded the Iris dataset using Scikit-Learn.
* Created a Pandas DataFrame for analysis.

### 2. Exploratory Data Analysis (EDA)

* Examined dataset shape and structure.
* Generated statistical summaries.
* Checked for missing values.
* Analyzed species distribution.

### 3. Data Visualization

* Species distribution bar chart.
* Histograms for feature distributions.
* Scatter plots showing relationships between features.
* Visual analysis of class separation.

### 4. Feature Selection

* Selected flower measurements as input features.
* Selected species labels as target values.

### 5. Train-Test Split

* Split the dataset into training and testing sets.
* Used an 80:20 ratio.
* Applied stratified sampling to maintain class balance.

### 6. Feature Scaling

* Applied StandardScaler to normalize feature values.
* Prepared data for distance-based KNN classification.

### 7. Model Building

* Implemented the K-Nearest Neighbors (KNN) algorithm.
* Used K = 3 nearest neighbors.
* Trained the model using the training dataset.

### 8. Prediction

* Generated predictions on unseen test data.
* Compared predicted and actual species labels.

### 9. Model Evaluation

* Calculated model accuracy.
* Evaluated prediction performance.
* Analyzed classification results.

### 10. Custom Predictions

* Tested the trained model on new flower measurements.
* Predicted species and confidence scores.

## Key Findings

* The Iris dataset is clean and contains no missing values.
* The dataset is perfectly balanced across all three species.
* Petal measurements provide strong separation between flower species.
* KNN successfully classified flower species with high accuracy.
* Iris Setosa is the easiest species to distinguish due to its distinct petal measurements.

## Conclusion

The K-Nearest Neighbors algorithm proved effective for Iris flower classification. Through data exploration, visualization, preprocessing, and model evaluation, the project demonstrates a complete machine learning workflow. The model achieved strong classification performance and successfully predicted flower species based on their physical characteristics.

## Author

Areeba Kagzi

CodeAlpha Data Science Internship
