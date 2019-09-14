---
title: "Week 04 Preclass"
---


## Introduction

We wil begin to learn how to use R to a much higher level. 



## Flipped Material 

- Sign into [Datacamp](https://www.datacamp.com/)
- Complete [Chapters 3: Flow Control and Initial Functions](https://campus.datacamp.com/courses/1118/) from PHP 1560/2560 Statistical Programing with R. 
- Complete [Intermediate R](https://www.datacamp.com/courses/intermediate-r) Course. 
- Complete these steps for the assignment:
    - Create a new folder in your pre-class Repository called: `Week 04`
    - Copy the `readme.md` and `pre-class-04.Rmd` document into this.
    - Follow the instructions and commit often.
    
## In-Class Problems

- [Find the files here](https://github.com/PHP-2560/pre-class/tree/master/Week%2004)
- Save the `README.md` and `pre-class-04.Rmd` in your pre-class repository under a new folder called `Week 04`. 
- Remember to commit often. 
    

## Preview of Pre-class Problems



### Question 1:

Using a loop, print the integers from 1 to 50. 

### Question 2:

A.  Using a loop, add all the integers between 0 and 1000.

B. Now, add all the EVEN integers between 0 and 1000 (hint: use seq())

C. Now, repeat A and B WITHOUT using a loop.


### Question 3: 

Learn the rules of the game yahtzee, we will be simulating this game in class. Make sure you are ready to do this. 

### (PHP 2560 Only) Question 4:

Here is a dataframe of survey data containing 5 questions :

```{r, eval=FALSE}
survey <- data.frame(
                     "participant" = c(1, 2, 3, 4, 5, 6),
                     "q1" = c(5, 3, 2, 7, 11, 0),
                     "q2" = c(4, 2, 2, 5, -10, 99),
                     "q3" = c(-4, -3, 4, 2, 9, 10),
                     "q4" = c(-30, 5, 2, 23, 4, 2),
                     "q5" = c(88, 4, -20, 2, 4, 2)
                     )
```
The response to each question should be an integer between 1 and 5. Obviously, we have some bad values in the dataframe. The goal of this problem is to fix them.

A. Using a loop, create a new dataframe called survey.clean where all the invalid values (those that are not integers between 1 and 5) are set to NA.

B. Now, again using a loop, add a new column to the dataframe called “invalid.answers” that indicates, for each participant, how many bad answers they gave.