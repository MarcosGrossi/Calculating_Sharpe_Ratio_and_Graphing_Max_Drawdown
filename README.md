# Calculating Sharpe Ratio and Graphing Maximum Drawdown

This project focuses on financial analysis of Walmart (WMT) stock by calculating cumulative returns, Sharpe ratio, and drawdown, and visualizing them. 
## Project Overview 📊

The main tasks performed in this project include:

1. **Cumulative Returns Calculation**: Calculates the cumulative returns of WMT, showing the compounded growth of an investment over time.

2. **Maximum Drawdown Analysis**: Calculates and graphs the maximum drawdown, representing the largest peak-to-trough decline in cumulative returns during the analysis period. The notebook includes visual cues (green dashed line) to highlight the exact point where the maximum drawdown occurs.

3. **Rolling Sharpe Ratio Calculation**: Calculates a rolling Sharpe ratio on a monthly basis over a 12-month rolling window to evaluate the risk-adjusted return. The highest Sharpe ratio is marked with a red "x" to easily identify periods with the best risk-adjusted performance.

4. **Graphical Visualization**: Uses `matplotlib` to plot cumulative returns, maximum drawdown, and rolling Sharpe ratio to provide a clear and detailed view of WMT stock's performance.

## Key Metrics Calculated 📈

- **Cumulative Returns**: Shows how an investment grows over time, accounting for compounding effects.
- **Maximum Drawdown**: Indicates the risk of the investment by calculating the largest observed loss from a peak.
- **Rolling Sharpe Ratio**: Evaluates risk-adjusted returns, helping to understand whether returns are due to good investment decisions or excessive risk.

## Files Included 📁

- **Calculating_Sharpe_Ratio_and_Graphing_Max_Drawdown.ipynb**: Jupyter notebook containing all code, analysis, and visualizations.


## Dependencies 📦

To run the notebook, you will need the following Python packages:

- **pandas**: For data manipulation and rolling calculations.
- **yfinance**: For downloading stock data.
- **matplotlib**: For visualizing the data.
- **numpy**: For numerical operations (optional, if used for calculations).

You can install the dependencies using the following command:

```sh
pip install pandas matplotlib numpy yfinance
```

## Usage 🚀

1. **Clone the Repository**:
   
   ```sh
   git clone <(https://github.com/MarcosGrossi/Calculating_Sharpe_Ratio_and_Graphing_Max_Drawdown)>
   ```

2. **Open the Notebook**:
   
   Navigate to the project directory and open the Jupyter notebook:
   
   ```sh
   jupyter notebook Calculating_Sharpe_Ratio_and_Graphing_Max_Drawdown.ipynb
   ```

3. **Run the Cells**:

   Execute each cell in the notebook to perform calculations and view the visualizations.

## Visual Insights 🖼️

- The **cumulative returns** plot shows the growth of investment in WMT over the analysis period.
- The **maximum drawdown** graph, with a green dashed line highlighting the point of maximum loss, helps assess risk exposure.
- The **rolling Sharpe ratio** plot helps identify periods of high or low risk-adjusted performance, with the best ratio highlighted using a red "x".

## Contributing 🤝

Feel free to fork this project, submit issues, or create pull requests if you have any suggestions or improvements.
