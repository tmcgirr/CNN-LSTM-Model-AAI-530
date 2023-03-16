# IoT Aquaponics Sensor Data Predictions

### MSAAI-503-03-SP23-Final-Project-TEAM6

This project aims to measure fish growth over time based on the water conditions of twelve ponds using machine learning. The project uses a gradient boosting model to predict fish growth based on water conditions, and LSTM to predict the reading expected in three minutes for each sensor attribute.

## Table of Contents

* [Data](Data)
* [Data Cleaning](Data_Cleaning)
* [Documents](Documents)
* [EDA](EDA)
* [Time Series Model Data](Time_Series_Model_Data)
* [Weight Prediction Model Data](Weight_prediction_Models)


Data
-----------------------------
[This](Data) folder contains the final csv files including the cleaned data pond, training and validation data, and combined dataset of the validation set with the predicted fish growth and predicted sensor data. The [combined pond result](Data/combined_pond_result.csv) csv will contain the dataframe with the attribues and their predictions.


Data Cleaning
-----------------------------
[This](Data_Cleaning) folder contains all of the Jupyter notebooks used in the data cleaning process. The notebooks include data cleaning procedures such as removing duplicates, handling missing values, and transforming data into a suitable format for machine learning models.

Documents
-----------------------------
[This](Documents) folder contains all the text documents for the sensor data and reports. These documents provide detailed descriptions of the sensor data and explain the methodology used in the project.

EDA
-----------------------------
[This](EDA) folder contains all of the Jupyter notebooks for the initial data processing and visualization. The notebooks were used to determine the volume, consistency, missing data as well as obvious correlations in the data. These notebooks were used to gain insights into the data and inform further data cleaning and model building.

Time Series Model Data
-----------------------------
[This](Time_Series_Model_Data) folder contains the LSTM Jupyter notebook that creates all of the predictions for each individual sensor. The notebook contains the code for the LSTM model that was trained to predict the readings expected in three minutes for each sensor attribute. The [CNN LSTM Workbook](Time_Series_Model_Data/CNN_LSTM_Workbook.ipynb) will contain the process of training, evaluating and generating the predictions for each sensor.

Weight Prediction Model Data
-----------------------------
[This](Weight_prediction_Models) folder contains the Jupyter notebooks and data for the fish weight prediction. The notebooks include the code for the gradient boosting model used to predict fish growth based on water conditions. The folder also contains the training and validation datasets used to train and test the model. The [Weight Difference Prediction](Weight_prediction_Models/Weight_Diff_Predictions.ipynb) will contain the process of training, evaluating and generating the predictions for the weight differences based on the pond conditions.
