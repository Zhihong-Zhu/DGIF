# A Dynamic Graph Interactive Framework with Label-Semantic Injection for Spoken Language Understanding

<img src="img/pytorch.png" width="10%"> [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the PyTorch implementation and the data of the paper: 
> **A Dynamic Graph Interactive Framework with Label-Semantic Injection for Spoken Language Understanding** 
>
> Zhihong Zhu, Weiyuan Xu, Xuxin Cheng, Tengtao Song, [Yuexian Zou](https://scholar.google.com/citations?user=sfyr7zMAAAAJ&hl=zh-CN&oi=ao)
> 
> ***ICASSP2023 [Under review]***.

## Update

- **[24 Oct 2022]** The code will be released soon since it is currently under review.

## Abstract

Multi-intent detection and slot filling joint models are gaining increasing traction since they are closer to complicated real-world scenarios. However, existing approaches (1) focus on identifying implicit correlations between utterances and one-hot encoded labels in both tasks while ignoring explicit label characteristics; (2) directly incorporate multi-intent information for each token, which could lead to incorrect slot prediction due to the introduction of irrelevant intent. In this paper, we propose a framework termed DGIF, which first leverages the semantic information of labels to give the model additional signals and enriched priors. Then, a multi-grain interactive graph is constructed to model correlations between intents and slots. Specifically, we propose a novel approach to construct the interactive graph based on the injection of label semantics, which can automatically update the graph to better alleviate error propagation. Experimental results show that our framework significantly outperforms existing approaches, obtaining a relative improvement of 13.7% over the previous best model on the MixATIS dataset in overall accuracy.

# Framework

<img align="center" src="img/framework.jpg" width="100%">

## Contact us

- Just feel free to open issues or send us email([Zhihong](mailto:zhihongzhu@stu.pku.edu.cn)) if you have any problems or find some mistakes in this work.
