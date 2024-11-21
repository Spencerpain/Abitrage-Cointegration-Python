# Pairs Trading Project: Exploring Market Neutrality and Statistical Arbitrage

This repository contains a Jupyter Notebook that implements a **Pairs Trading** strategy using Python. The project explores market neutrality and statistical arbitrage by identifying and analyzing pairs of assets with a potential for mean-reverting spreads.

---

## Overview

Pairs trading is a quantitative trading strategy that involves matching a long position with a short position in a pair of highly correlated assets. The theory is rooted in **cointegration** and **mean reversion**, where the spread between two assets fluctuates around a stable mean.

This project implements pairs trading using:
- Python programming.
- Libraries such as `pandas`, `matplotlib`, `seaborn`, `statsmodels`, and `yfinance`.
- A class-based approach for reusability and modularity.

---

## Features

- **Download Historical Data**:
  - Fetch historical stock prices using `yfinance`.
- **Calculate Spread**:
  - Use linear regression to calculate the hedge ratio and determine the spread.
- **Test Stationarity**:
  - Perform the Augmented Dickey-Fuller (ADF) test to check if the spread is stationary (mean-reverting).
- **Visualization**:
  - Plot historical price trends of assets.
  - Visualize the spread and its deviations from the mean.
- **Reusable Class**:
  - Encapsulate functionality in the `PairsTrade` class for modular and reusable code.

---

## Project Structure

- **Notebook**: Contains the main implementation and explanation of the project.
- **Python Script (Optional)**: Includes a standalone implementation of the `PairsTrade` class for production use.

---

## Installation and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>
```

### 2. Install Dependencies
Make sure you have Python 3.7+ installed. Install the required Python libraries:

pip install pandas numpy matplotlib seaborn statsmodels scikit-learn yfinance

### 3. Run the Notebook
Open the Jupyter Notebook and execute all cells:
