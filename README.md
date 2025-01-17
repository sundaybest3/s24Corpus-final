# Analyzing Passive Voice Usage: A Study of Spoken and Written English in TED Talks and NOW Corpus

Written by Ana. J. Choi

## 1. Introduction
  When we learn the passive voice, we understand that the subject of a passive sentence is the object of the corresponding active sentence, and the verb takes the form of 'be + past participle.' The agent, or the subject of the active sentence, is indicated by 'by + agent' or commonly omitted. During this process, we often encounter sentences with agents that are unlikely to be used in everyday situations.

In casual conversation and writing, the active voice predominates. However, in formal writing, it is recommended to use objects as the subjects rather than 'I,' and this form is often used in formal speech as well. Therefore, the passive voice is frequently employed, making it essential to learn its correct usage. This study aims to study the usage of passive voice with agents, beginning by examining how often this form appears in both spoken and written language.

## 2. Literature review
Paul Mathieson (2017) covered the use of the passive voice in English in six aspects -- (1) the passive syntax, (2) the be-passive, (3) the get-passive, (4) pseudo-passives, (5) the agent phrase, (6) verbs which cannot be used in passive form. The active voice is the most common form of expression in English, and is usually adopted where the 'agent' -- or doer -- of the action is the focal point (Paul Mathieson). However, as Huddlestone and Pullum (2002) point out, passive clauses place the grammatical subject in the position of 'patient', or the recipient of the action (p. 1427). The be-passive occurs in a variety of different tense and aspect combinations in English, making the most commonly used passive voice form. The get-passive is also used in a range of forms, although, as Quirk et al. (1985) highlight, it “is avoided in formal style, and even in informal English it is far less frequent than the be-passive” (p. 161). The pseudo-passives can be read as an adjectival complement phrase. Still, in this analysis, they will be considered as a passive structure since they take the form of the be or get + past participle. 

Several studies have examined the various types of passive constructions. For instance, Parrott (2010) distinguishes between standard passive constructions, which primarily use the "be + p.p." form, and causative passive constructions that can also use "get" as an auxiliary verb. Research has shown that the "get-passive" often emphasizes the subject's experience or a change of state, such as in "He got promoted" (Parrott, 2010). Ayoob (2020) further explores these constructions, noting the prevalence of both "be + p.p." and "get + p.p." forms in English passive structures. Given the predominance of "be + p.p." and "get + p.p." constructions in both academic literature and practical usage, this research will focus exclusively on these two types. This approach ensures a comprehensive analysis of the most commonly used passive forms while excluding less frequent constructions that may introduce unnecessary complexity (Ayoob, 2020; Parrott, 2010).

In the exploration of passive constructions in English, particularly those involving the "be + past participle" (be + p.p.) form, it is essential to distinguish between dynamic passive (actional passive) and statal passive (statal passive) constructions. Lee (2016) explains that the dynamic passive emphasizes a past action or event, such as "He was buried by his wife," where the focus is on the specific action carried out. In contrast, the statal passive highlights a current state resulting from an action, as seen in "He is buried in Mangwoo-ri," where the emphasis is on the resultant state. These constructions generally employ the "be + past participle" format, but they differ in their temporal and prepositional characteristics. Dynamic passives can accommodate adverbial modifiers like "immediately," while statal passives do not, as illustrated by the correct usage of "He was immediately surrounded by many people" versus the incorrect "*He was immediately surrounded with many people." Given these nuances, it is clear that the preposition "by" uniquely indicates the agent of an action in dynamic passives. Consequently, this research will exclusively consider "by" when identifying the agent in "be + p.p." constructions, disregarding other prepositions that do not serve this function. This focus ensures a precise analysis of agentive passive constructions without the confounding influence of prepositions used for other purposes.

In 'A Student's Grammar of the English Language', Greenbaum and Quirk identified 7 reasons why speakers and writers use the passive:
+ 1 They do not know the identity of the agent of the action. 
+ 2 They want to avoid identifying the agent in purpose.
+ 3 They feel there is no reason for mentioning the agent because the identification is unimportant or obvious.
+ 4 In scientific and technical writing, they need to avoid the constant use of the subject I or we and to put the emphasis on processes and experimental procedures.
+ 5 To put emphasis on the agent of the action
+ 6 To put long active agent on the end
+ 7 To retain the same subject throughout a long sentence
  
Reasons 1-4 illustrate the uses of the passive without the agent by-phrase, which is commonly omitted, and in reason 5-6, the passive voice provides a way of postponing the agentive subject by turning it into the agent in a passive construction. We thus reverse the active order of the agentive and affected elements where the agentive requires end-focus. This study focuses on the use of passives related to reason 5-6 to investigate passives with explicit agents. 

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
The chi-squared test shows no significant difference between the spoken and written language data regarding the occurrence of passives without agent and passives with agent. Further qualitative analyses or context-specific investigations needs to be conducted to identify patterns or differences that may not be apparent in the overall data. Patterns of different uses of prepositions may be included. Furthermore, since passive voice is used heavily in academic and formal settings, it is worth looking at other data in different areas to understand the usage patterns better. 

## References (APA style) (Miran comment: see how to italicize texts in md file)
Ayoob, T. M. (2020). _A Descriptive Study of Passive Constructions in English_. Journal of World Englishes and Educational Practices, 2(1), 1-6.

Greenbaum, S., & Quirk, R. (1990). _A student's Grammar of the English Language_. Longman Publishing Group.

Lee, G. (2016). _영어 태(English Voice)의 개념과 지도방안: 수동태와 중간태를 중심으로_. 충남대학교 

Mathieson, P. (2017). _Secret agents and innocent patients: The mysteries of the English passive voice and its use (and misuse) in EFL writing in Japan_. Journal of Pan-Pacific Association of Applied Linguistics.

Parrott, M. (2010). _Grammar for English Language Teachers_. Cambridge University Press.

Quirk, R., Greenbaum, S., Leech, G., & Svartvik, J. (1985). _A comprehensive grammar of the English language_. Longman.


