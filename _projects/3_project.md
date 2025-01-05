---
layout: page
title: Bayesian Retrievals using Machine Learning for Ariel Mission
description: Developing Novel Neural Networks to Replicate Nestled Sampling for Bayesian Exoplanet Atmospheric Retrievals 
img: assets/img/ariel.jpg
importance: 3
category: work
---

Transmission spectra—the analysis of an exoplanet's imprint on its host star's stellar flux—serve as the primary method for gaining insights into exoplanetary atmospheres. However, extracting meaningful information from these spectra is a challenging task. The process begins with constructing a complex forward radiative transfer model that accounts for the atmospheric structure, composition, and planetary parameters. Once the model is established, it is used to identify the best parameter distributions that match experimental observations. This approach, which combines the forward model with observational data to infer atmospheric parameters, is known as the retrieval process.

Classical retrieval methods require numerous forward model evaluations, resulting in significant computational complexity and slowing down research progress. Addressing this bottleneck is essential to accelerate advancements in the field. To tackle this challenge, my research group and I developed several machine learning pipelines. These pipelines efficiently process data, parameterize label distributions, and train models to replicate the classical retrieval methods commonly used in exoplanetary studies.

Our work has been recognized with several awards: 1st place in the Ariel Data Challenge 2022 (regular track), 2nd place in the Ariel Data Challenge 2022 (light track), and 1st place in the Ariel Data Challenge 2023. Additionally, the results of these efforts were published in the NeurIPS proceedings {% cite ariel2 %} and the ECML proceedings {% cite ariel1 %}.
