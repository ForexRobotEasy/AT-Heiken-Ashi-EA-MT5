# AT Heiken Ashi EA MT5

This is an Expert Advisor (EA) code for the MT5 platform that is designed to trade using the Heiken Ashi indicator. The EA is developed by Forex Robot Easy Team and more information about the product can be found at [forexroboteasy.com](https://www.forexroboteasy.com).

## Input Parameters

The EA has the following input parameters:

- `signalCandles` (default: 3): Number of consecutive candles required to generate a trading signal.
- `lotSize` (default: 0.1): Lot size for trading.
- `enableTrailingStop` (default: true): Enable or disable trailing stop.
- `trailingStop` (default: 50): Trailing stop value in points.

## Initialization Function

The `OnInit()` function is called during the initialization of the EA. It is used to initialize variables or set default values.

## Deinitialization Function

The `OnDeinit()` function is called when the EA is being removed. It is used to perform any necessary cleanup or actions before the EA is removed.

## Start Function

The `OnTick()` function is the main function of the EA that is called on each tick. It loops through all currency pairs and checks if the current chart is of the desired timeframe. It then retrieves the Heiken Ashi indicator values and checks if the number of consecutive candles with the same color has been reached. If the conditions for opening a trade are met, it opens a buy or sell trade accordingly.

## Helper Functions

The EA includes several helper functions:

- `CountConsecutiveCandles()`: This function counts the number of consecutive candles with the same color.
- `IsBullishCandle()`: This function checks if the current candle is bullish.
- `IsBearishCandle()`: This function checks if the current candle is bearish.
- `OpenBuyTrade()`: This function is used to open a buy trade.
- `OpenSellTrade()`: This function is used to open a sell trade.

## Product Description

AT Heiken Ashi EA MT5 is a professional Forex trading strategy that utilizes the Heiken Ashi indicator. It is designed to generate trading signals based on the number of consecutive candles with the same color. The EA is highly customizable with input parameters for signal candles, lot size, and trailing stop.

This EA is suitable for both beginner and experienced traders who want to automate their trading strategy using the Heiken Ashi indicator. It provides a reliable and systematic approach to trading in the Forex market.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that demonstrates how this product can work. For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-at-heiken-ashi-ea-mt5-a-professional-forex-traders-strategy-for-successful-trades/). To find the official developer of this product, please use the MQL5 website.
