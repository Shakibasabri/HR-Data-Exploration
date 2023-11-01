# HR Data Exploration

This repository contains Python code for exploring and analyzing a Human Resources dataset. The dataset provides information about employees, including their demographics, performance scores, pay rates, and more. In this README, I'll provide an overview of the code and its findings.

## Table of Contents
- [Introduction](#introduction)
- [Data Exploration](#data-exploration)
- [Key Findings](#key-findings)
- [Instructions for Running the Code](#instructions-for-running-the-code)

## Introduction

The code in this repository is designed to explore and analyze the HR dataset. It utilizes Python libraries like NumPy, Pandas, Matplotlib, Seaborn, and more to perform data analysis and create visualizations. The key objective is to gain insights into the dataset by answering various HR-related questions and creating informative plots.

## Data Exploration

### Gender Diversity
The code starts by examining gender diversity within the organization. It calculates and visualizes the distribution of males and females across different departments, highlighting the areas where gender diversity might need improvement.

### Race and Citizenship
Next, the code explores the racial and citizenship diversity within the company, providing pie charts and bar plots to visualize the distribution of races and citizenship statuses among employees.

### Age Distribution
The code also investigates the age distribution of employees, providing histograms to visualize the age demographics within the organization.

### Pay Rate vs. Age
One question the code addresses is whether there is a relationship between an employee's pay rate and their age. A scatter plot is generated to visualize this relationship.

### Performance Scores by Manager
The code explores which managers have the best-performing employees. A countplot is used to visualize the performance scores for each manager's team, helping to identify trends and differences in performance.

### Department and Pay Rates
The code also investigates which department pays the highest average salaries, highlighting the departments that might offer more competitive compensation.

### Position and Pay Rates
Similarly, the code examines which positions within the organization have the highest total pay rates. This doesn't necessarily mean that all employees in those positions have the highest salaries, but it does show which positions contribute the most to the organization's payroll.

### Hispanic/Latino Status and Pay Rates
The code further explores the relationship between an employee's Hispanic/Latino status and their pay rate, using a violin plot to visualize the distribution.

### Class Exercise
The code includes a class exercise section where you can explore additional aspects of the dataset. It includes tasks related to marital status, employment status, and working with another HR dataset (HRDataset_v9).

## Key Findings

After running the code, you can extract key findings from the dataset. Some of the insights that can be drawn from the provided code and analysis include:

- Observations on gender diversity across departments.
- Distribution of race and citizenship among employees.
- Age demographics of the workforce.
- The absence of a significant relationship between pay rates and age.
- Performance trends by manager.
- Departments and positions that pay more.

## Instructions for Running the Code

To run the code and explore the HR dataset, follow these steps:

1. Ensure you have Python installed on your system.

2. Install the required libraries by running the following command:
   ```
   pip install pandas numpy matplotlib seaborn
   ```

3. Download the HR dataset (assuming you haven't already) and adjust the file path in the code to match your local file location.

4. Open and run the Jupyter Notebook or Python script provided in this repository.

5. Follow the code comments and output to explore the dataset and gain insights into the HR-related aspects.

By following these steps, you can explore the HR dataset, answer questions about the organization's workforce, and generate informative visualizations.

Feel free to adapt and extend this code for your own data exploration or research purposes. 
