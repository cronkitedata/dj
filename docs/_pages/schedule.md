---
layout: single
sidebar:
  nav: docs
title: "Preliminary schedule"
permalink: /schedule
classes: wide
---

<style type="text/css">
table {
  border-collapse: collapse;
  font-size: .75em;
}
th, tr {
  border-top:1px solid #c6cbd1;
}
th:nth-of-type(1) {
  width: 10%;
}
th:nth-of-type(2) {
  width: 20%;
}
th:nth-of-type(3) {
  width: 35%;
}
th:nth-of-type(4) {
  width: 35%;
}
tbody tr:nth-of-type(odd){
  background-color: whitesmoke;
}
tbody tr:nth-of-type(odd) td {
  border-top: 1px solid lightgrey;
}
</style>


Here is a preliminary schedule with key deadlines. You will usually have something due every week beyond these bigger assignments, either as a lab or as homework. Be sure to check the detail page of each week for specifics. Everything is shown in the week that it's due, with the week beginning on Tuesday.

Try not to leave your explainer assignment until the last minute. It'll make your final week of class even more difficult than usual, and it's designed so that you can create your explainer any time you find something interesting.

When a deadline is shown for a class day, it means it's due before class starts.

Week<br>num | Date| Topics | Deadlines
--- | ----------- | ---- | ---
01 | [Jan. 14]({{ "weeks/week011" | relative_url}}) | Intros & overview; Excel reboot; | Tu: Survey
 | [Jan. 16]({{ "weeks/week012" | relative_url}}) | Ethics and data diaries; data types |
02 | Jan. 21  | Excel filter & sort |  Tu: Academic integrity pledge
 | Jan. 23 | Pivot tables |
03 | Jan. 28 | Understanding tidy data; review |
  | Jan. 30 | Excel review |
04 | Feb. 4 | **Excel exam** |
 | Feb. 6 | Cleaning data with Open Refine | Su. Feb. 9: 1st self-assessment
05 | Feb. 11 | Intro to R markdown & programming |
  | Feb. 13 | R for journalists: the tidyverse and its verbs |
06 | Feb. 18 | Replicating your Excel work in R: Filter and sort |
  | Feb. 20 | Replicating con't: Group by & mutate |
07 | Feb. 25 | Joining in R |
 | Feb. 27 | Introducing your project datasets; importing details |
08 | Mar. 3 | Basic charts in R ;  |
  | Mar. 5 | Explore your project dataset |
 | Mar. 10 | ****SPRING BREAK****  |
09 | Mar. 17 | R Review |
  | Mar. 19 | **R exam** | Su 3/22: 2nd self-assessment
10 | Mar. 24-26 | Visualization as a reporting tool | Su 3/29: Optional [Story memo draft]({{ "story-memo" | relative_url }}) draft
11 | Mar. 31-Apr. 2 | Open source investigations | Su 4/5: [Story memo]({{"story-memo" | relative_url }})
12 | Apr. 7-9  |  Building your own dataset; the data walk |  Su Apr 12: Data walk
13 | Apr. 14-16 | Scraping & API's ; a data hunt workshop |
14 | Apr. 21-23 | Students' choice | Su Apr 16: Dataset idea
15 | Apr. 28-30 | Wrap up & where to go from here  | Thu: Final self-assessment

**The explainer assignment is in lieu of a final exam and is due when your final exam would end. The specific date and time will be on the Canvas assignment**
{: .notice--info}

## [01- August 16]({{site.baseurl}}/weeks/week011)
* Introductions - you and me
* Review of syllabus
* {: .bluetext} Lecture: Overview of data reporting
* Excel refresher
*

## [02 - August 21]({{site.baseurl}}/weeks/02-excel-review)
* Quick reading exercise
* Excel math review and documentation assignment
* Thursday: Guest speaker Agnel Philip, Arizona Republic

## [03 - August 28]({{site.baseurl}}/weeks/03-excel-practice)
* Quick reading exercise
* Additional Excel practice with population data that's a little harder
* *Thursday*: What is tidy data and why do we care?

