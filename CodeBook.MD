#TidyData CodeBook

### 1) activity 
#### class: character
 Group of six motor activities performed by volunteers wearing a smartphone (Samsung Galaxy S II) on the waist.Using its embedded accelerometer and gyroscope, 3-axial linear acceleration and 3-axial angular velocity were captured at a constant rate of 50Hz
 
 * LAYING
 * SITTING
 * STANDING
 * WALKING
 * WALKING_DOWNSTAIRS
 * WALKING_UPSTAIRS

### 2) subject
#### class: integer
Group of 30 volunteers within an age bracket of 19-48 years, who performed experiments
 
 * 1
 * 2
 * 3
 * 4
 * 5
 * 6
 * 7
 * 8
 * 9
 * 10
 * 11
 * 12
 * 13
 * 14
 * 15
 * 16
 * 17
 * 18
 * 19
 * 20
 * 21
 * 22
 * 23
 * 24
 * 25
 * 26
 * 27
 * 28
 * 29
 * 30

## Variables from 3th to 68th
#### class: numeric 
* The acceleration signal from the smartphone accelerometer is the total acceleration: total acceleration= BodyAcc(body acceleration signal)+GravityAcc(gravity acceleration signal).
   Acceleration units: standard gravity units "g"
* BodyGyro is the angular velocity measured by the gyroscope.The units are radians/second 

### 3) tBodyAcc-mean()-X 
Mean value of body linear acceleration signal along direction of the X axis
 
 * variable number between 0.2216 and 0.3015
 
### 4) tBodyAcc-mean()-Y
Mean value of body linear acceleration signal along direction of the Y axis
 
 * variable number between -0.040514 and -0.001308 

### 5) tBodyAcc-mean()-Z 
Mean value of body linear acceleration signal along direction of the Z axis
 
 * variable number between -0.15251 and -0.07538
 
### 6) tBodyAcc-std()-X
Standard deviation of body linear acceleration signal along direction of the X axis

 * variable number between -0.9961 and 0.6269 

### 7) tBodyAcc-std()-Y
Standard deviation of body linear acceleration signal along direction of the Y axis

 * variable number between -0.76613 and 0.39243

### 8) tBodyAcc-std()-Z
Standard deviation of body linear acceleration signal along direction of the Z axis

 * variable number between -0.63235 and 0.60206

### 9) tGravityAcc-mean()-X
Mean value of gravity acceleration signal along direction of the X axis

 * variable number between -0.6800 and 0.9745

### 10) tGravityAcc-mean()-Y
Mean value of gravity acceleration signal along direction of the Y axis

 * variable number between -0.47989 and 0.95659

### 11) tGravityAcc-mean()-Z
Mean value of gravity acceleration signal along direction of the Z axis

 * variable number between -0.49509 and 0.95787

### 12) tGravityAcc-std()-X
Standard deviation of gravity acceleration signal along direction of the X axis

 * variable number between -0.9968 and -0.8296

### 13) tGravityAcc-std()-Y
Standard deviation of gravity acceleration signal along direction of the Y axis

 * variable number between -0.93782 and 0.90239

### 14) tGravityAcc-std()-Z
Standard deviation of gravity acceleration signal along direction of the Z axis

 * variable number between -0.93050 and 0.73379

### 15) tBodyAccJerk-mean()-X
Mean value of Jerk signal of body linear acceleration along direction of the X axis

 * variable number between 0.04269 and 0.13019
 
### 16) tBodyAccJerk-mean()-Y
Mean value of Jerk signal of body linear acceleration along direction of the Y axis

 * variable number between -0.0386872 and 0.0568186
 
### 17) tBodyAccJerk-mean()-Z
Mean value of Jerk signal of body linear acceleration along direction of the Z axis

 * variable number between -0.067458 and 0.038053
 
### 18) tBodyAccJerk-std()-X
Standard deviation of Jerk signal of body linear acceleration along direction of the X axis

 * variable number between -0.9946 and 0.5443
 
### 19) tBodyAccJerk-std()-Y
Standard deviation of Jerk signal of body linear acceleration along direction of the Y axis

 * variable number between -0.474625 and 0.617605
 
### 20) tBodyAccJerk-std()-Z
Standard deviation of Jerk signal of body linear acceleration along direction of the Z axis

 * variable number between -0.31108 and 0.60828
 
