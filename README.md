This project implements a PCA-based projection framework to decompose financial and sentiment features into structured signal and residual noise components.

Using a multi-source dataset combining market variables (price, returns, volatility, moving averages) and sentiment features (average sentiment, polarity ratios, sentiment pressure), we construct a projection matrix:

P = U Uᵀ

where U represents the principal component basis.

The feature space is decomposed as:
- Signal: PX (structured, low-dimensional information)
- Noise: X − PX (residual variation)

We quantify information quality using:
- Signal-to-Noise Ratio (SNR)
- Explained variance (PCA)

## Key Findings
- High intrinsic structure in the dataset (≈95% explained variance)
- Strong signal dominance (SNR ≈ 4.4)
- Evidence of feature redundancy and low-dimensional representation
- Structured sentiment signals that may not directly translate into predictive power

## Applications
- Quantitative finance (feature selection, alpha research)
- Financial sentiment analysis
- Dimensionality reduction and signal extraction
- Preprocessing for machine learning models

This work highlights the distinction between structural signal and predictive relevance in financial data.
