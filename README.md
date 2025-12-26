
# 📂 ProfileX — Smart Dataset Profiler & Preprocessor

**ProfileX** is an intelligent app for end-to-end data preprocessing. It helps you **profile, clean, encode, visualize, balance**, and **reduce dimensions** (using PCA) — all in a single interactive interface.

---

## 🚀 Features

✅ **Dataset Profiling**
	- Interactive dataset overview
	- Summary statistics, missing values, and data types

✅ **Data Cleaning**
	- Automatic detection and removal of duplicates
	- Missing value imputation
	- Label encoding for categorical features

✅ **Visualization**
	- Correlation heatmaps and bar charts
	- Histograms
	- PCA visualization with explained variance plots
	- Correlation of PCA components with target variable

✅ **Data Balancing**
	- Handle imbalanced datasets with **SMOTE (oversampling)** and **undersampling**
	- Compare before & after class distributions visually

✅ **Export Options**
	- Download processed dataset
	- Download PCA-transformed dataset

---

## 🧩 Tech Stack

- **Streamlit** — Interactive UI
- **Pandas**, **NumPy**, **Seaborn**, **Matplotlib** — Data wrangling & visualization
- **scikit-learn** — PCA, encoding, and sampling
- **ydata-profiling** — Exploratory Data Profiling

---

## ⚡️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/KarunyaGupta/ProjectX-Smart-Dataset-Profiler-Preprocessor.git
cd ProjectX-Smart-Dataset-Profiler-Preprocessor
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
streamlit run app.py
```

### 4. Using the App

- Upload your dataset (CSV format recommended)
- Explore profiling, cleaning, encoding, visualization, balancing, and PCA features
- Download processed or PCA-transformed datasets as needed

---

## 🛠️ Project Structure

- `app.py` — Main Streamlit application
- `utils.py` — Utility functions for data processing
- `requirements.txt` — List of required Python packages
- `test.ipynb` — Example/test notebook

---

## 🧹 Clean Code & Version Control

This project includes a `.gitignore` to keep your repository clean by ignoring:

- Python cache files (`__pycache__`, `*.pyc`)
- Jupyter checkpoints (`.ipynb_checkpoints`)
- Environment folders (`env/`, `.venv/`)
- System files (`.DS_Store`, `Thumbs.db`)
- VS Code settings (`.vscode/`)

---

## 📬 Feedback & Contributions

Feel free to open issues or submit pull requests to improve this project!
- **imblearn** — SMOTE and undersampling  

---

