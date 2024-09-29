
Overview
This Jupyter Notebook is part of a submission for a 2 Cents Capital's recruitment drive. It focuses on task 1: Strategy Development and Backtesting and Task 3: Alpha Factor Function Development and Backtesting using stock market data. The notebook is designed to load, process, and analyze stock data to create and evaluate alpha strategies for financial markets.

Features
The notebook includes the following key sections:

Library Imports: Essential libraries like Backtrader, Pandas, NumPy, and others are imported to facilitate data loading, processing, and backtesting.
Data Loading:
A function to load stock data from CSV files. You can also download the code and add the address of the Indian file from the dataset provided by the company
Handles datasets from multiple directories, ensuring proper formatting of timestamps and validation of necessary columns (open, high, low, close, volume).
Alpha Factor Development:
Alpha strategies are developed using historical stock data.
Backtesting:
Backtesting of alpha strategies across various stocks.
Performance Evaluation:
Measures of performance such as total return, annualized return, Sharpe ratio, and other key metrics.
Usage Instructions
Clone or download this repository.
Ensure you have the necessary dependencies installed:
Copy code
pip install -r requirements.txt
Place the stock market datasets (CSV files) in the appropriate folder structure, ensuring that each CSV file contains the required columns (open, high, low, close, volume, and a time column like timestamp or date).
Run the notebook to load the data, develop alpha factors, and conduct backtesting.
Folder Structure
/data: Place your stock CSV files here. The notebook reads from this directory.
Requirements
Python 3.x
Backtrader
Pandas
NumPy
How to Run
Open the notebook in Jupyter.
Update file paths as needed in the data-loading section.
Execute the notebook cells in sequence.
