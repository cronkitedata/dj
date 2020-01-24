---
layout: single
collection: assignments
title: "02 - Sort, filter and group on calls for service"
due_date: 2020-01-26
---

This assignment is due {{page.due_date | date: "%A, %B %-d"}}, based on the sorting, filtering and grouping that we've already done.

[Excel file]({{ site.cdocs}}/assets/data/xlexamples/calls_nov_2019.xlsx) \| [Source](https://www.phoenixopendata.com/dataset/calls-for-service/resource/1d536ee6-7ffb-49c3-bffe-5cdd98a3c97e)

The dataset is one week's worth of calls for service from the Phoenix police department extracted from the dataset published on its [open government site](https://www.phoenixopendata.com/dataset/calls-for-service/resource/1d536ee6-7ffb-49c3-bffe-5cdd98a3c97e). You should be sure to read the description of the data and the record layout before you try to do anything with it.  Don't forget to press "Show More" at the bottom of the page. I extracted just one week of calls and converted the date and time variables to make them a little easier to work with.

Using what you know about sorting, filtering and grouping with pivot tables, answer these questions:

* Which grid has the most calls for service in the city? Look at the community crime map to see where that is, and provide a little characterization of the neighborhood (eg, downtown near ASU or in the northwestern corner of the city.)
* On what days were "shots fired" in Phoenix during Thanksgiving week? Were any of them on Thanksgiving Day?
* What kinds of calls most often result in no action from the police; which kinds most often result in a "departmental report" (which refers to an incident report, or a report of a crime.)
* Look for calls for service on your block or in your neighborhood. You'll have to use a combination of street names and grids.

Now try to ask a few questions on your own -- try to think of things that might lead to a story. You only need to turn in one question (and its answer), but feel free to do more than one.

Finally, think of a question that can't be answered by this dataset.

I don't need a copy of the spreadsheet or the data diary, but keep it on hand in case I have questions.

### Processing notes

The raw data from the open government site was read directly into R, with 2.8 million 911 calls since 2016.

The data is already formatted as a "data table" in Excel.

#### Converting dates

The original date in the file wasn't formatted in a way that automatically converts from text to date/time.  I converted the data type, then filtered for any calls between 11/24 and 11/30 to create the Thanksgiving cut.

Exporting this to Excel created a problem: It converted the calcuated date-time to the UTC time, not Mountain Standard Time. I used a formula to subtract 7 hours to each call date-time to convert it back using the TIME function.

Once I checked the data to make sure the dates and times were accurate in our time zone, I deleted the original text column of the date and time.

The call date is formatted as a day of week with the date.

#### Reference days of week

You don't have a way to know whether the distribution over days of the week is unusual. Here is the the average number of calls by day of week, calculated in R by **grouping** by the day of the week, and **counting** the number of calls and the number of weeks for each day of the week for the full year of 2019. (Please don't ask about why Tuesday has 53 weeks - I don't quite understand it. I just know it happens even though 2019 wasn't a leap year.)

Day | # calls | # weeks | Avg # per week
--- | --- | --- | ---
Sun	92,938	52	1,787
Mon	99,170	52	1,907
Tue	98,977	53	1,867
Wed	97,466	52	1,874
Thu	97,834	52	1,881
Fri	102,271	52	1,967
Sat	98,701	52	1,898

### Grids

Some, but not all, of the calls for service are located in the Phoenix police department's grid system. But it's less useful than you'd think -- if a crime falls on a border, they don't assign a grid. This is really unfortunate for anyone trying to work with this geographically. For example, if a call comes from Central Avenue, it won't be included in a grid.

That said, understanding the grids will will help you if you want to narrow your work to one neighborhood or area using filters or find high-crime areas. I have inquired about getting an electronic copy of the grid map, but for now think of it as a checkerboard overlaid on top of Phoenix.

For reference, the grids are shown online on the crime map at https://communitycrimemap.com . Look on the left side of the screen, expand the "Agency Layers" arrow, and click on the grids. Generally, they are made up of two parts -- two letters, running South to North (generally), and two numbers, running West to East.:

* From West to East they run from 01 through 42. The last one (42) is right up against Scottsdale. Central Ave. is the border between 27 and 28.
* From North to South they're more confusing. Around South Mountain, they start at AB and move north to AC, AD through AJ, then BA through BF, etc. The northernmost grid is in the H's. But going south from around South Mountain, they start at IA, and go UP, to IB, IC, etc.

For reference, ASU's downtown campus is at BB28. That grid runs from Van Buren to Roosevelt and Central Avenue to 7th Street.
