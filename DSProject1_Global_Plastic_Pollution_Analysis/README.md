# 🌍 Global Plastic Pollution Analysis

## 📌 Project Overview

This project explores the relationship between **plastic waste generation per capita** and **GDP per capita** across countries using data from Our World in Data. The goal is to understand whether economic development is linked to environmental degradation in the form of plastic waste.

---

## 📊 Dataset Information

- **Source**: Our World in Data
- **File**: `per-capita-plastic-waste-vs-gdp-per-capita.csv`
- **Features**:
  - `Entity`: Country name
  - `Year`: Observation year
  - `Per capita plastic waste (kg/person/day)`
  - `GDP per capita, PPP (constant 2011 international $)`
  - `Total population`
  - `Continent`

---

## 🔍 Exploratory Analysis

- Trends in plastic waste across countries and continents.
- Correlation between GDP per capita and plastic waste.
- Identification of top plastic-producing nations.

**Techniques Used**:
- Data Cleaning (handling `NaN`, inconsistent entries)
- Statistical Visualization (`seaborn`, `matplotlib`)
- Correlation heatmaps and scatter plots
- Group-wise aggregation (continent-level insights)

---

## 💡 Key Insights

- High-income countries generally generate more plastic waste per person.
- Some middle-income countries show increasing trends over time.
- Several countries lack data due to underreporting or absence of measurement infrastructure.

---

## 🛠 Tools & Technologies

- Python (Jupyter Notebook)
- Libraries: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

---

## 📁 Folder Structure

Global_Plastic_Pollution_Analysis/
├── global-plastic-waste-2010.ipynb
├── data/
│ └── per-capita-plastic-waste-vs-gdp-per-capita.csv
└── README.md

---

## 🧠 Learning Outcomes

- Hands-on experience with large global datasets.
- Critical thinking about the intersection of economy and environment.
- Mastery in using visualizations to drive data storytelling.

---