# Seasonal Agriculture Performance Analysis

## Project Overview

**Seasonal Agriculture Performance Analysis** is a data analytics project that studies agricultural performance across different seasons, crops, states, resources, environmental conditions, and economic factors.

The project uses a dataset containing **4,000 agricultural records and 28 variables** to identify useful patterns and insights related to crop yield, production, rainfall, irrigation, water usage, revenue, profit, and farming risks.

The main goal is to understand agricultural performance and provide data-driven insights that can support better farming and resource-management decisions.

---

## Objectives

* Analyze agricultural performance across different seasons.
* Compare crop performance and productivity.
* Compare agricultural performance across states.
* Study the relationship between environmental factors and crop yield.
* Analyze irrigation methods and water efficiency.
* Evaluate revenue, cost, and profit.
* Analyze disease and pest risk across seasons.
* Identify important patterns, trends, and variations.
* Perform statistical analysis to support the findings.
* Provide evidence-based recommendations.

---

## Dataset

The dataset contains **4,000 records and 28 variables**.

### Important Variables

* Farm ID
* State
* District
* Crop
* Season
* Farm Area
* Rainfall
* Average Temperature
* Humidity
* Sunlight Hours
* Soil pH
* Soil Moisture
* Nitrogen
* Phosphorus
* Potassium
* Irrigation Method
* Fertilizer Usage
* Pesticide Usage
* Seed Quality
* Yield
* Production
* Market Price
* Total Cost
* Revenue
* Profit
* Water Used
* Water Efficiency
* Disease/Pest Risk

---

## Seasons Analyzed

The project analyzes three agricultural seasons:

* **Kharif**
* **Rabi**
* **Zaid**

---

## Crops Analyzed

The dataset contains the following major crops:

* Wheat
* Maize
* Pulses
* Rice
* Cotton
* Chilli
* Groundnut
* Sugarcane

---

## Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **SciPy**
* **CSV Dataset**

---

## Project Workflow

The project follows these major steps:

1. Data Collection
2. Data Loading
3. Data Understanding
4. Data Cleaning
5. Missing Value Handling
6. Exploratory Data Analysis
7. Season-wise Analysis
8. Crop-wise Analysis
9. State-wise Analysis
10. Resource and Irrigation Analysis
11. Economic Analysis
12. Risk Analysis
13. Correlation Analysis
14. Statistical Analysis
15. Visualization
16. Insights and Recommendations

---

## Data Cleaning

The dataset was checked for:

* Missing values
* Duplicate records
* Data types
* Numerical and categorical variables
* Invalid or inconsistent values

Missing values were handled before performing the main analysis.

---

## Key Analysis Areas

### 1. Seasonal Performance

Season-wise performance was analyzed using:

* Average yield
* Total production
* Revenue
* Cost
* Profit
* Water usage
* Water efficiency
* Disease/pest risk

### 2. Crop Performance

Different crops were compared based on:

* Average yield
* Total profit
* Production
* Resource usage

### 3. State Performance

States were compared using:

* Average yield
* Total profit
* Agricultural productivity

### 4. Resource Analysis

The project studies:

* Irrigation methods
* Water usage
* Water efficiency
* Fertilizer usage
* Environmental conditions

### 5. Economic Analysis

Economic performance was analyzed using:

* Market price
* Total cost
* Revenue
* Profit
* Profit margin

### 6. Risk Analysis

Disease and pest risk was analyzed across different seasons and agricultural conditions.

---

## Statistical Analysis

A one-way ANOVA test was performed to examine whether average crop yield differs significantly across agricultural seasons.

### Result

* **F-statistic:** 1.544
* **p-value:** 0.213678

Since the p-value is greater than 0.05, the analysis does not show a statistically significant difference in average yield between the seasons at the 5% significance level.

---

## Important Findings

* **Kharif** has the highest average yield among the three seasons.
* **Kharif** also has the highest total profit in the dataset.
* **Zaid** has negative total profit in the analyzed dataset.
* **Sugarcane** has the highest average yield among the analyzed crops.
* **Chilli** has the highest total profit among the analyzed crops.
* **Maharashtra** has the highest total profit among the analyzed states.
* **Punjab** has the highest average yield among the analyzed states.
* **Rainfed** has the highest average water-efficiency value in the dataset.
* Drip irrigation shows strong average yield performance.
* Flood irrigation has comparatively high water usage.
* Seasonal average yield differences were not statistically significant according to the ANOVA test.

---

## Visualizations

The project includes visualizations for:

* Average yield by season
* Total profit by season
* Crop-wise yield
* Crop-wise profit
* State-wise profit
* Environmental correlation heatmap
* Rainfall vs yield
* Profit distribution by season
* Disease/pest risk by season

---

## Project Structure

```text
Seasonal_Agriculture_Performance_Analysis_HS/
│
├── README.md
│
├── Seasonal_Agriculture_Performance_Analysis_FIXED.ipynb
│
├── data/
│   └── seasonal_agriculture_performance_dataset.csv
│
├── outputs/
│   ├── charts/
│   │   ├── 01_average_yield_by_season.png
│   │   ├── 02_total_profit_by_season.png
│   │   ├── 03_top_crops_yield.png
│   │   ├── 04_top_crops_profit.png
│   │   ├── 05_states_profit.png
│   │   ├── 06_environment_correlation_heatmap.png
│   │   ├── 07_rainfall_vs_yield.png
│   │   ├── 08_profit_distribution_season.png
│   │   └── 09_risk_by_season.png
│   │
│   └── summary_tables/
│
└── ...
```

---

## How to Run the Project

### Step 1: Install Python

Install Python on your system.

### Step 2: Install Required Libraries

Run:

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

### Step 3: Open Jupyter Notebook

Run:

```bash
jupyter notebook
```

### Step 4: Open the Notebook

Open:

```text
Seasonal_Agriculture_Performance_Analysis_FIXED.ipynb
```

### Step 5: Run All Cells

Run the notebook cells from beginning to end to reproduce the analysis and visualizations.

---

## Future Scope

The project can be extended in the future by:

* Adding more years and regions.
* Including additional crop categories.
* Developing machine-learning models for yield and profit prediction.
* Building crop recommendation systems.
* Adding advanced anomaly and risk detection.
* Integrating real-time weather and market-price data.
* Developing an interactive decision-support dashboard.

---

## Conclusion

This project provides a detailed analysis of agricultural performance using data analytics techniques. It compares seasons, crops, states, resources, economic outcomes, and agricultural risks.

The analysis helps identify profitable crops, productive regions, resource-efficiency patterns, and seasonal performance differences. These insights can support better agricultural planning and data-driven decision-making.

---

## Author

**Hasmukh Suthar**

**Project:** Seasonal Agriculture Performance Analysis

**GitHub:** `https://github.com/hasmukh-123`
