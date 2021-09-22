# iAQAR: Riyadh real-estate prediction (MVP):

### Goal the project:

> The primary goal of the project is to predict riyadh real-estate land prices.
### Interval:
> The chosen interval of data is the last 10 years riyadh land prices, the reason is minister of justice land prices started 2010.

### Training workflow:
> 1) EDA, to find anomalies in the data such as duplicates and outliers
> 2) Feature engineering to enhance the model
> 3) Time Series data split into training, validation and testing. 
> 4) The following models are used: <br>
> 4.1) Linear regression (Baseline) <br>
> 4.2) Polynomial regression <br>
> 4.3) Random forest <br>
> 4.4) XGboost <br>
> 4.4) Neural Network <br>
>The best found was neural network achieving R^2 of 0.60 

### Findings:
![image](https://raw.githubusercontent.com/Naif-Albader/Regression_Project/main/images/RealVsPredicted.png)
> The above figure shows predicted target vs real target; th figure shows a slight good model.
<br>
<br>

![image](https://raw.githubusercontent.com/Naif-Albader/Regression_Project/main/images/Sample.png)
> The above a sample of tested data (Area 500, Location: "الياسمين"), the prediction show the value of land after 5 years.
