Clean and Merge
0. Raw data of coins is from https://www.kaggle.com/georgezakharov/historical-data-on-the-trading-of-cryptocurrencies

CoinsDataCleaning.ipynb
1. Delete extra columns in the data source
2. Select the digital currency price changes and other data during COVID-19 according to the 'trade_date' column.
3. Save the result in a new csv file

MergeCoinDataAndCase.ipynb
4. Merge the processed coin date with the COVID-19 information through datetime
