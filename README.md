# **Data Analysis and Machine Learning Portfolio Project Starbucks Worldwide Locations**

## **Objective**:
The purpose of this project is to create a prediction model that can accurately forecast the number of Starbucks locations in a country by using factors such as GDP per capita, population, and ease of conducting business.

## **Criteria for Success**:
To be considered a success, the model's predictions must have an R-Squared value of at least 0.7.

## **Getting Started**

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### **Prerequisites**

* Programming Language:
    * Python
* Tools:
    * Jupyter Notebook
* Libraries
    * Pandas
    * Numpy
    * Scikit-learn
    * LighGBM
    * CatBoost
    * XGBoost

### **Installing**
Clone repository:

```
git clone https://github.com/HalisManaz/Data-Analysis-and-Machine-Learning-Portfolio-Project-Starbucks-Worldwide-Locations.git
```
Create virtual environment:
```
python -m venv venv
```
Activate virtual enviroment:

Windows:
```cmd
venv\Scripts\activate.bat
```
Linux or macOS:
```cmd
source venv/bin/activate
```

Install requirements:
```
pip install -r requirements.txt
```

### **Data**

Two datasets from Kaggle were employed to determine the number of Starbucks in different countries. One dataset was from 2016 and the other from 2021. Additionally, information from the World Bank on GDP and population in various countries was included using the wbgapi library. These datasets were:

[Starbucks Locations Worldwide 2016](https://www.kaggle.com/datasets/starbucks/store-locations)

[Starbucks Locations Worldwide 2021](https://www.kaggle.com/datasets/kukuroo3/starbucks-locations-worldwide-2021-version)

**Note**: The 2021 Starbucks dataset was only used in the data analysis part of the project, with some assumptions made. The machine learning model was constructed using the 2016 Starbucks dataset and the World Bank data.


### **Model Evaluation**

The model was evaluated using a number of metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE) and R-squared values. The results of the evaluation are summarized in the table provided.

### **Deployment**

Deployment part will be uploaded soon using Streamlit library

## **Note**

This work is a portfolio project and is used for educational purposes only.

## **License**

This project is licensed under the MIT License
