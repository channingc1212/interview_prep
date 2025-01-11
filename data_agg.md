# Sales Data Aggregation & Analysis

## 📄 Scenario
You have a CSV file named **`sales_data.csv`** that contains daily sales data for an e-commerce store. The file includes the following columns:

- **`order_id`** (str or int): Unique identifier for each order.
- **`order_date`** (datetime): Date the order was placed.
- **`product_id`** (str): Identifier for the product sold.
- **`quantity`** (int): Number of units purchased for that product.
- **`price`** (float): Price per unit for that product.
- **`customer_id`** (str): Unique identifier for the customer.

---

## 🛠️ Tasks
1. **Import the data using pandas** and examine its structure using methods like `.head()` and `.info()`.

2. **Clean the data** by:
   - Checking for missing or invalid values and deciding how to handle them (e.g., dropping rows or filling with default values).
   - Converting **`order_date`** to a datetime type if needed.

3. **Aggregate sales** by:
   - Computing total revenue per product using the formula:
     ```
     total_revenue = quantity * price
     ```
   - Grouping the data by **`product_id`** to calculate total revenue.
   - Sorting products by total revenue in **descending order**.

4. **Perform time-based analysis** by:
   - Creating a new DataFrame that shows **monthly total revenue**.
     - (Hint: Use **`resample('M')`** after setting **`order_date`** as the index, or group by year-month combinations).
   - **Plot the monthly trends** using **matplotlib** or **seaborn**.

5. **Conduct customer segmentation** by:
   - Finding the **top 5 customers** in terms of total spending.
   - Counting how many **unique products** each of these top 5 customers purchased.

---

## 🧑‍💻 Key Skills Practiced
- Data loading, cleaning, and validation
- Grouping and aggregation
- Time-series analysis
- Basic visualization using **matplotlib** or **seaborn**