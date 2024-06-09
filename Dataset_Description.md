# Datasets 
This project will combine multiple datasets. Individual & household census data from the American Community Survey years 2012-2022 excluding 2020 due to the data being impacted by the COVID-19 pandemic. Due to the size of the data, we selected features from the entire dataset using IPUMS. The datasets can be found in this Google Drive (https://drive.google.com/drive/folders/1BgAn6uJvuALPtYoMj1vYInDOWKlxUyXX?usp=drive_link) and can be accessed following these instructions https://usa.ipums.org/usa/extract_instructions.shtml Additionally, the World Happiness Report dataset from 2012-2022 excluding 2020 is being utilized to examine US happiness. Together the dataset contains over 10 million individuals and 81 variables.

# World Happiness Report Data

     Number of Variables: 15
     Number of Years: 10

## Variables

1. Country Name
2. Regional Indicator
3. Year
4. Happiness Index
5. Happiness Rank
6. Life Ladder
7. Log GDP Per Capita
8. Social Support
9. Healthy Life Expectancy At Birth
10. Freedom To Make Life Choices
11. Generosity
12. Perceptions Of Corruption
13. Positive Affect
14. Negative Affect
15. Confidence In National Government

# Individual Census Data

     Number of Variables: 35
     Number of Individuals: 10,000,426
     Number of Households: 1,394,624
        Note: The data includes multiple years of data for the same household and numerous people within the same household. 

## Variables

* Year
* SAMPLE (IPUMS sample identifier)
* SERIAL (Household serial number)
* CBSERIAL: (Original Census Bureau household serial number)
* HHWT: (Household weight)
* PERNUM: (Person number in sample unit)
* CBPERNUM: (Original Census Bureau Person number in sample unit)
* CLUSTER: (Household cluster for variance estimation)
* CPI99: (CPI-U adjustment factor to 1999 dollars)
* STRATA: (Household strata for variance estimation) Household Variables
* PERWT: (Person weight)
* FAMSIZE: (Number of own family members in household)
* GQ: (Group quarters status) Demographic Variables
* SEX: (Sex)
* AGE: (Age)
* MARST: (Marital status)
* RACE: (Race [general version])
* RACED: (Race [detailed version])
* CITIZEN: (Citizenship status) Education Variables
* SCHOOL: (School attendance)
* EDUC: (Educational attainment [general version])
* EDUCD: (Educational attainment [detailed version])
* SCHLTYPE: (Public or private school) Health Variables
* HCOVANY: (Any health insurance coverage) Employment & Income Variables
* EMPSTAT: (Employment status [general version])
* EMPSTATD: (Employment status [detailed version])
* CLASSWKR: (Class of worker [general version])
* CLASSWKRD: (Class of worker [detailed version])
* UHRSWORK: (Usual hours worked per week)
* LOOKING: (Looking for work)
* INCTOT: (Total personal income)
* FTOTINC: (Total family income)
* INCWELFR: (Welfare (public assistance) income)
* INCINVST: (Interest, dividend, and rental income)
* POVERTY: (Poverty status)

# Household Census Data

     Number of Variables: 31
     Number of Individuals: 1,0002,255
     Number of Households: 1,416,026
         Note: The data includes multiple years of data for the same household and numerous people within the same household.

## Variables

* YEAR
* SAMPLE: (IPUMS sample identifier)
* SERIAL: (Household serial number)
* CBSERIAL: (Original Census Bureau household serial number)
* HHWT: (Household weight)
* HHTYPE: (Household Type)
* CLUSTER: (Household cluster for variance estimation)
* CPI99: (CPI-U adjustment factor to 1999 dollars)
* STRATA: (Household strata for variance estimation) Geographic Variables
* STATEICP: (State (ICPSR code)) State Identifier with digit codes.
* MET2023: (Metropolitan area (2023 delineations, identifiable areas only)) Economic Characteristics
* MOBLHOME: (Annual mobile home costs)
* TAXINCL: (Mortgage payment includes property taxes)
* INSINCL: (Mortgage payment includes property insurance)
* RENTGRS: (Monthly gross rent)
* CONDOFEE: (Monthly condominium fee)
* MOBLHOME: (Annual mobile home costs)
* HHINCOME: (Total household income)
* FOODSTMP: (Food stamp recipiency)
* VALUEH: (House value) Appliance, Mechanical, Other Variables
* COSTELEC: (Annual electricity cost)
* COSTGAS: (Annual gas cost)
* COSTWATR: (Annual water cost)
* COSTFUEL: (Annual home heating fuel cost)
* CINETHH: (Access to internet)
* VEHICLES: (Vehicles available) Household Composition Variables
* GQ: (Group quarters status)
* FARM: (Farm status) Farm status is a categorical variable represented by digits.
* OWNERSHP: (Ownership of dwelling (tenure) [general version])
* OWNERSHPD: (Ownership of dwelling (tenure) [detailed version])
* COUPLETYPE: (Householder couple type)
* NFAMS: (Number of families in the household)
