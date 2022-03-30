# School_District_Analysis

## Overview
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once I replace the math and reading scores, Maria would like me to repeat the school district analysis that completed in this module and write up a report to describe how these changes affected the overall analysis.

## Results
The following tasks were accomplished:

### 1. Deliverable 1 - 
![This is an image](https://github.com/AleksKostrycka/School_District_Analysis/blob/main/Resources/Images%20used%20for%20Deliverable%203/Deliverable%201.png?raw=true)

### 2. Deliverable 2 - Repeat the school district analysis and recreate the below metrics. This was completed and compared to the original results from the Module. Results outlined below:

#### The District Summary

<p align="center"> Scores completed in the original Module:</p>

![This is an image](https://github.com/AleksKostrycka/School_District_Analysis/blob/main/Resources/Images%20used%20for%20Deliverable%203/D2%20District%20Summary%20Pre%20Corr.png?raw=true)

<p align="center">Scores redone after Thomas High School reading and math 9th grade scores were replaced with NaN. </p>

![This is an image](https://github.com/AleksKostrycka/School_District_Analysis/blob/main/Resources/Images%20used%20for%20Deliverable%203/D2%20-%20Distric%20Summary%20After%20Corr.png?raw=true)

The district summary was slightly affected by the correction made:
* The average Math Score decreased by 0.01 point to 78.9.
* The % Passing Math decreased by 0.2% to 74.8%.
* The % Overall Passing decreased by 0.3% to 64.9%.

#### The School Summary

<p align="center"> Scores completed in the original Module:</p>

![This is an image](https://github.com/AleksKostrycka/School_District_Analysis/blob/main/Resources/Images%20used%20for%20Deliverable%203/D2%20School%20Summary%20-%20pre%20corr.png?raw=true)

<p align="center">Scores redone after Thomas High School reading and math 9th grade scores were replaced with NaN. </p>

![This is an image](https://github.com/AleksKostrycka/School_District_Analysis/blob/main/Resources/Images%20used%20for%20Deliverable%203/D2%20School%20Summary%20-%20after%20correction.png?raw=true)

The school summary was slightly affected by the correction made:
* The average Reading Score increased by 0.1 point to 83.9.
* The % Passing Math decreased by 0.1% to 93.2%.
* The % Passing Reading decreased by 0.3% to 97.0%.
* The % Overall Passing decreased by 0.3% to 90.6%.

#### The top 5 and bottom 5 performing schools, based on the overall passing rate

<p align="center"> The top 5 and bottom 5 school scores were not affected by the correction made </p>

![This is an image](https://github.com/AleksKostrycka/School_District_Analysis/blob/main/Resources/Images%20used%20for%20Deliverable%203/D2%20Top%205%20and%20Bottom%205%20Schools.png?raw=true)

#### The average math score for each grade level from each school

![This is an image](https://github.com/AleksKostrycka/School_District_Analysis/blob/main/Resources/Images%20used%20for%20Deliverable%203/D2%20Math%20Scores%20by%20Grade.png?raw=true)

#### The average reading score for each grade level from each school

![This is an image](https://github.com/AleksKostrycka/School_District_Analysis/blob/main/Resources/Images%20used%20for%20Deliverable%203/D2%20Reading%20Scores%20by%20Grade.png?raw=true)

As expected the 9th grade math and reading scores are Nan. 

#### The scores by school spending per student

<p align="center"> Scores completed in the original Module:</p>

![This is an image](https://github.com/AleksKostrycka/School_District_Analysis/blob/main/Resources/Images%20used%20for%20Deliverable%203/D2%20Scored%20by%20School%20spending%20before%20corr.png?raw=true)

<p align="center">Scores redone after Thomas High School reading and math 9th grade scores were replaced with NaN. </p>

![This is an image](https://github.com/AleksKostrycka/School_District_Analysis/blob/main/Resources/Images%20used%20for%20Deliverable%203/D2%20Scores%20by%20School%20Spending%20after%20Corr.png?raw=true)

The only change is on the $585-629 range where the % Passing Math decreased by 0.1% from 87.2 to 87.1. The Average Reading score went up .1% from 83.1 to 83.2

#### The scores by school size

<p align="center">There are no notable changes in the school size results </p>

![This is an image](https://github.com/AleksKostrycka/School_District_Analysis/blob/main/Resources/Images%20used%20for%20Deliverable%203/D2%20Scores%20by%20School%20Size%20PRE%20Corr.png?raw=true)

#### The scores by school type

<p align="center">There are no notable changes in the school type results </p>

![This is an image](https://github.com/AleksKostrycka/School_District_Analysis/blob/main/Resources/Images%20used%20for%20Deliverable%203/D2%20Scores%20by%20School%20Type%20.png?raw=true)

## Summary

Replacing the math and reading scores did not imply any major change to the school district analysis.
The scores by grade summary for Thomas High School was obviously changed and displays NaN values for its ninth-graders math and reading scores.
The following metrics were slightly affected by the correction: the district summary, the school summary for Thomas High School, the scores by school spending - however the changes were very small and can be attributable to rounding while presenting the data to the board. 
