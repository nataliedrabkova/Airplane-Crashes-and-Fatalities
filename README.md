## Historical Analysis and Econometric Modeling of Global Aviation Accidents (1908–2009)

###  Project Overview
This project focuses on a comprehensive empirical analysis of historical aviation accidents dating back to 1908. The main objective is to process and clean raw historical data, identify long-term temporal trends, determine high-risk aircraft operators, and deploy an Ordinary Least Squares (OLS) regression model to statistically evaluate the relationship between the number of individuals aboard and the total fatalities.

### Project Structure
The analysis is divided into the following key phases:
1. **Data Preprocessing:** Handling missing values, converting temporal formats, and feature engineering (extracting Year, Month, and calculating Fatality Rate).
2. **Exploratory Data Analysis (EDA):** Visualizing the distribution of accidents across years and months, and profiling operator risk.
3. **Econometric Modeling:** Computing a Pearson correlation matrix and fitting an Ordinary Least Squares (OLS) regression model to explain the variance in fatalities.

### Key Findings
* **Most Frequent Operators:** Historically, the highest number of accidents were recorded by Aeroflot (179) and the Military - U.S. Air Force (174).
* **Seasonality:** The highest frequency of incidents occurred in December (513) and January (494), potentially indicating the impact of adverse winter weather conditions.
* **Fatality Rate:** The average fatality rate across all accidents in this dataset is remarkably high at 83.4%. The median rate is 1.0, meaning that in over half of the recorded crashes, there were no survivors.
* **OLS Regression:** The model demonstrated a strong positive correlation (r = 0.757) between the number of people aboard and the total fatalities (R-squared = 0.6800).

### Tech Stack
* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Statistics & Econometrics:** `statsmodels`

**Author:** Natalie Drábková
<img width="700" height="487" alt="image" src="https://github.com/user-attachments/assets/aa554f10-c11a-4ac6-ba33-5d92524493dd" />


