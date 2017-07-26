* via its representations, architecture, loss function, and data
  transformations. Domain-appropriate biases constrain the learning problem and
  thereby compensate for data limitations. 
* A classic form of bias for vision tasks--used even before the invention of
  back propagation--is the convolutional architecture, exploiting the
  homogeneity of image statistics and the relevance of local spatial structure.
  Many generic tricks of the trade in deep learning can be cast in this
  manner--as suitable forms of domain bias. Beyond these generic tricks, I will
  work through illustrations of domains in which prior knowledge can be
  leveraged to creatively construct models. My own particular research interest
  involves 
* cognitively-informed machine learning, where an understanding of the
  mechanisms of human perception, cognition, and reasoning can serve as a
  powerful constraint on models that are intended to predict human preferences
  and behavior.

#Syllabus

* The scaling problem
* Bias-variance dilemma
* Imposing domain-appropriate bias
  - via loss functions
  - via representations and representational constraints
  - via data augmentation
  - via architecture design
* Case studies of model crafting: memory in humans and recurrent networks 

#1 Overview 

* My background
* Inductive bias
* Means of imposing domain-appropriate bias
* Case studies involving deep learning and memory

#Ppt 2 

* Means Of Imposing Domain-Appropriate Bias
* Data augmentation p3
* Loss function p8
  * Perceptually Grounded Losses
* Representation p27
  * Psychologically Grounded Representations
    * Music composition network (Mozer, 1994)
  * Relational Constraints For Representation Learning
* Architectural constraints p56
  * brain: What versus where cortical processing p60
  * Fine-grain classification of birds p66

#3 Deep Learning Architectures Through Understanding Human Minds/Brains?

* Forgetting Is Influenced By The Temporal Distribution Of Study p5
* modeling and predicting many human activities p15
* Recent Research Involving Temporally Situated Events p16

##Hawkes  Process p18

* Neural Hawkes Process Memory p28
  * exper
    * Reddit p33
  * Word Learning Study (Kang et al., 2014) p37

##Continuous Time Gated Recurrent Networks p44
