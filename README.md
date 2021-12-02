# Data Analysis Project 

Build a model to forecast future hospital emergency admissions based on past emergency admissions.

## Dataset 

The data used in this project is obtained from the __Hospital Episodes Statistics (HES)__ dataset which consists of the record of all patients admitted to NHS (public) hospitals in the United Kingdom. 

Only the date (__"Month_Ending"__) and the treatment speciality type (__"TRETSPEF"__) columns are kept to predict the number of emergency admissions (__"EMERGENCY"__) in the future. All the other columns are dropped. 

Complete dataset available on the [NHS Digital website](https://digital.nhs.uk/data-and-information/publications/statistical/hospital-episode-statistics-for-admitted-patient-care-outpatient-and-accident-and-emergency-data/april-2021---september-2021)

## Prerequisites 
The modules needed to run this project can be installed using **pip**

## Project's steps:

- __Preprocessing the data: __
    - Normalize the data: to obtain better results.
    - Interpolate the data: to handle the missing values,
    - Split data into training set and test set. 
    - Format the data: to transform the time series problem to a supervised learning problem. 
    - Reshape data: give the data the 3D shape expected by LSTMs. 
- __Implement the model:__
    -  Build the LSTM model. 
    -  Train the model 

- __Make predictions:__
    - Use the model to make predictions 
    - Plot the predicted values compared to the actual values
