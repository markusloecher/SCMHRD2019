About this workshop
===================

Goals
-----

This 3 day workshop is intended to empower participants to perform serious nonlinear statistical modeling with the R statistical software. I assume that you are familiar with linear regression and R.

Agenda
======

Day 1
-----

-   Polynomial regression (review)
-   Regression Splines
-   Smoothing Splines

Day 2
-----

-   Generalized additive models
-   Modeling time series with GAMs
-   Resampling Methods
-   Cross-validation
-   Bootstrapping

Day 3
-----

-   CART
-   Loss Functions for trees
-   Optional: Surrogate Variables
-   Random Forests
-   Variable Importance

------------------------------------------------------------------------

How you should prepare
----------------------

The workshop will contain plenty of hands-on, interactive explorations of real data sets.

You should install the [R](https://cran.r-project.org/) language and its popular IDE [RStudio](https://www.rstudio.com/products/rstudio/download/) prior.

### Required libraries

When you start RStudio you should see 3 panels, one of them the *Console* where you can type commands.

``` r
#mandatory
if (!require(pacman)) install.packages("pacman")
library(pacman)

p_load(gamair, lubridate,knitr,dygraphs,xts,ISLR,splines,gam,boot,mgcv,ggplot2,scales,partykit, install = TRUE)
```

I would decline the compilation from source.

Be prepared to wait a while, lots of dependent packages are being installed as well.

------------------------------------------------------------------------

### Links

[Berlin School of Economics and Law](http://www.hwr-berlin.de "BSEL Homepage")

[Prof. Markus Loecher](https://www.hwr-berlin.de/en/hwr-berlin/about-us/staff/414-markus-loecher/ "ML official university link")

[my blog](https://blog.hwr-berlin.de/codeandstats/ "blog")

[my RgoogleMaps package](http://rgooglemaps.r-forge.r-project.org/ "RgoogleMaps on Rforge")

### Ressources

-   Main book
-   <http://www-bcf.usc.edu/~gareth/ISL/>
-   <https://www.r-bloggers.com/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/>
-   Alternative books
    -   Data Science <https://www.manning.com/books/practical-data-science-with-r> Make Your Own Neural Network (Tariq Rashid) Statistics Andy Field, Jeremy Miles, Zoe Field (2012), Discovering Statistics Using R, SAGE <https://uk.sagepub.com/en-gb/eur/discovering-statistics-using-r/book236067> <https://www.openintro.org/stat/> <http://onlinestatbook.com/>
-   Useful MOOCs
    -   Statistics

            https://classroom.udacity.com/courses/st101
            Intro to Descriptive Statistics: https://www.udacity.com/course/intro-to-descriptive-statistics--
            ud827
            Intro to Inferential Statistics: https://www.udacity.com/course/intro-to-inferential-statistics--ud201

-   R Programming <https://www.coursera.org/learn/r-programming/> Machine Learning <https://www.coursera.org/learn/machine-learning>

-   Why R is still one of the best data science language to learn today

        http://sharpsightlabs.com/blog/r-recommend-data-science/
        https://stackoverflow.blog/2017/10/10/impressive-growth-r/

-   Ethical Issues in Machine Learning: <https://www.propublica.org/series/machine-bias> Fairness of algorithms Equality of Opportunity in Supervised Learning Photo Categorization <http://www.wnyc.org/story/deep-problem-deep-learning/> <https://www.forbes.com/sites/mzhang/2015/07/01/google-photos-tags-two-african-americans-as-gorillas-through-facial-recognition-software/>
