# DATA-MANAGEMENT STQD6324 Assignment 1 - P149793

## 1. Data Introduction
This dataset originates from USA OPEN DATA, providing comprehensive records on alcoholic beverage taxation in Connecticut spanning January 2020 to February 2025. The dataset comprises:

- **29 columns** representing various tax categories and metrics
- **62 rows** of monthly data
- **Categories**: Malt Beverages, Cider, Wines, and Distilled Spirits (with subcategories)

![Data Overview](/Assignment1-picture/picture7.png)

## 2. Data Cleaning
Initial data quality assessment revealed:
- **No missing values** across all columns
- Consistent data structure throughout the time series

![Missing Value Check](/Assignment1-picture/picture1.png)

## 3. Data Visualization and Analysis

### 3.1 Monthly Tax Revenue Trends
The analysis shows distinct seasonal patterns with notable fluctuations:
- **June 2023** exhibits anomalously high revenue (possibly due to seasonal demand or policy changes)
- **2025 data** is incomplete (zeros shown after February)

![Monthly Revenue Trends](/Assignment1-picture/picture2.png)

### 3.2 Tax Contribution by Beverage Type
Key observations:
- **Distilled Spirits** dominate tax revenue (66-76%) with increasing share
- **Malt Beverages** contribute 10-17%
- **Wines** account for 12-16% (declining trend)
- **Cider** remains negligible (~0.2%)

![Tax Distribution](/Assignment1-picture/picture3.png)

### 3.3 Wine Tax Subcategory Analysis
Detailed wine tax breakdown:
- Large wineries contribute majority but show declining revenue
- High-alcohol/sparkling wines decreasing in contribution
- Small wineries have minor, unstable contributions

![Wine Tax Distribution](/Assignment1-picture/picture4.png)

## 4. Data Prediction and Analysis

### 4.1 Methodology: Prophet Model
Facebook's Prophet model was employed for forecasting due to its:
- Robustness to outliers
- Handling of seasonality and trend changes
- Suitability for monthly time series data

### 4.2 Prediction Results
Forecast for March-December 2025 shows:
- High volatility and uncertainty
- No clear stable trend
- Significant month-to-month fluctuations

![Revenue Forecast](/Assignment1-picture/picture5.png)
![Forecast Metrics](/Assignment1-picture/picture6.png)

## 5. Conclusion and Recommendations

### 5.1 Key Findings
- **2020 anomaly**: Likely pandemic impact
- **Stable 2021-2024**: Minimal fluctuations
- **Category trends**:
  - Distilled Spirits: 66-76% (growing)
  - Malt Beverages: 10-17%
  - Wines: 12-16% (declining)
  - Cider: ~0.2% (stable)

### 5.2 Strategic Recommendations
1. **Data Enhancement**: Incorporate demographic/sales channel data for deeper analysis
2. **Revenue Stabilization**: Implement promotions during low-tax periods
3. **Regulatory Focus**:
   - Strengthen oversight of high-growth categories
   - Support small-scale wineries through targeted policies
4. **Scenario Planning**: Develop contingency plans for revenue volatility
