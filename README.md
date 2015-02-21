# Getting-and-Cleaning-Data-Course-Project


The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected. 

One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

 You should create one R script called run_analysis.R that does the following:
 
 In the run_analysis.R script, functions were created for each step.

##Function read_Data : 

Tkes two variables, the suffix for the filename, folder name in which the file exists. Since the data exists in two folders with file names as subject_train, X_train, y_train. The y_data file contains Activity_ID. The X_data file contains data for MeasureID and MeasureName. The subject_data file contains SubjectID. This function reads the three files from a folder and creates data.frame in R environment with appropriate column names. The grep function is used to match only those columns which has MeasureName for mean and standard deviation.

##Function read_test_data : 

Read the test data into the R environment

##Function read_train_data : 

Read the train data into the R environment

##Function mergeDataset : 

Combines the two dataset read in the above functions, by rows.

##Function activityLabels: 

Takes a dataset as argument and reads the activity labels from text files and merges it with the dataset.

##Function merge_label_data : 

Runs the activityLabels function to get a activity labelled dataset.

##Function tidyData: 

creates a tidy data set with average of each variable for each activity and each subject.

##Function tidy_datafile: 

A new tidy independent dataset is generated and saved a text file to be submitted.
