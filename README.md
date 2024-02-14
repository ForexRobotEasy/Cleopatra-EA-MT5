# Cleopatra EA MT5 ReadMe

This code implements the necessary trade functions and features for Cleopatra EA MT5, an adaptable and innovative Forex trading software developed by Forex Robot Easy Team. For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Cleopatra EA MT5 Review](https://forexroboteasy.com/forex-robot-review/cleopatra-ea-mt5-review-adaptable-forex-trading-software/). Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

## Features

- Trading strategies implementation
- Automated trading functionality
- Risk management capabilities

## Dependencies

This code utilizes the following libraries and dependencies:

- Trade.mqh
- Risk.mqh

## Global Variables

- `CTrade trade` - Instance of the CTrade class for trade execution
- `CRisk risk` - Instance of the CRisk class for risk management

## Main Function

The main function, `OnTick()`, reads market conditions and makes trading decisions based on the current price. It sets the stop loss and take profit levels and calculates the lot size using risk management rules. Finally, it executes the trade using the `Buy()` function.

## Trade Class Implementation

The `CTrade` class contains the implementation for trade execution. The `Buy()` function is responsible for executing a buy order with the specified volume, symbol, price, stop loss, and take profit levels.

## Risk Class Implementation

The `CRisk` class handles risk management. The `CalculateLotSize()` function calculates the lot size based on the account balance and a predetermined risk percentage (2% in this case). It assumes 1 lot is equal to 100,000 units.

Please refer to the official developer documentation for more details on the implementation and usage of Cleopatra EA MT5.
