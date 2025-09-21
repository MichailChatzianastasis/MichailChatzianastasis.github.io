---
title: "Prot2Text-V2: Protein Function Prediction with Multimodal Contrastive Alignment"
collection: publications
permalink: /publication/prot2text
excerpt: "We propose Prot2Text, which predicts a protein function's in a free text style, moving beyond the conventional binary or categorical classifications. By combining Graph Neural Networks(GNNs) and Large Language Models(LLMs), in an encoder-decoder framework, our model effectively integrates diverse data types including proteins' sequences, structures, and textual annotations."
date: '2025-09-19'
venue: ' NeurIPS 2025 '
paperurl: 'https://arxiv.org/abs/2505.11194'
citation: 'Xiao Fei, <strong>Michail Chatzianastasis</strong>, Sarah Almeida Carneiro, Hadi Abdine, Lawrence P. Petalidis, Michalis Vazirgiannis'
abstract: "Predicting protein function from sequence is a central challenge in computational biology. While existing methods rely heavily on structured ontologies or similarity-based techniques, they often lack the flexibility to express structure-free functional descriptions and novel biological functions. In this work, we introduce Prot2Text-V2, a novel multimodal sequence-to-text model that generates free-form natural language descriptions of protein function directly from amino acid sequences. Our method combines a protein language model as a sequence encoder (ESM-3B) and a decoder-only language model (LLaMA-3.1-8B-Instruct) through a lightweight nonlinear modality projector. A key innovation is our Hybrid Sequence-level Contrastive Alignment Learning (H-SCALE), which improves cross-modal learning by matching mean- and std-pooled protein embeddings with text representations via contrastive loss. After the alignment phase, we apply instruction-based fine-tuning using LoRA on the decoder to teach the model how to generate accurate protein function descriptions conditioned on the protein sequence. We train Prot2Text-V2 on about 250K curated entries from SwissProt and evaluate it under low-homology conditions, where test sequences have low similarity with training samples. Prot2Text-V2 consistently outperforms traditional and LLM-based baselines across various metrics..
"
---
