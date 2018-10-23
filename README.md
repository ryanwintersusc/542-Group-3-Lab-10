# 542-Group-3-Lab-10
To run this code use the command python class3.py

Note that the matrix must be saved as a CSV file in the same directory as the python file.

The code requires that the matrix have no headers, and only biomarkers, no label for cancer/normal.

We import the appropriate libraries and then read in the matrix.

We hardcoded in the names for the dataset columns in this case, so it will need to be changed if 
biomarkers are added or deleted in the future.

Steps in the code:

Create the dependent variable class
Split the data into independent and dependent variables
Create the Training and Test set from data
Scale feature
Fit Random Forest Classification the training set
Predict Test Set Result
Perform analysis and print results
