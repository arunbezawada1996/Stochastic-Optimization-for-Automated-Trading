
# Stochastic Optimization for Automated Trading

## Summary

This project implements a high-frequency trading system using stochastic optimization techniques. It focuses on dynamically reallocating capital across S&P 500 stocks in 15-minute intervals throughout the trading day. The objective is to enhance trading performance by making real-time decisions based on market data while adhering to portfolio constraints.

## Objectives

- Design a stochastic model to represent market uncertainty.
- Develop an algorithm that rebalances portfolios at high frequency.
- Implement constraints to ensure practical and regulatory compliance.

## Key Components

### Data Acquisition
- Collect high-frequency data (price, volume, etc.) for S&P 500 assets.
- Real-time data ingestion is critical for timely decision-making.

### Modeling
- Use stochastic processes to simulate market dynamics.
- Assess risk and return profiles under uncertain conditions.

### Algorithm Development
- Employ stochastic optimization to determine asset allocations.
- Optimize for risk-adjusted returns or minimum variance portfolios.

### Constraints
- **Capital Constraint**: Investment must not exceed available funds.
- **Asset Holding Limits**: Restrictions on maximum and minimum positions.
- **Transaction Costs**: Account for costs associated with frequent trading.
- **Rebalancing Frequency**: Limited to specific intervals (e.g., every 15 minutes).

## Technologies Used

- Python
- NumPy, Pandas
- CVXPY or PyPortfolioOpt (for optimization)
- Matplotlib/Plotly (for visualization)
- Jupyter Notebook

## References

1. Birge, J.R., & Louveaux, F. (2011). *Introduction to Stochastic Programming*. Springer. [Link](https://link.springer.com/book/10.1007/978-1-4614-0237-4)
2. Shapiro, A., Dentcheva, D., & Ruszczyński, A. (2014). *Lectures on Stochastic Programming: Modeling and Theory*. SIAM. [Link](https://epubs.siam.org/doi/book/10.1137/1.9781611973441)
3. Fabozzi, F. J., Kolm, P. N., Pachamanova, D. A., & Focardi, S. M. (2007). *Robust Portfolio Optimization and Management*. Wiley. [Link](https://www.wiley.com/en-us/Robust+Portfolio+Optimization+and+Management-p-9780470056190)

## Future Improvements

- Integrate live data feeds (e.g., via Alpaca, IEX Cloud).
- Enhance model robustness with machine learning-based forecasts.
- Implement backtesting over historical data.
- Expand to multi-asset portfolios.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
