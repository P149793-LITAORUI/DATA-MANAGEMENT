# DATA-MANAGEMENT STQD6324 Assignment 1-P149793  
## 1.Data Introduction  
  This dataset comes from USA OPEN DATA, which provides data on alcoholic beverage taxation in Connecticut. The dataset contains alcoholic beverage taxes from January 2020 to February 2025. There are 29 columns and 62 rows of data in total. The categories included are Malt Beverages, Cider, Wines, and Distilled Spirits, and each category is divided into different subcategories.  
  ![Data](picture7.png)
## 2.Data Cleaning  
  ![Missing value](picture1.png)  
  By checking the data, there are no missing values ​​in the dataset.  
## 3.Data Visualization and Analysis  
  ![Monthly Alcohol Tax Revenue by Calendar Year](picture2.png)  
  Alcohol tax revenue in each year shows different monthly fluctuation characteristics, with tax revenue in June 2023 being particularly prominent, reflecting the impact of seasonal or special factors on alcohol tax in different years. Since there is no data from March 2025 onwards in the dataset, the curve for 2025 is followed by zeros.  
  ![Alcohol Tax Distribution](picture3.png)  
  The proportion of distilled spirits in alcohol tax continues to grow, and their dominance becomes more and more prominent; the tax share of malt beverages and wine decreases year by year; the tax contribution of cider is negligible and has remained stable for a long time. This reflects that there are obvious differences in the contribution of different alcoholic beverages to alcohol tax, and the trend changes are significant.  
  ![Wine Tax Distribution](picture4.png)  
  Large wineries are the main source of wine tax, but their revenue is decreasing year by year; taxes on high-alcohol and sparkling wines are also on a downward trend; the tax contribution of small wineries is small and unstable.  
## 4.Data Prediction and Analysis  
  ![Alcoholic Beverages Tax Revenue with Forecast](picture5.png)  
  ![Result](picture6.png)  
  The prophet model is used to predict the total tax revenue from March to December 2025. By analyzing the pictures, it is found that the tax revenue fluctuates greatly and there is no obvious stable trend, indicating that future tax revenue is affected by many uncertain factors and has high volatility and unpredictability.
## 5.Conclusion  

