# Customer-Churn-Analysis
This is a Data Visualization project that showed the percentage or rate of customers lost within  a bank following different  demography or status and was visualized accordingly using the Power BI tool.


![Customer Churn Analysis picture](https://github.com/ChimaJerry/Customer-Churn-Analysis/assets/132655711/6e0f178d-3987-47bb-81f0-9bd82cba9925)


##  Introduction
This project is aimed at analysis the customer churn (lost) of a bank and the services they render across 3 different countries. Churn analysis is the process of deep diving to know the attrition rate of customers in a company or in using a particular product or service. In this Power BI visualization, the Author compared the churn analysis across countries, gender, age, account balance, credit score etc.

### Table of Content
- [Data Source](#data-source)
- [Data Preparation](#data-preparation)
- [Data Modeling](#data-modeling)
- [Model View](#model-view)
- [Data Analysis](#data-analysis)                      
- [Data Visualization](#data-visualization)
- [Enhance the report](#enhance-the-report)
- [Save and publish](#save-and-publish)


### Data Source
The data for this Bank Customer Churn analysis was Downloaded from [here]( https://tinyurl.com/z4r3mv34). 

### Data Preparation 
Cleaning, formatting and reshaping the data was done. Data was imported into the power BI platform. At this stage I ensured there was no missing values within the data set. All columns were checked to ensure no outlier or unacceptable values find within the column by simple using the sort/filter function. The different columns were aligned to ensure it’s in the accurate data format for instance, age should be an integer, churn status a binary etc. Additional conditions were introduced into the dataset to group some of the elements of the datasets like age, credit score and account balance for ese of analysis.

### Data Modeling 
creating queries to model data for analysis and visualization. Appropriate data modeling techniques were introduces using queries to create data models for the account balance, age and credit score group as this will coming in useful during the data analysis and visualization build up.  

### Model view 
Review and edit relationships. The model view was checked to ensure each of the table view created aligns with the desired Model view or form of relation expected with each table. At this stage I created realigned each of the table views to reflect the kind of relation (one-to-one relationship with the customer data)

### Data analysis
Measure using the Data Analysis Expressions (DAX) was employed to get factors like the total number of customer using the count function, number of customers lost thus was able to calculate the churn rate or percentage the overall percentage was derived base on the information from the available data. 
### Data Visualization
Choosing and formatting the visual elements. The Donut chart was used to visualized the customer by age, active status, credit card status, categories customers by county and product while the line and Clustered column chart was used to show the relations between customers’ churn rate by age groups, customers churn rate by credit Score and customers churn rate by account balance. Also the Gauge chart was used to show the percentage of churn rate of customers across board for this bank. To be able to use the Gauge chart, I added two columns and customize same to show 0% as minimum and 100% as max and brought in the churn rate/percentage as the target into the chart. 
### Enhance the report
using and customizing themes. Enhance the report by making use of customer themes and formatted the designs to my choice to make it visually appealing to the eyes and removing any cluttering as much as possible.
### Save and publish
Every steps implemented was saved and then published to the Power BI service.


