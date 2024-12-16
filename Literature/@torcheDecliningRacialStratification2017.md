---
title: Declining Racial Stratification in Marriage Choices? Trends in Black/White Status Exchange in the United States, 1980 to 2010
authors: Florencia Torche, Peter Rich
year: "2017"
journal: Sociology of Race and Ethnicity
doi: 10.1177/2332649216648464
tags:
  - status-exchange
  - methods/log-linear
  - race-ethnicity
  - mate-selection
date created: 2024-12-11
date modified: 2024-12-16
---

## Abstract

The status exchange hypothesis suggests that partners in black/white marriages in the United States trade racial for educational status, indicating strong hierarchical barriers between racial groups. The authors examine trends in status exchange in black/white marriages and cohabitations between 1980 and 2010, a period during which these unions increased from 0.3 percent to 1.5 percent of all young couples. The authors find that status exchange between black men and white women did not decline among either marriages or cohabitations, even as interracial unions became more prevalent. The authors also distinguish two factors driving exchange: (1) the growing probability of marrying a white person as educational attainment increases for both blacks and whites (educational boundaries) and (2) a direct trade of race-by-education between partners (dyadic exchange). Although the theoretical interpretation of exchange has focused on the latter factor, the authors show that status exchange largely emerges from the former.

## Notes

> Status exchange can be regarded as evidence that in the marriage market--and presumably also in society at large--race is *treated* as a hierarchical variable ([[@kalmijnEducationalInequalityHomogamy2010]]).

Black/while intermarriages ([[@gullicksonBlackWhiteInterracial2006]]; [[@qianBreakingRacialBarriers1997]]; [[@qianSocialBoundariesMarital2007]])

- Low but increasing prevalence, attitudinal change
- Gender asymmetry

*Hypothesis 1:* Status exchange in black/white unions has declined over time as these unions have become more prevalent and accepted.

Two distinct channels

1. **Market exchange** (or educational boundaries) ([[@gullicksonPatternsRacialEducational2014]])
	1. Education will increase the likelihood of interracial marriage among blacks but will decrease the likelihood of interracial marriage among whites.
	2. This has nothing to do with the level of education of the potential partner.
2. **Dyadic exchange**
	- White partners in interracial marriages are expected to be more educationally hypergamous and less educationally hypogamous than white partners in intraracial marriage, and vice versa for black partners.
-

*Hypothesis 2:* Status exchange is weaker among cohabitations than marriages.

### Data and analytic strategy

Data: IPUMS 1980, 1990, and 2000, ACS (pooled from five years between 2008 and 2012)

Education: *high school or less*, *some college*, and *bachelor or above*

Race: *non-Hispanic white*, and *non-Hispanic black*

Hypergamy ratio captures any *excess observed white educational hypergamy* in interracial couples compared with what would be predicted by a model under random sorting ([[@kalmijnEducationalInequalityHomogamy2010]]).

Market and dyadic exchanges are distinguished by:

$$\log(F_{ijkl}) = HE_i + WE_j + HR_k + WR_l + 
(HE_i * HR_k) + (WE_j * WR_l) + (HE_i * WE_j) + 
(HR_k * WR_l) + 
\sum_{p=1}^z \eta_p u_{pij} + \sum_{q=1}^z \delta_q w_{qij} + \tau(x_{ijkl}) + \gamma(y_{ijkl})$$
$$u_{pij} = \begin{cases}
1 \text{ if } (i > p \text{ and BM/WF}) \text{ or } \\
\quad (j > p \text{ and WM/BF}) \\
0 \text{ otherwise}
\end{cases}

w_{qij} = \begin{cases}
1 \text{ if } (i > q \text{ and BM/WF}) \text{ or } \\
\quad (j > q \text{ and WM/BF}) \\
0 \text{ otherwise}
\end{cases}$$
$$x_{ijkl} = \begin{cases}
1 \text{ if } (i > j \text{ and BM/WF}) \text{ or } \\
\quad (j > i \text{ and WM/BF}) \\
0 \text{ otherwise}
\end{cases}

y_{ijkl} = \begin{cases}
1 \text{ if } (i < j \text{ and BM/WF}) \text{ or } \\
\quad (j < i \text{ and WM/BF}) \\
0 \text{ otherwise}
\end{cases}$$

### Findings

Descriptive findings
- Among white men, the probability of marrying a black women rises from 0.08% among those born around 1950 to 0.7% for those born around 1980.
- Among while women, the increase is from 0.3% to 1.5%.
- In 1980, 4% of black men and 1% of black women married a white partner; by 2010, as many as 15% of black men and 8% of black owmen married interracially.
- A decline in the proportion of interracial marriages formed by a black man and a white women, from 81% to 69% among marriages and from 87% to 79% among cohabitations.

Status exchange
- White wives in interracial marriages are much more likely to be educationally hypergamous than their counterparts in intraracial marriages, which did not decrease over time.
- The finding is nearly identical among cohabiters.
- Exchange in weaker among white male/black female unions. 

Market vs. dyadic exchange
- Educational boundaries are largely significant and positive for black men. As thier education increases, the chances of having a white wife substantially increase.
- White wives' educational boundaries became stronger, signaling a growing avoidance of black men as the education of white men increases.
- No indication of excess white hypergamy after the educational boundary component of exchange has been accounted for.
