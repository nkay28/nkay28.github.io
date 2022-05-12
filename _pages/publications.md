---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---


## Proposal automation product: An Advanced Enterprise Search Engine with Semantic Search assistant

##  Applicant recommender system via NLP based resume feature extraction combined with ATS fields query. 

## NIH’s international Heart Stroke AI Research with Federated learning and cloud native pipeline. 

## Well-Being estimation model for suicide prevention.

## AI Research Assistant for DARPA (Defense Advanced Research Projects Agency)

## AI-Assisted Decision making: Developed AlphaZero based Connect Four AI

## Smart Mobility: Automated Shuttles for Allegheny County

## Fast Approximate Graph Matching Algorithms for Decision Analysis 

## DARPA and Air Force Research Lab (AFRL) Hackathon

## General Services Administration (GSA) EULA Challenge



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
