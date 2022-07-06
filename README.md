# Machine_learning
Projects on machine learning models: Classifications, regression, forecasting and fuzzy matching

Clickstream data(Propensity model) : Imbalanced data set which had (100000,958), which required pre-processing of datetime atributes and cleaning out null values. Classification  modelling starts with collecting feature importance through random-forest feature selection and permutation importance. CV hyper parameter tuned models.
Model also has comparision between regularized and unregularized models accuracy and AUC. 

College admission: Data had unwanted attributes of MBA scores whhich required dropping as we were building the model for the admissions into MBA. CHIAD and CART model classification accuracy was checked and many models like RF, adaboost, and many more (12)  were CV and checked for runtime and accuracy. Business rules generated from CART tree. 

Forecast spares: Time-series data was checked for stationarity (ADF, KPSS, OCH ) tests for detrending and deseasonlizing the data. Holts-winter, ARIMA, SMA, EWMA were compared against RMSE and MAPE for which was appropriate for the spares. 

Fuzzy Matching: This was performed to map external Nielson data to Internal product master, which was done manually. This leads to trend analysis and market share analysis. Cosine similarity, Levensitne , MRA ( phonetic ) and few more algorithms are fit for 14 internal and external attributes. 
