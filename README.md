# Spending vs Scores: A Data-Driven Look at Education Spending and Student Achievement




## Table of Contents
* [Presentation](#presentation)
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#normalizing-the-data)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Data Sources](#data-sources)
* [Conclusion](#conclusion)

## Presentation
Link: https://www.canva.com/design/DAGwzaPNkm0/vZZU7axKwrYnan7-O9D3Xw/view?utm_content=DAGwzaPNkm0&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h6bd4bf5f77

## Motivation:
Education funding is one of the largest investments a state or district makes. It shapes the workforce and holds long-term economic implications, yet the relationship between financial decisions and student outcomes remains complex.  Without a clear understanding of how dollars translate into learning gains, policymakers and educators risk making decisions that do not maximize student success. 
By analyzing trends in funding alongside student performance outcomes, we can unveil patterns that will enable decision-makers to prioritize strategies that directly support student learning and long-term success, expanding access to high-quality education for all students.


## Questions:
Main question:
Does more spending on education actually lead to better student performance over time?

Sub-questions:
1) How have overall education budgets and per pupil expenditure (PPE) changed over time?
2) Is there a measurable correlation between spending and student performance
3) Do states with the highest and lowest education spending demonstrate predictable differences in student outcomes?
4) How do student economic backgrounds impact performance trends?

## Normalizing the Data
All monetary values are adjusted for inflation and expressed in 2024 dollars.

## Problems and Hurdles
Processing 24 years of budget data was time-consuming: each year had to be downloaded, cleaned, and merged. The final data set needed to be converted from wide to long format, especially for ease of creating visualizations. Some CSVs required encoding to load properly and all monetary values needed to be adjusted for inflation.

## Technologies Used
1) Python / Pandas - for exploration, normalizing, cleaning and aggregation of the dataset(s)
2) Power BI - for creating data visualizations
3) Canva - for project presentation
4) Git - for version control

## Data Sources
The following sources were used to collect datasets for my analysis:

1) National Assessment of Educational Progress (NAEP) - 4th & 8th grade Reading and Math, 2000-2024
https://www.nationsreportcard.gov/ndecore/xplore/nde

2) U.S. Department of Education Budget History, 2000-2024
https://www.ed.gov/about/ed-overview/annual-performance-reports/budget/us-department-of-education-budget-history

4) Kids Count Data Center, Per-Pupil Educational Expenditures in the United States, 2000-2020 
https://datacenter.aecf.org/

## Conclusion
The analysis shows that higher spending does not always correlate with better student performance. Utah, despite having the lowest per-pupil expenditure (PPE), outperforms the District of Columbia (DC), although student performance growth from 2000-2024 was slower than DC's. Massachusetts consistently leads in 4th and 8th grade math and reading, even though their PPE is below DC. Disaggregating performance data by socioeconomic status reveals widening achievement gaps, particularly in DC. Overall, the growth observed in DC suggests that targeted investments can drive measurable improvements in student outcomes.
