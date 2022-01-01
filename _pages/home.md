---
layout: home
title: home
permalink: /
description:

profile:
  align: left
  image: prof_pic.png
  address:

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
---

<!-- <br> -->
<span style="font-weight:500; font-size: 25px" > Hello there!</span>

I am a senior undergraduate at the [Indian Institute of Technology Bombay](https://www.iitb.ac.in/) majoring in [Mechanical Engineering](https://www.me.iitb.ac.in/) and pursuing dual minor degrees in the [Department of Computer Science](https://www.cse.iitb.ac.in/) and the [Centre of Machine Intelligence and Data Science](https://www.minds.iitb.ac.in/).<br>

During my undergraduate studies, I was fortunate to work under the guidance of wonderful mentors. I am working with [Prof. Soumen Chakrabarti](https://www.cse.iitb.ac.in/~soumen/) and [Prof. Abir De](https://www.cse.iitb.ac.in/~abir/) on my Undergraduate Thesis and I have worked with [Prof. Chakrabarti](https://www.cse.iitb.ac.in/~soumen/) on another research project dealing with entity alignment in multilingual knowledge graphs.<br>

I intend to use this website to give the world a peek into my mind and to share updates about my work.
<br><br>

<h4>Updates</h4>
<div class="news">
  {% assign news = site.news %}
  {% for item in news %}
  {{ item.content }}
  {% endfor %}
</div>
<br>

<h4>Research Interests</h4>
I am broadly interested in language technologies for bridging the interaction gap between humans and computers and applications of AI in Healthcare. More specifically, my research interests include [Knowledge Graphs](https://en.wikipedia.org/wiki/Knowledge_graph), [Natural Language Processing](https://en.wikipedia.org/wiki/Natural_language_processing), Graph Learning, and [Reinforcement Learning](https://en.wikipedia.org/wiki/Reinforcement_learning).
<br><br>

<h4>Experience</h4>
Check out my <a href="{{ 'projects' | relative_url }}">research and other key projects</a>, and my <a href="{{ 'work' | relative_url }}">professional work experience</a>. 
<br><br>


<h4>Teaching Responsibilities and Service</h4>
<br>
<div class="work">
  
  <div class="work-item">
    <div class="work-bubble-with-date">
      <img src="/assets/img/teaching.jpg" class="work-bubble" />
    </div>
    <p class="work-text">
      <strong>Teaching Assistant | IIT Bombay</strong> <br/>
      <span style="font-size: 0.9rem">
       » IE 643 - Deep Learning, Fall 2021 <br>
       » ME 119 - Engineering Graphics and Drawing, Fall 202 <br>
       » MA 106 - Linear Algebra, Spring 2021 <br>
       » MA 108 - Differential Equations, Spring 2021 <br>
       » PH 107 - Quantum Physics and applications, Fall 2020 <br>
       </span>
    </p>
  </div>

  <div class="work-item vertical-center-text">
    <div class="work-bubble-with-date">
      <img src="/assets/img/smp.jpg" class="work-bubble" />
    </div>
    <p class="work-text">
      <strong>Department Academic Mentor, Mechanical Engineering, from Fall 2021</strong> <br/>
      <strong>Institute Student Mentor, from Fall 2021</strong> <br/>
    </p>
  </div>

  <div class="work-item vertical-center-text">
    <div class="work-bubble-with-date">
      <img src="/assets/img/erc.jpeg" class="work-bubble" />
    </div>
    <p class="work-text">
      <strong>Manager, Electronics and Robotics Club, IIT Bombay, 2020-21</strong> <br/>
    </p>
  </div>


</div>