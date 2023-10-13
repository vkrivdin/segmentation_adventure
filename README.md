# Segmentation Adventure BI dashboard
This project is about realizing case of customer segmentation based on AdventureWorks dataset

## Objective
Create customer segmentation that shows customer count and their sales revenue for any selected period (up to month) using last 12 month sales revenue as a base of segmentaiton

## Requirements
1. Customers segmentation is set on static sales revenue threshold values
  - there are five segments in total
  - threshold levels are 0, 5 and 10 thousand $
3. Sales revenue amount to be checked against the thresgold is the last 12 month sales revenue amount
4. Last 12 month amount must be calculated respective to the period of interest or analysis
  -  i.e. if I am looking at May 2023 then I expect sales revenue of April 2022 to May 2023 to be considered as last 12 month
5. Customer may appear in different segment each month as a consequence of using last 12 month
6. It must be possible to see the overall situation with customers - how many, in which segment, how much sales revenue each segment brings
7. It must be possible to view the trend over time in situation with customers
8. It must be possible to investigate each customer individually - what they bught, when, what is their current segment, did they change the segment in any month

## Source of data
Microsoft sample dataset
- https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms

## Credits
The base idea of setting up the segmentation rules through DAX is realzied with pattern presented by SQLBI team
- Dynamic customer segmentation pattern article - https://www.daxpatterns.com/dynamic-segmentation/
- SQLBI - https://www.sqlbi.com/
