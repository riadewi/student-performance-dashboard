# 📊 Student Performance & Early Risk Dashboard

An interactive Power BI dashboard designed to analyze student academic performance, identify patterns associated with academic success, and highlight students who may require additional academic attention.

The project uses a dataset of 10,500 students containing information about school, major, grade level, study hours, attendance, previous GPA, extracurricular participation, and subject scores.

The dashboard transforms raw student data into interactive visual insights that can support data-driven educational decision-making.

---

## 📌 Project Overview

Student academic performance can be influenced by multiple factors, including study habits, attendance, previous academic achievement, and subject performance.

This project aims to explore these factors through an interactive Power BI dashboard and answer questions such as:

- How many students pass and fail?
- Does attendance relate to student performance?
- Does study time appear to be associated with the pass rate?
- How do academic scores differ between students who pass and those who do not?
- Which student groups may require additional attention?
- How does academic performance vary across schools, majors, and grade levels?

The final output is an interactive dashboard that allows users to explore these patterns through filters and visualizations.

---

## 🎯 Project Objectives

The main objectives of this project are to:

1. Analyze the overall academic performance of students.
2. Measure the overall pass and non-pass rates.
3. Analyze the relationship between study hours and academic outcomes.
4. Analyze the relationship between attendance and academic outcomes.
5. Compare subject performance between students who passed and did not pass.
6. Identify students or groups with potential academic risk.
7. Compare performance across schools, majors, and grade levels.
8. Present the findings through an interactive and user-friendly Power BI dashboard.

---

## 📂 Dataset

The dataset contains **10,500 student records** and **13 variables**.

### Dataset Information

| Attribute | Description |
|---|---|
| Records | 10,500 students |
| Columns | 13 |
| Schools | 5 |
| Majors | 3 |
| Grade Levels | 10, 11, 12 |
| File Format | CSV |
| Analysis Tool | Microsoft Power BI |

### Dataset Columns

| Column | Description |
|---|---|
| `student_id` | Unique identifier for each student |
| `school` | Student's school |
| `major` | Student's academic major |
| `grade` | Student's grade level |
| `hours_study_per_week` | Average study hours per week |
| `attendance_pct` | Student attendance percentage |
| `previous_gpa` | Student's previous GPA |
| `extracurricular` | Whether the student participates in extracurricular activities |
| `math_score` | Mathematics score |
| `indo_score` | Bahasa Indonesia score |
| `english_score` | English score |
| `total_score` | Total academic score |
| `passed` | Student pass status |

---

## 🌐 Data Source

The dataset used in this project was obtained from PraktikData Data Playground.

**Original Dataset:**  
https://praktikdata.com/resources/data-playground/student-performance

**Source:** PraktikData  
**Dataset:** Student Performance  
**Format:** CSV

The original dataset is used as the data source for this educational and portfolio project.

> **Data Attribution:** Credit for the original dataset goes to PraktikData. The dashboard design, data analysis, visualizations, measures, and insights presented in this repository were developed as part of this independent project.

---

## 🛠️ Tools & Technologies

This project was developed using the following tools:

| Tool / Technology | Purpose |
|---|---|
| **Microsoft Power BI** | Dashboard development and data visualization |
| **Power Query** | Data preparation and transformation |
| **DAX** | Analytical calculations and measures |
| **CSV** | Raw dataset |
| **GitHub** | Project documentation and portfolio |

---

## 🔄 Data Analysis Process

The project follows a typical data analytics workflow:

```text
Raw Dataset
     ↓
Data Understanding
     ↓
Data Preparation
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
Data Visualization
     ↓
Dashboard Development
     ↓
Insight & Analysis
```

### 1. Data Understanding

The dataset was examined to understand:

- Data structure
- Column types
- Categorical variables
- Numerical variables
- Student pass status
- Academic performance indicators

### 2. Data Preparation

The dataset was prepared for analysis using Power Query and Power BI.

The preparation process includes:

- Checking data types
- Validating numerical fields
- Preparing categorical fields
- Ensuring student records are suitable for analysis
- Preparing fields for dashboard filtering and visualization

### 3. Data Modeling

The prepared dataset was loaded into Power BI and structured for analytical purposes.

### 4. DAX Measures

DAX was used to create analytical metrics such as:

- Total Students
- Passed Students
- Failed Students
- Pass Rate
- Non-Pass Rate
- Average Academic Scores
- Score Gap
- Risk-related metrics

### 5. Data Visualization

The calculated metrics were presented through interactive charts, KPI cards, filters, and detailed student-level information.

---

# 📊 Dashboard Features

## 1. Overall Student Performance

The dashboard provides an overview of student performance through key performance indicators.

### Key KPIs

