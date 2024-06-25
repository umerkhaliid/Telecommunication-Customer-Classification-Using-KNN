# Telecommunication-Customer-Classification-Using-KNN

**Overview**
This project aims to classify customers of a telecommunication company into one of four groups based on various features using the K-Nearest Neighbors (KNN) classification algorithm.
Additionally, Exploratory Data Analysis (EDA) was performed to visualize and understand the distribution and impact of different features on customer segmentation.

**Objectives**
To classify customers into four groups using KNN.
To perform EDA to understand feature distributions and relationships.
To determine the best value of k by calculating classification accuracies for different k values.

**Dataset**
The dataset used for this project contains various features of customers from a telecommunication company. The features include region, tenure, age, marital status, and more.

**Steps and Methodologies**

**Exploratory Data Analysis (EDA)**
Visualization: Created box plots to visualize the distribution of customers against features such as region, tenure, age, and marital status etc.
Insights: Derived insights from visualizations to understand patterns and relationships in the data.

**Data Preprocessing**
Data Cleaning: Handling duplicate values.
Feature Encoding: Converting categorical variables into numerical format using techniques like one-hot encoding.
Scaling: Standardizing numerical features to ensure they contribute equally to the distance calculation in KNN.

**KNN Classification**
Implementation: Applied KNN algorithm to classify customers into four groups.
Model Evaluation: Calculated classification accuracies for different values of k (number of neighbors) to identify the optimal k value.

**Results**
Classification Accuracy: Achieved a classification accuracy of 37% with the optimal k value of 5.
Visual Insights: EDA provided valuable insights into customer distribution and feature relationships.

**Dependencies**
Python 3.x
pandas
numpy
matplotlib
seaborn
scikit-learn

**Conclusion**
This project successfully demonstrated the application of the KNN algorithm for customer classification in a telecommunication context. Through EDA and model evaluation, we identified key patterns and optimized the classification process to achieve the best possible accuracy.
