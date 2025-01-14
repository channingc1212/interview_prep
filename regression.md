# Handling Missing Data & Simple Regression Model

## 📄 Scenario
You receive a dataset named **`houses.csv`** that contains various features about houses and their selling prices. The columns include:

- **`house_id`** (str): Unique identifier for each house.
- **`num_rooms`** (float): Number of rooms (may contain missing values).
- **`num_bathrooms`** (float): Number of bathrooms (may contain missing values).
- **`square_feet`** (int): Size of the house in square feet.
- **`location`** (str): Location of the house.
- **`price`** (float): Selling price of the house (target variable).

---

## 🛠️ Tasks
1. **Load the dataset** using pandas and identify columns with **missing values**.

2. **Impute missing values**:
   - Choose a strategy to fill missing values in **`num_rooms`** and **`num_bathrooms`** (e.g., mean, median, or a constant value).

3. **Encode categorical features**:
   - One-hot encode the **`location`** column using **`pandas.get_dummies()`** or **`scikit-learn OneHotEncoder`**.

4. **Split the data** into **training** and **test sets**.

5. **Build a simple linear regression model** using **scikit-learn** to predict **`price`**.

6. **Evaluate the model**:
   - Compute the **R-squared** value on both **train** and **test sets**.
   - Print the model’s **coefficients** for each feature.

---

## 🧑‍💻 Key Skills Practiced
- Handling missing data
- Encoding categorical variables
- Train-test splitting
- Building a basic regression model using **scikit-learn**
- Evaluating regression performance (R-squared, feature coefficients)