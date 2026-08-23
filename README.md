# INS-407-Time-Series-Analysis


Welcome to my coursework and research repository for **Time Series Analysis** at AUPP. This repository houses time-indexed data processing scripts, statistical forecasting models, machine learning benchmarks, and the final empirical research project.

---

## **Repository Overview**

```text
├── data/                       # Datasets (Raw and Processed)
│   ├── raw/                    # Original time series datasets (unmodified)
│   └── processed/              # Stationary, scaled, and differenced datasets
├── notebooks/                  # Interactive Jupyter Analysis
│   ├── 01-eda-decomposition.ipynb  # Stationarity tests, trend/seasonal decomposition
│   ├── 02-classical-models.ipynb   # AR, MA, ARIMA, SARIMA, SARIMAX
│   ├── 03-volatility-garch.ipynb   # ARCH/GARCH financial modeling
│   └── 04-machine-learning.ipynb  # Prophet, XGBoost, and LSTM/RNN models
├── src/                        # Modular Python Scripts
│   ├── data_loader.py          # Time indexing, missing value interpolation
│   ├── stationarity.py         # ADF, KPSS tests, difference/log transforms
│   └── evaluation.py           # RMSE, MAE, MAPE, SMAPE metrics
├── project/                    # Final Forecasting Project
│   ├── report.pdf              # Final empirical report
│   └── slides.pdf              # Presentation slides
└── README.md                   # Repository overview and progress log
