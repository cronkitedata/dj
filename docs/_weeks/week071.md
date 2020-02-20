---
title: "7.1 Merging in R"
layout: single
excerpt: "A key advantage of data programs like R is the ability to merge to data tables together. You'll see how here."
collection: weeks
class_date: 2020-02-25
publish: true
---
{{page.class_date | date: "%A, %B %-d"}}


## In class

* Joining in R
* Calculating new information from old in R

If there's time, I'll introduce you to your dataset choices for the memo project, and we'll go over some details on importing data that doesn't behave well.  If not, we'll do that next week.

**Thursday, Feb. 27: Guest speaker, Pamela Ren Larsen of The Arizona Republic.** Be sure to do the reading of her work below so you can ask good questions. We'll also spend some time reviewing what we've done so far. She'll join the morning class at 9 and the afternoon class at 4. 

## Due this week

Lab from last week on the Murder Accountability Project filtering and grouping. You can work together on it, but everyone should upload your own version's knitted document.


## Preparation

### Skills

* Review the work we did last week in class, and prepare questions. You should practice on any of the datasets we've used in class so far, trying to come up with your own questions. You don't need to turn anything in, but I'll be asking for your examples in class.
* Review the [R study guide chapter on "mutate"](https://cronkitedata.github.io/rstudyguide/035-mutate.html) . After this, there's only one more verb!



### Reading (for Thursday)

* "[Where will the next deadly fire strike?](https://www.azcentral.com/in-depth/news/local/arizona-wildfires/2019/07/22/wildfire-risks-more-than-500-spots-have-greater-hazard-than-paradise/1434502001/)" by Dennis Wagner and Pamela Ren Larson, Arizona Republic, July 28, 2019.
* "[Digging into the Purple Vote](https://www.azcentral.com/story/news/politics/arizona/2018/11/13/maricopa-county-areas-split-tickets-kyrsten-sinema-and-doug-ducey/1988877002/)", by Yvonne Wingett Sanchez and Pamela Ren Larson, Arizona Republic, Nov. 14, 2018


#### Going further

Many of the problems that reporters have in joining datasets is that they're trying to merge data that doesn't have a common identifier. Read through
