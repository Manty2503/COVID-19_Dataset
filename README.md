# COVID-19_Dataset

Given a dataset containing details about new COVID-19 cases recorded in India on daily
basis as a csv file (daily_covid_cases.csv). It shows the rolling 7-day average of newly
confirmed cases starting from 30th-Jan-2020 to 2-Oct-2021. Rows are indexed with dates; the first
column represents the date and the second column represents the new COVID-19 cases recorded
that day. We will use this dataset to build an autoregression (AR) model.

The Lag_In_Days code:
* Generates plots of the data with some days lag.

The AutoCorrelation code:
* Splitting the data into 65% and 35% with shuffling as off.
* Imports the Autocorrelation model from statsmodels.tsa.ar_model.
* Applys the AR model with 5-Days lag.
* Calculating RMSE and MAPE for this case.

The AR_diff_Lag_Values code:
* Applys the AR model for different values of lag days and calculates the errors.

