
# 🚢 Titanic Survival Prediction – Exploratory Data Analysis (EDA)

This project was completed as part of my **Data Science internship** at **Prodigy InfoTech**, where I performed **data cleaning** and **exploratory data analysis (EDA)** on the Titanic dataset from Kaggle to discover patterns affecting survival.

---

## 📁 Dataset Used

- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- **Records**: 891 passengers
- **Target Variable**: `Survived` (0 = No, 1 = Yes)

---

## 📊 Goals

- Perform **data cleaning**: handle missing values, drop irrelevant columns
- Visualize key patterns using **Seaborn** and **Matplotlib**
- Understand which features (e.g. gender, class, fare) influence survival
- Prepare the dataset for further machine learning if needed

---

## 🔧 Key Steps

1. **Data Cleaning**
   - Removed nulls from `Age`, `Embarked`, and `Cabin`
   - Dropped unused columns like `Ticket`, `Name`, and `PassengerId`

2. **Exploratory Analysis**
   - Count plots for gender, class, embarkation
   - Survival rate by age, fare, and family members aboard
   - Grouped bar plots for multi-variable comparison (e.g. Gender × Survival)

3. **Insights**
   - 💡 **Women** had a much higher survival rate than men
   - 💡 **First class** passengers had better survival odds
   - 💡 Younger children had higher survival than older adults
   - 💡 People who paid higher fares were more likely to survive

---

## 📈 Visualizations Included

- Countplot: `Survived` by `Sex`
- Barplot: `Pclass` vs `Survived`
- Heatmap: correlation matrix
- Age & Fare distribution histograms
- Combined plots for deeper insight (e.g., `Sex` vs `Survived` by `Pclass`)

---

## 💻 Tools & Libraries

- Python (Jupyter Notebook)
- `pandas`, `numpy` for data handling
- `matplotlib`, `seaborn` for visualization

---

## 🧠 Conclusion

This project strengthened my understanding of:

- Exploratory Data Analysis
- Feature interpretation
- Pattern discovery in real-world datasets

It laid the foundation for applying machine learning to survival prediction.

---

## 📌 Internship Info

**Internship Provider**: Prodigy InfoTech  
**Task**: Perform EDA and draw insights from the Titanic dataset

---

> ✨ *Thank you for viewing my project! Feedback and suggestions are always welcome.*
