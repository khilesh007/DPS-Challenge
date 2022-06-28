
# DPS Challenege
This repository provides the code, plots, JSON endpoints and google cloud webapp to visualise and predict historically the number of accidents per category and to forecast the values for the future. The method is applied to a data set which contains the monthly values for traffic accidents in Munich until the end of 2020.

## Dataset
The data set "Monatszahlen Verkehrsunfälle" can be downloaded from the below link
Link:https://www.opengov-muenchen.de/dataset/monatszahlen-verkehrsunfaelle/resource/40094bd6-f82d-4979-949b-26c8dc00b9a7

## Web Application:

The link of the Web app is : https://mydpsproject.el.r.appspot.com/
The webapp is created using Flask and deployed to Google Cloud Platform.

![App Screenshot](https://github.com/khilesh007/DPS-Challenge/blob/main/Images/WebApp.png?raw=true)

Here, the user can enter the year and month and the webapp will give the prediction of number of accidents as an output.

## End Points that returns the Predictions in JSON Format :

Use this API endpoint https://mydpsproject.el.r.appspot.com//api/predict to returns your predictions.

![App Screenshot](https://github.com/khilesh007/DPS-Challenge/blob/main/Images/Postman.png?raw=true)

## Visualization
Visualizing historically the number of accidents per category

**Accidents by category**
![App Screenshot](https://github.com/khilesh007/DPS-Challenge/blob/main/Images/Visualization1.png?raw=true)
![App Screenshot](https://github.com/khilesh007/DPS-Challenge/blob/main/Images/Visualization2.png?raw=true)
![App Screenshot](https://github.com/khilesh007/DPS-Challenge/blob/main/Images/Visualization3.png?raw=true)
![App Screenshot](https://github.com/khilesh007/DPS-Challenge/blob/main/Images/Visualization4.png?raw=true)

**Number of Accidents per category**
![App Screenshot](https://github.com/khilesh007/DPS-Challenge/blob/main/Images/Category.png?raw=true)

**Number of Accidents per Accident_type**

![App Screenshot](https://github.com/khilesh007/DPS-Challenge/blob/main/Images/Accident%20Type.png?raw=true)


