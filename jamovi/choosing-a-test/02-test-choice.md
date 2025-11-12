---
layout: default
title: Choosing the Correct Statistical Test
---

<div class="explanation" markdown="1">
## Choosing the Correct Statistical Test

Selecting the right statistical test can be challenging. The correct choice depends on three key things:

1.  **Your research question:** Are you looking for differences between groups, changes within a group over time, or relationships between variables?
2.  **The number of groups or variables** you are comparing.
3.  **The level of measurement** of your data (Nominal, Ordinal, or Continuous).

These tables will guide you to the correct test for common, single-factor research designs.
</div>

---

### Table 1: Tests for Differences **Between** Groups

Use this table when you are comparing scores from two or more separate, independent groups (e.g., comparing an experimental group to a control group).

| Number of Groups | Level of Measurement of Outcome | Is the Data Normally Distributed? | Test to Use |
|:-----------------|:--------------------------------|:----------------------------------|:------------|
| 2 Groups         | Nominal                         | (Not Applicable)                  | **Chi-Square Test of Independence** |
| 2 Groups         | Ordinal                         | (Not Applicable)                  | **Mann-Whitney U Test** |
| 2 Groups         | Continuous (Interval/Ratio)     | Yes                               | **Independent Samples t-test** |
| 2 Groups         | Continuous (Interval/Ratio)     | No                                | **Mann-Whitney U Test** |
| 2+ Groups        | Nominal                         | (Not Applicable)                  | **Chi-Square Test of Independence** |
| 2+ Groups        | Ordinal                         | (Not Applicable)                  | **Kruskal-Wallis H Test** |
| 2+ Groups        | Continuous (Interval/Ratio)     | Yes                               | **One-Way ANOVA** |
| 2+ Groups        | Continuous (Interval/Ratio)     | No                                | **Kruskal-Wallis H Test** |

<br>

### Table 2: Tests for Differences **Within** Groups

Use this table when you are measuring the same group of participants at different times or under different conditions (repeated measures).

| Number of Conditions/Time Points | Level of Measurement of Outcome | Is the Data Normally Distributed? | Test to Use |
|:---------------------------------|:--------------------------------|:----------------------------------|:------------|
| 2 Conditions                     | Nominal                         | (Not Applicable)                  | **McNemar's Test** |
| 2 Conditions                     | Ordinal                         | (Not Applicable)                  | **Wilcoxon Signed-Rank Test** |
| 2 Conditions                     | Continuous (Interval/Ratio)     | Yes                               | **Paired Samples t-test** |
| 2 Conditions                     | Continuous (Interval/Ratio)     | No                                | **Wilcoxon Signed-Rank Test** |
| 2+ Conditions                    | Ordinal                         | (Not Applicable)                  | **Friedman's Test** |
| 2+ Conditions                    | Continuous (Interval/Ratio)     | Yes                               | **Repeated Measures ANOVA** |
| 2+ Conditions                    | Continuous (Interval/Ratio)     | No                                | **Friedman's Test** |

<br>

### Table 3: Tests for Relationships (Correlations)

Use this table when you want to see if two variables are related or associated with each other.

| Variable 1 Level of Measurement | Variable 2 Level of Measurement | Are the Data Normally Distributed? | Test to Use |
|:--------------------------------|:--------------------------------|:-----------------------------------|:------------|
| Nominal                         | Nominal                         | (Not Applicable)                   | **Chi-Square Test of Association** |
| Ordinal                         | Ordinal                         | (Not Applicable)                   | **Spearman's Rank Correlation** |
| Continuous (Interval/Ratio)     | Continuous (Interval/Ratio)     | Yes                                | **Pearson's Correlation** |
| Continuous (Interval/Ratio)     | Continuous (Interval/Ratio)     | No                                 | **Spearman's Rank Correlation** |

<div class="explanation" markdown="1">
**Note:** What is the relationship between a continuous variable (e.g., Age) and a categorical variable (e.g., County)? This is actually the same question as asking "Is there a difference in Age *between* the different Counties?" You would use the 'Tests for Differences Between Groups' table for this (e.g., a One-Way ANOVA).
</div>

<div style="text-align: center; margin-top: 3em;">
    <a href="{{ "/jamovi/" | relative_url }}">← Return to jamovi Guides Menu</a>
</div>

{% include pagination.html %}
