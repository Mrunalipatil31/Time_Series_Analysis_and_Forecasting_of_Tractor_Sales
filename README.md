# Time_Series_Analysis_and_Forecasting_of_Tractor_Sales

**Overview:**

PowerHorse, a tractor and farm eqipment manufacturing company, was established a few years after World War II. The company has shown a consistent growth in its revenue from tractor sales since its inceptio. However, over the years the company has struggled to keep it's inventory and production cost down because of variability in sales and tractor demand. The management are interested in understanding the impact of their marketing and farmaer connect efforts towards overall sales.

The dataset consists of 144 observations having the total monthwise sales data of Tractors for a past 12 years of period.

**Objective:**

An ARIMA model is developed to forecast sales of tractor for a next year for their production planning to maintain healthy business margins.
Monthly sales forecast is used towards effective inventory management.

**Project Methodology:**

The steps followed in the project are given below:

Step 1: Reading and Ploting tractor sales data as time series.

Step 2. Difference data to make data stationary on mean(remove trend).

Step 3. Log transform data to make data stationary on variance.

Step 4. Difference log transform data to make data stationary on both mean and variance.

Step 5. Plot ACF and PACF to identify potential AR and MA model.

Step 6. Identification of best fit ARIMA model.

Step 7. Forecast sales using the best fit ARIMA model.

Step 8: Plot ACF and PACF for residuals of ARIMA model to ensure no more information is left for extraction.

**Conclusion:**

Sales/Demand Forecast of Tractors for the Next 3 Years have been successfully done using Time Series ARIMA Model.
