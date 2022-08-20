# Introduction to focus on integrity

## Segments in this section overall

* Ensuring data integrity
* Understanding clean data
* Cleaning data using SQL
* Verifying and reporting cleaning results

## Going into it all

* Data integrity - The accuracy, completeness, consistency, and trustworthiness of data throughout its lifescycle
* Data replication - the process of staring data in multiple locations.  This can cause issues
* Data transfer - Can cause issues too
* Data manipulation - Can also cause issues if people manipulate it in the wrong ways

## Common data constraints

* Data type - information must fit the type
* Data range
* Mandatory - Some values cannot be left blank or NULL
* Unique - As the name says
* Regular expression (regex) - Values must match a certain pattern such as a phone number
* Cross-field validation - Certain conditions for multiple fields must be met such as all the numbers adding up to 100%
* Primary-key - Well... a primary key
* Set-membership - Values for a column must come from a set of discrete values.  Kinda like range
* Foreign-key - Values for a column must be unique values coming from a column in another table.  Basically a primary key in another table within a relational database
* Accuracy - Is the data itself accurate and is there a way to double check
* Completeness
* Consistency - If the data is stored in multiple places, is it the same in all the places

## Misc

* Clean data + alignment to business objective = accurate conclusions

## Dealing with insufficient data

* Identify trends with the available data
* Wait for more data if time allows
* Talk with stakeholders and adjust your objective
* Look for a new dataset

## What to do when you find an issue with your data

* No data - Either request additional time to recollect the missing data OR find something comperable
* Too little data - Fill in with something comperable OR redefine the scope of the analysis
* Wrong data - Identify errors in the data and correct them if there is a patter in the data that you do have

## Sample sizes

* Population
* Sample - typically no less than 30
* Margin of error - how much expected error difference is there between the sample and the full population
* Confidence level - Confidence in the repeatability of the results
* Confidence interval - The range of possible values that the population's result would be at the confidence leve of the study
* Statistical significance - A measure of if there is an actual result or just background data noise

Central limit theorem (CLT) gives the value of 30