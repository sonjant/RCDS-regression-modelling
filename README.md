# Hi! Welcome to the Regression Modelling in R course! :grinning: :chart_with_upwards_trend:

#### We're Sonja and Fernando, two PhD students at the Imperial School of Public Health :hospital:, and we'll be teaching this interactive, standalone, and roughly 3-hour course for the Graduate School in-person in the Central Library :books:. We highly recommend that you bring your own laptop to class and follow the pre-course setup below!

## 1. Learning outcomes :bulb:
By the end of this course, we hope that you will be able to:
1. **Identify** the correlation coefficient as a single measure of a linear association.
2. **Apply** general linear models to model a response variable in terms of a single or multiple variables.
3. **Evaluate** model fitness by comparing the results produced by the model with your data.
4. **Present** model fitness using data visualisation techniques.
5. **Interpret** regression model results from scientific papers.

## 2. Pre-course setup :computer:
We will be working with the open-source (a.k.a. free :partying_face:) programming language "R" and the integrated development environment (IDE) RStudio. Please download and install these in advance of the session to save yourself the hassle during the course:

:arrow_right: R (download the version that matches your operating system): https://cran.ma.imperial.ac.uk/  
:arrow_right: RStudio Desktop (the free version): https://posit.co/downloads/

## 3. Course materials :book:
Please copy-paste the following code into your "Console" in RStudio and run it by hitting "Enter" to install the required packages for the session:
```r
list.of.packages <- c("faraway")
new.packages <- list.of.packages[!(list.of.packages %in% installed.packages()[,"Package"])]
if(length(new.packages)) install.packages(new.packages)

library(faraway)
```
Alternatively, you can run the notebook online using Binder (although we do not recommend doing this using the classroom computers as they're very slow): [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ImperialCollegeLondon/RCDS-regression-modelling/HEAD?urlpath=rstudio)

## 4. Literature workshop :page_facing_up:
For the workshop, we will be interpreting the results from this paper by Sin *et al* titled "Mental health and caregiving experiences of family carers supporting people with psychosis". We will give you enough time to read through the abstract and interpret the results tables during the session, but you may get a headstart by doing this in advance: [link to paper](https://www.cambridge.org/core/journals/epidemiology-and-psychiatric-sciences/article/mental-health-and-caregiving-experiences-of-family-carers-supporting-people-with-psychosis/FF705DECFAC216D777B834E5D2A0180F).
