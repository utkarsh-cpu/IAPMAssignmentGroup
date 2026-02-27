# IAPMAssignmentGroup

Portfolio optimization project for Investment Analysis and Portfolio Management course.

## Notebooks

### IAPM_Portfolio_Discovery.ipynb
The original portfolio discovery notebook implementing classical Mean-Variance Optimization (MVO) with:
- NIFTY50 and custom stock selection
- Beam search and genetic algorithm portfolio search
- Risk parity optimization
- Multi-factor stock selection
- Market regime detection

### Advanced_Portfolio_Optimization.ipynb
A comprehensive notebook addressing the theoretical limitations of classical MVO:

| Problem | Classical MVO Limitation | Solution Implemented |
|---------|-------------------------|---------------------|
| Estimation Error | Uses historical means blindly | **Black-Litterman Model** |
| Covariance Instability | Sample covariance is noisy | **Ledoit-Wolf Shrinkage** |
| Static Risk | Assumes constant volatility | **EWMA Dynamic Volatility** |
| Normal Assumptions | Ignores fat tails/skewness | **CVaR/Sortino Optimization** |
| Matrix Inversion | Numerical instability | **Hierarchical Risk Parity** |
| In-Sample Bias | Overfits to historical data | **Walk-Forward Backtesting** |

## Team
Bharath, Chelsea, Gaurav, Vikram, Utkarsh, Yash