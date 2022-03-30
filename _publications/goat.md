---
title: "Graph Ordering Attention Networks"
collection: publications
permalink: /publication/goat
excerpt: " We introduce the Graph Ordering Attention
(GOAT) layer, a novel GNN component that learns local
node orderings via an attention mechanism and processes the ordered representations using a recurrent neural network aggregator. [Read More](https://michailchatzianastasis.github.io/publication/goat) "
date: '2022-02-18'
venue: 'Preprint'
#video : 'https://www.youtube.com/watch?v=-rZ4tpNvL6s'
#code: 'https://github.com/MichailChatzianastasis/Graph-based_NAS_with_Operation_Embeddings'
paperurl: 'https://michailchatzianastasis.github.io/files/goat.pdf'
citation: '<strong>Michail Chatzianastasis</strong>, Johannes Lutzeyer, George Dasoulas, Michalis Vazirgiannis'
abstract: "Graph Neural Networks (GNNs) have been successfully used in many problems involving graphstructured data, achieving state-of-the-art performance. GNNs typically employ a message-passing scheme, in which every node aggregates information from its neighbors using a permutationinvariant aggregation function. Standard wellexamined choices like mean or sum aggregation functions have limited capabilities, as they are not able to capture interactions among neighbors. In this work, we formalize these interactions using an
information-theoretic framework that notably includes synergistic information. Driven by this definition, we introduce the Graph Ordering Attention
(GOAT) layer, a novel GNN component that captures higher-level dependencies between nodes in a neighborhood. This is achieved by learning local
node orderings via an attention mechanism and processing the ordered representations using a recurrent neural network aggregator. This design allows
us to make use of a permutation-sensitive aggregator while maintaining the permutation-equivariance of the proposed GOAT layer. The GOAT model demonstrates its increased performance in modeling graph metrics that capture complex information, such as the betweenness centrality and the effective size of a node. In practical use-cases, its superior modeling capability is confirmed through its success in several real-world node classification benchmarks.
"
figure_1: "goat_venn.jpg"
figure_2: "goat_model.jpg"
---