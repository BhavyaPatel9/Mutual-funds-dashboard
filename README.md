#  Mutual Funds Dashboard

A Streamlit-based interactive dashboard for analyzing mutual fund performance, trends, and risk metrics. It offers dynamic visualizations and filters to help users explore various mutual fund schemes with ease.

### 🔗 Live Demo
👉 [Access the Dashboard](https://bhavyapatel9-mutual-funds-dashboar-mutual-fund-dashboard-jsj8we.streamlit.app/)

---

## ⚙️ Features

- 📄 **View Available Schemes**: Browse all mutual fund schemes across AMCs.  
- 📋 **Scheme Details**: View fund objectives, category, risk level, and more.  
- 📈 **Historical NAV**: Analyze Net Asset Value trends over time.  
- 🔀 **Compare NAVs**: Select multiple schemes and compare their performance.  
- 💰 **Average AUM**: Get average Assets Under Management insights.  
- 🔥 **Performance Heatmap**: Visual summary of scheme performance across periods.  
- ⚖️ **Risk and Volatility Analysis**: Standard deviation, Sharpe ratio, and more.  

## Mutual Fund (Short Explanation)
A mutual fund is an investment vehicle that pools money from multiple investors to purchase a diversified portfolio of stocks, bonds, or other securities. Professional fund managers make investment decisions on behalf of investors. Each investor owns shares representing a portion of the fund's holdings. The fund's performance is measured by its Net Asset Value (NAV), which fluctuates based on the underlying securities' market value.

## Dashboard Parameters Explained
### 1. View Available Schemes

Displays a comprehensive list of all mutual fund schemes available across different Asset Management Companies (AMCs)
Allows users to browse and filter schemes by categories, AMCs, or fund types
Provides basic information like scheme name, category, and current status

### 2. Scheme Details

Shows detailed information about a specific mutual fund scheme
Includes fund objectives, investment strategy, benchmark index
Displays category classification, risk level, minimum investment amount
Shows fund manager details, inception date, and expense ratio

### 3. Historical NAV

Tracks the Net Asset Value progression over different time periods
Visualizes price movements through interactive charts
Allows date range selection for custom analysis periods
Helps identify trends, peaks, and troughs in fund performance

### 4. Compare NAVs

Enables side-by-side comparison of multiple mutual fund schemes
Overlays performance charts to identify relative performance
Useful for evaluating similar category funds or different investment options
Helps in making informed investment decisions

### 5. Average AUM

Shows Assets Under Management trends over time
Indicates fund size and investor confidence
Higher AUM generally suggests better liquidity and lower expense ratios
Helps assess fund stability and growth trajectory

### 6. Performance Heatmap

Visual representation of returns across different time periods
Color-coded matrix showing performance intensity
Quick overview of fund performance patterns
Easy identification of consistent vs volatile performers

### 7. Risk and Volatility Analysis

Standard Deviation: Measures price volatility and risk level
Sharpe Ratio: Risk-adjusted return metric (higher is better)
Beta: Sensitivity to market movements (>1 = more volatile than market)
Alpha: Excess return over benchmark performance
Maximum Drawdown: Largest peak-to-trough decline

MFTool is a Python library designed to fetch mutual fund data from Indian markets. It provides easy access to mutual fund information without requiring API keys or complex authentication.

[mftool Documentation](https://mftool.readthedocs.io/en/latest/)

Data from AMFI (Association of Mutual Funds in India) website
[official NAV data file](https://www.amfiindia.com/spages/NAVAll.txt?t=03082025113405)

