# Visualising-bike-data-using-Tableau
![Illustration of the Citibike program](https://www.nyc.gov/assets/home/images/press_release/2018/November/pr576-18.jpg)

## Introduction
As the new lead analyst for the New York Citi Bike program, I'm now responsible for overseeing the largest bike-sharing program in the United States. In this new role, I will be expected to generate regular reports for city officials looking to publicise and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilisation. Each month, bike data is collected, organised, and made public on the Citi Bike DataLinks to an external site. webpage. However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so my first task on the job is to build a set of data reports to provide the answers.

## Instruction
-To see my Tableau visualisations, please navigate to "Links to Tableau workbook" file. Here, you'll see all the links to the workbooks that I created for the project with a brief description for each workbook. 
-To see my analysis of the results and insights gained from various Citibike datasets, please navigate to "citibike.md" file.

## Installations
The following dependency was installed for this project:project
1. `Tableau Public` which can be downloaded here: https://public-pantheon.tableau.com/en-us/s/download.

## Bike data dashboards and stories
For the current poject, I've created some visualisations, 2 dashboards (including a map) and a story to effectively build a set of data reports to provide the answers and insights into the Citibike program.

Please note that the months from June to August 2021-2023 were chosen for this analysis because they align with the summer break in NYC, where cycling activities are at their peak.

### Data retrieval and cleaning
These datasets were retrieved from https://citibikenyc.com/system-data for analysis and creating visualisations:
1. Bike data from the months of June-Aug 2021
2. Bike data from the months of June-Aug 2022
3. Bike data from the months of June-Aug 2023

Data cleaning and pre-processing was done using Python Pandas. Specifically, I:
1. Removed missing values
2. Renamed columns where needed
3. Performed type-casting where needed
4. Concatenated all 3 dataframes together (this was possible because the 3 datasets have matching columns)
5. Exported them as cleaned csv files

### Station-related dashboard
In this dashboard, I provide 2 bar graphs a map in order to answer these questions:

1. Which start stations were the most popular in the summer of 2021-2023?
2. Which end stations were the most popular in the summer of 2021-2023?
3. Where are these stations located?
![Alt text](<Screenshot 2023-12-23 at 5.04.50 pm.png>)

### Customer-related dashboard
In this dashboard, I provide 2 line graphs and a bar graph to anser these questions:
1. How does the distribution of members vs. casuals look like in the summer of 2021-2023?
2. What are the most popular weekdays for bike rides? 
3. What are the most popular hours for bike rides? 
![Alt text](<Screenshot 2023-12-23 at 5.11.51 pm.png>)

### Bike station story
Additionally, I aslo created a story  that brings together the visualisations, requested maps, and dashboards.
![Alt text](<Screenshot 2023-12-23 at 4.58.35 pm.png>)
![Alt text](<Screenshot 2023-12-23 at 4.58.50 pm.png>)

## Contribution
Special thanks to the following people for their contribution to the project:
-Camilo Vargas
-Learning assistants (BCS)
