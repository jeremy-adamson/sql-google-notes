# Workign with data in R

Data frame - A collection of columns

## Explore data and R

Tibbles are like streamlined data frames

* Never change the data types of the inputs
* Never change the names of your variables
* Never create row names
* Make printing easier

Tidy data - Standardizing how data is organized in R

* Variables are organized into columns
* Observations are organized into rows
* Each value must have its own cell

```
    library(ggplot2)
    data("diamonds")
    View(diamonds)
```

head() - gives a quick preview of what the table looks like

str() - Gives high level info on the names and all the data types contained within

colnames() - Just returns the names of the column names

mutate(table, col_to_add_name = put data here) - lets you modify the columns

Data import basics can be found [here](https://d18ky98rnyall9.cloudfront.net/kO62nTFvRAKutp0xbzQC0g_7f7c23790c334cea97fd6b96ff46a24d_Data-import.pdf?Expires=1661472000&Signature=FAphD3FANwRCvAoCwEUdWr~LzcNIwC69PRB7-XeWF2nD91vLq-Vn9U039-Q7~Bu0GHJNvgvdRhlFqcPTLxPSkizxUAsXwth7K0NEZ2vkaG~jGLn6wOJQzTxNhYeR1-E8yOkmOCpPdQQXXl7x5jKcNCeKuVYMpsZhesTD6a-4eXo_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

## Cleaning data - Along with a number of fuctions that go with it

Here package - Makes referencing files easier

Skimr package - Simplify data cleaning tasks

Janitor package - Cleaning data

skim_without_charts() - Gives a summary of the chart

glimpse() - Another way to get a summary

select() - selects that column or sets of columns requested

rename() - can let you change the column names

rename_with() - changes column names to be either upper or lower case

clean_names() - ensures there are only characters numbers and underscores in the names

arrange() - ORDER BY.  Use table_name %>% before calling it

group_by() - fairly similar

separate(table, field, into=c(first field, second field), sep=delimiter ) - splits a field

unite(table, new field, field 1, field 2, sep=delimiter)

mutate(new column = calculation) - adding a column to the table

Pivot tables in R can be found [here](https://tidyr.tidyverse.org/articles/pivot.html)

* Organizational functions help you sort, filter, and summarize your data
* Transformational functions help you separate and combine data, as well as create new tables
* Cleaning functions help you preview and rename data so that it's easier to work with

## Take a closer look at the data

Anscombe's quartet - Four datasets that have neraly identical summary statistics

Bias() - comparing the actual outcome of our data with the predicted outcome

Unbiased is close to 0
