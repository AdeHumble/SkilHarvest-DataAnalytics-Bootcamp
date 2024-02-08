# <p align="center"/> SKILLHARVEST DATA ANALYSIS BOOTCAMP</p>

## INTRODUCTION
This repository is an archive of my learning journals during the data analysis training bootcamp with SkillHarvest Academy. Below, is a curated list of the bootcamp contents:
1. Speadsheets Fundamentals (Microsoft Excel & Google Sheets) - [Download Here](https://www.microsoft.com)
2. Github Fundamentals - [Create Your Account](https://github.com/)
3. PowerQuery - [Download Here](https://www.bing.com/ck/a?!&&p=1e37fcbc5a9a0c62JmltdHM9MTcwNzM1MDQwMCZpZ3VpZD0wMGU2MGU2ZC0wY2QwLTYzYmQtMDcxMi0xZGQ3MGRjZDYyZjkmaW5zaWQ9NTQ3Mw&ptn=3&ver=2&hsh=3&fclid=00e60e6d-0cd0-63bd-0712-1dd70dcd62f9&psq=power+query+download&u=a1aHR0cDovL3d3dy5vZmZpY2UubWljcm9zb2Z0LmNvbS9leGNlbC9kb3dubG9hZC1taWNyb3NvZnQtcG93ZXItcXVlcnktZm9yLWV4Y2VsLUZYMTA0MDE4NjE2LmFzcHg&ntb=1)
4. Introduction to PowerBI - [Watch Tutorials Here](https://www.youtube.com/watch?v=fnA-_iDV_LY&list=PLoyECfvEFOjaMKFbBSKSmnOpEcXqqRegW)

## 1.0 SPREADSHEETS FUNDAMENTALS
Spreadsheets are powerful tools used for organizing, analyzing, and presenting data in a structured format. They consist of rows and columns, forming a grid where data can be entered, manipulated, and calculated.

They play a crucial role in various aspects of business, education, and personal organization. Hence, understanding their features and capabilities can significantly enhance productivity and decision-making processes.

- **Major types:** Microsoft Excel & Google sheet
- **Key features:** Organization, Calculations, Data analysis, Visualization & Collaboration
- **Common uses:** Financial management, Data tracking, Analysis & Reporting, and Decision making
- **Differences:**

<div align="center">
  
| Feature | Microsoft Excel | Google sheet |
|---------|-----------------|--------------|
|Ownership|Requires installation  & licenses|Cloud-based, accessible online|
|Cost|Paid software, licenses required|Free basic features, paid options|
|Functionalities|Advanced data analysis tools|Basic to intermediate capabilities|
|Collaboration|Limited collaboration features|Robust real-time collaboration capabilities|

</div>

## 2.0 GITHUB FUNDAMENTALS
A. Here, we were introduced to Github as a/an:
  - Version control & Collaboration Tool
  - Open source
  - Learning resources
    
B. How to create a Github account
C. How to create a repository
D. How to develop a Github project readme file
  
## 3.0 POWER QUERY
Here, we used **SkillHarvest_Stationary_Supplies.csv** to demonstrate the use cases of some power query functions. Below is an excerpt from the datasheet.

#<p align="center"/> **Excerpt From The Datasheet** </p>

![Datasheet](images/DatasheetExcerpt.PNG "Sample of Datasheet")

## 3.1 POWER QUERY EXERCISES
1. Show sales Rep whose Items are Pen Set and Binders
2. Show sales of binder items and pencil in 2015
3. Show sales in Central and East region in 2014
4. Show sales in August and September 2014
5. Show sales of items that start with Pen, include their region, sales rep and year.
6. Show sales of items that end with ‘sk’, include their region, sales rep and year

## <p align="center"/> TASK ONE SOLUTION </p>
```
PowerQuery
=QUERY(A1:H44, "SELECT B,C WHERE C='Pen Set' OR C='Binder'",1)
```
![Task1 Solution](images/Task1-Sol-Excerpt)

