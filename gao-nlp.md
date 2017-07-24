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

#Notes taken during the course

##1: Background

- DL in 50s: _cybernetics_
- Wave 3: layer-wise training?, 
  - not used any more, but significant for bringing the 3dr wave
  - deep residual network to save the vanishing gradient (help it get through)
- p44 DNN forms for different language structures 

##2: Deep semantic similarity models for text processing

- broad sense of similarity: MT, web search ranking

###DSSM for web search ranking

p56 dim(u) = 4, intuitively, topics
generative: generating the query given (the title of) the hit

###DSSM for recommendation

_don't know how many of you still using MS Office system_
fang+ cvpr 15: more last authors than programmers

###DSSM for automatic image captioning and other tasks

##3: Recurrent neural networks for text generation

- chat-bot: if you don't have a friend
- from p152: NMT by Facebook [Gehring+ 17] and [Vaswani+ 17 arXiv:1706.03762], no consense yet

##4: Neural machine reading models for question answering

##5: Deep reinforcement learning for task-completion dialogue
