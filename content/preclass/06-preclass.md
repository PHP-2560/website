---
title: "Week 06 Preclass"
---


## Introduction

This Class will be working with Functions again. This means there is little new material however, there is some good reading you should all do. 




## Required Reading

- [R For Data Science: Functions Chapter](http://r4ds.had.co.nz/functions.html)
- [Functional Programming - Advanced R](http://adv-r.had.co.nz/Functional-programming.html)
- [Functionals](http://adv-r.had.co.nz/Functionals.html)
- [Function Operators](http://adv-r.had.co.nz/Function-operators.html)
    
## In-Class Problems

- [Find the files here](https://github.com/PHP-2560/pre-class/tree/master/Week%2006)
- Save the `README.md` and `pre-class-05.Rmd` in your pre-class repository under a new folder called `Week 06`. 
- Remember to commit often. 
    

## These Questions come form your reading

1. Read the source code for each of the following three functions, puzzle out what they do, and then brainstorm better names.

```
f1 <- function(string, prefix) {
  substr(string, 1, nchar(prefix)) == prefix
}
f2 <- function(x) {
  if (length(x) <= 1) return(NULL)
  x[-length(x)]
}
f3 <- function(x, y) {
  rep(y, length.out = length(x))
}
```

2. Compare and contrast rnorm() and MASS::mvrnorm(). How could you make them more consistent?
3. Use `lapply()` and an anonymous function to find the coefficient of variation (the standard deviation divided by the mean) for all columns in the mtcars dataset. 
4. Use vapply() to:
    a. Compute the standard deviation of every column in a numeric data frame.
    b. Compute the standard deviation of every numeric column in a mixed data frame. (Hint: you’ll need to use vapply() twice.)

