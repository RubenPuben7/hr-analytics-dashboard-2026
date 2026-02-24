
🧾**Project Overview**

This project aims to develop a dynamic dashboard, linking an employee sample data via excel.  
The aim of this dashboard is to improve accuracy and accessibility by amalgamating data in an easily interpretable format. 



🎯 **Objectives**

This dashboard previews simulated company data, encompassing:
- headcounts
- tenure
- salary data
- attrition/separations

Some questions this dashboard sets out to answer:
  **Workforce size/capacity:**
- How many people do we have right now, and how is this changing over time? 
- Where is our workforce growing or shrinking (by team, function, location)? 

  **Retention/Stability**
- Are we losing people at a sustainable or concerning rate?
- Which teams, roles, or locations have the highest attrition?
- Is turnover increasing, decreasing, or stable over time?

  **Experience/Workforce maturity**
- Where are we at risk of knowledge loss due to long-tenured exits?

  **Pay/Investment**
- Are there pay equity risks (e.g. role, gender, location)?
- Are high-attrition areas underpaid relative to market or peers?



🧰 **Tools & Techniques**

- Power BI, Excel, Data cleaning, Data modeling, DAX measures.



💡 **Dashboard Highlights**

**Highlights**
- Attrition (23%) indicates risk - healthy attrition rates are between 10-15% according to Rippling https://www.rippling.com/en-AU/glossary/attrition 
- Growth has flattened despite continued hiring
- Mid-career exits are emerging as a strategic capability risk
- Pay pressure is unevenly distributed by function
- Engagement score (74%) is moderate - strong engagement is considered >80% according to CultureAmp https://support.cultureamp.com/en/articles/7048605-standard-report-factors



💡**Key Insights**
Screenshots with short explanations of visuals.

`Dashboard Snapshot Year_Range: 2010-2025`
<img width="845" height="479" alt="image" src="https://github.com/user-attachments/assets/4caffe56-fc04-4f0b-8556-092399ad0ed0" />

`Dashboard Snapshot Year_Range: 2023-2024`
<img width="845" height="479" alt="image" src="https://github.com/user-attachments/assets/ad872f49-a74a-4bc1-bfbd-7974e2099128" />



 **Workforce size/capacity:**
 - Headcount as at 2025 was 385, increasing steadily from 2010. Headcount peak was around 433 in 2019-2020
- 2020 showed the highest active employees, with a headcount of 433. Largest drop occured between 2022-2024 with 28 separations. Separations started increasing and remained high from 2018.
- The largest group with and age range between <20 - 50 are Males, with the exception of those around 30years and those >50years old. These seem to be dominated by Females.
- Gender split in the company is quite even. 50.8% Males, 49.2% Females
- Workforce is shrinking predominantly in HR, Finance, and IT.
- The Net Growth Rate from 2010-2025 was 134.4% and 96.2% in 2023-2024.

**Retention/Stability**
- It appears that salary may be a reason employees resign, as those in HR, Marketing and Sales have the high separations and are among the lowest paid.
- The organisation is struggling most with early- to mid-career retention, could point to less internal promotions and future hiring costs as, typically these roles are filled by the future leadership pipeline.
- Turnover is not abating despite slower growth, suggesting structural retention issues. 

The Net Growth Rate from 2010-2025 was 134.4% and 96.2% in 2023-2024. After 15years of operating, the Company likely would not be in a growth phase, which would explain the reduction in Net Growth Rate, however, this change, coupled with attrition rates of 23%, and moderate engagement score of 74% it may be worth reviewing reasons why separations are occuring, EVP and implement retention initiatives.


 **Experience/Workforce maturity**
- Most separations were staff with between 6-14years tenure.
- Most prevalent education level of separated employees at the entry/mid- levels are High school, Bachelors and Masters, with Mid- and Senior level separated employees holding PhD level education. Most Executive level staff who are leaving hold Bachelors degrees.
- Mid-level and Senior roles pose continuity risk, where exits are harder to fill. This group, rather than the Entry level, Manager and Executive level have the greater financial and operational impact to the Company.
- The average tenure is 8.44years. The concern around knowledge loss/Workforce maturity relates to the large number of separations occuring predominantly at 6, 8, 11, 13 years tenure. This may be an indication of leadership bottle necks and/or the lack of opportunities in career progression.



📈 **Recommendations**

- Identify roles which are most at risk of separations, and have the most impact on Company continuity
- May be worth reviewing reasons why separations are occuring, and if its due to lack of career progression, begin succession planning, particularly across the mid-level roles.
- Update/Implement rentention strategies and EVP 
- Review salary benchmarks in the market and price roles accordingly, particularly in HR, Finance and Operations



📁 **Repository Structure**

> File: _hr_analytics_dashboard_ PowerBI Dashboard with sample data
> File: _mock_hr_dataset.csv_  Mock dataset used to construct this dashboard
> File: _reportThemeSchema-2.114_ the PowerBI theme schema code
> File: _HR_MockData_Theme_ the PowerBI theme used in this dashboard
> File: _hr_analytics_dashboard-2010-2025_ 2010-2025 data snapshot
> File: _hr_analytics_dashboard-2010-2025_ 2010-2025 data snapshot
