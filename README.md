# Industrial Copper Modeling

## Introduction

This project focuses on modelling industrial copper data using Python and various libraries such as pandas, numpy, scikit-learn. The objective of the project is to preprocess the data, handle missing values, detect outliers, and handle skewness. Additionally, regression and classification models will be built to predict the selling price and determine if a sale was won or lost. The trained models will be saved as a pickle file for later use in a Streamlit application.

## Table of Contents

    Key Technologies
    Installation
    Usage
    Workflow

## Key Technologies

  • Python scripting 
  • Pandas  
  • Numpy  
  • Streamlit 
  • Scikit-learn 
  • Seaborn 
  • Matplotlib
  • Data Preprocessing
  • Exploratory Data Analysis

## Installation

To run this project, you will need to install the following packages:

  pip install streamlit 
  pip install numpy 
  pip install scikit-learn 
  pip install pandas 
  pip install seaborn
  pip install matplotlib

## Usage

To use this project, kindly follow the following steps:

1.	Clone the repository: git clone https://github.com/Theressac/Industrial-Copper-Modeling
2.	Install the required packages
3.	Run the Streamlit app: streamlit run app.py
4.	Access the app in your browser at http://localhost:8501

## Workflow

Data Cleaning and Preprocessing:
  Gain a deep understanding of the provided dataset variables and types
  Handle the missing values with appropriate strategies
  Prepare categorical features through encoding and data type conversion
  Address skewness and ensure data balance
  Identify and manage outliers
  Resolve date discrepancies for data integrity

Exploratory Data Analysis(EDA):
  Visualize and correct skewness           
  Identify and rectify outliers
  Feature improvement and creation for more effective modeling

Classification:
    Success and Failure Classification: Focusing on 'Won' and 'Lost' status
    Algorithm Assessment: Evaluating algorithms for classification
    Algorithm Selection: Opting for the Random Forest Classifier

Regression:
    Algorithm Assessment: Identifying algorithms for regression
    Algorithm Selection: Opting for the Extra Tree Regressor

## Author

@Theressac
