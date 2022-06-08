# Important notes
- 2022-06-08: Due to technical problems in SYSVAK, data on vaccination have not been updated today. SYSVAK is working to rectify the problem.

- 2022-04-04: Data for hospitalization all causes will no longer be presented as a part of the covid-19 statistics. This is due to the fact that it no longer gets updated from NoPAR and will give an underestimated number.

- 2022-03-18: Due to technical problems in SYSVAK, data on covid-19 vaccination have not been updated since 16th of March. SYSVAK is working to rectify the problem.

- 2022-03.17: The Covid-19 deaths data will from this date come from DÅR via Beredt C-19 instead of from MSIS. This is because the DÅR data is more up to date at this point. The new file will get a new name and the file will not include sex, age and counties. The file will be updated every Tuesday morning.

- 2022-03-14: Due to technical problems in SYSVAK, data on covid-19 vaccination have not been updated since 10th of March. SYSVAK is working to rectify the problem.

- 2022-03-07: Norwegian population data from 2022 is going to be used starting from 2022-03-10. Relevant changes are made in the R package `fhidata`. Affected datasets are norway_population_by_age_b2020, norway_population_by_age_sex_b2020; affected functions are norway_population_by_age_b2020, norway_population_by_age_sex_b2020. 

- 2022-02-03: There has been changes in the data from SYSVAK for covid-19 vaccination, which means that individuals with old municipality or county number will be registered as “unknown”. The change also applies to data back in time.

- 2022-01-27: The calculation of age for vaccinated individuals has changed from age at time of vaccination to age calculated as year of vaccination minus birth year. This means age will be presented as age groups(cohorts) after year of vaccination. The change also applies to data back in time.

- 2022-01-24: Persons with a 3rd dose (refreshment dose) or 2 doses of corona vaccination and have undergone covid-19 the last 3 months will as a general rule no longer be offered a confirmatory PCR test. This will affect the number of cases reported to MSIS, primarily in the population over the age of 18, where we will capture a lower proportion of those infected than before. Data on reported cases are therefore not directly comparable over time.

- 2022-01-21: The number of Covid-19 cases from Furst laboratories has been delayed in MSIS. This will be updated in the next few days. Once updated, the result will be that the number of cases registered from 15. January will increase by approx 5000-8000.

- 2022-01-05: The vaccination data may be different in this site compared to the covid-19 weekly report. This is because the denominator used in this site is based on SSB-data while the weekly report is based on Folkeregister-data. In addition, in the weekly report the age is calculated as of 31-12-2022 (whole yearly cohorts), while this page gives vaccination data based on age at date of vaccination.  

- 2021-11-18: The SYSVAK data published today (2021-11-18) at the municipality level was incorrect. The error has been corrected in the data published 2021-11-19.

- 2021-10-26: NIPaR data (hospitalisations) has not been updated because of problems with the NIPaR database. It is expected to be updated tomorrow (27th of October).

- 2021-09-08: SYSVAK data has not been updated today because of problems with the SYSVAK database

- 2021-06-30: The number of tested in this github data is not identical to the number of tested in the weekly covid-19 report made by FHI today. This is because the weekly report do include PCR and Antigen test, while this data only include only PCR tested.

- 2021-06-11: SYSVAK data has not been updated today because of problems with the SYSVAK database

- 2021-06-07: SYSVAK data has not been updated today because of problems with the SYSVAK database.

- 2021-04-30: There was earlier some missing values in the covid-19 SYSVAK data, this has been fixed, but can cause changes in the numbers in some areas.

- 2021-04-16: There is an error in the file from 2021_04_16, PLEASE DO NOT USE THIS FILE.

- From 2021_04_19: There is a change in the dates displayed in the file "data_covid19_lab_by_time_". This file will from this point only show data from 2020_04_01. This is because of a change to using MSIS data instead of laboratory data.

# Available COVID-19 datasets

- [covid19/data_covid19_demographics_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_demographics.txt) **First published 2020-06-25.** Contains demographic information about deaths.
- [covid19/data_covid19_hospital_by_time_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_hospital_by_time.txt) **First published 2020-06-23.** Contains information about number of people in hospitals and ICUs with COVID-19 as the primary cause.
- [covid19/data_covid19_lab_by_time_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_lab_by_time.txt) **First published 2020-06-23.** Contains information about the number of people tested for COVID-19.
- [covid19/data_covid19_msis_by_location_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_msis_by_location.txt) **First published 2020-06-04.** Contains the number of people diagnosed with COVID-19 per location.
- [covid19/data_covid19_msis_by_time_location_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_msis_by_time_location.txt) **First published 2020-04-24.** Contains the number of people diagnosed with COVID-19 per location and day (i.e. epicurves).
- [covid19/data_covid19_msis_by_time_sex_age_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_msis_by_time_sex_age.txt) **First published 2020-06-23.** Contains information about the sex/age of people diagnosed with COVID-19 over time.
- [covid19/data_covid19_sysvak_by_location_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_sysvak_by_location.txt) **First published 2021-01-20.** Contains the number of people who have been vaccinated for COVID-19 per location.
- [covid19/data_covid19_sysvak_by_time_location_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_sysvak_by_time_location.txt) **First published 2021-01-20.** Contains the number of people who have been vaccinated for COVID-19 per location and day.

# Note about "missing data" in the covid19 folder

![img](https://raw.githubusercontent.com/folkehelseinstituttet/surveillance_data/master/misc/img-missing-data.png)

Because we have uploaded over 1000 data files to the covid19 folder, some files are no longer directly viewable from the browser.

There are three ways that you can obtain your data:

1. Download the entire data repository https://github.com/folkehelseinstituttet/surveillance_data/archive/master.zip
2. Use a desktop program (e.g. https://desktop.github.com/) to syncronize the repository to your computer (this is similar to a manual dropbox/onedrive/google drive sync). The following links can be useful:
    - https://docs.github.com/en/free-pro-team@latest/desktop/contributing-and-collaborating-using-github-desktop/cloning-a-repository-from-github-to-github-desktop
    - https://docs.github.com/en/free-pro-team@latest/desktop/contributing-and-collaborating-using-github-desktop/syncing-your-branch#pulling-to-your-local-branch-from-the-remote
3. Directly "knowing" the link of the data file you are interested in (e.g. https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/data_covid19_msis_by_time_location_2020-11-23.csv)

We recommend that you use either solution #1 or #2.

# surveillance_data

This is a frequently updated repository for Norwegian surveillance data from Folkehelseinstituttet (Norwegian Institute of Public Health).

The purpose of this repository is to make surveillance data easily accessible from a machine-reading perspective.

Documentation for each dataset is available in text files beginning with \_DOCUMENTATION\_

If something does not appear to be correct, or more documentation is needed in a particular area, or you have suggestions about the way the data is presented/formatted, please email the following three email addresses simultaneously: sykdomspulsen@fhi.no, RichardAubrey.White@fhi.no, and CelineVictoria.Berg-Hansen@fhi.no
