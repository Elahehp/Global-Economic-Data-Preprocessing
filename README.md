# Global Economic Data Preprocessing 🌍🐍


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Elahehp/Global-Economic-Data-Preprocessing/blob/main/Colab.ipynb)

## 📌 Project Overview
This project focuses on the **Data Engineering** and **Exploratory Data Analysis (EDA)** of Global GDP per Capita. Economic datasets from international sources (IMF, World Bank, and UN) are often inconsistent and contain extreme wealth outliers that skew global averages. 

I developed a Python-based preprocessing pipeline to merge these disparate sources and transform raw financial data into a high-quality, "analysis-ready" format.

## 🛠 Tech Stack
- **Language:** Python
- **Environment:** Google Colab
- **Libraries:** - `Pandas`: Data merging, cleaning, and normalization.
  - `NumPy`: Numerical operations and array handling.
  - `Matplotlib` & `Seaborn`: Statistical data visualization.

## ⚙️ Key Technical Features
- **Multi-Source Integration:** Successfully merged estimates from the IMF, World Bank, and UN to provide a multi-perspective economic view.
- **Data Normalization:** Performed string normalization (stripping whitespace and standardizing country names) to ensure 100% join accuracy.
- **Outlier Detection (IQR Method):** Utilized the **Interquartile Range (IQR)** method to identify and isolate economic outliers—countries with significantly higher GDP per capita (e.g., Luxembourg, Ireland, Norway).
- **Data Integrity:** Handled missing values and performed data type conversions to ensure future predictive models aren't skewed by "noisy" data.



---
### 🔗 Quick Link
- [**Back to Main Portfolio**](https://github.com/Elahehp)
