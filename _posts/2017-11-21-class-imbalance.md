---
title: "Class Imbalance Problem in Convolutional Neural Networks"
description: "In this study, we systematically investigate the impact of class imbalance on classification performance of convolutional neural networks (CNNs) and compare perform an extensive comparison of several methods to address the issue.
Based on results from our experiments we conclude that
(i) the effect of class imbalance on classification performance is detrimental;
(ii) the method of addressing class imbalance that emerged as dominant in almost all analyzed scenarios was oversampling;
(iii) thresholding should be applied to compensate for prior class probabilities when overall number of properly classified cases is of interest."
---

<style>
p, li {
	text-align: justify
}
</style>


In this study, we systematically investigate the impact of class imbalance on classification performance of convolutional neural networks and compare frequently used methods to address the issue.
Class imbalance refers to significantly different number of examples among classes in a training set.
It is a common problem that has been comprehensively studied in classical machine learning, yet very limited systematic research is available in the context of deep learning.

### Experiments

We define and parameterize two representative types of imbalance, i.e. <i>step</i> and <i>linear</i>.
Using three benchmark datasets of increasing complexity, MNIST, CIFAR-10 and ImageNet, we investigate the effects of imbalance on classification and perform an extensive comparison of several methods to address the issue: oversampling, undersampling, two-phase training, and thresholding that compensates for prior class probabilities.
Our main evaluation metric is area under the receiver operating characteristic curve (ROC AUC) adjusted to multi-class tasks since overall accuracy metric is associated with notable difficulties in the context of imbalanced data.

| ![MNIST](/assets/mnist.png){:height="200px" width="200px"} | ![CIFAR-10](/assets/cifar.png){:height="200px" width="260px"} | ![ImageNet](/assets/imagenet.jpg){:height="200px" width="267px"} |
|:-------------:|:-------------:|:-----:|
| MNIST | CIFAR-10 | ImageNet |

Figure 1: Examples from datasets used in experiments.

### Conclusions

Based on results from our experiments we conclude that
- the effect of class imbalance on classification performance is detrimental and increases with the extent of imbalance and the scale of a task;
- the method of addressing class imbalance that emerged as dominant in almost all analyzed scenarios was oversampling;
- oversampling should be applied to the level that totally eliminates the imbalance, whereas undersampling can perform better when the imbalance is only removed to some extent;
- thresholding should be applied to compensate for prior class probabilities when overall number of properly classified cases is of interest;
- as opposed to some classical machine learning models, oversampling does not necessarily cause overfitting of convolutional neural networks.

### Links

Full paper: [arXiv:1710.05381](https://arxiv.org/abs/1710.05381)<br>
LeNet-5: [github.com/BVLC](https://github.com/BVLC/caffe/tree/master/examples/mnist)<br>
All-CNN: [github.com/mateuszbuda](https://github.com/mateuszbuda/ALL-CNN)<br>
ResNet-10: [github.com/cvjena](https://github.com/cvjena/cnn-models)<br>
