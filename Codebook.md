Assessment project

The original data was transformed by

  1.- Merges the training and the test sets to create one data set.
  2.- Extracts only the measurements on the mean and standard deviation for each measurement. 
  3.- Uses descriptive activity names to name the activities in the data set
  4.- Appropriately labels the data set with descriptive variable names. 
  5.- From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
  
Result of this code:

  "ActivityName" 
  "SubjectID" 
  "tBodyAccMeanX" "tBodyAccMeanY" "tBodyAccMeanZ" "tBodyAccStdX" "tBodyAccStdY" "tBodyAccStdZ" 
  "tGravityAccMeanX" "tGravityAccMeanY" "tGravityAccMeanZ" "tGravityAccStdX" "tGravityAccStdY" "tGravityAccStdZ" 
  "tBodyAccJerkMeanX" "tBodyAccJerkMeanY" "tBodyAccJerkMeanZ" "tBodyAccJerkStdX" "tBodyAccJerkStdY" "tBodyAccJerkStdZ"
  "tBodyGyroMeanX" "tBodyGyroMeanY" "tBodyGyroMeanZ" "tBodyGyroStdX" "tBodyGyroStdY" "tBodyGyroStdZ" 
  "tBodyGyroJerkMeanX" "tBodyGyroJerkMeanY" "tBodyGyroJerkMeanZ" "tBodyGyroJerkStdX" "tBodyGyroJerkStdY" 
  "tBodyGyroJerkStdZ" "tBodyAccMagMean" "tBodyAccMagStd" "tGravityAccMagMean" "tGravityAccMagStd" "
  tBodyAccJerkMagMean" "tBodyAccJerkMagStd" "tBodyGyroMagMean" "tBodyGyroMagStd" "tBodyGyroJerkMagMean" 
  "tBodyGyroJerkMagStd" "fBodyAccMeanX" "fBodyAccMeanY" "fBodyAccMeanZ" "fBodyAccStdX" "fBodyAccStdY" "fBodyAccStdZ" 
  "fBodyAccJerkMeanX" "fBodyAccJerkMeanY" "fBodyAccJerkMeanZ" "fBodyAccJerkStdX" "fBodyAccJerkStdY" "fBodyAccJerkStdZ"
  "fBodyGyroMeanX" "fBodyGyroMeanY" "fBodyGyroMeanZ" "fBodyGyroStdX" "fBodyGyroStdY" "fBodyGyroStdZ" 
  "fBodyAccMagMean"  "fBodyAccMagStd" "fBodyBodyAccJerkMagMean" "fBodyBodyAccJerkMagStd" "fBodyBodyGyroMagMean" "fBodyBodyGyroMagStd" "fBodyBodyGyroJerkMagMean" "fBodyBodyGyroJerkMagStd"

As a result, the variables remaining are just the calculatd means and standard deviations of these sets of data - one each for the X, Y and Z dimensions:

  Means:
    "tBodyAccMeanX" 
    "tBodyAccMeanY" 
    "tBodyAccMeanZ" 
  Standard deviation:
    "tBodyAccStdX" 
    "tBodyAccStdY" 
    "tBodyAccStdZ" 
