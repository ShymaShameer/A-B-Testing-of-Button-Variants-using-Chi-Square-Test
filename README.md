# A-B-Testing-of-Button-Variants-using-Chi-Square-Test
Project Overview
This project analyzes the performance of four button variations on the Eniac website using Chi-Square hypothesis testing in Python.

The goal was to determine whether different button designs lead to statistically significant differences in user behavior, primarily focusing on click-through rates (CTR), while also considering user engagement metrics.

**Objective**
* Identify whether any button variant significantly outperforms others in terms of CTR
* Use statistical testing to validate results
* Support decision-making with additional behavioral metrics
  
**Variants Tested**
A - White “SHOP NOW”
B - Red “SHOP NOW”
C - White “SEE DEALS”
D - Red “SEE DEALS”

**Metrics Used**
1. Click-Through Rate (Primary Metric)
  * CTR = Total Clicks / Total Visits
  * Measures how effectively the button drives user interaction
  * Used for statistical significance testing
2. Drop-Off Rate (Secondary Metric)
  * Percentage of users who start but do not complete a conversion
  * Indicates how well users stay engaged after clicking
  * Lower is better
3. Homepage Return Rate (HRR)
  * Measures how often users return to the homepage after clicking
  * Indicates whether users find relevant content after clicking
  * Lower is better

**Methodology**
* Conducted Chi-Square Test of Independence
* Performed post-hoc analysis with Bonferroni correction
* Analysis implemented in Python

**Key Insights**
* A and C perform similarly in CTR (not statistically different)
* C attracts more clicks but loses users quickly
* A provides better overall user engagement
* D significantly underperforms across key metrics

**Conclusion**
* No single statistically dominant winner was identified
* Versions A and C belong to the top performance tier
* Version A is more balanced, while C is more attention-grabbing but less effective post-click

**Next Steps**

To identify a definitive winner, further actions are recommended:
  * Consider additional metrics beyond CTR
  * Incorporate qualitative user research
  * Consult subject-matter experts
  * Redesign and rerun the experiment

**Tools & Technologies**
* Python
* NumPy
* SciPy (chi2_contingency)
* Statistical Hypothesis Testing
