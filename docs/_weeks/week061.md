---
title: "6 - Replicating your work in Excel with R"
layout: single
excerpt: "Filtering, arranging, grouping and summarising. You've done it all before, just not with the British spelling."
collection: weeks
class_date: 2020-02-18
publish: true
---
{{page.class_date | date: "%A, %B %-d"}}

Beginning this week, I'll start adding additional tutorials and resources at the bottom of each page for people who feel like they'd like to go further than what we'll get to in class. There is absolutely NO expectation that you'll do this.  It's only there if you want it.

## In class

### Tuesday

* Filtering in R: We'll take on the Murder Accountability Project's database <br>[R Data file for download](https://github.com/cronkitedata/rstudyguide/blob/master/data/murder_data.Rda?raw=true) \| [Exercises](https://cronkitedata.github.io/rstudyguide/A04-murders),

Here is a quote from the Serial Killer Detective about the Green River Killer. Let's see if we can build a query that might isolate at least some of those cases:

> Ridgway’s slayings began in 1982, when young runaways and prostitutes began disappearing from state Route 99 in south King County, Washington. He brought many of them to his home and strangled them, then left them in woodsy, remote sites. The first few bodies turned up along the now-notorious Green River.<br><br>Ridgway told investigators he killed as many as 75-80 women along Route 99 in south King County, Washington. He was convicted and received multiple life sentences.

(I decided the NEA data wasn't a good fit for today's work.)

### Thursday

* Grouping and summarising in R: More with the Murder Accountability Project data.

## Due this week

* Sunday, Feb. 16: Nothing except the lab. Take this time to carefully go through all of the material in R until you're comfortable with it.  If you have a "eureka!" moment, post it to Slack in the new #wins channel. If you need help, post it in #sos using the principles of asking good questions.

* Sunday, Feb. 23: Finish your lab work and upload it. You can work on it together if you want, but everyone should have their own document and it should have a list of names of people who contributed to it outside of class. 

## Preparation

### Skills

Try to follow along with the examples in the chapters, but you don't have to do the exercises unless they're assigned. We'll work on the murder data from the filtering chapter in class. (I will post the data for the vaccinations and show you how to load it into R by Friday.)

* [R Study Guide](https://cronkitedata.github.io/rstudyguide/030-intro-verbs) chapters 5.1-5.3:
  * A quick tour of verbs
  * Verbs Part 1: Picking and choosing (for Tuesday)
  * Verbs Part 2: group_by and summarise (for Thursday)


### Reading

* "[Pharmacies miss half of dangerous drug combinations](https://www.chicagotribune.com/investigations/ct-drug-interactions-pharmacy-met-20161214-story.html)", Chicago Tribune, Dec. 15, 2016, by Sam Roe and Karisa King.

#### Going further

R had powerful ways to work with text using `regular expressions`. To get a handle on what regular expressions can do, [go through the tutorial on our resources site]({{site.cdocs}}/special/regex-beginning). It's not in R, but it will translate directly into filtering in R using the [str_detect()](https://cran.r-project.org/web/packages/stringr/vignettes/stringr.html) function.  
