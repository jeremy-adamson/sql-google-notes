# Aggregating data for analysis

Aggregation -  Collecting or gathering many swparate pieces into a whole
Data Aggregation - Identify trends, make comparisons, gain insights

## VLOOKUP for data aggregation

VALUE - A function that converts a text string that represents a number to a numerical value

=VLOOKUP(value to search for even if it's a cell, table range, column # in range, FALSE)

* Search_key - The value to seach for
* Range - The range to consider for the seach or the first cloumn in the range is searched to locate data matching the value specified by the search_key
* Index - The comun index of the value to be retunred where the first column is 1
* Is_sorted - Indicated whether the column to be searched is sorted, TRUE by default.  This will typically be FALSE for most uses.

### Limitations of VLOOKUP

* VLOOKUP cannot look left.  To get around it, copy and paste the data so that the needed data are not to the left.
* Protected ranges restrict who can edit things
* MATCH - A funciton used to locate the position of a specific lookup value
* Exact and approximate matching
  * approximate match finds the first thing that is greater than the lookup value going down vertically

When do you need to use VLOOKUP?

* Populating data in a spreadsheet
* Merging data from one spreadsheet with data in another

## Use JOINS to aggregate data in SQL

JOIN - A SQL caluse that is used to combine rows from two or more tables based on a related column

* Inner - returns records with matching values in both tables
* Left - A function that will return all the recoreds from the left table and only the matching records from the right table
* Right - Same thing as Left join but right
* Outer - Everything

Primary keys reference columns in which each value is unique
Forgien keys are primary keys in other tables

COUNT - Returns the number of rows
COUNT DISTINCT - Returns the distinct values in a specified range
Aliasing only lasts for the duration of the given query

## Work with subqueries

Outer Select and Inner Select.  Innermost executes first.
HAVING
CASE / IF

INSUFFICIENT INFORMATION FROM THIS COURSE TO COVER THIS TOPIC AS NEEDED

Will have to continue from backup sources
