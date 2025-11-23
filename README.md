## NYC Coffee Shop Sales Analytics ☕

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=flat-square&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![License](https://img.shields.io/badge/Data-Open_Source-lightgrey?style=flat-square)

> **Executive Summary:** An analysis of sales patterns across three Maven Roasters locations in NYC (Astoria, Lower Manhattan, Hell's Kitchen). The project identifies key drivers of revenue, seasonal demand shifts, and opportunities for operational optimization.

## 🎯 Project Objectives
The goal of this analysis was to support strategic decision-making by:
1.  **Cleaning & Processing** raw transaction data (149k+ records).
2.  **Identifying Sales Patterns** by time of day, season, and product type.
3.  **Comparing Location Performance** to tailor marketing strategies.

## 🛠 Tools & Technologies
*   **Language:** Python
*   **Libraries:** Pandas (Data Manipulation), Seaborn/Matplotlib (Visualization)
*   **Data Source:** [Kaggle - Coffee Shop Sales Dataset](https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales)

## 📊 Key Findings

### 1. Peak Operational Hours
*   **Observation:** Revenue peaks consistently between **7:00 AM and 10:00 AM** across all product categories.
*   **Business Insight:** Staffing levels and inventory preparation (pre-brewing) must be maximized during this 3-hour window to reduce wait times and capture maximum revenue.

### 2. Location-Based Preferences
*   **Astoria:** Strong preference for **Gourmet Brewed Coffee** (>6,000 transactions).
*   **Hell's Kitchen & Lower Manhattan:** Higher demand for **Barista Espresso**.
*   **Strategy:** Marketing in Astoria should focus on "Single Origin/Gourmet" messaging, while the other locations should focus on "Artisan Espresso" quality.

### 3. Seasonal Trends
*   **Winter:** Shows the highest sales volume (likely due to cold weather driving hot drink demand).
*   **Autumn Dip:** A noticeable decline in sales during Autumn.
*   **Recommendation:** Launch aggressive promotional campaigns (e.g., "Pumpkin Spice" or loyalty boosters) in September/October to counteract the seasonal slump.

## 📈 Visualizations
*(Note: Full visualizations can be found in the Jupyter Notebook)*

*   **Hourly Revenue Heatmap:** Shows the concentration of sales in the morning commute.
*   **Seasonal Sales Count:** Highlights the winter surge and autumn dip.
*   **Revenue by Location (Boxplot):** Displays the variability of transaction sizes in Hell's Kitchen vs. the consistency in Lower Manhattan.

## 📂 File Structure
```text
├── data/
│   └── Coffee Shop Sales.csv   # Raw dataset (or link to source)
├── notebooks/
│   └── coffee_sales_eda.ipynb  # The main analysis code
├── images/                     # Output graphs (Heatmaps, Boxplots)
└── README.md                   # Project documentation
