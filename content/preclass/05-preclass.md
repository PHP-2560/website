---
title: "Week 05 Preclass"
---


## Introduction

We will begin working with functions in R. 



## Flipped Material

- Sign into [Datacamp](https://www.datacamp.com/)
- Complete [Chapters 4: Functions](https://campus.datacamp.com/courses/1118/) from PHP 1560/2560 Statistical Programing with R. 
- Complete [Writing Functions in R Course](https://www.datacamp.com/courses/writing-functions-in-r)
- Complete these steps for the assignment:
    - Create a new folder in your pre-class Repository called: `Week 05`
    - Copy the `readme.md` and `pre-class-05.Rmd` document into this.
    - Follow the instructions and commit often.
    
## In-Class Problems

- [Find the files here](https://github.com/PHP-2560/pre-class/tree/master/Week%2005)
- Save the `README.md` and `pre-class-05.Rmd` in your pre-class repository under a new folder called `Week 05`. 
- Remember to commit often. 
    

Standardizing a variable means subtracting the mean, and then dividing by the standard deviation. Let’s use a loop to standardize the numeric columns in the [Western Collaborative Group Study](https://clinicaltrials.gov/ct2/show/NCT00005174). This study began in 1960 with 3154 men ages 39-59, who were employed in one of 11 California based companies. They were followed until 1969 during this time, 257 of these men developed coronary heart disease (CHD). 


The data has the following variables:



WCGS has the following variables:

-----------------------------------------------------------
Name    Description
------- -------------------------------------------
id      Subject identification number

age     Age in years

height  Height in inches

weight  Weight in lbs.

sbp     Systolic blood pressure in mm 

dbp     Diastolic blood pressure in mm Hg

chol    Fasting serum cholesterol in mm 

behpat  Behavior

  1       A1

  2       A2

  3       B3

  4       B4

ncigs   Cigarettes per day

dibpat  Behavior

1       type A

2       type B

chd69   Coronary heart disease

1       Yes

0       no

typechd Type of CHD

1       myocardial infarction or death

2       silent myocardial infarction

3       angina perctoris

time169 Time of CHD event or end of follow-up

arcus   Arcus senilis

0       absent

1       present

bmi     Body Mass Index
-----------------------------------------------------------




### Question 1: Standardize Function

A. Create a function called standardize.me() that takes a numeric vector as an argument, and returns the standardized version of the vector. 
B. Assign all the numeric columns of the original WCGS dataset to a new dataset called WCGS.new.
C. Using a loop and your new function, standardize all the variables WCGS.new dataset.
D. What should the mean and standard deviation of all your new standardized variables be? Test your prediction by running a loop




### Question 2: Looping to Calculate

A. Using a loop, calculate the mean weight of the subjects separated by the type of CHD they have.
B. Now do the same thing, but now don’t use a loop
