# Iris Flower Classification using Machine Learning

## CodeAlpha Data Science Internship Project

### Project Overview

This project focuses on classifying Iris flowers into their respective species using Machine Learning. The classification is performed using the K-Nearest Neighbors (KNN) algorithm based on flower measurements such as sepal length, sepal width, petal length, and petal width.

The project demonstrates the complete machine learning workflow, including data exploration, visualization, preprocessing, model training, prediction, and evaluation.

---

## Dataset Information

The Iris dataset is one of the most widely used datasets for machine learning classification tasks.

### Dataset Characteristics

* Total Samples: 150
* Number of Features: 4
* Number of Classes: 3
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

The dataset is balanced, with 50 samples belonging to each species.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

The Iris dataset was loaded into a Pandas DataFrame and inspected to understand its structure and contents.

### 2. Data Exploration

Basic dataset analysis was performed using:

* Dataset shape
* Data types
* Statistical summary
* Feature inspection

### 3. Missing Value Analysis

The dataset was checked for missing values to ensure data quality before model development.

### 4. Exploratory Data Analysis (EDA)

Several visualizations were created to better understand the dataset:

* Species Distribution
* Sepal Length Distribution
* Petal Length Distribution
* Petal Length vs Petal Width Relationship

### 5. Feature Selection

The flower measurements were selected as input features, while the species labels were used as the target variable.

### 6. Data Splitting

The dataset was divided into training and testing sets using an 80:20 ratio.

### 7. Feature Scaling

StandardScaler was applied to standardize feature values before training the KNN model.

### 8. Model Development

A K-Nearest Neighbors (KNN) classifier was implemented using Scikit-Learn with K = 3 neighbors.

### 9. Prediction and Evaluation

The trained model was used to predict flower species on unseen test data. Model performance was evaluated using accuracy score.

### 10. Custom Prediction

The model was tested using a custom flower sample to demonstrate real-world classification capability.

---

## Key Findings

* The dataset contains no missing values.
* All three Iris species are equally represented.
* Petal measurements provide strong separation between flower species.
* Feature scaling improves the effectiveness of distance-based algorithms such as KNN.
* The KNN model achieved high classification accuracy.
* Machine learning can successfully classify flower species using simple flower measurements.

---

## Results

The K-Nearest Neighbors classifier successfully classified Iris flower species with high accuracy. The model demonstrated strong predictive performance on unseen test data and correctly identified custom flower samples.

---

## Conclusion

This project successfully implemented a machine learning classification system using the K-Nearest Neighbors algorithm. Through data exploration, visualization, preprocessing, model training, and evaluation, the project demonstrated how machine learning techniques can be applied to classify biological data. The results highlight the effectiveness of KNN for solving classification problems and provide practical experience with the complete machine learning workflow.

---

## Author

**Areeba Kagzi**

CodeAlpha Data Science Internship
