# **Time Series Forecasting Prophet**
This Python application is to Forecast using Prophet. This program runs in Google Colab.

It uses timeframe manipulation and slicing methods to perform "Time Series" analysis; and uses a correlation to validate if any predictable relationship exists between Search Traffic trends and the Stock Volatility.

Also, Visualization techniques for time series data are created to better understand and predict search traffic and revenues.

---
## Technologies
This application is developed on the *Python 3.7.11 version* 

* [Jupyter Notebook](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html) - It's a server-client application that allows editing and running notebook documents via a web browser.

* [pandas](https://pandas.pydata.org/pandas-docs/stable/index.html) - For Series, DataFrame, and plots

* [hvplot](https://hvplot.holoviz.org/user_guide/Introduction.html) - For a high-level plotting API built on HoloViews and Bokeh that provides a general and consistent API for plotting data in all the abovementioned formats.

* [sklearn](https://scikit-learn.org/stable/index.html) - For Simple and efficient tools for predictive data analysis.


* [fpprophet](https://pypi.org/project/fbprophet/)- For forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects.


---
## Installation Guide
The following installation must be performed before running the program:

```python
  pip install pandas
  pip install jupyterlab
  pip install -U scikit-learn
  pip install fbprophet
```


---
## Usage
This section is an explanation of how to use this program: 

First, the app seeks to analyze Google search data and determine whether there is a pattern linking this data to corporate financial events. Next, hourly search data is grouped and considered for whether there are specific times of day where search data peaks. Along with search data, the app reads in stock price data and compares it with time series search data. Lastly, the app analyzes and forecasts patterns in the hourly search data. Plots are rendered throughout the app to visualize trends.

---
## Contributors
*Contributors*: Saina Azimi

*Email*: azimi.sainaa@gmail.com

*LinkedIn*: https://www.linkedin.com/in/azimi-saina/ 

---
## License 
UC Berkeley

----