# TTC Ridership Analysis and Forecasting Project

## Project Objective
The main goal of this project was to analyze historical ridership data for the Toronto Transit Commission (TTC) and forecast future ridership trends. This analysis aimed to provide insights into usage patterns, identify key fare media types, and predict future ridership to support strategic planning and decision-making. The dataset used is from [here](https://open.toronto.ca/dataset/ttc-ridership-analysis/)

## Key Steps and Components
1. **Data Collection and Preparation**:
   - Collected historical ridership data from 1985 to 2019.
   - Cleaned and preprocessed the data to ensure accuracy and consistency.

2. **Exploratory Data Analysis (EDA)**:
   - Conducted EDA to identify usage patterns, trends, and anomalies in the ridership data.
   - Analyzed annual ridership trends and identified top fare media types.

3. **Visualization**:
   - Created visualizations to illustrate annual ridership trends and fare media usage.
   - Plotted ridership trends for top fare media types over the years.

4. **Predictive Modeling**:
   - Utilized the ARIMA (AutoRegressive Integrated Moving Average) model to forecast future ridership trends.
   - Evaluated the model's performance using Root Mean Squared Error (RMSE).
   - Generated a forecast for the next 10 years based on historical data.

## Tools and Techniques Used
1. **Python Libraries**:
   - **Pandas**: For data manipulation and analysis.
   - **Matplotlib**: For creating visualizations and plots.
   - **Statsmodels**: For time series analysis and forecasting using the ARIMA model.
   - **Scikit-learn**: For evaluating the performance of the predictive model.

2. **Data Cleaning and Preparation**:
   - Loaded data from an Excel file and cleaned it to remove irrelevant rows and columns.
   - Transformed and aggregated data for analysis.

3. **Exploratory Data Analysis**:
   - Performed descriptive statistics and visualizations to understand data distribution and trends.
   - Identified key metrics such as top fare media types and annual ridership patterns.

4. **Time Series Forecasting**:
   - Split the data into training and testing sets.
   - Trained an ARIMA model on the training set and validated it using the test set.
   - Forecasted future ridership trends and visualized the predictions.
