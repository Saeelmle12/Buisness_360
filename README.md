# Buisness_360
Buisness_360 Dashboard
Problem Statement:-
Atliq is a company which sells hardware product like keyboard,mouse,laptop etc.They faced significant losses in "North America" region so they decided 
to hire a data analyst team who can provide valuable insights which will help their company to give a overall analysis on how they should conduct their
buisness.
Steps:-
getting the data
1.Connected PowerBI to MySQL DB to fetch the data 

Cleaning the data
1.Replaced values of some of the columns where the values were inconsistent.
2.Change the data types for the columns.
2.Used merge and append queries on the tables for the  buisness requirement
3.Added a separate dim along with the fiscal year(for Atliq Fiscal year starts from september)
4.Created custom columns for visualization purpose

Modelling the Data:
1.After applying the transformation i created the relationship between more than 10 tables using snowflake schema.

Measures and Calculated Columns:
Craeted calculated columns like gross margin,net sales,postinvoice deduction etc in powerbi dekstop along with that
I have created some complex measures by using dax function like sameperiodlastyear,filter,selectedvalue,related,sum,switch etc

Insights Generation:
1.Created a report of 5 pages for 5 different audiences i.e finance team,sales team,marketing team,supply chain team,executive 
2.Each of the team will implement their policies based on the insights 
3.A variety of charts are used like bar chart,line chart,waterfall chart,KPI's(Key Performance Indicator) etc along with that bookmarks,report tooltip 
are also the part of the insights.

