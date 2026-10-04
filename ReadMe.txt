# Student Performance Prediction Using Machine Learning

## Assignment 1 – TSI

This project focuses on analyzing student performance using a dataset from the UCI Machine Learning Repository. The purpose of Assignment 1 is to understand the dataset, perform basic data cleaning, and carry out initial exploratory data analysis (EDA).

## Dataset

The dataset contains student information from two subjects:

* Mathematics
* Portuguese

The two datasets were combined, giving a total of **1,044 records**.

## Target Variable

A new `performance` column was created:

* **Pass** – Final grade (G3) ≥ 10
* **Fail** – Final grade (G3) < 10

## Work Completed in Assignment 1

* Loaded the Mathematics and Portuguese datasets
* Combined both datasets
* Checked dataset size and columns
* Checked missing values
* Checked duplicate records
* Created the Pass/Fail target
* Performed descriptive statistics
* Analyzed Pass/Fail distribution
* Analyzed study time
* Compared study time with performance
* Compared previous failures with performance

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab
* Jupyter Notebook (`.ipynb`)

## Files

* `Student_Performance_TSI_Assignment1.ipynb` – Assignment 1 notebook
* `student-mat.csv` – Mathematics student dataset
* `student-por.csv` – Portuguese student dataset

## Conclusion

The initial analysis showed that most students in the combined dataset passed. The analysis also showed a relationship between previous failures and student performance. These findings will be useful for the next stage of the project, where machine learning techniques can be applied to predict student performance.

##
