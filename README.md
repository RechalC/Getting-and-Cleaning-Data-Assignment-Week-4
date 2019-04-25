# Getting-and-Cleaning-Data-Assignment-Week-4
Coursera: Getting and Cleaning Data week 4 Peer Graded assignment

This is a repository created to complete the Week 4 - Peer Graded assignment of the Getting and Cleaning Data Course by Coursera.

### Data description
The variables in the data X are sensor signals measured with waist-mounted smartphone from 30 subjects (aged 19-48 years). The variable in the data Y indicates type of activity the subjects performed during recording.

### Code explaination
The code combines training and test dataset,  and extracts partial variables to create another dataset with the averages of each variable for every activity.

### New dataset
The new dataset generated contained variables calculated based on the mean and standard deviation. Each row of the dataset is an average of each activity type for all subjects.

### The code was written based on the instruction of this assignment
Read training and test dataset into R environment.
Read variable names into R envrionment.
Read subject index into R environment.

1. Merges the training and the test sets to create one data set.

2. Extracts only the measurements on the mean and standard deviation for each measurement.

3. Uses descriptive activity names to name the activities in the data set

4. Appropriately labels the data set with descriptive variable names.

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

