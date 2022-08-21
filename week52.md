# Formatting and Adjusting Data

## Convert and Format Data

Check data types so that they are consistent

Incorrectly formatted dat can:

* Lead to mistakes
* Take time to fix
* Affect stakeholder's decision-making

Highlight columns and then can define the data type in a spreadsheet

CONVERT(cell, unit1, unit2)

* Paste special and can copy values only

All sorts of ways to convert but the more common ones are:

* String to date
* String to numbers
* Combining columns
* Numbers as percentages

Data validation function - Allows you to controll what can and can't be entered into a worksheet

* Add dropdown lists with predetermined options
* Create custom checkboxes
* Protect structured data and formulas
* Best combined with conditional formatting

### Transforming data in SQL

While there are conversions that can be done using CAST, there are also more specialized ones like COERCION when working iwth big numbers and UNIX_DATE when working with dates.  But most of the time CAST will be the go-to choice.

* Numeric - Integer, Numeric, Big number, Float, String
* String - Bool, Integer, Numeric, Big number, Glat, String, Bytes, Date, Datetime, Time, Timestamp
* Date - String, Date, Date time, Timestamp

CAST( expression AS typename)

Other documentation:

* [CAST and CONVERT](https://docs.microsoft.com/en-us/sql/t-sql/functions/cast-and-convert-transact-sql?view=sql-server-ver15)
* [MySQL CAST Functions and Operators](https://dev.mysql.com/doc/refman/8.0/en/cast-functions.html)
* [How to: SQL Type Casting](https://www.blendo.co/blog/how-to-sql-type-casting/)

## Combine Multiple Data Sets



## Get Support During Analysis
