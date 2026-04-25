#  Titanic Data Analysis

Exploratory Data Analysis (EDA) on Titanic passenger data using Python.  
Data was cleaned, engineered, and visualized to uncover survival patterns.

---

##  Tools & Libraries
- **Python** — Pandas, NumPy, Matplotlib, Seaborn

---

##  Project Structure
| File | Description |
|------|-------------|
| `titanic.ipynb` | Main notebook — cleaning + EDA |
| `titanic.csv` | Raw dataset |
| `Titanic_cleaned.csv` | Cleaned dataset |
---

##  Data Cleaning
1. Checked null values, duplicates, and data types
2. Filled missing Age values with median
3. Filled missing Embarked values with mode
4. Dropped Cabin column (77% missing values)
5. Dropped unnecessary columns — Name, Ticket

---

##  Feature Engineering
| Feature | Logic |
|---------|-------|
| `FamilySize` | SibSp + Parch + 1 |
| `IsAlone` | 1 if FamilySize == 1, else 0 |
| `AgeGroup` | Child / Young / Adult / Senior |

---

##  EDA & Visualizations
-  Survival Count
-  Survival by Gender
-  Survival by Passenger Class
-  Age Distribution
-  Fare Distribution
-  FamilySize vs Survival Rate
-  Embarked vs Survival
-  Correlation Heatmap

---

##  Key Insights
1. Only **38.38%** passengers survived
2. **Females** survived far more than males (74.8% vs 18.9%)
3. **1st Class** passengers had the highest survival rate (~63%)
4. **Small families (2-4)** had the best survival chances
5. **Higher fare** positively correlated with survival (+0.26)
6. **Cherbourg (C)** port passengers survived the most

---

##  Author
**Waleed Ahmad**  
BS Data Science (2nd Semester) — Riphah International University  
[GitHub](https://github.com/mianwaleed155847-hub)
