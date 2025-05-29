
# University Salary Analysis Dashboard

## Project Background

This project analyzes salary data across 320 universities in the United States, examining compensation trends across different majors, school types, and geographic regions. As a data analyst investigating higher education career outcomes, this analysis provides insights into post-graduation earning potential for students and stakeholders in the education sector.

The analysis focuses on understanding salary variations across different academic disciplines and institutional characteristics, helping prospective students make informed decisions about their educational investments and career paths.

**Insights and recommendations are provided on the following key areas:**
- Regional salary disparities across the United States
- Performance comparison between different school types (Public vs Private)
- Major-specific earning potential and career prospects  
- Top-performing universities for starting salaries

**Analysis Tools:**
- Interactive Tableau dashboard for exploring salary trends can be found [here](https://public.tableau.com/views/salary_17460440281580/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Data Structure & Initial Challenges

The analysis utilized three primary datasets containing university and salary information, with a total of 320+ university records. The main challenge involved integrating multiple CSV files with inconsistent data structures:

![Screenshot 2025-05-29 150349](https://github.com/user-attachments/assets/202d4206-cf92-407a-acd7-6d14444f01aa)

**Dataset 1:** University basic information (Undergraduate Major,Starting Median Salary , Mid career median salary ,% change from starting to  Mid career median salary, Mid career 10th Percentile salary, Mid career 25th Percentile salary, Mid career 90th Percentile salary )

**Dataset 2:** Salary data by major and school (Starting/Mid-career salaries,School Name , School type)

**Dataset 3:** Detailed major categories and classifications(Starting/Mid-career salaries,School Name , Region)

**Key Data Quality Issues Addressed:**
- **Missing Salary Values:** Approximately 15% of salary records contained null values, particularly in the starting salary field
- **Data Integration Challenges:** Inconsistent key fields across the three CSV files prevented seamless joins
- **Data Standardization:** Varying formats for school names and major classifications required normalization

## Executive Summary

### Overview of Findings

The analysis reveals significant salary disparities across regions, majors, and institution types, with California leading at $51,032 average starting salary while the Western region trails at $44,414. Engineering and technology disciplines dominate the highest-paying majors, with Economics leading at $48,500, while traditional liberal arts fields like Criminal Justice ($35,000) and Education ($34,900) show lower starting compensation. Private institutions consistently outperform public universities in salary outcomes across all measured categories.

![Screenshot 2025-05-29 131753](https://github.com/user-attachments/assets/bbfd4c0b-5d30-49e7-9fbf-773b9f658003)


## Insights Deep Dive

### Regional Salary Analysis
**California dominates the salary landscape** with an average starting salary of $51,032, representing a 15% premium over the national baseline. This reflects the state's concentration of high-tech industries and higher cost of living adjustments.

**Northeastern region follows closely** at $48,496, benefiting from the financial services sector in New York and established business hubs in Boston and Philadelphia.

**Southern and Western regions lag significantly** at $44,522 and $44,414 respectively, indicating regional economic disparities that affect graduate compensation packages.

**Rural vs Urban divide is evident** across all regions, with metropolitan areas consistently offering 20-25% higher starting salaries than rural locations.

### School Type Performance
**Private institutions demonstrate superior salary outcomes** across nearly all metrics, with graduates earning approximately 12% more than their public university counterparts.

**Dartmouth College leads private institutions** with exceptional performance in the $130K+ range for average salaries, positioning itself among elite institutions.

**Public universities show competitive clustering** around the $100K average mark, with several institutions like Purdue University performing exceptionally well relative to their public status.

**Value proposition varies significantly** between institution types, suggesting that private school premiums may be justified by career outcome improvements.

### Major-Specific Earning Potential
**STEM fields dominate the top salary brackets** with Economics ($48,500), Physics ($47,000), and Math ($47,000) leading undergraduate major earnings.

**Engineering disciplines cluster consistently** in the $42,000-$43,600 range across Chemical, Computer, Aerospace, and Electrical specializations, showing reliable career prospects.

**Liberal arts and social sciences trail significantly** with Criminal Justice ($35,000), Education ($34,900), and Religion ($34,100) representing the lowest starting salary potential.

**Career trajectory analysis shows** that while starting salaries vary dramatically, mid-career growth rates tend to be more consistent across disciplines.

### Top University Performance
**California Institute of Technology (Caltech) leads** with $75,500 average starting salary, reflecting its elite engineering and science programs.

**MIT and Harvard represent** the traditional powerhouse combination of technical excellence and prestigious networking opportunities.

**Regional champions emerge** with Harvey Mudd College ($71,800) and Princeton University providing excellent value within their respective categories.

**Public institution representation** in the top 10 demonstrates that state schools can compete effectively with private institutions in specific program areas.

## Recommendations

Based on the insights and findings above, we would recommend **prospective students and education stakeholders** to consider the following:

**Regional considerations should heavily influence career planning.** Students seeking maximum earning potential should prioritize California and Northeastern opportunities, while those in Southern/Western regions should factor in 10-15% salary adjustments when evaluating job offers.

**STEM major selection provides the strongest ROI on education investment.** Students with aptitude in Economics, Physics, Math, or Engineering fields can expect 35-40% higher starting salaries compared to liberal arts disciplines, justifying the additional academic rigor.

**Private institution premiums may be justified for career-focused students.** The 12% salary premium associated with private universities, combined with networking advantages, can offset higher tuition costs over a career span.

**Geographic mobility significantly impacts earning potential.** Students should consider relocation flexibility as a key career strategy, particularly for those graduating from lower-salary regions.

**Data-driven major selection should incorporate both passion and pragmatism.** While following interests remains important, students should understand the financial implications of major selection and plan accordingly for debt management and career transitions.

## Assumptions and Caveats

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

**Assumption 1:** Missing salary values (approximately 15% of records) were imputed using the average salary for the corresponding major and school type combination. This approach maintains data integrity while acknowledging that actual values may vary from computed averages.

**Assumption 2:** Due to incompatible key fields across the three CSV datasets, two files were successfully merged while the third dataset was analyzed separately and integrated visually in the same dashboard. This approach provides comprehensive insights while acknowledging data integration limitations.

**Assumption 3:** Regional classifications follow standard US Census Bureau definitions, though some institutions near regional boundaries may have been categorized based on primary state location rather than actual geographic influence.

**Assumption 4:** Starting salary data represents immediate post-graduation compensation and does not account for variations in cost of living, benefits packages, or regional economic conditions that may affect real purchasing power.

**Assumption 5:** School type classifications (Public vs Private) were validated against institutional data, though some hybrid institutions may not perfectly fit these binary categories.

---

## Technical Implementation Notes

- **Data Cleaning:** Implemented systematic null value handling using statistical imputation methods
- **Data Integration:** Overcame CSV compatibility issues through strategic partial merging and parallel visualization
- **Dashboard Design:** Created comprehensive Tableau dashboard with interactive filtering capabilities
- **Performance Optimization:** Structured analysis to handle 320+ institutional records efficiently

