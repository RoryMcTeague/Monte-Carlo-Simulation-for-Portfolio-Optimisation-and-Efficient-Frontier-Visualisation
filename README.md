
# Monte Carlo Simulation for Portfolio Optimization and Efficient Frontier

This repository implements a Monte Carlo simulation to model and visualize the **Efficient Frontier** of portfolio optimization. The simulation generates thousands of random portfolios with varying asset weights and calculates their returns, volatilities, and Sharpe ratios. The resulting portfolios are visualized in a scatter plot, with the efficient frontier highlighted as the optimal portfolios offering the highest returns for each level of risk (volatility). 

## Key Features:
- Generation of 10,000 random portfolios.
- Calculation of portfolio performance metrics: return, volatility, and Sharpe ratio.
- Identification and visualization of the efficient frontier.
- Interactive plots using **Matplotlib** to display risk-return trade-offs and Sharpe ratio distributions.

This project is ideal for understanding the principles of Modern Portfolio Theory (MPT) and the trade-offs between risk and return when optimizing a portfolio.

## Installation

To run the code, make sure you have the necessary dependencies installed. You can install them using:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/portfolio-optimization.git
    ```
2. Run the Python script to generate the portfolio simulation and efficient frontier visualization.
3. The plot will display a scatter plot with the efficient frontier line.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

