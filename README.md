# HR_Data_Analytics

### Software Tools and Requirements

1. [Github Account](https://github.com)
2. [VSCode IDE](https://code.visualstudio.com)
3. [Tableau](https://tableau.com)

## HR Analytics Dashboard

This Dashboard is used by HR department to know the total count of the employees, total attritation rate in particular department, age, gender, and many other factors. The dashboard contains different graphs such as pie chart, matrix, histogram, and many more to visualise different Factors. The excel dataset contains 39 columns and 1470 data entries.

![image](https://user-images.githubusercontent.com/69414362/219826837-ced75367-dfea-40a7-b9a4-94960532ad44.png)


Sheet 1 – KPI

●	Calculated field ‘Attrition count’ is created to count the people who have left the company.

●	Next calculated field ‘Attrition Rate’ is calcluated with the formula

 		Attrition Rate: Sum Attrition Count/ Sum Employee Count
		Active Employees: Sum Employee Count - Sum Attrition Count

<img width="1008" alt="KPI" src="https://user-images.githubusercontent.com/69414362/219811766-4fa724c8-37cf-47bd-8f9f-439a91736508.png">

Sheet 2 – Attrition rate by Gender

This sheet indicates the visulisation of attrition rate with respect to gender i.e. It shows how many Males/Females have resigned the company or organisation. 
●	Add Gener and Customer attrition count in Rows and Columns. 
●	Create another instance of the attrition count and make a Dual Axis chart and final graph looks like a lollipop chart.

![image](https://user-images.githubusercontent.com/69414362/219812451-33734138-d518-4132-a4c1-2af73c8e8890.png)


Sheet 3 – Department wise Attrition

●	Creation of pie chart with the column Department and sum of the attrition count.
●	The pie chart shows the attrition rate in department ‘R & D’ and ‘Sales’ is 56.12 % and 38.82% respectively. The attrition rate is very less comapred to the rest two.

![image](https://user-images.githubusercontent.com/69414362/219826819-1d3d5faa-4148-45e9-9fbe-b516b4d4e086.png)


Sheet 4 – Number of Employee by Age Group

●	Creation of bin with minimum size = 2, maximise size = 10, bin size = 1.
●	New parameter is created with Age(bin).
●	Employee count is added to the rows and bar chart is created as shown in the below figure.

![image](https://user-images.githubusercontent.com/69414362/219826876-5aa05dc8-8a36-4b22-b85c-7d4f83e26317.png)


Sheet 5 – Heat Map Chart / Matrix Chart

●	This sheet shows the job statisfaction index against their roles. The Job statisfaction column is converted to a categorical variable and table is retrieved which consists of rating from 1 to 4 where 1 being the lowest and 4 being the highest. The totals of both the rows and columns have been retrieved to get the total count.

![image](https://user-images.githubusercontent.com/69414362/219826904-48771d84-11fb-4818-b4d6-23292bc091f6.png)


Sheet 6  – Education Field wise Attrition

●	The bar graph is plotted to to view the attrition rate with respect to the education.

![image](https://user-images.githubusercontent.com/69414362/219826934-07aea988-5aeb-45a0-bbbc-7b2e6651ba65.png)


Sheet 7  – Attrition Rate by Gender with different Age group

●	The graph shows ‘donut’ chart of Age band w.r.t Gender and attrition count.
●	Add an dummy axis by clicking on the rows and type “min(1)”.
●	Create the same chart once again by dragging the AGG(min(1)) into the rows as shown in the below figure.
●         From the second Agg(min(1))(2), remove Gender and some attrition.
●	Make the dual axis chart.
●	Remove the header and axis, the labels must indicate the total count and even the percentage of total count.
●	Drag the attrition count into the second Agg. The age band is not in proper order and hence click on drop down of the Age band-> Sort -> Manual 

![image](https://user-images.githubusercontent.com/69414362/219826948-61081b9f-2e9c-4a15-825d-8b29df0e5998.png)


Dashboard: HR Analytics Dashboard

●	Select the size of the dashboard whih fits to the systems resolution.
●	The background of the dashboard is designed with the help of power point presentation(PPT).
●	All the 7 charts are added into the dashboard. All the grid lines, fonts, colors, size of the labels and titles are edited for a better look and easily readable.
●	Finally, the filter is being applied on few charts which makes all the other charts to change according to that data.












          





