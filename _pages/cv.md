---
layout: page
title: CV
permalink: /CV/
nav: True
nav_order: 1
# social: true # includes social icons at the bottom of the page
---

<!-- <a href="{{ 'CV.pdf' | relative_url }}">
    <img src="{{ 'pdf.svg' | prepend: '/assets/' | relative_url }}" alt="CV" title="Dowload CV" height="30px"> &nbsp;
    <span style="color:var(--global-theme-color); font-size:1.25em; position: relative; top: 4px;"> Curriculum Vitae </span>
</a> &nbsp; &nbsp; &nbsp;
<a href="{{ 'Resume.pdf' | relative_url }}">
    <img src="{{ 'pdf.svg' | prepend: '/assets/' | relative_url }}" alt="Resume" title="Dowload Resume" height="30px"> &nbsp;
    <span style="color:var(--global-theme-color); font-size:1.25em; position: relative; top: 4px;"> Resume </span>
</a> -->

<!-- <iframe src="{{ 'Resume.pdf' | relative_url }}" width="100%" height="600px"></iframe> -->

<button id="cvButton" class="resumebutton">CV</button>
<button id="resumeButton" class="resumebutton selected">Resume</button>
<iframe id="cvIframe" src="{{ 'Resume.pdf' | relative_url }}" width="100%" height="600px"></iframe>