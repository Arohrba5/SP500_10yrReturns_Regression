# SP500_10yrReturns_Regression
Personal project to practice running regressions in Python 
  
# About
I did this project so I could practice the regression techniques I have been learning in Python. As a beginner to Python and ML, I likely made some mistakes. 
  
My analysis aimed to predict 10-year total S&P 500 market returns based on the PE multiple and 10-year interest rate from 10 years prior. I found that the R-squared value of approximately 0.2 indicates a weak relationship between these input variables and the total returns. Although this might seem low, I still find it noteworthy that the model could explain 20% of the variability in market returns over such an extended period. This suggests that, while the relationship between the predictor variables and the market returns is not particularly strong, there may be some predictive power in the input features. Further research and analysis may reveal additional factors that contribute to the prediction of long-term market returns, leading to an improved model.
  
# Data  
I used excel to combine and modify the data into a single csv file.  
  
Data sources:  
Historical PE ratios of S&P 500 (no modifications): https://www.multpl.com/s-p-500-pe-ratio/table/by-year  
10_Year Treasury Rates (no modifications): https://www.multpl.com/10-year-treasury-rate/table/by-year  
1_Year Total Returns (modifications to generate 10_Year Returns): https://www.slickcharts.com/sp500/returns  
  * Calculated 10-year compounding total returns by multiplying returns of current and next 9 years  
  * Insufficient history to calculate returns for years 2014-2023   
