# Machine Learning Techniques Showcase 🚀

This repository contains a set of practical implementations of Machine Learning techniques, developed in an academic context. The project explores three main paradigms of Machine Learning: **Classification**, **Clustering**, and **Association Rules**, applied to real and distinct datasets.

## 📋 Project Overview

The goal of this project is to demonstrate the complete Data Science lifecycle: from Exploratory Data Analysis (EDA) and preprocessing to model implementation and evaluation.

The repository is divided into three case studies:

### 1. Classification: Body Performance 🏋️
* **Objective:** Predict an individual's physical performance class (A, B, C, or D) based on physiological metrics.
* **Data:** `bodyPerformance.csv` (age, gender, height, weight, body fat, systolic/diastolic pressure, grip strength, etc.).
* **Approach:** Correlation analysis, outlier treatment, and training supervised classification models.

### 2. Clustering: Formula 1 Drivers 🏎️
* **Objective:** Cluster F1 drivers based on performance-related characteristics to identify similar profiles without using predefined labels.
* **Data:** Historical data on races, drivers, constructors, and qualifying results (1950–Present).
* **Approach:** Feature engineering, dimensionality reduction (PCA), and clustering algorithms (K-Means, Hierarchical).

### 3. Association Rules: Fantasy Premier League ⚽
* **Objective:** Discover hidden patterns and relationships between players selected by users in the Fantasy league.
* **Data:** `merged_gw.csv` (Premier League gameweek data).
* **Approach:** Apriori algorithm to identify frequent itemsets and association rules (e.g., users who select player X tend to also select player Y).

## 🗂️ Repository Structure

```text
├── data/                   # Datasets (Raw and Processed)
├── notebooks/              # Jupyter Notebooks with analyses
│   ├── 01_eda_...          # Exploratory Analysis (Classification)
│   ├── 02_eda_...          # Exploratory Analysis (Clustering)
│   ├── 03_eda_...          # Exploratory Analysis (Association Rules)
│   ├── 04_imp_...          # Model Implementation (Classification)
│   ├── 05_imp_...          # Model Implementation (Clustering)
│   └── 06_imp_...          # Model Implementation (Association Rules)
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas & NumPy:** Data manipulation
- **Matplotlib & Seaborn:** Data visualization
- **Scikit-Learn:** Classification and clustering algorithms
- **Mlxtend:** Implementation of the Apriori algorithm (Association Rules)

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/Gusta11M/machine-learning-techniques-showcase.git
cd machine-learning-techniques-showcase
```

Install dependencies (using a virtual environment is recommended):

```bash
pip install -r requirements.txt
```

Explore the notebooks:  
Launch Jupyter Notebook or Jupyter Lab and navigate to the `notebooks/` folder.

## 👥 Authors

Project developed as part of the **Artificial Intelligence** course at **IPCA**.

- **Gustavo Marques** – https://www.linkedin.com/in/gustavo-marques-32424a2b3/ | https://github.com/Gusta11M  
- **Igor Costa** – https://github.com/mtcigor  
- **Gustavo Pereira** – https://github.com/a29852  
- **Hugo Cruz** - https://github.com/hugocruz13

This project is intended for educational and portfolio purposes.
