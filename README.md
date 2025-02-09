# Iris-Flower-Analysis

# Overview

This project focuses on classifying Iris flowers into three species (Setosa, Versicolor, and Virginica) using Machine Learning Techniques. The classification is based on four key features:

1. Sepal Length

2. Sepal Width

3. Petal Length

4. Petal Width

The dataset used for training and testing is the Iris dataset, which is a well known dataset in Machine Learning.

# Project Workflow

1. <ins> Load the Dataset </ins>

   1. The dataset is imported using Scikit-learn's load_iris() function.
  
   2. It is then converted into a Pandas Dataframe for easy manipulation.
  
2. <ins> Data Preprocessing </ins>

   1. The dataset is split into features (X) and target labels (y).
  
   2. Data is divided into training (80%) and testing (20%) sets using train_test_split().
  
   3. Standardization is applied to scale the feature values using StandardScaler().
  
3. <ins> Model Training </ins>

   1. A Support Vector Machine (SVM) classifier with a linear kernel is used to train the model.
  
   2. The model is trained on the preprocessed training data.

4. <ins> Model Evaluation </ins>

   1. The trained model is tested on unseen data (test data).
  
   2. The following performance metrics are calculated :
  
         1. Accuracy Score : Measures overall performance.
     
         2. Confusion Matrix : Displays correct and incorrect predictions.
     
         3. Classification Report : Shows Precision, Recall, and F1-score for each class.
     
5. <ins> Visualization </ins>

The confusion matrix is visualized using Seaborn heatmap to understand model performance.

# Expected Output

1. Accuracy Score : typically >95%

2. Confusion matrix to analyze correct and incorrect classifications.

3. Classification report displaying Precision, Recall and F1-score.

4. Visualization of the confusion matrix.
