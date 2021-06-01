---
title: "Fast, Self Supervised, Fully Convolutional Color Normalization Of H&E Stained Images"
collection: publications
permalink: /publication/isbi20211
date: 2021-04-12
excerpt: This paper introduces novel self-supervision based color-normalisation schemes for H&E images.
venue: '2021 IEEE 18th International Symposium on Biomedical Imaging (ISBI)'
image: 'isbii2.PNG'
width: '800'
---


Normalizing unwanted color variations due to differences in staining processes and scanner responses has been shown to aid machine learning in computational pathology. Of the several popular techniques for color normalization, structure preserving color normalization (SPCN) is well-motivated, convincingly tested, and published with its code base. However, SPCN makes occasional errors in color basis estimation leading to artifacts such as swapping the color basis vectors between stains or giving a colored tinge to the background with no tissue. We made several algorithmic improvements to remove these artifacts. Additionally, the original SPCN code is not readily usable on gigapixel whole slide images (WSIs) due to long run times, use of proprietary software platform and libraries, and its inability to automatically handle WSIs. We completely rewrote the software such that it can automatically handle images of any size in popular WSI formats. Our software utilizes GPU-acceleration and open-source libraries that are becoming ubiquitous with the advent of deep learning. We also made several other small improvements and achieved a multifold overall speedup on gigapixel images, processing $10^9$ pixels in 3 minutes. Our algorithm and software is usable right out-of-the-box by the computational pathology community.

### Citation
Patil, Abhijeet, Mohd Talha, Aniket Bhatia, Nikhil Cherian Kurian, Sammed Mangale, Sunil Patel, and Amit Sethi. "Fast, Self Supervised, Fully Convolutional Color Normalization Of H&E Stained Images." In 2021 IEEE 18th International Symposium on Biomedical Imaging (ISBI), pp. 1563-1567. IEEE, 2021.

[Paper Link](https://ieeexplore.ieee.org/abstract/document/9434121)
