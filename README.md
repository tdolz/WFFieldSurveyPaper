# WFFieldSurveyPaper
compare mortality and growth between bays, cohort assignment, CDFS

#CSV files#
- somedata3_Mar-4-2020.csv - is all the data on catch and environmental measurements, except for mattituck
- some_mt_data.csv - is the mattituck data
- lyndie_lengths.csv is the melted version of the lyndie data. 
- allmeltdec2019.csv is a melted version of all bays and years. 

#CatchandGrowthCurves.Rmd#  
-- Catch and growth comparisons between bays and years --
Bays: Shinnecock, Moriches, Mattituck, Napeague, Cold Spring Pond, Jamaica
Years: 2010, 2011, 2015, 2016, 2017
uses somedata3_Mar-4-2020.csv, some_mt_data.csv, lyndie_lengths.csv, allmeltdec2019.csv

#CohortGrowthJune2020_Ver1.Rmd#
-- Cohort assignment and catch and growth for cohorts in Mattituck 2016, Shinnecock 2016 and Shinnecock 2017 --
uses skcompiled4gams2.csv but also lyndie-lengths, mattyage4.csv and some_mt_data
#Updates needed#
- We are using the "skcompiled4gams2.csv** but we should consider re-doing this using the "somedata_Mar-4-2020.csv" for consistency with the other scripts**
- we should update the file paths for exporting figures
- transfer the cohort assignment code to a gist/update current gist. 

#COHORTCDFS.Rmd#  
cdfs for cohorts. 
- uses skcompiled4gams2.csv but we should change to somedata_Mar-4-2020.csv for consistency. 
- uses allscoJune30.csv
- need to make a gist of the CDF creation. 

#taraCDFSBAYYEAR.Rmd#
- need to create gist of the CDF creation
- uses skcompiled4gams2,csv. you should update to use somedata3_Mar-4-2020.csv. 