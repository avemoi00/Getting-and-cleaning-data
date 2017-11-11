# Getting-and-cleaning-data

## With this script, just enter the right path value for your working directory and run it.

#The script performs the following:

##we load the features, activity labels, test data, train data using fread (data.table library)
##we merge the training and test data
##we remove the numbers in front of the feature names
##we merge the result activities with the labels
##we combine the subject identification for the test and train data
##we calculate the statistics mean and standard deviation
##we combine all and calculate the summary for all variables



List activities :

##WALKING
##WALKING_UPSTAIRS
##WALKING_DOWNSTAIRS
##SITTING
##STANDING
##LAYING