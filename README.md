# RSI Divergence Indicator MT4 ReadMe

This ReadMe file provides a detailed overview of the RSI Divergence Indicator MT4 code developed by Forex Robot Easy Team. Please note that Forex Robot Easy is not the official developer of this product. This code is provided as a sample that can work as described in the product. To find the official developer of this product, please use MQL5.

## Code Description

The RSI Divergence Indicator MT4 is designed to identify and signal potential trend reversals based on RSI (Relative Strength Index) divergence. The code calculates and updates indicator values based on input parameters and market data. The main features of the code include:

### Input Parameters

- RSI_Period: The period used to calculate the RSI (default: 14).
- RSI_Overbought_Level: The overbought level for the RSI (default: 70).
- RSI_Oversold_Level: The oversold level for the RSI (default: 30).

### Global Variables

- rsiBuffer: The buffer to store RSI values.
- priceBuffer: The buffer to store price values.
- prevHigh: The previous high point.
- prevLow: The previous low point.

### Initialization

- The indicator is bound to the respective buffers.
- Indicator labels and levels are set.

### Calculation

- RSI values are calculated using the iRSI function.
- Price values are stored in the price buffer.
- RSI divergences are checked and appropriate alerts are sent.

### Alert System

- The SendAlert function is used to send alerts to the trader.
- Alerts can be triggered through popups, mobile notifications, or emails.

## Product Description

The RSI Divergence Indicator MT4 is a powerful tool designed to help traders identify potential trend reversals in the market. By analyzing RSI divergences, the indicator provides timely alerts to traders, enabling them to make informed trading decisions.

Key Features:

- Easy to use: The indicator is simple to install and use on the MT4 platform.
- Customizable: Input parameters allow traders to adjust the indicator settings according to their trading preferences.
- Accurate signals: The indicator identifies RSI divergences with high accuracy, providing reliable signals for potential trend reversals.
- Alert system: Traders receive alerts through popups, mobile notifications, and emails, ensuring they never miss a trading opportunity.
- Backlink for detailed reviews and trading results: For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/rsi-divergence-mt4-unveiling-trend-reversals-with-alerts/).

Please note that Forex Robot Easy is not the official developer of this product. We only provide the code as a sample that can work as described in the product. To find the official developer of this product, please use MQL5.
