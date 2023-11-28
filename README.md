# Exploratory Data Analysis on Data Science Job Salaries

## Investigate a small sample of the data science job market using Python

This project aims to provide a comprehensive investigation of the data science job landscape, focusing on depicting the most lucrative jobs available along with the demography. The main business question I aim to answer is: “Where in the world can potential entrants in the data science field find the most financially rewarding opportunities, and which factor influences these variations?”

**Dataset**

The dataset contains 11 attributes and 607 observations. There are 6 categorical attributes and 3 numerical attributes for analysis. The attributes of the dataset are:
Numerical: work_year, salary, salaryinusd, remote_ratio
Categorical: experience_level, employment_type, job_title, salary_currency, employee_residence, company_location and company_size. 

The flow of the project is as follows:
* Data Exploration
* Data Understanding
* Data Preprocessing
* Missing Value Exploration
* Outlier Identification
* Data Visualizations (both univariate and bivariate analysis)
* Evaluation, discussion and conclusion

The following libraries were used:
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Plotly
* country_converter

## How to run this project
Download the notebook file (ipnyb) and the ds_salaries.csv dataset. Change the directory of the dataset in the notebook. Use any platform to play around with the code (Jupyter Notebook, Google Collab etc).

## How to tweak this project for your own use
There are limitations to the dataset, especially since it focuses on observations of company locations based in the US. So you can filter out the dataset for only US-based observations and conduct analysis for those records. This will allow you to have an unbiased analysis.

