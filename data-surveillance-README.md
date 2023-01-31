## WNV Surveillance Data

This page provides information on the surveillance data provided to participating teams.
 
## Data Use

In order to receive the data, all teams need to submit a completed [data request form](./data_surveillance/data-use-agreement.pdf) to <vbd-predict@cdc.gov>. On behalf of all team members, the team lead should fill out items 1-3 on page 3 and date and sign page 4 to acknowledge the following limitations of ArboNET data:
 
1. Access to ArboNET data is limited to team members named on the model submission form. The data provided will be treated as confidential and should not be provided to other persons. All other requests for access to ArboNET data should be directed to the CDC Arboviral Diseases Branch (<dvbid2@cdc.gov>). Comments or questions about the challenge should be directed to <vbd-predict@cdc.gov>.
2. The data are provided for the purpose of statistical reporting and analysis only and may not be combined with other data or information for the purpose of matching records to identify individuals. Any information that could be used directly or indirectly to identify individuals will not be disclosed. If the identity of a person included in the data is discovered inadvertently, that information should not be disclosed or otherwise made public.
3. Analysis and reporting will be performed only on the variables and final data provided and should not be combined or compared to provisional data from the current or previous years.
4. Case-specific data cannot be released by any geographic unit smaller than a state.
5. Provisional data, other than that which is already publicly available, cannot be released.
6. The data provided, including any temporary or permanent files created from the ArboNET data, should be stored on a password protected computer. Copies of the data file(s) should not be made, even for back-up purposes. Hard copies of the data will be stored securely and shredded when they are no longer needed.
7. The team is responsible for obtaining Institutional Review Board (IRB) review of projects when appropriate.
8. ArboNET will be appropriately referenced in any publications or presentations that are derived from these data and a draft of the article or presentation will be provided to the CDC Arboviral Diseases Branch for review.
 
 
## Data Dictionary
Data consist of monthly neuroinvasive disease counts reported to ArboNET for the 48 states within the contiguous United States, as well as the District of Columbia, from 2000–2022 (2022 data are provisional as of January 10, 2023). Each line represents all cases for a single state in a single month.  Zeroes indicate a state did not report neuroinvasive cases in the given month. A detailed description of the fields included in the csv file is included below.
 
### `fips`
The two-digit state FIPS code. Please note that the FIPS codes are written as a character string to preserve any leading zeroes.
 
(Examples: 09, 36)
 
### `state`
The name of the state that reported the cases.
 
(Examples: Missouri, New York)
 
### `year`
The year (four-digit) the cases were reported.
 
(Examples: 2002, 2014)
 
### `month`
The month (two-digit) the cases were reported.
 
(Examples: 05, 10)
 
### `count`
Number of WNV neuroinvasive disease cases reported. Zeroes indicate a state did not report neuroinvasive cases in a given month.
 
