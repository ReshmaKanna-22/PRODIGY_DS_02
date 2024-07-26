# Exploratory Data Analysis (EDA) on Titanic Dataset #

## Introduction: ##
This analysis aims to uncover patterns and relationships within the Titanic dataset to understand factors affecting passenger survival. The dataset includes information such as passenger class, age, sex, and fare.

## Methodology: ##

### 1. Data Loading: ###
- Pandas, matplotlib, and seaborn libraries are imported.
- The training, testing, and gender submission datasets are loaded.

### 2. Data Overview: ###
- Summary statistics and data types are displayed.
- Columns with missing values are identified.

### 3. Missing Values: ###
- Missing values in each column are counted.
- Missing values are visualized using heatmaps.

### 4. Univariate Analysis: ###
- The distribution of the 'Survived' variable is plotted.
- The distributions of 'Pclass' and 'Sex' are analyzed.
- The age distribution is visualized with a histogram and KDE.

### 5. Bivariate Analysis: ###
- The survival rate by 'Sex' and 'Pclass' is examined.
- Age distribution by survival status is analyzed.

### 6. Categorical Analysis: ###
- Survival rates by 'Embarked' are investigated.
- Pair plots are created for 'Pclass', 'Age', 'SibSp', 'Parch', and 'Fare'.

### 7. Multivariate Analysis: ###
- A correlation heatmap is generated.
- Survival by 'Age' and 'Sex' is analyzed with box plots.
- Fare distribution by 'Pclass' and survival status is examined.

## Results: ##
- Higher survival rates are observed for females and passengers in first class.
- Younger passengers have higher survival rates.
- Passengers who embark from certain locations have different survival rates.
- There are strong correlations between some features, indicating potential interactions affecting survival.
