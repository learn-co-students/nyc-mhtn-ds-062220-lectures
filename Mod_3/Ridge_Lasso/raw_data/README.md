# Raw Data

This directory will store raw data related to this project.

* `advertising.csv` comes from [An Introduction to Statistical Learning with Applications in R (ISLR)](http://faculty.marshall.usc.edu/gareth-james/ISL/)
* `social_network_ads.csv` comes from the [Logistic Regression](https://www.kaggle.com/dragonheir/logistic-regression/downloads/logistic-regression.zip/1) kernel on Kaggle.
* `all_stocks_5yr.csv` comes from [S&P 500 stock data](https://www.kaggle.com/camnugent/sandp500) kernel on Kaggle. Please note that this `.csv` will not be found inside of `raw_data/` because it is too large to live on GitHub. However, you will find a modified copy of this `.csv` file in `write_csv/all_stocks_5yr.pkl`. The only difference between the two files is that the `date` feature was changed from `YYYY-MM-DD` format to `Month DD, YYYY` format.