### 21) tBodyGyro-mean()-X
Mean value of body angular velocity signal along direction of the X axis

 * variable number between -0.20578 and 0.19270
 
### 22) tBodyGyro-mean()-Y
Mean value of body angular velocity signal along direction of the Y axis

 * variable number between -0.20421 and 0.02747
 
### 23) tBodyGyro-mean()-Z
Mean value of body angular velocity signal along direction of the Z axis

 * variable number between -0.07245 and 0.17910
 
### 24) tBodyGyro-std()-X 
Standard deviation of body angular velocity signal along direction of the X axis

 * variable number between -0.9943 and  0.2677
 
### 25) tBodyGyro-std()-Y
Standard deviation of body angular velocity signal along direction of the Y axis

 * variable number between -0.63424 and 0.55521

### 26) tBodyGyro-std()-Z
Standard deviation of body angular velocity signal along direction of the Z axis

 * variable number between -0.61639 and 0.71267
 
### 27) tBodyGyroJerk-mean()-X
Mean value of Jerk signal of body angular velocity along direction of the X axis

 * variable number between -0.15721 and -0.02209 

### 28) tBodyGyroJerk-mean()-Y
Mean value of Jerk signal of body angular velocity along direction of the Y axis

 * variable number between -0.07681 and -0.01320 

### 29) tBodyGyroJerk-mean()-Z
Mean value of Jerk signal of body angular velocity along direction of the Z axis

 * variable number between -0.092500 and -0.006941

### 30) tBodyGyroJerk-std()-X
Standard deviation of Jerk signal of body angular velocity along direction of the X axis

 * variable number between -0.9965 and 0.1791 

### 31) tBodyGyroJerk-std()-Y
Standard deviation of Jerk signal of body angular velocity along direction of the Y axis

 * variable number between -0.34551 and 0.52159 

### 32) tBodyGyroJerk-std()-Z
Standard deviation of Jerk signal of body angular velocity along direction of the Z axis

 * variable number between -0.499421 and 0.289402

### 33) tBodyAccMag-mean()
Mean value of magnitude of body linear acceleration signal

 * variable number between -0.24046 and 0.28179

### 34) tBodyAccMag-std()
Standard deviation of magnitude of body linear acceleration signal

 * variable number between -0.36472 and 0.30270

### 35) tGravityAccMag-mean()
Mean value of magnitude of gravity acceleration signal

 * variable number between -0.24046 and 0.28179

### 36) tGravityAccMag-std()
Standard deviation of magnitude of gravity acceleration signal

 * variable number between -0.36472 and 0.30270

### 37) tBodyAccJerkMag-mean()
Mean value of magnitude of Jerk signal of body linear acceleration

 * variable number between -0.48574 and 0.13709

### 38) tBodyAccJerkMag-std()
Standard deviation of magnitude of Jerk signal of body linear acceleration

 * variable number between -0.38581 and 0.37683

### 39) tBodyGyroMag-mean()
Mean value of magnitude of body angular velocity signal

 * variable number between -0.3385 and 0.4235

### 40) tBodyGyroMag-std()
Standard deviation of magnitude of body angular velocity signal

 * variable number between -0.355891 and 0.315765

### 41) tBodyGyroJerkMag-mean()
Mean value of magnitude of Jerk signal of body angular velocity

 * variable number between -0.632429 and 0.345238

### 42) tBodyGyroJerkMag-std()
Standard deviation of magnitude of Jerk signal of body angular velocity

 * variable number between -0.44625 and 0.47972

### 43) fBodyAcc-mean()-X
Mean value of Fast Fourier Transform of body linear acceleration signal along direction of the X axis

 * variable number between -0.9952 and 0.5370

### 44) fBodyAcc-mean()-Y
Mean value of Fast Fourier Transform of body linear acceleration signal along direction of the Y axis

 * variable number between -0.98903 and 0.52419

### 45) fBodyAcc-mean()-Z
Mean value of Fast Fourier Transform of body linear acceleration signal along direction of the Z axis

 * variable number between -0.9895 and 0.2807

### 46) fBodyAcc-std()-X 
Standard deviation of Fast Fourier Transform of body linear acceleration signal along direction of the X axis

 * variable number between -0.9966 and 0.6585

