# Kickstarting with Excel
## Overview of Project
Performing data analysis on the Kickstarting dataset that is from previous crowdfunding campaigns and analyzing it in Excel to help a playwright, Louise to determine specific factors that make a campaign for her upcoming project, a play “Fever” with a budget of over $10,000, successful. 
### Purpose
This project is to analyze Kickstarter dataset and visualize campaign outcomes to uncover any hidden trends in relation to goal amount, pledged amount, campaign outcomes, country, category and run times. Within the analysis, the dataset consisting of more than 4000 crowdfunding campaigns were further analyzed to understand how different campaigns fared in relation to their launch dates and their funding goals. 
## Analysis and Challenges
### Challenges and Difficulties Encountered
Challenges encountered were addressed below. 
### Analysis of Outcomes Based on Launch Date
The first part of the analysis is to visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date. I organized the data using conditional formatting to highlight the outcomes in different colors. Then I used the "Convert Text to Columns Wizard" feature to create two columns showing Parent Category and Subcategory, which will be utilized in the analysis. Then I ran into a challenge where I was to convert the Unix Timestamps into readable format. To overcome this challenge, I learned to use excel formula to convert and further create two columns "Date Created Conversion” and “Years” which will be utilized in the visualization. The length of crowdfunding campaigns is analyzed to help Louis plan her campaign timeline. Another challenge is to determine what type of chart can be created to determine the effectiveness of the timing of a campaign and to understand if there is a certain time of year when campaigns tend to be more successful. To create an insightful chart, Pivot Table is used to filter the Parent Category column to show only “theater” and to filter the outcomes column to show only “"successful," "failed," and "canceled." The table result shows the number of these three types of outcomes for each month of the year. Then a line chart from the Pivot Charts was created to visualize the relationship between outcomes and launch month. 
![](picture/Screenshot%201%20in%20Analysis.PNG)
### Analysis of Outcomes Based on Goals
The second part of the analysis is to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. The first challenge was to determine an effective way to analyze the relationship between the goal amount and the percentage of successful, failed, or canceled projects, for the “play” subcategory. The COUNTIFs formula was used to calculate these numbers, and the goal amount was grouped based on the dollar-amount ranges. That way, the percentage was easily calculated. A line chart from the Pivot Charts was created to visualize the relationship. 
![](picture/Screenshot%202%20in%20Analysis.PNG)
## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
1.  More successful campaigns for theater were launched in from April to August, and the month that launched the most successful Kickstarter campaigns was May. Therefore, Louise has a greater success rate if she creates a theater campaign in May. 
2. The number of successful campaigns is smaller in October, November and December and during this period, the number of failed theater campaigns increased in October. Therefore, Louise is not recommended to launch the campaign in October. 
- What can you conclude about the Outcomes based on Goals?

    The results from the graph show that if the goal amount is within less than $1,000 and up to $14,999, the success rate is higher than then the failure rate. The failure rate is higher than the success rate if the goal amount is within greater than $20,000 and up to $34,999 whereas campaigns with goal amount of greater than $45,000 have a higher failure rate. In summary, a reasonable goal setting is a very important factor to ensure a more successful campaign. 
- What are some limitations of this dataset?
  
    More demographics information of the backers can be analyzed to help us understand the targeted backers based on their locations, ages and interests. 
The dataset size is limited. With a larger dataset, we can identify more insights about measuring the spread of the campaign’s dataset based on descriptive statistics, and we can better understand any outliers and determine distributions of the data. 
The data period is from 2009 to 2017. Adding data from more recent years (for example, 2017-2022) can add insights into more recent trends. 
The data source can be extended to more sites. 
- What are some other possible tables and/or graphs that we could create? 
  
    Additional Pivot Table and Pivot Charts could be created to show 1) the relationship between campaigns success rates and country, 2) the average donation of different campaign outcomes (successful compared to failed), and 3) further analysis into the spotlight and staff pick information to see their impact on the campaign outcomes.   

