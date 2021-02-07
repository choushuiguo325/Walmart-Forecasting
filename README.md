# Time series analysis and forecasting on Walmart product unit sales

## Project Description

In this project, our group performed 28-day unit sales predictions using four models for one Walmart product (FOODS_3_352) based on the Walmart five-year unit sales data from [Kaggle](https://www.kaggle.com/c/m5-forecasting-accuracy/data).<br/>
First, we performed basic data cleaning and visualization and explored the sales pattern. Then, we applied regression models, the ETS (error, trend, seasonality) model, the seasonal ARIMA (auto-regressive, integrated, moving average) model, and the dynamic regression model to further decompose the data and to do forecasting. Finally, we evaluated the model performance of prediction based on the parameter RMSE. 

* All the project files are contained in this repo
* Tools/Languages used: `Python(pandas, numpy)`, `R(forecast, ggplot, dbplyr, urca, lubricate)`, `Excel`
* See our final [analysis report](https://www.notion.so/Project-Walmart-Forecasting-e046af1e2d72448f9d38ca11a4d88414)


## File Description

### 1. `data`

* `calendar_factors.csv` contains the targeted sales data with cleaned and prepared calendar dummy variables
* `calendar.csv` contains the raw calendar variables information 
* `eventAndHoliday.csv` contains the titles and types of all the holidays and events involved 
* `calendar.csv` contains all the sales info about food products in CA_1 Walmart store

### 2. `static`
* `calendar.ipynb` contains the Python code that cleans, prepares and explores the calendar variables involved in predictions
* `walmart.Rmd` contains the R notebook that constructs and optimizes all the prediction models
* `walmart.nb.html` contain the HTML version of the R notebook that constructs and optimizes all the prediction models




