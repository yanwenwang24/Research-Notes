---
title: Is Meritocracy Not So Bad After All? Educational Expansion and Intergenerational Mobility in 40 Countries
authors: Herman G. Van De Werfhorst
year: "2024"
journal: American Sociological Review
doi: 10.1177/00031224241292352
tags:
  - mobility/occupation
  - mobility/education
  - methods/decomposition
---
## Abstract

In the face of continued socioeconomic inheritance, the belief that the simple expansion of educational opportunities will create meritocratic societies has been met with skepticism. It is well documented that within expanding educational systems, class-advantaged families attempt to secure further advantages for their offspring. Conversely, for many, the modernist belief that educational expansion is a means to achieving a fairer society remains compelling. Studying trends in intergenerational occupational mobility in 40 countries from four continents, I examine whether educational expansion enhances occupational mobility, and whether such trends are counteracted by heightened persistence between social origin and destination within education groups. The results indicate that educational expansion over time, and the policies supporting it, are linked to improved intergenerational occupational mobility. Furthermore, this increased mobility through expanded educational opportunities is not negated by a strengthening of within-education elite persistence in occupational status, suggesting that occupational mobility patterns can genuinely change through educational expansion. The modernist ideology around educational expansion as a driver of social mobility may warrant renewed attention.

## Notes

### Theoretical frameworks

```mermaid
graph LR;
A[Origin] ---> B[Destination];
A ---> C[Education];
C ---> B
```

Origin-Education-Destination (OED) triangle
- The $OE$ path: inequality in educational attainment between families of different socioeconomic statuses
- The $ED$ path: the returns to education in the labor market
- The $OD|E$ path: direct association between origin and destination within levels of educational attainment

Three claims about social change, meritocracy, and intergenerational mobility
- *Context matters:* Through educational expansion, intergenerational persistence declines both through education and directly from parents' occupational status to children's occupational status.
- *Context does not matter:* With educational expansion, resourceful families will keep their children ahead in their educational and occupational attainment, leading to highly similar patterns of mobility across societies and across time.
- *Direct persistence:* Even if expansion equalizes educational attainment across social origins, the direct association between origin and destination (i.e., within broad levels of educational attainment) is much more persistent to change and may even strengthen to compensate a loss of advantage by resourceful families.

### Research design

Data
- European Social Survey (rounds 1-7), International Social Survey Programme (between 1985-2019)
- 175,804 individuals from 297 country-cohorts (five-year) and 40 countries

Variables
- Rank scores based on ISEI, for parents and children, by country and cohort, separately
- Education: *lower-secondary or less*, *upper-secondary or some postsecondary*, and *college degree or more*
- Context: *university participation per 10 capita* (Cross-national Time Series data Archive), *proportion of tertiary degree holders*, *participation rate in any level above lower-secondary*, *participation rates in secondary schooling per 10 capita*, *minimal school-leaving age*

Decomposition
1. $D_{i} = α + β^{jk}_{1}O_{i}+{i} + ε_{i}$
	- $D_{i}$ is the destination status of individual $i$
	- $O_{i}$ is the origin status of individual $i$
	- $β^{jk}_{1}$ represents the total intergenerational persistence in country $j$ and cohort $k$
2. $β_{1} = \sum_{e}((π_{e}B^{b}_{e}) + (π_{e}B^{w}_{e}))$
	- $π_{e}$ is the share of people in education group $e$
	- $B^{b}_{e}$ is the indirect (between) path through education
	- $B^{w}_{e}$ is the indirect (within) path for each educational group
	- $B^{b}_{e}$ and $B^{w}_{e}$ are estimated on the individual-level within country-cohort group
3. $β_{jk}^{b} = α + γC_{jk} + ζ_{j} + ε_{jk}^{b}$; $β_{jk}^{w} = α + γC_{jk} + ζ_{j} + ε_{jk}^{b}$
	- $C_{jk}$ represents educational expansion measures in country $j$ and cohort $k$
	- $ζ_{j}$ are country-fixed effects

### Results

1. The OD association is weaker for graduates of tertiary education than for those with lower education.
2. Over time, there is a sharp decline in the direct OD association in most, but not all, countries.
3. Educational expansion (and the related policies) is associated with declining levels of intergenerational persistence (both direct and indirect paths).
