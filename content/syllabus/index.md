---
title: ""
---


<style type="text/css">code{white-space: pre;}</style>
<style type="text/css">
  pre:not([class]) {
    background-color: white;
  }
</style>
<script type="text/javascript">
if (window.hljs) {
  hljs.configure({languages: []});
  hljs.initHighlightingOnLoad();
  if (document.readyState && document.readyState === "complete") {
    window.setTimeout(function() { hljs.initHighlighting(); }, 0);
  }
}
</script>



<style type="text/css">
h1 {
  font-size: 34px;
}
h1.title {
  font-size: 38px;
}
h2 {
  font-size: 30px;
}
h3 {
  font-size: 24px;
}
h4 {
  font-size: 18px;
}
h5 {
  font-size: 16px;
}
h6 {
  font-size: 12px;
}
.table th:not([align]) {
  text-align: left;
}
</style>


</head>

<body>

<style type="text/css">
.main-container {
  max-width: 940px;
  margin-left: auto;
  margin-right: auto;
}
code {
  color: inherit;
  background-color: rgba(0, 0, 0, 0.04);
}
img {
  max-width:100%;
  height: auto;
}
.tabbed-pane {
  padding-top: 12px;
}
button.code-folding-btn:focus {
  outline: none;
}
</style>



<div class="container-fluid main-container">

<!-- tabsets -->
<script>
$(document).ready(function () {
  window.buildTabsets("TOC");
});
</script>

<!-- code folding -->





<div class="fluid-row" id="header">



<h1 class="title toc-ignore">PHP 1560/2560: Statistical Computing with R</h1>
<h4 class="author">Dr. Adam J Sullivan</h4>
<h4 class="date">Fall 2019</h4>

</div>


