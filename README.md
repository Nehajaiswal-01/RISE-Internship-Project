# 🦠 COVID-19 Global Data Analysis Project

This project performs an exploratory analysis of the global COVID-19 pandemic using Python and Pandas. It covers data cleaning, trend identification, and visualizations to better understand the impact and timeline of the virus across the world.

---

## 📁 Dataset

- **Name:** `covid_19_clean_complete.csv`
- **Source:** Kaggle (or provided as part of internship resources)
- **Columns:** `Province/State`, `Country/Region`, `Date`, `Confirmed`, `Deaths`, `Recovered`, etc.
- **Coverage:** Daily global data from 2020 to 2021+

---

## 🔧 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Project Structure

| Section | Description |
|--------|-------------|
| 🔹 **1. Data Loading** | Import CSV, initial data check |
| 🔹 **2. Data Cleaning** | Missing value handling, new columns (e.g. `Active`) |
| 🔹 **3. Grouping** | Aggregation by `Date`, `Country/Region` |
| 🔹 **4. Global Trend** | Line charts showing confirmed, recovered, deaths |
| 🔹 **5. Country-wise Analysis** | Identify top impacted countries |
| 🔹 **6. Visualization** | Matplotlib plots for trends and summaries |

---

## 📈 Sample Insights

- Calculated and plotted global active cases over time.
- Identified top countries by confirmed and death counts.
- Tracked trendlines for `Confirmed`, `Deaths`, `Recovered` cases globally.
- Aggregated data at `Country/Region` level and `Date`.

---

## 💡 Key Learning Outcomes

- How to clean and preprocess real-world datasets.
- Creating new informative columns such as `Active = Confirmed - Deaths - Recovered`.
- Using `groupby()` and time-based aggregations.
- Creating meaningful visualizations with Matplotlib.

---

## 🧠 Common Interview Questions Answered

1. What are missing value handling techniques in Pandas?
2. How do you use `groupby()` for date and region analysis?
3. How do you derive insights from time-series health data?
4. How do you calculate and interpret `Active` cases?

---

## 🗃️ Files Included

- `Covid19 Project.ipynb` — main notebook
- `covid_19_clean_complete.csv` — raw dataset
- README.md (this file)

---

## 🚀 How to Run

1. Clone the repository
2. Open the Jupyter Notebook `Covid19 Project.ipynb`
3. Make sure the CSV file is in the same folder
4. Run all cells

---

## 📌 Credits

- Dataset: [Kaggle COVID-19 Dataset]
- Project by: Neha Jaiswal (Data Analyst Intern)

---
