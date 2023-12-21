# Neowave Chart Plotter

Neowave Chart Plotter is an expert advisor that plots a wave chart based on the NeoWave method and generates trading signals based on this chart. This expert advisor is developed by the Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com).

## Functionality

The Neowave Chart Plotter expert advisor performs the following actions:

1. Includes the necessary Trade library.
2. Defines constants, such as the number of supported timeframes and the ENUM_TIMEFRAMES enumeration.
3. Initializes variables, including the trade object, current symbol index, and current timeframe index.
4. Implements the `OnTick` event function, which is triggered on every tick.
   - Checks if the current symbol and timeframe are valid.
   - Retrieves the current high and low prices.
   - Calls the `PlotWaveChart` function to plot the wave chart.
   - Calls the `CheckTradingSignal` function to check for a trading signal.
   - Places a trade if a trading signal is generated.
5. Implements the `PlotWaveChart` function, which plots the wave chart based on the NeoWave method. (The code for this function is not provided and should be implemented by the user.)
6. Implements the `CheckTradingSignal` function, which checks for a trading signal based on the NeoWave method. (The code for this function is not provided and should be implemented by the user.)
7. Implements the `OnChartEvent` event function, which is triggered when a chart event occurs.
   - Checks if a new symbol is selected and updates the current symbol index accordingly.
   - Checks if a new timeframe is selected and updates the current timeframe index accordingly.
8. Implements the `GetTimeframeIndex` function, which returns the current timeframe index based on the ENUM_TIMEFRAMES enumeration.
9. Implements the `OnInit` function, which is called during expert advisor initialization.
   - Sets initial values for variables.
   - Allows trading operations by setting the expert magic number.
   - Subscribes to chart events.
10. Implements the `OnDeinit` function, which is called during expert advisor deinitialization.
   - Unsubscribes from chart events.

## Product Description

Neowave Chart Plotter is an expert advisor that combines the power of the NeoWave method with automated trading. It plots a wave chart based on the NeoWave method and generates trading signals based on this chart.

The NeoWave method is a technical analysis approach that aims to identify and predict market trends. By plotting the wave chart, this expert advisor provides a visual representation of the market dynamics, allowing traders to make informed trading decisions.

Key Features:
- Plots wave chart based on the NeoWave method.
- Generates trading signals based on the wave chart.
- Supports multiple timeframes: Yearly, Monthly, and Weekly.
- Easy to use and customizable.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product and for detailed reviews and trading results, please visit the [Neowave Chart Plotter - Unbiased Review and Real Results](https://forexroboteasy.com/forex-robot-review/neowave-chart-plotter-unbiased-review-and-real-results/) page on forexroboteasy.com or use the MQL5 platform.
