# Boston_Crime_Analyis
Capstone Project for Analytics Systems Technology

### Introduction

As a lifelong Boston resident, I wanted to learn more about crimes committed within Boston. Thankfully, the Boston Police Department (BPD) provide incdient reproting data to the city for public use. Records in the new system begin in June of 2015. Additionally, the dataset contains records from the new crime incident report system, which includes a reduced set of fields focused on capturing the type of incident as well as when and where it occurred.  I have collected several datasets from https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system. Although the available data starts in 2015, I will be using data from 2017 - 2021 with a total sample size of n=314597; both 2019 (n=19782 | Sep-Dec) and 2021 (n=23695 | Jan - May) are partial years. Hopefully, the information the authorities have gathered will allow me to take a glimpse at Boston's seedy underbelly.

Total number of observations per dataset:
* 2017, n=101338  
* 2018, n=98888
* 2020, n=70894

Total size: 54.5 MB 

**Business Requirements/Understanding:**

1. What are the top offenses committed in the city?
2. Are certain crimes committed during a specific time period?
3. Does geography play a role in particular crimes being committed?
4. Has crime decreased or increased over time?
    * What types of offenses remain relevant (stats-quo)
    * Newer crimes being committed 
    * Has a specific occurrence of a particular offense decreased over time?
5. Can we determine high-risk areas based on a set of features?

**Overview:**

I plan to utilize the [CRISP-DM](https://www.datascience-pm.com/crisp-dm-2/) process model for this project:
1.    Business understanding – What does the business need?
2.    Data understanding – What data do we have/need? Is it clean?
3.    Data preparation – How do we organize the data for modeling?
4.    Modeling – What modeling techniques should we apply?
5.    Evaluation – Which model best meets the business objectives?
6.    Deployment – How do stakeholders access the results?

![crisp-dm](https://www.kdnuggets.com/wp-content/uploads/crisp-dm-4-problems-fig1.png)
