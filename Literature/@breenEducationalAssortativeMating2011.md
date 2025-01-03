---
title: Educational Assortative Mating and Earnings Inequality in the United States
authors: Richard Breen, Leire Salazar
year: "2011"
journal: American Journal of Sociology
doi: 10.1086/661778
tags:
  - education
  - mate-selection
  - income
  - methods/decomposition
date created: 2024-12-29
date modified: 2024-12-30
---

## Abstract

This article investigates how changes in educational assortative mating affected the growth in earnings inequality among households in the United States between the late 1970s and early 2000s. The authors find that these changes had a small, negative effect on inequality: there would have been more inequality in earnings in the early 2000s if educational assortative mating patterns had remained as they were in the 1970s. Given the educational distribution of men and women in the United States, educational assortative mating can have only a weak impact on inequality, and educational sorting among partners is a poor proxy for sorting on earnings.

## Notes

### Background

The assumption is: Increasing educational homogamy, or more generally, increased educational assortative mating, may lead to greater inequality ([[@schwartzTrendsEducationalAssortative2005]]; [[@blossfeldEducationalAssortativeMarriage2009]]).

This paper offers an empirical analysis, focusing on changes in:

- educational assortative mating
- patterns of marriage and cohabitation
- propensity to marry or form a cohabiting partnership

Earning inequality between families are decomposed into between-group and within-group components (35 types of households in total)

- Between-type inequality: the differences between types in their average equivalized earnings weighted by the relative frequency of each type.
- Within-type inequality: the variation in equivalized earnings within each type, weighted by the types' relative frequencies.

Main findings

- Developments in educational assortative mating in the United States during the final decades of the 20th century had a small impact on inequality, but in the direction of ameliorating rather than exacerbating it.

### Data and methods

The March Annual Demographic File and Income Supplement of the Current Population Survey, pooled into each of the following two periods:

- 1976-1980
- 2002-2006

Labor earnings

- Income from wages, salaries, and self-employment (including income from business and farming)
- Consider only the earrings of the household head and his or her partner
- Total household earnings were equivalized using the square root of the total number in the family and deflated to 1990 U.S. dollars.

Top-coding of earnings

- In 2002-6, none were top coded beneath the 99th percentile.
- In 1976-80, none of the earnings components was top coded until the 97th percentile.

The Theil index

$$
T = \frac{1}{n} \sum_{i=1}^{n} \frac{x_i}{\bar{x}} \ln\left(\frac{x_i}{\bar{x}}\right)
$$$$

T = \sum_j p_j \frac{\bar{x}_j}{\bar{x}} \ln\left(\frac{\bar{x}_j}{\bar{x}}\right) + \sum_j p_j \frac{\bar{x}_j}{\bar{x}} T_j

$$
$$

T_j = \frac{1}{n_j} \sum_{i=1}^{n_j} \frac{x_{i|j}}{\bar{x}_j} \ln\left(\frac{x_{i|j}}{\bar{x}_j}\right)

$$
$$

T = \sum_j p_j \frac{\bar{x}_j}{\sum_j \bar{x}_j p_j} \ln\left(\frac{\bar{x}_j}{\sum_j \bar{x}_j p_j}\right) + \sum_j p_j \frac{\bar{x}_j}{\sum_j \bar{x}_j p_j} T_j

$$
### Results

|                                                       | Theil | Between | Within |
| ----------------------------------------------------- | ----: | ------: | -----: |
| **A. Basic counterfactuals:**                         |       |         |        |
| 1975-79 observed                                      | .2791 |   .0666 |  .2125 |
| Change within-group Theil, T<sub>j</sub>              | .3563 |   .0666 |  .2898 |
| Change mean earnings, x̄<sub>j</sub>                  | .3172 |   .1144 |  .2027 |
| Change p<sub>j</sub>                                  | .2509 |   .0485 |  .2025 |
| 2001-5 observed                                       | .3432 |   .0853 |  .2579 |
| **B. Decomposing the distribution of p<sub>j</sub>:** |       |         |        |
| Change distribution of couples only                   | .2655 |   .0627 |  .2028 |
| Change educational homogamy only                      | .2562 |   .0542 |  .2020 |
| Change marginal distributions of educa-               |       |         |        |
| tion only                                             | .2518 |   .0498 |  .2020 |
| Change husband-wife association only                  | .2752 |   .0622 |  .2130 |
