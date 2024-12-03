# Breast Cancer Prediction using Random Forest

This project aims to predict whether a breast cancer is malignant or benign using the Random Forest classification algorithm. The dataset used for this project contains features extracted from breast mass images. 

## Steps

1. **Import necessary libraries:**
   - numpy
   - pandas
   - matplotlib
   - sklearn (for model selection, preprocessing, and metrics)

2. **Load the dataset:**
   - Read the 'data.csv' file into a pandas DataFrame.

3. **Explore the dataset:**
   - Display the first few rows of the dataset.
   - Check the shape of the dataset.
   - Get information about the dataset (data types, missing values).
   - Calculate statistical measures (mean, standard deviation, etc.).

4. **Preprocess the data:**
   - Drop the last column from the dataset.
   - Check for missing values.
   - Check the distribution of the target variable ('diagnosis').
   - Calculate the mean of features grouped by 'diagnosis'.
   - Separate features (X) and target variable (y).
   - Encode the target variable using LabelEncoder.

5. **Split the dataset:**
   - Split the dataset into training and testing sets (80% training, 20% testing).

6. **Train the Random Forest model:**
   - Create a RandomForestClassifier with specified parameters.
   - Fit the model on the training data.

7. **Evaluate the model:**
   - Predict on the test data.
   - Calculate the confusion matrix.
   - Calculate the accuracy score.

8. **Build a predictive system:**
   - Define input data as a tuple.
   - Convert input data to a numpy array and reshape it.
   - Predict using the trained model.
   - Print the prediction (0 for malignant, 1 for benign).

## How to run

1. Make sure you have the required libraries installed.
2. Place the 'data.csv' file in the same directory as the code.
3. Execute the code in a Jupyter Notebook or a Python environment.
