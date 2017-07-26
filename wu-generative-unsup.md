* We shall focus on two classes of models, namely the undirected energy based
  models and the directed latent variable models, including the deep undirected
  and directed graphical models parametrized by convolutional neural networks.

#Syllabus

1. Markov random field models, maximum entropy and maximum likelihood.
2. Latent factor models including factor analysis, independent component
   analysis, sparse coding, matrix factorization; auto-encoder and embedding.
3. Deep undirected and directed models, maximum likelihood, contrastive
   divergence, variational, adversarial, and cooperative learning methods.

The focus will be on 3., with 1. and 2. laying the groundwork.

#Material other than the three slides

[Deep FRAME model](http://www.stat.ucla.edu/~yang.lu/project/deepFrame/main.html)
[Deep convolutional energy-based model](http://www.stat.ucla.edu/~ywu/GenerativeConvNet/main.html)
[Deep spatial-temporal energy-based model](http://www.stat.ucla.edu/~jxie/STGConvNet/STGConvNet.html)
[Deep generator network](http://www.stat.ucla.edu/~ywu/ABP/main.html)
[Cooperative learning of deep energy-based model and deep generator model](http://www.stat.ucla.edu/~ywu/CoopNets/main.html)

The rest of this file contains notes based on the slides.

#Overview

## Modes of learning

* Supervised learning: classification and regression
* Reinforcement learning: policy and value networks
* Unsupervised learning:
  * Generative models and density estimation
    * Latent variable models, factor analysis
    * Energy-based models, exponential family models
  * Embedding and auto-encoding

## Deep learning

* Convolutional neural network (ConvNet or CNN)
* Recurrent neural network (RNN)
* Models with multi-layer latent variables

## Latent variable models

## Energy-based models

p(X, W)

## Dual networks

* Top-down net: generator net
* Bottom-up net:
  * Variational Bayes auto-encoder [Kingma and Welling, 2013; Rezende et al., 2014]: inference net
  * Generative adversarial training [Goodfellow et al., 2014; Radford et al., 2015] : discriminator net
  * Cooperative learning: descriptor net

## Plan

* Latent variable models (2nd pdf p14)
  * factor analysis, independent component analysis, sparse coding,
    non-negative matrix factorization, recommender
  * restricted Boltzmann machine, auto-encoder, embedding
  * sigmoid network, Helmholtz machine p3.44, wake-sleep p 2.41
  * generator network, alternating back-propagation
  * variational auto-encoder, generative adversarial networks
* Energy-based models
  * Dual networks
  * Markov random field, Gibbs distribution
  * FRAME (Filters, Random field, And Maximum Entropy)
  * field of experts, product of experts
  * FRAME model with ConvNet filters, descriptor net
  * Cooperative learning
* Latent energy-based models, auto-regressive models

#Latent Variable Models

* Supervised learning
  * p8
    * Kernel machine: h i = h(X i ) implicit, kernel trick hh(X), h(X 0 )i =
    * Boosting machine: h ik weak classifiers, e.g., trees
    * CART: h ik = h k (X i ) simple base functions, piecewise constant,...
    * MARS: h ik simple base functions, product of hinge max(0, x j − b).
    * Neural net: h ik = h k (X i ) learned, not designed
* Unsupervised learning
* Linear latent variable models
* Sparse coding [Olshausen, Field 1996]
* Generator network
* Learning and inference

#Dual Nets

* Two Nets of Opposite Directions
  Bottom-up ConvNet   energy <= signal            (a) Descriptor Net
  Top-down ConvNet    latent variables => signal  (b) Generator Net
  [Kim, Bengio 2016; Xie et al. 2017]
* Energy-based model
* Latent variable model
* Deep Generative Models and Unsupervised
* Learning: Dual Nets
* Cooperative learning
  * MCMC: Markov chain Monte Carlo
* Related mode

#Conclusion

* Linear + minimal non-linearity
* Learn representation and computation (inferencer, sampler)
* Blackbox: CNN, quantum mechanics, ...
* Interpretable And-Or graphs (Zhu, Mumford 2007)
