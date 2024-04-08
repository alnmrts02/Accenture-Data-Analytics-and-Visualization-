# Accenture-Data-Analytics-and-Visualization
## Certificate 
[Certificate](https://github.com/alnmrts02/Accenture-Data-Analytics-and-Visualization-/blob/main/Accenture_virtual%20internship%20certificate.pdf)

## Tools Used
- Excel
- Tableau
- PowerPoint

## Project Overview
This data analysis project involves thorough analysis of three different datasets to understand the user behaviour within the app. The main aim is to uncover insights such as peak usage in a month and also to find the highest scoring content category. Processes such as cleaning of raw datasets, data modelling, visualization and clear presentation of insights are critical steps in achieving the objectives of this data analysis project. 

## Process
### Understanding the Business Problem
- Understanding the client needs and business challenge.
- Identify the project deliverables and requirements.
- Identify the key tasks as a Data Analyst.

### Data Cleaning and Modelling
- Identifying which datasets will be required to identify " the top 5 categories with the largest popularity " using this [Data Model](https://github.com/alnmrts02/Accenture-Data-Analytics-and-Visualization-/blob/main/Data%20model.pdf).
- The required data sets are:
>- Content ID
>- Reaction Types
>- Content Type
>- Category
>- Sentiment
>- Score
- Cleaning of raw data by removing the rows that have missing values, changing the data type of a column and deleting rows that are not relevant for analysis.
- The raw data sets are:
>- [Content](https://github.com/alnmrts02/Accenture-Data-Analytics-and-Visualization-/blob/main/Content.csv)
>- [Reaction Types](https://github.com/alnmrts02/Accenture-Data-Analytics-and-Visualization-/blob/main/ReactionTypes.csv)
>- [Reactions](https://github.com/alnmrts02/Accenture-Data-Analytics-and-Visualization-/blob/main/Reactions.csv)
- The Datasets are cleaned by removing the blank rows using filter option, changing the data type to make sure it is consistent and removing columns which are not relevant to the analysis.
- The columns are merged using VLOOKUP function.
- The sum of different categories is derived using SUMIFS function and converted the data type to values.
- By arranging the values in descending order, we get the top 5 categories.
- The final data set: [Clean data](https://github.com/alnmrts02/Accenture-Data-Analytics-and-Visualization-/blob/main/clean%20data.xlsx).

### Data Visualization
- The cleaned data is converted into meaning full insights by graphically representing it.
- Visualization is done using Tableau.
- Top 5 categories by aggregate popularity score [Here](https://github.com/alnmrts02/Accenture-Data-Analytics-and-Visualization-/blob/main/Top%205%20Categories.png).
- Popularity score in percentage of top 5 categories [Here](https://github.com/alnmrts02/Accenture-Data-Analytics-and-Visualization-/blob/main/Popularity%20percentage.png).
- Monthly usage [Here](https://github.com/alnmrts02/Accenture-Data-Analytics-and-Visualization-/blob/main/Monthly%20posts.png).

### Presentation
- The presentation was prepared on PowerPoint and was presented to the client [Here](https://github.com/alnmrts02/Accenture-Data-Analytics-and-Visualization-/blob/main/Social%20Buzz%20Presentation.pptx).

## Insights
- The Top 5 categories are:
>- Animals
>- Science
>- Healthy eating
>- Technology
>- Food
- The category "Animals" had the highest score (75K).
- The month of May had the highest usage.
- It was found that there were 16 unique categories.
