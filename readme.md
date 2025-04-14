Repository aims to predict Lithuanian energy sector impabalances based on weather conditions predictions (known one day ahead). 

To solve the problem Linear Regression model was used, howeved proved to be not sufficient, thus, XGBoost model was used ( + one with imbalance lags (known 30 minutes after the end of timestamp)).