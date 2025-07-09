# 🏡💵 House Price Prediction Project (Regression) - ML

## 📍 Overview

This project applies three powerful machine learning algorithms—**Decision Tree**, **Random Forest**, and **Gradient Boosting**—to predict housing prices based on features such as size, location, and amenities. The goal is to build accurate models and compare their performance using regression metrics: **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R-squared (R²)**.

---

## 📁 Project Structure

```bash
.
├── data/
│   ├── train.csv
│   ├── test.csv
│   ├── data_description.txt
├── notebooks/
│   ├── house_price.ipynb
├── output/
│   └── dt_output.png
│   ├── rf_output.png
│   ├── gb_output.png
├── src
├── README.md
└── requirements.txt
```

## 🧠 Models Used
**Decision Tree**	    `Simple tree-based model that splits data based on feature thresholds`

**Random Forest**	    `Ensemble of Decision Trees that reduces variance and overfitting`

**Gradient Boosting**	`Boosted ensemble model that sequentially corrects prediction errors`

## 🚀 How to run

1. `Install dependencies`
 
    ```bash
    pip install -r requirements.txt
    ```
2. `Launch Jupyter Notebook`

    ```bash
    jupyter notebook
    ```
    
3. `Open notebooks/house_price.ipynb`