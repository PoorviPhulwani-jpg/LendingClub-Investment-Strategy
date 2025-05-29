# LendingClub Investment Strategy
A data-driven portfolio optimization project leveraging peer-to-peer loan data from LendingClub to develop a risk-aware investment strategy. This project uses clustering, regression modeling, and Sharpe ratio analysis to construct a diversified loan portfolio with an expected return of 4.42%.

## Objective
To maximize investment returns while managing credit risk by identifying borrower segments and designing a portfolio that balances risk and reward.

## Key Insights
- Used K-Means clustering to group borrowers into 7 distinct risk profiles.
- Assigned risk levels using the standard deviation of predicted returns from Ridge regression.
- Developed portfolio strategies based on Sharpe ratios, return thresholds, and risk profiles.
- Final 100-loan portfolio delivered a 4.42% expected return — outperforming all benchmark strategies.

## Tools & Technologies
- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)
- **Machine Learning**: Ridge Regression, Logistic Regression, K-Means Clustering
- **Optimization**: Sharpe Ratio, Return-Risk tradeoff modeling
- **Data Source**: LendingClub loan data (public dataset)

## Project Structure

## Results
| Strategy | Avg Return | Risk (Std Dev) | Sharpe Ratio |
|----------|------------|----------------|---------------|
| Final Portfolio | 4.42% | Balanced | Highest |

## Business Value
This project simulates how a data analyst or investment strategist could segment risk, quantify return, and guide real-world lending decisions using statistical models — making it highly relevant to finance, asset management, and risk teams.

## Contact
For questions or collaboration opportunities, reach out via [LinkedIn](https://linkedin.com/in/poorviphulwani) or email at **pphulwan@tepper.cmu.edu**.
