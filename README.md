# Project1_Group4
First Group Project

Hypothesis:
We believe the main reasons for retirement at a younger age is consistent numerous factors such as; financial success within household, physical capabilities for their respective field & how dependant they are by defacto members. We also believe the age of retirement well prove to be less consistent overtime as there is more opportunity for success in certail fields of work.

The 3 Questions:
-Question 1: Do certain professions retire at an earlier age?
-Question 2: What factors influence early retirement?
-Question 3: How has retirement age changed overtime for everyone?

Assignments for members:
Swapna: Question 1 (all)
Gayan: Question 2 (factors including: super contribution & reasons for retiring)
Braydon: Question 2 (initial data cleaning of 'Characteristics of Retirees.xlsx' file & pre-retirement income factor).
Julia: Question 3 (dropped) 

Notes on assignment:
Findings:
Limitations:


# Retirement Analysis: 
Do certain professions retire at an earlier age? What factors influence early retirement?
 How has retirement age changed overtime for everyone?

##  Overview
The objective of this analysis is to investigate whether specific professions exhibit an inclination for early retirement and what factors influence it. By examining retirement age data across various professions, we aim to identify any patterns, trends that suggest a correlation between a person's occupation and the age at which they retire. This analysis seeks to provide insights into the retirement landscape across different professions and contribute to a better understanding of retirement patterns in the workforce.
#Data Source
https://www.abs.gov.au/statistics/labour/employment-and-unemployment/retirement-and-retirement-intentions-australia/2020-21#data-downloads


 ## prerequisites
  To produce this analysis, we will need the following tools and libraries:
  
  -Python Pandas
  -NumPy
  -Jupyter Notebook Matplotlib
  -The project involves several tasks:
  
# Table of contents:
1.	Preparing the Data
2.	Generate Summary Statistics and Obersvations
3.	Created Bar Charts
4.	A Line Plot 
5.	Results



# Tasks
  Our project team divided our tasks in to three parts:
  -Do certain professions retire at an earlier age? 
  -What factors influence early retirement?
    How has retirement age changed overtime for everyone?

First Task:
#  Do certain professions retire at an earlier age?
## Data overview:
## Preparing Data:
We cleaned data to desired data frame by using python code.
-The main Data set is read from excel file (Previous jobs of retirees - cleaned.xlsx)   is     retiries _df  consist of  Cleaned data set  includes variables , Year, Population of interest , age at different intervals ,Average age, Classification ,Category.
Image: retirees Data set.



Identify a statistical relationship or connection between two variables i.e. the type of profession and the retirement age.
**Specific Professions: ** The question is focused on particular occupations. It suggests exploring whether individuals in certain fields tend to retire earlier than those in other professions. Evaluate variable Category , find lists of last jobs in variable Classification and group them .
**Earlier Retirement Ages:** The primary focus is on the timing of retirement.  Determine if there's a tendency  for individuals in certain professions to retire at a younger age compared to different fields.
 **Implication:** The question implies that there might be a pattern or trend, and the analysis will involve examining data to identify if such a correlation exists.
  
### Observations:

**Early Retirement Industries:**- Categories such as Financial and insurance services, Electricity, gas, water and waste services, and Mining have notably lower average ages at retirement, suggesting that individuals in these industries tend to retire relatively early. i.e. at average age 48.16 and 48.83 .
**Mid-Range Retirement Ages:**  -Categories like "Manufacturing," "Wholesale trade," and "Arts and recreation services" fall in the mid-range of average retirement age falls under 52.9 to 54.8
 **Later Retirement Industries:** - Professions such as Professional, scientific and technical services, Transport, postal and warehousing, and Education and training have higher average ages at retirement, indicating a tendency for later retirement in these sectors .i.e. average age falls in  60.8 to 62.1

**Explore patterns**
   - Investigate potential patterns influencing retirement age and  decisions by calculating mean and median over  all years(2014-2021)

** Exploring median average age and related years**
**Graph showing top 5 Median average age values and respected years :**


 **Trends Over Time:** 
. **Comparative Analysis:**
   - Monitor the data over time to identify any emerging trends or shifts in retirement patterns within these industries.Compare these average retirement ages in two different years 1918-19 and 2020-21



# RESULTS:
In conclusion, our analysis of average retirement ages reveals distinct patterns across professions. Industries such as Financial and insurance services,Electricity, gas, water and waste services, and Mining exhibit a consistent trend of early retirements. So, it means some of professions retire early compared to other professions. 
Understanding these patterns is crucial for employers, policymakers, and individuals planning for their retirement. Further research, behind these trends and effecting factors can provide information to make future decisions.


About
-These projects were completed as part of Data Analysis Bootcamp.
Contact
If there are any questions or concerns, I can be reached at:
github: svuth23
[email: swapna.vuthpala@gmail.com]

Second Task:
What factors influence early retirement?

Dictionaries:
new_column_names: replaces headers in order to reduce length of titles in charts. (Specifier of data being in thousands is represented in the y axis of the charts).
income_categories: holds necessary income categories & reference values for sorting
income_classification: holds necessary income categories & reference values for sorting

##Breakdown of 'Characteristics of Retirees.xlsx' file

raw_data: derived from initial file, contains all relevant rows in regards to the question straight from 'Characteristics of Retirees.xlsx' file.
  | tidied_retirement_df: derived from raw_data, eliminating rows titled 'TOTAL' in order to not compromise data.
    |generalised_df: derived from tidied_retirement_df, only keeping rows where the 'Sex' column had the input 'Persons' (recognising this data is the total genders data).
      |income_df: derived from generalised_data, only keeping relevant classifications & categories (held by income_categories & income_classification).
                  Columns include 'Year', 'Classification', 'Category', (The 5 Age brackets), 'Total Retirees (thousands) & a Reference column (to order future df's when grouping).
        |chart_data_all: derived from income_df, only keeping columns with the most recent year for relevant data (2020-21)
        |chart_data: derived from income_df, exactly same as chart_data_all only without the 'Totals' column.
        |chart_data2: deriving from income_df, 




