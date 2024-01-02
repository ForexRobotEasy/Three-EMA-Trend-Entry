# Three EMA Trend Entry

This code is a trading strategy that utilizes three Exponential Moving Averages (EMA) to identify optimal entry points in the market. It is designed for use in the MQL5 platform.

## Input Parameters
- EMA200_Period: The period for the 200 EMA.
- EMA32_Period: The period for the 32 EMA.

## Global Variables
- prevSwingHigh: Stores the value of the previous swing high.
- prevSwingLow: Stores the value of the previous swing low.
- buySignal: Boolean variable indicating a buy entry signal.
- sellSignal: Boolean variable indicating a sell entry signal.

## Initialization
The OnInit() function is called when the program starts. It sets up the indicator buffers and initializes the prevSwingHigh and prevSwingLow variables.

## Trading Function
The OnTick() function is called on each tick of the market. It calculates the EMAs using the input parameters and checks for buy and sell entry signals based on the EMA values and price action. If a buy or sell signal is detected, the corresponding signal variable is set to true and the prevSwingHigh or prevSwingLow is updated. A comment is also printed to the chart to indicate the entry signal.

## Program Execution
The start() function is called to execute the trading function. In this case, it calls the OnTick() function.

**Note: ForexRobotEasy is not the official developer of this product. We only provide the sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.**

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/three-ema-trend-entry-review-forex-software-for-optimal-entries/).
