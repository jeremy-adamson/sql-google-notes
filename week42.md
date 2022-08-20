# Why is data cleaning important

Data engineers transform data into a useful format for analysis and give it a reliable infrastructure
Data warehousing specialists develop processes and procedures to effectively store and organize data

## Dirty Data

* Duplicate data - Anything that shows up more than once
* Outdated data
* Incomplete data - Missing fields
* Incorrect/inaccurate data
* Inconsistent data - Using different formats to represent the same thing

* Validity - The concept of using data integrity principles to ensure measures conform to defined business rules or constraints
* Accuracy - The degree of conformity of a measure to a standard or true value
* Completeness - The degree to which all required measures are known
* Consistency - The degree to which a set of measures is equivalent across systems

## Data-cleaning tools and techniques

Combining data from multiple sources can lead to interesting and unintended results

* Check for duplicates
* Removing blanks in the data (spaces)
* Fixing misspellings
* Inconsistent capitalization
* Incorrect punctuation and other typos

* Mergers can cause interesting results like this

## Common data-cleaning pitfalls

* Not checking for spelling errors
* Forgetting to document errors
* Not checking for misfielded values
* Overlooking missing values
* Looking at a subset of data and not the whole picture
* Losing track of the business objectives
* Not fixing the source of the error
* Not analyzing the system prior to data cleaning
* Not backing up your data prior to data cleansing
* Not accounting for data cleaning in your deadlines/process

## Data cleaning features in spreadsheets

* Conditional formatting - A spreadsheet tool that changes how cells appear when values meet specific conditions
* Using delimiters to separate or split data within columns
* Function - A set of instructins that performs a specific calculation using the data in a spreadsheet
  * =COUNTIF(range, "value")
  * =LEN(range)
  * =LEFT(range, number of characters) - A function that gives you a set number of characters from the right side of a text string
  * Same thing with RIGHT
  * Another similar one with MID(range, reference starting point, number of middle characters)
  * CONCATENATE(item 1, item 2)
  * TRIM (range)

## Workflow Automation

FILL IN LATER FROM THE LINKS

## Different data perspectives

Pivot table - A data summarization tool that is used in data processing

* TAKE A CLOSER LOOK AT PIVOT TABLES

VLOOKUP - A function that searches for a certain value in a column to return a corresponding piece of information

 * VLOOKUP(data to look up, 'where to look'!Range, column, false)

