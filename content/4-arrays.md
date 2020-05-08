---
title: Arrays
nav: true
---

# Arrays

Arrays are a common question type used when you need scaled responses to a series of subquestions. The most common example is the 'How much do you agree with the following statements?' type. Responses are usually placed on a [Likert scale](https://en.wikipedia.org/wiki/Likert_scale).

## Add another question group

{% capture text %}
1.	In the `Survey explorer` panel on the left-hand side of the screen, click on the `Add Group` button.
2.	In the `Title:` text box, type **Food**.
3.	In the `Description:` box, type (or copy and `Paste as Plain Text`):

**This section relates to your food consumption over a typical week. It is broken down into 3 main areas: Fruit & Veg, Grains & Dairy and Meat, Poultry & Fish.
Please answer as honestly and accurately as possible.**

4.	Click the `Save and close button`.{% endcapture %}
{% include card.md header="Group 2" text=text %}

## Array question types

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/4159dazqze8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Creating Array questions

{% capture text %}
1.	Click the `Add new Question to Group` button for the **Food** group.
2.	In the `Code:` text box, type **FV**.
3.	In the `Question:` text box, type (or copy and `Paste as Plain Text`):

**Fruit and Vegetables
Please select how often you eat at least ONE portion of the following foods and drinks.**

4.	Bold the heading **Fruit and Vegetables**.
5.	In the `Help:` text box, type (or copy and `Paste as Plain Text`):

**A portion includes: a handful of grapes, an orange, a serving of carrots, a side salad.**

6.	Italicise the `Help` text.
7.	`Question type:`    scroll down to `Arrays`, then choose **Array**.
8.	Click the `Save and close button`.{% endcapture %}
{% include card.md header="Create the question" text=text %}

{% capture text %}Array answers have values on two axes Ð Subquestions on the Y axis and Answer Options on the X axis.{% endcapture %}
{% include alert.md text=text color="info" %}

{% capture text %}
9.	Click the `Edit subquestions` button on the `Survey toolbar``.
10.	`Code:`   **FV1**
11.	In the first text box, type **Fruit (tinned or fresh)**.
12.	Click the `Insert a new subquestion after this one` button (the '+' sign), then repeat until all answer options are added.

**Vegetables (fresh, frozen or tinned)
Beans or pulses (including baked beans)**

13.	Click the `Save and close` button.{% endcapture %}
{% include card.md header="Create the subquestions" text=text %}

{% capture text %}
14.	Click the `Edit answer options` button on the `Survey toolbar`.
15.	`Code:`    **FVa**
16.	In the first text box, type **Rarely or never**.
17.	Add the `Answer options:` as for the subquestions incrementing the codes Ð FVb, FVc, etc. Ð as you go.

**1-3 times per week
4-6 times per week
7+ times per week**

18.	Click the `Save and close` button.
19.	Preview the question, then close the `Preview` tab.{% endcapture %}
{% include card.md header="Create the answer options" text=text %}

## Second array question

{% capture text %}
1.	Click the `Add new Question to Group` button for the **Food** group.
2.	In the `Code:` text box, type **GDS**.
3.	In the `Question:` text box, type or copy and `Paste as Plain Text`:

**Grains, Dairy and Sugars
Please selected how often you eat at least ONE portion of the following foods and drinks.**

4.	Bold the heading **Grains, Dairy and Sugars**.
5.	In the `Help:` text box, type or copy and `Paste as Plain Text`:

**A portion includes: a bowl of cereal, one slice of bread, one glass of milk.**

6.	Italicise the `Help` text.
7.	`Question type:`    scroll down to `Arrays`, then choose **Array**.
8.	Click the `Save and close` button.{% endcapture %}
{% include card.md header="Create the question" text=text %}

{% capture text %}
9.	Click the `Edit subquestions` button on the `Survey toolbar`.

**GDS1	Fibre-rich breakfast cereal (like Weetabix, Fruit & Fibre, Porridge, Muesli)
GDS2	Wholemeal, rye or grain bread
GDS3	Milk, cheese or yoghurt**

10.	Click the `Save and close` button.{% endcapture %}
{% include card.md header="Create the subquestions" text=text %}

{% capture text %}
11.	Click the Edit answer options button on the Survey toolbar.

**GDSa	Rarely or never**

{% capture text %}**Note:** LimeSurvey has remembered these answers which were used previously and is prompting for you to reuse them.  This saves extra typing.{% endcapture %}
{% include alert.md text=text color="info" %}

**GDSb	1-3 times per week  
GDSc	4-6 times per week  
GDSd	7+ times per week  **

12.	Click the `Save and close` button.
13.	Preview the question, then close the `Preview tab`.{% endcapture %}
{% include card.md header="Create the answer options" text=text %}

{% capture text %}**A note on codes**
---
Have you noticed a pattern in the codes recommended here?  Questions have whole codes Ð subquestions have incrementing numerals added to the question code, answer options have incrementing alpha characters added to the question code.  This is not a hard and fast rule (you can use whatever codes you like), but it is a consistent standard which links answers with the question when collected data is viewed for analysis.{% endcapture %}
{% include alert.md text=text color="secondary" %}

## Third array question

{% capture text %}
1.	Click the `Add new Question to Group` button for the **Food** group.
2.	In the `Code:` text box, type **MPF**.
3.	In the `Question:` text box, type or copy and `Paste as Plain Text`:

**Meat, Poultry and Fish
Please selected how often you eat at least ONE portion of the following foods.**

4.	Bold the heading **Meat, Poultry and Fish**.
5.	`Question type:`    scroll down to `Arrays`, then choose **Array**.
6.	Click the `Save and close` button.{% endcapture %}
{% include card.md header="Create the question" text=text %}

{% capture text %}
7.	Click the `Edit subquestions` button on the `Survey toolbar`.

**MPF1	Beef, lamb or pork  
MPF2	Chicken or turkey (not in batter or breadcrumbs)  
MPF3	Sausages, bacon, corned beef, meat pies, burgers  
MPF4	Chicken nuggets, chicken burgers, chicken pies  
MPF5	White fish  
MPF6	Oily fish - like herrings, sardines, salmon, trout, mackerel, fresh tuna (not tinned tuna)  **

8.	Click the `Save and close` button.{% endcapture %}
{% include card.md header="Create the subquestions" text=text %}

{% capture text %}
9.	Click the `Edit answer options` button on the `Survey toolbar`.

**MPFa	Rarely or never  
MPFb	1-3 times per week  
MPFc	4-6 times per week  
MPFd	7+ times per week  **

10.	Click the `Save and close` button.
11.	Preview the question, then close the `Preview tab`.{% endcapture %}
{% include card.md header="Create the answer options" text=text %}

---
