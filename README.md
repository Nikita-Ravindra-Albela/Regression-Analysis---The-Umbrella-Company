☂️ Regression Analysis – The Umbrella Company
Goal: To uncover how weather variables influence umbrella sales, and build predictive models to forecast demand based on rainfall, temperature, and wind speed.
-------------------------------------------------------------------------------------------------------------------------------
🧠 Problem Statement
The Umbrella Company wanted to optimize inventory forecasting by understanding how weather patterns—especially rainfall—affect umbrella sales across months. This project explores those relationships using Linear and Multiple Regression techniques.

📊 Data Overview
-------------------------------------------------------------------------------------------------------------------------------
Time Period: Feb 2023 – Feb 2024

Data Points: 19 monthly records

Features:

Rainfall (mm)

Temperature (°C)

Wind Speed (km/h)

Quantity Sold (umbrella units)

----------------------------------------------------------------------------------------------------------------------------
🔎 Methodology
1️⃣ Simple Linear Regression
Objective: Model the relationship between Rainfall and Quantity Sold.

Key Output:

R² = 0.82 → Rainfall alone explains 82% of the variation in sales.

Regression Equation:

Sales

=
−
630.33
+
47.14
×
Rainfall (mm)
Highly significant predictor (p-value < 0.001)



🎯 Takeaway: Umbrella sales rise by ~47 units for every additional mm of rainfall.
----------------------------------------------------------------------------------------------------------------------------
2️⃣ Multiple Linear Regression
Objective: Examine how Rainfall, Temperature, and Wind Speed collectively impact sales.

Key Output:

Adjusted R² = 0.88 → Stronger model with multiple features.

Significant Predictors:

Rainfall (p < 0.001) → Strong positive impact

Temperature (p < 0.05) → Positive contributor

Wind Speed → Not statistically significant (p > 0.6)

Regression Equation:

Sales

=
−
2971.68

+
58.40
×
Rainfall
+
55.76
×
Temp
+
32.89
×
Wind


🎯 Takeaway: Rainfall and temperature are the primary drivers of umbrella demand. Wind speed shows minimal influence.
----------------------------------------------------------------------------------------------------------------------------
📈 Business Impact
Inventory Optimization: Focus stocking around months with expected high rainfall and cooler temperatures.

Marketing: Target campaigns during specific climate conditions to boost conversions.

Forecasting: Model can predict future sales given weather forecasts.

----------------------------------------------------------------------------------------------------------------------------
🛠️ Tools Used
Microsoft Excel for data cleaning and regression modeling

Statistical Techniques:

Linear Regression

Multiple Linear Regression

ANOVA

Coefficient Interpretation

Significance Testing

---------------------------------------------------------------------------------------------------------------------------
✅ Key Skills Demonstrated
Data wrangling and transformation

Statistical storytelling

Model interpretation and business translation

Analytical thinking and presentation

---------------------------------------------------------------------------------------------------------------------------
