# The Tools for Data Science: Notebooks and Versioning - Assignment
##  1. Problem Understanding

To ensure system preparedness throughout the pandemic, hospitals were asked to identify the number of beds (i.e., non-ICU beds) and related resources that could be made available within 24 hours for use as an ICU bed in case of a surge in COVID patients. 

##  2. Dataset description

This dataset compiles daily counts of patients (both COVID-related and non-COVID-related) in adult and pediatric ICU beds and the number of adult and pediatric ICU beds that are unoccupied.

Data includes:

* date
* number of adults in ICU for COVID-related critical illness (CRCI)
* number of adults in ICU for non-CRCI reasons
* number of adult ICU beds that are unoccupied
* total number of adults in ICU for any reason
* number of patients in pediatric ICU for COVID-related critical illness (CRCI)
* number of patients in pediatric ICU beds for non-CRCI reasons
* number of pediatric ICU beds that are unoccupied
* total number of patients in pediatric ICU beds for any reason

## 3. Exploration and results
**How does the daily utilization rate of adult ICU beds change over time?**

The average daily utilization rate of adult ICU beds at 74% indicates a notable strain on hospital bed supply from March 2020 to April 2024. The rate experienced a gradual but consistent increase leading up to March 2021, with a significant fluctuation noted in May 2021. Subsequently, a substantial decline occurred until August 2021, followed by a gradual increase leading up to April 2024.

**What is the ratio between COVID-related and non-COVID-related adult ICU beds?**

As depicted in the figure, from July 2020 to January 2024, the number of adult ICU beds allocated for non-COVID patients significantly exceeded those designated for COVID patients. Notably, between February 2021 and January 2024, there is a slight impact indicating a gradual rise in the number of non-COVID patients relative to COVID patients.

**What is the trend of COVID-related cases in pediatric ICU?**

There were two peaks observed, approximately in May 2021 and February 2022, reached to 13 and 10 in the overall number of pediatric patients in the Pediatric ICU. Notably, despite these peaks, the overall number of pediatric patients remained relatively low, hovering around 2 during this period.

**How does the overall utilization rate of adult and pediatric ICU beds change?**

In contrast to the relatively stable changes observed in adult ICU bed numbers, pediatric ICU beds exhibited significant fluctuations during this period. Before 2021-07, the utilization rate of  pediatric ICU beds remained around 60%, and lower the that of adult ICU beds, which was around 70%. However, it exceeded after 2021-07 until 2022-01, reached to 80% and significantly droped to 50% on 2022-01. It reached an obvious point of shortage around January 2023.
