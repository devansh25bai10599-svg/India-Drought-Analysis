India Drought Analysis (2000–2023)



📌 Project Overview

This project analyzes drought patterns in India from 2000 to 2023 using three major datasets:

GRACE Groundwater Anomaly Data (2003–2017)

GLDAS Soil Moisture Data (2018–2023)

ICRISAT Agricultural District-Level Data


Using Python, the project performs:

Data loading & preprocessing

Statistical analysis

Regional & seasonal drought pattern detection

Visualizations of groundwater, soil moisture & crop conditions.📂 Dataset Details

1. GRACE Groundwater Data

Years: 2003–2008, 2009–2017

Columns include:

date

region

district

lwe_thickness (Liquid Water Equivalent)




Agricultural Data (ICRISAT)

District-level agriculture metrics

Includes crop area, rainfall, production values, etc.Technologies Used

Tool / Library	Purpose

Python 3.x	Programming
Pandas	Data loading & cleaning
NumPy	Numerical operations
Matplotlib	Data visualization
Seaborn	Enhanced plotting
Kaggle	Dataset environmentCode Summary

1. Importing Libraries

Loads pandas, numpy, matplotlib, seaborn for data handling & visualization.

2. Loading Datasets

Reads:

GRACE 2003–2008

GRACE 2009–2017

GLDAS 2018–2023

Agricultural (ICRISAT)


3. Combining Data

GRACE datasets are merged using pd.concat().Preprocessing

Converted date column to datetime

Extracted year and month

Checked missing values

Displayed summary statistics


Visualization

Generated:

✔ Groundwater anomaly trends by region
✔ Soil moisture variation by region
✔ District-wise groundwater anomaly bar chart
✔ Monthly/seasonal groundwater cycle plot.Insights

Several regions show declining groundwater after 2010

Soil moisture dropped significantly around 2019–2020

Districts with negative anomalies are water-stressed

Seasonal cycle shows groundwater recharge during monsoon months.Outputs & Plots

The project generates multiple visualizations:

Time-series plots of groundwater & soil moisture

Regional comparison graphs

District-level drought intensity bars

Seasonal groundwater cycle
How to Run the Project

Step 1: Install Requirements

pip install pandas numpy matplotlib seaborn

Step 2: Place datasets in the correct folder

Inside /data directory or update the paths in the code.

Step 3: Run the Python script or Jupyter Notebook

python drought_analysis.py

Or open the .ipynb file in Jupyter/Kaggle.Future Improvements

Add rainfall & temperature datasets

Use machine learning for drought prediction

Build an interactive dashboard

Automate regional drought classification

Incorporate long-term climate modelsReferences

NASA GRACE Mission

NASA GLDAS Hydrological Data

ICRISAT Agriculture Dataset

India Drought Analysis Dataset (Kaggle)

Pandas, Matplotlib, Seaborn Documentation
