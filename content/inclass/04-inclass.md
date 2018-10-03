---
title: "Week 04 Inclass"
---


# Fourth Class:  October 3, 2018


## Agenda

1. Questions
2. Discuss Preclass work
3. In Class Project



## DO NOT DO ANYTHING BELOW BEFORE I GIVE INSTRUCTIONS

1. Have one Person in your group click on this link and create a group and name that group. 
2. All other members can then click on the link and join the appropriate group. 

[In Class Exercise](https://classroom.github.com/g/1OzB85w5)



```
bubblesort <- function(x) {

if (length(x) < 2) return (x)

for(last in length(x):2) {
for(first in 1:(last - 1)) {
if(x[first] > x[first + 1]) { 
save <- x[first]
x[first] <- x[first + 1]
x[first + 1] <- save
}
}
}
return (x)
}
```

