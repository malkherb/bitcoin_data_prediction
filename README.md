### bitcoin_data_prediction
**Experience on building a Bitcoin Data Predictive Model and Analysis**
Bitcoin Historical Data Analysis:

### Installation
The analysis code uses the following libraries:

numpy

pandas

matplotlib.pyplot

from sklearn.linear_model import LinearRegression

from sklearn.model_selection import train_test_split

from sklearn.metrics import r2_score, mean_squared_error

import seaborn as sns

from sklearn.model_selection import train_test_split 

from sklearn.linear_model import Ridge

from sklearn import metrics

from sklearn.model_selection import cross_val_score

from sklearn.preprocessing import StandardScaler

from sklearn.model_selection import train_test_split

from sklearn.model_selection import GridSearchCV

%matplotlib inline

### Project Overview:
**Problem domain:**

An analysis on Jupiter on Bitcoin Historical Data.**

**Project origin and dataset:**

The raw data was downloaded directly from djrmarques at Kaggle.

### Strategy:

First, I will preprocess the data, build a model, optimize it, then use it to predict the future price changes. In addition, I will use the hostrical data to answer several questions including:

Can we predict the change % of Bitcoin price tomorrow using the collected data set ?

Is Bitcoin price likely to increase or decrease in the coming years?

Which date had the most trading volume?

How is the trading volume during the Weekends versus Weekday?

Which months during Bitcoin history has the highest increase % and which one has the lowest decrease %?


### File Descriptions
There are two files in the repo:

bitcoin_hist_data.csv: This is the Bitcoin Historical Raw Data.
btc_modeling.ipynb: This is the code written to develop the model, analysis, and to answer the questions.

### How to Interact with your project:
Feel free to use or contribute to my analysis as long as the sources are mentioned in your documentation.

### Acknowledgements:
The raw data was downloaded directly from djrmarques at Kaggle
