# 🥑 Avocado Price Prediction using Machine Learning

This project predicts avocado prices across different regions using machine learning regression models.
It focuses on **data analysis, feature engineering, and predictive modeling** to uncover patterns in price variations and forecast future market trends.

---

## 🎯 Problem Statement

Avocado prices fluctuate due to factors such as region, type, and market demand.
This project aims to develop a **predictive model** that helps understand these patterns and estimate future avocado prices using historical sales data.

---

## 🧩 Features

- Conducted **data cleaning** and **exploratory data analysis (EDA)** on historical avocado price datasets.
- Engineered new features such as **average price trends**, **region-based demand**, and **year-over-year changes**.
- Trained multiple **regression models** — Linear Regression, Lasso, Ridge, Random Forest, and XGBoost.
- Evaluated model performance using **R²**, **Mean Squared Error (MSE)**, and **Mean Absolute Error (MAE)**.
- Visualized regional price trends and feature correlations with **Matplotlib** and **Seaborn**.

---

## 🧠 Tech Stack

| Category                       | Tools / Libraries                      |
| ------------------------------ | -------------------------------------- |
| **Programming Language** | Python                                 |
| **Data Handling**        | Pandas, NumPy                          |
| **Visualization**        | Matplotlib, Seaborn                    |
| **Machine Learning**     | Scikit-learn, XGBoost                  |
| **Development Tools**    | Jupyter Notebook, VS Code, Git, GitHub |

---

## 📊 Dataset

- **File Name:** `avocado.csv`
- **Description:** Contains average avocado prices, region, type, and total volume data.
- **Source:** [Kaggle - Avocado Prices Dataset](https://www.kaggle.com/datasets/neuromusic/avocado-prices)

---

## ⚙️ Installation

1️⃣ Clone the repository and navigate to this project folder:

```bash
git clone https://github.com/krishna54250/Data-Science-and-Machine-Learning-Projects.git
cd Machine-Learning/Regression/2_Avocado-Price-Prediction
```

2️⃣ Install the required dependencies:

<pre class="overflow-visible!" data-start="3093" data-end="3136"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span>pip install -r requirements.txt
</span></span></code></div></div></pre>

3️⃣ Run the Jupyter Notebook:

<pre class="overflow-visible!" data-start="3168" data-end="3225"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span>jupyter notebook AvocadoPricePrediction.ipynb
</span></span></code></div></div></pre>

---

## 🚀 How to Run / Test

* Open the notebook, execute all cells sequentially.
* Modify the dataset or input features to test predictions on new data.
* Compare models based on evaluation metrics and visualization outputs.

---

## 📈 Results

* Achieved an **R² score of 0.89** with **Random Forest** and **XGBoost** models.
* Reduced Mean Squared Error (MSE) by **17%** through feature optimization.
* Delivered clear insights into **regional pricing patterns** and  **seasonal trends** .

---

## 📬 Author

👨‍💻 **Krishna**

🎓 Data Science & Machine Learning Enthusiast

🌐 [GitHub Profile](https://github.com/krishna54250)
