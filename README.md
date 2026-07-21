# Student Performance Statistical Analysis

An exploratory statistical analysis of a high school student performance dataset using **R** and **Quarto**.

This project investigates academic performance through descriptive statistics, data visualisation and introductory probability modelling. The analysis explores how demographic characteristics, study habits and tutoring relate to student outcomes while demonstrating a reproducible statistical workflow using R.

---

## Project Overview

This project analyses a dataset containing **2,392 high school students** and **15 variables** covering:

- Demographic characteristics
- Study habits
- Parental involvement
- Extracurricular activities
- Academic performance

The analysis combines descriptive statistics, exploratory data analysis (EDA), visualisation and Normal distribution modelling to better understand patterns within the dataset.

---

## Objectives

The project was designed to:

- Understand the structure and measurement types of variables
- Explore the distribution of academic performance
- Summarise categorical and numerical variables using descriptive statistics
- Compare academic performance between tutoring groups
- Assess whether GPA can be reasonably approximated using a Normal distribution
- Compare theoretical probabilities with empirical observations

---

# Project Workflow

```
Dataset
      │
      ▼
Data Understanding
      │
      ▼
Descriptive Statistics
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Relationship Analysis
      │
      ▼
Normal Distribution Assessment
      │
      ▼
Probability & Percentile Analysis
```

---

# Dataset

**Observations:** 2,392 students

**Variables:** 15

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

- Sports
- Music
- Volunteering
- Extracurricular Participation

### Academic Performance

- GPA
- Grade Class

> The dataset was provided for educational purposes.

---

# Statistical Analysis

The project includes:

## Data Understanding

- Variable classification
- Measurement scales
- Research question development

---

## Descriptive Statistics

Categorical variables

- Frequency tables
- Percentage distributions
- Bar charts

Numerical variables

- Mean
- Median
- Standard deviation
- Interquartile range (IQR)
- Summary statistics
- Histograms
- Boxplots
- Outlier assessment using the 1.5 × IQR rule

---

## Relationship Analysis

Comparison of tutoring participation and academic performance using

- Contingency tables
- Conditional proportions
- Grouped bar charts
- Boxplots
- Summary statistics

---

## Normal Distribution

Assessment of GPA using

- Histogram with Normal density curve
- Normal Q-Q plot

---

## Probability Analysis

Comparison between

- Normal model probabilities
- Empirical probabilities

including

- Probability estimation
- Percentile estimation
- Top 10% GPA cutoff

---

# Key Findings

- GPA follows an approximately symmetric distribution with no extreme outliers under the 1.5 × IQR rule.
- Students receiving tutoring generally achieved slightly higher GPA values than students who did not receive tutoring.
- GPA can be reasonably approximated using a Normal distribution, although slight deviations occur in the tails.
- Theoretical probabilities from the Normal model were close to empirical probabilities observed in the dataset.

---

# Visualisations

## Distribution of GPA

![Distribution of GPA](images/histogram_gpa.png)

The histogram provides an overview of the GPA distribution and supports the assessment of symmetry and central tendency.

---

## GPA Boxplot

![Boxplot of GPA](images/boxplot_gpa.png)

The boxplot summarises the spread of GPA values and confirms that no observations were identified as outliers using the 1.5 × IQR rule.

---

## Grade Distribution by Tutoring

![Grade Distribution by Tutoring](images/grade_distribution_by_tutoring.png)

Grade distributions were compared between students who received tutoring and those who did not using conditional proportions.

---

## GPA by Tutoring

![GPA by Tutoring](images/gpa_by_tutoring.png)

Students receiving tutoring generally exhibited a slightly higher GPA distribution while maintaining a similar level of variability.

---

## GPA with Normal Distribution

![Normal Distribution](images/gpa_normal_curve.png)

The Normal density curve was overlaid on the GPA distribution to evaluate the suitability of a Normal approximation.

---

## Normal Q-Q Plot

![Normal Q-Q Plot](images/qqplot_gpa.png)

Most observations align closely with the theoretical Normal line, although mild deviations are visible in the tails.

---

# Tools & Technologies

- R
- Quarto
- ggplot2
- Base R
- Git
- GitHub

---

# Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Data Visualisation
- Statistical Reporting
- Probability Modelling
- Normal Distribution Assessment
- Reproducible Research using Quarto
- Data Interpretation using R

---

# Repository Structure

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

# Reproducibility

The complete analysis can be reproduced using:

- `student_performance_analysis.qmd`

The rendered report is available in:

- `student_performance_analysis.pdf`

---

# Future Improvements

Potential extensions of this project include:

- Statistical hypothesis testing
- Correlation analysis
- Regression modelling
- Interactive dashboards
- Predictive modelling of academic performance

---

# License

This project is released under the MIT License.

---

# Author

**Viktor (Xuan Nam) Ngo**

Master of Data Science  
Adelaide University

GitHub: https://github.com/ViktorNgo3012
