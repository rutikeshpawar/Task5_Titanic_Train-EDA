# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Objective
The goal of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to identify patterns, relationships, and trends that may have influenced passenger survival.

## 📂 Dataset
- **Source**: Kaggle Titanic Competition Dataset ([link](https://www.kaggle.com/c/titanic/data))
- **File used**: `train.csv`
- **Rows**: 891 passengers
- **Columns**: 12 features (including target variable `Survived`)

## 🛠 Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 EDA Steps
1. **Data Understanding**: Checked data types, missing values, and basic statistics.
2. **Univariate Analysis**: Explored individual variables (histograms, countplots).
3. **Bivariate Analysis**: Compared variables with survival status.
4. **Multivariate Analysis**: Used heatmaps and combined category analysis.
5. **Handling Missing Values**: Filled or flagged missing data for Age, Embarked, and Cabin.
6. **Visualization**: Created barplots, boxplots, scatterplots, and KDE plots.
7. **Summary of Findings**: Documented key patterns and insights.

## 🔍 Key Insights
- **Gender**: Females had ~74% survival rate vs ~19% for males.
- **Pclass**: Higher classes had better survival chances (Pclass 1 ~63%, Pclass 3 ~24%).
- **Fare**: Higher fares correlated with better survival rates.
- **Age**: Children under 10 had slightly better chances of survival.
- **Embarked**: Passengers from Cherbourg had higher survival rates.
- **Family Size**: Small families (2–4 members) survived more often than solo or large families.

## 📄 Deliverables
- `Titanic_EDA.ipynb` → Jupyter Notebook with code, plots, and observations.
- `Titanic_EDA.pdf` → PDF report exported from the notebook.
- `train.csv` → Dataset used for the analysis.

## 👩‍💻 Author
**Rutikesh Pawar** 

