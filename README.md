# Trading Bot Configuration

To configure your trading bot, update the following settings in the configuration file:

```json
{
    "api_key": "your_api_key",
    "api_secret": "your_api_secret",
    "symbol": "BTC/USD",
    "initial_balance": 10,
    "risk_per_trade": 1,
    "strategy": "moving_average_crossover",
    "sleep_duration": 60
}

```

## Parameters

- **api_key**: Your API key for accessing the trading platform.
- **api_secret**: Your API secret for accessing the trading platform.
- **symbol**: The trading pair symbol (e.g., BTC/USD).
- **initial_balance**: The initial balance to start trading with.
- **risk_per_trade**: The percentage of the balance to risk per trade.
- **strategy**: The trading strategy to use (e.g., moving_average_crossover).
- **sleep_duration**: The duration (in seconds) to wait between each trading cycle.

Make sure to replace the placeholder values with your actual configuration settings.