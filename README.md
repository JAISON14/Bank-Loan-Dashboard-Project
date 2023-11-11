# Bank-Loan-Dashboard-Project
## Overview
The Bank Loan Dashboard project was designed to monitor, assess, and provide insights into the bank's lending activities and performance. The dashboards created in PowerBI and Excel serve to enhance data-driven decision-making, allowing for strategic planning in the lending operations of the bank.

## Dashboards
### Dashboard 1: Summary
The Summary Dashboard captures key loan-related metrics and their changes over time, providing a snapshot of the loan portfolio's health and lending strategy impact. It includes the following KPIs:

Total Loan Applications (MTD and MoM)
Total Funded Amount (MTD and MoM)
Total Amount Received (MTD and MoM)
Average Interest Rate (MTD and MoM)
Average Debt-to-Income Ratio (DTI) (MTD and MoM)
Additionally, it distinguishes between 'Good Loans' and 'Bad Loans,' with specific indicators for each category, helping in the assessment of loan portfolio quality.

### Dashboard 2: Overview
The Overview Dashboard visually represents various loan-related metrics through different chart types:

Monthly Trends by Issue Date (Line Chart)
Regional Analysis by State (Filled Map)
Loan Term Analysis (Donut Chart)
Employment Length Analysis (Bar Chart)
Loan Purpose Breakdown (Bar Chart)
Home Ownership Analysis (Tree Map)
These visualizations aid in identifying trends, seasonal patterns, and the distribution of loans across various categories.

### Dashboard 3: Details
The Details Dashboard offers a detailed view of the loan data, providing a comprehensive and user-friendly interface for accessing vital loan metrics, borrower profiles, and performance data.

### Excel Implementation
In addition to PowerBI, the dashboards were also constructed in Excel to provide a familiar and accessible format for data analysis. The Excel version mirrors the KPIs and visualizations of the PowerBI dashboards, utilizing pivot tables, charts, and formulas to manage and display the data effectively.

### Data Fields and Usage
The data utilized in the dashboards comprise several fields, each serving a specific purpose in loan management and risk assessment:

Loan ID: Unique identifier for loans.
Address State: Borrower location for regional analysis.
Employment Length: Indicates employment stability.
Employee Title: Job title for income source verification.
Grade/Sub Grade: Creditworthiness and risk classification.
Home Ownership: Housing status for financial stability assessment.
Issue Date: Loan origination date.
Loan Status: Current state of the loan for performance tracking.
Purpose: Loan reason for segmentation and customization.
Term: Loan duration.
Verification Status: Status of financial information verification.
Annual Income: Yearly earnings for creditworthiness.
DTI: Debt burden relative to income.
Instalment: Monthly repayment amount.
Interest Rate: Cost of borrowing.
Loan Amount: Principal amount borrowed.
Each field plays a crucial role in managing loans, assessing borrower risk, structuring loan terms, and making informed lending decisions.

## Implementation
The project involved loading the dataset from MS SQL into PowerBI and Excel. The dashboards were created using PowerBI's visualization tools and Excel's analytical functions, adhering to the requirements outlined in the problem statement and leveraging the data dictionary for accurate field usage.

## Data Validation
To ensure the accuracy and integrity of the data reflected in the dashboards, a thorough data validation process was undertaken. After the dataset was loaded into PowerBI and Excel from the MS SQL database, the following measures were implemented:

* SQL Query Verification: Direct queries were run against the MS SQL database to fetch raw data. This data served as a benchmark to validate the data presented in the dashboards.

* Data Consistency Checks: The results from PowerBI and Excel were compared against the SQL query results to ensure consistency. This step was critical to confirm that the data transformation and logic applied within PowerBI did not alter the actual figures.

* KPI Logic Validation: The calculations and logic that underpin the KPIs were meticulously reviewed. SQL scripts were used to replicate the KPI calculations independently, verifying that the PowerBI and Excel computations were correct and reliable.

* Cross-Verification with Source Data: The transformed data in PowerBI and Excel was cross-verified with the source data from the MS SQL database. This step was crucial to confirm that all data transformations, including filtering, grouping, and aggregation, were correctly applied.

Through these validation steps, the project ensured that the dashboards accurately represent the data and the insights derived are based on truthful and unaltered information. This rigorous validation process enhances the credibility of the dashboards and reinforces confidence in the data-driven decisions made using these tools.

## Conclusion
With the inclusion of robust data validation techniques, the Bank Loan Dashboard project stands as a reliable and authoritative source for monitoring the bank’s loan activities. The project not only presents critical data through intuitive visualizations but also guarantees the precision of the information displayed, enabling the bank to make informed and assured strategic decisions.
