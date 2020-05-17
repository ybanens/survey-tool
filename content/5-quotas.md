---
title: Quotas
nav: true
---

# Quotas

{% capture text %}Quotas are used to terminate the survey when a respondent’s answer is invalid.  For example, you can use Quotas to limit the survey to respondents aged over 25, to balance the respondents (e.g. 50 male and 50 female), or to seek agreement to provided terms and conditions.{% endcapture %}
{% include alert.md text=text color="info" %}


### Create a Quota question

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/zjDf6a0_3es" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

1.	Click the `Survey` button at the top of the `Survey explorer` to return to the `Survey Quick Actions` screen.   

{% capture text %}
2.	In the `Survey explorer panel` on the left-hand side of the screen, click on the `Add Group` button.
3.	In the `Title:` text box, type **Consent**.
4.	In the `Description:` box, type (or copy and `Paste as Plain Text`):

**Please confirm that you consent to participating in this survey.**

5.	Click the `Save and close` button.{% endcapture %}
{% include card.md header="Add a new Question Group" text=text %}

{% capture text %}
6.	Click the Add new Question to Group button.
7.	In the `Code:` text box, type **C1**.
8.	In the `Question:` text box, type or copy and `Paste as Plain Text`:

**I have read and agree to abide by the Code for the Responsible Conduct of Research**

9.	Open the `Question type` selection list, scroll down to `Mask questions`, then choose **Yes/No**.
10.	Click the `Save and close button`.{% endcapture %}
{% include card.md header="Add a new question" text=text %}

{% capture text %}
1.	Click the `Survey` button at the top of the `Survey explorer` to return to the `Survey Quick Actions` screen.
2.	Click on the `Survey properties` button on the Survey toolbar.
3.	Click on `Quotas`.
4.	Under `Actions`, click the `Add new quota` button.
5.	In the `Quota name:` text box, type:

**Consent Exclusion**

6.	The `Quota limit:` text box, type **0** (zero).
{% capture text %}A zero limit for a specific answer means that the survey will immediately end.{% endcapture %}
{% include alert.md text=text color="info" %}
7.	In the `Quota message:` box, type **You have chosen not to continue**.
8.	Leave the `End URL:` and `URL Description:` as they are.
9.	Click the `Save` button.{% endcapture %}
{% include card.md header="Create a Quota" text=text %}

{% capture text %}
1.	Click the `Add answer` button.
2.	Click to choose the **C1** question, then click `Next`.
3.	Click to choose *No* question, then click `Next`.
4.	Click the `Close` button.{% endcapture %}
{% include card.md header="Apply the Quota" text=text %}

{% capture text %}**Note:** Quotas cannot be previewed – they are applied only when the survey is active.{% endcapture %}
{% include alert.md text=text color="warning" %}

## Reordering Question Groups and Questions

{% capture text %}
1.	In the `Survey explorer` panel on the left-hand side of the screen, click on the `Question Organizer` button.
2.	Point the mouse to the top of the `Consent` question group to display a four-headed arrow mouse cursor.  Click and drag the question group to the top of the Survey so that it will appear first.
3.	Click the `Save and Close` button.
4.	Preview the survey. Remember the `Quota` will not apply until the survey is upgraded to Production and activated.{% endcapture %}
{% include card.md header="Reorganise questions" text=text %}

---

{% capture text %}**Ready to move on?** Head to the [next page](6-registration.html) or [ask a question](https://griffithu.padlet.org/y_banens1/gli5hpobgpzwcuym){:target="_blank"}. {% endcapture %}
{% include alert.md text=text color="success" %}
