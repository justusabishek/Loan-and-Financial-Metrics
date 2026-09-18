# Loan-and-Financial-Metrics-Dashboard

###Dashboard Link : https://app.fabric.microsoft.com/groups/6217c4d8-2cf4-4717-a2f2-017b97a42569/reports/ee39bb85-55b9-48de-b9e2-41f5aec50ca9/4e27094a3fc36f9a4756?experience=fabric-developer

### Problem Statement
This dashboard provides a comprehensive view of loan performance, applicant demographics, and financial risk metrics. It helps financial institutions understand borrower profiles, track loan distribution across categories, and monitor default trends. By combining demographic and financial data, the dashboard enables better risk assessment and supports data-driven lending decisions.

### Steps followed
 - Step 1 : Uploaded dataset into Microsoft SQL Server Management Studio (SSMS).

 - Step 2 : Performed data cleaning in SQL Server (handled nulls, standardized column names, removed duplicates).

 - Step 3 : Connected the cleaned dataset to Power BI Service through a Dataflow.

 - Step 4 : Configured the Dataflow to refresh and transform the dataset, ensuring reusable and scalable data pipelines.

 - Step 5 : Connected the Dataflow output into Power BI Desktop for report building.

 - Step 6 : Created calculated columns and measures using DAX for loan amounts, credit score bins, and applicant segmentation.

 - Step 7 : Designed multiple dashboards with tabs:

   - Loan Default & Overview

   - Applicant Demographics & Financial Profile

   - Financial Risk Metrics

 - Step 8 : Added visual filters (Slicers) for Age Group, Marital Status, Education Type, Employment Type, and Credit Score Category.

 - Step 9 : Inserted card visuals for KPIs such as median loan amount, total loans, and YOY changes.

 - Step 10 : Built bar charts, line charts, and flow diagrams to represent loan distribution, default rates, and demographic breakdowns.

 - Step 11 : Styled the dashboard with a professional theme, added project title and company logo.

 - Step 12 : Published the report to Power BI Service for collaboration and sharing.

### Snapshot of Dashboard (Power BI Service)
Loan Insights 
<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/3e60dcf5-64a6-4234-a792-4c72fa64f0c2" />

Applicant Demographics
<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/db059beb-5283-4ab8-ae33-fbb996f381ab" />

Financial Risks Metrics
<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/ede57bdf-3147-4ea7-97e4-051521f56d14" />

## Insights 

A multi-page report was created in Power BI Desktop and published to Power BI Service.

Following inferences can be drawn from the dashboard:

### [1] Loan Default & Overview
 - Default Rate by Employment Type: Full-time, Self-employed, Part-time all around 22, Unemployed slightly lower at 21.

 - Average Income by Employment Type: Full-time highest at 82,792, others around 82,000.

 - Loan Amount by Purpose: Business loans highest at 1,684M, followed closely by Auto, Other, Education, and Home.

 - Average Loan Amount by Age Group: Middle Adults and Young Adults around 127K, Adults slightly lower at 120K.

 - Default Rate by Year: Stable around 88%, with slight increase in 2017.

### [2] Applicant Demographics & Financial Profile
 - Median Loan Amount by Credit Score: Ranges from 126.8K (Very Low) to 129.1K (Low).

 - Total Loans (Adults by Credit Score): Medium and High categories dominate with 1.19bn and 1.17bn respectively.

 - Loans by Education Type: Bachelor’s and PhD holders have the highest loan counts (~16.5K each).

 - Loan distribution by marital status and age group shows balanced segmentation across Single, Married, and Divorced categories.

### [3] Financial Risk Metrics
 - YOY Loan Amount Change: Fluctuations observed, with growth in 2015 (+3.82) and decline in 2014 (-2.03) and 2016 (-1.79).

 - YOY Default Loans Change: Similar trend, with increase in 2015 (+3) and decline in 2014 (-2).

 - YTD Loan Amount by Credit Score & Marital Status: Medium and High credit score bins dominate across marital categories.

 - Income Bracket vs Employment Type: High-income borrowers contribute 6bn in loans, with significant share from self-employed.
