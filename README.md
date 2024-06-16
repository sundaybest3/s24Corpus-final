# s24Corpus-final project

Written by Jungmin Choi 

## 1. Introduction
This study 
## 2. Literature review

RQ. Is there a significant difference in the use of the "passive voice + by + agent" construction between spoken and written materials?

## 3. Methodology

1) Select spoken and written language data. 
For spoken language data, scripts of TED video clips are used. The most-viewed TED speeches are refined, mostly delivered by native(-like) speakers. 
For written language data, NOW Sample Data from COCA are used. The Now Corpus is the only structured corpus that shows what is actually happening in language -- virtually right up to the present.

(a) Spoken data: 
+ 100 Scripts of Most viewed TED video clips from the area of "Communication"
+ Excluded some clips that are of the same speaker, too long, have certain performances during their speech or have more than one speaker.
+ Removed time stamps in the format "00:00" and words that are written in the format of stage directions such as (laughs), (applauds), etc.

(b) Written data
+ The NOW corpus containing 2916 texts, 1.7 million words of data from web-based newspapers and magazines from 2010 to 2016.
+ Removed unnecessary characters such as "@", < p >, and < h >.
+ Split Text ID from the texts.

2) Find occurrences of passives and passives with agent from spoken and written language data.
3) Conduct a chi-square test of independence to see if there is a significant association between types of language(spoken vs written) and types of passive construction(without agent vs. with agent).
(a) Null hypothesis: Types of language(spoken vs written) are independent of types of passive construction(without agent vs. with agent).
(b) Alternative hypothesis: There is a dependence between types of text and types of passive construction.

Detailed process: https://github.com/sundaybest3/s24Corpus-final/blob/main/Corpus/NLTK_spokenwritten.ipynb

## 4. Result and discussion
The objective of this analysis was to determine whether there is a significant association between types of language and occurrences of passives without agent and with agent. 
In both spoken and written language data, passive constructions without an agent appeared overwhelmingly more frequently than those with an agent, with approximately 1% more usage observed in the written language data.  

![Occurences_comparison](https://github.com/sundaybest3/s24Corpus-final/assets/163014658/6c99138b-2cc0-4931-9699-417b2a56998f)


# Results of Passive Construction Analysis 
| Category                        | Occurrences  | Percentage |
|---------------------------------|--------------|------------|
| Spoken passives without agent   | 629          | 96.32%     |
| Spoken passives with agent      | 24           | 3.68%      |
| Written passives without agent  | 9255         | 95.39%     |
| Written passives with agent     | 447          | 4.61%      |

A contingency table was constructed from the results of analysis to cross-tabulate the occurrences of passives with and without agent by types of language data (spoken and written). The contingency table and expected frequencies were as follows: 

# Chi-Squared Test Results
| Statistic                  | Value                |
|----------------------------|----------------------|
| Chi-squared statistic      | 0.8868529837026333   |
| p-value                    | 0.34633154664298904  |
| Degrees of freedom         | 1                    |

# Expected Frequencies
| Category                   | Spoken Expected | Written Expected |
|----------------------------|-----------------|------------------|
| Passives without agent     | 614.6761165     | 9216.3238835     |
| Passives with agent        | 29.3238835      | 439.6761165      |

The Chi-squared test of independence was applied to assess if the observed occurrences of passive types across data of two types of language were statistically significant (($\chi^2 = 0.887, DoF = 1, $p = 0.346). The p-value of 0.346 suggests that there is no significant difference between the language types and occurrences of passives with or without agent. The observed frequencies do not deviate significantly from the expected frequencies. 

## 5. Summary and future research
The chi-squared test shows no significant difference between the spoken and written language data regarding the occurrence of passives without agent and passives with agent. Further qualitative analyses or context-specific investigations needs to be conducted to identify patterns or differences that may not be apparent in the overall data. Furthermore, since passive voice is used heavily in academic and formal settings, it is worth looking at other data in different areas to understand the usage patterns better. 

## References (APA style) 
