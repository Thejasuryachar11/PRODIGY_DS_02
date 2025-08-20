# PRODIGY_DS_02 - Exploratory Data Analysis (Titanic Dataset)

## 🎯 Objective
Perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset. Explore the relationships between variables and identify patterns and trends in the data.

## 🛠 Workflow
1. **Load Data**
   - Used Titanic dataset from Kaggle.
   - Inspected dataset shape and datatypes.

2. **Data Cleaning**
   - Handled missing values (`Age`, `Embarked`).
   - Dropped unnecessary columns (`PassengerId`, `Name`, `Ticket`, `Cabin`).
   - Converted categorical variables (`Sex`, `Embarked`) into numerical if required.

3. **Exploratory Analysis**
   - Survival distribution overall and by gender, class, age group.
   - Survival vs family size (SibSp + Parch).
   - Embarked port survival comparison.
   - Correlation heatmap for numerical features.

4. **Visualizations**
   - Bar plots, histograms, count plots, heatmaps.
   - Showed clear survival patterns.

5. **Key Insights**
   - Females had a much higher survival rate than males.
   - 1st class passengers had the highest chance of survival.
   - Children (Age < 10) had better survival rates.
   - Passengers embarked at Cherbourg had higher chances.

## 📊 Tech Stack
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## 📂 Files
- `titanic.ipynb` → Notebook with all code and analysis
- `images/` → Saved plots and graphs
- `README.md` → Documentation

## 🚀 How to Run
```bash
git clone https://github.com/thejasuryachar11/PRODIGY_DS_02.git
cd PRODIGY_DS_02
jupyter notebook titanic.ipynb
