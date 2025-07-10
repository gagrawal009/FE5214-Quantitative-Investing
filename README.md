# FE5214 - Quantitative Investing

This repository contains all assignments and the group project submitted for **FE5214 Quantitative Investing**, a course in the Master of Science in Financial Engineering program at the National University of Singapore (NUS).

## 📚 Course Overview

The course focuses on data-driven approaches to systematic investing. Topics include:
- Factor-based investing (e.g., Fama-French models)
- Portfolio construction and optimization
- Backtesting and performance evaluation
- Machine learning applications in finance

## 📂 Repository Structure

- Each assignment is organized in its own folder, containing questions, code, data (if applicable), and documentation or reports.
- /Project: Group project on ML-based portfolio construction using Fama-French factors


## Assignments

**Assignment 1 – Industry Analysis and Return Regression**
Analyzed GICS sector/industry compositions and market capitalizations in the S&P 500 (2014 vs. 2024). Conducted return regression of NVIDIA against its peer industry index using both equal-weighted and market-cap-weighted methods.

**Assignment 2 – Alpha Factor and Long-Short Portfolio**
Created a return-predictive alpha factor using 5-day momentum normalized by 21-day volatility and adjusted for industry effect. Evaluated significance using cross-sectional regressions and built a long-short portfolio strategy with backtested annual returns and Sharpe ratios (with/without trading costs).

**Assignment 3 – Multi-Asset Portfolio Optimization**
Downloaded and used historical returns (2000–present) for U.S. equities, bonds, REITs, and commodities to implement portfolio optimizations under constraints:
    Maximize return with risk cap,
    Minimize risk with return floor,
    Maximize Sharpe ratio.
Also backtested equal-weight, min-volatility, and max-diversification portfolios and studied the impact of regime shifts in asset risk.


## 🧠 Group Project  
**Title**: *Can Traditional Factors Like Fama-French Power Modern Machine Learning Portfolio Design?*  
**Submitted**: April 2025  
**Course**: FE5214 Quantitative Investing  
**Instructor**: Prof. Chen Kan & Ding Li

This project explores whether traditional factor models, particularly the Fama-French framework, can be enhanced using machine learning for improved equity portfolio construction. It involves:
- Predicting monthly returns using models like SVR, Lasso, and XGBoost
- Modeling volatilities via EGARCH(1,1)
- Clustering stocks into risk-return profiles (KMeans, Agglomerative, Grid-based)
- Portfolio construction via top-N selection and Sharpe ratio optimization

Despite no major improvements in forecast accuracy over OLS, the clustering and optimization pipeline was effective in producing competitive Sharpe ratios, occasionally outperforming the S&P 500 benchmark.

📄 Full report available in the `Project/` folder.

### 👥 Group Members
- **Michael Wynn**  
- **Poreddy Saikiran Reddy**  
- **Gaurav Agrawal**  
- **Zheng Zhoudong**  
- **Raditya**  
- **Wang Yidong**  

Special thanks to our professors for their guidance and feedback throughout the course.