<div id="course-description" class="section level1">
<h1>Course Description</h1>
<p>Statistical computing is an essential part of analysis. Statisticians need not only be able to run existing computer software but understand how that software functions. Students will learn fundamental concepts - Data Management, Data types, Data cleaning and manipulation, databases, graphics, functions, loops, simulation and Markov Chain Monte Carlo through working with various statistical analysis. Students will learn to write code in an organized fashion with comments. This course will use a variety of web-based material from:</p>
<ul>
<li><a href="http://php2560.com">php2560.com</a></li>
<li><a href="https://www.datacamp.com/courses/1118">DataCamp</a></li>
<li><a href="http://http://statseducation.com/Introduction-to-R/">Online Book</a></li>
<li><a href="https://www.github.com">Github</a></li>
</ul>
</div>
<div id="course-format" class="section level1">
<h1>Course Format</h1>
<p>This course will be taught in a “flipped” format. Students will watch a series of videos and work through some simple coding examples before coming to class. The sequence of these will be displayed on the course website as well as a calendar for which videos need to be watched prior to attending class.</p>
<p>The classroom format will focus on labs and projects. You will be involved with computing and coding on a regular basis. Labs will form into projects which you will finish outside of class and turn in for grading.</p>
</div>
<div id="flipped-format-and-references" class="section level1">
<h1>Flipped Format and References</h1>
<p>We need to take some time to discuss what it means to have a flipped format class. In this style of formatting the note taking portion of the course will be done via videos. Think of these as video textbooks in which you gather the basic details before practicing the material.</p>
<p>In the traditional format this course would have the instructor teaching 160 minutes a week with some hands on lab activities but most coding work done outside of class. In the flipped format you will have access to these lectures as your work prior to class. You then will have 180 minutes of hands on coding projects, code sharing and time with the instructor.</p>
<p>This course will utilize a wealth of materials from many different resources aside from the textbooks:</p>
<ul>
<li>The majority of R videos will be hosted by  and created by the instructor.</li>
<li>Some notes have been adapted from:
<ul>
<li>Shalizi, C. R. and Thomas, A. C. (2014), <a href="http://www.stat.cmu.edu/~cshalizi/statcomp/14">Statistical Computing 36-350: Beginning to Advanced Techniques in R</a></li>
</ul></li>
<li>Shiny is a product of R Studio and will be presented by RStudio with example created by the last 2 classes PHP 2560 class and the instructor.</li>
</ul>
</div>
<div id="prerequisites" class="section level1">
<h1>Prerequisites</h1>
<p>Students should have courses in probability and statistical inference at the level of PHP 1510 or PHP 2510.</p>
</div>
<div id="recommended-textbooks" class="section level1">
<h1>Recommended Textbooks</h1>
<ul>
<li>Matloff, Norman (2011). <a href="https://www.nostarch.com/artofr.htm">The Art of Programming</a>. No Starch Press.</li>
<li>Rizzo, Maria L. (2007). <a href="https://www.crcpress.com/Statistical-Computing-with-R/Rizzo/9781584885450">Statistical Computing with R</a>. Chapman and Hall/CRC.</li>
<li>Jones, Owens; Maillardet, Robert &amp; Robinson, Andrew. (2011). <a href="https://www.crcpress.com/Introduction-to-Scientific-Programming-and-Simulation-Using-R-Second-Edition/Jones-Maillardet-Robinson/9781466569997">An Introduction to Scientific Programming and Simulation Using R</a>. Chapman and Hall/CRC.</li>
<li>Teetor, Paul. (2011). <a href="http://shop.oreilly.com/product/9780596809164.do">R Cookbook</a>. O’Reilly Media.</li>
</ul>
</div>
<div id="course-objectives" class="section level1">
<h1>Course Objectives</h1>
<p>After the successful completion of this course, you will understand and be able to implement the fundamental principles of statistical computing in R. In particular these include the following capabilities:</p>
<ol style="list-style-type: decimal">
<li>item Obtain and work with Data.</li>
<li>Clean and Transform data into usable dataframes.</li>
<li>Create Graphics.</li>
<li>Understand the writing and use of functions.</li>
<li>Working with larger dataframes efficiently.</li>
<li>Perform Statistical Optimizations</li>
<li>Code and run an MCMC.</li>
<li>Data visualization.</li>
<li>Relational Databases</li>
</ol>
</div>
<div id="overall-course-expectations" class="section level1">
<h1>Overall Course Expectations</h1>
<p>Students in this course will be expected to do the following:</p>
<ol style="list-style-type: decimal">
<li>Attend all lectures and actively participate in in class sessions, for every class missed there will be a 5% reduction in overall grade.<br />
</li>
<li>Complete all assigned flipped material <em>prior</em> to coming to class and be prepared to work on in class lab.</li>
<li>Complete and turn in all assignments on time. All assignments will be graded on ability of code to work, quality of coding and quality of comments on code.</li>
<li>Demonstrate an understanding on material on all projects.<br />
</li>
<li>Respect each other, each others questions and each others discussion.</li>
<li>Peer review other students code.</li>
</ol>
</div>
<div id="evaluation" class="section level1">
<h1>Evaluation</h1>
<p>Students will be evaluated based on:</p>
<table style="width:78%;">
<colgroup>
<col width="31%"></col>
<col width="45%"></col>
</colgroup>
<thead>
<tr class="header">
<th align="left">Grade Category</th>
<th align="center">Percentage</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Pre-Class Assignments</td>
<td align="center">20%</td>
</tr>
<tr class="even">
<td align="left">In-Class Projects</td>
<td align="center">20%</td>
</tr>
<tr class="odd">
<td align="left">R Package</td>
<td align="center">30%</td>
</tr>
<tr class="even">
<td align="left">Shiny App</td>
<td align="center">30%</td>
</tr>
</tbody>
</table>

