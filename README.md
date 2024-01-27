# Udemy-Dashboard-Onyx-DataSet-Challenge-
This is a Dataset challenge held by OnyxData In Jan 2024.  The aim of the challenge is to showcase the best visualisation dashboard that will help the business leverage the data and drive growth. The dataset consist of details on Udemy course.


## Problem Statement
1. What is the Total Sales and Profit by Year and Month?
2. Is the Total Sales increasing or decreasing compared Year-on-Year? 
3. What are the propertions of sales for the various Sales Channel?
4. Are most of the products bought in-store via Cash payment or online payment?
5. What is the top selling and bottom selling product? And how much sales do they bring in?
6. What is the Ranking of Products based on Sales
7. What is the most popular Product Category?

## Data Sourcing
The data set is given by Onyx Data for the Data Challenge.
Link: [https://www.youtube.com/watch?v=CGgXHsD19Ek](https://onyxdata.co.uk/data-dna-dataset-challenge/datadna-dataset-archive/)


## Data Transformation/Cleaning
Data was cleaned and transformed with the Power Query Editor in Power BI and by creating new measures using DAX and the 'Quick Measure' function. Some of the applied steps include:
* Removing duplicate rows for the same course title
* Renaming Column headers to a more suitable and readable header (eg. 'is_paid' is renamed to 'Enrollment Type' to indicate if the course is Free or Paid.)
* Extracting Date from DateTime column as the course first published time is not crucial in this visualisation
* Creating new columns to classify the 'Course Fee' and 'Course Duration' in a Range for easy visualisation and interpretation of data (eg. Course Fee has been reclassified under the range (Free, <=50, 51-100, 101-150, 151-200, >200)

## Data Visualisation

This Dashboard was created for the Challenge Project. The second pic shows that when a user mouse over the visualisation, in this case the bar chart at the bottom-most righthand side, a tooltip will appear showing more details of the course including 'No. of subcribers, Course first published date, Course Fee, Course Duration and URL for the course'.

![Dashboard](https://github.com/VizCreation/Udemy-Dashboard-Onyx-DataSet-Challenge-/assets/157504708/3c38491c-70ad-422d-9e51-ae32b9cec1ec)


![Tooltip](https://github.com/VizCreation/Udemy-Dashboard-Onyx-DataSet-Challenge-/assets/157504708/f1947fb6-a9f9-465d-958b-116fff2a6428)

![Paid Enrolment Selection](https://github.com/VizCreation/Udemy-Dashboard-Onyx-DataSet-Challenge-/assets/157504708/2ca7be5b-2cc7-4570-bfc4-e601cfc6461b)

## Findings/Conclusion
1. The Total Sales and Profit in both years are $410k and $69k
2. The YoY profit is 127%, meaning that the Sales performance is better in 2022 compared to 2021.
3. The first Donut Chart shows that the highest Sales comes in the order of Direct Sales, Online and Wholesaler.
4. The second Donut Chart shows that Sales come almost equally from in-store purchase and online purchase.
5. Based on accumulated Sales in both years, the Top Selling Product is 'Product 41' and the Bottom Selling Product is 'Product 09'.
6. The Horizontal Clustested Bar Chart shows the ranking of Products by Sales (The top products are Product 41, 31, 42...)
7. The Pie Chart shows that the most popular product category is 'Category 04'.
