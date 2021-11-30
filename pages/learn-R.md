# Resources for learning R

Getting to grips with R and RStudio can be a steep learning curve. There is no substitute for diving in a completing a small project but there are lots of amazing (and often free!) resources out there to help you. The following lists should give you a range of options to look at. 

## Getting Started with R
* Rstudio have a [nice introductory course](https://education.rstudio.com/learn/) for beginners. They also have learning tracks for intermediate R users and experts too
* [Swirl](https://swirlstats.com) is a great platform for learning how to use R and it can all be done using R commands. You can get started by running the following code:
```
> install.packages("swirl") # Run this once
> library(swirl) # load the package at the start of a fresh session
> swirl()
```
* Alex Douglas, Deon Roos, Francesca Mancini, Ana Couto & David Lusseau have produced a book called [An Introduction to R](https://intro2r.com/index.html)
* Winston Chang's [Cookbook for R](http://www.cookbook-r.com/) is a great reference for common tasks

## Best Practices
* This guide on [using projects](https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects) is really useful
* The [Tidyverse Style Guide](https://style.tidyverse.org/) provides tidyverse-flavoured advice on writing clear code
* Alongside the style guide there is a package called `{styler}` which you can use to automatically style your code in R

## Data Manipulation & Analysis
* Ewen Harrison, Riinu Pius, [R for Health Data Science](https://argoshare.is.ed.ac.uk/healthyr_book/), Chapman and Hall/CRC, 2021.
* Garrett Grolemund and Hadley Wickham, [R for Data Science](https://r4ds.had.co.nz/index.html), O'Reilly, 2017.
* [The Epidemiologist R Handbook](https://epirhandbook.com/en/) and [R for Epidemiology](https://www.r4epi.com/) are both great for common health related analysis
* [This](https://github.com/ujjwalkarn/DataScienceR) github repository maintained by Ujjwal Karn lists a variety of Data Science in R tutorials
* Most of the RStudio maintained tidyverse packages have [cheatsheets](https://www.rstudio.com/resources/cheatsheets/) which you can use to quickly reference key functions

## Plotting
* Claus O. Wilke, [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/), O’Reilly Media, 2019.
* Kieran Healy, [Data Visualization: A Practical Introduction](https://socviz.co/), Princeton University Press, 2018.
* [Understanding ggplot2 part 1](https://www.youtube.com/watch?v=h29g21z0a68&ab_channel=ThomasLinPedersen)
* [Understanding ggplot2 part 2](https://www.youtube.com/watch?v=0m4yywqNPVY&t=0s&ab_channel=ThomasLinPedersen)
* [The R Graph Gallery](https://www.r-graph-gallery.com/) is an excellent website with code for a variety of different visualisations using the package ggplot2
* Trafford Data Lab, [How to make maps in R](https://medium.com/@traffordDataLab/lets-make-a-map-in-r-7bd1d9366098), 2018.

## Collaboration
* Jenny Bryan, the STAT 545 TAs, Jim Hester, [Happy Git and GitHub for the useR](https://happygitwithr.com/), Github Bookdown.
* Katie Sylor-Miller, [Oh Shit, Git!?!](https://ohshitgit.com/) Unknown publisher, 2016-2021.

## Places to go for help
If problems pop up during your coding, probably the best thing to do is simply google it! Someone else will have encountered the same problem and asked for help before and very often people will give useful advice to help solve the issue. Failing that, there are some places online you can go for help.
* RStudio has [community support pages](https://community.rstudio.com/)
* [stackoverflow](https://stackoverflow.com/questions/tagged/r) is another common source of help
#### Remember - If you are asking for help it is good practice to provide additional information about your R/RStudio version and other information about your environment. It's also a good idea to make and provide a Minimal Reproducible Example or [Reprex](https://www.tidyverse.org/help/). Sometimes making these can allow you to think about what might be going wrong and solve the problem yourself.


### [Next: Collaboration with GitHub](collaboration.md)
[Previous: Good code reviewing practices](code-review.md)

[Index](index.md)
