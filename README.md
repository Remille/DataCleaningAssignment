# Getting and Cleaning Data
##  How to run
Set the working directory to the folder containing the data set UCI HAR, available [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip).

When you execute the script, a text file will be generated. It will be in the same folder 
as the data sets that have the average values for each element of the 561 feature vector.

The script will create a large table that combines training and test data. Rows with 
standard deviation or mean data will be collected and then the columns will be renamed. 
After that, it is outputted to a text file.