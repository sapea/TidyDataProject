#  Steps to get tidyData dataframe

## Step 1
   
 * with setwd() I set my working directory
 * subject_train dataframe: I upload with read.table() subject_train.txt dataframe 
 * xTrain dataframe   : with read.table() I upload X_train.txt dataframe 
 * yTrain dataframe : with read.table() I upload y_train.txt dataframe 
 * subjectTest dataframe: with read.table() I upload subject_test.txt dataframe 
 * xTest dataframe: with read.table() I upload X_test.txt dataframe
 * yTest dataframe: with read.table() I upload y_test.txt dataframe 
 * with dim() I get  subjectTest dimension: 2947 rows and 1 column
 * with dim() I get  subjectTrain dimension: 7352 rows and 1 column
 * subjectData dataframe : subjectTest and subjectTrain both have 1 column,so I join them by adding their rows with rbind()
 * with dim() I get subjectData dimension: 10299 rows (sums of the rows of  subjectTest and subjectTrain) and 1 column
 * with colnames() I name "subject" the  only column of subjectData
 * with dim() I get  yTest dimension: 2947 rows and 1 column
 * with dim() I get  yTrain dimension: 7352 rows and 1 column
 * activityData dataframe : yTest and yTrain both have 1 column,so I join them by adding their rows with rbind()
 * with dim() I get activityData dimension: 10299 rows (sums of the rows of  yTest and yTrain) and 1 column
 * with colnames() I name "activity" the  only column of activityData
 * with dim() I get  xTest dimension: 2947 rows and 561 columns
 * with dim() I get  xTrain dimension: 7352 rows and 561 columns
 * recordingsTotalData dataframe: xTest and xTrain both have 561 columns,so I join them by adding their rows with rbind()
 * with dim() I get recordingsTotalData dimension: 10299 rows (sums of the rows of  xTest and xTrain) and 561 columns
 * subjectActivityData dataframe : subjectData and activityData both have 10299 rows,so I join them by adding their columns with cbind()
 * with dim() I get subjectActivityData dimension: 10299 rows and 2 columns (sums of the columns of subjectData and activityData)
 * testTrainTotalData dataframe: subjectActivityData and recordingsTotalData both have 10299 rows,so I join them by adding their columns with cbind()
 * with dim() I get testTrainTotalData dimension: 10299 rows and 563 columns (sums of the columns of  subjectActivityData and recordingsTotalData)
 
 ## Step 2
 
 * features dataframe : with read.table() I upload features.txt dataframe 
 * character vector recordingsTotalNames: I take the second column of features dataframe and with as.character() I transform it in this vector which contains the 561 names of all experiments recordings
 * logic vector recordingsLogic: with grepl() I analyze the character vector recordingsTotalNames to search only the names which contain words "mean()" (mean value) or "std()" (standard deviation)
 * testTrainData dataframe : I create this new dataframe by keeping subject and  activity columns of testTrainTotalData and selecting only mean or std recordings measurements columns thanks to logic vector recordingsLogic
 
 ## Step 3
 
 * activityLabels dataframe: with read.table() I upload activity_labels.txt dataframe
 * with unclass() and table() I see the six factors levels of activityLabels
 * integer vector activityNumbers: I extract activity column of testTrainData which is composed of 10299 activity numbers
 * character vector activityNames:I extract the second column (column with activity names) from activityLabels dataframe and I associate it integer vector activityNumbers,using factor levels of activityLabels.So I get the factor vector composed of 10299 activity names and with as.character() I turned it into character vector  
 * I set activity column of testTrainData is equal to vector activityNames and so activities in the data set have descriptive names
 
  ## Step 4
   
 * character vector recordingsNames: I extract from character vector recordingsTotalNames only the 66 names which contain words "mean()" or "std()", using logic vector recordingsLogic
 * with colnames() I name columns testTrainData ranging from 3th to 68th (1th and 2th columns are "subject" and "activity" ) with character vector recordingsNames and so recordings variable in the data set have descriptive names
 
 ##  Step 5
 
 * with library (dplyr) I load dplyr package
 * tidyData dataframe: with group_by() I group testTrainData by activity and subject and then with summarise_each() I get the mean value of recordings columns (ranging from 3th to 68th) for each activity and each subject.
 * with write.table() I create a txt file of tidyData dataframe, which I save in my directory. 
 
 ## How you can read in R my tidyData.txt
 
 * you save my tidyData.txt in your R working directory and then you upload it with the following code: tidyFinalData<-read.table(file= "tidyData.txt",header=TRUE). Then: View(tidyFinalData)
 
 
 