---
title: "Neuro-Modulated Hebbian Learning for Fully Test-Time Adaptation"
collection: publications
permalink: /publication/testtime_cvpr_2023
excerpt: 'Keywords: Test-time Adaptation, Hebbian Learning. '
venue: 'IEEE Conference on Computer Vision and Pattern Recognition (CVPR)'
date: 2023-06-01
paperurl: ''
citation: 'Tang Y, Zhang C, Xu H, et al. Neuro-Modulated Hebbian Learning for Fully Test-Time Adaptation[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023: 3728-3738.'
---
Fully test-time adaptation aims to adapt the network model based on sequential analysis of input samples during the inference stage to address the cross-domain performance degradation problem of deep neural networks. We take inspiration from the biological plausibility learning where the neuron responses are tuned based on a local synapse-change procedure and activated by competitive lateral inhibition rules. Based on these feed-forward learning rules, we design a soft Hebbian learning process which provides an unsupervised and effective mechanism for online adaptation. We observe that the performance of this feed-forward Hebbian learning for fully test-time adaptation can be significantly improved by incorporating a feedback neuro-modulation layer. It is able to fine-tune the neuron responses based on the external feedback generated by the error back-propagation from the top inference layers. This leads to our proposed neuro-modulated Hebbian learning (NHL) method for fully test-time adaptation. With the unsupervised feed-forward soft Hebbian learning being combined with a learned neuro-modulator to capture feedback from external responses, the source model can be effectively adapted during the testing process. Experimental results on benchmark datasets demonstrate that our proposed method can significantly improve the adaptation performance of network models and outperforms existing state-of-the-art methods.

[Download Paper Here](http://PhoebeChen123.github.io/files/testtime_cvpr_2023.pdf)
