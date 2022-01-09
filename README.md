# Kickstater-analysis

Performing analysis on [Kickstarter data](https://github.com/crdhilep/Kickstater-analysis/blob/main/Kickstarter_Challenge.xlsx) to uncover the trends

## Overview of Project:
- Analyze the data Provided and share the hidden trends with Louise

### Purpose
The purpose of this project is to share results with Louise to compare the results of fundraising campaigns based on their launch dates and their funding goals. Which helps in planning successful Campaign in feature.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Based on Launch date, I created pivot table to filter the outcomes based on category and launch date.The Colums gives status of the campaign and rows shows the month of the campaign, this allows us to view the count of successful, failed and cancelled campaigns based on Parent Category selected.

![Theater Outcomes by Launch Date](/resources/Theater_Outcomes_vs_launch.png)


### Analysis of Outcomes Based on Goals
To analyze the Outcomes Based on Goals, I created a table to retrieve the total number of campaigns based off certain criteria. I used `COUNTIFS` formula to retrive the count based on given criteria which including a range for the desired campaign goal, the specific category, and the outcomes of these campaigns.

![Outcomes Based on Goals](/resources/Outcomes_vs_Goals.png)

### Challenges faced:
- Few shortcuts are bit tricky with MAC, like changing color of Markers & its fillings(Internet search helped more than F1 key) 

## Results

### Outcomes Based on Launch Date Conclusions

Based on [Theater Outcomes by Launch Date Chart](/resources/Theater_Outcomes_vs_launch.png) best months to start a Theater Campaign is May & June with higher success outcome(with May has highest successful events). Similarly, December would not be best month with more than 50% of non successful campaign.

### Outcomes Based on Goals Conclusions

Based on [Outcomes Based on Goals](/resources/Outcomes_vs_Goals.png), Play campaigns with higher goals tend to have a greater percent chance of failing. We can see that there is a treand where campaign success rates fall when goal amount become larger.
