# Mutual-Fund-Analysis
Project Overview

This project focuses on building a Mutual Fund Portfolio Planning system using Python. The goal of the project is to simulate how an investor can create a diversified mutual fund–like portfolio using historical stock data and evaluate the risk, return, and growth of investments over time.

The project analyzes stock price data, calculates portfolio performance, and simulates Systematic Investment Plan (SIP) growth to help investors understand how regular investments can grow in the long term.

The analysis is implemented in a Jupyter Notebook using Python libraries for data analysis and interactive visualization.

Project Objectives

Create a mutual fund–style portfolio using historical stock data.

Analyze returns and risk levels of the selected assets.

Simulate SIP investment growth over time.

Provide visual insights through graphs and charts.

Help investors understand portfolio diversification and long-term investment planning.

Technologies and Libraries Used

The project is implemented using the following Python libraries:

Python

Pandas – Data manipulation and analysis

NumPy – Numerical computations

Plotly Express – Interactive visualizations

Plotly Graph Objects – Advanced interactive charts

Jupyter Notebook – Development and analysis environment

Dataset

The dataset used in this project contains historical stock price data which is used to simulate mutual fund portfolio investments.

Typical fields used in the dataset include:

Date

Stock/Asset Name

Closing Price

Returns

Investment Value

This data is used to calculate portfolio performance and simulate investment growth.

Project Workflow

The project follows a structured data analysis pipeline:

1. Data Loading

The dataset is imported and loaded using Pandas for further analysis.

2. Data Cleaning

Basic preprocessing is performed to ensure the dataset is structured and usable for analysis.

3. Return Calculation

Daily or periodic returns are calculated to measure how each asset performs over time.

4. Portfolio Construction

A portfolio is created by combining multiple assets to simulate a mutual fund investment strategy.

5. Risk and Return Analysis

The project evaluates:

Portfolio returns

Investment growth

Performance trends

6. SIP Simulation

A Systematic Investment Plan (SIP) model is simulated to demonstrate how consistent investments can grow over time.

7. Data Visualization

Multiple interactive graphs are generated to analyze portfolio performance and investment growth.

Visualizations Included

The project includes several charts to make the analysis easier to understand:

Portfolio growth over time

Asset performance comparison

Return distribution

SIP investment growth

Portfolio value trends

Additional analytical charts for better insights

These visualizations help users quickly understand investment performance and risk patterns.

How to Run the Project
Step 1: Clone the Repository
git clone https://github.com/your-username/mutual-fund-portfolio-python.git
Step 2: Navigate to the Project Folder
cd mutual-fund-portfolio-python
Step 3: Install Required Libraries
pip install pandas numpy plotly
Step 4: Run the Notebook

Open the Jupyter Notebook:

jupyter notebook

Then run:

mutual_fund_portfolio_project.ipynb
Project Structure
Mutual-Fund-Portfolio-Python
│
├── mutual_fund_portfolio_project.ipynb
├── dataset.csv
├── README.md
Key Insights

Diversification helps reduce investment risk.

SIP investments allow gradual wealth accumulation.

Portfolio performance varies based on asset allocation.

Visualization helps investors better understand financial trends.

Future Improvements

Possible enhancements for this project include:

Adding real-time stock market data

Implementing portfolio optimization models

Including risk metrics such as Sharpe Ratio

Building a web dashboard using Streamlit or Dash

Allowing users to create custom portfolios

Author

Rutvik Kajrekar

MMS Student | Data Analysis & Business Intelligence Enthusiast
