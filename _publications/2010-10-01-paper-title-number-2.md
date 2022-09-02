---
title: "Mixed-precision Quantized Neural Networks with Progressively Decreasing Bitwidth."
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
date: 2021-03-10
venue: 'Pattern Recognition'
---

[Download paper here](https://www.sciencedirect.com/science/article/pii/S0031320320304507)

Recommended citation: Tianshu Chu, Qin Luo, Jie Yang, Xiaolin Huang**, Mixed-precision Quantized Neural Networks with Progressively Decreasing Bitwidth. Pattern Recognition (PR), 2021, 111: 107647. ([Download paper here](https://www.sciencedirect.com/science/article/pii/S0031320320304507)) 

Efficient model inference is an important and practical issue in the deployment of deep neural networks on resource constraint platforms. Network quantization addresses this problem effectively by leveraging low-bit representation and arithmetic that could be conducted on dedicated embedded systems. In the previous works, the parameter bitwidth is set homogeneously and there is a trade-off between superior performance and aggressive compression. Actually, the stacked network layers, which are generally regarded as hierarchical feature extractors, contribute diversely to the overall performance. For a well-trained neural network, the feature distributions of different categories are organized gradually as the network propagates forward. Hence the capability requirement on the subsequent feature extractors is reduced. It indicates that the neurons in posterior layers could be assigned with lower bitwidth for quantized neural networks. Based on this observation, a simple yet effective mixed-precision quantized neural network with progressively decreasing bitwidth is proposed to improve the trade-off between accuracy and compression. Extensive experiments on typical network architectures and benchmark datasets demonstrate that the proposed method could achieve better or comparable results while reducing the memory space for quantized parameters by more than 25% in comparison with the homogeneous counterparts. In addition, the results also demonstrate that the higher-precision bottom layers could boost the 1-bit network performance appreciably due to a better preservation of the original image information while the lower-precision posterior layers contribute to the regularization of k-bit networks.
