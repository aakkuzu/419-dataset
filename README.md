# This is our 419-dataset, and the following gives a instruction of what we did for our dataset.


# The structure of your code/folders



# A self-evaluation of your project with respect to your proposal.
Initially, we planned to do semi-supervised learning with only 20 videos in order to get more data. Then train with a model that deals with sequence data. However, we did not understand the semi-supervised learning well. We spend a lot of time working on learning the TensorFlow which seems to provide a solution for the shortage of data. This link provides the history work we tried with Tensorflow: https://colab.research.google.com/drive/13H3Q38XdNJAncF0MxcCofa6RkWlb3w6S?usp=sharing. The method is called Neural Structured Learning provided in the link: https://www.tensorflow.org/neural_structured_learning. However, we seem to misunderstand the Tensorflow that we were told Tensorflow only works well with a large dataset. With limited time, we decided to annotate as much data as possible and train with a K-NN model with the independently multidimensional dynamic time warping. In the end, we had 104 clips in total, 55 for flirting action, 50 for non-flirting action. We then train our model with the final similarity matrix computed with the independently multidimensional DTW. Overall, I think our group is trying as hard as we can, and we gain a lot more new knowledge on the process of doing this project. Good Job Team!
