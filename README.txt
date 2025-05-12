# 🧾 Food Waste Analysis Project

## 👤 Name
**Touseef Ahmed**

## 📌 Objective
The goal of this project is to analyze food service data to understand patterns in food waste generation and identify actionable insights to optimize staffing, event planning, and waste management.

---

## 📁 Dataset Overview

The dataset includes:
- `meals_served`: Number of meals served per day
- `kitchen_staff`: Number of kitchen staff working
- `temperature_C`: Daily temperature in Celsius
- `humidity_percent`: Daily humidity percentage
- `special_event`: Binary flag for special events
- `past_waste_kg`: Amount of food waste in kilograms
- `staff_experience`: Experience level of the staff
- `waste_category`: Type of food waste (e.g., dairy, meat)
- `date`, `day_of_week`, `ID`: Additional identifiers and time features

---

## 🧹 Data Cleaning
- Converted `date` to datetime format
- Standardized text in `waste_category`
- Imputed missing numeric values using **median**
- Imputed categorical missing values using **mode** or **fixed values** (e.g., `'Beginner'`)
- Removed or verified duplicates

---

## 📊 Exploratory Data Analysis (EDA)
- Histograms and boxplots were used to detect outliers
- Correlation matrix helped explore relationships
- Scatter plots showed relationships between meals served and waste
- Count plots for `staff_experience` and `waste_category` provided categorical distribution insights

---

## 📈 Hypothesis Testing
- **ANOVA** was used to test the effect of kitchen staff levels on food waste
- **T-Test** compared waste on special event days vs. regular days
- Results indicated statistically significant differences in both cases

---

## 💡 Key Insights
- Higher staff levels are linked to increased waste
- Special events lead to more food waste
- Environmental factors (temperature, humidity) may also play a role

---

## ✅ Recommendations
- Optimize staffing schedules based on expected meal demand
- Improve planning for special events to reduce waste
- Monitor temperature/humidity to adjust food storage/prep

---

## 📦 Files Included
- `Food_Waste_Analysis_Report_Touseef_Ahmed.pdf`: Summary report
- `Detailed_Food_Waste_Analysis_Report_Touseef_Ahmed.pdf`: Full analysis report
- `Food data.csv`: The dataset used
- `eda_notebook.ipynb`: (Optional) Python notebook with full code

---

## 🛠 Technologies Used
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- SciPy for hypothesis testing


---

## 📬 Contact
For questions or collaboration:  
**Touseef Ahmed**  
📧 [Touseefahmed00710@gmail.com]  
