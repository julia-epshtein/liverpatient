# Liver Patient Classification

This repository contains a Jupyter Notebook (LiverPatient.ipynb) that demonstrates the process of importing, cleaning, visualizing, and classifying a dataset related to liver patients using different machine learning algorithms. The dataset used in this project is the "Indian Liver Patient Dataset (ILPD)".

## Getting Started

Before running the notebook, you will need to mount Google Drive to access the dataset. The dataset should be placed in the following location within your Google Drive:

`/content/drive/MyDrive/Colab Notebooks/Indian Liver Patient Dataset (ILPD).csv`

## Sections

### Section 1: Importing Libraries and Content

This section imports the required libraries for data manipulation, visualization, and classification. It also imports the dataset and provides information about the number of liver and non-liver patients.

### Section 2: Cleaning and Visualizing the Dataset

In this section, the dataset is cleaned by dropping rows with missing values. It then creates histograms and scatter matrices to visualize the distribution and correlation between features.

### Section 3: ML Classification

This section covers the machine learning classification process. The dataset is preprocessed by normalizing the data using the Standard Scaler method. The classification task involves three algorithms:

1. K-Nearest Neighbors (KNN): The notebook determines the best value of 'k' for KNN classification.
2. Decision Tree Classifier: A decision tree classifier is trained and evaluated.
3. Random Forest Classifier: The notebook iterates over a range of estimators to find the optimal number for the Random Forest Classifier.
4. Logistic Regression: Logistic Regression is performed, and the accuracy and estimated probabilities for each class are displayed.

## Usage

To run the notebook, make sure you have the required libraries installed. It is recommended to use Google Colab to run the notebook as it automatically mounts your Google Drive.

Feel free to experiment and modify the code to suit your specific requirements!
