# 🍷 Wine Quality Prediction

A machine learning project to predict wine quality based on physicochemical properties, built with Python in a Jupyter Notebook environment.

---

## 📌 Overview

Wine quality assessment traditionally relies on human experts — a process that is both time-consuming and subjective. This project automates that process by training machine learning models on chemical measurements such as acidity, alcohol content, pH, and sulfur dioxide levels to predict the quality score of a wine sample.

---

## 🚀 Features

- In-depth Exploratory Data Analysis (EDA) with visualizations
- Feature correlation analysis to identify key quality drivers
- Data preprocessing and normalization
- Training and comparing multiple ML classification models
- Model evaluation with accuracy, precision, recall, and F1-score
- Feature importance analysis

---

## 🧪 Dataset

The project uses the well-known **UCI Wine Quality Dataset**, which contains physicochemical test results for red and/or white wine samples. Each sample is labeled with a quality score from 0 to 10.

**Input Features include:**
- Fixed acidity, Volatile acidity, Citric acid
- Residual sugar, Chlorides
- Free & Total sulfur dioxide
- Density, pH, Sulphates
- Alcohol content

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Jupyter Notebook | Interactive development |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Scikit-learn | ML models & evaluation |
| Matplotlib / Seaborn | Data visualization |

---

## 📁 Project Structure

```
Wine-Quality-Prediction/
│
├── notebooka85004353b.ipynb   # Main notebook: EDA, modeling, evaluation
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Run the Notebook

```bash
git clone https://github.com/alirezaderavi/Wine-Quality-Prediction.git
cd Wine-Quality-Prediction
jupyter notebook notebooka85004353b.ipynb
```

---

## 📊 Workflow

1. **Data Loading** — Import and inspect the wine quality dataset
2. **EDA** — Visualize distributions, correlations, and class balance
3. **Preprocessing** — Handle missing values, scale features, encode labels
4. **Modeling** — Train classification models (e.g. Random Forest, SVM, KNN)
5. **Evaluation** — Compare models using accuracy, F1-score, confusion matrix
6. **Insights** — Identify the chemical properties most influential to quality

---

## 🔍 Key Insights

- **Alcohol content** tends to have the strongest positive correlation with wine quality
- **Volatile acidity** negatively impacts perceived quality
- Ensemble methods like Random Forest generally outperform simpler classifiers on this dataset

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open a pull request or issue.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Alireza Deravi**  
[GitHub](https://github.com/alirezaderavi)
