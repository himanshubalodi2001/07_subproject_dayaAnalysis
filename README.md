# 🦠 COVID-19 Data Analysis Project

This project is focused on analyzing global COVID-19 data to uncover insights such as the most and least affected regions, recoveries, and death rates. The analysis is done using Python in a Jupyter Notebook.

---

## 📁 Project Name

`covid19_data_analysis`

---

## 🎯 Objective

To analyze a COVID-19 dataset using Python and answer key data-driven questions related to the pandemic's global impact until **29 April 2020**.

---

## 📂 Files Included

- `covide19_data_analysis.ipynb` – Jupyter Notebook containing all analysis and visualizations.
- `covid_19_dataSets.csv` – The dataset containing global COVID-19 statistics.
- `covid19_problem_statement.txt` – Problem statement and commands used.

---

## 📌 Questions Answered

1. Number of Confirmed, Deaths, and Recovered cases in each Region.
2. Removal of records with less than 10 confirmed cases.
3. Region with **maximum confirmed** cases.
4. Region with **minimum death** cases.
5. COVID-19 statistics reported from **India** till 29 April 2020.
6. Sorting data:
   - A) By number of Confirmed cases (ascending)
   - B) By number of Recovered cases (descending)

---

## 🔍 Key Techniques Used

- Handling missing values using `df.isnull().sum()` and heatmaps.
- Grouping and aggregating data using `groupby`.
- Filtering with conditions (`df[df.Confirmed > 10]` etc.)
- Sorting data using `sort_values`.
- Data Visualization with Seaborn and Matplotlib.

---

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## 🧪 How to Run

1. Download or clone the repository.
2. Ensure required libraries are installed:
   ```bash
   pip install pandas matplotlib seaborn
