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

Concatenate - A function that joins together two or more test strings
CONCAT() - Combines strings from different tables
Openness - Free access, usage, and sharing of data

### Strings in spreadsheets

* LEN - Length of a string
* LEFT - Similar to RIGHT
* RIGHT(cell, character to start at)
* FIND(cell, condition)

* CONCAT - Just the regular function
* CONCAT_WS - Throws in a separator which is whatever is the first argument in the function
* CONCAT with - Adds two or more strings using the + operator

## Get Support During Analysis

What to do when you get stuck

REVISIT THESE LATER ON:

* [Keyboard Shortcuts for Excel](https://support.microsoft.com/en-us/office/keyboard-shortcuts-in-excel-1798d9d5-842a-42b8-9c99-9b7213f0040f?ui=en-US&rs=en-US&ad=US)
* [List of Spreadsheet functions Excel](https://exceljet.net/excel-functions)
* [List of Spreadsheet formulas Excel](https://exceljet.net/formulas)
* [Advanced Spreadsheet skills](https://www.slideshare.net/markjhonoxillo/advanced-spreadsheet-skills)
* [Essential Excel Skills for Analyzing Data](https://learntocodewith.me/posts/excel-skills/)

Best practices for seaching online

* Mental model - thought process in how to approach a problem
* Use the right terms/vocab
