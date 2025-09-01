# 🛒 E-commerce Dataset Analysis (NumPy & Pandas)

## 📌 Overview
This project analyzes an **E-commerce dataset** using only **NumPy and Pandas**.  
The goal is to extract valuable business insights such as:
- 🧑‍🤝‍🧑 Customer purchase behavior  
- 📦 Product sales performance  
- 📅 Time-based sales trends  
- 📊 Customer segmentation (Basic RFM Model)  

All results are saved as **separate CSV files** for reporting and further usage.

---

## 📂 Project Structure
```

Ecommerce_Data_Analysis/
│
├── Data/
│   ├── ecommerce_dataset.csv        # raw dataset
│   ├── cleaned_ecommerce.csv        # cleaned dataset
│   ├── output_top_customers.csv     # top customers by revenue
│   ├── output_top_products.csv      # best-selling products
│   ├── output_least_products.csv    # least-selling products
│   ├── output_monthly_sales.csv     # monthly sales trends
│   ├── output_daily_sales.csv       # daily sales trends
│   └── output_rfm.csv               # customer segmentation data
│
├── Notebooks/
│   ├── analysis_notebook.ipynb       # cleaning raw dataset → cleaned dataset
│
└── README.md                        # project documentation

````

---

## ⚙️ Installation & Setup
1. Clone repository:
    ``` bash
   git clone https://github.com/avinash-kamble-9/Ecommerce_data_analysis_numpy_pandas.git
   cd Ecommerce_data_analysis_numpy_pandas
   ```
2. Install required dependencies:

   ```bash
   pip install numpy pandas
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook analysis_notebook.ipynb
   ```



## 📊 Analysis Performed

### 1. Customer Purchase Behavior

* Top 10 customers by total spending
* Average Order Value (AOV)
* Repeat vs One-time customers

### 2. Product Sales Insights

* Top-selling products by revenue
* Least-selling products
* Revenue contribution

### 3. Time-Based Sales Trends

* Monthly sales trend
* Daily sales performance
* Peak sales days

### 4. Customer Segmentation (RFM)

* **Recency**: Days since last purchase
* **Frequency**: Number of purchases
* **Monetary**: Total spending

---

## 📑 Outputs

* `top_customers.csv` → Top customers by spending
* `top_products.csv` → Best-selling products
* `least_products.csv` → Least-selling products
* `monthly_sales.csv` → Monthly sales trends
* `daily_sales.csv` → Daily sales trends
* `rfm.csv` → Customer segmentation data

---

## 🚀 Future Enhancements

* Add data visualization (Matplotlib/Seaborn/Plotly)
* Build interactive dashboard using **Streamlit/Power BI**
* Predictive analysis with **Machine Learning**

---

## 👨‍💻 Author

**Avinash Kamble**
[LinkedIn](https://www.linkedin.com/in/avinashzz)

