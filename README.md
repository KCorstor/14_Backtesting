## **Backtesting Machine Learning**


***Adjusting the training algorithm***
I first trained the training algorithm by adjusting the size of the training dataset. The first model I ran was with a 3-month baseline of data. I changed that to 6 months and was able to see moderate increases of around 1bp for Precision, recall, and f1-score.

When I changed the timeframe from 6 months to 8 months, accuracy dropped by two bps, but the f1-score increased by around 5 for the macro and weighted averages.

When I changed the testing timeframe down to one month, there was a 2bp decrease in the macro average from the 3 month baseline for precision, recall and f1. Adjusting the timeframe had a somewhat negligible effect on the performance of the model. 

***Tuning the SMA input features***
I adjusted the SMA input features from a short window of 4 days, to 20 days, and moved the long window from 100 to 150. While increasing these periods, I was able to increase my f-1 macro average by 9bps. The precision and recall scores both lost a bp, but overall it appeared to be a beneficial change. 


~~### Step 3: Choose the set of parameters that best improved the trading algorithm returns.
Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your `README.md` file.~~

