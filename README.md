# WFFieldSurveyPaper
compare mortality and growth between bays, cohort assignment, CDFS

#CatchandGrowthCurves.Rmd.  
-- Catch and growth comparisons between bays and years --
Bays: Shinnecock, Moriches, Mattituck, Napeague, Cold Spring Pond, Jamaica
Years: 2010, 2011, 2015, 2016, 2017
uses somedata3_Mar-4-2020.csv 
some_mt_data.csv
lyndie_lengths.csv
allmeltdec2019.csv
- total effort and capture table
- plots of CPUE by week 
- graph abundance for all years and bays
- extract regression coefficients for table
- compare mortality estimates with dummy regression
- Tukey HSD to extract differences between the intercepts
- LSmeans for pairwise comparisons of slopes
- Chapman-Robson method to extract mortality estimates
- mortality estimates barplot
- selectivity correct lyndie's (2010-2011) length data
- ggridges graphs for length data each year and bay
- growth by year
- growth ANCOVAs
- lsmeans for growth estimate pairwise comparisons
- regressions for each bayyear growth

#CohortGrowthJune2020_Ver1.Rmd
-- Cohort assignment and catch and growth for cohorts in Mattituck 2016, Shinnecock 2016 and Shinnecock 2017 --
**We are using the "skcompiled4gams2.csv** but we should consider re-doing this using the "somedata_Mar-4-2020.csv" for consistency with the other scripts**
**we should update the file paths for exporting figures**
also uses "some_mt_data.csv", lyndie_lengths.csv, allmeltdec2019.csv and "mattyage4.csv"
- histogram of environmental data for each bay and year. **this does not belong in this script, but w/e**
- Cohort assignment including a comparison of mixture vs. normal model fits. 
- alter the plot mixEM function to fix the density bars. 
- function to do cohort assignment with mixtools
- A multi-histogram function that we are not using because it's broken
- another broken multi-histogram function with a custom distribution
- cohort assignment applied to all bays and years. 
- a comparison of cohorts assigned by our function to those assigned by age. 
-  mortality regression standardized to days since peak
- extract coefficients of regression
- facet plot fo cohort regression in Shinnecock
- shinnecock and mattituck mortality ANCOVAs, Tukey Test and LS means 
- extract mortality estimate for each cohort from catch curves
- barplots of mortality estimates
- cohort regressions, ANCOVAS, tests, plots for growth
- ggridges plot for cohorts
- extract regression coefficients for growth from each cohort
-  barplots of regression estimates for growth
-  