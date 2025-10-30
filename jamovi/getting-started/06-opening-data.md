---
layout: default
title: Opening and Saving Data
---

<div class="explanation" markdown="1">
## Opening and Saving Datasets

When working on a dataset, you will want to save your progress and open existing data files.

All of these core functions are located in the main menu, which is accessed by clicking the **button with three horizontal lines (`≡`)** in the top-left corner of the jamovi window. This is often called the 'hamburger menu'.

Inside this menu, you will find common functions that work as you would expect in most software:
*   **Open**
*   **Save**
*   **Save As**
</div>

<div class="explanation" markdown="1">
### File Formats

jamovi can open a wide variety of data files. Its own native format has the `.omv` extension, but it can also open data from other programs, such as SPSS, Stata, and Microsoft Excel.

**Important:** If you are opening data from an Excel file, make sure your data is formatted correctly:
1.  The very **first row** of your spreadsheet must contain the variable names.
2.  Each subsequent row must represent a single participant or case.
</div>

<div class="instructions" markdown="1">
### Opening the Course Dataset

This dataset has been created by Dr Sarah Northcott and Prof Christina Jerosch-Herold. It contains real data collected from anonymised patients with cerebrovascular accident. This is used for teaching purposes only.

1.  Download the data file used for this course from your Blackboard page and save it somewhere you can easily find it.
2.  In jamovi, click the **hamburger menu (`≡`)** in the top-left.
3.  Select **Open**.
4.  Use the **Browse** button to navigate to where you saved the file, select it, and click **Open**.
</div>

<div class="explanation" markdown="1">
### The Dataset
  
In this study, researchers wanted to investigate whether stroke patients experienced an improvement in wellbeing, independence, and cognitive and motor function following a course of intervention.
*  Some variables were measured at the start (baseline) of the study: Age, Sex, CVA side, NIHSS, FASTbase, ARATbase, BARTHELbase, GHQ12base.
*  Some were measured at three months follow-up: FAST3month, ARAT3month, BARTHEL3month, GHQ3month.
*  NIHSS categorises patients into 4 groups for stroke severity: 1=mild, 4=very severe
*  The Action Research Arm Test (ARAT) is a measure of upper limb functioning.  It is scored from 0-57, with higher scores indicating better functioning
*  The Barthel Index (BARTHEL) measures a patient’s ability to perform activities of daily living. It is scored from 0-100, with higher scores indicating greater functional independence
*  The Frenchay Aphasia Screen Test (FAST) assesses whether patients may have a language deficit.  It is scored from 0-30, with higher scores indicating better performance
*  The 12-item General Health Questionnaire (GHQ-12) is used to assess patients’ psychological well-being. It was scored from 0-12, with higher scores indicating greater psychological distress

Explore the dataset and check that all of the variables are defined as the correct level of data.
</div>

---

### Check Your Understanding

{% include question_numerical.html
    id="q_num_vars"
    title="Number of Variables"
    question_text="Excluding the participant ID variable, how many variables are there in the dataset?"
    correct_answer="12"
    tolerance="0"
    solution_text="There are 8 variables measured at baseline and 4 variables measured at follow-up, for a total of 12."
%}

{% include question_numerical.html
    id="q_num_participants"
    title="Number of Participants"
    question_text="How many participants are included in the dataset? (Hint: scroll to the bottom of the data spreadsheet in jamovi and see what the last row number is)."
    correct_answer="50"
    tolerance="0"
    solution_text="The data grid shows that there are 50 rows, meaning there are 50 participants in the study."
%}

<!-- This is the link back to the main jamovi guides page -->
<div style="text-align: center; margin-top: 3em;">
    <a href="{{ "/jamovi/" | relative_url }}">← Return to jamovi Guides Menu</a>
</div>


<!-- This automatically adds the "Previous" and "Next" navigation buttons -->
{% include pagination.html %}
