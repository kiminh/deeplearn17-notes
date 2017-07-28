* brief introduction to the history of deep learning and its application to
  natural language processing (NLP) tasks
* deep learning technologies that are recently developed for three areas of NLP
  tasks.  
  1. semantic similarities between texts and images, the task that is
     fundamental to a wide range of applications, such as Web search ranking,
     recommendation, image captioning and machine translation. 
  2. a set of neural models developed for machine reading comprehension and
     question answering
  3. dialogue agents, including task-completion bots and social chat bots.

#Syllabus


##1. Introduction to deep learning and natural language processing (NLP)

- A brief history of deep learning
- An example of neural models for query classification
- Overview of deep learning models for NLP tasks

##2. Deep Semantic Similarity Models (DSSM) for text processing

- Challenges of modeling semantic similarity
- What is DSSM
- DSSM for Web search ranking
- DSSM for recommendation
- DSSM for automatic image captioning and other tasks

##3. Deep learning for Machine Reading Comprehension (MRC) and Question Answering (QA) 

- Challenges of MRC and QA
- A brief review of symbolic approaches
- From symbolic to neural approaches
- State of the art MRC models
- Toward an open-domain QA system

##4. Deep learning for dialogue

- Challenges of developing open-domain dialogue agents
- The development of task-oriented dialogue agents using deep reinforcement
  learning
- The development of neural conversation engines for social chat bots

#Following the slides

##1: Background

* Historical trends, Three waves
  * DL in 50s: _cybernetics_
  * Wave 3 (current wave), deep learning
    * Started at 2006 
    * bib
      * Hinton+ 06
      * Bengio+ 07
      * Ranzato+ 07
        Automatic recognition of biological particles in microscopic images
        M Ranzato, PE Taylor, JM House, RC Flagan, Y LeCun, P Perona
        Pattern recognition letters 28 (1), 31-39
    * layer-wise training?, 
      * not used any more, but significant for bringing the 3dr wave
      * deep residual network to save the vanishing gradient (help it get through)
* the state of the art p22
  * on NLP component tasks
    * Inference (NLI) Stanford NLI corpus Accuracy 78.2 88.3 Chen+ 16
    * Also see a summary by [Goldberg 15]
* p44 DNN forms for different language structures 

##2: Deep semantic similarity models for text processing p46

- broad sense of similarity: MT, web search ranking
* What is DSSM p48

###DSSM for web search ranking

* Task
* Model architecture
* Model training
* Analysis 
* p56 dim(u) = 4, intuitively, topics
* discriminative noise-contrastive vagy hogy hívják p62
* Evaluation p71
* generative: generating the query given (the title of) the hit p73

###DSSM for recommendation p77

* organization
  * Two interestingness tasks for recommendation: Automatic highlighting; Entity linking
  * Modeling interestingness via DSSM
  * Training data acquisition
  * Evaluation
  * Summary 
* wisecracks
  * _don't know how many of you still using MS Office system_
  * fang+ cvpr 15: more last authors than programmers

###DSSM for automatic image captioning and other tasks p99

##3: Recurrent neural networks for text generation p121

* Neural language models and word embedding 
  * RNN p126
  * embedding p130
* Neural machine translation
  * SMT p140
  * neural in phrase-based p143
  * e2e p144
    * Convolutional S2S model beat Recurrent models [Gehring+ 17] p152
    - NMT by Facebook [Gehring+ 17] and [Vaswani+ 17 arXiv:1706.03762], no consense yet
* Neural social bots p154
  - if you don't have a friend
  * bland szelíd kedves nyájas udvarias jóságos lágy édeskés mézesmázos enyhe
    nyugtató csillapító enyhítő kellemes üdítő fűszerezetlen semmitmondó
  * anti-LM p163
  * RL Li 16c p168
  * A data driven engine trained on social chitchat data [Sordoni+ 15; Li+ 16a]
  * Persona based models and speaker-role based models [Li+ 16b; Luan+ 17] p171
  * Image-grounded models [Mostafazadeh+ 17] p176
  * Knowledge-grounded models [Ghazvininejad+ 17] p177 

##4: Neural machine reading models for question answering p181

* product rule~production/rewrite rule
* symbolic: 
  * MSR MindNet [Dolan+ 93; Richardson+ 98], duck Purpose egg
  * QA as graph matching
  * Worked beautifully, just not very often, because of paraphrase alternations
* neural: 
  * ReasoNet with Shared Memory [Shen+ 16a] p195
  * other models (with inference steps) p204
    * Maluuba: EpiReader [Trischler+ 16] Attention sum reader Single-step
    * Maluuba: Iterative AR [Sordoni+ 16] Attention sum reader
    * Multi-step, step size is predefined
    * BiDAF [Seo+ 16] Co-attention Single-step
    * MSR: ReasoNet [Shen+ 16b] Co-attention Dynamic multi-step 
    * MSRA: R-net [Wang+ 17]
  * RL p215

##5: Deep reinforcement learning for task-completion dialogue p219

* Reinforcement learning (RL) vs. supervised learning (SL) p227
* [Sutton & Barto 98]
* Three types of dialogue systems p240
* Deep RL for dialogues p244
* Three case studies p250
  * Info bot: end-to-end training with non-differentiable knowledge base 
  [Dhuwan+ 17]
  * Task-completion bot: efficient exploration for domain extension p258
  [Zachary+ 17]
    * [DeepMind 15]
  * Composite task completion bot with Hierarchical RL [Peng+ 17] p266
    * travel assistant
