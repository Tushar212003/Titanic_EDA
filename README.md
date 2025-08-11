# 🛳 Titanic Dataset – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis** (EDA) on the classic Titanic dataset to uncover patterns in passenger demographics, travel classes, and survival outcomes.  
We use Python with **pandas**, **NumPy**, **Matplotlib**, and **Seaborn** to clean, visualize, and interpret the data.

---

## 📂 Dataset
The dataset consists of three CSV files:

- `train.csv` – Training dataset with survival labels  
- `test.csv` – Test dataset without survival labels  
- `gender_submission.csv` – Example submission file for Kaggle  

**Key Columns:**
- `Survived` – Survival indicator (0 = No, 1 = Yes)
- `Pclass` – Passenger class (1, 2, 3)
- `Name`, `Sex`, `Age`
- `SibSp`, `Parch` – Number of siblings/spouses & parents/children aboard
- `Ticket`, `Fare`, `Cabin`, `Embarked`

---

## ⚙️ Tools & Libraries
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

---

## 🔍 EDA Steps
1. **Data Loading & Inspection**  
   - `.head()`, `.info()`, `.describe()` for structure and summary  
   - Missing value analysis (`.isnull().sum()`)

2. **Univariate Analysis**  
   - Distribution plots: Age, Fare  
   - Bar plots: Survival by Sex, Pclass, Embarked

3. **Bivariate Analysis**  
   - Survival vs Age/Fare (scatterplots)  
   - Correlation heatmap of numeric features  
   - Pairplots for selected variables

4. **Feature Engineering**  
   - Extracted `Title` from Name  
   - Created `FamilySize` and `IsAlone`  
   - Created binary `HasCabin` feature

5. **Missing Data Handling**  
   - Filled `Age` with median  
   - Filled `Embarked` with mode

---

