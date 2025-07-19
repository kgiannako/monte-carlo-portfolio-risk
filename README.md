# monte-carlo-portfolio-risk
Monte Carlo simulations for portfolio VaR and CVaR estimation.

📊 Portfolio Risk Analysis Summary
This project compares portfolio risk metrics estimated using three approaches:

* Monte Carlo Simulation (Normal Distribution)
* Monte Carlo Simulation (t-Distribution)
* Historical Rolling Returns

📝 Key Findings:
1️⃣ Comparison of Risk Estimation Methods
The t-Distribution simulation consistently produced the highest VaR and CVaR estimates, reflecting its ability to capture fat tails and extreme downside risk.

The Normal-based Monte Carlo underestimated tail risks compared to the t-Distribution, especially for market-cap weighted portfolios.

Historical data showed the lowest VaR and CVaR, highlighting that past market behavior may underrepresent potential future extremes.

2️⃣ Comparison Between Portfolio Strategies
The Market Cap Weighted Portfolio exhibited higher simulated risk in both Normal and t-Distribution scenarios, suggesting higher exposure to systemic market downturns.

Conversely, historically, the Equal Weight Portfolio experienced higher risk, likely due to its greater exposure to smaller, more volatile stocks.

This contrast shows how simulation-based risk measures can reveal latent risks not evident in historical performance alone.

**Conclusion**:
The analysis underscores the importance of stress-testing portfolios under different modeling assumptions.
Relying solely on historical data may give a false sense of security, while distribution-aware simulations (especially with fat-tailed models) help uncover potential tail risks.
