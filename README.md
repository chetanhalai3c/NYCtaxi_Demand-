
# 🚖 NYC Taxi Demand Project 📊

I explored the fascinating world of predicting NYC taxi demand with this end-to-end time series ML project! Predict the next hour's ride count, helping taxi companies bridge the supply-demand gap and serve users better. 

## 📊 Data Source 
We've harnessed data from the official NYC government's "TLC Trip Record Data," covering the extensive time span from January 2022 to June 2023.

## 🧐 Key Columns
While there are many columns available in the dataset, we're primarily honing in on two critical ones: 'tpep_pickup_datetime' and 'PULocationID.' These data points are the cornerstone of our predictive modeling.

## 🔍 Preprocessing
In the preprocessing phase, we've gone above and beyond. We've introduced new time slots that were missing in the original data, enhancing our forecasting accuracy. 

## 🤖 Modeling
Our journey takes us through the world of predictive modeling. We've explored baseline estimators, harnessed the power of XGBoost, and embraced LightGBM. Spoiler alert: LightGBM emerged as the champion with its stellar performance.

## 🧠 Feature Store
I've utilized the Hopsworks Featurestore, a powerful tool for storing and managing features. This facilitates streamlined experimentation and model deployment.

## 🌐 Interactive Frontend
But that's not all! I've taken it a step further by creating an engaging Streamlit-powered application. It visualizes NYC's map, highlighting regions with high ride predictions in dark green. Plus, you can explore forecasts for the next ten locations.

## 🚀 DEMO 
Ready to dive in? Experience our project live by visiting this [link](https://frontendpy-chetan-nyctaxidemand.streamlit.app ). It's a fascinating journey into the world of taxi demand prediction! 🌟🗽🚕

## Authors

- [@ChetanHalai](https://github.com/chetanhalai3c)




## Features

- End-to-End Solution 
- Time Series Analysis
- Real-World Data
- Scalable

## Installation

Install [Python Poetry](https://python-poetry.org/)

```bash
 curl -sSL https://install.python-poetry.org | python3 -

```


cd into the project folder and run

```bash
$ poetry install
 
```


Activate the virtual env that you just created with

```bash
$ poetry shell
 
```
    
## Tech Stack

**Data Analysis:** Numpy, Pandas, Plotly 

**Modeling** Python, Scikit-Learn, XGboost, LightGBM

**Deployment** Hopsworks, Streamlit


## License

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)

