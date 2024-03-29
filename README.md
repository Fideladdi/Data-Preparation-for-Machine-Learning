# Data-Preparation-for-Machine-Learning
Data Preparation for Machine Learning in R_Scientific Journals Influence Scores Prediction

Project Overview
This project focuses on the initial stage of preparing a dataset for a machine learning model aimed at predicting the influence scores of scientific journals. This is a regression problem where the outcome variable is the projected article influence score. The dataset involves information from various sources, including researchers, web scraping, and publishers, featuring details such as journal ISSN, title, publisher, subscription price, and article influence scores.
Objectives

-Data Cleaning:Identify and correct issues in the dataset to prepare it for machine learning analysis. This includes handling missing values, identifying and fixing data inconsistencies, and ensuring data quality.
- Data Integration: Combine information from three separate files into a single dataset, ready for analysis.
- Exploratory Data Analysis (EDA):Perform a preliminary analysis to understand the dataset's structure, variables, and potential issues.

Data Source
The data comes from the Flourish OA dataset and includes three files:
- `api_journal11-13-17.csv`: Contains journal ISSN, name, publisher, hybrid status, category, and URL.
- `api_price11-13-17.csv`: Includes subscription price, date of information collection, journal ISSN, influence ID, URL, and license information.
- `estimated-article-influence-scores-201.csv`: Features journal name, ISSN, citation count, paper count, average citations per paper, projected article influence, and the year of influence projection.

Methods and Tools
   - R Programming Language: Utilized for all data manipulation, cleaning, and analysis tasks.
   - RStudio and R Markdown: Employed for scripting, documentation, and reporting findings in an interactive manner.
   - Libraries: dplyr, tidyr, stringr, and other CRAN packages for data manipulation and preparation.

Installation and Usage
Ensure you have R and RStudio installed on your system. To replicate the analysis:
    Clone the repository or download the files to your local machine.
    Open the RMD file in RStudio.
    Install required libraries by running install.packages(c("dplyr", "tidyr", "stringr")) if not already installed.
    Execute the code chunks within the RMD file to perform the data cleaning process.
