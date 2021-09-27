---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
---

Education
======
* Ph.D. in Computer Science, University of Utah (Expected graduation: May 2022)
* B.Tech in Computer Science and Engineering, Indian Institute of Technology (IIT) Kanpur, 2016

Work experience
======
* Summer 2021: ML Engineer Intern
  * Implemented a NLP based conversational AI assistant to provide low-friction discovery of advanced features.
  * Created end-to-end architecture and APIs to deploy trained models in a scalable and secure manner using Docker.
  * Used AWS cloud infrastructure and Terraform for MLOps and Python for model creation.

* Summer 2019: Research Intern
  * Proposed a method to create an auto-encoding framework using Recurrent Neural Networks for time-series data.
  * Developed models to create embeddings for entities that capture multiple facets using unsupervised learning.
  * Implemented an end-to-end pipeline in PyTorch to interface with upstream tasks.
  * Implemented efficient and scalable models capable of handling more than a million data points.

* Jun 2016 - July 2017
  * Built and optimized ETL pipelines for processing device logs for Samsung smartphones using Apache Spark.
  * Proposed and implemented methods to find recurrent temporal patterns in smartphone usage and app activities.
  * Developed server side aggregation for upto 500 million daily users with nearly 5 billion data points.
  * Integrated the output from above into the intelligence module for Bixby in low-resource high-throughput setting.
  
Skills
======
* Programming Languages - Python, Javascript, C, Terraform
* Data Science - Tensorflow, Pytorch, Scikit-Learn, Numpy, Pandas, Apache Spark (PySpark), SQL
* Frameworks - Vue, Angular, CSS, HTML, D3.js (frontend), Docker (container technology), Hadoop, Spark, AWS (cloud and distributed computing)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
