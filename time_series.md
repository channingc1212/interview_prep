# Time-Series Analysis & Rolling Statistics

## 📄 Scenario
You have a time-series dataset named **`stock_prices.csv`** that contains daily closing prices for multiple stocks. The dataset includes the following columns:

- **`date`** (datetime): Date of the stock price.
- **`ticker`** (str): Stock ticker symbol (e.g., "AAPL", "MSFT").
- **`close_price`** (float): Daily closing price of the stock.

---

## 🛠️ Tasks
1. **Load the dataset** using pandas and convert the **`date`** column to a **datetime index** for easier time-series operations.

2. **Focus on a single ticker**:
   - Extract the rows corresponding to a specific **ticker** (e.g., **"AAPL"**) and sort the data by **date**.

3. **Compute rolling metrics**:
   - Calculate the **7-day** and **30-day rolling averages** of the **`close_price`**.
   - **Plot** the rolling averages alongside the **daily closing price** using **matplotlib** or **seaborn**.

4. **Calculate percent change**:
   - Create a new column that shows the **daily percent change** in **`close_price`**.

5. **Optional**: Evaluate **correlations** between different tickers:
   - **Pivot** the data into a wider format (one column per ticker) and calculate the **correlation matrix**.

---

## 🧑‍💻 Key Skills Practiced
- Time-series filtering and indexing
- Rolling and expanding window calculations
- Data pivoting and reshaping
- Correlation analysis
- Data visualization using **matplotlib** or **seaborn**