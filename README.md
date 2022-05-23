# SAT/ACT

## Problem Statment:

- Since the ACT/SAT College Board has used these standardized testing scores for admission rank into colleges. However, after changing the format of the SAT participation and average scores in every state has changed year. My analysis aims to explore these specific changes in the performance of the SAT/ACT. I aim to assist College board gaining information regarding this change and supply answers to where College Board should focus SAT/ACT prep-course assistance.

## ACT Data Dictionary:

### ACT_2017_clearned

| Field Name        | Type   | Description                     |
| ----------------- | ------ | ------------------------------- |
| **State**         | string | States Name                     |
| **Participation** | float  | Percent of Participation of ACT |
| **Composite**     | float  | Average Composite Score of ACT  |

### ACT_2018_clearned

| Field Name        | Type   | Description                     |
| ----------------- | ------ | ------------------------------- |
| **State**         | string | States Name                     |
| **Participation** | float  | Percent of Participation of ACT |
| **Composite**     | float  | Average Composite Score of ACT  |

### ACT_2019_clearned

| Field Name        | Type   | Description                     |
| ----------------- | ------ | ------------------------------- |
| **State**         | string | States Name                     |
| **Participation** | float  | Percent of Participation of ACT |
| **Composite**     | float  | Average Composite Score of ACT  |

## SAT Data Dictionary:

### SAT_2017_clearned

| Field Name        | Type   | Description                     |
| ----------------- | ------ | ------------------------------- |
| **State**         | string | States Name                     |
| **Participation** | float  | Percent of Participation of SAT |
| **Total**         | float  | Average Total Score of SAT      |

### SAT_2018_clearned

| Field Name        | Type   | Description                     |
| ----------------- | ------ | ------------------------------- |
| **State**         | string | States Name                     |
| **Participation** | float  | Percent of Participation of SAT |
| **Total**         | float  | Average Total Score of SAT      |

### SAT_2019_clearned

| Field Name        | Type   | Description                     |
| ----------------- | ------ | ------------------------------- |
| **State**         | string | States Name                     |
| **Participation** | float  | Percent of Participation of SAT |
| **Total**         | float  | Average Total Score of SAT      |

## Quick Proceess Summary:

1.  I initially ran a Profile Report within my jupyter notebook using the pandas library https://github.com/ydataai/pandas-profiling. I found that it was unnecessary to my understanding of the problem because a lot the data was incomplete 2017 ACT and SAT data had more specific metrics to the averages of each state (ACT: English, math, reading, science, SAT: Evidence Based, math).
2.  This led me to believe that the best approach to analyzing these datasets was to focus on the ACT composite score and SAT Total Scores along with Participation Percentages.
3.  After Cleaning my data to be in the format stated in the Data Dictionaries. I was able to graph: descriptive variables, heat maps, bar charts to enable me to solve my problem statement
4.  The rest was just wording and formatting the jupyter notebook and google slides.

## Conclusion:

College Board Should put more focus on locations such as Mississippi, Nevada, and South Carolina for ACT Prep Coursework due to their high participation percentage but low testing scores. While for the SAT College Board needs to put more focus on locations such as Delaware, District of Columbia, Idaho due to their low participation and lower composite score. In terms of the SAT new format performance, I believe it is bad. Although, the SAT had recently been changed it seems less and less people are taking the SAT year by year. This might be related to the stigma of the difficulty of the SAT. If this stigma doesn’t change and participation doesn’t increase in another 3 years, I believe another reformat of the SAT should be considered.
