# ganesh_encoder
My custom encoder to create dummies for categorical columns

## This encoder uses the index value of elements in a list to be used as dummies

For example : If a categorical column in a DataFrame has two unique values; A and B,
then categories = ['A','B']. The index values of A and B in the categories list are 0 and 1 respectively. These are in-turn used as
dummies before applying the machine learning algorithms. For every A in the DataFrameSeries, 0 is replaced and accordingly 1 for B.
