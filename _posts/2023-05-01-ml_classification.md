---
layout: post
title: Compare classification models
date: 2022-05-01 08:57:00-0400
description: based on the titanic disaster data
tags: 
categories: machine_learning
related_posts: true
---

### Compare different classification models using the titanic disaster data 

<br>

| Model | F1 score |
| ------- | ----------- |
| Random Forest | 0.7917 |
| Logistic Regression | 0.7586 |
| Neural Network | 0.7536 |
| K-Neighbors | 0.7500 |
| Naive Bayes | 0.7436 |
| XGBClassifier | 0.7347 |
| Decision Tree | 0.7020 |

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/ml_compare.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/ml_compare.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}


