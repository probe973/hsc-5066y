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
    *   *Example:* Types of pets (Dog, Cat, Fish).

*   **Ordinal:** These are categories that have a meaningful order or rank, but the distance between the categories is not equal or measurable. In jamovi, this is the **Ordinal** data type.
    *   *Example:* A satisfaction rating (Very Dissatisfied, Dissatisfied, Neutral, Satisfied, Very Satisfied).
</div>

<div class="explanation" markdown="1">
### Numerical Data: Interval and Ratio

Academically, measured numerical data is often split into two types: Interval and Ratio. However, for practical purposes, **jamovi calls both Interval and Ratio data 'Continuous'**.
</div>

<div class="explanation" markdown="1">
### Numerical Data: Discrete and Continuous

Another way to think about numerical data is whether it's discrete (can only take specific values, like number of siblings) or continuous (can take any value in a range, like height). However, once again, **jamovi simplifies this and calls all numerical data (both Discrete and Continuous) 'Continuous'**.
</div>

---

### Check Your Understanding
For the following variables, how would you classify them in jamovi?

{% include question_multiple_choice.html
    id="q_eyecolour"
    title="Eye Colour"
    question_text="A variable recording a person's eye colour (e.g., Blue, Green, Brown)."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="nominal"
    solution_text="Eye colour categories have no inherent order, so they are Nominal."
%}

{% include question_multiple_choice.html
    id="q_satisfaction"
    title="Satisfaction Rating"
    question_text="A variable recording a participant's satisfaction on a scale from 'Very Dissatisfied' to 'Very Satisfied'."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="ordinal"
    solution_text="The categories have a clear order, but the distance between them is not equal, making them Ordinal."
%}

{% include question_multiple_choice.html
    id="q_temperature"
    title="Temperature"
    question_text="A variable recording the temperature of a room in degrees Celsius."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="continuous"
    solution_text="Temperature is a measured numerical variable. In jamovi, all numerical data is classified as Continuous."
%}

{% include question_multiple_choice.html
    id="q_siblings"
    title="Number of Siblings"
    question_text="A variable recording the number of siblings a person has."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="continuous"
    solution_text="Although this is technically discrete numerical data, jamovi handles all numerical data as Continuous."
%}

{% include question_multiple_choice.html
    id="q_height"
    title="Height"
    question_text="A variable recording a person's height in centimetres."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="continuous"
    solution_text="Height is a measured numerical variable (specifically, ratio data), and jamovi handles all numerical data as Continuous."
%}

<!-- This automatically adds the "Previous" and "Next" navigation buttons -->
{% include pagination.html %}
