# Asier Ugarteche

Senior Software Engineer at the Financial Times. I work on production subscription
systems by day, and on time-series forecasting and quantitative finance the rest of
the time.

MSc Business Analytics & Data Science (Concentration in Advanced AI) — GPA 3.95/4.00,
ranked 2nd in cohort, Dean's List. CQF candidate.

## Building

**[alphabacktest.com](https://alphabacktest.com)** — an event-driven backtesting engine
and web platform for equity strategies. Signals form on each bar's close and fill at the
next bar's open; commission and slippage are configurable; and the buy-and-hold benchmark
runs through the same engine and the same costs as the strategy, so the comparison is
like-for-like. Verified with a hand-computed P&L golden test and a look-ahead regression
test that mutates future bars and asserts past P&L is unchanged.
*Python · pandas · NumPy · Flask · Redis · React*

**[stockandconquer.com](https://stockandconquer.com)** — a multi-model ML pipeline for
weekly stock-movement prediction over engineered technical, volume and statistical
features (MACD, RSI, moving averages, lagged returns, rolling moments), comparing
logistic regression, SVM, random forest, XGBoost and a neural network.
*Python · scikit-learn · XGBoost · TensorFlow · Flask · React*

## Selected repositories

**[silver-thesis](https://github.com/asugar13/silver-thesis)** — companion code for my MSc
thesis on forecasting weekly silver returns and realised volatility, graded Honours
(4.0/4.0). Eight model families (ARIMA/ARIMAX, MIDAS, VAR, LSTM, XGBoost, Random Forest,
HAR-RV, GARCH) judged on a level footing against a random-walk benchmark, walk-forward
over 591 weeks.

> The headline result: the mean is a martingale, the variance is not. No model beat the
> drift on returns out-of-sample, but realised volatility was strongly forecastable — and
> Reddit and financial-news sentiment (RoBERTa/FinBERT) measurably improved the volatility
> forecasts.

**[mlops-credit-risk](https://github.com/asugar13/mlops-credit-risk)** — MLOps pipeline for
an auto-insurance pricing use case.

**[rl-taxi-pong](https://github.com/asugar13/rl-taxi-pong)** — Deep Q-Network agents for two
Gymnasium environments, built from scratch in PyTorch.

**[novacart-chatbot](https://github.com/asugar13/novacart-chatbot)** — RAG-powered support
chatbot built with Streamlit, Qwen (via Ollama) and ChromaDB.

## Background

Before the FT I was a Senior Cyber Technology Specialist at Darktrace in Toronto — a
customer-facing technical role running discovery and proof-of-value engagements for
enterprise clients across Canada and Latin America, in English, French and Spanish.
BSc Computer Science & Economics, University of Toronto.

**Python · TypeScript · R · SQL · pandas · scikit-learn · PyTorch · BigQuery · Node.js · Java **

London, UK · [LinkedIn](https://www.linkedin.com/in/asier-ugarteche-perez/) ·
asier.ugarteche@gmail.com
