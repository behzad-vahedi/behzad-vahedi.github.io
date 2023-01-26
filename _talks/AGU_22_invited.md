---
title: "Sea Ice Type Classification using Deep Convolutional Networks and Partial Label Learning (Invited)"
collection: talks
type: "Talk"
permalink: /talks/AGU_22_invited
venue: "2022 AGU Fall Meeting"
date: 2022-12-12
location: Chicago, Illinois"
---

Deep Convolutional Neural Networks (DCNNs) have been used to automate classification of sea ice properties, such as type, extent, and concentration, from remotely-sensed images using expert-generated operational sea ice charts as labels for training samples. These ice charts comprise a set of polygons, each containing up to three different ice types with corresponding partial concentration levels. This approach, which essentially assigns multiple labels (sea ice types) to each polygon, poses a challenge for conventional deep learning-based sea ice type classification algorithms, which are trained using single-label training samples.
Additionally, training datasets for sea ice classification, and environmental remote sensing more generally, often suffer from class imbalance. This skews the performance of deep learning algorithms towards producing higher accuracy on the majority classes, even if the minority classes are of more importance, as is the case in sea ice classification, with the minority sea ice classes against the majority open water class.


To address these challenges, we present a novel approach to sea ice classification by formalizing this problem as a partial label learning task with explicit confidence scores, while leveraging focal loss to address the aforementioned class imbalance problem. Based on this approach, we treat the multiple polygon-level labels as candidate partial labels at the patch level, assign explicit confidence scores obtained from partial sea ice concentrations to each candidate label, and then integrate them within a focal loss function to train a DCNN. Our experiments show that our approach leads to enhanced performance for sea ice classification using Sentinel-1 dual-polarized Synthetic Aperture Radar (SAR) imagery.

Authors: Behzad Vahedi, Benjamin Lucas, Farnoush Banaei-Kashani, Andrew Barrett, Walt Meier, 
Morteza Karimzadeh

Read more [here](https://agu.confex.com/agu/fm22/meetingapp.cgi/Paper/1190517)