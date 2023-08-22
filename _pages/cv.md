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
* M.S. in Information Science, University of Pittsburgh, 2024 
* BTech. in Computer Science and Engineering, Indian Institute of Information Technology, Nagpur, 2021

Research experience
======

* **Stanford Intelligent Systems Laboratory** 
  * Summer 2023: Independent Student Researcher
  * Supervisor: Mansur Arief
    * Improving rare traffic sign recognition via data augmentation: Addressed challenges of out-of-training distribution images (e.g., Rusty traffic signs), crucial for vehicle perception systems.
    * Augmented the German Traffic Sign Recognition Benchmark dataset through neural style transfer, introducing rusty sign images. Constructed a pipeline with Variational Prototyping Encoders to identify rare image class, achieving a 0.90 class-weighted F1 score

* **University of Pittsburgh**
  * Summer 2023: Graduate Student Researcher
  * Supervisor: Daqing He
    *  Guided summarization of clinical notes: Developed a comprehensive summary template covering patient demographics, chief complaint, OPQRST assessment, diagnostics, treatment, etc
    * Developed a sentence classifier to determine sentence importance within clinical notes, providing guidance to the BART-based summarization model.
    * Additionally, fine-tuned a Bio-ClinicalBERT-based Named Entity Recognition (NER) system, enabling the implementation of a fact-checking metric for validating predicted summaries against the ground truth.
    * Currently experimenting with medically focused prompt engineering techniques by running multi-GPU inference using Huggingface Accelerate on large language models (LLMs) like LLaMA to improve the task of clinical note summarization.

* **University of California, San Diego**  
  * 2021-2022: Research Intern
  * Advisor: Pengtao Xie 
    * Neural Architecture Search (NAS) for Pneumonia Diagnosis: Implemented Neural Architecture Search (NAS) for improving pneumonia diagnosis from Chest X-Ray images by Leveraging the ’Learning By Teaching’ framework, inspired by teacher-student learning paradigm that outperforms previous NAS methods like DARTS and PC-DARTS by 5.1%
    * The searched model attained a 97.6% ROC-AUC score for pneumonia detection, while being 4% smaller than DARTS. 
    * Reading by Translating: Implemented the ’Reading by Translating’ framework that improves the task of ’Machine Reading’ i.e extracting meaningful instances from the dataset. 
    * Involves 2 transformer based encoder-decoder models, that are trained mutually on the task of Machine Translation to learn importance weights assigned to the dataset instances. 

* **Tata Research, Design and Development Centre**  
  * 2020: Research and Development Intern
  * Advisor: Sagar Sunkle
    * Named Entity Recognition (NER): Worked on information retrieval using NER on domain-specific scientific corpora.
    * Implemented incremental learning for NER by adapting classifiers from open-source libraries such as Adaptive Random Forests, AdaBoost, Pretrained Spacy NER, Conditonal Random Fields (CRF) and Seq2Seq model.
    * Developed an ’Extractive search system for entity retrieval’ similar to AllenAI’s Spike cord search system that enables one to perform selective information extraction and annotate results by querying

* **National Institute of Technology, Nagpur** 
  * 2018: Research Intern
  * Advisor: Dr. Mansi A Radke
    *  Word sense disambiguation: Detected the 'geospatialness' of a preposition in a sentence.
    * Formulated a geo-parser using NLP (implemented in Python) preprocessing tools that performed gazetteer lookups to extract placenames and geo-feature types from a sentence.
    * Implemented baseline classification methods like Naive Bayes, BayesNet, Random Forests, SVM’s and meta-classifiers. 
    * Conducted a comparative study by fine-tuning  pre-trained models like ULMFiT, XLNet, Transformer-XL, RoBERTa, BERT, ALBERT and DistilBERT.
    * Achieved an F1 score of 0.947, an increase of 15% as compared to baseline methods

  
Skills
======
* Languages - Python, R, MySQL, C++, C, Bash
* ML/DL - PyTorch, Tensorflow, Fastai, Keras, scikit-learn, spaCy, Hugging Face, Langchain, Caret, glmnet
* Data Processing - Pandas, NLTK, CoreNLP, Gensim, Tidyverse (Dplyr, Tibble, Purrr), igraph
* Visualisation - Matplotlib, Seaborn, ggplot
* Graduate Coursework: Machine Learning in R (Code), Databases, Algorithms, Data Mining, Artificial Intelligence, Information Storage and Retrieval
* Undergraduate Coursework: Natural Language Processing, Deep Learning, Computer Vision, Neuro-Fuzzy Techniques, Probability, Graph Theory, Data Science Bio-informatics

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
* Conducted a day long workshop on 'Introduction to Machine Learning' at the Cummins college of Engineering, Nagpur. 

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
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
