A gRadual intRoduction to data wRangling
================
Chester Ismay and Ted Laderas

Welcome! This is a workshop for the Cascadia R Conference that is meant to be a gentle introduction to data wrangling using the `tidyverse` R packages. You'll find there are lots of functions in the `tidyverse` designed to help solve your common headaches when working with data and can even make data wrangling fun!

Prerequisites
-------------

Please make sure to have this completed prior to the workshop beginning. Reading over all the materials here will help you get an understanding of what is to be expected and a better grounding to dive into the material as the workshop gets started. To participate in this workshop, you'll need to do the following on your own laptops:

1.  Have the latest version of R AND RStudio installed ([Directions are here](http://moderndive.netlify.com/2-getting-started.html#what-are-r-and-rstudio))
2.  Be familiar with the [basics of the RStudio Interface](https://ismayc.github.io/rbasics-book/3-rstudiobasics.html#rstudio-layout)
3.  Have the following R packages installed: `dplyr`, `tidyr`, `readr`, `readxl`, `haven`, `gapminder`, and `fivethirtyeight`

    This can be accomplished by copying the following code into the *Console* in RStudio and pressing Enter. Note that you'll see quite a few lines of code run while the packages are installing. Don't be alarmed. After the packages (and the packages they depend on) are done installing, you should see a `>` waiting for you to enter something new waiting for you in the Console tab of RStudio.
    
    After all of these packages are installed you should see them listed in the Packages tab in the bottom right section of RStudio.

        install.packages(c("dplyr", "tidyr", "readr", "readxl", "haven", "gapminder", "fivethirtyeight"))

    -   The [`tidyverse`](http://tidyverse.tidyverse.org/) contains a variety of different packages that will be useful in your analysis and will be the focus of this workshop. We will focus on 
    - the [`dplyr`](http://dplyr.tidyverse.org) package for data wrangling,
    - the [`tidyr`](http://tidyr.tidyverse.org) package for data reshaping,
    - and the [`readr`](http://readr.tidyverse.org), [`readxl`](http://readxl.tidyverse.org), and [`haven`](http://haven.tidyverse.org) packages for data importing.
    -   The [`gapminder`](https://github.com/jennybc/gapminder/blob/master/README.md) package contains a data set made famous by Hans Rosling exploring data on the world's countries.
    -   The [`fivethirtyeight`](http://fivethirtyeight-r.netlify.com/) package contains many datasets used by data journalists at FiveThirtyEight.com.

IMPORTANT FINAL STEPS
---------------------

-   Download the conference materials as a [ZIP file](https://github.com/tidyverse-intro/gradual_data_wrangling/archive/master.zip) and extract the files there as a folder on your computer. Note the importance of actually extracting all the files to a folder. This will be particularly important when we talk about importing files. 

- Double click on the **gradual_data_wrangling.Rproj** file in that folder to open up an RStudio project containing the files needed for the workshop. This might take a bit the first time. You'll see `gradual_data_wrangling-master` in the top right corner when it is ready to go.

You'll be following along in the **Part1-dplyr_intro.Rmd**, **Part2-loading_data.Rmd**, and **Part3-why_tidy_data.Rmd** files, running the R code in the "chunks" there, and writing your own code to practice. You can also follow along with the webpage for the workshop at <https://cascadiarconf-wrangle.netlify.com>.

Remember, in this workshop we will adhere to the [code of conduct for this conference](https://cascadiarconf.com/coc/). Be respectful of your fellow students, workshop leaders, and workshop TAs and let's learn together.

Outline of this Workshop
------------------------

1.  Using `dplyr` for data wrangling / summarizing
    -   Subsetting rows with `filter()`
    -   Creating a numerical summary with `summarize()`
    -   Building summaries across groups of one or more variable with `group_by() %>% summarize()`
    -   Designing a new variable using `mutate()`
    -   Sorting the data based on one or more variables with `arrange()`
    -   Using the pipe `%>%` to chain it all together
2.  Importing data using `readxl`, `readr`, and `haven` packages
3.  What is tidy data?
4.  Using the `tidyr` package to reshape/tidy/make data long
