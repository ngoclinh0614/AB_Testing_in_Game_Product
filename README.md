# Cookie Cats Player Retention Analysis

## Introduction
This repository contains the code, data, and documentation for a project aimed at increasing player retention in the mobile puzzle game Cookie Cats. The objective was to investigate the impact of changing the number of levels required to open the first gate from 30 to 40 on player retention rates. The project was conducted as part of a course, and the necessary data was already available for analysis.

## Hypothesis
- The hypothesis stated that changing the number of levels required to open the first gate would impact player retention rates. Key metrics for evaluating user retention included: 
  - sum of game rounds played
  - retention rate after 1 day installed
  - retention rate after 7 days installed.
- The control group consisted of users playing the 30-level version (group A), while the treatment group played the 40-level version (group B)
Therefore, we have to check 3 different hypotheses:
> Hypothesis 1:
  - H0: mean of sum_of_game_round_group_A = mean of sum_of_game_round_group_B
  - H1: mean of sum_of_game_round_group_A >< mean of sum_of_game_round_group_B
> Hypothesis 2:
  - H0: retention_rate_after_1day_of_group_A = retention_rate_after_1day_of_group_B
  - H1: retention_rate_after_1day_of_group_A >< retention_rate_after_1day_of_group_B
> Hypothesis 3:
  - H0: retention_rate_after_7day_of_group_A = retention_rate_after_7day_of_group_B
  - H1: retention_rate_after_7day_of_group_A >< retention_rate_after_7day_of_group_B
- The project focused on individual players as the randomization unit, although the specific target population was not defined. Segmenting or grouping players based on characteristics such as gender, age, and device type would have ensured the results were not influenced by other factors.

## Data Collection
- Data collection involved gathering the necessary data for analysis.
- The test duration typically lasted 1-2 weeks.
- The sample size was determined based on the desired significance level, power of the test, and effect size.
- Statistical methods, such as the Shapiro test for normality and Levene's test for homogeneity, were employed in the data analysis. Assumptions made during the analysis could have had an impact on the results.

## Results
- The results showed that the p-value for the sum of game rounds was 0.03, retention after 1 day was 0.09, and retention after 7 days was 0.0002.
- With the given data and a significance level of 0.05, the null hypothesis was clearly rejected for retention after 7 days and the sum of game rounds which means there are significant impact on the retention rate after 7 days and the number of game rounds when changing the number of levels required to open the first gate. 
- The null hypothesis could not be rejected for retention after 1 day.


