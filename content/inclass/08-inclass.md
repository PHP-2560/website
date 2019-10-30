---
title: "Week 08 Inclass"
---


#  Class 8:  October 30, 2019


## Agenda

1. Questions


## DO NOT DO ANYTHING BELOW BEFORE I GIVE INSTRUCTIONS

1.This is an individual lab so everyone needs to click on the link below. 
2. You can still work together. 



[Please click](https://classroom.github.com/a/U1kJRVEV) in order to get your github repository with the assignment and starter code. 

You will not turn anything in but by Friday, November 2 at 11:59pm you will no longer be able to commit. So make sure the files showing your contribution are committed by then. 


## Tips

- Clone this github repository
- Then open the R-Project not just the file
- When you make changes Follow these steps:
    - Add files changed
    - Commit Changes
    - Pull 
    - Push
    
    
## Database




[Download Data](https://drive.google.com/file/d/1q2VGPjaK6MxaRDiKFA0x405dAbGvXJNy/view?usp=sharing)

Then you can connect to the database in R with the following code:

```
library(RMySQL)
con <- dbConnect(MySQL(),
                 user = 'rcourse',
                 password = .rs.askForPassword("Enter Password"),
                 host = 'rcourse.c00zdn7tgzwg.us-east-1.rds.amazonaws.com',
                 port=3306,
                 dbname='rcourse')
```
    
    
## Change the read data code for where your file is:

```
titanic <- read.table("C:/Users/adam_/Downloads/titanic.csv", header=TRUE, sep=",")
```



## Directly use Dplyr in SQL

[THis page shows you how](https://beanumber.github.io/mysql-r-webinar/dplyr.html)
    