## 🏡 California Housing Data Analysis (EDA)
This Jupyter Notebook (california.ipynb) contains an exploratory data analysis (EDA) of the California housing dataset 📊. It demonstrates data cleaning, preprocessing, feature engineering, and correlation analysis to explore the relationships between various housing features across California 🌉.Our goal is to predict the price of houses using this dataset.

### 📦 Dataset Description
The dataset provides information about housing blocks in California, with the following features:

📍 longitude: How far west a house is located (higher = further west)

📍 latitude: How far north a house is located (higher = further north)

🏠 housing_median_age: Median age of homes (lower = newer)

🚪 total_rooms: Total number of rooms per block

🛏️ total_bedrooms: Total number of bedrooms per block

👨‍👩‍👧‍👦 population: Number of residents in a block

🏘️ households: Number of household units in a block

💵 median_income: Median income (in tens of thousands of USD)

🏷️ median_house_value: Median house value (in USD)

🌊 ocean_proximity: Distance from the ocean

## 📘 Notebook Overview
### 🔍 1. Data Loading & Exploration
Import libraries: NumPy, Pandas, Seaborn, Matplotlib

Load the dataset from housing.csv

View data structure and initial rows

### 🧹 2. Data Cleaning
Handle missing values by removing rows with NA

Confirm dataset is cleaned and ready

### 🛠️ 3. Feature Engineering
One-hot encode the ocean_proximity categorical feature

Merge the encoded features with the dataset

Drop the original ocean_proximity column

### 📊 4. Data Analysis
#### Compute and analyze correlation matrix 🔗

Correlation heatmap via Seaborn

### 🔄 5. Transformations
Apply log transformations to skewed features (preparation for modeling/visualization)

### 🧩 Dependencies
Make sure you have the following installed:

Python 3.x 🐍

Jupyter Notebook 📓

pandas, numpy, matplotlib, seaborn

Install everything with:
 
```
pip install jupyter pandas numpy matplotlib seaborn
```
### ▶️ Usage
Clone the repo or download the notebook

Place the housing.csv file in the same directory

Launch Jupyter Notebook and run the cells in order

### 💡 Notes
Demonstrates a typical EDA pipeline in data science

Uses correlation analysis to reveal relationships between features

One-hot encoding for categorical features

Missing values are addressed via row removal (dropna)
