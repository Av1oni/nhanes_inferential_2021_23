# nhanes_inferential_2021_23
NHANES 2021-2023 Inferential Analytics Assignment 507

## Note Book Link


## Q1 Is there an association between marital status (married or not married) and education level (bachelor’s degree or higher vs. less than a bachelor’s degree)?

# A chi-square test was used to look at whether marital status is related to education level. The results showed a significant relationship between the two, meaning marital status and education are not independent of each other (p < 0.001). Overall, married adults were more likely to have a bachelor’s degree or higher, while adults who were not married were more likely to have less than a bachelor’s degree. Even though the effect size was small, this difference is still meaningful given the large national sample used in NHANES.

## Q2 Is there a difference in mean sedentary behavior time between those who are married and those who are not married?

# A Welch’s t-test was used to compare average sedentary time between married and not married adults. The results showed a statistically significant difference between the two groups (p < 0.001). On average, adults who were not married reported spending more time in sedentary activities per day compared to those who were married. This difference is small but consistent, especially given the large sample size.

## Q3 How do age and marital status affect systolic blood pressure?

# A linear regression was used to examine how age and marital status are related to systolic blood pressure. Age was a strong and statistically significant predictor, with systolic blood pressure increasing as age increased. After adjusting for age, marital status was also significantly associated with systolic blood pressure, with married adults having slightly lower systolic blood pressure compared to those who were not married. Overall, age had a much larger influence on systolic blood pressure than marital status.

## Q4 Is there a correlation between self-reported weight and minutes of sedentary behavior?

# A Pearson correlation was used to examine the relationship between self-reported weight and sedentary behavior. The results showed a statistically significant but weak positive correlation (r ≈ 0.16), indicating that higher self-reported weight was associated with slightly more sedentary time. While the relationship is not strong, it is consistent across the large NHANES sample and suggests a general trend rather than a large effect.

## Q5 
## Is there an association between marital status and reporting weak or failing kidneys?

# A chi-square test was used to examine whether marital status is associated with reporting weak or failing kidneys. The results showed a statistically significant association between marital status and kidney health status (p = 0.003). Not married adults were slightly more likely to report weak or failing kidneys compared to married adults. However, the effect size was very small (Cramér’s V = 0.03), suggesting that marital status alone explains very little of the variation in reported kidney problems.