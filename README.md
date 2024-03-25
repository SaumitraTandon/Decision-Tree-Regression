# Decision Tree Regression

This repository contains code for implementing Decision Tree Regression on a dataset of position levels and corresponding salaries. The code is written in Python and uses the scikit-learn library.

## Code Explanation

The code performs the following steps:

1. Imports the required libraries: numpy, matplotlib, and pandas.
2. Reads the dataset from a CSV file named `Position_Salaries.csv`.
3. Separates the independent variable (position level) and the dependent variable (salary) from the dataset.
4. Trains a Decision Tree Regression model on the entire dataset using the DecisionTreeRegressor class from scikit-learn. The `random_state` parameter is set to 0 for reproducibility.
5. Demonstrates how to predict a new salary using the trained Decision Tree Regression model for a position level of 6.5.
6. Visualizes the Decision Tree Regression results using a scatter plot for the actual data points and a line plot for the predicted values.
7. Generates a higher resolution curve for the Decision Tree Regression model by creating a grid of position levels.

## Dataset

The dataset used in this code is included in the repository and named `Position_Salaries.csv`. It contains the following columns:

| Position | Level | Salary |
| -------- | ----- | ------ |
| Business Analyst | 1 | 45000 |
| Junior Consultant | 2 | 50000 |
| Senior Consultant | 3 | 60000 |
| Manager | 4 | 80000 |
| Country Manager | 5 | 110000 |
| Region Manager | 6 | 150000 |
| Partner | 7 | 200000 |
| Senior Partner | 8 | 300000 |
| C-level | 9 | 500000 |
| CEO | 10 | 1000000 |

The `Level` column represents the level of the position, and the `Salary` column represents the corresponding salary for that position level.

## Usage

To run the code, you need to have Python and the required libraries installed. You can install the necessary libraries using pip:
After installing the required libraries, you can run the code by executing the Python script.

## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
