# ✈️ Flight Ticket Price Data Analytics Project

## 📌 Executive Summary

This project focuses on analyzing historical flight booking data to understand the key factors that influence airline ticket prices. The goal is not to build a prediction model but to perform a complete **data analytics and feature engineering pipeline** that transforms raw airline data into a structured, machine-learning-ready dataset.
The project explores how variables such as airline, source and destination cities, travel date, flight duration, departure time, arrival time, and number of stops impact ticket pricing. Through extensive exploratory data analysis (EDA), feature engineering, encoding techniques, and statistical analysis, this project identifies important pricing patterns and prepares meaningful features for future predictive modeling.
The final outcome is a clean and enriched dataset with engineered features, valuable business insights, and a foundation for developing a flight price prediction system.

## 📖 Project Overview

Airline ticket prices are influenced by multiple dynamic factors including airline brand, route popularity, travel season, flight duration, and departure schedules. Understanding these relationships is important for airlines, travel platforms, and customers to make data-driven pricing decisions.
This project analyzes airline booking data to uncover pricing trends and identify the variables that contribute most significantly to fare variations.
Instead of focusing only on prediction accuracy, this project emphasizes the **data analytics lifecycle**, including:

- Data understanding and cleaning
- Exploratory data analysis
- Feature creation
- Data transformation
- Encoding categorical variables
- Statistical feature evaluation
- Preparation for machine learning workflows

## 📂 Project Structure
```
├── Images/                                             # Visualizations generated during analysis
├── airline_ticket_data.xlsx                            # Dataset containing marketing information
├── flight_ticket_price_data_analytics_project.ipynb    # Jupyter Notebook with analysis and findings
├── README.md                                           # Project documentation
```

## 🎯 Project Objectives
The main objectives of this project are:

### 1. Understand Flight Pricing Patterns
- Analyze how airline, route, travel date, and flight characteristics influence ticket prices.
- Identify patterns in pricing behavior across different categories.

### 2. Perform Data Cleaning and Transformation
- Handle missing values.
- Convert raw date and time information into meaningful numerical features.
- Standardize data formats for analysis.

### 3. Create Meaningful Features
Generate additional features from existing variables:
- Journey day
- Journey month
- Departure hour
- Departure minute
- Arrival hour
- Arrival minute
- Flight duration in hours
- Number of stops
These engineered variables provide more analytical value compared to raw data.

### 4. Analyze Important Pricing Factors
Determine which features have the strongest relationship with ticket prices using statistical methods and visualization techniques.

### 5. Prepare Data for Machine Learning
Transform categorical variables into numerical formats and create a machine-learning-ready dataset for future predictive modeling.

**Data Visualization**
Here are some visualizations from the project:
    ![alt text](https://github.com/asna-amjad/Flight-Ticket-Price-Project-Data-Analytics/blob/704d2f24c51fcf887c9528485eea9c70ebbea911/Images/plot1.png)
    ![alt text](https://github.com/asna-amjad/Flight-Ticket-Price-Project-Data-Analytics/blob/704d2f24c51fcf887c9528485eea9c70ebbea911/Images/plot2.png)
    ![alt text](https://github.com/asna-amjad/Flight-Ticket-Price-Project-Data-Analytics/blob/704d2f24c51fcf887c9528485eea9c70ebbea911/Images/plot3.png)
    ![alt text](https://github.com/asna-amjad/Flight-Ticket-Price-Project-Data-Analytics/blob/704d2f24c51fcf887c9528485eea9c70ebbea911/Images/plot4.png)

## 🛠️ Methodology
The project follows a complete data analytics workflow:

## 1. Data Loading & Initial Exploration
- Imported airline booking dataset using Pandas.
- Examined:
  - Dataset structure
  - Data types
  - Missing values
  - Statistical summaries
  - Unique categories

## 2. Data Cleaning & Preprocessing
Performed data quality improvements:
- Identified and handled missing values.
- Converted date columns into proper datetime format.
- Removed inconsistencies in categorical values.
- Prepared numerical columns for analysis.

## 3. Feature Engineering
Created additional analytical features from existing data.
### Date Features:
- Journey Day
- Journey Month

### Time Features:
- Departure Hour
- Departure Minute
- Arrival Hour
- Arrival Minute

### Duration Features:
Converted flight duration into numerical hours for easier analysis.
Example: Flight Duration = 2 hours 45 minutes
Converted Value = 2.75 hours
These features allow deeper analysis of pricing behavior.

## 4. Exploratory Data Analysis (EDA)
Used visualization techniques to identify patterns and relationships.
Performed analysis on:
- Airline-wise ticket price distribution
- Route-based pricing differences
- Number of stops vs ticket prices
- Flight duration vs ticket prices

## 5. Feature Encoding
Machine learning algorithms require numerical inputs, therefore categorical variables were transformed.
Techniques applied:
### One-Hot Encoding
Used for categorical variables with fewer unique categories.
Examples:
- Airline
- Source city
- Destination city

### Target Guided Encoding
Used to capture the relationship between categorical variables and ticket prices.

## 6. Outlier Detection
Identified extreme values in ticket prices using the:
### Interquartile Range (IQR) Method
Steps:
- Calculate Q1 and Q3
- Determine IQR range
- Detect unusual ticket prices
- Evaluate their impact on analysis

## 7. Feature Selection
Used:
### Mutual Information Regression
to measure the relationship between input features and ticket prices.
This helped identify the most influential variables for future modeling.

## 🛠 Technologies Used

- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Jupyter Notebook**
- **Git & GitHub**

## 🔑 Key Features
✔ Cleaned and transformed raw airline booking data  
✔ Created meaningful date, time, and duration features  
✔ Performed detailed exploratory data analysis  
✔ Identified pricing trends across airlines and routes  
✔ Converted categorical data into machine-readable formats  
✔ Applied target-guided encoding techniques  
✔ Detected pricing outliers using statistical methods  
✔ Evaluated feature importance using Mutual Information  
✔ Generated a machine-learning-ready dataset  

# 📊 Key Insights
## ✈️ Flight Duration Impacts Pricing
Longer flights generally have higher ticket prices due to:
- Increased operational costs
- Longer travel distance
- Premium service availability

## 🏢 Airline Brand Influences Ticket Prices
Premium airlines typically show higher fare distributions compared to budget carriers because of:
- Better services
- Additional amenities
- Brand positioning

## 📅 Seasonal Trends Affect Prices
Ticket prices vary across different months due to:
- Holiday seasons
- Travel demand
- Peak vacation periods
Certain months show higher average fares compared to others.

## 🛫 Number of Stops Impacts Fare
Flights with fewer stops often have higher prices because passengers pay for:
- Convenience
- Reduced travel time
- Better travel experience

## ⏰ Departure Time Influences Ticket Prices
Flight schedules affect pricing because airlines adjust fares based on:
- Business travel demand
- Passenger preferences
- Availability

## 📈 Project Outcome
The project successfully converted raw flight booking data into a structured analytical dataset by applying:
- Data cleaning
- Feature engineering
- Exploratory data analysis
- Encoding techniques
- Statistical feature evaluation

## 🚀 Future Improvements
* Build a Machine Learning Prediction Model
* Add External Data Sources. Enhance predictions by incorporating:
  - Weather conditions
  - Fuel prices
  - Airport traffic volume
  - Holiday calendars
  - Economic indicators
* Create an Interactive Dashboard
  - Develop a business dashboard using: Tableau, Power BI or Plotly Dash
* Deploy a Price Prediction Application
