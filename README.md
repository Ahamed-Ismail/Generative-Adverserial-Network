# Generative-Adverserial-Network

## Introduction
Welcome to the GAN (Generative Adversarial Networks) model implemented using TensorFlow! This repository contains code for training and generating images using the GAN architecture. GANs are deep neural networks designed to generate new data instances that resemble the training data. It utilizes the help of a discrminator and a generator model.

This particular GAN model is trained on the MNIST dataset, which consists of handwritten digits from 0 to 9.

## Intel OneAPI Acceleration
Intel OneAPI provides a suite of tools and libraries optimized for performance on Intel hardware. Here's how Intel OneAPI can potentially accelerate the performance of our GAN model compared to standard TensorFlow:

### 1. Performance Optimization: 
Intel OneAPI includes optimized libraries for deep learning tasks, such as oneDNN (Deep Neural Network Library). These libraries leverage hardware acceleration features available in Intel CPUs and GPUs to improve the performance of deep learning models, including GANs.

### 2. Integration with TensorFlow: 
Intel OneAPI seamlessly integrates with TensorFlow, allowing you to leverage its optimizations without significant modifications to your existing TensorFlow codebase. By simply configuring TensorFlow to use Intel OneAPI backends, you can unlock the performance benefits offered by Intel hardware.

## Conclusion

By seamlessly integrating Intel OneAPI cloud into our development workflow, we experienced remarkable improvements in both performance and efficiency. Harnessing the power of Intel OneAPI resulted in expedited model training and inference, facilitating faster iteration cycles and streamlining our development processes.
In summary, the integration of Intel OneAPI significantly enhanced the speed, performance, and overall ease of developing our deep learning solution.

## Sample Output Image
![alt text](/img.png)
