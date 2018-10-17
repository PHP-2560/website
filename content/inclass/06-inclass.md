---
title: "Week 05 Inclass"
---


# sixth Class:  October 17, 2018


## Agenda

1. Questions


## DO NOT DO ANYTHING BELOW BEFORE I GIVE INSTRUCTIONS

1. Have one Person in your group click on this link and create a group and name that group. 
2. All other members can then click on the link and join the appropriate group. 

[In Class Exercise](https://classroom.github.com/g/QAZJmnfP)


You may need to just use these functions directly:

```
omit.case <- function(the_data,omitted_point) {
    # This should take the data and omit one point at a time and return the new data
        if(is.null(dim(the_data))) {
          return(the_data[-omitted_point])
        } else {
          return(the_data[-omitted_point,])
        }
      }
```



```
omit_and_est <- function(omit) {
  estimator(omit.case(data,omit)) # This function should take the output of omit.case and use it as input for the estimator
}
```