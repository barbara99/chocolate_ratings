# EXPLORATORY DATA ANALYSIS FOR CHOCOLATE BAR RATINGS DATASET

# Authors

BERLINDA ASIEDU

BARBARA ASIAMAH

BENEDICT NARTEY

BELINDA OSEI-TUTU

# INTRODUCTION

Exploratory Data Analysis(EDA) is one of the most crucial steps in a Data Science project. EDA in basic terms is a way of "Understanding the data with the help of visualizations and descriptive statistics".
Chocolate is a preparation of roasted and ground cacao seeds that is made in the form of a liquid, paste, or in a block, which may also be used as a flavoring ingredient in other food. Chocolate is a worldwide loved candy for both kids and adults. Chocolate is basically made from cacao and a few other additives. 
The exploration of this data will be based on the data analysis cycle: understanding the data, posing questions, drawing hypotheses, data cleaning, data analysis, findings, and recommendations. This report spells out in detail the steps and procedures used in analysing the Chocolate Bar Ratings dataset. This is an analysis of 1795 chocolate bars from around the world. From the data, we will be looking at the chocolate bars’ various manufacturing locations, country of origin of the cacao beans, and overall rating, among a variety of other miscellaneous information. The data was gathered from Brady Brelinski of the Manhattan Chocolate Society.

# SOURCE OF THE DATASET

The dataset used here was given by the Azubi Africa, June 2020 Cohort Program.
The original ratings were compiled by Brady Brelinski, Founding Member of the Manhattan Chocolate Society.

# TOOLS USED

Jupyter Notebook via the cocalc, Collaborative Calculation and Data Science - For analysis and code

Google Sheets - For exploratory data analysis report

Google Slides - For Presentation

# UNDERSTANDING THE DATA

Analysis of data can only be effectively conducted when the data scientist is well informed and understands the data given. To achieve this, data profiling is done on datasets before any analysis is made. Data profiling involves summarizing a dataset through descriptive statistics, obtained in this project using Python’s describe function. After successfully completing profiling of the dataset, the results show that the dataset can be worked on after a few corrections.This dataset contains expert ratings of 1,795 individual chocolate bars from 2006-2017 along with information on their regional origin, percentage of cocoa, the variety of chocolate beans used and where the beans were grown. A rating here only represents an experience with one bar from one batch. Batch numbers, vintages and review dates are included in the database when known.  
A simple skim through the data can show that there are chocolates with rating, 1,0.9 and so on. However this is not enough to draw conclusions, thus the need for the data analysis.
A thorough look at the data revealed 9 columns and 1796 rows including column headings.The column heads cover the chocolate rating, the years under consideration, the specific cocoa bean type used to produce the chocolate, the companies producing the chocolate and more. The specific bean talks about the specific geo-region of origin for the bar.The column REF refers to a value linked to when the review was entered in the database. Under this the higher the REF, the more recent the rating. The review date is the date of publication of the review. The column cocoa percent talks about the cocoa percentage or the darkness of the chocolate bar being reviewed. The company location refers to  the manufacturer’s base country. The rating refers to the expert rating for the bar and the bean type is the variety or breed of bean used, if provided. Lastly, the bean origin refers to the broad geo-region of origin for the bean.

# QUESTIONS
After going through the data and understanding it we came up with a number of questions that will guide us in our analysis.

Which countries are the top 10 producers of beans used for chocolate bars?

What is the rating with the highest frequency?

How many chocolate bars have a 100% rating?

Which countries are the top 10 bean suppliers?

Which 10 companies have the highest ratings?

What is the average rating for each year?

Is there a relationship between the origin of a bean and the average rating of bars made from it?

Which chocolate beans have the highest ratings?

What is the average rating of chocolate bars made up of 100% cocoa?

What is the average rating of chocolate bars made up of 70% cocoa?

These questions were posed to help us make a good analysis of our data. They are the directional points in undertaking the exploratory data analysis. 

# HYPOTHESIS
From the questions asked above, we drew our hypothesis as stated below.

Null hypotheses

  There is no relationship between the percentage of cocoa in a chocolate bar and its rating.

  Less than 50% of raters will give chocolate bars ratings higher than 2.5.

  The average percentage of cocoa in bars does not change as the years go by. 

  The average rating of chocolate bars decreases over the years.

Alternate hypotheses

  There is a relationship between the percentage of cocoa in a chocolate bar and its rating.

  More than 50% of experts will give chocolate bar ratings higher than 2.5.

  The average percentage of cocoa in bars changes as the years go by.

  The average rating of chocolate bars increases over the years.

# Refer to the report in the repository for a detailed report on the analysis done.
