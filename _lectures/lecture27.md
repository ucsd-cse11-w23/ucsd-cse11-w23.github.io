---
layout: with-sidebar
index: 27
name: AUA and Goodbye!
released-on: "2023-03-17"
worksheets:
  - title: Lecture
    url: https://drive.google.com/file/d/1FSE4h8Ub79Ei-0U57xrhmWYZFmtT8rkr
---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

Survey to be completed (again) by tonight (2 points)

- [CSE 11 - Experiences in CSE - Winter 2023 I](https://forms.gle/S9oDaGZpWSMk5Dwb9)

Please submit your CAPEs for the course at [https://cape.ucsd.edu/](https://cape.ucsd.edu/), including evaluations for your TAs!

The theme of this lecture is “Ask Us (Almost) Anything!” Feel free to ask questions about the course, CSE, our experience, programming, and so on. This can be a mix of review and other topics you find helpful. 

## Handout

<iframe src="https://drive.google.com/file/d/136ff6Qk8LZDZk8GxfjzZqIwO_kRa2p8S/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
</div>
{% endfor %}