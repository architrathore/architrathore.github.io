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

Skills
======
  * Research - Machine Learning, Deep Neural Networks, Topological Data Analysis, Ethics and Fairness in ML
  * Programming Languages - Python, Javascript, C
  * Data Science - Tensorflow, Pytorch, Scikit-Learn, Numpy, Pandas, Apache Spark (PySpark), SQL, Jupyter
  * Frameworks - Vue, Angular, Docker, Terraform, Hadoop, Spark, AWS (ECS, Fargate, API Gateway)

Research
======
I work on understanding ML models through the lens of Computational Topology and Visualization. I believe that the strong mathematical foundations of topological analysis and interactive capabilities through visualization techniques can help traverse the inherently complex structures of ML models, especially in the context of deep learning. I am create frameworks for Topological Data Analysis (TDA) and visualization to analyze and reason about deep learning models, as a step towards explainable and interpretable ML.

Work experience
======
* Summer 2021: ML Engineer Intern @ OpenSesame Inc, OR
  * Built a data pipeline and NLP based chatbot service to provide course recommendation to learning admins.
  * Created the architecture and APIs to deploy trained models in a scalable and secure manner.
  * Planned and coordinated integration of the chatbot service with the recommendation system and frontend UI. 
  * Chatbot prototype identified as one of the key goals for the data science arm of the organization.

* Summer 2019: Research Intern @ VISA Research, CA
  * Proposed a method to create auto-encoding models using Recurrent Neural Networks for financial transactions.
  * Developed models to create embeddings for entities under weak labels.
  * Implemented an end-to-end pipeline in PyTorch to interface with upstream tasks.
  * Implemented efficient models capable of handling more than a million data points using pruning and distillation.

* Jun 2016 - July 2017 @ Samsung Research, Bangalore
  * Built and optimized ETL pipelines for processing device logs for Samsung smartphones using Apache Spark.
  * Proposed and implemented methods to find recurrent temporal patterns in smartphone usage and app activities.
  * Deployed distributed processing pipelines for 500 million daily users with nearly 5 billion data points.
  * Integrated the output from above into the intelligence module for Bixby in low-resource high-throughput setting.

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
  
