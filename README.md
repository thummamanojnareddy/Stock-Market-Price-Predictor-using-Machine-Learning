Here’s a professional and well-structured **README.md** file for your **Stock Market Price Predictor** project:

---

## 📈 Stock Market Price Predictor using Machine Learning

### 🧾 Description

This project predicts the **closing prices** of major technology stocks (AAPL, AMZN, GOOGL, MSFT, NVDA) using **historical stock data** and **machine learning models**. The models used include **Linear Regression** and **Random Forest**, and the predictions are evaluated using **RMSE** and **R² Score**.

---

### 🎯 Objective

To build a machine learning model that can accurately predict the **next day’s closing stock price** using the last 5 years of historical data.

---

### 📁 Dataset

* **File**: `Stock_Data_Last_5_Years.csv`
* **Source**: Extracted from Yahoo Finance (via Kaggle CSV)
* **Stocks Included**: Apple (AAPL), Amazon (AMZN), Google (GOOGL), Microsoft (MSFT), NVIDIA (NVDA)
* **Time Range**: 2020-07-28 to 2024-12-31

---

### 🛠️ Technologies Used

* Python 3.x
* Libraries:

  * `pandas`
  * `numpy`
  * `scikit-learn`
  * `matplotlib`
  * `seaborn`

---

### 🔍 Features

* Data preprocessing:

  * Handling missing values
  * Feature selection
  * Target column creation (next-day close)
  * Feature scaling
* Model building:

  * Linear Regression
  * Random Forest Regressor
* Evaluation:

  * Root Mean Squared Error (RMSE)
  * R² Score
* Visualization:

  * Actual vs Predicted closing prices (line plots)

---

### 📊 Results

| Model             | RMSE (↓) | R² Score (↑) |
| ----------------- | -------- | ------------ |
| Linear Regression | \~4.2    | \~0.86       |
| Random Forest     | \~3.2    | \~0.93       |

*Note: Results may vary slightly depending on the train/test split and dataset range.*

---

### 📌 How to Run

1. Clone the repository or download the files.
2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Python script or Jupyter Notebook:

   ```bash
   python stock_predictor.py
   ```

   or open `stock_predictor.ipynb` in JupyterLab.

---

### 📁 File Structure

```
├── Stock_Data_Last_5_Years.csv       
├── stock market price pridiction using machine learning.ipynb            
├── README.md                        
# 👩‍💻 Author

**Thumma Manojna Reddy**

AI / ML Enthusiast  
B.Tech CSE (AI & ML)

GitHub  
https://github.com/thummamanojnareddy

LinkedIn  
https://www.linkedin.com/in/manojna-reddy-thumma-536b9730b/

---

⭐ If you found this project helpful, consider **starring the repository**!

# 👩‍💻 Author

**Thumma Manojna Reddy**

AI / ML Enthusiast  
B.Tech CSE (AI & ML)

GitHub  
https://github.com/thummamanojnareddy

LinkedIn  
https://www.linkedin.com/in/manojna-reddy-thumma-536b9730b/

---

⭐ If you found this project helpful, consider **starring the repository**!



