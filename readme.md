# Cryptocurrency Price Movement Prediction

This project builds a machine learning pipeline to classify short-term price movements of cryptocurrencies based on historical market data and technical indicators.

## 🧠 Objective
To predict whether the price of a cryptocurrency will go up, down, or remain stable over a short horizon using supervised classification models.

## 🧪 Methodology

### Data Preprocessing
- Used historical price data for a selected cryptocurrency.
- Engineered key features including moving averages, momentum indicators, and volume signals.
- Created a target variable representing price direction: Up, Down, or No Change.

### Feature Engineering
- Applied rolling windows to generate lag-based features.
- Constructed technical indicators such as:
  - Moving Average Convergence Divergence (MACD)
  - Relative Strength Index (RSI)
  - Exponential Moving Averages (EMA)

### Modeling & Evaluation
- Trained multiple classification models:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - XGBoost
- Evaluated using accuracy, F1 score, and confusion matrix.

## 📊 Results
- Models showed improved classification accuracy over baseline heuristics.
- Feature importance analysis provided insights into key drivers of short-term price changes.

## 🛠️ Tech Stack
- Python (Pandas, NumPy, Scikit-learn, XGBoost)
- Jupyter Notebook
- Matplotlib / Seaborn for visualization

## 📌 Notes
- This project focuses on classification, not price regression.
- Ideal for traders or data scientists exploring predictive modeling in financial markets.

## 👥 Team
- Rohit Kamineni  
- [Add teammates if applicable]

