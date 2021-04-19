# (US flight investigation for cause of delay and cancellation)
## by (Mahmoud Elsayed)


## Dataset

> Summary information on the number of on-time, delayed, canceled and diverted flights appears in DOT's monthly Air Travel Consumer Report, the dataset contains 294237 observations from June 2003 to january 2021.

## Data Wrangling
 - Dropped a faulty column with all Nans
 - Renamed columns to better describe their values
 - removed all rows with Nans from the dataset


## Summary of Findings

>  all the univariate exploration (histograms plots) were rightly skewed
> CA state having the highest cancelled flight due to weather 
> Strong positive correlation between delay feature with its corresponding count feature 
> Weather delays of flight are the highest in the summer months
> Highest number of cancelled flights were in the begining of the pandemic (march and april of 2020)

## Key Insights for Presentation

> Weather isn't the main cause for delays and cancellation of flights instead the late_aircraft feature was the main reason of flight delays

> The hot weather had more effect on the delay of  flights than the cold weather

> Texas is the state with most delayed flights due to weather

