---
title: A New Methodological Framework for Studying Status Exchange in Marriage
authors: Yu Xie, Hao Dong
year: "2021"
journal: American Journal of Sociology
doi: 10.1086/713927
tags:
  - mate-selection/status-exchange
---
## Abstract

The authors propose a new methodological framework for studying status exchange in marriage. As shown in recent debates on status-race or status-beauty exchange, the conventional log-linear modeling approach is prone to controversial specifications and alternative interpretations. This study develops a simple method—the exchange index (EI)—with cohort- and gender-specific relative status measures, statistical distribution balancing, and nonparametric matching. While allowing for multiple covariate controls, the EI measures the average difference in spouse’s status between intermarriages and matched in-group marriages. To demonstrate the new framework, two analytical examples of status-race and status-age exchange, based on the IPUMS 2000 U.S. Census 5% microdata sample, are used. To verify the new method, replication and simulation studies are also conducted. This approach reduces model dependency, improves flexibility to account for confounders, allows for examination of heterogeneous patterns, speaks to fundamental concepts in status exchange theory, and takes advantage of increasingly available large-scale microdata.

## Notes

**Status exchange** refers to a marriage pattern in which one spouse compensates for his or her disadvantage--relative to the other spouse--in one status dimension with an advantage in another status dimension.

Example: Black-White intermarriages (e.g., [[@qianBreakingRacialBarriers1997]]; [[@qianSocialBoundariesMarital2007]]; [[@torcheDecliningRacialStratification2017]])

Methodological disputes
- Rosenfeld ([[@rosenfeldCritiqueExchangeTheory2005]]; [[@rosenfeldStillWeakSupport2010]]) treats status exchange parameters as four-way interation terms.
- [[@gullicksonCommentEndorsementExchange2010]] considers certain three-way interaction terms to be adequate.
- [[@kalmijnEducationalInequalityHomogamy2010]] and [[@qianBreakingRacialBarriers1997]] compare observed frequencies with predicted frequencies under no status exchange

The Exchange Index $EI$
1. Convert status to percentile ranking (within a subpopulation defined, for instance, by gender and cohort).
2. (Optional) Equalize the nonfocal spouse’s status distributions between controls and treated cases.
3. Match controls to treated cases by the focal spouse’s status and other covariates.
4. Compute $EI$ as the estiamted $ATT$ of intermarriage (treatment)
	- $EI_{H}$ reveals, for “the same” husbands belonging to a racial group, whether and to what extent their wives would have lower social status on average when they intermarry.
	- Likewise for $EI_{W}$

Advantages over log-linear models
- A single, simple, nonparametric summary measure, straightforward for interpretation
- Accommodate covariates (especially continuous ones)
- Distinguish between "market exchange" and "dyadic exchange" ([[@torcheDecliningRacialStratification2017]])