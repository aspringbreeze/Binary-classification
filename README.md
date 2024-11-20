# Binary classification
 This project demonstrates how to train a logistic regression model using scikit-learn to perform binary classification. The script loads a dataset, splits it into training and testing sets, trains a logistic regression model, and evaluates its performance.

## Features
* _Data Splitting_: Splits the data into training and testing sets.
* _Model Training_: Trains a logistic regression model on the training data.
* _Model Evaluation_: Predicts on the test set and evaluates the model's accuracy.

## Prerequisites
Make sure the following packages are installed:

pip install pandas scikit-learn


## Setup and Usage
1. Clone the repository:

git clone https://github.com/aspringbreeze/Binary-classification/logistic-regression-model.git
cd logistic-regression-model

2. Add the Dataset:

* Place your dataset in the directory and name it exampledataset1.csv or update the script with your own dataset filename.

3. Run the Script:

python script.py

4. Expected Output:

* Predicted values for the test set.
* Coefficients and intercept values for the logistic regression model.
* Model accuracy printed as a percentage.


## Example Output

Predictions: [0 1 0 1 0]
Model Accuracy: 0.85

## Project Structure
script.py: The main script that runs the data processing, model training, and evaluation.
