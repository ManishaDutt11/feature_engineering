# 🧪 Feature Engineering

A hands-on collection of Jupyter notebooks covering essential **feature engineering** techniques used to prepare raw data for machine learning models — including handling missing values, dealing with imbalanced datasets, outlier detection, and encoding categorical data. Most examples use the classic **Titanic dataset**.

## 📚 Contents

| Notebook | Description |
|---|---|
| [`1_Handling_missing_value.ipynb`](./1_Handling_missing_value.ipynb) | Techniques to detect and handle missing values in a dataset (imputation, dropping, etc.). |
| [`2_Handling_imbalance_datset.ipynb`](./2_Handling_imbalance_datset.ipynb) | Methods to deal with class imbalance in datasets, such as undersampling and oversampling. |
| [`3_Smote.ipynb`](./3_Smote.ipynb) | Using **SMOTE** (Synthetic Minority Oversampling Technique) to balance imbalanced datasets. |
| [`4_boxplot.ipynb`](./4_boxplot.ipynb) | Using boxplots to visualize data distribution and detect outliers. |
| [`5_nominal_data_encoding.ipynb`](./5_nominal_data_encoding.ipynb) | Encoding nominal (unordered categorical) data, e.g., One-Hot Encoding. |
| [`6_Label_encoding.ipynb`](./6_Label_encoding.ipynb) | Converting categorical labels into numeric form using Label Encoding. |
| [`7_Ordinal_encoding.ipynb`](./7_Ordinal_encoding.ipynb) | Encoding ordinal (ordered categorical) data while preserving rank order. |

## 📊 Dataset

- [`Titanic-Dataset.xls`](./Titanic-Dataset.xls) — the well-known Titanic passenger dataset, used throughout several notebooks to demonstrate real-world feature engineering scenarios.

## 🎯 Purpose

Feature engineering is one of the most important steps in any machine learning pipeline — the quality of your features often matters more than the choice of model. This repository is a personal learning log documenting my practice with core feature engineering concepts, built one notebook at a time.

## 🛠️ Tech Stack

- **Python 3**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Imbalanced-learn** (for SMOTE)
- **Matplotlib / Seaborn** (for visualizations like boxplots)

## 🚀 Getting Started

### Prerequisites

Install the required libraries:

```bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn jupyter
```

### Running the notebooks

1. Clone the repository:
   ```bash
   git clone https://github.com/ManishaDutt11/feature_engineering.git
   cd feature_engineering
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open any `.ipynb` file and run the cells in order.

## 📈 Topics Covered

- Handling missing data (imputation strategies, dropping rows/columns)
- Balancing imbalanced datasets (undersampling, oversampling, SMOTE)
- Outlier detection using boxplots
- Encoding categorical variables:
  - Nominal encoding (One-Hot Encoding)
  - Label encoding
  - Ordinal encoding

## 🤝 Contributing

This is primarily a personal learning repository, but suggestions and improvements are always welcome! Feel free to open an issue or submit a pull request.


## 👩‍💻 Author

**Manisha Dutt**
GitHub: [@ManishaDutt11](https://github.com/ManishaDutt11)

---

⭐ If you find this helpful, consider starring the repo!
