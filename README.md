# A Derivation of the Backpropagation Algorithm

Andrew Ng's Coursera courses on Machine Learning and Deep Learning provide only the equations for backpropagation, without their derivations. To accompany my studies, I have written up full derivations of the backpropagation algorithm (for differentiating a neural network's cost function) as they apply to both the Stanford Machine Learning course and the deeplearning.ai Deep Learning specialization.

My first derivation [here][1], which is just an excerpt from my lecture notes, was motivated mostly by the need to make sense of the strange notation and network structure (e.g. using bias _nodes_ rather than bias _vectors_) used throughout the Machine Learning Coursera course offered by Stanford.

My second derivation [here][2] formalizes, streamlines, and updates my derivation so that it is more consistent with the modern network structure and notation used in the Coursera Deep Learning specialization offered by [deeplearning.ai](https://www.deeplearning.ai), as well as more logically motivated from step to step. In other words, it better shows how the backpropagation algorithm might be obtained from first principles if we had never heard of the algorithm before.

![equations]

[1]:https://github.com/chrismbryant/backpropagation/blob/master/2017_06_21%20Backpropagation%20Derivation%20(for%20Coursera%20ML).pdf
[2]:https://github.com/chrismbryant/backpropagation/blob/master/2017_09_27%20Backpropagation%20Derivation%20(for%20Coursera%20Deep%20Learning).pdf

[equations]: https://raw.githubusercontent.com/chrismbryant/backpropagation/master/The%20Equations%20of%20Backpropagation.png
