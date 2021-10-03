## Overview

Prediction of NIFTY50 index movement for 7 days period.
LSTM layers are used in keras to predict NIFTY50 index movement for 7 days period.

Project is divided into three parts:</br>
* loadData.py
Scraped Wiki's NIFTY50 page to get all 50 ticker symbols and performed transformation on the raw data.<br>
Used Quandl API to fetch stock data for past 6 years(2012-2018)

* Preprocess.py
Label training data as 0(sell) and 1(buy)<br>
Scale data using sklearn preprocessing libarary

* Build_model.py</br>
Build model in keras with LSTM layers.

Program runs at 61% Validation accuracy

### Dependencies:
* pandas
* quandl
* tensorflow
* keras
* sklearn
* numpy
* beautifulsoup4
* requests

### Usage:
Run Buildmodel.py script on commandline.

### Acknowledgements:
https://youtu.be/BYd9M_ragR0
