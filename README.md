# 🎓 Student Performance Analysis  

This project explores a dataset of student performance to understand basic trends and patterns. Using **Python (Pandas, NumPy, Matplotlib, Seaborn)**, we clean the data and perform exploratory data analysis (EDA) with visualizations.  

---

## 📂 Dataset Overview  

- **Rows:** 30,641  
- **Columns:** 14 (after cleaning)  

### Features  
- 👤 **Demographics** → `Gender`, `EthnicGroup`  
- 🏫 **Family** → `ParentEduc`, `ParentMaritalStatus`  
- ⚽ **Lifestyle** → `PracticeSport`, `WklyStudyHours`, `TransportMeans`  
- ✍️ **Academics** → `MathScore`, `ReadingScore`, `WritingScore`  

---

## 🔧 Workflow  

1. **Data Cleaning**  
   - Dropped unnecessary column (`Unnamed: 0`).  
   - Fixed inconsistent values in `WklyStudyHours`.  
   - Checked and handled missing values.  

2. **Exploratory Data Analysis (EDA)**  
   - 📊 Gender distribution (countplot)  
   - 🔥 Parent education vs scores (heatmap)  
   - 💍 Parent marital status vs scores (heatmap)  
   - 🥧 Ethnic group distribution (pie chart & countplot)  
   - 📦 Math score distribution (boxen plot)  


## 🛠️ Tech Stack  

- **Python** 🐍  
- **Pandas / NumPy** → Data handling  
- **Matplotlib / Seaborn** → Visualization  

---

## 🚀 Future Scope  

- 📌 Handle missing values using imputation.  
- 📌 Explore correlation between study hours & scores.  
- 📌 Build prediction models (ML).  
- 📌 Interactive dashboard (Power BI / Plotly).  

---

✨ This project shows how **basic EDA** can turn raw data into meaningful insights about students’ academic performance.  
