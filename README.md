# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis was to determine how other Kickstarter goals fared in relation to their launch dates and their funding goals.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The analysis of outcomes based on launch dates was performed through a pivot table and corresponding pivot chart. To make the pivot table I selected all the data from the Kickstarter file and selected the pivot table action in Excel. From there, the parent category was used as the filter, the outcomes as the legend, the months of the year as the axis, and the count of outcomes as the values. Then once the pivot table was made, I was able to select theater as the parent category and see the corresponding outcomes based on launch dates. From this pivot table, I was able to create a line chart to see a more visible analysis of the varrying launch dates and how they affected outcomes. 
### Analysis of Outcomes Based on Goals
The analysis of outcomes based on goals was performed through various equations and a corresponding line chart. To start, I separted out the different goal amounts into different rows and made columns that represented the amount of successful, failed, and canceled projects. To calculate the number of successful, failed, and canceled projects for each goal amount, I needed to use a COUNTIFS equation and select certain columns from the Kickstarter sheet to accurately represent the data I was looking for.  Once that was done, the total projects could be added up between each goal and the percentage of successful, failed, and canceled could be taken by dividng the respective number by the total projects. From there, a line chart was made with the x axis representing the goal amounts and the y axis representing the percentages. This chart was able to more visually the outcomes based on the goal amount.
### Challenges and Difficulties Encountered
The one challengeing step in this process was when making the pivot table (for the outcomes based on launch dates) the first option for row label is years, but we wanted to see this data through months. The other part I had trouble with was getting my pivot table to be in descending order, but I learned if you select the drop down arrow on the column labels tab you are able to select descending. As far as the analysis for outcomes based on goals, the difficult part in this was making sure to select the correct columns and writing the statement to count goals between two values.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
One conclusion that can be drawn about the outcomes based on launch date is that a theater production is more likely to be succesful than fail if the launch date is in June. The other conclusion that can be drawn is during the month of October a play will either be successful or fail but will not be canceled. 
- What can you conclude about the Outcomes based on Goals?
One conclusion that can be drawn about the outcomes based on goals is that a play has a very high percentage of failure rate is their goal is between 45,000 and 49,999 dollars. Another conclusion that can be made is that a goal between 15,000 and 19,999 has an equal chance of succeeding as it does failing. 
- What are some limitations of this dataset?
Some limitations of this dataset that might affect the goal of the analysis is that the dataset does not include genres. So while the purpose of our analysis is to look at the outcomes of other plays, it would be more beneficial to see the same results for the genre of play that our user is looking for.
- What are some other possible tables and/or graphs that we could create?
Some tables that could be created would be specific outcomes related to where the play is hoped to be launched. This would cause a better analysis and a more realistic outcome. This table could also then be translated into a bar graph to show the number of succesful, failed, and canceled kickstarters.
s
