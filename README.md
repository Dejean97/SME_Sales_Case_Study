# SME Sales Case Study

This project was my first attempt at an 'end-to-end' analytics project, taking raw business data and producing data models, insights and recommendations (including proposed customer segmentation) for a future sales strategy, as well as documenting the entire process as if in a consulting role.

Inspiration, and the data used, for this project came from the KPMG Data Analytics Virtual Experience Program on [Forage](https://www.theforage.com/virtual-internships/theme/m7W4GMqeT3bh9Nb2c/KPMG-Data-Analytics-Virtual-Internship?ref=oiP3eujQmJmMY5YfG). A powerpoint presentation covering the entire project can be found [here](https://github.com/Dejean97/SME_Sales_Case_Study/blob/73cf16fb2b729338cefbb498ae9d5b5ad51fd44d/Sprocket%20Central%20Ltd.pptx).

## Data Quality Assessment

### Brief

*Sprocket Central Pty Ltd , a medium size bikes & cycling accessories organisation, has approached Tony Smith (Partner) in KPMG’s Lighthouse & Innovation Team. Sprocket Central Pty Ltd  is keen to learn more about KPMG’s expertise in its Analytics, Information & Modelling team.*

*Primarily, Sprocket Central Pty Ltd needs help with its customer and transactions data. The organisation has a large dataset relating to its customers, but their team is unsure how to effectively analyse it to help optimise its marketing strategy.*

*The client provided KPMG with 3 datasets:*

- *Customer Demographic*
- *Customer Addresses*
- *Transactions data in the past 3 months*

*As well as a new customer list to employ a targeted sales startegy on, later on in the project.*

*You decide to start the preliminary data exploration and identify ways to improve the quality of Sprocket Central Pty Ltd’s data.*

### Task
Explore the data and draft an email to the client identifying the data quality issues and strategies to mitigate these issues.

This towards data science blog [post](https://towardsdatascience.com/the-six-dimensions-of-data-quality-and-how-to-deal-with-them-bdcf9a3dba71) was used as a framework to identify and measure data quality issues.

The raw [data](https://github.com/Dejean97/SME_Sales_Case_Study/blob/5b6dd3650e13e097ae742323e7f35f9a7e2ee9c4/Task%201/raw_data_for_cleaning.xlsx) was cleaned using python in jupyter notebook, which can be found [here](https://github.com/Dejean97/SME_Sales_Case_Study/blob/5b6dd3650e13e097ae742323e7f35f9a7e2ee9c4/Task%201/Data%20Cleaning.ipynb), and the resulting clean dataset exported as an excel file can be found [here](https://github.com/Dejean97/SME_Sales_Case_Study/blob/5b6dd3650e13e097ae742323e7f35f9a7e2ee9c4/Task%201/Sprocket%20Central%20Pty%20Ltd%20Clean.xlsx). Below are the key table stats pre and post data cleaning, as well as a summary of the identified data quality issues.

Pre-Cleaning Table Stats

![Pre-Cleaning Table Stats](https://github.com/Dejean97/SME_Sales_Case_Study/blob/8c7f4be3b954c8489b34c873aec1867235a24b6b/Task%201/Pre-Cleaning%20Table%20Stats.png)

Identified Data Quality Issues

![Identified Data Quality Issues](https://github.com/Dejean97/SME_Sales_Case_Study/blob/73cf16fb2b729338cefbb498ae9d5b5ad51fd44d/Task%201/Identified%20Data%20Quality%20Issues.png)

Post-Cleaning Table Stats

![Post-Cleaning Table Stats](https://github.com/Dejean97/SME_Sales_Case_Study/blob/73cf16fb2b729338cefbb498ae9d5b5ad51fd44d/Task%201/Post-Cleaning%20Table%20Stats.png)

A detailed description of data quality issues, and mitigatiion actions, can be found [here](https://github.com/Dejean97/SME_Sales_Case_Study/blob/73cf16fb2b729338cefbb498ae9d5b5ad51fd44d/Task%201/Draft%20Email%20Task%201.pdf) in the draft email for task 1.

Having cleaned the data, some preliminary insights into the three datasets were visualised in Power BI.

## Data Insights

Having read [this](https://towardsdatascience.com/cluster-then-predict-for-classification-tasks-142fdfdc87d6) towards data science post, I looked to combine previously learnt clustering analysis techniques with classification to identify which of the new customers posed the greatest potential value.

## Dashboard Presentation
