---
layout: page
title: Inference Portal --- Suzuki Reactions Yield Prediction 
description: Real-time Inference Portal hosting trained DNNs for on-the-fly Suzuki Coupling Reaction Feature Extraction, Yield Prediction and Ranking 
img: assets/img/airflow.png
importance: 6 
category: aganitha
---

Several projects, especially common in academic research, end upon successful training of models and that’s it. These models may be state-of-the-art but end up being non-reproducible and hence, unusable by others. This project gave me an essence of need of reproducibility of deep learning models along with making them useful for the customers who may or may not have the background or expertise in the same.

I designed and implemented a web-based portal for real-time ranking of query reactions. In case, the reactions were not already present in the database, the entire data preprocessing and featurization pipelines were run and tracked (using AirFlow) and the results were notified to the customers via email. The inference models were hosted on an in-house server of the client (using Flask).