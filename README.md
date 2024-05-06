# Project 1

## Analysis of the Australian stock market during period 2014-2023

In the past 10 years, with the hit of COVID, the Australian Stock Market has seen many changes in the stock prices. This project objective is to identify trends in the stocks over the last 10 years, review their performance and identify the top and bottom 5 performing stocks. Review the movement of these stocks individually and analyse the effect of COVID if any.

## Data Source

https://www.marketindex.com.au/data-downloads

API : https://api.marketstack.com/
(API is used to collect splits and dividend nformation for ASX Stock.)

## Data cleaning and scope

The following steps were taken to clean the data:

- Removal of stocks with inconsistent data.
- Filtering out stocks that are of type "Equity".
- Elimination of ambiguous stock entries.

### What do you need?

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib

### How to use the code?

1. Clone the repository to your local machine.
2. Open the desired Notebook.
3. Run each cell sequentially to execute the analysis and view the results.

### Project structure

Below structue only shows final files

Project 1/
│
├── DataCleaning/
│ ├── resources/
│ │ ├── .... all input files .xlsx & .csv
│ │ ├── complete_stock_data.csv
│ └── final_stock_data_with_splits_dividends.ipynb
│
├── DataVisualisation/
│ ├── Output/
│ │ ├── .... all charts .png
│ ├── calculate_top_and_buttom_gainers-during_covid.ipynb
│ └── calculate_top_and_buttom_gainers.ipynb
│
└── README.md
