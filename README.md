# Bitcoin Trading Strategy Simulation

This repository contains a Python script for simulating a Bitcoin trading strategy based on historical price data. The strategy involves buying Bitcoin on Saturdays and selling it on Wednesdays. The script uses data from Yahoo Finance to backtest the strategy starting from January 1, 2019.

## Overview
**The script performs the following steps:**


* **Data Download:** Fetches Bitcoin historical price data (BTC-USD) from Yahoo Finance starting from January 1, 2019.

* **Data Preprocessing:**
Filters the data to include only Saturdays and Wednesdays.
Calculates the next day's high and close prices.

* **Strategy Simulation:**
Buys Bitcoin with an initial balance of $1000 on Saturdays.
Sells the Bitcoin on Wednesdays, and calculates the new balance.
Repeats the process for each week.

* **Alternative Calculation (Optional):**
The script also includes an option to calculate the potential maximum profit by using the highest price (High) on Wednesdays instead of the closing price (Close).
This allows the user to understand how much profit could have been made under the best possible scenario.

* **Results Visualization:**
Plots the portfolio value in USD and the equivalent amount of Bitcoin over time.


## Results Interpretation

* The first plot shows how the portfolio's value in USD changes over time based on the strategy.
* The second plot shows how the amount of Bitcoin held in the portfolio fluctuates over time.
* The alternative calculation using the High prices can be used to compare and understand the potential maximum profit versus the actual profit based on closing prices.

## Contributing

We welcome contributions to enhance this project. To contribute, please follow these steps:

* Fork the repository.
* Create a new branch with your changes.
* Commit your changes and push to the branch.
* Open a Pull Request.

## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License. See the `LICENSE` file for more details.
