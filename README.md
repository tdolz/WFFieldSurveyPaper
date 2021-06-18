# WFFieldSurveyPaper

**This is the repo for the code used in the analysis for the paper "Winter Flounder Navigate the Postsettlement Gauntlet with a Bet-Hedging Strategy" in press in Marine and Coastal Fisheries. It still needs a lot of editing. Please feel free to email me at dolan.tara.e@gmail.com if you have questions about it. Not all of the code contained in this repo made it into the final analysis for the publication** 

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
- we should update the file paths for exporting figures
- transfer the cohort assignment code to a gist/update current gist. 

#COHORTCDFS.Rmd#  
cdfs for cohorts. 
- uses allscoJune30.csv
- need to make a gist of the CDF creation. 

#taraCDFSBAYYEAR.Rmd#
- need to create gist of the CDF creation
