# Unit_10_Yen_forthe_Future

![Yen Photo](Yen.jpg)

#### Time-Series Forecasting

**1. Based on your time series analysis, would you buy the yen now?**

A: I would buy the yen now.  It's projected to increase as shown by various models, however this increase has a high degree of risk and volatility. 

**2. Is the risk of the yen expected to increase or decrease?**

A: The risk of the yen is expected to increase as shown by the increased volatility in the GARCH model. 

**3. Based on the model evaluation, would you feel confident in using these models for trading?**

A: Not for an extended period of time.  The model could potentially predict short term changes but would not be good for a trading tool to project long-term price changes. 

#### Linear Regression Forecasting

**Does this model perform better or worse on out-of-sample data compared to in-sample data?**

For both the in-sample and out-sample performance, the RMSE is relatively high (.59 for in-sample and .42 for out-of-sample), indicating the model is likely not a good fit. 
Since the RMSE is lower on the out-sample, this indicates the model error rates is lower in predicting the testing set than the error rate in the training set. 
