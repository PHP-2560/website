---
layout: page
title: Final Projects!
published: true
---

## Overview

The goal of your final two projects are to merge everything that you have learned and to create something useful for another researcher or future student to use. 

It is very important that we can create tools and present and display material for audiences with diverse backgrounds to engage in. We need to take the code and the skills we have and put them to use for an audience that does not have the same skills. 

## Project 1: R Package

### Project Guidelines

#### Group Aspect

- Come up with a group R Package
- Clearly assign roles for individuals
    - Functions
    - Vignettes
    - File layout
- Make sure things are cohesive
- Keep on track with Package
- All pieces should fit well together


#### Individual Aspect


- Work to complete your functions.
- Comment and make sure you parts are neat and well organized.
- Make sure you commit your work so that you can verify what you have done. 



1. 11/15/2017-11/21/2017
  - For the second part of the your work, you will be expected to start learning about R Packages:
    - [Hilary Parker Tutorial](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/)
    - [RStudio Package Creation](https://support.rstudio.com/hc/en-us/articles/200486488-Developing-Packages-with-RStudio)
    - [MIT Package Step-by-Step Guide](http://web.mit.edu/insong/www/pdf/rpackage_instructions.pdf)
    - [Karl Broman Package Primer](http://kbroman.org/pkg_primer/)
    - [Hadley Wickham Package Creation Book](http://r-pkgs.had.co.nz/)
  - Getting Ready for Your Package
    -  You will be working in groups of 2-3 for this task. 
    - Identify your group
    - Create your team and start a [repository](https://classroom.github.com/g/wxbg5R5K)
    - Create a`README.md` outlining what your package will be and what each member of the group will do for this package. 
2. 11/21/2017-11/29/2017
  - Bring your package to Class so we can work on it. 
3.  12/16/2017 
    - Final package due to me.
    - Provide an explanation of how it is to be used and discussing the creation of it.
    - Detail the parts of the app you did individually.

 



#### Rubric


Topic| Excellent: <br> ✓+ coded as +  | Satisfactory: <br> ✓ coded as 0  |Needs work: <br> ✓- coded as - |
|----| ------ |-------| -----|
|Coding style| Student has gone beyond what was expected and required, , code is well commented | Coding style lacks refinement and has some errors, but code is readable and has some comments | Many errors in coding style, little attention paid to making the code human readable|
|Coding strategy| Complicated problem broken down into sub-problems that are individually much simpler. Code is efficient, correct, and minimal. Code uses appropriate data structure (list, data frame, vector/matrix/array). Code checks for common errors  | Code is correct, but could be edited down to leaner code. Some "hacking" instead of using suitable data structure. Some checks for errors. |   Code tackles complicated problem in one big chunk. Code is repetitive and could easily be functionalized. No anticipation of errors. |
|Presentation: graphs | Graph(s) carefully tuned for desired purpose. One graph illustrates one point | Graph(s) well chosen, but with a few minor problems: inappropriate aspect ratios, poor labels. | Graph(s) poorly chosen to support questions. |
|Presentation: tables | Table(s) carefully constructed to make it easy to perform important comparisons. Careful styling highlights important features. | Table(s) generally appropriate but possibly some minor formatting deficiencies.| Table(s) with too many, or inconsistent, decimal places. Table(s) not appropriate for questions and findings. Major display problems.|
|Achievement, mastery, cleverness, creativity|Student has gone beyond what was expected and required, e.g., extraordinary effort, additional tools not addressed by this course, unusually sophisticated application of tools from course.|Tools and techniques from the course are applied very competently and, perhaps,somewhat creatively. Chosen task was acceptable, but fairly conservative in ambition.|Student does not display the expected level of mastery of the tools and techniques in this course. Chosen task was too limited in scope.|
|Ease of access for instructor, compliance with course conventions for submitted work|Access as easy as possible, code runs! | Satisfactory | Not an earnest effort to reduce friction and comply with conventions  and/or code does not run|
|Package Runs | Package installs flawlessly | Package installs but with some minor things needed | Package does not run or requires too much to work. |
| Overall Feel of Package | Package is easy to navigate due to amazing documentation. | Package is able to be navigated but not as much documentation to make it easier. | Package needs to be explored with little guidance available | 

## Project 2: Shiny Project

### Individual Aspect

1. Go to the [Shiny](http://shiny.rstudio.com/) website.
    - Explore the [gallery](http://shiny.rstudio.com/gallery/) of Project ideas. 
    - Follow the [Tutorial](http://shiny.rstudio.com/tutorial/)
    - Go through this [Walkthrough by Dean Attali](http://deanattali.com/blog/building-shiny-apps-tutorial/)
    - To show you have done this, create a simple app that takes a standard normal statistic and displays the probability of achieving that value or greater in a standard normal distribution. In other words it takes a \(z\) value and gives a p-value. 

    
### Group Aspect

2. As a group your first task will be to come up with an idea for a Shiny app and to write the code for this. In order to facilitate this more I will provide some structure. 
    - Your app must allow a researcher to use their own inputs. 
    - Your app must display some type of interactive user interface aspects. 
        - For example - [Normal Calculator](https://www.sullivanstatistics.com/shiny/normcalc/): In this app I created depending on where the researcher wants to shade the normal distribution different boxes will pop up after the researcher makes a choice. 
    - You app must display graphical as well as statistical output. 
    - Your app must not be created copying code from an example app that is out there.
        - We want to make sure you are not plagiarizing. In the Normal Calculator app I provided, it appears similar to the DistCalc app from the shiny gallery, however the code behind it comes from my own code and graphing work that I have done in the past. None was copied or pasted from another Shiny app.
    - Your app must function properly and be useful. 
    - Your app must run quickly and not be bulky.
    - Your app should be easy to use or contain detailed instructions.
3. Go through all of the [past Shiny Apps created in PHP 2560](https://github.com/php2560/Final_Projects)
    - Go into the code and download all of the necessary packages to make them run. 
    - Run them using the commands in the README.md file of the repository. 
    - You can use the code from these to help you. 

## Dates of Importance



1. 11/29/2017 - 12/05/2017
    - During this week you will be learning how to write a shiny app.
    - Your calculator must be in a single file format.
    - Must be done individually.
    - Form a group of 3-4 people and have an idea of what kind of app you want to create by this date.  
    - Provide me with an explanation of:
        - What your app will do?
        - How do you see it being used?
        - What types of options might you try to included for the user.
    - If you are struggling with ideas [check this out](/ideas)
    - [Project Starter Code](https://classroom.github.com/group-assignment-invitations/b77f48fc4b1da879109937becd702531)
3. 12/06/2017
    - Bring a rough copy of your app to class.
    - We will spend the entire class working on Apps. 
4. 12/16/2017 at 9:00 AM
    - We will take this last class to explore the apps together.
    - Each group will briefly discuss their app and show how to use it.
    - Presentations must be concise and display usage of the app.
5. 12/21/2017 
    - Final App due to me.
    - You must have your final app in either a 1 or 2 file format.
    - Provide an explanation of how it is to be used and discussing the creation of it.
    - Detail the parts of the app you did individually.
    - Submit form on grading your group members work and contribution to the project.
 

## Rubric For Shiny Project

Grade Category | Points
-------------- | ------------
Tutorial/ Simple App | 10 
App Idea and Explanation | 10 
App and Presentation | 70
Group Evaluations | 10

Recall Rubric From Above. 
