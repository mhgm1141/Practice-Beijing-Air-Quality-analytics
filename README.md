# Practice-Beijing-Air-Quality-analytics
Interactive Power BI dashboard for Beijing air quality analysis. Includes advanced DAX measures and ETL processes for environmental data insights.
----------------------------------------------------------------------------------------------------------------------------------------------------------

Overview

This project presents an interactive analysis of air quality in Beijing, utilizing a dataset from a specialized Udemy course. The dashboard explores the relationship between climate variables (temperature, humidity) and chemical pollutants (NO2, CO, Sulphur), providing a clear view of environmental trends over a year-long period.

----------------------------------------------------------------------------------------------------------------------------------------------------------

Key Questions Answered

  Pollution Trends: How do NO2 and CO levels fluctuate on an hourly basis?
  Extreme Conditions: What were the exact dates and times for the highest temperature and humidity levels?
  Air Composition: What is the average distribution of rare compounds and hourly air contents?

Data Engineering (ETL Process)

A rigorous data cleaning process was performed using Power Query to ensure the integrity of the analysis:

  Data Cleaning: Removed null values and handled empty records to prevent skewing averages.
  Data Typing: Validated and corrected data types for dates, times, and numerical pollutants.
  Feature Selection: Conducted a utility audit of columns, removing irrelevant data to optimize model performance.

Advanced DAX Measures

To identify specific environmental milestones, I developed custom DAX measures that filter the dataset based on maximum values