## [04 - September 4]({{site.baseurl}}/weeks/04-excel-pivot-tables)
* Quick reading exercise
* Grouping / pivot table assignment
* *Thursday*: Guest speaker: Allison McCann, Vice / HBO
* *Graduate students' story recommendation and review due Friday 5pm.*

## [05 - September 11]({{site.baseurl}}/weeks/05-excel-build)
* Excel review and
* *Thursday*: ~~Assign teams for public records project; Guest speaker Sandhya Kambhampati, ProPublica Illinois~~ Going further with Excel: Lookup, date math (not on exam)

## [06 - September 18]({{site.baseurl}}/weeks/06-excel-exam)
* **Excel exam** You'll start the exam in class and have 24 hours to complete it. Any technical or clarification questions you have must be asked in class in front of the rest of the group. You can leave whenever you want, but I won't respond to any questions until after the deadline.
* *Thursday*: Public records workshop; assign teams and start research. Details are on the [data negotiation project page]({{site.baseurl}}/data-negotiation)

## [07- September 25]({{site.baseurl}}/weeks/07-formats-public-records)
* Quick demo of data formats (xml, json, csv and cousins)
* Public records sprint both days. There may be some phone calls required between Tuesday and Thursday. First memo due Thursday.

## [08 - October 2]({{site.baseurl}}/08-pdfs)
* [Dealing with PDFs and other bad formats]({{site.baseurl}}/tutorials/xl-pdf-convert); converting reports to data (demo)

*Thursday*: Public records workshop: Assign a team member to make the informal request. We'll have two weeks for follow up. Second memo due.

*Grad students'* [story critique]({{site.baseurl}}/assignments/02-MCO510-story-assignment) is due Friday at 5pm.

## 09 - October 11 (fall break Oct. 9)
* ~~Cleaning data with OpenRefine~~
* NEW!! SPJ & Google News Initiative training. Sign up and see details here: https://www.spj.org/election18-phoenix.asp.

## [10 - October 16]({{site.baseurl}}/weeks/10-scrape-simple)
* Finding hidden data in websites.
* ~~In-class exercise on finding hidden data instead of cleaning exam~~
* *Thursday*: Public records workshop : Public records memo & request due

## [11 - October 23]({{site.baseurl}}/weeks/11-r-intro)
* Beyond Excel - Beginning programming with R
* *Thursday*: Data analysis project: First ideas for dataset.

## [12 October 30]({{site.baseurl}}/weeks/12-r-dplyr)
*Tuesday*
* Importing into R
* Filters and ~~group by~~ selects in R
* ~~Joining in R~~
* *Thursday*
* Guest: Prof. Marianne Barrett, on literature reviews
* Continue with Wrangling in R

* ~~[begin work on project]({{site.baseurl}}/assignments/08-story-memo-project)~~

## 13 - November 6
* Due Nov 5: [Your proposal for the story memo project dataset]({{site.baseurl}}/assignments/08-story-memo-project).
*Tuesday*
Election day. We'll go over your story proposals and get started on the project in class as a workshop.
*Thursday*
Some people are getting very frustrated with R, and I think part of it is that you don't see the point -- we're doing things you could have done in Excel. I want to give you some motivation for learning it with some examples of what it can do, esp. in exploratory visualization.


## [14 - November 13]({{site.baseurl}}/weeks/14-vis-r):
* Due Friday, Nov 16: [First draft - option 1]({{site.baseurl}}/assignments/08-story-memo-project)
* Making maps in R? We may not get to this.
* Visualization in R and options for other tools
* Get to next step on the data analysis project. We'll talk about what a first draft would look like for each of your projects.
* *Thursday*:  Two additional skills in R - data cleaning and basic charts.

## 15 - November 20
* Finish your **R walkthrough** instead of R exam
* Thursday: *Thanksgiving*

## 16 - November 26
* Due Nov. 25: [First or second draft]({{site.baseurl}}/assignments/08-story-memo-project).
* Data analysis lab.
* Thursday: Where to go from here?

## December 4
Data analysis project due instead of final exam
