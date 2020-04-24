---
title: Logic
nav: true
---

# Conditions, Arrays and Quotas

## Conditions

{% capture text %}If statements have the syntax “if…then”, however LimeSurvey Conditions meet the statement “Only show this question if…”  In simple terms, a LimeSurvey Condition is the “then” part of the If statement, so it is applied to the second (conditional) question.
In this example, we are saying “ask how many hours (VI2) only if the answer to VI1 is 1 or more”.{% endcapture %}
{% include alert.md text=text color=info %}


{% capture text %}
1.	With the Question Summary screen showing for the second (conditional) question (VI2), click on the Set conditions button on the Survey toolbar.
2.	In the Previous questions tab of the Question text box, click on the question that this question is conditional upon – VI1.
3.	Choose the appropriate Comparison operator – Greater than or equal to
4.	Click the Constant tab in the Answer text box, then type 1.
5.	Click the Add Condition button.
6.	Click the Close button in the top right-hand corner to close the Conditions designer window.
7.	Click Preview question group to preview the question, testing entering a 0, then another number.
8.	Close the Preview tab.{% endcapture %}
{% include card.md header="Conditions" text=text %}

## Copy questions

{% capture text %}
1.	Click on Question explorer in the Survey explorer panel on the left of the screen.
2.	Click on the VI1 question to select it.
3.	Click the Copy button on the Survey toolbar.
4.	In the Code: text box, type a new code – MI1 (Moderate Intensity 1 – refer to the survey design).
5.	In the Question: text box, change “vigorous” intensity sports   to   “moderate” intensity sports. (two places)
6.	In the Help: text box, delete the existing text then type (or copy and Paste as Plain Text):
Moderate-intensity sports include brisk walking, cycling or swimming; are likely to cause small increases in breathing or heart rate, and should be done for at least 10 minutes continuously.
7.	No Copy options are required for this question - click the Save and close button on the toolbar.

8.	Now click on the VI2 question in Question explorer to select it.
9.	Click the Copy button on the Survey toolbar.
10.	Type a new code – MI2.
11.	In the Question: text box, change “vigorous” intensity sports   to   “moderate” intensity sports.
12.	Click the Save and close button on the toolbar.
13.	With the Question Summary screen showing for MI2, click on the Set conditions button on the Survey toolbar.
14.	In the Previous questions tab of the Question text box, click on the question that this question is conditional upon – MI1.
15.	Choose the appropriate Comparison operator – Greater than or equal to 
16.	Click the Constant tab in the Answer text box, then type 1.
17.	Click the Add Condition button.
18.	Click the Close button in the top right-hand corner to close the Conditions designer window.{% endcapture %}
{% include card.md header="Copy questions" text=text %}

## Answer options

{% capture text %}In the previous questions, the respondent is to enter (type) an answer to the question.  For questions where the answers are provided for selection (e.g. multiple choice), the question and answers are created in two separate steps.{% endcapture %}
{% include alert.md text=text color=info %}

{% capture text %}
1.	Click the Add new Question to Group button.
2.	Code:    SR
3.	Question:    Type (or copy and Paste as Plain Text):
The following question is about sitting or reclining including time spent sitting at a desk, sitting with friends, travelling in a car, bus, train, reading, playing cards or watching television. Do not include time spent sleeping.
How much time do you usually spend sitting or reclining on a typical day?
4.	Question type:  under Single choice questions choose List (dropdown).
5.	Click the Save and close button.{% endcapture %}
{% include card.md header="Create a new question" text=text %}

{% capture text %}
6.	Click the Edit answer options button on the Survey toolbar.
7.	In the first answer box, add Code:    SRa, then in the first text box, type Less than 1 hour.
8.	Click the Insert a new answer option after this one button (the plus sign), then repeat until all answer options are added, incrementing the codes – SR1b, SR1c, etc. – as you go.
`SRb		3 hours
`SRc		4-8 hours
`SRd		9-12 hours
`SRe		More than 12 hours
9.	Click the Save and close button.
10.	Preview the question, then close the Preview tab.{% endcapture %}
{% include card.md header="Create the answer options" text=text %}

## Add another question group

{% capture text %}
1.	In the Survey explorer panel on the left-hand side of the screen, click on the Add Group button.
2.	In the Title: text box, type Food.
3.	In the Description: box, type (or copy and Paste as Plain Text):
This section relates to your food consumption over a typical week. It is broken down into 3 main areas: Fruit & Veg, Grains & Dairy and Meat, Poultry & Fish.
Please answer as honestly and accurately as possible.
4.	Click the Save and close button.{% endcapture %}
{% include card.md header="Group 2" text=text %}

