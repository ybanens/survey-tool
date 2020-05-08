---
title: Conditions
nav: true
---

# Conditions

## Conditions

{% capture text %}If statements have the syntax “if…then”, however LimeSurvey Conditions meet the statement “Only show this question if…”  In simple terms, a LimeSurvey Condition is the “then” part of the If statement, so it is applied to the second (conditional) question.
In this example, we are saying “ask how many hours (VI2) only if the answer to VI1 is 1 or more”.{% endcapture %}
{% include alert.md text=text color=info %}

In this section we will tell LimeSurvey to only display the following questions if certain conditions are met.

{% capture text %}
1.	With the `Question Summary` screen showing for the second (conditional) question (**VI2**), click on the `Set conditions` button on the `Survey toolbar`.
2.	In the `Previous questions` tab of the `Question` text box, click on the question that this question is conditional upon – **VI1**.
3.	Choose the appropriate `Comparison operator` – **Greater than or equal to**
4.	Click the `Constant` tab in the `Answer` text box, then type **1**.
5.	Click the `Add Condition` button.
6.	Click the `Close` button in the top right-hand corner to close the `Conditions designer` window.
7.	Click `Preview question group` to preview the question, testing entering a **0**, then another number.
8.	Close the `Preview` tab.{% endcapture %}
{% include card.md header="Conditions" text=text %}

## Copy questions

{% capture text %}
1.	Click on `Question explorer` in the `Survey explorer` panel on the left of the screen.
2.	Click on the **VI1** question to select it.
3.	Click the `Copy` button on the `Survey toolbar`.
4.	In the `Code:` text box, type a new code – **MI1** (Moderate Intensity 1 – refer to the survey design).
5.	In the `Question:` text box, change “vigorous” intensity sports   to   “**moderate**” intensity sports. (two places)
6.	In the `Help:` text box, delete the existing text then type (or copy and `Paste as Plain Text`):

**Moderate-intensity sports include brisk walking, cycling or swimming; are likely to cause small increases in breathing or heart rate, and should be done for at least 10 minutes continuously.**

7.	No `Copy options` are required for this question - click the `Save and close` button on the toolbar.
8.	Now click on the **VI2** question in `Question explorer` to select it.
9.	Click the `Copy` button on the `Survey toolbar`.
10.	Type a new code – **MI2**.
11.	In the `Question:` text box, change “vigorous” intensity sports to “**moderate**” intensity sports.
12.	Click the `Save and close` button on the toolbar.
13.	With the `Question Summary` screen showing for **MI2**, click on the `Set conditions` button on the `Survey toolbar`.
14.	In the `Previous questions` tab of the `Question` text box, click on the question that this question is conditional upon – **MI1**.
15.	Choose the appropriate `Comparison operator` – **Greater than or equal to** 
16.	Click the `Constant` tab in the `Answer` text box, then type **1**.
17.	Click the `Add Condition` button.
18.	Click the `Close` button in the top right-hand corner to close the `Conditions designer` window.{% endcapture %}
{% include card.md header="Copy questions" text=text %}

## Answer options

{% capture text %}In the previous questions, the respondent is to enter (type) an answer to the question.  For questions where the answers are provided for selection (e.g. multiple choice), the question and answers are created in two separate steps.{% endcapture %}
{% include alert.md text=text color=info %}

{% capture text %}
1.	Click the `Add new Question to Group` button.
2.	`Code:`    **SR**
3.	`Question:`    Type (or copy and `Paste as Plain Text`):

**The following question is about sitting or reclining including time spent sitting at a desk, sitting with friends, travelling in a car, bus, train, reading, playing cards or watching television. Do not include time spent sleeping.
How much time do you usually spend sitting or reclining on a typical day?**

4.	`Question type:`  under `Single choice questions` choose **List (dropdown)**.
5.	Click the `Save and close` button.{% endcapture %}
{% include card.md header="Create a new question" text=text %}

{% capture text %}
6.	Click the `Edit answer options` button on the `Survey toolbar`.
7.	In the first answer box, add `Code:`    **SRa**, then in the first text box, type `Less than 1 hour`.
8.	Click the `Insert a new answer option after this one` button (the '+' sign), then repeat until all answer options are added, incrementing the codes – SR1b, SR1c, etc. – as you go.


**SRb		3 hours  
SRc		4-8 hours  
SRd		9-12 hours  
SRe		More than 12 hours**

9.	Click the `Save and close` button.
10.	Preview the question, then close the `Preview` tab.{% endcapture %}
{% include card.md header="Create the answer options" text=text %}

---
