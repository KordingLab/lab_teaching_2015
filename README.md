Kording lab teaching 2015
=========================

Repository for lab teaching at Kording's Lab.

## Session 1

Presentation covers how to get up running [Spark](http://spark.apache.org/) on Quest (Northwestern Computing Clusters). Notebook goes through Map Reduce algorithm where we provide an example on a simple text file. We then implement stochatic gradient descent to train Logistic Regression in order to classify MNIST dataset. Here is a [link](http://klab.smpp.northwestern.edu/wiki/images/9/9b/Big_data_klab.pdf) to a presentation file.


## Session 2

This tutorial is one of the Deep learning tutorial by Kording lab.
In this presentation, we will go through simple neural network architecture and math behind it including forward propagation and back propagation (ref. Andrew Ng lecture).
We will then code the forward propagation and back propagation algorithm and test it on MNIST examples. If we have time, we will go through existing
python packages that implement Neural Network (e.g. [`Lasagne`](https://github.com/Lasagne/Lasagne), [`scikit-neuralnetwork`](https://github.com/aigamedev/scikit-neuralnetwork), [`pybrain`](http://pybrain.org/), [`nolearn`](https://github.com/dnouri/nolearn).


## Session 3

In this session, we will go over Recurrent Neural Network (RNN) and its application in Natural Language Processing (NLP).
We'll go through architecture of the RNN also a bit of Convolutional Neural Network (CNN) presented by Pavan.
We use blog posts and [CS224d: Deep Learning for Natural Language Processing](http://cs224d.stanford.edu/syllabus.html) as main materials. After the lecture, We will go over implementing RNN for application in NLP.


## Session 4 (Luca Lonini and Daniel Acuna)

In this tutorial we show how to use TensorFlow to build and train 2 models: a Softmax Regression Model and a CNN.
The example shows how to train the networks and how save the variables and the computation graph for display in the TensorFlow board.
Further info can be found here: [TensorFlow.org](https://www.tensorflow.org/versions/0.6.0/tutorials/mnist/pros/index.html)


## Session 5 (Pavan Ramkumar and Luca Lonini)

In this session, we go through various kind of ConvNet visualization techniques. We focus on techniques to visualize the entire neural code, layerwise neural codes, individual units, as well as individual layers and units conditioned on specific images.

Here is a list of papers we discuss.

- [`t-SNE: van der Maaten & Hinton (2008)`](http://siplab.tudelft.nl/sites/default/files/vandermaaten08a.pdf)
- [`t-SNE of convnet codebook: Karpathy's blog`](http://cs.stanford.edu/people/karpathy/cnnembed/)
- [`Occlusion technique: Zeiler & Fergus (2014)`](http://arxiv.org/pdf/1311.2901.pdf)
- [`Deconvolutional net: Zeiler & Fergus (2014)`](http://arxiv.org/pdf/1311.2901.pdf)
- [`Backpropagation technique: Simonyan et al. (2014)`](http://arxiv.org/pdf/1312.6034.pdf)
- [`Guided deconvolution: Springenberg, Dosovitskiy et al. (2015)`](http://arxiv.org/pdf/1412.6806.pdf)
- [`Visualizing preferred images: Girshick et al. (2013)`](http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.pdf)
- [`Gradient ascent on input image with L2-prior: Simonyan et al. (2014)`](http://arxiv.org/pdf/1312.6034.pdf)
- [`Gradient ascent on input image with natural image priors: Yosinski et al. (2015)`](http://yosinski.com/media/papers/Yosinski__2015__ICML_DL__Understanding_Neural_Networks_Through_Deep_Visualization__.pdf)
- [`Visualizing unique representation of layers: Mahendran & Vedaldi (2014)`](http://arxiv.org/pdf/1412.0035.pdf)
- [`Inceptionism: Google blog`](http://googleresearch.blogspot.com/2015/06/inceptionism-going-deeper-into-neural.html)
- [`Deepart: Gatys et al. 2015`](http://www.deepart.io)
- [`Fooling convnets: Nguyen et al. 2015`](http://arxiv.org/pdf/1412.1897.pdf)

We also provide an iTorch demo of how to specify and train a conventional CNN (LeNet) using Torch.
