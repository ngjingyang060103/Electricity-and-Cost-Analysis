# Electricity-and-Cost-Analysis
##Electricity and Cost Analysis This project analyzes , visualise and build a predictive model to forecast electricity costs based on usage and occupancy by using python

##Dataset Description The dataset includes household electricity consumption, cost, and number of occupants across three regions for Urban, Suburaban, and Rural .Each record contains monthly readings from 2018 to 2022.

##Tools used -Python -Pandas -Matpolib -Scikit-learn -Google Colab

##How to run 1.Open the Google Colab link below \n 2.Run all cells from top to bottom

##Google Colab Link https://colab.research.google.com/drive/1G0MWy0NK-plytsClqwQuVAmUGfu96PP4?usp=sharing

##Result

Data Cleaning and Preprocessing The dataset underwent a rigorous cleaning process to ensure the accuracy of the predictive model. Missing Values: Missing entries in Consumption_kWh were addressed using interpolation to maintain the continuity of the time-series data. Outlier Management: Outliers were identified using the Interquartile Range (IQR) method. Data points falling below the lower bound or above the upper bound were replaced with the median value to prevent skewed analysis.

Descriptive Analysis The analysis of electricity patterns across Urban, Suburban, and Rural regions revealed key insights. Regional Trends: Summary statistics (mean and standard deviation) were calculated to compare how geographic location impacts average monthly costs and usage. Occupancy Correlation: A correlation analysis between Occupants and Consumption_kWh was performed. A positive correlation generally indicates that as the number of people in a household increases, electricity consumption rises accordingly.

Data Visualisation Visual representations provided a clear view of the household data. Monthly Trends: Multi-line plots for each region highlighted seasonal consumption patterns from 2018 to 2022. Consumption Drivers: Scatter plots confirmed the relationship between household size and usage, identifying specific "spikes" or irregular patterns in the data.

Predictive Model Performance A Linear Regression model was developed to forecast Cost_RM based on Consumption_kWh and Occupants. Accuracy: The model was evaluated using an 80/20 train-test split. Metrics: Performance was measured via R-squared (R²) and Mean Absolute Error (MAE). Visual Validation: The "Actual vs. Predicted" plot showed data points closely following the y=x line, indicating high predictive reliability, though some variance was noted in "under-predicted" or "over-predicted" values.

##Conclusion This analysis successfully demonstrated that household electricity consumption is driven by both regional location and the number of occupants. By implementing a Python-based predictive model, we established a reliable method for forecasting electricity costs. These findings provide valuable insights into household energy trends from 2018 to 2022 and underscore the importance of data cleaning in building accurate predictive systems.

