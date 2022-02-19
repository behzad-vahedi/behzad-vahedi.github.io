---
title: "Sea Ice Type Classification from Sentinel-1 SAR Imagery Using Deep Neural Networks"
collection: talks
type: "Talk"
permalink: /talks/AGU_22_sea_ice_classificaion
venue: "2021 AGU Fall Meeting"
date: 2021-12-15
location: "New Orleans, Louisiana"
---

Sea ice plays an important role in climate change and marine navigation. Mapping of sea ice types, however, still remains largely a manual effort. Automated classification of ice types in Synthetic Aperture Radar (SAR) imagery is a challenging task due to many different factors including, but not limited to: i) low ice type separability in SAR backscatter, and ii) spatial, temporal, and thematic inconsistencies in the quality of the Stage of Development (SoD) sea ice charts, which are often used as labels for training. When generating SoD charts, ice experts prioritize operational needs, mostly marine navigation, which leads to (generally) higher precision in delineating young and new ice polygon boundaries compared to multi-year, or first-year ice. Furthermore, the sea ice charts include polygons containing mixed ice types, reflecting the partial concentrations of each ice type in polygons, posing a challenge in using the charts as training data, especially since the reported partial concentrations of ice are approximate, and to some extent, subjective.

We present a deep neural network model for classifying sea ice types in the Chukchi Sea using Sentinel-1 SAR images in Extra-Wide swath mode. To alleviate the issues of data inconsistency and partially correct labels, we use class- and label- dependent spatial preprocessing and filtering to incorporate the partial concentrations (of the ice classes) in deriving our models. The parameters for spatial processing as well as partial concentration weights are optimized during the neural network training. To further improve class separability, we include local incident angle in addition to HH and HV backscattered values as input to the model. We evaluate our model output against values retrieved from the ice charts using metrics such as accuracy and F-1 score, and analyze the performance of the model across different ice types.
