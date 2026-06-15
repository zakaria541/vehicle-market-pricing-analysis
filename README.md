# Vehicle Market Pricing Analysis
### Business Statistics

## Project Overview
This project performs an exploratory data analysis (EDA) on a vehicle market dataset to understand the key factors influencing car pricing. The analysis examines relationships between price and various vehicle attributes such as mileage, number of cylinders, number of doors, manufacturer, and year of manufacture.

## Dataset
- **File:** `vehicle_dataset.csv`
- **Features:** Make, Year, Price, Cylinders, Mileage, Doors, Exterior Colour
- **Period Covered:** 2023–2025
- **Price Range:** $0 – $195,895 (mean approx. $52,023)

## Tools & Technologies
- **Language:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## Analysis Performed

### Descriptive Statistics
- Summary statistics across key numerical variables (price, year, cylinders, mileage, doors)
- Identified missing values in price, cylinders, mileage, and doors columns

### Visualisations
- **Price Distribution** — Histogram showing the spread of vehicle prices across the dataset
- **Manufacturer Distribution** — Countplot of vehicles by make
- **Price vs Number of Doors** — Five-door vehicles averaged the highest price (~$80,000)
- **Price vs Cylinders** — Zero-cylinder vehicles (electric) averaged the highest price (~$65,000); three-cylinder vehicles the lowest (~$30,000)
- **Price vs Mileage** — Inverse relationship observed; lower mileage generally associated with higher prices
- **Price Distribution (Box Plot)** — Median price ~$50,000 with notable outliers above $100,000
- **Exterior Colour Distribution** — Countplot of vehicle counts by colour
- **Price vs Year** — Prices remained relatively stable across 2023–2025 (~$50,000 average)

## Key Findings
- Vehicle price is inversely related to mileage — lower mileage vehicles command higher prices
- Five-door vehicles are the most expensive on average, while four-door vehicles are the most affordable
- Electric vehicles (zero cylinders) average the highest price, suggesting a premium market segment
- Prices remained stable across the 2023–2025 period with no significant upward or downward trend
- Several high-value outliers exist above $100,000, indicating the presence of luxury vehicles in the dataset

## Files
| File | Description |
|---|---|
| `vehicle_market_pricing_analysis.ipynb` | Full Jupyter Notebook with code and visualisations |
| `vehicle_dataset.csv` | Vehicle market dataset |

## Author
**Zakaria Gou-Ali**
MSc Business Analytics — University of Greenwich
[LinkedIn](https://www.linkedin.com/in/zakaria-gou-ali-896175347/)
