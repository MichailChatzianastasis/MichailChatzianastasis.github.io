---
title: "Weisfeiler and Leman go Hyperbolic: Learning Distance Preserving Node Representations"
collection: publications
permalink: /publication/wlhn
excerpt: "In this paper, we define a distance function between nodes which is based on the hierarchy produced by the WL algorithm, and propose a model that learns representations which preserve those distances between nodes. Since the emerging hierarchy corresponds to a tree, to learn these representations, we capitalize on recent advances in the field of hyperbolic neural networks."
date: '2022-11-04'
venue: ' <a href="http://aistats.org/aistats2023/">AISTATS 2023</a>'
code: 'https://github.com/MichailChatzianastasis/WLHN'
paperurl: 'https://arxiv.org/pdf/2211.02501.pdf'
citation: 'Giannis Nikolentzos, Michail Chatzianastasis, Michalis Vazirgiannis'
abstract: "In recent years, graph neural networks (GNNs)
have emerged as a promising tool for solving
machine learning problems on graphs. Most
GNNs are members of the family of message
passing neural networks (MPNNs). There is a
close connection between these models and the
Weisfeiler-Leman (WL) test of isomorphism, an
algorithm that can successfully test isomorphism
for a broad class of graphs. Recently, much research has focused on measuring the expressive
power of GNNs. For instance, it has been shown
that standard MPNNs are at most as powerful as
WL in terms of distinguishing non-isomorphic
graphs. However, these studies have largely ignored the distances between the representations of
nodes/graphs which are of paramount importance
for learning tasks. In this paper, we define a distance function between nodes which is based on
the hierarchy produced by the WL algorithm, and
propose a model that learns representations which
preserve those distances between nodes. Since the
emerging hierarchy corresponds to a tree, to learn
these representations, we capitalize on recent advances in the field of hyperbolic neural networks.
We empirically evaluate the proposed model on
standard node and graph classification datasets
where it achieves competitive performance with
state-of-the-art models.
"
---
