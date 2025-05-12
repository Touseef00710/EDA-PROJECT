🧾 Food Waste Analysis Project
👤 Name

Touseef Ahmed

📌 Objective

This project aims to study food service data to find patterns in food waste. It seeks to uncover practical ways to improve staffing, plan events, and handle waste better.

📁 Dataset Overview

The data includes:

meals_served: Number of meals served each day
kitchen_staff: Staff working in the kitchen
temperature_C: Daily temperature in Celsius
humidity_percent: Humidity level each day
special_event: Yes or no indicator for special events
past_waste_kg: Food waste in kilograms
staff_experience: Experience level of staff members
waste_category: Type of waste, like dairy or meat
date, day_of_week, ID: Extra info about time and IDs
🧹 Data Cleaning
Changed date into a date format
Made sure waste_category text was consistent
Filled missing numbers with median values
Filled missing categories with mode or set values like 'Beginner'
Removed or checked duplicate records Exploratory Data Analysis (EDA)
Used histograms and boxplots to find outliers
Created a correlation matrix to see relationships
Used scatter plots to compare meals served and waste
Count plots showed how staff experience and waste types are spread out

Hypothesis Testing ANOVA checked if more staff caused more waste T-Test compared waste on special event days versus regular days Both tests showed clear differences.

Key Insights

More staff often means more waste
Special events tend to produce more waste
Weather factors like temperature and humidity may affect waste

Files Included

Food_Waste_Analysis_Report_Touseef_Ahmed.pdf
Food data.csv: the dataset used
Cleaned data Set.csv
eda_notebook.ipynb: optional Python code file

Technologies Used

Python with Pandas, NumPy, Seaborn, Matplotlib
SciPy for tests

Contact For questions or teamwork:
Touseef Ahmed
📧 Touseefahmed00710@gmail.com
