* Changed data type of the TotalCharges column from object -> numeric
* After changing the column proved to have 11 NaN values, since the 11 < 1% of the data set (~0.16%) the rows were dropped, since of negligible impact and is also the simplest method. (Also since if we're imputing we have to check for the tenure \* monthly charges connection, and also cannot impute median since it might get affected with outliers.
* 
