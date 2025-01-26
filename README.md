# Bike-Sharing-Demand
Predicting bike-sharing demand for BoomBikes using statistical modeling. Analyzes factors influencing bike usage to optimize business strategy post-pandemic. #bikesharing #demandforecasting

## Table of Contents
In this notebook, we'll build a linear regression model to predict demand using an appropriate predictor variable for bikes

**The steps we will follow in this excercise are as follows**:

1. Reading, understanding and visualising the data
2. Preparing the data for modelling
3. Training the model
4. Residual analysis
5. Predictions and evaluation on the test set

## General Information
- **Brief Description**: This project develops a multiple linear regression model to predict bike-sharing demand for BoomBikes, considering weather, seasonality, and temporal trends.
- **Problem Statement/Motivation**: BoomBikes, a US-based bike-sharing company, experienced revenue decline due to the COVID-19 pandemic. This model aims to provide insights into post-pandemic demand drivers to optimize resource allocation and business strategy.
  
- **Key Features/Functionality**:
    - Predicts daily bike rentals.
    - Identifies key factors influencing bike-sharing demand.
    - Provides actionable insights for business planning.
      
- **Target Audience**: data analysts, business strategists, and anyone interested in bike-sharing demand modeling.

  ## Installation and Setup:

  - Prerequisites: Python 3.x, scikit-learn, pandas, numpy, statsmodel
 
  ## Conclusion

*   **Temperature (temp):** This has the largest positive coefficient (4991.00). This strongly suggests that higher temperatures are associated with significantly increased bike-sharing demand. People are more likely to cycle when the weather is warm.
*   **Year (yr):** The positive coefficient (1918.70) indicates a general upward trend in bike-sharing usage over time. This could be due to increased awareness, infrastructure improvements, or growing popularity of bike sharing.
*   **Seasonality:**
    *   **Winter:** Has a positive coefficient (1287.13), but it's important to consider this in relation to temperature. While winter might have some demand, it's likely that the "temp" variable captures the negative impact of cold weather more directly.
    *   **Summer:** Also has a positive coefficient (879.63), further supporting the idea that warmer weather boosts demand.
    *   **Months:** September (1112.69), August (431.82), and March (321.13) show varying degrees of positive influence, likely reflecting the transition seasons and milder weather in those months.
*   **Weather Conditions:**
    *   **Cloudy:** Has a negative coefficient (-393.39), suggesting that cloudy days may slightly reduce bike-sharing demand.
    *   **Windspeed:** Has a substantial negative coefficient (-1202.22). Strong winds likely deter people from cycling.
    *   **Humidity (hum):** Also has a negative coefficient (-1373.03), indicating that high humidity makes cycling less appealing.
    *   **Light snow/rain:** Has the largest negative coefficient (-1802.74). This clearly shows that precipitation strongly discourages bike sharing.

**Overall Conclusion for Bike Sharing Demand:**

Bike-sharing demand is heavily influenced by weather conditions, with temperature being the most significant factor. Demand is highest in warmer temperatures, particularly during summer and transition months like September and March. Adverse weather conditions such as strong winds, high humidity, and especially precipitation significantly reduce demand. Additionally, there's a general trend of increasing bike-sharing usage over the years.

**Practical Implications for Bike Sharing Operators:**

*   **Resource Allocation:** Operators should anticipate higher demand during warmer months and allocate resources (bikes, staff, maintenance) accordingly.
*   **Weather Monitoring:** Real-time weather monitoring is crucial for anticipating fluctuations in demand and adjusting operations.
*   **Promotional Strategies:** Targeted promotions could be used to incentivize usage during periods of lower demand (e.g., discounts on cloudy days or during winter).
*   **Infrastructure Planning:** Investments in infrastructure that provides some weather protection (e.g., covered bike stations) could help mitigate the negative impact of adverse weather.

## Contact
Created by [@nitishnarayanan002] - feel free to contact me!

