---
editor_options: 
  markdown: 
    wrap: 72
---

# Maternal Mortality

## Overview

This project explores the factors influencing maternal mortality rates
globally, focusing on data from 2015. Maternal mortality is defined as
deaths resulting from complications during pregnancy or childbirth. This
is a pressing issue as approximately 84% of these deaths are
preventable.

## Data Sources

The analysis utilizes data from the **QOG Standard
Dataset** and **Kaggle**.

## Variables

The following independent variables were examined for their impact on
maternal mortality rates:

-   **Gross Domestic Product (GDP)**

-   **Human Development Index (HDI)**

-   **Current Health Expenditure**

-   **Current Education Expenditure**

-   **Comparative Abortion Index (CAI)**

## Methodology

An **Ordinary Least Squares (OLS)** regression analysis was conducted,
along with partial regression and regression coefficient plots. The
model achieved an **R-squared value of 0.856**, indicating a strong fit.
At the 5% significance level, only HDI and CAI were found to be
statistically significant predictors.

## Limitations

This analysis acknowledges several limitations:

-   The data set is limited to 2015, potentially affecting the
    applicability of the findings.

-   Not all countries had complete data, which may introduce bias.

-   Some variables of interest were excluded due to missing values.

## Conclusion

This project sheds light on critical factors affecting maternal
mortality and emphasizes the importance of addressing preventable causes
to improve global health outcomes.

## Sources

-   [Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/maternal-mortality-dataset)

-   [QOG](https://www.qogdata.pol.gu.se/data/codebook_std_jan24.pdf)

-   [World Health
    Organization](https://www.who.int/news-room/fact-sheets/detail/maternal-mortality)
