# Portfolio Optimization of Factor-Based Risk Model using Machine Learning 

This repository highlights my recent work at the intersection of **quantitative finance**, **statistical learning**, and **portfolio optimization**. The materials are written to be clear, reproducible, and interview-friendly for quantitative roles in New York City.

---

## Featured Research Project
### Portfolio Optimization of a Factor-Based Risk Model using Machine Learning

This project develops a multi-factor risk model and integrates machine-learning alpha estimation with efficient portfolio construction.

**Scope**
- Construct a factor risk model with industry and style factors; estimate specific risk and factor covariance.
- Generate candidate alphas and preprocess returns (neutralization, outlier handling, standardization).
- Estimate expected returns using **regularized weighted least squares (WLS)** and compare with a **neural network (MLP)** baseline.
- Compute optimal holdings using closed-form linear-algebra identities (e.g., **Woodbury**) under factor/specific risk structure and common constraints.
- Backtest daily to evaluate turnover, exposures, realized risk, and P&L decomposition (factor vs. idiosyncratic).

**Files**
- `Portfolio Optimization of Factor-Based Risk Model using Machine Learning.ipynb`
- `Portfolio Optimization of Factor-Based Risk Model using Machine Learning.pdf`

**Notes for reviewers**
- Code emphasizes transparent modeling choices, cross-validation for regularization strength, and careful train/test separation.
- The notebook includes diagnostics (residual analysis, exposure control, risk contribution) to make assumptions and trade-offs explicit.

---

## Technical Summary

**Languages**: Python, SQL  
**Core libraries**: NumPy, pandas, SciPy, scikit-learn, statsmodels, matplotlib  
**Quant topics**: Factor modeling, risk decomposition, portfolio optimization, cross-sectional prediction, backtesting methodology  
**Techniques**: Weighted regression, shrinkage/regularization, nonlinear models (MLP), constraint handling, efficient linear algebra (Woodbury / block matrices)

---

## How to Review / Reproduce

1. Clone the repository and open the Jupyter notebook in a Python 3.9+ environment.
2. Install standard scientific-Python packages (NumPy, pandas, SciPy, scikit-learn, statsmodels, matplotlib).
3. Run the notebook cells in order. The PDF provides a static overview if an interactive environment is not available.


---

## Professional Considerations

- **Reproducibility**: deterministic seeds where relevant, versioned dependencies when specified.  
- **Risk & governance**: clear separation of signal modeling vs. risk control; exposure constraints documented.  
- **Interpretability**: factor exposures and risk contributions reported alongside performance metrics.  
- **Trade-offs**: regularization vs. capacity; turnover vs. transaction frictions (discussed in-notebook).

---

## Author

**Kecheng Shi**  
Email: ks4327@columbia.edu  
Phone: (212) 814-1023  

Please contact me with any questions, concerns, or recommendations.