### 47) fBodyAcc-std()-Y 
Standard deviation of Fast Fourier Transform of body linear acceleration signal along direction of the Y axis

 * variable number between -0.9997 and 0.3206

### 48) fBodyAcc-std()-Z
Standard deviation of Fast Fourier Transform of body linear acceleration signal along direction of the Z axis

 * variable number between -0.9998 and -0.5594

### 49) fBodyAccJerk-mean()-X
Mean value of Fast Fourier Transform of Jerk signal of body linear acceleration along direction of the X axis

 * variable number between -0.9946 and 0.4743

### 50) fBodyAccJerk-mean()-Y
Mean value of Fast Fourier Transform of Jerk signal of body linear acceleration along direction of the Y axis

 * variable number between -0.9894 and 0.2767

### 51) fBodyAccJerk-mean()-Z
Mean value of Fast Fourier Transform of Jerk signal of body linear acceleration along direction of the Z axis

 * variable number between -0.9920 and 0.1578 

### 52) fBodyAccJerk-std()-X
Standard deviation of Fast Fourier Transform of Jerk signal of body linear acceleration along direction of the X axis

 * variable number between -0.9951 and 0.4768 
 
### 53) fBodyAccJerk-std()-Y

Standard deviation of Fast Fourier Transform of Jerk signal of body linear acceleration along direction of the Y axis

 * variable number between -0.9999 and -0.1739
 
### 54) fBodyAccJerk-std()-Z
Standard deviation of Fast Fourier Transform of Jerk signal of body linear acceleration along direction of the Z axis

 * variable number between -0.9999 and -0.5624
 
### 55) fBodyGyro-mean()-X
Mean value of Fast Fourier Transform of body angular velocity signal along direction of the X axis

 * variable number between -0.9931 and 0.4750 
 
### 56) fBodyGyro-mean()-Y
Mean value of Fast Fourier Transform of body angular velocity signal along direction of the Y axis

 * variable number between -0.9940 and 0.3288 
 
### 57) fBodyGyro-mean()-Z
Mean value of Fast Fourier Transform of body angular velocity signal along direction of the Z axis

 * variable number between -0.9860 and 0.4924
 
### 58) fBodyGyro-std()-X 
Standard deviation of Fast Fourier Transform of body angular velocity signal along direction of the X axis

 * variable number between -0.9947 and 0.1966
 
### 59) fBodyGyro-std()-Y
Standard deviation of Fast Fourier Transform of body angular velocity signal along direction of the Y axis

 * variable number between -0.9997 and 0.2421
 
### 60) fBodyGyro-std()-Z
Standard deviation of Fast Fourier Transform of body angular velocity signal along direction of the Z axis

 * variable number between -1.0000 and -0.5832 
 
### 61) fBodyAccMag-mean()
Mean value of Fast Fourier Transform of magnitude of body linear acceleration signal

 * variable number between -0.7000 and 0.1473 
 
### 62) fBodyAccMag-std()
Standard deviation of Fast Fourier Transform of magnitude of body linear acceleration signal

 * variable number between -0.90484 and -0.09634
 
### 63) fBodyBodyAccJerkMag-mean() 
Mean value of Fast Fourier Transform of magnitude of Jerk signal of body linear acceleration

 * variable number between -0.6579 and 0.5198
 
### 64) fBodyBodyAccJerkMag-std()
Standard deviation of Fast Fourier Transform of magnitude of Jerk signal of body linear acceleration 

 * variable number between -0.8988 and 0.3343 

### 65) fBodyBodyGyroMag-mean()
Mean value of Fast Fourier Transform of magnitude of body angular velocity signal

 * variable number between -0.6344 and 0.1654
 
### 66) fBodyBodyGyroMag-std()
Standard deviation of Fast Fourier Transform of magnitude of body angular velocity signal

 * variable number between -0.84972 and -0.09368
 
### 67) fBodyBodyGyroJerkMag-mean()
Mean value of Fast Fourier Transform of magnitude of Jerk signal of body angular velocity

* variable number between -0.87457 and 0.42476 

### 68) fBodyBodyGyroJerkMag-std()
Standard deviation of Fast Fourier Transform of magnitude of Jerk signal of body angular velocity

* variable number between -0.873649 and 0.390444
