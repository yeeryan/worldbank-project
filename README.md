# worldbank-project


➡️ ***<a href = "https://yeeryan.github.io/worldbank-project/">View the Report</a>*** ⬅️

## About the Project

*Originally submitted in 2019 as a final project*

In this project, I am hoping to determine if there is a relationship in countries between school enrolment rates and the following factors: access to electricity, rate of urbanisation, and the number of hospital beds per 1000 people. I will utilise data from the World Bank. In order to analyse, I’ll create a linear model for each outcome measure with all the predictors, and a sub-model without the Hospital beds (per 1,000 people) predictor to compare whether or not the models have significant differences. With these models, I’ll conduct ANOVA tests, interpret coefficients & confidence intervals, and compare their regression diagnostic plots to measure the models’ fit and to analyse their potential differences and similarities.

### Packages Used

- tidyverse
- wbstats
- ggfortify

## Setup

A. Access the report <a href = "https://yeeryan.github.io/worldbank-project/">HERE</a>.

***OR***

B. Knit the report using the following steps:

1. In rstudio run the following command to install the packages used:

`install.packages(c("tidyverse","wbstats","ggfortify"))`

*This command will install `tidyverse`, `wbstats`, and `ggfortify`.

2. Clone the repo and open the `World Bank Find.Rmd` file located in the  `src` folder in Rstudio.

3. Knit the rmarkdown file.

