# NLEDN
Image rain mitigation model

# Abstract
Single image rain streaks removal has recently witnessed substantial progress due to the development of deep convolutional neural networks. However, existing deep learning based methods either focus on the entrance and exit of the network by decomposing the input image into high and low frequency information and employing residual learning to reduce the mapping range, or focus on the introduction of cascaded learning scheme to decompose the task of rain streaks removal into multi-stages. These methods treat the convolutional neural network as an encapsulated end-to-end mapping module without deepening into the rationality and superiority of neural network design. In this paper, we delve into an effective endto-end neural network structure for stronger feature expression and spatial correlation learning. Specifically, we propose a non-locally  enhanced encoder-decoder network framework, which consists of a pooling indices embedded encoder-decoder network to efficiently learn increasingly abstract feature representation for more accurate rain streaks modeling while perfectly preserving the image detail. The proposed encoder-decoder framework is composed of a series of non-locally enhanced dense blocks that are designed to not only fully exploit hierarchical features from all the convolutional layers but also well capture the long-distance dependencies and structural information. Extensive experiments on synthetic and real datasets demonstrate that the proposed method can effectively remove rainstreaks on rainy image of various densities while well preserving the image details, which achieves significant improvements over the recent state-of-the-art methods.

![image](https://user-images.githubusercontent.com/35444743/114492579-6d969f00-9c4b-11eb-81be-8f823ba59ef0.png)