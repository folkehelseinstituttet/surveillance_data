# 2021_09_08: SYSVAK data has not been updated today because of problems with the SYSVAK database

# 2021_06_30: The number of tested in this github data is not identical to the number of tested in the weekly covid-19 report made by FHI today. This is because the weekly report do include PCR and Antigen test, while this data only include only PCR tested.

# 2021_06_11: SYSVAK data has not been updated today because of problems with the SYSVAK database

# 2021_06_07: SYSVAK data has not been updated today because of problems with the SYSVAK database.

# 2021_04_30: There was earlier some missing values in the covid-19 SYSVAK data, this has been fixed, but can cause changes in the numbers in some areas.

# 2021_04_16: There is an error in the file from 2021_04_16, PLEASE DO NOT USE THIS FILE.

# From 2021_04_19: There is a change in the dates displayed in the file "data_covid19_lab_by_time_". This file will from this point only show data from 2020_04_01. This is because of a change to using MSIS data instead of laboratory data.
#####################################################################################################################################################

# Available COVID-19 datasets

- [covid19/data_covid19_demographics_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_demographics.txt) **First published 2020-06-25.** Contains demographic information about deaths.
- [covid19/data_covid19_hospital_by_time_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_hospital_by_time.txt) **First published 2020-06-23.** Contains information about number of people in hospitals and ICUs with COVID-19 as the primary cause.
- [covid19/data_covid19_lab_by_time_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_lab_by_time.txt) **First published 2020-06-23.** Contains information about the number of people tested for COVID-19.
- [covid19/data_covid19_msis_by_location_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_msis_by_location.txt) **First published 2020-06-04.** Contains the number of people diagnosed with COVID-19 per location.
- [covid19/data_covid19_msis_by_time_location_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_msis_by_time_location.txt) **First published 2020-04-24.** Contains the number of people diagnosed with COVID-19 per location and day (i.e. epicurves).
- [covid19/data_covid19_msis_by_time_sex_age_YYYY_MM_DD](https://github.com/folkehelseinstituttet/surveillance_data/blob/master/covid19/_DOCUMENTATION_data_covid19_msis_by_time_sex_age.txt) **First published 2020-06-23.** Contains information about the sex/age of people diagnosed with COVID-19 over time.
- covid19/data_covid19_sysvak_by_location_YYYY_MM_DD **First published 2021-01-20.** Contains the number of people who have been vaccinated for COVID-19 per location.
- covid19/data_covid19_sysvak_by_time_location_YYYY_MM_DD **First published 2021-01-20.** Contains the number of people who have been vaccinated for COVID-19 per location and day.

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

If something does not appear to be correct, or more documentation is needed in a particular area, or you have suggestions about the way the data is presented/formatted, please email RichardAubrey.White@fhi.no
