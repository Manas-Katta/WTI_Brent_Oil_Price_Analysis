# Crude Oil Price Analysis: WTI and Brent

This project offers a comprehensive exploratory analysis of historical crude oil prices for West Texas Intermediate (WTI) and Brent crude. By examining long-term trends, seasonal patterns, and price volatility, this analysis provides valuable insights into one of the world’s most significant commodities.

## Project Overview

### Objective
To analyze historical WTI and Brent crude oil prices, identify patterns and trends, and gain insights into seasonal variations and market volatility.

### Data Source
- **WTI Data**: Cushing, OK WTI Spot Price FOB (Dollars per Barrel)
- **Brent Data**: Europe Brent Spot Price FOB (Dollars per Barrel)

These datasets provide weekly data points from the mid-1980s to the present.

### Tools & Libraries
- **Data Processing**: `Pandas`
- **Visualization**: `Matplotlib` (for static visualizations)
- **Time Series Decomposition**: `statsmodels`

## Project Structure

### 1. Data Extraction and Preparation
The datasets were imported from public sources and formatted into structured DataFrames. The `date` column was converted to datetime format, and any missing values were managed to ensure data integrity throughout the analysis.

### 2. Exploratory Data Analysis (EDA)
A series of visualizations and statistical summaries were conducted to explore price patterns and identify key trends. Highlights include:
- **Trend Analysis**: Line charts visualize overall price trends for both WTI and Brent.
- **4-Week Rolling Statistics**: Rolling averages and standard deviations capture short-term fluctuations and provide insights into price volatility.
- **Distribution Analysis**: Histograms illustrate the distribution of prices for WTI and Brent, highlighting periods of price stability and instability.

### 3. Seasonal Decomposition
Using seasonal decomposition, the project breaks down WTI and Brent prices into trend, seasonal, and residual components. This analysis highlights recurring annual patterns, aiding in the understanding of seasonal behaviors in the crude oil market.

### 4. Seasonal Analysis by Quarter
To further examine seasonal influences, average prices were calculated for each season (Winter, Spring, Summer, Fall). This section reveals how prices fluctuate with seasonal demand changes, providing insights relevant to economic and market analysts.

### 5. Volatility and Percentage Change Analysis
- **Weekly Percentage Change**: Analyzed weekly percentage changes to assess market volatility, distinguishing between positive and negative price shifts.
- **Statistical Summary**: Computed metrics such as maximum, minimum, average, and mean absolute deviation (MAD) for percentage changes, shedding light on periods of high price movement.

## Key Insights
- **Long-Term Trends**: Analysis reveals significant trends in WTI and Brent prices, reflecting geopolitical events, economic shifts, and supply-demand dynamics.
- **Seasonal Price Behavior**: Seasonal analysis indicates variations in average prices by season, likely influenced by demand patterns and economic cycles.
- **Market Volatility**: Weekly percentage change analysis underscores periods of heightened volatility, valuable for investors, policymakers, and economic analysts.

