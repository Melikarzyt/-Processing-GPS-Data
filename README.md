# -Processing-GPS-Data
“A data cleaning practice project focused on missing GPS data and outlier detection using IQR.

# GPS Data Cleaning, Missing Data, and Outlier Detection Practice

## Project Overview  
This project focuses on cleaning and preprocessing GPS data collected from a car tracking device. The dataset contains missing values and unrealistic data points due to occasional recording issues by the device.  
The main goal is to practice essential data preprocessing techniques such as handling missing values and detecting outliers — crucial steps in any data analysis or machine learning pipeline.

## Tasks Completed  
- Uploaded the CSV file and displayed the first five rows  
- Displayed dataset structure using `info()`  
- Replaced NaN values with the mean of each column  
- Handled missing values using `SimpleImputer`  
- Detected and replaced outliers using the Interquartile Range (IQR) method
