# ![](https://www.google.com/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwiXgbP_jsLmAhWTwjgGHcljDjMQjRx6BAgBEAQ&url=https%3A%2F%2Fwww.insidehighered.com%2Fadmissions%2Farticle%2F2019%2F03%2F11%2Fcollege-board-calls-sat-three-countries&psig=AOvVaw0YIF6uj4b44HXt4FF36KpV&ust=1576858813708886) Project 1: Standardized Testing, Statistical Summaries and Inference

## Problem Statement

There are still potential for SAT participation rate to increase across all states. Given the data set of SAT and ACT in 2017 and 2018, we hope to identify insightful trend to suggest effective measures to implement to increase participation rate; especially in states with low SAT participation rate. 


## Executive Summary

### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)


## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|SAT|The state of USA with students participated in SAT & ACT| 
|**17_sat_part**|*float*|SAT|The 2017 participation rate of students of each state for SAT|
|**17_sat_ebrw**|*float*|SAT|The 2017 average score of Evidence-Based Reading and Writing for each state|
|**17_sat_math**|*float*|SAT|The 2017 average score of Math for each state|
|**17_sat_total**|*float*|SAT|The 2017 average total score of SAT for each state|
|**18_sat_part**|*float*|SAT|The 2018 participation rate of students of each state for SAT|
|**18_sat_ebrw**|*float*|SAT|The 2018 average score of Evidence-Based Reading and Writing for each state|
|**18_sat_math**|*float*|SAT|The 2018 average score of Math for each state|
|**18_sat_total**|*float*|SAT|The 2018 average total score of SAT for each state|
|**17_act_part**|*float*|ACT|The 2017 participation rate of students of each state for ACT|
|**17_act_english**|*float*|ACT|The 2017 average score of English for each state|
|**17_act_math**|*float*|ACT|The 2017 average score of Math for each state|
|**17_act_reading**|*float*|ACT|The 2017 average score of Reading for each state|
|**17_act_science**|*float*|ACT|The 2017 average score of Science for each state|
|**17_act_composite**|*float*|ACT|The2017  average composite score of ACT for each state|
|**18_act_part**|*float*|ACT|The 2018 participation rate of students of each state for ACT|
|**18_act_english**|*float*|ACT|The 2018 average score of English for each state|
|**18_act_math**|*float*|ACT|The 2018 average score of Math for each state|
|**18_act_reading**|*float*|ACT|The 2018 average score of Reading for each state|
|**18_act_science**|*float*|ACT|The 2018 average score of Science for each state|
|**18_act_composite**|*float*|ACT|The2018  average composite score of ACT for each state|


## Distributions Summary

|Variable|Mean|STD|Q1|Q2|Q3|Min|Max|Description based on statistics & boxplot|
|---|---|---|---|---|---|---|---|---|
|**17_sat_part**|40|35|4|38|66|2|100|Distribution is skewed to the right with a wide spread data from mean|
|**17_sat_ebrw**|569|45|533|559|613|482|644|Distribution is slightly skewed to the left|
|**17_sat_math**|557|47|523|548|599|468|651|Distribution is not skewed|
|**17_sat_total**|1126|93|1055|1107|1212|950|1295|Distribution is not skewed|
|**18_sat_part**|46|37|5|52|78|2|100|Distribution is skewed to the right with a wide spread data from mean|
|**18_sat_ebrw**|564|48|535|552|611|180|643|Distribution is slightly skewed to the left|
|**18_sat_math**|556|48|522|544|594|480|655|Distribution is not skewed|
|**18_sat_total**|1120|94|1058|1098|1204|977|1298|Distribution is not skewed|
|**17_act_part**|65|32|31|69|100|8|100|Distribution is skewed to the left with a wide spread data from mean|
|**17_act_english**|21|2|19|20|23|16|26|Distribution is not skewed|
|**17_act_math**|21|2|19|21|23|18|25|Distribution is slightly skewed to the right|
|**17_act_reading**|22|2|21|22|24|18|26|Distribution is slightly skewed to the left|
|**17_act_science**|22|2|20|21|23|18|25|Distribution is not skewed|
|**17_act_composite**|22|2|20|21|24|18|26|Distribution is not skewed|
|**18_act_part**|61|34|29|66|100|7|100|Distribution is skewed to the left with a wide spread data from mean|
|**18_act_english**|21|3|19|20|24|17|26|Distribution is not skewed|
|**18_act_math**|21|2|19|21|23|18|25|Distribution is slightly skewed to the right|
|**18_act_reading**|22|2|21|22|24|18|26|Distribution is not skewed|
|**18_act_science**|21|2|18|20|21|23|25|Distribution is not skewed|
|**18_act_composite**|22|2|20|21|24|18|26|Distribution is not skewed|


## Conculstion/Recommendation

Based on the hypothesis testing, there may be a higher probability that the difference between the mean participation rate of SAT and ACT is decreasing. We also know from our dataset that the mean participation rate of ACT dropped from 65 to 61 and mean participation rate of SAT increased from 40 to 46. Hence we can infer that there is a trend in USA with more and more students taking up SAT. 

Our previous analysis of the 3 states (Colorado, Florida and New York) showed that SAT's wavier and allowing students to take exam during schol days program have increased the popularity of SAT effectively. 

Hence, the focus of the colleage board should be targeting a state that has not yet make ACT mandatory with low SAT participation rate, which is the state of Iowa. The following recommendation are made based on the Every Student Succeeds Act requirement signed by President Obama in 2015. [Source](https://www.ed.gov/esea)

**Recommendation on increasing participation rate in Iowa:**

1) Widen the wavier eligibility of students to more lower income group

2) Consider providing more support in terms of preparing for SAT exam to lower income group, especially in math and science (where the average scores are lower than that of Evidence-Based, Reading and Writing)

3) Reach out to minority group such as black african american and provide equity opportunity to the groups to take SAT

4) Create awareness about SAT's inclusive program to state government and universities in Iowa


### References:

1. Chalkbeat.org : 
    https://www.chalkbeat.org/posts/co/2015/12/23/goodbye-act-hello-sat-a-significant-change-for-colorado-high-schoolers/
    https://chalkbeat.org/posts/ny/2018/01/11/record-number-of-new-york-city-students-take-sat-after-city-offers-test-for-free/

2. Washinton Post: https://www.washingtonpost.com/local/education/sat-usage-declined-in-29-states-over-7-years/2014/03/15/f4504cfc-a5ff-11e3-8466-d34c451760b9_story.html

3. Orlando Sentinal: https://www.orlandosentinel.com/news/education/os-ne-act-sat-florida-scores-20181024-story.html

4. US Department of Education: https://www.ed.gov/esea