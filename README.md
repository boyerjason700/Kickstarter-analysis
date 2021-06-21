
# Kickstarting with Excel

## Overview of Project
Using Kickstarter dataset, compare campaign outcomes based on launch dates and campaign goals.

### Purpose
Understand relationship of past Kickstarter campaigns between the launch dates and goals in relation to their outcomes.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
On 'Kickstarter' tab, new column was insterted at column U to identify year campaign was created using 'YEAR()' formula.  Using entire dataset, a pivot table was created on a new sheet to sort "theater" outcomes for each year. Outcome columns were reduced to "successful", "failed" and "canceled", removing "live" outcome.  Outcome columns were sorted by "successful" first.  
![Piviot_1](https://user-images.githubusercontent.com/74840026/122826464-083cdb00-d298-11eb-9d91-a9743a345acd.PNG)


Pivot line chart with markers was created using pivot table to graph data.  Data series were changed to match colors similar to example on Canvas.  Title was given to chart.  Chart was copied and pasted into 'Paint' and saved as .png file.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/74840026/122826781-679aeb00-d298-11eb-87cc-51793a76e764.png)


### Analysis of Outcomes Based on Goals
Creating new tab labeled 'Outcome Based on Goals', 8 columns created using defined categories as well as 12 rows with assigned value ranges.  Using the 'COUNTIFS()' formula, each count was found by drilling down the criteria for each column and its coresponding row value range, as well as by subcategory defined in the project.  Total number of counts were totaled up using the 'SUM()' formula in column E labeled "Total Projects".  Rows 15 and 16 were used to check accuracy of data by comparing column total with formula to find total number of projects with >0 value for each assinged outcome.  Columns F, G and H were found by dividing each outcome count by total number of projects for each value range and changing the cell format to 'percentage'.  
![Table_1](https://user-images.githubusercontent.com/74840026/122826550-260a4000-d298-11eb-8dc9-b73b8991e6fb.PNG)

Line chart was created to show the % of successful, failed and canceled outcomes for each value range.  Y axis was formated to have max bounds of 1.2 and major units of 0.2 to match example on Canvas.  Chart colors were also formated to match example.  Title given to chart.  Chart was copied and pasted intp 'Paint' and then saved as .png.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/74840026/122826744-5c47bf80-d298-11eb-8207-4249add2d0f3.png)

### Challenges and Difficulties Encountered
While using the 'COUNTIFS()' formula for deliverable #2, I did not include the 'plays' criteria for each cell to drill down through, giving me an incorrect chart result.  After re-reading the instructions, I realized my mistake and was able to include that criteria into each cell, giving me the desired result.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Based on the chart data, the month of May has had the most successful outcomes in the theater category.
2. Spring/early summer months yeild more successful outcomes than fall/winter months.

- What can you conclude about the Outcomes based on Goals?
1. Campaigns with a goal of $14,999 or less have a higher % for a successful outcome.

- What are some limitations of this dataset?
1. Can not conclude from data set why campaigns were canceled when goal fully met 

- What are some other possible tables and/or graphs that we could create?
1. Relation between staff picks and outcomes
2. Relation between spotlight and outcomes
3. What types of projects perform better in different countries

