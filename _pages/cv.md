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
* BTech. in Computer Science and Engineering, Indian Institute of Information Technology, Nagpur, 2021
* M.S. in Information Science, University of Pittsburgh, 2024 

Work experience
======
* Summer 2023: Graduate Student Researcher
  * University of Pittsburgh
  * Supervisor: Daqing He
    *  Guided summarization of clinical notes: Developed a comprehensive summary template covering patient demographics, chief complaint, OPQRST assessment, diagnostics, treatment, etc
    * Developed a sentence classifier to determine sentence importance within clinical notes, providing guidance to the BART-based summarization model.
    * Additionally, fine-tuned a Bio-ClinicalBERT-based Named Entity Recognition (NER) system, enabling the implementation of a fact-checking metric for validating predicted summaries against the ground truth.
    * Currently experimenting with medically focused prompt engineering techniques by running multi-GPU inference using Huggingface Accelerate on large language models (LLMs) like LLaMA to improve the task of clinical note summarization.

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Skills
======
* Languages - Python, R, MySQL, C++, C, Bash\
* ML/DL - PyTorch, Tensorflow, Fastai, Keras, scikit-learn, spaCy, Hugging Face, Langchain, Caret, glmnet\
* Data Processing - Pandas, NLTK, CoreNLP, Gensim, Tidyverse (Dplyr, Tibble, Purrr), igraph\
* Visualisation - Matplotlib, Seaborn, ggplot\
* Graduate Coursework: Machine Learning in R (Code), Databases, Algorithms, Data Mining, Artificial Intelligence, Information Storage and Retrieval\
* Undergraduate Coursework: Natural
Language Processing, Deep Learning, Computer Vision, Neuro-Fuzzy Techniques, Probability, Graph Theory, Data Science, Bio-informatics

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
  {% endfor %}</ul> -->
  
Service and leadership
======
* Currently signed in to 43 different slack teams
