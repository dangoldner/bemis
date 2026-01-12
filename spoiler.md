# Portfolio Statistics and Optimization - Chapter Summaries

## Chapter 1: Introduction
Chapter 1 introduces the efficient market hypothesis (EMH) and its contradictions (anomalies), then outlines the book's focus on CAPM, Fama-French, and Mean-Variance Optimization as interpretive tools rather than prescriptive models, emphasizing the importance of understanding statistical assumptions and non-stationarity in financial data.

## Chapter 2: Distributions and Summary Statistics
Chapter 2 builds the statistical foundation: CDFs, PDFs, mean, variance, percentiles, skew, and kurtosis for univariate and multivariate distributions (normal, log-normal, Student t). Real equity returns have fat tails that normal distributions fail to capture, yet understanding these distributions remains essential for estimation and diversification analysis.

## Chapter 3: Covariance
Chapter 3 develops the covariance matrix as the core structure for multivariate analysis: covariance as an inner product (Cauchy-Schwarz, correlation bounds), CAPM β derivation, copulas for modeling joint distributions, and eigenvalue/eigenvector analysis (including the 2008 crisis cautionary tale about Gaussian copula misuse).

## Chapter 4: Ordinary Least Squares
Chapter 4 derives OLS from minimizing squared errors and maximum likelihood, establishes Gauss-Markov assumptions, proves the OLS estimator is unbiased with known distribution (leading to t-tests and F-tests), and develops hypothesis testing, confidence intervals, and variable selection methods (forward selection, backward elimination).

## Chapter 5: Math Preliminaries
Chapter 5 provides mathematical foundations for optimization: gradients, Hessians, Jacobians for multivariate calculus; big-O and little-o notation for growth rates; Taylor series expansions; and convexity definitions and equivalences (function lies above tangent plane ⟺ positive semidefinite Hessian).

## Chapter 6: Unconstrained Optimization
Chapter 6 establishes necessary/sufficient conditions for minima (stationary points, positive definite Hessian), proves convex functions have global minima at stationary points, and develops Newton's method with quadratic convergence proof—applied to OLS, GLS, and index tracking problems.

## Chapter 7: Constrained Optimization
Chapter 7 develops the Karush-Kuhn-Tucker (KKT) conditions for constrained optimization, proves their necessity/sufficiency for convex problems, and applies them to Quadratic Programming (QPLC) and Linear Programming (LPLC), including quantile regression and the tangency portfolio problem.

## Chapter 8: Mean-Variance Optimization
Chapter 8 presents Merton's mean-variance optimization: derives the efficient frontier analytically, proves the Mutual Fund Separation Theorem (any efficient portfolio is a combination of two others), develops the Capital Market Line with a risk-free asset, and connects to CAPM—but warns about practical "error maximization" issues with sample covariances.

## Chapter 9: Coherent Measures of Risk
Chapter 9 defines coherent risk measures (positive homogeneity, translation invariance, monotonicity, subadditivity), analyzes VaR (fails subadditivity in general) and CVaR (coherent), introduces drawdown measures (CDaR), and shows how to implement these as linear constraints in portfolio optimization.

## Chapter 10: Covariance Modifications
Chapter 10 addresses sample covariance estimation problems through factor models (time-series with observed factors, cross-sectional with observed loadings, PCA), shrinkage estimators (Ledoit-Wolf to constant correlation or CAPM targets), and proves that portfolio constraints act like covariance modifications—unifying constrained optimization with maximum likelihood estimation.nce
Chapter 3 develops the covariance matrix as the core structure for multivariate analysis: covariance as an inner product (leading to Cauchy-Schwarz and correlation bounds), the CAPM β derivation, copulas for separating marginal and joint distributions (with a cautionary tale about CDOs and the 2008 crisis), and eigenvalue decomposition to understand total variance, dimension reduction via principal components, and the empirical observation that one dominant "market" eigenportfolio explains much of equity co-movement.
