
# QA Performance Dashboard (Excel Project)

## Project Overview
This dashboard was designed to support the Quality Assurance (QA) team in tracking both their auditing workload and Customer Service Advisor performance. It provides a dynamic, filterable view of monthly audit volumes, pass/fail rates, a 22-question scorecard, failure reasons, and remediation outcomes. The aim is to highlight performance trends, uncover training needs, and drive process improvement across departments and interaction types.


## Tools Used

**SharePoint** - Original data source (CSV Export)
**Excel** - Dashboard visuals, pivot tables, slicers, and KPI metrics
**Power Query** -  Data cleaning and transformation from SharePoint source
**Data Model** - Linked multiple tables for cross-filtering and data relationships
**DAX Measures** - Custom KPIs (e.g. Total Audits, Pass Rate %, Remediation Rate %)
**Pivot Tables** - Summarised data across time, questions, teams, and interaction types
**Conditional Formatting** -  Highlighted key thresholds for readability and quick decision-making


### KPIs
- **Target** – Editable field for monthly QA targets
- **Total Audits Completed** – Count of QA audits
- **Pass Rate (%)** – % of audits meeting quality standards
- **Remediation Rate (%)** – % of failed audits needing follow-up



### Core Visuals
- **Q1–Q22 Scorecard:** Pass/Fail/NA rates for each scorecard question  
- **Top 3 Failing Questions & Failure Reasons:** Quickly identify weak points  
- **Interaction Type Breakdown:** Channel-specific trends (e.g., calls, chat)  
- **Pass Rate Trend:** Month-by-month quality performance  
- **QA Volume by Auditor:** Audits completed per QA  
- **Team & Tenure Performance:** View results by team and experience level



## Example Insights
- Certain questions (Q3–Q5) consistently had high failure rates across multiple teams
- A process change in late December caused a dip in pass rates in January, followed by a recovery in February
- New agents (under 3 months tenure) showed lower QA pass rates, prompting tailored onboarding improvements



## Power Query Steps

- Removed sensitive fields (e.g., customer/employee names)
- Filtered blanks and irrelevant rows
- Split multi-response questions and failure reason fields
- Changed data types to enable correct analysis
- Unpivoted scorecard columns for better reporting
- Standardised text fields (QA names, team leads)
- Created custom columns (e.g., “Pass/Fail” logic) to support KPIs


## Files Included
- 'Excel_Dashboard_Aug_25_.xlsx' - Excel file containing the dashboard and a readme instruction page
- 'Excel_QA_Dashboard.png' - Screenshot of the final Excel dashboard
- 'readme_Excel.md' - Project overview and documentation


## Notes
- Data was sourced from SharePoint and anonymised before use
- Covers audits from **Nov 2024 – May 2025**
- Manual input: KPI target can be edited in Excel
- QA names and team leads have been anonymised
- Power Query steps are saved inside the Excel file under *Data > Queries & Connections*

