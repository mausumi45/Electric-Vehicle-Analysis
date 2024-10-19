# Electric-Vehicle-Analysis
This repository contains an Exploratory Data Analysis (EDA) of Electric Vehicles (EV), which is a part of the Data Science with Gen AI internship. The analysis leverages various data visualization techniques and libraries such as Plotly Express, Matplotlib, Seaborn, and Bar Chart Race for interactive and informative insights into electric vehicle data.

## Project Overview
The project aims to explore the electric vehicle dataset and uncover key insights into the trends and characteristics of EV adoption, electric ranges, manufacturer contributions, and regional distributions. The notebook walks through different steps of EDA, from loading the dataset to generating various plots and animations.

## Libraries Used:
numpy
pandas
matplotlib
seaborn
plotly.express
bar_chart_race
## Main Analysis Performed:
Dataset overview: Checking the size, shape, and structure of the data.
Data types and column information.
Statistical summaries and data cleaning (if applicable).
Visualizations:
Stacked bar charts to analyze electric vehicle types across different regions.
Animated bar race charts to showcase trends over time.
Scatter plots to examine relationships between variables like electric range, model year, and base MSRP.
## Dataset
The dataset (dataset.csv) contains various attributes related to electric vehicles, such as:

Vehicle Identification Number (VIN)object              int64
County                                                object
City                                                  object
State                                                 object
Postal Code                                            int64
Model Year                                             int64
Make                                                  object
Model                                                 object
Electric Vehicle Type                                 object
Clean Alternative Fuel Vehicle (CAFV) Eligibility     object
Electric Range                                         int64
Base MSRP                                              int64
Legislative District                                 float64
DOL Vehicle ID                                         int64
Vehicle Location                                      object
Electric Utility                                      object
2020 Census Tract                                      int64

## Visualizations
This notebook generates various interactive visualizations using Plotly Express and other tools:

Stacked bar charts to show vehicle type distribution by region.
Animated bar race to visualize the growth of different EV makes over time.
Scatter plots to compare electric range and MSRP for different EV models.
Conclusion
This EDA provides valuable insights into the electric vehicle market, highlighting trends over time, vehicle characteristics, and regional patterns. The visualizations help in understanding the current state and potential growth areas of electric vehicle adoption.
