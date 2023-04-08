# MACD + Stochastic Oscillator Trading Strategy
This is a TradingView Pine Script that implements a strategy based on the MACD and Stochastic Oscillator indicators. The strategy generates buy and sell signals based on crossovers of the MACD and Signal Line and the %K and %D lines of the Stochastic Oscillator.

## Indicator Inputs
The following inputs are available for customizing the indicators:

## MACD
- `Fast Length`: the number of periods used to calculate the fast EMA.
- `Slow Length`: the number of periods used to calculate the slow EMA.
- `Signal Length`: the number of periods used to calculate the signal line.
## Stochastic Oscillator
- `K Length`: the number of periods used to calculate the %K line.
- `D Length`: the number of periods used to calculate the %D line.
- `Smooth K`: the number of periods used to smooth the %K line.
- `Smooth D`: the number of periods used to smooth the %D line.
## Buy and Sell Signals
The strategy generates buy signals when the MACD crosses above the Signal Line and the %K line of the Stochastic Oscillator is below 20. It generates sell signals when the MACD crosses below the Signal Line and the %K line is above 80.

Buy and sell signals are plotted on the chart as green triangles pointing up and red triangles pointing down, respectively.

## How to Use
To use this strategy in TradingView, copy the Pine Script and paste it into a new script editor window. Then, click the "Add to Chart" button to apply the strategy to a chart. You can adjust the input values to customize the indicators and analyze the chart.

Please note that this strategy is intended for educational purposes only and should not be used for actual trading without proper backtesting and risk management.

## References
https://www.tradingview.com/pine-script-docs/en/v4/index.html