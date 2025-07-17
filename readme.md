# California Housing Price Prediction 🏡

## Overview

This project predicts housing prices in California using machine learning techniques. It follows a complete end-to-end pipeline from data exploration to model evaluation, utilizing multiple regression algorithms to compare performance.

---

##  Dataset

- **Source**: California Housing Dataset (Scikit-Learn)
- **Features**: `MedInc`, `HouseAge`, `AveRooms`, `AveBedrms`, `Population`, `AveOccup`, `Latitude`, `Longitude`
- **Target**: `price` - Median House Price

---

## Project Highlights

| Phase                   | Details                                                            |
| ----------------------- | ------------------------------------------------------------------ |
| **Data Exploration**    | Summary statistics, correlation matrix, distribution and box plots |
| **Data Cleaning**       | Outlier handling using IQR capping                                 |
| **Feature Engineering** | Feature scaling with StandardScaler                                |
| **Modeling**            | Linear Regression, Random Forest, Gradient Boosting, XGBoost       |
| **Evaluation**          | RMSE, R² Score, Actual vs Predicted Plots, Residual Plots          |

---

##  Models Used

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

---

## Results Summary (Sample)

| Model             | RMSE ↓ | R² Score ↑ |
| ----------------- | ------ | ---------- |
| Linear Regression | \~0.72 | \~0.61     |
| Random Forest     | \~0.49 | \~0.81     |
| Gradient Boosting | \~0.52 | \~0.79     |
| XGBoost           | \~0.48 | \~0.82     |

---

##  How to Run

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `california.ipynb` in Jupyter Notebook and run all cells.

---

## Conclusion

XGBoost and Random Forest consistently provide better performance in terms of RMSE and R² Score compared to simpler models like Linear Regression.


---
