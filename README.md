# San Francisco Police Department Incident Reports Data Analysis:
### Marijuana crimes 2003 through 2020

### The Project
This data analysis project investigates how marijuana law enforcement has changed in San Francisco between 2003 and 2020, drawing from two different databases of San Francisco Police Department (SFPD) incident reports. Those databases include:

1. SF police incident reports [2018 to present](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783).
2. SF police incident reports: [2003 to May 2018](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry).

The data used in this project was downloaded on Oct 14, 2021. Since the source data is regularly updated, you can download the data used in this analysis [here](https://drive.google.com/drive/folders/1RBFfl-G6BCBR9ZA79K6jrbFeBXJqpHJl?usp=sharing).

This data analysis seeks to answer the following questions: 

- How many marijuana-involved incidents did the SFPD report each year over time?
- Which types of marijuana incidents did SFPD report each year? Comparing the types of incidents over time.
- How many marijuana-involved incidents did SFPD report in the different police districts across the city?

The core of this data analysis is contained within four Python notebooks saved in this repo. They are labeled in the numerical order in which they should be run. (Begin with 01, then 02, etc.) Please ignore any Python notebooks that are not labeled with a number, they are 'scratch' notebooks that do not contain clear documentation. 

Additional notes about the data:
- In 2018, the SFPD released a new dataset of police incidents. You can read more about how the transitioned from their old dataset to the new database [here](https://drive.google.com/file/d/13n7pncEOxFTWig9-sTKnB2sRiTB54Kb-/view?usp=sharing).
- There is a lengthy data dictionary for this police incident database which is available [here](https://datasf.gitbook.io/datasf-dataset-explainers/sfpd-incident-report-2018-to-present).
- The SFPD documentation tells us that reports in this data are filed by officers or self-reported by members of the public using SFPD's online reporting system.
- The SFPD docomentation tells us that data has been added to this set once incident reports have been reviewed and approved by a supervising Sergeant or Lieutenant. Incident reports may be removed from the dataset if in compliance with court orders to seal records or for administrative purposes such as active internal affair investigations and/or criminal investigations.

*This project was reported and developed in fall 2021 by Noah Baustin for the J233: Coding for Journalists course at the UC Berkeley Graduate School of Journalism, taught by Soo Oh.*
