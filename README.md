# Exploratory Data Analysis (EDA) Repository

This repository contains a collection of Exploratory Data Analysis (EDA) projects and tutorials. EDA is a crucial step in the data science workflow, involving the examination and visualization of data to uncover patterns, anomalies, and insights before applying machine learning models or further analysis.

## Table of Contents
- [Overview](#overview)
- [Installation and Setup](#installation-and-setup)
- [Folder Structure](#folder-structure)
- [Projects and Datasets](#projects-and-datasets)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
This folder serves as a hub for various EDA exercises and projects using real-world datasets. Each subfolder focuses on a specific dataset or theme, providing Jupyter notebooks that demonstrate data cleaning, visualization, feature engineering, and initial modeling techniques.

Key technologies and libraries used:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Installation and Setup
1. Clone or download this repository.
2. Make a virtual environment 
    ```
    conda create -p venv python==3.10.0
    conda activate venv/
    ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```
5. Navigate to the desired subfolder and open the `.ipynb` files.

### Dependencies
The `requirements.txt` file includes the following packages:
- pandas: Data manipulation and analysis
- ipykernel: Jupyter kernel for Python
- seaborn: Statistical data visualization
- openpyxl: Reading/writing Excel files
- scikit-learn: Machine learning library

## Folder Structure
```
Exploratory Data Analysis/
├── .gitignore
├── README.md
├── requirements.txt
├── EDA and Feature Engineering/
│   ├── Flight_Price_Prediction.ipynb
│   ├── flight_price.xlsx
│   └── Notes.md
├── Google PlayStore Dataset/
│   ├── Google_PlayStore_self_tried.ipynb
│   ├── googleplaystore.csv
│   ├── tutorial_cleaned_dataset.csv
│   ├── Tutorial_part2.ipynb
│   └── Tutorial.ipynb
└── Red Wine Dataset/
    ├── Introduction_To_EDA.ipynb
    └── winequality-red.csv
```

## Projects and Datasets

### 1. EDA and Feature Engineering
This folder focuses on flight price prediction, demonstrating advanced EDA techniques and feature engineering.

- **Flight_Price_Prediction.ipynb**: A comprehensive notebook covering data exploration, cleaning, feature engineering, and predictive modeling for flight prices.
- **flight_price.xlsx**: The raw dataset containing flight pricing information.
- **Notes.md**: Detailed notes on Pandas APIs, string operations, and best practices for data manipulation.

### 2. Google PlayStore Dataset
Exploration of Google Play Store app data, including data cleaning, visualization, and analysis of app ratings, categories, and trends.

- **Tutorial.ipynb**: Introductory tutorial on EDA for the Play Store dataset.
- **Tutorial_part2.ipynb**: Advanced analysis and modeling techniques.
- **Google_PlayStore_self_tried.ipynb**: Personal exploration and custom analysis of the dataset.
- **googleplaystore.csv**: Raw Play Store app data.
- **tutorial_cleaned_dataset.csv**: Preprocessed version of the dataset for analysis.

### 3. Red Wine Dataset
Analysis of red wine quality data, focusing on physicochemical properties and their relationship to wine quality ratings.

- **Introduction_To_EDA.ipynb**: Beginner-friendly introduction to EDA concepts using the wine dataset.
- **winequality-red.csv**: Dataset containing chemical properties and quality ratings of red wines.

## Usage
1. Choose a project folder based on your interest or learning goals.
2. Open the corresponding Jupyter notebook(s).
3. Follow the step-by-step analysis in the notebooks.
4. Experiment with the code, modify visualizations, or apply techniques to your own datasets.
5. Refer to the Notes.md file in the EDA and Feature Engineering folder for additional insights on data manipulation.

### Running Notebooks
- Ensure Jupyter is installed and running.
- Open the `.ipynb` files in your VS Code.
- Execute cells sequentially to follow the analysis.
- Some notebooks may require additional data preprocessing or library installations.

---

Happy Coding!