- **Total Students**
- **Pass Rate**
- **Non-Pass Rate**
- **Average Score**
- **Average Attendance**
- **Average Study Hours**

These KPIs provide a quick overview of the overall academic condition of the student population.

---

## 2. Pass Rate Analysis

The dashboard analyzes the proportion of students who passed and did not pass.

Based on the dataset:

| Status | Students | Percentage |
|---|---:|---:|
| Passed | 8,234 | 78.42% |
| Not Passed | 2,266 | 21.58% |
| **Total** | **10,500** | **100%** |

The overall pass rate is approximately **78.42%**, while **21.58%** of students did not pass.

---

## 3. Study Hours vs Pass Rate

This analysis examines student pass rates based on weekly study hours.

The objective is to identify whether students with different study-hour patterns show different academic outcomes.

This visualization can help answer:

> "Do students who spend more time studying tend to have higher pass rates?"

---

## 4. Attendance vs Pass Rate

Attendance is analyzed against student pass status to understand whether attendance patterns are associated with academic outcomes.

The analysis can help identify groups with lower attendance and potentially lower academic performance.

This provides a useful perspective for identifying students who may benefit from attendance-related interventions.

---

## 5. Academic Performance Comparison

The dashboard compares academic performance between students who passed and students who did not pass.

The comparison includes:

- Mathematics
- Bahasa Indonesia
- English

### Overall Average Scores

| Metric | Average |
|---|---:|
| Mathematics | 67.90 |
| Bahasa Indonesia | 67.74 |
| English | 67.76 |
| Total Score | 203.40 |
| Previous GPA | 77.60 |
| Attendance | 80.17% |
| Study Hours / Week | 4.24 |

These values provide a baseline for comparing different student segments.

---

## 6. Score Gap Analysis

The dashboard uses **Score Gap** to highlight the difference in average academic performance between students who passed and those who did not pass.

The metric can be used to answer:

> "How large is the academic performance gap between successful and unsuccessful students?"

This provides more insight than simply showing average scores because it focuses attention on the difference between the two groups.

---

## 7. Student Risk Analysis

A risk categorization is used to identify students who may require additional academic attention.

The risk analysis can consider indicators such as:

- Attendance
- Study hours
- Academic scores
- Previous GPA
- Pass status

The purpose is not to predict student outcomes with machine learning, but to provide an analytical segmentation that can help prioritize further investigation.

---

## 8. Student-Level Details

The dashboard provides detailed information that allows users to drill down from aggregate performance to individual student records.

Example fields include:

- Student ID
- School
- Major
- Grade
- Attendance
- Study Hours
- Previous GPA
- Mathematics Score
- Bahasa Indonesia Score
- English Score
- Total Score
- Pass Status

This allows users to move from:

**Overall Performance → Group Analysis → Individual Student**

---

# 🎛️ Interactive Filters

The dashboard includes interactive filters that allow users to analyze specific student segments.

Available filters include:

- **School**
- **Major**
- **Grade**

These filters allow users to answer questions such as:

- Which school has the highest pass rate?
- How does performance differ between majors?
- Does performance change across grade levels?
- Which student groups have the highest academic risk?

---

# 🔍 Key Findings

Based on the dataset, several high-level findings can be observed.

### 1. Overall Pass Rate

Out of **10,500 students**, **8,234 students passed**, resulting in an overall pass rate of approximately **78.42%**.

However, **2,266 students**, or approximately **21.58%**, did not pass.

This indicates that although the majority of students achieved the passing criteria, a significant minority still requires attention.

### 2. Average Attendance

The average attendance rate across all students is approximately:

**80.17%**

Attendance can therefore be explored as one of the potential indicators associated with academic performance.

### 3. Average Study Time

Students study approximately:

**4.24 hours per week**

on average.

This provides a baseline for comparing study patterns between different academic outcome groups.

### 4. Academic Performance

The average subject scores are relatively similar:

- Mathematics: **67.90**
- Bahasa Indonesia: **67.74**
- English: **67.76**

This allows further analysis of whether particular subjects contribute more strongly to differences in overall academic outcomes.

---

# 📈 Dashboard Design

The dashboard follows a simple analytical hierarchy:

```text
┌──────────────────────────────────────────────┐
│       STUDENT PERFORMANCE DASHBOARD          │
├──────────────────────────────────────────────┤
│ School │ Major │ Grade                       │
├──────────────┬──────────────┬────────────────┤
│ Total        │ Pass Rate    │ Non-Pass Rate  │
│ Students     │              │                │
├──────────────┴──────────────┴────────────────┤
│                                              │
│ Study Hours vs Pass Rate                     │
│                                              │
├───────────────────────┬──────────────────────┤
│ Attendance vs         │ Student Risk         │
│ Pass Rate             │ Distribution         │
├───────────────────────┴──────────────────────┤
│                                              │
│ Academic Performance: Passed vs Not Passed  │
│                                              │
├──────────────────────────────────────────────┤
│              Student Details                 │
└──────────────────────────────────────────────┘
```

