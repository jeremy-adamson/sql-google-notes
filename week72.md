# Programming using RStudio

## Understanding basic programming concepts

Basic concepts of R

* Functions
  * Reusable code with arguements
  * Use ? before the fucntion name to find out what it does
* Comments
* Variables
  * Can store values which are to be used later
  * Assignment isn't done with = but with '<-'
* Data types
* Vectors
  * Basically an array with all the same data type
* Pipes
  * A tool in R for expressing a sequence of multiple operations, represented with %>%
  * Use to channel the output of one function into another

Data structures in R

* Vectors - use the c() function
  * Atomic vectors
    * Six types and come in logical, integer, double, character, complex, raw
    * typeof() Will return the data type of that vector
    * is.logical() will return a bool response
    * names(x) will assign names to the elements of that vector
  * Lists - use the list() function
    * Any data type
    * Lists can contain lists
    * str() or structure call will return how many elements are in the list, each element, along with the data type of that element next to it
    * List elements can be named too
* Data frames
  * Collection of columns similar to a spreadsheet
    * Columns should be named
    * Data frames can include many different data types
    * Elements in each column should all be the same data type
  * data.frame() takes in vectors to make a data frame
* Matrices
* Arrays

### Dates and times in R

* Three different types of representations
  * today() returns the date itself
  * now() returns the date and time

Converting from strings

* ymd() or any variation of that

## Explore coding in R

Operator - A symbol that names the type of operation or calculation in a function

* Assignment operator -  '<-'
* Arithmetic operators - Typical things

Logical operators and conditional statment syntax can be found [here](https://d18ky98rnyall9.cloudfront.net/IH3jvjscStK94747HNrSCg_9681cba255d44707b891ea5e0eb0e2f1_Logical-operators-and-conditional-statements.pdf?Expires=1661472000&Signature=BhPkrhKRDMrewlubOwGuehE~5qq9ebZ90fHfNE4rnDvsefgQoLQpD-izIrdGw6xqtprm9aCIvwc2RmHVtYD-~xNF9jJ5oByFd8lYhsx6urtiFSfV9WS~VBNtNJ2PXz3wEe7kCikyhiZtooZTXVDMEP7LDtIMC3VZe9K-ORIpv40_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A). In short it's pretty similar to any other programming language like C++

Proper way to comment can be found [here](https://d18ky98rnyall9.cloudfront.net/O4EaLwvJSyWBGi8LycsltA_1bd17f3110814c78a739c3d3c0f4use1_Keeping-your-code-readable.pdf?Expires=1661472000&Signature=NYlvctbpUX7QDqioqyZLtbWl5eVJ9GMKuq9wpdDUSlaVSFNl8CvhgoGGrU-BOXi2RX035XMeEPtI~AvY1t5YGOYvAN-htowaq3yopfyNOPM269ki-UkTw4JouVYDO8TO6cF1l~T3Q3lpGtGUqayeSwhlgk~Vkth3uK7eMgRvYqU_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A).  Just be sure to use the # symbol when ti comes to commenting each line.

## Learning about R packages

All sorts of packages out there but they do include:

* Resuable R functions
* Documentation about the functions
* Sample datasets
* Tests for checking your code

Just like with any other OOP language, have to load the package (technically library) for that session.

library() - function to load whatever package is needed

CRAN (Comprehensieve R Archive Network) - Place for packages

[Tidyverse](https://www.tidyverse.org/) - Another good place for mostly data analysis packages

* A system of packages in R with a common design philosophy for data manipulation, exploration, and visualization

Eight core tidyverse packages

* ggpot2
* tibble
* tidyr
* readr
* purrr
* dplyr
* stringr
* forcats

## Explore the tidyverse

Four packages that are an essential part of the workflow for data analysts:

* ggplot2 - Data visualization. Create a variety of data vix by applying different visual properties to the data variables in R
* dplyr - Offers a consistent set of functions that help you complete some common data manipulation tasks
* tidyr - Data cleaning. A package used for data cleaning to make tidy data.
* readr - Importing data

Factors - Store categorical data in R where the data values are limited and usually based on a finite group like country or year

### Pipes

Nested - In programming, describes code that performs a particular cunftion and is contained witthin code that perfoms a broader function

* Call up data (and then)
* Group the data (and then)
* Summarize the grouped data using a mean function
* Puts it into the first argument in the fucntion call on the following line

Guides for learning more about R can be found [here](https://www.r-bloggers.com/2015/12/how-to-learn-r-2/#h.y5b98o9o2h1r)
