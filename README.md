# Healthcare_Expenditure_Analysis

### Project Overview

This report presents an analysis of the trends in health expenditure in Canada, with a focus on the allocation of resources from 2010 to 2020. Demographic trends, per capita spending and correlations between categories of health expenditure were analyzed using data sourced from the Canadian Institute of Health Information.

### Problem Statement

Healthcare resource allocation across Canada has not consistently aligned with demographic changes or healthcare needs. Additionally, provincial-level spending trends across Canada reveal disparities that may not align with population growth or healthcare demands.

### Objectives

- Analyze healthcare expenditure trends.
- Examine demographic correlations.
- Evaluate cost-effectiveness of Healthcare resources.
- Support data-driven policy making.

### Data Selection

The primary dataset for this project is sourced from the Canadian Institute of Health Information (CIHI). 
It includes population statistics, public and private healthcare expenditures and detailed spending data categorized by province and healthcare priority areas. Data spans from 2010 to 2020.

### Data Preparation
#### Data Cleaning:
- Handled missing and null values
- Standardized inconsistent categorizations across provinces
#### Data Transformation:
- Calculated metrics such as per capita expenditures and growth rates
- Aggregated data to simplify analysis and identify trends
#### Data Integration:
- Merged population data with expenditure statistics to establish relationships and enhance analytical depth
#### Data Modeling:
- A snowflake schema was designed, consisting of a central fact table and supporting dimension tables
- Calculated columns, hierarchical date dimensions and one-to-many relationships were established to improve data model precision

### Tools

- Microsoft Excel (Data Wrangling)
- Power BI (Modeling and Dashboard)

### Results/ Findings
- A consistent upward trajectory in healthcare expenditure. Expenditure increased from 45 to 63 million representing a growth rate of 40% between 2010 and 2020
- Population growth showed a steady but slower increase. Growing from approximately 13.4 million to 14.7 million residents which is about 9.7% increase over the decade.
- The growing disparity between expenditure and population suggests increasing healthcare service demands and rising healthcare delivery cost.
- There is a strong positive correlation (0.99) between hospital and physician spending, indicating that increases or decreases in one are closely matched by changes in the other. For example, expanding hospital capacity often requires hiring more physicians, leading to higher spending in both areas.
- A very strong correlation of 0.97 also exists between hospital spending and drug expenditures, showing that as hospital activity increases, drug usage and costs also rise.
- Government healthcare spending per capita grew at an average rate of 4.58% outpacing population growth
- Privare sector spending also grew, though still lower in absoluter terms than public spenging

### Conclusion

- The growth of healthcare expenditure has outpaced that of population growth over the past decade indicating other cost drivers beyond the demographic expansion.
- Strong interdependencies between categories like hospitals, physicians, and drugs suggests budgetary planning across categories need to be in coherence for efficiency.
- Government’s spending per-capita kept pace with the nation’s growing population to ensure equitable access to healthcare.

Albeit the results showing publicly funded spending kept up with population growth, increases and uneven private spending trends highlights proactive strategies to address inefficiencies. Continuous monitoring and evaluation of expenditure patterns are essential for responsive and sustainable policymaking.

This analysis sets out the foundation for fostering a commitment to the equitable allocation of resources across provinces to ensure the sustainability of high-quality healthcare.
