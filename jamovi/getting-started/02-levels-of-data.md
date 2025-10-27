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

*   **Nominal:** These are categories with no inherent order or ranking. The categories are just labels. In jamovi, this is the **Nominal** data type.
    *   *Example:* Types of pets (Dog, Cat, Fish). 'Dog' is not "higher" or "better" than 'Cat'.

*   **Ordinal:** These are categories that have a meaningful order or rank, but the distance between the categories is not equal or measurable. In jamovi, this is the **Ordinal** data type.
    *   *Example:* A satisfaction rating (Very Dissatisfied, Dissatisfied, Neutral, Satisfied, Very Satisfied). We know 'Satisfied' is higher than 'Neutral', but we can't say it's exactly double the satisfaction.
</div>

<div class="explanation" markdown="1">
### Numerical Data: Interval and Ratio

Academically, measured numerical data is often split into two types:

*   **Interval:** The data is ordered and the intervals between values are equal, but there is no "true zero".
    *   *Example:* Temperature in Celsius. The difference between 10°C and 20°C is the same as between 20°C and 30°C, but 0°C is a temperature, not the absence of all heat.

*   **Ratio:** The data has all the properties of interval data, but it also has a "true zero", meaning 0 represents the complete absence of the variable.
    *   *Example:* Height in centimetres. 0 cm means no height.

**Important:** For practical purposes, **jamovi calls both Interval and Ratio data 'Continuous'**.
</div>

<div class="explanation" markdown="1">
### Numerical Data: Discrete and Continuous

Another way to think about numerical data is whether it's discrete or continuous.

*   **Discrete Data** can only take specific, separate values (often whole numbers).
    *   *Example:* The number of siblings a person has. You can have 2 or 3 siblings, but not 2.5.

*   **Continuous Data** can take any value within a given range.
    *   *Example:* A person's height. It could be 175cm, 175.1cm, or 175.11cm, depending on the precision of the measurement.

**Important:** Once again, **jamovi simplifies this and calls all numerical data (both Discrete and Continuous) 'Continuous'**. This is the third and final data type you can select in jamovi.
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
    solution_text="Correct. Eye colour categories have no inherent order, so they are Nominal."
%}

{% include question_multiple_choice.html
    id="q_satisfaction"
    title="Satisfaction Rating"
    question_text="A variable recording a participant's satisfaction on a scale from 'Very Dissatisfied' to 'Very Satisfied'."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="ordinal"
    solution_text="Correct. The categories have a clear order, but the distance between them is not equal, making them Ordinal."
%}

{% include question_multiple_choice.html
    id="q_temperature"
    title="Temperature"
    question_text="A variable recording the temperature of a room in degrees Celsius."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="continuous"
    solution_text="Correct. Temperature is a measured numerical variable. In jamovi, all numerical data (Interval, Ratio, Discrete, or Continuous) is classified as Continuous."
%}

{% include question_multiple_choice.html
    id="q_siblings"
    title="Number of Siblings"
    question_text="A variable recording the number of siblings a person has."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="continuous"
    solution_text="Correct. Although this is technically discrete numerical data, jamovi handles all numerical data as Continuous."
%}

{% include question_multiple_choice.html
    id="q_height"
    title="Height"
    question_text="A variable recording a person's height in centimetres."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="continuous"
    solution_text="Correct. Height is a measured numerical variable (specifically, ratio data), and jamovi handles all numerical data as Continuous."
%}

<!-- This automatically adds the "Previous" and "Next" navigation buttons -->
{% include pagination.html %}
