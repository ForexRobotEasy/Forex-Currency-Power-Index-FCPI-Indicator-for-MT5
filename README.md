README.md

## FCPI Indicator for MT5

This is a custom indicator for MetaTrader 5 (MT5) developed by Forex Robot Easy Team. It calculates the currency power index based on the selected calculation method.

### Calculation Methods

There are two calculation methods available:

1. Price Power method: This method calculates the currency power based on price movements.
2. ADX Power method: This method calculates the currency power based on the ADX indicator.

### Input Parameters

- CalculationMethod: Allows you to select the calculation method for currency power index.

### Currency Pairs

The indicator supports both major and cross currency pairs. The major pairs include:
- EURUSD
- GBPUSD
- AUDUSD
- NZDUSD
- USDCAD
- USDCHF
- USDJPY

The cross pairs include:
- EURGBP
- EURAUD
- EURNZD
- EURCAD
- EURCHF
- EURJPY
- GBPAUD
- GBPNZD
- GBPCAD
- GBPCHF
- GBPJPY
- AUDNZD
- AUDCAD
- AUDCHF
- AUDJPY
- NZDCAD
- NZDCHF
- NZDJPY
- CADCHF
- CADJPY

### Initialization

During initialization, the indicator initializes all currency pairs by combining major and cross pairs into a single array.

### Custom Indicator Iteration

The `OnCalculate` function is responsible for calculating the currency power index based on the selected calculation method. It receives the necessary price data for each candle and performs the calculation.

### Calculation Methods

The `CalculatePricePower` function calculates the currency power using the Price Power method. You can add your own code in this function to perform the calculation.

The `CalculateADXPower` function calculates the currency power using the ADX Power method. You can add your own code in this function to perform the calculation.

### Usage

To use this indicator, simply add it to your MetaTrader 5 platform and apply it to the desired chart. You can then customize the input parameters and select the calculation method. The indicator will then display the currency power index based on your settings.

Please note that Forex Robot Easy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please refer to the MQL5 website.

For more detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-fcpi-indicator-for-mt5-optimize-forex-trading/).