</div>
<div id="differences-between-php-15602560" class="section level1">
<h1>Differences between PHP 1560/2560</h1>
<p>Given the nature of this course with multiple levels of students from Undergraduate to PhD, it is important to discuss the differences of expectations and how students will be graded.</p>
<div id="undergraduates" class="section level2">
<h2>Undergraduates</h2>
<table style="width:78%;">
<colgroup>
<col width="31%"></col>
<col width="45%"></col>
</colgroup>
<thead>
<tr class="header">
<th align="left">Grade Category</th>
<th align="center">Comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Participation</td>
<td align="center">Graded the same as all students, Must be in class and prepared to work in groups.</td>
</tr>
<tr class="even">
<td align="left">Pre-Class Assignments</td>
<td align="center">Students will be expected to complete a portion of the material with the exception of some more difficult problems which may be attempted but do not have to be complete. Peer Review will be the same.</td>
</tr>
<tr class="odd">
<td align="left">In-Class Projects</td>
<td align="center">Students will work on the same projects that all other students work on. They will be placed in groups with other students but will not be expected to contribute the same level of coding as graduate students.</td>
</tr>
<tr class="even">
<td align="left">R Package</td>
<td align="center">Students will build an R package. Functions may be basic or simple given the amount of statistics taken by this point in time.</td>
</tr>
<tr class="odd">
<td align="left">Shiny App</td>
<td align="center">Shiny app coding as well as end result will be at an appropriate level for the understanding of statistics and data analysis of the students.</td>
</tr>
</tbody>
</table>

</div>
<div id="graduate-students" class="section level2">
<h2>Graduate Students</h2>
<table style="width:78%;">
<colgroup>
<col width="31%"></col>
<col width="45%"></col>
</colgroup>
<thead>
<tr class="header">
<th align="left">Grade Category</th>
<th align="center">Comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Participation</td>
<td align="center">Graded the same as all students, Must be in class and prepared to work in groups.</td>
</tr>
<tr class="even">
<td align="left">Pre-Class Assignments</td>
<td align="center">Students will be expected to complete all parts of the assignments. Peer reviews will be thorough and well critiqued.</td>
</tr>
<tr class="odd">
<td align="left">In-Class Projects</td>
<td align="center">Students will work on the same projects that all other students work on. It is expected that graduate students will contribute more coding to the projects as well as leadership.</td>
</tr>
<tr class="even">
<td align="left">R Package</td>
<td align="center">Students will build an R package. Functions are expected to be useful to the area of statistics students are working in. Graduate students will be expected to have more challenging methods and data incorporated into their R package.</td>
</tr>
<tr class="odd">
<td align="left">Shiny App</td>
<td align="center">Shiny app coding as well as end result will be at an appropriate level for the understanding of statistics and data analysis of the students.</td>
</tr>
</tbody>
</table>

</div>
<div id="evaluation-category-details" class="section level2">
<h2>Evaluation Category Details</h2>
<div id="participation" class="section level3">
<h3>Participation</h3>
<p>Participation will be calculated by the successful completion of videos and practice coding done prior to class as well as being present and engaged during the in class portion.</p>
<p>With the class meeting once a week it is crucial that all students attend. Any student who needs to miss a class must inform the instructor by 9 am the morning of the class. Unexcused absences will result in a 5% reduction in overall course grade.</p>
</div>
<div id="pre-class-assignments" class="section level3">
<h3>Pre-Class Assignments</h3>
<p>At the end of the videos each week a preview of the in class lab will need to be completed. This will ensure that all students are prepared to work on the material in the lab. Once this assignment is turned in, each student will be required to peer review code of a number of other students. Code will be graded and commented on based on criteria given out in class. Each students grade will be a combination of there own work as well as their peer reviewing of other students code.</p>
</div>
<div id="in-class-project" class="section level3">
<h3>In-Class Project</h3>
<p>Projects will be a culmination of in class labs with some extra parameters associated with them. Most of the work on Projects will be done in groups</p>
</div>
<div id="r-package" class="section level3">
<h3>R Package</h3>
<p>Another useful skill with R is to take methods, data or other user created tools and turn them into a package. Students will work in groups to create an R Package as directed by the instructor.</p>
</div>
<div id="shiny-app" class="section level3">
<h3>Shiny App</h3>
<p>An important part of statistics is the visualization and representation of data. Students will be expected to code and build their own Shiny Apps. You will also create a video presentation for your app, displaying the use for all in the class.</p>

