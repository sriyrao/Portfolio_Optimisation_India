itle: Portfolio Optimization of Indian Equities using the Markowitz Efficient Frontier
By: Srivatsa Yesentarao

This project applies the foundational principles of Modern Portfolio Theory (MPT) to a real-world Indian equity portfolio. Using historical data of 10 diversified large-cap stocks (TCS, Infosys, HDFC Bank, ITC, Reliance, etc.), I simulated 100,000 portfolios via Monte Carlo simulation to visualize the Efficient Frontier and identify the optimal risk-return allocation using the Sharpe Ratio as the objective function.

🔍 What I did:

Fetched and cleaned 5 years of historical data using yfinance

Calculated daily and annualized returns, standard deviation, and the covariance matrix

Simulated 100,000 random portfolios using Python

Visualized the Efficient Frontier using matplotlib and interpreted Sharpe Ratio dynamics

Used PyPortfolioOpt to compute the Sharpe-optimal portfolio

Compared the optimal portfolio with an equal-weighted benchmark

Created a detailed analytical report explaining methodology, assumptions, results, and insights

📈 Key Takeaways:

The optimized portfolio achieved a 27.7% expected return with a Sharpe Ratio of 1.35, outperforming the equal-weighted portfolio's Sharpe of 0.99.

Most optimal weights leaned toward Bharti Airtel, Titan, and Infosys, showing favorable return-to-risk profiles.

The entire project is modular and easily extendable for further constraints, ESG filtering, or transaction cost inclusion.

🔧 Tools Used: Python, Pandas, NumPy, Matplotlib, Seaborn, PyPortfolioOpt, yfinance, Databricks

📄 Full report available inside the repo: Portfolio_Optimization_Report_by_Srivatsa_Yesentarao.pdf
