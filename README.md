# Coursera-Getting-And-Cleaning-Data-Project
Coursera "Getting and Cleaning Data" Final Project
# Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does the following:

A. Download the dataset if it does not already exist in the working directory
B. Load the activity and feature information
C. Loads both the training and test datasets while keeping only those columns      which contain a mean or standard deviation
D. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset
E. Merges the two datasets together
F. Converts the `activity` and `subject` columns into factors
G. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.

The end result is shown in the file `tidy.txt`.
