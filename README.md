# Task2_Trend_Analysis_and_Visualization
Happie Loop Technologies

**Task 2 – Trend Analysis and Visualization using Amazon Sales Dataset**
**Project Overview**

This project focuses on performing trend analysis and visualization on the Amazon Sales dataset using Python. The main purpose of this task is to analyze how sales-related values change over time and identify meaningful patterns, trends, and seasonal behavior within the dataset.

Trend analysis is an important part of data analytics because it helps in understanding growth patterns, fluctuations, and long-term behavior of data over a period of time.

**Objectives of the Project**

The primary objectives of this project are:

To load and analyze time-series data
To visualize trends over time using line charts
To calculate moving averages for smoother trend analysis
To identify patterns, seasonality, and fluctuations
To perform seasonal decomposition
To highlight important insights using annotations and visualizations
Tools and Technologies Used
Tool / Library	Purpose
Python	Programming Language
Pandas	Data Analysis and Manipulation
NumPy	Numerical Operations
Matplotlib	Data Visualization
Seaborn	Statistical Visualization
Statsmodels	Seasonal Decomposition
**Dataset Description**

The dataset used in this project is the Amazon Sales dataset stored in CSV format. The dataset contains sales-related information along with date-based records which are useful for time-series analysis.

The date column was converted into datetime format to perform trend-based operations and visualizations.

**Steps Performed in the Project**
1. Importing Required Libraries

All necessary Python libraries were imported for handling time-series analysis and visualizations.

2. Loading the Dataset

The dataset was loaded using pandas and the date column was converted into datetime format for proper trend analysis.

3. Data Cleaning

Basic preprocessing steps were performed including:

Removing duplicate records
Handling missing values
Formatting date columns properly

These steps ensured accurate trend analysis.

4. Time-Series Visualization

A line chart was created to visualize how sales values changed over time. This helped in identifying:

Increasing trends
Decreasing trends
Sudden fluctuations
Overall sales movement
5. Moving Average Calculation

A moving average was calculated to smooth out short-term fluctuations and better observe long-term trends in the dataset.

This helped in understanding the actual direction of the data without noise.

6. Seasonal Decomposition

Seasonal decomposition was applied to break the time-series data into:

Trend Component
Seasonal Component
Residual Component

This analysis helped in identifying repeating seasonal patterns and irregular fluctuations.

7. Data Visualization

Different visualizations were generated including:

Line Plot

Used to visualize trends over time.

Moving Average Plot

Used to smooth fluctuations and identify long-term behavior.

Seasonal Decomposition Plot

Used to identify trend, seasonality, and residual patterns.

All visualizations were saved inside the images folder.

**Key Observations**
The dataset showed noticeable fluctuations over time.
Moving averages helped in identifying smoother long-term trends.
Seasonal decomposition revealed repeating patterns in the dataset.
Some periods showed higher activity compared to others.
Trend analysis provided better understanding of sales behavior over time.
**Challenges Faced**

During the project, a few issues were encountered such as:

Converting date columns into datetime format
Handling missing values in time-series data
Managing visualization formatting
Saving output images correctly

These issues were resolved using proper preprocessing and Python functions.

**Conclusion**
This project successfully demonstrated trend analysis and time-series visualization using Python. The analysis helped in understanding sales patterns, seasonal behavior, and fluctuations within the Amazon Sales dataset.

The project also improved practical knowledge of time-series analysis, moving averages, and visualization techniques which are highly valuable in real-world data analytics projects.

**Project Structure**

Task2_Trend_Analysis/

│

├── amazon_sales_data_2025.csv

├── trend_analysis.py

├── README.md

│

└── images/



**Output Generated**

The project generated:

Time-series trend visualizations
Moving average analysis
Seasonal decomposition graphs
Trend insights and observations

These outputs helped in understanding how the data changes over time.

**Output Images**
<img width="1200" height="500" alt="moving_average" src="https://github.com/user-attachments/assets/a577c827-0e19-4010-af9f-e67fe4471fb0" />
<img width="1000" height="500" alt="monthly_sales_trend" src="https://github.com/user-attachments/assets/9b9b6ba7-00e2-4587-8bed-e0158b07eb39" />
<img width="1200" height="500" alt="line_plot" src="https://github.com/user-attachments/assets/f7e87a56-0b10-4ff3-ae9d-b5fcfdb90327" />


**Learning Outcomes**

Through this project, the following skills were improved:

Time-series analysis
Trend visualization
Moving average calculation
Seasonal decomposition
Data preprocessing
Analytical reporting

**Final Result**

The trend analysis and visualization task was completed successfully using Python libraries such as pandas, matplotlib, seaborn, and statsmodels. The project provided meaningful insights into the time-based behavior of the Amazon Sales dataset.
