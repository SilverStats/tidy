tidy
====

The course project for "Getting and Cleaning Data" on Coursera

Note that you must be in the main folder (the one that contains the folder entitled "UCI HAR Dataset") for this script to work.

My transformations are as follows:

* changed activity numbers to activity names as coded by activity_labels.txt
* added activity and subject information to the test and training datasets
* merged the two datasets into one
* extracted only the columns dealing with mean and standard deviation (using grep to find "mean" or "std" in the variable names)
* renamed the columns to reflect the information they contain, using the key provided in features.txt
* melted the data to get observations for each activity/subject combination
* recast the data and calculated the average for each combination
* wrote the resulting data set to a text file

The result is a single, tidy dataset, containing the averages for measurements dealing with population means and standard deviations.
