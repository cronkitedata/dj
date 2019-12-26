---
layout: single
title: "Week 12 - From Excel to R"
date: 2018-10-12
toc: true
sidebar:
   nav: docs
collection: weeks
---

This week we'll work on doing some of the tasks we did in Excel -- reading in data, filtering and grouping. If there's time, we're going to add joining -- something that you found difficult using VLOOKUP in our Excel work.

This all relies on the *tidyverse*, which is a way to reduce the confusing syntax of R and to mimic standard languages like SQL.

## Skills work

You should go through two chapters of the learn-r textbook:
* [Importing / Exporting Data](https://learn.r-journalism.com/en/importing_exporting/). I can't get the paste from the Hamilton broadway stats page to work and it's not really worth fiddling with. You know how to get it into a csv using Scrape Similar. Also don't worry about doing the folder bulk import. Just know it's there for when you need it.
* [Wrangling Data] [https://learn.r-journalism.com/en/wrangling/](https://learn.r-journalism.com/en/wrangling/), first two sections: "Transforming and analyzing data" and "Tidying and joining data". These are the things that you'll need the most when we get started on your projects.

Be sure to take all of the quizzes at the end of the chapters. If you get stuck, post your question or problem in the #questions Slack channel. I'll try to chime in quickly. But if you're having trouble, the chances are high that others are as well.

## Tuesday
We'll do some exercises that you'll turn in as R scripts, using datasets you've already seen for tasks you've already done in Excel.

* [R Review](https://cronkitedata.github.io/rstats-training/r-review-md) goes over some of the things we did in class on Tuesday

* [Beginning R Wrangling](https://cronkitedata.github.io/rstats-training/r-wrangle). [UPDATED -- YOU DON'T HAVE TO DO THE "On your own", BUT YOU MIGHT WANT TO TRY BEFORE THE EXAM.]

The data is
* The [zipped data from the original tutorial]({{site.baseurl}}/assets/data/SHR76_16.sav.zip) (to begin with)

* [A saved copy of the filtered and selected data](https://github.com/cronkitedata/rstats-training/blob/master/murder_data.Rda?raw=true).

## Reading for Thursday
* [Text analysis of Trump's tweets](http://varianceexplained.org/r/trump-tweets/) and

* [When Algorithms Decide What You Pay, from ProPublica](https://www.propublica.org/article/breaking-the-black-box-when-algorithms-decide-what-you-pay)-- You may have already read these -- they were linked off of Chapter 3 tutorial. [UPDATED LINK]


## Thursday


* Guest lecturer: Prof. Marianne Barrett on the value of a good literature review before you start any analysis, and how to do one.

* More on data wrangling in R on the [weather data from your Excel exam](https://github.com/cronkitedata/rstats-training/blob/master/data/temperatures2017.xlsx?raw=true):

  * [Mutate examples](https://github.com/cronkitedata/rstats-training/blob/master/temps.R). Choose the "raw" button so you can easily copy and paste into an R session.

  *  [Group by and Join examples](https://github.com/cronkitedata/rstats-training/blob/master/group-join.R)

*  ~~Work on  your data analysis / story memo project.~~


## Some tips on how to troubleshoot

### Read the error message

The most common error message will be something like "object ... not found". Pay attention to WHAT isn't found. An object is like a noun, but it's one you supply. Some common reasons that it isn't found:

* You have misspelled the name of a data frame, variable, or something else. They are case-sensitive.
* You skipped a previous step. This is easy to do in R, because once you write the code you can easily forget to run it.
* You haven't closed a parentheses. This is a weird reason to get this error, but R thinks you're continuing along with the previous command. This is hard to get out of. Make  your console active and hit escape enough times to see the little > command prompt. Then try again.
* You haven't loaded a library.
* You've only run part of a statement. In a script in RStudio, selecting part of a command only runs that part. Placing your cursor just above or anywhere within a command runs that whole command, or code chunk.




### Set the right working directory

Another common problem is that you get lost in your directories.

       Mac:
       setwd("~/Documents/")  (if it's in your Documents folder.)

       Windows:
       setwd("C:/Users/YOURID/Documents") (if it's in your My Documents folder.)

You can also set it using the menu item, then copy and paste what the console says when it runs:

![]({{site.baseurl}}/weeks/assets/setwd.gif)
