
# 🔩 Machine-Learning-Project-Parshwanath Steel Trading: Brandwise Stock Forecasting 📈

This project applies machine learning to forecast brandwise stock quantities for **Parshwanath Steel Trading** using **data stored in a SQL database**. It uses a **Linear Regression model** to predict future stock needs, helping optimize inventory planning.

---

## 📌 Project Overview

This project helps the steel trading business forecast **brandwise stock levels** to improve purchase decisions and reduce overstock/understock issues.

Using **SQL** for data handling and **Python** for machine learning, this project demonstrates a real-world application of data science in inventory forecasting.

---

## 🔄 Project Workflow

1. **🗃️ Data Loading (SQL)**
   - Connected to a SQL database (e.g., PostgreSQL/MySQL).
   - Queried brandwise historical stock data using SQL.
   - Loaded data into a Pandas DataFrame for analysis.

2. **📊 Exploratory Data Analysis (EDA)**
   - Analyzed stock distribution per brand.
   - Checked for seasonality, trends, and outliers.

3. **🧹 Data Preprocessing**
   - Cleaned null or inconsistent values.
   - Converted time series and categorical values as needed.

4. **📈 Model Building**
   - Built a **Linear Regression** model using Scikit-learn.
   - Trained on brandwise historical stock data.

5. **📏 Model Evaluation**
   - Evaluated performance using:
     - R² Score
     - Mean Absolute Error (MAE)
     - Root Mean Squared Error (RMSE)

6. **🔮 Forecasting**
   - Predicted future stock values for each brand.
   - Visualized actual vs predicted stock levels.

---

## 🛠️ Tech Stack Used

- **SQL** (for data storage)
- **Python** (for modeling)
- **Pandas & NumPy** (data manipulation)
- **Matplotlib & Seaborn** (visualizations)
- **Scikit-learn** (machine learning)
- **Jupyter Notebook**

---

## 🧠 Key Insights

- Certain brands showed recurring stock depletion patterns.
- Stock levels can now be forecasted a few weeks/months in advance.
- Enabled smarter procurement strategy using historical trends.
