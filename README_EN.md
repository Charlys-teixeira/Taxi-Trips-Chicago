## 📌 Project

This project is an exploratory data analysis (EDA) and hypothesis testing applied to Chicago taxi ride data. The goal is to understand travel patterns, identify the busiest neighborhoods, and test whether external factors (such as weather) affect ride duration.

## 📂 Data

Three CSV datasets were used:

- `project_sql_result_01.csv` – number of rides per taxi company (Nov 15–16, 2017)  
- `project_sql_result_04.csv` – destination neighborhoods and average rides in November 2017  
- `project_sql_result_07.csv` – rides from the Loop to O'Hare International Airport, including datetime, weather conditions, and ride duration  

## 🛠 Methodology

**Step 4 – Exploratory Data Analysis (EDA):**

- Data import and inspection (pandas)  
- Data type verification and correction  
- Identification of the top 10 neighborhoods by ride count  
- Graph creation:
  - Number of rides per taxi company  
  - Top 10 neighborhoods by ride count  
- Interpretation and conclusions based on the graphs  

**Step 5 – Hypothesis Testing:**

- Tested hypothesis:  
  "The average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays."  
- Steps:
  - Formulate null hypothesis (H₀) and alternative (H₁)  
  - Define significance level (α = 0.05)  
  - Select the appropriate statistical test (t-test or Mann-Whitney depending on distribution)  
  - Analyze the p-value and decide on H₀  
  - Interpret the results  

## 📊 Key Results

- Most active taxi companies had higher ride volumes during the period analyzed  
- The top 10 neighborhoods showed geographic concentration of destinations  
- Hypothesis testing indicated that weather conditions affect the average ride duration on Saturdays, providing valuable insights for logistics planning and demand forecasting  

## 🛠 Technologies Used

- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- SciPy / Statsmodels  

## 💡 Conclusion

The project demonstrates skills in:  

- Data manipulation and analysis in Python  
- Visualization and interpretation of insights  
- Hypothesis testing and applied statistics  
- Clear communication of results  
