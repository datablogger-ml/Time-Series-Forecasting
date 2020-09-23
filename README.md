# Industrial Production Forecasting

#### -- Project Status: Active

## Project Intro/Objective
The purpose of this project is to get familiar with Time Series Forecasting which is very helpful in univariate analysis, and is extensively used in Demand Forecasting. Time series forecasting uses the information in a time series to forecast future values of that series.

### Methods Used
* Time Series Forecasting
* Machine Learning
* Hyper-Parameter Optimization
* Data Visualization
* Inferential Statistics

### Technologies
* Python
* sklearn, statsmodels
* Pandas, jupyter
* matplotlib

## Project Description
(Provide more detailed overview of the project.  Talk a bit about your data sources and what questions and hypothesis you are exploring. What specific data analysis/visualization and modelling work are you using to solve the problem? What blockers and challenges are you facing?  Feel free to number or bullet point things here)

### Data
The industrial production index (IPI) is a monthly economic indicator measuring real output in the manufacturing, mining, electric and gas industries, relative to a base year. It also measures capacity, an estimate of the production levels that could be sustainably maintained and capacity utilization.

It is expressed as an index level relative to a base year (currently 2012) ie. the percentage change in production relative to the base year (2012). In this specific problem, we would be looking at the ice cream and frozen desert IPI.

<a href='https://fred.stlouisfed.org/series/IPN31152N'>Download Link</a>

### Methods

#### 1. Holt-Winters (TES)
#### 2. ARIMA

ARIMA (Autoregressive Independent Moving Average) is a combination of 3 models:
* <strong>AR(p)</strong> Autoregression - a regression model that utilizes the dependent relationship between a current observation and observations over a previous period.
* <strong>I(d)</strong> Integration - uses differencing of observations (subtracting an observation from an observation at the previous time step) in order to make the time series stationary (constant mean -> No trend, constant variance).
* <strong>MA(q)</strong> Moving Average - a model that uses the dependency between an observation and a residual error from a moving average model applied to lagged observations.

#### 3. SARIMA


## Needs of this project

- frontend developers
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting
- etc. (be as specific as possible)

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](Repo folder containing raw data) within this repo.

    *If using offline data mention that and how they may obtain the data from the froup)*
    
3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
4. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

5. Follow setup [instructions](Link to file)

## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)
