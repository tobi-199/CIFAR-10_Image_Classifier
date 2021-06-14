# CIFAR-10_Image_Classifier

Project Overview

In this project, you'll demonstrate the skills you’ve developed in this course by building an image classifier and object detection system using PyTorch. To do this project, you'll need to pull together the new deep learning skills you've just learned, such as data augmentation and building neural networks in order to solve the problem presented in the scenario below.

Scenario
You are a new machine learning engineer at a self-driving car startup. Management is trying to decide whether to build or buy an object detection algorithm for objects that may be on the side of the road. They are considering buying a computer vision algorithm from a company called Detectocorp. Detectocorp’s algorithm claims a 70% accuracy rate on the CIFAR-10 dataset, a benchmark used to evaluate the state of the art for computer vision systems.

But before making this purchase, management wants to explore whether you can build an in-house solution that performs well. They have asked you to try your hand at creating a neural network that can classify arbitrary objects and potentially be fine-tuned on a larger dataset using transfer learning.

Using the skills you’ve acquired building neural networks using PyTorch, your task is to build an image classifier using the CIFAR-10 dataset and evaluate its accuracy. Then you'll compare its performance to both Detectocorp’s algorithm (which achieved 70% accuracy) as well as the state of the art results detailed in the notebook—and make a recommendation to management about whether to build the solution in-house or buy the algorithm from Detectocorp.

CIFAR-10
Your image classifier will be trained and evaluated on one of the most classic and well-studied computer vision data sets, CIFAR-10. This dataset has spurred loads of innovation in neural network design and implementation. The current state of the art is a 99% accuracy rate, achieved by GPipe, which has 557 million parameters and was developed in late 2018. GPipe is an extremely large network with a lot of advanced techniques not introduced in this course, but feel free to use any architecture that suits your needs.
