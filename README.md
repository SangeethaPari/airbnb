# Airbnb Dynamic Pricing Recommendation Engine

## Project Overview

This project analyzes the Airbnb New York City 2019 dataset to identify the key factors that influence listing prices and to build a machine learning model for price prediction. The project also includes an interactive Tableau dashboard for visualizing pricing trends across neighbourhoods, room types, reviews, and availability.

---

## Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Identify factors affecting Airbnb prices
- Build regression models for price prediction
- Evaluate model performance
- Create an interactive Tableau dashboard
- Generate actionable pricing insights

---

## Dataset

**Dataset:** AB_NYC_2019.csv

The dataset contains Airbnb listings in New York City with information such as:

- Neighbourhood Group
- Neighbourhood
- Room Type
- Price
- Minimum Nights
- Number of Reviews
- Reviews per Month
- Availability (365 days)
- Host Information
- Latitude & Longitude

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Tableau Public
- GitHub

---

## Project Workflow

### 1. Data Collection

- Imported Airbnb NYC 2019 dataset

### 2. Data Cleaning

- Removed duplicate records
- Handled missing values
- Removed price outliers
- Converted data types

### 3. Exploratory Data Analysis

- Price Distribution
- Room Type Distribution
- Average Price by Neighbourhood Group
- Average Price by Room Type
- Reviews vs Price
- Availability vs Price
- Correlation Heatmap
- Top 10 Expensive Neighbourhoods

### 4. Machine Learning

Regression Models Used:

- Linear Regression
- Random Forest Regressor

Evaluation Metrics:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 5. Dashboard

An interactive Tableau dashboard was created to visualize:

- Average Price by Neighbourhood Group
- Room Type Distribution
- Average Price by Room Type
- Reviews vs Price
- Availability vs Price
- Top 10 Expensive Neighbourhoods

Interactive Filters:

- Neighbourhood Group
- Room Type
- Minimum Nights

---

## Key Insights

- Manhattan has the highest average Airbnb prices.
- Entire homes/apartments are generally more expensive than private and shared rooms.
- Room type and neighbourhood significantly influence listing prices.
- Reviews and availability also contribute to pricing decisions.

---

## Project Structure

```
Airbnb-Dynamic-Pricing/
│
├── AB_NYC_2019.csv
├── cleaned_airbnb.csv
├── Airbnb_Price_Prediction.ipynb
├── Tableau_Dashboard.twbx
├── Project_Report.pdf
└── README.md
```

---

## Results

- Successfully cleaned and analyzed the Airbnb dataset.
- Built regression models for predicting listing prices.
- Developed an interactive Tableau dashboard for business insights.
- Generated recommendations to support data-driven pricing strategies.

---

## Future Improvements

- Include seasonal demand analysis.
- Use advanced models such as XGBoost.
- Deploy the pricing model as a web application.
- Integrate real-time Airbnb listing data.

---

