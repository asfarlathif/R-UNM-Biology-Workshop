# R-UNM-Biology-Workshop
General workshops on using R for biology. Originally designed for use in the University of New Mexico biology department.

## Setting up R and RStudio
Installing R:

If using a PC system, go to: https://cran.r-project.org/bin/windows/base/.

If using an Apple/MAC system, go to: https://cran.r-project.org/bin/macosx/.

If using a Linux system, go to: https://cran.r-project.org/bin/linux/.

Installing RStudio:

Once R is installed, go to: https://rstudio.com/products/rstudio/download/ and download the appropriate version of RStudio.

## List of R packages needed for this workshop
{car} - useful tools for ANOVAs in R

{dplyr} - useful tools for processing data

{ggplot2} - useful graphics package for producing publication-quality figures

{ggplotgui} - provides a basic graphical user interface (GUI) for ggplot2

{lubridate} - useful tools for handling dates and times in R

{minpack.lm} - useful set of tools for non-linear curve fitting

{nlme} - useful set of tools for mixed effects statistical modeling

{patchwork} - useful for making multipaneled figures

{readxl} - lets you read in xls and xlsx files into R

{robust} - provides some basic robust statistical tools in R

{tidyr} - useful tools for keeping data 'tidy'

Run the following command to install these packages:

    install.packages(c("car", "dplyr", "ggplot2", "ggplotgui", "lubridate", "minpack.lm", 
    "nlme", "patchwork", "readxl", "robust", "tidyr"))

## Resources
Burns. The R Inferno. https://www.burns-stat.com/pages/Tutor/R_inferno.pdf

    Great resource that goes over common pitfalls that for the nine circles of R hell.
    Based loosely on Dante's Inferno.

Grolemund & Wickham. R for Data Science. https://r4ds.had.co.nz/

    Solid resource for how to analyze data using R.

Long & Teetor. R Cookbook. https://rc2e.com/

    Solid resource for everything from using R to data visualization and statistics.


Wickham. Advanced R. http://adv-r.had.co.nz/

    An excellent resource for those who want to start modifying R itself.
