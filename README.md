# SAT - ACT Analysis

## Executive Summary
1. Problem statement
    The SAT dataset is showing statistics related to the SAT test for each state in the U.S. from years 2017, 2018, and 2019.The SAT is a standardized test widely used for college admissions in the United States. The SAT has four sections: Reading, Writing and Language, Math (no calculator), and Math (calculator allowed). These datasets take data from years 2017 to 2019.

    The ACT dataset is showing statistics related to the ACT test for each state in the U.S. from years 2017, 2018, and 2019. The ACT is a standardized test used for college admissions in the United States that covers four academic skill areas: English, mathematics, reading, and science reasoning. The main four ACT test sections are individually scored on a scale of 1–36, and a composite score is the rounded whole number average of the four sections. 

    With these datasets, we are trying to find correlations and trends related to SAT and/or ACT participation rates in specific states, to determine a way to improve participation rates within these states. To do this, we will thoroughly analyze this data using pandas, matplotlib, seaborn, numpy, and other tools to draw our conclusions

2. Description of data

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|one of the 50 U.S. states of the United States| 
|participation_SAT / participation_ACT|float|ACT/SAT|percentage of students in the class of {year} that took the specified test (units percent to two decimal places 98.10 means 98.1%)| 
|ebrw_sat|int|SAT|scores for evidence-based reading and writing (total score = 800)| 
|math_sat|int|SAT|scores for mathematics (total score = 800)|
|total_sat|int|SAT|total score for the SAT out of 1600 points| 
|english_act|float|ACT|english scores. (scaled from 1-36)| 
|math_act|float|ACT|mathematics scores. (scaled from 1-36)|
|reading_act|float|ACT|reading scores. (scaled from 1-36)|
|science_act|float|ACT|science scores. (scaled from 1-36)|
|composite_act|float|ACT|total score. (average of four test scores.)|

3. Primary findings/conclusions/recommendations
    
    Key Recommendations: Collect more data. For example, math without a calculator would be more correlated with a student’s natural ability, whereas scores of math without a calculator would be more correlated with rote memorization. If we see lower scores without a calculator than we would see that the problem likely has to do with teaching, and systems within the school system than a population’s natural ability. If possible, collect more data about the students themselves, and their personal data. Including what classes they took, which schools they are in, proximity of universities, average income, etc.


Key takeaways:
1. ACT participation is higher than SAT.
2. States that do well or have high participation rates on one test, rarely have the same or similar results for the other test.
3. Government and educational policy has a major impact on participation rates.
4. Improved and more targeted data collection could aid analysis drastically.


