# Medical Insurance Cost Prediction using Linear Regression

An end-to-end Machine Learning pipeline demonstrating raw data preprocessing and regression modeling using Python, Pandas, and Scikit-Learn.

## 📌 Project Overview
The objective of this project is to predict individual medical insurance charges based on demographic and health indicators (age, BMI, smoking habits, region, etc.).

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-Learn
- **Visualization:** Matplotlib

## ⚙️ Workflow & Preprocessing
1. **Raw Data Handling:** Assigned explicit schema headers to an unlabelled raw dataset.
2. **Data Cleaning:** Imputed missing values (NaN conversion & median strategy) and removed duplicates.
3. **Categorical Encoding:** Converted categorical variables (`sex`, `region`) into numeric indicators via One-Hot Encoding (`pd.get_dummies`).
4. **Feature Scaling:** Applied `StandardScaler` to normalize feature distributions.
5. **Model Training:** Trained a Multiple Linear Regression model with an 80/20 train-test split.

## 📊 Key Results & Metrics
- **R² Score:** ~0.807 (Explains 80.7% of the variance in charges)
- **Root Mean Squared Error (RMSE):** ~5956.34
- **Mean Absolute Error (MAE):** ~4177.05

### Feature Importance Insights
- **Smoker Status:** The strongest positive driver of healthcare costs.
- **Age & BMI:** Show consistent positive correlation with medical expenses.
- **Sex & Region:** Exhibit minimal impact on overall insurance charges.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/<repo-name>.git
   cd <repo-name>
