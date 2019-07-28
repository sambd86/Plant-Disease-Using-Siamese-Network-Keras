# Plant-Disease-Using-Siamese-Network-Keras

Last Version: https://www.kaggle.com/bulentsiyah/plant-disease-using-siamese-network-keras

We will understand the siamese network by building the plant disease model. The objective of our network is to understand whether two plants are similar or dissimilar.

Once we have our data as pairs along with their labels, we train our siamese network. From the image pair, we feed one image to the network A and another image to the network B. The role of these two networks is only to extract the feature vectors. So, we use two convolution layers with relu activations for extracting the features. Once we have learned the feature, we feed the resultant feature vector from both of the networks to the energy function which measures the similarity, we use Euclidean distance as our energy function. So, we train our network by feeding the image pair to learn the semantic similarity between them.

References :

https://github.com/sudharsan13296/Hands-On-Meta-Learning-With-Python/blob/master/02.%20Face%20and%20Audio%20Recognition%20using%20Siamese%20Networks/2.4%20Face%20Recognition%20Using%20Siamese%20Network.ipynb
https://keras.io/examples/mnist_siamese/
https://msiam.github.io/Few-Shot-Learning/
https://towardsdatascience.com/one-shot-learning-with-siamese-networks-using-keras-17f34e75bb3d
https://medium.com/@subham.tiwari186/siamese-neural-network-for-one-shot-image-recognition-paper-analysis-44cf7f0c66cb
https://www.katnoria.com/siamese-one-shot/
https://sorenbouma.github.io/blog/oneshot/
