# AAIP Batch 18 Project
## Suresh Oliver Lakes [email: suresholiverlakes@yahoo.com.sg]

#### The submitted folder structure is as follows:
     1. .github
     2.  src
         a. Python file consisting of end-to-end ML pipeline in .py format
     3. README.md
     4. eda.ipynb
     5. requirements.txt
     6. run.sh
      
The Steps taken for the EDA and to develop the ML pipeline are as follows:

## Content
1. Import and Understand Data
2. Clean Data
3. Feature Selection
4. Train and Test Data
5. Model Accuracy
6. Summary

Followinn the study of the data types and data, the data are cleaned. This is the foremost the most important part of EDA before features selection which is equally important for ML projects.

We have used all of the following features to predict the outcome for **Daily Solar Panel Efficiency**

_Daily Rainfall Total (mm)_
_Highest 30 Min Rainfall (mm)_
_Highest 60 Min Rainfall (mm)_
_Highest 120 Min Rainfall (mm)_
_Min Temperature (deg C)_
_Maximum Temperature (deg C)_
_Min Wind Speed (km/h)_
_Max Wind Speed (km/h)_
_Sunshine Duration (hrs)_
_Cloud Cover (%)_
_Wet Bulb Temperature (deg F)_
_Relative Humidity (%)_
_Air Pressure (hPa)_
_Dew Point Category_
_Wind Direction_

The model used is based on **scikit-learn** which is the most common package. In particular due to time constraints we have used the logstics regression model
It would have been ideal to build other ML models such as Decision Trees and Random Forest so that users are able to compare the models. Also it would have been
ideal to create a function to call these models based on user need.

The in deployment of the logistics regression model, we have used the metrices such as **accuracy_score, confusion matrix, and classification report**. With reference to the accuracy score we take comfort in the fact that the train and test scores are very close indicating that the training dataset is accurate. If more time is available, it would have been ideal to join the Air Quality dataset as well to see if these also impact **Daily Solar Panel Efficiency**

Fruther details of each of the EDA steps taken are described in the "eda.ipynb"  file
