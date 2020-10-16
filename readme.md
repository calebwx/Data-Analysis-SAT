# 2017 - 2019 SAT and ACT Scores and Participation Rates

------

### Contents:
- [Problem Statement](#Problem-Statement)
- [Executive Summary](#Executive-Summary)
- [Data Dictionary](#Data-Dictionary)
- [Conclusions](#Conclusions)

---

## Problem Statement

The format of the college entrance exam SAT, administered by College Board, changed to a new format in 2016. Tracking the nation-wide changes and understanding the factors behind those changes is important to the future of the SAT. In particular, we want to see how participation rates have changed over the past three years since the new format was introduces, and look at the specific states where participation has increased, or where participation could likely be improved.

---

## Executive Summary

Data was cleaned with Python and explored with visualizations utilizing the matplotlib and seaborn libraries. From this analysis, states of interest were selected and examined to better understand the changes occuring in participation rates and test scores. Further research was done for a few states to relate changes in state education policy to changes in the data. Select data was compiled for a presentation, included with these files, for a quick overview of the findings.

---

## Data Dictionary

------

|Feature|Type|Dataset|Description|
|---|---|---|---|
**state**|*string*|All Data|The name of the state, including D.C., for which test scores and participation are listed|
**participation_act_17**|*float*|act_2017|Proportion of graduating high school students taking the ACT in 2017|
**english_act**|*float*|act_2017|Average English subtest score of students taking the ACT in 2017|
**math_act**|*float*|act_2017|Average Math subtest score of students taking the ACT in 2017|
**reading**|*float*|act_2017|Average Reading subtest score of students taking the ACT in 2017|
**science**|*float*|act_2017|Average Science subtest score of students taking the ACT in 2017|
**composite_act_17**|*float*|act_2017|Average composite score of students taking the ACT in 2017|
**participation_sat_17**|*float*|sat_2017|Proportion of graduating high school students taking the SAT in 2017|
**english_sat_17**|*float*|sat_2017|Average Evidence-Based Reading and Writing subtest score of students taking the SAT in 2017|
**math_sat_17**|*float*|sat_2017|Average Math subtest score of students taking the SAT in 2017|
**total_sat_17**|*float*|sat_2017|Average total score of students taking the SAT in 2017|
**participation_act_18**|*float*|act_2018|Proportion of graduating high school students taking the ACT in 2018|
**composite_act_18**|*float*|act_2018|Average composite score of students taking the ACT in 2018|
**participation_sat_18**|*float*|sat_2018|Proportion of graduating high school students taking the SAT in 2018|
**english_sat_18**|*float*|sat_2018|Average Evidence-Based Reading and Writing subtest score of students taking the SAT in 2018|
**math_sat_18**|*float*|sat_2018|Average Math subtest score of students taking the SAT in 2018|
**total_sat_18**|*float*|sat_2018|Average total score of students taking the SAT in 2018|
**participation_act_19**|*float*|act_2019|Proportion of graduating high school students taking the ACT in 2019|
**composite_act_19**|*float*|act_2019|Average composite score of students taking the ACT in 2019|
**participation_sat_19**|*float*|sat_2019|Proportion of graduating high school students taking the SAT in 2019|
**english_sat_19**|*float*|sat_2019|Average Evidence-Based Reading and Writing subtest score of students taking the SAT in 2019|
**math_sat_19**|*float*|sat_2019|Average Math subtest score of students taking the SAT in 2019|
**total_sat_19**|*float*|sat_2019|Average total score of students taking the SAT in 2019|

------

## Conclusions

SAT participation has been growing nationwide, largely driven by states that require students to take the SAT in order to graduate high school. If this trend is to continue, the best course of action is to encourage more states to adopt policies requiring students to take a college entrance exam. Schools or states that offer students the ability to take the test during school hours, free of charge, have also seen high participation rates. There are also a number of states with low participation rates in both exams, and leaders, educators, and students in these states could be encouraged to promote the SAT test.