Marc’Aurelio Ranzato, FB AI Research Lab

* convolutional neural networks, and embeddings. The former is employed in
* audio and visual processing applications, while the latter is used for
* representing text, graphs and other discrete or symbolic data
* deal with sequential data, like videos. 
* Lectures will provide intuitions, the underlying mathematics, typical
* applications, code snippets and references
* attendees are expected to gain enough familiarity to be able to apply these
  basic tools to standard datasets on their own.

#Syllabus

##Session 1 - Deep Learning for Vision and Audio Processing Applications

* The basics: from logistic regression to fully connected neural networks, and
  from fully connected neural networks to convolutional neural networks (CNNs).
* Special layers used in vision applications.
* Example of CNNs using the pyTorch open source library.  

##Session 2: - Deep Learning for Text Processing Applications.

* How neural networks can be adapted to work with discrete symbolic data like
  text: the concept of embedding.
* Methods using embeddings for a variety of text application tasks.
* Example of learning from text using pyTorch.

##Session 3: Deep Learning for Sequential Data.

* Learning from sequences: Recurrent Neural Networks (RNNs).
* How to train and generate from RNNs, variants of RNNs.
* Examples of applications of RNNs using pyTorch.

#Notes taken during the lessons and reading the slides

##Vision

- p95 pooling represents that an eye can appear anywhere
- p98 pooling and the parameter space
* p117 Latest & Greatest CNNs: BatchNormalization
* vision + text: We will discuss more recent works during the 3rd lecture!
* Tips of the trade p132

##NLP

* factorized bigram p16
* Representing Phrases p37
  * recovery from Bag-of-embeddings
* RNN p45
  * history Elman “Finding structure in time” Cognitive Science 1990
  * gating: LSTM and GRU p72
* Skip-Thought Vectors p76

##Seq

* seq 2 single label
  * fastText; Bag of tricks for efficient text classification, Joulin et al. 2016
* LM
  - RNNs Exploring the limits of language modeling, Jozefowicz et al. 2016
  - CNNs (more recently) 
    * Language modeling with gated convolutional networks, Dauphin et al. 2016
* visual QA p29
* image captioning with RNN p40
* seq2seq p44
  * machine translation p45
    * scoring
      * bi-LSTM 
      Neural machine translation by jointly learning to align and translate,
      Bahdanau et al. ICLR 2015
      * CNN CNNs. A convolutional encoder model for NMT, Gehring et al. 2016
  * OCR p54
