# Performing Data Calculations

## Get Started with data calculations

* COUNTIF
* SUMIF(condition_range, condition, range_to_add)

However there is a different format for a similar function

* SUMIFS(sum_range, condition_range1, condition1, ...)
* COUNTIFS - similar syntax to SUMIFS

* SUMPRODUCT() - Multiplies the contents of two similar arrays and then adds them

## Pivot Tables

Pivot tables let you view data in multiple ways to find insights and trends

Calculated field - A new field within a pivot table that carriers out certain calculations based on the values of other fields

* Rows
* Columns
* Values - Input the variables you want to measure
* Filters

## Learn more SQL calculations

Fairly similar arithmetic operators in SQL including mod

GROUP BY - A command that groups rows that have the same values from a table into summary rows

## The data-validation process

Validating:

* Data type - Check that the data matches the data type defined for a field
  * There are limitations of similar types behaving similarly (timestamp/date)
* Data range - Check that the data falls within an acceptable range of values defined for the field
  * However wonky things can still sneak past this like decimals when only integers are expected
* Data constraints - Checking that the data meets certain conditions or criteria for a field.  This include the type of data entered as well as other attributes of the field such as the number of characters.
* Data consistency - Check that the data follows or conforms to a set structure
  * The data itself may not be accurate
* Code validation - Check that the application cose performs any of the previously mentions validations during user input
  * Can be tricky to impliment

## Using SQL with temporary tables

Temporary table - A database table that is created and exists temporarily on a database server

WITH - A type of temparary table that you can query from multiple times.  Approximates a temporary table

SELECT INTO - Make a copy of a table with specific parameters (not in big query)

CREATE TABLE - Makes a table in the database that everyone can use

Global vs. local temprary tables:

* Global tables are made available to all datgabase users and are deleted when all connections that use them have closed.  Local is just to that individular user.
* Dropping temp tables, it's different from deleting the table.

[Intermediate guide to SQL](https://d18ky98rnyall9.cloudfront.net/BsaAoIwwQLKGgKCMMOCyFw_d522c0a682164c5dbaa4e2b507f01df1_Your-Intermediate-Guide-to-SQL.pdf?Expires=1661299200&Signature=gc6dRqDwUHItu2auxLZi9CTp~pHsX6WW19EzfxcLUKfex2cwK5YfcmyWp3KjVo2mZyHfJBg9TLBjnUlDbJsWAWMNbRhPQJEsdqT16ReFEhmFodESUWBzpT2G4ilV-LyWygNSFFljNXiIwW~a7hCdYjMf7ssOtux8VzcCtmESm2g_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)
