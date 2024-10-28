# Lending-Club-ITI-Graduation-Project
## Project Overview
This project analyzes Lending Club data as part of our ITI graduation project. This project builds a complete data solution for Lending Club, covering everything from data preparation to visualization.
- We created a database and data warehouse to organize Lending Club’s data.
- Built data pipelines with SSIS to move data smoothly from the database to the warehouse.
- Analyzed business data with SSAS and SSRS to generate meaningful reports.
- Developed interactive dashboards in Power BI and Tableau, making key insights easy to explore.

## Tools and Technologies
- **SQL Server**: For database management and queries.
- **SSIS**: For ETL processes.
- **SSAS** and **SSRS**: For advanced analysis and reporting.
- **Power BI** and **Tableau**: For creating visual dashboards.

## What is Lending Club?

[Lending Club](https://www.lendingclub.com/) is a peer-to-peer (P2P) lending platform that connects borrowers with investors, offering an alternative to traditional bank loans.

Lending Club enables borrowers to create unsecured personal loans between $1,000 and $40,000.
The standard loan period is three years. Investors can search and browse the loan listings on Lending Club website and select loans that they want to invest in based on the information supplied about the borrower, amount of loan, loan grade, and loan purpose. Investors make money from interest. Lending Club makes money by charging borrowers an origination fee and investors a service fee.

## Entity Relationship Diagram

![ERD](ERD.png)

## Database Diagram

![Database Diagram](<Database Diagram - OLTP.jpg>)

## Creating Data Warehouse using SSIS

![DWH SSIS](<LendingClub_DWH_ETL_SSIS\SC/Application Dim.PNG>)
![DWH SSIS](<LendingClub_DWH_ETL_SSIS\SC/Borrower Dim.PNG>)
![DWH SSIS](<LendingClub_DWH_ETL_SSIS\SC/Loan Fact.PNG>)

## Data Warehouse Diagram

![DWH Diagram](<DWH Diagram.jpg>)

## Analysis using SSAS

![Cube1](<SSAS/Cube 1.1.jpeg>)
![Cube1.2](<SSAS/Cube 1.2.jpeg>)
![Cube2](<SSAS/Cube 2.1.jpeg>)
![Cube2.2](<SSAS/Cube 2.2.jpeg>)

## Reporting using SSRS

![Report1](<SSRS/Report 1.jpeg>)
![Report2](<SSRS/Report 2.jpeg>)
![Report3](<SSRS/Report 3.1.jpeg>)
![Report](<SSRS/Report 3.2.jpeg>)

# Data Visualization
## Using Power Bi

![Dashboard](<Powerbi/1.PNG>)
![Dashboard](<PowerBi/2.PNG>)
![Dashboard](<PowerBi/3.PNG>)

## Using Tableau

[Public Tableau link](https://public.tableau.com/views/Grad-project/TrendsAndAnalysisDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

![Dashboard](<Tableau/Borrower Dashboard .png>)
![Dashboard](<Tableau/Loan Overview Dashboard .png>)
![Dashboard](<Tableau/Trends And Analysis Dashboard .png>)



