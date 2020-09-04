Some of the factors which should be kept in mind are as follows:

1- Dealing with data leakages 
----------------------------------------------------------------
     For this we in the start only split the datasets into training and testing and then further process are performed
     separatedly i.e. first for traindata sets whole process till model creation then we move to testdata sets and repeat
     the whole process for test datasets

2- Dealing with randomness of data (It should follow standard normal distribution - bell curve)
-----------------------------------------------------------------------------------------------
     For this we do feature engineering to be precise we do transformation of variables some of the techniques are as 
     follow:
     1-Power transformation
     2-Exponential transformation 
     3-Polynomial transformation
     4-Log transformation
     5-Sqrt transformation
     6-Reciprocal transformation
     7-Box-cox transformation
                            The main idea behind such transformation is to deal with skewness and kurtosis
                            1-Skewness ranges from -1 to +1 and types are left, right and centered
                            2-Kurtosis ranges from -3 to +3 and types are Meso,lept and plato
     
