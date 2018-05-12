A gRadual intRoduction to data wRangling
================
Chester Ismay and Ted Laderas

Welcome! This is a workshop for the Cascadia R conference that is meant to be a gentle introduction to data wrangling using the `tidyverse` packages. You'll find that there's lots of functions in the `tidyverse` that help solve your common headaches with working with data and can even make data wrangling more fun!

Prerequisites
-------------

To participate in this workshop, you'll need to do the following:

-   Have the latest R/Rstudio Installed ([Directions are here](https://ismayc.github.io/rbasics-book/3-rstudiobasics.html))
-   Be familiar with the [basics of the RStudio Interface](https://ismayc.github.io/rbasics-book/3-rstudiobasics.html)
-   Have the following packages installed:
    -   `tidyverse` and `fivethirtyeight`

Remember, in this workshop we will adhere the [code of conduct for this conference](https://cascadiarconf.com/coc/). Be respectful and let's learn together.

Outline of this Workshop
------------------------

1.  Use `dplyr` for data wrangling / summarizing
    -   Subsetting rows with `filter()`
    -   Creating a numerical summary with `summarize()`
    -   Building summaries across groups of one or more variable with `group_by() %>% summarize()`
    -   Design a new variable using `mutate()`
    -   Sort the data based on one or more variables with `arrange()`
    -   Using the pipe `%>%` to chain it all together
2.  Importing data using `readr`, `readxl`, and `haven` packages
3.  What is tidy data?
4.  Using the `tidyr` package to reshape/tidy/make data long
