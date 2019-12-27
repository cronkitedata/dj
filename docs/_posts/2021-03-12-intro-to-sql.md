---
layout: post
permalink: /weeks/week091/
title: "Week 9: Intro to SQL"
categories: weeks
---

Structured Query Language, or SQL, is commonly used to hold and query large, structured datasets. Instead of a single worksheet, a relational database system contains tables that are linked together.
We'll learn how to link those tables together later, but for now we're going to walk through a simple set of queries on a single table to learn the power and simplicity of SQL syntax.

Reporters use sql-based databases to:
* Query larger datasets that don't fit comfortably in Excel
* Find tips for further reporting, such as old, forgotten bridges or campaign contributors.
* Merge datasets based on common fields (columns)
* Extract data for further analysis in Excel

... and many other uses.

When you move from spreadsheets to databases, the language changes a little. A filter is called a **query**; a row is called a **record** and a column is called a **field**. You can't mix data types within a field -- if it's a number, it must always be a number or blank.

NOTE: I moved the filtering tips to the [SQL guide](../../sql-guide/)

### data.world
If you haven't signed up already, please sign up for data.world now using your ASU email address.

Create a project called "practice data".  
We're going to walk through data.world's SQL tutorial, with some adjustments to make it even more powerful:

[https://docs.data.world/documentation/sql/concepts/basic/intro.html](https://docs.data.world/documentation/sql/concepts/basic/intro.html)

1. Add the datasets to your project.
2. Write your queries.
3. When a query works, copy and paste it into a text file, Google doc or Word doc, ending each one with a semicolon.  Keep adding interesting queries to your document. This will later become your data diary.

Use the [sql guide](../../assets/docs/sql-guide) to remind yourself of the syntax.

### For Wednesday, March 14

Practice your sql using the [swimming pool inspection](../../assets/xlexamples/swimmingpool_inspections_mces.xlsx) data we looked at in Excel. You can use the copy of it in our file.
