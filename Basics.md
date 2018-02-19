R Markdown
----------

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

    summary(cars)

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

Including Plots
---------------

You can also embed plots, for example:

![](Basics_files/figure-markdown_strict/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

Assignement Operator
====================

    num <- 10
    num

    ## [1] 10

    num1 = 20
    num1

    ## [1] 20

Numeric Object
==============

    thirty <- 30
    thirty

    ## [1] 30

    ten <- 10
    ten

    ## [1] 10

    result <- ten+thirty
    result

    ## [1] 40

    result1 <- ten*thirty
    result1

    ## [1] 300

    result2 <- ten/num1
    result2

    ## [1] 0.5

    num2 <- 4.5
    num2

    ## [1] 4.5

Object data type
================

    class(num)

    ## [1] "numeric"

    class(result1)

    ## [1] "numeric"

    class(num2)

    ## [1] "numeric"

Operations
----------

    num3 <- 10.75
    num3

    ## [1] 10.75

    result3 <- num2-result2
    result3

    ## [1] 4

    result4 <- num3+num2
    result4

    ## [1] 15.25

Logical Objects
===============

    YES <- TRUE
    YES

    ## [1] TRUE

    yes <- T
    yes

    ## [1] TRUE

    NO <- FALSE
    NO

    ## [1] FALSE

    no <- F
    no

    ## [1] FALSE

NULL
====

    EMPTY <- NULL
    EMPTY

    ## NULL

NA
==

    missing_value <- NA
    missing_value

    ## [1] NA
