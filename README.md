# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:

![Screenshot 2025-04-18 112420](https://github.com/user-attachments/assets/34ed6684-cb61-4219-a823-f0435d07b4a6)
![Screenshot 2025-04-18 112451](https://github.com/user-attachments/assets/7e85c6e8-48e0-46f7-bac4-59af9385a8d8)
![Screenshot 2025-04-18 112509](https://github.com/user-attachments/assets/6801c8f2-6244-492f-a5be-0f18921eb7ce)
![Screenshot 2025-04-18 112527](https://github.com/user-attachments/assets/6da0b3e8-50b7-4934-9ef4-ff031dd332a0)
![Screenshot 2025-04-18 112545](https://github.com/user-attachments/assets/4c79b7b3-3f9b-422a-b1fa-6e15e0b48ae6)
![Screenshot 2025-04-18 112642](https://github.com/user-attachments/assets/00783c1e-5603-40b6-8d2c-be7cf9900f5e)
![Screenshot 2025-04-18 112655](https://github.com/user-attachments/assets/a386f003-24e0-42cf-a592-7c7a79c2e2e9)
![Screenshot 2025-04-18 112709](https://github.com/user-attachments/assets/c0d30bad-dfef-48ff-9302-9233a67b9633)
# RESULT:
Feature scaling and Feature selection process sucessfully completed.
