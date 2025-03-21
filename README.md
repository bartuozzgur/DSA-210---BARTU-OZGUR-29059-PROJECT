# DSA-210---BARTU-OZGUR-29059-PROJECT
DSA 210 - BARTU OZGUR 29059 PROJECT


DSA TERM PROJECT

This project investigates the relationship between total sales of a local coffee shop and current weather conditions. By analyzing historical sales data and corresponding weather records, we aim to determine whether weather has a significant impact on daily revenue and customer traffic.

The following hypotheses will be tested: 

**H1:** There is a statistically significant correlation between total sales and specific weather conditions (e.g., temperature, precipitation, humidity).

**H2:** There is a statistically weak correlation between total sales and specific weather conditions.


**Contents**  

- Motivation 
- Research Questions
- Data Source
- Data Analysis
- Findings
- Methadology
- Limitations and Future Work


**Motivation** 

The coffee shop industry is highly sensitive to external factors, including location, competition, and seasonality. Weather conditions, in particular, play a crucial role in consumer behavior and purchasing decisions. Having worked in this sector, I have firsthand knowledge of how various factors impact sales. By integrating my practical experience with the analytical methods taught in DSA 210, I aim to provide actionable insights that can help coffee shop owners optimize their business strategies.

**Research Questions**

 1. Do specific weather conditions (e.g., rainy days, extremely hot days) impact customer footfall? 
2. How do different weather conditions affect sales of specific products (e.g., iced vs. hot beverages)? 
3. Can predictive models be used to forecast daily sales based on weather forecasts?

**Data Source** 

The dataset for this study will be obtained from a local coffee shop located in Kadıköy, Bağdat Caddesi. The coffee shop has been tracking its sales for the past nine months through a software program that logs order details, including product type and timestamp. Additionally, historical weather data (temperature, humidity, precipitation, wind speed, etc.) will be collected from an open-source weather database (e.g., OpenWeather API, Meteorological Institute records).

**Data Analysis** 

 1. Data Cleaning & Preparation 
Convert date and time columns into a proper datetime format. 
Handle missing values in both sales and weather data. 
Standardize numerical features (e.g., temperature in Celsius, sales in USD). 
- Encode categorical variables (e.g., "Rainy", "Sunny", "Cloudy" → numerical labels). 

2. Exploratory Data Analysis (EDA) 
Plot daily sales trends over the past 9 months to identify patterns.
 - Create a heatmap of correlations to see how weather factors (temperature, humidity, precipitation) affect sales.
 - Generate bar charts and boxplots to compare sales distributions under different weather conditions. 

3. Statistical Analysis
 - Calculate Pearson correlation coefficients between total sales and weather factors. 
Perform ANOVA tests to check if sales differences across weather conditions are statistically significant.
 - Run a linear regression model to quantify the effect of weather on sales. 

4. Machine Learning Model 
Train a Random Forest Regressor to predict daily sales based on weather features.
 - Evaluate model performance using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
   

**Findings**




<img width="801" alt="Screen Shot 2025-03-21 at 12 02 56" src="https://github.com/user-attachments/assets/f03bf5f3-8d71-4764-ad75-8ecc93810476" />







This graph provides a clear overview of weather trends in Kadıköy, Istanbul, between June 2024 and March 2025. It presents three key weather indicators: 

Average Temperature (°C) –  Blue Line: 
 - The temperature is highest in July and August (~24.5°C) and starts decreasing from September.  - The lowest temperatures are observed in January (~5.9°C)  and gradually rise again towards March. 

 Precipitation (mm) – Gray Bars: 
- Rainfall is relatively low during the summer months (**June to August**). - It increases significantly in October (~80mm) and reaches its peak in December (~107mm), indicating a wetter winter season. 

 Humidity (%) – Green Dashed Line: 
The humidity level remains relatively stable but increases slightly during winter months (December - February), aligning with increased precipitation. 

How to Read the Graph Efficiently?   
If you focus on the blue line, you can see how temperature changes over time. - The gray bars indicate the months with higher or lower precipitation, showing rainy periods. - The green dashed line helps understand how humidity correlates with seasonal changes.















This graph visualizes the total product sales recorded in a local coffee shop over monthly intervals from June 2024 to February 2025. The red line represents the total number of products sold each month, allowing us to observe trends and fluctuations in sales.

 Key Observations:
 
1. Steady Growth in Summer (June - September) - Sales increased from 13,128 in June-July to 15,400 in August-September, indicating higher demand during summer months. 

2. Fluctuations in Autumn (September - December) 
Sales slightly dropped after August-September but remained stable around 14,000 - 14,600 units from September to December. 
This could be due to seasonal changes affecting customer visits. 

3. Significant Increase in Winter (December - February)
The highest sales were recorded in January-February (17,200 units), showing a notable growth of 21% compared to the lowest recorded month (June-July). 
Possible factors include winter promotions, increased indoor coffee consumption, or holiday season effects. 

4. How to Interpret the Graph? 
X-Axis (Date Range): Shows monthly intervals from 07.06.2024 - 07.02.2025.
 - Y-Axis (Total Product Sales):  Displays the number of products sold during each month. 
Red Line with Markers: Helps track sales trends over time, making it easy to identify increases or decreases.

 5. Final Thoughts: This graph provides useful insights into seasonal sales trends, helping businesses anticipate demand and plan their stock or promotions accordingly.



**Methodology** 

Data Collection
 - Extract sales records from the coffee shop’s software system.
 - Retrieve weather data corresponding to the sales period from an external source. 

 Data Preprocessing
- Clean and organize the dataset (handling missing values, formatting timestamps, etc.). 
- Merge sales data with weather data based on matching dates and times. 

 Exploratory Data Analysis (EDA)
 - Visualize sales trends over time.
 - Identify seasonal patterns and potential weather-related sales fluctuations. 

 Statistical Analysis & Hypothesis Testing
 - Perform correlation analysis to measure the strength of the relationship between weather conditions and total sales. 
- Use regression models to evaluate the predictive power of weather variables. 

 Machine Learning Model (if applicable)
 - Train a predictive model (e.g., linear regression, random forest) to forecast daily sales based on weather conditions.






**Limitations and Future Work** 

-This study primarily focuses on total sales rather than specific product sales. Further analysis of specific product sales movements might be obtained by having more detailed dataset. 

 - Additional external factors such as promotions, competitor pricing, or events could be considered in future analyses.

