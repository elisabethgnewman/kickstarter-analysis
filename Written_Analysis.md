# kickstarter-analysis

## Overview of project
This project involved utilizing what we learned in Module 1 in Excel to help Louise analyze the data she had for kickstarters. The purpose was to take the dataset and organize the data in a way that we could present it to Louise in a clear and concise way. We specifically looked at:
* Outcomes based on launch date and
* Outcomes based on goal
We utilized the skills we learned in Module 1 including: pivot tables, charts, and conditional formatting. It was a great way to conclude our chapter on Excel and put what we learned to the test! 

## Analysis and challenges
My analysis involved creating pivot tables to drill down to the specific type of parent category and subcategory of data that I wanted to present to Louise. Using pivot tables allowed me to organize the data in a way that it was easily presentable and interperatable. I also used charts to visualize the data. Using both the pivot tables and charts allows for the user to see the data in different ways. 

One challenge with both pivot tables and charts is deciding how to filter your data. When looking at the theater outcomes by launch date chart, this includes every year that had data about a theater launch. If the user is only interested in recent years or a specific time period, you would need to filter that data accordingly. It's important to understand what the user is trying to accomplish when organizing and presenting your data in both pivot tables and charts.

Another challenge I encountered was deciding what type of chart to use. Although we were advised to use a line chart for the outcomes based on goal pivot, I found the output to be rather hard to wrap my head around. The Y axis was percentage and the X axis was a dollar amount, so I did not feel a line chart was the best way for me to visualize the data. The good thing about Excel is you have many chart types to choose from and you can edit your data to help you paint the picture :paintbrush:.

## Results
![Outcomes Based on Goal](https://user-images.githubusercontent.com/88783255/132113333-2442dfaa-49a4-47ec-acce-327f7ec017b6.PNG)

As mentioned above, my outcomes based on goals chart presented the percentage of successful, failed, and canceled kickstarters in a line chart. As you can see in the chart, the goal amount does not seem to be highly correlated to the outcome. There are low dollar goals with high success rates (ex: >$1000 to $10,000) and high dollar goals with high success rates (ex: $25,000-$35,000).

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/88783255/132113335-82f59252-d387-4c8d-9ada-a520f2cfb512.PNG)

The theater outcomes based on the launch date chart above shows that May, June, and July are great months to launch a theater kickstarter! Overall, we see that theater kickstarters are more likely to succeed than fail in any given month, but the delta between the two is most significant in the summer months.

## Limitations
One limitation I encountered with this dataset is that there is a lot of unused information. The blurb and name fields do not provide us with information that we can easily compare across ids. Each blurb and name is unique to an id, so those fields don't help us analyze the data.

## Recommendations
I would recommend analyzing the data by both year and country. Since we are working with a lot of data in this file, sub-dividing or filtering the data into additional categories will help us better assist Louise with her kickstarter analysis. 
