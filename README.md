# Student-Registry-Status

![image](https://user-images.githubusercontent.com/81252980/144570320-77b00f27-1a13-42d0-9cdc-73928be35fab.png)

A machine learning project predicting student registry status for the upcoming university semester.

Project authors: **Lina Hourieh**, **Sara Ghaboura**, **Zeinab Zeitoun** and **Imad Moustafa**

## why is it important to predict student status?
- Optimizing resources such as books, labs, materials, dormatory, lecturer contract and etc. 
- Being prepared to help out students acadamically, financially and psychologically.
- Helping out in budget planning 

## How to predict student status?
Traditional ways are time consuming and inaccurate so we tried machine learning method.

## Libraries used:
- numpy
- pandas
- seaborn
- matplotlib
- shap

## Scaling techniques adapted:
- Robust Scaling
- Standard Scaling

## Exploratory Data Analysis with Pandas


+ pie chart showing students who dropped/ didn't register for the semester (dropped) versus those who continued studying (continued)
![image](https://user-images.githubusercontent.com/81252980/144564985-89fe4b81-97a8-47a6-a363-1b2d63a5b74f.png)

+ Students dropping tend to have more number of warnings
![image](https://user-images.githubusercontent.com/81252980/144567347-8561daf1-64f8-4067-af7c-8eb8fbf757db.png)

+ Students who dropped tend to have lower GPA.
Blue: continuing students
Green: dropped students
![image](https://user-images.githubusercontent.com/81252980/144567505-ce279311-5163-4a57-b11c-94afc3e56668.png)

+ 20% of students who didn’t pay any of their fees dropped out of university where as only 3% of the students who fully paid the fees dropped
![image](https://user-images.githubusercontent.com/81252980/144567888-bd790b07-6e77-4a61-a6d7-e9aee3bde99c.png)


## Report
+ Standard Scaling

| Algorithm          | Accuracy| Precision | Recall |F1-score|AUC|
|--------------------|---|---|---|---|---|
| Decision Tree      |98.82|99.54|99.24|99.39|0.93|
| Logistic Regression |98.28|98.74|99.49|99.12|0.80|


+ Robust Scaling

| Algorithm          | Accuracy| Precision | Recall |F1-score|AUC|
|--------------------|---|---|---|---|---|
| Decision Tree      |98.82|99.54|99.24|99.39|0.93|
| Logistic Regression |98.30|98.73|99.52|99.12|0.80|


