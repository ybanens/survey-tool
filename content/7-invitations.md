---
title: Invitations
nav: true
---

# Invitations

When you have a list of names and email addresses you'd like to invite, you can use closed-access mode to create unique invitations and track responses.  You can even send reminders to people who haven't completed the survey.

<iframe width="560" height="315" src="https://www.youtube.com/embed/G45Ou4w_QZQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

{% capture text %}Note: There are some important caveats to closed-access mode. Participants must use the unique link they are sent and are (usually) unable to use their invitation more than once.{% endcapture %}
{% include alert.md text=text color="warning" %}

{% capture text %}
1. Click on `Survey participants`
2. At the warning screen, click `Initialise participant table`
3. Click `Continue`{% endcapture %}
{% include card.md header="Setting up closed-access mode" text=text %}

Once you've created the table, click on `Display participants' to see your table. Now it's time to add some dummy data. 

{% capture text %}
1. CLick `Create`
2. Select `Add participant`
3. Enter your first name and your university email address in the relevant fields. Leave all the other fields blank. 
4. Click `Save`
5. Click '`Browse survey participants'{% endcapture %}
{% include card.md header="Setting up closed-access mode" text=text %}

Now you'll need to generate a token for your participant. Tokens are (usually random) alphanumeric strings that uniquely identify each participant and allow them to complete the survey.

{% capture text %}By default, each token can only be used once. You can alter this if you need to. {% endcapture %}
{% include alert.md text=text color="info" %}

{% capture text %}
1. Click `Generate tokens`
2. Click `Yes` to the info panel
3. Click `OK` {% endcapture %}
{% include card.md header="Generating tokens" text=text %}

## Sending invitations

Now that you have a participant (yourself) and a valid toekn, you're going to send an invitation to yourself. 

{% capture text %}
1. Click `Invitations and reminders
2. Select `Send email invitation`
3. Highlight and delete the text in the invitation field and type or paste the following: 

**Dear {FIRSTNAME}**  
**Please complete the following survey: {SURVEYNAME}**  
**Access the survey here: {SURVEYURL}**  
**Note that this link is unique to you and can only be used once.**  

4. Click 'Send invitations`{% endcapture %}
{% include card.md header="Create an invitation" text=text %}

You should receive the invitation in your email straight away. You can test that the invitation link works by clicking on the link in your email.
---

{% capture text %}**Ready to move on?** Head to the [next page](8-resources.html) or [ask a question](https://griffithu.padlet.org/y_banens1/gli5hpobgpzwcuym){:target="_blank"}. {% endcapture %}
{% include alert.md text=text color="success" %}
