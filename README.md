Linear Regression Model for House Price Prediction
This Python script implements a linear regression model to predict house prices based on selected features. It uses the 'train.csv' dataset containing information about residential properties.

Requirements
Python 3.x
Required Libraries: numpy, pandas, scikit-learn
How to Use
Ensure you have Python installed on your system.
Install the required libraries using pip:
pip install numpy pandas scikit-learn
Download the train.csv dataset.
Place the dataset file in the same directory as the script.
Run the script.
Description
The script imports necessary libraries such as numpy, pandas, and scikit-learn.
It loads the dataset using Pandas.
Rows with missing values in specific columns (GrLivArea, BedroomAbvGr, FullBath, SalePrice) are dropped.
Features (GrLivArea, BedroomAbvGr, FullBath) and the target variable (SalePrice) are selected.
The data is split into training and testing sets using the train_test_split function from scikit-learn.
A linear regression model is initialized and fitted to the training data.
Predictions are made on the testing data using the trained model.
The model is evaluated using the R-squared score.

