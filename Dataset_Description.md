# Datasets 
This project will combine multiple datasets. Individual & household census data from the American Community Survey years 2012-2022 excluding 2020 due to the data being impacted by the COVID-19 pandemic. Due to the size of the data, we selected features from the entire dataset using IPUMS. The datasets can be found in this [Google Drive](https://drive.google.com/drive/folders/1BgAn6uJvuALPtYoMj1vYInDOWKlxUyXX?usp=drive_link]) and can be accessed following these [instructions](https://usa.ipums.org/usa/extract_instructions.shtml). Additionally, the World Happiness Report dataset from 2012-2022 excluding 2020 is being utilized to examine US happiness. Together the dataset contains over 10 million individuals and 81 variables. The variables were split into groups for ease of understanding. The encoding of categorical variables can be found in the data exploration notebook. 

# World Happiness Report Data

     Number of Variables: 15
     Number of Years: 10

## Variables

**1. Country Name** <br/>
**2. Regional Indicator** <br/>
**3. Year** <br/>
**4. Happiness Index** <br/>
**6. Happiness Rank** (also referred to as the Happiness Score) <br/>
> The rank compared to all other countries examined.
  
**7. Life Ladder** (also referred to as Cantril life ladder). <br/>
> Life ladder is the national average response the Gallup World poll which is stated as: <br/> _“Please imagine a ladder, with steps numbered from 0 at the bottom to 10 at the top. The top of the ladder represents the best possible life for you and the bottom of the ladder represents the worst possible life for you. On which step of the ladder would you say you personally feel you stand at this time?”_

**8. Log GDP Per Capita** <br/>
**9. Social Support** <br/>
> The Social support variable is the national average on a binary scale in response to the question: <br/> _“If you were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?”_

**10. Healthy Life Expectancy At Birth** <br/>
> Life expectancy at birth is monitored by The World Health Organization.

**11. Freedom To Make Life Choices** <br/>
> Freedom to make life choices is the national average of responses to the question: <br/> _“Are you satisfied or dissatisfied with your freedom to choose what you do with your life?”_

**12. Generosity** <br/>
> Generosity is represented by the residual national average to the question: <br/> _“Have you donated money to a charity in the past month?”_ on GDP per capita.

**13. Perceptions Of Corruption** <br/>
> Percent of Corruption is represented by individuals' perception of corruption which is measured by the national average of two true or false questions: <br/>
_1.   “Is corruption widespread throughout the government or not?”_ <br/>
_2.   “Is corruption widespread within businesses or not?”_

**14. Positive Affect** <br/>
> Positive affect represents the national average of three Gallup World Pole Questions: <br/>
_1.   “Did you smile or laugh a lot yesterday?”_ <br/>
_2.   “Did you experience the following feelings during A LOT OF THE DAY yesterday? How about Enjoyment?”_ <br/>
_3.   “Did you learn or do something interesting yesterday?”_

**15. Negative Affect** <br/>
> Negative Affect is also the national average of three Gallup World Pole Questions: <br/>
_1.   “Did you experience the following feelings during A LOT OF THE DAY yesterday? How about Worry?”_ <br/>
_2.   “Did you experience the following feelings during A LOT OF THE DAY yesterday? How about Sadness?”_ <br/>
_3.   Did you experience the following feelings during A LOT OF THE DAY yesterday? How about Anger?”_

**16. Confidence In National Government** <br/>
> The National government variable is relative to the 75th percentile of the global distribution of the first principal component of five measurements of confidence in the national government, judicial system, courts, honesty of election, local police force, and perceived corruption in business.

# Individual Census Data

     Number of Variables: 35
     Number of Individuals: 10,000,426
     Number of Households: 1,394,624
        Note: The data includes multiple years of data for the same household and numerous people within the same household. 

## Variables

#### Technical Variables
**1. Year** <br/>
**2. SAMPLE:** IPUMS sample identifier <br/>
**3. SERIAL:** Household serial number <br/>
**4. CBSERIAL:** Original Census Bureau household serial number <br/>
**5. HHWT:** Household weight <br/>
**6. PERNUM:** Person number in sample unit <br/>
**7. CBPERNUM:** Original Census Bureau Person number in sample unit <br/>
**8. CLUSTER:** Household cluster for variance estimation <br/>
**9. CPI99:** CPI-U adjustment factor to 1999 dollars <br/>
**10. STRATA:** Household strata for variance estimation <br/>

#### Household Variables
**11. PERWT:** Person weight <br/>
**12. FAMSIZE:** Number of own family members in household <br/>
**13. GQ:** Group quarters status <br/>

#### Demographic Variables
**14. SEX:** Sex <br/>
**15. AGE:** Age <br/>
**16. MARST:** Marital status <br/>
**17. RACE:** Race [general version] <br/>
**18. RACED:** Race [detailed version] <br/>
**19. CITIZEN:** Citizenship status <br/>

#### Education Variables
**20. SCHOOL:** School attendance <br/>
**21. EDUC:** Educational attainment [general version] <br/>
**22. EDUCD:** Educational attainment [detailed version] <br/>
**23. SCHLTYPE:** Public or private school <br/>

#### Health Variables
**24. HCOVANY:** Any health insurance coverage <br/>

#### Employment & Income Variables
**25. EMPSTAT:** Employment status [general version] <br/>
**26. EMPSTATD:** Employment status [detailed version] <br/>
**27. CLASSWKR:** Class of worker [general version] <br/>
**28. CLASSWKRD:** Class of worker [detailed version] <br/>
**29. UHRSWORK:** Usual hours worked per week <br/>
**30. LOOKING:** Looking for work <br/>
**31. INCTOT:** Total personal income <br/>
**32. FTOTINC:** Total family income <br/>
**33. INCWELFR:** Welfare (public assistance) income <br/>
**34. INCINVST:** Interest, dividend, and rental income <br/>
**35. POVERTY:** Poverty status <br/>

# Household Census Data

     Number of Variables: 31
     Number of Individuals: 1,0002,255
     Number of Households: 1,416,026
         Note: The data includes multiple years of data for the same household and numerous people within the same household.

## Variables

#### Technical Variables 
**1. YEAR** <br/>
**2. SAMPLE:** IPUMS sample identifier <br/>
**3. SERIAL:** Household serial number <br/>
**4. CBSERIAL:** Original Census Bureau household serial number <br/>
**5. HHWT:** Household weight <br/>
**6. HHTYPE:** Household Type <br/>
**7. CLUSTER:** Household cluster for variance estimation <br/>
**8. CPI99:** CPI-U adjustment factor to 1999 dollars <br/>
**9. STRATA:** Household strata for variance estimation <br/>
   
#### Geographic Variables
**10. STATEICP:** State (ICPSR code) State Identifier with digit codes. <br/>
**11. MET2023:** Metropolitan area (2023 delineations, identifiable areas only) <br/>

#### Economic Characteristics
**12. MOBLHOME:** Annual mobile home costs <br/>
**13. TAXINCL:** Mortgage payment includes property taxes <br/>
**14. INSINCL:** Mortgage payment includes property insurance <br/>
**15. RENTGRS:** Monthly gross rent <br/>
**16. CONDOFEE:** Monthly condominium fee <br/>
**17. MOBLHOME:** Annual mobile home costs <br/>
**18. HHINCOME:** Total household income <br/>
**19. FOODSTMP:** Food stamp recipiency <br/>
**20. VALUEH:** House value <br/>
  
#### Appliance, Mechanical, Other Variables
**21. COSTELEC:** Annual electricity cost <br/>
**22. COSTGAS:** Annual gas cost <br/>
**23. COSTWATR:** Annual water cost <br/>
**24. COSTFUEL:** Annual home heating fuel cost <br/>
**25. CINETHH:** Access to the internet <br/>
**26. VEHICLES:** Vehicles available <br/>
  
#### Household Composition Variables
**27. GQ:** Group quarters status) <br/>
**28. FARM:** Farm status) Farm status is a categorical variable represented by digits. <br/>
**29. OWNERSHP**: Ownership of dwelling (tenure) [general version] <br/>
**30. OWNERSHPD:** Ownership of dwelling (tenure) [detailed version] <br/>
**31. COUPLETYPE:** Householder couple type <br/>
**32. NFAMS:** Number of families in the household <br/>
