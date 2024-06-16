# Phase-1-aviation-project-2024-ES

## Business Problem
Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.

# Aircraft Safety Analysis
## Identifying Low-Risk Aircrafts for Commercial and Private Enterprise Operations

## Overview
The scope of this project is to determine the most secure models of aircraft that can be used by the new division of the company: aviation. By estimation and analysis of past incidents data, the main purpose of this analysis is to do a recommendation on what actionable insights will help guide the company in making informed decisions in regard to both private and commercial purchase and operations.

## Business Understanding
This company is venturing into the airline business through diversification. It is targeting the least risky commercial aircraft models, and this analysis is required to  determine how to sustain passenger and crew safety, reduce operational risks, and cut down incident costs. The stakeholders will be head of the new aviation division, a group of safety officers, and decision supports in finance. 

This analysis will ensure the following interests of stakeholders:

**Safety Assurance**: To sustain the reputation and operational success of our company, it is essential to put passengers and crew safety first, thus prioritizing the acquisition of low-risk aircraft.

**Cost Efficiency**: Fewer incidents lead to fewer accidents, decreasing costs associated with vehicle repairs, legal liabilities and insurance premiums.

**Operational Reliability**: By choosing aircraft models of a high reliability, the machine downtime is reduced whilst the airplane service image is improved, what results in superior customer satisfaction and loyalty.

**Informed Strategic Investments**: By using proper risk analysis to make well-informed decisions, resources could be strategically directed to the acquisition of aircraft whose safety and performance metrics are second to none.


**Business critical questions**

1. Which commercial aircraft model has the least probability for an injury occurrence?
2. What phases of flight entail the highest injury risks?
3. How can we use historical data to make informed decisions on aircraft purchases?

## Data Understanding and Analysis
### Source of Data
The data for this analysis was sourced from the National Transportation Safety Board (NTSB).It has a database containing extensive records of aviation incidents that occur in the United States. This detailed dataset offers insights into the specifics of each incident, the aircraft involved, and the resulting outcomes. It is continuously updated and reviewed by aviation safety professionals. [Aviation Accident Database & Synopses](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)

-Data Cleaning: Removal of duplicate records, correction of inconsistencies, and handling of missing values.

-Variable Selection: The major variables of interest to the study were selected, such as Incident Year, Aircraft Make and Model, Broad Phase of Flight, Injury Severity, and Total Injuries, narrowing down the analysis for pertinent aircraft safety aspects.

The aggregated data set was prepared for analyzing trends presented in aircraft safety.

### Data Description
There are very many variables that were obtained from the dataset but there were a few chosen that would be key in this analysis.
The key variables include:
- **Incident Year**: The year the incident occurred.
- **Aircraft Make**: The manufacturer and specific make of the aircraft involved.
- **Broad Phase of Flight**: The phase of flight during which the incident happened (e.g., takeoff, cruise, landing).
- **Injury Severity**: Classification of injuries (e.g., uninjured, minor, serious, fatal).
- **Total Injuries**: The total number of injuries reported in each incident.

### Three Visualizations
1. **Total Injuries per Year** [Analysis Chart](https://github.com/ElsieSerem/phase-1-aviation-project-2024-ES/blob/main/images/Total%20Injuries%20per%20year.png)

   Data from multiple years was collected and summed up the total the number of injuries for each year.
   A line graph was utilized to show the trends of total injuries over the years.

   **Key findings:** The visualization shows fluctuations in total injuries over the years, highlighting years with significant spikes.
   The fluctuations were potentially caused by periods of increased risk, potentially correlating with industry changes, regulatory updates, or other external factors. 
   

2. **Total Injuries by Broad Phase of Flight** [Analysis Chart](https://github.com/ElsieSerem/phase-1-aviation-project-2024-ES/blob/main/images/Total%20Injuries%20in%20relation%20to%20Broad%20Phase%20of%20Flight.png)
   
   Grouped incident data by the broad phase of flight (e.g., takeoff, cruise, landing).
   This was portrayed by a bar chart representing the number of injuries in each flight phase. 

   **Key findings:** The phase with the highest number of injuries  that was identified was the  landing  phase which leaves a distinctive large gap from the cruising phase which has the second highest number of injuries.


3. **Airplane Make with Highest Number of Uninjured and Total Injuries** [Analysis Chart](https://github.com/ElsieSerem/phase-1-aviation-project-2024-ES/blob/main/images/Airplane%20Make%20with%20Highest%20Number%20of%20Total%20Uninjured%20%20and%20Total%20Injuries.png)

   
   This data was used to identify the airplane makes with the highest number of uninjured individuals.
   A dual-axis bar chart showing the number of uninjured and total injuries for top airplane makes was created to portray this information.

   **Key Findings:** It is important to ascertain  which airplane models to consider for purchase which means we choose the airplane  make with the highest number of uninjured  and low  total injuries from the incident.
   
An Aircraft Safety Analysis Dashboard was also created for further analysis. This somewhat general tool was meant to enable a great deal of insight Visualization into the historical aviation incident data for insights on aviation incidents easily. Like this interactive dashboard would enable stakeholders to explore trends, identify most unsafe parts of the flight, and compare how various aircraft models are rated in terms of their safety features. [Interactive Dasboard](https://public.tableau.com/app/profile/elsie.serem/viz/AviationAnalysis_17185612532730/Dashboard1)


## Conclusion
Through our analysis, we have come up with the following recommendations:
1. **Prioritize Safety**: Aircraft models with consistently low injury rates should be prioritized for purchase. Historical data shows that certain models have a strong safety record, minimizing operational risks.

2. **Enhance Training**: Flight phases such as takeoff and landing are associated with higher injury rates. Developing targeted training programs for these phases can significantly improve overall flight safety.

3. **Continuous Monitoring**: Implementing a continuous monitoring system to track safety metrics and adapt to evolving industry standards is crucial. This approach ensures that safety measures remain up-to-date and effective in mitigating risks.

By addressing these areas, our company can make informed decisions to ensure the highest standards of safety in our new aviation operations.
It is particularly important to note that there has been a significant drop in aircraft incidents, and by relation total number of injuries in the last 5 years. This shows that, aviation is indeed a lucrative business venture that can generate profits for the company as long as the company takes appropriate measures to ensure the overall saftety of all stake holders involved.
