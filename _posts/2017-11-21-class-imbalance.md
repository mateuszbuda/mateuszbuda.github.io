---
title: "Class Imbalance Problem in Convolutional Neural Networks"
description: "In this study, we systematically investigate the impact of class imbalance on classification performance of convolutional neural networks (CNNs) and compare perform an extensive comparison of several methods to address the issue.
Based on results from our experiments we conclude that
(i) the effect of class imbalance on classification performance is detrimental;
(ii) the method of addressing class imbalance that emerged as dominant in almost all analyzed scenarios was oversampling;
(iii) thresholding should be applied to compensate for prior class probabilities when overall number of properly classified cases is of interest."
---

## Class Imbalance Problem in Convolutional Neural Networks

In this study, we systematically investigate the impact of class imbalance on classification performance of convolutional neural networks and compare frequently used methods to address the issue.
Class imbalance refers to significantly different number of examples among classes in a training set.
It is a common problem that has been comprehensively studied in classical machine learning, yet very limited systematic research is available in the context of deep learning.

We define and parameterize two representative types of imbalance, i.e. <i>step</i> and <i>linear</i>.
Using three benchmark datasets of increasing complexity, MNIST, CIFAR-10 and ImageNet, we investigate the effects of imbalance on classification and perform an extensive comparison of several methods to address the issue: oversampling, undersampling, two-phase training, and thresholding that compensates for prior class probabilities.
Our main evaluation metric is area under the receiver operating characteristic curve (ROC AUC) adjusted to multi-class tasks since overall accuracy metric is associated with notable difficulties in the context of imbalanced data.

Based on results from our experiments we conclude that
- the effect of class imbalance on classification performance is detrimental and increases with the extent of imbalance and the scale of a task;
- the method of addressing class imbalance that emerged as dominant in almost all analyzed scenarios was oversampling;
- oversampling should be applied to the level that totally eliminates the imbalance, whereas undersampling can perform better when the imbalance is only removed to some extent;
- thresholding should be applied to compensate for prior class probabilities when overall number of properly classified cases is of interest;
- as opposed to some classical machine learning models, oversampling does not necessarily cause overfitting of convolutional neural networks.

[arXiv:1710.05381](https://arxiv.org/abs/1710.05381)
