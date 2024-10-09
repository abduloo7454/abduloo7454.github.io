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
* Ph.D in Machine Learning, Universiti Teknologi PETRONAS, 2024
* M.S. in Mathematics, AMU, India, 2018
* B.S. in Mathematics, AMU, India, 2016

Work experience
======
* 2021 - 2024 Thesis: Development of adaptive threshold and graph-based methods for electroencephalogram channel selection in brain-computer interface.
  * Developed an adaptive threshold-based method integrated with a modified Convolutional Neural Network (CNN) architecture to enhance EEG channel selection in Brain-Computer Interface (BCI) applications. This approach 
    achieved significant improvements in accuracy, reaching 93.90% with the k-adaptEEGCS model and 95.60% with the G-EEGCS model.
  * Introduced Hyper-GCN, a novel hyperscanning EEG signal classification approach in an end-to-end manner. This introduces graph convolutional neural networks (GCN) to handle the spatial-temporal dynamics of EEG data for 
    improving the accuracy of neuroimaging studies. The model achieved an accuracy of 95.92\% on eight average subject-wise trials and 93.54\% on a hyperscanning dataset containing considerable variability in tasks.

  
Tools
======
* Pandas, Numpy, Matplotlib, Seaborn, Plotly, Sklearn, Keras, PyTorch, R, Matlab, Tableau, Streamlit
* GNN, GCN, CNN, K-means, PCA, Transformer
* MS Word, Excel, PowerPoint

Skills
======
* Applied Mathematics
* Probability
* Python Programming
* Deep Learning
* Linear Algebra
* Calculus
* Optimization
* Reinforcement Learning

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Reviewer
======
* Health information science and systems (SPRINGER)
* Human-centric intelligent systems (SPRINGER)
* ICONIP conference
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

