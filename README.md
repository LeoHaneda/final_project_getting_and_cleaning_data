## final_project_getting_and_cleaning_data
This repository contains the R code, codebook, and tidy data set from the final project of Coursera's "Getting and Cleaning Data" course.

##Course Project Overview
Johns Hopkins Data Science Specialization Getting and Cleaning Data Coursera Week 4 Class Project

R code for Cleaning and Working with Data

#Source Data

The data used in this course project represent data collected from the accelerometers from the Samsung Galaxy S smartphone.

More information can be found at the data source website: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The data for this project can be downloaded here:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

#The R run_analysis.R code in this repository primarily performs these 5 functions:

Merges the training and the test sets to create one data set.

Extracts only the measurements on the mean and standard deviation for each measurement

Uses descriptive activity names to name the activities in the data set

Appropriately labels the data set with descriptive variable names

From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject

#Files:
CodeBook.md describes the how to use all this, variables, the data, and any transformations or work that was performed to clean up the data.

run_analysis.R contains all the code to perform the analyses described in the 5 steps. They can be launched in RStudio by just importing the file.

tidyData.txt is the output of the final step
