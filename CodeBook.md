## Study design
From the original authors:

> The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 
>
> The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain. See 'features_info.txt' for more details. 

## Code book
All signals were normalized to have a value ranging from -1 to 1, so all of the data is unitless.

Each variable below is a single column in the tidy datasets. For the details, I interpreted them to the best of my ability, but I am clearly not a physicist or engineer.

| Variable | Details
| -------- |---------
| Subject | The ID of the test subject.
| Test | The specific test peformed.
| time.BodyAcceleration.mean.X | Mean time for acceleration of body for X direction.
| time.BodyAcceleration.mean.Y | Mean time for acceleration of body for Y direction.
| time.BodyAcceleration.mean.Z | Mean time for acceleration of body for Z direction.
| time.BodyAcceleration.std.X | Standard deviation of time for acceleration of body for X direction.
| time.BodyAcceleration.std.Y | Standard deviation of time for acceleration of body for Y direction.
| time.BodyAcceleration.std.Z | Standard deviation of time for acceleration of body for Z direction.
| time.GravityAcceleration.mean.X | Mean time of acceleration of gravity for X direction.
| time.GravityAcceleration.mean.Y | Mean time of acceleration of gravity for Y direction.
| time.GravityAcceleration.mean.Z | Mean time of acceleration of gravity for Z direction.
| time.GravityAcceleration.std.X | Standard deviation of time of acceleration of gravity for X direction.
| time.GravityAcceleration.std.Y | Standard deviation of time of acceleration of gravity for Y direction.
| time.GravityAcceleration.std.Z | Standard deviation of time of acceleration of gravity for Z direction.
| time.BodyAccelerationJerk.mean.X | Mean time of body acceleration jerk for X direction. 
| time.BodyAccelerationJerk.mean.Y | Mean time of body acceleration jerk for Y direction
| time.BodyAccelerationJerk.mean.Z | Mean time of body acceleration jerk for Z direction
| time.BodyAccelerationJerk.std.X | Standard deviation of time of body acceleration jerk for X direction. 
| time.BodyAccelerationJerk.std.Y | Standard deviation of time of body acceleration jerk for Y direction. 
| time.BodyAccelerationJerk.std.Z | Standard deviation of time of body acceleration jerk for Z direction. 
| time.BodyGyro.mean.X | Mean body gyroscope measurement for X direction.
| time.BodyGyro.mean.Y | Mean body gyroscope measurement for Y direction.
| time.BodyGyro.mean.Z | Mean body gyroscope measurement for Z direction.
| time.BodyGyro.std.X | Standard deviation of body gyroscope measurement for X direction.
| time.BodyGyro.std.Y | Standard deviation of body gyroscope measurement for Y direction.
| time.BodyGyro.std.Z | Standard deviation of body gyroscope measurement for Z direction.
| time.BodyGyroJerk.mean.X | Mean jerk signal of body for X direction.
| time.BodyGyroJerk.mean.Y | Mean jerk signal of body for Y direction.
| time.BodyGyroJerk.mean.Z | Mean jerk signal of body for Z direction.
| time.BodyGyroJerk.std.X | Standard deviation of jerk signal of body for X direction.
| time.BodyGyroJerk.std.Y | Standard deviation of jerk signal of body for Y direction.
| time.BodyGyroJerk.std.Z | Standard deviation of jerk signal of body for Z direction.
| time.BodyAccelerationMagnitude.mean | Mean magnitude of body acceleration.
| time.BodyAccelerationMagnitude.std | Standard deviation of magnitude of body acceleration.
| time.GravityAccelerationMagnitude.mean | Mean gravity acceleration magnitude.
| time.GravityAccelerationMagnitude.std | Standard deviation of gravity acceleration magnitude.
| time.BodyAccelerationJerkMagnitude.mean | Mean magnitude of body acceleration jerk.
| time.BodyAccelerationJerkMagnitude.std | Standard deviation of magnitude of body acceleration jerk.
| time.BodyGyroMagnitude.mean | Mean magnitude of body gyroscope measurement.
| time.BodyGyroMagnitude.std | Standard deviation of magnitude of body gyroscope measurement.
| time.BodyGyroJerkMagnitude.mean | Mean magnitude of body body gyroscope jerk measurement.
| time.BodyGyroJerkMagnitude.std | Standard deviation of magnitude of body body gyroscope jerk measurement.
| freq.BodyAcceleration.mean.X | Mean frequency of body acceleration for X direction. 
| freq.BodyAcceleration.mean.Y | Mean frequency of body acceleration for Y direction. 
| freq.BodyAcceleration.mean.Z | Mean frequency of body acceleration for Z direction. 
| freq.BodyAcceleration.std.X | Standard deviation of frequency of body acceleration for X direction. 
| freq.BodyAcceleration.std.Y | Standard deviation of frequency of body acceleration for Y direction. 
| freq.BodyAcceleration.std.Z | Standard deviation of frequency of body acceleration for Z direction. 
| freq.BodyAccelerationJerk.mean.X | Mean frequency of body accerlation jerk for X direction.
| freq.BodyAccelerationJerk.mean.Y | Mean frequency of body accerlation jerk for Y direction.
| freq.BodyAccelerationJerk.mean.Z | Mean frequency of body accerlation jerk for Z direction.
| freq.BodyAccelerationJerk.std.X | Standard deviation frequency of body accerlation jerk for X direction.
| freq.BodyAccelerationJerk.std.Y | Standard deviation frequency of body accerlation jerk for Y direction.
| freq.BodyAccelerationJerk.std.Z | Standard deviation frequency of body accerlation jerk for Z direction.
| freq.BodyGyro.mean.X | Mean frequency of body gyroscope measurement for X direction.
| freq.BodyGyro.mean.Y | Mean frequency of body gyroscope measurement for Y direction.
| freq.BodyGyro.mean.Z | Mean frequency of body gyroscope measurement for Z direction.
| freq.BodyGyro.std.X | Standard deviation frequency of body gyroscope measurement for X direction.
| freq.BodyGyro.std.Y | Standard deviation frequency of body gyroscope measurement for Y direction.
| freq.BodyGyro.std.Z | Standard deviation frequency of body gyroscope measurement for Z direction.
| freq.BodyAccelerationMagnitude.mean | Mean frequency of body acceleration magnitude.
| freq.BodyAccelerationMagnitude.std | Standard deviation of frequency of body acceleration magnitude.
| freq.BodyBodyAccelerationJerkMagnitude.mean | Mean frequency of body acceleration jerk magnitude.
| freq.BodyBodyAccelerationJerkMagnitude.std | Standard deviation of frequency of body acceleration jerk magnitude.
| freq.BodyBodyGyroMagnitude.mean | Mean frequency of magnitude of body gyroscope measurement.
| freq.BodyBodyGyroMagnitude.std | Standard deviation of frequency of magnitude of body gyroscope measurement.
| freq.BodyBodyGyroJerkMagnitude.mean | Mean frequency of magnitude of body gyroscope jerk measurement.
| freq.BodyBodyGyroJerkMagnitude.std | Standard deviation of frequency of magnitude of body gyroscope jerk measurement.
| Set | Which set the measurement came from (train or test).
