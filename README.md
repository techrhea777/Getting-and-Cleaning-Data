Getting and Cleaning Data Course Project

Project Overview

The purpose of this project is to demonstrate your ability to collect, work with, and clean a dataset. The goal is to prepare a tidy data set that can be used for later analysis. This project involves data from accelerometers on the Samsung Galaxy S smartphone.

Data Source

The data used in this project is from the Human Activity Recognition Using Smartphones Dataset. The data linked to from the course website represents data collected from the accelerometers from the Samsung Galaxy S smartphone.

Files Included in This Repository

run_analysis.R: This script performs the following actions:

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set.
Appropriately labels the data set with descriptive variable names.
From the data set in the previous step, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
CodeBook.md: This file describes the variables, data, and any transformations or work that was performed to clean up the data.

README.md: This file explains the purpose of the project, how to use the files in this repository, and details about the project.

tidy_data_set.csv: This is the final tidy data set output by the run_analysis.R script.

Steps to Reproduce the Analysis

To reproduce the analysis:

Clone this repository to your local machine.
Download the data set from this link and unzip it into your working directory.
Place the run_analysis.R script in your working directory.
Run the run_analysis.R script.
The output will be a file named tidy_data_set.csv in your working directory.
Grading Criteria

The submitted data set is tidy.
The GitHub repository contains the required scripts.
The CodeBook.md file modifies and updates the available codebooks with the data to indicate all the variables and summaries calculated, along with units and any other relevant information.
The README.md file explains the analysis files clearly and understandably.
The work submitted for this project is the work of the student who submitted it.
