# Student Performance Data Analysis

## Maincrafts Technology - Data Science/Analysis with Python Internship

### Task 1: Student Performance Dataset

## Project Overview

This project analyzes the Student Performance dataset using Python. The objective is to explore, clean, analyze, and visualize student academic data to identify patterns related to final grades, study time, and gender-based academic performance.

The project follows a basic data analysis workflow:

Data Loading → Data Exploration → Data Cleaning → Statistical Analysis → Data Visualization → Conclusion

## Dataset

The project uses the `student-mat.csv` dataset.

The dataset contains:

- 395 student records
- 33 attributes
- Demographic information
- Family-related information
- Study habits
- Academic grades

The `G3` column represents the final grade of each student and is used as the main performance variable in this analysis.

## Analysis Questions

The project answers the following questions:

1. What is the average final grade (G3)?
2. How many students scored above 15?
3. Is study time correlated with student performance?
4. Which gender performs better on average?

## Data Cleaning

The dataset was explored and cleaned using Pandas.

The following checks were performed:

- Dataset shape inspection
- Column inspection
- Data type inspection
- Missing value detection
- Duplicate record detection
- Duplicate removal precaution
- Descriptive statistical analysis

The dataset contains no missing values and no duplicate records.

## Key Findings

- The dataset contains 395 students and 33 attributes.
- The average final grade (G3) is approximately 10.42 out of 20.
- 40 students scored above 15 in their final grade.
- The correlation between study time and final grade is approximately 0.098.
- Study time has a very weak positive linear relationship with final academic performance.
- Male students achieved an average final grade of approximately 10.91.
- Female students achieved an average final grade of approximately 9.97.
- Male students performed slightly better on average within this dataset.

## Data Visualizations

### Distribution of Final Grades

The histogram shows the distribution of students' final grades.

![Distribution of Final Grades](images/final_grades_histogram.png)

### Study Time vs Final Grade

The scatter plot shows the relationship between weekly study time and students' final grades.

![Study Time vs Final Grade](images/studytime_vs_grade.png)

### Average Final Grade by Gender

The bar chart compares the average final grade of male and female students.

![Average Final Grade by Gender](images/gender_average_grade.png)

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Files

- `student_analysis.ipynb` - Complete data analysis notebook
- `student-mat.csv` - Student Performance dataset
- `README.md` - Project documentation

## Conclusion

The Student Performance dataset was successfully loaded, explored, cleaned, analyzed, and visualized using Python.

The analysis indicates that study time has only a very weak positive linear correlation with final grades in this dataset. Gender-based analysis shows a small difference in average final grades between male and female students.

This project demonstrates a complete basic data analysis workflow using Python, Pandas, and Matplotlib.
