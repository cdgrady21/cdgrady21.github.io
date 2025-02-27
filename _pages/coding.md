---
layout: archive
permalink: /coding/
title: "Learning to Code"
author_profile: true
---

Many colleagues have asked me about resources for learning R, Python, and causal inference statistics. I'm not expert enough in Python to recommend good learning resources, but here I've recommended my favorite resources for learning the basics of R, how to use R for particular tasks, and for learning the basics of causal inference.

These are all free, online resources. They give you code that you can easily copy & paste into your R console, which allows you to play around with R and learn by doing. To keep the list manageable, I've limited it to one resource for learning the basics of R, five resources for learning how to use R for specific tasks, and one resource for causal inference in R.

If you are brand new to coding, I recommend starting with the first resource (Hands-On Programming with R) and then selecting other options based on your learning interests.

&nbsp;

********
# Learning R

[Hands-On Programming with R](https://rstudio-education.github.io/hopr/)

This book will teach you the basics of programming in R. It is written it for non-programmers and provides a friendly introduction to the R language. Throughout the book, you’ll use your newfound skills to solve practical data science problems. Start here.

&nbsp;

# Specific tasks in R

**Data science**: [R for Data Science](https://r4ds.hadley.nz)

This online book will walk you through everything you need to get started using R for data science. It is comprehensive and will provide you with a solid foundation for learning to do other tasks in R. This is a good place to start if you have some prior experience with R.


**Machine learning**: [Basics of Statistical Learning](https://statisticallearning.org/index.html)

This online version of a stats course at the University of Illinois provides "a broad introduction to machine learning from the perspective of a statistician who uses R and emphasizes practice over theory". Good for people with a basic understanding of R and Regression.


**Distributed computing**: [Mastering Spark with R](https://therinspark.com/intro.html)

This excellent online textbook will teach you how to analyze "big data" using R.  It assumes no prior knowledge of R or of distributed computing.


**Data visualizations**: [R Graphics Cookbook](https://r-graphics.org/)

This is "a practical guide that provides more than 150 recipes to help you generate high-quality graphs quickly, without having to comb through all the details of R’s graphing systems."


**Web applications**: [Mastering Shiny](https://mastering-shiny.org/)

"This book is designed to take you from knowing nothing about Shiny to being an expert developer who can write large complex apps that are still maintainable and performant. You’ll gain a deep understanding of the reactive programming model that underlies Shiny, as well as building a tool box of useful techniques to solve common app challenges."

&nbsp;

# Causal Inference in R

[Causal Inference: The Mixtape](https://mixtape.scunning.com/) 

This excellent book "introduces students and practitioners to the methods necessary to arrive at meaningful answers to the questions of causation, using a range of modeling techniques and coding instructions for both the R and the Stata programming languages."  Go here to learn about matching, difference-in-differences, regression discontinuity, synthetic controls, and more.

# Bonus: General coding assistance

[Cursor](https://www.cursor.com/en)

There are many good AI tools for coding assistance. I recommend Cursor. It provides a text editor where you can write your code, and a built in AI chat window that can see the code in the text editor, recommend improvements, and even copy the improvements directly into the text editor. It also allows you to select from several AI language models.



Good luck!


<!--

**Applied Statistics**: [Applied Statistics with R](https://book.stat420.org/)

This book serves as an introduction to statistics in R and an introduction to the R programming language. It was designed for use with STAT 420, Methods of Applied Statistics, at the University of Illinois Urbana-Champaign. It is a good place to start if you have some prior experience with statitsics.

**Causal inference**: [Causal Inference for The Brave and True](https://matheusfacure.github.io/python-causality-handbook/landing-page.html)

This book describes itself as "A light-hearted yet rigorous approach to learning impact estimation and sensitivity analysis. Everything in Python and with as many memes as I could find."  I fully endorse that description. It is somewhat similar to the Causal Inference Mixtape, but with two major differences: (1) the coding examples are in Python, and (2) it's second part also goes into some predictive modeling and machine learning applications.
-->

<!--
Dave Dalpiaz website (and not already here): https://daviddalpiaz.org/
- [Atomic R](https://book.stat385.org/)
- [R Coding Basics](https://www.gastonsanchez.com/R-coding-basics/)
- [Deep R Programming](https://deepr.gagolewski.com/)
- [R Packages](https://r-pkgs.org/)
- [R Markdown](https://bookdown.org/yihui/rmarkdown/)
- [Github](https://happygitwithr.com/)
- [Stat 545, Data Wrangling](https://stat545.com/)
- [Efficient R Programming](https://csgillespie.github.io/efficientR/)
- [What they forgot to teach you about R](https://rstats.wtf/)
- [The R Inferno](https://www.burns-stat.com/documents/books/the-r-inferno/)
- [The R Manuals](https://rstudio.github.io/r-manuals/)
- [Posit Cheatsheets](https://posit.co/resources/cheatsheets/)



https://cares.gse.harvard.edu/
- [Designing Monte Carlo Simulations in R](https://jepusto.github.io/Designing-Simulations-in-R/)
- [Matching Guide](https://cares-blog.gse.harvard.edu/post/matching-guide-pt-1/)

- SPARK with R and Python
https://therinspark.com/intro.html
	- CERN example: https://db-blog.web.cern.ch/blog/luca-canali/2017-08-apache-spark-and-cern-open-data-example
	- Big data in R paper: https://www.econstor.eu/handle/10419/214153
https://www.reddit.com/r/dataengineering/comments/1cmmuux/best_way_to_learn_apache_spark_in_2024/
- https://github.com/DataTalksClub/data-engineering-zoomcamp/tree/main/05-batch
https://cognitiveclass.ai/courses/analyzing-big-data-in-r-using-apache-spark
https://www.altexsoft.com/blog/apache-spark-pros-cons/

- Rshiny
https://shiny.posit.co/r/getstarted/shiny-basics/lesson1/
https://mastering-shiny.org/

- Data Viz
https://ggplot2.tidyverse.org/
- https://r-graphics.org/

- Statistical Learning
https://statisticallearning.org/index.html
https://faculty.washington.edu/otoomet/machinelearning-R/ (skip to ch.10, probably)

- Structural modeling
https://sites.google.com/site/andrewjohnstoneconomics/my-advice/structural-for-beginners
https://bookdown.org/bean_jerry/using_r_for_social_work_research/structural-equation-modeling.html
https://rpubs.com/Agrele/SEM
https://stats.oarc.ucla.edu/r/seminars/rsem/
https://www.reddit.com/r/academiceconomics/comments/uqfovo/can_anyone_explain_what_exactly_is_meant_by/
- https://people.sabanciuniv.edu/atilgan/FE500_Fall2013/2Nov2013_CevdetAkcay/LucasCritique_1976.pdf
- https://editorialexpress.com/jrust/econ615/readings/keane_article_je.pdf
https://www.aeaweb.org/articles?id=10.1257/jep.31.2.33


- Basic R tutorials
https://r4ds.hadley.nz (see ch.24 on web scraping)

- Advanced R
http://adv-r.had.co.nz/

- Python
https://www.codecademy.com/learn/learn-python-3


OCTAVE from coursera (Andrew Ng)
Game Theory with Scott Page
NLP
Calculus
Matrix Algebra


**From methods materials documnet**
Statistics & Programming Textbook
-	[Statistical Modeling: A Fresh Approach](https://dtkaplan.github.io/SM2-bookdown/) # fantastic but kind of dated.
-	[Research Methods Knowledge Base](https://conjointly.com/kb/)

Stats & Programming Resources
-	Regex cheatsheet (here, here)
-	Extreme Bounds analysis in R
-	Which Bootstrap When

Field Experiments
-	EGAP Learning Days: Theory and Practice of Field Experiments
-	OES Methods Guides

Quasi-experimental
-	Causal Inference for the Brave and True
-	Causal Inference Mixtape
-	DiD
-	Medium
-	Generalized DiD article
-	DiD AnnRev
-	Simple: DIME diff-in-diff
-	Pischke diff-in-diff
-	OES Quasi-experimental designs
-	Causality, Applications, and Research in Education and Statistics (C.A.R.E.S. Lab)
-	Ex: Matching Guide

Qualitative research
-	Best guide: Seawright and Gerring 2008: case selection: a menu of qualitative and quantitative options
-	Good blog summary of most similar & most different
-	Old classics
-	Collier 1991, 1993
-	Lijphart 1971
-	Process-tracing
-	Beach and Pedersen 2012 Guide
-	Bennet 2012 practitioner guide
-	Collier 2011 - Understanding Process Tracing
-	Ricks and Liu 5 page guide

General
-	https://www.povertyactionlab.org/sites/default/files/research-resources/2016.08.31-Impact-Evaluation-Methods.pdf



-->
