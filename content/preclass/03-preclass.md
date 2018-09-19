---
title: "Week 03 Preclass"
---


## Introduction

We have started to use RStudio and Github. Now is your time to get more acquainted with R itself. We will start working with some of the very basic tools of R. 



## Flipped Material 

- Sign into [Datacamp](https://www.datacamp.com/)
- Complete [Joining Data in R with dplyr](https://www.datacamp.com/courses/joining-data-in-r-with-dplyr) course. 
- Complete these steps for the assignment:
    - Create a new folder in your pre-class Repository called: `Week 03`
    - Copy the `readme.md` and `pre-class-03.Rmd` document into this.
    - Follow the instructions and commit often. 
    

## Preview of Pre-class Problems

### Getting Started


We will work with the dataset called [gapminder](https://github.com/jennybc/gapminder), this is a cleaned up version from [Gapminder Data](http://www.gapminder.org/data/). Gapminder contains a lot of great data on all of the nations of the world. We first need to install the gapminder package in R. 

```
install.packages("gapminder")
```



```
library(dplyr)
library(gapminder)
gapminder
```



### Pre-Class Problems

Use **dplyr** functions to address the following questions:

1. How many unique countries are represented per continent?
2. Which European nation had the lowest GDP per capita in 1997? 
3. According to the data available, what was the average life expectancy across each continent in the 1980s?
4. What 5 countries have the highest total GDP over all years combined?
5. What countries and years had life expectancies of _at least_ 80 years? _N.b. only output the columns of interest: country, life expectancy and year (in that order)._
6. What 10 countries have the strongest correlation (in either direction) between life expectancy and per capita GDP?
7. Which combinations of continent (besides Asia) and year have the highest average population across all countries? _N.b. your output should include all results sorted by highest average population_. With what you already know, this one may stump you. See [this Q&A](http://stackoverflow.com/q/27207963/654296) for how to `ungroup` before `arrange`ing. This also [behaves differently in more recent versions of dplyr](https://github.com/hadley/dplyr/releases/tag/v0.5.0).
8. Which three countries have had the most consistent population estimates (i.e. lowest standard deviation) across the years of available data? 
9. Subset **gm** to only include observations from 1992 and store the results as **gm1992**. What kind of object is this?
10. Which observations indicate that the population of a country has *decreased* from the previous year **and** the life expectancy has *increased* from the previous year? See [the vignette on window functions](https://cran.r-project.org/web/packages/dplyr/vignettes/window-functions.html).