The dashboard is designed to prioritize:

1. **High-level KPIs**
2. **Performance drivers**
3. **Risk identification**
4. **Detailed student information**

---

# 💡 Business / Educational Questions

This dashboard can help stakeholders answer the following questions:

### Performance

- What is the overall student pass rate?
- How many students did not pass?
- What is the average academic score?

### Attendance

- Is attendance associated with the pass rate?
- Which attendance groups have lower performance?

### Study Habits

- How does study time relate to student outcomes?
- Which study-hour groups have higher pass rates?

### Academic Performance

- How large is the score gap between passed and non-passed students?
- Which subject shows the largest performance difference?

### Student Risk

- Which students may require additional academic attention?
- Which school, major, or grade contains a larger proportion of potentially at-risk students?

---

# 📁 Project Structure

```text
student-performance-dashboard/
│
├── README.md
│
├── student_performance.pbix
│
├── student_performance.csv
│
└── screenshots/
    │
    └── dashboard.png
```

### File Description

| File | Description |
|---|---|
| `README.md` | Project documentation |
| `student_performance.pbix` | Power BI dashboard file |
| `student_performance.csv` | Original dataset used for analysis |
| `screenshots/dashboard.png` | Dashboard preview image |

---

# 🖥️ Dashboard Preview

Add a screenshot of the final dashboard to the `screenshots` folder.

Then display it in this README using:

```markdown
![Student Performance Dashboard](screenshots/dashboard.png)
```

---

# 🚀 How to Use

## 1. Clone the Repository

```bash
git clone https://github.com/yourusername/student-performance-dashboard.git
```

## 2. Open the Project

Open:

```text
student_performance.pbix
```

using **Microsoft Power BI Desktop**.

## 3. Explore the Dashboard

Use the available filters to analyze:

- Schools
- Majors
- Grade levels

You can then explore the relationship between:

- Study hours
- Attendance
- Academic scores
- Pass status
- Student risk

---

# 📌 Limitations

Several limitations should be considered when interpreting the results.

### 1. Correlation Does Not Imply Causation

The dashboard identifies patterns and associations within the dataset. It does not establish that a particular factor directly causes students to pass or fail.

### 2. Limited Variables

The dataset does not include potentially important factors such as:

- Socioeconomic background
- Family support
- Teacher quality
- Learning environment
- Mental well-being
- Access to educational resources
- Previous academic interventions

Therefore, the analysis should not be used as the sole basis for educational decisions.

### 3. Risk Classification

The risk categories are analytical segments rather than a validated predictive model.

For real-world implementation, the risk model should be validated using historical outcomes and appropriate statistical or machine learning methods.

---

# 🔮 Future Improvements

Several improvements could be implemented in future versions of the project:

### Data & Analytics

- Add additional student demographic variables.
- Add historical academic records.
- Analyze trends across academic periods.
- Develop a more comprehensive student risk score.

### Machine Learning

Future versions could include predictive models for:

- Student pass/fail prediction
- Academic performance prediction
- Early identification of at-risk students

Potential algorithms include:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

### Dashboard

Additional dashboard pages could include:

- **Executive Summary**
- **Academic Performance**
- **Attendance Analysis**
- **Student Risk**
- **School Performance**
- **Student Details**

### Recommendations

The dashboard could also be extended to provide recommended interventions based on student risk categories.

---

# 📚 Learning Outcomes

This project demonstrates practical skills in:

- Data cleaning
- Data exploration
- Data modeling
- DAX
- KPI development
- Data visualization
- Dashboard design
- Exploratory data analysis
- Educational analytics
- Business intelligence
- Insight communication

---

# 👩‍💻 Author

**Dewi**

Data Analytics & Business Intelligence Portfolio

### Skills

`Power BI` · `DAX` · `Power Query` · `Data Analysis` · `Data Visualization` · `Dashboard Design` · `Business Intelligence`

---

# 📄 Disclaimer

This project is created for **educational and portfolio purposes**.

The dataset is sourced from **PraktikData Data Playground**. The analysis, dashboard design, DAX measures, visualizations, and interpretations are developed independently for learning and portfolio demonstration.

For the original dataset and source information, please visit:

**https://praktikdata.com/resources/data-playground/student-performance**

---

# ⭐ If You Find This Project Useful

If this project is helpful or interesting, feel free to:

- ⭐ Star the repository
- 🍴 Fork the repository
- 💬 Provide feedback
- 📌 Explore other projects in the portfolio
