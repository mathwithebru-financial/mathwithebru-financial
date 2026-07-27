# Ebru

Applied Mathematics master's student working on reproducible financial time-series modeling and data analysis.

## Current research

My thesis studies multi-asset return and volatility forecasting with Transformer-based architectures.

- Assets: BIST 100, USD/TRY, EUR/TRY, and Gold
- Methods: Transformer architectures, LSTM, XGBoost, GARCH-family models
- Evaluation: chronological validation, leakage controls, DM-HLN tests with Holm correction
- Explainability: post-hoc SHAP analysis with explicit non-causal interpretation

The project emphasizes transparent negative results as much as successful forecasts. The current evidence does not support a general superiority claim for the final Transformer model.

## Tools used in the thesis

`Python` · `PyTorch` · `pandas` · `NumPy` · `scikit-learn` · `XGBoost` · `arch` · `SHAP`

## Featured project

### [Multi-Asset Return and Volatility Forecasting](https://github.com/mathwithebru-financial/tez-codes)

An audited research pipeline covering data preparation, 480-configuration model search, three-seed final evaluation, naive and learned baselines, GARCH-family baselines, Holm-adjusted DM-HLN comparisons, and post-hoc SHAP diagnostics.

The repository contains checksum-verified scripts, locked protocol records, an output-cleared research notebook, reproducibility notes, and compact SHAP result summaries. Raw data, trained model weights, scalers, and large prediction arrays are excluded.

## Research principles

- Chronological, target-realization-aware evaluation
- Train-only preprocessing and explicit leakage controls
- Locked test protocol and checksum-tracked artifacts
- Transparent reporting of positive, negative, and inconclusive results
- Post-hoc explainability without causal claims
