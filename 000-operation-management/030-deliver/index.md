---
title: 030 Deliver
permalink: 030-deliver.html
url: 030-deliver
layout: page
---

## Preview
[preview]( 000-operation-management/030-deliver/preview/index.html )


## SCORM
You can download the SCORM package to be integrated into an LMS, e.g. Moodle.

{% assign files = site.static_files  %}
{% for file in files   %}
{% if file.path contains file.url and file.path contains  'zip' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}


## Content
The theoretical contents of the course are shown below.

{% assign files = site.static_files  %}
{% for file in files   %}
{% if file.path contains file.url and file.path contains  'pdf' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}




