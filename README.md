# HR Attrition Dashboard

An interactive two-page Power BI report that shows where employee attrition is highest, who is most at risk, and where HR should act first.

## Dashboard Preview

### Overview
![HR Attrition Executive page](HR%20Attrition%20Executive%20page.jpg)

### Job Role Deep-Dive
![HR Attrition deep-dive page](HR%20Attrition%20deep-dive%20page.jpg)

## Business Question

Losing employees is expensive. This project answers three questions for an HR team:
- Where is attrition concentrated?
- Which factors go together with employees leaving?
- Where should HR act first?

## Dataset

A public HR employee attrition dataset with 1,470 employees. 237 employees left, an overall attrition rate of 16.12%.

## Key Findings

- Attrition is highest during the first 1-2 years of employment.
- Attrition declines as tenure grows.
- 30.53% of employees working overtime left, compared with 10.44% of those who do not (about 2.9x higher).
- Attrition is highest in the lowest income group.

## Recommendations

- Review overtime workloads, especially in roles and departments with the highest attrition.
- Strengthen onboarding and support in the first two years, for example mentoring and regular check-ins.
- Review pay competitiveness for the lowest income group.

These patterns show association, not proven cause. They should be tested with further analysis such as exit interviews or statistical testing.

## How I Built It

- Data preparation: cleaned the raw dataset into a reporting table.
- Calculated columns: age group, tenure group, salary group and risk level.
- DAX measures: attrition rate, retention rate, turnover rate, headcount and early turnover.
- Interactivity: department and job role slicers, plus drillthrough from the overview to a job role deep-dive page.

## Limitations and Next Steps

- Some groups are small (for example, Human Resources has 63 employees), so their rates should be read with care.
- The data is a snapshot, so it cannot show how attrition changes over time.
- Next: repeat the analysis in SQL and test whether the overtime and income differences are statistically significant.

## Tools

Power BI, DAX

## Files

- Attrition dashboard main.pbix: the Power BI report (open with Power BI Desktop)
