# deep_learning_with_python
My notebooks on the book "Deep Learning with Python" by Francois Chollet (2018). This series of notebooks show how to build neural networks using Keras.   

## chap2-1_first_neural_network_for_recognizing_handwritten_digits  
MNIST handwritten digits are classified using a fully-connected neural network.

## chap3-1_binary_classification_IMDB  
Binary classification

## [chap3-2_multiclass_classification_reuters](https://github.com/ksonod/deep_learning_with_python/blob/master/chap3-2_multiclass_classification_reuters.ipynb)  
<strong>Abstract</strong>
In this notebook, neural networks will be build for classifying topics of Reuters' newswires. This is a multiclass classification example.  
<strong>Reference</strong>
See pages 78-84 of "Deep Learning with Python" by Francois Chollet (2018).  
<strong>Summary (page 84)</strong>
- For a multiclass classification problem, the final activation function should be softmax, which returns a value between 0 and 1.
- An appropreate loss function is categorical_crossentropy.
- If you want to classify data with N labels, try to avoid using layers whose nodes are less than N.
