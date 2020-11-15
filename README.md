# Getting and Cleaning Data - Course Project

This repository contains the Getting and Cleaning Data Course Project

# Description 
- Dataset: contains the database Human Activity Recognition Using Smartphones Data Set, The files are separated into a set of train and test. 
the names of the characteristics and activities are in separate archival, all files are <code>.txt</code>
- CodeBook.md : contains a description of the database and the scripts.
- Run_Analysis.R :performs the analysis and cleaning of the data
  - Read the dataset from the <code>Dataset</code> folder
  - Merge training and test data to create a single data set.
  - Extract the mean and standard deviation of each measure from the data set.
  - Rename the characteristics of the data set with descriptive variable names.
  - Change the values the activities
  - Create a new data set with the average of the characteristics based on each subject and activity.
- Data.txt: single data set of size <code>10299x68</code>, 
- Dity_Data.txt: are the ordered and averaged data regarding subjects and activities of size <code>180x68</code>, 
