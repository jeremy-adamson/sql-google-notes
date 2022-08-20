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
