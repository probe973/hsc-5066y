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
    id="q_transport"
    title="Method of Transport"
    question_text="A variable recording a person's primary method of transport to work (e.g., Car, Bus, Train, Bicycle)."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="nominal"
    solution_text="The transport methods are distinct categories with no logical order, making this Nominal data."
%}

{% include question_multiple_choice.html
    id="q_tshirt"
    title="T-Shirt Size"
    question_text="A variable recording a t-shirt size (e.g., Small, Medium, Large, Extra Large)."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="ordinal"
    solution_text="The sizes have a clear, meaningful order, but the difference in measurement between 'Small' and 'Medium' isn't necessarily the same as between 'Large' and 'Extra Large'. This is Ordinal data."
%}

{% include question_multiple_choice.html
    id="q_weight"
    title="Weight of a Package"
    question_text="A variable recording the weight of a package in kilograms."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="continuous"
    solution_text="Weight is a precise numerical measurement. In jamovi, all numerical data is classified as Continuous."
%}

{% include question_multiple_choice.html
    id="q_phone"
    title="Mobile Phone Brand"
    question_text="A variable recording the brand of a person's mobile phone (e.g., Apple, Samsung, Google)."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="nominal"
    solution_text="Phone brands are just labels. There is no inherent ranking or order, so this is Nominal data."
%}

{% include question_multiple_choice.html
    id="q_injury"
    title="Injury Severity"
    question_text="A variable from a medical record classifying an injury as 'Mild', 'Moderate', or 'Severe'."
    options="nominal::Nominal||ordinal::Ordinal||continuous::Continuous"
    correct_answer="ordinal"
    solution_text="'Severe' is clearly worse than 'Moderate', so there is an order. However, the difference between the levels is not a measurable quantity. This is Ordinal data."
%}

<!-- This automatically adds the "Previous" and "Next" navigation buttons -->
{% include pagination.html %}
