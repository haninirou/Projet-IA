# 🚗 Projet-IA — Car Price Prediction

A machine learning project that analyzes a dataset of used cars and builds models to **predict a car's price** from its characteristics. The full workflow (data exploration, preprocessing, modeling and evaluation) is documented in a single Jupyter Notebook.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Repository Structure](#-repository-structure)
- [Dataset](#-dataset)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Methodology](#-methodology)
- [Results](#-results)
- [Possible Improvements](#-possible-improvements)
- [Author](#-author)

---

## 🔎 Overview

The goal of this project is to apply machine learning techniques to a real-world regression problem: estimating the market price of a car based on features such as brand, model, year, mileage, fuel type, and more.

The project covers:

- Loading and inspecting the dataset
- Exploratory data analysis (EDA) and visualization
- Data cleaning and feature preparation
- Training and comparing regression models
- Evaluating model performance

## 📁 Repository Structure

```
Projet-IA/
├── car_price_prediction.csv   # Dataset used for training and evaluation
├── projet (1).ipynb           # Main notebook (analysis + modeling)
├── requirements.txt           # Python dependencies
├── .gitignore
└── README.md
```

## 📊 Dataset

**File:** `car_price_prediction.csv`

The dataset contains one row per car listing, with a set of descriptive features and the target variable (**price**).

> 💡 *Add details here: number of rows/columns, a description of each column, and the source of the data (e.g. Kaggle link).*

## 🛠 Tech Stack

| Library | Purpose |
|---|---|
| `pandas` | Data loading and manipulation |
| `numpy` | Numerical computing |
| `matplotlib` | Data visualization |
| `seaborn` | Statistical visualization |
| `scikit-learn` | Preprocessing, ML models, and evaluation |
| `statsmodels` | Statistical modeling and analysis |
| `scipy` | Scientific and statistical functions |
| `jupyter` / `ipykernel` | Running the notebook |

## ⚙️ Installation

**1. Clone the repository**

```bash
git clone https://github.com/haninirou/Projet-IA.git
cd Projet-IA
```

**2. (Recommended) Create a virtual environment**

```bash
python -m venv venv

# Linux / macOS
source venv/bin/activate

# Windows
venv\Scripts\activate
```

**3. Install the dependencies**

```bash
pip install -r requirements.txt
```

## ▶️ Usage

Launch Jupyter and open the notebook:

```bash
jupyter notebook "projet (1).ipynb"
```

Then run the cells in order (**Kernel → Restart & Run All**). Make sure `car_price_prediction.csv` stays in the same folder as the notebook so it can be loaded correctly.

## 🧪 Methodology

1. **Data exploration** — inspect the structure, types, missing values, and statistical summary of the dataset.
2. **Visualization** — study distributions, correlations, and relationships between features and price.
3. **Preprocessing** — clean the data, handle missing values and outliers, encode categorical variables, and scale features where needed.
4. **Modeling** — train regression models to predict car prices.
5. **Evaluation** — compare models using standard regression metrics (e.g. MAE, RMSE, R²).

## 📈 Results

> 💡 *Add your final results here, for example:*
>
> | Model | MAE | RMSE | R² |
> |---|---|---|---|
> | Linear Regression | – | – | – |
> | Random Forest | – | – | – |

## 🚀 Possible Improvements

- Hyperparameter tuning with `GridSearchCV` / `RandomizedSearchCV`
- Trying additional models (Gradient Boosting, XGBoost, etc.)
- More advanced feature engineering
- Deploying the best model as a small web app (Streamlit / Flask)

## 👤 Author

**haninirou** — [GitHub profile](https://github.com/haninirou)

---

⭐ If you find this project useful, feel free to give it a star!