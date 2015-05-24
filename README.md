# Getting_and_Cleaning_Data
# Course Project
The run_analysis accomplishes the following tasks:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# Directions:
1. Unzip the source file (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive, example: C:/User/yourname/Documents/UCI HAR Dataset/
2. Put run_analysis.R into C:/Users/yourname/Documents/UCI HAR Dataset/
3. In RStudio: setwd("C:/Users\yourname/Documents/"), followed by: source("run_analysis.R")
4. Use data <- read.table("UCI HAR Dataset/data_set_with_the_averages.txt") to read the data.
