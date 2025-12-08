# HR Analytics Dashboard - TechVision Solutions
![POWER BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)  ![STATUS](https://img.shields.io/badge/Status-Complete-4CAF50?style=for-the-badge)

> IBCS-styled HR Insights Dashboard built in Power BI. Features headcount, hiring, turnover, salary trends, demographic analysis, and performance metrics across 2020–2025.

[View Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjk0YjIyMDItNjhjMi00ZTU5LTljZWMtYjk0NzA4NGQ5OTc5IiwidCI6ImJlODMyOWE3LTcyMTgtNDlhMy05YWMxLWQ3Yjk1NDU2M2YzOSIsImMiOjEwfQ%3D%3D) | [Documentation](./Documentation/Documentation_HR_Dashboard.xlsm)

## Table of Contents
1. [Client Background](#client-background)
2. [Executive Summary](#executive-summary)
3. [Dashboard Analysis](#dashboard-analysis)
4. [Key Findings](#key-findings)
5. [Business Recommendations](#business-recommendations)
6. [Methodology](#methodology)
7. [Skills Demonstrated](#skills-demonstrated)
8. [Next Steps](#next-steps)
9. [Lessons Learned](#lessons-learned)

---

## Client Background

**TechVision Solutions** is a rapidly growing technology consulting firm founded in 2019. Starting with just a handful of employees, the company experienced explosive growth following successful Series A and B funding rounds. By 2023, TechVision had expanded to over 800 employees across multiple departments including IT, Sales, Research & Development, Marketing, HR, and Finance.

The company's leadership recognized the need for data-driven HR insights to manage this rapid growth effectively. They commissioned this Power BI dashboard to track workforce metrics, identify trends, and make informed decisions about hiring, retention, and compensation strategies.

---

## Executive Summary

### Questions Answered
- How has workforce size and composition evolved from 2020-2025?
- What are the hiring and termination patterns across years?
- Which departments show the highest growth or turnover?
- How is compensation tracking against workforce growth?
- What demographic trends exist in our workforce?

### Findings at a Glance
- **547% workforce growth** from 2020 to 2023 (126 to 813 employees)
- **2023 marked a pivotal correction year** with 65.5% reduction in hiring
- **Total salary optimization** achieved 24% cost reduction despite larger workforce
- **Termination rate peaked at 14.1%** in 2023, indicating strategic restructuring
- **IT and Sales departments** remain the largest workforce segments

### Business Impact
The analysis revealed that TechVision's hypergrowth phase (2020-2022) was unsustainable, leading to necessary corrections in 2023. The data-driven insights enabled leadership to right-size the organization, optimize compensation costs by $23.85M, and establish more sustainable hiring practices moving forward.

---

## Dashboard Analysis

### Figure 1: 2020 Overview - Foundation Year
![2020 Dashboard](Image-2)

The 2020 dashboard shows TechVision's early stage with 126 employees. Notable metrics include:
- **Hire Rate: 102.4%** - The company essentially doubled its size
- **Total Salary: $98.94M** - High per-capita compensation for a small team
- **Terminations: Only 3** - Exceptional retention rate of 97.6%

### Figure 2: 2021 Overview - Initial Growth
![2021 Dashboard](Image-5)

2021 marked significant expansion:
- **Headcount: 271** (115.1% YoY growth)
- **Hires: 161** - Aggressive talent acquisition
- **Department Distribution**: Marketing grew by 233%, IT by 160%

### Figure 3: 2022 Overview - Scaling Phase
![2022 Dashboard](Image-4)

Continued expansion with more structured growth:
- **Headcount: 452** (66.8% YoY growth)
- **Age Demographics**: Balanced distribution across all age groups
- **Education Levels**: 73% bachelor's degree or higher

### Figure 4: 2023 Overview - Strategic Correction
![2023 Dashboard](Image-1)

The pivotal year showing organizational maturation:
- **Headcount: 813** (slower 2.8% growth)
- **Hires: Only 92** (-65.5% YoY)
- **Terminations: 115** (+101.8% YoY)
- **Salary Optimization**: Reduced to $75.09M despite larger workforce

### Figure 5: 2024 Overview - Stabilization
![2024 Dashboard](Image-3)

Return to controlled growth:
- **Headcount: 836** (33.5% YoY growth)
- **Hires: 267** - Resumed strategic hiring
- **Termination Rate: 6.8%** - Normalized from 2023 peak

---

## Key Findings

Our analysis uncovered critical insights about TechVision's workforce evolution. The company's journey from **startup to scale-up** is clearly reflected in the metrics, with **2020-2022 representing hypergrowth**, where hiring rates exceeded 47% annually. The **2023 correction** was necessary and strategic, reducing hiring by 65.5% while increasing terminations to optimize the workforce. Most importantly, the **salary-per-employee ratio improved** from $785K (2020) to $92K (2023), indicating more efficient resource allocation. The **demographic distribution** shows a healthy mix across age groups and education levels, with **IT and Sales** consistently maintaining 40% of total workforce.

---

## Business Recommendations

Based on our comprehensive analysis, TechVision should **maintain current hiring velocity** at 250-300 annual hires to support sustainable growth without creating future imbalances. The company must **focus retention efforts** on high-performing departments, particularly in IT and R&D where domain expertise is critical. We recommend **implementing predictive analytics** for turnover risk assessment, especially for employees in the 30-40 age bracket showing highest mobility. Additionally, **compensation benchmarking** should be conducted quarterly to ensure competitive positioning while maintaining the improved cost structure achieved in 2023. Finally, **department-specific KPIs** should be established for hiring managers to ensure quality over quantity in talent acquisition.

---

## Methodology

1. **Data Collection**: Imported employee records from HR system (DataTable.csv)
2. **Data Modeling**: Created relationships between employee data and date dimension
3. **DAX Development**: Built 40+ measures for headcount, hiring, termination calculations
4. **Visualization Design**: Developed interactive dashboard with KPI cards and demographic breakdowns
5. **Time Intelligence**: Implemented year-over-year comparisons and trend analysis
6. **Testing**: Validated calculations against source system records

---

## Skills Demonstrated

- **Power BI Development** - Dashboard design and implementation
- **DAX (Data Analysis Expressions)** - Complex measure calculations
- **Data Modeling** - Star schema design
- **Business Intelligence** - KPI identification and tracking
- **Data Visualization** - Clear and actionable visual design
- **HR Analytics** - Workforce metrics and trends analysis

---

## Next Steps

1. **Integrate Predictive Models** - Add machine learning for turnover prediction
2. **Expand Demographics** - Include skills matrix and succession planning metrics
3. **Real-time Data** - Connect to live HR system for daily updates
4. **Mobile Optimization** - Create mobile-responsive version for executives
5. **Benchmark Integration** - Add industry comparison data
6. **Cost Analysis** - Deeper dive into compensation by role and performance

---

## Lessons Learned

Working on this project taught me that numbers tell stories, but context brings them to life. Initially, I was overwhelmed by the sheer volume of metrics we could track, but I learned that effective analytics isn't about showing everything possible - it's about highlighting what matters most. The 2023 data was particularly eye-opening; what first appeared as negative trends (reduced hiring, increased terminations) actually represented strategic decisions that improved the company's health. I also discovered that color coding and visual cues are incredibly powerful for quick comprehension - those red and green indicators made year-over-year comparisons instantly understandable for executives who only had minutes to review the dashboard.

---

## Contact
For questions or collaboration opportunities, please reach out via GitHub issues.

**Dashboard Created By**: [Your Name]  
**Date**: December 2025  
**Tools**: Power BI, DAX, Excel
