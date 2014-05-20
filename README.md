tidy
====

The course project for "Getting and Cleaning Data" on Coursera

Note that you must be in the main folder (the one that contains the folder entitled "UCI HAR Dataset") for this script to work.

The only script is run_analysis.R, which is explained in CodeBook.md.

run_analysis.R contains all of the code necessary for tidying the data set and extracting mean and standard deviation info. Some non-standard packages (reshape and reshape2) must be installed by the user, but are loaded by the script.

Simply set your working directory to where the data are and run the script. The result will be a space-separated text file ("tidyAverages.txt") in the same directory.

The text files prepended with "study" are all provided by the data collectors and are explained in more detail in CodeBook.md.
