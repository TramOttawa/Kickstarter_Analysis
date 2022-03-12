# Kickstarting with Excel

## Overview of Project
The analysis will be conducted based on the Kickstarter campaign data collected from 2009 to 2017 of 21 countries.

### Purpose
The purpose of this project is to provide Louis with the comparation between campaigns faired in relation to their launch dates and funding goals. Through kickstart data set provided, I will apply my knowledge in excel by using pivot tables and graphing to analyze the outcomes based on launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The following steps were applied to conduct the analysis:
Separate category and subcategory into two separated columns to apply filter by category
Convert dates using Unix timestamps into a readable format
Insert a “Year” column to filter by year
Apply pivot table and line charts to analyze the dataset.

### Analysis of Outcomes Based on Goals
The following steps were applied to conduct the analysis:
•	Create a new table to group the funding goals into 12 groups from less than $1,000 to over $50,0000
•	Apply COUNTIFS function to determine the number of successful, failed and cancelled of the campaigns based on the funding goal
•	Apply line chart that graphs the relationship between goal amounts, and it chances of success, failure or cancellation.

### Challenges and Difficulties Encountered
•	The main challenge I encountered while working on this project is that I spent a lot of time to understand the data and the requirements before working on analysis. I have followed the instructions and followed the guidelines on how to solve the problems as this is my first project working as a data analyst.
•	Another challenge that I had, is that the percentage of cancelled campaigns have all zeros which I first thought it was my mistake. I have verified the formulas and the dataset to make sure they are correct.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
•	When looking at the theater campaigns by month, we can see the best months to start the campaigns is in April with 107 successful campaigns, following by May with 104.
•	The worst months to start the campaigns is in November with only 35 successful campaigns, following is February with 44.
![image](https://user-images.githubusercontent.com/100484606/158025850-19701e47-02d6-4673-9372-1abf910dc39a.png)

- What can you conclude about the Outcomes based on Goals?
•	When looking at outcomes based on goal, it can be concluded that the rate of success is higher for campaigns with a funding goal that is less than $5,000; in which campaigns with a funding goal of less than a $1,000 up to $4,999 had a success rate ranging from 73% - 76%.
•	The campaigns with higher funding goals (from $50,000 or more) have a very low chance of success with the rate of 13% only.
![image](https://user-images.githubusercontent.com/100484606/158029648-7f93372c-0cc7-47de-9cbe-52a7a6ba8261.png)

- What are some limitations of this dataset?
•	Looking at the campaigns by country, 74% of the data is from the United States, which may not accurately predict the potential success of campaigns in other countries.
•	because theater is the largest category of campaigns, this could skew the success probabilities of other categories if the overall analysis was used to predict the potential for success of a campaign from another category.
•	To accurately predict the success of future campaigns, it would be best to consider the specific category and sub-category success probabilities in addition to the whole categories.

- What are some other possible tables and/or graphs that we could create?
![image](https://user-images.githubusercontent.com/100484606/158029782-c3f10c9a-505a-424f-b0d8-1bc9fae0b576.png)
![image](https://user-images.githubusercontent.com/100484606/158029794-6741b451-8efa-46a8-b956-4f3d863f8d80.png)


