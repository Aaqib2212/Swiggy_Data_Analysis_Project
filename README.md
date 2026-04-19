# Swiggy_Data_Analysis_Project
An end-to-end **food delivery analytics project** built in Microsoft Excel, exploring Swiggy order data across India. The dataset spans **197,430 orders** across **28 states** over **8 months (Jan–Aug 2025)**, with insights into restaurant performance, dish-level pricing, ratings, and food preferences.

# Dashboard Preview
Interactive Excel dashboard with KPI cards, pivot charts, and slicers for dynamic filtering by state, city, food type, and time period.

# File Structure

```
Swiggy_Data_Analysis_Project.xlsx
│
├── 📋 Raw_Data       → 197,430 rows of cleaned order-level data
├── 📐 Analysis       → Pivot tables, KPI calculations, and summaries
└── 📊 Dashboard      → Interactive charts and slicers
```

---
# Key Metrics

| Metric | Value |
|---|---|
| Total Revenue | ₹5.3 Crore |
| Total Orders | 1,97,430 |
| Average Order Value | ₹268.5 |
| Average Rating | 4.34 / 5 |
| States Covered | 28 |
| Cities Covered | 28 |
| Unique Dish Categories | ~5,000 |

---
# Dataset Columns

| Column | Description |
|---|---|
| `State` | Indian state of the order |
| `City` | City of the order |
| `Order Date` | Date of order (Jan–Aug 2025) |
| `Day` | Day of the week |
| `Quarter` | Quarter (Q1–Q3) |
| `Week` | Week number of the year |
| `Restaurant Name` | Name of the restaurant |
| `Location` | Locality/neighbourhood |
| `Category` | Dish category (e.g., North Indian Gravy, Snack) |
| `Dish Name` | Name of the ordered dish |
| `Food Type` | Veg / Non-Veg (auto-classified via formula) |
| `Price (INR)` | Price of the dish in Indian Rupees |
| `Rating` | Restaurant rating (1.5–5.0) |
| `Rating Count` | Number of ratings received |

---
# Analysis Highlights

- **Veg vs Non-Veg Split:** ~71% Veg (1,39,546) | ~29% Non-Veg (57,884)
- **Price Range:** ₹0.95 (min) → ₹8,000 (max) | Median: ₹229
- **Rating Distribution:** Majority clustered between 4.3–4.5
- **Time Coverage:** January 2025 to August 2025 (Q1–Q3)
- **Geographic Reach:** Pan-India — from Karnataka & Maharashtra to Sikkim & Mizoram

---
# Tools & Techniques

- **Microsoft Excel**
  - Pivot Tables & Pivot Charts
  - Slicers for dynamic filtering
  - `TEXT()`, `WEEKNUM()`, `IF()`, `SEARCH()` formulas
  - `GETPIVOTDATA()` for KPI extraction
  - Conditional Formatting
  - Structured Tables (`Table1`)

---
# How to Use

1. Download `Swiggy_Data_Analysis_Project.xlsx`
2. Open in **Microsoft Excel** (2016 or later recommended)
3. Navigate to the **Dashboard** sheet
4. Use the **slicers** to filter by State, City, Food Type, or Quarter
5. Explore the **Analysis** sheet for pivot-based breakdowns

---
# Potential Extensions

- [ ] Connect to Power BI for advanced visualizations
- [ ] Automate data refresh using Power Query
- [ ] Add city-wise revenue heatmap
- [ ] Build a Python/Pandas version of the analysis
- [ ] Predict ratings using ML regression

---
# License
This project is open-source and available under the [MIT License](LICENSE).


# Contact
Feel free to connect:
- Linkedin: https://www.linkedin.com/in/aaqib2212/
- Mail: aaqibbelim0@gmail.com