## Array question types

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/4159dazqze8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Creating Array questions

{% capture text %}
1.	Click the Add new Question to Group button for the Food group.
2.	In the Code: text box, type FV.
3.	In the Question: text box, type (or copy and Paste as Plain Text):
Fruit and Vegetables
Please select how often you eat at least ONE portion of the following foods and drinks.
4.	Bold the heading Fruit and Vegetables.
5.	In the Help: text box, type (or copy and Paste as Plain Text):
A portion includes: a handful of grapes, an orange, a serving of carrots, a side salad.
6.	Italicise the Help text.
7.	Question type:    scroll down to Arrays, then choose Array.
8.	Click the Save and close button.{% endcapture %}
{% include card.md header="Create the question" text=text %}

{% capture text %}Array answers have values on two axes – Subquestions on the Y axis and Answer Options on the X axis.{% endcapture %}
{% include alert.md text=text color=info %}

{% capture text %}
9.	Click the Edit subquestions button on the Survey toolbar.
10.	Code:    FV1
11.	In the first text box, type Fruit (tinned or fresh)
12.	Click the Insert a new subquestion after this one button (the plus sign), then repeat until all answer options are added.
Vegetables (fresh, frozen or tinned)
Beans or pulses (including baked beans)
13.	Click the Save and close button.{% endcapture %}
{% include card.md header="Create the subquestions" text=text %}

{% capture text %}
14.	Click the Edit answer options button on the Survey toolbar.
15.	Code:    FVa
16.	In the first text box, type Rarely or never
17.	Add the Answer options: as for the subquestions incrementing the codes – FVb, FVc, etc. – as you go.
1-3 times per week
4-6 times per week
7+ times per week
18.	Click the Save and close button.
19.	Preview the question, then close the Preview tab.{% endcapture %}
{% include card.md header="Create the answer options" text=text %}

## Second array question

{% capture text %}
1.	Click the Add new Question to Group button for the Food group.
2.	In the Code: text box, type GDS.
3.	In the Question: text box, type or copy and Paste as Plain Text:
Grains, Dairy and Sugars
Please selected how often you eat at least ONE portion of the following foods and drinks.
4.	Bold the heading Grains, Dairy and Sugars.
5.	In the Help: text box, type or copy and Paste as Plain Text:
A portion includes: a bowl of cereal, one slice of bread, one glass of milk.
6.	Italicise the Help text.
7.	Question type:    scroll down to Arrays, then choose Array.
8.	Click the Save and close button.{% endcapture %}
{% include card.md header="Create the question" text=text %}

{% capture text %}
9.	Click the Edit subquestions button on the Survey toolbar.
GDS1	Fibre-rich breakfast cereal (like Weetabix, Fruit & Fibre, Porridge, Muesli)
GDS2	Wholemeal, rye or grain bread
GDS3	Milk, cheese or yoghurt
10.	Click the Save and close button.{% endcapture %}
{% include card.md header="Create the subquestions" text=text %}

{% capture text %}
11.	Click the Edit answer options button on the Survey toolbar.
`GDSa	Rarely or never
{% capture text %}Note that LimeSurvey has remembered these answers which were used previously and is prompting for you to reuse them.  This saves extra typing.{% endcapture %}
{% include alert.md text=text color=info %}

`GDSb	1-3 times per week
`GDSc	4-6 times per week
`GDSd	7+ times per week
12.	Click the Save and close button.
13.	Preview the question, then close the Preview tab.{% endcapture %}
{% include card.md header="Create the answer options" text=text %}

{% capture text %}A note on codes
Have you noticed a pattern in the codes recommended here?  Questions have whole codes – subquestions have incrementing numerals added to the question code, answer options have incrementing alpha characters added to the question code.  This is not a hard and fast rule (you can use whatever codes you like), but it is a consistent standard which links answers with the question when collected data is viewed for analysis.{% endcapture %}
{% include alert.md text=text color=secondary %}

## Third array question

