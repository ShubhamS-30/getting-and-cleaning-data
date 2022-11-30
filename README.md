
# Human Activity Recognition with Smartphones - Getting and Cleaning Data Course Project from Johns Hopkins University by Coursera 

## Processing
I created the script "run_analysis.R" which does the following:
1. It merges the training and the test sets to create one data set. The files used are txt files in the unzipped directories "train" and "test" with names starting with "subject_" with subject IDs, "X_" with measurements and "y_" with labels. They are read seperately and then bound together for "test" and "train" and finally bound together to form "alldata".

2. It extracts only the columns that include the measurements on the mean and standard deviation for each measurement, together with the key columns presenting the subject ID and the Activity. The columns extracted are those having the terms mean() or std() in the name of the variable. The "fixed" parameter is used to exclude cases like meanFreq(). 

3. Uses descriptive activity names to name the activities in the data set. For this purpose the file activity_labels.txt is used.

4. Appropriately labels the data set with descriptive variable names. The replacement uses the structure of the variable names. It has been developed and tested using the features.txt file. 

5. From the data set in step 4, it creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Files submitted
The following files have been included in this repo: 
1) the script "run_analysis.R" 
2) the tidy data set "TidyData.txt" produced by the script as indicated below, 
3) the present "README.md" file
4) code book describing the variables



