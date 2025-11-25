# News Sentiment & Stock Price Analysis

## Project Overview
This project analyzes the relationship between financial news sentiment and stock price movements. The analysis includes:

1. **News Data Analysis** – Exploratory Data Analysis (EDA) on news headlines.
2. **Stock Price Analysis** – Calculation of technical indicators like SMA and RSI.
3. **Correlation Analysis** – Measuring correlation between news sentiment and stock returns.

The goal is to understand how news sentiment may impact stock price changes.

---

## Repository Structure
├── .github/
│ └── workflows/
│ └── unittests.yml # CI/CD setup
├── notebooks/
│ └── README.md # Notes for exploratory analysis
├── scripts/
│ └── init.py
├── src/
│ └── init.py
├── tests/
│ └── init.py
├── .gitignore
├── requirements.txt # Python dependencies
└── README.md # Project description

---

## Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo

## Create and activate a virtual environment:
python -m venv .venv
source .venv/bin/activate      # On Windows use `.venv\Scripts\activate`

pip install -r requirements.txt