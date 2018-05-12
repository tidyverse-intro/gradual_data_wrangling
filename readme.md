# A gRadual intRoduction to data wRangling

Chester Ismay and Ted Laderas

Welcome! This is a workshop for the Cascadia R conference that is meant to be a gentle introduction to the tidyverse.

To run this workshop, you'll need to do the following

- R/Rstudio Installed ([Directions are here](https://ismayc.github.io/rbasics-book/3-rstudiobasics.html))
- Be familiar with the [basics of the RStudio Interface](https://ismayc.github.io/rbasics-book/3-rstudiobasics.html)
- Have the following packages installed:
    - `tidyverse` and `fivethirtyeight`
    
Remember, in this workshop we will adhere the [code of conduct for this conference](https://cascadiarconf.com/coc/). Be respectful and let's learn together.

## Outline of this Workshop

1. Use `dplyr` for data wrangling / summarizing
    - Subsetting rows with `filter()`
    - Creating a numerical summary with `summarize()`
    - Building summaries across groups of one or more variable with `group_by() %>% summarize()`
    - Design a new variable using `mutate()`
    - Sort the data based on one or more variables with `arrange()`
    - Using the pipe `%>%` to chain it all together 
1. Importing data using `readr`, `readxl`, and `haven` packages
1. What is tidy data?
1. Using the `tidyr` package to reshape/tidy/make data long

