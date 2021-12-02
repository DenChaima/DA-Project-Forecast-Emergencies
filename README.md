# Data Analysis Project 

Build a model to forecast future hospital emergency admissions based on past emergency admissions.

## Dataset 

The data used in this project is obtained from the Hospital Episodes Statistics (HES) dataset which consists of the record of all patients admitted to NHS (public) hospitals in the United Kingdom. 
Only the date ("Month_Ending") and the treatment speciality type ("TRETSPEF") columns are kept to predict the number of emergency admissions ("EMERGENCY") in the future. All the other columns are dropped. 

Complete dataset available on the [NHS Digital website](https://digital.nhs.uk/data-and-information/publications/statistical/hospital-episode-statistics-for-admitted-patient-care-outpatient-and-accident-and-emergency-data/april-2021---september-2021)

## Prerequisites 
The modules needed to run this project can be installed using **pip**

## Project's steps:

- Preprocessing the data: 
    - Normalize the data: to obtain better results.
    - Interpolate the data: to handle the missing values,
    - Split data into training set and test set. 
    - Format the data: to transform the time series problem to a supervised learning problem. 
    - Reshape data: give the data the 3D shape expected by LSTMs. 
- Implement the model:
    -  Build the LSTM model. 
    -  Train the model 

- Make predictions:
    - Use the model to make predictions 
    - Plot the predicted values compared to the actual values
