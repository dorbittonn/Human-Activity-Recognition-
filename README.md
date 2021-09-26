# Human Activity Recognition

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

SOURCE: https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones#

This specific task is actually about predicting the human activity using only 6 features (measurements of sensors) of a patient:

- Body Accelerations in 3 axes
- Angular velocity in 3 axes (Measured by Gyro)

To handle this task I've used of LSTM vs KNN - one Deep learning model and another Classic ML model.
