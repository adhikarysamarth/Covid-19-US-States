Covid-19 Data Analysis with R don
================

# Getting Started

## Downloading and Importing Up-To-Date COVID-19 Data

``` r
rpath1 = "https://raw.githubusercontent.com/nytimes/covid-19-data/master/us-states.csv"
usstates = read.csv(rpath1)
```

## Make a copy

``` r
dat_state = usstates
head(dat_state)
```

    ##         date      state fips cases deaths
    ## 1 2020-01-21 Washington   53     1      0
    ## 2 2020-01-22 Washington   53     1      0
    ## 3 2020-01-23 Washington   53     1      0
    ## 4 2020-01-24   Illinois   17     1      0
    ## 5 2020-01-24 Washington   53     1      0
    ## 6 2020-01-25 California    6     1      0

## Including Code

You can include R code in the document as follows:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](Covid19Samarth_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
