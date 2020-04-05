# Getting and Cleaning Data
This repo was created for the course project of the Getting and Cleaning Data course for Coursera

# Project Summary
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.

Here are the data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The steps to be followed are :
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each      subject.

# Repo Information
This repo contains the following files

1. `RunAnalysis.R` - This script is used to perform the analysis of the given sample data
2. `avgdata.txt` - This is the output after executing the above R script.
3. `codebook.md` - This contains the variables that is generated by running the script.

# Note
1. Need to install `reshape` plugin for the script to run.
2. Need to download the sample data from the link mentioned above.
3. For better understanding of the output of the script `avgdata.txt` please view the file using NOTEPAD++
