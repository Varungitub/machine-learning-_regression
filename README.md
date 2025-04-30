# 💎 Diamond Price Prediction

This project uses machine learning techniques to predict the prices of diamonds based on various features such as carat, cut, color, clarity, and more. It involves data exploration, preprocessing, model building, and evaluation.

---

## 📁 Files in This Repository

- `DiamondPrice.ipynb`: The main Jupyter notebook containing data analysis, visualizations, and model training steps.
- `diamonds.csv`: Dataset containing features and prices of diamonds.

---

## 📊 Dataset

The dataset contains the following features:

- `carat`: Weight of the diamond.
- `cut`: Quality of the cut (Fair, Good, Very Good, Premium, Ideal).
- `color`: Diamond color grade (from J - worst to D - best).
- `clarity`: Diamond clarity (I1 - worst, to IF - best).
- `depth`, `table`: Physical dimensions of the diamond.
- `x`, `y`, `z`: Dimensions in mm.
- `price`: Target variable, the price of the diamond in USD.

---

## 🔍 What the Project Does

1. **Loads the dataset**
2. **Explores and visualizes the data**
3. **Handles missing values (if any)**
4. **Performs feature encoding for categorical variables**
5. **Builds a regression model to predict price**
6. **Evaluates the model using metrics like R², MAE, etc.**
