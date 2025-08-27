# TCS Stock Market Analysis (2020–2025)

## Project Overview
This project focuses on analyzing the stock price trends of Tata Consultancy Services (TCS) from 2020 to 2025. The analysis includes exploratory data analysis (EDA), statistical modeling, and machine learning approaches for time series forecasting. Various forecasting models are compared to evaluate their performance.

## Objectives
- Perform exploratory data analysis (EDA) on TCS stock data.
- Apply statistical and machine learning models for stock price forecasting.
- Compare ARIMA, SARIMA, Prophet, and LSTM models.
- Visualize stock price trends and forecast results.

## Dataset
- **Source**: TCS stock data from 2020 to 2025 (CSV format).
- **Features**: Date, Open, High, Low, Close, Volume, etc.

## Models Used
1. **ARIMA** – Autoregressive Integrated Moving Average for time series forecasting.
2. **SARIMA** – Seasonal ARIMA to capture seasonality patterns.
3. **Prophet** – Forecasting model developed by Facebook, suitable for daily observations with trend and seasonality.
4. **LSTM** – Long Short-Term Memory neural network for sequential data prediction.

## Project Workflow
1. Data preprocessing and cleaning.
2. Exploratory Data Analysis (EDA).
3. Model training and evaluation:
   - Train ARIMA, SARIMA, Prophet, and LSTM.
   - Compare results using performance metrics (RMSE, MAE, R²).
4. Visualization of actual vs predicted stock prices.

## Results
- Comparative performance of models was evaluated.
- Strengths and weaknesses of statistical vs deep learning models were highlighted.
- Visualizations clearly showed forecasting trends and residuals.

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Statsmodels
- Prophet
- TensorFlow / Keras (for LSTM)
- Jupyter Notebook

## Files
- `Stock Market Analysis – TCS (2020–2025).html` : Exported notebook (view results directly in browser).  
- `Time series stock market_20250417_183146_0000.pdf` : Report summarizing analysis and results.  
- `tcs_data.csv` : Dataset file (if included).  

⚠️ **Note**: The original `.ipynb` Jupyter Notebook file is missing. Due to technical errors while recreating it, only the `.html` version is uploaded. Please open the HTML file in a browser to view the complete notebook with code, outputs, and visualizations.

## Future Enhancements
- Integrate real-time stock market APIs.
- Build an interactive dashboard for live visualization.
- Extend forecasting horizon beyond 2025 with updated data.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/TCS-Stock-Market-Analysis-2020-2025.git
   cd TCS-Stock-Market-Analysis-2020-2025
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the HTML file in any browser to explore results:
   ```bash
   open "Stock Market Analysis – TCS (2020–2025).html"
   ```

## Author
Mohan Narayanapuram
