# Portfolio Management and Optimization

## Overview

This project focuses on portfolio management and optimization using historical stock data. It utilizes the `yfinance` library to download stock data and the `riskfolio-lib` library to perform various portfolio optimization techniques, including Mean-Variance and Mean-CVaR optimization. The project also includes a comparison of the optimized portfolio's performance against a benchmark (Nifty 50).

## Functionality

The project performs the following steps:

1.  **Data Retrieval:** Downloads historical adjusted closing prices for a list of stocks and a benchmark index (Nifty 50) from Yahoo Finance.
2.  **Data Preparation:** Calculates daily returns and handles missing values in the data.
3.  **Mean-Variance Optimization:**
    *   Calculates asset statistics (mean returns and covariance matrix).
    *   Optimizes the portfolio to maximize the Sharpe Ratio using the Mean-Variance model.
    *   Visualizes the portfolio composition using a pie chart.
    *   Calculates and plots the efficient frontier.
4.  **Mean-CVaR Optimization:**
    *   Optimizes the portfolio to maximize the Return/CVaR ratio using the Mean-CVaR model.
    *   Visualizes the portfolio composition using a pie chart.
    *   Calculates and plots the efficient frontier.
5.  **Comparison of Risk Measures:** Compares optimal portfolios based on various risk measures (MV, MAD, MSV, FLPM, SLPM, CVaR, EVaR, WR, MDD, ADD, CDaR, UCI, EDaR).
6.  **Building Constraints:** Demonstrates how to build and apply constraints on asset classes during portfolio optimization.
7.  **Portfolio Comparison:** Compares the cumulative returns of the optimized portfolio against the Nifty 50 benchmark.

## Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/git098/Portfolio-Management.git
    cd Portfolio-Management
    ```

2.  **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Run the Jupyter Notebooks:**

    *   Open `Portfolio_Optimisation.ipynb` and `Portfolio_Management.ipynb` using Jupyter Notebook or JupyterLab.
    *   Run the cells in the notebooks to perform portfolio analysis and optimization.
2.  **Modify Stock List and Date Range:**
    *   Update the `stocks` list and the `start_date` and `end_date` variables in the notebooks to analyze different stocks and time periods.

## Requirements

*   Python 3.6+
*   `numpy`
*   `pandas`
*   `yfinance`
*   `matplotlib`
*   `riskfolio-lib`

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.
