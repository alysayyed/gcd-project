# Coursera Course Project (Getting and Cleaning Data)

This is the Coursera Course (Getting and Cleaning Data) Project.
The attached R script, `run_analysis.R`, does the following:

1. Download the dataset from web if it does not already exist in the working directory.
2. Load the activity and feature information
3. Read both the training and test datasets and keeps the columns named mean(-mean) and standard(-std).
4. Loads the activity and subject data for each dataset, and merges those columns with the dataset
5. Merges the two datasets
6. Converts the `activity` and `subject` columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The result is shown in the file `tidy.txt`.
