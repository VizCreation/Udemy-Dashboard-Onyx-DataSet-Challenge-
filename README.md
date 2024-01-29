# Udemy-Dashboard-Onyx-DataSet-Challenge-
This is a Dataset challenge held by OnyxData In Jan 2024.  The aim of the challenge is to showcase the best visualisation dashboard that will help the business leverage the data and drive growth. The dataset consist of details on Udemy course.


## Problem Statement
1. Is the Udemy business model sustainable? Are people willing to pay for the courses?
2. How to boost Udemy's profit from selling courses? What are some ways to expand the business?
3. Which courses are most sellable?

## Data Sourcing
The data set is given by Onyx Data for the Data Challenge.
Link: [https://www.youtube.com/watch?v=CGgXHsD19Ek](https://onyxdata.co.uk/data-dna-dataset-challenge/datadna-dataset-archive/)


## Data Transformation/Cleaning
Data was cleaned and transformed with the Power Query Editor in Power BI and by creating new measures using DAX and the 'Quick Measure' function. Some of the applied steps include:
* Removing duplicate rows for the same course title
* Renaming Column headers to a more suitable and readable header (eg. 'is_paid' is renamed to 'Enrollment Type' to indicate if the course is Free or Paid.)
* Extracting Date from DateTime column as the course first published time is not crucial in this visualisation
* Creating new columns to classify the 'Course Fee' and 'Course Duration' in a Range for easy visualisation and interpretation of data (eg. Course Fee has been reclassified under the range (Free, <=50, 51-100, 101-150, 151-200, >200)
* Creating a new SortOrder table in Power Query to sort the 'Course Fee (Range)' in the correct order by value
* Merging Queries and expanding tables with the desired columns

## Data Visualisation

This Dashboard was created for the Challenge Project. <br>
<br>Users can use the 3 slicers at the top (in red) to choose their desired view for 'Cateogry, Year of Publish' and 'Enrollment Type'. The third picture is a tooltip that will appear showing more details of the course whenever a user mouse over the bar chart. Such details include the 'No. of subcribers, Course first published date, Course Fee, Course Duration and URL for the course'.

![Dashboard](https://github.com/VizCreation/Udemy-Dashboard-Onyx-DataSet-Challenge-/assets/157504708/97342dcc-ba3d-43c6-b588-6a4b92ab06d1)


![Tooltip](https://github.com/VizCreation/Udemy-Dashboard-Onyx-DataSet-Challenge-/assets/157504708/577da39f-617d-4f36-a8ba-772b1a806c88)

![Paid Enrollment Selection](https://github.com/VizCreation/Udemy-Dashboard-Onyx-DataSet-Challenge-/assets/157504708/0f10779e-091e-4f01-bcf5-d548b84d1db7)

## Findings/Conclusion
1. Most subscribers (69%) are willing to pay for the courses, compared to 31% who are taking only the free courses. Hence, it seems that this business model is sustainable as there are moajority of people paying than taking free courses and the earnings are sufficient to cover the course of running the site.
2. Currently there are only 4 categories of courses (Web Development, Graphic Design, Business Finance and Musical Instrument), Udemy may consider expanding the categories to include others such as language, personal improvement, grooming etc. Also, majority of subscribers (71%)  are interested in Web development courses, hence Udemy may consider including more such courses or add on intermediate or higher level web development courses. Also, based on the bottom middle bar chart, 61% of the total sales come from the courses that charge between $151-$200. It shows that people are willing to pay for the courses as long as the content is of their interest and beneficial to them.
3. Based on the course ranking by sales, Web Development and Musical lesson on Piano are one of the more sellable courses.
