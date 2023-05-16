# Stock Price Prediction Project

## Description
* This project is a stock price prediction model that uses linear regression to predict the closing price of a given stock. 
* The model is trained on the history of the data and evaluated on the a portion to determine its accuracy.
* The model acquires an accuracy of 90-99%
## Usage
### Get API key
Get an API key from https://www.alphavantage.co/support/#api-key.

### Get the symbol ticket
Choose the symbol ticket for the stock you want to predict from https://finance.yahoo.com or https://www.google.com/finance/.

### Download and run the jupiter notebook
1. Download the Jupyter notebook file stock-price-prediction.ipynb from this repository.
2. Open the downloaded file in Jupyter Notebook.
3. Replace the api_key variable with your API key in the code cell that imports data from Alpha Vantage.
4. Replace the symbol variable with your desired stock symbol in the code cell that imports data from Alpha Vantage.
5. Run the notebook cells to see the data visualization and perform feature engineering and linear regression modeling.
6. To predict the stock price for a specific date, modify the end_date_str variable in the notebook and run the appropriate cells.
