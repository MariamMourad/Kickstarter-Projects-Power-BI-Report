#Kickstarter Projects Power BI Report

- Data Source: Two CSV Files (2016,2018)
https://www.kaggle.com/kemical/kickstarter-projects


Data Transformation:
- Create Custom Column has the file name (ex: 2016 or ks-projects-201612) (M Language)
- Append (Union) two files using M Language (Power Query)
- Rename the table that has the whole data with clear name (ex: KSProjects, ks-projects, Projects, AllDate) and
remove or hide other table/tables based on the steps. "we can do this by modeling"

Modeling:
- Create Hierarchy ( Main Category, Category and Project Name) Called it "Category Hierarchy"  
- We can hide the unneeded tables or rename tables.
- Number of Projects Measure
- Number of Backers Measure
- Total Pledged Measure 
- Total Goal Measure

Visuals: (Use Measures)
- Number of Projects Card
- Number of Backers Card
- Total Pledged Card
- Total Goal Card

- # Projects by Status (Execlude numeric statuses)
- # Projects by Category Hierarchy (Drill Down)
- # Projects by launched
- Total Pledged by currency
