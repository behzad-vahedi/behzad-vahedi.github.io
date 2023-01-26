---
title: "Semantic Segmentation of Sea Ice Using Multi-scale Spatial Context"
collection: talks
type: "Talk"
permalink: /talks/AGU_22_multi_scale_segmentation
venue: "2022 AGU Fall Meeting"
date: 2022-12-15
location: Chicago, Illinois"
---

Semantic segmentation is known to generally benefit from combining local features with global scale context and semantic information. This is especially the case for remote sensing applications of image segmentation, where spatial contextual information can lead to better semantic identification. State-of-the-art semantic segmentation algorithms often incorporate local and global features at multiple scales, albeit with different approaches. However, the vast majority of these approaches have an inward-looking focus, meaning that they generate multi-scale features at different subscales, frequently using pooling, which can be interpreted as zooming in on the image’s prominent features. This might not be the optimal solution for semantic segmentation of sea ice type as the operational sea ice charts used to generate ground truth training samples often contain large polygons that can cover up to hundreds of square kilometers of area, or tens of thousands of pixels. Therefore, dividing the image into smaller regions may yield little to no additional information. Instead, we hypothesize that incorporating a larger spatial context could be beneficial in increasing the accuracy of semantic segmentation of sea ice type from Synthetic Aperture Radar (SAR) images.

To investigate how incorporating larger spatial context can affect model performance, we present a novel approach for semantic segmentation of sea ice by combining spatial features at multiple scales with an outward-looking focus. In other words, to perform segmentation for a specific image patch (crop), we combine the features extracted from the primary patch with features extracted from larger encircling patches. We use ResNet to extract the features of the different patches via multiple streams, one for each patch, and combine the features from multiple streams before performing the final segmentation. We evaluate our multi-scale approach against a model containing a single stream (for the primary patch) as a baseline using pixel-wise accuracy and Intersection over Union (IoU) metrics.

Authors: Behzad Vahedi, Rafael Pires de Lima, Benjamin Lucas, Morteza Karimzadeh

Read more [here](https://agu.confex.com/agu/fm22/meetingapp.cgi/Paper/1193367)