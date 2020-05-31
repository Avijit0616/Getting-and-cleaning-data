# Getting-and-cleaning-data
  This is the course project for the Getting and Cleaning Data Coursera course. The R script, run_analysis.R, does the following:

1. Download and unzip the dataset if it does not already exist in the working directory(via the link https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)
2. Read both the train and test datasets and merge them into x(measurements), y(activity) and subject, respectively.
3. Load the data feature, activity info and extract columns named 'mean'(-mean) and 'standard'(-std)
4. Select the measurements(x) of the extracted columns in the previous step
5. Merges the selected measurements(x) with activity and subject info.
6. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
