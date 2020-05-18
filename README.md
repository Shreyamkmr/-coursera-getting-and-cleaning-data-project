# Getting and Cleaning Data - Course Project


The R script, `run_analysis.R`, does the following:

step#1. Download the dataset if it does not already exist in the working directory(script will parse only when the data set exist)
step#2. Load the activity and feature info
step#3. Loads both the training and test datasets, keeping only those columns which
   reflect a mean or standard deviation
step#4. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset
step#5. Merges the two datasets
step#6. Converts the `activity` and `subject` columns into factors
step#7. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.

The end result is shown in the file `clean_data.txt`.
