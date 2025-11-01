# ELECTRIC-VEHICLE-SALES-ADOPTION-PREDICTION-ML-PROJECT-
A Machine Learning project that analyzes global Electric Vehicle (EV) sales and adoption trends, predicts future EV sales, and classifies countries based on adoption levels using real-world data and predictive modeling.

# Project Overview
This project analyzes and predicts Electric Vehicle (EV) sales and adoption patterns using Machine Learning and Data Analytics.

It combines:
1. Exploratory Data Analysis (EDA) to visualize EV trends
2. Regression Models to forecast future EV sales
3. Classification Models to categorize countries by EV adoption levels
 
# Objectives
Study the global growth of EVs using historical data
1. Forecast future EV sales using ML regression models
2. Classify countries as High, Medium, or Low EV adopters
3. Identify major factors influencing EV adoption

# Dataset
Source:https://www.kaggle.com/datasets/rameezmeerasahib/electric-vehicle-ev-sales-and-adoption/data 

KEY COLUMNS 
| Column            | Description                         |
| ----------------- | ----------------------------------- |
| Year              | Year of record                      |
| Country           | Name of country                     |
| EV_Sales          | Number of EVs sold                  |
| Market_Share      | EV share of total vehicles          |
| Charging_Stations | Available EV charging points        |
| GDP               | Economic indicator (per capita GDP) |
| Vehicle_Type      | BEV/PHEV/Hybrid                     |
| Population        | Population of region                |

TECH STACK 
| Category         | Tools/Libraries                 |
| ---------------- | ------------------------------- |
| Language         | Python                          |
| IDE              | Jupyter Notebook / Google Colab |
| Data Analysis    | pandas, numpy                   |
| Visualization    | matplotlib, seaborn, plotly     |
| Machine Learning | scikit-learn, xgboost           |
| Version Control  | Git & GitHub                    |

ML MODEL USED 
| Task                | Model Type     | Algorithms                                        |
| ------------------- | -------------- | ------------------------------------------------- |
| EV Sales Prediction | Regression     | Linear Regression, Random Forest, XGBoost         |
| EV Adoption Level   | Classification | Logistic Regression, Decision Tree, Random Forest |

# Results & Insights
 1. EV Sales Trend
    EV sales increased exponentially between 2015–2023
    Top growth countries: China, Norway, USA, Germany

 2. EV Sales Prediction
    Forecasted EV sales for 2025 show ~40% increase globally
    Random Forest Regressor performed best (R² = 0.91)

 3. Adoption Classification
    Countries categorized as:
      High Adoption: Norway, China, Netherlands
      Medium Adoption: USA, UK, Germany
      Low Adoption: India, Brazil, South Africa

 4. Key Factors
    EV sales strongly correlated with:
    GDP per capita
    Number of charging stations
    Market share percentage

# WORK FLOW DIAGRAM
flowchart TD
A[Dataset: EV Sales & Adoption Data] --> B[Data Preprocessing & Cleaning]
B --> C[Exploratory Data Analysis]
C --> D[Regression Model - Predict EV Sales]
C --> E[Classification Model - Adoption Level]
D --> F[Visualization of Predictions]
E --> F
F --> G[Insights & Future Forecasts]
