Notes: 3/26/2024

years spreadsheet:

1 row for each milestone for each project.
"Year" column refers to the year in which the project entered that development stage (milestone)


# Capital Cost Escalation and Overrun for Federally-funded Fixed-guideway transit
This is a project of Dr Carole Turley Voulgaris, which has been supported by the
following research assistants over the years (listed alphabetically):

* Charuvi Begwani
* Sue Chen
* Alex Cox
* Michaela Gwiazda
* Zoe Iacovino
* Ryan Johnson
* Mojdeh Mahdavi
* Cam McCutchen
* Arnav Murulidhar
* Tianyu Su
* Megan Willis-Jackson

The purpose of this project is to compile a database of projects that have been
funded by the Federal Transit Administrations Capital Improvement Grants program
(section 5309) and how project budgets and timelines have changes over the the
project planning and project construction periods.

Here is a sentence. Here is another

## Data sources (ranked by priority; up to January 2024)
* Capital Investment Grant (CIG) Dashboard: https://www.transit.dot.gov/funding/grants/grant-programs/capital-investments/capital-investment-grant-cig-dashboard 
* Annual Report on Funding Recommendations: https://www.transit.dot.gov/funding/grant-programs/capital-investments/annual-report-funding-recommendations  
* Before and After Studies of New Starts Projects: https://www.transit.dot.gov/funding/grant-programs/capital-investments/and-after-studies-new-starts-projects 
* Capital Investment Program Project Profiles: https://www.transit.dot.gov/funding/grant-programs/capital-investments/current-capital-investment-grant-cig-projects

## Notes on progress
### TO DO
9. Project completeness: check all projects that appear in four sources are included in our dataset [In Progress - Tianyu]
10. Add sponsor information into "project-data-all" [IN PROGRESS]
11. Check whetehr the information in the data sheets correclt refeects the report [IN PROGRESS]
11. Search for missing reports (1999 report, 2003 Appendices, reports before 1997, project profiles no longer on website) [NOT YET STARTED]
12. Add project statues: open/abandoned/ongoing [NOT YET STARTED]
13. Add AR22, AR23, BA21 [NOT YET STARTED]

### DONE
project-data-all, project-data-srcs-all, year-data-srcs-all
1. Consolidate spreadsheets from all reviewers [DONE]
2. Update Cam portions of spreadsheets [DONE]
3. Standardization changes: correct typos [DONE]
4. Standardization changes: standardizing data input [DONE]

all reports
5. Add "Year" column to "year-data-srcs-all" so that sources can be matched up with the right milestone [DONE]
6. Review "year-data-all" rows with "Milestone" column issues [DONE]
7. Spot check [DONE]
8. Add missing years for AR, PP and BA [DONE]

## Notes on data
- Where there are multiple names for the same project, it's been included as "(aka ...)". 412 is included in AR97 and 98 but never entered Preliminary Engineering.
- Section 5309 funding does not include non-New Starts FFGA Commitment funding. Specifically, it does not include Fixed Guideway Modernization which is included in other federal funding.
- We have captured the estimates when projects enter a milestone, not when estimates change during a milestone.
- For projects approved into preliminary engineering under SAFETEA-LU, when MAP-21 was adopted, some were considered to be in project development and needed to be approved again in order to enter into preliminary engineering.
- Cost estimate ranges are averaged.
- FTA approval of Final Design pending resolution of compliance with the Americans for Disabilities Act is considered to be Final Design.

## Repository directories and files
### background

The material in this folder offers background on the project itself as well as on
the history of the data gathering exercise.

* *Eno.pptx:* These are slides from a presentation Dr Voulgaris gave as part of 
the Project Delivery Symposium hosted by the Eno Center for Transportation in 
October 2021. The focus of the presentation was on the relationship between
cost estimation and ridership forecasting and the differences and similarities
between studying bias in each.
* *Voulgaris dissertation.docx:* This is the full text of Dr Voulgaris's doctoral
dissertation, including all appendices. Chapter 2 includes a history of the
Capital Improvements Grants program and Chapter 7 includes an analysis of both
cost estimate accuracy and ridership forecast accuracy for a set of projects for
which data on cost estimates, ridership forecasts, observed ridership, and final
cost were available at the time (2017).
* *Notes on spreadsheets.docx:* This is a word document that describes some of 
the abbreviations that are used in the current data files, lists the variables
we are gathering, and includes links to some of the data sources.


* *initial-data-2020.xlsx:* This was an initial data assembly attempt by Mojdeh
Mahdavi and Charuvi Begwani in 2020.
* *Source inventory.xlsx:* This is a more complete list of the documents and 
reports we are using as data sources, including urls for where they are available
online.

### project-data

The csv file "project-data-all.csv" should be a compilation of all the data
that is in the other five files.

The "Notes on spreadsheets" word document in the Notes and Background directory
is intended to explain the data in this file.

### project-data-srcs

The csv files in this file include codes to indicate the data sources for each 
piece of data in the project-data folder. Data source abbreviations are explained
in the "Notes on spreadsheets" word document in the Notes and Background directory.

### year-data

The csv file "year-data-all.csv" should be a compilation of all the data
that is in the other five files.

The "Notes on spreadsheets" word document in the Notes and Background directory
is intended to explain the data in this file.

### year-data-srcs

The csv files in this file include codes to indicate the data sources for each 
piece of data in the year-data folder. Data source abbreviations are explained
in the "Notes on spreadsheets" word document in the Notes and Background directory.

## Useful tools
* PDF to Excel: https://www.adobe.com/acrobat/online/pdf-to-excel.html 

## Spot check projects

* 106		South Corridor I-205 / Portland Mall LRT 
* 107		Portland-Milwaukie Light Rail Project
* 108		Columbia River Crossing Project
* 109		Columbia River Crossing Project
* 111		TriMet Interstate MAX Light Rail
* 112		MAX Red Line Extension and Reliability Improvements
* 113		Westside Express Service Rail Project - Wilsonville - Beaverton
* 117		Southwest Corridor Light Rail Transit Project
* 119		West Eugene EmX Extension
* 121		Interstate 71 corridor (MOS-1)
* 122		Cleveland Avenue Bus Rapid Transit (aka Northeast Corridor BRT Project)
* 124		Cleveland Avenue Bus Rapid Transit [This has been deleted and combined with 122.]
* 125		Craig, Alaska (Alaska-Hollis Ketchikan Ferry) [This has been deleted as it does not appear to be within the scope of this project.]
* 128		Alaska Marine Highway System [This has been deleted as it does not appear to be within the scope of this project.]
* 129		Norfolk -Virginia Beach Corridor
* 130		Norfolk LRT - The Tide Light Rail
* 131		West End Transitway
* 134		Central Link Initial Segment (Initial)
* 136		University Link LRT Extension
* 137		Lynnwood Link Extension
* 139		Federal Way Link Extension
* 141		Link Extension and North Link [This has been deleted as it is the same as 143.]
* 142		Airport Link [This has been deleted as it was ultimately included in 134 and the financials are not reported separately.]
* 143		North Link [This has been deleted as North Link was ultimately divided into different projects, including University Link at 136.]
* 144		Everett to Seattle Commuter Rail
* 145		Federal Way Link Extension [This has been deleted as it is the same as 139]
* 152		Lakewood to Tacoma Commuter Rail
* 159		Ashland Avenue BRT Phase I
* 339		Southwest First Coast Flyer BRT
* 513		Southwest Light Rail Transit
