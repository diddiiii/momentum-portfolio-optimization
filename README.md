# Momentum-Based Multi-Asset Portfolio Construction & Risk Analysis
This project analyzes a multi-asset portfolio consisting of equities, bonds, commodities, and foreign exchange. It compares an equal-weighted portfolio with a 60-day momentum-based dynamic allocation strategy and evaluates their performance and risk characteristics using Python.

## My Contribution
#### This was a group project. I was responsible for Part 1B (Portfolio Construction) and Part 1C (Risk Measures), including the Python implementation, quantitative analysis, and data visualizations.

- Portfolio Construction & Performance Analysis: Constructed and evaluated a five-asset portfolio across equities, bonds, commodities, and FX, comparing a 20% equal-weighted portfolio with a 60-day momentum-based dynamic allocation strategy.

- Momentum-Based Dynamic Allocation: Developed a dynamic weighting approach based on 60-day historical momentum signals and used prior-period portfolio weights to calculate returns, avoiding the use of future information.

- Performance Evaluation: Calculated and compared annualized returns, annualized volatility, cumulative returns, and 60-day rolling volatility across the two portfolio strategies.

- Data Visualization: Created Python visualizations for asset momentum, dynamic portfolio weights, cumulative performance, and rolling volatility to illustrate changes in portfolio allocation and performance over time.

- Risk-Return Comparison: Compared the two strategies and found that the momentum-based portfolio achieved higher returns, while also exhibiting higher volatility and greater concentration in selected assets.

- Monte Carlo Simulation & VaR Analysis: Conducted 100,000-scenario Monte Carlo simulations and estimated Value at Risk (VaR) at the 95% and 99% confidence levels to compare downside and tail-risk exposure between the two strategies.

- Model Limitations: Discussed key limitations of the risk model, including the normality assumption, reliance on historical parameters, and VaR's inability to measure the severity of losses beyond the selected confidence threshold.
