# NU_Bootcamp_2022_Project_1

# Title: "A Deepdive on STEM Salaries"
![alt text](https://github.com/nealp1910/NU_Bootcamp_2022_Project_1/blob/main/Data-Science-1.jpg)
## **Description:**
Using the powerful resources within Kaggle, our team sought to find salary information within data science-related occupations. Using this data, our team was able to get an overview on gender and experience demographics within various job fields, along with finding information regarding potential sought-after companies and locations, among more.


## Data Source 
Kaggle: https://www.kaggle.com/datasets/jackogozaly/data-science-and-stem-salaries

## Contributors
Connor Grant

Alfredo Garica

Yousuf Amin AlFatwa

Neel Patel

## Methods Used
![alt text](https://github.com/nealp1910/NU_Bootcamp_2022_Project_1/blob/main/Project_tools.png)

Dataframes, summary statistics, bar and pie charts, line plots, scatter plots, correlation and regression

## Technologies 
Jupyter Notebook, Pandas, MatPlotLib, Stats, NumPy, Seaborn, Python

## Installation
	source activate PythonData38
	jupyter notebook

## Analysis / Visualization / Graphs

1. Using cleaned data frame that removed any base salary counts of zero, a new data frame was built.
[![1.jpg](https://i.postimg.cc/Zqnzt5jc/1.jpg)](https://postimg.cc/8720LD2J)

2. Using the cleaned data frame, we were able to find which job titles/roles appeared the most within our data, and could be a further means of interest in seeing which roles these companies are hiring for if they are relevant to our skills.
[![top-ten-job-roles.png](https://i.postimg.cc/kXv02bps/top-ten-job-roles.png)](https://postimg.cc/BXtYyXsP)

3. Using the cleaned data frame, we were able to find the top 10 companies appeared the most within our data, and could be a further means of interest in seeing which roles these companies are hiring for if they are relevant to our skills.
[![top-ten-hiring-companies.png](https://i.postimg.cc/kXqZP5gb/top-ten-hiring-companies.png)](https://postimg.cc/dDNn8wds)
![alt text](https://github.com/nealp1910/NU_Bootcamp_2022_Project_1/blob/main/output_images/dataset-cover.png)
4. Using the cleaned data frame, we were able to find the top 10 locations in this data set.
[![top-ten-job-locations.png](https://i.postimg.cc/fRbrkgXW/top-ten-job-locations.png)](https://postimg.cc/bsKTBg34)
![alt text](https://github.com/nealp1910/NU_Bootcamp_2022_Project_1/blob/main/output_images/JOB_MAP.png)
Data skewed very much to first ten years, signifying that people don't typically stay in jobs for lifetime.

[![Years-In-Company.png](https://i.postimg.cc/3R2LPMM1/Years-In-Company.png)](https://postimg.cc/tZCtxM4n)

Data skewed more evenly in terms of years, barring some outliers.

[![Years-In-Industry.png](https://i.postimg.cc/rschThMk/Years-In-Industry.png)](https://postimg.cc/1nC0cr8C)

STEM is heavily dominated by MALE. 

[![Genders-In-Stem-Bar-Graph.png](https://i.postimg.cc/90pLQGQq/Genders-In-Stem-Bar-Graph.png)](https://postimg.cc/1V8GWV69)

[![Genders-In-Stem.png](https://i.postimg.cc/jdx8kkM6/Genders-In-Stem.png)](https://postimg.cc/pySYmkby)

There is no correlation between Gender and Salaries. 

[![Gender-vs-Base-Salary.png](https://i.postimg.cc/qM1mfXFP/Gender-vs-Base-Salary.png)](https://postimg.cc/6yGVnRtc)

[![Gender-vs-Total-Yearly-Compensation.png](https://i.postimg.cc/Hkj6T8DV/Gender-vs-Total-Yearly-Compensation.png)](https://postimg.cc/SnF6rsKh)

## Distribution of jobs in The World and Usa

![World_job_map](https://github.com/nealp1910/NU_Bootcamp_2022_Project_1/blob/main/output_images/World_job_map.png)
![Usa_Job_map](https://github.com/nealp1910/NU_Bootcamp_2022_Project_1/blob/main/output_images/Usa_Job_map.png)

## Distribution of race in jobs 

![race_as_factor_Pie](https://github.com/nealp1910/NU_Bootcamp_2022_Project_1/blob/main/output_images/race_as_factor_Pie.png)

![race_as_factor_bars](https://github.com/nealp1910/NU_Bootcamp_2022_Project_1/blob/main/output_images/race_as_factor_bars.png)
### Asian has a Dominance in Race Distribution

## Relation Between Education Degree  And Job Count 
**The Main Question here is: Can Education Replace Experience?**

![distribution_of_education_bar](https://github.com/nealp1910/NU_Bootcamp_2022_Project_1/blob/main/output_images/distribution_of_education_bar.png)
![distribution_of_education_pie](https://github.com/nealp1910/NU_Bootcamp_2022_Project_1/blob/main/output_images/distribution_of_education_pie.png)

Work experience can make you a good match for a particular job, but you may lack the essential skills for advancement tomorrow without higher education.

## Relation Between Education Degree and BaseSalary:

![basesalary_Vs_education](https://github.com/nealp1910/NU_Bootcamp_2022_Project_1/blob/main/output_images/basesalary_Vs_education.png)
![basesalary_Vs_education](https://github.com/nealp1910/NU_Bootcamp_2022_Project_1/blob/main/output_images/basesalary_Based_on_degrees.png)

Educational attainment and income are closely correlated, with higher degrees typically leading to higher salaries.
