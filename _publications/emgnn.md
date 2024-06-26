---
title: "Explainable Multilayer Graph Neural Network for Cancer Gene Prediction"
collection: publications
permalink: /publication/emgnn
excerpt: "We introduce an Explainable Multilayer Graph Neural Network (EMGNN) approach to identify cancer genes by leveraging multiple gene-gene interaction networks
and pan-cancer multi-omics data."
date: '2023-10-19'
venue: '<a href="https://academic.oup.com/bioinformatics">Bioinformatics, Oxford Academic</a>'
paperurl: 'https://academic.oup.com/bioinformatics/article/39/11/btad643/7325352'
code: 'https://github.com/zhanglab-aim/EMGNN'
citation: '<strong>Michail Chatzianastasis</strong>, Michalis Vazirgiannis, Zijun Zang'
abstract: " <strong>Motivation</strong>: The identification of cancer genes is a critical yet challenging problem in cancer genomics research. Existing
computational methods, including deep graph neural networks, fail to exploit the multilayered gene-gene interactions or
provide limited explanations for their predictions. These methods are restricted to a single biological network, which cannot
capture the full complexity of tumorigenesis. Models trained on different biological networks often yield different and even
opposite cancer gene predictions, hindering their trustworthy adaptation. Here, we introduce an Explainable Multilayer
Graph Neural Network (EMGNN) approach to identify cancer genes by leveraging multiple gene-gene interaction networks
and pan-cancer multi-omics data. Unlike conventional graph learning on a single biological network, EMGNN uses a
multilayered graph neural network to learn from multiple biological networks for accurate cancer gene prediction.<br />
<strong>Results</strong>: Our method consistently outperforms all existing methods, with an average 7.15% improvement in area under the
precision-recall curve (AUPR) over the current state-of-the-art method. Importantly, EMGNN integrated multiple graphs
to prioritize newly predicted cancer genes with conflicting predictions from single biological networks. For each prediction,
EMGNN provided valuable biological insights via both model-level feature importance explanations and molecular-level
gene set enrichment analysis. Overall, EMGNN offers a powerful new paradigm of graph learning through modeling the
multilayered topological gene relationships and provides a valuable tool for cancer genomics research. <br />
<strong>Availability</strong>: Our code is publicly available at https://github.com/zhanglab-aim/EMGNN.
"
---
