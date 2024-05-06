# Australian Stock Analysis (2014-2023)

This repository contains an analysis of Australian stocks for the period spanning from 2014 to 2023. The analysis utilizes data sourced from two primary platforms: Market Index and the Marketstack API. The aim of this analysis is to provide insights into the performance of Australian stocks over the specified timeframe, with a focus on identifying top-performing stocks, understanding their movement trends, and highlighting top-performing industries within the stock market.

## Data Collection and Cleaning

### Data Sources:

- <strong>Market Index</strong>: Historical stock data is obtained from Market Index.
- <strong>Marketstack API</strong>: Splits and dividends data are fetched using the Marketstack API.

### Data Cleaning:

- Stocks with inconsistent entries for the past ten years are removed to ensure data consistency.
- Only stocks categorized as "Equity" are retained for analysis.
- Ambiguous stock entries are removed to maintain data accuracy.
- Stocks with available industry information are retained for further analysis.

## Analysis Methodology

### Chart Generation:

- Jupyter Notebook and Python 3.x are utilized for analysis and visualization.
- Matplotlib library is used for generating charts.

### Key Analysis Points:

- Identification of the top 5 and bottom 5 performing stocks over the 2014-2023 period.
- Analysis of the movement trends of top and bottom-performing stocks throughout the past 10 years.
- Determination of top and bottom-performing stocks during the COVID-19 pandemic.
- Identification of the top-performing industries in the Australian stock market.

## Repository Structure

- <strong>Data</strong>: Contains cleaned and processed stock data.
- <strong>Notebooks</strong>: Includes Jupyter notebooks used for data analysis and chart generation.
- <strong>Charts</strong>: Stores visualizations generated from the analysis.
- <strong>README.md</strong>: Provides an overview of the analysis process and repository contents.

## What do you need?

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib

## How to use the code?

1. Clone the repository to your local machine.
2. Ensure you have Jupyter Notebook and Python 3.x installed.
3. Open the Jupyter Notebook files in the Notebooks directory to view the analysis steps and code.
4. Execute the notebooks to reproduce the analysis and generate charts.

## Contributors

Trupti Radadiya
Mason Seifaddini
Hao(Frank) Nguyen
Uthpalie

## Disclaimer

This analysis is for informational purposes only and should not be considered financial advice. Investors should conduct their own research or consult with a financial advisor before making investment decisions based on this analysis.
