# Our Data

The preprocessing file we used to create these dataframes can be found in '../Data/Data-Merge/data-merge.ipynb'.

## df 

The data we use in scenario 1.
It includes the following data:

-- S&P 500 close prices

-- 10-year treasury bond yield (tby)

-- Federal funding rate (ffr)

-- Total Federal assets (fta)

-- Earnings-per-share (eps)

-- Dividend yield (div)

-- Unemployment rate (une)

-- WTI Oil Index (wti)

-- Producer Price Index (ppi)

-- Retail and Food Services Sales (rfs)

More information on each dataset is included below.

## df2

The data we use in scenario 1 model comparison.
It includes the following data:

-- S&P 500 open/close/high/low prices

-- 10-year treasury bond yield (tby)

-- Federal funding rate (ffr)

-- Total Federal assets (fta)

-- Earnings-per-share (eps)

-- Dividend yield (div)

-- Unemployment rate (une)

-- WTI Oil Index (wti)

-- Producer Price Index (ppi)

-- Retail and Food Services Sales (rfs)

More information on each dataset is included below.

## dff1

The data we use in scenario 2 (before covid time). It includes the following data:

-- S&P 500 Closing price (y)

-- 10-year treasury bond yield (tby)

-- Federal funding rate (ffr)

-- Total Federal assets (fta)

-- Earnings-per-share (eps)

-- Dividend yield (div)

-- Unemployment rate (une)

-- WTI Oil Index (wti)

-- Producer Price Index (ppi)

-- Retail and Food Services Sales (rfs)

-- FB Prophet predction (fbsp)

-- Difference between actual S&P 500 Price and FB Prophet predction (diff)

More information on each dataset is included below.

## dff2

The data we use in scenario 2 (include covid time). It includes the following data:

-- S&P 500 Closing price (y)

-- 10-year treasury bond yield (tby)

-- Federal funding rate (ffr)

-- Total Federal assets (fta)

-- Earnings-per-share (eps)

-- Dividend yield (div)

-- Unemployment rate (une)

-- WTI Oil Index (wti)

-- Producer Price Index (ppi)

-- Retail and Food Services Sales (rfs)

-- FB Prophet predction (fbsp)

-- Difference between actual S&P 500 Price and FB Prophet predction (diff)

More information on each dataset is included below.

### S&P 500 Market Data (sp500_df)

This dataframe contains historical data for the S&P 500 index.

The columns are: Date, Open, High, Low, Close.

The dates range from Jan 3, 1978 to May 14, 2021. The data is recorded daily.

downloaded from www.wsj.com

###  Earning-Per-share (sp500eps_df)

This dataset contains the historical Earning-Per-share data for S&P 500.

The columns are: Date, Value.

The dates range from Jan, 1871 to Dec, 2020. The data is reported monthly (at the end of the month).

downloaded from https://www.quandl.com/

### Price-to-Earning Ratio Data (sp500per_df)

This dataframe contains historical price-to-earnings ratio for the S&P 500.

The columns are: date, value.

The dates range from Dec 1927 to Dec 2020. The data is recorded monthly.

downloaded from https://www.quandl.com/

### Treasury Bond Yield Data (bond_df)

This dataset contains the historical bond yields for 10-year US treasury bonds.

The columns are: Date, Value.

The dates range from Jan 1, 1962 to May 6, 2021. The data is recorded daily.

downloaded from https://fred.stlouisfed.org/

### Federal Funding Rate Data (ffr_df)

This dataset contains the historical Federal Funding Rates data.

The columns are: DATE, FEDFUNDS.

The dates range from July, 1954 to April, 2021. The data is reported monthly (on the first day of the month).

downloaded from https://fred.stlouisfed.org/

### Total Federal Assets (fta_df)

This dataset contains the historical Total Federal Assets data.

The columns are: DATE, RESPPANWW.

The dates range from Dec 18, 2002 to May 12, 2021. The data is reported weekly (on Wednesdays).

downloaded from https://fred.stlouisfed.org/

### Advance Retail Sales: Retail and Food Services, Total (rfs_df)

This dataset contains the retail sales data of U.S.

The columns are: Date, Value.

The dates range from January, 1871 to May 2021. The data is reported monthly (at the end of the month).

downloaded from https://www.quandl.com

### Unemployment rates (une_df)

This dataset contains the historical U.S. unemployment rate data

The columns are: DATE,UNRATE

The dates range from Jan 1992 to Apr 2021. The data is reported monthly (at the beginning of the month).

downloaded from https://fred.stlouisfed.org/

### Producer Price Index of All Commodities (ppi_df)

This dataset contains the Producer Price Index of All Commodities

The columns are: DATE,PPIACO

The dates range from Jan 1913 to Jan 2021. The data is reported monthly (at the beginning of the month).

downloaded from https://fred.stlouisfed.org/

### NYSE ARCA oil index(nao_df)

This dataset contains the NYSE ARCA oil index.

The dates range from 04/30/09 to 05/25/21. The data is reported daily.

The columns are Date, Open, High, Low, Close

downloaded from www.wsj.com

### WTI oil index (wti_df)

This dataset contains the WTI oil index.

The dates range from 1986-01-02 to 2021-05-17

The columns are DATE, DCOILWTICO

downloaded from https://fred.stlouisfed.org/
