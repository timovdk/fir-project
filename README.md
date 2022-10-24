## Assignment
Use the data set of London images available in the Assignment 02 of the course. You can choose to use the same 
reduced data set, or the extended version mentioned in the notebook and also provided with Assignment 02.
Starting from the Bag of Words approach, of which you have developed the main structure in the Assignment 02, 
make hypotheses, implement and evaluate approaches to improve its retrieval performance. The formulation of 
the hypotheses (or problem statement) is up to you: you decide on and motivate interesting aspects to investigate.

Example aspects that you may want to take into account are:
- use of different keypoint descriptors (e.g. SIFT, SURF, and so on) to extract basic visual words from the 
images
- study the impact of different clustering techniques to learn the visual dictionary (e.g. fuzzy k-means, soft 
k-means, hierarchical clustering) of different sizes of the vocabulary (values of k)
- use of different distance metrics to compare the final descriptors 
- the implementation of an inverted index using the learned visual vocabulary
- use of Machine Learning for learning to rank
Comparison with other methods (e.g. Convolutional Networks for holistic descriptor extraction) is also possible, 
but it will be considered as a plus.

## Report
Make a clear problem statement (research questions) and design your experiments and evaluations accordingly. 
Report your finding and observations in an essay paper, following the instructions given on Canvas