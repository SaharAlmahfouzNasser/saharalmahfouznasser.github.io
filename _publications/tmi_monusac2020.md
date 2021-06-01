---
title: "MoNuSAC2020: A Multi-organ Nuclei Segmentation and Classification Challenge"
collection: publications
permalink: /publication/tmi_monusac2021
excerpt: ' In this paper, we present the key findings of MoNuSAC challenge at [MICCAI 2020](https://monusac-2020.grand-challenge.org/)'
date: 2021-04-03
venue: 'Transaction of Medical Imaging, IEEE'
image: 'monusac1.png'
width: '800'
---
Generalized nucleus segmentation techniques can contribute greatly to reducing the time to develop and validate visual biomarkers for new digital pathology datasets. We summarize the results of MoNuSeg 2018 Challenge whose objective was to develop generalizable nuclei segmentation techniques in digital pathology. The challenge was an official satellite event of the
MICCAI 2018 conference in which 32 teams with more than 80 participants from geographically diverse institutes participated. Contestants were given a training set with 30 images from seven organs with annotations of 21,623 individual nuclei. Atest dataset with 14 images taken from seven organs, including two organs that did not appear in the training set was released
without annotations. Entries were evaluated based on average aggregated Jaccard index (AJI) on the test set to prioritize accurate instance segmentation as opposed to mere semantic segmentation. More than half the teams that completed the challenge outperformed a previous baseline. Among the trends observed that contributed to increased accuracy were the use of color normalization as well as heavy data augmentation.
Additionally, fully convolutional networks inspired by variants of U-Net, FCN, and Mask-RCNN were popularly used, typically based on ResNet or VGG base architectures. Watershed segmentation on predicted semantic segmentation maps was a popular post-processing strategy. Several of the top techniques compared favorably to an individual human annotator and can be used with confidence for nuclear morphometrics

### Citation
'Verma, R.,Kumar, N, Patil.A.,Kurian,N.C., et.al. and Sethi, A. (2021). &quot;MoNuSAC2020: A Multi-organ Nuclei Segmentation and Classification Challenge &quot; <i>Transaction of Medical Imaging</i>, IEEE 

