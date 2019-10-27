# Pentaho ETL Process Samples

## ETL: dw_di_time
ETL process responsible for generating time loads that can be used in BI analysis.
Time data is generated from the start date (Parameter: INITIAL_DATE) by sequentially adding the number of days defined by the parameter: NUMBER_OF_DAYS.

This process will generate the fields below for the chosen time range:

- Next Date
- Day of the week
- Month of the year
- Year
- It's weekend?
- Is it a national holiday?
- 1nd Quarter (Two months) of the year
- 2nd Quarter (Three months) of the year
- 3nd Quarter (Four months) of the year
- Semester of the year

Date Format: yyyy-MM-dd
