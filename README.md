# NY Stock Exchange Data Analysis

## Purpose:
The purpose of this final project is to choose a dataset to explore, analyze and present insights gained that might benefit a company or client. Analysis will be performed using python and several of its packages, visualizations of the data will be performed, and the work will be presented.

The purpose of my analysis that I performed is to provide a more easily readable and visual format of the historical data of S&P 500 companies from the New York Stock Exchange that could help individuals who are interested in investing in a certain stock to see the stock's past information and performance. This could help individuals make decisions more easily on where they would like to invest.

## Milestone 1: 
To identify a domain of interest, identify potential clients, find datasets that can be used, and propose a list of questions to ask the dataset(s) that an individual might be interested in.

**Domain:** New York Stock Exchange

**Potential Client/Stakeholders:** Individuals interested in investing, specifically buying stocks

**Datasets Used:** https://www.kaggle.com/datasets/dgawlik/nyse

  **These datasets consist of historical data of S&P 500 companies from 2013 to 2016.*
  
**Questions:**
1. What date did Aetna Inc have the highest "high" in 2016?
2. Which company had the lowest "low" in March of 2013?
3. What was the average gross profit of General Motors between 2013 and 2016?
4. What was the average total revenue of Amazon.com Inc from 2013 to 2016?
5. What was the total liability of Netflix Inc. in 2014?

## Milestone 2:
To read in the datasets using pandas and perform exploratory analysis to see the structure of each dataset, to see if any cleaning will need to be done 
in order to perform data analysis on them.

**Observations Made From Exploratory Analysis:**

*Dataset 1 "Fundamentals":* 
- Although the format of the data seems to be consistent at both ends of the dataset, there are NaN values which may interfere with data analysis and should be looked at more closely for each case if needed to answer the questions.
- There are many columns that will not need to be used, so several columns should be removed when the dataset is cleaned. The column names might also be shortened.
- Most columns with numerical data are float

*Dataset 2 "Securities":*
- There are some NaN values in both the head and tail of this dataset, which might need to be looked at more closely for data cleaning if they will be needed to answer the questions.
- These columns might need to be renamed so that it could be more easily understood what the columns show.
- Most of the columns are object types except the CIK column (that holds numerical data) which is an int type.

*Dataset 3 "Prices":*
- There do not seem to be many NaN values and the data looks consistent at the beginning and end of the dataset.
- These column names might need to be changed so that they are more descriptive.
- There is much more data in this dataset than in the first two datasets, in terms of number of rows.
- The numerical columns are float data types.

*Dataset 4 "Prices-Split-Adjusted":*
- Dataset 4 seems to be very similar to Dataset 3 in terms of its structure, either Dataset 3 or 4 will need to be chosen for the analysis


**The Jupyter Notebook file that contains the code for this milestone is included in the Repository under the name:*
- Final_Project_Part_2

## Milestone 3:
Read in each dataset again and putting each of them into a dataframe using pandas. Then cleaning each dataset so that information can be extracted more easily to analye the data and answer the questions. Each cleaned dataframe will then be saved to another CSV file.
- Some cleaning functions that were performed on the datasets include removing several columns, changing column names, and removing NA values.


**The Cleaned CSV files are included in the Repository under the names:*
- Fundamentals_Cleaned.csv
- Securities_Cleaned.csv



**The Prices_Cleaned.csv and Prices_Split_Adjusted_Cleaned.csv are too big to include in this repository but they are saved in the Final_Project_Part3 Jupyter Notebook file and the Prices_Split_Adjusted_Cleaned.csv is imported and used in Milestone 4 and 5.*


**The Jupyter Notebook file that contains the code for this milestone is included in the Repository under the name:*
- Final_Project_Part3
  
## Milestone 4:
To read in the datasets that were cleaned in Milestone 3 using pandas, and perform data analysis on them using aggregate functions in order to answer two of the question listed in Milestone 1. Plots are then created to visually represent the answers to these questions using matplotlib.py. Additional cleaning was performed on the cleaned datasets to more easily perform data analysis.

**Questions Answered:**
- Question 3: What was the average gross profit of General Motors between 2013 and 2016?
     - **Answer:** The average gross profit that General Motors had from 2013 to 2016 was $17854750000.0.
- Question 4: What was the average total revenue of Amazon.com Inc from 2013 to 2016?
     - **Answer:** The average total revenue of Amazon from 2013 to 2016 was about $101608250000.0.


**The Jupyter Notebook file that contains the code for this milestone is included in the Repository under the name:*
- Final_Project_Part4

## Milestone 5:
To read in again the datasets that were cleaned in Milestone 3 using pandas, and perform data analysis on the datasets using aggregate functions in order to answer all the questions listed in Milestone 1. Several more cleaning steps were performed on the datasets in order to get the desired output to answer the questions. The answers to questions 2, 3, 4 and 5 are also visually represented in bar plots using matplotlib.py. This milestone also includes a presentation that puts together all the work done on this project and to describe the purpose and use of this analysis, as well as insights gained and possible future work.

**All Questions Answered:**
- Question 1: Question 1: What date did Aetna Inc have the highest "high" in 2016?
     - **Answer:** Aetna Inc had the highest high in 2016 on December 2nd, 2016.
- Question 2: Which company had the lowest "low" in March of 2013?
     - **Answer:** The company with the lowest low in March of 2013 was Frontier Communications.
- Question 3: What was the average gross profit of General Motors between 2013 and 2016?
     - **Answer:** The average gross profit that General Motors had from 2013 to 2016 was $17854750000.0.
- Question 4: What was the average total revenue of Amazon.com Inc from 2013 to 2016?
     - **Answer:** The average total revenue of Amazon from 2013 to 2016 was about $101608250000.0.
- Question 5: What was the total liability of Netflix Inc. in 2014?
     - **Answer:** The total liabilities of Netflix Inc. in 2014 was 5184792000.0.


**The Jupyter Notebook file that contains the code for this milestone is included in the Repository under the name:*
- Final_Project_Part5

**The file to the Final Project Presentation Slides is included in this Repository under the name:*
- NY Stock Exchange Data Analysis - CMP Final Project.pptx

**A file of a summary of the project, including the insights learned and possible future work identified is included in this repository under the name:*
- CMP-262 Final Project Summary.docx



