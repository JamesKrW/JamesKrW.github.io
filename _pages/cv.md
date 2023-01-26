---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Science, Shanghai Jiao Tong University University, 2018-2022
* Pre-Doctoral M.S. in Computer Science, University of Chicago, 2022-present
<!-- * Ph.D in Version Control Theory, GitHub University, 2018 (expected) -->

Research experience
======
* Fall 2022-present: Research Assistant
  * Toyata Technological Institute at Chicago
  * Duties included: 
    * Created a multi-choice QA dataset based on EntailmentBank
    * Applied adversarial matching in generating the negative choices:
      * Used dependency parser and English tokenizer in sentence alignment.
      * Fine-tuned BERT to calculate the relevance between choice and question. Calculated sentence
    similarity with all-mpnet-base-v2.
      * Evaluted the dataset on GPT3.
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
