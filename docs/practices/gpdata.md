# General Practice Data

## GP Profile
The GP profile is a minimum data set about each of the practices your PHN supports. 
When practices login to their GP Data report, they will be requested to confirm that details held in the PHN Exchange about their practise are correct. The following profile field will appear for each practice as they log into their GP Data report.
![GP profile form](/img/gp-profile.png)
This information should be regarded as the one source of truth, and it is this information that should be transcribed into your PHN’s client relationship management system. A customised verserion of Dynamics 365 customer relationship management systems is recommended to be used in conjunction with teh PHN Exchange.

## GP Data report
The capability of automated reporting at an incidence level is unique to GP Data Report and can interface with any of the multiple software programs currently used in the primary care sector. 
The GP Data Report is tailored for each practice and displays practice trends and regional and catchment-wide comparisons, so GPs can make informed decisions about their patients, workforce and practice. 
The graphical data monitors areas such as demographics, disease prevalence, immunisation status, cancer screening rates and activities of patients with chronic disease. This allows practices to identify gaps, improve detection rates, use early interventions and achieve better outcomes.  
Reports also include patient indicators across focus areas including cardiovascular disease, respiratory disorders and diabetes. 
The dashboard reports display constant 15-month trends and are updated monthly.  
This automated process saves a practice significant time in producing reports and can also be used as evidence of data monitoring and quality improvement activities for accreditation.

### Benchmarking
A unique feature of the GP data report is its ability to benchmark shared data. Each practice views their own data and  average calculated from all data sharing practices. This enable the practice to assess their performance against their peers. Of course, all practice specific data is only viewable by the practice sharing its. Please review the PIP QI measures video linked in the above section to review the benchmarking line. PHN Exchange is developing benchmarking across data extraction software.

### Validating
GP Engagement Validating the GP data report 2 min 11 secs [CLICK HERE](https://youtu.be/eWFtcGspuEY)

## GP Data Source
Configuration for the GP data extraction is found within the admin page. It shows the individual connection details between the PHN Exchange and your PHNs GP data source (the data base of extracted DE identified GP data held by and under the custodianship of your PHN). Only designated people within the PHN should modify of edit this section

*Note that the PHN Exchange does not use individual lines of data but rather aggregates numbers within the PHNs data base and send the aggregates back to the PHN exchange for visualisations to the GP practice. An example would be for number of patients in a practice.*

The PHN Exchange sends a data base query to the PHN’s GP data and calculates the number of patients for a practice. This number is sent back to the PHN Exchange. When a practice logs into their GP data report, the number is used to generate the graph.

![GP data source details](/img/gp-datasource.png)