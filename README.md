# DBSD
Driver Behavior Bio-signal Dataset

The compressed DBSD Dataset file contains five CSV files

The CollectedDataSamples file is a CSV file containing all samples of aggressive driving behaviors. It is collected from the accelerometer (Accel_X, Accel_Y, Accel_Z) and gyroscope (Gyro_X, Gyro_Y, Gyro_Z) of the Wearable Shimmer3 IMU Unit sensor, as well as, the Timestamp, Class_Number, Class_Label, Class_Name. 
It contains 120,000 data samples.

The TrainSet_ProcessdDataset1 file is a CSV file containing the train instances that are processed from the original dataset using a window size of 200 and a time step of 20. It has 4193 instances.
The TestSet_ProcessdDataset1 file is a CSV file containing the test instances that are processed from the original dataset using a window size of 200 and a time step of 20. It has 1797 instances.

The TrainSet_ProcessdDataset2 file is a CSV file containing the train instances that are processed from the original dataset using a window size of 400 and a time step of 40. It has 2093 instances.
The TestSet_ProcessdDataset2 file is a CSV file containing the test instances that are processed from the original dataset using a window size of 400 and a time step of 40. It has 897 instances.
  
The Class_Number, Class_Name, and Class_Label of aggressive driving behaviors are as follows:

Behavior Class Number	Behavior Class Name	          Behavior Class Label
0	                Non-aggressive	                  NonAgr
1	                Aggressive breaking	          AgrBrk
2	                Aggressive acceleration	          AgrAce
3	                Aggressive left lane change       AgrLefLanCha
4	                Aggressive right lane change      AgrRigLanCha
