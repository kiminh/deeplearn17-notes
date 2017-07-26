* With the diffusion of cheap sensors, sensor-equipped devices (e.g., drones),
  and sensor networks (such as Internet of Things), as well as the development
  of inexpensive human-machine interaction interfaces, the ability to quickly
  and effectively process sequential data is becoming more and more important.
* tasks 
  * monitoring and classification of human behavior to prediction of future
    events
* approaches 
  * linear models to early models of Recurrent Neural Networks, up to more
    recent Deep Learning solutions. 

#Syllabus

1. Introduction to sequential domains and related computational tasks
  * types of sequences
    * symbolic sequences, time series, multivariate sequences
  * tasks (e.g., classification, prediction, transduction)
2. Linear models for sequences
3. Linear auto-encoders for sequences: optimal and approximated solutions
4. Recurrent Neural Network models and related training algorithms
5. Computational problems of Recurrent Neural Networks and some 'solutions'
6. Novel linear-based pre-training approaches for Recurrent Neural Networks
7. Recent Deep Learning models
8. Relationship between Feed-forward and Recurrent Neural Networks
9. Beyond sequences: trees and graphs 

#Slides

1. Introduction to sequential domains p3
2. Linear models for sequences p20
3. Linear auto-encoders for sequences p33
4. Recurrent Neural Network models p52
5. Computational problems of RNN p78
  * Reservoir Computing: Echo State Nets 6 and Liquid State Machines p86
6. Linear-based pre-training approaches for RNN p101
  * HMM-based pre-training p103
7. An Empirical Comparison p105
  * Folk tunes stored in a special text format; Piano-midi.de
8. Recent Deep Learning models p122
  * Encoder-Decoder
  * Alignment/Attention
  * Adaptive Computation Time
  * “External” memory
    * Neural Turing Machines (Graves et al., arXiv:1410.5401v2)
    * Memory Networks (Weston et al., ICLR 2015)
    * End-to-End Memory Networks (Sukhbaatar et al., NIPS 2015)
    * Learning to Transduce with Unbounded Memory 
      (Grefenstette et al., NIPS 2015)
  * Pointers
  * image to text applications
9. Relationship between Feed-forward Nets and RNN p134
  * Given a Feed-forward network how to build an “equivalente” RNN
10. Beyond sequences: trees and graphs p137
