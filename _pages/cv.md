---
layout: default
title: CV
permalink: /CV/
description: 
nav: True
nav_order: 1
# social: true # includes social icons at the bottom of the page
---

### Curriculum Vitae and Resume
<br>

<button id="cvButton" class="resumebutton">CV</button>
<button id="resumeButton" class="resumebutton selected">Resume</button>
<iframe id="cvIframe" src="{{ 'Resume.pdf' | relative_url }}" width="100%" height="600px"></iframe>
<br>
<a id="resumeDownloadButton" class="div-right" href="{{ 'Resume.pdf' | relative_url }}" download="ShubhamLohiya_Resume.pdf">
    <button class="resumebutton">Download</button>
</a>

<script>
    var iframe = document.getElementById('cvIframe');

    iframe.onload = function() {
        var width = iframe.offsetWidth;
        iframe.style.height = (1.35 * width) + 'px';
    };

    document.getElementById('cvButton').addEventListener('click', function() {
        document.getElementById('cvIframe').src = "../CV.pdf";
        document.getElementById('resumeDownloadButton').href = "../CV.pdf";
        document.getElementById('resumeDownloadButton').download = "ShubhamLohiya_CV.pdf";
        this.classList.add('selected');
        document.getElementById('resumeButton').classList.remove('selected');
    });

    document.getElementById('resumeButton').addEventListener('click', function() {
        document.getElementById('cvIframe').src = "../Resume.pdf";
        document.getElementById('resumeDownloadButton').href = "../Resume.pdf";
        document.getElementById('resumeDownloadButton').download = "ShubhamLohiya_Resume.pdf";
        this.classList.add('selected');
        document.getElementById('cvButton').classList.remove('selected');
    });
</script>