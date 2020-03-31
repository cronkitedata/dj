---
title: "11 - Scraping web sites"
layout: single
excerpt: "Getting data off of the Web can be easy or hard. You won't know until you try. This week we'll go through strategies and concepts of data on the Web."
collection: weeks
class_date: 2020-03-31
publish: true
---
{{page.class_date | date: "%A, %B %-d"}}


## Deadlines

Note that the optional draft story memo has been pushed back a week, to April 12.


## In class

Both Tuesday and Thursday will be devoted to scraping data from the web and from PDF's. "Scraping" is a weird word, in that it means something different to different people. Some consider it just getting data off the internet; others consider it pulling out structure from unstructured documents like PDFs. We'll just use the second definition in order to put them all together.

* Demo of getting data from PDF's.

   * Tutorial on "[Dealing with PDF's](https://cronkitedata.github.io/cronkite-docs/special/cleanup_pdf.html) - this is just something you can look at in the future for reference.
   * Demo of  [Tabula](https://tabula.technology/)
   * Demo of [Able2Extract](https://www.investintech.com/prod_a2e.htm#convert) ($150 for a lifetime license, $35 for a month)
   * Demo of the full Adobe Acrobat product, which comes with your Creative Cloud package, but is pretty expensive if you get it when you're done with school.
   * Example data: A printout from Phoenix PD with COVID-19 public gathering complaints

* Introduction to scraping data from the web
  * Understanding GET requests
  * Looking under the hood
  * Tricking websites into giving you more :
      * Overriding page limits (need a good example)
      * Is the data already there?? (It might be in the source, just not showing up - Maricipa County mugshots.  "Sources" is different than the "Elements" - "Source" is the raw HTML that is rendered before any javascript changes it - inspection is what's actually what you see after javascript.
  * A JSON miracle :
      * [A simple page example](https://cronkitedata.github.io/cronkite-docs/assets/docs/simple-page.html)
  * Scraping using the structure of the page
      * The DOM and XPATH as a way to unnest a page
      * Testing it out on Chrome scraper on a simple table
      * Trying something a little more complicated
      * Where to go from here.


(We'll get as far as we can each day on these - they're quick overviews, not intended for you to master them, but with enough detail so you understand what is, and isn't, easy.)


## Thursday, April 2

**Guest speaker**: Guest speaker, Rob O'Dell, Arizona Republic investigative reporter, and a member of the team that just won the Goldsmith Award for "Copy, Paste, Legislate."  He'll talk about this story and technology they used behind it.


## Preparation for class

### Reading

For Thursday: "[Copy, Paste, Legislate](https://www.usatoday.com/in-depth/news/investigations/2019/04/03/abortion-gun-laws-stand-your-ground-model-bills-conservatives-liberal-corporate-influence-lobbyists/3162173002/)" main story, by a team from USA Today, the Arizona Republic and the Center for Public Integrity


### Materials for after class
