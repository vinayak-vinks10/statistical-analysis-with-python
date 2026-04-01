A/B Testing Analysis – Cookie Cats Case Study:

This project focuses on understanding how statistical methods can be used to make data-driven decisions. Using a real-world mobile game dataset, the goal is to analyze whether changing the game level gate from 30 to 40 has any meaningful impact on player retention.

Objective:

The main objective of this project is to compare two versions of a game and determine whether the new version improves user retention or if the observed difference is just due to random variation.

Approach:

The dataset was divided into two groups — gate_30 (control group) and gate_40 (test group). The analysis was carried out in a structured way:

Explored and understood the dataset
Compared retention rates between both groups
Applied hypothesis testing (two-proportion Z-test)
Calculated confidence interval for deeper statistical insight
Visualized the results using graphs

Key Findings:

The analysis showed a slight difference in retention between the two groups, but:

The p-value was greater than 0.05, meaning the result is not statistically significant
The confidence interval included zero, indicating that the true difference could be zero

👉 This suggests that the observed change in retention may simply be due to random chance rather than an actual improvement.

Conclusion:

Based on statistical testing and analysis, there is no strong evidence to support that changing the game level from 30 to 40 improves player retention. While a small difference was observed, it is not reliable enough to make a confident decision.

Tech Stack:
Python
Pandas, NumPy
Matplotlib
Statsmodels

Learning Outcome:

Through this project, I gained a clear understanding of how statistical concepts like hypothesis testing and confidence intervals are applied in real-world scenarios to validate decisions using data.