# PRODIGY_ML_Task01
A Machine Learning project that predicts house prices using Multiple Linear Regression based on living area, number of bedrooms, and number of bathrooms. Developed as part of the Prodigy Infotech Machine Learning Internship – Task 01 using Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

## 📌 Task Overview
This project is **Task-01** of the **Prodigy InfoTech Machine Learning Internship**.

**Objective:** Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.

## 📊 Dataset
[House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) (Kaggle)

Download `train.csv` from the link above and use it when running the notebook.

## 🧠 Features Used
| Feature | Description |
|---|---|
| `GrLivArea` | Above-ground living area (square footage) |
| `BedroomAbvGr` | Number of bedrooms above ground |
| `TotalBathrooms` | Full baths + 0.5 × half baths |
| `SalePrice` | Target variable (house price) |

## 🛠️ Tech Stack
- Python 3
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Google Colab / Jupyter Notebook

## 🚀 How to Run
1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/PRODIGY_ML_01.git
   cd PRODIGY_ML_01
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Open `PRODIGY_ML_01_House_Price_Prediction.ipynb` in Jupyter Notebook or Google Colab.
4. Download `train.csv` from the [Kaggle dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) and upload it when prompted in the notebook.
5. Run all cells in order.

## 📈 Workflow
1. Load and inspect the dataset
2. Select relevant features (square footage, bedrooms, bathrooms)
3. Handle missing values
4. Exploratory data analysis (scatter plots, box plots, correlation heatmap)
5. Train-test split (80/20)
6. Train a `LinearRegression` model using scikit-learn
7. Evaluate using MSE, RMSE, MAE, and R² score
8. Visualize actual vs. predicted prices and residuals
9. Predict price for a sample house

## 📉 Model Evaluation Metrics
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

## 🔮 Future Improvements
- Include additional features (`OverallQual`, `GarageCars`, `YearBuilt`, etc.)
- Handle outliers in `GrLivArea`
- Compare with regularized models (Ridge, Lasso) or tree-based models

## 📄 License
This project is for educational purposes as part of the Prodigy InfoTech internship.

## 🙋 Author
Created as part of the **Prodigy InfoTech ML Internship** — Task 01.
