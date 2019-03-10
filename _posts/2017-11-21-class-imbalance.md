---
title: "Class imbalance problem in convolutional neural networks"
description: "In this study, we systematically investigate the impact of class imbalance on classification performance of convolutional neural networks (CNNs) and compare perform an extensive comparison of several methods to address the issue.
Based on results from our experiments we conclude that
(i)&nbsp;the effect of class imbalance on classification performance is detrimental;
(ii)&nbsp;the method of addressing class imbalance that emerged as dominant in almost all analyzed scenarios was oversampling;
(iii)&nbsp;thresholding should be applied to compensate for prior class probabilities when overall number of properly classified cases is of interest."
---

<style>
li {
	text-align: justify
}
</style>


In this study, we systematically investigate the impact of class imbalance on classification performance of convolutional neural networks and compare frequently used methods to address the issue.
Class imbalance refers to a significantly different number of examples among classes in a training set.
It is a common problem that has been comprehensively studied in classical machine learning, yet very limited systematic research is available in the context of deep learning.

### Experiments

We define and parameterize two representative types of imbalance, i.e. <i>step</i> and <i>linear</i>.
Using three benchmark datasets of increasing complexity, MNIST, CIFAR-10 and ImageNet, we investigate the effects of imbalance on classification and perform an extensive comparison of several methods to address the issue: oversampling, undersampling, two-phase training, and thresholding that compensates for prior class probabilities.
Our main evaluation metric is area under the receiver operating characteristic curve (ROC AUC) adjusted to multi-class tasks since overall accuracy metric is associated with notable difficulties in the context of imbalanced data.

<p>
	<center>
		<table style="text-align: center">
			<tr>
				<td>
					<img src="/images/imbalance/mnist.png" alt="MNIST" style="max-height: 200px; width: auto;" />
				</td>
				<td>
					<img src="/images/imbalance/cifar.png" alt="CIFAR-10" style="max-height: 200px; width: auto;" />
				</td>
				<td>
					<img src="/images/imbalance/imagenet.jpg" alt="ImageNet" style="max-height: 200px; width: auto;" />
				</td>
			</tr>
			<tr>
				<td>
					MNIST
				</td>
				<td>
					CIFAR-10
				</td>
				<td>
					ImageNet
				</td>
			</tr>
		</table>
		Figure 1: Examples from datasets used in experiments.
	</center>
</p>

<p>
	<center>
		<table style="text-align: center; width: 80%; border-collapse: collapse;">
			<thead style="border-bottom: 1px solid black; border-top: 2px solid black;">
				<th width="20%">
					Dataset
				</th>
				<th width="20%">
					Network
				</th>
				<th width="20%">
					Code
				</th>
				<th width="20%">
					Paper
				</th>
			</thead>
			<tr>
				<td>
					MNIST
				</td>
				<td>
					LeNet-5
				</td>
				<td>
					<a href="https://github.com/BVLC/caffe/tree/master/examples/mnist">BVLC</a>
				</td>
				<td>
					<a href="http://www.iro.umontreal.ca/~lisa/bib/pub_subject/finance/pointeurs/lecun-98.pdf">umontreal.ca</a>
				</td>
			</tr>
			<tr>
				<td>
					CIFAR-10
				</td>
				<td>
					All-CNN
				</td>
				<td>
					<a href="https://github.com/mateuszbuda/ALL-CNN">mateuszbuda</a>
				</td>
				<td>
					<a href="https://arxiv.org/abs/1412.6806">arXiv</a>
				</td>
			</tr>
			<tr style="border-bottom: 2px solid black;">
				<td>
					ImageNet
				</td>
				<td>
					ResNet-10
				</td>
				<td>
					<a href="https://github.com/cvjena/cnn-models">cvjena</a>
				</td>
				<td>
					<a href="https://arxiv.org/abs/1612.01452">arXiv</a>
				</td>
			</tr>
		</table>
		Table 1: Networks used in experiments.
	</center>
</p>

### Conclusions

Based on results from our experiments we conclude that
- the effect of class imbalance on classification performance is detrimental and increases with the extent of imbalance and the scale of a task;
- the method of addressing class imbalance that emerged as dominant in almost all analyzed scenarios was oversampling;
- oversampling should be applied to the level that eliminates the imbalance, whereas undersampling can perform better when the imbalance is only removed to some extent;
- thresholding should be applied to compensate for prior class probabilities when overall number of properly classified cases is of interest;
- as opposed to some classical machine learning models, oversampling does not necessarily cause overfitting of convolutional neural networks.

### Links

- Full paper: <a href="https://arxiv.org/abs/1710.05381" target="_blank">arXiv:1710.05381</a>
- Extended report: <a href="http://www.diva-portal.org/smash/get/diva2:1165840/FULLTEXT01.pdf" target="_blank">diva2:1165840</a>

