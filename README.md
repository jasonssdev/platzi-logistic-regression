# Logistic Regression Course with Python 📊

[![Python Version](https://img.shields.io/badge/Python-3.12+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Platform](https://img.shields.io/badge/platform-Mac%20%7C%20Linux%20%7C%20Windows-lightgrey.svg)]()
[![Status](https://img.shields.io/badge/status-learning-informational.svg)]()
[![Made With](https://img.shields.io/badge/made%20with-💚%20by%20Jason-lightblue.svg)]()

This repository contains all materials, code, and notes for the **Logistic Regression with Python** course on [Platzi](https://platzi.com/cursos/regresion-logistica/).

## 📁 Project Structure

```bash
platzi-logistic-regression/
│
├── data/               # Dataset for the course
│   ├── raw/            # Original raw data
│   └── processed/      # Cleaned and processed data
│
├── notebooks/          # Jupyter notebooks with examples, theory, and exercises
│
├── references/         # Theoretical resources and additional materials
│
├── utils/              # Helper functions (paths, utilities, etc.)
│   ├── __init__.py
│   └── paths.py
│
├── environment.yml     # Conda environment specification
├── pyproject.toml      # Project metadata and dependencies (PEP 621)
├── .gitignore          # Git ignore rules
├── LICENSE             # Apache License 2.0
└── README.md           # This file
```

## 🚀 Installation

Clone the repository and create the Conda environment:

```bash
git clone https://github.com/jasonssdev/platzi-logistic-regression.git
cd platzi-logistic-regression
conda env create -f environment.yml
conda activate platzi-logistic
```

Alternatively, use `venv` and `pip`:

```bash
python -m venv .venv
# macOS / Linux
a source .venv/bin/activate
# Windows
.venv\\Scripts\\activate
pip install -r requirements.txt
```

## 🧠 Key Technologies & Libraries

* **Data Handling:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Modeling:** `statsmodels`, `scikit-learn`
* **Interactive Environment:** `jupyterlab`, `notebook`, `ipywidgets`

## 📌 Course Objectives

1. Understand the fundamentals of logistic regression.
2. Implement binary classification models in Python.
3. Evaluate model performance using various metrics.
4. Visualize results and interpret model outcomes.

## 🧑‍💻 Author

**Jason**
📧 [jasonssdev@gmail.com](mailto:jasonssdev@gmail.com)
🐙 [GitHub Profile](https://github.com/jasonssdev)

---

> This repository will be continuously updated throughout the course. Feel free to follow along and contribute!
