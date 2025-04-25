# Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**. The goal is to understand the data, uncover meaningful insights, and identify patterns that affect passenger survival.

---

##What I Have Learned

- **Data Visualization** using Seaborn, Matplotlib, and Plotly
- **Descriptive Statistics** like mean, median, and standard deviation
- **Pattern Recognition** involving survival based on age, gender, fare, and class
- **Data Cleaning**: handling missing values, encoding categories, detecting/removing outliers

---

## Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn
---

## Dataset Information

- Cleaned Dataset: `Titanic-Dataset-cleaned.csv`
- Original Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

---

## EDA Workflow

### 1. Generate Summary Statistics
- Used `df.describe()` to get insights into central tendencies and spread of data.

### 2. Create Histograms and Boxplots for Numeric Features
- Visualized distribution of `Age` and `Fare`
- Detected outliers using boxplots

### 3. Use Pairplot and Correlation Matrix
- Pairplot helped analyze relationships between numerical features and `Survived`
- Heatmap used to identify linear correlations between variables

### 4. Identify Patterns, Trends, and Anomalies
- Grouped survival analysis by:
  - `Sex`
  - `Pclass`
- Observed that females and higher-class passengers survived more frequently

### 5. Make Feature-Level Inferences from Visuals
- Found that:
  - Females had higher survival rates
  - First-class passengers paid more and had better chances
  - Young passengers had better survival odds
  - High fare outliers indicated VIPs or high-paying passengers

---

## Example Plots

- Histograms and boxplots for `Age` and `Fare`
- Pairplot for survival vs. features
- Heatmap for feature correlations
- Barplots and countplots by `Sex`, `Pclass`, and `Survived`

---

## Key Insights

- **Females** were more likely to survive than males
- **First-class passengers** had better survival chances
- **Higher fare** correlated with higher class and better survival rate
- **Children and younger adults** had increased odds of survival
- **Outliers** in `Fare` signaled premium ticket holders

---

---

## Status

✅ EDA Completed  and visualizations Added  
**Ready for Feature Engineering / Model Building**
