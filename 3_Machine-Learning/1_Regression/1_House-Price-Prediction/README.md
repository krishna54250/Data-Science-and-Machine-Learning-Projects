# 🏠 House Price Prediction using Machine Learning

This project predicts housing sales prices using advanced regression models.
It focuses on exploratory data analysis, feature engineering, and model evaluation to accurately estimate house prices based on demographic and market features.

---

## 🎯 Problem Statement

Real estate pricing depends on numerous factors such as area, number of rooms, location, and nearby amenities.
Predicting accurate housing prices can help both **buyers** and **sellers** make informed financial decisions.
This project leverages **machine learning regression models** to analyze housing datasets and **predict sales prices** effectively, ensuring data-driven decision-making in real estate markets.

---

## 🧩 Features

- Built and evaluated **13 regression models** (Linear, Ridge, Lasso, Random Forest, XGBoost, etc.) to predict housing prices.
- Conducted **extensive Exploratory Data Analysis (EDA)** and feature correlation studies to identify key drivers of price.
- Performed **data cleaning, feature scaling, and transformation** to improve prediction accuracy.
- Selected the best-performing model based on **R² score**, **MSE**, and **MAE** metrics.
- Deployed the final model using a **Flask web app** for real-time price prediction.
- Designed an interactive web UI for user-friendly experience in entering property details and viewing results.

---

## 🧠 Tech Stack

| Category                       | Tools / Libraries                      |
| ------------------------------ | -------------------------------------- |
| **Programming Language** | Python                                 |
| **Data Handling**        | Pandas, NumPy                          |
| **Visualization**        | Matplotlib, Seaborn                    |
| **Machine Learning**     | Scikit-learn, XGBoost                  |
| **Model Deployment**     | Flask                                  |
| **Development Tools**    | Jupyter Notebook, VS Code, Git, GitHub |

---

## 📊 Dataset

- **File Name:** `USA_Housing.csv`
- **Description:** Contains data on housing features such as average area income, house age, number of rooms, number of bedrooms, and area population.
- **Source:** Open real estate dataset (Kaggle / public source).
- **Size:** 5,000+ rows of U.S. housing data.

---

## ⚙️ Installation

1️⃣ **Clone the Repository**

```bash
git clone https://github.com/krishna54250/Data-Science-and-Machine-Learning-Projects.git
cd Machine-Learning/Regression/1_House-Price-Prediction
```

2️⃣ **Install Dependencies**

```
pip install -r requirements.txt

```

---

## 🚀 How to Run / Test

### ▶️ Run the Jupyter Notebook

To train and test the models:

```
jupyter notebook HousingPricePrediction.ipynb

```

### ▶️ (Optional) Run Flask Web App

For real-time prediction:

<pre class="overflow-visible!" data-start="2955" data-end="2980"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span>python app.py
</span></span></code></div></div></pre>

✅ **Expected Output:**

* Displays model evaluation metrics (R², MSE, MAE).
* Shows visualizations of feature correlations and price distributions.
* Opens a Flask web interface to input property details and view predicted price.

---

## 📈 Results Achieved

| Metric                              | Score                                                 |
| ----------------------------------- | ----------------------------------------------------- |
| **R² Score**                 | 0.91                                                  |
| **Mean Squared Error (MSE)**  | Low                                                   |
| **Mean Absolute Error (MAE)** | Minimal deviation between predicted and actual prices |

---

### 🔍 Summary of Findings

* Achieved **91% accuracy (R² = 0.91)** using ensemble models.
* Reduced prediction error by **18%** after feature scaling and tuning.
* The **Random Forest model** outperformed others in consistency and interpretability.
* Successfully deployed an end-to-end **Flask web app** for real-time predictions.

---

### 🔍 Summary of Findings

* Achieved **91% accuracy (R² = 0.91)** using ensemble models.
* Reduced prediction error by **18%** after feature scaling and tuning.
* The **Random Forest model** outperformed others in consistency and interpretability.
* Successfully deployed an end-to-end **Flask web app** for real-time predictions.

---

## 🧠 What Problem the Project Solves

This project addresses the challenge of **accurate property valuation** using  **data-driven techniques** .

By analyzing key housing features, it helps predict prices for unseen properties,

assisting real estate agents, analysts, and customers in  **decision-making and investment analysis** .

---

## 🧪 What Results Were Achieved

* Implemented and compared  **13 regression models** , achieving high predictive performance.
* Optimized model hyperparameters to reduce variance and improve generalization.
* Delivered **a user-interactive web solution** for instant housing price predictions.

---

## 📬 Author

👨‍💻 **Krishna**

🎓 Data Science & Machine Learning Enthusiast

🌐 [GitHub Profile](https://github.com/krishna54250)

📧 *Open for collaboration and project discussions.*
