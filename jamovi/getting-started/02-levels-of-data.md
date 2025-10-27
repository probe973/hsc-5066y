---
layout: default
title: Levels of Data
---

<div class="explanation" markdown="1">
## Levels of Data in jamovi

All data can be broadly split into two main types: **categorical** and **numerical**. Understanding the difference is the first key step to choosing the correct analysis.

*   **Categorical Data** represents groups or categories. For example, Eye Colour (Blue, Brown, Green) or Highest Qualification (GCSE, A-Level, Degree).
*   **Numerical Data** represents quantities. For example, Height in centimetres, Number of siblings, or Temperature in Celsius.
</div>

<div class="explanation" markdown="1">
### Categorical Data: Nominal and Ordinal

When data is categorical, we can further classify it:

*   **Nominal:** These are categories with no inherent order or ranking. In jamovi, this is the **Nominal** data type.
*   **Ordinal:** These are categories that have a meaningful order or rank, but the distance between the categories is not equal or measurable. In jamovi, this is the **Ordinal** data type.
</div>

<div class="explanation" markdown="1">
### Numerical Data (Continuous in jamovi)

For practical purposes, jamovi simplifies all numerical data (whether it's discrete, continuous, interval, or ratio) into a single data type: **Continuous**.
</div>

---

### Check Your Understanding
For the following variables, how would you classify them in jamovi?

{% include question_multiple_choice.html
    id="q_ethnicity"
    title="Participant Ethnicity"
    question_text="A variable recording a participant's self-reported ethnicity (e.g., White, Black, Asian)."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="nominal"
    solution_text="Ethnicity is a set of categories with no inherent order, making it Nominal."
%}

{% include question_multiple_choice.html
    id="q_finish_position"
    title="Race Finishing Position"
    question_text="A variable recording the finishing position in a race (e.g., 1st, 2nd, 3rd)."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="ordinal"
    solution_text="Finishing positions have a clear rank (1st is better than 2nd), but the time difference between 1st and 2nd might not be the same as between 2nd and 3rd. This makes it Ordinal."
%}

{% include question_multiple_choice.html
    id="q_reaction_time"
    title="Reaction Time"
    question_text="A variable recording the time in milliseconds a person takes to press a button."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="continuous"
    solution_text="Time is a measured numerical variable. In jamovi, this is classified as Continuous."
%}

{% include question_multiple_choice.html
    id="q_postcode"
    title="Postcode"
    question_text="A variable recording a participant's postcode (e.g., NR4 7TJ)."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="nominal"
    solution_text="Although it contains numbers, a postcode is just a label for a location. It has no numerical value or order, so it is Nominal."
%}

{% include question_multiple_choice.html
    id="q_likert_scale"
    title="Likert Scale Agreement"
    question_text="A variable from a survey asking for agreement on a 5-point scale from 'Strongly Disagree' to 'Strongly Agree'."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="ordinal"
    solution_text="The 5 points have a clear order of agreement, but we can't assume the 'distance' between 'Agree' and 'Strongly Agree' is measurable. This is classic Ordinal data."
%}

<!-- This automatically adds the "Previous" and "Next" navigation buttons -->
{% include pagination.html %}
