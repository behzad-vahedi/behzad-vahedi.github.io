---
title: "A Comparison Of Classic Deep Learning Architectures For Sea Ice Classification From SAR"
collection: talks
type: "Talk"
permalink: /talks/AGU_22_DL_comparison
venue: "2021 AGU Fall Meeting"
date: 2021-12-15
location: "New Orleans, Louisiana"
---

During the last decade, advances in the state-of-the-art deep learning models, in particular convolutional neural networks, have facilitated significant improvements in image recognition tasks. In fact, on the benchmark ImageNet dataset, the state of the art is now recognized as performing better than human. As a result, many adjacent tasks, including image recognition in remote sensing, have adopted these state-of-the-art models with little investigation into their transferability. For instance, the common image datasets—from which pre-trained model weights are derived or modern architectures are evaluated on—contain R-G-B images of everyday items such as animals, symbols, and vehicles. Needless to say, this is very different from the contents of a standard optical or radar image acquired by a satellite.

In this work we explore this idea of transferability in the context of the classification of sea ice type from Sentinel-1 SAR imagery. We compare the performance of a basic CNN with 4 significant models from the field of computer vision—`ResNet, VGG, Xception Net and Inception Net'—in the task of classifying sea ice in a region of the Chukchi Sea, a sea of the Arctic Ocean. We extend these experiments further to compare models that have been pre-trained on the ImageNet dataset with models where the parameters are randomly initialized, to demonstrate whether pre-trained models are beneficial for this application. The performance of models is compared using overall accuracy and F-1 score. Finally, we hypothesize why some models perform better on our dataset than the others, and we conclude by explaining how the results inform our model choice for future sea ice classification projects.


