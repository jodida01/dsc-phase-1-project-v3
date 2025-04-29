# Aircraft Risk Evaluation for Business Expansion

# Overview

This project analyzes aviation accident data from 1962 to 2023 to help a company planning to expand into the aviation sector. By cleaning, analyzing, and visualizing the data, I provide actionable insights for selecting the safest aircraft models for purchase.

# Business Understanding

The company is expanding into new industries and considering purchasing aircraft for commercial and private use. However, they lack information about the risks associated with different aircraft types.

## Stakeholder:

    Head of the new aviation division.

## Key Business Questions:

    Which types of aircraft have the lowest accident rates?

    What are the most common causes of aviation accidents?

    How can the company minimize risk when selecting aircraft for their fleet?

# Data Understanding and Analysis

## Source of Data:

    Kaggle - Aviation Accident Database Synopses

## Description of Data:

    The dataset includes civil aviation accidents and incidents from 1962 to 2023.

    With a total columns in the dataset: 31 and total rows in the dataset: 90348

    It contains fields such as event date, location, aircraft model, flight purpose, accident narrative, injury severity, and probable cause.

## Three Visualizations:

   ### Risk Score Distribution

        A histogram displaying the risk score associated with different aircraft models, helping to identify safer models.
        

   ### Top 10 Riskiest Aircraft Models:

        A bar plot display top 10 most riskiest aircraft models that should be avoided by the business
        Highlights aircraft models contributing most to overall operational risk 

   ### Scatter Plot - Fatal Injuries vs. Total Incidents

        A scatter plot showing fatal injuries visa vie total incidents.

   ###  Heatmap - Correlation Between Injury Types
        High positive correlation between Fatal and Serious Injuries ➔ severe accidents tend to cause both.
        Negative correlation between Fatalities and Uninjured ➔ The more fatalities, the fewer uninjured.
        Minor injuries might have weaker correlation with fatal/serious injuries ➔ Minor accidents are often different in nature.

   ### Barplot - Safest Aircraft Models
        All Aircrafts have zero Risk Score no deaths, no injuries reported despite incidents — great safety record!
        Incident Counts vary while some aircraft had more incidents (8 incidents for Piper PA38 and EMBRAER EMB145) but still no injuries. Others had only 5 incidents (e.g., CESSNA 150C, Maule MX7).
        Larger Aircrafts are inherently safer models like Mcdonnell Douglas DC-10-40 and Douglas DC-8-71 (big commercial jets) show very high "Total Uninjured" numbers (816-965 passengers) — despite incidents, no harm.
        Light Aircrafts also perform well small planes like CESSNA 150C and Maule MX7 also have a perfect record,although with fewer total passengers involved.
        Consistency Across Manufacturers No single manufacturer is dominant — Cessna, Piper, McDonnell Douglas, Beech, Douglas, EMBRAER all appear, showing safety across brands.

# Conclusion

## Summary of Conclusions:

    Aircraft models with fewer accidents such as - 
- **CESSNA 150C**
- **Mcdonnell Douglas DC-10-40**
- **Let L-23**
- **Beech F90**
- **Douglas DC-8-71**
- **Socata TB-9**
- **Douglas DC-9-51**
- **EMBRAER EMB145**
- **Maule MX7**
- **Piper PA38**
   The above aircraft models should be prioritized for purchase to minimize operational risk.

    Pilot error and mechanical failure were identified as the leading causes of aviation accidents, suggesting that investments in pilot training and rigorous maintenance programs are crucial.

    Accident rates have decreased significantly over the past few decades, indicating that newer aircraft models and modern safety regulations have improved aviation safety.

These insights will assist the head of the aviation division in making informed, data-driven decisions about aircraft procurement and safety strategy.

# Final Recommendation
To ensure a strong and secure entry into the aviation industry, we recommend prioritizing the acquisition and leasing of the above models. These aircraft have a demonstrated track record of operational safety, significantly reducing business risk while ensuring reliable performance

# Limitations
- Missing data in key fields like location and aircraft details.
- Lack of information on flight hours and distance flown for better risk assessment.
- Potential biases in data collection and reporting.

# Next Steps
Expand data collection to include additional critical variables such as flight hours, aircraft age, and maintenance history. Enhance feature engineering methodologies to optimize the precision of risk and severity assessments. Incorporate external data sources to validate insights and strengthen analytical robustness

# How to Run the Project
- Clone the repository.
- Ensure the required datasets (AviationData.csv and USState_Codes.csv) are in the Data/ directory.
- Install the required Python libraries by running pip install -r requirements.txt 
- Open the Jupyter Notebook file Phase 1 Project Analysis.ipynb.
- Run the cells sequentially to reproduce the analysis and visualizations.

# Interactive Dashboard
Explore the interactive dashboard here. The dashboard provides insights into accident frequencies grouped by aircraft type, Proportional Fatal Injuries, risk score and safest ircrafts models, allowing users to interact with the data for deeper analysis.

# Contact
For questions or feedback, please contact the project team:
• Email: odidajudah01@gmail.com

• LinkedIn: Jodida's Profile (www.linkedin.com/in/jodida)
