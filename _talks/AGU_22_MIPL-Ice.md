---
title: "Sea Ice Type Classification using Deep Convolutional Networks and Partial Label Learning (Invited)"
collection: talks
type: "Talk"
permalink: /talks/AGU_22_MIPL-Ice
venue: "2022 AGU Fall Meeting"
date: 2022-12-12
location: Chicago, Illinois"
---

Ice charts that map Arctic sea ice type serve tactical and strategic operational purposes in marine navigation while providing a reference for scientific studies in the arctic region. Traditionally, ice charts are generated by human experts who interpret daily/weekly collected remote sensing imagery (e.g., Sentinel-1 Synthetic Aperture Radar (SAR) imagery) and annotate the imagery by identifying areas/polygons with a relatively homogeneous distribution of sea ice types. For each polygon, the dominant types of oldest ice as well as the corresponding partial ice concentrations, are then identified via annotation. While such expert-generated maps are useful, manual generation of ice charts is laborious, unscalable, and error-prone, in turn limiting the coverage, recency, and accuracy of ice charts. In this study, we propose a novel multi-instance proportion label sea ice classification model to automate the generation of ice charts. In the past, many supervised learning methods have been deployed that leverage the manually generated ice charts as labeled data and train models for automated sea ice classification. However, since most developed models are defined to classify each pixel in the imagery by learning from “pixel-level” labels in the training dataset, all these methods resort to generating pixel-level labels for model training by approximating these labels from the “polygon-level” labels available in ice charts. In turn, such approximations reduce the accuracy of the trained sea ice classification models. To address the ill-posed problem of training “pixel-level” models from “polygon-level” labels, instead we propose a model, dubbed MIPL-Ice, that expects polygon-level labels (such as ice charts directly) as input for training, and learns to generate pixel-level and polygon-level class predictions as output. With extensive experimentation using the selection of ice charts, we show that our proposed model outperforms existing sea ice classification methods in terms of accuracy, while benefiting from more resource-efficient training and reduced training time.

Authors: Samira Alkaee Taleghan, Behzad Vahedi, Morteza Karimzadeh, Andrew Barrett, Walt Meier, Siri Jodha S Khalsa, Farnoush Banaei-Kashani


Read more [here](https://agu.confex.com/agu/fm22/meetingapp.cgi/Paper/1190517)