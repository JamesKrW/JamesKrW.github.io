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
* Logical Inference and Event Predict
  * Oct 2022-present: Research Assistant
  * Toyata Technological Institute at Chicago
  * Supervisor: Professor Hongyuan Mei, Mo Yu
  * Duties included: 
    * Created a multi-choice QA dataset based on EntailmentBank
    * Applied adversarial matching in generating the negative choices:
      * Used dependency parser and English tokenizer in sentence alignment.
      * Fine-tuned BERT to calculate the relevance between choice and question. Calculated sentence
    similarity with all-mpnet-base-v2.
      * Evaluted the dataset on GPT3.
  

* Towards Continually Learning Application Performance Models
  * Sep 2022-present: Research Assistant
  * University of Chicago, UCARE group
  * Supervisor: Professor Haryadi s. Gunawi
  * Duties included: 
    * Applied Online Continual Learning methods in making decisions about job scheduling
    * Improved model overtime while alleviating catastrophic forgetting of prior knowledge or experiences
caused by concept drifts.
    * Created Siamese-network based model to detect data drifts after software upgrades and hardware
degradation.

* Information Interactions in Languages and Images
  * Sep 2021-June 2022: Research Assistant
  * Shanghai Jiao Tong University, Explainable AI Laboratory
  * Supervisor: Professor Quanshi Zhan
  * Duties included: 
    * Applied Online Continual Learning methods in making decisions about job scheduling
    * Improved model overtime while alleviating catastrophic forgetting of prior knowledge or experiences
caused by concept drifts.
    * Created Siamese-network based model to detect data drifts after software upgrades and hardware
degradation.

* Trap of Feature Diversity in the Learning of MLPs
  * June 2021–Mar 2022: Research Assistant
  * Shanghai Jiao Tong University, Explainable AI Laboratory
  * Supervisor: Professor Quanshi Zhan
  * Duties included: 
    * Explained a two-phase phenomenon discovered in the learning of MLPs and named it as the self-
activated state
    * Derived the learning dynamics of the MLPs
    * Experimented different method to avoid self-activated state and verified that this effect could be
eliminated by adding the Batch Normalization

* Federated Learning on Mobile Devices
  * Sep 2020–June 2021: Research Group Leader
  * Shanghai Jiao Tong University, Advanced Network Laboratory
  * Supervisor: Professor Fan Wu
  * Duties included: 
    * Transplanted pre-trained face recognition model to the industrial robots and implemented real-time
face recognition in robot based on video stream and pre-trained mode
    * Designed federated learning system, which enabled data-share among robots while privacy guaran-
teed
    * Solved Non-IID problem in federated learning and class-incremental problem in face recognition by
modifying FedAvg






  

Skills
======
* Programming Languages
  * Python, C/C++, Java
  * MATLAB
  * Verilog
  * LaTex
* Framework
  * Pytorch, Tensorflow, JAX
  * Spring Boot, MySQL
  * Hadoop, Spark
* DNN Architecture&Model
  * Diffusion Model, GAN, VAE
  * BERT, GPT3
  * Transforme, RNN, CNN

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
