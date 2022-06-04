# EXCEL-Analyze-Survey-Data-pivot

Here we are going to learn how to analyze data from a multiple choice survey or test.

The first thing we typically need to do is transform the data into a layout that is suitable for use with a pivot table.


The exported data is typically in one of two formats:

Format #1: Multiple Columns for Each Choice
The most common is where each choice for the survey question is listed in a separate column.  Each row of the data set contains one person's results, and the corresponding columns contain their answers to the question.

Survey Results - Multiple Columns for Each Choice with Survey

------------------------------------------------
Format #2: One Column of Comma Separated Values
Another common layout is where there is one column of results that contains comma separated values.

Survey Results - One Column of Comma Separated Values with Survey
Unpivot the Data with Power Query
The first thing we need to do is get this data in a format that is easier to summarize with a pivot table.

We want the data to look like the following, with one column that lists the results.  We will then have multiple rows for each survey taken.  This format will make it easy to create a pivot table to summarize the results.

Unpivoted Survey Results Data - Ready for Pivot Table

-------------------------------------------------------
Once the data is in the proper format, we can then use a pivot table to quickly summarize the results.
