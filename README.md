# Getting-and-Cleaning-Data-Project

The R script, run_analysis.R, does the following:

*Downloads the dataset if it does not already exist in the working directory
*Loads the activity and feature info
*Loads both the training and test datasets, keeping only the columns with a mean or standard deviation
*Loads the activity and subject data for each dataset, and merges those columns with the dataset
*Merges the two datasets
*Creates a tidy dataset that consists of the average value of each variable for each subject and activity.
*The end result is shown in the file averages_data.txt.
