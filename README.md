# 🛒 Walmart Sales Prediction

This project focuses on predicting **weekly sales** for Walmart stores using historical sales data. The analysis involves data preprocessing, feature engineering, and building machine learning models to forecast sales trends effectively.

## 🚀 Project Overview

- **Objective**: Predict weekly sales based on historical data.
- **Dataset**: Included in the repository under `dataset/`.
- **Main Files**:
  - `report.ipynb`: Jupyter Notebook with code and analysis.
  - `report.html`: HTML version of the notebook for easy viewing.
  - `dataset/`: Folder containing raw data for model training and evaluation.

## 📁 Repository Structure

```plaintext
├── dataset/                # Raw data for Walmart sales
├── report.html             # HTML version of the report notebook
├── report.ipynb            # Jupyter Notebook with full analysis and model building
└── README.md               # Project documentation
```

## 🔧 Installation
Clone the repository:
```bash
git clone https://github.com/Siddharth-Chandel/Walmart-sales-prediction.git
cd Walmart-sales-prediction
```

## 🛠️ Project Workflow
1. Data Preprocessing:
- Merged sales, store, and features datasets.
- Handled missing values, feature encoding, and normalization.

2. Exploratory Data Analysis (EDA):
- Analyzed weekly sales trends.
- Visualized feature importance and holiday effects.

3. Model Building:
- Tested and compared models:
  - Linear Regression
  - KNN
  - Polynomial Regressor
  - Random Forest Regressor
  - SVM

4. Model Evaluation:
- Evaluated models using:
  - Root Mean Square Error (RMSE)

## 📊 Results
| Model                   |	 RMSE         |
| ----------------------  | ------------- |
| Linear Regression	      | 524418        |
| KNN                     | 476625        |
| Polynomial Regressor    | 473423        |
| Random Forest Regressor | 125896        |
| SVM                     | 575594        |

The **Random Forest Regressor** achieved the best performance.

## 📈 Visualizations
Sales Trends: Insights into sales patterns over time.
Feature Importance: Identified key contributors to sales prediction.
Predictions vs Actuals: Visual comparison of predicted and true sales.

## 💻 How to Run
Open and run the report.ipynb notebook step-by-step using Jupyter Notebook or Jupyter Lab:

```bash
jupyter notebook report.ipynb
```

Alternatively, view the report directly in report.html.

$$ 🤝 Contributions
Contributions are welcome! If you'd like to improve the project:

1. Fork the repository.
2. Create a new branch: git checkout -b feature-branch.
3. Submit a pull request.

##📬 Contact
Siddharth Chandel

- Email: siddharthchandel2004@gmail.com
- LinkedIn: [siddharth-chandel-001097245](https://www.linkedin.com/in/siddharth-chandel-001097245/)
