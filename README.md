# MLDS-400-Group-9
MLDS 400 Group Project for Group 9

## Timeline & Deliverables: 
| Week | Date(s) | Plan & Deliverable(s) |
|----------|----------|----------|
| [Week 1](https://github.com/MSIA/MLDS-400-Group-9/tree/main/Week1)| Oct 6 - Oct 13 | Planning, Setting up access & Preliminary EDA |
| [Week 2](https://github.com/MSIA/MLDS-400-Group-9/tree/main/Week2)| Oct 14 - Oct 20 | Understanding and Cleaning the Data | 
| [Week 3](https://github.com/MSIA/MLDS-400-Group-9/tree/main/Week3)| Oct 21 - Oct 27 | Understanding and Cleaning the Data | 
| [Week 4](https://github.com/MSIA/MLDS-400-Group-9/tree/main/Week4)| Oct 28 - Nov 3 | Identify the Research Question | 
| [Week 5](https://github.com/MSIA/MLDS-400-Group-9/tree/main/Week5)| Nov 4 - Nov 10 | Feature Selection & Engineering | 
| [Week 6](https://github.com/MSIA/MLDS-400-Group-9/tree/main/Week6)| Nov 11 - Nov 17 | Feature Engineering|
| [Week 7](https://github.com/MSIA/MLDS-400-Group-9/tree/main/Week7)| Nov 18 - Nov 24 | Data Modelling| 
| [Week 8](https://github.com/MSIA/MLDS-400-Group-9/tree/main/Week8)| Nov 25 - Dec 1 | Data Modelling & ROI Analysis| 
| [Final Submission](https://github.com/MSIA/MLDS-400-Group-9/tree/main/Final%20Submission)| Dec 2 - Dec 5 | Presentation Week | 


## Weekly Updates: 

### Until Dec 1st, 2023
**What we’ve done this week:**
- Settled down with clustering and MBA analysis
- Started working on the report
- Prepared for ROI analysis

**Plan for next week:**
- Consolidate all codes
- Finish the report
- Complete ROI analysis

### Until Nov 24th, 2023
**What we’ve done this week:**
- Reduced dimensions used to cluster
- Clustered SKU using K-Prototypes
- Apply Market Basket Analysis for three clusters

**Plan for next week:**
- Optimze K-Prototype to find optimal K number
- Settle down with threhold for Market Basket Analysis
- Interpret Market Basket Analysis Rules generated
- Continue with the ROI Analysis

### Until Nov 17th, 2023
**What we’ve done this week:**
- Started working on Feature Preprocessing by looking at the selected columns in detail and checking feasibility for clustering
- Read up on Huang's paper : Extensions to the k-Means Algorithm for Clustering Large Data Sets with Categorical Values to include cateogrical and numerical data in clustering
- Explored using PCA to reduce dimensions since categorical variables have >10 levels
- Final selection of features finalised (with reasons to drop the others)

**Plan for next week:**
- Use learnings of PCA to reduce dimentions
- Start implementing the clustering model to group the SKUs
- Further implement MBA to recommend products for customers 
- Start with the ROI Analysis
  
### Until Nov 10th, 2023
**What we’ve done this week:**
- Selected the 'recommendation system' research question
- Started doing Feature Engineering on the columns in SKUINFO to ready them for clustering
- Laid out the entire Outline of how we will first use K-modes clustering followed by Market Basket Analysis to build the system
- Decided on what columns to use and how we will be treating them - WIP

**Plan for next week:**
- Start with engineering the features as decided and look out for problems, if any
- On completing the feature engineering step start with data modelling
- Data modelling would include first applying K-modes clustering followed by Market Basket Analysis
 
### Until Nov 3rd, 2023
**What we’ve done this week:**
- Brainstormed 2 possible research questions
- Cleaned up the TRNSACT and SKU tables that had inconsistent and missing data
- Fixed an error with the pg connection

**Plan for next week:**
- Assess the feasibility of the two questions and decide the final research question
- Study on how to do Market Basket Analysis/KNN and other clustering techniques on Python 
- Start feature engineering and preparation for the selected problem
- Apply an iterative approach to go back and clean/model the data for unforeseen problems 

### Until Oct 27th, 2023
**What we’ve done this week:**
- Identified inconsistent values in the price column (0s) in the TRNSACT table
- Discussed possible treatments for the inconsistent columns
- Brainstormed and narrowed down possible research questions that can be answered
- Loaded SKSTINFO and SKUINFO cleaned data into postgre using python connection

**Plan for next week:**
- Narrow down Research Questions and validate the problems
- Finalise the research question
- Fill in Null values or missing values in database if needed
  
### Until Oct 20th, 2023
**What we’ve done this week:**
- Cross-checked the column matching for csv files SKUINFO, SKSTINFO and TRNSACT
- Cleaned data for SKUINFO and TRNSACT
- Validate cleaned data for SKUINFO by checking csv file and pandas
- Test using postgres (Giving access, running SQL commands)
- Import DEPTINFO and STRINFO into postgress database
- Establishing the connection between pg database and python to access the table to access tables on python
- Setting up Dbeaver/pgadmin IDE for smoother running of codes

**Plan for next week:**
- EDA on cleaned data
- Verify special characters in SKUINFO
- Load remaining tables into pg
- Research Business questions that can be answered by ML techniques

### Until Oct 13rd, 2023
**What we’ve done this week:**
- Build up github repository
- Set up postgres, downloaded pgAdmin, connected to everything2023
- Examine DEPTINFO & STRINFO table through Python
- Clean SKSTINFO and SKUINFO table through Python
- Created the table, write TRANSACT.csv into postgres following the schema
- Import TRANSACT.csv from postgres into Python
- Import SKSTINFO.csv and SKUINFO.csv into Python
- Primary EDA 

**Plan for next week:**
- Create tables for the rest four datasets in postgres
- Explore the database and figure out the relationship between each other
- Further EDA
- Start cleaning the database tables
- Validate data cleaning result for SKUINFO table
- Explore ML questions
