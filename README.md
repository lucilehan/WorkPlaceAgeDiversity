# Workplace Age Diversity Analysis
In this capstone project, I uncover the best and worst source of talent acquisition for promoting Workplace Age Diversity. I also try to see if there is a meaningful statistical difference in the sample means of work performance scores between commonly represented and under-represented age groups. 
Although the data set used here is synthetic, with similar information available, the following analysis can be repeated and applied to companies looking to improve their age diversity profiles. The .csv file of the data set used can be found [here](data/hr-dataset-v14.csv) and the original Kaggle introduction by Dr. Rich Huebner and Dr. Carla Patalano can be found [here](https://www.kaggle.com/rhuebner/human-resources-data-set). 
 
**Goal**

I was able to boil down to a couple of recruitment sources that contribute to more inclusive age representations via basic exploratory data analysis, but why should the company care? One might argue that the Represented age group is the most qualified in terms of their work abilities, thus dismissing the need to re-evaluate current recruiting practices.
This assumes an inevitable decline in work abilities of both young and older workers, thus justifies using age as a “proxy” for inferior job performance. I was curious to see if these assumptions are statistically valid.
 
**Hypothesis**

I ran the ttest_ind() function to perform 3 separate t-tests for the two age groups I identified earlier in my data analysis. The three features I tested are ```PerfScoreID```, ```DaysLateLast30```, and ```Absences```. The null hypothesis was that there is no difference between these two samples’ means. A low p-value would negate this null hypothesis.
 
**Results**

All three t-tests I ran had a large p-value at p<.05 confidence level, thus failing to reject the three null hypotheses that there is no significant difference between the means.
At large, the results revealed that contrary to many negative implications of age and job performance, there is not a significant difference in work quality between the two age groups. This of course assumes that good work quality can be expected from combinations of the three specific conditions I decided to base my study on (high performance scores, low tardiness, and low absences).
 
**Final Note**

Workplace Age Diversity creates opportunities for the organization to leverage the unique backgrounds and characteristics of all employees to contribute to its success. This notebook features some key findings in regards to Workplace Age Diversity.

1. Diversity Job Fair and Employee Referrals are the best available sources of recruitment from a workplace Age Diversity standpoint.
2. We should digress from the current social network-centric approach to talent acquisition to a more diversity-centric, age-friendly approach to recruitment.
3.  There are no statistically significant differences in the means of ```PerfScoreID```, ```DaysLateLast30```, and ```Absences``` between the commonly represented and under-represented age groups, thus invalidating the argument that the under-represented are 'unqualified.'

Future studies for this particular company on mixed-age work teams should focus on demonstrating how the age diversity climate within an organization could have the potential to improve performance and lower employee turnover.
 
 
 
 
 
 
 
 
 
 
 
 
 

