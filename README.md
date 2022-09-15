# Kickstarting with Excel

## Overview of Project
Performing analysis on Kickstarter data to uncover trends

### Purpose
Evaluate the outcomes of Kickstarter campaigns based on launch date and financing goals to determine ideal conditions for launching a successful compaign

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Using information provided on the details of 4,114 Kickstarter compaigns, data was first analyzed using a pivot table to determine the number of successful, failed, and canceled campaigns based on the months in which they were launched. It was further filtered by parent category to view only results labeled "theater". 

This data was visualized with a line graph. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111674383/190319037-b425868d-ee38-4b52-85b5-e76dd750b45f.png)

### Analysis of Outcomes Based on Goals
The next analysis used the same Kickstarter campaign data to compare the outcomes (successful, failed, or canceled) of campaigns in the "plays" subcategory to their financing goals. Campaign goals were broken into 12 data ranges starting with "less than 1,000", ending with "50,000 or more", and then divided equally into 10 ranges between those amounts. The CountIfs() function was used to calculate how many of each outcome occurred in each financing goal range. After calculating the total projects at each funding goal amount, the percentage of succesful, failed, and canceled campgaigns for each goal range was calculated. 

This data was also visualized with a line graph.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111674383/190318009-dc77cd18-885c-4f18-ae5c-7cee27570d17.png)

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
