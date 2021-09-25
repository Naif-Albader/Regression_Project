
# iAQAR

By:
> >  Naif Albader
> >  Yazeed Musallam



## Abstract
Many Saudi people want to buy land in Riyadh city for investment, personal use but they don’t know the future of this investment so, the goal of iAQAR is to use linear regression models to predict the Land price to help people to invest in the right place.

## Design
The data is scrapped from the Saudi Arabian Ministry of Justice website and it represents the sales deals of lands in Riyadh in the last 11 years and the goal was to analysis it to answer these three main questions

•	What are the top stations on traffic to do the campaign on those stations?
•	Is weekday or weekend better to do the campaign on?
•	What is the best time of the day to do the campaign?


## Data Description:
* Datasets with description: </br>
This project based on the data availabile on the ministy of justice website:

> The land prices are scrapped from: https://www.moj.gov.sa/ar/opendata/bi/birealestate/Dashboards/100_kpiDistrict/101_Monthly/kpi101_04.aspx. <br />


## Scope of the work
Sample size:

>  11 years scrapped (2010 to 2021) worth of data will be used for the analysis, and the reason is to make a robust model for the future predections.

> Only riyadh city will be involved in this project.

Description for the datset as num of rows, number of features/columns, names of columns with description:

Description of scrapped data: </br>
The dataset represent the sales deals of lands in riyadh in last 11 years

> Number of features:  8 features/Columns

> Number of rows: Approx.: 600K rows

> Names of columns with description and type:

| Field Name | Description                                                                      |
|-------------|---------------------------------------------------------------------------------|
| Neighborhood| Neighborhoods of Riyadh                                                         |
| Scheme      | Specific Scheme inside a Neighborhood                                           |                                 |
| Land        | Specific Land inside a Scheme                                                   |
| Date        | Date of a land sale                                                             |
| Id          | Unique id for a specific sale                                                   |
| Price (SAR) | The total price of a land in SAR                                                |
| Area (m2)	  | The area of a land in m^2                                                       |                          |
| Price (m2)  | The price of a land for each m^2                                                |


## Algorithms

*Data gathering*:
> 1) Web scrapped the data from ministy of justice website
> 2) helper tools:
> >     1- BeautifulSoup
> >     2- Selenium

*Data cleaning*:
> 1) Deleteing the duplicated data points
> 2) Dealing with outliers using IQR
> 3) Deleting some inaccurate Neighborhoods

*Data validation*:
> 1) Checking no nulls
> 2) Checking datatypes
*feature engineering*:
Features add:
 > 1)  Change date to numeric value
 > 2)  Year
 > 3) Yearly/Area
 > 4) Categorical values are changed to one label  encoder
 
 Model Training &  Evaluation 
Data split:
 >  Training: 2010 - 2020 
 >  Validation: 2021/1 to 2021/5
 >  Testing: 2021/5 to 2021/9

Model used: Neural Network
  results:
    > R2 (Training): 0.70 
    > R2 (Validation):  0.62
    > R2 (Testing):  0.60
 









The main technologies and libraries that will be used are:
Technologies:
> - Python
> - Jupyter Notebook
> - HTML/CSS
> - Flask

Libraries:
> - Pandas
> - pickle
> - BeautifulSoup and selenium
> - OS
> - Matplotlib
> - Seaborn
> - NumPy
> - Sklearn
> - Category Encoders
> - Tensorflow/keras
> - Plotly

Processing tools: 
> Google Colab

## Communication
Findings:

