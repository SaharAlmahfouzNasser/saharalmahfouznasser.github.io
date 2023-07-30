---
title: "Improving Mitosis Detection via UNet-Based Adversarial Domain Homogenizer."
collection: publications
permalink: /publication/mitosis_2023
date: 2023-03-24
excerpt: This paper proposes a domain homogenizer for mitosis detection that attempts to alleviate domain differences in histology images via adversarial reconstruction of input images
venue: '16th International Joint Conference on Biomedical Engineering Systems and Technologies (BIOSTEC 2023)'
image: 'mitosis2023.png'
width: '800'
---
The effective counting of mitotic figures in cancer pathology specimen is a critical task for deciding tumor grade and prognosis. Automated mitosis detection through deep learning-based image analysis often fails on unseen patient data due to domain shifts in the form of changes in stain appearance, pixel noise, tissue quality, and magnification. This paper proposes a domain homogenizer for mitosis detection that attempts to alleviate domain differences in histology images via adversarial reconstruction of input images. The proposed homogenizer is based on a U-Net architecture and can effectively reduce domain differences commonly seen with histology imaging data. We demonstrate our domain homogenizer’s effectiveness by showing a reduction in domain differences between the preprocessed images. Using this homogenizer with a RetinaNet object detector, we were able to outperform the baselines of the 2021 MIDOG challenge in terms of average precision of the detected mitotic figures.

### Citation 

'Chandra, T.; Nasser, S.; Kurian, N. and Sethi, A. (2023). Improving Mitosis Detection via UNet-Based Adversarial Domain Homogenizer. In Proceedings of the 16th International Joint Conference on Biomedical Engineering Systems and Technologies - Volume 2: BIOIMAGING, ISBN 978-989-758-631-6, ISSN 2184-4305, pages 52-56. DOI: 10.5220/0011629700003414'

[Paper Link](https://www.scitepress.org/Papers/2023/116297/116297.pdf)