</div>
</div>
</div>
<div id="semester-hours" class="section level1">
<h1>Semester Hours</h1>
<p>Over the course of the semester students will spend at least the amounts of time shown below:</p>
<table style="width:78%;">
<colgroup>
<col width="31%"></col>
<col width="45%"></col>
</colgroup>
<thead>
<tr class="header">
<th align="left">Task</th>
<th align="center">Hours Spent of Task</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Class Time</td>
<td align="center">40</td>
</tr>
<tr class="even">
<td align="left">Online Content</td>
<td align="center">90</td>
</tr>
<tr class="odd">
<td align="left">Weekly Assignments</td>
<td align="center">15</td>
</tr>
<tr class="even">
<td align="left">R Package</td>
<td align="center">15</td>
</tr>
<tr class="odd">
<td align="left">Shiny App</td>
<td align="center">30</td>
</tr>
<tr class="even">
<td align="left">Total</td>
<td align="center">190</td>
</tr>
</tbody>
</table>
</div>
<div id="class-schedule" class="section level1">
<h1>Class Schedule</h1>
<p>Important: Flipped material and readings are subject to change, contingent on mitigating circumstances and the progress we make as a class.</p>
<div id="week-00-0902---0906-no-class-first-class-will-be-september-11th" class="section level2">
<h2>Week 00, 09/02 - 09/06: NO CLASS: First Class will be September 11th</h2>
<ul>
<li><strong>NO CLASS</strong></li>
<li>You are expected to complete work before the first class.</li>
<li>Familiarize yourself with:
<ul>
<li><a href="http://www.php2560.com/">Course Website</a></li>
<li><a href="https://www.github.com/">Github</a></li>
<li><a href="https://www.rstudio.com">RStudio</a></li>
</ul></li>
</ul>
</div>
<div id="week-01-0909---0913-syllabus-getting-started-github" class="section level2">
<h2>Week 01, 09/09 - 09/13: Syllabus / Getting Started / Github</h2>
<ul>
<li><em>First Day of Class</em></li>
<li>Go over syllabus</li>
<li>Learn about flipped course.</li>
<li>Learn Basics of R and RMarkdown</li>
<li>Basic Data Retrieval and tracking Code</li>
</ul>
</div>
<div id="week-02-0916---0920-r-basics-and-data-types-working-with-dplyr-and-tidyr" class="section level2">
<h2>Week 02, 09/16 - 09/20: R Basics and Data Types / Working with Dplyr and Tidyr</h2>
<ul>
<li>Vectors, Matrices, Arrays, Lists and Dataframes.</li>
<li><em>Required Reading</em>:
<ul>
<li>Matloff Chap 1-5</li>
<li>Jones Chap 1-2</li>
<li>Teetor Chap 7</li>
<li>Rizzo Chap 1</li>
</ul></li>
<li>Cleaning Data with Dplyr and Tidyr.</li>
<li><em>Required Readings</em>:
<ul>
<li><a href="http://statseducation.com/Introduction-to-R/modules/tidy%20data/tidy-data/">tidyr and dplyr from Stats Education</a></li>
<li><a href="http://r4ds.had.co.nz/wrangle-intro.html">Chapters 9-16 in R for Data Science (short chapters)</a></li>
</ul></li>
</ul>
</div>
<div id="week-03-0923---0927-graphics-in-r" class="section level2">
<h2>Week 03, 09/23 - 09/27: Graphics in R</h2>
<ul>
<li><code>ggplot2</code> in R</li>
<li><em>Required Readings</em>:
<ul>
<li><a href="http://statseducation.com/Introduction-to-R/modules/graphics/ggplot2/">Graphics from Stats Education</a></li>
</ul></li>
</ul>
</div>
<div id="week-04-0930---1004-controlling-the-flow" class="section level2">
<h2>Week 04, 09/30 - 10/04: Controlling the Flow</h2>
<ul>
<li>Basics of Logic</li>
<li>Loops and other Controls.</li>
<li><em>Required Reading</em>:
<ul>
<li>Matloff Chap 7</li>
<li>Jones Chap 5</li>
</ul></li>
</ul>
</div>
<div id="week-64-1123---1127-functions-in-r" class="section level2">
<h2>Week 64, 11/23 - 11/27: Functions in R</h2>
<ul>
<li>Writing and Debugging Functions in R</li>
<li><em>Required Reading</em>:
<ul>
<li>Matloff Chap 12-14</li>
<li>Rizzo Chap 4</li>
<li>Jones Chap 7-9</li>
<li>Teetor Chap 13</li>
</ul></li>
</ul>
</div>
<div id="week-06-1014---1018-functions-in-r-part-2" class="section level2">
<h2>Week 06, 10/14 - 10/18: Functions in R: Part 2</h2>
<ul>
<li>Writing and Debugging Functions in R</li>
<li><em>Required Reading</em>:
<ul>
<li>Matloff Chap 12-14</li>
<li>Rizzo Chap 4</li>
<li>Jones Chap 7-9</li>
<li>Teetor Chap 13</li>
</ul></li>
</ul>
</div>
<div id="week-07-1021---1025-writing-efficient-r-code" class="section level2">
<h2>Week 07, 10/21 - 10/25: Writing Efficient R Code</h2>
<ul>
<li>Working on more Efficient Coding</li>
<li><em>Require Reading</em>:
<ul>
<li><a href="https://adv-r.hadley.nz/perf-measure.html">Advanced R Chapter 23</a></li>
<li><a href="https://adv-r.hadley.nz/perf-improve.html">Advanced R Chapter 24</a></li>
</ul></li>
</ul>
</div>
<div id="week-08-1028---1101-sql" class="section level2">
<h2>Week 08, 10/28 - 11/01: SQL</h2>
<ul>
<li>Basic SQL Commands.</li>
<li>Accessing MySQL on a server.</li>
<li><em>Required Readings</em>:
<ul>
<li>Datacamp work Only</li>
</ul></li>
</ul>
</div>
<div id="week-09-1104---1108-text-mining-in-r" class="section level2">
<h2>Week 09, 11/04 - 11/08: Text Mining in R</h2>
<ul>
<li>tidytext</li>
<li>Text mining in R.</li>
<li>Sentiment Analysis</li>
<li><em>Required Readings</em>:
<ul>
<li><a href="http://tidytextmining.com/">Text Mining with R</a></li>
</ul></li>
</ul>
</div>
<div id="week-10-1111---1115-webscraping-in-r" class="section level2">
<h2>Week 10, 11/11 - 11/15: Webscraping in R</h2>
<ul>
<li>Webscraping in R</li>
<li><em>Required Readings</em>:
<ul>
<li>TBD</li>
</ul></li>
</ul>
</div>
<div id="week-11-1118---1122-thanksgiving-break" class="section level2">
<h2>Week 11, 11/18 - 11/22: Thanksgiving Break</h2>
<p><em>No Classes - Thanksgiving Break</em></p>
</div>
<div id="week-12-1125---1129-package-building-in-r" class="section level2">
<h2>Week 12, 11/25 - 11/29: Package Building in R</h2>
<ul>
<li>Creating packages in R</li>
<li><em>Required Readings</em>:
<ul>
<li><a href="http://r-pkgs.had.co.nz/">R Packages</a></li>
</ul></li>
</ul>
</div>
<div id="week-13-1202---1206-shiny-apps" class="section level2">
<h2>Week 13, 12/02 - 12/06: Shiny Apps</h2>
<ul>
<li>Developing a Shiny App in R</li>
<li><em>Required Readings</em>:
<ul>
<li>TBD</li>
</ul></li>
</ul>
</div>
<div id="week-14-1209---1213-shiny-apps-continued" class="section level2">
<h2>Week 14, 12/09 - 12/13: Shiny Apps Continued</h2>
<ul>
<li>Creating packages in R</li>
<li><em>Required Readings</em>:
<ul>
<li>TBD</li>
</ul></li>
</ul>

