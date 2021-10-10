# Analysis-of-Cryptocurrencies
Project for the Data Analysis Course

Team Name: Bits_Please
Team Members: Vibha Kurpad (PES1201800158)
Shreya Sri (PES1201800132)
Mahah Sadique (PES1201801529)

-------------------------------------------------------------------------------------------------------------------------------------------
## AIM
Our aim is to conduct a thorough analysis of cryptocurrencies. From a technical point of view as well as from a financial and social point of view.
We have studied the impacts of various Global events on Bitcoin prices. We have found that the very recent global pandemic has had an impact on 
Bitcoin prices. Prices dropped as many people started liquidating their assets. In our report an evident spike is seen between
mid 2017 to 2018 .Prices soared by a whopping 1,813 percent . What caused this sudden spike ? A whale .According to research a single whale – which is 
someone who holds large quantities of bitcoins , was behind the iconic rise . We also explored techniques to predict Bitcoin prices. The techniques 
explored were Simple Moving Average, Exponential Smoothing as well as ARIMA models. Amongst all 3, the ARIMA model gave the best results.

-------------------------------------------------------------------------------------------------------------------------------------------
## FILES:

- 13_Bits_please-Stage1.pdf : The initial report which contains our findings of previous work done and the problem statement we wish to address.

- ARIMA.ipynb: Documented code which contains the process of model builing along with some visualizations.

- bitcoin_price.csv: Part of our dataset. It contains the Bitcoin prices (open,close,high and low) along with the date, volume and market cap.

- bitcoin.ipynb: The pre-processing file that outputs the cleaned dataset.

- ethereum_price.csv: Part of our dataset. It contains the Ethereum prices (open,close,high and low) along with the date, volume and market cap.

- ethereum.ipynb: The pre-processing file that outputs the cleaned dataset.

- exponential_smoothing.ipynb: This notebook explores forecasting bitcoin prices using exponential smoothing methods.

- ripple_price.csv: Part of our dataset. It contains the Ripple prices (open,close,high and low) along with the date, volume and market cap.

- ripple.ipynb:The pre-processing file that outputs the cleaned dataset.

- SMA.ipynb: Documented code which contains the Simple Moving Average Technique.

- Stock-taking_of_data.docx: Document containing in detail, the process of data cleaning and data preprocessing, with visualizations of boxplots.

- Stock-taking_of_data.pdf: Stock-taking_of_data.docx in pdf form.

-------------------------------------------------------------------------------------------------------------------------------------------
## USER GUIDE:
Save all the notebooks (and associated csv files) in the same directory.
Make sure to have all the required modules provided in requirements.txt file.
Simply run each cell using the preferred python notebook interface.

To install the required modules:
	`Using pip: pip install -r requirements.txt`
 
-------------------------------------------------------------------------------------------------------------------------------------------
## JUPYTER NOTEBOOKS:

1. Exponential_smoothing.ipynb: 

ASSOCIATED FILES:
bitcoin_price.csv: Original bitcoin prices dataset (Included in bitcoin.ipynb)
bitcoin.ipynb: The pre-processing file that outputs the cleaned dataset.

This notebook contains a bitcoin prices analysis along with the following:
Decomposition of the time series data
Implementing Simple exponential smoothing and plotting the results.
Implementing Double exponential smothing (Holt's method) and plotting the results.
Implementing Triple exponential smoothing (Holt-Winters method) and plotting the results.
Error percentages of the predictions using MAPE.

2. SMA.ipynb:

ASSOCIATED FILES:
bitcoin_price.csv: Original bitcoin prices dataset (Included in bitcoin.ipynb)
bitcoin.ipynb: The pre-processing file that outputs the cleaned dataset.

This notebook contains a bitcoin prices analysis along with the following:
Implementing Simple Moving Average with window of size 3.
Implementing Simple Moving Average with window of size 4.
Plotting the results against the actual data.
Error predictions using MSE.
Implementing Simple Moving Average with window of size 50.
Implementing Simple Moving Average with window of size 10.
Implementing Simple Moving Average with window of size 15.
Implementing Simple Moving Average with window of size 20.
Error predictions using MSE.

3. ARIMA.ipynb:

ASSOCIATED FILES:
bitcoin_price.csv: Original bitcoin prices dataset (Included in bitcoin.ipynb)
bitcoin.ipynb: The pre-processing file that outputs the cleaned dataset.

This notebook contains a bitcoin prices analysis along with the following:
Plot the close prices of Bitcoin.
Plot the candlestick plot for Bitcoin.
Performing the Dickey Fuller test to check if data is stationary.
Plotting Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots.
Fitting the model with p,d and q parameters.
Error Predictions using MSE.
Box-Cox transform and Q-Q Plot transform.
