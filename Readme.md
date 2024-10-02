Google Trends vs Market Data Analysis
This project explores the relationship between Google Trends search data and various market data, such as stock prices and unemployment rates. The goal is to investigate whether search popularity on Google correlates with changes in stock prices (e.g., Tesla, Bitcoin) or economic indicators (e.g., unemployment rate in the U.S.).

Project Overview
In this analysis, we examine:

Tesla: Exploring the correlation between Tesla's search trends and its stock price.
Bitcoin: Analyzing if there's a relationship between Bitcoin's price and the frequency of related searches.
Unemployment: Investigating the connection between Google search trends for "Unemployment Benefits" and the actual unemployment rate in the U.S.
Data Sources
Google Trends: Search popularity data.
Yahoo Finance: Historical stock prices for Tesla and Bitcoin.
FRED: U.S. unemployment rate data.
Getting Started
Prerequisites
Python 3.x
Jupyter Notebook
Required Python Libraries:
pandas
matplotlib
Install the required libraries via pip:

bash
Copy code
pip install pandas matplotlib
Running the Project
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/google-trends-market-analysis.git
Navigate to the project directory:
bash
Copy code
cd google-trends-market-analysis
Place the CSV data files in the same directory as the notebook.

TESLA Search Trend vs Price.csv
Bitcoin Search Trend.csv
Daily Bitcoin Price.csv
UE Benefits Search vs UE Rate 2004-19.csv
Run the Jupyter Notebook:

bash
Copy code
jupyter notebook
Open and execute the cells in the notebook to explore the analysis.
Analysis and Visualizations
Tesla: A line chart that visualizes the relationship between Tesla's stock price and the Google search trend for "Tesla".


Bitcoin: A line chart for Bitcoin's price against search volume, with search trends marked by circular points and prices in dashed lines.


Unemployment: Visualization of unemployment search trends and the U.S. unemployment rate, including a rolling average to observe patterns.


Features
Data cleaning and preprocessing: Handling missing values, date conversions, and resampling time series data.
Visualizations: Using Matplotlib for creating insightful and clear charts with dual axes for search trends and price/rate data.
Rolling averages: Calculation of 6-month rolling averages to smooth out short-term fluctuations and observe long-term trends.
Challenges
Data cleaning: Handling missing values and converting date strings to Pandas datetime objects.
Time series resampling: Aggregating daily data into monthly data for better trend visualization.
Multi-axis plotting: Visualizing two datasets (search trends and market data) on the same chart using dual y-axes.
Future Work
Incorporate additional data sources such as news sentiment analysis or broader economic indicators.
Extend the analysis to other stocks or market assets.
Automate data collection via APIs (e.g., Google Trends, Yahoo Finance).
Contributing
Feel free to open an issue or submit a pull request if you'd like to contribute to the project.

License
This project is licensed under the MIT License. See the LICENSE file for details.