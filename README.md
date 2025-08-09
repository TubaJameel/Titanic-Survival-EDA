# 🧊 Exploratory Data Analysis on Titanic Dataset

This project performs an exploratory data analysis (EDA) on the Titanic dataset to uncover insights about the passengers and their survival. The analysis includes data cleaning, preprocessing, and visual exploration to understand how features like age, sex, class, and embarkation point influenced survival.


## 📁 Dataset

- **Name**: Titanic Dataset  
- **Source**: Included as `Titanic.csv` in the working directory  
- **Attributes**:
  - PassengerId, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked, Survived

## 🔧 Project Workflow
### 1. Data Cleaning
- Handled missing values:
  - Filled missing `Age` with median.
  - Filled missing `Embarked` with mode.
  - Dropped the `Cabin` column due to excessive missing data.
- Saved the cleaned dataset as `titanic_cleaned.csv`.
### 2. Data Transformation
- Converted data types for categorical features (`Sex`, `Embarked`).
- Encoded categories numerically:
  - `Sex`: male → 0, female → 1
  - `Embarked`: S → 0, C → 1, Q → 2
### 3. Statistical Analysis
- Used `describe()` to summarize central tendencies, spread, and shape of the dataset's distribution.
### 4. Visualization (in notebook)
- Bar plot and correlation analysis to explore survival trends across different groups.

## 🛠️ Tools & Libraries
- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook
## 🔍 Key Insights
- Women had a higher survival rate than men.
- Passengers in higher classes (1st class) had better chances of survival.
- Children and younger passengers had relatively better survival odds.
- Embarkation point had minor but observable effects on survival.
## 📊 How to Run
1. Open the notebook in Jupyter or VSCode.
2. Make sure `Titanic.csv` is in the same directory.
3. Run the notebook step by step to see EDA and visualizations.
## 📬 Contact
For suggestions or collaborations, feel free to connect via GitHub.

