# Introduction
With rising crime rates globally, law enforcement agencies face increasingly complex challenges in maintaining public safety. Traditional policing methods, while still essential, often fall short in responding swiftly to dynamic and evolving criminal activities. This case study explores how leveraging advanced technologies and crime data analysis can revolutionize law enforcement efforts in a major city, optimizing crime prevention, response, and resource allocation. This futher highlights the critical role that data analysis can play in modern policing and provides a framework for other cities looking to enhance their law enforcement efforts in the face of rising crime rates.







# Problem Statement
In recent years, the surge in crime rates has posed significant challenges for law enforcement agencies. Traditional policing methods struggle to keep pace with the evolving nature of criminal activities, leading to inefficiencies in crime prevention, resource allocation, and response times. The lack of real-time data-driven insights further complicates decision-making processes, hindering law enforcement’s ability to proactively address potential threats. The successful completion of this project will equip the police department to make more informed decisions, significantly enhancing crime prevention and law enforcement efficiency. This shift not only modernizes traditional policing methods but also highlights the importance of a proactive, data-driven strategy in tackling the evolving challenges of urban crime.
# Data sourcing
- [Location Dataset](https://docs.google.com/spreadsheets/d/1R1Vs6hZuWCk7KHzaHeaizCHDH-ob39IRCSRFo6bskIk/edit?usp=sharing)
- [Crime Dataset](https://docs.google.com/spreadsheets/d/1WQ-oucMeizVOPiLD9WlyFAnBejeHyGsFHIZjs0cawLU/edit?usp=sharing)
- [Data Dictionary](https://docs.google.com/document/d/1931IJpxFdsm9XS15EMpSNrRXQzbcnbl2MDq0p1cQULc/edit?usp=sharing)

# Data transformation and cleaning
The dataset underwent comprehensive cleaning, which included the removal of duplicates, the creation of additional columns by extracting relevant data, the correction of inconsistencies, and the formatting of the data to ensure it was suitable for both analysis and visualization.

-Data Before cleaning



![Before Cleaning](https://github.com/user-attachments/assets/9688d3c6-f074-44ea-b644-f1961837aeb1)



-Data After cleaning



![After Cleaning](https://github.com/user-attachments/assets/1a225b77-f963-4167-bd45-9d9b7e7a5ad4)



# Data modeling
Key dimensions for breaking down the analysis were identified, leading to the creation of new tables corresponding to each dimension. These include the following tables:
- Location Dimennsion
- Date Dimension
- Offense Dimension
- Crimefact Table
-  Metrix Table
  The data model was structured using a Star Schema, where multiple dimension tables were linked to the central Fact table through one-to-many relationships.


![Data Model](https://github.com/user-attachments/assets/cfc6bfa3-3719-49b8-a79c-4e843085ba87)


# Visualization

![Screenshot 2025-02-04 134932](https://github.com/user-attachments/assets/b854add7-40ba-48c3-972b-f3fe12f85d31)


This visualization is a comprehensive crime analysis dashboard, highlighting key crime trends and statistics over time, categorized by various factors. Here are the main takeaways:

- Trends Over Time:

Total crime has generally increased from 2012/13 to 2022/23, peaking in recent years, with some fluctuations.
Quarterly trends show consistency across financial years, with noticeable dips in some years (e.g., 2020/21, potentially due to external factors like the pandemic).

- Total Crime:

Total crime recorded is 60 million.
Average crime per year is 230 incidents, with a year-on-year growth rate of 2.9%.

- Crime by CSP Name:

Harrogate has the highest crime rate among Community Safety Partnerships (CSPs), significantly ahead of others like South Devon and Basildon.

- Crime by Region:

The South East region leads in total crime, followed by Yorkshire and the Eastern region.
Crime by Offence Group:

Theft and violence are the most prevalent offence groups, followed by fraud and criminal damage.
Crime by Offence Subgroup:

"Violence with injury" and "Criminal damage and arson" are dominant subcategories, indicating areas requiring targeted intervention.
The dashboard provides actionable insights for stakeholders to identify hotspots and prioritize resources for reducing specific types of crimes.

  
