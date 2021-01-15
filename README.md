# Light Rail Patronage
Light Rail Patronage project is a machine learning model to predict the total patronage numbers on the Light Rail Network in Canberra. This is based on "Time Series Forecasting" and the forecasting algorithm used here is Holt Winter’s Exponential Smoothing (HWES) also know as ETS model.

The ETS model is based on error (E), trend (T), seasonal (S) component. Its suitable for exponentially weighted linear seasonal forecasting where the weightage is given for recent past. It's for predicting univariate variable where only one variable varies over a constant period of time.

The ETS model works well on regular patterns will slight change in trend and forecasts with minimal errors. But its prediction on sudden drop or increase in trend is on a large scale results in poor results. 

The ETS model is implemented using python and requires Jupyter Notebook to run.

### Required Packages:
- Pandas
- NumPy
- Matplotlib
- Sklearn
- Statsmodels
- Notebook (jupyter)

### How To Run :
Make sure your have python 3.6+, pip and git installed. Open shell or cmd prompt and run the following commands.
```sh
$ git clone https://github.com/hk-23/light_rail_patronage.git
```
```sh
$ cd light_rail_patronage
```
```sh
$ pip install -r requirements.txt
```
```sh
$ jupyter notebook
```
Once these run withour any errors then a browser will pop up with all the files in the repository. Click the "light_rail_forecast.ipynb" file to view and run the file.

# Activity 2

Check the "activity2.pdf" file in this repository. Thank You!