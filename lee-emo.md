#Emotion, Top-Down Attention, and Brain Internal States for Next-Generation Chatbots

 Human emotion is an internal state of human brain which makes different
 decision and behavior from same sensory inputs. Therefore, for efficient
 interactions between human and machine, i.e. chatbot, it is important for the
 machine to estimate human emotions. Due to the internal nature, the
 classification accuracy of the emotion from a single modality is not high. For
 example, our result was ranked as Top-1 with only 61.6% accuracy for the
 emotion recognition task from facial images at EmotiW2015 challenge. In this
 tutorial we will first present a hierarchical Committee machine to win
 EmotiW2015 challenge, and further extend the ideas to multi-modal
 classification with top-down attention and identification of brain signals for
 the two other brain internal states.

* first talk (between 9:30 to 11:15 am)
* second talk (between 2:30 to 4:15 pm), to improve the accuracy, we will add
  speech and text modalities to recognize human emotions
  * there exist much more top-down synapses than bottom-up synapses in our
    brain.  
* third talk (between 11:45 am to 13:30 pm), we will introduce more general
  brain internal states, of which popular one is emotion. Especially, we made
  hypothesis on 2 axes of the internal state space, i.e.,
  agreement/disagreement and trust/distrust to conversational counterparts
  during conversation, and identified fMRI and/or EEG signal components related
  to those internal states. Then, we will propose a method to utilize these
  brain signals for generating near-ground-truth labels of brain internal
  states, which will be used to train classifiers from audio-visual signals.

##Syllabus

1. Hierarchical Committee Machine for the Emotion Recognition in the Wild 2015 
  * A brief history of emotion recognition
  * Deep learning for emotion recognition from facial images
  * Learning facial representations for emotion recognition
  * Deep CNN architectures for emotion recognition
  * Hierarchical Committee Machine with many CNN classifiers

2. Multi-modal Integration based on Top-Down Attention
  * Early Integration model with data concatenation
  * Late Integration model with committee machine
  * Top-Down Attention model with gated neural networks

3. Understanding Brain Internal States with Brain Signals
  * Agreement vs. Disagreement to others during conversation
  * Trust vs. Distrust to others during conversation
  * Known vs. Unknown for memory test
