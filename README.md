# IOS Store Monetization Experiment Design Capstone Project
## A/B testing
### Author: Yunjia Xu

Introduction: 

We can increase average spend per user or conversion rate to increase entire store's revenue for next year. After exploratory data analysis, I found that average spend and conversion rate are both highest if users added gift card as the form of payment. So my hypothesis is that if we incentivize users to add gift card, they may be more likely to click buy and purchase more in the future.

Experiment:

North star: total spend per day.
Target population: users who see the 'click buy', and spend is lower than $300.
Treatment: show additional message "You can also buy with gift card".
Approach: Two sample t-test comparing two 5% groups.
Duration: 1 week.

Result:
statistic=2.88, p-value=0.003967<0.05
We can reasonably sure that average spend of treatment group is significantly more than that of control group with 95% confidence.


