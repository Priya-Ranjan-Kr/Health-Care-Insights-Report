# Health Care Insights Project

## Table of Contents
- [Overview](#overview)
- [Key Findings](#key-findings)
  - [Admissions by Gender](#admissions-by-gender)
  - [Patient Blood Type Composition](#patient-blood-type-composition)
  - [Mortality Rate by Department and Gender](#mortality-rate-by-department-and-gender)
  - [Admission vs Billing Amount](#admission-vs-billing-amount)
  - [Medication Usage by Medical Condition](#medication-usage-by-medical-condition)
  - [Billing Amount vs Target Value](#billing-amount-vs-target-value)
  - [Admission Types Distribution](#admission-types-distribution)
  - [Top Hospitals and Doctors by Billing Amount](#top-hospitals-and-doctors-by-billing-amount)
  - [Age vs Billing Amount](#age-vs-billing-amount)
- [Data Sources](#data-sources)
- [Analysis Methods](#analysis-methods)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- 

---

## Overview

The **Health Care Insights Project** is a comprehensive analysis of healthcare data collected over a five-year period from **May 8, 2019, to May 7, 2024**. The primary objective of this project is to uncover critical insights into patient demographics, medical conditions, treatment outcomes, hospital performance, and financial metrics. Utilizing **Power BI** for data visualization and analysis, this project aims to assist healthcare providers and stakeholders in making data-driven decisions to improve patient care, optimize operational efficiency, and enhance financial performance.

---

## Key Findings

### Admissions by Gender

- **Summary**: The distribution of hospital admissions between male and female patients is nearly equal, indicating balanced access to healthcare services across genders.

- **Statistics**:
  - **Male Patients**: 27,770 admissions (50.02%)
  - **Female Patients**: 27,730 admissions (49.98%)

- **Insights**:
  - The slight difference suggests equitable healthcare utilization among genders.
  - Tailored health programs can be developed without significant gender bias.
  
- **Visualization**:
  - A bar chart illustrating nearly identical heights for both male and female admissions, emphasizing the minimal difference.

### Patient Blood Type Composition

- **Summary**: The distribution of blood types among patients is relatively uniform, with a slight prevalence of certain blood groups.

- **Statistics**:
  - **A-**: 6,970 patients (12.56%)
  - **A+**: 6,960 patients (12.53%)
  - **AB+**: 6,950 patients (12.52%)
  - **AB-**: 6,950 patients (12.51%)
  - **B+**: 6,950 patients (12.51%)
  - **B-**: 6,940 patients (12.51%)
  - **O+**: 6,920 patients (12.46%)
  - **O-**: 6,880 patients (12.39%)

- **Insights**:
  - The slight variations indicate a diverse patient population.
  - Resource planning for blood transfusions and related services should account for this diversity.
  
- **Visualization**:
  - A pie chart or bar graph showing proportional representation of each blood type.

### Mortality Rate by Department and Gender

- **Summary**: The **Pulmonology/Respiratory Medicine** department exhibits the highest mortality rates among both male and female patients.

- **Statistics**:
  - **Pulmonology/Respiratory Medicine**:
    - **Female Mortality Rate**: 16.06%
    - **Male Mortality Rate**: 15.74%
  - Other departments show mortality rates ranging between 13.73% and 15.60%.

- **Insights**:
  - High mortality rates in Pulmonology indicate a need for improved treatment protocols and resource allocation.
  - Slightly higher female mortality in some departments suggests possible gender-specific health challenges.
  - Minimal gender differences in mortality rates in departments like Cardiology/Internal Medicine indicate consistent care quality.

- **Visualization**:
  - A clustered bar chart comparing mortality rates across departments segmented by gender.

### Admission vs Billing Amount

- **Summary**: The year **2019** recorded the highest number of admissions and billing amounts, with noticeable fluctuations in subsequent years.

- **Statistics**:
  - **2019**:
    - **Admissions**: 1,013
    - **Billing Amount**: $25.3 million
  - **2020-2024**:
    - Admissions range between 213 and 1,014 per year.
    - Billing amounts fluctuate between $19.2 million and $26.3 million.

- **Insights**:
  - The peak in 2019 may be attributed to specific health events or improved healthcare accessibility.
  - The drop in admissions and billing in 2024 could indicate data collection anomalies or external factors affecting healthcare demand.
  - Understanding these trends can help in forecasting and budgeting for future healthcare services.

- **Visualization**:
  - A line or area chart displaying admissions and billing amounts over time for trend analysis.

### Medication Usage by Medical Condition

- **Summary**: Medication prescriptions are evenly distributed across various medical conditions, suggesting comprehensive treatment approaches.

- **Statistics**:
  - For medications like **Lipitor**, **Ibuprofen**, **Aspirin**, **Paracetamol**, and **Penicillin**, usage across conditions such as **Cancer**, **Diabetes**, **Hypertension**, **Obesity**, **Arthritis**, and **Asthma** ranges between 1.70K and 1.92K prescriptions.

- **Insights**:
  - The balanced distribution implies standard treatment protocols for common conditions.
  - Monitoring these patterns assists in inventory management and identifying over or under-prescription trends.

- **Visualization**:
  - A heatmap or matrix chart showing the correlation between medications and medical conditions.

### Billing Amount vs Target Value

- **Summary**: The total billing amount is closely approaching the set target, indicating strong financial performance.

- **Statistics**:
  - **Target Billing Amount**: $1.50 billion
  - **Actual Billing Amount**: $1.42 billion
  - **Achievement**: 94.67% of the target

- **Insights**:
  - The near attainment of the billing target reflects effective revenue generation and financial management.
  - Strategies can be implemented to bridge the remaining 5.33% gap, such as optimizing services and improving patient throughput.

- **Visualization**:
  - A progress bar or gauge chart illustrating the proportion of the target achieved.

### Admission Types Distribution

- **Summary**: Admissions are almost evenly split among **Elective**, **Urgent**, and **Emergency** types, demonstrating the hospital's capacity to handle diverse medical needs.

- **Statistics**:
  - **Elective Admissions**: 18.66K (33.61%)
  - **Urgent Admissions**: 18.58K (33.47%)
  - **Emergency Admissions**: 18.27K (32.92%)

- **Insights**:
  - Balanced admission types suggest efficient scheduling and resource allocation.
  - Continuous monitoring ensures readiness for sudden increases in urgent or emergency cases.

- **Visualization**:
  - A pie chart or stacked bar chart showing the proportion of each admission type.

### Top Hospitals and Doctors by Billing Amount

- **Hospitals**:
  - **Top Performing Hospital**: *Johnson PLC*
    - **Highest Billing Amount**: Over $0.6 million for satisfaction score 3.
  - **Insights**:
    - Consistent billing amounts across top hospitals indicate competitive performance.
    - Correlating billing with satisfaction scores helps identify areas for service improvement.

- **Doctors**:
  - **Top Performing Doctor**: *Dr. Michael Smith*
    - **Billing Amount**: $784.50K
  - **Insights**:
    - High billing amounts may reflect extensive patient loads or specialization in high-cost treatments.
    - Recognizing top performers can guide resource distribution and reward systems.

- **Visualization**:
  - Bar charts ranking hospitals and doctors by billing amounts alongside satisfaction scores.

### Age vs Billing Amount

- **Summary**: Billing amounts vary across different age groups, with the highest amounts observed in middle-aged patients.

- **Statistics**:
  - **Peak Billing Amount**: $24 million around the age of 38.
  - **General Trend**: Increase in billing from younger ages peaking in middle age and slightly decreasing in older age groups.

- **Insights**:
  - Middle-aged patients may require more complex or costly treatments, contributing to higher billing.
  - Tailored health interventions can be designed for high-cost age groups to manage expenses and improve outcomes.

- **Visualization**:
  - A scatter plot or line chart depicting the relationship between patient age and billing amounts, differentiated by gender.

---

## Data Sources

The analysis is based on comprehensive datasets collected over a five-year period, encompassing various aspects of healthcare services:

- **Patient Demographics**:
  - Age, gender, blood type, and medical conditions.
- **Admission Records**:
  - Dates, types (elective, urgent, emergency), and departmental allocations.
- **Billing Information**:
  - Individual billing amounts, cumulative totals, and comparisons against targets.
- **Medical Treatments**:
  - Medications prescribed, treatment durations, and outcomes.
- **Hospital Performance**:
  - Metrics across different hospitals and departments, including satisfaction scores and mortality rates.
- **Healthcare Providers**:
  - Data on doctors’ performance, patient loads, and billing contributions.
- **Insurance Details**:
  - Coverage types, providers, and their impact on billing and patient care.
- **Test Results**:
  - Diagnostic outcomes categorized as normal, abnormal, and inconclusive.

**Data Quality and Integrity**:
- The data underwent thorough cleaning and validation processes to ensure accuracy and reliability.
- Missing or anomalous data points were identified and appropriately addressed through imputation or exclusion methods.
  
---

## Analysis Methods

The project leveraged various analytical techniques and tools to derive meaningful insights:

- **Data Processing**:
  - Utilized **Power Query** for data extraction, transformation, and loading (ETL).
  - Implemented data normalization and aggregation for consistent analysis.
- **Statistical Analysis**:
  - Descriptive statistics to summarize data distributions and central tendencies.
  - Inferential statistics to identify significant differences and correlations.
- **Visualization Techniques**:
  - Created interactive dashboards in **Power BI** for dynamic data exploration.
  - Employed various chart types (bar, line, scatter, pie, heatmaps, and decomposition trees) to represent data effectively.
- **Trend Analysis**:
  - Conducted time-series analyses to observe patterns over the five-year period.
  - Identified seasonal trends and anomalies in admissions and billing.
- **Comparative Analysis**:
  - Compared performance metrics across different departments, hospitals, and demographic groups.
  - Assessed the impact of various factors (e.g., age, gender, medical conditions) on healthcare outcomes and costs.
- **Performance Metrics**:
  - Calculated Key Performance Indicators (KPIs) such as:
    - **Average Length of Stay**: 15.51 days
    - **Patient-Doctor Ratio**: 1.38
    - **Average Satisfaction Score**: 3.0/5
    - **Year-over-Year Admission Growth**: 7.46%

**Tools Used**:
- **Power BI Desktop**: For data visualization and dashboard creation.
- **Excel**: For initial data manipulation and preliminary analysis.
- **DAX (Data Analysis Expressions)**: For advanced calculations and data modeling within Power BI.
  
---

## Visualizations

The project features a variety of visualizations to convey insights effectively:

1. **Admissions by Gender**:
   - *Type*: Bar Chart
   - *Description*: Compares the number of admissions between male and female patients, showcasing near parity.

2. **Patient Blood Type Composition**:
   - *Type*: Pie Chart
   - *Description*: Displays the proportion of each blood type within the patient population, aiding in medical resource planning.

3. **Mortality Rate by Department and Gender**:
   - *Type*: Clustered Bar Chart
   - *Description*: Highlights mortality rates across departments segmented by gender, identifying high-risk areas.

4. **Admission vs Billing Amount Over Time**:
   - *Type*: Dual-Axis Line Chart
   - *Description*: Shows the relationship and trends between admissions and billing amounts across years, indicating financial and operational performance.

5. **Medication Usage by Medical Condition**:
   - *Type*: Heatmap
   - *Description*: Illustrates the frequency of specific medications prescribed for various conditions, revealing treatment patterns.

6. **Billing Amount vs Target Achievement**:
   - *Type*: Gauge Chart
   - *Description*: Depicts progress towards billing targets, indicating financial health.

7. **Admission Types Distribution**:
   - *Type*: Stacked Bar Chart
   - *Description*: Breaks down admissions into elective, urgent, and emergency categories, showing operational diversity.

8. **Top Hospitals by Billing and Satisfaction**:
   - *Type*: Combined Bar and Line Chart
   - *Description*: Ranks hospitals based on billing amounts and overlays satisfaction scores, balancing financial and service quality metrics.

9. **Top Doctors by Billing Amount**:
   - *Type*: Horizontal Bar Chart
   - *Description*: Lists leading doctors according to billing amounts, useful for performance recognition and resource allocation.

10. **Age vs Billing Amount Scatter Plot**:
    - *Type*: Scatter Plot
    - *Description*: Plots patient ages against billing amounts, identifying age groups with higher healthcare costs.

**Interactive Dashboards**:
- The visualizations are integrated into interactive dashboards allowing users to filter and drill down into specific data segments for detailed analysis.

**Design Considerations**:
- **Clarity**: Chose appropriate chart types to present data intuitively.
- **Consistency**: Maintained uniform color schemes and formatting across visualizations.
- **Interactivity**: Enabled features like tooltips and slicers for enhanced user engagement.
- **Accessibility**: Ensured visualizations are easily interpretable with clear labels and legends.

---

## Conclusion

The **Health Care Insights Project** provides a comprehensive analysis of critical healthcare metrics over a substantial period. Key takeaways include:

- **Balanced Patient Demographics**: Equal access and utilization of healthcare services across genders and diverse blood types.
- **Departmental Performance**: Identification of high-risk departments like Pulmonology necessitates targeted improvements.
- **Financial Health**: Strong billing performance approaching set targets indicates effective financial management, though continuous monitoring is essential.
- **Resource Allocation**: Insights into medication usage and admission types support optimized resource distribution and scheduling.
- **Healthcare Outcomes**: Data-driven understanding of mortality rates and satisfaction scores guides quality enhancement initiatives.

**Impact**:
- The findings equip healthcare administrators and policymakers with actionable insights to improve patient care, streamline operations, and ensure financial sustainability.
- The project demonstrates the power of data analytics and visualization in transforming raw data into strategic knowledge.

---


*For any questions or contributions, please contact [Priya Ranjan ](mailto: priyaranjankumar238@gmail.com).*

