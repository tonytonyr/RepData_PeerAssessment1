# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

```r
activity <- read.csv("activity.csv")
activity[,2] <- as.Date(activity[,2])
activity <- as.data.frame(activity)
```


## What is mean total number of steps taken per day?


## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
