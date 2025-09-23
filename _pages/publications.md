---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>
<h1 class="page__title">Projects</h1>

<h2 class="archive__item-title" itemprop="headline">
      
  Interactive Earth Climate Visualisation in Unity
    
</h2>
This project uses Python to process and visualize global atmospheric data from the TROPOMI satellite, specifically focusing on methane concentrations. The code cleans the data, handles land/sea masking, and generates high-resolution global map plots. These 2D map outputs are designed to be imported into Unity as materials for creating interactive 3D visualizations of climate trends.

The github repo for plotting the atmospheric data can be accessed [here](https://github.com/Laprama/Climate_Data_Visualisation) and the Unity github repo [here](https://github.com/Laprama/Interactive_Earth_Climate_3D_Unity).

![Unity Earth Demo](../images/Unity_Earth_Demo.gif)

   

<h2 class="archive__item-title" itemprop="headline">
      
        <a href="http://w3phiai2023.w3phi.com/hackathon.html" rel="permalink">Ensuring age clock models are not attending to erroneous features for improved
biological age prediction
</a>
     
</h2>
We won a prize of $250 for this work at the 2023 AAAI Health Intelligence Hackathon. Our work used a convolutional neural network to predict biological age from participant MRI images. We looked to improve existing age prediction models by ensuring features known to be unrelated to age were not being attended to by the model. 

   

<h2 class="archive__item-title" itemprop="headline">
      
        <a href="https://arxiv.org/abs/1603.00797" rel="permalink">Explaining Multimodal Activity Predictions for the
SPHERE Challenge using Interactive Visualizations
</a>
      
</h2>

The SPHERE challenge presents an activity recognition task based on multimodal data collected from Smart Home sensors. While aiming to advance the safety of vulnerable people, the intrusive nature of the SPHERE technology renders transparency a particularly important feature of any SPHERE solution. Accordingly, current researchers present an interactive visualization dashboard that offers clear insights into the collected data, while giving healthcare professionals an opportunity to evaluate an algorithm’s predictions and assess sensor activity at the proximate time of an identified incident. Two phases of research are presented: 1) data modelling, 2) dashboard development. After curating multiple datasets that attempted to address key pre-processing challenges (e.g. pertaining to missing data points and an imbalanced class distribution), the data modelling phase trained and tested a series of machine learning models. Using Brier score as the selected evaluation metric, a multilayer perceptron, trained on a subset of selected features, was identified as the top performer with a score of .205. The dashboard development phase then visualised a sample recording sequence, displaying multiple data features for each second of the sequence. Visualizations included: bounding box positions, accelerometer data, the patient’s precise location within the smart home, and the predicted label distribution associated with the given timestep. The resulting dashboard offered insightful information, however there are potential improvements such as integrating a recent history of actions to give a clearer outline of data trends. Its efficacy can be further enhanced by optimising model performance, for example through a more sophisticated weighted re-sampling procedure and a greater focus on recall to emphasise minority classes.

