# Bike-Sales-Analysis

## INTRODUCTION
The purpose of this research is to provide answers to specific queries regarding bike consumers in a certain region that fall into different age groups, have varied income levels, and so on. The dataset utilised in this evaluation was obtained from PSP Analytic's Data Analytics/Science class.

## Data Analysis Process
To effectively analyze this data, we followed the following process:

1.	Data collection
2.	Data Cleaning and Formating
3.	Data Exploration
4.	Data Visualization
5.	Insights and Recommendation

## Data Collection
This information was gathered via Joseph Elijah's email. Two files were attached to the email: the group assessment question and the assessment spreadsheet. When we opened the assessment file in Microsoft Excel, we saw that it contained multiple rows and columns of different types of data. The assessment questions that were provided helped us with the data analysis.

## Given questions: 
A.	Cleaning Data
1.	Eliminate Duplicates
2.	In column 2, change M and S to Married and Single. Likewise, using Male and Female in column 3 for M and F
3.	Verify that the values in the income column have '0' decimal points.
4.	Sort the ages by age groups in a separate column: youth (0–30), middle age (31–54), and elderly (55+). Use the 'IF' function as a tip.

B.	Visualisation and Analysis of Data

5. Display the correlation between
- Each gender's average salary and their history of bike purchases using PIVOT tables and charts.
- Commuters' trip distance and bike purchases
- Age range and bike acquisition.
- Based on the data in c above, recommend which age group the bike manufacturers should ignore.

## Data Cleaning and Formatting 
Make sure the data was clean and structured correctly before moving further with the research and visualisation. This is a screen grab of the initial information. 
- To make it easier to spot duplicate rows and blanks, we first highlighted and conditionally formatted the entire page in order to remove duplicates.
- Then, in order to obtain unique data, we used the Remove Duplicates function on the Data tab. When deleting duplicates, we discovered that the ID is the table's main key.
- Using the Find and Replace option in the HOME tab, we changed M and S as well as M and F with Married and Single with Male and Female in the Marital status and Gender column, respectively.
- Since the range was large, we next used the IF function to divide the ages into three major age groups. =IF(L2<=30,"Adolescent",IF(L2<=54,"Middle Age",IF(L2>=55,"Old")) is the formula that is employed. 

The cleaned dataset's appearance is displayed on the worksheet's Cleaned Data sheet.

## Data Exploration
To examine the structured data set and respond to the previously stated queries, we used pivot tables. Additionally, we employed data visualisation tools, specifically line charts, to precisely determine which age group bike makers ought to focus less on.

## Data Visualisation: An Illustrated View
We mostly used Microsoft Excel's bar and line charts to visualise the data and build the dashboards for this datasheet. 
- We can infer the purchasing behaviour of middle-aged singles in Europe using the slicer in the dashboard above.
- The figure below illustrates how using the slicer, it can be determined that those with graduate degrees make more money, with an average salary of $70,000.

## Conclusion
We have been able to respond to a number of fundamental business enquiries as a result of our investigation, including: 
- Which age group bike manufacturers should pay less attention to.
- The behaviour of middle-aged single Europeans when they buy bikes.
- Which degree receives the highest earnings

## Recommendations
- The middle-aged demographic should receive less attention from bike manufacturers because the chart indicates that they typically purchase more. 
- Therefore, since the number of middle-aged single Europeans who acquire bikes is quite low (approximately 70), these individuals are observed to travel fewer kilometres. 
- Instead, marketing efforts should concentrate more on the adolescent and elderly demographic.
