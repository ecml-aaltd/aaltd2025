---
layout: default
title: Rethinking Time Series Clustering - Lessons from Complex Data Streams
nav_order: 3.5
---

## Abstract
Clustering of time series is widely used to uncover regime changes and structural patterns across domains such as health, finance, and industry. Its strength lies in detecting patterns without predefined labels, but this also creates a fundamental challenge: without ground truth, how can we know whether discovered clusters reflect genuine structures, algorithmic artefacts, or weaknesses in the validation process? Traditional clustering validity indices were developed mainly for Euclidean spaces and provide little insight when applied to correlation structures in time series.

In this keynote, I will trace a journey from analysing patterns in crowdsourced, real-world time series to developing a principled framework for clustering validation. Using continuous glucose and insulin delivery data from people with Type 1 Diabetes as a motivating case study, I will show how sophisticated methods—particularly correlation-based clustering and probabilistic models—can generate results that appear convincing yet contradictory. Traditional indices provide limited guidance, and domain expertise is subjective and often shaped by prior knowledge, creating a validation loop that constrains genuine discovery. This recognition motivated the development of a mathematical validation framework based on canonical correlation patterns, enabling systematic evaluation of clustering methods for time series. The framework offers evidence-based guidance on distance functions, internal indices, and protocol design, laying the methodological foundations for reliable unsupervised discovery.

The talk will share lessons learned from building clustering pipelines for irregular, high-frequency time series and complex data streams, and highlight how rigorous validation can transform clustering from speculative pattern-finding into a scientifically grounded tool, with implications well beyond the clinical case study.

## Dr Zahraa Abdallah, Senior Lecturer, School of Engineering Mathematics and Technology, University of Bristol, UK

![Zahraa Abdallah](<Profile_Photo_Zahraa.jpg>)



[website](https://research-information.bris.ac.uk/en/persons/zahraa-s-abdallah)
