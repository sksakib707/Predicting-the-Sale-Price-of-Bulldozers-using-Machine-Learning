# Predicting-the-Sale-Price-of-Bulldozers-using-Machine-Learning
This project builds a Machine Learning model to predict the future sale price of used bulldozers, using the dataset from the Kaggle Bluebook for Bulldozers competition. The goal is to develop a high-quality regression model that can estimate auction prices based on historical equipment sale data.
##  Project Overview

The goal of this project is to build a **regression model** that predicts the sale price of a bulldozer using a large dataset from the **Kaggle Blue Book for Bulldozers** competition.

This project demonstrates:

- Comprehensive **data cleaning and preprocessing**
- **Handling large time-series datasets**
- Exploratory Data Analysis (EDA)
- Feature engineering (dates, categories, missing values)
- RandomizedSearchCV
- Training machine learning models:
  - Random Forest Regressor   
- Hyperparameter tuning
- Evaluation using:
  - RMSLE (Root Mean Squared Log Error)
  - R² Score
  - MAE (Mean Absolute Error)

---

##  Tech Stack

- **Python 3**
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

---

##  Dataset

The dataset used is the **Blue Book for Bulldozers** dataset from **Kaggle**, which contains auction data for thousands of bulldozers.

It includes features such as:

- Model ID  
- Usage hours  
- Year made  
- Product size  
- Auction date  
- Machine condition  
- Hydraulic options  
- And more…

This dataset is ideal for learning **regression modeling** and **feature engineering**.

---

##  Model Performance

After extensive experimentation, the best-performing model achieved:

-  **Low RMSLE error**  
-  Strong generalization on validation data  
-  Improved accuracy with feature engineering and time-based split  

(Random Forest Regressor often performs strongly on this dataset.)

---

##  Project Structure
```
 bulldozer-price-prediction
├── data/ # Dataset (ignored in Git)
├── notebooks/ # Jupyter notebooks for EDA & training
├── models/ # Saved trained models
├── README.md # Project documentation
├── requirements.txt # Dependencies
└── main.ipynb # End-to-end pipeline
```
---
##  How to Run This Project

Follow these steps to run the project on your local machine:

1. **Clone the repository**
```bash
git clone https://github.com/sksakib707/Predicting-the-Sale-Price-of-Bulldozers-using-Machine-Learning.git
cd Predicting-the-Sale-Price-of-Bulldozers-using-Machine-Learning
```
2.**Create a virtual environment**
```bash
python -m venv env
# Activate the environment
# Windows:
env\Scripts\activate
# macOS/Linux:
source env/bin/activate
```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
4. **Download the dataset**
   * Get the data from Kaggle Blue Book for Bulldozers
   * Place the files inside the `data/` folder
5. **Run the project**
   * Open `main.ipynb` or notebooks in `notebooks/` folder
  ---
  
##  Future Improvements

- Implement advanced models (XGBoost, LightGBM, CatBoost)  
- Add model interpretability (SHAP values)   

---

##  Author

**Sheikh Shadman Sakib**    

[GitHub](https://github.com/sksakib707) • [LinkedIn](https://www.linkedin.com/in/sheikh-shadman-sakib)

---

##  License

This project is for **educational and research purposes only**.
