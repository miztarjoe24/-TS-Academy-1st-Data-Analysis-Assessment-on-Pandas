Notebook Summary

Dataset overview

1,000 students, 8 columns — 5 categorical (gender, race/ethnicity, parental education, lunch type, test prep) and 3 numeric (math, reading, writing scores). No missing values at all.

Student: Ikhazobor Michael Izuagie | Course: Data Science |1st Assessment: Pandas Analysis Assessment The notebook analyses the StudentsPerformance.csv dataset across 5 sections using Python (pandas, numpy, matplotlib).

Section A — Basic Exploration. Loads the dataset and performs foundational inspection: viewing first/last 10 rows, .info(), .shape, column names, identifying numeric vs categorical columns, descriptive statistics, and checking for missing values. The dataset has 3 numeric columns (math, reading, writing scores). Five categorical columns (gender, race/ethnicity, parental education, lunch, test prep course).

Section B — Filtering & Conditional Selection. Four filtering tasks: students who completed test prep, students scoring above 70 in math, female students scoring at least 65 in all three subjects (using & and .all()), and a count of students on free/reduced lunch.

Section C — Group By & Aggregation. Three groupby analyses: average math score by gender, average scores by parental education level, and a comparison of scores between students who completed vs skipped test preparation.

Section D — Visualisation. Histograms for all three scores, plus a bar chart of average scores by gender.

Section E — Interpretation. Answers the question: "Does test preparation improve performance?" — confirmed yes, with grouped averages showing completed-course students score higher across all three subjects.
