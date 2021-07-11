# Variables: <br />
* In the downloaded dataset exist : x_train, y_train, x_test, y_test, subject_train and subject_test that contain the data.<br />
* x_data, y_data, subject_data merge the previous datasets to further analysis.<br />
* features contains the correct names for the x_data dataset, which are applied to the column names stored in.<br />
<br />
<br />


# Source Data: <br />
The source data are from the Human Activity Recognition Using Samsung Galaxy S Smartphones Data Set. A full description is available at the site where the data was obtained:<br />
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones <br />
data project zip file:<br />
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip <br />
<br />
<br />

# Description of R script:<br />
1. Reading in the files and merging the training and the test sets to create one data set.<br />
   1.1 Reading following files:<br />
   1.1.1 Training tabels.<br />
   1.1.2 Testing tabels.<br />
   1.1.3 Feature vector.<br />
   1.1.4 Activity labels.<br />
   1.2 Assigning variable names.<br />
   1.3 Merging all data in one set.<br />
<br />
2. Extracting only the measurements on the mean and standard deviation for each measurement.<br />
   2.1 Reading variable names.<br />
   2.2 Create vector for defining ID, mean and standard deviation.<br />
   2.3 Making nessesary subset from merged data set.<br />
   <br />
3. Using descriptive activity names to name the activities in the data set.<br />
<br />
4. Labeling the data set with descriptive variable names.<br />
<br />
5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject.<br />
   5.1 Making second tidy data set.<br />
   5.2 Writing second tidy data set in txt file.(tidtSet.txt)<br />

