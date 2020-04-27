---
title: Setup
nav: true
---

# Setting up your survey 

<iframe width="560" height="315" src="https://www.youtube.com/embed/A2eSz9Wph64" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Creating a survey

{% capture text %}
1.	Open a browser and go to the `Research Survey Centre` web page.
NOTE:  If you are working off-campus, you will need to connect via the VPN client.
2.	Click on the `Register or Upgrade` link in the navigation panel on the left.
3.	Click on `Register a new Survey`.
4.	Log in with your Griffith “s” number and password, then click the `Log in` button.
5.	Click on the `Sandpit survey` radio button.
6.	Fill in the details for the survey, noting that some fields are mandatory.  For this exercise, enter the title **Healthy Lifestyles**.
7.	Click the `Submit` button.{% endcapture %}
{% include card.md header="Registering a survey" text=text %}

## Accessing the survey

{% capture text %}
1.	You will have received an email to your Griffith Outlook account which contains a link to open the survey.  For now, click on the [https://prodsurvey.rcs.griffith.edu.au/prodls200/admin](https://prodsurvey.rcs.griffith.edu.au/prodls200/admin) link that you see on the screen in front of you.
{% capture text %}**Note:** You can bookmark this page or add it to your Favorites for easy access later on.{% endcapture %}
{% include alert.md text=text color="info" %}
{% endcapture %}
{% include card.md header="Accessing the survey" text=text %}

## Logging in to LimeSurvey

{% capture text %}
1.	Log in again with your Griffith “s” number and password, then click the `Log in` button.
{% capture text %}**Note:**  Your Griffith Single Sign-On credentials have been automatically authenticated with LimeSurvey login.{% endcapture %}
{% include alert.md text=text color="info" %}
2.	Click on the `List surveys` button.  Any surveys you have created will be listed.
3.	Click on the survey you want to open.
4.	Read any warnings (shown in brown) and any information panels (shown in blue).  The large buttons on the screen are highlighted blue (available) or grey (not available at this time).{% endcapture %}
{% include card.md header="Logging in to LimeSurvey" text=text %}


## Texts and general settings

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/OXf8LPtgPOw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

{% capture text %}
1.	Click on the large `Edit text elements and general settings` button on the screen.
2.	Click into the `Title:` text box.
3.	Add: **(S)** to the end of the Title to indicate that the survey is in Sandpit. 
{% capture text %}**Note:** This can be deleted when the survey is upgraded to Production.{% endcapture %}
{% include alert.md text=text color="info" %}
{% endcapture %}
{% include card.md header="Survey properties - Title" text=text %}
 
## Survey description

{% capture text %}
1.	Click into the `Description:` text box.
2.	Type:    **Do YOU have a healthy lifestyle?**{% endcapture %}
{% include card.md header="Survey properties - Description" text=text %}


## Understanding the HTML toolbar

{% capture text %}
{% include figure.html img="text-edit-controls.png" alt="The text editing controls on LimeSurvey" caption="LimeSurvey text editing controls" width="100%" %}
The `HTML toolbar` provides options for text formatting in any LimeSurvey text box that allows it.  Most of the buttons will be familiar to you as they are very similar to the functions you see on the Microsoft Word ribbon.
The first button on the toolbar expands and collapses the text box and is useful if you have a lot of text or a lot of formatting.
1.	Explore and familiarise yourself with the buttons on the `HTML toolbar`.
2.	In the `Description:` text box, `Bold` the text **YOU**.{% endcapture %}
{% include card.md header="Understanding the HTML toolbar" text=text %}


## Add images

An image might be a corporate or brand logo, especially if you are conducting collaborative research. Alternatively, you may be using an image as a stimulus for your participants to respond to.

{% capture text %}
1.	Still in the `Description:` text box, insert some ``<Enter>`s before the text, then position the insertion point at the top.
2.	On the `HTML toolbar`, click the `Insert image` button.
3.	In the `Image Properties` dialog box, click on the `Browse Server` button.
4.	Click the `Upload` button and browse to the **Exercise Files** folder.
5.	Select **HealthyLogo.PNG** and click `Open`.  The file will be uploaded to the `Images` folder on the LimeSurvey server.
6.	Double-click on the image to display the `Image Properties` dialog box again.
7.	Adjust the properties to suit and click `OK`.{% endcapture %}
{% include card.md header="Survey properties - adding images" text=text %}


## Survey Properties

{% capture text %}
1.	Click into the `Welcome message:` text box.
{% capture text %}**Note:** If you have previously planned your survey in a Microsoft Word document, you might want to copy and paste some text to save typing it again.  Copying and pasting directly from a Microsoft Word document can cause problems as Word has its own underlying codes, so you should always use the `Paste as Plain Text` button on the `HTML toolbar` then reapply any formatting.{% endcapture %}
{% include alert.md text=text color="warning" %}

2.	Type (or copy and `Paste as Plain Text`):

>There's often so much going on in an average day that it's hard to stop and think, so it's easy for a few bad habits to slip into everyone's daily routine.
We've put together this assessment to help you identify where you are doing well, and where there is room for improvement. On completion, you'll receive a personalised report containing advice and guidance on keeping yourself healthy.
Click Next to begin.

Note that the larger portion of text goes into the `Welcome message` and not into the `Description` as you might think.  This is because the underlying template uses a large font for the Description field – too much text would fill a screen!{% endcapture %}
{% include card.md header="Welcome message" text=text %}


{% capture text %}
1.	Still in the `Welcome message:` text box, insert some `<Enter>`s after the text and type **Please read the Code for the Responsible Conduct of Research**.
2.	Select the text **Code for the Responsible Conduct of Research**, then on the `HTML toolbar`, click the `Link` button.
3.	Click the `Browse Server` button.  Any files already uploaded will be listed here and can be selected.
4.	To upload a new file, click the `Upload` button and browse to the **Exercise Files** folder.
5.	Select The Responsible Conduct of Research.pdf and click Open.  The file will be uploaded to the Files folder on the LimeSurvey server.
6.	Once uploaded, double-click on the file to include it.

{% capture text %}
**Link targets**
In web technologies, Target refers to the window in which the linked item is displayed.  The default is <_Self> which means the window that is currently open.  This setting would require users to click the `<Back>` button to return to the survey and can be confusing for some users.  Whenever you are linking to a document, the `Target` should always be set to **New Window (_blank)**.
**Note:** Most browsers read “new window” to mean “new tab”.{% endcapture %}`
{% include alert.md text=text color="info" %}


7.	Still in the `Link` dialog box, click the `Target` tab.
8.	Click the `Target selection list arrow`.
9.	Click on **New Window (_blank)** to select it.
10.	Click the `OK` button.{% endcapture %}
{% include card.md header="Attaching documents" text=text %}
 
## End message, End URL and URL description

At the end of the survey, you will want to thank your participants for taking the time to complete your survey. You may also want to direct them to another page for further information, or to enter a prize draw.

{% capture text %}
1.	Click into the `End message:` text box.
2.	Type:    **Thank you for taking the time to complete this survey.**
3.	Click into the `End URL:` text box (optional)
4.	Type:    **www.griffith.edu.au**
5.	Click into the `URL description:` text box (used only when `End URL` is used)
6.	Type:    **Griffith University**{% endcapture %}
{% include card.md header="End message, End URL and URL description" text=text %}

{% capture text %}You have now completed the Welcome, Description and End messages for your survey. Next, you will want to check the general settings of your survey, before you begin to add questions.{% endcapture %}
{% include alert.md text=text color="success" %}

---

## Survey settings panel

{% capture text %}
The `Survey settings panel` is on the right-hand side of the `Edit survey text elements and settings` screen.
1.	Clicking on any **left-facing arrowhead** will expand the `Survey settings`.
2.	Click on each **heading** to explore the options but don’t select anything at this time.{% endcapture %}
{% include card.md header="Survey settings panel" text=text %}


## Save buttons

{% capture text %}
Near the top on the right-hand side of the screen you will see three buttons:  Save, Save and close and Close.
•	The `Save` button saves your changes and allows you to continue editing.
•	The `Save and close` button saves your changes and closes the current screen.
•	The `Close` button closes the current screen without saving.

1.	Click the `Save and close button`.{% endcapture %}
{% include card.md header="Survey settings panel" text=text %}

---
