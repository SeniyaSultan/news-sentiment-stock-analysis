# Predicting Price Moves with News Sentiment

## Overview
This project analyzes financial news headlines and stock price data to understand how news sentiment affects stock movements. Using NLP techniques, sentiment scores are computed for each headline, and correlations are drawn with daily stock returns. Technical indicators like Moving Averages (MA), RSI, and MACD are also calculated to support the analysis.

The goal is to provide actionable insights and potential predictive strategies for stock market trends based on financial news sentiment.

---

## Project Structure
├── .vscode/ # VSCode settings
├── .github/
│ └── workflows/ # GitHub Actions (CI/CD)
├── notebooks/ # Jupyter notebooks
├── scripts/ # Python scripts for data processing
├── src/ # Source code modules
├── tests/ # Unit tests
├── requirements.txt # Python dependencies
├── README.md # Project overview and instructions

---

## Setup Instructions

1. **Clone the repository:**
```bash
Create and activate a virtual environment:

python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate


Install dependencies:

pip install -r requirements.txt


Run Jupyter notebooks:

jupyter notebook
git clone https://github.com/YourUsername/news-sentiment-stock-analysis.git
cd news-sentiment-stock-analysis
