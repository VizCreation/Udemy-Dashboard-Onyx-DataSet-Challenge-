# Udemy-Dashboard-Onyx-DataSet-Challenge-
<In the process of editing>
This is a Dataset challenge held by OnyxData In Jan 2024.  The aim of the challenge is to showcase the best visualisation dashboard that will help the business leverage the data and drive growth. The dataset consist of details on Udemy course.


## Problem Statement
1. Is the Udemy business model sustainable? Are people willing to pay for the courses?
2. How to boost Udemy's profit from selling courses? What are some ways to expand the business?
3. Which category of courses is most sellable?

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

![Paid Enrollment Selection](https://github.com/VizCreation/Udemy-Dashboard-Onyx-DataSet-Challenge-/assets/157504708/2ca7be5b-2cc7-4570-bfc4-e601cfc6461b)

## Findings/Conclusion
1. Most subscribers (69%) are willing to pay for the courses, compared to 31% who are taking only the free courses. Hence, it seems that this business model is sustainable as there are more people paying than taking free courses.
2. From the Dashboard, 36% of all paid subscribers are willing to pay for courses that are less than $50. Udemy may consider providing more courses within this range and expand the category to include others such as language, personal improvement etc.
3. Web development is the most sellable course with 
