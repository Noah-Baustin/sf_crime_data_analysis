# SF Crime Data Analysis
Repo for my Coding for Journalists final project.

#### Datasets I’m using:
1. SF police incident reports [2018 to present](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783).
2. SF police incident reports: [2003 to May 2018](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry).

#### Possible analysis:
Analyzing how marijuana law enforcement has changed over time in San Francisco. Could include changes over time in:
- The number of marijuana-involved incidents each year over time.
- Which marijuana crimes were charged each year, comparing over time.
- The locations in the city where crimes were charged.
- The results of marijuana-involved incidents. (arrests, etc.)

##### Additional possibilities:
- Compare marijuana arrests to other types of crimes, like narcotics.

##### Analysis that’s not feasible after looking at the data:
- The number of felony vs. misdemeanor marijuana charges over time.

#### Interviews:
*You can read the rough notes from the interviews I've conducted in [this Google doc](https://docs.google.com/document/d/1-BAcVMG_gv_RyiF2uTdD1RFpmQl7z-1Jg9s_pL1wIBI/edit).*

## Details about the datasets I'm using

#### 2018 to Present data:
*Downloaded this data Oct 14, 2021 for analysis.*

Details about the data:
*There is a full writeup about this data [here](https://datasf.gitbook.io/datasf-dataset-explainers/sfpd-incident-report-2018-to-present).*
- Includes incident reports that have been filed as of Jan 1, 2018.
- This dataset can be used to provide counts of incident reports, by type, date, time and location. This information can be used to help understand the number, location, and nature, of incidents of crime that are reported to or reported by the SFPD.
- This is NOT the 'official' count of crime. While incident reports may serve as the basis for official crime statistics, official crime statistics are governed by the FBI’s UCR and NIBRS program." 
- This dataset does NOT include all data surrounding policing. Data that is not included:
	- Citations. 
	- Identifiable information about specific people involved in incidents. 
	- The actions of other law enforcement agencies besides the SFPD.
	- Records involving juveniles.
		-Including the crime: encrouaging a minor to use marijuana.
	- Records coded as 'confidential.'
		- Incidents may be removed from dataset because of court orders to seal records, or for ongoing investigations. 
	- Precise addresses. Locations are shown at the intersection level only.
- Reports are filed by officers or self-reported by members of the public using SFPD's online reporting system.
- Report categories:
    - Initial Reports: the first report filed for an incident.
    - Supplemental Reports: a follow up report to an initial, Coplogic or vehicle report.
    - Coplogic Reports: incident reports filed by members of the public using SFPD’s online reporting system
    - Vehicle Reports: any incident reports related to stolen and/or recovered vehicles
- Data is added to open data once incident reports have been reviewed and approved by a supervising Sergeant or Lieutenant. Incident reports may be removed from the dataset if in compliance with court orders to seal records or for administrative purposes such as active internal affair investigations and/or criminal investigations.
- Once a supervising officer has provided approval via electronic signature, no further changes can be made to the initial report. If changes or additional information is required or discovered during an investigation, a supplemental report may be generated to capture updates.
	- For example, a supplemental report may be issued to show an arrest was made, a missing person was found, or to provide additional details of property taken in a theft. To differentiate between the initial and supplemental reports, a filter can be applied to the “Report Type Description” field. Failing to filter between the initial and supplemental report can lead to double counting of incidents.
- Incident reports can have one or more associated Incident Codes. For example, an officer may have a warrant for an arrest and while making the arrest, discovers narcotics in the individual’s possession. The officer would record two Incident Codes: (1) for the warrant and (2) for the discovery of narcotics. When multiple Incident Codes exist, the Incident ID, Incident Number and CAD Numbers remain the same and the Row ID field can be used as a unique identifier for each row of data.
- Data is updated daily by 10:00 PT.


#### 2003 to May 2018 data:
*Downloaded 10/14/2021 for analysis.*
- This data is different than the 2018 to present dataset. It contains 13 less fields. For more information, see file *Dataset_Change_Notice_Police_Incidents_2018_04_16.pdf*. Saved in the data folder.
	- - Note: the present dataset begins on Jan 2018. So beware of that overlap with analysis. 
- Last updated March 25, 2021.
- Data provided by: City and County of San Francisco.
	- Publishing department: Police Department.
	- Publishing frequecy: not updated (historical only)
- See webpage for column types and some definitions. 

### Potential Pitfalls to Beware Of:
- Be very careful about which comparisons I'm making between the historical data and the 2018 to present data as the data collection system is different.
- Multiple reports may be filed in the present day data for a single incident. There may be both an initial report and a supplemental report for the same incident.
- Incident reports can have one or more associated Incident Codes. For example, an officer may have a warrant for an arrest and while making the arrest, discovers narcotics in the individual’s possession. The officer would record two Incident Codes: (1) for the warrant and (2) for the discovery of narcotics. When multiple Incident Codes exist, the Incident ID, Incident Number and CAD Numbers remain the same and the Row ID field can be used as a unique identifier for each row of data.


