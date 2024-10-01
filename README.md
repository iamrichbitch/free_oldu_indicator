# FREE_oldu Indicator (Pine Script)

This is a Pine Script indicator that provides buy and sell signals based on crossover strategies, with additional filtering using RSI and ATR for trend and volatility detection. The indicator also plots trend ribbons, swing points, and allows for various customizations to suit different trading strategies.

## Features

- **Buy & Sell Signals**: Generated based on EMA crossovers with additional sensitivity and trend filtering.
- **Trend Ribbon**: Visual representation of market trends using simple moving averages (SMA).
- **Reversals**: Option to display reversal points.
- **Swing Points**: Detects key swing points in the market.
- **Stop Loss**: Optional stop loss percentage.
- **ATR and RSI Filters**: Filters buy/sell signals based on trend strength and volatility.

## Inputs

### Buy & Sell Signals
- **Show Buy & Sell**: Enable or disable buy and sell signals.
- **Sensitivity (1-6)**: Adjust the sensitivity of the buy/sell signals (higher = more sensitive).
- **Stop Loss %**: Set a stop loss percentage to protect your trades.
- **Signals Offset**: Adjust the offset of the signals to fine-tune their position on the chart.

### Trend Ribbon
- **Show Trend Ribbon**: Display or hide the trend ribbon.
- **Smoothing 1 & Smoothing 2**: Adjust the smoothing values for the trend ribbon.

### Reversal Signals
- **Show Reversals**: Enable or disable reversal signal plotting.

### Previous Day High/Low/Close
- **Show P.D H/L/C**: Display or hide the previous day’s high, low, and close.
- **Line Colors, Width, and Style**: Customize the appearance of these lines.

### EMA Settings
- **Show EMAs**: Toggle the display of Exponential Moving Averages (EMAs).
- **EMA 1, EMA 2, EMA 3**: Set the lengths of three different EMAs for the crossover signals.

### Swing Points
- **Show Swing Points**: Enable or disable the display of swing points.
- **Swing Point Period**: Adjust the period used to detect swing points.
- **Positive/Negative Swing Color**: Customize the color of the swing points.

### Trend Filters
- **Use RSI for Trend Filtering**: Use the RSI (Relative Strength Index) to filter signals based on the strength of the trend.
- **RSI Period**: Set the period for RSI calculation.
- **RSI Overbought/Oversold Levels**: Define overbought and oversold levels for filtering signals.

- **Use ATR for Volatility Filtering**: Use ATR (Average True Range) to filter signals based on market volatility.
- **ATR Period**: Set the period for ATR calculation.
- **ATR Multiplier**: Define the multiplier to adjust the sensitivity of the volatility filter.

## Alerts

The script includes several built-in alert conditions that can be used to trigger notifications based on various signals:

- **Ribbon Crossover**: Alerts when the blue and red trend ribbons cross.
- **Buy Signal**: Alerts when a buy signal is triggered.
- **Sell Signal**: Alerts when a sell signal is triggered.
- **Filtered Buy Signal**: Alerts when a buy signal passes the trend and volatility filters.
- **Filtered Sell Signal**: Alerts when a sell signal passes the trend and volatility filters.

## How to Use

1. **Add the Indicator**: Copy the script into the Pine Script editor on TradingView and add it to your chart.
2. **Customize Settings**: Adjust the various settings to suit your trading strategy. The defaults provide a balanced strategy, but customization is encouraged.
3. **Set Alerts**: Configure alerts using the provided alert conditions to receive notifications for key buy/sell opportunities.
4. **Monitor the Chart**: Observe the buy and sell signals, trend ribbon, swing points, and any reversals on your chart.

## License

This script is for educational and personal use only. Always use appropriate risk management when trading live markets.

