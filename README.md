# Car-data-Analysis

## Set up the environment
You need to install Python, NumPy, Pandas, Matplotlib and Seaborn. Numpy version = 1.2.1 and Python= 3.9

## Getting the data
 The Car price dataset.

You can do it with wget:

wget https://raw.githubusercontent.com/alexeygrigorev/mlbookcamp-code/master/chapter-02-car-price/data.csv

## The following questiona were answered:

 How many records are in the dataset?

 Who are the most frequent car manufacturers (top-3) according to the dataset?

 What's the number of unique Audi car models in the dataset?

 How many columns in the dataset have missing values?

 Does the median value change after filling missing values?

 Find the median value of "Engine Cylinders" column in the dataset.
 Next, calculate the most frequent value of the same "Engine Cylinders".
 Use the fillna method to fill the missing values in "Engine Cylinders" with the most frequent value from the previous step.
 Now, calculate the median value of "Engine Cylinders" once again.

 Perform matrix by matrix multiplication:

 Select all the "Lotus" cars from the dataset.
 Select only columns "Engine HP", "Engine Cylinders".
 Now drop all duplicated rows using drop_duplicates method (you should get a dataframe with 9 rows).
 Get the underlying NumPy array. Let's call it X.
 Compute matrix-matrix multiplication between the transpose of X and X. To get the transpose, use X.T. Let's call the result XTX.
 Invert XTX.
 Create an array y with values [1100, 800, 750, 850, 1300, 1000, 1000, 1300, 800].
 Multiply the inverse of XTX with the transpose of X, and then multiply the result by y. Call the result w.
 What's the value of the first element of w?

 