---
title: Questions
nav: true
---

# Creating Groups and Basic Questions

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/A2eSz9Wph64" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Create a question group

It is a requirement of LimeSurvey that each survey has at least one Question group, but it is useful to categorise each set of questions into different Question groups so that respondents understand the focus of any set of questions (refer to the survey design).

{% capture text %}
1.	Click on the large Add Group button on the screen.
2.	In the Title: text box, type Activity and Movement.  (Refer to the survey design)
3.	In the Description: text box, type (or copy and Paste as Plain Text):
You are about to be asked about your day to day activity levels. This section is broken down into two main types of activities: vigorous-intensity sports and moderate-intensity sports.
When answering, please think about a typical week when you would be at school, university or at work. If you do not work and are not in education, please think about the activities you do during the equivalent hours of the day.
4.	Click the Save and close button.{% endcapture %}
{% include card.md header="Question Group 1" text=text %}


## Navigation panel

{% capture text %}The panel on the left of the screen is the Navigation panel.  Now that you have created a Question group, the Question explorer section has opened and displays the new Question group.{% endcapture %}
{% include alert.md text=text color=info %}


## Create a question

{% capture text %}
1.	Click the large Add new question to group button on the screen. (You could alternatively click the plus symbol beside the Question group name in the Question explorer.)
2.	In the Code: text box, type VI1. (Vigorous Intensity 1 – refer to the survey design)
3.	In the Question: text box, type (or copy and Paste as Plain Text):
Vigorous intensity sports
How many days in a typical week do you do vigorous-intensity sports, fitness or recreational activity?
Please answer in number of days
4.	Bold the heading Vigorous intensity sports.
5.	In the Help: text box, type (or copy and Paste as Plain Text):
Vigorous-intensity sports include running or football; are likely to cause large increases in breathing or heart rate and should be done for at least 10 minutes continuously.
6.	Select and italicise the Help: text.{% endcapture %}
{% include card.md header="Question 1" text=text %}

 
### Question settings panel

The `Question settings panel` is the panel on the right-hand side of the `Question` screen.  As before, clicking on any left-facing arrowhead will expand the `Question settings``, while clicking on each heading will display the options.
1.	Click on each heading (e.g. Advanced Settings or General Options) to explore the options in the Question settings panel but don’t select anything.
2.	Click on General options, open the Question type selection list, scroll down to Mask questions, then choose Numerical input.
3.	Click the Save and close button.

{% capture text %}
1.	Click on the Preview question button on the Survey toolbar.  The preview will open in a new tab.
2.	Test the question, then close the Preview tab.{% endcapture %}
{% include card.md header="Preview the question" text=text %}

### Add another question

{% capture text %}
1.	Click the large Add new Question to Group button on the screen.
2.	In the Code: text box, type VI2. (Vigorous Intensity 2 – refer to the survey design)
3.	In the Question: text box, type or copy and Paste as Plain Text:
How much time do you spend doing vigorous-intensity sports on a typical day?
Please answer in minutes
4.	Open the Question type selection list, scroll down to Mask questions, then choose Numerical input.
5.	Click the Save and close button.{% endcapture %}
{% include card.md header="Question 2" text=text %}

---