</div>
</div>
<div id="brown-undergraduate-competencies" class="section level1">
<h1>Brown Undergraduate Competencies</h1>
<div id="primary-competencies" class="section level2">
<h2>Primary Competencies</h2>
<ol style="list-style-type: decimal">
<li>Be familiar with high speed and high throughput computing.</li>
<li>Apply Computationally intensive statistical methods (e.g., iterative methods, optimization, resampling, and simulation/Monte Carlo methods)</li>
</ol>
</div>
<div id="refresher-competencies" class="section level2">
<h2>Refresher Competencies</h2>
<ol style="list-style-type: decimal">
<li>Be able to manipulate data (possibly “big”) using software in a well-documented and reproducible way.</li>
<li>Apply basic programming concepts (e.g., breaking a problem into modular pieces, algorithmic thinking, structured programming, debugging, and efficiency)</li>
<li>Be able to use of one or more professional statistical software environment</li>
</ol>
</div>
</div>
<div id="brown-scmam-competencies" class="section level1">
<h1>Brown ScM/AM Competencies</h1>
<div id="primary-competencies-1" class="section level2">
<h2>Primary Competencies</h2>
<ol style="list-style-type: decimal">
<li>Identify and implement statistical techniques and models for analysis of data.</li>
<li>Attain proficiency in management, documentation of study data for use in practical statistical analysis.</li>
</ol>
</div>
<div id="refresher-competencies-1" class="section level2">
<h2>Refresher Competencies</h2>
<ol style="list-style-type: decimal">
<li>Acquire knowledge and skills in research methodologies to collaborate with substantive investigators<br />
</li>
<li>Apply programming skills to analyze data and develop simulation studies</li>
<li>Develop proficiency in making oral, written and poster presentations of work to statistical and non-statistical colleagues</li>
</ol>
</div>
</div>
<div id="brown-phd-competencies" class="section level1">
<h1>Brown PhD Competencies</h1>
<div id="refreshed-competencies" class="section level2">
<h2>Refreshed Competencies</h2>
<ol style="list-style-type: decimal">
<li>Identify and implement advanced statistical models for the purposes of estimation, comparison, prediction, and adjustment in non-standard settings.</li>
<li>Apply programming skills to analyze data and develop simulation studies.</li>
<li>Develop proficiency in making oral, written and poster presentations of work to statistical and non-statistical colleagues</li>
<li>Generate original computer code for new statistical techniques</li>
<li>Determine the statistical properties of new methods using mathematical and computer tools</li>
</ol>
</div>
</div>
<div id="students-with-special-needs" class="section level1">
<h1>Students with Special Needs</h1>
<p>Brown University is committed to full inclusion of all students. Students who, by nature of a documented disability, require academic accommodations should contact the professor during office hours. Students may also speak with Student and Employee Accessibility Services at 401-863-9588 to discuss the process for requesting accommodations.</p>
</div>
<div id="diversity-statement" class="section level1">
<h1>Diversity Statement</h1>
<p>This course is designed to support an inclusive learning environment where diverse perspectives are recognized, respected and seen as a source of strength. It is our intent to provide materials and activities that are respectful of various levels of diversity: mathematical background, previous computing skills, gender, sexuality, disability, age, socioeconomic status, ethnicity, race, and culture.</p>
</div>
<div id="english-language-learners" class="section level1">
<h1>English Language Learners</h1>
<p>Brown University welcomes students from around the world, and the unique perspectives international students bring enrich the campus community. To empower students whose first language is not English, an array of ELL support is available on campus including language and culture workshops and individual appointments. For more information about English Language Learning at Brown, contact the ELL Specialists at <a href="mailto:ellwriting@brown.edu">ellwriting@brown.edu</a>.</p>
</div>




</div>
<script>

// add bootstrap table styles to pandoc tables
function bootstrapStylePandocTables() {
  $('tr.header').parent('thead').parent('table').addClass('table table-condensed');
}
$(document).ready(function () {
  bootstrapStylePandocTables();
});


</script>

<!-- dynamically load mathjax for compatibility with self-contained -->
<script>
  (function () {
    var script = document.createElement("script");
    script.type = "text/javascript";
    script.src  = "https://mathjax.rstudio.com/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML";
    document.getElementsByTagName("head")[0].appendChild(script);
  })();
</script>

</body>
