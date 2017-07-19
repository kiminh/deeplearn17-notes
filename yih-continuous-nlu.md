The rest of lecture focuses on two key natural language understanding tasks:
* information extraction
  * Transforming unstructured text to structured databases
  * aims to find the entities and their relationships in text, as well as to
    make the extracted facts easily accessible programmatically
  * basic problem setting, such as binary relation extraction as sequence
    labeling problems. After that, we will emphasize more on the
  * latest distant supervision methods, which model the multi-sentence, n-ary
    relation settings using structured LSTM models. New approaches for
  * embedding entities and relations in a knowledge base for reasoning for
    previously unknown facts will also be covered.
* Question answering, while often used as the means to demonstrate machine
  intelligence, is an important application for fulfilling user's information
  need. In this part, we'll start by introducing the general framework of
  answering question using unstructured text, such as Wikipedia or the Web, and
  describe the current state-of-the-art deep learning approaches. We will also
  discuss how to leverage structured data such as databases or tables to answer
  questions, with the focus on semantic parsing methods.

#Syllabus

#Part 1. Background of Natural Language Processing and Machine Learning

* What is natural language understanding and why is it difficult?
* Representative NLP tasks
* Machine learning models & paradigms

#Part 2. Knowledge Base Completion and Information Extraction

* Information extraction tasks:
  * bridging unstructured text and structured databases
* Simple and complex problem settings
  * Binary to n-ary relations
  * Distant supervision for combating annotation bottleneck
  * Going beyond sentence boundaries
* Sequence labeling to structured LSTM models
* Deep-learning approaches for embedding structured knowledge and text

#Part 3. Semantic Parsing and Question Answering

* Current research trend of question answering
* Question answering with unstructured text and the Web
* Question answering with knowledge bases
  * Semantic parsing (of questions)
  * Matching questions and answers in embedding space
  * Information extraction and text matching

#Notes taken during the courses

- tutorials linked in the course description and related
  - Yih, He & Gao. Deep learning and continuous representations for natural
    language processing. Tutorial presented in HLT-NAACL-2015, IJCAI-2016.  
  - Yih & Ma. [Question answering with knowledge bases, Web and beyond](https://github.com/scottyih/Slides/blob/master/QA%20Tutorial.pdf)
    Tutorial presented in HLT-NAACL-2016, SIGIR-2016.  
  - Tutorial to be presented in ACL-2017
    - linked Poon, Quirk, Toutanova & Yih. Natural Language Processing for Precision Medicine. 
    - also there: Deep Learning for Semantic Composition, Xiaodan Zhu and Edward Grefenstette

Part 1 QA, deep learning
part 2 konwl base embed & info extract
part 3 sem pars & QA

## Intro

- the test of intelligence: QA
- categs of **early** QA syss (not just text-based)

##KB-embed 

- tensor decomp
loss func is least sqs of $ v(Obama) \times R_bornIn \times v(hawai)^T $
- typed tensor decomp (Chang+ emnlp 14)
- Exper: KB completion

## KB augmented with textual relations

- Combine information from text and existing KB
- convolution 
- Toutanova+ emnlp 2015, acl 2016; Verga+ naacl 16

##Embed relation paths

Take multi-hop paths as input (e.g., [Guu+ 2015])
also RNN (Neelakantan+ 15) sum (Lin+ 15)
- problems
  - number of pathes grow exp in max length
    - prune or sample (Lao+ 11, Lin+ 15, Guu+ 15)
  - take nodes into account
- more compositions (Toutanova+ acl 16)
