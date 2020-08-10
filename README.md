# Project 1: SAT & ACT Analysis
## Problem Statement
In this project we will be exploring what can data tell us about SAT and ACT participation rates and what College Board can do to increase participation rates.

***

## Executive Summary

The SAT and ACT are widely used standardized tests taken in the US for the purpose of College admission. Data pertaining to these tests were split into state means, and have been thoroughly analyzed.

Through analysis, it has been found that a high participation rate for SAT correlates with a low ACT participation rate, and vice versa. Low participation rates have also been found to correlate with a higher scores all around for that specific test.

Further research has shown that the best way to increase SAT participation is to make it mandatory state-wide.

Datasets have been provided by the team at GA and consists of 'sat_2017.csv', 'act_2017.csv', 'sat_2018.csv', and 'act_2018_updated.csv'

2017 data from provided links have also been compiled into csv files: 'sat_2017_fromweb.csv' and 'act_2017_fromweb.csv'

***

### Contents:
- [2017 Data Import & Cleaning](#2017-Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

***

### Data Dictionary:
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state_act_2017|object|ACT 2017|The state in which the ACT was taken in. Data reflected is from 2017.|
|participation_act_2017	|float|ACT 2017|The ACT participation rate of eligible students in the state  in 2017. This is a percentage value saved as a float, with a maximum value  of 100, which means 100%.|
|english_act_2017|float|ACT 2017|The average score across the state for the english section of the ACT in 2017. This value ranges from 1 to 36.|
|math_act_2017|float|ACT 2017|The average score across the state for the math section of the ACT in 2017. This value ranges from 1 to 36.|
|reading_act_2017|float|ACT 2017|The average score across the state for the reading section of the ACT in 2017. This value ranges from 1 to 36.|
|science_act_2017|float|ACT 2017|The average score across the state for the science section of the ACT in 2017. This value ranges from 1 to 36.|
|composite_act_2017|float|ACT 2017|The average overall ACT score across the state in 2017. This value ranges from 1 to 36 and is obtained by taking the averaging scores from all four sections (english, math, reading, and science).|
|state_sat_2017|object|SAT 2017|The state in which the SAT was taken in. Data reflected is from 2017.|
|participation_sat_2017	|float|SAT 2017|The SAT participation rate of eligible students in the state  in 2017. This is a percentage value saved as a float, with a maximum value  of 100, which means 100%.|
|ebrw_sat_2017|float|SAT 2017|The average score across the state for the evidence-based reading and writing section of the SAT in 2017. This section is basically the SAT equivalent of the ACTs english and reading sections. This value ranges from 200 to 800.|
|math_sat_2017|float|SAT 2017|The average score across the state for the math section of the SAT in 2017. This value ranges from 200 to 800.|
|total_sat_2017|float|SAT 2017|The average overall score across the state for the SAT in 2017. This value ranges from 400 to 1600 and is the sum of the two sections in the SAT (english-based reading and writing, math).|
|state_act_2018|object|ACT 2018|The state in which the ACT was taken in. Data reflected is from 2018.|
|participation_act_2018	|float|ACT 2018|The ACT participation rate of eligible students in the state  in 2018. This is a percentage value saved as a float, with a maximum value  of 100, which means 100%.|
|english_act_2018|float|ACT 2018|The average score across the state for the english section of the ACT in 2018. This value ranges from 1 to 36.|
|math_act_2018|float|ACT 2018|The average score across the state for the math section of the ACT in 2018. This value ranges from 1 to 36.|
|reading_act_2018|float|ACT 2018|The average score across the state for the reading section of the ACT in 2018. This value ranges from 1 to 36.|
|science_act_2018|float|ACT 2018|The average score across the state for the science section of the ACT in 2018. This value ranges from 1 to 36.|
|composite_act_2018|float|ACT 2018|The average overall ACT score across the state in 2018. This value ranges from 1 to 36 and is obtained by taking the averaging scores from all four sections (english, math, reading, and science).|
|state_sat_2018|object|SAT 2018|The state in which the SAT was taken in. Data reflected is from 2018.|
|participation_sat_2018	|float|SAT 2018|The SAT participation rate of eligible students in the state  in 2018. This is a percentage value saved as a float, with a maximum value  of 100, which means 100%.|
|ebrw_sat_2018|float|SAT 2018|The average score across the state for the evidence-based reading and writing section of the SAT in 2018. This section is basically the SAT equivalent of the ACTs english and reading sections. This value ranges from 200 to 800.|
|math_sat_2018|float|SAT 2018|The average score across the state for the math section of the SAT in 2018. This value ranges from 200 to 800.|
|total_sat_2018|float|SAT 2018|The average overall score across the state for the SAT in 2018. This value ranges from 400 to 1600 and is the sum of the two sections in the SAT (english-based reading and writing, math).|

***

## Conclusions and Recommendations
Based on your exploration of the data, what are you key takeaways and recommendations? 

**Answer:**

Key takwaways and recommendations:
* Work with local policy makers to find out what is stopping them from making the SAT mandatory.
    * As shown with Colorado and Illinois, the most effective way to increase participation rate is to make it mandatory for graduating students.
    * Questions to ask: Is the ACT already mandatory? If so, why? What does the ACT offer that the SAT does not? Is there any way to leverage on what the SAT does differently?
    
***

Choose one state with a lower participation rate and provide a suggestion for how the College Board might increase participation amongst graduating seniors in this state.

**Answer:** 

North Dakota has the lowest SAT participation rate out of all the states. After some research, it was found that the ACT is mandatory in North Dakota[[6]](#[6]https://blog.prepscholar.com/which-states-require-the-act-full-list-and-advice). One way that College Board may increase participation amongst graduating seniors is to find out why policy makers have chosen ACT as the mandatory test. 

Another way that College Board could increase participation rates in North Dakota is to find ways to subsidize the test fees. In Illinois, participation rates dramatically increased once the SAT was subsidized by the state[[4]](#[4]https://www.chicagotribune.com/news/ct-illinois-chooses-sat-met-20160211-story.html). College Board could work with the state to find room in the budget, or an alternative would be to subsidize it themselves to increase participation rates. 

***

Are there additional data you desire that would better inform your investigations?

**Answer:**

Information about what % of students in each state took both tests, and also what was the respective average of each score for this group. This will allow us to better understand the relationship between both tests.

***

### References

##### [1]https://www.edweek.org/ew/section/multimedia/states-require-students-take-sat-or-act.html
##### [2]https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/
##### [3]https://www.denverpost.com/2017/03/06/colorado-juniors-sat-college-exam/
##### [4]https://www.chicagotribune.com/news/ct-illinois-chooses-sat-met-20160211-story.html
##### [5]https://reports.collegeboard.org/pdf/2018-florida-sat-suite-assessments-annual-report.pdf
##### [6]https://blog.prepscholar.com/which-states-require-the-act-full-list-and-advice