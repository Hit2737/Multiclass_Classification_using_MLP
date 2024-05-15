<span style="font-family: Times_new_roman; font-size: 20px;">

<h1>Multiclass-Classification of MNIST & Fashion MNIST Datasets Using MLP</h1>
We require two datasets, one is MNIST dataset which consists of 28x28 images of handwritten of 28x28 images of fashion items.
You can download the dataset from the following link:

- <a href="https://www.kaggle.com/datasets/hojjatk/mnist-dataset?resource=download">MNIST</a>
- <a href="https://www.kaggle.com/zalando-research/fashionmnist">Fashion MNIST</a>

This repository contains the solution to the given problem statement.

<h3>Problem Statement</h3>

<p>
Train on MNIST dataset using an MLP. The original training dataset contains 60,000
images and test contains 10,000 images. If you are short on compute, use a stratified
subset of a smaller number of images. But, the test set remains the same 10,000
images. Compare against RF and Logistic Regression models. The metrics can be:
F1-score, confusion matrix. What do you observe? What all digits are commonly
confused?
Let us assume your MLP has 30 neurons in first layer, 20 in second layer and then 10
finally for the output layer (corresponding to 10 classes). On the trained MLP, plot the t-SNE for
the output from the layer containing 20 neurons for the 10 digits. Contrast this with the t-SNE for
the same layer but for an untrained model. What do you conclude?
Now, use the trained MLP to predict on the Fashion-MNIST dataset. What do you
observe? How do the embeddings (t-SNE viz for the second layer compare for MNIST
and Fashion-MNIST images)
</p>

<p>
You can go through the file to understand the code and the approach used to solve the given problem statement.
</p>
</span>
