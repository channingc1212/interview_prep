# Building a Classification Pipeline

## 📄 Scenario
You have a dataset named **`bank_customers.csv`** containing customers' personal and financial information along with a binary target variable **`churn`** (where **1** indicates the customer left the bank, and **0** otherwise). The dataset includes the following columns:

- **`customer_id`** (str): Unique identifier for each customer.
- **`age`** (int): Age of the customer.
- **`salary`** (float): Annual salary of the customer.
- **`num_of_products`** (int): Number of products the customer has with the bank.
- **`is_active_member`** (int): Indicates if the customer is an active member (1) or not (0).
- **`churn`** (int): Target variable indicating if the customer churned (1) or not (0).

---

## 🛠️ Tasks
1. **Data Preparation**:
   - Load the dataset and explore **basic distributions** and **correlations**.
   - Check for and handle **missing values** (you can assume none for this exercise).

2. **Split the data** into **training** and **test sets**.

3. **Build a scikit-learn pipeline**:
   - Use **`StandardScaler`** from **`sklearn.preprocessing`** to **scale numerical features** (e.g., **`age`**, **`salary`**).
   - Use a **simple classifier** such as **`LogisticRegression`** or **`RandomForestClassifier`**.
   - Chain the scaler and classifier together using **`Pipeline`** from **`sklearn.pipeline`**.

4. **Model Evaluation**:
   - Compute the following metrics on the **test set**:
     - **Accuracy**
     - **Precision**
     - **Recall**
     - **F1-score**
   - Perform **cross-validation** using **`cross_val_score`** for more robust metrics.

---

## 🧑‍💻 Key Skills Practiced
- Pipeline construction using **scikit-learn**
- Feature scaling with **StandardScaler**
- Classification modeling with **LogisticRegression** or **RandomForestClassifier**
- Model evaluation using metrics such as accuracy, precision, recall, and F1-score
- Cross-validation with **`cross_val_score`**