{% capture text %}
1.	Click the Add new Question to Group button for the Food group.
2.	In the Code: text box, type MPF.
3.	In the Question: text box, type or copy and Paste as Plain Text:
Meat, Poultry and Fish
Please selected how often you eat at least ONE portion of the following foods.
4.	Bold the heading Meat, Poultry and Fish.
5.	Question type:    scroll down to Arrays, then choose Array.
6.	Click the Save and close button.{% endcapture %}
{% include card.md header="Create the question" text=text %}

{% capture text %}
7.	Click the Edit subquestions button on the Survey toolbar.
`MPF1	Beef, lamb or pork
`MPF2	Chicken or turkey (not in batter or breadcrumbs)
`MPF3	Sausages, bacon, corned beef, meat pies, burgers
`MPF4	Chicken nuggets, chicken burgers, chicken pies
`MPF5	White fish
`MPF6	Oily fish - like herrings, sardines, salmon, trout, mackerel, fresh tuna (not tinned tuna)
8.	Click the Save and close button.{% endcapture %}
{% include card.md header="Create the subquestions" text=text %}

| Priority apples | Second priority | Third priority |
|-------|--------|---------|
| ambrosia | gala | red delicious |
| pink lady | jazz | macintosh |
| honeycrisp | granny smith | fuji |

{% capture text %}
9.	Click the Edit answer options button on the Survey toolbar.
| Code | Value |
|------|--------------------|
|MPFa | Rarely or never |
| MPFb | 1-3 times per week |
| MPFc | 4-6 times per week | 
| MPFd | 7+ times per week |

10.	Click the Save and close button.
11.	Preview the question, then close the Preview tab.{% endcapture %}
{% include card.md header="Create the answer options" text=text %}

---

## Quotas

### Create a Quota question

{% capture text %}Quotas are used to terminate the survey when a respondent’s answer is invalid.  For example, you can use Quotas to limit the survey to respondents aged over 25, to balance the respondents (e.g. 50 male and 50 female), or to seek agreement to provided terms and conditions.{% endcapture %}
{% include alert.md text=text color=info %}

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/zjDf6a0_3es" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

1.	Click the Survey button at the top of the Survey explorer to return to the Survey Quick Actions screen.   

{% capture text %}
2.	In the Survey explorer panel on the left-hand side of the screen, click on the Add Group button.
3.	In the Title: text box, type Consent.
4.	In the Description: box, type (or copy and Paste as Plain Text):
Please confirm that you consent to participating in this survey.
5.	Click the Save and close button.{% endcapture %}
{% include card.md header="Add a new Question Group" text=text %}

{% capture text %}
6.	Click the Add new Question to Group button.
7.	In the Code: text box, type C1.
8.	In the Question: text box, type or copy and Paste as Plain Text:
I have read and agree to abide by the Code for the Responsible Conduct of Research
9.	Open the Question type selection list, scroll down to Mask questions, then choose Yes/No.
10.	Click the Save and close button.{% endcapture %}
{% include card.md header="Add a new question" text=text %}

{% capture text %}
1.	Click the Survey button at the top of the Survey explorer to return to the Survey Quick Actions screen.
2.	Click on the Survey properties button on the Survey toolbar.
3.	Click on Quotas.
4.	Under Actions, click the Add new quota button.
5.	In the Quota name: text box, type:
Consent Exclusion
6.	The Quota limit: text box, type 0 (zero).  (A zero limit for a specific answer means that the survey will immediately end.)
7.	In the Quota message: box, type You have chosen not to continue.
8.	Leave the End URL: and URL Description: as they are.
9.	Click the Save button.{% endcapture %}
{% include card.md header="Create a Quota" text=text %}

{% capture text %}
1.	Click the Add answer button.
2.	Click to choose the C1 question, then click Next.
3.	Click to choose No question, then click Next.
4.	Click the Close button.{% endcapture %}
{% include card.md header="Apply the Quota" text=text %}

{% capture text %}NOTE:  Quotas cannot be previewed – they are applied only when the survey is active.{% endcapture %}
{% include alert.md text=text color=warning %}

## Reordering Question Groups and Questions

{% capture text %}
1.	In the Survey explorer panel on the left-hand side of the screen, click on the Question Organizer button.
2.	Point the mouse to the top of the Consent question group to display a four-headed arrow mouse cursor.  Click and drag the question group to the top of the Survey so that it will appear first.
3.	Click the Save and Close button.
4.	Preview the survey. Remember the Quota will not apply until the survey is upgraded to Production and activated.{% endcapture %}
{% include card.md header="Reorganise questions" text=text %}


---
