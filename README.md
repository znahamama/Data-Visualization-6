# 📊 COMP 4304 – Assignment 6: Births Heatmap Analysis

## Overview

This Jupyter Notebook addresses **Assignment 6** for COMP 4304, focused on visualizing birth data in England and Wales using a **heat map**. The dataset spans from **1995 to 2023**, and the goal is to reproduce a stylized heat map that highlights birth trends across the calendar year.

![Viz6](https://github.com/user-attachments/assets/f652ce12-6649-49a2-9447-94ff71cbe015)

The assignment uses **`pandas`**, **`matplotlib`**, and **`seaborn`** to manipulate and visualize the data.

---

## 🔍 Objective

Recreate a heat map of **average daily births** in England and Wales using:

- **Seaborn's `heatmap()`** function  
- **ColorBrewer's `YlOrRd`** colormap with **5 discrete bins**  
- **X-axis:** Months (January to December)  
- **Y-axis:** Days of the month (1–31)  
- Exclude invalid dates (e.g., February 30)  
- Special handling of **February 29** to adjust for leap years  
- Add a **bold title** to the plot

---

## 📁 Files Included

- `Assignment 6.ipynb` – Jupyter notebook containing all code and output  
- `daily-births.csv` – Dataset used for analysis and visualization  
- `assignment6.pdf` – Assignment instructions

---

## 📊 Visualization Preview

The notebook generates a heat map where:
- Colors represent average births from **1600 to 1950**, split into **5 bins**
- Lighter shades = fewer births, darker shades = more births
- Summer and early Autumn show the highest birth rates

---

## 🧪 Technologies Used

- Python  
- [pandas](https://pandas.pydata.org/)  
- [matplotlib](https://matplotlib.org/)  
- [seaborn](https://seaborn.pydata.org/)
