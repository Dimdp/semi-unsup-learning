# Semi unsupervised learning on MNIST using Categorical GANs with Tensorflow in google colab

This notebook implements a Categorical Gan for MNIST data which trains a Discriminative Classifier using small labaled data and big unlabaled data. <br />

Using 100 labeled data and 59900 unlabaled data we could get 95% of accuracy on the test set. <br />

The algorithm is described in this paper:

@inproceedings{
Author = {Jost Tobias Springenberg},
Title = {Unsupervised and Semi-supervised Learning with Categorical Generative Adversarial Networks
},
Year = {2016}
}
