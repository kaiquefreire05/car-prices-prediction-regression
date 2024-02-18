# Car Price Prediction Using Machine Learning Models

Author: [Kaíque Freire dos Santos]<br>
Date: [2024/02/18]

# Description:

This notebook demonstrates the process of building a machine learning model to predict the price of used cars based on various characteristics such as make, model, year, mileage, and condition. It includes steps such as data import, exploratory analysis, pre-processing, training of linear regression, random forest, SVM and artificial neural network models, and comparison of results.

# Data:

The dataset used is "CarPricesPrediction.csv", which contains information about used cars such as make, model, year, mileage, condition and price.

# Methodology:

1. Importing and reading data:
  * Import required libraries (pandas, numpy, matplotlib, etc.).
  * Read the CSV file using pd.read_csv.
2. Exploratory analysis:
  * View the first and last records.
  * Check general data information using df.info().
  * Describe the data using df.describe().
  * Check for null values using df.isnull().sum().
  * Create graphs for visual analysis, such as price distribution by year, vehicle count by manufacturer, etc.
3. Pre-processing:
  * Remove unnecessary column "Unnamed: 0".
  * Separate the data into predictors (X) and target variable (y).
  * Identify categorical columns.
  * Encode the categorical columns using OneHotEncoder and ColumnTransformer.
  * Standardize the values using StandardScaler.
  * Split the data into training and testing basis using train_test_split.
4. Model training:
  * Define a function to perform a random search for the best parameters for each model.
  * Train linear regression, random forest, SVM, and artificial neural network models using GridSearchCV or RandomizedSearchCV.
  * Evaluate the performance of the models using indicators such as R² score and mean absolute error (MAE).
  * Select the model with the best performance.
5. Assessment and results:
  * Compare model results on a testing and training basis.
  * Make predictions with the selected model and calculate the final MAE.
6. Conclusion:
  * Discuss results and possible improvements.
  * Suggest future directions for the project.

# Requirements:

* Python 3.6 or higher
* Libraries: pandas, numpy, matplotlib, seaborn, sklearn

# How to run:

1. Download the "CarPricesPrediction.csv" file and place it in the same folder on your notebook.
2. Open the notebook in a Jupyter Notebook environment.
3. Run the notebook cells sequentially.

# Comments:

* This is a basic example of car price prediction.
* There are several other algorithms and techniques that can be explored to improve the accuracy of models.
