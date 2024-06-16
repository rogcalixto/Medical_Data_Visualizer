# Medical Data Visualizer
This project involves analyzing and visualizing medical examination data to identify patterns and correlations. The visualizations include categorical plots and a heatmap to better understand the relationships between various health indicators and cardiovascular disease.

## Tasks
1. Create a Chart of Good and Bad Outcomes
Generate a chart showing the counts of good and bad outcomes for the cholesterol, gluc, alco, active, and smoke variables for patients with cardio=1 and cardio=0 in different panels.

2. Data Processing and Visualization in medical_data_visualizer.py
   
  Add Overweight Column: Calculate BMI and determine if a person is overweight. Use 0 for NOT overweight and 1 for overweight.
  
  Normalize Data: Convert data such that 0 is always good and 1 is always bad for cholesterol and gluc.
  
  Categorical Plot: Convert data into long format and create a chart using seaborn's catplot(). Split the dataset by cardio to create one chart for each cardio value.
  
  Clean Data: Filter out incorrect data where:Diastolic pressure is higher than systolic. Height is less than the 2.5th percentile or more than the 97.5th percentile. Weight is less than the 2.5th percentile or more than the 97.5th percentile.
  
  Correlation Matrix: Create and plot a correlation matrix using seaborn's heatmap().
