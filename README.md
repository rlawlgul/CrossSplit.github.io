# CrossSplit.github.io

CrossSplit: Mitigating Label Noise Memorization through Data Splitting (ICML 2023)

The code will be coming soon.

# Abstract
We approach the problem of improving robustness of deep learning algorithms in the presence of label noise. Building upon existing label correction and co-teaching methods, we propose a novel training procedure to mitigate the memorization of noisy labels, called CrossSplit, which uses a pair of neural networks trained on two disjoint parts of the labeled dataset. Cross\-Split combines two main ingredients: $(i)$ Cross-split label correction. The idea is that, since the model trained on one part of the data cannot memorize example-label pairs from the other part, the training labels presented to each network can be smoothly adjusted by using the predictions of its peer network; $(ii)$ Cross-split semi-supervised training. A network trained on one part of the data also uses the unlabeled inputs of the other part. Extensive experiments on CIFAR-10, CIFAR-100, Tiny-ImageNet and mini-WebVision datasets demonstrate that our method can outperform the current state-of-the-art in a wide range of noise ratios.

# Method
![fig_arch7](https://user-images.githubusercontent.com/100881552/235355178-d426d9e1-30e8-40a5-a281-502edb31c254.png)

# Results


