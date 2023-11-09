---
title: "Neural Architecture Search with Multimodal Fusion Methods for Diagnosing Dementia"
collection: publications
permalink: /publication/nas_multimodal_dementia
excerpt: "We propose a multimodal deep learning approach to combine speech and text modalities for recognizing Alzheimer’s dementia (AD) using Neural Architecture Search."
date: '2023-02-16'
venue: ' <a href="https://2023.ieeeicassp.org/">ICASSP 2023</a>'
paperurl: 'https://arxiv.org/pdf/2302.05894.pdf'
citation: '<strong>Michail Chatzianastasis</strong>, Loukas Ilias, Dimitris Askounis, Michalis Vazirgiannis'
abstract: "Alzheimer’s dementia (AD) affects memory, thinking, and language, deteriorating person’s life. An early diagnosis is very important as it enables the person to receive medical help and ensure quality of life. 
Therefore, leveraging spontaneous speech in conjunction with machine learning methods for recognizing AD patients has emerged into a hot topic. Most of the previous works employ Convolutional Neural Networks (CNNs), to process the input signal. However,
finding a CNN architecture is a time-consuming process and requires domain expertise. Moreover, the researchers introduce early and late fusion approaches for fusing different modalities or concatenate the representations of the different modalities during training, thus the inter-modal interactions are not captured. To tackle these limitations, first we exploit a Neural Architecture Search (NAS) method to automatically find a high performing CNN architecture. Next, we
exploit several fusion methods, including Multimodal Factorized Bilinear Pooling and Tucker Decomposition, to combine both speech and text modalities. To the best of our knowledge, there is no prior work exploiting a NAS approach and these fusion methods in the task of dementia detection from spontaneous speech. We perform extensive experiments on the ADReSS Challenge dataset and show the effectiveness of our approach over state-of-the-art methods.
"
---
