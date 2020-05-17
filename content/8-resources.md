---
title: Resources
nav: true
---

# Exporting to SPSS and additional support Resources 

## Exporting to SPSS
SPSS Statistics is a software package used for logical batched and non-batched statistical analysis. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/C0omLC2Pq44" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

There are two parts to an SPSS export from LimeSurvey:
 - The syntax file (`survey_xxxx_SPSS_syntax_file.sps`) holds the commands that should be run to import the data. It is like a programming language inside SPSS.
 - The data file (`survey_xxxx_SPSS_data_file.dat`) contains a comma separated value file with all data.

### General

{% capture text %}
1.	Go to the Survey quick actions screen (the Home screen) and click on the Responses button.
2.	Click on Responses & statistics.
3.	Click the Export button, then click on Export results to a SPSS/PASW command file.{% endcapture %}
{% include card.md header="To export your response data to SPSS:" text=text %}

{% capture text %}
When exporting data to SPSS there are two filter options:
 - you can select which data should be selected (all records/complete records only/incomplete records only) and
 - the SPSS version the export files will be compatible with (prior version 16/16 or up).
Follow the instructions shown below (also shown on the Export response data to SPSS page):

1.	Click on the `Export syntax` button to download the syntax file
2.	Click on the `Export data` button to download the syntax file to the same location as the syntax file
3.	Open SPSS
4.	Click on `File`, `Open`, `Syntax`
5.	Choose the appropriate file (e.g. `c:\desktop\survey_xxxx_SPSS_syntax_file.sps`)
6.	When the syntax file opens, change the line that reads:
`FILE='survey_xxxx_SPSS_data_file.dat`'
to include the path where the files are, e.g.:
`/FILE='c:\desktop\survey_xxxx_SPSS_data_file.dat`'
(for Mac user: `/FILE='HD/Users/username/survey_xxxx_SPSS_data_file.dat`')

{% capture text %}NOTE:  include the single quote marks{% endcapture %}
{% include alert.md text=text color="primary" %}

7.	Now mark the whole command text and click on `Run`, `All` from the menu.
{% endcapture %}
{% include card.md header="Export and filter data" text=text %}

{% capture text %}PLEASE BE PATIENT WHILE THE DATA FILE LOADS.{% endcapture %}
{% include alert.md text=text color="secondary" %}

---

## Additional resources

Use the resources on the website to guide you:

###  Help & Resources

This page contains helpful pointers, hints, tips, links and documents to assist you with the creation of your surveys.

### Training & Consultations

In this page, you can get electronic copies of training documents, as well as registering for additional LimeSurvey™ training or book a consultation

### Services we Offer

This page lists the services offered by the Research Survey Tool Support Team.

### Request Help

From this page, you can submit a request for assistance from the Research Survey Tool Support Team.

### Provide Feedback

A webform for providing feedback to the Research Survey Support Team.

### Frequently asked Questions

See what other users have been concerned about.

### Contact Us

This page provides contact details for the LimeSurvey™ first-level support.  

{% capture text %}Note that your request may be escalated to the Research Survey Tool Support Team if required.{% endcapture %}
{% include alert.md text=text color="info" %}

It's time to start asking questions! Use the Padlet below to add a question. You might prefer to open it in a new window. 

<div class="padlet-embed" style="border:1px solid rgba(0,0,0,0.1);border-radius:2px;box-sizing:border-box;overflow:hidden;position:relative;width:100%;background:#F4F4F4"><p style="padding:0;margin:0"><iframe src="https://griffithu.padlet.org/embed/gli5hpobgpzwcuym" frameborder="0" allow="camera;microphone;geolocation" style="width:100%;height:608px;display:block;padding:0;margin:0"></iframe></p><div style="padding:8px;text-align:right;margin:0;"><a href="https://padlet.com?ref=embed" style="padding:0;margin:0;border:none;display:block;line-height:1;height:16px" target="_blank"><img src="https://padlet.net/embeds/made_with_padlet.png" width="86" height="16" style="padding:0;margin:0;background:none;border:none;display:inline;box-shadow:none" alt="Made with Padlet"></a></div></div>

<!-- 

To learn about using `workshop-template-b`, the [Readme](https://github.com/evanwill/workshop-template-b/blob/master/README.md) and content pages have some documentation.

Workshop sites using this template:

- [Make OER!](https://evanwill.github.io/make-oer/) (presentation)
- [Hey API!](https://evanwill.github.io/hey-api/) (workshop)
- [Teaching Tech Hands-on](https://evanwill.github.io/tech-hands-on/) (presentation)
- [Refine APIs](https://evanwill.github.io/refine-apis/) (workshop)
- [Mini Web Crash Course](https://evanwill.github.io/mini-web-crash-course/) (workshop)

Other workshop sites an [minimal version of this template](https://github.com/evanwill/workshop-template) (no bootstrap):

- [get-git](https://evanwill.github.io/get-git/)
- [hello-arduino](https://evanwill.github.io/hello-arduino/)
- [clean-your-data](https://evanwill.github.io/clean-your-data/)
- [go-go gh-pages](https://evanwill.github.io/go-go-ghpages/)
- [Make @ the MILL](https://uidaholib.github.io/make-at-the-mill/)

# Reference

### Git & GitHub

[GitHub](https://github.com/){:target="_blank" rel="noopener"} is a popular web service for hosting Git repositories--with benefits!
It provides a handy web interface for editing and collaborating on repos, as well as, built in project management features and [free static web hosting](https://pages.github.com/){:target="blank"} powered by [Jekyll](https://jekyllrb.com/){:target="blank"}.
Accounts are free.
To learn more check out Hellow World on [GitHub Guides](https://guides.github.com/){:target="_blank" rel="noopener"} or [GitHub Training](https://services.github.com/on-demand/){:target="_blank" rel="noopener"}.

### Markdown

[Markdown](https://daringfireball.net/projects/markdown/) is a standard to simplify writing content for the web. 
[GitHub markdown flavor](https://help.github.com/articles/basic-writing-and-formatting-syntax/) can be used any where on GitHub and in Jekyll.

- [Markdown in a Minute](https://evanwill.github.io/_drafts/notes/markdown-minute.html)
- GitHub Guide [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

### Bootstrap 4

[Bootstrap](https://getbootstrap.com/) is a CSS framework designed to streamline developing user interfaces for your website. 
It is combined with a JavaScript library [jQuery](https://jquery.com/) to simplify adding interactive components. 

### FontAwesome 5

[FontAwesome](https://fontawesome.com/) is an icon set used to easily add icons to websites.
Check the [gallery](https://fontawesome.com/icons?d=gallery&m=free) for the freely available icons.

### YAML

[YAML](http://www.yaml.org/) is a human readable plain text data format.
It is used in Jekyll for configuration, site data, and front matter.
Jekyll projects are [configured](https://jekyllrb.com/docs/configuration/) using the `_config.yml` file.

### Liquid

[Liquid](http://shopify.github.io/liquid/) is a flexible template language.
[In Jekyll](https://jekyllrb.com/docs/templates/) it allows you to layout pages built from modular components and data, using the `_includes`, `_layouts`, and `_data` directories.
Liquid includes features such as operators, loops, and filters to manipulate raw content. 
Liquid statements are enclosed by {% raw %}`{%  %}`{% endraw %} and variables in {% raw %}`{{  }}`{% endraw %}.

### Sass  

[Sass](http://sass-lang.com/) is a CSS extension / preprocessor. 
All normal CSS is valid SCSS, but Sass adds many powerful functions and programatic features. 
Writing SCSS is often easier and more sensible, for example by supporting nesting, variables, and operators. 
Jekyll lets you write SASS in modular chucks called partials, in the `_sass` directory, that will be combined and compiled into normal CSS files when the site is built.
-->

