# Student Performance Statistical Analysis

Statistical analysis of a high school student performance dataset using **R** and **Quarto** as part of **STAT5020 – Assignment 2 (Part 1)**.

This project explores student demographics, study habits, tutoring participation, and academic performance using descriptive statistics, data visualisation, and introductory probability concepts. The analysis follows the assignment requirements and demonstrates the application of fundamental statistical techniques for exploratory data analysis.

---

## Project Overview

The analysis is based on a dataset containing **2,392 students** and **15 variables**, covering:

- Demographic information
- Study habits
- Parental involvement
- Extracurricular activities
- Academic performance

The project investigates:

- Variable types
- Descriptive statistics
- Distribution of GPA
- Relationship between tutoring and academic performance
- Normal distribution approximation
- Probability calculations using the Normal model

The analysis was completed using **R** and documented in **Quarto**, with the final report rendered as a PDF.

---

## Repository Structure

```
student-performance-statistical-analysis/
│
├── images/
│   ├── histogram_gpa.png
│   ├── boxplot_gpa.png
│   ├── grade_distribution_by_tutoring.png
│   ├── gpa_by_tutoring.png
│   ├── gpa_normal_curve.png
│   └── qqplot_gpa.png
│
├── student_performance_analysis.qmd
├── student_performance_analysis.pdf
├── student_performance_data.csv
├── README.md
└── LICENSE
```

---

## Dataset

The dataset contains information for **2,392 high school students**.

Variables include:

### Demographics

- Age
- Gender
- Ethnicity
- Parental Education

### Study Habits

- Weekly Study Time
- Absences
- Tutoring

### Parental Involvement

- Parental Support

### Extracurricular Activities

- Extracurricular Participation
- Sports
- Music
- Volunteering

### Academic Performance

- GPA
- Grade Class

The dataset was supplied as part of the STAT5020 assignment.

---

## Statistical Analysis

The project includes the following analyses.

### Part 1 – Understanding the Data

- Identification of variable types
- Justification of measurement scales
- Development of a research question

---

### Part 2 – One-Variable Analysis

Categorical analysis:

- Frequency table
- Percentage table
- Bar chart
- Distribution interpretation

Numerical analysis:

- Histogram
- Mean
- Standard deviation
- Median
- Interquartile range (IQR)
- Summary statistics
- Boxplot
- 1.5 × IQR outlier assessment

---

### Part 3 – Relationship Between Variables

Relationship between Tutoring and Grade Class:

- Contingency table
- Conditional proportions
- Grouped bar chart
- Interpretation

Comparison of GPA by Tutoring status:

- Boxplot
- Comparison of centre
- Comparison of spread
- Summary statistics by tutoring group

---

### Part 4 – Normal Distribution and Probability

Assessment of GPA normality:

- Histogram with Normal curve
- Normal Q-Q plot

Probability analysis:

- Normal probability calculation
- Empirical probability calculation
- Comparison between theoretical and empirical probabilities

Percentile analysis:

- Top 10% GPA cutoff using the Normal model
- Empirical percentile comparison

---

## Tools and Technologies

- R
- Quarto
- ggplot2
- Base R
- Git
- GitHub

---

## Data Processing

The original dataset was analysed as provided.

No observations or variables were removed or modified.

Encoded categorical variables (such as **GradeClass** and **Tutoring**) were converted to **factor variables within R** to support statistical analysis and visualisation.

Numerical values presented in tables were rounded for reporting purposes only.

---

## Key Learning Outcomes

Through this project, I gained practical experience in:

- Classifying variable types
- Producing descriptive statistics
- Creating statistical visualisations
- Comparing categorical and numerical variables
- Interpreting contingency tables
- Assessing distributions using histograms and Q-Q plots
- Applying the Normal distribution to probability estimation
- Reporting statistical findings using Quarto

---

## Report

The completed statistical analysis is available in:

```
student_performance_analysis.pdf
```

The complete analysis workflow and reproducible R code are available in:

```
student_performance_analysis.qmd
```

---

## Licence

This repository is released under the MIT License.

---

## Author

**Viktor (Xuan Nam) Ngo**

Master of Data Science  
Adelaide University

GitHub:
https://github.com/ViktorNgo3012
