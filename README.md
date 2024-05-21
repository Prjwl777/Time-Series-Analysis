## Analyzing Temporal Data Trends Using Exponential Smoothing

Welcome to the follow-up repository for my seminar on "Analyzing Temporal Data Trends Using Exponential Smoothing." This project extends our exploration into time series analysis, focusing on the application of ARIMA (AutoRegressive Integrated Moving Average) models for predicting stock prices of Tesla and Microsoft.

Some slides from my presentation as provided below.

<img width="781" alt="Screenshot 2024-05-21 at 12 12 36 PM" src="https://github.com/Prjwl777/Time-Series-Analysis/assets/143058960/1d993c8c-d14b-44ef-bb2e-af6422fd739b">

<img width="774" alt="Screenshot 2024-05-21 at 12 12 59 PM" src="https://github.com/Prjwl777/Time-Series-Analysis/assets/143058960/0bf43825-aa09-40f8-a03e-0daf12f76d5d">

<img width="782" alt="Screenshot 2024-05-21 at 12 13 12 PM" src="https://github.com/Prjwl777/Time-Series-Analysis/assets/143058960/b3cb065b-bc7c-43b9-b5f7-73a668ef1bab">

<img width="709" alt="Screenshot 2024-05-21 at 12 13 29 PM" src="https://github.com/Prjwl777/Time-Series-Analysis/assets/143058960/3c469448-5acf-4023-917d-927e5119a8c1">

<img width="738" alt="Screenshot 2024-05-21 at 12 13 39 PM" src="https://github.com/Prjwl777/Time-Series-Analysis/assets/143058960/bf815d8d-9d08-40b9-9aa8-47eb8cba4bd5">





### Aim and Objective
The aim of this project is to perform a comprehensive analysis and time series prediction of Tesla and Microsoft stock prices using the ARIMA model. The objective is to preprocess the data, analyze stock market trends, and forecast future stock prices to provide insights into the performance and potential investment opportunities for these two technology giants.

### Description of the Datasets
The datasets contain historical stock price data for Microsoft and Tesla. Each dataset includes the following attributes: Date (trading date), Open (opening price), High (highest price during the trading session), Low (lowest price during the trading session), Close (closing price), Volume (number of shares traded), and OpenInt (open interest, which is always zero in these datasets). The Microsoft dataset starts from March 13, 1986, capturing the company's long-term market performance, while the Tesla dataset begins on June 28, 2010, reflecting its market activity since its IPO. This data will be used for analysis and forecasting of stock prices to gain insights into the financial trends of these companies.

### Notebook Outline

1. **Importing Libraries:**
   - Load necessary libraries for data analysis and visualization.
   
2. **Preprocessing:**
   - Clean and prepare the data for analysis by handling missing values and formatting dates.

3. **Tesla Stock Market Analysis:**
   - Analyze historical stock price trends and patterns for Tesla.
   
4. **Tesla ARIMA Time Series Prediction:**
   - Implement ARIMA model to predict future Tesla stock prices.

5. **Microsoft Stock Market Analysis:**
   - Analyze historical stock price trends and patterns for Microsoft.

6. **Microsoft ARIMA Time Series Prediction:**
   - Implement ARIMA model to predict future Microsoft stock prices.

### Interpretation and Conclusion

**Tesla Stock Market Analysis:**
- The dataset covers Tesla's stock prices from its IPO on June 28, 2010, to November 10, 2017.
- Visualizing Tesla's stock prices shows significant fluctuations, typical for a growth-phase company.
- The ARIMA model (order=(5,1,0)) was used for prediction, achieving an MSE of 40.550 and a SMAPE of 26.015%.

**Microsoft Stock Market Analysis:**
- The dataset spans from March 13, 1986, to November 10, 2017.
- Microsoft's stock prices show a steady upward trend over the long term.
- The ARIMA model (order=(5,1,0)) was used for prediction, achieving an MSE of 0.343 and a SMAPE of 40.776%.

These analyses demonstrate the utility of ARIMA models in forecasting stock prices, providing valuable insights into the financial trends of Tesla and Microsoft.
